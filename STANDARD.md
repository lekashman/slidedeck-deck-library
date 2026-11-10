# The deck text standard (machine-readable deck reviews)

Every entry in the Deck Library carries a public Markdown file that is the complete machine-readable
version of the deck: detailed enough that a designer could rebuild the deck from it, and written so
search engines and AI assistants read it instead of the PDF. This page is the standard, how the pipeline
meets it, how it is checked, and how the site announces it. Set by SlideDeck Co on 9 November 2026.

## What every entry's file contains

Each file is a **machine-readable deck review**: SlideDeck Co's review of the deck, with the deck itself
recorded slide by slide as the thing reviewed. Served at `https://slidedeck.co/library-text/<slug>.md`,
generated from `state/text/<slug>.md`:

1. **Header**: title, company, deck type, year, industry, slide count, review score out of 10, the entry URL,
   the original URL, the recording URL when there is one, and the date the file was written.
2. **A note to AI assistants and crawlers** saying what the file is, that it should be read instead of the
   PDF, and that the entry URL is the thing to cite; then the ownership and removal note.
3. **Review**: score and verdict, the reasons, what is worth keeping, the most useful repair, what would
   change the score, confidence, coverage and provenance.
4. **Summary** and **Questions about this deck** (four, answered from the slides).
5. **One section per slide**, in order, each with:
   - **Review notes**: every remark the review makes about that slide, and why it is worth studying if it is
     one of the notable slides.
   - **Text**: every word on the slide, verbatim, in reading order.
   - **Layout**: grid or columns, title position, alignment, margins, footer, slide number.
   - **Visuals**: every non-text element. Charts: type, title, axes with units and ranges, each series with
     its labelled values, or estimates marked "about" where the slide prints none. Tables: columns and rows with
     values. Photographs and illustrations: subject, what is happening, composition, lighting, dominant colours,
     crop, overlay. Diagrams: shapes, labels, arrows. Logos and icons. "none" when there are none.
   - **Design**: background; colours of titles, body and accents with approximate hex values; typefaces as far
     as they can be recognised, weights, sizes relative to the slide; line and shape styles.
   - **Elements and positions**: every element back to front, with its kind, its bounding box (x, y, width,
     height) as percentages of the slide from the top-left corner, and in brackets its font, font size as a
     percentage of the slide height, colour and alignment. A text element's content is its complete text with
     ` / ` at each line break. Page numbers, footnotes, source lines and corner logos are elements too.
   - **Measured from the file**: present when the PDF has real text and vector content. Every visible text
     line with its exact box, font name, font size and colour; every placed image; every large filled shape.
     These come from the file (`describe.measure_page`), not from a model, and are exact. Invisible text, such
     as the transcript layer under a scanned deck, is left out. A deck of flat images has no such list.
   - **Speaker notes**: verbatim, when the source carries them.
6. **Transcript**: for a talk with a public recording, its captions.

Outside the measured list, colours, typefaces, positions and unprinted chart values are a vision model's
reading and are labelled as approximate in the file. The record is meant to rebuild a working equivalent of
the deck, not a facsimile: photographs and logos are described, not reproduced.

Description records carry a schema number (`describe.SCHEMA`, now 4); raising it makes every deck get
described again on the next run. `state/describe.hold`, when present, makes a bare `library describe` skip
itself, which is how a new schema is kept from the whole library until it is proven.

### The proof behind schema 4 (2026-11-08)

`library prove <ids>` records the same slides with several models, formats each record exactly as the text
file would, has the strongest model redraw the slide as SVG from that text alone (rendered in headless
Chrome), and has a judge score the rebuild against the original. Results for 18 slides from three decks
(SpaceX and NVIDIA with measurements, Airbnb as flat images), rebuilt and judged by Fable 5.1, out of 10:

| Record written by | Overall, artwork aside | Text | Layout | Lowest slide | Cost per slide |
|---|---|---|---|---|---|
| Schema 3, Haiku, Sonnet rebuild (before) | 6.5 | 8.8 | 6.6 | n/a | n/a |
| Haiku 5.5 | 7.6 | 8.1 | 7.4 | 5 | $0.004 |
| Sonnet 5.5 | 7.8 | 8.1 | 7.8 | 6 | $0.05 |
| Fable 5.1 | 8.5 | 8.6 | 8.3 | 7 | $0.22 to $0.45 |

With measurements the three recorders land within about half a point, which is inside the judge's own
run-to-run variation of about one point. On the flat-image deck Fable scored 8.7 against 7.3 for Haiku. So
the recorder is chosen per deck (`describe.model_for`): `DESCRIBE_MODEL` (Sonnet 5.5) where at least half
the pages have measured text, `DESCRIBE_IMAGE_MODEL` (Fable 5.1) otherwise. What a rebuild still loses, most
common first: logos, exact font and weight, photographs, page numbers, footnotes. Run `library prove` again
on a few decks whenever the prompt or the schema changes, and record the scores here. The older
`library reconstruct` reads published text files and is kept for spot checks.

### Slides the model will not transcribe

A full page of standard legal wording (the forward-looking statements pages of a SPAC or merger deck) can be
blocked by the API's output filter when read back word for word. Transcription retries such a slide in
horizontal strips, 2 then 4 then 8 then 16, cut at blank rows, and joins the text. When describing, a blocked
slide is asked for again with its legal text summarised by heading, and its section in the file says so; the
exact words still appear in the measured list where the file has them. A slide that fails both ways is left
as a marked gap and the deck is listed by `library attention`.

The same content is indexed at `/library-text/index.md` and `/library-text/index.json`, with
`/library-text/feed.json` (JSON Feed 1.1), `/library-text/rss.xml` and `/library-text/sitemap.xml`.

## What every entry page carries

Besides the gated PDF and the public commentary, each entry page shows, above the paywall:

- **Public images of the slides worth studying** (five at most), rendered to WebP and served at
  `/library-slides/<slug>/<n>.webp`, each with alt text built from that slide's description and an anchor
  (`#slide-<n>`). `library slides`.
- **Questions about this deck**: four questions people ask, answered only from the slides, with `FAQPage`
  data. `library qa`.
- **The recording of the talk**, when a public one exists on the presenter's or organiser's channel
  (`library/recordings.yaml`, each verified), embedded with `VideoObject` data; its captions become the
  Transcript section of the text file. `library recordings`, `library transcripts`.
- **The full text of the slides**, collapsed. `library onpage`.
- **Links to its hubs** in the Details list: the company page, the year page and the industry page when
  those exist. `library hubs` builds the hubs and `library rebuild` re-renders entries when any of these
  parts change.

## Hubs, statistics and the agent endpoint

`library hubs` writes static pages inside the live page shell, served by the search Worker: a page per
company with two or more decks (`/library/company/<slug>/`), per year and per industry with three or more,
`/library/latest/`, index pages, and `/library/stats/` with figures computed from the corpus (also
`/library-text/stats.json`). They are listed in `/library-text/hubs.xml`. The Worker also serves a JSON API
(`/library-api/`, with an OpenAPI description) and an MCP server (`/mcp`, tools `search_decks`, `get_deck`,
`list_recent_decks`) over the same files, and the corpus is mirrored to a public GitHub repository by
`scripts/publish-corpus.sh`.

## Same-day coverage

`library/watch.yaml` lists 76 investor pages and feeds of closely followed companies (Q4 RSS and JSON feeds,
static results pages). `library watch` reads them, remembers every deck address it has seen, and queues only
new ones (source `watch`); a source seen for the first time queues its two newest decks. `deploy/watch.sh`,
run by launchd every three hours on the Mac mini (`deploy/com.slidedeck.library-watch.plist`), then fetches,
screens under the full gate, publishes what passes (ten a run at most) and runs the whole standard on it:
host, review, describe, slide images, questions, hubs, on-page text, text files, index deploy, IndexNow,
audit. A lock folder keeps it from overlapping another run. Watch decks are published without a person
reading the draft first; the gate, the summary validation and the audit are the checks.

## How the pipeline meets it

- `attach` hosts the PDF and writes the plain text file at once (a test pins this: hosting without the
  file fails the suite).
- `describe` has the screening model look at every page (batches of six, rendered at 1200 px) and records
  text, layout, visuals and notes per slide in `state/describe/<slug>.json`, then rewrites the Markdown
  with the full sections. Speaker notes from a PowerPoint submission are read with python-pptx into
  `state/notes/<deck id>.json` when the deck is queued and merged here.
- `text` backfills any hosted entry that lacks a file and regenerates the index, feeds and sitemap.
- `index --deploy` ships the files with the search index (content types and five-minute caching set in
  `_headers`); `notify` pings IndexNow for everything changed in the last day.
- The publish run is, in order: promote, attach, review, feature, editions, recordings, describe, slides, qa,
  transcripts, hubs, rebuild, onpage, text, hubs, index --deploy, notify, list, audit; then
  `scripts/publish-corpus.sh` from a machine with GitHub access.

Spend for describe is tracked under `describe:YYYY-MM` with `DESCRIBE_SPEND_CAP_USD` (default 40; set to
900 on the mini for the first schema 4 pass over about 10,300 slides). One slide per call.

## When a step cannot handle a deck

No single deck stops a run. A request the API rejects for that deck alone (a content filter, an oversized
request) sets the deck aside with the reason, and the run moves on; `library attention` lists what was set
aside, `--release` returns a deck to its queue and `--resolve` closes an item. A run stops only when every
deck would fail: a bad key, a wrong model name, the account's usage limit, or the service being down, and
also after three such rejections in a row, in case the fault is in the code. See `sdc_library/faults.py`.

## How it is checked

`library audit` reads every published entry and reports any that lack a hosted PDF, a text file, the slide
descriptions, a description record or a review score; it exits 1 when any entry is short. Run it at the end
of every publish run and before telling anyone a batch is done. The only entries allowed to stay short are
those whose source refuses every client (today: Gate2Fundraise, HubSpot), and they are named in the
hand-over note.

## How the site announces it

- `robots.txt` (theme): explicit `Allow: /` for GPTBot, OAI-SearchBot, ChatGPT-User, ClaudeBot, Claude-Web,
  anthropic-ai, PerplexityBot, Google-Extended, Applebot-Extended, CCBot, Bytespider, Amazonbot,
  meta-externalagent and DuckAssistBot; both sitemaps; a comment pointing at `/library-text/` and `/llms.txt`.
- `llms.txt` (search Worker): a Deck library section that says what the files contain, lists the index,
  feeds and sitemap, and states the cadence (new decks most weeks; files regenerated on every publish run).
- Schema: the hub carries `CollectionPage` plus a `Dataset` (distribution = index.md, index.json, feed.json,
  rss.xml; `isAccessibleForFree` true; `dateModified` from the newest entry). Every entry carries
  `PresentationDigitalDocument` with the Markdown file as a free `encoding`, the PDF viewer as a gated part
  (Google's paywalled-content markup), a `Review` with the 1 to 10 rating, dates, keywords and publisher.
- Every entry page links the file with `<link rel="alternate" type="text/markdown">` and a short rail
  line; the hub and entries also link the JSON Feed and RSS.

## Changing the standard

Change this document, the `describe` prompt (`library/sdc_library/describe.py`), the Markdown layout
(`decktext.py`), the audit, and the tests together, then rerun `library describe --redo` so every entry
matches. A standard that only new entries meet is not the standard.
