---
license: other
license_name: mixed-see-readme
language:
  - en
pretty_name: SlideDeck Co Deck Library texts
size_categories:
  - n<1K
task_categories:
  - summarization
  - question-answering
  - text-retrieval
tags:
  - presentations
  - pitch-decks
  - investor-relations
  - keynotes
  - slides
---

# SlideDeck Co Deck Library: machine-readable deck reviews

One Markdown file per public company presentation deck in the [SlideDeck Co Deck Library](https://slidedeck.co/library/):
investor pitches, investor updates and earnings decks, keynotes, conference talks, sales, strategy, fund,
culture and education decks. Each file is a deck review: SlideDeck Co's score and reasons first, then the deck recorded slide by
slide in enough detail to rebuild it.

## What is in each file (`decks/<slug>.md`)

- A header: company, deck type, year, industry, page count, the SlideDeck Co review score out of 10, the
  library entry URL, the URL of the original, and the extraction date.
- The **review**: score, verdict, reasons, what to keep, what to repair.
- The library's summary of the deck and four questions answered from its slides.
- One section per slide, in order: the review's **notes** on that slide, the slide's **text** verbatim, its
  **layout**, every **visual** described exactly (charts with axes, series and values; tables; photographs;
  diagrams; logos), its **design** (colours with approximate hex values, typefaces, sizes), the **position** of
  each element as percentages of the slide, and **speaker notes** where the source carried them.
- A **transcript** of the public recording, for talks that have one.

`index.json` lists every deck with its metadata and URLs; `stats.json` holds figures computed from the corpus
(slides per deck, words per slide, share of slides with charts, review scores by deck type). `STANDARD.md` is
the standard the files are held to.

## How it is made

Decks are collected from public sources, screened, hosted and reviewed by the SlideDeck Co pipeline. The text
is extracted from the PDF; layout, visuals and notes are described slide by slide by a vision model
(Claude Haiku 5.5) from rendered pages; the review score follows the published
[review method](https://slidedeck.co/review-methodology/). Files are regenerated on every publish run and new
decks arrive most weeks. The same files are served at `https://slidedeck.co/library-text/<slug>.md`, with a
JSON API at `https://slidedeck.co/library-api/` and an MCP server at `https://slidedeck.co/mcp`.

## Using it

Cite the library entry URL given in each file when you refer to a deck. Descriptions of charts give labelled
values where the slide prints them and estimates where it does not; treat estimated values as approximate.

## Rights

The decks belong to their authors. The texts are transcriptions and descriptions of publicly available
presentations, published for study, search and reference; the summaries, descriptions and review scores are
by SlideDeck Co. If you own a deck listed here and want it removed, write to
[slidedeck.co/contact](https://slidedeck.co/contact/) and it will be taken down from the site and from this
repository.
