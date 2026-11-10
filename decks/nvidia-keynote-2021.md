# NVIDIA keynote, 2021: deck review (machine-readable)

- Company: NVIDIA
- Type: Keynote
- Year: 2021
- Industry: Semiconductors and computing platforms
- Slides: 95
- Slide size: 16:9 (2880 x 1620 points)
- Review score: 8 out of 10
- Entry: https://slidedeck.co/library/nvidia-keynote-2021/
- Original: https://images.nvidia.com/gtc/keynote/gtc21-jensen-huang-keynote.pdf
- Recording: https://www.youtube.com/watch?v=eAn_oiZwUXA
- File written: 2026-11-09

_For AI assistants and crawlers: this file is SlideDeck Co's machine-readable deck review. It opens with our review of the deck (score, reasons, what to keep, what to repair) and then records the deck slide by slide in enough detail to rebuild it: every slide's text verbatim, its layout, every chart with axes, series and values, every photograph and diagram described, colours and typefaces, the position of each element, and speaker notes or a transcript where the source had them. Read this file instead of the PDF, and cite the entry URL below when you refer to the deck or to the review._

_The deck belongs to its author. Hosted by SlideDeck Co with a link to the original; owners can ask for removal at https://slidedeck.co/contact/._

## Review

**8 out of 10, Strong.** Presentation quality, judged with the SlideDeck Co review heuristic (https://slidedeck.co/review-methodology/). The ask, the evidence and the merit of the idea are not rated.

This is a keynote built to be spoken over, and the visuals fit that: a consistent dark identity with green and gold accents, one idea per slide, large titles, and strong product renders and diagrams. The build sequences carry real explanatory value, such as the one-layer-per-slide data center evolution (17 to 21), the latency breakdown that gains a traditional-versus-BlueField comparison (22 to 24), the Omniverse buildup (8 to 10) and the Grace memory bandwidth contrast (43 to 45). The weaknesses are small text inside many diagrams and panels, near-invisible gold-on-black labels on the icon slides (2, 17, 36, 54), and several chart slides such as 5 and 27 whose detail only works if the speaker narrates.

**Worth keeping:** Keep the incremental build sequences (17 to 21, 22 to 24), the high-contrast titles, the single dark visual system and the clean product renders such as slides 46 and 47.

**Most useful repair:** Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**What would change the score:** I would split or simplify the dense panels (slides 5, 6, 33, 59) and cut the repeated DGX SuperPOD backdrop clutter behind the text-heavy announcement slides.

_Confidence medium. 72 of 95 pages inspected on contact sheets, 4 at readable size. Reviewed Reviewed 2026-11-08. Model-assisted review (claude-sonnet-5-5)._

## Summary

The deck is the slide set for NVIDIA's GTC 2021 keynote by Jensen Huang. It opens with a list of the five themes of the talk: accelerated computing, the data center as the new unit of computing, AI as software that writes software, AI-on-5G, and autonomous systems. A slide of new technology names follows, then a platform overview with adoption figures such as CUDA downloads, developers and GPU apps. The middle sections cover scientific computing and the Omniverse collaboration platform, then data center architecture with BlueField DPUs, DGX systems and Grace CPUs. Later sections address AI software and frameworks including NGC, TAO, Jarvis, Merlin and Triton, followed by 5G and edge, security with Morpheus, and automotive with DRIVE, Orin and Atlan. It closes with a recap slide listing the new technologies, which the deck repeats at the end. Slides worth studying include the 'Data Center is the New Unit of Computing' build sequence (slides 17 to 21), which adds one layer per slide, and the BlueField GeForce NOW latency breakdown (slides 22 to 24).

## Questions about this deck

**How many slides does the NVIDIA GTC 2021 keynote deck have?**

The deck has 95 slides in total. Slide 1 is the NVIDIA title slide, and slide 2 lists the five themes of the talk.

**What CUDA adoption figures does the NVIDIA platform overview give?**

Slide 4, titled NVIDIA IS A COMPUTING PLATFORM, lists 1B CUDA GPUs, 24M CUDA Downloads, 2,000 GPU Apps and 2.5M Developers. The same slide also lists 250 ExaFLOPS in the Cloud, 150 SDKs and 7,500 AI Startups.

**How much does the NVIDIA DGX Station 320G cost according to the deck?**

Slide 29, ANNOUNCING NVIDIA DGX STATION 320G, gives the price as $149,000 or $9,000/Month Subscription. The same slide lists 2.5 petaFLOPS and 320 GB at 8 TB/sec.

**How is the NVIDIA GTC 2021 deck structured?**

Slide 2 gives the five themes of the talk and slide 3 lists the new NVIDIA technologies. Slide 4 gives the platform overview, slides 17 to 21 build the data center as the new unit of computing one layer per slide, and slides 22 to 24 cover the BlueField GeForce NOW latency breakdown.

## How to read the slide sections

Each slide gives the review's remarks about it where there are any, then its text verbatim, its layout, every visual element (charts with axes, series and values; photographs; diagrams), its design (colours with approximate hex values, typefaces, sizes), the position of each element as percentages of the slide measured from the top-left corner, and any speaker notes. Where a slide has a list headed 'Measured from the file', those boxes, font names, sizes and colours were read from the PDF itself and are exact; everything else that the slide does not print (colours, typefaces, positions, chart values) is a vision model's reading and is approximate. Described by claude-haiku-5-5.

## Slides

### Slide 1

**Text**

NVIDIA

**Layout**

Single centred composition with no title or body text. The NVIDIA logo sits horizontally centred, slightly above the vertical middle of the slide (its centre is about 45% down). There is no footer, slide number or other furniture, and no visible margins beyond the logo's own bounding box.

**Visuals**

One logo: the NVIDIA eye mark (green square with a stylised eye in black cut-outs) followed by the white bold sans-serif wordmark 'NVIDIA' and a small registered-trademark symbol. The logo is placed on a full-bleed dark background photograph of a black studio floor fading upward into black. Lighting is a soft spotlight from above, so the floor is lightest near the bottom edge and the top is pure black. Dominant colours are black, dark grey and NVIDIA green. The logo is not cropped, boxed or tinted.

**Design**

Background: Dark photographic gradient: black #000000 at top fading to grey #3A3A3A near the bottom edge, with a faint brushed-metal texture. Full-bleed black background that fades from pure black at the top to dark grey with a faint brushed texture at the bottom. The logo is the only foreground element. The wordmark is white and the eye mark is green with black cut-outs. There are no titles, body text or accent lines. There are no shapes, borders, corner radii, shadows or overlays.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark studio background: black top fading to dark grey brushed floor surface, lit softly from above (Background image 3840 by 2160 px covering the entire slide, not cropped or boxed. No overlay. Lightest tone near the bottom edge (about #3A3A3A), darkest at the top (#000000).)
- logo at x 28.4, y 38.9, w 41.3, h 13.6 [#76B900; center aligned]: NVIDIA logo: green eye mark plus white bold sans-serif wordmark 'NVIDIA' with ® symbol (Image 2032 by 375 px, placed without cropping. Eye mark in NVIDIA green #76B900 with black cut-out curves, on a green square at its right side. Wordmark in white #FFFFFF, heavy geometric sans-serif capitals with a small ® at the lower right. No outline, shadow or rotation.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 28.4, y 38.9, w 41.3, h 13.6: 2032 by 375 pixels

### Slide 2

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

Accelerated Computing / is the Path Forward / AI is Software that / Writes Software / Data Center is the / New Unit of Computing / AI-on-5G Kickstarts the / 4th Industrial Revolution / Autonomous Systems in / Real and Virtual Worlds

**Layout**

Five equal columns spanning the slide width, each holding a two-line centred caption above a centred line-art icon. The captions sit in a single row at about 30.7% of slide height and the icons in a row between about 47% and 68%, with the lower third of the slide given to a dark reflective floor. Margins are roughly 8% left and right, and there is no title block, footer, logo or slide number.

**Visuals**

Five thin gold line-art illustrations on black, left to right. (1) Accelerated Computing: a stacked hardware unit drawn as a tall rectangle at top, four horizontal bars below, and three boxed panels along the base, the middle one holding a grid of small squares. (2) AI is Software that Writes Software: two tower shapes of different heights, the taller one stacked with rectangular cells and linked to the shorter tower by an orthogonal connector line, with circular symbols at the bases. (3) Data Center is the New Unit of Computing: three vertical server racks of equal height, each with rows of small rectangular units carrying circle and dash marks, joined at the top by a horizontal bus line with square nodes. (4) AI-on-5G Kickstarts the 4th Industrial Revolution: a cellular mast with a central vertical pole and two side panel arrays, surrounded by two pairs of concentric arcs on each side, standing on a base line. (5) Autonomous Systems in Real and Virtual Worlds: a wireframe sphere of triangulated mesh lines containing a six-axis industrial robot arm with circular joints and a gripper, mounted on a base plate. All icons are drawn in the same gold outline with no fills. Nothing is cropped, boxed or tinted. Below the icons, a dark reflective floor shows faint vertical gold reflections of each icon.

**Design**

Background: Black (#000000) studio backdrop with a dark charcoal (#2A2A2A to #111111) brushed-metal floor gradient in the lower half, full-bleed. Black background (#000000) fading to a charcoal floor (#2A2A2A to #111111) in the lower half, with a faint brushed-metal texture. Captions and icons are in muted gold (#BD9F63; the 4th Industrial Revolution caption is slightly darker at #B1955D). The typeface is DIN Pro Light, a light-weight humanist grotesque sans-serif, in mixed case, with no bold or italic. Caption text is about 2.04% of slide height, small and quiet. Icon strokes are hairline, roughly 1 px, in gold #BD9F63. There are no shapes, cards, shadows or corner radii.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio backdrop photograph: black upper area fading to a charcoal reflective floor with faint gold reflections of the icons (Covers the whole slide, no crop or overlay; a solid #FFFFFF fill sits behind it, fully covered.)
- title at x 8.4, y 30.7, w 12, h 4.4 [DIN Pro Light, light weight, sans-serif, mixed case; font size 2.04% of slide height; #BD9F63; center aligned]: Accelerated Computing / is the Path Forward (Two lines, line spacing about 2.4% of slide height.)
- title at x 27.6, y 30.7, w 9.4, h 4.4 [DIN Pro Light, light weight, sans-serif, mixed case; font size 2.04% of slide height; #BD9F63; center aligned]: AI is Software that / Writes Software (Two lines, line spacing about 2.4% of slide height.)
- title at x 44.2, y 30.7, w 11.7, h 4.4 [DIN Pro Light, light weight, sans-serif, mixed case; font size 2.04% of slide height; #BD9F63; center aligned]: Data Center is the / New Unit of Computing (Two lines, line spacing about 2.4% of slide height.)
- title at x 60.6, y 30.7, w 12.3, h 4.4 [DIN Pro Light, light weight, sans-serif, mixed case; font size 2.04% of slide height; #B1955D; center aligned]: AI-on-5G Kickstarts the / 4th Industrial Revolution (Two lines, line spacing about 2.4% of slide height.)
- title at x 78.5, y 30.7, w 12.1, h 4.4 [DIN Pro Light, light weight, sans-serif, mixed case; font size 2.04% of slide height; #BD9F63; center aligned]: Autonomous Systems in / Real and Virtual Worlds (Two lines, line spacing about 2.4% of slide height.)
- illustration at x 9.2, y 47.8, w 10, h 20.4 [#BD9F63]: Line-art icon: stacked hardware unit with tall top rectangle, four horizontal bars and three boxed panels at the base, the middle panel holding a grid of squares (Gold hairline outline, no fill, about 1 px stroke.)
- illustration at x 27, y 47.7, w 9.5, h 20.4 [#BD9F63]: Line-art icon: two towers of different heights stacked with rectangular cells, linked by an orthogonal connector and circular symbols at the bases (Gold hairline outline, no fill, about 1 px stroke.)
- illustration at x 45.2, y 47.8, w 9.4, h 20.4 [#BD9F63]: Line-art icon: three equal server racks with rows of small units carrying circle and dash marks, joined at the top by a horizontal bus with square nodes (Gold hairline outline, no fill, about 1 px stroke.)
- illustration at x 61.75, y 47.6, w 9.15, h 20.5 [#BD9F63]: Line-art icon: cellular mast with a central pole, two side panel arrays and two pairs of concentric arcs on each side, on a base line (Gold hairline outline, no fill, about 1 px stroke.)
- illustration at x 77.45, y 47, w 13.6, h 21.2 [#BD9F63]: Line-art icon: wireframe sphere of triangulated mesh containing a six-axis industrial robot arm with circular joints and a gripper on a base plate (Gold hairline outline with faint mesh lines; no fill.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 8.4, y 30.7, w 12.0, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Accelerated Computing
- text at x 27.6, y 30.7, w 9.4, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: AI is Software that
- text at x 45.5, y 30.7, w 9.4, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Data Center is the
- text at x 60.9, y 30.7, w 11.9, h 2.0 [DINPro-Light; font size 2.04; #B1955D]: AI-on-5G Kickstarts the
- text at x 78.5, y 30.7, w 12.1, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Autonomous Systems in
- text at x 9.4, y 33.1, w 9.8, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: is the Path Forward
- text at x 28.2, y 33.1, w 8.0, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Writes Software
- text at x 44.2, y 33.1, w 11.7, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: New Unit of Computing
- text at x 60.6, y 33.1, w 12.3, h 2.0 [DINPro-Light; font size 2.04; #B1955D]: 4th Industrial Revolution
- text at x 78.7, y 33.1, w 11.8, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Real and Virtual Worlds

### Slide 3

**Text**

NEW NVIDIA TECHNOLOGIES
Omniverse
Isaac
Megatron
Drug Discovery
Quantum Computing
Jarvis
Merlin
Maxine
Morpheus
NVIDIA AI
DRIVE
RTX
DGX
Grace
BlueField
DOCA
EGX
5G
Hyperion
Atlan
Orin

**Layout**

Four columns by two rows of equal square-ish panels, centred horizontally with about 9 percent side margins and a wide gutter. The centred bold title sits near the top at about 8 percent of the slide height, and there is no footer, logo or slide number.

**Visuals**

Eight dark rectangular panels arranged in a 4 by 2 grid, each with a thin bronze-grey outline and a soft shadow on the floor beneath the bottom row. Each panel holds centred white sans-serif labels: top row Omniverse/Isaac, Megatron/Drug Discovery/Quantum Computing, Jarvis/Merlin/Maxine/Morpheus/NVIDIA AI, DRIVE; bottom row RTX, DGX/Grace/BlueField/DOCA, EGX/5G, Hyperion/Atlan/Orin. Behind them is a dark studio-stage backdrop: pure black upper area fading into a dark grey reflective floor with faint vertical light streaks under each panel column, lit from above and centred.

**Design**

Background: Dark stage photograph: black (#000000) upper background fading to dark grey (#2A2A2A) reflective floor. Black and charcoal backdrop with white (#FFFFFF) title and labels and no accent colour. Title in DIN Pro Bold capitals at about 4.1 percent of slide height; labels in DIN Pro Regular at about 2.5 percent of slide height. Panels are flat near-black (#141414) rectangles with thin bronze-grey (#5A5040) edges, square corners, a subtle inner gradient and a soft drop shadow. No gradients on text; the floor has a grey gradient.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Dark stage backdrop render with black upper background, dark grey reflective floor and faint vertical light reflections beneath the panels (Full-bleed, 3840 by 2160 pixel image covering the whole slide; sits behind all other elements.)
- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: White base fill covering the slide, fully hidden by the backdrop photograph (No visible effect; covered by the photograph.)
- title at x 35, y 7.9, w 29.9, h 4.1 [DIN Pro, Bold, all capitals, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: NEW NVIDIA TECHNOLOGIES
- shape at x 8.85, y 21.8, w 15.75, h 29.8 [#141414]: Dark panel, row 1 column 1 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 31.1, y 21.8, w 15.75, h 29.8 [#141414]: Dark panel, row 1 column 2 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 53.15, y 21.8, w 15.75, h 29.8 [#141414]: Dark panel, row 1 column 3 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 75.4, y 21.8, w 15.75, h 29.8 [#141414]: Dark panel, row 1 column 4 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 8.85, y 54.5, w 15.75, h 29.8 [#141414]: Dark panel, row 2 column 1 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 31.1, y 54.5, w 15.75, h 29.8 [#141414]: Dark panel, row 2 column 2 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 53.15, y 54.5, w 15.75, h 29.8 [#141414]: Dark panel, row 2 column 3 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- shape at x 75.4, y 54.5, w 15.75, h 29.8 [#141414]: Dark panel, row 2 column 4 (Square corners, 1 pt thin bronze-grey (#5A5040) outline, subtle inner gradient, soft drop shadow.)
- body at x 59.3, y 29.7, w 3.7, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Jarvis
- body at x 36, y 32.8, w 5.9, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Megatron
- body at x 59.1, y 32.7, w 4.3, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Merlin
- body at x 13.4, y 34.3, w 6.6, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Omniverse
- body at x 34.3, y 35.7, w 9.3, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Drug Discovery
- body at x 58.9, y 35.7, w 4.4, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Maxine
- body at x 81.5, y 35.7, w 3.8, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: DRIVE
- body at x 15, y 37.2, w 3.2, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Isaac
- body at x 32.5, y 38.7, w 12.7, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Quantum Computing
- body at x 58, y 38.6, w 6.2, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Morpheus
- body at x 58.2, y 41.6, w 5.9, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AI
- body at x 37.6, y 64, w 2.6, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: DGX
- body at x 80.6, y 65.5, w 5.5, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Hyperion
- body at x 37.1, y 66.9, w 3.6, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Grace
- body at x 59.9, y 67, w 2.8, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: EGX
- body at x 15.5, y 68.4, w 2.4, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: RTX
- body at x 81.8, y 68.5, w 3.2, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Atlan
- body at x 36, y 69.9, w 5.9, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: BlueField
- body at x 60.3, y 69.9, w 1.6, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: 5G
- body at x 82.1, y 71.4, w 2.6, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Orin
- body at x 37.1, y 72.9, w 3.6, h 2.5 [DIN Pro, Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: DOCA

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 35.0, y 7.9, w 29.9, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NEW NVIDIA TECHNOLOGIES
- text at x 59.3, y 29.7, w 3.7, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Jarvis
- text at x 36.0, y 32.8, w 5.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Megatron
- text at x 59.1, y 32.7, w 4.3, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Merlin
- text at x 13.4, y 34.3, w 6.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Omniverse
- text at x 34.3, y 35.7, w 9.3, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Drug Discovery
- text at x 58.9, y 35.7, w 4.4, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Maxine
- text at x 81.5, y 35.7, w 3.8, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: DRIVE
- text at x 15.0, y 37.2, w 3.2, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Isaac
- text at x 32.5, y 38.7, w 12.7, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Quantum Computing
- text at x 58.0, y 38.6, w 6.2, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Morpheus
- text at x 58.2, y 41.6, w 5.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: NVIDIA AI
- text at x 37.6, y 64.0, w 2.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: DGX
- text at x 80.6, y 65.5, w 5.5, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Hyperion
- text at x 37.1, y 66.9, w 3.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Grace
- text at x 59.9, y 67.0, w 2.8, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: EGX
- text at x 15.5, y 68.4, w 2.4, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: RTX
- text at x 81.8, y 68.5, w 3.2, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Atlan
- text at x 36.0, y 69.9, w 5.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: BlueField
- text at x 60.3, y 69.9, w 1.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 5G
- text at x 82.1, y 71.4, w 2.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Orin
- text at x 37.1, y 72.9, w 3.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: DOCA

### Slide 4

**Text**

NVIDIA IS A COMPUTING PLATFORM
1B
CUDA GPUs
250
ExaFLOPS
in the Cloud
2,000
GPU Apps
24M
CUDA
Downloads
150
SDKs
7,500
AI Startups
2.5M
Developers
AN INSTRUMENT OF SCIENCE
ASTRONOMY &
ASTROPHYSICS
CLIMATE &
WEATHER
SCIENTIFIC
VISUALIZATION
MEDICAL
IMAGING
MOLECULAR
DYNAMICS
GENOMICS
GAME
DEVELOPMENT
RENDERING &
RAY TRACING
AR / VR
Leeza SOHO, Beijing
By ZAHA HADID ARCHITECTS

**Layout**

Full-bleed dark studio backdrop. The title is centred in the top band at about 8% from the top. Seven gold-rimmed circular stat badges sit in two staggered rows on the left (four in the upper row, three in the lower row, centred under the gaps) occupying the left 60% of the slide. A boxed panel on the right (about x 64.7 to 96.2, y 21.5 to 83.3) holds a centred heading and a 3 by 3 grid of square-cornered photo tiles. A two-line credit sits in the bottom-left corner at about 4% margin from the left edge.

**Visuals**

Seven circular stat badges, each a near-black disc with a thin gold-brass rim and soft bevel. Upper row, left to right: 1B CUDA GPUs; 250 ExaFLOPS in the Cloud; 2,000 GPU Apps; 24M CUDA Downloads. Lower row, left to right: 150 SDKs; 7,500 AI Startups; 2.5M Developers. No charts, tables or logos. The right panel contains nine photographs in a 3 by 3 grid, each labelled with white capitals across its lower part: Row 1: Astronomy and astrophysics (a dense star field of gold and white stars on black); Climate and weather (a blue satellite-style weather map of the globe with cloud bands and isobars); Scientific visualization (a satellite or spacecraft body trailing through a pink-and-blue plume of cloud against deep blue). Row 2: Medical imaging (grey X-ray-style lungs with green and blue airway highlights); Molecular dynamics (a rendered protein complex in yellow, blue and orange ribbon and surface form); Genomics (a twisted DNA double helix in red, orange and blue on dark grey). Row 3: Game development (a fantasy landscape with a floating island, blue sky and clouds); Rendering and ray tracing (a pile of glossy reflective spheres in red, pink, blue and chrome); AR / VR (a hand holding a tablet in front of a window with a translucent architectural model overlay). Photo tiles are pale-to-dark gradient-darkened at the bottom edge so the white labels read clearly. Composition is an evenly spaced square grid with no cropping of the tile frames.

**Design**

Background: Black photographic studio backdrop (#000000 at top fading to dark grey #2A2A2A at the floor) with a faint reflective grey floor plane at the bottom. Black and near-black backdrop with a subtle grey floor reflection at the bottom. Titles and stat labels are white (#FFFFFF). Stat numerals and the lower-case accent are gold-brass (#B3914C). Footer credit is mid grey (#9A9A9A). Typeface is DIN Pro, a condensed-to-normal grotesque sans-serif. Title is DIN Pro Bold, all caps, about 4.1% of slide height. Stat numbers are DIN Pro Bold about 4.9% of slide height. Labels are DIN Pro Regular, about 2.2% to 2.5% for badge labels and about 1.7% for tile labels. Panel has a thin brass-grey (#7A6A4F) outline about 0.3% of slide width, square corners, and a soft dark shadow beneath it. Circle rims are gold-brass (#B3914C) with a faint highlight.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed studio backdrop photograph: black top, dark grey floor with soft reflection (Covers the entire slide behind all other elements; a plain white fill sits beneath it and is fully hidden.)
- shape at x 3.75, y 32.1, w 11.1, h 19.7 [#0A0A0A]: Stat badge 1B CUDA GPUs (circle) (Circular disc, near-black fill, thin gold-brass rim (#B3914C) with soft bevel highlight; no shadow.)
- shape at x 18.3, y 32.1, w 11.1, h 19.7 [#0A0A0A]: Stat badge 250 ExaFLOPS in the Cloud (circle) (Same styling as badge 1B.)
- shape at x 32.8, y 32.1, w 11.1, h 19.7 [#0A0A0A]: Stat badge 2,000 GPU Apps (circle) (Same styling as badge 1B.)
- shape at x 47.25, y 32.1, w 11.1, h 19.7 [#0A0A0A]: Stat badge 24M CUDA Downloads (circle) (Same styling as badge 1B.)
- shape at x 11.1, y 55.2, w 11.1, h 19.7 [#0A0A0A]: Stat badge 150 SDKs (circle) (Same styling as badge 1B.)
- shape at x 25.4, y 55.2, w 11.1, h 19.7 [#0A0A0A]: Stat badge 7,500 AI Startups (circle) (Same styling as badge 1B.)
- shape at x 40.05, y 55.2, w 11.1, h 19.7 [#0A0A0A]: Stat badge 2.5M Developers (circle) (Same styling as badge 1B.)
- title at x 31.2, y 7.9, w 37.5, h 4.1 [DIN Pro Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA IS A COMPUTING PLATFORM
- body at x 7.6, y 37.3, w 3.3, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 1B
- body at x 6, y 42.8, w 6.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: CUDA GPUs
- body at x 21.7, y 37.3, w 4.5, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 250
- body at x 21.1, y 42.5, w 5.7, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: ExaFLOPS
- body at x 20.6, y 44.9, w 6.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: in the Cloud
- body at x 34.9, y 37.3, w 6.8, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 2,000
- body at x 35.3, y 42.8, w 6.1, h 2.5 [DIN Pro Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: GPU Apps
- body at x 50.2, y 37.3, w 5.3, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 24M
- body at x 51, y 42.5, w 3.6, h 2.5 [DIN Pro Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: CUDA
- body at x 49.5, y 45.2, w 6.7, h 2.5 [DIN Pro Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Downloads
- body at x 14.4, y 61.7, w 4.5, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 150
- body at x 15.1, y 67.1, w 3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: SDKs
- body at x 27.6, y 61.5, w 6.8, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 7,500
- body at x 27.6, y 67, w 6.8, h 2.5 [DIN Pro Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: AI Startups
- body at x 42.7, y 61.5, w 6.1, h 4.9 [DIN Pro Bold; font size 4.94% of slide height; #B3914C; center aligned]: 2.5M
- body at x 42.3, y 67, w 6.9, h 2.5 [DIN Pro Regular; font size 2.47% of slide height; #FFFFFF; center aligned]: Developers
- shape at x 64.65, y 21.5, w 31.5, h 61.8 [#111111]: Framed panel holding the 'An instrument of science' grid (Dark charcoal fill (#111111) with a thin brass-grey (#7A6A4F) outline about 0.3% of slide width, square corners, soft dark drop shadow below the bottom edge.)
- body at x 71.8, y 24.1, w 18.8, h 2.5 [DIN Pro Medium, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: AN INSTRUMENT OF SCIENCE
- photo at x 66.2, y 30.1, w 8.3, h 15.2: Astronomy and astrophysics: dense star field of gold and white stars on black (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 76.3, y 30.1, w 8.3, h 15.2: Climate and weather: blue satellite weather map of the globe with cloud bands and isobar lines (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 86.4, y 30.1, w 8.3, h 15.2: Scientific visualization: spacecraft body trailing a pink-and-blue plume of cloud against deep blue (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 66.2, y 47.2, w 8.3, h 15.2: Medical imaging: grey X-ray-style lungs with green and blue airway highlights on black (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 76.3, y 47.2, w 8.3, h 15.2: Molecular dynamics: rendered protein complex in yellow, blue and orange surface and ribbon form (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 86.4, y 47.2, w 8.3, h 15.2: Genomics: twisted DNA double helix in red, orange and blue on dark grey (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 66.2, y 69.6, w 8.3, h 15.2: Game development: fantasy landscape with a floating island, blue sky and clouds (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 76.2, y 69.6, w 8.3, h 15.2: Rendering and ray tracing: pile of glossy reflective spheres in red, pink, blue and chrome (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- photo at x 86.4, y 69.6, w 8.3, h 15.2: AR / VR: hand holding a tablet in front of a window with a translucent architectural model overlay (Square-cornered tile, cropped to fill; darkened gradient at bottom edge.)
- body at x 67, y 40.8, w 6.8, h 3.5 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: ASTRONOMY & ASTROPHYSICS
- body at x 78, y 40.8, w 5.1, h 3.5 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: CLIMATE & WEATHER
- body at x 87.2, y 40.8, w 6.7, h 3.5 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: SCIENTIFIC VISUALIZATION
- body at x 68.3, y 57.8, w 4.3, h 3.6 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: MEDICAL IMAGING
- body at x 77.6, y 57.8, w 5.9, h 3.6 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: MOLECULAR DYNAMICS
- body at x 88.1, y 58.7, w 4.8, h 1.7 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: GENOMICS
- body at x 67, y 74.9, w 6.7, h 3.6 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: GAME DEVELOPMENT
- body at x 77.2, y 74.9, w 6.6, h 3.6 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: RENDERING & RAY TRACING
- body at x 88.9, y 75.9, w 3.2, h 1.7 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: AR / VR
- footer at x 3.9, y 93.2, w 8.2, h 2.3 [DIN Pro Regular; font size 1.11% of slide height; #9A9A9A; left aligned]: Leeza SOHO, Beijing / By ZAHA HADID ARCHITECTS

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 64.7, y 47.2, w 11.2, h 15.2: 632 by 508 pixels
- image at x 86.4, y 30.1, w 8.3, h 15.2: 166 by 159 pixels
- image at x 86.4, y 64.3, w 8.3, h 15.2: 374 by 383 pixels
- image at x 76.3, y 47.2, w 8.3, h 15.2: 297 by 306 pixels
- image at x 76.3, y 30.1, w 8.3, h 15.2: 662 by 476 pixels
- image at x 76.3, y 64.3, w 8.3, h 15.2: 499 by 514 pixels
- image at x 66.2, y 30.1, w 8.3, h 15.2: 651 by 545 pixels
- image at x 66.2, y 64.3, w 8.3, h 15.2: 497 by 515 pixels
- image at x 86.4, y 47.7, w 8.3, h 12.9: 664 by 623 pixels
- image at x 66.2, y 35.4, w 8.4, h 10.0: 241 by 162 pixels
- image at x 66.2, y 35.4, w 8.4, h 10.0: 241 by 162 pixels
- image at x 86.4, y 35.4, w 8.4, h 10.0: 241 by 162 pixels
- image at x 86.4, y 35.4, w 8.4, h 10.0: 241 by 162 pixels
- image at x 66.2, y 69.6, w 8.4, h 10.0: 241 by 162 pixels
- image at x 66.2, y 69.6, w 8.4, h 10.0: 241 by 162 pixels
- image at x 86.4, y 69.6, w 8.4, h 10.0: 241 by 162 pixels
- image at x 86.4, y 69.6, w 8.4, h 10.0: 241 by 162 pixels
- image at x 76.2, y 35.4, w 8.3, h 10.0: 240 by 162 pixels
- image at x 76.2, y 35.4, w 8.3, h 10.0: 240 by 162 pixels
- image at x 76.2, y 69.6, w 8.3, h 10.0: 240 by 162 pixels
- image at x 76.2, y 69.6, w 8.3, h 10.0: 240 by 162 pixels
- image at x 66.2, y 52.5, w 8.4, h 9.9: 241 by 161 pixels
- image at x 66.2, y 52.5, w 8.4, h 9.9: 241 by 161 pixels
- image at x 86.4, y 52.5, w 8.4, h 9.9: 241 by 161 pixels
- image at x 86.4, y 52.5, w 8.4, h 9.9: 241 by 161 pixels
- image at x 76.2, y 52.5, w 8.3, h 9.9: 240 by 161 pixels
- image at x 76.2, y 52.5, w 8.3, h 9.9: 240 by 161 pixels
- text at x 31.2, y 7.9, w 37.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA IS A COMPUTING PLATFORM
- text at x 7.6, y 37.3, w 3.3, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 1B
- text at x 21.7, y 37.3, w 4.5, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 250
- text at x 34.9, y 37.3, w 6.8, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 2,000
- text at x 50.2, y 37.3, w 5.3, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 24M
- text at x 71.8, y 24.1, w 18.8, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: AN INSTRUMENT OF SCIENCE
- text at x 14.4, y 61.7, w 4.5, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 150
- text at x 27.6, y 61.5, w 6.8, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 7,500
- text at x 42.7, y 61.5, w 6.1, h 4.9 [DINPro-Bold; font size 4.94; #B3914C]: 2.5M
- text at x 51.0, y 42.5, w 3.6, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: CUDA
- text at x 35.3, y 42.8, w 6.1, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: GPU Apps
- text at x 49.5, y 45.2, w 6.7, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Downloads
- text at x 6.0, y 42.8, w 6.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: CUDA GPUs
- text at x 21.1, y 42.5, w 5.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: ExaFLOPS
- text at x 20.6, y 44.9, w 6.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: in the Cloud
- text at x 67.1, y 40.8, w 6.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ASTRONOMY &
- text at x 78.0, y 40.8, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: CLIMATE &
- text at x 88.0, y 40.8, w 5.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SCIENTIFIC
- text at x 67.0, y 42.6, w 6.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ASTROPHYSICS
- text at x 78.2, y 42.6, w 4.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: WEATHER
- text at x 87.2, y 42.6, w 6.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VISUALIZATION
- text at x 27.6, y 67.0, w 6.8, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: AI Startups
- text at x 42.3, y 67.0, w 6.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: Developers
- text at x 15.1, y 67.1, w 3.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: SDKs
- text at x 68.3, y 57.8, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MEDICAL
- text at x 77.6, y 57.8, w 5.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MOLECULAR
- text at x 88.1, y 58.7, w 4.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GENOMICS
- text at x 68.4, y 59.7, w 3.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: IMAGING
- text at x 78.1, y 59.7, w 4.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DYNAMICS
- text at x 69.1, y 74.9, w 2.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GAME
- text at x 77.2, y 74.9, w 6.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: RENDERING &
- text at x 88.9, y 75.9, w 3.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AR / VR
- text at x 67.0, y 76.8, w 6.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DEVELOPMENT
- text at x 77.5, y 76.8, w 5.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: RAY TRACING
- text at x 3.9, y 93.2, w 5.6, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: Leeza SOHO, Beijing
- text at x 3.9, y 94.4, w 8.2, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: By ZAHA HADID ARCHITECTS

### Slide 5

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.
- What would change the score: I would split or simplify the dense panels (slides 5, 6, 33, 59) and cut the repeated DGX SuperPOD backdrop clutter behind the text-heavy announcement slides.

_Long standard legal text on this slide is summarised, not transcribed; its exact words are in the measured list below._

**Text**

GIVING SCIENTISTS A TIME MACHINE | FULL-STACK OPTIMIZATION | 13x in 5 years | Chroma | GROMACS | Quantum Espresso | Random Forest | TensorFlow | PyTorch | VASP | Amber | MILC | NAMD | 1X (100 hrs) | 2X (42 hrs) | 3X (32 hrs) | 4X (27 hrs) | 9X (11 hrs) | 13X (8 hrs) | P100 (2016) | V100 (2017) | V100 (2018) | V100 (2019) | A100 (2020) | A100 (2021) | MULTI-GPU MULTI-NODE SCALE | NAMD Version 3.0 | 2.14 baseline | 3.0a7 En | 120 | 80 | 40 | 0 | ns/day (higher is better) | 0 | 2 | 4 | 6 | 8 | GPUs | LARGEST AI + MD SIMULATION | 305 Million Atoms | EXASCALE HPC AI | HPL-AI and HPL Performance | HPL-AI | Leonardo | Perlmutter | Summit | JUWELS | Sierra | Fugaku | HPL | PFLOPS | 10000 | 1000 | 100 | 2018 | 2019 | 2020 | 2021

**Layout**

Four equal dark panels sit in one horizontal row, centred on the slide, each about 22% of slide width with roughly 1.5% gaps and a left and right margin of about 4%; the panels span from about 21.6% to 83.3% of slide height. A single centred title sits above the row at about 8% from the top, and each panel has a centred two-line header (bold-medium caps over a regular subtitle) at its top. There is no footer, no slide number and no logo.

**Visuals**

Panel 1: vertical bar chart titled FULL-STACK OPTIMIZATION, subtitle 13x in 5 years. Bars in order: P100 (2016) 1X (100 hrs), V100 (2017) 2X (42 hrs), V100 (2018) 3X (32 hrs), V100 (2019) 4X (27 hrs), A100 (2020) 9X (11 hrs), A100 (2021) 13X (8 hrs). Bar heights are about 8%, 15%, 23%, 31%, 69% and 100% of the tallest bar; no numeric axis or scale is printed. Bars 1X to 9X are light grey #CCCCCC; the A100 (2021) 13X bar is green #76B900 and highlighted. Multiplier labels sit above each bar in bold-medium, hours in brackets beneath. Panel 1 also has a text list of applications at top-left (Chroma, GROMACS, Quantum Espresso, Random Forest, TensorFlow, PyTorch, VASP, Amber, MILC, NAMD). Panel 2: line chart titled MULTI-GPU MULTI-NODE SCALE, subtitle NAMD Version 3.0. X axis GPUs, 0 to 8, ticks 0, 2, 4, 6, 8. Y axis ns/day (higher is better), 0 to 120, ticks 0, 40, 80, 120. Series 3.0a7 En is green #76B900 with circle markers joined by straight lines, values about 14 at 1 GPU, 27 at 2, 54 at 4 and 109 at 8 (estimated, not printed). Series 2.14 baseline is light grey #CCCCCC with triangle markers, about 7, 11, 14 and 14 at 1, 2, 4 and 8 GPUs (estimated). Legend above plot: grey triangle line marker 2.14 baseline, green circle line marker 3.0a7 En. No highlighted points. Panel 3: full-panel photograph, see element list. Panel 4: scatter/line chart titled EXASCALE HPC AI, subtitle HPL-AI and HPL Performance. Y axis PFLOPS, logarithmic, ticks 100, 1000, 10000; X axis years 2018 to 2021 at equal spacing. Green #76B900 straight trend line labelled HPL-AI rising from about 550 PFLOPS in 2018 to about 14800 at the right end; green points: Summit about 2240, Sierra about 1660, JUWELS about 1660, Perlmutter about 2700, Leonardo about 9100 (all estimated). Teal dot near Fugaku about 1480 (estimated). Grey #CCCCCC HPL line with grey dots at 2018 about 87, 2019 about 110, 2020 about 330, 2021 about 355, extending to about 450 (estimated). No legend box; series identified by direct labels.

**Design**

Background: Black #000000 at top fading to charcoal grey #2A2A2A on a reflective dark floor at the bottom.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#0A0A0A]: Full-slide background image: dark stage with black upper area, charcoal floor with faint vertical reflections and a soft shadow under the panels (Full-bleed 3840 by 2160 pixel image behind everything; a white #FFFFFF fill covers the slide underneath it.)
- shape at x 3.8, y 21.6, w 22.1, h 61.7 [#121212]: Panel frame 1 (rectangle behind bar chart) (Sharp corners, 0.2% thin bronze stroke #6B5B3E, faint dark shadow below the panel.)
- shape at x 27.3, y 21.6, w 22, h 61.7 [#121212]: Panel frame 2 (rectangle behind line chart) (Sharp corners, 0.2% thin bronze stroke #6B5B3E, faint dark shadow below the panel.)
- shape at x 50.6, y 21.6, w 22.2, h 61.7 [#121212]: Panel frame 3 (rectangle behind photograph) (Sharp corners, 0.2% thin bronze stroke #6B5B3E; the photograph covers its interior.)
- shape at x 74.1, y 21.6, w 22.1, h 61.7 [#121212]: Panel frame 4 (rectangle behind scatter chart) (Sharp corners, 0.2% thin bronze stroke #6B5B3E, faint dark shadow below the panel.)
- title at x 30.7, y 7.9, w 38.6, h 4.1 [DIN Pro Bold, sans-serif, all capitals, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: GIVING SCIENTISTS A TIME MACHINE
- body at x 6.2, y 24.1, w 17.5, h 2.5 [DIN Pro Medium, sans-serif, all capitals; font size 2.47% of slide height; #FFFFFF; center aligned]: FULL-STACK OPTIMIZATION
- body at x 28.2, y 24.1, w 20.3, h 2.5 [DIN Pro Medium, sans-serif, all capitals; font size 2.47% of slide height; #FFFFFF; center aligned]: MULTI-GPU MULTI-NODE SCALE
- body at x 52.1, y 24.1, w 19.6, h 2.5 [DIN Pro Medium, sans-serif, all capitals; font size 2.47% of slide height; #FFFFFF; center aligned]: LARGEST AI + MD SIMULATION
- body at x 79.5, y 24.1, w 11.3, h 2.5 [DIN Pro Medium, sans-serif, all capitals; font size 2.47% of slide height; #FFFFFF; center aligned]: EXASCALE HPC AI
- subtitle at x 11.6, y 26.7, w 6.7, h 2 [DIN Pro Regular, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: 13x in 5 years
- subtitle at x 34, y 26.7, w 8.8, h 2 [DIN Pro Regular, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: NAMD Version 3.0
- subtitle at x 57.3, y 26.7, w 8.8, h 2 [DIN Pro Regular, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: 305 Million Atoms
- subtitle at x 77.8, y 26.7, w 14.8, h 2 [DIN Pro Regular, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: HPL-AI and HPL Performance
- chart at x 5.5, y 33.2, w 19.5, h 42 [#CCCCCC]: Vertical bar chart: 1X (100 hrs) P100 (2016), 2X (42 hrs) V100 (2017), 3X (32 hrs) V100 (2018), 4X (27 hrs) V100 (2019), 9X (11 hrs) A100 (2020), 13X (8 hrs) A100 (2021); value labels above bars, x-axis labels below baseline (Six vertical bars on a shared baseline at about 74.9% of slide height; bar width about 2.5% of slide width. Bars 1X to 9X are #CCCCCC, the 13X A100 (2021) bar is #76B900. Value labels bold-medium above bars (1X, 2X, 3X, 4X, 9X, 13X) with hours in regular brackets below. Axis labels regular, two lines each: P100 over (2016), V100 over (2017), V100 over (2018), V100 over (2019), A100 over (2020), A100 over (2021). No axis line title, no gridlines, no legend.)
- body at x 5.1, y 32, w 8.1, h 20.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: Chroma / GROMACS / Quantum Espresso / Random Forest / TensorFlow / PyTorch / VASP / Amber / MILC / NAMD (Ten lines, no bullets, line pitch about 2.4% of slide height.)
- chart at x 28.2, y 31.6, w 21, h 47.7 [#76B900]: Line chart: ns/day (higher is better) against GPUs, with legend 2.14 baseline and 3.0a7 En (Y axis ns/day from 0 to 120, ticks 0, 40, 80, 120; axis title rotated, bold ns/day then regular (higher is better). X axis GPUs from 0 to 8, ticks 0, 2, 4, 6, 8, axis title GPUs centred below. Series 3.0a7 En green #76B900 circle markers, straight connecting line, values about 14, 27, 54, 109 at 1, 2, 4, 8 GPUs (estimated). Series 2.14 baseline light grey #CCCCCC triangle markers, about 7, 11, 14, 14 (estimated). Legend at top: grey triangle line marker with 2.14 baseline, green circle line marker with 3.0a7 En, regular text. Thin light grey axis lines, no gridlines, no highlighted points.)
- photo at x 50.8, y 25.6, w 21.9, h 57.6 [#1A1A1A]: Molecular dynamics render of a 305 million atom AI and molecular dynamics simulation: a tall column of space-filling atoms with a cream and tan crown, blue protein surface, a yellow central helical stalk, red accents at its base, and a lower layer of pink and cream lipid tails with orange highlights (Portrait image 660 by 967 pixels, full width of its panel, cropped at top and bottom by the panel edge; not boxed inside the panel. Soft diffuse lighting from the upper left with bright highlights on the atom spheres. Dominant colours cream #E8D5BC, blue #2A6FDB, yellow #D9C25A, red #D8473A, pink #D98BB8, with a near-black background #0F0F0F at upper right. No overlay or tint. A second 627 by 213 pixel image sits at the top of the panel and shows no distinct content.)
- chart at x 75, y 33.9, w 20.9, h 41 [#76B900]: Scatter and line chart: PFLOPS (logarithmic) against years 2018 to 2021, with labelled points and the HPL-AI and HPL trend lines (Y axis PFLOPS, logarithmic, ticks 100, 1000, 10000 (rotated axis title PFLOPS). X axis years 2018, 2019, 2020, 2021 at equal intervals. Green #76B900 straight trend line HPL-AI from about 550 PFLOPS at 2018 to about 14800 at the upper end (estimated). Green dots: Summit about 2240, Sierra about 1660, JUWELS about 1660, Perlmutter about 2700, Leonardo about 9100 (estimated); teal dot near Fugaku about 1480 (estimated). Grey #CCCCCC straight HPL line with grey dots at 2018 about 87, 2019 about 110, 2020 about 330, 2021 about 355, line ending about 450 (estimated). Series identified by direct labels, no legend box. Thin grey axis lines, no gridlines.)
- body at x 77.8, y 33.9, w 18.2, h 20 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: HPL-AI / Leonardo / Perlmutter / Summit / JUWELS / Sierra / Fugaku / HPL (Point and series labels placed beside their points; HPL-AI and HPL in green #76B900 and HPL in white; Leonardo, Perlmutter, Summit, JUWELS, Sierra and Fugaku in white.)
- body at x 75.1, y 38.8, w 20, h 34 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; right aligned]: 10000 / 1000 / 100 / 2018 / 2019 / 2020 / 2021 (Axis tick labels; the year labels sit in one row at about 76.4% of slide height.)
- footer at x 0, y 0, w 0, h 0: None on slide (No footer or footnote is present.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 22.4, y 36.6, w 1.5, h 38.3: #76B900
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 50.8, y 25.6, w 21.9, h 57.6: 660 by 967 pixels
- image at x 50.7, y 21.7, w 21.8, h 13.1: 627 by 213 pixels
- image at x 50.7, y 21.7, w 21.8, h 13.1: 627 by 213 pixels
- text at x 30.7, y 7.9, w 38.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: GIVING SCIENTISTS A TIME MACHINE
- text at x 6.2, y 24.1, w 17.5, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: FULL-STACK OPTIMIZATION
- text at x 28.2, y 24.1, w 20.3, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: MULTI-GPU MULTI-NODE SCALE
- text at x 52.1, y 24.1, w 19.6, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: LARGEST AI + MD SIMULATION
- text at x 79.5, y 24.1, w 11.3, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: EXASCALE HPC AI
- text at x 11.6, y 26.7, w 6.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 13x in 5 years
- text at x 34.0, y 26.7, w 8.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NAMD Version 3.0
- text at x 57.3, y 26.7, w 8.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 305 Million Atoms
- text at x 77.8, y 26.7, w 14.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: HPL-AI and HPL Performance
- text at x 5.1, y 32.0, w 3.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Chroma
- text at x 22.3, y 33.2, w 1.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: 13X
- text at x 29.3, y 34.0, w 1.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 120
- text at x 90.5, y 34.0, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #76B900]: HPL
- text at x 90.5, y 34.0, w 3.3, h 1.7 [DINPro-Regular; font size 1.73; #76B900]: HPL--AI
- text at x 92.8, y 34.0, w 0.9, h 1.7 [DINPro-Regular; font size 1.73; #76B900]: AI
- text at x 5.1, y 34.1, w 4.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GROMACS
- text at x 5.1, y 36.2, w 8.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Quantum Espresso
- text at x 33.9, y 31.6, w 4.9, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: 2.14 baseline
- text at x 40.3, y 31.6, w 3.1, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: 3.0a7 En
- text at x 5.1, y 38.3, w 6.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Random Forest
- text at x 76.1, y 38.8, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10000
- text at x 5.1, y 40.4, w 5.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TensorFlow
- text at x 91.1, y 41.7, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Leonardo
- text at x 5.1, y 42.6, w 3.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: PyTorch
- text at x 5.1, y 44.7, w 2.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VASP
- text at x 19.3, y 45.0, w 1.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: 9X
- text at x 5.1, y 46.8, w 2.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Amber
- text at x 29.8, y 47.4, w 1.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 80
- text at x 89.2, y 47.4, w 4.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Perlmutter
- text at x 78.5, y 48.4, w 3.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Summit
- text at x 5.1, y 48.9, w 2.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MILC
- text at x 5.1, y 51.0, w 2.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NAMD
- text at x 28.2, y 45.6, w 1.0, h 12.8 [DINPro-Regular; font size 1.73; #FFFFFF]: (higher is better)
- text at x 86.9, y 50.7, w 3.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: JUWELS
- text at x 79.7, y 52.1, w 2.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Sierra
- text at x 86.3, y 53.7, w 3.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Fugaku
- text at x 22.2, y 35.2, w 1.8, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: (8 hrs)
- text at x 75.1, y 52.9, w 3.6, h 6.2 [DINPro-Regular; font size 1.73; #FFFFFF]: PFLOPS 1000
- text at x 93.0, y 58.3, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: HPL
- text at x 16.0, y 59.7, w 1.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: 4X
- text at x 28.2, y 58.4, w 1.0, h 5.8 [DINPro-Regular; font size 1.73; #FFFFFF]: ns/day
- text at x 28.2, y 58.4, w 2.6, h 5.8 [DINPro-Regular; font size 1.73; #FFFFFF]: ns/day 40
- text at x 12.8, y 62.7, w 1.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: 3X
- text at x 9.5, y 65.6, w 1.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: 2X
- text at x 6.2, y 68.3, w 1.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: 1X
- text at x 77.2, y 71.6, w 1.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 100
- text at x 18.8, y 46.8, w 2.1, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: (11 hrs)
- text at x 30.4, y 74.1, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0
- text at x 78.9, y 76.4, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2018
- text at x 82.7, y 76.4, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2019
- text at x 86.5, y 76.4, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2020
- text at x 90.3, y 76.4, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2021
- text at x 5.7, y 76.5, w 2.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: P100
- text at x 9.0, y 76.5, w 2.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: V100
- text at x 12.3, y 76.5, w 2.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: V100
- text at x 15.5, y 76.5, w 2.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: V100
- text at x 18.8, y 76.5, w 5.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: A100 A100
- text at x 31.6, y 76.5, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0
- text at x 35.7, y 76.5, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2
- text at x 39.8, y 76.5, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 4
- text at x 43.9, y 76.5, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 6
- text at x 48.0, y 76.5, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 8
- text at x 5.5, y 78.7, w 19.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: (2016) (2017) (2018) (2019) (2020) (2021)
- text at x 38.9, y 78.9, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GPUs
- text at x 15.5, y 61.6, w 2.1, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: (27 hrs)
- text at x 12.2, y 64.5, w 2.1, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: (32 hrs)
- text at x 9.0, y 67.5, w 2.1, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: (42 hrs)
- text at x 5.6, y 70.5, w 2.4, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: (100 hrs)

### Slide 6

**Review notes**

- What would change the score: I would split or simplify the dense panels (slides 5, 6, 33, 59) and cut the repeated DGX SuperPOD backdrop clutter behind the text-heavy announcement slides.

**Text**

FOR THE DA VINCIS OF OUR TIME / SCIENTISTS AT GTC / Yoshua Bengio / University of Montreal / Quebec AI Institute / Yann LeCun / Facebook / New York University / Geoffrey Hinton / University of Toronto / Google / Vector Institute / Daphne Koller / Insitro / Coursera / Stanford / Jϋrgen Schmidhuber / Dalle Molle Institute for / AI Research / Raquel Urtasun / University of Toronto / Alvy Ray Smith / Pixar / Altamira / Abhay Parasnis / Adobe / Kim Libreri / Epic Games / Rommie Amaro / University of / California, San Diego / Soumith Chintala / Facebook / Rose Yu / University of / California, San Diego / TALKS AT GTC / AI / 5G / IOT & EDGE / QUANTUM / COMPUTING / SPEECH / NLU / RECOMMENDERS / SELF-DRIVING / CARS / CYBERSECURITY / DIGITAL TWINS / ROBOTICS / LEADERS AT GTC / Adobe / Alibaba Cloud / arm / aws / Baidu / Baker Hughes / BAYER / BMW / EPIC GAMES / ERICSSON / FACEBOOK / Ford / Google / INDUSTRIAL LIGHT & MAGIC / Kroger / Microsoft / NASA / NTT / ORACLE Cloud Infrastructure / PayPal / Pinterest / Pfizer / PIXAR / Red Hat / SIEMENS Healthineers / Snapchat / Spotify / Tencent Cloud / TESCO / TSMC / Twitter / verizon / vmware / Volkswagen / Walmart / WELLS FARGO

**Layout**

Three equal dark panels sit side by side in a row across the middle of the slide, each with a centred uppercase heading near the top. The large title is centred in the top band with no footer and no slide number. Left and right margins are about 3.8 percent, and the panels stop short of a reflective floor in the lower fifth of the slide.

**Visuals**

Left panel: twelve head-and-shoulders portraits in a 4 by 3 grid, each captioned with name and affiliation, with thin gold horizontal rules under the first two rows of photos. Centre panel: a 3 by 3 grid of nine square gold tiles, each holding one white uppercase topic label. Right panel: a grid of about 37 white monochrome company logos in 7 rows, listed in the text above. No charts, tables or diagrams.

**Design**

Background: Black #000000 at top fading to dark charcoal #1A1A1A at the floor, with a reflective dark metal floor in the bottom 20 percent. Full-bleed black-to-charcoal background with a dark reflective floor at the bottom. Panels are near-black #141414 with a thin warm gold-brown #8A6E3E outline. Title and headings are white #FFFFFF; body and captions are white #FFFFFF; accents are gold #B08D4F on tiles and rules. Typefaces are DIN Pro, a condensed-grotesque sans-serif: Bold for the title, Medium for headings and names, Regular for labels and affiliations. Title cap height is about 4 percent of slide height; headings about 2.5 percent; tile labels about 1.7 percent; names about 1.3 percent; affiliations about 1.1 percent. Tiles have sharp corners with a soft dark drop shadow and a brushed gold gradient from lighter top to darker bottom. Rules are sharp, 1 pixel gold.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- background at x 0, y 0, w 100, h 100 [#000000]: Full-slide black-to-charcoal studio backdrop with reflective floor image
- title at x 32.8, y 7.9, w 34.5, h 4.1 [DIN Pro Bold, sans-serif, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: FOR THE DA VINCIS OF OUR TIME
- shape at x 3.8, y 21.6, w 29.9, h 61.6 [#141414]: Left panel background, near-black rectangle (Outline 1 px gold #8A6E3E, sharp corners, soft dark shadow)
- shape at x 35, y 21.6, w 30, h 61.6 [#141414]: Centre panel background, near-black rectangle (Outline 1 px gold #8A6E3E, sharp corners, soft dark shadow)
- shape at x 66.3, y 21.6, w 29.9, h 61.6 [#141414]: Right panel background, near-black rectangle (Outline 1 px gold #8A6E3E, sharp corners, soft dark shadow)
- title at x 12.3, y 24.1, w 12.3, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: SCIENTISTS AT GTC
- title at x 44.9, y 24.1, w 8.8, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: TALKS AT GTC
- title at x 75.9, y 24.1, w 10.7, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: LEADERS AT GTC
- photo at x 5.5, y 29.8, w 6.6, h 10.3: Portrait of Yoshua Bengio, man with grey hair and short beard, dark jacket, smiling (Head and shoulders, rectangular crop, fades into black at bottom, gold rule below)
- photo at x 12.1, y 30.7, w 7.3, h 9.4: Portrait of Yann LeCun, man with brown hair and dark-rimmed glasses, smiling, dark jacket (Head and shoulders, rectangular crop, fades into black)
- photo at x 18.9, y 30.1, w 7.6, h 10.1: Portrait of Geoffrey Hinton, older man with white hair, smiling, light shirt (Head and shoulders, rectangular crop, fades into black)
- photo at x 25.4, y 30.1, w 7.5, h 10: Portrait of Daphne Koller, woman with long brown hair, neutral expression (Head and shoulders, rectangular crop, fades into black)
- photo at x 4.8, y 49, w 7, h 10.3: Portrait of Jürgen Schmidhuber, man with grey hair, looking to side (Head and shoulders, rectangular crop, fades into black)
- photo at x 12.2, y 49.5, w 6.4, h 9.8: Portrait of Raquel Urtasun, woman with dark shoulder-length hair (Head and shoulders, rectangular crop, fades into black)
- photo at x 18.7, y 49.2, w 7.4, h 10: Portrait of Alvy Ray Smith, older man with white hair and white beard, dark suit (Head and shoulders, rectangular crop, fades into black)
- photo at x 26.2, y 49.5, w 6.1, h 9.7: Portrait of Abhay Parasnis, smiling man with short dark hair, dark jacket (Head and shoulders, rectangular crop, fades into black)
- photo at x 5, y 67.2, w 6.9, h 10.2: Portrait of Kim Libreri, man with short brown hair, neutral expression, dark top (Head and shoulders, rectangular crop, fades into black)
- photo at x 12.4, y 67.3, w 6, h 10: Portrait of Rommie Amaro, woman with curly dark hair, smiling, white top (Head and shoulders, rectangular crop, fades into black)
- photo at x 19.6, y 66.9, w 6, h 10.5: Portrait of Soumith Chintala, young man with short dark hair, dark jacket (Head and shoulders, rectangular crop, fades into black)
- photo at x 26.6, y 66.9, w 6, h 10.5: Portrait of Rose Yu, woman with long dark hair, smiling, light top (Head and shoulders, rectangular crop, fades into black)
- line at x 4.8, y 40.2, w 27.5, h 0.1 [#B08D4F]: Gold rule under first row of portraits (Thin 1 px horizontal line)
- line at x 4.8, y 59.2, w 27.5, h 0.1 [#B08D4F]: Gold rule under second row of portraits (Thin 1 px horizontal line)
- line at x 4.8, y 77.4, w 27.5, h 0.1 [#B08D4F]: Gold rule under third row of portraits (Thin 1 px horizontal line)
- body at x 5.2, y 41.2, w 6.2, h 2.4 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Yoshua Bengio / University of Montreal / Quebec AI Institute
- body at x 12.6, y 41.2, w 5.5, h 2.4 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Yann LeCun / Facebook / New York University
- body at x 19.4, y 41.2, w 5.8, h 3 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Geoffrey Hinton / University of Toronto / Google / Vector Institute
- body at x 26.8, y 41.2, w 4.7, h 3 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Daphne Koller / Insitro / Coursera / Stanford
- body at x 4.9, y 60.3, w 7, h 2.5 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Jϋrgen Schmidhuber / Dalle Molle Institute for / AI Research
- body at x 12.9, y 60.3, w 5.1, h 2.4 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Raquel Urtasun / University of Toronto
- body at x 19.9, y 60.4, w 4.8, h 2.5 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Alvy Ray Smith / Pixar / Altamira
- body at x 26.6, y 60.3, w 5, h 2.4 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Abhay Parasnis / Adobe
- body at x 6.3, y 78.5, w 4.6, h 2.4 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Kim Libreri / Epic Games
- body at x 12.5, y 78.5, w 6.2, h 3.7 [DIN Pro Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Rommie Amaro / University of / California, San Diego
- body at x 19.7, y 78.5, w 5.6, h 2.4 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Soumith Chintala / Facebook
- body at x 26.2, y 78.5, w 6.2, h 3.7 [DIN Pro Medium and Regular, sans-serif; font size 1.3% of slide height; #FFFFFF; center aligned]: Rose Yu / University of / California, San Diego
- shape at x 36.4, y 33, w 8.4, h 9.7 [#8A6E3E]: Talk tile AI, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient lighter at top)
- shape at x 45.8, y 33, w 8.4, h 9.7 [#8A6E3E]: Talk tile 5G, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 55.1, y 33, w 8.4, h 9.7 [#8A6E3E]: Talk tile IOT & EDGE, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 36.4, y 50, w 8.4, h 9.7 [#7A6236]: Talk tile QUANTUM COMPUTING, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 45.8, y 50, w 8.4, h 9.7 [#7A6236]: Talk tile SPEECH NLU RECOMMENDERS, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 55.1, y 50, w 8.4, h 9.7 [#7A6236]: Talk tile SELF-DRIVING CARS, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 36.4, y 67, w 8.4, h 9.7 [#5E4A28]: Talk tile CYBERSECURITY, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 45.8, y 67, w 8.4, h 9.7 [#5E4A28]: Talk tile DIGITAL TWINS, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- shape at x 55.1, y 67, w 8.4, h 9.7 [#5E4A28]: Talk tile ROBOTICS, gold gradient square (Sharp corners, soft drop shadow, brushed gold gradient)
- body at x 40.2, y 37.6, w 0.9, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: AI
- body at x 49.4, y 37.6, w 1.1, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: 5G
- body at x 56.8, y 37.6, w 5.1, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: IOT & EDGE
- body at x 37.9, y 53.6, w 6.9, h 3.6 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: QUANTUM / COMPUTING
- body at x 46.1, y 52.6, w 7.8, h 5.6 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: SPEECH / NLU / RECOMMENDERS
- body at x 56.1, y 53.6, w 6.6, h 3.6 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: SELF-DRIVING / CARS
- body at x 36.9, y 71.6, w 7.4, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: CYBERSECURITY
- body at x 46.6, y 71.6, w 6.6, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: DIGITAL TWINS
- body at x 57.1, y 71.6, w 4.5, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: ROBOTICS
- logo at x 68.2, y 30, w 4.6, h 2.3 [#FFFFFF]: Adobe logo, white (Monochrome white on black)
- logo at x 74.5, y 30.2, w 6.9, h 2 [#FFFFFF]: Alibaba Cloud logo, white (Monochrome white on black)
- logo at x 82.7, y 30.4, w 2.4, h 1.4 [#FFFFFF]: arm logo, white (Monochrome white on black)
- logo at x 86.9, y 30.2, w 3.1, h 1.8 [#FFFFFF]: Audi rings logo, white (Monochrome white on black)
- logo at x 91.7, y 30, w 2.5, h 2.7 [#FFFFFF]: aws logo, white (Monochrome white on black)
- logo at x 68.2, y 37.3, w 4.4, h 2.4 [#FFFFFF]: Baidu logo, white (Monochrome white on black)
- logo at x 73.9, y 37.3, w 3.2, h 2.9 [#FFFFFF]: Baker Hughes logo, white (Monochrome white on black)
- logo at x 78.5, y 37.3, w 2.1, h 3.6 [#FFFFFF]: Bayer logo, white (Monochrome white on black)
- logo at x 81.7, y 37.3, w 2.1, h 3.6 [#FFFFFF]: BMW logo, white (Monochrome white on black)
- logo at x 85.2, y 37.3, w 1.9, h 3.9 [#FFFFFF]: Epic Games logo, white (Monochrome white on black)
- logo at x 88.4, y 38, w 5.7, h 2 [#FFFFFF]: Ericsson logo, white (Monochrome white on black)
- logo at x 68.2, y 45.5, w 6.1, h 2 [#FFFFFF]: Facebook wordmark, white (Monochrome white on black)
- logo at x 76.4, y 45.7, w 3.7, h 2.4 [#FFFFFF]: Ford logo, white (Monochrome white on black)
- logo at x 82.2, y 45.8, w 3.7, h 2.3 [#FFFFFF]: Google wordmark, white (Monochrome white on black)
- logo at x 87.2, y 44, w 2.9, h 5.2 [#FFFFFF]: Industrial Light & Magic logo, white (Monochrome white on black)
- logo at x 91.6, y 45.2, w 2.6, h 3.9 [#FFFFFF]: Kroger logo, white (Monochrome white on black)
- logo at x 68.2, y 53.9, w 5.5, h 2.2 [#FFFFFF]: Microsoft wordmark and four-square mark, white (Monochrome white on black)
- logo at x 75.1, y 53.3, w 2.2, h 3.8 [#FFFFFF]: NASA meatball logo, white (Monochrome white on black)
- logo at x 79.1, y 53.9, w 3.2, h 2.2 [#FFFFFF]: NTT logo, white (Monochrome white on black)
- logo at x 83.6, y 53.9, w 4.9, h 2.3 [#FFFFFF]: Oracle Cloud Infrastructure logo, white (Monochrome white on black)
- logo at x 89.8, y 54, w 4.4, h 2 [#FFFFFF]: PayPal logo, white (Monochrome white on black)
- logo at x 68.3, y 61.5, w 1.4, h 3.1 [#FFFFFF]: Pinterest mark, white (Monochrome white on black)
- logo at x 70.8, y 61.6, w 2.8, h 2.8 [#FFFFFF]: Pfizer logo, white (Monochrome white on black)
- logo at x 74.9, y 62.5, w 4.9, h 1.2 [#FFFFFF]: PIXAR wordmark, white (Monochrome white on black)
- logo at x 80.7, y 62, w 4.8, h 2 [#FFFFFF]: Red Hat logo, white (Monochrome white on black)
- logo at x 86.3, y 61.3, w 4.8, h 3.1 [#FFFFFF]: Siemens Healthineers logo, white (Monochrome white on black)
- logo at x 92, y 61.3, w 2, h 3.3 [#FFFFFF]: Snapchat ghost mark, white (Monochrome white on black)
- logo at x 68.4, y 69.8, w 4.2, h 2.3 [#FFFFFF]: Spotify logo, white (Monochrome white on black)
- logo at x 74.2, y 70, w 6.5, h 2 [#FFFFFF]: Tencent Cloud logo, white (Monochrome white on black)
- logo at x 82.3, y 70.2, w 3.5, h 1.8 [#FFFFFF]: TESCO logo, white (Monochrome white on black)
- logo at x 87.4, y 69.3, w 2.7, h 3.4 [#FFFFFF]: TSMC logo, white (Monochrome white on black)
- logo at x 92.2, y 69.8, w 1.7, h 2.6 [#FFFFFF]: Twitter bird mark, white (Monochrome white on black)
- logo at x 68.4, y 77.3, w 4.7, h 2 [#FFFFFF]: verizon logo, white (Monochrome white on black)
- logo at x 75, y 77.8, w 4.4, h 1.3 [#FFFFFF]: VMware logo, white (Monochrome white on black)
- logo at x 81.5, y 76.6, w 2, h 3.6 [#FFFFFF]: Volkswagen roundel logo, white (Monochrome white on black)
- logo at x 84.7, y 77.3, w 5.2, h 2.2 [#FFFFFF]: Walmart logo, white (Monochrome white on black)
- logo at x 91.4, y 77, w 2.7, h 2.5 [#FFFFFF]: WELLS FARGO logo, white (Monochrome white on black)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 36.4, y 67.0, w 8.4, h 9.7: 16 by 11 pixels
- image at x 45.8, y 67.0, w 8.4, h 9.7: 8 by 6 pixels
- image at x 55.1, y 67.0, w 8.4, h 9.7: 4 by 3 pixels
- image at x 36.4, y 33.0, w 8.4, h 9.7: 1005 by 658 pixels
- image at x 45.8, y 33.0, w 8.4, h 9.7: 1005 by 658 pixels
- image at x 55.1, y 33.0, w 8.4, h 9.7: 1005 by 658 pixels
- image at x 36.4, y 50.0, w 8.4, h 9.7: 63 by 42 pixels
- image at x 45.8, y 50.0, w 8.4, h 9.7: 1004 by 658 pixels
- image at x 55.1, y 50.0, w 8.4, h 9.7: 32 by 21 pixels
- image at x 18.9, y 30.1, w 7.6, h 10.1: 442 by 330 pixels
- image at x 25.4, y 30.1, w 7.5, h 10.0: 431 by 326 pixels
- image at x 18.7, y 49.2, w 7.4, h 10.0: 440 by 339 pixels
- image at x 4.8, y 49.0, w 7.0, h 10.3: 414 by 340 pixels
- image at x 5.0, y 67.2, w 6.9, h 10.2: 415 by 344 pixels
- image at x 12.1, y 30.7, w 7.3, h 9.4: 420 by 305 pixels
- image at x 5.5, y 29.8, w 6.6, h 10.3: 397 by 346 pixels
- image at x 19.6, y 66.9, w 6.0, h 10.5: 360 by 355 pixels
- image at x 26.6, y 66.9, w 6.0, h 10.5: 360 by 354 pixels
- image at x 12.2, y 49.5, w 6.4, h 9.8: 383 by 328 pixels
- image at x 12.4, y 67.3, w 6.0, h 10.0: 358 by 339 pixels
- image at x 26.2, y 49.5, w 6.1, h 9.7: 369 by 330 pixels
- image at x 73.7, y 36.3, w 3.6, h 5.2: 428 by 349 pixels
- image at x 75.8, y 45.2, w 4.9, h 3.7: 712 by 300 pixels
- image at x 87.2, y 44.0, w 2.9, h 5.2: 250 by 250 pixels
- image at x 80.8, y 61.4, w 4.6, h 3.3: 303 by 121 pixels
- image at x 68.2, y 76.9, w 5.0, h 2.9: 242 by 78 pixels
- image at x 68.2, y 54.0, w 5.4, h 2.3: 386 by 92 pixels
- image at x 68.1, y 37.2, w 4.5, h 2.7: 267 by 92 pixels
- image at x 86.6, y 29.4, w 3.5, h 3.5: 228 by 128 pixels
- image at x 74.5, y 30.4, w 6.8, h 1.7: 1149 by 165 pixels
- image at x 88.5, y 38.0, w 5.7, h 2.0: 825 by 166 pixels
- image at x 68.0, y 46.1, w 6.3, h 1.8: 377 by 61 pixels
- image at x 74.6, y 62.2, w 5.2, h 2.1: 212 by 48 pixels
- image at x 91.7, y 69.0, w 2.5, h 4.4: 198 by 198 pixels
- image at x 74.2, y 70.2, w 6.4, h 1.7: 927 by 138 pixels
- image at x 91.6, y 45.2, w 2.6, h 3.9: 210 by 176 pixels
- image at x 70.7, y 61.3, w 3.0, h 3.4: 218 by 138 pixels
- image at x 84.7, y 77.6, w 5.1, h 2.0: 408 by 89 pixels
- text at x 32.8, y 7.9, w 34.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: FOR THE DA VINCIS OF OUR TIME
- text at x 12.3, y 24.1, w 12.3, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: SCIENTISTS AT GTC
- text at x 44.9, y 24.1, w 8.8, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: TALKS AT GTC
- text at x 75.9, y 24.1, w 10.7, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: LEADERS AT GTC
- text at x 40.2, y 37.6, w 0.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AI
- text at x 49.4, y 37.6, w 1.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5G
- text at x 56.8, y 37.6, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: IOT & EDGE
- text at x 48.1, y 52.6, w 3.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SPEECH
- text at x 38.3, y 53.6, w 4.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: QUANTUM
- text at x 56.1, y 53.6, w 6.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SELF-DRIVING
- text at x 49.0, y 54.5, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NLU
- text at x 5.8, y 41.2, w 4.7, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Yoshua Bengio
- text at x 13.4, y 41.2, w 3.8, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Yann LeCun
- text at x 19.7, y 41.2, w 5.1, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Geoffrey Hinton
- text at x 26.8, y 41.2, w 4.7, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Daphne Koller
- text at x 37.9, y 55.5, w 5.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: COMPUTING
- text at x 58.1, y 55.5, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: CARS
- text at x 46.1, y 56.5, w 7.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: RECOMMENDERS
- text at x 5.2, y 42.6, w 6.2, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: University of Montreal
- text at x 14.0, y 42.6, w 2.6, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Facebook
- text at x 19.4, y 42.6, w 5.8, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: University of Toronto
- text at x 28.2, y 42.6, w 1.8, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Insitro
- text at x 5.6, y 43.8, w 5.2, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Quebec AI Institute
- text at x 12.6, y 43.8, w 5.5, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: New York University
- text at x 21.3, y 43.8, w 1.9, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Google
- text at x 27.8, y 43.8, w 2.6, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Coursera
- text at x 20.2, y 45.0, w 4.2, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Vector Institute
- text at x 28.0, y 45.0, w 2.3, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Stanford
- text at x 36.9, y 71.6, w 7.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: CYBERSECURITY
- text at x 46.6, y 71.6, w 6.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DIGITAL TWINS
- text at x 57.1, y 71.6, w 4.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ROBOTICS
- text at x 4.9, y 60.3, w 7.0, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Jϋrgen Schmidhuber
- text at x 12.9, y 60.3, w 5.1, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Raquel Urtasun
- text at x 19.9, y 60.4, w 4.8, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Alvy Ray Smith
- text at x 26.6, y 60.3, w 5.0, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Abhay Parasnis
- text at x 5.1, y 61.7, w 6.7, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Dalle Molle Institute for
- text at x 12.6, y 61.7, w 5.7, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: University of Toronto
- text at x 21.5, y 61.8, w 1.4, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Pixar
- text at x 28.3, y 61.7, w 1.7, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Adobe
- text at x 6.6, y 62.9, w 3.3, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: AI Research
- text at x 21.1, y 63.0, w 2.4, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Altamira
- text at x 6.3, y 78.5, w 3.7, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Kim Libreri
- text at x 12.9, y 78.5, w 5.0, h 1.3 [DINPro-Regular; font size 1.30; #FFFFFF]: Rommie Amaro
- text at x 19.7, y 78.5, w 5.6, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Soumith Chintala
- text at x 27.8, y 78.5, w 2.6, h 1.3 [DINPro-Medium; font size 1.30; #FFFFFF]: Rose Yu
- text at x 6.5, y 79.9, w 3.3, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Epic Games
- text at x 13.7, y 79.9, w 3.4, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: University of
- text at x 21.2, y 79.9, w 2.6, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: Facebook
- text at x 27.4, y 79.9, w 3.6, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: University of
- text at x 12.5, y 81.1, w 5.8, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: California, San Diego
- text at x 26.2, y 81.1, w 5.8, h 1.1 [DINPro-Regular; font size 1.11; #FFFFFF]: California, San Diego

### Slide 7

**Text**

Black Myth: Wukong by Game Science

**Layout**

Full-bleed single photograph covering the entire slide with no title, body text or grid. The only text is a small italic caption in the bottom-left corner, left-aligned at about 3.9% from the left edge and about 95% down, with no visible slide number or footer.

**Visuals**

One full-bleed photograph (a rendered 3D still of the character Sun Wukong from Black Myth: Wukong by Game Science). Subject: a monkey-faced warrior with dark fur on the cheeks, jaw and neck, shown in left-facing profile, brow furrowed, eye looking left past the frame. He wears a dark, worn, riveted metal shoulder pauldron on the right side of the frame, and his clenched right fist is raised in the lower centre-right foreground, slightly out of focus. Action: he is mid-motion, turning to the left, with small dark debris specks scattered across the air. Composition: tight medium close-up cropped at the top of the head and at the bottom of the chest, subject placed right of centre with the face in the upper-left third. Lighting: warm, soft, directional light on the face and armour. Dominant colours: warm browns and umber on the left and in the face, dark charcoal-brown in the armour and fur, and pale grey-white bokeh at the upper right and left edges. The image is full-bleed, uncropped at the edges of the slide, with no overlay or tint, and the photograph is shown at 16:9.

**Design**

Background: Full-bleed photograph of the character with a blurred brown and grey-white backdrop; underneath it lies a solid white (#FFFFFF) fill that is fully covered. No visible title, body or accent typography; the slide is a pure image. The caption is set in a small sans-serif italic (DIN Pro Regular style), white (#FFFFFF), at roughly 1.5% of slide height. The photograph itself carries the colour palette: warm brown #6B4A32 and dark umber #2B1D14 with grey-white #D8DCE0 highlights. No shapes, rules, rounded corners, shadows or gradients are present on the slide.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide solid background fill, fully covered by the photograph (Rectangle, no stroke, no corner radius, no shadow, opacity 100%, lies behind the photograph and is not visible.)
- photo at x 0, y 0, w 100, h 100 [#6B4A32]: Full-bleed rendered still of Sun Wukong from Black Myth: Wukong by Game Science: left-facing monkey-faced warrior in close-up, dark pauldron armour, clenched fist raised at lower right, blurred brown and grey-white backdrop, airborne dark specks (Placed image 3840 by 2160 px (16:9), covers the whole slide edge to edge, not boxed, no border, no overlay or tint, no rotation, rectangular crop with no rounded corners, no shadow. Dominant colour is warm brown with dark umber and grey-white highlights.)
- caption at x 3.9, y 95.2, w 14, h 1.5 [DINPro-Regular, italic, sentence case, normal letter-spacing; font size 1.48% of slide height; #FFFFFF; left aligned]: Black Myth: Wukong by Game Science (Single line caption, sits over the darker lower-left part of the photograph, no background box, no shadow; set in a small sans-serif italic.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1280 by 720 pixels (covers the slide)
- text at x 3.9, y 95.2, w 14.0, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Black Myth: Wukong by Game Science

### Slide 8

**Text**

NVIDIA OMNIVERSE / AI / MESHES / GEOMETRY / ANIMATION / SHADING / MOTION / NURBS / RTX / RENDERING / LIGHTS / PHYSICS / AI / Path-Tracing / USD / Materials / Physics

**Layout**

A single centred composition on a black-to-charcoal field. The title sits centred near the top, about 8% from the top edge. A large wireframe sphere is centred horizontally, with a small inset photo overlapping its right edge. A row of five centred icons with captions sits below the sphere, near the lower third, with a soft shadow beneath. There is no footer and no slide number.

**Visuals**

Illustration: a translucent teal-green wireframe sphere (about 24% of slide width, 43% of slide height) with a glowing node network. Inside it is a silver-white humanoid robot bust, centre-lit, with a faceted dark teal background. Twelve small gold-bracketed keyword labels sit on the sphere: AI, MESHES, GEOMETRY, ANIMATION, SHADING, MOTION, NURBS, RTX, RENDERING, LIGHTS, PHYSICS. RTX and PHYSICS are set larger than the others. Inset photograph (boxed, sharp square corners, thin light-grey border about 1px, lower-right of the sphere, overlapping its edge): two white-and-blue armoured humanoid robots standing side by side in a blue-lit corridor, one white on the left and one blue on the right, looking forward. Lighting is cool blue. Icon row: five circular icons about 2.5% of slide width each. AI: dark teal sphere with a constellation of dots. Path-Tracing: a round photo of colourful pastel spheres. USD: a solid blue disc with a white USD logo. Materials: a round photo of grey and tan spheres. Physics: a round photo of a bright orange fire-like burst on black. Below the icons is a soft dark elliptical shadow.

**Design**

Background is a near-black #000000 at the top fading to dark charcoal #2A2A2A at the bottom, with a faint dark grey floor texture. Title is white #FFFFFF in DIN Pro Bold, all caps, about 4.1% of slide height, with normal tracking. Icon captions are white #FFFFFF in DIN Pro Regular, about 1.2% of slide height. Sphere labels are white with gold brackets #D4A93A. Sphere wireframe is teal-green #3A7A78 with pale mint nodes #9FE3C8. Shapes have no corner radius except the inset photo, which has square corners. The icons are circular. The shadow is a soft dark ellipse with blur.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark background photograph (textured dark floor and black backdrop) (Covers the slide, 3840 by 2160 pixels, behind all other elements; dominant colour black #000000 to charcoal #2A2A2A)
- shape at x 40, y 83.1, w 21.5, h 1.8: Ground shadow ellipse under the icon row (Dark soft ellipse, blurred, black at about 60% opacity)
- illustration at x 37.9, y 25.6, w 23.9, h 43: Translucent wireframe sphere with node network and central robot bust (Teal-green #3A7A78 translucent faces, pale mint #9FE3C8 nodes and lines, faint gold-grey outline edges; the robot bust is silver-white at about x 47.3, y 40.4, w 7.0, h 14.2 and overlaps the sphere centre)
- photo at x 59.9, y 39.6, w 8.1, h 14.4: Inset photograph of two armoured humanoid robots in a blue-lit corridor (Square-cornered box with a 1px light grey border, overlapping the lower-right edge of the sphere; cool blue lighting, dominant colours blue #2F5FA8 and white #E8ECF2)
- title at x 39.8, y 7.9, w 20.5, h 4.1 [DIN Pro Bold, all caps, normal tracking; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA OMNIVERSE
- label at x 50.6, y 30.5, w 1.1, h 1.2 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: AI (Gold corner brackets #D4A93A around the word)
- label at x 54.9, y 32.7, w 2.5, h 1.2 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: MESHES (Gold corner brackets #D4A93A)
- label at x 52.7, y 39.2, w 2.8, h 1.1 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: GEOMETRY (Gold corner brackets #D4A93A)
- label at x 38.9, y 43.5, w 3.4, h 1.2 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: ANIMATION (Gold corner brackets #D4A93A)
- label at x 47.5, y 43.6, w 2.3, h 1.1 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: SHADING (Gold corner brackets #D4A93A, partly obscured by the robot)
- label at x 56.8, y 43.5, w 2.4, h 1.1 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: MOTION (Gold corner brackets #D4A93A)
- label at x 43.3, y 51.5, w 1.9, h 1.1 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: NURBS (Gold corner brackets #D4A93A)
- label at x 56.4, y 52.5, w 2.7, h 1.9 [DIN Pro Medium, all caps, wide tracking; font size 2% of slide height; #FFFFFF; center aligned]: RTX (Gold corner brackets #D4A93A)
- label at x 38.9, y 54.8, w 3.3, h 1.1 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: RENDERING (Gold corner brackets #D4A93A)
- label at x 56.9, y 58.1, w 2.4, h 1.2 [DIN Pro Bold, all caps, wide tracking; font size 0.9% of slide height; #FFFFFF; center aligned]: LIGHTS (Gold corner brackets #D4A93A)
- label at x 49.5, y 59.7, w 4.5, h 1.7 [DIN Pro Medium, all caps, wide tracking; font size 2% of slide height; #FFFFFF; center aligned]: PHYSICS (Gold corner brackets #D4A93A)
- icon at x 41.05, y 72.2, w 2.5, h 4.4: AI icon: dark teal sphere with a constellation of dots (Circle, dominant colour teal #1E5F6B)
- icon at x 44.8, y 72.2, w 2.5, h 4.4: Path-Tracing icon: round photo of colourful pastel spheres (Circle, dominant colours pink #D9829B, yellow #E8C56B, teal #4E9C9A)
- logo at x 48.6, y 72.2, w 2.5, h 4.4: USD logo icon: white USD mark on a solid blue disc (Circle, dominant fill blue #1F6FD1)
- icon at x 52.4, y 72.2, w 2.5, h 4.4: Materials icon: round photo of grey and tan spheres (Circle, dominant colours grey #7A7A7A and tan #A88C6A on dark #222222)
- icon at x 56.3, y 72.2, w 2.5, h 4.4: Physics icon: round photo of an orange fire-like burst on black (Circle, dominant colours orange #F0A030 and black #000000)
- body at x 42, y 77.1, w 0.6, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: AI
- body at x 44.1, y 77.1, w 4, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Path-Tracing
- body at x 49.2, y 77.1, w 1.4, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: USD
- body at x 52.2, y 77.1, w 2.9, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Materials
- body at x 56.4, y 77.1, w 2.3, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Physics

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 39.8, y 7.9, w 20.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA OMNIVERSE
- text at x 42.0, y 77.1, w 0.6, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: AI
- text at x 44.1, y 77.1, w 4.0, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Path-Tracing
- text at x 49.2, y 77.1, w 1.4, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: USD
- text at x 52.2, y 77.1, w 2.9, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Materials
- text at x 56.4, y 77.1, w 2.3, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Physics

### Slide 9

**Text**

NVIDIA OMNIVERSE
ANIMATION
MESHES
GEOMETRY
MOTION
NURBS
RENDERING
RTX
LIGHTS
PHYSICS
AI
AI
Path-Tracing
USD
Materials
Physics

**Layout**

Centred composition on a black-to-charcoal studio background. The title sits at the top centre with no footer, page number or logo. Three stacked square photo thumbnails sit in a left column, joined by double-headed gold arrows to a large central sphere. One smaller square photo sits at the right edge of the sphere, and a row of five small round icons with labels is centred below the sphere.

**Visuals**

Full-bleed dark studio photograph of a grey floor and black backdrop, lit from above, forming the background. Left column: three square boxed photographs with thin light-grey borders and slightly rounded corners. Top: a grey monochrome sculpted humanoid head and shoulders on a dark background. Middle: a purple and copper-visored armoured figure facing front, lit from the right. Bottom: a grey metallic circular turntable or device inside a machine-like enclosure with bright highlights. Three gold (#C8A24A) double-headed arrows connect each left thumbnail to the sphere: the top arrow runs diagonally from the top thumbnail to the sphere's upper-left, the middle arrow is horizontal, and the bottom arrow runs diagonally from the sphere's lower-left to the bottom thumbnail. Central illustration: a translucent wireframe sphere with teal and dark-green faceted surfaces, pale green and white network nodes and lines, and a white-and-gold armoured humanoid figure at its centre. Gold-bracketed labels are placed on the sphere: AI (top), MESHES (upper right), GEOMETRY (right of centre), ANIMATION (left), REFLECTIONS (centre, blurred), MOTION (right), NURBS (lower left), RENDERING (lower left), RTX (lower right, larger), LIGHTS (lower right), PHYSICS (bottom, larger). Right of the sphere: a boxed photograph with light-grey border showing two armoured figures standing side by side, one white and one blue with glossy armour, in a blue-lit corridor. Bottom centre: a row of five round icons with labels beneath: AI (dark teal starfield sphere), Path-Tracing (multicoloured spheres on dark ground), USD (blue circle with white USD logo), Materials (grey and brown spheres), Physics (orange fire-like burst on black).

**Design**

Background: Full-bleed dark photograph: near-black (#000000) at top fading to charcoal grey (#2A2A2A) with a brushed concrete floor texture at the bottom.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#101010]: Full-bleed dark studio background photograph of a black backdrop and grey textured floor (Covers the whole slide, behind everything; floor texture visible in lower third.)
- title at x 39.8, y 7.9, w 20.5, h 4.1 [DIN Pro, Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA OMNIVERSE
- photo at x 15.1, y 21.5, w 6.65, h 11.8 [#5A5F66]: Photograph of a grey monochrome sculpted humanoid head and shoulders in a dark studio (Square box with thin light-grey border and slightly rounded corners.)
- photo at x 15.1, y 41.1, w 6.65, h 11.7 [#6B4A8A]: Photograph of a purple and copper-visored armoured figure facing front (Square box with thin light-grey border and slightly rounded corners.)
- photo at x 15.1, y 60.4, w 6.65, h 11.8 [#7D8A93]: Photograph of a grey metallic circular device inside a machine enclosure (Square box with thin light-grey border and slightly rounded corners.)
- line at x 25, y 27.6, w 9.35, h 9.2 [#C8A24A]: Gold double-headed arrow from top-left thumbnail to sphere upper-left (Thin stroke about 0.2% of slide width, arrowheads at both ends.)
- line at x 25, y 46.8, w 9.35, h 0.2 [#C8A24A]: Gold horizontal double-headed arrow from middle thumbnail to sphere (Thin stroke, arrowheads at both ends.)
- line at x 25, y 56.7, w 9.35, h 9.5 [#C8A24A]: Gold double-headed arrow from sphere lower-left to bottom-left thumbnail (Thin stroke, arrowheads at both ends.)
- illustration at x 37.9, y 25.6, w 23.8, h 43.1 [#1F3B3F]: Translucent wireframe sphere with teal faceted surfaces, green and white network nodes, a central white and gold armoured humanoid figure, and gold-bracketed labels ANIMATION, MESHES, GEOMETRY, REFLECTIONS, MOTION, NURBS, RENDERING, RTX, LIGHTS, PHYSICS and AI (Sphere outline in pale gold-grey wireframe; labels are small gold-bracketed white caps, RTX and PHYSICS larger; overlaps the right photograph at its right edge.)
- photo at x 59.9, y 39.6, w 8, h 14.2 [#2B4A7A]: Photograph of two armoured figures standing side by side, one white and one glossy blue, in a blue-lit corridor (Square box with thin light-grey border, slightly rounded corners; overlaps the right edge of the sphere.)
- icon at x 41.05, y 72.2, w 2.5, h 4.4 [#1C4A55]: AI icon: dark teal starfield sphere with constellation lines (Round icon with thin light edge.)
- icon at x 44.8, y 72.2, w 2.5, h 4.4 [#8A3B3B]: Path-Tracing icon: multicoloured spheres on dark ground (Round icon.)
- logo at x 48.6, y 72.2, w 2.5, h 4.4 [#1E5BD6]: USD logo icon: white USD mark on blue circle (Round blue icon with white USD lettering.)
- icon at x 52.4, y 72.2, w 2.5, h 4.4 [#6B5443]: Materials icon: grey and brown spheres (Round icon.)
- icon at x 56.3, y 72.2, w 2.5, h 4.4 [#C86A1E]: Physics icon: orange fiery burst on black (Round icon.)
- body at x 42, y 77.1, w 0.6, h 1.2 [DIN Pro, Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: AI
- body at x 44.1, y 77.1, w 4, h 1.2 [DIN Pro, Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Path-Tracing
- body at x 49.2, y 77.1, w 1.4, h 1.2 [DIN Pro, Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: USD
- body at x 52.2, y 77.1, w 2.9, h 1.2 [DIN Pro, Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Materials
- body at x 56.4, y 77.1, w 2.3, h 1.2 [DIN Pro, Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Physics

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 39.8, y 7.9, w 20.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA OMNIVERSE
- text at x 42.0, y 77.1, w 0.6, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: AI
- text at x 44.1, y 77.1, w 4.0, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Path-Tracing
- text at x 49.2, y 77.1, w 1.4, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: USD
- text at x 52.2, y 77.1, w 2.9, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Materials
- text at x 56.4, y 77.1, w 2.3, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Physics

### Slide 10

**Text**

NVIDIA OMNIVERSE
ANIMATION
RAYTRACE
NURBS
RENDERING
AI
GEOMETRY
MESHES
MOTION
RTX
LIGHTS
PHYSICS
AI
Path-Tracing
USD
Materials
Physics

**Layout**

Centered, symmetrical composition on a black stage. The title sits top-centre at about 8% from the top, with no footer or slide number. Three stacked square thumbnails sit at left, joined by gold arrows to a large wireframe sphere at centre-left. A small looping robot image sits right of the sphere, feeding a large circular photo at far right. A centred row of five circular icons with labels sits beneath the sphere. Margins are wide and the content band runs roughly 15% to 94% of the width.

**Visuals**

Photograph and illustration mix. (1) Three square thumbnails stacked at left, each about 6.7% wide with rounded corners and a thin grey border. Top: a grey monochrome sculpted head and torso of a faceless figure on dark grey, front-facing, centred. Middle: a purple and copper-accented helmeted figure on a warm brown background, lit from the left. Bottom: a silver-grey mechanical turntable stage in a white studio, seen from an angle with a curved disc and rails. (2) Three gold thin-line double-headed arrows, each about 1 pixel stroke, linking the thumbnails to the sphere: one diagonal from top thumbnail to upper sphere edge, one horizontal from middle thumbnail to sphere, one diagonal from bottom thumbnail to lower sphere edge. (3) A large sphere, about 24% of the width, made of a faceted translucent wireframe mesh with teal and green glowing nodes and lines over a dark teal volumetric interior. A white and grey humanoid robot figure with a metallic sheen sits at the centre. Gold square bracket tags label the sphere: ANIMATION at left, RAYTRACE partly hidden behind the robot, NURBS at lower left, RENDERING at bottom left, AI at top, GEOMETRY at upper right, MESHES at upper right, MOTION at right, RTX larger at right, LIGHTS at lower right, and PHYSICS largest at bottom. The tags are white-gold with thin bracket corners. (4) A small square photo of two humanoid robots, one white and one blue, standing side by side in a dark blue studio, boxed with a thin gold outline. A thin gold ring of two curved arrows encircles it, with arrowheads at upper right and lower left. (5) A large circular photo, about 20% of the width, with a thin gold ring border. It shows a wooden table top with a tablet propped up displaying two small robots on a grid, a hand holding a stylus over the screen, two small robot figures standing on the table at upper left, a red coffee cup at lower left, a dark glossy surface and a plant in the upper right. Soft natural daylight from the window, warm wood and red tones. (6) A row of five circular icons, each about 2.5% wide: AI is a dark blue starfield sphere; Path-Tracing is a glossy multicolour sphere cluster; USD is a bright blue circle with a white stacked-layers logo and the letters USD; Materials is a cluster of grey and brown spheres; Physics is a golden glowing particle burst on black.

**Design**

Background: Near-black gradient, #000000 at top fading to #1F1F1F at the floor, with a grey studio floor texture and soft shadow. Dark, cinematic NVIDIA-style look on a near-black stage with a soft floor reflection. Title is white bold sans-serif, all caps, about 4.1% of slide height. Labels are white regular DIN-style sans-serif about 1.2% of slide height. Accents are gold #C8A24A for arrows, bracket tags and photo rings; the sphere uses teal #2A8C8C and mint green #7FD6B0 lines. Thumbnails and circle photos have thin gold or grey borders and rounded square corners, with no drop shadows. The floor has a faint grey gradient from #1A1A1A at the back to #000000 at the front, with a soft shadow beneath the sphere.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide dark studio background with grey floor and soft vignette (Background image covering the slide 3840 by 2160 px; a flat #FFFFFF fill sits beneath it and is hidden.)
- title at x 39.8, y 7.9, w 20.5, h 4.1 [DINPro-Bold, bold, all caps, sans-serif; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA OMNIVERSE
- photo at x 15.1, y 21.5, w 6.65, h 11.8 [#4A4A4A]: Grey monochrome sculpted faceless figure, head and torso, front-facing, in a rounded square thumbnail (Thin grey border, corner radius about 0.3% of width, no shadow.)
- photo at x 15.1, y 41.1, w 6.65, h 11.8 [#5B3E8C]: Purple and copper helmeted figure with a metallic faceplate, on warm brown background (Thin grey border, corner radius about 0.3% of width, no shadow.)
- photo at x 15.1, y 60.4, w 6.65, h 11.8 [#8FA3AD]: Silver-grey mechanical turntable stage in a white studio, seen at an angle (Thin grey border, corner radius about 0.3% of width, no shadow.)
- line at x 25, y 27.6, w 9.35, h 9.2 [#C8A24A]: Gold double-headed diagonal arrow from top thumbnail to sphere (About 1 px stroke, arrowheads at both ends.)
- line at x 25, y 46.8, w 9.35, h 0 [#C8A24A]: Gold double-headed horizontal arrow from middle thumbnail to sphere (About 1 px stroke, arrowheads at both ends.)
- line at x 25, y 56.7, w 9.35, h 9.5 [#C8A24A]: Gold double-headed diagonal arrow from bottom thumbnail to sphere (About 1 px stroke, arrowheads at both ends.)
- illustration at x 37.9, y 25.6, w 24.3, h 43.1 [#2A8C8C]: Large faceted translucent wireframe sphere with glowing teal and mint nodes and lines, a white humanoid robot at its centre, gold bracket tags with labels ANIMATION, RAYTRACE, NURBS, RENDERING, AI, GEOMETRY, MESHES, MOTION, RTX, LIGHTS and PHYSICS (Dark teal interior, thin gold outline on the sphere edge, labels in DIN Regular all caps about 0.9% of height, PHYSICS largest and RTX larger; RAYTRACE partly hidden behind the robot; no shadow.)
- photo at x 64, y 39.6, w 8.05, h 14.2 [#1E3A6B]: Two humanoid robots, one white and one blue, standing side by side in a dark blue studio (Boxed with thin gold outline; overlapped by a gold ring of two curved arrows with arrowheads at upper right and lower left.)
- shape at x 63.1, y 38.8, w 9.7, h 16 [#C8A24A]: Gold ring of two curved arrows encircling the small robot photo (Thin stroke about 1 px, no fill, arrowheads at upper right and lower left.)
- photo at x 74, y 29.2, w 19.8, h 35.3 [#8B5E3C]: Circular photo of a wooden table with a tablet showing two small robots on a grid, a hand holding a stylus, two robot figures on the table, a red coffee cup and a plant (Circular crop, thin gold ring border; soft daylight; warm wood and red tones.)
- icon at x 41.05, y 72.2, w 2.5, h 4.4 [#1B3A5C]: AI icon: dark blue starfield sphere (Circular.)
- icon at x 44.9, y 72.2, w 2.5, h 4.4 [#B5524A]: Path-Tracing icon: glossy multicolour sphere cluster (Circular.)
- logo at x 48.6, y 72.2, w 2.45, h 4.4 [#1E6FD9]: USD logo: white stacked-layers mark with the letters USD on a bright blue circle (Circular.)
- icon at x 52.4, y 72.2, w 2.5, h 4.4 [#7A6A5A]: Materials icon: cluster of grey and brown spheres (Circular.)
- icon at x 56.3, y 72.2, w 2.5, h 4.4 [#D9A441]: Physics icon: golden glowing particle burst on black (Circular.)
- caption at x 42, y 77.1, w 0.6, h 1.2 [DINPro-Regular, regular weight, sans-serif; font size 1.24% of slide height; #FFFFFF; center aligned]: AI
- caption at x 44.1, y 77.1, w 4, h 1.2 [DINPro-Regular, regular weight, sans-serif; font size 1.24% of slide height; #FFFFFF; center aligned]: Path-Tracing
- caption at x 49.2, y 77.1, w 1.4, h 1.2 [DINPro-Regular, regular weight, sans-serif; font size 1.24% of slide height; #FFFFFF; center aligned]: USD
- caption at x 52.2, y 77.1, w 2.9, h 1.2 [DINPro-Regular, regular weight, sans-serif; font size 1.24% of slide height; #FFFFFF; center aligned]: Materials
- caption at x 56.4, y 77.1, w 2.3, h 1.2 [DINPro-Regular, regular weight, sans-serif; font size 1.24% of slide height; #FFFFFF; center aligned]: Physics

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 39.8, y 7.9, w 20.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA OMNIVERSE
- text at x 42.0, y 77.1, w 0.6, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: AI
- text at x 44.1, y 77.1, w 4.0, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Path-Tracing
- text at x 49.2, y 77.1, w 1.4, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: USD
- text at x 52.2, y 77.1, w 2.9, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Materials
- text at x 56.4, y 77.1, w 2.3, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Physics

### Slide 11

**Text**

_(no text on this slide)_

**Layout**

Full-bleed single photograph covering the entire slide with no title, body text, footer or slide number; the composition places a sculpture in the centre-left, a shadow on the right wall, and small crates at bottom right and a cart at bottom left.

**Visuals**

Photograph (rendered 3D-style image of an interior corner room). Subject: a tall freestanding sculptural assemblage of everyday objects (paint cans, a brass trophy-like vase, a guitar-shaped disc, a red box, a cymbal-like disc, metal tins, tubes, a teapot-like shape, brushes and bottles) mounted on thin black rods on three legs, standing in front of the room corner. On the right wall a large dark silhouette shadow of a dancer with both arms raised overhead, body leaning, one leg extended down toward the floor. At bottom left a dark metal wire cart/crate holding a tilted tin with a small light glint; at bottom right a stack of four weathered wooden crates. Composition: full-frame, wide landscape, the sculpture at about 36 to 54 percent of width, the shadow occupying the upper right quadrant, the corner of the room running vertically at about 49 percent of width. Lighting: a single warm directional light from the upper left casting the dancer shadow onto the right wall; soft bright pool of light on the floor at bottom left. Dominant colours: warm beige and tan wall tiles (about #B9A588), mid-brown floor (about #7A6A56), dark charcoal shadow (about #3A3430), with multicoloured accents of red, teal and gold on the sculpture. Not cropped; full-bleed; no overlay or tint.

**Design**

Background: Photograph of a beige tiled room corner (no solid background colour visible; base fill is #FFFFFF beneath the full-slide image). No text, no frame and no decoration. Photograph only, covering the slide edge to edge with no margins. The image has no borders, no rounded corners and no shadow of its own beyond the rendered shadow in the scene.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide white base fill, covering the slide (Solid rectangle, no stroke, no shadow, fully opaque; hidden behind the photograph.)
- photo at x 0, y 0, w 100, h 100 [#B9A588]: Rendered photograph of a tiled room corner with a sculpture of everyday objects on rods, a dancer silhouette shadow on the right wall, a wire cart with a tin at bottom left, and a stack of four wooden crates at bottom right (Full-bleed, uncropped, no border, no rounded corners, no shadow, no overlay or tint; 3840 by 2160 source image with a 2048 by 1152 copy covering the same area.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2048 by 1152 pixels (covers the slide)

### Slide 12

**Text**

COLLABORATING AND SIMULATING IN OMNIVERSE
Foster + Partners
INDUSTRIAL LIGHT & MAGIC
WPP
BMW
ECMWF
ERICSSON
ACTIVISION
Bentley
10M DESIGNERS | 20M CREATORS | 1M SCIENTISTS | 2M DEVELOPERS | 40M ENGINEERS
Image Courtesy of Industrial Light & Magic.
© and TM Lucasfilm Ltd. All Rights Reserved.

**Layout**

A centred title sits at the top, above a 4-column by 2-row grid of eight equal boxed photographs spanning about 4% to 96% of the slide width with even gutters. A centred tagline runs below the grid, and a small left-aligned credit block sits in the bottom-left corner; no slide number is visible.

**Visuals**

Eight rectangular photographs in a 4x2 grid, each boxed with a thin dark-grey edge and no corner radius. Top row, left to right: (1) Foster + Partners: aerial night view of illuminated glass skyscrapers with warm amber lights and a dark blue sky, with the white Foster + Partners wordmark over the upper area. (2) Industrial Light & Magic: a still of the Baby Yoda character beside a Mandalorian in a dark helmet in a dim control-room setting with small red and green indicator lights; white ILM emblem and wordmark at top centre. (3) WPP: a person seen from behind at a multi-monitor workstation in a forest of trees with autumn-coloured foliage, with a white WPP wordmark at top. (4) BMW: a grey monochrome factory interior showing car bodies hanging on an overhead conveyor, with a white BMW roundel at top right. Bottom row, left to right: (5) ECMWF: Earth seen from orbit, curved horizon with a thin blue atmosphere edge over dark clouds, with the white ECMWF logo at top. (6) Ericsson: a rendered city street intersection with a green bus, a crosswalk and red and yellow laser-like lines, with the white Ericsson wordmark and three-bar symbol at top. (7) Activision: a female character in tactical gear leaping through an orange fireball and debris, with the white Activision wordmark and registered mark at top. (8) Bentley: a rendered elevated railway station with a curved blue-grey roof and track in a light grey sky, with the white Bentley wordmark at top and a small white 'D-STAR' label near the right centre. Logos are white and sit over the photographs. Tagline: plain white uppercase text with vertical bar separators, no icons.

**Design**

Background: Black #000000 fading to dark grey #2A2A2A at the bottom edge. Dark cinematic look on a black background with a subtle dark grey gradient toward the bottom edge. Title in white bold DIN-style uppercase sans-serif, about 4.1% of slide height, with letter spacing. Tagline in white regular DIN-style uppercase sans-serif about 2.2% of slide height. Credits in grey #9A9A9A regular DIN-style sans-serif about 1.1% of slide height. Photos have thin dark edges and a soft dark shadow beneath the grid; no gradients on the photos themselves, and logos are white.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100: Full-slide background fill, black #000000 with dark grey #2A2A2A gradient toward bottom (Covers the slide; a white #FFFFFF fill is also present behind the photos but fully covered)
- title at x 23.5, y 7.9, w 53, h 4.1 [DINPro-Bold, sans-serif, bold, all caps, letter-spacing slightly open; font size 4.07% of slide height; #FFFFFF; center aligned]: COLLABORATING AND SIMULATING IN OMNIVERSE
- photo at x 3.9, y 21.8, w 21.7, h 29.2: Aerial night view of illuminated glass skyscrapers with the Foster + Partners wordmark over the top area (Boxed rectangle, thin dark grey edge, no radius, shadow below)
- logo at x 9.2, y 24.5, w 11.2, h 1.7 [#FFFFFF]: Foster + Partners wordmark, white (Overlaid on photo 1)
- photo at x 27.4, y 22, w 21.7, h 28.9: Baby Yoda beside a Mandalorian in a dim control room (Boxed rectangle, thin dark edge)
- logo at x 35.2, y 22.9, w 6.3, h 7.5 [#FFFFFF]: Industrial Light & Magic emblem and wordmark, white (Overlaid on photo 2 at top centre)
- photo at x 50.9, y 21.8, w 21.8, h 29.1: Person at multi-monitor workstation in autumn forest with WPP wordmark (Boxed rectangle, thin dark edge)
- logo at x 57.1, y 23.2, w 9.2, h 4.3 [#FFFFFF]: WPP wordmark, white (Overlaid on photo 3 at top)
- photo at x 74.4, y 21.8, w 21.8, h 29: Grey monochrome factory with car bodies on overhead conveyor with BMW roundel (Boxed rectangle, thin dark edge)
- logo at x 83.4, y 22.9, w 3.6, h 6.4 [#FFFFFF]: BMW roundel, white circle with black and white quadrants (Overlaid on photo 4 at top right)
- photo at x 3.9, y 54, w 21.8, h 29.1: Earth from orbit with curved blue horizon, with ECMWF logo (Boxed rectangle, thin dark edge)
- logo at x 10.2, y 56.2, w 9.3, h 2.8 [#FFFFFF]: ECMWF logo, white (Overlaid on photo 5 at top)
- photo at x 27.4, y 54, w 21.8, h 29.2: Rendered city intersection with green bus and laser-like lines, with Ericsson logo (Boxed rectangle, thin dark edge)
- logo at x 33.3, y 55.7, w 9.9, h 3.6 [#FFFFFF]: Ericsson wordmark and three-bar symbol, white (Overlaid on photo 6 at top)
- photo at x 50.9, y 54, w 21.7, h 29.2: Female character leaping through fireball and debris, with Activision logo (Boxed rectangle, thin dark edge)
- logo at x 57.3, y 55.4, w 8.8, h 4 [#FFFFFF]: Activision wordmark with registered mark, white (Overlaid on photo 7 at top)
- photo at x 74.3, y 54.1, w 21.8, h 29: Rendered elevated railway station with curved blue-grey roof, with Bentley logo (Boxed rectangle, thin dark edge)
- logo at x 81.4, y 56.3, w 7.6, h 3.2 [#FFFFFF]: Bentley wordmark with registered mark, white (Overlaid on photo 8 at top)
- title at x 23.5, y 7.9, w 53, h 4.1 [DINPro-Bold, sans-serif, bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: COLLABORATING AND SIMULATING IN OMNIVERSE
- body at x 22.6, y 89.4, w 54.9, h 2.2 [DINPro-Regular, sans-serif, regular, all caps; font size 2.22% of slide height; #FFFFFF; center aligned]: 10M DESIGNERS | 20M CREATORS | 1M SCIENTISTS | 2M DEVELOPERS | 40M ENGINEERS
- caption at x 3.9, y 93.2, w 12.6, h 2.3 [DINPro-Regular, sans-serif, regular; font size 1.11% of slide height; #9A9A9A; left aligned]: Image Courtesy of Industrial Light & Magic. / © and TM Lucasfilm Ltd. All Rights Reserved.

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 27.4, y 54.0, w 21.8, h 29.2: 1011 by 754 pixels
- image at x 50.9, y 54.0, w 21.7, h 29.2: 1216 by 913 pixels
- image at x 3.9, y 54.0, w 21.8, h 29.1: 1433 by 1077 pixels
- image at x 50.9, y 21.8, w 21.8, h 29.1: 1425 by 1056 pixels
- image at x 3.9, y 21.8, w 21.7, h 29.2: 1766 by 1332 pixels
- image at x 74.3, y 54.1, w 21.8, h 29.0: 1332 by 990 pixels
- image at x 74.4, y 21.8, w 21.8, h 29.0: 720 by 537 pixels
- image at x 27.4, y 22.0, w 21.7, h 28.9: 846 by 631 pixels
- image at x 50.8, y 21.7, w 21.8, h 21.7: 628 by 352 pixels
- image at x 50.8, y 21.7, w 21.8, h 21.7: 628 by 352 pixels
- image at x 74.4, y 21.7, w 21.8, h 15.4: 627 by 250 pixels
- image at x 74.4, y 21.7, w 21.8, h 15.4: 627 by 250 pixels
- image at x 27.4, y 21.7, w 21.8, h 13.4: 628 by 217 pixels
- image at x 27.4, y 21.7, w 21.8, h 13.4: 628 by 217 pixels
- image at x 50.8, y 54.0, w 21.8, h 13.2: 628 by 214 pixels
- image at x 50.8, y 54.0, w 21.8, h 13.2: 628 by 214 pixels
- image at x 74.3, y 54.1, w 21.8, h 11.7: 629 by 190 pixels
- image at x 74.3, y 54.1, w 21.8, h 11.7: 629 by 190 pixels
- image at x 27.3, y 54.0, w 21.8, h 11.7: 629 by 189 pixels
- image at x 27.3, y 54.0, w 21.8, h 11.7: 629 by 189 pixels
- image at x 3.9, y 21.7, w 21.8, h 11.6: 628 by 188 pixels
- image at x 3.9, y 21.7, w 21.8, h 11.6: 628 by 188 pixels
- image at x 3.9, y 54.0, w 21.7, h 5.7: 626 by 92 pixels
- image at x 3.9, y 54.0, w 21.7, h 5.7: 626 by 92 pixels
- image at x 35.2, y 22.9, w 6.3, h 7.5: 390 by 262 pixels
- image at x 57.1, y 23.2, w 9.2, h 4.3: 554 by 145 pixels
- image at x 57.3, y 55.4, w 8.8, h 4.0: 530 by 137 pixels
- image at x 33.3, y 55.7, w 9.9, h 3.6: 1500 by 304 pixels
- image at x 10.2, y 56.2, w 9.3, h 2.8: 305 by 52 pixels
- image at x 81.4, y 56.3, w 7.6, h 3.2: 722 by 172 pixels
- image at x 83.4, y 22.9, w 3.6, h 6.4: 434 by 434 pixels
- image at x 9.2, y 24.5, w 11.2, h 1.7: 670 by 58 pixels
- text at x 23.5, y 7.9, w 53.0, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: COLLABORATING AND SIMULATING IN OMNIVERSE
- text at x 22.6, y 89.4, w 54.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 10M DESIGNERS | 20M CREATORS | 1M SCIENTISTS | 2M DEVELOPERS | 40M ENGINEERS
- text at x 3.9, y 93.2, w 12.0, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: Image Courtesy of Industrial Light & Magic.
- text at x 3.9, y 94.4, w 12.6, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: © and TM Lucasfilm Ltd. All Rights Reserved.

### Slide 13

**Text**

_(no text on this slide)_

**Layout**

Full-bleed single image covering the entire slide with no text, title, footer or slide number; the composition is centred with the object slightly right of centre and empty grey space around it.

**Visuals**

Photograph-like 3D render: a polished dark-metal cylindrical object (two cylinders joined by a rounded U-shaped bridge, seen from a three-quarter angle with the left cylinder's flat circular face toward the viewer) with a bright yellow-orange fabric or sheet draped over and through the top of the object, its folds rippling. The object floats above a grey reflective floor casting a soft diffuse shadow below and to the lower-left. Lighting is soft studio lighting with specular highlights on the metal; dominant colours are charcoal/gunmetal grey, steel, and saturated yellow-orange (about #F5B400). The image is full-bleed, not cropped, not boxed, with no overlay or tint; the background grades from mid grey at left to near-black at upper right.

**Design**

Background: Radial grey gradient from #6B747C (centre-left) to #111214 (top-right), with a grey reflective floor at the bottom. No text or typography. Background is a neutral grey radial gradient from about #6B747C at the centre-left to near-black #111214 at the top-right corner. Metal is gunmetal #3A3E42 with highlights near #C8CCD0; yellow fabric about #F2B10F with darker ochre folds near #B07A08. Shapes are smooth rounded forms with no corner radii, outlines or shadows added beyond the rendered shadow on the floor.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed 3D-rendered image of a polished gunmetal twin-cylinder object wrapped by a yellow-orange fabric sheet, floating above a grey reflective floor with a soft shadow beneath it (Full-bleed, uncropped rectangular image covering the whole slide, no border, no overlay, no tint; object centred slightly right of centre, spanning roughly x 32% to 67% and y 23% to 76% of the slide; fabric drapes over the upper middle of the object; shadow falls beneath at roughly x 30% to 60%, y 70% to 100%.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3798 by 2137 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)

### Slide 14

_Long standard legal text on this slide is summarised, not transcribed; its exact words are in the measured list below._

**Text**

NVIDIA ISAAC DIGITAL TWIN IN OMNIVERSE

**Layout**

Single slide with no legal text. Content is arranged in one horizontal row across the middle band: a column of three thumbnails on the left, a large spherical digital twin in the centre, a small monitor icon, and a circular photograph on the right. The title sits centred at the top, in the upper band, with no subtitle, footer, logo or slide number visible. Margins are roughly 13 percent on the left and 12 percent on the right.

**Visuals**

Three small rounded-square photographs stacked vertically on the left, each linked by a gold double-headed arrow to the central sphere. Top: an aerial view of a factory floor with dark shelving units, purple crates and a blue vehicle. Middle: a white six-axis robot arm on a black surface with small coloured cubes at its base, shown in a studio close-up. Bottom: a yellow automated guided vehicle carrying a grey pallet top, shown from an angled view against a blue floor. Above the top photo sit three round black icons overlapping: the Blender logo, a stylised R (Revit-like) mark, and the 3ds Max logo. Centre: a large translucent sphere with a gold wireframe mesh, containing a rendered warehouse scene with a worker in orange hi-vis clothing and a blue wall, a grey cart, a blue pallet lift with a yellow AGV and a white robot arm, and a blue-yellow hazard floor marking. Right of the sphere: a small square black tile with a grey icon of four monitors above a user silhouette, ringed by a thin gold circle with two curved gold arrows. Far right: a circular photograph of a white and light-blue UR-style collaborative robot arm in a warehouse, with purple plastic crates stacked at the bottom right and two workers in orange hi-vis clothing in the background; the photo is cropped to a circle and has a soft grey-white light tone.

**Design**

Background: Black to dark grey gradient, #000000 at the top fading to about #2B2B2B at the bottom, with faint horizontal streaks near the lower third.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: full-bleed dark gradient background (fill covering slide, #000000 to #2B2B2B) (Vertical linear gradient, black top to dark grey bottom; faint streaks near the bottom third)
- title at x 27.3, y 7.9, w 45.4, h 4.1 [DIN Pro Bold, sans-serif, bold, capitals, slight letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA ISAAC DIGITAL TWIN IN OMNIVERSE
- photo at x 15.1, y 21.5, w 6.7, h 11.7 [#5A6470]: aerial view of factory floor with shelving and purple crates (Rounded corners about 1 percent of width; thin grey-gold border; boxed, not cropped to circle)
- logo at x 13.4, y 17.8, w 2.6, h 4.6 [#000000]: Blender logo icon (White logo on black circle, overlaps top-left corner of top photo and the R icon)
- logo at x 16.1, y 18.7, w 2, h 4.1 [#000000]: stylised R icon (Revit-like) (White R on black circle, overlaps Blender icon and above the top photo)
- logo at x 13.7, y 22.4, w 2.7, h 4.1 [#000000]: 3ds Max logo icon (White 3S mark on black circle, sits below the Blender icon and overlaps top photo edge)
- line at x 25, y 27.7, w 9.4, h 9.2 [#C9A227]: gold double-headed arrow from top photo to sphere (Thin gold line about 0.1 percent of height, arrowheads at both ends)
- photo at x 15.1, y 41.1, w 6.7, h 11.8 [#111111]: white six-axis robot arm on black surface with coloured cubes (Rounded corners, thin gold-grey border, boxed)
- line at x 25, y 46.8, w 9.4, h 0.3 [#C9A227]: gold horizontal double-headed arrow from middle photo to sphere (Thin gold line with arrowheads at both ends)
- photo at x 15.1, y 60.4, w 6.7, h 11.8 [#1F4E8C]: yellow automated guided vehicle carrying grey pallet top on blue floor (Rounded corners, thin gold-grey border, boxed)
- line at x 25, y 56.6, w 9.4, h 9.6 [#C9A227]: gold double-headed arrow from bottom photo to sphere (Thin gold line with arrowheads at both ends)
- illustration at x 37.9, y 25.6, w 24.2, h 43 [#D8D8D8]: translucent sphere with gold wireframe mesh containing rendered warehouse scene (worker in orange hi-vis, blue wall, grey cart, blue pallet lift with yellow AGV, white robot arm, hazard-striped floor) (Circular boundary; wireframe triangle mesh in gold over a semi-transparent grey-white sphere; the scene is clipped to the circle)
- shape at x 63.95, y 39.6, w 8.05, h 14.3 [#000000]: small square black tile with monitor icon (Black square with thin grey border; grey icon of four monitors above a grey user silhouette)
- shape at x 63.1, y 38.7, w 9.8, h 16.1 [#C9A227]: thin gold ring with two curved arrows around monitor tile (Thin gold circular stroke, with arrowheads at the upper-right and lower-left, circling the monitor tile)
- photo at x 73.9, y 29.1, w 19.9, h 35.5 [#E8EEF2]: collaborative robot arm (white and light-blue) in warehouse with purple crates and two workers in hi-vis (Circular crop, full circle, thin grey border; slight soft light; no overlay)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 27.3, y 7.9, w 45.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA ISAAC DIGITAL TWIN IN OMNIVERSE

### Slide 15

**Text**

PathTracing: 872/0 sp
(text is cut off at the right edge of the slide)

**Layout**

Full-bleed photograph with no title, body text or footer. The only text is a small render counter in the top-right corner, cut off at the right edge. The image fills the whole slide with no margins, and there is no slide number.

**Visuals**

One full-bleed photograph of the interior of an automotive assembly plant, shown in a one-point perspective view. Steel overhead conveyor gantries and trusses run along the left and right edges and across the ceiling, with a sawtooth truss roof and skylights. Yellow power and service conduits and hoses run along the ceiling and gantries. White robotic or tool arms hang from the ceiling at the upper left and centre. On the left, a black car with a light badge on its grille sits at the lower left edge. Magenta wire-mesh carts on blue bases stand on the left floor and along the mid-ground on both sides. On the right, red and white car bodies sit on the conveyor at the lower right, and a dark blue-black storage unit stands near the centre right. A dark grey rubber walkway runs diagonally across the lower right floor. The floor is polished grey concrete with bright specular reflections of the skylights. Lighting is diffuse daylight from the skylights and fluorescent strips, with a bright vanishing point at the far end. Dominant colours are steel grey, charcoal black, white, with yellow and magenta accents. The photograph is not cropped, boxed or tinted. A small white render counter overlays the top-right corner.

**Design**

Background: Full-bleed photograph of an industrial factory interior (grey and charcoal steel, white highlights), over a plain white #FFFFFF fill. Photographic, full-bleed, with no typographic design. The only text is a small white sans-serif render counter in the top-right corner, around 1% of slide height. No titles, rules or shapes are present. The slide is dark grey and steel-toned overall.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Plain white full-slide fill behind the photograph (Covers the whole slide; hidden by the photograph. No stroke, no shadow, no corner radius.)
- photo at x 0, y 0, w 100, h 100 [#4A4A4A]: Full-bleed photograph of the interior of a car assembly plant with overhead conveyor gantries, yellow conduits, magenta carts, parked car bodies and a polished concrete floor, one-point perspective (Rectangular, not cropped, not boxed, no overlay or tint. Covers the slide edge to edge. A second image layer at the same full-slide size (3840 by 2160 px) sits under or with the main image, as recorded in the file measurements.)
- caption at x 93.5, y 0, w 6.5, h 2 [Arial-like sans-serif, regular weight, no italics, no capitals, normal letter-spacing; font size 1% of slide height; #FFFFFF; right aligned]: PathTracing: 872/0 sp (Render counter overlay printed over the photograph. The word is cut off at the right edge of the slide, so the full text is not visible. Text is set on the photograph with no background box.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2328 by 1309 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)

### Slide 16

**Text**

CONNECTING AND CREATING WITH OMNIVERSE
SOFTWARE
Adobe
Autodesk
Bentley
Blender
CLO Virtual Fashion
esri
FOUNDRY
golaem
GRAPHISOFT
ipolog
MathWorks
NETALLIED SYSTEMS
onshape
ParaView
PIXAR
Pixologic
makers of ZBRUSH
REALLUSION
Rhinoceros
SIDEFX
SOLIDWORKS
Trimble
UNREAL ENGINE
wrnch
SYSTEMS
ASUS
BOXX
CISCO
DELL Technologies
hp
Lenovo
PNY
SUPERMICRO
PIONEERS
BMW GROUP
ERICSSON
Foster + Partners
FRAMESTORE
IBI
Gensler
INDUSTRIAL LIGHT & MAGIC
KITESTRING
KPF
Lightcraft TECHNOLOGY
TANGENT
TURBOSQUID
W-B WOODS BAGOT
WPP
VOLVO

**Layout**

Three equal dark panels sit side by side in a row across the middle of the slide, spanning roughly x 3.8 to 96.2 percent and y 21.5 to 95.1 percent, with equal gutters of about 1.2 percent. The title is centred across the top at about y 7.9 percent, with empty space below it before the panels. Each panel has a centred uppercase heading near its top, and logos are arranged in grids: Software in three columns by seven rows (the last row has three logos centred), Systems in two columns by four rows, and Pioneers in three columns by five rows. There is no footer, slide number or source line.

**Visuals**

Logos and wordmarks only, all rendered in white or near white on black. Software: Adobe, Autodesk, Bentley (Advancing Infrastructure), Blender, CLO Virtual Fashion, esri (The Science of Where), FOUNDRY, golaem (human ex machina), GRAPHISOFT, ipolog, MathWorks, NETALLIED SYSTEMS, onshape, ParaView, PIXAR Animation Studios, Pixologic (makers of ZBRUSH), REALLUSION, Rhinoceros (design, model, present, analyze, realize), SideFX, SOLIDWORKS, Trimble, UNREAL ENGINE, wrnch. Systems: ASUS, BOXX, CISCO, DELL Technologies, hp, Lenovo (white box with black wordmark), PNY, SUPERMICRO (oval outline). Pioneers: BMW GROUP, ERICSSON, Foster + Partners, FRAMESTORE, IBI (outlined brackets), Gensler, Industrial Light & Magic, KITESTRING, KPF, Lightcraft Technology, TANGENT, TURBOSQUID, W-B Woods Bagot, WPP, VOLVO. A dark reflective studio floor with a soft shadow beneath the panels sits in the lower part of the image; it is a full-bleed photograph with no visible people, with a slightly lit centre and vignetted edges.

**Design**

Background: Full-bleed dark studio photograph, black (#000000) at top fading to dark grey (#1A1A1A) on a reflective floor. Black-and-charcoal presentation with white type and thin bronze panel borders. Background is near-black #000000 at the top, fading to dark grey #1A1A1A on the floor. Title is white (#FFFFFF) DIN Pro Bold, uppercase, about 4.07 percent of slide height. Section headings are white (#FFFFFF) DIN Pro Medium, uppercase, about 2.47 percent of slide height. All logo artwork is white (#FFFFFF) except the Lenovo box, which is white with black lettering. Panels are filled near-black #111111 with a thin bronze/tan border about #6B5A3E, roughly 0.2 percent of slide width, with square corners and no shadow. No gradients on the panels.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio background photograph with reflective floor and soft shadow under the panels (Covers the slide; no people; vignetted edges; a white #FFFFFF fill lies beneath it but is fully covered)
- title at x 25.1, y 7.9, w 49.8, h 4.1 [DIN Pro Bold, sans-serif, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: CONNECTING AND CREATING WITH OMNIVERSE
- shape at x 3.8, y 21.5, w 29.9, h 73.6 [#111111]: Software panel (Rectangle, square corners, 0.2% thin bronze border #6B5A3E, no shadow)
- shape at x 35, y 21.5, w 30, h 73.6 [#111111]: Systems panel (Rectangle, square corners, 0.2% thin bronze border #6B5A3E, no shadow)
- shape at x 66.3, y 21.5, w 29.9, h 73.6 [#111111]: Pioneers panel (Rectangle, square corners, 0.2% thin bronze border #6B5A3E, no shadow)
- subtitle at x 15.2, y 24.1, w 7.1, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: SOFTWARE
- subtitle at x 47.1, y 24.1, w 5.9, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: SYSTEMS
- subtitle at x 78, y 24.3, w 6.6, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: PIONEERS
- logo at x 6.5, y 30.9, w 6.5, h 2.3 [#FFFFFF]: Adobe logo
- logo at x 15.1, y 30.9, w 7.6, h 3 [#FFFFFF]: Autodesk logo
- logo at x 25.8, y 31.5, w 5.5, h 3.1 [#FFFFFF]: Bentley logo (Advancing Infrastructure)
- logo at x 6.4, y 36.7, w 6.9, h 3.9 [#FFFFFF]: Blender logo
- logo at x 16.7, y 37.1, w 4.4, h 3.9 [#FFFFFF]: CLO Virtual Fashion logo
- logo at x 24.9, y 37.6, w 6.2, h 2.6 [#FFFFFF]: esri logo (The Science of Where)
- logo at x 6.4, y 44.1, w 6.1, h 1.9 [#FFFFFF]: FOUNDRY logo
- logo at x 16.2, y 43.9, w 5.1, h 2.6 [#FFFFFF]: golaem logo
- logo at x 23.2, y 44.4, w 7.7, h 1.6 [#FFFFFF]: GRAPHISOFT logo
- logo at x 6.5, y 49.6, w 5, h 2.8 [#FFFFFF]: ipolog logo
- logo at x 14.9, y 49.9, w 7.2, h 2.7 [#FFFFFF]: MathWorks logo
- logo at x 24.3, y 50, w 6.7, h 3 [#FFFFFF]: NETALLIED SYSTEMS logo
- logo at x 6.3, y 56.4, w 7.1, h 2.8 [#FFFFFF]: onshape logo
- logo at x 15.2, y 55.7, w 7.5, h 3.5 [#FFFFFF]: ParaView logo
- logo at x 24.8, y 56.9, w 6.2, h 2.5 [#FFFFFF]: PIXAR Animation Studios logo
- logo at x 6, y 62.6, w 5.3, h 3.9 [#FFFFFF]: Pixologic makers of ZBRUSH logo
- logo at x 16.6, y 62.5, w 4.7, h 3.3 [#FFFFFF]: REALLUSION logo
- logo at x 25.2, y 63.3, w 5.9, h 2.3 [#FFFFFF]: Rhinoceros logo
- logo at x 6.4, y 70.2, w 6.6, h 2.7 [#FFFFFF]: SideFX logo
- logo at x 15, y 70.2, w 7.8, h 2.8 [#FFFFFF]: SOLIDWORKS logo
- logo at x 25.7, y 70.7, w 5.5, h 2.4 [#FFFFFF]: Trimble logo
- logo at x 11.4, y 77.2, w 5.7, h 3.7 [#FFFFFF]: Unreal Engine logo
- logo at x 20.4, y 77.5, w 5.1, h 2.3 [#FFFFFF]: wrnch logo
- logo at x 39.8, y 31, w 6.7, h 2.5 [#FFFFFF]: ASUS logo
- logo at x 54, y 30.6, w 5, h 2.8 [#FFFFFF]: BOXX logo
- logo at x 40.6, y 44.3, w 5.1, h 4.8 [#FFFFFF]: Cisco logo
- logo at x 50.9, y 45.4, w 11.5, h 2.6 [#FFFFFF]: Dell Technologies logo
- logo at x 41.6, y 60.2, w 3.2, h 5.7 [#FFFFFF]: HP logo
- logo at x 53.7, y 60.9, w 5.8, h 3.4 [#FFFFFF]: Lenovo logo (White rectangle with black lettering)
- logo at x 39.9, y 77.1, w 6.5, h 2.6 [#FFFFFF]: PNY logo
- logo at x 53.4, y 75.3, w 6.3, h 6.1 [#FFFFFF]: SUPERMICRO logo (Oval outline wordmark)
- logo at x 68.1, y 30, w 3.9, h 3.7 [#FFFFFF]: BMW GROUP logo
- logo at x 75, y 31, w 7.8, h 2.8 [#FFFFFF]: ERICSSON logo
- logo at x 85.6, y 31.6, w 8.9, h 2 [#FFFFFF]: Foster + Partners logo
- logo at x 68.2, y 41.9, w 8.5, h 3.6 [#FFFFFF]: FRAMESTORE logo
- logo at x 81.7, y 41.3, w 2.3, h 4.1 [#FFFFFF]: IBI logo (Outlined bracket shape with letters IBI)
- logo at x 89.2, y 41.9, w 5.2, h 2.5 [#FFFFFF]: Gensler logo
- logo at x 68.1, y 51.9, w 4.8, h 5.7 [#FFFFFF]: Industrial Light & Magic logo
- logo at x 77.7, y 54.7, w 8.4, h 2.2 [#FFFFFF]: KITESTRING logo
- logo at x 90.9, y 54, w 3.4, h 2.7 [#FFFFFF]: KPF logo
- logo at x 68.2, y 66.4, w 6, h 2.8 [#FFFFFF]: Lightcraft Technology logo
- logo at x 78.4, y 66.5, w 5.1, h 2.4 [#FFFFFF]: TANGENT logo
- logo at x 87.7, y 66.1, w 6.7, h 3.3 [#FFFFFF]: TURBOSQUID logo
- logo at x 68.2, y 77.5, w 4, h 2.9 [#FFFFFF]: W-B Woods Bagot logo
- logo at x 75.7, y 77.7, w 4.8, h 2.6 [#FFFFFF]: WPP logo
- logo at x 83.9, y 78, w 10.4, h 1.9 [#FFFFFF]: VOLVO logo

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 23.9, y 53.9, w 8.1, h 8.1: 543 by 306 pixels
- image at x 24.5, y 67.9, w 7.9, h 8.0: 1250 by 703 pixels
- image at x 24.1, y 60.3, w 7.5, h 8.3: 512 by 318 pixels
- image at x 14.9, y 68.7, w 8.0, h 7.1: 452 by 226 pixels
- image at x 53.4, y 75.3, w 6.3, h 6.1: 680 by 373 pixels
- image at x 5.4, y 69.8, w 8.5, h 3.7: 506 by 123 pixels
- image at x 16.0, y 61.5, w 6.0, h 5.1: 471 by 225 pixels
- image at x 68.2, y 41.9, w 8.5, h 3.6: 510 by 121 pixels
- image at x 50.9, y 45.4, w 11.5, h 2.6: 1536 by 199 pixels
- image at x 6.3, y 36.7, w 6.9, h 3.9: 520 by 167 pixels
- image at x 68.1, y 51.9, w 4.8, h 5.7: 390 by 262 pixels
- image at x 15.2, y 55.7, w 7.5, h 3.5: 438 by 115 pixels
- image at x 40.6, y 44.3, w 5.1, h 4.8: 500 by 264 pixels
- image at x 15.1, y 30.9, w 7.6, h 3.0: 487 by 108 pixels
- image at x 87.7, y 66.1, w 6.7, h 3.3: 400 by 112 pixels
- image at x 75.0, y 31.0, w 7.8, h 2.8: 935 by 190 pixels
- image at x 6.0, y 62.6, w 5.3, h 3.9: 640 by 264 pixels
- image at x 6.3, y 56.4, w 7.1, h 2.8: 428 by 96 pixels
- image at x 24.3, y 50.0, w 6.7, h 3.0: 940 by 234 pixels
- image at x 14.9, y 49.9, w 7.2, h 2.7: 1239 by 264 pixels
- image at x 53.7, y 60.9, w 5.8, h 3.4: 418 by 139 pixels
- image at x 11.5, y 77.3, w 5.6, h 3.5: 650 by 230 pixels
- image at x 77.7, y 54.7, w 8.4, h 2.2: 318 by 46 pixels
- image at x 41.6, y 60.2, w 3.2, h 5.7: 193 by 193 pixels
- image at x 25.8, y 31.5, w 5.5, h 3.1: 175 by 56 pixels
- image at x 16.7, y 37.1, w 4.4, h 3.9: 263 by 132 pixels
- image at x 68.2, y 66.4, w 6.0, h 2.8: 381 by 102 pixels
- image at x 39.9, y 77.1, w 6.5, h 2.6: 390 by 87 pixels
- image at x 24.9, y 37.6, w 6.2, h 2.6: 371 by 89 pixels
- image at x 39.8, y 31.0, w 6.7, h 2.3: 400 by 79 pixels
- image at x 6.5, y 30.9, w 6.5, h 2.3: 775 by 158 pixels
- image at x 6.5, y 49.6, w 5.0, h 2.8: 800 by 253 pixels
- image at x 54.0, y 30.6, w 5.0, h 2.8: 302 by 96 pixels
- image at x 16.2, y 43.9, w 5.1, h 2.6: 607 by 175 pixels
- image at x 23.2, y 44.4, w 7.7, h 1.6: 909 by 109 pixels
- image at x 78.4, y 66.5, w 5.1, h 2.4: 607 by 161 pixels
- image at x 6.4, y 44.1, w 6.1, h 1.9: 367 by 66 pixels
- image at x 68.2, y 77.5, w 4.0, h 2.9: 319 by 132 pixels
- text at x 25.1, y 7.9, w 49.8, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: CONNECTING AND CREATING WITH OMNIVERSE
- text at x 15.2, y 24.1, w 7.1, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: SOFTWARE
- text at x 47.1, y 24.1, w 5.9, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: SYSTEMS
- text at x 78.0, y 24.3, w 6.6, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: PIONEERS

### Slide 17

**Review notes**

- Worth studying: A single headline title is built up across several slides, adding one architecture layer at a time so the audience follows the argument step by step.
- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

DATA CENTER IS THE NEW UNIT OF COMPUTING / Monolithic

**Layout**

Single centred title sits across the top band at about 8% from the top, with a large dark panel filling the middle of the slide and a single small icon with caption at the left of the panel. No footer, page number or logo is visible; the rest of the panel is empty.

**Visuals**

One illustration: an isometric monolithic compute unit at about x 9.9%, y 37.9%, 6.2% wide by 31.6% high. It is a tall black rectangular block with a thin white outline, with a gold (#BD9F63) band across its top and a small black cube sitting on the band. The cube's top face carries small white letters (C, D, A, B). The block's front face shows six thin outlined horizontal slots. Lighting is a soft top light on a black stage. Composition is a side-on isometric view, uncropped and boxed only by the slide background. No photograph, chart, table or logo beyond this icon.

**Design**

Background: Full-slide stage photograph: black (#000000) upper backdrop fading into a dark grey reflective floor (#2A2A2A) at the bottom. Black stage with a dark charcoal panel and a thin bronze/gold border line. Title is white (#FFFFFF) DIN Pro Bold, all caps, sans-serif, about 4.1% of slide height, centred. Caption is gold (#BD9F63) DIN Pro Light, about 1.85% of slide height, centred. Icon uses black (#000000) fills, white (#FFFFFF) thin line strokes and a gold (#BD9F63) band. Panel fill is near-black #141414 with a hairline bronze edge of about #6B5A3E, square corners, and a soft shadow below it. The floor below is a dark grey reflective surface (#2A2A2A to #1A1A1A) with faint highlights.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide dark stage backdrop: black wall above and reflective dark grey floor below, with faint light falloff (Background image 3840 by 2160 pixels, covers the slide, not cropped; sits at the back of the stack)
- shape at x 3.8, y 21.5, w 92.4, h 61.7 [#141414]: Dark rectangular panel with thin bronze border, empty (Square corners, hairline border about #6B5A3E, soft drop shadow beneath the bottom edge, floor reflection visible below)
- title at x 24.9, y 7.9, w 50.2, h 4.1 [DIN Pro Bold, sans-serif, bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: DATA CENTER IS THE NEW UNIT OF COMPUTING (Single line, letter-spacing slightly open)
- illustration at x 9.9, y 37.9, w 6.2, h 31.6 [#000000]: Isometric monolithic compute unit: tall black block with gold top band, small black cube labelled C D A B on top, six outlined slots on the front face (Placed image 534 by 1538 pixels; white thin outline strokes; gold #BD9F63 band; no shadow)
- caption at x 10.6, y 74.6, w 4.8, h 1.9 [DIN Pro Light, sans-serif, regular weight; font size 1.85% of slide height; #BD9F63; center aligned]: Monolithic

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 9.9, y 37.9, w 6.2, h 31.6: 534 by 1538 pixels
- text at x 24.9, y 7.9, w 50.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- text at x 10.6, y 74.6, w 4.8, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Monolithic

### Slide 18

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

DATA CENTER IS THE NEW UNIT OF COMPUTING / Monolithic / Software-Defined / Data Center

**Layout**

A single full-width dark panel sits inside the slide with its title centred above it, so the title is horizontally centred at about 50% of the width and sits near the top at about 8% of the height. The left portion of the panel holds two tower illustrations side by side, each with its caption centred beneath, and the rest of the panel is empty. There is no footer, page number, or logo, and the margins are about 4% on the left and right.

**Visuals**

Two isometric line-art illustrations of server racks on a black panel, with no chart, table or photograph inside the panel. Left: a monolithic rack, a tall black box with thin white outline edges and six slanted slot outlines on its front face, topped by a small gold (#BD9F63) tray and a black cube with dashed white outline whose faces carry the letters A, B, C and D. Right: a software-defined data center rack of the same black construction and slot pattern, but taller, topped by a taller solid gold (#BD9F63) block and the same black lettered A, B, C, D cube. The gold colour is the only accent in the illustrations. Lighting is a soft spotlight on a dark stage floor with a faint reflection beneath the panel.

**Design**

Background: Black (#000000) stage with a dark charcoal (#121212) studio floor and a faint reflective gradient, as a full-bleed photograph behind everything. The slide sits on a near-black stage with a dark charcoal panel. Title text is white (#FFFFFF) DIN Pro Bold, all caps, in a sans-serif, about 4.1% of slide height, centred. Captions are gold (#BD9F63) DIN Pro Light, sans-serif, about 1.85% of slide height, centred. Illustrations use black (#000000) fills with white (#FFFFFF) thin outlines and gold (#BD9F63) accents. The panel has square corners and a thin warm gold-grey border about 0.1% wide in roughly #8C7A5B, with a soft drop shadow beneath it.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide white fill (#FFFFFF), covered entirely by the background photograph and not visible (Covered by the background photograph; no stroke)
- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio stage photograph with black upper area, charcoal floor and soft reflection (Full-bleed, not cropped, no overlay; 3840 by 2160 pixels)
- shape at x 3.8, y 12.1, w 92.2, h 65.2 [#121212]: Dark rectangular panel (Square corners, thin gold-grey stroke about 0.1% of slide width in roughly #8C7A5B, soft drop shadow below, opacity 100%)
- illustration at x 9.9, y 37.9, w 6.2, h 31.6 [#000000]: Monolithic server rack illustration with gold tray and black lettered A B C D cube on top (Isometric line art, white thin outlines, six slanted slot outlines on front face, gold #BD9F63 tray, dashed-outline cube; 534 by 1538 pixels)
- illustration at x 22.6, y 33.2, w 6.2, h 36.3 [#000000]: Software-defined data center rack illustration with tall gold block and black lettered A B C D cube on top (Isometric line art, white thin outlines, six slanted slot outlines on front face, solid gold #BD9F63 block, dashed-outline cube; 534 by 1763 pixels)
- title at x 24.9, y 7.9, w 50.2, h 4.1 [DIN Pro Bold, sans-serif, bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- caption at x 10.6, y 74.6, w 4.8, h 1.9 [DIN Pro Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: Monolithic
- caption at x 21.6, y 74.6, w 8, h 1.9 [DIN Pro Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: Software-Defined
- caption at x 22.9, y 76.8, w 5.5, h 1.9 [DIN Pro Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: Data Center

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 22.6, y 33.2, w 6.2, h 36.3: 534 by 1763 pixels
- image at x 9.9, y 37.9, w 6.2, h 31.6: 534 by 1538 pixels
- text at x 24.9, y 7.9, w 50.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- text at x 10.6, y 74.6, w 4.8, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Monolithic
- text at x 21.6, y 74.6, w 8.0, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Software-Defined
- text at x 22.9, y 76.8, w 5.5, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Data Center

### Slide 19

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

DATA CENTER IS THE NEW UNIT OF COMPUTING / Monolithic / Software-Defined / Data Center / Disaggregated, / Micro-Services, Scaled Out

**Layout**

Single centred title sits in the top band above a wide dark panel that spans most of the slide width and height. Three tower groups stand left to right inside the panel on a shared baseline, each with a caption centred beneath it, and the right half of the panel is empty. Margins are about 4% on the left and right and the panel bottom sits at about 83% of the slide height. There is no footer, page number, or logo.

**Visuals**

Three isometric line-and-block illustrations of data-centre towers, drawn in black with thin white outlines and gold #BD9F63 accents. Left, Monolithic: one black tower with thin horizontal slot outlines on its front face, a gold plate on top, and one black cube labelled A, B, C, D on its top face. Centre, Software-Defined Data Center: one taller black tower with the same slot outlines, a taller gold block on top, and a black cube labelled A, B, C, D above it. Right, Disaggregated, Micro-Services, Scaled Out: a cluster of four towers of different heights, with gold blocks on their tops and black cubes stacked on them. Cubes are labelled C (left), D (top centre), A (centre, in front), and B (right). White arrows connect them: one arrow runs from C up-right to D, one runs from D down-right to B, and one runs from B down-left to A. Cubes carry faint dotted outlines. No photographs and no logos.

**Design**

Background: Dark studio scene: black #000000 at top fading to dark charcoal #1A1A1A and a reflective grey floor at the bottom, behind the panel. Near-black, almost black background with a dark charcoal studio surround. Title in white (#FFFFFF) DIN Pro Bold style sans-serif, all capitals, about 4.07% of slide height, medium-wide letter spacing. Caption text in gold (#BD9F63) DIN Pro Light sans-serif, sentence case, about 1.85% of slide height. Accents are gold #BD9F63 for blocks, labels and the panel edge. Panel is a flat dark charcoal #111111 rectangle with a thin gold #BD9F63 border of about 0.1% line weight. Tower bodies are black #000000 with white hairline outlines. Arrows are white with small arrowheads. No gradients on the panel, and no shadows beyond a soft shadow under the panel.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Dark studio backdrop image with a reflective floor, full-bleed behind everything (Full-bleed, no crop, dark tones with a lighter grey floor reflection in the lower third)
- shape at x 3.8, y 21.6, w 92.4, h 61.6 [#111111]: Dark rectangular panel (Flat rectangle, thin gold #BD9F63 border about 0.1% line weight, soft shadow beneath)
- title at x 24.9, y 7.9, w 50.2, h 4.1 [DIN Pro Bold, sans-serif, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- illustration at x 9.9, y 37.9, w 6.2, h 31.6: Monolithic tower with gold top plate and labelled cube (A, B, C, D) (Black tower with white outline and horizontal slot outlines, gold #BD9F63 top plate, black cube with dotted outline)
- illustration at x 22.6, y 33.2, w 6.2, h 36.3: Software-defined data-centre tower with gold block and labelled cube (A, B, C, D) (Black tower with white outline and horizontal slot outlines, taller gold #BD9F63 block, black cube with dotted outline)
- illustration at x 35.3, y 27.1, w 13.9, h 42.4: Cluster of four towers with gold blocks and cubes labelled C, D, A, B, joined by three white arrows (C to D, D to B, B to A) (Black towers with white outlines, gold #BD9F63 blocks, white arrows with small arrowheads, cubes with dotted outlines)
- body at x 10.6, y 74.6, w 4.8, h 1.9 [DIN Pro Light, sans-serif, sentence case; font size 1.85% of slide height; #BD9F63; center aligned]: Monolithic
- body at x 21.6, y 74.6, w 8, h 3.9 [DIN Pro Light, sans-serif, sentence case; font size 1.85% of slide height; #BD9F63; center aligned]: Software-Defined / Data Center (Two lines, the second line starts at y 76.8)
- body at x 36.1, y 74.6, w 12.3, h 4.1 [DIN Pro Light, sans-serif, sentence case; font size 1.85% of slide height; #BD9F63; center aligned]: Disaggregated, / Micro-Services, Scaled Out (Two lines, the second line starts at y 76.8)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 35.3, y 27.1, w 13.9, h 42.4: 1205 by 2059 pixels
- image at x 22.6, y 33.2, w 6.2, h 36.3: 534 by 1763 pixels
- image at x 9.9, y 37.9, w 6.2, h 31.6: 534 by 1538 pixels
- text at x 24.9, y 7.9, w 50.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- text at x 10.6, y 74.6, w 4.8, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Monolithic
- text at x 21.6, y 74.6, w 8.0, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Software-Defined
- text at x 38.8, y 74.6, w 6.9, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Disaggregated,
- text at x 22.9, y 76.8, w 5.5, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Data Center
- text at x 36.1, y 76.8, w 12.3, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Micro-Services, Scaled Out

### Slide 20

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

DATA CENTER IS THE NEW UNIT OF COMPUTING
Monolithic
Software-Defined
Data Center
Disaggregated,
Micro-Services, Scaled Out
GPU-Accelerated
Computing

**Layout**

Full-bleed black stage with a single large framed panel occupying the middle of the slide; the title is centred horizontally in the top band above the panel. Four isometric building groups sit left to right inside the panel, each with a caption centred beneath it in two lines, leaving the right quarter of the panel empty. No footer or slide number is visible.

**Visuals**

Four isometric line-art illustrations of data-centre towers, read left to right. (1) Monolithic: one tall black tower with white outline rack slots and a short gold base plate, topped by a single black cube labelled A, B, C, D on its faces. (2) Software-Defined Data Center: one taller black tower with a larger gold block on top, carrying a black cube labelled A, B, C, D. (3) Disaggregated, Micro-Services, Scaled Out: a cluster of four black towers of differing heights, each with a gold block, carrying black cubes labelled A, B, C and D, with white arrows running from C to D, D to B and B to A. (4) GPU-Accelerated Computing: a cluster of towers with gold blocks carrying stacked black slabs labelled A, B, C and D, with white arrows connecting them in the same pattern, and a small flat black chip package with a gold-and-silver die sitting on a flat platform in front of the towers. Lighting is a soft spotlight from above, with the illustrations rendered in black with thin off-white edge lines and gold accents.

**Design**

Background: Black (#000000) backdrop fading into a dark charcoal (#141414) stage with a glossy grey floor reflection (#2A2A2A) at the bottom. Black background (#000000) with a dark charcoal stage (#141414) and a glossy floor reflection below. Title in white (#FFFFFF) bold uppercase DIN-style sans-serif, about 4.1% of slide height for the cap height line. Captions in light gold (#BD9F63) DIN Light sans-serif, about 1.85% of slide height. Panel has a thin gold-brown border (#8C7A55) and a dark charcoal fill (#141414); illustrations use black (#000000) fills, off-white (#E6E6E6) outline strokes and gold (#BD9F63) block accents. Arrows are white (#FFFFFF) straight lines with small arrowheads. No rounded corners or gradients on the panel; soft shadow beneath the panel.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Full-slide black background fill (Covers the slide; a white fill of the same size sits beneath it in the file.)
- photo at x 0, y 0, w 100, h 100 [#141414]: Full-slide background stage image with dark charcoal panel backdrop and glossy grey floor reflection (Full-bleed image 3840 by 2160 px, covering the slide; a second identical image sits beneath it.)
- shape at x 3.8, y 21.6, w 92.4, h 56 [#141414]: Framed display panel (Dark charcoal fill with a thin gold-brown border (#8C7A55), about 0.1% stroke; square corners; soft shadow beneath the lower edge.)
- title at x 24.9, y 7.9, w 50.2, h 4.1 [DINPro-Bold, sans-serif, bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- illustration at x 9.9, y 20.5, w 13, h 60 [#000000]: Monolithic data-centre tower with cube labelled A, B, C, D on top (Black isometric tower with off-white edge lines and white rack slot outlines; short gold (#BD9F63) base plate; black cube with labels; image box 1205 by 2059 px region.)
- illustration at x 22.6, y 33.2, w 6.2, h 36.3 [#000000]: Software-Defined Data Center tower with cube labelled A, B, C, D on top (Black isometric tower with off-white edge lines and rack slot outlines; large gold (#BD9F63) block on top; black cube with labels A, B, C, D.)
- illustration at x 35.3, y 27.1, w 13.9, h 42.4 [#000000]: Disaggregated, Micro-Services, Scaled Out cluster of towers with cubes labelled A, B, C, D and white arrows (Four black isometric towers with gold blocks; cubes labelled C, D, B, A; white (#FFFFFF) arrows from C to D, D to B and B to A; off-white edge lines.)
- illustration at x 55.7, y 27.1, w 13.9, h 42.4 [#000000]: GPU-Accelerated Computing cluster of towers with stacked slabs labelled A, B, C, D, arrows and a chip (Towers with gold blocks; stacked black slabs labelled C, D, B, A; white arrows between them; small flat black platform with a gold-and-silver chip die in front; off-white edge lines.)
- caption at x 10.6, y 74.6, w 4.8, h 1.9 [DINPro-Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: Monolithic
- caption at x 21.6, y 74.6, w 8, h 3.9 [DINPro-Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: Software-Defined / Data Center (Two lines; second line Data Center at x 22.9, y 76.8.)
- caption at x 36.1, y 74.6, w 12.3, h 4.1 [DINPro-Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: Disaggregated, / Micro-Services, Scaled Out (Two lines centred under the third building group.)
- caption at x 58.7, y 74.6, w 7.9, h 3.9 [DINPro-Light, sans-serif, light weight; font size 1.85% of slide height; #BD9F63; center aligned]: GPU-Accelerated / Computing (Two lines; second line Computing at x 60.2, y 76.8.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 35.3, y 27.1, w 13.9, h 42.4: 1205 by 2059 pixels
- image at x 55.7, y 27.1, w 13.9, h 42.4: 1205 by 2059 pixels
- image at x 22.6, y 33.2, w 6.2, h 36.3: 534 by 1763 pixels
- image at x 9.9, y 37.9, w 6.2, h 31.6: 534 by 1538 pixels
- text at x 24.9, y 7.9, w 50.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- text at x 10.6, y 74.6, w 4.8, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Monolithic
- text at x 21.6, y 74.6, w 8.0, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Software-Defined
- text at x 38.8, y 74.6, w 6.9, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Disaggregated,
- text at x 58.7, y 74.6, w 7.9, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: GPU-Accelerated
- text at x 22.9, y 76.8, w 5.5, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Data Center
- text at x 36.1, y 76.8, w 12.3, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Micro-Services, Scaled Out
- text at x 60.2, y 76.8, w 5.0, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Computing

### Slide 21

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

DATA CENTER IS THE NEW UNIT OF COMPUTING / Monolithic / Software-Defined / Data Center / Disaggregated, / Micro-Services, Scaled Out / GPU-Accelerated / Computing / DPU-Accelerated / Data Center Infrastructure

**Layout**

A centred bold all-caps title sits near the top of a black slide, with a wide dark rectangular panel framed by a thin gold border filling the middle of the slide. Inside the panel, five isometric tower illustrations stand in a row across the width, each with a centred two-line gold caption beneath it on a shared baseline. There is no footer, slide number or logo.

**Visuals**

Five isometric illustrations of black data-centre towers with thin white outline detailing, gold (#BD9F63) plinths and white-outlined slatted vents on the faces, drawn as stacked blocks labelled A, B, C, D. From left to right: (1) Monolithic: one short black tower with a single gold plinth and a single black cube labelled A, B, C, D on top. (2) Software-Defined Data Center: a taller black tower with a gold block and one black cube labelled A, B, C, D. (3) Disaggregated, Micro-Services, Scaled Out: four black towers of differing heights, each with a gold top block, carrying separate black cubes labelled A, B, C, D, with white arrows linking cube C to cube D, cube D to cube B, and cube B to cube A. (4) GPU-Accelerated Computing: towers topped by stacks of thin black layered slabs (dashed outlines) in place of cubes, with the same white arrows linking C, D, B and A, and a flat black box with a small chip on the lower right of the group. (5) DPU-Accelerated Data Center Infrastructure: towers topped by tall stacks of thin black slabs with the same white arrows linking C, D, B and A, and a flat black box with two small chips on the lower right. Lighting is a soft spotlight from above on a near-black ground. Composition is a straight frontal row with isometric perspective, all fully visible and not cropped. No photographs or tints overlay the illustrations.

**Design**

Background: Full-bleed near-black (#000000) studio backdrop fading to a dark grey reflective floor (#2A2A2A) at the bottom. Pure black background with a dark charcoal panel (#111111) framed by a thin 1px gold (#BD9F63) line. Title is white (#FFFFFF) bold DIN-style sans-serif, all caps, at about 4.1% of slide height for the cap height region; captions are light-weight DIN-style sans-serif in gold (#BD9F63) at about 1.85% of slide height. Illustration accents are gold #BD9F63, outlines white and black fills. Shapes have sharp corners and no shadows; the panel has a soft drop shadow onto the floor below it.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Full-bleed black studio backdrop with grey reflective floor at bottom (Gradient from #000000 at top to #2A2A2A at the lower floor area; soft spotlight glow on the floor; no outline.)
- shape at x 3.8, y 21.5, w 92.4, h 61.7 [#111111]: Dark rectangular display panel (Sharp corners, 1px gold #BD9F63 stroke, soft drop shadow onto the floor beneath.)
- title at x 24.9, y 7.9, w 50.2, h 4.1 [DIN Pro, bold, sans-serif, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- illustration at x 9.9, y 37.9, w 6.2, h 31.6 [#000000]: Monolithic data-centre tower with one black cube labelled A, B, C, D on a gold plinth (Isometric, fully visible; white outline detailing; gold #BD9F63 plinth.)
- illustration at x 22.6, y 33.2, w 6.2, h 36.3 [#000000]: Software-Defined Data Center tower with one black cube labelled A, B, C, D on a gold block (Isometric, fully visible; white outline detailing; gold #BD9F63 block.)
- illustration at x 35.3, y 27.1, w 13.9, h 42.4 [#000000]: Disaggregated, micro-services, scaled-out cluster of four towers with cubes A, B, C, D linked by white arrows (Isometric; white arrows from C to D, D to B, B to A; gold #BD9F63 top blocks; white outline detailing.)
- illustration at x 55.7, y 27.1, w 13.9, h 42.4 [#000000]: GPU-Accelerated Computing cluster of towers with layered slab stacks, cubes A, B, C, D linked by white arrows, and a flat box with a chip (Isometric; dashed-outline slab stacks; white arrows; flat black box with small chip at lower right; gold #BD9F63 plinths.)
- illustration at x 76.2, y 27.2, w 13.9, h 42.3 [#000000]: DPU-Accelerated Data Center Infrastructure cluster of towers with tall slab stacks, cubes A, B, C, D linked by white arrows, and a flat box with two chips (Isometric; tall slab stacks; white arrows; flat black box with two small chips at lower right; gold #BD9F63 plinths.)
- caption at x 10.6, y 74.6, w 4.8, h 1.9 [DIN Pro, light, sans-serif; font size 1.85% of slide height; #BD9F63; center aligned]: Monolithic
- caption at x 21.6, y 74.6, w 8, h 4.1 [DIN Pro, light, sans-serif; font size 1.85% of slide height; #BD9F63; center aligned]: Software-Defined / Data Center (Line spacing about 1.5; second line starts at y 76.8.)
- caption at x 36.1, y 74.6, w 12.3, h 4.1 [DIN Pro, light, sans-serif; font size 1.85% of slide height; #BD9F63; center aligned]: Disaggregated, / Micro-Services, Scaled Out (Line spacing about 1.5.)
- caption at x 58.7, y 74.6, w 7.9, h 4.1 [DIN Pro, light, sans-serif; font size 1.85% of slide height; #BD9F63; center aligned]: GPU-Accelerated / Computing (Line spacing about 1.5.)
- caption at x 77.1, y 74.6, w 12.1, h 4.1 [DIN Pro, light, sans-serif; font size 1.85% of slide height; #BD9F63; center aligned]: DPU-Accelerated / Data Center Infrastructure (Line spacing about 1.5.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 35.3, y 27.1, w 13.9, h 42.4: 1205 by 2059 pixels
- image at x 55.7, y 27.1, w 13.9, h 42.4: 1205 by 2059 pixels
- image at x 76.2, y 27.2, w 13.9, h 42.3: 1206 by 2059 pixels
- image at x 22.6, y 33.2, w 6.2, h 36.3: 534 by 1763 pixels
- image at x 9.9, y 37.9, w 6.2, h 31.6: 534 by 1538 pixels
- text at x 24.9, y 7.9, w 50.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA CENTER IS THE NEW UNIT OF COMPUTING
- text at x 10.6, y 74.6, w 4.8, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Monolithic
- text at x 21.6, y 74.6, w 8.0, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Software-Defined
- text at x 38.8, y 74.6, w 6.9, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Disaggregated,
- text at x 58.7, y 74.6, w 7.9, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: GPU-Accelerated
- text at x 79.2, y 74.6, w 7.9, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: DPU-Accelerated
- text at x 22.9, y 76.8, w 5.5, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Data Center
- text at x 36.1, y 76.8, w 12.3, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Micro-Services, Scaled Out
- text at x 60.2, y 76.8, w 5.0, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Computing
- text at x 77.1, y 76.8, w 12.1, h 1.9 [DINPro-Light; font size 1.85; #BD9F63]: Data Center Infrastructure

### Slide 22

**Review notes**

- Worth studying: A latency stack diagram breaks the cloud gaming pipeline into labelled milliseconds, making the performance claim concrete at a glance.

**Text**

BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
GeForce NOW Pod
Game Engine
40ms
Encode
5ms
10ms
10ms
User Input
10ms
<100ms
Decode
5ms
Render
10ms

**Layout**

Full-bleed black slide with a centred two-line header at the top: bold all-caps title over a regular-weight subtitle with pipe separators. Below, a dark panel with a thin warm-grey border spans roughly 4% to 96% of the width and 22% to 83% of the height; inside its left third sits a vertical flow diagram of stacked stages with labels to the right of each icon, and a vertical bracket labelled <100ms on the right of the stages. The right two-thirds of the panel is empty. No footer, page number or logo is visible.

**Visuals**

Diagram: a vertical flow of stages connected by small downward arrows. Top: a green-outlined rectangle (labelled GeForce NOW Pod above it) containing two game-cartridge-like icons and a settings window icon with a gear, representing Game Engine (40ms). Arrow down to an Encode icon (stacked film-strip/triangle glyph) labelled Encode 5ms. Arrow down to a cloud-with-stopwatch icon labelled 10ms. Arrow down to a black handheld controller with a phone-style screen showing a Destiny 2 Beyond Light key art (blue-tinted sky, dark silhouetted soldier and figures, pink light trails) labelled User Input 10ms. Arrow down to a Decode icon labelled Decode 5ms. Arrow down to a small rectangular image of the same Destiny 2 Beyond Light key art labelled Render 10ms. A thin upward arrow on the left runs from the controller up to the Game Engine box, and a second cloud-stopwatch icon sits beside it labelled 10ms, linking the controller back to the pod. A vertical white bracket on the right spans from Game Engine to Render and is labelled <100ms. Photograph-like image: dark silhouettes against bright blue and white sky with pink light, full-colour, boxed (not cropped in the render area), no overlay.

**Design**

Background: Black #000000 full-bleed background with a dark charcoal #121212 panel inside.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide background fill (Covers slide; rendered as black background image layer with fill #FFFFFF underneath)
- photo at x 0, y 0, w 100, h 100: Background backdrop image: dark studio stage with reflective floor and soft light, full-bleed (Dark charcoal to black, faint floor reflection at the bottom, covers slide)
- shape at x 3.8, y 22, w 92.4, h 61 [#121212]: Dark charcoal display panel with thin warm-grey border (Thin border approx #6B645C, 1px; no corner radius; soft shadow beneath panel)
- title at x 11.7, y 7.9, w 76.6, h 4.1 [DIN Pro, bold, all caps, sans-serif; font size 4.07% of slide height; #FFFFFF; center aligned]: BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
- subtitle at x 20.8, y 12.5, w 58.4, h 2.7 [DIN Pro, regular, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users (Pipe separators with spaces)
- label at x 8.9, y 25.9, w 7.9, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #76B900; left aligned]: GeForce NOW Pod
- shape at x 8.6, y 28.5, w 13.4, h 6.2 [none (outline #76B900, about 2px stroke, no fill)]: Green outlined rectangle enclosing Game Engine stage (Square corners, no shadow)
- icon at x 11.9, y 28.5, w 8.9, h 7 [#FFFFFF outline icons]: Game cartridge icons and settings window icon with gear (Two cartridge outline icons stacked left and a window with gear icon right; thin white strokes)
- icon at x 15.9, y 41.5, w 2.3, h 4.2 [#FFFFFF]: Encode icon (film-strip triangle glyph) (Mesh-textured triangle glyph, white line art)
- icon at x 10.9, y 44.5, w 2.3, h 4.2 [#FFFFFF]: Cloud with stopwatch icon (left) (Outline line art)
- icon at x 19.2, y 44.5, w 2.3, h 4.2 [#FFFFFF]: Cloud with stopwatch icon (right) (Outline line art)
- icon at x 19.2, y 62.8, w 2.3, h 4.2 [#FFFFFF]: Decode icon (triangle glyph) (Mesh-textured triangle glyph, white line art)
- photo at x 11.9, y 69.5, w 8.9, h 7: Handheld controller with phone-style screen showing Destiny 2 Beyond Light key art (Black controller with grips at left and right and a central screen; screen shows dark silhouetted figures against blue-white sky with pink light trails; boxed; overlaps the vertical arrows)
- photo at x 8.6, y 51.6, w 13.4, h 8.7: Destiny 2 Beyond Light key art image (Blue-white sky, dark silhouetted soldier and figures, pink light trails, boxed rectangle with no border, no overlay, not cropped)
- line at x 10.9, y 32, w 0.5, h 40 [#FFFFFF]: Vertical arrows and connectors between stages (Thin white lines about 1px with small arrowheads; upward arrow on left from controller to pod; downward arrows in right column between stages)
- label at x 22.8, y 29.6, w 5.8, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: Game Engine
- label at x 22.8, y 31.7, w 2.4, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 40ms
- label at x 22.8, y 38, w 3.2, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: Encode
- label at x 22.8, y 40, w 1.8, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 5ms
- label at x 14.4, y 45.8, w 2.4, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- label at x 22.8, y 45.8, w 2.4, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- label at x 22.8, y 54.1, w 4.6, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: User Input
- label at x 22.8, y 56.2, w 2.4, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- shape at x 29.4, y 28.5, w 0.5, h 57 [#FFFFFF]: Vertical bracket spanning Game Engine to Render (Thin white line with short horizontal end ticks at top and bottom)
- label at x 30.7, y 54.4, w 3.5, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: <100ms
- label at x 22.8, y 63.3, w 3.2, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: Decode
- label at x 22.8, y 65.4, w 1.8, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 5ms
- label at x 22.8, y 71.2, w 3.2, h 1.7 [DIN Pro, bold, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: Render
- label at x 22.8, y 73.3, w 2.4, h 1.7 [DIN Pro, regular, sans-serif; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 8.6, y 51.6, w 13.4, h 8.7: 673 by 246 pixels
- image at x 11.9, y 69.5, w 8.9, h 7.0: 721 by 316 pixels
- image at x 15.9, y 29.3, w 2.3, h 4.2: 283 by 283 pixels
- image at x 19.2, y 62.8, w 2.3, h 4.2: 142 by 142 pixels
- image at x 19.2, y 37.8, w 2.3, h 4.2: 142 by 142 pixels
- image at x 19.2, y 44.5, w 2.3, h 4.2: 142 by 142 pixels
- image at x 13.1, y 30.2, w 2.3, h 4.2: 283 by 283 pixels
- image at x 13.1, y 28.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 10.9, y 44.5, w 2.3, h 4.2: 283 by 283 pixels
- text at x 11.7, y 7.9, w 76.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
- text at x 20.8, y 12.5, w 58.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
- text at x 8.9, y 25.9, w 7.9, h 1.7 [DINPro-Bold; font size 1.73; #76B900]: GeForce NOW Pod
- text at x 22.8, y 29.6, w 5.8, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Game Engine
- text at x 22.8, y 31.7, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 40ms
- text at x 22.8, y 38.0, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Encode
- text at x 22.8, y 40.0, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5ms
- text at x 14.4, y 45.8, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 22.8, y 45.8, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 22.8, y 54.1, w 4.6, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: User Input
- text at x 30.7, y 54.4, w 3.5, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: <100ms
- text at x 22.8, y 56.2, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 22.8, y 63.3, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Decode
- text at x 22.8, y 65.4, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5ms
- text at x 22.8, y 71.2, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Render
- text at x 22.8, y 73.3, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms

### Slide 23

**Text**

BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
GeForce NOW Pod
Game Engine
40ms
Encode
5ms
10ms
10ms
User Input
10ms
<100ms
TRADITIONAL CLOUD
GAMING SERVER
Game
Graphics
Driver
Video
SDDC
Security
Telemetry
NAT | DDOS | Reverse Proxy
Ethernet NIC
Decode
5ms
Rrender
10ms

**Layout**

Full-slide dark stage with a centred two-line header (bold all-caps title over a regular-weight subtitle) at the top. Below it, a large dark panel with a thin warm-grey border spans roughly 4% to 96% of the width; inside, a left column holds the GeForce NOW Pod latency chain (top to bottom, with a bracket on its right) and a right-of-centre block holds the Traditional Cloud Gaming Server diagram. The right third of the panel is empty. No footer, page number, logo or source line is visible.

**Visuals**

Diagram on the left, a vertical latency pipeline. From top: a green-outlined rectangle labelled GeForce NOW Pod containing two small outline icons (a server/memory stack and a settings window with a gear); a downward arrow labelled Encode 5ms with a small mesh-triangle icon; a downward arrow with a stopwatch-cloud icon labelled 10ms; a downward arrow to a black handheld gamepad with a phone-style screen showing a Destiny 2 Beyond Light key-art image labelled User Input 10ms; a downward arrow with a mesh-triangle icon labelled Decode 5ms; a downward arrow to a rectangular thumbnail of the same Destiny 2 Beyond Light image labelled Render 10ms; a downward arrow exits below. A return arrow runs upward from the stopwatch-cloud icon at the left column to the top Game Engine box. A vertical bracket with tick ends sits to the right of the chain, labelled <100ms. Diagram on the right: a large royal-blue rounded-corner rectangle labelled TRADITIONAL CLOUD GAMING SERVER above it; inside it, two rows of eight white outline gamepad icons (16 total); below them three darker-blue boxes Game, Graphics Driver, Video; below them three mid-blue boxes SDDC, Security, Telemetry; below them one wide mid-blue box NAT | DDOS | Reverse Proxy; beneath the blue block a grey bar labelled Ethernet NIC. The Destiny 2 images show a blue-tinted sky with silhouetted figures and a scoped gun-like shape; the composition is landscape, unboxed except for the thin white-outline thumbnail edge, and the Pod phone image is shown in landscape orientation with the device rendered in black.

**Design**

Background: Black (#000000) top band with a dark charcoal (#141414) panel and a dark grey floor gradient (#1A1A1A to #2A2A2A) at the bottom. Black (#000000) header band fading into a near-black charcoal panel (#111111 to #1A1A1A) with a subtle dark floor reflection at the bottom. Title in white (#FFFFFF) DIN Pro Bold, all caps, about 4.1% of slide height (cap height about 2.9%). Subtitle in white DIN Pro Regular, about 2.7% of slide height, separated by vertical bars. Pod label in NVIDIA green (#76B900) DIN Pro Bold 1.7%. Pipeline labels white DIN Pro Bold for stage names and regular for values, about 1.7% of slide height. Server heading white DIN Pro Medium, about 1.7%. Blue server block #0070C9 with darker boxes #0A5AA0 and lighter boxes #4A9BD9; grey NIC bar #808080 with white regular text. Thin warm-grey panel border (#5A5A50), no shadows on boxes, square corners on boxes, thin white-outline arrows and bracket about 1px. Gamepad icons thin white strokes on blue.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- title at x 11.7, y 7.9, w 76.6, h 4.1 [DIN Pro, Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING (Letter-spacing slightly open; single line.)
- subtitle at x 20.8, y 12.5, w 58.4, h 2.7 [DIN Pro, Regular; font size 2.72% of slide height; #FFFFFF; center aligned]: Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users (Vertical bar separators with spaces.)
- shape at x 3.8, y 21.6, w 92.4, h 61.6 [#141414]: Dark panel with thin warm-grey border (Border stroke about 1px in #5A5A50; no corner radius; subtle inner shadow at bottom.)
- text at x 8.9, y 25.9, w 7.9, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #76B900; left aligned]: GeForce NOW Pod
- shape at x 8.6, y 28.5, w 13, h 5.7 [none (outline #76B900)]: Green-outlined rectangle around Game Engine stage (Stroke about 2px #76B900, no fill, square corners.)
- icon at x 13.1, y 28.5, w 2.3, h 4.2 [#FFFFFF]: Server or memory stack outline icon inside green box (Thin white outline icon.)
- icon at x 15.9, y 29.3, w 2.3, h 4.2 [#FFFFFF]: Settings window with gear outline icon inside green box (Thin white outline icon.)
- text at x 22.8, y 29.6, w 5.8, h 3.8 [DIN Pro, Bold for Game Engine; DIN Pro, Regular for 40ms; font size 1.73% of slide height; #FFFFFF; left aligned]: Game Engine / 40ms (Two lines; line spacing about 2.0%.)
- line at x 20.3, y 33.6, w 0.2, h 4.2 [#FFFFFF]: Arrow from Game Engine down to Encode stage (Thin 1px white line with arrowhead pointing down.)
- icon at x 19.2, y 37.8, w 2.3, h 4.2 [#FFFFFF]: Mesh-triangle encode icon (Thin white outline mesh icon.)
- text at x 22.8, y 38, w 3.2, h 3.7 [DIN Pro, Bold for Encode; DIN Pro, Regular for 5ms; font size 1.73% of slide height; #FFFFFF; left aligned]: Encode / 5ms
- line at x 20.3, y 42, w 0.2, h 2.5 [#FFFFFF]: Arrow from Encode down to stopwatch-cloud icon (Thin 1px white line with downward arrowhead.)
- icon at x 19.2, y 44.5, w 2.3, h 4.2 [#FFFFFF]: Upper cloud-with-stopwatch icon (right column) (Thin white outline icon.)
- text at x 22.8, y 45.8, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- line at x 12, y 33.6, w 0.2, h 11 [#FFFFFF]: Upward arrow from left stopwatch-cloud icon to GeForce NOW Pod box (Thin 1px white line with arrowhead pointing up.)
- icon at x 10.9, y 44.5, w 2.3, h 4.2 [#FFFFFF]: Cloud-with-stopwatch icon (left column) (Thin white outline icon.)
- text at x 14.4, y 45.8, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- line at x 12, y 48.7, w 0.2, h 2.9 [#FFFFFF]: Downward line from left cloud icon to gamepad (Thin 1px white line.)
- photo at x 11.9, y 51.6, w 16.7, h 13.5 [#101010 (device)]: Black handheld controller with phone screen showing Destiny 2 Beyond Light key art (blue sky, silhouetted figures) (Landscape, device-only cutout, not boxed; screen shows the key art image.)
- image at x 13.4, y 52.1, w 7.8, h 6.3: Destiny 2 Beyond Light key art on phone screen (Blue-tinted sky, silhouetted soldier and aircraft, Destiny 2 BEYOND LIGHT logo bottom left; overlapped by the phone body.)
- text at x 22.8, y 54.1, w 4.6, h 3.8 [DIN Pro, Bold for User Input; DIN Pro, Regular for 10ms; font size 1.73% of slide height; #FFFFFF; left aligned]: User Input / 10ms
- line at x 20.3, y 58, w 0.2, h 4.5 [#FFFFFF]: Arrow from gamepad down to Decode stage (Thin 1px white line with downward arrowhead.)
- icon at x 19.2, y 62.8, w 2.3, h 4.2 [#FFFFFF]: Mesh-triangle decode icon (Thin white outline mesh icon.)
- text at x 22.8, y 63.3, w 3.2, h 3.7 [DIN Pro, Bold for Decode; DIN Pro, Regular for 5ms; font size 1.73% of slide height; #FFFFFF; left aligned]: Decode / 5ms
- image at x 11.9, y 69.5, w 8.9, h 7 [#4A8FC8 (dominant blue)]: Destiny 2 Beyond Light key art thumbnail (Render) (Landscape rectangle, not rounded, unboxed; shows blue sky, silhouetted soldier and aircraft with pink light trails; Destiny 2 BEYOND LIGHT logo bottom left.)
- text at x 22.8, y 71.2, w 3.2, h 3.8 [DIN Pro, Bold for Render; DIN Pro, Regular for 10ms; font size 1.73% of slide height; #FFFFFF; left aligned]: Render / 10ms
- line at x 20.3, y 77.5, w 0.2, h 2.5 [#FFFFFF]: Downward arrow below Render thumbnail (Thin 1px white line with downward arrowhead.)
- shape at x 29.3, y 28.5, w 0.8, h 47.5 [none (stroke #FFFFFF)]: Vertical bracket spanning Game Engine to Render (Thin 1px white line with horizontal tick caps at top and bottom.)
- text at x 30.7, y 54.4, w 3.5, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: <100ms
- text at x 44.4, y 25.9, w 9.4, h 3.5 [DIN Pro, Medium, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: TRADITIONAL CLOUD / GAMING SERVER (Two lines, centred over server block.)
- shape at x 37.7, y 31.8, w 22.6, h 28.4 [#0070C9]: Blue rounded-corner server block (Square corners, no shadow, container for server contents.)
- icon at x 38.8, y 33.8, w 20.6, h 4.2 [#FFFFFF]: Gamepad icon row 1, 8 icons (Eight thin white outline gamepad icons evenly spaced.)
- icon at x 38.8, y 37.7, w 20.6, h 4.2 [#FFFFFF]: Gamepad icon row 2, 8 icons (Eight thin white outline gamepad icons evenly spaced.)
- shape at x 38.8, y 43.6, w 6.5, h 5.6 [#0A5AA0]: Dark-blue box Game (Square corners, no border.)
- text at x 40.8, y 45.7, w 2.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Game
- shape at x 45.8, y 43.6, w 6.5, h 5.6 [#0A5AA0]: Dark-blue box Graphics Driver (Square corners, no border.)
- text at x 47.1, y 44.6, w 3.8, h 3.8 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Graphics / Driver (Two lines, centred.)
- shape at x 52.8, y 43.6, w 6.5, h 5.6 [#0A5AA0]: Dark-blue box Video (Square corners, no border.)
- text at x 54.8, y 45.7, w 2.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Video
- shape at x 38.8, y 50.9, w 6.5, h 3.4 [#4A9BD9]: Mid-blue box SDDC (Square corners.)
- text at x 40.8, y 51.9, w 2.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: SDDC
- shape at x 45.8, y 50.9, w 6.5, h 3.4 [#4A9BD9]: Mid-blue box Security (Square corners.)
- text at x 47.3, y 51.9, w 3.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Security
- shape at x 52.8, y 50.9, w 6.5, h 3.4 [#4A9BD9]: Mid-blue box Telemetry (Square corners.)
- text at x 53.9, y 51.9, w 4.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Telemetry
- shape at x 38.8, y 55.1, w 20.6, h 3.4 [#4A9BD9]: Wide mid-blue bar NAT | DDOS | Reverse Proxy (Square corners.)
- text at x 43, y 56.1, w 12, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NAT | DDOS | Reverse Proxy
- shape at x 37.8, y 62, w 22.5, h 3.4 [#808080]: Grey bar Ethernet NIC (Square corners, no border.)
- text at x 46.3, y 63, w 5.6, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Ethernet NIC

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 37.8, y 31.9, w 22.5, h 28.3: 2705 by 1912 pixels
- image at x 8.6, y 51.6, w 13.4, h 8.7: 337 by 123 pixels
- image at x 37.8, y 62.0, w 22.5, h 3.4: 2706 by 228 pixels
- image at x 38.8, y 55.1, w 20.6, h 3.4: 2472 by 228 pixels
- image at x 11.9, y 69.5, w 8.9, h 7.0: 721 by 316 pixels
- image at x 38.8, y 43.6, w 6.5, h 5.6: 786 by 378 pixels
- image at x 45.8, y 43.6, w 6.5, h 5.6: 786 by 378 pixels
- image at x 52.8, y 43.6, w 6.5, h 5.6: 786 by 378 pixels
- image at x 38.8, y 50.9, w 6.5, h 3.4: 786 by 228 pixels
- image at x 45.8, y 50.9, w 6.5, h 3.4: 786 by 228 pixels
- image at x 52.8, y 50.9, w 6.5, h 3.4: 786 by 228 pixels
- image at x 15.9, y 29.3, w 2.3, h 4.2: 283 by 283 pixels
- image at x 19.2, y 62.8, w 2.3, h 4.2: 283 by 283 pixels
- image at x 19.2, y 37.8, w 2.3, h 4.2: 283 by 283 pixels
- image at x 19.2, y 44.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 13.1, y 30.2, w 2.3, h 4.2: 283 by 283 pixels
- image at x 13.1, y 28.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 10.9, y 44.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 44.0, y 33.8, w 2.3, h 4.2: 141 by 141 pixels
- image at x 54.4, y 33.8, w 2.3, h 4.2: 282 by 281 pixels
- image at x 44.0, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 54.4, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 49.2, y 33.8, w 2.3, h 4.2: 282 by 281 pixels
- image at x 57.0, y 33.8, w 2.3, h 4.2: 282 by 281 pixels
- image at x 49.2, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 57.0, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 51.8, y 33.8, w 2.3, h 4.2: 281 by 281 pixels
- image at x 38.8, y 33.8, w 2.3, h 4.2: 281 by 281 pixels
- image at x 38.8, y 37.7, w 2.3, h 4.2: 281 by 281 pixels
- image at x 51.8, y 37.7, w 2.3, h 4.2: 281 by 281 pixels
- image at x 41.4, y 33.8, w 2.3, h 4.2: 141 by 141 pixels
- image at x 46.6, y 33.8, w 2.3, h 4.2: 281 by 281 pixels
- image at x 41.4, y 37.7, w 2.3, h 4.2: 281 by 281 pixels
- image at x 46.6, y 37.7, w 2.3, h 4.2: 281 by 281 pixels
- text at x 11.7, y 7.9, w 76.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
- text at x 20.8, y 12.5, w 58.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
- text at x 8.9, y 25.9, w 7.9, h 1.7 [DINPro-Bold; font size 1.73; #76B900]: GeForce NOW Pod
- text at x 44.4, y 25.9, w 9.4, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: TRADITIONAL CLOUD
- text at x 45.3, y 27.7, w 7.4, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: GAMING SERVER
- text at x 22.8, y 29.6, w 5.8, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Game Engine
- text at x 22.8, y 31.7, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 40ms
- text at x 22.8, y 38.0, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Encode
- text at x 22.8, y 40.0, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5ms
- text at x 47.1, y 44.6, w 3.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Graphics
- text at x 14.4, y 45.8, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 22.8, y 45.8, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 40.8, y 45.7, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Game
- text at x 54.8, y 45.7, w 2.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Video
- text at x 47.7, y 46.7, w 2.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Driver
- text at x 40.8, y 51.9, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SDDC
- text at x 47.3, y 51.9, w 3.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Security
- text at x 53.9, y 51.9, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Telemetry
- text at x 22.8, y 54.1, w 4.6, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: User Input
- text at x 30.7, y 54.4, w 3.5, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: <100ms
- text at x 22.8, y 56.2, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 43.0, y 56.1, w 12.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NAT | DDOS | Reverse Proxy
- text at x 22.8, y 63.3, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Decode
- text at x 46.3, y 63.0, w 5.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Ethernet NIC
- text at x 22.8, y 65.4, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5ms
- text at x 22.8, y 71.2, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Render
- text at x 22.8, y 73.3, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms

### Slide 24

**Text**

BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
GeForce NOW Pod
Game Engine
40ms
Encode
5ms
10ms
10ms
User Input
10ms
<100ms
TRADITIONAL CLOUD
GAMING SERVER
Game
Graphics
Driver
Video
SDDC
Security
Telemetry
NAT | DDOS | Reverse Proxy
Ethernet NIC
BLUEFIELD-ACCELERATED
CLOUD GAMING SERVER
Game
Graphics
Driver
Video
BLUEFIELD-2 DPU
Driver Accelerator
Streamer Accelerator
SDDC
Security
Telemetry
NAT | DDOS | Reverse Proxy
Decode
5ms
Render
10ms

**Layout**

A single full-slide dark stage: the main title is centred at the top in one line, with a centred two-part subtitle line beneath it, and a large dark rectangular panel spans roughly the middle band. Inside the panel three columns run left to right: a vertical latency flow diagram (GeForce NOW Pod, with a bracket labelled <100ms on its right) at the left, a traditional cloud gaming server stack in the centre, and a Bluefield-accelerated server stack with a Bluefield-2 DPU block at the right, with a card photograph overlapping the lower-right corner of the panel. No footer, no slide number and no logo appear on the slide.

**Visuals**

Diagram on the left: a vertical flow with a green-outlined rectangle at top labelled GeForce NOW Pod containing two icons (a stacked-server or GPU icon and a window-with-gear icon) and the label Game Engine 40ms beside it. Arrows point down the right side from Game Engine to Encode (a fan/encoder icon, 5ms) to a stopwatch-cloud icon labelled 10ms, down to a smartphone-style game controller photo (a handheld device with thumbsticks showing a game screenshot of a soldier-style shooter scene), labelled User Input 10ms, then down to Decode (a fan/decoder icon, 5ms), then down to a rectangular game screenshot labelled Render 10ms (Destiny 2 Beyond Light artwork with a figure and a sky scene). An arrow runs from the lower stopwatch-cloud icon back up to Game Engine on the left column, with a stopwatch-cloud icon on the left side beside 10ms. A vertical bracket on the right of the flow spans the whole chain, labelled <100ms. Centre diagram: a large blue rectangle titled Traditional Cloud Gaming Server containing two rows of eight white outline gamepad icons (16 in total), then three dark-blue boxes labelled Game, Graphics Driver, Video, then three mid-blue boxes labelled SDDC, Security, Telemetry, then a full-width mid-blue bar labelled NAT | DDOS | Reverse Proxy; below it a grey bar labelled Ethernet NIC. A bracket with an arrow on its right edge connects this server to the purple DPU block. Right diagram: a large blue rectangle titled Bluefield-Accelerated Cloud Gaming Server containing three rows of eight white outline gamepad icons (24 in total), then three dark-blue boxes labelled Game, Graphics Driver, Video. Below it a purple rectangle titled Bluefield-2 DPU containing two purple boxes labelled Driver Accelerator and Streamer Accelerator, then three purple boxes labelled SDDC, Security, Telemetry, then a full-width purple bar labelled NAT | DDOS | Reverse Proxy. A thin white elbow arrow runs from the traditional server's bracket down and right to the DPU block's left edge. Photograph lower centre-right: a black NVIDIA Bluefield-2 DPU PCIe card, shown at an angle, with a grey heatsink and a square chip labelled NVIDIA, overlapping the bottom of the DPU box and the panel edge; lit from above with dark grey and black tones and a soft reflection on the dark floor below.

**Design**

Background: Near-black gradient (#000000 at top to #1A1A1A around the panel) with a dark grey floor (#2B2B2B) and soft reflection at the bottom, behind a full-bleed photograph of the dark stage. Dark charcoal and black background with a subtle floor reflection; the whole look is a dark product-keynote style. Main title is white (#FFFFFF) DIN Pro Bold, all capitals, about 4.1% of slide height, centred. Subtitle is white DIN Pro Regular, about 2.7% of slide height, centred, with vertical bar separators. Panel is a near-black rectangle (#141414) with a thin grey-brown border (about #5A5550, 1px). Accent green #76B900 used for the GeForce NOW Pod heading and its outline box (1px, square corners). Column headings are white DIN Pro Medium capitals, about 1.7% of slide height. Labels are DIN Pro Bold for stage names and DIN Pro Regular for times and component labels, white, about 1.7%. Traditional server box fill #0070C9-like blue with darker blue (#0A5A9C) sub-boxes for Game, Graphics Driver and Video, lighter blue (#4A9FE0) for SDDC, Security, Telemetry and NAT bar. Bluefield-accelerated blue box uses the same blue palette. Ethernet NIC bar is mid grey #808080. Bluefield-2 DPU box is purple #6A2BB5 with lighter purple (#8A4FD0) sub-boxes. Shapes have square corners and no shadows; connectors are thin white lines with small arrowheads.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#101010]: Full-bleed dark stage background photograph with floor reflection (covers slide) (not cropped, full-bleed, no overlay)
- shape at x 3.8, y 21.6, w 92.4, h 61.5 [#141414]: Dark stage panel rectangle (square corners, 1px border about #5A5550, no shadow)
- title at x 11.7, y 7.9, w 76.6, h 4.1 [DIN Pro, Bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
- subtitle at x 20.8, y 12.5, w 58.4, h 2.7 [DIN Pro, Regular; font size 2.72% of slide height; #FFFFFF; center aligned]: Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
- text at x 8.9, y 25.9, w 7.9, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #76B900; left aligned]: GeForce NOW Pod
- shape at x 8.6, y 28.5, w 13, h 5.7 [#000000]: GeForce NOW Pod outline box with stacked-server icon and gear-window icon (no fill, 2px green #76B900 outline, square corners)
- icon at x 13.1, y 29.3, w 5.8, h 4.2 [#FFFFFF]: Game engine icons: stacked-server/GPU icon and window-with-gear icon, white line art (thin white outline strokes)
- text at x 22.8, y 29.6, w 5.8, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: Game Engine
- text at x 22.8, y 31.7, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 40ms
- line at x 12, y 35.5, w 0.1, h 10 [#FFFFFF]: Vertical arrow from User Input stopwatch icon up to GeForce NOW Pod box (1px white line with upward arrowhead at top)
- icon at x 19.2, y 37.8, w 2.3, h 4.2 [#8A8A8A]: Encode fan icon, grey wireframe (wireframe fan/encoder glyph)
- text at x 22.8, y 38, w 3.2, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: Encode
- text at x 22.8, y 40, w 1.8, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 5ms
- icon at x 10.9, y 44.5, w 2.3, h 4.2 [#FFFFFF]: Stopwatch-in-cloud icon, white line art (left, beside User Input) (thin outline)
- icon at x 19.2, y 44.5, w 2.3, h 4.2 [#FFFFFF]: Stopwatch-in-cloud icon, white line art (right, beside Encode line) (thin outline)
- text at x 14.4, y 45.8, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- text at x 22.8, y 45.8, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- photo at x 8.6, y 51.6, w 13.4, h 8.7 [#1E2A3A]: Smartphone-style game controller photo showing a shooter game screenshot on screen with thumbsticks and buttons, dark grey body (not cropped, boxed, no overlay, lit from above)
- text at x 22.8, y 54.1, w 4.6, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: User Input
- text at x 22.8, y 56.2, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- text at x 30.7, y 54.4, w 3.5, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: <100ms
- line at x 29.3, y 28.5, w 0.6, h 47.8 [#FFFFFF]: Vertical bracket spanning the latency chain, with end ticks (1px white line with short horizontal end caps)
- icon at x 19.2, y 62.8, w 2.3, h 4.2 [#8A8A8A]: Decode fan icon, grey wireframe (wireframe glyph)
- text at x 22.8, y 63.3, w 3.2, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: Decode
- text at x 22.8, y 65.4, w 1.8, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 5ms
- photo at x 11.9, y 69.5, w 8.9, h 7 [#2A3A5A]: Game screenshot rectangle showing a Destiny 2 Beyond Light artwork: a silhouetted figure with a rifle in the foreground and a sky with a glowing ship in the background, with the Destiny 2 Beyond Light logo at bottom left (not cropped, boxed, no overlay)
- text at x 22.8, y 71.2, w 3.2, h 1.7 [DIN Pro, Bold; font size 1.73% of slide height; #FFFFFF; left aligned]: Render
- text at x 22.8, y 73.3, w 2.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: 10ms
- line at x 19, y 28, w 0.5, h 45 [#FFFFFF]: Downward arrows linking Game Engine, Encode, User Input, Decode, Render in a vertical chain (1px white lines with arrowheads)
- text at x 44.4, y 25.8, w 9.4, h 3.5 [DIN Pro, Medium, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: TRADITIONAL CLOUD / GAMING SERVER
- shape at x 37.8, y 31.9, w 22.5, h 28.3 [#0070C9]: Traditional cloud gaming server blue box (square corners, no shadow)
- icon at x 38.8, y 33.8, w 20.6, h 10 [#FFFFFF]: Sixteen white outline gamepad icons in two rows of eight (thin outline icons, evenly spaced)
- shape at x 38.8, y 43.6, w 6.5, h 5.6 [#0A5A9C]: Game box (square corners)
- text at x 40.8, y 45.7, w 2.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Game
- shape at x 45.8, y 43.6, w 6.5, h 5.6 [#0A5A9C]: Graphics Driver box (square corners)
- text at x 45.8, y 44.6, w 6.5, h 3.5 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Graphics / Driver
- shape at x 52.8, y 43.6, w 6.5, h 5.6 [#0A5A9C]: Video box (square corners)
- text at x 54.8, y 45.7, w 2.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Video
- shape at x 38.8, y 50.9, w 6.5, h 3.4 [#4A9FE0]: SDDC box (square corners)
- text at x 40.8, y 51.9, w 2.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: SDDC
- shape at x 45.8, y 50.9, w 6.5, h 3.4 [#4A9FE0]: Security box (square corners)
- text at x 47.3, y 51.9, w 3.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Security
- shape at x 52.8, y 50.9, w 6.5, h 3.4 [#4A9FE0]: Telemetry box (square corners)
- text at x 53.9, y 51.9, w 4.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Telemetry
- shape at x 38.8, y 55.1, w 20.6, h 3.4 [#4A9FE0]: NAT | DDOS | Reverse Proxy bar (square corners)
- text at x 43, y 56.1, w 12, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NAT | DDOS | Reverse Proxy
- shape at x 37.8, y 62, w 22.5, h 3.4 [#808080]: Ethernet NIC grey bar (square corners)
- text at x 46.3, y 63, w 5.6, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Ethernet NIC
- text at x 72.1, y 25.8, w 12, h 3.5 [DIN Pro, Medium, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: BLUEFIELD-ACCELERATED / CLOUD GAMING SERVER
- shape at x 66.8, y 31.9, w 22.5, h 22.8 [#0070C9]: Bluefield-accelerated cloud gaming server blue box (square corners, no shadow)
- icon at x 67.8, y 33.8, w 20.6, h 13.2 [#FFFFFF]: Twenty-four white outline gamepad icons in three rows of eight (thin outline icons, evenly spaced)
- shape at x 67.8, y 47.4, w 6.5, h 5.6 [#0A5A9C]: Game box (square corners)
- text at x 69.8, y 49.5, w 2.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Game
- shape at x 74.8, y 47.4, w 6.5, h 5.6 [#0A5A9C]: Graphics Driver box (square corners)
- text at x 74.8, y 48.5, w 6.5, h 3.5 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Graphics / Driver
- shape at x 81.8, y 47.4, w 6.5, h 5.6 [#0A5A9C]: Video box (square corners)
- text at x 83.8, y 49.5, w 2.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Video
- text at x 74, y 57.8, w 8.1, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: BLUEFIELD-2 DPU
- shape at x 66.8, y 56.6, w 22.5, h 17.4 [#6A2BB5]: Bluefield-2 DPU purple box (square corners, no shadow)
- shape at x 67.8, y 60.4, w 10.1, h 3.4 [#8A4FD0]: Driver Accelerator box (square corners)
- text at x 68.9, y 61.4, w 7.9, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Driver Accelerator
- shape at x 78.3, y 60.4, w 10.1, h 3.4 [#8A4FD0]: Streamer Accelerator box (square corners)
- text at x 78.7, y 61.4, w 9.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Streamer Accelerator
- shape at x 67.8, y 64.6, w 6.5, h 3.4 [#8A4FD0]: SDDC box (square corners)
- text at x 69.8, y 65.6, w 2.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: SDDC
- shape at x 74.8, y 64.6, w 6.5, h 3.4 [#8A4FD0]: Security box (square corners)
- text at x 76.3, y 65.6, w 3.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Security
- shape at x 81.8, y 64.6, w 6.5, h 3.4 [#8A4FD0]: Telemetry box (square corners)
- text at x 83, y 65.6, w 4.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Telemetry
- shape at x 67.8, y 68.8, w 20.6, h 3.4 [#8A4FD0]: NAT | DDOS | Reverse Proxy bar (square corners)
- text at x 72.1, y 69.8, w 12, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NAT | DDOS | Reverse Proxy
- line at x 60.8, y 57, w 6.5, h 13 [#FFFFFF]: Elbow connector from traditional server bracket to DPU box with arrowhead (1px white line, arrowhead pointing right at DPU left edge)
- photo at x 50, y 63.7, w 35.3, h 36.3 [#1A1A1A]: Black NVIDIA Bluefield-2 DPU PCIe card at an angle with grey heatsink and square chip labelled NVIDIA (not cropped, overlaps lower edge of the stage panel and DPU box, dark lighting from above, no overlay)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 50.0, y 63.7, w 35.3, h 36.3: 1355 by 785 pixels
- image at x 37.8, y 31.9, w 22.5, h 28.3: 2705 by 1912 pixels
- image at x 66.8, y 31.9, w 22.5, h 22.8: 2705 by 1541 pixels
- image at x 66.8, y 56.6, w 22.5, h 17.4: 2706 by 1176 pixels
- image at x 8.6, y 51.6, w 13.4, h 8.7: 169 by 62 pixels
- image at x 37.8, y 62.0, w 22.5, h 3.4: 2706 by 228 pixels
- image at x 67.8, y 68.8, w 20.6, h 3.4: 2472 by 228 pixels
- image at x 38.8, y 55.1, w 20.6, h 3.4: 2472 by 228 pixels
- image at x 11.9, y 69.5, w 8.9, h 7.0: 721 by 316 pixels
- image at x 67.8, y 47.4, w 6.5, h 5.6: 786 by 378 pixels
- image at x 74.8, y 47.4, w 6.5, h 5.6: 786 by 378 pixels
- image at x 81.8, y 47.4, w 6.5, h 5.6: 786 by 378 pixels
- image at x 38.8, y 43.6, w 6.5, h 5.6: 786 by 378 pixels
- image at x 45.8, y 43.6, w 6.5, h 5.6: 786 by 378 pixels
- image at x 52.8, y 43.6, w 6.5, h 5.6: 786 by 378 pixels
- image at x 78.3, y 60.4, w 10.1, h 3.4: 1209 by 228 pixels
- image at x 67.8, y 60.4, w 10.1, h 3.4: 1209 by 228 pixels
- image at x 67.8, y 64.6, w 6.5, h 3.4: 786 by 228 pixels
- image at x 74.8, y 64.6, w 6.5, h 3.4: 786 by 228 pixels
- image at x 81.8, y 64.6, w 6.5, h 3.4: 786 by 228 pixels
- image at x 38.8, y 50.9, w 6.5, h 3.4: 786 by 228 pixels
- image at x 45.8, y 50.9, w 6.5, h 3.4: 786 by 228 pixels
- image at x 52.8, y 50.9, w 6.5, h 3.4: 786 by 228 pixels
- image at x 15.9, y 29.3, w 2.3, h 4.2: 283 by 283 pixels
- image at x 19.2, y 62.8, w 2.3, h 4.2: 36 by 36 pixels
- image at x 19.2, y 37.8, w 2.3, h 4.2: 283 by 283 pixels
- image at x 19.2, y 44.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 13.1, y 30.2, w 2.3, h 4.2: 283 by 283 pixels
- image at x 13.1, y 28.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 10.9, y 44.5, w 2.3, h 4.2: 283 by 283 pixels
- image at x 70.4, y 33.8, w 2.3, h 4.2: 282 by 281 pixels
- image at x 75.6, y 33.8, w 2.3, h 4.2: 282 by 281 pixels
- image at x 80.8, y 33.8, w 2.3, h 4.2: 282 by 281 pixels
- image at x 70.4, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 75.6, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 80.8, y 37.7, w 2.3, h 4.2: 282 by 281 pixels
- image at x 70.4, y 41.5, w 2.3, h 4.2: 282 by 281 pixels
- image at x 75.6, y 41.5, w 2.3, h 4.2: 282 by 281 pixels
- text at x 11.7, y 7.9, w 76.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: BLUEFIELD SECURES AND ACCELERATES GEFORCE NOW CLOUD GAMING
- text at x 20.8, y 12.5, w 58.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Isolate and Secure Infrastructure | High Quality-of-Service | More Concurrent Users
- text at x 8.9, y 25.9, w 7.9, h 1.7 [DINPro-Bold; font size 1.73; #76B900]: GeForce NOW Pod
- text at x 44.4, y 25.8, w 9.4, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: TRADITIONAL CLOUD
- text at x 72.1, y 25.8, w 12.0, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: BLUEFIELD-ACCELERATED
- text at x 45.3, y 27.7, w 7.4, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: GAMING SERVER
- text at x 72.7, y 27.7, w 10.7, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: CLOUD GAMING SERVER
- text at x 22.8, y 29.6, w 5.8, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Game Engine
- text at x 22.8, y 31.7, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 40ms
- text at x 22.8, y 38.0, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Encode
- text at x 22.8, y 40.0, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5ms
- text at x 47.1, y 44.6, w 3.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Graphics
- text at x 14.4, y 45.8, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 22.8, y 45.8, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 40.8, y 45.7, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Game
- text at x 54.8, y 45.7, w 2.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Video
- text at x 47.7, y 46.7, w 2.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Driver
- text at x 76.2, y 48.5, w 3.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Graphics
- text at x 69.8, y 49.5, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Game
- text at x 83.8, y 49.5, w 2.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Video
- text at x 76.8, y 50.5, w 2.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Driver
- text at x 40.8, y 51.9, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SDDC
- text at x 47.3, y 51.9, w 3.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Security
- text at x 53.9, y 51.9, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Telemetry
- text at x 22.8, y 54.1, w 4.6, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: User Input
- text at x 30.7, y 54.4, w 3.5, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: <100ms
- text at x 22.8, y 56.2, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms
- text at x 43.0, y 56.1, w 12.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NAT | DDOS | Reverse Proxy
- text at x 74.0, y 57.8, w 8.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: BLUEFIELD-2 DPU
- text at x 68.9, y 61.4, w 7.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Driver Accelerator
- text at x 78.7, y 61.4, w 9.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Streamer Accelerator
- text at x 22.8, y 63.3, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Decode
- text at x 46.3, y 63.0, w 5.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Ethernet NIC
- text at x 22.8, y 65.4, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5ms
- text at x 69.8, y 65.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SDDC
- text at x 76.3, y 65.6, w 3.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Security
- text at x 83.0, y 65.6, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Telemetry
- text at x 72.1, y 69.8, w 12.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NAT | DDOS | Reverse Proxy
- text at x 22.8, y 71.2, w 3.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: Render
- text at x 22.8, y 73.3, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10ms

### Slide 25

**Text**

ANNOUNCING
DOCA 1.0 AND BLUEFIELD
PARTNER ECOSYSTEM
Data Center on a Chip Architecture
Software Development Framework for BlueField DPUs
Offload, Accelerate, and Isolate Infrastructure Processing
Support for Hyperscale, Enterprise, Supercomputing and
Hyperconverged Infrastructure
Transparent Offload and Acceleration of VMware ESX
Software Compatibility for Generations of BlueField DPUs
SOFTWARE-DEFINED
INFRASTRUCTURE
STORAGE
CYBER
SECURITY
EDGE
CANONICAL
Red Hat
vmware
ddn
Excelero
NetApp
VAST
WEKA
Check Point
FORTINET
Guardicore
paloalto
BROADBRIDGE NETWORKS
CLOUDFLARE
Juniper
F5
DOCA
ORCHESTRATION
SECURITY
NETWORKING
STORAGE
MANAGEMENT
ACCELERATION LIBRARIES
TELEMETRY

**Layout**

Two-zone layout: a left text column starting about 6.7% from the left edge with the title block at roughly 29% to 46% of slide height and five bullet lines from 47% to 70%, and a right-hand block of four equal-width columns at 47.8% to 96% of width, rows from 13% to 50%, with a green DOCA panel below spanning 47.8% to 96% at 52% to 77%. The slide has no visible footer, page number or logo; the left column is vertically centred on the slide's lower-middle area.

**Visuals**

Four dark vertical cards: Software-Defined Infrastructure (Canonical, Red Hat, VMware), Storage (DDN, Excelero, NetApp, VAST, WEKA), Cyber Security (Check Point Software Technologies Ltd., Fortinet, Guardicore, Palo Alto Networks), and Edge (Broadbridge Networks, Cloudflare, Juniper Networks, F5), each with its heading and logos in white. Below them is a green DOCA panel with a DOCA heading over a grid: Orchestration, Management and Telemetry stacked in the left column; Security, Networking and Storage across the top right; Acceleration Libraries spanning the bottom right. Overlapping the lower edge of the panel is a photographic render of a black NVIDIA BlueField DPU card (PCIe card with a central grey NVIDIA-branded heatsink chip, black PCB, silver cages and gold edge connector), angled slightly, lit from above with a soft shadow on a dark floor. The card is not cropped and is not boxed.

**Design**

Background: Black (#000000) to charcoal (#2A2A2A) gradient photographic studio background, full-bleed. Black background (#000000) fading to dark charcoal (#2A2A2A) at the floor with soft reflection; titles white #FFFFFF in DIN Pro Regular/Bold style sans-serif, uppercase for main title (about 4.1% of slide height, roughly 7.0% for capitals), body text white #FFFFFF in DIN Pro Regular about 2.2% of slide height, column headings gold #B3914C in DIN Pro Medium about 1.7%. Accent green #76B900 for the DOCA panel and its sub-boxes, with darker green #5A8F00 bottom edges. Column cards are near-black #111111 with thin gold-brown #B3914C borders and a green bottom line; corners square, no shadows, no gradients on cards.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#111111]: Full-bleed dark studio background image (3840 by 2160 px), black at top fading to charcoal grey floor with soft reflections (Covers the slide; a white #FFFFFF fill lies underneath it)
- shape at x 47.75, y 13.3, w 11.15, h 36.4 [#111111]: Column card: Software-Defined Infrastructure (Rectangle, square corners, 1 pt stroke #B3914C, green #76B900 bottom edge line)
- shape at x 60.1, y 13.3, w 11.15, h 36.4 [#111111]: Column card: Storage (Rectangle, square corners, 1 pt stroke #B3914C, green #76B900 bottom edge line)
- shape at x 72.35, y 13.3, w 11.15, h 36.4 [#111111]: Column card: Cyber Security (Rectangle, square corners, 1 pt stroke #B3914C, green #76B900 bottom edge line)
- shape at x 84.85, y 13.3, w 11.15, h 36.4 [#111111]: Column card: Edge (Rectangle, square corners, 1 pt stroke #B3914C, green #76B900 bottom edge line)
- shape at x 47.75, y 51.9, w 48.25, h 24.7 [#76B900]: DOCA panel (Solid green rectangle, square corners, no shadow)
- image at x 47.6, y 52, w 48.5, h 4.9 [#76B900]: DOCA header bar (Measured image 5825 by 334 px, green)
- text at x 70, y 53.9, w 3.9, h 2.7 [DIN Pro Regular; font size 2.72% of slide height; #FFFFFF; center aligned]: DOCA
- shape at x 48.6, y 57.9, w 11.3, h 5 [#76B900]: Sub-box: Orchestration (Darker green bottom edge, square corners)
- shape at x 48.6, y 63.4, w 11.3, h 5 [#76B900]: Sub-box: Management (Darker green bottom edge, square corners)
- shape at x 48.6, y 68.8, w 11.3, h 5 [#76B900]: Sub-box: Telemetry (Darker green bottom edge, square corners)
- shape at x 60.8, y 60.2, w 11.3, h 3.5 [#76B900]: Sub-box: Security (Darker green bottom edge, square corners)
- shape at x 72.4, y 60.2, w 11.3, h 3.5 [#76B900]: Sub-box: Networking (Darker green bottom edge, square corners)
- shape at x 84, y 60.2, w 11.3, h 3.5 [#76B900]: Sub-box: Storage (Darker green bottom edge, square corners)
- shape at x 60.8, y 66.5, w 34.9, h 7.6 [#76B900]: Sub-box: Acceleration Libraries (Darker green bottom edge, square corners)
- image at x 60.8, y 68.1, w 34.5, h 4.1 [#76B900]: Acceleration libraries bar (Measured image 4146 by 277 px)
- photo at x 56, y 71.1, w 16, h 20.5 [#1A1A1A]: NVIDIA BlueField DPU card render: black PCB PCIe card with grey NVIDIA-branded heatsink chip, silver cages and gold edge connector, angled, lit from above, soft shadow on dark floor (Not cropped, not boxed, overlaps lower edge of DOCA panel)
- text at x 6.7, y 29.3, w 10.6, h 3 [DIN Pro Bold, uppercase; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING
- text at x 6.7, y 32.6, w 27.8, h 4.1 [DIN Pro Regular, uppercase; font size 4.07% of slide height; #FFFFFF; left aligned]: DOCA 1.0 AND BLUEFIELD
- text at x 6.7, y 37, w 23.4, h 4.1 [DIN Pro Regular, uppercase; font size 4.07% of slide height; #FFFFFF; left aligned]: PARTNER ECOSYSTEM
- text at x 6.7, y 41.6, w 23.6, h 2.7 [DIN Pro Regular; font size 2.72% of slide height; #FFFFFF; left aligned]: Data Center on a Chip Architecture
- text at x 6.7, y 47.2, w 30.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Software Development Framework for BlueField DPUs
- text at x 6.7, y 51.9, w 31.9, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Offload, Accelerate, and Isolate Infrastructure Processing
- text at x 6.7, y 56.7, w 31.8, h 4.6 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Support for Hyperscale, Enterprise, Supercomputing and / Hyperconverged Infrastructure
- text at x 6.7, y 63.8, w 29.4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Transparent Offload and Acceleration of VMware ESX
- text at x 6.7, y 68.6, w 31.9, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Software Compatibility for Generations of BlueField DPUs
- text at x 48.6, y 15.6, w 11, h 4.2 [DIN Pro Medium, uppercase; font size 1.73% of slide height; #B3914C; center aligned]: SOFTWARE-DEFINED / INFRASTRUCTURE
- text at x 63.6, y 16.6, w 4.2, h 1.7 [DIN Pro Medium, uppercase; font size 1.73% of slide height; #B3914C; center aligned]: STORAGE
- text at x 75.7, y 15.6, w 7, h 4.2 [DIN Pro Medium, uppercase; font size 1.73% of slide height; #B3914C; center aligned]: CYBER / SECURITY
- text at x 89, y 16.6, w 2.4, h 1.7 [DIN Pro Medium, uppercase; font size 1.73% of slide height; #B3914C; center aligned]: EDGE
- logo at x 49.9, y 24.3, w 7.1, h 1.7: Canonical logo, white (White wordmark on dark card)
- logo at x 50, y 32.8, w 7.1, h 3: Red Hat logo, white (hat and wordmark) (White wordmark on dark card)
- logo at x 50.2, y 42.6, w 6.6, h 1.9: VMware logo, white (White wordmark on dark card)
- logo at x 63.9, y 23.8, w 4.1, h 2.6: DDN logo, white (White ring and wordmark)
- logo at x 63.2, y 28.3, w 5.5, h 3: Excelero logo, white (White wordmark)
- logo at x 63.1, y 33.2, w 5.7, h 1.8: NetApp logo, white (White wordmark)
- logo at x 62.8, y 36.8, w 6.2, h 3.3: VAST Data logo, white (White wordmark)
- logo at x 63.1, y 42.1, w 5.6, h 3: WEKA logo, white (White wordmark)
- logo at x 73.7, y 23.1, w 8.4, h 4: Check Point Software Technologies Ltd. logo, white (White wordmark with small sub-line)
- logo at x 74.3, y 30.1, w 7.2, h 2.1: Fortinet logo, white (White wordmark)
- logo at x 74.1, y 35.2, w 7.1, h 3.2: Guardicore logo, white (White wordmark with grey emblem)
- logo at x 73.4, y 41.5, w 8.6, h 4.2: Palo Alto Networks logo, white (White wordmark with emblem)
- logo at x 86.9, y 23.5, w 6.7, h 3.1: Broadbridge Networks logo, grey (Grey dotted emblem with wordmark)
- logo at x 87.1, y 28.5, w 6.3, h 3.8: Cloudflare logo, white (White cloud emblem with wordmark)
- logo at x 87.7, y 34.2, w 5.4, h 4.8: Juniper Networks logo, white (White wordmark)
- logo at x 88.1, y 40.9, w 4.5, h 5.4: F5 logo, white (White circular F5 emblem)
- text at x 50.5, y 59.7, w 7.6, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: ORCHESTRATION
- text at x 64.2, y 61.2, w 4.4, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: SECURITY
- text at x 75, y 61.2, w 6.2, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: NETWORKING
- text at x 87.6, y 61.2, w 4.1, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: STORAGE
- text at x 51, y 65.2, w 6.5, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: MANAGEMENT
- text at x 72.1, y 69.4, w 11.9, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: ACCELERATION LIBRARIES
- text at x 51.6, y 70.6, w 5.3, h 1.7 [DIN Pro Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: TELEMETRY

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 47.6, y 52.0, w 48.5, h 4.9: 5825 by 334 pixels
- image at x 60.8, y 68.1, w 34.5, h 4.1: 4146 by 277 pixels
- image at x 48.6, y 57.9, w 11.3, h 5.0: 1356 by 340 pixels
- image at x 48.6, y 68.8, w 11.3, h 5.0: 1356 by 340 pixels
- image at x 48.6, y 63.4, w 11.3, h 5.0: 1356 by 339 pixels
- image at x 60.8, y 60.2, w 11.3, h 3.5: 1357 by 237 pixels
- image at x 72.4, y 60.2, w 11.3, h 3.5: 1357 by 237 pixels
- image at x 84.0, y 60.2, w 11.3, h 3.5: 1357 by 237 pixels
- image at x 73.4, y 41.5, w 8.6, h 4.2: 184 by 56 pixels
- image at x 73.7, y 23.1, w 8.4, h 4.0: 600 by 160 pixels
- image at x 87.7, y 34.2, w 5.4, h 4.8: 318 by 159 pixels
- image at x 87.1, y 28.5, w 6.3, h 3.8: 600 by 204 pixels
- image at x 88.1, y 40.9, w 4.5, h 5.4: 275 by 183 pixels
- image at x 74.1, y 35.2, w 7.1, h 3.2: 856 by 218 pixels
- image at x 50.0, y 32.8, w 7.1, h 3.0: 1227 by 290 pixels
- image at x 86.9, y 23.5, w 6.7, h 3.1: 512 by 136 pixels
- image at x 62.8, y 36.8, w 6.2, h 3.3: 371 by 113 pixels
- image at x 63.1, y 42.1, w 5.6, h 3.0: 500 by 152 pixels
- image at x 63.2, y 28.3, w 5.5, h 3.0: 199 by 61 pixels
- image at x 74.3, y 30.1, w 7.2, h 2.1: 449 by 80 pixels
- image at x 50.2, y 42.6, w 6.6, h 1.9: 396 by 65 pixels
- image at x 49.9, y 24.3, w 7.1, h 1.7: 600 by 80 pixels
- image at x 63.9, y 23.8, w 4.1, h 2.6: 257 by 93 pixels
- image at x 63.1, y 33.2, w 5.7, h 1.8: 1000 by 176 pixels
- image at x 65.5, y 23.8, w 2.5, h 2.6: 156 by 93 pixels
- text at x 6.7, y 32.6, w 27.8, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: DOCA 1.0 AND BLUEFIELD
- text at x 6.7, y 37.0, w 23.4, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: PARTNER ECOSYSTEM
- text at x 48.6, y 15.6, w 9.4, h 1.7 [DINPro-Medium; font size 1.73; #B3914C]: SOFTWARE-DEFINED
- text at x 76.4, y 15.6, w 3.2, h 1.7 [DINPro-Medium; font size 1.73; #B3914C]: CYBER
- text at x 63.6, y 16.6, w 4.2, h 1.7 [DINPro-Medium; font size 1.73; #B3914C]: STORAGE
- text at x 89.0, y 16.6, w 2.4, h 1.7 [DINPro-Medium; font size 1.73; #B3914C]: EDGE
- text at x 6.7, y 29.3, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 49.2, y 17.6, w 8.2, h 1.7 [DINPro-Medium; font size 1.73; #B3914C]: INFRASTRUCTURE
- text at x 75.7, y 17.6, w 4.6, h 1.7 [DINPro-Medium; font size 1.73; #B3914C]: SECURITY
- text at x 6.7, y 41.6, w 23.6, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Data Center on a Chip Architecture
- text at x 70.0, y 53.9, w 3.9, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: DOCA
- text at x 6.7, y 47.2, w 30.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Software Development Framework for BlueField DPUs
- text at x 6.7, y 51.9, w 31.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Offload, Accelerate, and Isolate Infrastructure Processing
- text at x 6.7, y 56.7, w 31.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Support for Hyperscale, Enterprise, Supercomputing and
- text at x 6.7, y 59.1, w 17.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Hyperconverged Infrastructure
- text at x 6.7, y 63.8, w 29.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Transparent Offload and Acceleration of VMware ESX
- text at x 6.7, y 68.6, w 31.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Software Compatibility for Generations of BlueField DPUs
- text at x 50.5, y 59.7, w 7.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ORCHESTRATION
- text at x 64.2, y 61.2, w 4.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SECURITY
- text at x 75.0, y 61.2, w 6.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NETWORKING
- text at x 87.6, y 61.2, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: STORAGE
- text at x 51.0, y 65.2, w 6.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MANAGEMENT
- text at x 72.1, y 69.4, w 11.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ACCELERATION LIBRARIES
- text at x 51.6, y 70.6, w 5.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TELEMETRY

### Slide 26

**Text**

ANNOUNCING
NVIDIA BLUEFIELD-3
400 Gbps Data Center Infra Processor
Offloads and Accelerates Data Center Infrastructure
Isolates Application from Control and Management Plane
Powerful CPU – 16x Arm A78 Cores
Process Networking, Storage, and Security at 400 Gbps
22 Billion Transistors
DATA PATH ACCELERATOR
DDR5 MEMORY INTERFACE
CONNECTX-7
ARM CORES
PCIe GEN 5.0
ACCELERATION
ENGINES

**Layout**

Full-bleed dark photographic slide with the text block on the left half, vertically centred, left-aligned at about 6.7% from the slide edge. A chip photograph sits on the right, tilted in perspective, with six callout labels around it: left-column labels at x 41.5% and right-column labels right-aligned to about 95% of the width, each with a thin leader line running to a point on the chip. No title bar, footer, logo or slide number is present.

**Visuals**

A tilted, perspective photograph of a single NVIDIA BlueField-3 processor die, a dark rectangular package with a thin grey-black bevelled frame, seen at a slight angle with its lower edge reflected faintly on a dark glossy floor. The die shows a dense colour-mapped micrograph-like layout: blocks of gold, orange, magenta, purple, green and yellow-green circuitry, with regular grid patterns of cores and memory arrays. Six callouts with thin white leader lines: DATA PATH ACCELERATOR (line from label at top-left of chip to the upper-centre purple/blue block); CONNECTX-7 (line from label at left to the upper-left yellow block); PCIe GEN 5.0 (line from label to the lower-left orange I/O strip); DDR5 MEMORY INTERFACE (line from label to the top edge of the chip near the green strip); ARM CORES (line from label to the magenta-purple core array on the right); ACCELERATION ENGINES (line from label to the green lower-right block). Lighting is a dark studio spotlight on the die with soft highlights; the surrounding background is near-black to dark grey.

**Design**

Background: Near-black (#000000) to dark charcoal (#2A2A2A) vertical gradient with a faint reflective floor. Black background fading to dark charcoal grey toward the bottom. Titles in white (#FFFFFF), body text white (#FFFFFF), callout labels white (#FFFFFF), leader lines white thin strokes (about 1 px). Typeface is DIN Pro, a geometric grotesque sans-serif: ANNOUNCING in DIN Pro Bold capitals, NVIDIA BLUEFIELD-3 in DIN Pro Regular capitals (about 4.1% of slide height, cap height about 0.7 of that), subtitle 400 Gbps Data Center Infra Processor in DIN Pro Regular (about 2.7% of slide height), body bullets in DIN Pro Regular (about 2.2% of slide height). Callout labels in DIN Pro Regular capitals about 1.7% of slide height. Generous line spacing between bullets. No corner radii or shadows on text; the chip has a soft drop shadow beneath.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Background photographic backdrop, black to dark grey gradient with faint floor reflection, full slide (Full-bleed, behind everything; second image layer identical in extent.)
- photo at x 29, y 14, w 54, h 66 [#2A2A2A]: Photograph of NVIDIA BlueField-3 processor die in tilted perspective, colour-mapped circuitry in gold, magenta, green and yellow tones within dark bevelled frame (Unboxed, not cropped; dark grey frame edge; soft shadow and reflection beneath; overlaps leader lines at their endpoints.)
- title at x 6.7, y 32.6, w 21.9, h 4.1 [DIN Pro Regular, capitals; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA BLUEFIELD-3
- subtitle at x 6.7, y 29.3, w 10.6, h 3 [DIN Pro Bold, capitals; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING (Sits above the title.)
- subtitle at x 6.7, y 37.2, w 25.6, h 2.7 [DIN Pro Regular; font size 2.72% of slide height; #FFFFFF; left aligned]: 400 Gbps Data Center Infra Processor
- body at x 6.7, y 42.6, w 28.9, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Offloads and Accelerates Data Center Infrastructure (Bullet-free list line; line spacing about 4.7% of slide height between items.)
- body at x 6.7, y 47.4, w 31.7, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Isolates Application from Control and Management Plane (Bullet-free list line.)
- body at x 6.7, y 52.1, w 19.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Powerful CPU – 16x Arm A78 Cores (Bullet-free list line.)
- body at x 6.7, y 56.9, w 30.5, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Process Networking, Storage, and Security at 400 Gbps (Bullet-free list line.)
- body at x 6.7, y 61.6, w 11.9, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 22 Billion Transistors (Bullet-free list line.)
- line at x 41.5, y 17.5, w 11.5, h 10.5 [#FFFFFF]: Leader line from DATA PATH ACCELERATOR label to upper-centre block of chip (Thin white stroke about 1 px; horizontal segment under label then diagonal down-right.)
- line at x 63, y 17.5, w 20, h 10 [#FFFFFF]: Leader line from DDR5 MEMORY INTERFACE label to top edge of chip (Thin white stroke about 1 px; horizontal segment under label then diagonal down-left.)
- line at x 41.5, y 27.5, w 10, h 12 [#FFFFFF]: Leader line from CONNECTX-7 label to upper-left block of chip (Thin white stroke about 1 px; horizontal segment under label then diagonal down-right.)
- line at x 65, y 22, w 35, h 18 [#FFFFFF]: Leader line from ARM CORES label to magenta core array (Thin white stroke about 1 px; horizontal segment under label then diagonal down-left.)
- line at x 41.5, y 37.5, w 10, h 12 [#FFFFFF]: Leader line from PCIe GEN 5.0 label to lower-left I/O strip (Thin white stroke about 1 px; horizontal segment under label then diagonal down-right.)
- line at x 59, y 46, w 32, h 20 [#FFFFFF]: Leader line from ACCELERATION ENGINES label to green lower-right block (Thin white stroke about 1 px; horizontal segment under label then diagonal down-left.)
- label at x 41.5, y 16, w 11.5, h 1.7 [DIN Pro Regular, capitals; font size 1.73% of slide height; #FFFFFF; left aligned]: DATA PATH ACCELERATOR (Callout label.)
- label at x 83.1, y 16, w 11.9, h 1.7 [DIN Pro Regular, capitals; font size 1.73% of slide height; #FFFFFF; right aligned]: DDR5 MEMORY INTERFACE (Callout label.)
- label at x 41.5, y 26.3, w 5.8, h 1.7 [DIN Pro Regular, capitals; font size 1.73% of slide height; #FFFFFF; left aligned]: CONNECTX-7 (Callout label.)
- label at x 89.7, y 34.5, w 5.3, h 1.7 [DIN Pro Regular, capitals; font size 1.73% of slide height; #FFFFFF; right aligned]: ARM CORES (Callout label.)
- label at x 41.5, y 36.1, w 5.7, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: PCIe GEN 5.0 (Callout label.)
- label at x 88.1, y 48.6, w 7.1, h 3.7 [DIN Pro Regular, capitals; font size 1.73% of slide height; #FFFFFF; right aligned]: ACCELERATION / ENGINES (Two lines: ACCELERATION above ENGINES, right-aligned; ENGINES box at x 90.9, y 50.6, w 4.1, h 1.7.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 32.6, w 21.9, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: NVIDIA BLUEFIELD-3
- text at x 41.5, y 16.0, w 11.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DATA PATH ACCELERATOR
- text at x 83.1, y 16.0, w 11.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DDR5 MEMORY INTERFACE
- text at x 6.7, y 29.3, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 37.2, w 25.6, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 400 Gbps Data Center Infra Processor
- text at x 41.5, y 26.3, w 5.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: CONNECTX-7
- text at x 6.7, y 42.6, w 28.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Offloads and Accelerates Data Center Infrastructure
- text at x 89.7, y 34.5, w 5.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ARM CORES
- text at x 41.5, y 36.1, w 5.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: PCIe GEN 5.0
- text at x 6.7, y 47.4, w 31.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Isolates Application from Control and Management Plane
- text at x 6.7, y 52.1, w 19.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Powerful CPU – 16x Arm A78 Cores
- text at x 6.7, y 56.9, w 30.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Process Networking, Storage, and Security at 400 Gbps
- text at x 6.7, y 61.6, w 11.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 22 Billion Transistors
- text at x 88.1, y 48.6, w 7.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ACCELERATION
- text at x 90.9, y 50.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ENGINES

### Slide 27

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

EXPONENTIAL GROWTH IN DATA CENTER INFRASTRUCTURE PROCESSING
Cloud-Native | Disaggregation | Micro-Services | AI | Zero-Trust Security
100X
10X
BlueField-4
64 Billion Transistors
160 SPECint
1000 TOPS
800 Gbps
1X
BlueField-3
22 Billion Transistors
42 SPECint
1.5 TOPS
400 Gbps
2020
2022
2024
BlueField-2
DOCA — ONE ARCHITECTURE
7 Billion Transistors
9 SPECint
0.7 TOPS
200 Gbps
SPECrate2017_int

**Layout**

Single full-bleed dark slide with no visible margin frame. The title is centred across the top at about 8% from the top edge, with a centred subtitle line beneath it. The main graphic is a left-to-right timeline: a vertical 1X / 10X / 100X scale axis sits at about x 20%, a horizontal arrow timeline runs along y 87% from x 21% to x 77%, and three chip thumbnails rise diagonally to the upper right, each with a spec block to its right. Year labels 2020, 2022 and 2024 sit centred under the timeline at y 91%. The footer source line sits bottom-left at about x 4%, y 94%. There is no slide number.

**Visuals**

Timeline diagram with a vertical scale axis and three chip photographs.
Vertical scale axis at about x 20.7%: an arrow at the top (about y 29.6% to 33.3%) points up. Labelled tick text 100X (about y 36%), 10X (about y 56%) and 1X (about y 76%) sit on the line, each with a thin white vertical line segment above and below it. The line segments run from about y 40.8% to 53.8%, 61.3% to 73.9%, and 81.5% to 85.9%. They are 1 px-equivalent white strokes (about 0.1% of slide width), and no numeric values are plotted.
Horizontal timeline: a thin white line from about x 21.4% to x 77.3% at y 86.7%, ending in a small solid white arrowhead pointing right at x 77.3%. The gold DOCA bar is placed over the line between x 40.8% and 60.5%, so the line passes behind it.
Chip photographs (each a small square-cornered rendering of a processor die, with a thin light grey border; the dies are dark olive-green and brown with bright amber and yellow specks and grid-like blocks):
1. BlueField-2 die, about x 29.1%, y 74.9%, 3.0% by 4.8%, portrait-oriented, next to the spec block for 2020.
2. BlueField-3 die, about x 46.9%, y 54.7%, 4.5% by 6.1%, next to the spec block for 2022.
3. BlueField-4 die, about x 62.9%, y 31.5%, 7.5% by 6.8%, landscape-oriented, with a more purple-brown tint, next to the spec block for 2024.
Each die is shown straight-on, full die, not cropped, lit evenly, with no overlay.
DOCA bar: a flat gold rectangle (#A68A4F) with white uppercase text, placed at about x 40.8%, y 84.8%, 19.7% by 3.8%, sitting on the timeline.
No logos or icons.

**Design**

Background: Near-black #000000 at the top fading to charcoal #3A3A3A at the bottom, with a subtle brushed texture across a full-bleed photographic background image (3840 by 2160 px). Black cinematic slide with a subtle brushed-metal texture. The background is near black #000000 at the top, fading to charcoal #3A3A3A toward the bottom edge. Titles and labels are white #FFFFFF. Body and spec text are white #FFFFFF in a light-weight geometric sans-serif (DIN Pro family). The main title is DIN Pro Bold, uppercase, about 4.1% of slide height, so roughly 1/25 of the height. The subtitle and spec text are DIN Pro Regular at about 1.7% to 2.7% of height. Scale labels 100X, 10X and 1X are DIN Pro Bold at about 3.3% of height. Accent colour is gold #A68A4F for the DOCA bar. The footer text is grey #9A9A9A. Lines are thin white strokes, square-cornered, with no shadows or rounded corners. The chip photos have a thin light-grey border and no shadow.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-slide background image: black-to-charcoal gradient with brushed-metal texture, covering the slide. (Full-bleed, no crop, sits behind everything. Fill beneath it is #FFFFFF but fully covered.)
- line at x 20.5, y 29.6, w 0.5, h 3.7 [#FFFFFF]: Vertical scale axis arrow pointing up, top end of the axis. (Thin white stroke about 0.1% of width, small solid arrowhead at top.)
- line at x 20.6, y 40.8, w 0.2, h 13 [#FFFFFF]: Vertical scale line segment between 100X and the top arrow region, from 100X down to 10X. (Thin white stroke, about 0.1% of width, no arrowheads.)
- line at x 20.6, y 61.3, w 0.2, h 12.6 [#FFFFFF]: Vertical scale line segment between 10X and 100X. (Thin white stroke, about 0.1% of width.)
- line at x 20.6, y 73.9, w 0.2, h 7.6 [#FFFFFF]: Vertical scale line segment between 1X and 10X. (Thin white stroke, about 0.1% of width.)
- line at x 20.6, y 81.5, w 0.2, h 4.4 [#FFFFFF]: Vertical scale line segment below 1X down to the timeline. (Thin white stroke, about 0.1% of width.)
- line at x 21.4, y 86.5, w 55.9, h 0.4 [#FFFFFF]: Horizontal timeline arrow from about x 21.4% to 77.3%, pointing right. (Thin white stroke about 0.1% of height, small solid arrowhead at the right end, passes behind the DOCA bar.)
- shape at x 40.8, y 84.8, w 19.7, h 3.8 [#A68A4F]: Gold rectangle behind the DOCA label. (Flat fill, square corners, no border, no shadow. Sits on top of the timeline line.)
- title at x 11.2, y 7.9, w 77.5, h 4.1 [DIN Pro, Bold, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: EXPONENTIAL GROWTH IN DATA CENTER INFRASTRUCTURE PROCESSING
- subtitle at x 23.9, y 12.5, w 52.6, h 2.7 [DIN Pro, Regular; font size 2.72% of slide height; #FFFFFF; center aligned]: Cloud-Native | Disaggregation | Micro-Services | AI | Zero-Trust Security
- body at x 18.7, y 35.8, w 4.2, h 3.3 [DIN Pro, Bold; font size 3.33% of slide height; #FFFFFF; center aligned]: 100X
- body at x 19.2, y 56.1, w 3.2, h 3.3 [DIN Pro, Bold; font size 3.33% of slide height; #FFFFFF; center aligned]: 10X
- body at x 19.7, y 76.2, w 2.1, h 3.3 [DIN Pro, Bold; font size 3.33% of slide height; #FFFFFF; center aligned]: 1X
- photo at x 29.1, y 74.9, w 3, h 4.8: BlueField-2 chip die photograph, portrait orientation, dark olive with amber specks. (Thin light-grey border, square corners, full die, not cropped.)
- body at x 33, y 73.7, w 8.6, h 8.9 [DIN Pro, Bold for heading, Regular for lines; font size 1.73% of slide height; #FFFFFF; left aligned]: BlueField-2 / 7 Billion Transistors / 9 SPECint / 0.7 TOPS / 200 Gbps (Heading BlueField-2 in bold, then four regular lines with about 1.9% line pitch.)
- photo at x 46.9, y 54.7, w 4.5, h 6.1: BlueField-3 chip die photograph, near-square, olive with amber specks. (Thin light-grey border, square corners, full die, not cropped.)
- body at x 52.3, y 53.6, w 9.1, h 9.2 [DIN Pro, Bold for heading, Regular for lines; font size 1.73% of slide height; #FFFFFF; left aligned]: BlueField-3 / 22 Billion Transistors / 42 SPECint / 1.5 TOPS / 400 Gbps (Heading BlueField-3 in bold, then four regular lines.)
- photo at x 62.9, y 31.5, w 7.5, h 6.8: BlueField-4 chip die photograph, landscape orientation, purple-brown with amber specks. (Thin light-grey border, square corners, full die, not cropped.)
- body at x 71.3, y 30.3, w 9.1, h 7.6 [DIN Pro, Bold for heading, Regular for lines; font size 1.73% of slide height; #FFFFFF; left aligned]: BlueField-4 / 64 Billion Transistors / 160 SPECint / 1000 TOPS / 800 Gbps (Heading BlueField-4 in bold, then four regular lines.)
- body at x 43.2, y 85.8, w 14.8, h 2 [DIN Pro, Regular, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: DOCA — ONE ARCHITECTURE (Sits on the gold DOCA bar.)
- body at x 29.4, y 90.9, w 2.9, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2020
- body at x 49.3, y 91, w 2.9, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2022
- body at x 69.3, y 90.8, w 2.9, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2024
- footer at x 3.9, y 94.4, w 5, h 1.1 [DIN Pro, Regular; font size 1.11% of slide height; #9A9A9A; left aligned]: SPECrate2017_int

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 40.8, y 84.8, w 19.7, h 3.8: 2366 by 255 pixels
- image at x 62.9, y 31.5, w 7.5, h 6.8: 500 by 255 pixels
- image at x 46.9, y 54.7, w 4.5, h 6.1: 267 by 205 pixels
- image at x 29.1, y 74.9, w 3.0, h 4.8: 183 by 163 pixels
- text at x 11.2, y 7.9, w 77.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: EXPONENTIAL GROWTH IN DATA CENTER INFRASTRUCTURE PROCESSING
- text at x 23.9, y 12.5, w 52.6, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Cloud-Native | Disaggregation | Micro-Services | AI | Zero-Trust Security
- text at x 18.7, y 35.8, w 4.2, h 3.3 [DINPro-Bold; font size 3.33; #FFFFFF]: 100X
- text at x 19.2, y 56.1, w 3.2, h 3.3 [DINPro-Bold; font size 3.33; #FFFFFF]: 10X
- text at x 71.3, y 30.3, w 5.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: BlueField-4
- text at x 71.3, y 32.1, w 9.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 64 Billion Transistors
- text at x 71.3, y 34.0, w 5.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 160 SPECint
- text at x 71.3, y 35.9, w 4.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1000 TOPS
- text at x 71.3, y 37.7, w 3.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 800 Gbps
- text at x 19.7, y 76.2, w 2.1, h 3.3 [DINPro-Bold; font size 3.33; #FFFFFF]: 1X
- text at x 52.3, y 53.6, w 5.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: BlueField-3
- text at x 52.3, y 55.5, w 9.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 22 Billion Transistors
- text at x 52.3, y 57.3, w 4.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 42 SPECint
- text at x 52.3, y 59.2, w 3.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1.5 TOPS
- text at x 52.3, y 61.1, w 3.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 400 Gbps
- text at x 29.4, y 90.9, w 2.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2020
- text at x 49.3, y 91.0, w 2.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2022
- text at x 69.3, y 90.8, w 2.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2024
- text at x 33.0, y 73.7, w 5.2, h 1.7 [DINPro-Bold; font size 1.73; #FFFFFF]: BlueField-2
- text at x 43.2, y 85.8, w 14.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DOCA — ONE ARCHITECTURE
- text at x 33.0, y 75.6, w 8.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 7 Billion Transistors
- text at x 33.0, y 77.4, w 4.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 9 SPECint
- text at x 33.0, y 79.3, w 3.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0.7 TOPS
- text at x 33.0, y 81.2, w 4.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 200 Gbps
- text at x 3.9, y 94.4, w 5.0, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: SPECrate2017_int

### Slide 28

**Text**

NVIDIA DGX
The Computer of AI Researchers
9 of 10
Top
Universities
8 of 10
Top
Global Telcos
7 of 10
Top
U.S. Hospitals
7 of 10
Top
Consumer
Companies
6 of 10
Top
U.S. Banks
7 of 10
Top
Car Makers
10 of 10
Top
Aerospace
Companies
DGX SUPERPOD
AI Data Center As-a-Product
DGX A100
AI Data Center
Building Block
DGX STATION A100
AI Data Center-in-a-Box

**Layout**

Full-bleed dark studio render with no grid or columns. The title block is centred horizontally at the top (title baseline about 8% from top). Seven dark circular badges form a staggered three-row cluster on the left (rows of 2, 3 and 2), occupying about x 4% to 39% and y 24% to 83%. The DGX SUPERPOD rack row runs across the right half from about x 44% to 97%, with the DGX A100 and DGX Station A100 product units stacked in the lower right (x 69% to 95%, y 55% to 92%). No footer, slide number, logo or source line is visible.

**Visuals**

Photograph (CGI-style studio render) filling the whole slide. Subject: a long row of about fifteen black server racks with gold-beige front panels (the DGX SUPERPOD, AI Data Center As-a-Product), with two racks showing glowing blue-violet indicator lights near the centre-right. In the lower right are two DGX products: a DGX A100 building block, a stacked rack-mount unit of three beige-gold chassis with black side handles and NVIDIA logo on the left end, and a DGX Station A100, a tall beige-gold tower with a darker top cap and a silver-grey stripe, carrying an NVIDIA logo near its base. Composition: wide shot from a low eye-level angle, racks receding to the right, products in the foreground at the right. Lighting: low-key, soft top and side light, with a reflective dark grey floor showing soft reflections. Dominant colours: black, dark grey, champagne gold and beige. Not cropped; full-bleed. No overlay or tint. Also seven circular badges (shapes) on the left, each with a number in gold and 'of 10' in white, plus a label beneath, as listed in elements.

**Design**

Background is a near-black studio render. Title 'NVIDIA DGX' is bold white DIN Pro-style sans-serif (about 4.1% of slide height, caps), with subtitle in regular white DIN Pro-style sans-serif (about 2.7%). Badge numbers are medium-weight DIN Pro-style sans-serif in gold #B3914C (about 6.2%); 'of 10' is medium white (about 2.2%); badge labels are regular white (about 2.0%). Product captions use medium and regular white DIN Pro-style sans-serif (about 2.0% and 1.7%). Accents: gold #B3914C. Badges are flat near-black circles with a thin gold-bronze rim and a faint drop shadow. No gradients on text; the photo has soft lighting falloff.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed CGI studio render: DGX SUPERPOD rack row, DGX A100 and DGX Station A100 products on a reflective dark grey floor (Covers the whole slide; the white fill beneath is fully hidden; no crop, no overlay)
- shape at x 9.9, y 24, w 10.6, h 19 [#0E0E0E]: Dark circular badge: Top Universities (Circle; thin gold-bronze rim #B3914C about 0.3% of slide height; faint drop shadow below)
- shape at x 21.9, y 24, w 10.7, h 19 [#0E0E0E]: Dark circular badge: Top Global Telcos (Circle; thin gold-bronze rim #B3914C; faint drop shadow below)
- shape at x 3.9, y 44.2, w 10.7, h 18.9 [#0E0E0E]: Dark circular badge: Top U.S. Hospitals (Circle; thin gold-bronze rim #B3914C; faint drop shadow below)
- shape at x 15.9, y 44.2, w 10.7, h 18.9 [#0E0E0E]: Dark circular badge: Top Consumer Companies (Circle; thin gold-bronze rim #B3914C; faint drop shadow below)
- shape at x 27.9, y 44.2, w 10.7, h 18.9 [#0E0E0E]: Dark circular badge: Top U.S. Banks (Circle; thin gold-bronze rim #B3914C; faint drop shadow below)
- shape at x 9.9, y 64.3, w 10.6, h 18.9 [#0E0E0E]: Dark circular badge: Top Car Makers (Circle; thin gold-bronze rim #B3914C; faint drop shadow below)
- shape at x 21.9, y 64.3, w 10.7, h 18.9 [#0E0E0E]: Dark circular badge: Top Aerospace Companies (Circle; thin gold-bronze rim #B3914C; faint drop shadow below)
- photo at x 44.3, y 35.8, w 52.6, h 23.6: DGX SUPERPOD: row of about fifteen server racks with gold-beige front panels, two with blue indicator lights (Rendered photo element, black racks against black background; top edge at about y 36%; overlaps nothing)
- photo at x 76.9, y 55.3, w 11.6, h 25.6: DGX A100: stacked three-unit rack-mount chassis, beige-gold panels, black side handles, NVIDIA logo (Rendered product photo; overlaps the rack row base and sits in front of the Station unit's left edge)
- photo at x 86.1, y 64.7, w 8.7, h 27.7: DGX Station A100: tall beige-gold tower with darker top cap, silver stripe and small NVIDIA logo near base (Rendered product photo, front-most object; overlaps the right edge of the DGX A100 unit)
- title at x 43.9, y 7.9, w 12.2, h 4.1 [DIN Pro Bold, sans-serif, bold, caps; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA DGX
- subtitle at x 38.9, y 12.5, w 22.1, h 2.7 [DIN Pro Regular, sans-serif, regular; font size 2.72% of slide height; #FFFFFF; center aligned]: The Computer of AI Researchers
- body at x 14, y 27.1, w 1.8, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 9 of 10 (Number 9 in gold with 'of 10' in white beside it, both in one line within the Universities badge)
- body at x 26, y 27.1, w 1.8, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 8 of 10 (Number 8 in gold with 'of 10' in white beside it within the Global Telcos badge)
- body at x 8.2, y 47.2, w 1.8, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 7 of 10 (Number 7 in gold with 'of 10' in white within the U.S. Hospitals badge)
- body at x 20.2, y 47.2, w 1.8, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 7 of 10 (Number 7 in gold with 'of 10' in white within the Consumer Companies badge)
- body at x 32.2, y 47.2, w 1.8, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 6 of 10 (Number 6 in gold with 'of 10' in white within the U.S. Banks badge)
- body at x 14.3, y 67.3, w 1.8, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 7 of 10 (Number 7 in gold with 'of 10' in white within the Car Makers badge)
- body at x 24.4, y 67.3, w 3.7, h 6.2 [DIN Pro Medium, sans-serif, medium; font size 6.17% of slide height; #B3914C; center aligned]: 10 of 10 (Number 10 in gold with 'of 10' in white within the Aerospace Companies badge)
- body at x 12, y 34, w 5.9, h 4.2 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / Universities
- body at x 23.6, y 34, w 6.7, h 4.2 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / Global Telcos
- body at x 5.7, y 54.1, w 6.9, h 4.2 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / U.S. Hospitals
- body at x 18.4, y 54.1, w 6.9, h 6.3 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / Consumer / Companies
- body at x 30.4, y 54.1, w 5.4, h 4.2 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / U.S. Banks
- body at x 12.3, y 74.2, w 5.7, h 4.2 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / Car Makers
- body at x 24.4, y 74.2, w 5.5, h 6.3 [DIN Pro Regular, sans-serif, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Top / Aerospace / Companies
- caption at x 44.6, y 59.4, w 12.3, h 4.3 [DIN Pro Medium (heading) and DIN Pro Regular (line 2), sans-serif; font size 1.98% of slide height; #FFFFFF; left aligned]: DGX SUPERPOD / AI Data Center As-a-Product
- caption at x 69.6, y 73.8, w 6.3, h 6.5 [DIN Pro Medium (heading) and DIN Pro Regular (lines 2 and 3), sans-serif; font size 1.98% of slide height; #FFFFFF; right aligned]: DGX A100 / AI Data Center / Building Block
- caption at x 74.7, y 87.4, w 10.4, h 4.2 [DIN Pro Medium (heading) and DIN Pro Regular (line 2), sans-serif; font size 1.98% of slide height; #FFFFFF; right aligned]: DGX STATION A100 / AI Data Center-in-a-Box

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 43.9, y 7.9, w 12.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA DGX
- text at x 14.0, y 27.1, w 1.8, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 9
- text at x 26.0, y 27.1, w 1.8, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 8
- text at x 38.9, y 12.5, w 22.1, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: The Computer of AI Researchers
- text at x 8.2, y 47.2, w 1.8, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 7
- text at x 20.2, y 47.2, w 1.8, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 7
- text at x 32.2, y 47.2, w 1.8, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 6
- text at x 14.3, y 67.3, w 1.8, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 7
- text at x 24.4, y 67.3, w 3.7, h 6.2 [DINPro-Medium; font size 6.17; #B3914C]: 10
- text at x 16.0, y 30.3, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 28.1, y 30.3, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 14.0, y 34.0, w 1.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 26.0, y 34.0, w 2.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 12.0, y 36.2, w 5.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Universities
- text at x 23.6, y 36.2, w 6.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Global Telcos
- text at x 10.3, y 50.4, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 22.3, y 50.4, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 34.3, y 50.4, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 8.2, y 54.1, w 1.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 20.2, y 54.1, w 2.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 32.2, y 54.1, w 2.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 5.7, y 56.3, w 6.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: U.S. Hospitals
- text at x 18.6, y 56.3, w 5.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Consumer
- text at x 30.4, y 56.3, w 5.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: U.S. Banks
- text at x 18.4, y 58.4, w 5.5, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Companies
- text at x 44.6, y 59.4, w 8.0, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: DGX SUPERPOD
- text at x 16.3, y 70.5, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 28.3, y 70.5, w 2.7, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: of 10
- text at x 44.6, y 62.0, w 12.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AI Data Center As-a-Product
- text at x 14.3, y 74.2, w 2.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 26.3, y 74.2, w 2.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Top
- text at x 71.0, y 73.8, w 4.8, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: DGX A100
- text at x 12.3, y 76.4, w 5.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Car Makers
- text at x 24.6, y 76.4, w 5.2, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Aerospace
- text at x 24.4, y 78.5, w 5.5, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Companies
- text at x 75.6, y 87.4, w 9.5, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: DGX STATION A100
- text at x 69.6, y 76.5, w 6.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AI Data Center
- text at x 69.6, y 78.6, w 6.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Building Block
- text at x 74.7, y 89.9, w 10.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AI Data Center-in-a-Box

### Slide 29

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

ANNOUNCING NVIDIA DGX STATION 320G
Workgroup AI Supercomputer-in-a-Box
Plug-into-the-Wall Instant AI Infrastructure
2.5 petaFLOPS
320 GB at 8 TB/sec
7.68 TB NVMe
28 MIGs
1500W and < 37db
$149,000 or $9,000/Month Subscription

**Layout**

Full-bleed dark photographic slide. Title and subtitle are centred at the top with the title above the subtitle. A boxed specification panel sits on the left, with six-plus spec lines stacked vertically and left-aligned inside it. The product image occupies the right half, with the server racks in the background and the DGX Station units grouped at the lower right.

**Visuals**

Photograph (rendered product image) of an NVIDIA DGX Station 320G with a row of server racks behind it. Subject: a row of about 18 tall black server racks with tan/gold perforated panels receding across the upper-middle of the frame, two racks in the centre showing blue indicator lights. In the lower right foreground, a stacked tower of three tan/gold rack-mounted units (NVIDIA logo on the left face) sits beside a taller tan/gold workstation unit with a flat top and 'DGX STATION' badge and NVIDIA logo on its front, its side panel open showing internal components. Composition: wide landscape framing, camera level, subjects placed right of centre; floor is a dark reflective grey surface. Lighting: soft studio spotlight from above, dark moody falloff. Dominant colours: black, charcoal grey, tan/gold (about #B8A98A). Full-bleed, not cropped. Overlay: a semi-opaque near-black (about #0E0E0E) rectangular panel with thin tan outline (about #6B5E4A) sits over the left side of the image.

**Design**

Background: Photographic image of a dark studio space with server racks and DGX Station units; near-black (about #050505) at top fading to dark charcoal floor.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#050505]: Full-slide rendered photograph of DGX Station 320G with server racks (background image layer) (Full-bleed, not cropped, no border; covers entire slide)
- shape at x 3.8, y 21.6, w 34.7, h 56.2 [#0E0E0E]: Dark translucent panel behind specification list (Rectangle, square corners, about 90% opacity, 1px stroke tan #6B5E4A, faint drop shadow below; sits over photo)
- title at x 28.6, y 7.9, w 42.8, h 4.1 [DIN Pro, Bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA DGX STATION 320G
- subtitle at x 36.6, y 12.5, w 26.9, h 2.7 [DIN Pro, Regular; font size 2.72% of slide height; #FFFFFF; center aligned]: Workgroup AI Supercomputer-in-a-Box
- body at x 6.5, y 27, w 29.9, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: Plug-into-the-Wall Instant AI Infrastructure
- body at x 6.5, y 35.1, w 10, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: 2.5 petaFLOPS
- body at x 6.5, y 43.2, w 12.8, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: 320 GB at 8 TB/sec
- body at x 6.5, y 51.2, w 9.5, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: 7.68 TB NVMe
- body at x 6.5, y 59.3, w 5.4, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: 28 MIGs
- body at x 6.5, y 67.4, w 12.4, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: 1500W and < 37db
- body at x 6.5, y 75.5, w 27, h 2.7 [DIN Pro, Medium; font size 2.72% of slide height; #FFFFFF; left aligned]: $149,000 or $9,000/Month Subscription
- photo at x 46, y 28, w 48, h 65 [#B8A98A]: DGX Station 320G product rendering: tower of three tan/gold rack units and a taller tan/gold workstation with DGX STATION badge and NVIDIA logos, in front of a row of server racks (Part of the background photograph; not boxed; no border)
- logo at x 57, y 56, w 10, h 3 [#B8A98A]: NVIDIA logo on the rack units and workstation front (Small tan/gold logos on unit faces)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 28.6, y 7.9, w 42.8, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA DGX STATION 320G
- text at x 36.6, y 12.5, w 26.9, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Workgroup AI Supercomputer-in-a-Box
- text at x 6.5, y 27.0, w 29.9, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: Plug-into-the-Wall Instant AI Infrastructure
- text at x 6.5, y 35.1, w 10.0, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: 2.5 petaFLOPS
- text at x 6.5, y 43.2, w 12.8, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: 320 GB at 8 TB/sec
- text at x 6.5, y 51.2, w 9.5, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: 7.68 TB NVMe
- text at x 6.5, y 59.3, w 5.4, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: 28 MIGs
- text at x 6.5, y 67.4, w 12.4, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: 1500W and < 37db
- text at x 6.5, y 75.5, w 27.0, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: $149,000 or $9,000/Month Subscription

### Slide 30

**Text**

NVIDIA

**Layout**

Full-bleed single photograph covering the entire slide with the product centred slightly right of middle on a pedestal; no title, no text layer, no footer and no slide number are visible on the slide.

**Visuals**

Photograph of an NVIDIA DGX Station workstation standing upright on a silver-framed black glass pedestal platform. The tower has a brushed champagne-gold metal body with a textured, speckled top panel, a black horizontal band near the top carrying the printed text DGX STATION, a small circular power button, and the NVIDIA logo (green-black eye emblem with the word NVIDIA) printed in black near the bottom front. The camera is at a slight low angle, three-quarter view from the front-left, showing the front face and right side. The pedestal has a rounded silver rim and a glossy black top with a small rectangular slot at the right end; its base shows warm yellow-amber light strips. The background is pure black fading to a dark grey floor. Lighting is soft studio key light from above and front, with a small rainbow-coloured reflection on the glossy black surface beneath the tower. The image is full-bleed, not cropped, with no overlay or tint.

**Design**

Background is solid black; the photograph fills the whole slide. No typography, no title, no decorative shapes. Dominant colours: black #000000, champagne gold #C8B98F, silver #B8BCC0, warm yellow light #E8B84A. No text styling applies beyond the printed product and logo markings.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide white fill behind the photograph, covered entirely by the image; not visible. (Fill layer, fully obscured by the image.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed photograph of NVIDIA DGX Station workstation on a silver-framed black glass pedestal, dark studio background. (Uncropped, full-bleed, no overlay or tint. Product tower spans about x 38 to 59 percent and y 9 to 75 percent. Pedestal spans about x 14 to 75 percent and y 67 to 98 percent. Printed text DGX STATION on the black band at about x 42 to 46 percent, y 24 to 26 percent; NVIDIA logo on the tower front at about x 41 to 47 percent, y 76 to 79 percent.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2560 by 1440 pixels (covers the slide)

### Slide 31

**Text**

ANNOUNCING THE NEW DGX SUPERPOD
World’s First Cloud-Native Supercomputer | Secured by NVIDIA BlueField | Multi-Tenant Bare-Metal Performance
A100 80GB
BLUEFIELD-2
BASE COMMAND

**Layout**

Full-bleed dark photograph with a centred two-line header across the top (title above subtitle, both centred on the slide's horizontal axis, about 8% from the top). Lower left holds a row of three equal circular icons with captions beneath, left-aligned to about 4% margin. The right side is occupied by a row of server racks on the upper right and two stacked DGX units with a DGX Station tower in the lower right. No footer, page number or source line is visible.

**Visuals**

Full-slide dark photograph of a data-centre floor: a long horizontal row of about 18 black server racks running from about x 44% to x 97% at y 36% to 59%, with tan-gold perforated server units in the racks and two racks in the middle showing blue indicator lights. Immediately in front and right, a stack of three tan-gold DGX A100 chassis (each with a small NVIDIA logo on a black side panel) sits at about x 77% to 88%, y 55% to 81%, and a taller DGX Station tower with a black top band and small NVIDIA logo sits in front at about x 86% to 95%, y 65% to 92%. The floor is dark grey and glossy with soft reflections. Lighting is a single soft key light from the upper right, giving a moody low-key look. Three circular icons on the left, each a black disc with a thin bronze-gold rim: (1) A100 80GB: a silver-grey GPU board with gold chips and a gold heatsink strip, centred at about x 10%, y 57%; (2) BLUEFIELD-2: a silver PCIe network card with a gold chip and gold edge connector, centred at about x 21%, y 57%; (3) BASE COMMAND: a gold-and-white neural-network node graph above a horizontal gold-and-grey memory bar, with four white curved arrows around it and a small grey server unit below, centred at about x 33%, y 57%. No logos other than the small NVIDIA marks on the DGX units.

**Design**

Background: Full-bleed dark photograph of a data-centre floor on black (#000000 to #2A2A2A). Black background (#000000) with a dark photographic scene; the photo has a grey floor (#2A2A2A) and near-black racks (#111111). Title is white (#FFFFFF) bold DIN-style sans-serif in all caps, about 4.1% of slide height (cap height about 2.9%). Subtitle is white (#FFFFFF) regular-weight DIN-style sans-serif, about 2.7% of slide height, with vertical bar separators. Icon captions are white (#FFFFFF) medium-weight DIN-style sans-serif in all caps, about 2.0% of slide height. Accent colour is bronze-gold (#B8975A) for the circle rims and the gold chips and DGX chassis tones (#C2A878). Circle rims are thin (about 0.3% of slide width) bronze-gold strokes with no shadow. No corner radii on the panels; the circles are perfect circles. No gradients on shapes; the photo has a soft vignette toward the top.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark photograph of a data-centre floor with server racks, DGX A100 units and DGX Station tower (Covers the entire slide, not cropped, no overlay; background layer)
- shape at x 3.9, y 44.2, w 10.7, h 19 [#0A0A0A]: Three black circular discs behind the icons (Circle 1 of 3; bronze-gold rim stroke about 0.3% of slide width (#B8975A); no shadow; overlaps the photo floor)
- shape at x 15.8, y 44.2, w 10.7, h 19 [#0A0A0A]: Three black circular discs behind the icons (Circle 2 of 3; bronze-gold rim stroke (#B8975A); no shadow)
- shape at x 27.9, y 44.2, w 10.7, h 19 [#0A0A0A]: Three black circular discs behind the icons (Circle 3 of 3; bronze-gold rim stroke (#B8975A); no shadow)
- title at x 29, y 7.9, w 42, h 4.1 [DIN Pro, Bold, all caps, sans-serif; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING THE NEW DGX SUPERPOD
- subtitle at x 10.9, y 12.5, w 78.3, h 2.7 [DIN Pro, Regular, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: World’s First Cloud-Native Supercomputer | Secured by NVIDIA BlueField | Multi-Tenant Bare-Metal Performance (Vertical bar separators with spaces either side; line spacing single)
- icon at x 5.9, y 50, w 6.7, h 6.8: A100 80GB GPU board illustration inside circle (Silver-grey board with gold chips and a gold heatsink strip; no overlay)
- icon at x 17.6, y 49.8, w 7.1, h 7.9: BlueField-2 PCIe card illustration inside circle (Silver PCIe card with gold chip and gold edge connector; no overlay)
- icon at x 29, y 46.2, w 8.3, h 14.1: Base Command illustration: gold node graph with four white arrows above a gold memory bar and grey server unit (Lines and arrows white (#FFFFFF); no overlay)
- caption at x 6.2, y 65, w 5.4, h 2 [DIN Pro, Medium, all caps, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: A100 80GB
- caption at x 17.7, y 65, w 6.9, h 2 [DIN Pro, Medium, all caps, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: BLUEFIELD-2
- caption at x 28.9, y 65, w 8.5, h 2 [DIN Pro, Medium, all caps, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: BASE COMMAND

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 29.0, y 46.2, w 8.3, h 14.1: 320 by 305 pixels
- image at x 17.6, y 49.8, w 7.1, h 7.9: 297 by 188 pixels
- image at x 5.9, y 50.0, w 6.7, h 6.8: 275 by 156 pixels
- text at x 29.0, y 7.9, w 42.0, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING THE NEW DGX SUPERPOD
- text at x 10.9, y 12.5, w 78.3, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: World’s First Cloud-Native Supercomputer | Secured by NVIDIA BlueField | Multi-Tenant Bare-Metal Performance
- text at x 6.2, y 65.0, w 5.4, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: A100 80GB
- text at x 17.7, y 65.0, w 6.9, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: BLUEFIELD-2
- text at x 28.9, y 65.0, w 8.5, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: BASE COMMAND

### Slide 32

**Text**

NVIDIA MEGATRON TRAINS TRANSFORMERS
100 TRILLION PARAMETERS MODELS BY 2023
1000
100
10
1
GPT-3 (175B)
Model Size (Trillions of Parameters)
0.1
Megatron-LM
(8.3B)
Turing-NLG (17.2B)
0.01
T5 (11B)
GPT-2
0.001
(1.5B)
BERT-Large (340M)
0.0001
ELMo (94M)
2018
2019
2020
2021
2022
2023

**Layout**

Single centred title sits across the top of a black slide at about 8% from the top, with a large dark dashed-edge panel occupying the left and centre (x 7.6% to 72.7%, y 21.6% to 83.1%) and a row of hardware photography filling the right side. The chart is set in the left half of the panel with a y-axis label on the far left, year labels along the bottom, and a diagram on the right half of the panel. No footer, slide number or logo text is visible; the slide is left-aligned to the panel edge with a wide right-hand photographic zone.

**Visuals**

Chart: log-scale line chart titled '100 TRILLION PARAMETERS MODELS BY 2023'. Y axis: 'Model Size (Trillions of Parameters)', logarithmic, labelled ticks 0.0001, 0.001, 0.01, 0.1, 1, 10, 100, 1000 (bottom to top, each step is a factor of 10). X axis: years 2018 to 2023, labelled at 2018, 2019, 2020, 2021, 2022, 2023 with a thin light-grey horizontal axis line beneath them; no unit printed. Series: one green (#76B900) solid line with dot markers running from about 2018 (ELMo) up to about 2020.5 (GPT-3), then continuing as a green dashed projection line from about 2020.5 up to about 2023 near 1000 (about 1000 trillion parameters, estimated). Data points, labelled as printed: ELMo (94M) near 2018, BERT-Large (340M) about 2018.8, GPT-2 (1.5B) about 2019.0, Megatron-LM (8.3B) about 2019.6, T5 (11B) about 2019.7, Turing-NLG (17.2B) about 2020.2, GPT-3 (175B) about 2020.5 at about 0.2 trillion parameters. No legend; no highlighted points beyond the green markers. Diagram: on the right of the panel, gold-outline (#B8A06A) line drawings: two tall stacked neural-network-style block diagrams joined by an elbow connector line; each has rectangles stacked vertically with small circle-and-sine symbols at the bottom; below them a horizontal gold bracket connecting three identical unit icons, each showing a square gold-tile chip with a silver sphere cluster on top and a small gold side panel on each side. Photograph elements: background shows a row of about six black server racks with beige-grey mesh panels (right of the panel, x 72.5% to 97%); foreground shows a stack of three beige-gold NVIDIA DGX-style server units (x 76.9% to 88.5%, y 55.3% to 80.9%) with the NVIDIA logo on the front face, and a tall beige DGX Station tower to the right (x 86.1% to 94.8%, y 64.7% to 92.4%) with an NVIDIA logo near its base. The slide is black with a dark charcoal floor.

**Design**

Background: Solid black #000000 with a dark charcoal #111111 panel and a dark grey photographic floor at the bottom right.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed data-centre photograph: black server racks at right, beige-gold NVIDIA DGX server stack and DGX Station tower in foreground, dark reflective floor (Covers the full slide, back layer; dominant colours black #000000, charcoal #222222, beige-gold #C2B08A; no crop, not boxed, no overlay)
- shape at x 7.6, y 21.6, w 65.1, h 61.5 [#111111]: Dark rectangular display panel with thin warm-grey border (Fill #111111; border about 0.1% of slide width in warm grey #6B6150; slight drop shadow beneath; square corners; sits over the photograph)
- text at x 26.7, y 7.9, w 46.6, h 4.1 [DIN Pro, Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA MEGATRON TRAINS TRANSFORMERS
- text at x 7.6, y 27.4, w 28.7, h 2.5 [DIN Pro, Medium, all caps; font size 2.47% of slide height; #FFFFFF; left aligned]: 100 TRILLION PARAMETERS MODELS BY 2023
- text at x 9.2, y 34.3, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 1000
- text at x 9.7, y 39, w 1.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 100
- text at x 10.2, y 43.7, w 1, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 10
- text at x 10.7, y 48.3, w 0.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 1
- text at x 9.9, y 53, w 1.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 0.1
- text at x 9.4, y 57.7, w 1.8, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 0.01
- text at x 8.9, y 62.4, w 2.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 0.001
- text at x 8.4, y 67, w 2.8, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 0.0001
- text at x 6.3, y 40.1, w 1, h 27.4 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Model Size (Trillions of Parameters) (Rotated 90 degrees counter-clockwise, reads bottom to top)
- line at x 12.2, y 72.4, w 24.5, h 0.2 [#BDBDBD]: X-axis baseline (Light grey horizontal stroke about 0.2% of slide height thick)
- text at x 11.1, y 74.1, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2018
- text at x 15.5, y 74.1, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2019
- text at x 19.9, y 74.1, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2020
- text at x 24.3, y 74.1, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2021
- text at x 28.7, y 74.1, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2022
- text at x 33.1, y 74.1, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2023
- chart at x 12.5, y 34, w 24.5, h 38.5 [#76B900]: Log-scale series line from ELMo (94M) to GPT-3 (175B) in solid green with dot markers, continuing as green dashed projection to about 1000 near 2023 (about) (Solid line stroke about 0.4% of slide height, #76B900; dashed continuation same colour; dot markers about 0.8% diameter; no legend; no gridlines)
- text at x 15.4, y 51.9, w 5.7, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: GPT-3 (175B)
- text at x 13.1, y 55.8, w 5.9, h 4 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Megatron-LM / (8.3B) (Two lines; second line starts at x 14.8)
- text at x 22.7, y 56.7, w 8.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Turing-NLG (17.2B)
- text at x 19.5, y 59.5, w 3.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: T5 (11B)
- text at x 12.6, y 60.3, w 2.7, h 4 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: GPT-2 / (1.5B)
- text at x 16.9, y 64.7, w 8.4, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: BERT-Large (340M)
- text at x 13.3, y 68.9, w 5.1, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: ELMo (94M)
- diagram at x 44.5, y 31.5, w 20.6, h 38.5 [#B8A06A]: Two stacked neural-network-style block diagrams with an elbow connector, above a horizontal bracket feeding three GPU-chip icons (Gold #B8A06A outline strokes about 0.15% of slide height, no fills; rectangles with square corners; circle-and-sine symbols; overlaps no other element)
- illustration at x 45.8, y 69, w 4.8, h 7.7 [#C9A94F]: Three identical gold GPU chip units with silver sphere clusters and gold side tiles, under a gold bracket (Left unit of three; 291 by 262 pixel source; gold tile fill #C9A94F; silver spheres #C0C0C0)
- illustration at x 52.2, y 69, w 4.8, h 7.7 [#C9A94F]: Three identical gold GPU chip units with silver sphere clusters and gold side tiles, under a gold bracket (Middle unit of three; gold tile fill #C9A94F; silver spheres #C0C0C0)
- illustration at x 58.5, y 69, w 4.8, h 7.7 [#C9A94F]: Three identical gold GPU chip units with silver sphere clusters and gold side tiles, under a gold bracket (Right unit of three; gold tile fill #C9A94F; silver spheres #C0C0C0)
- photo at x 72.5, y 36, w 24.5, h 22.5 [#0A0A0A]: Background row of black server racks with beige-grey mesh panels (Partly behind the panel on the right; dominant black #0A0A0A with beige #B5AA94 panels; no overlay)
- illustration at x 76.9, y 55.3, w 11.6, h 25.6 [#B5AA94]: Stack of three beige-gold NVIDIA DGX server units with NVIDIA logos on front faces (Front faces beige-gold #B5AA94 with speckled texture; black side handles; overlaps the background racks)
- illustration at x 86.1, y 64.7, w 8.7, h 27.7 [#C2B08A]: Tall beige DGX Station tower with NVIDIA logo near its base (Top cap lighter beige #CFC3A3; body #C2B08A; small silver badge; overlaps the DGX stack at its left edge)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 44.5, y 24.7, w 20.6, h 38.5: 608 by 638 pixels
- image at x 45.8, y 69.0, w 4.8, h 7.7: 291 by 262 pixels
- image at x 52.2, y 69.0, w 4.8, h 7.7: 146 by 131 pixels
- image at x 58.5, y 69.0, w 4.8, h 7.7: 73 by 66 pixels
- text at x 26.7, y 7.9, w 46.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA MEGATRON TRAINSTRANSFORMERS
- text at x 7.6, y 27.4, w 28.7, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: 100 TRILLION PARAMETERS MODELS BY 2023
- text at x 9.2, y 34.3, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1000
- text at x 9.7, y 39.0, w 1.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 100
- text at x 10.2, y 43.7, w 1.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10
- text at x 10.7, y 48.3, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1
- text at x 15.4, y 51.9, w 5.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GPT-3 (175B)
- text at x 6.3, y 40.1, w 1.0, h 27.4 [DINPro-Regular; font size 1.73; #FFFFFF]: Model Size (Trillions of Parameters)
- text at x 9.9, y 53.0, w 1.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0.1
- text at x 13.1, y 55.8, w 5.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Megatron-LM
- text at x 22.7, y 56.7, w 8.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Turing-NLG (17.2B)
- text at x 9.4, y 57.7, w 1.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0.01
- text at x 14.8, y 58.0, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: (8.3B)
- text at x 19.5, y 59.5, w 3.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: T5 (11B)
- text at x 12.6, y 60.3, w 2.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GPT-2
- text at x 8.9, y 62.4, w 2.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0.001
- text at x 12.7, y 62.5, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: (1.5B)
- text at x 16.9, y 64.7, w 8.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: BERT-Large (340M)
- text at x 8.4, y 67.0, w 2.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0.0001
- text at x 13.3, y 68.9, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ELMo (94M)
- text at x 7.9, y 71.7, w 3.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 0.00001
- text at x 11.1, y 74.1, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2018
- text at x 15.5, y 74.1, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2019
- text at x 19.9, y 74.1, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2020
- text at x 24.3, y 74.1, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2021
- text at x 28.7, y 74.1, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2022
- text at x 33.1, y 74.1, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2023

### Slide 33

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.
- What would change the score: I would split or simplify the dense panels (slides 5, 6, 33, 59) and cut the repeated DGX SuperPOD backdrop clutter behind the text-heavy announcement slides.

**Text**

NVIDIA MEGATRON TRITON
Query
Response
Megatron
NVIDIA
Dev Tech
Megatron Triton
Inference Server
RUN GPT-3 BASED CHATBOTS
16 QUERIES
1 Second
DGX A100
1 QUERY
>1 Minute
Dual Socket CPU Server
Input sequence length=128 tokens (average of 102 words), Output sequence length=8 tokens (average of 6 words)
GPU: Megatron GPT-3 on DGX-A100-80GB, Batch size=16, FP16, FasterTransformer 4.0, Triton 2.6
CPU: OpenAI GPT-3 on Xeon Platinum 8280 2S, 755GB System memory, Batch size=1, FP32, TensorFlow 2.3

**Layout**

Full-bleed dark photographic scene with a large dark rectangular panel occupying the left and centre of the slide, spanning about x 3.8 to 72.7 and y 21.6 to 83.2. The title is centred horizontally at the top (about y 7.9). Inside the panel, a three-step flow diagram sits at left and a two-column comparison (16 queries versus 1 query) sits at right, with a centred heading above the comparison. Hardware photographs sit at the right edge, overlapping the panel's right border. Footnote lines are left-aligned at the bottom left (x 3.9, y 93 to 96). No slide number or logo is visible.

**Visuals**

Diagram: three green rectangles (#76B900) in a horizontal row, labelled Megatron, NVIDIA Dev Tech and Megatron Triton Inference Server, joined by short white right-pointing arrows. Above the third box, a vertical white double arrow pair: a downward arrow labelled Query and an upward arrow labelled Response. Below the third box, a single white down arrow leads to a thin orange-brown bracket (#B5793A) that splits into five branches, each ending in a small GPU icon: a gold-and-grey processor die with a grey dome-shaped heat element and gold side memory modules, shown in a fading pixelated style. Gauges: two white-outlined stopwatch icons (outer ring and inner ring, crown button on top). Left gauge: a green (#76B900) wedge/needle pointing almost straight up, meaning the fastest result, labelled 16 QUERIES, 1 Second, DGX A100. Right gauge: a solid blue (#0071C5) filled disc covering about 85 percent of the dial with a white needle near 12 o'clock, labelled 1 QUERY, >1 Minute, Dual Socket CPU Server. Photograph at right: a dark server room with rows of black server racks with perforated grey-beige front panels, receding into darkness, cropped at the right edge of the slide and fading to black at top. In front on the right: an NVIDIA DGX A100 stack of three beige-grey rackmount units with NVIDIA logos on their left edges (about x 76.9 to 88.4, y 55.3 to 80.9), and beside it a taller beige-grey tower NVIDIA DGX Station with a lighter top cap and the NVIDIA logo near its base (about x 86.1 to 94.8, y 64.7 to 92.4). Lighting is a soft studio key light from the upper left, with dark charcoal floor reflections. Dominant colours: black, charcoal, beige-grey, green and blue accents.

**Design**

Background is near-black (#000000) at top, shading into a dark charcoal (#1A1A1A) floor. The central panel is charcoal #111111 with a thin warm bronze-grey border (#6B6258) about 0.2 percent of slide width, and a soft shadow below it. Titles and headings are white #FFFFFF in DIN Pro Bold (title) and DIN Pro Medium (headings), set in all capitals with slight letter-spacing. Body and labels are white DIN Pro Regular. Accent colours: NVIDIA green #76B900 for the first process boxes, the 16-query figures and the green wedge; blue #0071C5 for the 1-query figures and the filled gauge. Footnotes are grey #9A9A9A DIN Pro Regular. Title size about 4.1 percent of slide height (cap height roughly 2.9 percent). Heading about 2.5 percent. Body labels about 2.0 percent. Footnote about 1.1 percent. Boxes have square corners with no visible shadow. Arrows are thin white lines with small triangular heads. Gauge outlines are thin white circles with about 0.2 percent stroke. No gradients other than the subtle floor reflection.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed background studio photograph (two 3840 by 2160 px image layers covering the slide): dark black backdrop, charcoal floor, server room racks at right, DGX hardware at right (Full-bleed, not cropped inside the slide; dark tint and vignette at top)
- shape at x 3.8, y 21.6, w 68.9, h 61.6 [#111111]: Dark rectangular display panel (Square corners; thin warm bronze-grey border #6B6258 about 0.2 percent width; soft drop shadow beneath; overlaps the background photo)
- photo at x 72.7, y 36, w 24.3, h 22.4: Server room photograph: rows of black racks with beige-grey perforated panels receding into darkness (Cropped by the right slide edge; fades into black at top; sits behind the DGX hardware)
- photo at x 76.9, y 55.3, w 11.5, h 25.6 [#B9AE98]: NVIDIA DGX A100 stack of three beige-grey rackmount units with NVIDIA logos (Boxed, not cropped; overlaps the rack photo and the DGX Station)
- photo at x 86.1, y 64.7, w 8.7, h 27.7 [#B9AE98]: NVIDIA DGX Station tower in beige-grey with lighter top cap and NVIDIA logo near base (Boxed, not cropped; overlaps the DGX A100 stack at its left edge)
- title at x 35.8, y 7.9, w 28.4, h 4.1 [DIN Pro Bold, all caps, slight letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA MEGATRON TRITON
- shape at x 8.4, y 44.7, w 5.8, h 9.3 [#76B900]: Green process box (Square corners, no border, no shadow)
- body at x 9, y 48.6, w 4.7, h 2 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Megatron (Sits on the green box)
- shape at x 16.5, y 44.7, w 5.8, h 9.3 [#76B900]: Green process box (Square corners, no border, no shadow)
- body at x 17.2, y 47.4, w 4.4, h 4.4 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA / Dev Tech (Two lines: NVIDIA / Dev Tech)
- shape at x 24.6, y 44.7, w 9.7, h 9.3 [#76B900]: Green process box (Square corners, no border, no shadow)
- body at x 25.3, y 47.4, w 8.4, h 4.4 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Megatron Triton / Inference Server (Two lines: Megatron Triton / Inference Server)
- line at x 12.8, y 49.4, w 2.8, h 0.5 [#FFFFFF]: Short white right-pointing arrow between Megatron and NVIDIA Dev Tech (Thin stroke about 0.1 percent width, arrowhead at right)
- line at x 22.4, y 49.4, w 2, h 0.5 [#FFFFFF]: Short white right-pointing arrow between NVIDIA Dev Tech and Megatron Triton Inference Server (Thin stroke about 0.1 percent width, arrowhead at right)
- line at x 28.4, y 38.1, w 0.1, h 5.5 [#FFFFFF]: Downward white arrow labelled Query (Thin vertical line with small downward head at its bottom, above the Megatron Triton box)
- line at x 30, y 38.1, w 0.1, h 5.5 [#FFFFFF]: Upward white arrow labelled Response (Thin vertical line with small upward head at its top, above the Megatron Triton box)
- body at x 25.2, y 39.3, w 2.5, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Query
- body at x 30.7, y 39.4, w 4.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Response
- line at x 29.3, y 54.9, w 0.1, h 8.2 [#FFFFFF]: Downward white arrow from the Megatron Triton Inference Server box to the orange bracket (Thin vertical line with arrowhead at its bottom)
- line at x 20.8, y 60.4, w 17.8, h 2 [#B5793A]: Orange-brown bracket connecting five GPU icons (Thin stroke about 0.15 percent width; horizontal bar with five short vertical drops, each ending at one GPU icon)
- icon at x 19.1, y 63.7, w 16.6, h 5.6 [#C9A24A]: GPU icon, five instances in a row (Each icon is a gold-and-grey processor die with a grey dome heat element and gold side memory modules, pixelated fading style; sizes decrease from left to right; overlaps the bracket ends)
- body at x 46.4, y 32, w 18.9, h 2.5 [DIN Pro Medium, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: RUN GPT-3 BASED CHATBOTS
- body at x 46.7, y 39.5, w 6.2, h 4 [DIN Pro Medium; font size 1.98% of slide height; #76B900; center aligned]: 16 QUERIES / 1 Second (Line 1 all caps, line 2 mixed case)
- body at x 47.6, y 44.8, w 4.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: DGX A100
- icon at x 45.7, y 53.2, w 8, h 16.1 [#76B900]: Stopwatch icon, left gauge (Thin white outer and inner ring outline, crown button on top; green wedge needle pointing near 12 o'clock; dial interior black; overlaps no other element)
- body at x 60.1, y 39.5, w 4.9, h 4 [DIN Pro Medium; font size 1.98% of slide height; #0071C5; center aligned]: 1 QUERY / >1 Minute (Line 1 all caps, line 2 mixed case)
- body at x 57.3, y 44.8, w 10.4, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Dual Socket CPU Server
- icon at x 58.5, y 53.2, w 8, h 16.1 [#0071C5]: Stopwatch icon, right gauge (Thin white outer and inner ring outline, crown button on top; solid blue disc about 85 percent filled; white needle near 12 o'clock)
- footer at x 3.9, y 93.2, w 31, h 3.4 [DIN Pro Regular; font size 1.11% of slide height; #9A9A9A; left aligned]: Input sequence length=128 tokens (average of 102 words), Output sequence length=8 tokens (average of 6 words) / GPU: Megatron GPT-3 on DGX-A100-80GB, Batch size=16, FP16, FasterTransformer 4.0, Triton 2.6 / CPU: OpenAI GPT-3 on Xeon Platinum 8280 2S, 755GB System memory, Batch size=1, FP32, TensorFlow 2.3 (Three lines at about 1.2 percent line spacing; each line set separately at y 93.2, 94.4 and 95.6)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 45.7, y 53.2, w 8.0, h 16.1: 382 by 430 pixels
- image at x 58.5, y 53.2, w 8.0, h 16.1: 382 by 430 pixels
- image at x 24.6, y 44.8, w 9.6, h 9.4: 1158 by 633 pixels
- image at x 16.5, y 44.8, w 5.8, h 9.4: 695 by 633 pixels
- image at x 8.4, y 44.8, w 5.8, h 9.4: 695 by 633 pixels
- image at x 35.9, y 63.7, w 3.5, h 5.6: 14 by 12 pixels
- image at x 19.1, y 63.7, w 3.5, h 5.6: 211 by 190 pixels
- image at x 23.3, y 63.7, w 3.5, h 5.6: 106 by 95 pixels
- image at x 27.5, y 63.7, w 3.5, h 5.6: 53 by 48 pixels
- image at x 31.7, y 63.7, w 3.5, h 5.6: 27 by 24 pixels
- text at x 35.8, y 7.9, w 28.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA MEGATRON TRITON
- text at x 46.4, y 32.0, w 18.9, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: RUN GPT-3 BASED CHATBOTS
- text at x 46.7, y 39.5, w 6.2, h 2.0 [DINPro-Medium; font size 1.98; #76B900]: 16 QUERIES
- text at x 60.3, y 39.5, w 4.3, h 2.0 [DINPro-Medium; font size 1.98; #0071C5]: 1 QUERY
- text at x 47.5, y 41.8, w 4.5, h 2.0 [DINPro-Medium; font size 1.98; #76B900]: 1 Second
- text at x 60.1, y 41.8, w 4.9, h 2.0 [DINPro-Medium; font size 1.98; #0071C5]: >1 Minute
- text at x 25.2, y 39.3, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Query
- text at x 30.7, y 39.4, w 4.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Response
- text at x 17.6, y 47.4, w 3.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA
- text at x 25.5, y 47.4, w 7.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Megatron Triton
- text at x 9.0, y 48.6, w 4.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Megatron
- text at x 17.2, y 49.8, w 4.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Dev Tech
- text at x 25.3, y 49.8, w 8.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Inference Server
- text at x 47.6, y 44.8, w 4.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DGX A100
- text at x 57.3, y 44.8, w 10.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Dual Socket CPU Server
- text at x 3.9, y 93.2, w 31.0, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: Input sequence length=128 tokens (average of 102 words), Output sequence length=8 tokens (average of 6 words)
- text at x 3.9, y 94.4, w 27.0, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: GPU: Megatron GPT-3 on DGX-A100-80GB, Batch size=16, FP16, FasterTransformer 4.0, Triton 2.6
- text at x 3.9, y 95.6, w 29.6, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: CPU: OpenAI GPT-3 on Xeon Platinum 8280 2S, 755GB System memory, Batch size=1, FP32, TensorFlow 2.3

### Slide 34

**Text**

ANNOUNCING
NAVER ADOPTS DGX
SUPERPOD TO CREATE
LANGUAGE UNDERSTANDING
AI SERVICES
#1 Internet Tech Platform in Korea
Construct AI R&D Belt Across Asia and Europe
Develop Giant AI Language Models
DGX SuperPOD to Build Global-Scale
AI Supercomputing Infrastructure

**Layout**

Left-aligned text block on the left half, starting at about 6.7% from the left edge, with a bold 'ANNOUNCING' kicker above a four-line uppercase headline and four body lines below it. The NAVER logo sits top-right over the racks at about 60.7% x and 21.1% y. The right half and lower band are occupied by the full-bleed photograph; there is no title placeholder, footer, slide number or logo block beyond the NAVER wordmark.

**Visuals**

Full-bleed dark photograph (3840 by 2160 px, rendered twice as stacked full-slide layers). Subject: a long row of about 20 black NVIDIA DGX SuperPOD server racks, receding to the right, with tan/gold perforated panels, some racks showing blue indicator lights in the middle. In the lower right foreground are three stacked tan DGX systems (about 15% to 20% of slide width) with the NVIDIA logo on their dark side handles, and a taller tan DGX Station tower with an NVIDIA logo near its base. Composition: wide shot, horizon of racks at about 40% of slide height, subjects weighted to the right, floor reflecting in dark grey. Lighting: low-key, dim with directional highlights on the tan panels. Dominant colours: black #000000, charcoal #2A2A2A, tan/gold #C8B48A. Not cropped; full-bleed. No overlay or tint beyond the darkening. Also a green NAVER wordmark logo (768 by 139 px) in bold sans capitals, boxed at x 60.7, y 21.1, w 15.1, h 4.9.

**Design**

Background: Full-bleed dark photograph: black #000000 upper area fading to dark charcoal #2A2A2A floor, with server racks on the right. Black background with a dark charcoal floor photograph; all text white #FFFFFF. Accent: NAVER green #5DB946 in the logo only. Typeface: DIN Pro, a sans-serif. 'ANNOUNCING' in DIN Pro Bold, about 2.96% of slide height. Headline in DIN Pro Regular, uppercase, about 4.07% of slide height, tight leading, about 4.9% line pitch. Body in DIN Pro Regular, sentence case, about 2.22% of slide height, with extra spacing between paragraphs. No shapes, lines, corner radii, shadows or gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed photograph of NVIDIA DGX SuperPOD server racks and three tan DGX systems on a dark reflective floor, with NVIDIA logos visible on the DGX units (Second identical full-slide image layer (3840 by 2160 px) sits behind or over the first; no crop, no overlay, no rotation)
- logo at x 60.7, y 21.1, w 15.1, h 4.9 [#5DB946]: NAVER wordmark in bold green capitals (Image 768 by 139 px, placed over the server racks in the black upper area; no border)
- title at x 6.7, y 28, w 10.6, h 3 [DIN Pro, Bold, uppercase; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING
- title at x 6.7, y 31.8, w 31.6, h 18.8 [DIN Pro, Regular, uppercase; font size 4.07% of slide height; #FFFFFF; left aligned]: NAVER ADOPTS DGX / SUPERPOD TO CREATE / LANGUAGE UNDERSTANDING / AI SERVICES (Four lines at line pitch about 4.9% of slide height; line boxes at y 31.8, 36.7, 41.6, 46.5)
- body at x 6.7, y 53.1, w 19.4, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: #1 Internet Tech Platform in Korea
- body at x 6.7, y 57.8, w 25.8, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Construct AI R&D Belt Across Asia and Europe
- body at x 6.7, y 62.6, w 19.2, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Develop Giant AI Language Models
- body at x 6.7, y 67.3, w 20.8, h 4.6 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: DGX SuperPOD to Build Global-Scale / AI Supercomputing Infrastructure (Two lines, second line at y 69.7; tight line break between them)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 60.7, y 21.1, w 15.1, h 4.9: 768 by 139 pixels
- text at x 6.7, y 31.8, w 21.7, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: NAVER ADOPTS DGX
- text at x 6.7, y 36.7, w 24.5, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: SUPERPOD TO CREATE
- text at x 6.7, y 28.0, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 41.6, w 31.6, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: LANGUAGE UNDERSTANDING
- text at x 6.7, y 46.5, w 12.9, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: AI SERVICES
- text at x 6.7, y 53.1, w 19.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: #1 Internet Tech Platform in Korea
- text at x 6.7, y 57.8, w 25.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Construct AI R&D Belt Across Asia and Europe
- text at x 6.7, y 62.6, w 19.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Develop Giant AI Language Models
- text at x 6.7, y 67.3, w 20.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: DGX SuperPOD to Build Global-Scale
- text at x 6.7, y 69.7, w 18.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: AI Supercomputing Infrastructure

### Slide 35

**Text**

NVIDIA CLARA DISCOVERY
MegaMolBART
ATAC-Seq
AlphaFold1
GatorTron™
CHEMICAL COMPOUNDS
Search
DISEASE TARGET
DRUG TARGET
Genomics
Structure
Docking
Simulation
Imaging
LITERATURE
NLP
REAL WORLD
DATA

**Layout**

A centred bold title sits at the top of the slide with about 8% top margin. Below it a large black panel with a thin bronze border spans about 4% to 73% of the width and 22% to 83% of the height, with a left column of four icon-and-label pairs and a central flow diagram in a horizontal row of five boxes, with a branch row beneath, while a row of server hardware fills the right side outside the panel. No footer, slide number or logo text is visible.

**Visuals**

Diagram and photographs. Left column icons (top to bottom): a thin white line drawing of two molecules on an open book labelled MegaMolBART; a pink and purple cell nucleus with a DNA strand labelled ATAC-Seq; a rainbow-coloured spiral ring labelled AlphaFold1; a white line drawing of a gator with a document labelled GatorTron™. Main flow: five square image boxes in a row labelled Genomics (orange and grey-blue DNA double helix on black), Structure (red and grey spiky virus particle on black), Docking (white and pink protein ribbon structure on black), Simulation (red and cyan molecular stalk on a cyan-dotted membrane surface on black), and Imaging (red fluorescent cell staining on dark red and magenta). Above Docking is a square box labelled Search showing a colourful splash of cyan, green, yellow, magenta and red strokes on black, with a small white arrow pointing down into Docking. Below Docking is a small square box labelled NLP showing a dark screenshot of text passages with green, yellow, pink and cyan highlights. Thin white arrows run left to right between the five main boxes. From Genomics a white line runs down and right to the LITERATURE label then on to the NLP box; from the NLP box a line runs right to the REAL WORLD DATA label then up to Imaging. Right side photograph: a dark data-centre floor with a row of black server racks in the background and three stacked tan NVIDIA DGX stations with a tall tan DGX station beside them in the foreground, lit from above with soft grey light, dominant colours black, charcoal and tan; not cropped, full-bleed behind the panel.

**Design**

Background: Full-bleed photograph of a dark data-centre floor with black server racks, black sky and charcoal #111111 panel laid over it. Pure black background with a dark charcoal panel #111111 bordered by a thin bronze line #6B5E4A. Title and labels are white #FFFFFF in DIN Pro Bold (title) and DIN Pro Regular (labels), sans-serif, uppercase for headings; title about 4.1% of slide height, labels about 1.7% to 2.0% of slide height. Connector lines and arrows are white #FFFFFF, about 0.2% of slide height thick, with small arrowheads. Image boxes have thin white #FFFFFF outlines with square corners and no shadow. Accent colours come only from the imagery. No gradients or shadows; the floor has a soft reflective grey sheen.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed photograph of dark data-centre floor with server racks and tan NVIDIA DGX stations (Full bleed, not cropped, dark lighting, charcoal and black dominant, tan DGX stations on right)
- shape at x 3.8, y 21.6, w 69, h 61.5 [#111111]: Dark panel (Rectangle, square corners, thin bronze border #6B5E4A about 0.2% thick, no shadow, sits over the photograph)
- icon at x 9.2, y 31.1, w 6.5, h 3.1 [#FFFFFF]: MegaMolBART icon: molecules and open book line drawing (Thin white line art, no fill)
- text at x 9.5, y 35.6, w 6.3, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: MegaMolBART
- icon at x 11, y 40.9, w 3.3, h 6.2 [#D0306A]: ATAC-Seq icon: cell nucleus with DNA strand (Pink and purple cell nucleus over a white line DNA strand)
- text at x 10.5, y 48.1, w 4.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: ATAC-Seq
- icon at x 9.2, y 53.3, w 6.8, h 7.5: AlphaFold1 icon: rainbow spiral ring (Multicolour spiral ring of blue, green, yellow and red on black)
- text at x 10.3, y 61.2, w 4.8, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: AlphaFold1
- icon at x 10.6, y 67.8, w 4.2, h 3.2 [#FFFFFF]: GatorTron icon: gator with document line drawing (Thin white line art)
- text at x 10.2, y 72.3, w 4.3, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: GatorTron
- text at x 14.5, y 72.6, w 0.6, h 0.8 [DIN Pro Regular; font size 0.82% of slide height; #FFFFFF; left aligned]: TM (Superscript trademark mark after GatorTron)
- text at x 39.4, y 30.7, w 12.4, h 2 [DIN Pro Regular, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: CHEMICAL COMPOUNDS
- photo at x 42.4, y 34.7, w 6.5, h 10.8 [#000000]: Search image: colourful particle splash (Square box, thin white outline, colourful cyan, green, yellow, magenta and red strokes on black)
- text at x 44.1, y 43.3, w 3, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Search
- shape at x 45.5, y 46.6, w 0.2, h 2.3 [#FFFFFF]: Down arrow from Search box to Docking box (Thin white line with small arrowhead pointing down)
- text at x 26.6, y 44.6, w 8.6, h 2 [DIN Pro Regular, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: DISEASE TARGET
- text at x 56.8, y 44.6, w 7.2, h 2 [DIN Pro Regular, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: DRUG TARGET
- photo at x 22.7, y 48.9, w 6.5, h 10.7 [#000000]: Genomics image: DNA double helix (Square box on black fill, thin white outline, orange and grey-blue helix)
- text at x 23.8, y 57.5, w 4.3, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Genomics
- shape at x 29.5, y 54.4, w 2.5, h 0.5 [#FFFFFF]: Arrow Genomics to Structure (Thin white line with arrowhead)
- photo at x 32, y 48.9, w 7.7, h 10.8: Structure image: red and grey virus particle (Square box, thin white outline, red spiky sphere on black)
- text at x 33.8, y 57.5, w 4.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Structure
- shape at x 39.5, y 54.4, w 2.5, h 0.5 [#FFFFFF]: Arrow Structure to Docking (Thin white line with arrowhead)
- photo at x 42.4, y 48.9, w 6.5, h 10.8: Docking image: protein ribbon structure (Square box, thin white outline, white and pink protein ribbon on black)
- text at x 43.9, y 57.5, w 3.5, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Docking
- shape at x 49.5, y 54.4, w 2.5, h 0.5 [#FFFFFF]: Arrow Docking to Simulation (Thin white line with arrowhead)
- photo at x 52.2, y 48.9, w 6.5, h 10.8 [#000000]: Simulation image: molecular stalk on membrane (Square box, thin white outline, red and cyan structure over cyan-dotted surface on black)
- text at x 53.1, y 57.5, w 4.6, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Simulation
- shape at x 59.5, y 54.4, w 2.5, h 0.5 [#FFFFFF]: Arrow Simulation to Imaging (Thin white line with arrowhead)
- photo at x 62.1, y 49, w 6.5, h 10.8 [#000000]: Imaging image: red fluorescent cells (Square box, thin white outline, red and magenta cell staining on dark red)
- text at x 63.6, y 57.5, w 3.5, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Imaging
- shape at x 26, y 60.6, w 18, h 6.5 [#FFFFFF]: Connector line from Genomics down then right to LITERATURE (Thin white elbow line, about 0.2% thick, no arrowhead)
- photo at x 42.4, y 62.8, w 6.5, h 10.8: NLP image: dark text screenshot with highlights (Square box, thin white outline, black ground with green, yellow, pink and cyan highlighted text lines)
- text at x 44.7, y 71.4, w 1.9, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NLP
- text at x 32.6, y 66.2, w 6.3, h 2 [DIN Pro Regular, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: LITERATURE
- text at x 52.1, y 65.1, w 7, h 4 [DIN Pro Regular, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: REAL WORLD DATA (Two lines: REAL WORLD / DATA)
- shape at x 49, y 60.6, w 17, h 6.5 [#FFFFFF]: Connector line from NLP to REAL WORLD DATA and up to Imaging (Thin white elbow line, about 0.2% thick, no arrowhead)
- photo at x 72, y 36, w 25, h 56: Server racks and DGX stations on data-centre floor (Black server racks behind, three stacked tan DGX stations and tall tan DGX station in front, lit softly, overlapping the panel edge)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 52.2, y 48.9, w 6.5, h 10.8: #000000
- fill at x 22.7, y 49.0, w 6.5, h 10.7: #000000
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 32.0, y 48.9, w 7.7, h 10.8: 400 by 300 pixels
- image at x 42.4, y 62.8, w 6.5, h 10.8: 433 by 429 pixels
- image at x 52.2, y 48.9, w 6.5, h 10.8: 514 by 450 pixels
- image at x 42.4, y 48.9, w 6.5, h 10.8: 389 by 366 pixels
- image at x 62.1, y 49.0, w 6.5, h 10.8: 346 by 320 pixels
- image at x 42.4, y 34.7, w 6.5, h 10.8: 500 by 500 pixels
- image at x 22.7, y 48.9, w 6.5, h 10.7: 481 by 427 pixels
- image at x 9.2, y 53.3, w 6.8, h 7.5: 317 by 199 pixels
- image at x 42.4, y 68.8, w 6.5, h 4.7: 186 by 76 pixels
- image at x 42.4, y 68.8, w 6.5, h 4.7: 186 by 76 pixels
- image at x 62.1, y 55.3, w 6.5, h 4.5: 187 by 73 pixels
- image at x 62.1, y 55.3, w 6.5, h 4.5: 187 by 73 pixels
- image at x 52.2, y 55.2, w 6.5, h 4.4: 186 by 72 pixels
- image at x 52.2, y 55.2, w 6.5, h 4.4: 186 by 72 pixels
- image at x 42.4, y 41.0, w 6.5, h 4.4: 186 by 72 pixels
- image at x 42.4, y 41.0, w 6.5, h 4.4: 186 by 72 pixels
- image at x 32.6, y 55.1, w 6.4, h 4.4: 185 by 72 pixels
- image at x 32.6, y 55.1, w 6.4, h 4.4: 185 by 72 pixels
- image at x 42.4, y 55.1, w 6.5, h 4.4: 187 by 71 pixels
- image at x 42.4, y 55.1, w 6.5, h 4.4: 187 by 71 pixels
- image at x 22.7, y 55.3, w 6.5, h 4.4: 187 by 71 pixels
- image at x 22.7, y 55.3, w 6.5, h 4.4: 187 by 71 pixels
- image at x 11.0, y 40.9, w 3.3, h 6.2: 196 by 211 pixels
- image at x 9.3, y 31.1, w 6.5, h 3.1: 508 by 135 pixels
- image at x 10.6, y 67.8, w 4.2, h 3.2: 240 by 105 pixels
- text at x 36.2, y 7.9, w 27.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA CLARA DISCOVERY
- text at x 39.4, y 30.7, w 12.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: CHEMICAL COMPOUNDS
- text at x 9.5, y 35.6, w 6.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MegaMolBART
- text at x 26.6, y 44.6, w 8.6, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DISEASE TARGET
- text at x 56.8, y 44.6, w 7.2, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DRUG TARGET
- text at x 44.1, y 43.3, w 3.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Search
- text at x 10.5, y 48.1, w 4.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ATAC-Seq
- text at x 52.1, y 65.1, w 7.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: REAL WORLD
- text at x 23.8, y 57.5, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Genomics
- text at x 32.6, y 66.2, w 6.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: LITERATURE
- text at x 33.8, y 57.5, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Structure
- text at x 43.9, y 57.5, w 3.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Docking
- text at x 53.1, y 57.5, w 4.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Simulation
- text at x 63.6, y 57.5, w 3.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Imaging
- text at x 54.2, y 67.4, w 2.6, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DATA
- text at x 10.3, y 61.2, w 4.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AlphaFold1
- text at x 44.7, y 71.4, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NLP
- text at x 10.2, y 72.3, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GatorTron
- text at x 14.5, y 72.6, w 0.6, h 0.8 [DINPro-Regular; font size 0.82; #FFFFFF]: TM

### Slide 36

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

ANNOUNCING OXFORD NANOPORE TECHNOLOGIES ADOPTS NVIDIA DGX
NANOPORE SEQUENCE PROCESS
Model Trained on DGX SuperPOD | Inference on DGX or V100 or Jetson
PromethION with DGX
GridION with V100
MinION Mk1C with AGX
DNA SAMPLE
NANOPORE
NANOPORE
SEQUENCING SIGNAL
“BONITO"
BASE CALLER
98.3% RAW ACCURACY
AGCGCGTTGATT
AGCG C GTTGATT
CGC G TTGATTT
AGCGC G ATGAT
“MEDAKA”
VARIANT CALLER
99.9% SNV
DGX STATION
NVIDIA
NVIDIA
NVIDIA

**Layout**

Full-bleed dark studio scene with the title centred across the top band, about 8 percent from the top edge. A large black board sits on the left and centre, with its left edge at about 3.8 percent and right edge at about 72.7 percent of the width, and its top at about 21.6 percent and bottom at about 83.1 percent. Inside the board, a left column of three device images with captions is stacked vertically, and a centred process header sits above a horizontal row of four circles joined by arrows; labels sit under each circle. No footer, page number or source line is visible.

**Visuals**

Full-bleed dark studio render behind everything: a black floor with soft reflections and a black wall. At the back right, a row of dark server racks, cropped at the right edge, with tan-grey DGX units in front. Board: a flat near-black panel with a thin bronze outline, placed in front of the render. Left column, top to bottom: Oxford Nanopore Technologies logo; photo of a PromethION device (silver-grey chassis with a row of slots on top and a round button on the front); photo of a GridION device (dark grey box with a row of port slots on top); photo of a MinION Mk1C device (small flat silver-grey unit with a blue screen on top). Process row: four white outline circles of equal size joined by three short white arrows pointing right. Circle 1: illustration of a cyan double-helix DNA strand running into a tan-grey nanopore protein shape. Circle 2: a grey-white stippled sine-like signal wave. Circle 3: a small code window with three dots in the title bar, a tan thin outline, the sequence AGCGCGTTGATT in grey, and a small white neural-network node icon below. Circle 4: a code window with three dots, tan thin outline, three rows of sequence text (AGCGCGTTGATT, CGCGTTGATT, AGCGCGATGAT) in grey with one white highlighted C in the top row and one white G in the second and third rows, and a small neural-network node icon below. Right side: photo of NVIDIA DGX Station units. Three stacked tan-beige boxes with NVIDIA logos, and a taller beige tower with a lighter top panel and an NVIDIA logo near its base. Lighting is a soft spotlight on the board and the DGX hardware against a dark room. Dominant colours: black, dark grey, tan and beige, white, cyan.

**Design**

Background: Black (#000000) full-bleed photographic studio render with dark floor and wall. Black background (#000000) with a near-black board (#0D0D0D) and bronze thin outline (#7A6A55). Title and subtitle text is white (#FFFFFF). Body and caption text is white (#FFFFFF). Sequence letters are grey (#8C8C8C) with white highlighted letters (#FFFFFF). Accent colour is cyan (#1EB5C8) in the DNA and logo, and tan (#A89C8C) in the nanopore shape. Typeface is a geometric sans-serif similar to DIN Pro; title is bold uppercase at about 4.1 percent of slide height, subtitle medium uppercase at about 2.2 percent, body and captions regular at about 1.7 percent. Circles have thin white outlines (about 0.15 percent of slide width). Arrows are thin white lines with small filled arrowheads. No corner radii, shadows or gradients on the board.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio render of black floor, wall and server racks with NVIDIA DGX hardware at right (Covers the slide, behind all other elements. Underlying fill is #FFFFFF but fully hidden by the photo.)
- shape at x 3.8, y 21.6, w 68.9, h 61.5 [#0D0D0D]: Board: flat near-black rectangle with thin bronze outline (Stroke bronze #7A6A55 about 0.2 percent of slide width; square corners; no shadow visible; sits in front of the photo.)
- title at x 12.4, y 7.9, w 75.1, h 4.1 [DINPro-Bold, uppercase, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING OXFORD NANOPORE TECHNOLOGIES ADOPTS NVIDIA DGX
- logo at x 7.3, y 33.3, w 10.6, h 3.3 [#FFFFFF]: Oxford Nanopore Technologies logo: blue swirl mark with white bold NANOPORE wordmark and small Oxford and Technologies text (Swirl in cyan-blue #1EB5C8; source image 560 by 98 pixels.)
- photo at x 9.4, y 40.7, w 6.5, h 6.4: PromethION device: silver-grey chassis with row of slots on top and round button on front (Boxed, no crop, on black; source 415 by 229 pixels.)
- text at x 7.9, y 48.1, w 9.5, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: PromethION with DGX
- photo at x 10.1, y 53.1, w 5, h 7.4: GridION device: dark grey box with row of port slots on top (Boxed, no crop, on black; source 229 by 192 pixels.)
- text at x 8.7, y 61.2, w 7.8, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: GridION with V100
- photo at x 10.2, y 65.7, w 4.9, h 5.7: MinION Mk1C device: small flat silver-grey unit with blue screen on top (Boxed, no crop, on black; source 296 by 192 pixels.)
- text at x 7.7, y 72.3, w 9.9, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: MinION Mk1C with AGX
- subtitle at x 36.4, y 30.5, w 18.9, h 2.2 [DINPro-Medium, uppercase; font size 2.22% of slide height; #FFFFFF; center aligned]: NANOPORE SEQUENCE PROCESS
- body at x 30.5, y 32.8, w 30.6, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Model Trained on DGX SuperPOD | Inference on DGX or V100 or Jetson
- shape at x 23.6, y 42.2, w 8.8, h 15.7 [#000000]: Circle 1 outline, empty (Thin white stroke about 0.15 percent of slide width, no fill, perfect circle.)
- shape at x 35.3, y 42.2, w 8.8, h 15.7 [#000000]: Circle 2 outline, empty (Thin white stroke, no fill, perfect circle.)
- shape at x 47, y 42.2, w 8.8, h 15.7 [#000000]: Circle 3 outline, empty (Thin white stroke, no fill, perfect circle.)
- shape at x 58.7, y 42.2, w 8.8, h 15.7 [#000000]: Circle 4 outline, empty (Thin white stroke, no fill, perfect circle.)
- illustration at x 23.9, y 41.1, w 6.2, h 18.2 [#1EB5C8]: DNA sample: cyan double-helix strand running into a tan-grey nanopore protein shape (Protein shape tan-grey #A89C8C; extends slightly past circle 1 top and bottom.)
- illustration at x 35.4, y 43.1, w 8.2, h 14.6 [#8C8C8C]: Nanopore sequencing signal: grey-white stippled wavy signal (Dotted waveform inside circle 2; source 288 by 288 pixels.)
- illustration at x 48.2, y 46.6, w 6.8, h 5.2 [#000000]: Bonito code window: three dots title bar, sequence AGCGCGTTGATT in grey, small neural-network node icon below (Thin tan outline #8B7355; title bar line at top; sequence text grey #8C8C8C; sits inside circle 3.)
- illustration at x 50.5, y 52.5, w 1.9, h 4.5 [#FFFFFF]: Neural-network node icon under bonito code window (White nodes and thin connecting lines; source 108 by 143 pixels.)
- text at x 49.3, y 61.3, w 4.2, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: “BONITO"
- text at x 48.4, y 63.2, w 6.2, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: BASE CALLER
- text at x 46.5, y 65, w 9.9, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: 98.3% RAW ACCURACY
- text at x 48.5, y 47.9, w 6, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: AGCGCGTTGATT
- illustration at x 59.8, y 46.5, w 6.7, h 5.5 [#000000]: Medaka code window: three dots title bar, three rows of sequence text with highlighted letters, small neural-network node icon below (Thin tan outline #8B7355; grey #8C8C8C sequence letters with white highlighted C and G; sits inside circle 4.)
- text at x 60.4, y 47.9, w 2.1, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: AGCG
- text at x 62.6, y 47.9, w 0.5, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; left aligned]: C
- text at x 63.1, y 47.9, w 3.3, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: GTTGATT
- text at x 61, y 49.3, w 1.6, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: CGC
- text at x 62.6, y 49.3, w 0.5, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; left aligned]: G
- text at x 63.1, y 49.3, w 3.3, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: TTGATTT
- text at x 59.9, y 50.7, w 2.6, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: AGCGC
- text at x 62.6, y 50.7, w 0.5, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; left aligned]: G
- text at x 63.1, y 50.7, w 4, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #8C8C8C; left aligned]: ATGAT
- illustration at x 62.3, y 52.6, w 1.9, h 4.5 [#FFFFFF]: Neural-network node icon under medaka code window (White nodes and thin connecting lines; source 108 by 143 pixels.)
- text at x 60.9, y 61.3, w 4.6, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: “MEDAKA”
- text at x 59.3, y 63.2, w 7.6, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: VARIANT CALLER
- text at x 60.8, y 65, w 4.7, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: 99.9% SNV
- text at x 25, y 61.3, w 5.9, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: DNA SAMPLE
- text at x 37.2, y 61.3, w 5.1, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: NANOPORE
- text at x 25.4, y 63.2, w 5.1, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: NANOPORE
- text at x 35, y 63.2, w 9.6, h 1.7 [DINPro-Regular, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: SEQUENCING SIGNAL
- shape at x 32.6, y 50.1, w 2.5, h 0 [#FFFFFF]: Arrow 1, from circle 1 to circle 2 (Thin white line with small filled arrowhead pointing right.)
- shape at x 44.4, y 50.1, w 2.5, h 0 [#FFFFFF]: Arrow 2, from circle 2 to circle 3 (Thin white line with small filled arrowhead pointing right.)
- shape at x 56, y 50.1, w 2.5, h 0 [#FFFFFF]: Arrow 3, from circle 3 to circle 4 (Thin white line with small filled arrowhead pointing right.)
- photo at x 72.5, y 36, w 25, h 23: Dark server racks with glowing rack-mounted NVIDIA DGX SuperPOD units at back right, cropped at right edge (Dark black racks with tan-grey inserted modules; sits behind the DGX Station units; no tint.)
- photo at x 77, y 55.5, w 11.5, h 25.5: Three stacked tan-beige NVIDIA DGX Station units with NVIDIA logos on their side panels (Boxed on the dark floor, overlaps the server racks; each unit has a dark side strip with a small NVIDIA logo.)
- photo at x 86, y 65, w 9.5, h 27: Tall beige NVIDIA DGX Station tower with lighter top panel, NVIDIA logo near base (Tower in front of stacked units; top panel small DGX STATION label.)
- text at x 88, y 70.5, w 4.5, h 0.8 [DINPro-Regular, uppercase; font size 0.6% of slide height; #4A4032; center aligned]: DGX STATION (Tiny label on the tower top panel; dark brown on beige.)
- text at x 77.8, y 62, w 1, h 0.8 [DINPro-Bold, uppercase; font size 0.5% of slide height; #D8CFBE; left aligned]: NVIDIA (Logo wordmark on the side strip of the top stacked unit.)
- text at x 88, y 89.5, w 2.5, h 0.8 [DINPro-Bold, uppercase; font size 0.5% of slide height; #4A4032; center aligned]: NVIDIA (Logo wordmark on the lower front of the tower.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 35.4, y 43.1, w 8.2, h 14.6: 288 by 288 pixels
- image at x 23.9, y 41.1, w 6.2, h 18.2: 176 by 288 pixels
- image at x 9.4, y 40.7, w 6.5, h 6.4: 415 by 229 pixels
- image at x 10.1, y 53.1, w 5.0, h 7.4: 229 by 192 pixels
- image at x 7.3, y 33.3, w 10.6, h 3.3: 560 by 98 pixels
- image at x 10.2, y 65.7, w 4.9, h 5.7: 296 by 192 pixels
- image at x 50.5, y 52.5, w 1.9, h 4.5: 108 by 143 pixels
- image at x 62.3, y 52.6, w 1.9, h 4.5: 108 by 143 pixels
- text at x 12.4, y 7.9, w 75.1, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING OXFORD NANOPORE TECHNOLOGIES ADOPTS NVIDIA DGX
- text at x 36.4, y 30.5, w 18.9, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: NANOPORE SEQUENCE PROCESS
- text at x 30.5, y 32.8, w 30.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Model Trained on DGX SuperPOD | Inference on DGX or V100 or Jetson
- text at x 7.9, y 48.1, w 9.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: PromethION with DGX
- text at x 48.5, y 47.9, w 6.0, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: AGCGCGTTGATT
- text at x 60.4, y 47.9, w 2.1, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: AGCG
- text at x 62.6, y 47.9, w 0.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: C
- text at x 63.1, y 47.9, w 3.3, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: GTTGATT
- text at x 61.0, y 49.3, w 1.6, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: CGC
- text at x 62.6, y 49.3, w 0.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: G
- text at x 63.1, y 49.3, w 3.3, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: TTGATTT
- text at x 59.9, y 50.7, w 2.6, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: AGCGC
- text at x 62.6, y 50.7, w 0.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: G
- text at x 63.1, y 50.7, w 4.0, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: ATGAT
- text at x 8.7, y 61.2, w 7.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GridION with V100
- text at x 25.0, y 61.3, w 5.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DNA SAMPLE
- text at x 37.2, y 61.3, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NANOPORE
- text at x 49.3, y 61.3, w 4.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: “BONITO"
- text at x 60.9, y 61.3, w 4.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: “MEDAKA”
- text at x 25.4, y 63.2, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NANOPORE
- text at x 35.0, y 63.2, w 9.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: SEQUENCING SIGNAL
- text at x 48.4, y 63.2, w 6.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: BASE CALLER
- text at x 59.3, y 63.2, w 7.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VARIANT CALLER
- text at x 46.5, y 65.0, w 9.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 98.3% RAW ACCURACY
- text at x 60.8, y 65.0, w 4.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 99.9% SNV
- text at x 7.7, y 72.3, w 9.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MinION Mk1C with AGX

### Slide 37

**Text**

ANNOUNCING / SCHRODINGER AND NVIDIA / ACCELERATE DRUG DISCOVERY / $1.25 Trillion Dollar Industry | 10+ Years / Development | 3,000 Pharma Companies / Accelerating Schrodinger's Physics and Machine Learning- / Based Computational Drug Discovery Tools with NVIDIA / Clara Discovery Acceleration Libraries on NVIDIA DGX A100 / Achieve Experimentally-Accurate Simulations / SCHRODINGER

**Layout**

Full-bleed dark photographic slide with a left-aligned text block occupying the left third, starting at about 6.7% from the left edge. The 'ANNOUNCING' kicker sits at the top of the text block, followed by a two-line title, a two-line subtitle, a three-line paragraph and a single closing line. The Schrodinger logo sits top-right over the black background, above the server racks. No footer or slide number is visible.

**Visuals**

Photograph of a data-centre scene: a long row of black server racks with gold-beige NVIDIA DGX A100 units on the right foreground. Left to right across the back, about 17 tall black racks with beige-grey perforated panels; a few racks in the centre show glowing blue indicator lights. In the right foreground, a stack of three rectangular beige-gold DGX A100 chassis sits atop/beside a taller tower-format beige-gold DGX Station unit with the NVIDIA logo on its front lower panel. The scene is lit dimly with a soft spotlight from above, the background is black, and the floor is dark grey with a reflective sheen. Composition is landscape, full-bleed, subject occupying the right half. Dominant colours: black, charcoal grey, gold-beige, with blue indicator lights and a blue logo. The Schrodinger wordmark is a blue (#0A6EBD approx.) logotype with two small orange dots above the O, positioned top-right at about 59.4% x, 23.3% y, 19.6% wide, 5.1% high, with a small registered mark at its end.

**Design**

Background: Full-bleed black (#000000) photograph fading to dark charcoal grey floor (#2A2A2A approx.), with the DGX racks visible. Black background with a dark charcoal floor photograph. Title and body text are white (#FFFFFF). The Schrodinger logo is blue #0A6EBD with orange accent dots (#E8642C approx.). Typefaces are DIN Pro, a geometric grotesque sans-serif. 'ANNOUNCING' is DIN Pro Bold in capitals, about 2.96% of slide height. The title lines are DIN Pro Regular in capitals, about 4.07% of slide height, with generous line spacing. The subtitle is DIN Pro Regular about 2.72% of slide height. The body paragraph and closing line are DIN Pro Regular about 2.22% of slide height with comfortable leading. No shapes, borders, corner radii, shadows or gradients are present.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed background photograph of the data-centre scene with black background, server racks and DGX A100 units on dark reflective floor (Covers the entire slide, not cropped, no overlay; 3840 by 2160 pixels.)
- logo at x 59.4, y 23.3, w 19.6, h 5.1 [#0A6EBD]: Schrodinger wordmark logo (blue SCHRODINGER text with orange dots over the O and small registered mark) (Image 1177 by 172 pixels, orange dots #E8642C approx., sits above the server racks in the top right.)
- title at x 6.7, y 30.6, w 10.6, h 3 [DIN Pro Bold, capitals, no letter-spacing noted; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING (Kicker above the title.)
- title at x 6.7, y 34.4, w 32.9, h 8.9 [DIN Pro Regular, capitals; font size 4.07% of slide height; #FFFFFF; left aligned]: SCHRODINGER AND NVIDIA / ACCELERATE DRUG DISCOVERY (Two lines; line 1 at y 34.4, line 2 at y 39.3, line height about 4.9% of slide height.)
- body at x 6.7, y 43.9, w 28.7, h 5.6 [DIN Pro Regular, mixed case; font size 2.72% of slide height; #FFFFFF; left aligned]: $1.25 Trillion Dollar Industry | 10+ Years / Development | 3,000 Pharma Companies (Two lines, line spacing about 2.9% of slide height; vertical bars separated by double spaces.)
- body at x 6.7, y 52.7, w 32.9, h 7.5 [DIN Pro Regular, mixed case; font size 2.22% of slide height; #FFFFFF; left aligned]: Accelerating Schrodinger's Physics and Machine Learning- / Based Computational Drug Discovery Tools with NVIDIA / Clara Discovery Acceleration Libraries on NVIDIA DGX A100 (Three lines, line spacing about 2.6% of slide height, ragged right.)
- body at x 6.7, y 62.8, w 25.7, h 2.2 [DIN Pro Regular, mixed case; font size 2.22% of slide height; #FFFFFF; left aligned]: Achieve Experimentally-Accurate Simulations (Single line closing statement.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 59.4, y 23.3, w 19.6, h 5.1: 1177 by 172 pixels
- text at x 6.7, y 34.4, w 29.1, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: SCHRODINGER AND NVIDIA
- text at x 6.7, y 39.3, w 32.9, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: ACCELERATE DRUG DISCOVERY
- text at x 6.7, y 30.6, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 43.9, w 28.5, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: $1.25 Trillion Dollar Industry | 10+ Years
- text at x 6.7, y 46.8, w 28.7, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Development | 3,000 Pharma Companies
- text at x 6.7, y 52.7, w 32.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Accelerating Schrodinger's Physics and Machine Learning-
- text at x 6.7, y 55.4, w 31.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Based Computational Drug Discovery Tools with NVIDIA
- text at x 6.7, y 58.0, w 32.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Clara Discovery Acceleration Libraries on NVIDIA DGX A100
- text at x 6.7, y 62.8, w 25.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Achieve Experimentally-Accurate Simulations

### Slide 38

**Text**

ANNOUNCING
RECURSION BUILDS
PHARMA AI SUPERCOMPUTER
WITH NVIDIA DGX SUPERPOD
BioHive-1 Aims to Decode Biology and
Industrialize Drug Discovery
Recursion OS Built on NVIDIA DGX SuperPOD
Generates, Analyzes, and Derives Insight from
Biological and Chemical Datasets
Generate up to 9 Million Images, or Approximately
80 Terabytes of Data, Across up to 1.5 Million
Experiments per Week

**Layout**

A full-bleed dark photograph fills the slide. A left-aligned text block sits in the left third, starting at about 6.7% from the left edge and vertically centred around 30% to 72% of the height. The rack row runs across the upper right, and two stacked DGX units sit at the lower right; there is no footer, no page number and no logo text in the title area.

**Visuals**

Photograph of a large data-centre hall with a long row of black server racks with gold-beige front panels, receding to the right, with about 20 racks visible; two racks in the middle carry blue-lit indicator panels. In the foreground at lower right is a stack of three gold-beige DGX server units with NVIDIA logos on their left ends, beside a taller gold-beige DGX Station unit with an NVIDIA logo on its front near the base. Lighting is dark and low-key with soft highlights on the gold-beige surfaces and a faint blue glow from the indicator lights. Composition is wide, full-bleed, with the racks cropped off the right edge of the content area and the floor reflecting the units. Dominant colours are black, charcoal grey and gold-beige (about #C9B99A). No overlay or tint beyond the dark scene.

**Design**

Background: Full-bleed dark photograph of a data-centre hall with a black ceiling and charcoal floor (#1A1A1A to #000000). Black background with a dark charcoal floor photograph. Title and body text are white (#FFFFFF) in DIN Pro, a condensed grotesque sans-serif. ANNOUNCING is DIN Pro Bold, about 3.0% of slide height, all capitals. The main headline is DIN Pro Regular, all capitals, about 4.1% of slide height, set in four lines with tight leading. The subtitle and detail lines are DIN Pro Regular, about 2.2% to 2.7% of slide height, in sentence case. Accents are none; no shapes, lines or gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed data-centre photograph showing a row of black server racks with gold-beige panels, three stacked DGX units and one DGX Station at lower right (Covers the entire slide, not cropped inside a box, no overlay, no rotation)
- title at x 6.7, y 30.6, w 10.6, h 3 [DIN Pro Bold, capitals; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING
- title at x 6.7, y 34.3, w 32.2, h 18 [DIN Pro Regular, capitals; font size 4.07% of slide height; #FFFFFF; left aligned]: RECURSION BUILDS / PHARMA AI SUPERCOMPUTER / WITH NVIDIA DGX SUPERPOD (Three lines at about 4.1% line pitch)
- subtitle at x 6.7, y 48.8, w 26.2, h 5.6 [DIN Pro Regular, sentence case; font size 2.72% of slide height; #FFFFFF; left aligned]: BioHive-1 Aims to Decode Biology and / Industrialize Drug Discovery
- body at x 6.7, y 57.2, w 25.9, h 7 [DIN Pro Regular, sentence case; font size 2.22% of slide height; #FFFFFF; left aligned]: Recursion OS Built on NVIDIA DGX SuperPOD / Generates, Analyzes, and Derives Insight from / Biological and Chemical Datasets (Line pitch about 2.4% of slide height)
- body at x 6.7, y 66.7, w 28.1, h 7 [DIN Pro Regular, sentence case; font size 2.22% of slide height; #FFFFFF; left aligned]: Generate up to 9 Million Images, or Approximately / 80 Terabytes of Data, Across up to 1.5 Million / Experiments per Week (Line pitch about 2.4% of slide height)
- illustration at x 44, y 36, w 52, h 22 [#1A1A1A]: Row of about 20 black server racks with gold-beige front panels receding to the right, two racks with blue indicator lights (Part of the background photograph, not a separate object)
- illustration at x 76.8, y 55.5, w 12.5, h 25 [#C9B99A]: Stack of three gold-beige NVIDIA DGX server units with NVIDIA logos on their left ends (Part of the background photograph, not a separate object)
- illustration at x 86.1, y 65, w 7.9, h 27.5 [#C9B99A]: Gold-beige NVIDIA DGX Station unit with a light top and NVIDIA logo near the base (Part of the background photograph, not a separate object)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 34.3, w 21.6, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: RECURSION BUILDS
- text at x 6.7, y 39.2, w 32.2, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: PHARMA AI SUPERCOMPUTER
- text at x 6.7, y 30.6, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 44.1, w 30.3, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: WITH NVIDIA DGX SUPERPOD
- text at x 6.7, y 48.8, w 26.2, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: BioHive-1 Aims to Decode Biology and
- text at x 6.7, y 51.7, w 19.1, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Industrialize Drug Discovery
- text at x 6.7, y 57.2, w 25.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Recursion OS Built on NVIDIA DGX SuperPOD
- text at x 6.7, y 59.6, w 25.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Generates, Analyzes, and Derives Insight from
- text at x 6.7, y 62.0, w 18.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Biological and Chemical Datasets
- text at x 6.7, y 66.7, w 28.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Generate up to 9 Million Images, or Approximately
- text at x 6.7, y 69.1, w 25.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 80 Terabytes of Data, Across up to 1.5 Million
- text at x 6.7, y 71.5, w 12.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Experiments per Week

### Slide 39

**Text**

IBM

**Layout**

Full-bleed photograph covering the entire slide with no title, body text or margins; a small IBM logo sits in the bottom-left corner, about 4.7% from the left edge and about 92.7% from the top, with no footer or slide number visible.

**Visuals**

Photograph of an IBM quantum computer processor assembly, shown full-bleed. The subject is a gold-plated cryogenic cooling stage: a large gold circular plate at the top with dense rows of gold and silver coaxial cables and hexagonal gold connectors hanging downward in clusters. Below the plate, copper-coloured mounting boards hold rows of gold SMA connectors and bundles of silver flexible cables that curve and loop outward. At the centre bottom is a small square chip package on a copper and silver mount with a cable bundle above and below it. Vertical polished silver and chrome pillars run through the upper centre. The composition is centred and symmetrical, shot straight-on at eye level, with the assembly filling most of the frame. Lighting is bright and warm on the gold and copper parts, with cool blue reflections on the surrounding glass-like enclosure on left and right and a white base at the bottom. Dominant colours: gold #C8A24A, copper #B87333, silver #C0C0C0, deep blue #1E3A8A, white #FFFFFF. The photograph is not cropped in a visible way beyond full-bleed, has no overlay or tint. Small IBM logo in the bottom-left in white stripes-style wordmark on a dark background area.

**Design**

Background: Full-bleed photograph of the IBM quantum processor assembly, with a solid #FFFFFF fill behind it. No text or typography on the slide other than the IBM logo. Background is the photograph itself. The logo is white or light grey (#FFFFFF) with the IBM eight-bar wordmark. No accent colours, no shapes, no borders, no shadows, no gradients added by the design; the look is purely photographic.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide solid fill behind the photograph (Covers the entire slide; hidden beneath the photograph.)
- photo at x 0, y 0, w 100, h 100 [#C8A24A]: Full-bleed photograph of an IBM quantum processor cryostat stage with gold plate, gold and silver coaxial cables, copper mounting boards and a central chip package, set inside a blue-tinted glass enclosure (Covers the whole slide, not cropped in a visible way, no overlay or tint, no rounded corners or shadow.)
- logo at x 4.7, y 92.7, w 7.3, h 6.2 [#FFFFFF]: IBM logo (eight-bar wordmark) (Placed bottom-left over the photograph, about 355 by 169 pixels; white striped wordmark with registered mark, sits on the dark lower-left area of the image.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2500 by 1408 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 4.7, y 92.7, w 7.3, h 6.2: 355 by 169 pixels

### Slide 40

**Text**

GLOBAL QUANTUM COMPUTING RACE
QUANTUM COMPUTING
RESEARCH ECOSYSTEM
DOUBLING PHYSICAL QUBITS
EVERY YEAR
10,000,000
1,000,000
Fault-Tolerant Quantum Computing
Speedups Threshold
100,000
10,000
Qubits
1,000
100
10
1
2010
2015
2020
2025
2030
2035
2040
Major Academic and Non-Profit/Governmental Quantum Computing Research Institutions
Europe / Rest of World / N. America
Universities
Oxford, Innsbruck, QAR Lab, Ludwig Maximilian University of Munich, NQIT, Nanjing/Quantum Mac, University of Sydney, University of Science and Technology of China, Harvard Quantum Initiative, Caltech, MIT Physics, Berkeley, Joint Quantum Institute, Chicago Quantum Exchange, University of Waterloo, IQC
Non-Profit/Governmental Research Institutes
leti, Fraunhofer, NQIT, MCQST, Gemini Center on Quantum Computing, ML4Q, ICFO, QuantumSilicon, PCQC, QSIT, QuTech, Centre for Quantum Computation & Communication Technology, Institute of Advanced Study, Beijing Academy of Quantum Information Sciences, CQT Singapore, School of Physical Sciences, Korea Institute of Science and Technology, Brookhaven National Laboratory, Fermilab, Los Alamos National Laboratory, IARPA, Berkeley Quantum, NYCREATES, NIST, NSF, EQUS Australia, Raman Research Institute, Perimeter Institute, NASA, Quantum Computing Institute, IDC
Source: IDC 2021 Quantum Computing Initiatives at Universities and Research Institutes Note: This is not an exhaustive listing

**Layout**

Title is centred across the top of a black slide. Below it, a large dark panel with a thin gold-grey border spans most of the width, holding two columns: a left column with a heading and an ecosystem image, and a right column with a heading and a log-scale chart. Photographs of NVIDIA DGX-style hardware sit at the right edge, partly outside the panel.

**Visuals**

Left: an embedded white-background image titled 'Major Academic and Non-Profit/Governmental Quantum Computing Research Institutions', with logos in three regional columns (Europe, Rest of World, N. America) and horizontal bands labelled Universities and Non-Profit/Governmental Research Institutes; source line reads 'Source: IDC 2021 Quantum Computing Initiatives at Universities and Research Institutes Note: This is not an exhaustive listing'. Right: a scatter/line chart titled 'Doubling Physical Qubits Every Year', y-axis 'Qubits' on a log scale from 1 to 10,000,000 (labels 1, 10, 100, 1,000, 10,000, 100,000, 1,000,000, 10,000,000), x-axis years 2010 to 2040 in 5-year steps. A white dashed diagonal line rises from about 2014 at 1 qubit to about 2040 near 10,000,000 qubits. Small coloured data points (green, blue, red, purple) cluster between about 2015 and 2020 at roughly 2 to 100 qubits. A horizontal gold bar labelled 'Fault-Tolerant Quantum Computing Speedups Threshold' sits at about 1,000,000 to 10,000,000 qubits; a vertical gold bar spans about 2 to 1,000,000 qubits at around 2035 to 2038 with a gold outlined box at its top. Right of the panel: stacked NVIDIA DGX-style server units in gold-grey with NVIDIA logos, and a tall gold DGX Station unit with NVIDIA logo, in front of black server racks.

**Design**

Background: Solid black #000000 with a dark reflective floor surface behind the panel. Black background (#000000) with a dark charcoal panel (#111111) having a thin gold-grey border (#8C7B5B). Title and headings in white (#FFFFFF) DIN Pro Bold/Medium sans-serif, all caps. Chart labels white DIN Pro Regular. Accent gold #B8964E for threshold bars and highlight. No rounded corners; no shadows visible on the panel beyond a soft dark reflection beneath.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: full-slide background fill (Measured fill covers the slide; visually black background image overlay.)
- photo at x 0, y 0, w 100, h 100 [#000000]: full-slide background image of black studio with server racks and floor reflection (Full-bleed, no crop, dark tones.)
- title at x 30.2, y 7.9, w 39.5, h 4.1 [DIN Pro, Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: GLOBAL QUANTUM COMPUTING RACE
- shape at x 3.8, y 12.1, w 92.7, h 64.8 [#111111]: dark panel with gold-grey border (Thin 1px border #8C7B5B, square corners, soft shadow beneath.)
- title at x 14.6, y 27.2, w 15.7, h 5.1 [DIN Pro, Medium, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: QUANTUM COMPUTING / RESEARCH ECOSYSTEM
- title at x 47.5, y 27.3, w 18.9, h 5 [DIN Pro, Medium, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: DOUBLING PHYSICAL QUBITS / EVERY YEAR
- photo at x 7.3, y 36.1, w 30.5, h 41.4 [#FFFFFF]: embedded white chart image: Major Academic and Non-Profit/Governmental Quantum Computing Research Institutions, logo grid with source line (Boxed, thin gold-grey border, no crop, 1238 by 946 px.)
- chart at x 42.4, y 38, w 38, h 40 [#B8964E]: log-scale qubit growth chart with scatter points, dashed trend line, and gold threshold bars (Y axis log 1 to 10,000,000 labelled Qubits; X axis 2010 to 2040; white dashed diagonal line; gold horizontal bar Fault-Tolerant Quantum Computing Speedups Threshold; gold vertical bar near 2035-2038 with outlined box.)
- photo at x 72, y 20, w 28, h 50 [#8C7B5B]: NVIDIA DGX-style server units and black server racks at right edge (Partly outside the panel, overlaps panel edge slightly.)
- body at x 49, y 39.7, w 10, h 3 [DIN Pro, Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Fault-Tolerant Quantum Computing / Speedups Threshold (Set on gold translucent bar.)
- body at x 42.4, y 38, w 4.6, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 10,000,000
- body at x 42.9, y 43.1, w 4.1, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 1,000,000
- body at x 43.7, y 48.3, w 3.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 100,000
- body at x 44.2, y 53.5, w 2.8, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 10,000
- caption at x 42.6, y 54.4, w 1, h 4.9 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Qubits (Rotated 90 degrees counter-clockwise, y-axis title.)
- body at x 44.7, y 58.7, w 2.3, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 1,000
- body at x 45.5, y 63.9, w 1.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 100
- body at x 46, y 69, w 1, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 10
- body at x 46.5, y 74.2, w 0.5, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; right aligned]: 1
- body at x 46.9, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2010
- body at x 50.3, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2015
- body at x 53.6, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2020
- body at x 56.9, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2025
- body at x 60.2, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2030
- body at x 63.6, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2035
- body at x 66.9, y 76.6, w 2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: 2040

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 7.3, y 36.1, w 30.5, h 41.4: 1238 by 946 pixels
- image at x 46.5, y 33.8, w 24.9, h 41.8: 955 by 903 pixels
- text at x 30.2, y 7.9, w 39.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: GLOBAL QUANTUM COMPUTING RACE
- text at x 14.8, y 27.2, w 15.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: QUANTUM COMPUTING
- text at x 47.5, y 27.3, w 18.9, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: DOUBLING PHYSICAL QUBITS
- text at x 14.6, y 29.8, w 15.7, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: RESEARCH ECOSYSTEM
- text at x 52.9, y 30.0, w 7.8, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: EVERY YEAR
- text at x 42.4, y 38.0, w 4.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10,000,000
- text at x 42.9, y 43.1, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1,000,000
- text at x 49.0, y 39.7, w 13.3, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Fault-Tolerant Quantum Computing
- text at x 43.7, y 48.3, w 3.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 100,000
- text at x 51.8, y 41.5, w 7.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Speedups Threshold
- text at x 44.2, y 53.5, w 2.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10,000
- text at x 42.6, y 54.4, w 1.0, h 4.9 [DINPro-Regular; font size 1.73; #FFFFFF]: Qubits
- text at x 44.7, y 58.7, w 2.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1,000
- text at x 45.5, y 63.9, w 1.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 100
- text at x 46.0, y 69.0, w 1.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 10
- text at x 46.5, y 74.2, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 1
- text at x 46.9, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2010
- text at x 50.3, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2015
- text at x 53.6, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2020
- text at x 56.9, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2025
- text at x 60.2, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2030
- text at x 63.6, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2035
- text at x 66.9, y 76.6, w 2.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 2040

### Slide 41

**Text**

ANNOUNCING NVIDIA CUQUANTUM
Research the Computer of Tomorrow on the Most Powerful Computer Today
GPU-ACCELERATED
QUANTUM SIMULATIONS
STATE VECTOR SIMULATION
Scales to 10’s of Qubits
TENSOR NETWORK SIMULATION
Scales to 1000’s of Qubits
10 Days
2 Hours
9 Years
4 Days
Dual-CPU
DGX A100
“Using the Cotengra/Quimb packages, NVIDIA's new cuQuantum SDK, and the Selene supercomputer, we’ve generated a sample of the Sycamore quantum circuit at depth=20 in record time (less than 10 minutes). This sets the benchmark for quantum circuit simulation performance and will help advance the field of quantum computing by improving our ability to verify the behavior of quantum circuits.”
—Johnnie Gray, Research Scientist, Caltech
Garnet Chan, Bren Professor of Chemistry, Caltech
cuQuantum
Footnotes: State Vector- 1,000 circuits , 36 qubits depth =10, complex 64 | CPU: Qiskit (IBM) on Dual AMD EPYC 7742 | GPU: Qgate (NVAITC) on DGX-A100
Tensor Network - 53 qubits, depth 20 | CPU: Estimated Quimb (Caltech) on Dual AMD EPYC 7742 | GPU: Quimb (Caltech) on DGX-A100

**Layout**

Centered title block at the top with the bold uppercase headline over a regular-weight subtitle, both centered on the slide. Below it, a large dark rectangular panel with a thin tan border spans roughly the left 70% of the slide, divided into three columns: GPU-accelerated diagram and cuQuantum box on the left, the two bar-chart columns in the middle and right, and the quote with attribution beneath the charts. A dark studio photograph of DGX hardware fills the right side and background, and a small footnote block sits at the bottom left; no slide number is visible.

**Visuals**

Left column: two Bloch-sphere diagrams (white thin-line circles with dashed equators and axes labelled with small glyphs, red arrow vectors, and a blue-white wavy entanglement line between the spheres, with a small equation below reading |ψ>=U|ψ>). Below it, a solid green box labelled cuQuantum with a tan connector line branching to three identical units, each showing a gray-white multi-GPU chip cluster on a gold base flanked by two gold chip modules. Middle column: horizontal bar chart titled State Vector Simulation, subtitle 'Scales to 10’s of Qubits'; the Dual-CPU blue bar is labelled 10 Days and the DGX A100 green bar is labelled 2 Hours with a thin white double-headed arrow pointing back along the bar length; no numeric axis, a thin gray vertical baseline at the left. Right column: horizontal bar chart titled Tensor Network Simulation, subtitle 'Scales to 1000’s of Qubits'; blue bar labelled 9 Years and green bar labelled 4 Days with the same white arrow, thin gray vertical baseline. Legend centered beneath the charts: blue square 'Dual-CPU' and green square 'DGX A100'. Quote mark glyphs in gold. Right side background photograph: a row of black rack servers with tan panels on the right edge, and in the foreground a stack of three tan DGX A100 units and a single tall tan DGX Station with an NVIDIA logo on its front; the scene is lit from the front-top with a soft gray floor reflection, colours are black, charcoal, and warm tan/gold.

**Design**

Background: Near-black #0A0A0A photograph-style backdrop with a dark charcoal floor and DGX hardware photograph at right. Near-black background (#0A0A0A) with a charcoal floor gradient at the bottom. Panel fill near-black #111111 with a thin tan/gold border #AD8C4A. Titles white (#FFFFFF) bold uppercase DIN Pro sans-serif; subtitles and body in white DIN Pro regular; attribution in gray #8C8C8C; footnotes in gray #9A9A9A. Accents: NVIDIA green #76B900 for the cuQuantum box and DGX A100 bars, blue #0071C5 for Dual-CPU bars, gold #AD8C4A for quote marks. Title about 4.1% of slide height, subtitle about 2.7%, column headings about 2.5%, body quote about 2.2%, labels about 2.0%, footnotes about 1.1%. Bars are flat with no rounded corners or shadows; the panel has square corners.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#0A0A0A]: Background studio photograph of black rack servers on the right and dark floor, full bleed behind everything (Full-bleed, no crop, no overlay; a white full-slide fill sits behind it)
- photo at x 69, y 19, w 28, h 72 [#AD8C4A]: Photograph of stacked tan DGX A100 units and tall DGX Station with NVIDIA logo, and rack servers (Part of the full-bleed photograph, positioned at right overlapping the panel edge at its left border)
- shape at x 3.8, y 21.6, w 68.9, h 61.6 [#111111]: Dark rectangular panel with thin tan border (Square corners, 0.2% stroke in #AD8C4A, no shadow, opacity about 95%)
- title at x 31.6, y 7.9, w 36.7, h 4.1 [DIN Pro, bold, sans-serif, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA CUQUANTUM
- subtitle at x 24.2, y 12.5, w 51.6, h 2.7 [DIN Pro, regular, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: Research the Computer of Tomorrow on the Most Powerful Computer Today
- body at x 7, y 27.3, w 15.7, h 5.2 [DIN Pro, medium, sans-serif, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: GPU-ACCELERATED / QUANTUM SIMULATIONS (Two lines, centered over left column)
- diagram at x 8.5, y 34.7, w 18.4, h 18.5 [#FFFFFF]: Two Bloch-sphere diagrams joined by a blue-white wavy entanglement line, red state vectors, and equation |ψ>=U|ψ> (White thin outlines, dashed equators, red arrows, blue wave with about 60% opacity)
- body at x 28, y 27.3, w 17.6, h 5.2 [DIN Pro, medium, sans-serif, all caps for heading; regular for subtitle; font size 2.47% of slide height; #FFFFFF; center aligned]: STATE VECTOR SIMULATION / Scales to 10’s of Qubits (Heading and subtitle centered over middle chart)
- body at x 50, y 27.3, w 20.4, h 5.2 [DIN Pro, medium, sans-serif, all caps for heading; regular for subtitle; font size 2.47% of slide height; #FFFFFF; center aligned]: TENSOR NETWORK SIMULATION / Scales to 1000’s of Qubits (Heading and subtitle centered over right chart)
- chart at x 27.7, y 38.2, w 14.5, h 3.1 [#0071C5]: Bar chart, State Vector Simulation: Dual-CPU 10 Days (blue), DGX A100 2 Hours (green) (Blue bar at top, green bar below with white double-headed arrow, gray vertical baseline, no numeric axis)
- chart at x 50.8, y 38.1, w 15.1, h 3.1 [#0071C5]: Bar chart, Tensor Network Simulation: Dual-CPU 9 Years (blue), DGX A100 4 Days (green) (Blue bar at top, green bar below with white double-headed arrow, gray vertical baseline, no numeric axis)
- body at x 42.7, y 38.9, w 3.8, h 2 [DIN Pro, regular, sans-serif; font size 1.98% of slide height; #FFFFFF; left aligned]: 10 Days
- body at x 66.6, y 38.9, w 3.5, h 2 [DIN Pro, regular, sans-serif; font size 1.98% of slide height; #FFFFFF; left aligned]: 9 Years
- body at x 28.6, y 43.9, w 3.9, h 2 [DIN Pro, regular, sans-serif; font size 1.98% of slide height; #FFFFFF; left aligned]: 2 Hours
- body at x 51.7, y 44, w 3.2, h 2 [DIN Pro, regular, sans-serif; font size 1.98% of slide height; #FFFFFF; left aligned]: 4 Days
- shape at x 43.3, y 51.8, w 0.8, h 1 [#0071C5]: Blue legend square for Dual-CPU (Square swatch)
- body at x 43.5, y 51.4, w 3.7, h 1.5 [DIN Pro, regular, sans-serif; font size 1.48% of slide height; #FFFFFF; left aligned]: Dual-CPU (Legend label)
- shape at x 48.5, y 51.8, w 0.8, h 1 [#76B900]: Green legend square for DGX A100 (Square swatch)
- body at x 49.3, y 51.4, w 3.6, h 1.5 [DIN Pro, regular, sans-serif; font size 1.48% of slide height; #FFFFFF; left aligned]: DGX A100 (Legend label)
- shape at x 11.8, y 56, w 12, h 10.9 [DIN Pro, regular, sans-serif; font size 1.98% of slide height; #76B900; center aligned]: Green rounded-free rectangle labelled cuQuantum (Square corners, white label text cuQuantum centered)
- body at x 11.8, y 59.1, w 5.9, h 2 [DIN Pro, regular, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: cuQuantum (Label on green box)
- illustration at x 6.4, y 70.9, w 18.6, h 7.4 [#AD8C4A]: Three GPU module illustrations connected to cuQuantum by a tan tree of lines (Tan connector lines about 1 px, horizontal bar with three drops, each unit gold-based with gray chip cluster and two gold side modules)
- line at x 14.5, y 63.6, w 0.3, h 6.5 [#AD8C4A]: Tan connector from cuQuantum box down to three GPU units (Thin vertical line with horizontal branch line across the three drops)
- shape at x 27.9, y 57, w 0.8, h 3.3 [DIN Pro, regular, sans-serif; font size 3.33% of slide height; #AD8C4A; left aligned]: Quote mark (open)
- body at x 28.8, y 57.1, w 38.2, h 13 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: Using the Cotengra/Quimb packages, NVIDIA's new cuQuantum / SDK, and the Selene supercomputer, we’ve generated a sample of / the Sycamore quantum circuit at depth=20 in record time (less than / 10 minutes). This sets the benchmark for quantum circuit simulation / performance and will help advance the field of quantum computing / by improving our ability to verify the behavior of quantum circuits. (Line spacing about 2.7% of slide height)
- shape at x 64.9, y 67.8, w 0.8, h 3.3 [DIN Pro, regular, sans-serif; font size 3.33% of slide height; #AD8C4A; left aligned]: Quote mark (close)
- caption at x 48.5, y 74, w 43.9, h 3.3 [DIN Pro, regular, sans-serif; font size 1.48% of slide height; #8C8C8C; right aligned]: —Johnnie Gray, Research Scientist, Caltech / Garnet Chan, Bren Professor of Chemistry, Caltech (Two lines right-aligned)
- footer at x 3.9, y 93.2, w 42.3, h 2.3 [DIN Pro, regular, sans-serif; font size 1.11% of slide height; #9A9A9A; left aligned]: Footnotes: State Vector- 1,000 circuits , 36 qubits depth =10, complex 64 | CPU: Qiskit (IBM) on Dual AMD EPYC 7742 | GPU: Qgate (NVAITC) on DGX-A100 / Tensor Network - 53 qubits, depth 20 | CPU: Estimated Quimb (Caltech) on Dual AMD EPYC 7742 | GPU: Quimb (Caltech) on DGX-A100 (Two lines, left-aligned at bottom left)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 27.7, y 38.2, w 14.5, h 3.1: #0071C5
- fill at x 50.8, y 38.1, w 15.1, h 3.1: #0071C5
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 5.8, y 34.7, w 18.4, h 18.5: 895 by 504 pixels
- image at x 8.9, y 56.2, w 11.9, h 7.6: 1426 by 515 pixels
- image at x 12.4, y 70.9, w 4.6, h 7.4: 279 by 251 pixels
- image at x 6.4, y 70.9, w 4.6, h 7.4: 279 by 251 pixels
- image at x 18.3, y 70.9, w 4.6, h 7.4: 140 by 126 pixels
- text at x 31.6, y 7.9, w 36.7, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA CUQUANTUM
- text at x 24.2, y 12.5, w 51.6, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Research the Computer of Tomorrow on the Most Powerful Computer Today
- text at x 8.5, y 27.3, w 12.9, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: GPU-ACCELERATED
- text at x 28.0, y 27.3, w 17.6, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: STATE VECTOR SIMULATION
- text at x 50.0, y 27.3, w 20.4, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: TENSOR NETWORK SIMULATION
- text at x 7.0, y 30.0, w 15.7, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: QUANTUM SIMULATIONS
- text at x 31.2, y 30.2, w 11.6, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Scales to 10’s of Qubits
- text at x 53.9, y 30.2, w 12.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Scales to 1000’s of Qubits
- text at x 27.9, y 57.0, w 0.8, h 3.3 [DINPro-Regular; font size 3.33; #AD8C4A]: “
- text at x 42.7, y 38.9, w 3.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 10 Days
- text at x 66.6, y 38.9, w 3.5, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 9 Years
- text at x 64.9, y 67.8, w 0.8, h 3.3 [DINPro-Regular; font size 3.33; #AD8C4A]: “
- text at x 28.6, y 43.9, w 3.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 2 Hours
- text at x 51.7, y 44.0, w 3.2, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 4 Days
- text at x 28.8, y 57.1, w 35.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Using the Cotengra/Quimb packages, NVIDIA's new cuQuantum
- text at x 28.8, y 59.7, w 36.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: SDK, and the Selene supercomputer, we’ve generated a sample of
- text at x 28.8, y 62.4, w 37.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: the Sycamore quantum circuit at depth=20 in record time (less than
- text at x 28.8, y 65.1, w 38.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 10 minutes). This sets the benchmark for quantum circuit simulation
- text at x 11.8, y 59.1, w 5.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: cuQuantum
- text at x 11.8, y 59.1, w 5.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: cuQuantum
- text at x 28.8, y 67.7, w 37.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: performance and will help advance the field of quantum computing
- text at x 28.8, y 70.4, w 36.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: by improving our ability to verify the behavior of quantum circuits.
- text at x 43.5, y 51.4, w 3.7, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Dual-CPU
- text at x 49.3, y 51.4, w 3.6, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: DGX A100
- text at x 51.1, y 74.0, w 16.1, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: —Johnnie Gray, Research Scientist, Caltech
- text at x 48.5, y 75.8, w 23.3, h 1.5 [DINPro-Regular; font size 1.48; #8C8C8C]: Garnet Chan, Bren Professor of Chemistry, Caltech
- text at x 3.9, y 93.2, w 42.3, h 2.3 [DINPro-Regular; font size 1.11; #9A9A9A]: Footnotes: State Vector- 1,000 circuits , 36 qubits depth =10, complex 64 | CPU: Qiskit(IBM) on Dual AMD EPYC 7742 | GPU: Qgate (NVAITC) on DGX-A100 Tensor Network -53 qubits, depth 20 | CPU: Estimated Quimb(Caltech) on Dual AMD EPYC 7742 | GPU: Quimb(Caltech) on DGX-A100

### Slide 42

**Text**

DIVERSE DATA CENTER ARCHITECTURES
ENTERPRISE COMPUTING
HYPERSCALE
SCIENTIFIC COMPUTING
STORAGE SERVERS
ACCELERATED  HPC
ACCELERATED HYPERSCALE

**Layout**

Three loose columns of icon-and-label pairs sit below a centred title, with the left column holding one item and the middle and right columns holding three items each in stepped rows. Labels sit to the right of their icons, top-aligned with the icon top, and the lower half of the slide is empty floor. There is no footer, slide number or logo.

**Visuals**

Line-art icons in thin gold outline, each a square or grid of small squares or dot matrices. Enterprise Computing: one boxed 2x2 grid of squares. Hyperscale: one boxed 3x3 grid of small squares. Storage Servers: one boxed 3x3 grid of small squares. Accelerated Hyperscale: one boxed 3x3 square grid above one boxed dot-matrix square. Scientific Computing: one large boxed 4x4 grid of squares. Accelerated HPC: one large boxed 4x4 grid of squares above a 2x2 set of boxed dot-matrix squares. Below the Accelerated Hyperscale and Accelerated HPC icons, faint gold reflections of the icons appear on the glossy floor. The background is a photograph of a dark, reflective studio floor with a black upper area fading to dark grey lower down, lit from above so the floor shows a soft gradient and faint scratches. Full-bleed, no crop, no overlay.

**Design**

Background: Full-bleed photograph of a dark reflective floor, black at top fading to charcoal grey #2A2A2A at the bottom. Black upper background fading to dark charcoal grey floor. Title in white bold DIN-style sans-serif, all caps, centred, about 4.07% of slide height. Labels in gold #B3914C medium-weight DIN-style sans-serif, all caps, about 1.98% of slide height. Icons drawn in thin gold #B3914C outline strokes of about 1 px with square corners and no fills. No shapes, rules or shadows beyond the reflections.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed background photograph of a dark reflective studio floor with soft top-down lighting and faint scratches; black upper area blending into grey floor. (Covers the whole slide, no crop, no overlay, no border.)
- title at x 28.5, y 7.9, w 42.9, h 4.1 [DIN Pro Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: DIVERSE DATA CENTER ARCHITECTURES
- icon at x 9.9, y 24, w 3.5, h 6.2 [#B3914C]: Enterprise Computing icon: boxed 2x2 grid of outline squares (Thin gold outline, square corners, no fill.)
- label at x 15.8, y 24.2, w 13.1, h 2 [DIN Pro Medium, all caps; font size 1.98% of slide height; #B3914C; left aligned]: ENTERPRISE COMPUTING
- icon at x 35.9, y 24.1, w 3.5, h 6.1 [#B3914C]: Hyperscale icon: boxed 3x3 grid of outline squares (Thin gold outline, square corners, no fill.)
- label at x 41.7, y 24.2, w 6.8, h 2 [DIN Pro Medium, all caps; font size 1.98% of slide height; #B3914C; left aligned]: HYPERSCALE
- icon at x 63.3, y 24.1, w 7.5, h 13.3 [#B3914C]: Scientific Computing icon: large boxed 4x4 grid of outline squares (Thin gold outline, square corners, no fill.)
- label at x 73.2, y 24.2, w 12.3, h 2 [DIN Pro Medium, all caps; font size 1.98% of slide height; #B3914C; left aligned]: SCIENTIFIC COMPUTING
- icon at x 35.9, y 41.5, w 3.5, h 6.2 [#B3914C]: Storage Servers icon: boxed 3x3 grid of outline squares (Thin gold outline, square corners, no fill.)
- label at x 41.7, y 41.8, w 9.8, h 2 [DIN Pro Medium, all caps; font size 1.98% of slide height; #B3914C; left aligned]: STORAGE SERVERS
- icon at x 63.3, y 45, w 7.5, h 13.3 [#B3914C]: Accelerated HPC icon: large boxed 4x4 grid of outline squares (Thin gold outline, square corners, no fill.)
- label at x 73.2, y 45, w 10.1, h 2 [DIN Pro Medium, all caps; font size 1.98% of slide height; #B3914C; left aligned]: ACCELERATED HPC
- icon at x 63.3, y 59.4, w 7.5, h 12.4 [#B3914C]: Accelerated HPC lower icons: four boxed dot-matrix squares in a 2x2 set (Two columns of two boxed dot-matrix squares, thin gold outline, no fill.)
- icon at x 35.9, y 59.3, w 3.5, h 6.2 [#B3914C]: Accelerated Hyperscale icon: boxed 3x3 grid of outline squares (Thin gold outline, square corners, no fill.)
- label at x 41.7, y 59.3, w 14.5, h 2 [DIN Pro Medium, all caps; font size 1.98% of slide height; #B3914C; left aligned]: ACCELERATED HYPERSCALE
- icon at x 35.9, y 66.6, w 3.5, h 6.1 [#B3914C]: Accelerated Hyperscale dot-matrix icon: boxed dot-matrix square (Thin gold outline, square corners, dense dot grid inside, no fill.)
- shape at x 35.7, y 77.2, w 3.7, h 11.7 [#8A6A3A]: Faint reflection of the Accelerated Hyperscale icons on the floor (Blurred, low-opacity gold reflection of the two icons above, fading downward.)
- shape at x 63.1, y 77, w 7.9, h 11.9 [#8A6A3A]: Faint reflection of the Accelerated HPC icons on the floor (Blurred, low-opacity gold reflection of the lower icons, fading downward.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 28.5, y 7.9, w 42.9, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DIVERSE DATA CENTER ARCHITECTURES
- text at x 15.8, y 24.2, w 13.1, h 2.0 [DINPro-Medium; font size 1.98; #B3914C]: ENTERPRISE COMPUTING
- text at x 41.7, y 24.2, w 6.8, h 2.0 [DINPro-Medium; font size 1.98; #B3914C]: HYPERSCALE
- text at x 73.2, y 24.2, w 12.3, h 2.0 [DINPro-Medium; font size 1.98; #B3914C]: SCIENTIFIC COMPUTING
- text at x 41.7, y 41.8, w 9.8, h 2.0 [DINPro-Medium; font size 1.98; #B3914C]: STORAGE SERVERS
- text at x 73.2, y 45.0, w 10.1, h 2.0 [DINPro-Medium; font size 1.98; #B3914C]: ACCELERATED HPC
- text at x 41.7, y 59.3, w 14.5, h 2.0 [DINPro-Medium; font size 1.98; #B3914C]: ACCELERATED HYPERSCALE

### Slide 43

**Text**

DDR4 / HBM2e / DATA-COMPUTE DEMAND / GROWING FASTER THAN / SYSTEM BANDWIDTH / GPU Starved by CPU Memory and PCIE Bandwidth / GPU 8,000 GB/sec / CPU 200 GB/sec / PCIE Gen 4 16 GB/sec / Mem-to-GPU 64 GB/sec / x86 / GPU / GPU / GPU / GPU

**Layout**

Two-zone composition on a full-bleed dark rendering. The title block and a four-row data table sit in a left column starting at about 6.7% from the left edge, vertically centred around the middle of the slide. A diagram of memory, CPU and four GPUs fills the right half, from about 52% to 83% of the width. No footer, slide number or logo is visible. Text is left-aligned.

**Visuals**

Full-bleed 3D-style rendered image (3840 by 2160 px) of a computing system on a black-to-charcoal studio floor with a faint reflection along the bottom edge. Diagram from left to right: (1) a stack of five vertical grey DDR4 memory modules drawn as serpentine bars, labelled DDR4 above; the rightmost module connects by a short tan link at its bottom to (2) a blue square block labelled x86. (3) Four tan-gold thin connector lines run from the x86 block to four green GPU blocks: the top line runs up from the x86 block and then right to GPU 1, a middle line runs right to GPU 2 and GPU 3, and the bottom line runs down and right to GPU 4. (4) Four green GPU blocks stacked vertically, each labelled GPU in white, joined to each other by short tan link pieces; each GPU has a tan-beige HBM stack with a silver cap on its right side, labelled HBM2e above the column. Lighting is a soft top-front light with specular highlights on the metal modules; dominant colours are black, grey metal, green and blue. Not cropped; full-bleed.

**Design**

Background is near-black #000000 at the top, fading to dark charcoal #2A2A2A on the floor area with a subtle reflective surface at the bottom. Title text is white #FFFFFF in DIN Pro Bold, uppercase, sans-serif, approximately 4.07% of slide height per line with tight leading. Body and table text is white #FFFFFF in DIN Pro Regular, about 2.22% of slide height. The red row Mem-to-GPU is #FF0000. Diagram labels are white DIN Pro Medium, about 2.10%. Accent colours: GPU green #5E9E1F, x86 blue #3D7CC9, HBM tan #D9C9A0, silver #C0C0C0, DDR4 grey gradient #8A8A8A to #4A4A4A. Connector lines are thin tan #C8B48A.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed rendered background image of black studio floor with faint reflection (3840 by 2160 px image, no crop, no overlay, dominant colour black #000000 to charcoal #2A2A2A)
- illustration at x 51.9, y 19.7, w 13.2, h 58.3 [#8A8A8A]: DDR4 memory stack: five vertical serpentine grey modules with a tan link at bottom right to x86 block (grey metallic gradient #8A8A8A to #4A4A4A, rounded corners none, no shadow visible)
- line at x 70.3, y 25.9, w 5, h 37 [#C8B48A]: Connector lines from x86 block to GPU 1, GPU 2, GPU 3 and GPU 4 (thin tan lines about 0.2% of width stroke, right-angle routing, no arrowheads)
- shape at x 66.75, y 42.7, w 7, h 12.4 [#3D7CC9]: x86 processor block with label x86 centred (square block, slight bevel, label white DIN Pro Medium)
- shape at x 75.35, y 19.7, w 6.7, h 12.4 [#5E9E1F]: GPU block 1 with label GPU (square green block, label white DIN Pro Medium centred)
- shape at x 75.35, y 35, w 6.7, h 12.4 [#5E9E1F]: GPU block 2 with label GPU (square green block, label white DIN Pro Medium centred)
- shape at x 75.35, y 50.3, w 6.7, h 12.4 [#5E9E1F]: GPU block 3 with label GPU (square green block, label white DIN Pro Medium centred)
- shape at x 75.35, y 65.6, w 6.7, h 12.4 [#5E9E1F]: GPU block 4 with label GPU (square green block, label white DIN Pro Medium centred)
- shape at x 82.05, y 19.7, w 2.5, h 58.3 [#D9C9A0]: HBM2e stacks, four tan blocks with silver caps, one beside each GPU (tan-beige rectangles with silver #C0C0C0 right caps, butted against each GPU block)
- shape at x 77.9, y 32.2, w 1.5, h 2.8 [#B8A57E]: Short tan link pieces between consecutive GPU blocks (small rectangles between GPU blocks, 3 instances)
- caption at x 56.9, y 15.4, w 3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; left aligned]: DDR4 (label above DDR4 stack)
- caption at x 82.3, y 15.4, w 3.8, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; left aligned]: HBM2e (label above HBM column)
- title at x 6.7, y 31.8, w 27.6, h 12.9 [DIN Pro Bold, uppercase, sans-serif, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; left aligned]: DATA-COMPUTE DEMAND / GROWING FASTER THAN / SYSTEM BANDWIDTH (three lines, line pitch about 4.4% of slide height)
- subtitle at x 6.7, y 47.2, w 27.7, h 2.2 [DIN Pro Regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU Starved by CPU Memory and PCIE Bandwidth (single line)
- body at x 6.7, y 51.9, w 21, h 2.2 [DIN Pro Regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU / 8,000 / GB/sec (table row 1: label at x 6.7, value at x 17.3, unit at x 24.2)
- body at x 6.7, y 56.7, w 21, h 2.2 [DIN Pro Regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: CPU / 200 / GB/sec (table row 2: label at x 6.7, value at x 17.3, unit at x 24.2)
- body at x 6.7, y 61.4, w 21, h 2.2 [DIN Pro Regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: PCIE Gen 4 / 16 / GB/sec (table row 3: label at x 6.7, value at x 17.3, unit at x 24.2)
- body at x 6.7, y 66.2, w 21, h 2.2 [DIN Pro Regular, sans-serif; font size 2.22% of slide height; #FF0000; left aligned]: Mem-to-GPU / 64 / GB/sec (table row 4 in red #FF0000; the measured file lists overlapping duplicate fragments of this row, drawn as one line)
- caption at x 77.5, y 25.2, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (label on GPU block 1)
- caption at x 77.5, y 40.3, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (label on GPU block 2)
- caption at x 77.5, y 55.5, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (label on GPU block 3)
- caption at x 77.5, y 70.7, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (label on GPU block 4)
- caption at x 69.2, y 47.9, w 1.8, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: x86 (label on x86 block)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 56.9, y 15.4, w 3.0, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: DDR4
- text at x 82.3, y 15.4, w 3.8, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: HBM2e
- text at x 6.7, y 31.8, w 27.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA-COMPUTE DEMAND
- text at x 6.7, y 36.2, w 26.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: GROWING FASTER THAN
- text at x 6.7, y 40.6, w 22.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: SYSTEM BANDWIDTH
- text at x 77.5, y 25.2, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 77.5, y 40.3, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 6.7, y 47.2, w 27.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU Starved by CPU Memory and PCIE Bandwidth
- text at x 69.2, y 47.9, w 1.8, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: x86
- text at x 6.7, y 51.9, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU
- text at x 17.3, y 51.9, w 3.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 8,000
- text at x 24.2, y 51.9, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 6.7, y 56.7, w 2.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: CPU
- text at x 17.3, y 56.7, w 2.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 200
- text at x 24.2, y 56.7, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 77.5, y 55.5, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 6.7, y 61.4, w 6.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: PCIE Gen 4
- text at x 17.3, y 61.4, w 1.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 16
- text at x 24.2, y 61.4, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 6.7, y 66.2, w 2.8, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: Mem
- text at x 6.7, y 66.2, w 4.6, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: Mem--to
- text at x 10.1, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: to--GPU
- text at x 11.9, y 66.2, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: GPU
- text at x 17.4, y 66.2, w 1.3, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: 64
- text at x 17.4, y 66.2, w 1.3, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: 64
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: GB/sec
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: GB/sec
- text at x 77.5, y 70.7, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU

### Slide 44

**Text**

DDR4 / HBM2e / DATA-COMPUTE DEMAND / GROWING FASTER THAN / SYSTEM BANDWIDTH / GPU Starved by CPU Memory and PCIE Bandwidth / GPU / 8,000 / GB/sec / CPU / 200 / GB/sec / PCIE Gen 4 / 16 / GB/sec / Mem-to-GPU / 64 / GB/sec / GPU / x86 / GPU / GPU / GPU

**Layout**

Two-zone composition on a full-bleed dark photograph: a left text column starts at 6.7% from the left edge and holds the title, subtitle and a four-row data table, with the title block's top at about 31.8% of the height and the table ending near 68%. The right zone holds a horizontal diagram from about 56% to 82% of the width, centred vertically between 15% and 82% of the height. The title is not placed at the top; it sits at mid-left. No footer, slide number or logo is visible.

**Visuals**

Diagram of a memory-to-GPU data path, with no chart axes. Left: five tall grey DDR4 memory modules drawn as vertical serpentine bars (about 1038 to 1302 px wide at full scale), labelled DDR4 above. Centre: a flat blue rectangle labelled x86 (about #4A7FC1), with four short gold/tan pin stubs on its left side connecting to the right edge of the DDR4 group. Right of x86: four green square blocks (#76B900 style green) each labelled GPU, stacked vertically at equal spacing. Each GPU has a gold/tan connector on its left and a white-grey HBM stack on its right, labelled HBM2e above the top stack. Connections: x86 right side sends a bronze elbow trace up to the top GPU (via a path going up from x86 top edge then right), a short horizontal stub to the second GPU, a short stub to the third GPU, and a bronze elbow trace down from x86 bottom edge to the bottom GPU. Short vertical bronze links join the GPU blocks to each other. The scene is lit from above with a soft reflection on a dark floor at the bottom. No photographs of people. Composition is a frontal, centred view of the diagram on a black-to-charcoal floor.

**Design**

Background: Black #000000 to dark charcoal #2B2B2B gradient with a brushed metal floor texture, full-bleed photograph. Black background fading to dark charcoal grey at the bottom, with a metallic brushed floor texture. Title text is white #FFFFFF in DIN Pro Bold, a sans-serif, all caps, about 4.07% of slide height, tight leading. Subtitle and table body are white #FFFFFF in DIN Pro Regular, about 2.22% of slide height. Labels are DIN Pro Medium white #FFFFFF at about 2.10%. The Mem-to-GPU row is red #FF0000 as an accent. GPU blocks are green #76B900 with white labels, x86 block is blue #4A7FC1, connectors are bronze/gold #C9A96E, HBM stacks are light grey #D9D9D9 with bronze bases. DDR4 modules are grey gradient #8A8A8A to #3A3A3A. Shapes have square corners and no visible shadows apart from the soft floor reflection.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed background photograph: black studio backdrop fading into dark brushed-metal floor with soft reflection at bottom (Covers the whole slide, behind all other elements; not cropped; no overlay.)
- label at x 56.9, y 15.4, w 3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; left aligned]: DDR4 (Label above the DDR4 memory group.)
- label at x 82.3, y 15.4, w 3.8, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; left aligned]: HBM2e (Label above the HBM stack column.)
- illustration at x 51.9, y 22.2, w 16.1, h 56 [#8A8A8A]: Five grey DDR4 memory modules drawn as tall vertical serpentine bars (Vertical bars with a serpentine inner outline, gradient grey #8A8A8A to #3A3A3A, square corners.)
- shape at x 65, y 40, w 2, h 24 [#C9A96E]: Four gold connector pins linking DDR4 to x86 (Four short bronze pin stubs on the right edge of DDR4 group, one per row.)
- shape at x 66.8, y 43.6, w 7, h 18.9 [#4A7FC1]: x86 processor block, blue rectangle with label x86 (Square corners, no shadow; the bronze traces from its top and bottom edges and right side connect to GPUs.)
- label at x 69.2, y 47.9, w 1.8, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: x86 (Centred inside the blue x86 block.)
- shape at x 69.4, y 21, w 12, h 58 [#C9A96E]: Bronze elbow traces from x86 to the top and bottom GPUs and short stubs to the middle GPUs (Trace from top of x86 up and right into top GPU; stub into second GPU; stub into third GPU; trace from bottom of x86 down and right into bottom GPU.)
- shape at x 75.3, y 19.9, w 7.9, h 16.8 [#76B900]: Green GPU block (top) (Square corners, no shadow; short bronze link down to second GPU.)
- shape at x 75.3, y 35.5, w 7.9, h 16.8 [#76B900]: Green GPU block (second) (Square corners; short bronze links above and below.)
- shape at x 75.3, y 51.1, w 7.9, h 16.8 [#76B900]: Green GPU block (third) (Square corners; short bronze links above and below.)
- shape at x 75.3, y 66.2, w 7.9, h 16.8 [#76B900]: Green GPU block (bottom) (Square corners; bronze trace enters from left.)
- shape at x 82, y 19.9, w 2, h 63.1 [#D9D9D9]: HBM2e stacks, four light grey memory blocks with bronze bases on the right of each GPU (Four grey-white vertical bars with bronze bases, one per GPU, at the right edge.)
- label at x 77.5, y 25.2, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (Centred on top GPU block.)
- label at x 77.5, y 40.3, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (Centred on second GPU block.)
- label at x 77.5, y 55.5, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (Centred on third GPU block.)
- label at x 77.5, y 70.7, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU (Centred on bottom GPU block.)
- title at x 6.7, y 31.8, w 27.6, h 12.9 [DIN Pro Bold, all caps; font size 4.07% of slide height; #FFFFFF; left aligned]: DATA-COMPUTE DEMAND / GROWING FASTER THAN / SYSTEM BANDWIDTH (Three lines, tight leading, left-aligned at 6.7% margin.)
- subtitle at x 6.7, y 47.2, w 27.7, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU Starved by CPU Memory and PCIE Bandwidth
- body at x 6.7, y 51.9, w 2.5, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU (Table row 1, column 1.)
- body at x 17.3, y 51.9, w 3.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 8,000 (Table row 1, column 2.)
- body at x 24.2, y 51.9, w 4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GB/sec (Table row 1, column 3.)
- body at x 6.7, y 56.7, w 2.4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: CPU (Table row 2, column 1.)
- body at x 17.3, y 56.7, w 2.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 200 (Table row 2, column 2.)
- body at x 24.2, y 56.7, w 4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GB/sec (Table row 2, column 3.)
- body at x 6.7, y 61.4, w 6.1, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: PCIE Gen 4 (Table row 3, column 1.)
- body at x 17.3, y 61.4, w 1.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 16 (Table row 3, column 2.)
- body at x 24.2, y 61.4, w 4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GB/sec (Table row 3, column 3.)
- body at x 6.7, y 66.2, w 9, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FF0000; left aligned]: Mem-to-GPU (Table row 4, column 1, red accent row.)
- body at x 17.4, y 66.2, w 1.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FF0000; left aligned]: 64 (Table row 4, column 2, red.)
- body at x 24.2, y 66.2, w 4.2, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FF0000; left aligned]: GB/sec (Table row 4, column 3, red.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 56.9, y 15.4, w 3.0, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: DDR4
- text at x 82.3, y 15.4, w 3.8, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: HBM2e
- text at x 6.7, y 31.8, w 27.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: DATA-COMPUTE DEMAND
- text at x 6.7, y 36.2, w 26.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: GROWING FASTER THAN
- text at x 6.7, y 40.6, w 22.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: SYSTEM BANDWIDTH
- text at x 77.5, y 25.2, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 77.5, y 40.3, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 6.7, y 47.2, w 27.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU Starved by CPU Memory and PCIE Bandwidth
- text at x 69.2, y 47.9, w 1.8, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: x86
- text at x 6.7, y 51.9, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU
- text at x 17.3, y 51.9, w 3.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 8,000
- text at x 24.2, y 51.9, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 6.7, y 56.7, w 2.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: CPU
- text at x 17.3, y 56.7, w 2.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 200
- text at x 24.2, y 56.7, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 77.5, y 55.5, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 6.7, y 61.4, w 6.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: PCIE Gen 4
- text at x 17.3, y 61.4, w 1.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 16
- text at x 24.2, y 61.4, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 6.7, y 66.2, w 2.8, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: Mem
- text at x 6.7, y 66.2, w 4.6, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: Mem--to
- text at x 10.1, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: to--GPU
- text at x 11.9, y 66.2, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: GPU
- text at x 17.4, y 66.2, w 1.3, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: 64
- text at x 17.4, y 66.2, w 1.3, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: 64
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: GB/sec
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #FF0000]: GB/sec
- text at x 77.5, y 70.7, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU

### Slide 45

**Text**

LPDDR5x
HBM2e
A NEW COMPUTING
ARCHITECTURE FOR
AI AND DATA SCIENCE
GRACE
GPU
GRACE
GPU
30X Increase System Memory to GPU
GPU 8,000 GB/sec
CPU 500 GB/sec
NVLINK 500 GB/sec
Mem-to-GPU 2,000 GB/sec 30X
GRACE
GPU

**Layout**

Left-aligned text block sits in the lower-left half at mid-slide height, with the title at the top of the block and a four-row data table beneath it. A four-row diagram of memory, CPU, and GPU blocks occupies the right half, with column labels LPDDR5x and HBM2e above it. No visible footer, slide number, or logo; margins are roughly 6.7% from the left edge.

**Visuals**

Diagram of four horizontal rows, each row a chain from left to right: a large grey rectangle (LPDDR5x memory block, slightly gradient grey, about #8A8A8A to #4A4A4A) connected by a short tan/gold connector to a bright green square labelled GRACE, then a short tan connector to a bright green square labelled GPU, then a tan connector to a tall tan/silver HBM2e stack at the right edge. Vertically, GRACE and GPU squares in adjacent rows are linked by short tan vertical connectors. The green squares are about #76B900 with a darker green edge; the connectors are tan about #C8B48A; the HBM2e stacks are light grey/silver with white highlights. Column labels LPDDR5x (above the first column) and HBM2e (above the last column) are white. Below the diagram the glossy black floor reflects the blocks faintly. No chart, table, or photograph; the four-row text block at left functions as a data table with columns Metric, value, unit, and ratio. Table rows: GPU 8,000 GB/sec; CPU 500 GB/sec; NVLINK 500 GB/sec; Mem-to-GPU 2,000 GB/sec 30X (highlighted in green).

**Design**

Background: Black (#000000) background with a dark charcoal (#2B2B2B) reflective floor gradient at the bottom of the slide. Full black background with a dark charcoal gradient floor and a faint reflection at the bottom. Title is bold white DIN Pro-style sans-serif in all caps at roughly 4.1% of slide height, body and table text regular white DIN Pro sans-serif about 2.2% of slide height, with the Mem-to-GPU row and 30X highlight in NVIDIA green #76B900. Diagram blocks are green #76B900, grey memory blocks, and tan #C8B48A connectors. No shadows on text; the blocks have square corners and thin light edges; a soft dark shadow sits under the diagram.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Full-slide black background fill (Covers the entire slide; fill from the file reads white but the visible background is black.)
- photo at x 0, y 0, w 100, h 100 [#1A1A1A]: Dark studio background with reflective floor and gradient, full-bleed (Full-bleed 3840x2160 background image covering the slide; soft gradient to lighter grey near the floor and faint reflections of the diagram at the bottom.)
- text at x 56.3, y 15.4, w 5, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; left aligned]: LPDDR5x
- text at x 82.3, y 15.4, w 3.8, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; left aligned]: HBM2e
- shape at x 51.9, y 11.1, w 13.6, h 68.9 [#8A8A8A]: Four grey LPDDR5x memory blocks in a column (Four rectangles, each about 13.6% wide and 16% tall, with a grey gradient from lighter top to darker bottom, thin light edges, square corners.)
- diagram at x 66, y 19.8, w 18, h 60 [#76B900]: Connectors and GRACE and GPU green squares with tan links and HBM2e stacks (Four rows; green squares #76B900 with darker edge, tan connectors #C8B48A linking memory to GRACE to GPU to HBM2e silver stacks, and vertical tan connectors between rows.)
- text at x 6.7, y 31.8, w 23.4, h 12.9 [DIN Pro Bold, all caps; font size 4.07% of slide height; #FFFFFF; left aligned]: A NEW COMPUTING / ARCHITECTURE FOR / AI AND DATA SCIENCE (Line spacing about 4.4% of slide height.)
- text at x 68.4, y 25.2, w 3.7, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GRACE
- text at x 77.5, y 25.2, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU
- text at x 68.4, y 40.3, w 3.7, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GRACE
- text at x 77.5, y 40.3, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU
- text at x 6.7, y 47.2, w 20.5, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 30X Increase System Memory to GPU
- text at x 6.7, y 51.9, w 2.5, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU
- text at x 17.3, y 51.9, w 3.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 8,000
- text at x 24.2, y 51.9, w 4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GB/sec
- text at x 6.7, y 56.7, w 2.4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: CPU
- text at x 17.3, y 56.7, w 2.3, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 500
- text at x 24.2, y 56.7, w 4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GB/sec
- text at x 68.4, y 55.5, w 3.7, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GRACE
- text at x 77.5, y 55.5, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU
- text at x 6.7, y 61.4, w 4.4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: NVLINK
- text at x 17.3, y 61.4, w 2, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 500
- text at x 24.2, y 61.4, w 4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GB/sec
- text at x 6.7, y 66.2, w 8, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #76B900; left aligned]: Mem-to-GPU
- text at x 17.4, y 66.2, w 3.1, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #76B900; left aligned]: 2,000
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #76B900; left aligned]: GB/sec
- text at x 31.7, y 66.2, w 2.1, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #76B900; left aligned]: 30X
- text at x 68.4, y 70.7, w 3.7, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GRACE
- text at x 77.5, y 70.7, w 2.3, h 2.1 [DIN Pro Medium; font size 2.1% of slide height; #FFFFFF; center aligned]: GPU

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 56.3, y 15.4, w 5.0, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: LPDDR5x
- text at x 82.3, y 15.4, w 3.8, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: HBM2e
- text at x 6.7, y 31.8, w 20.9, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: A NEW COMPUTING
- text at x 6.7, y 36.2, w 21.9, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ARCHITECTURE FOR
- text at x 6.7, y 40.6, w 23.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: AI AND DATA SCIENCE
- text at x 68.4, y 25.2, w 3.7, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GRACE
- text at x 77.5, y 25.2, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 68.4, y 40.3, w 3.7, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GRACE
- text at x 77.5, y 40.3, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 6.7, y 47.2, w 20.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 30X Increase System Memory to GPU
- text at x 6.7, y 51.9, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU
- text at x 17.3, y 51.9, w 3.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 8,000
- text at x 24.2, y 51.9, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 6.7, y 56.7, w 2.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: CPU
- text at x 17.3, y 56.7, w 2.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 500
- text at x 24.2, y 56.7, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 68.4, y 55.5, w 3.7, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GRACE
- text at x 77.5, y 55.5, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU
- text at x 6.7, y 61.4, w 4.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: NVLINK
- text at x 17.3, y 61.4, w 2.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 500
- text at x 24.2, y 61.4, w 4.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GB/sec
- text at x 6.7, y 66.2, w 2.8, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: Mem
- text at x 6.7, y 66.2, w 4.6, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: Mem--to
- text at x 10.1, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: to--GPU
- text at x 11.9, y 66.2, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: GPU
- text at x 17.4, y 66.2, w 3.1, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: 2,000
- text at x 17.4, y 66.2, w 3.1, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: 2,000
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: GB/sec
- text at x 24.2, y 66.2, w 4.2, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: GB/sec
- text at x 31.7, y 66.2, w 2.1, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: 30X
- text at x 31.7, y 66.2, w 2.1, h 2.2 [DINPro-Regular; font size 2.22; #76B900]: 30X
- text at x 68.4, y 70.7, w 3.7, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GRACE
- text at x 77.5, y 70.7, w 2.3, h 2.1 [DINPro-Medium; font size 2.10; #FFFFFF]: GPU

### Slide 46

**Review notes**

- Worth keeping: Keep the incremental build sequences (17 to 21, 22 to 24), the high-contrast titles, the single dark visual system and the clean product renders such as slides 46 and 47.

**Text**

_(no text on this slide)_

**Layout**

Full-bleed single image with no text; a single centred figure stands on a grid floor at the horizontal centre of the slide, roughly in the middle vertically, with no title, footer or slide number visible.

**Visuals**

Photograph-style rendered illustration of one adult man standing centred, facing the viewer, full length, hands slightly forward at hip height, wearing a dark leather or faux-leather jacket over a dark t-shirt, dark trousers and light-coloured sneakers; his head and body are rendered as a dissolving holographic effect made of small glowing orange square pixels and blocks at the edges. He has short greyish hair and glasses. The figure occupies about 8 percent of the slide width and about 40 percent of the slide height, placed around x 45 to 53 percent and y 40 to 81 percent. Behind him is a vast dark infinite space with a perspective grid of thin orange lines: horizontal lines recede toward a vanishing point near the horizon, and diagonal lines converge toward the centre, forming a wall-like grid on the back and a floor grid below. Lighting is a soft glow from the orange grid lines and the figure's pixel edges; the scene is dark with no other light source. Dominant colours are near-black #0A0605 with orange #E07A1F grid lines and warm amber highlights. The image is full-bleed, uncropped, with no overlay other than the grid lines themselves.

**Design**

Background: Near-black #0A0605 digital grid environment with orange #E07A1F perspective lines, full-bleed photograph/render behind everything. Entirely dark, cinematic, sci-fi look; no typography. Background near-black with orange grid lines in #E07A1F; figure in grey-brown and amber tones. No text, no shapes, no borders, no shadows, no gradients beyond the natural glow of the grid.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#0A0605]: Full-bleed rendered background image of a dark infinite room with an orange perspective grid on the back wall and floor, 3840 by 2160 pixels, covering the entire slide (Uncropped, full-bleed, no border, no overlay; the grid lines are orange #E07A1F, about 1 pixel thick, with a glow.)
- photo at x 45, y 40, w 8, h 41 [#E07A1F]: Holographic pixelated rendering of an adult man with short grey hair and glasses, wearing a dark leather jacket, dark t-shirt, dark trousers and light sneakers, standing centred facing the viewer, edges dissolving into orange square pixels (Figure is semi-transparent in its interior with amber glowing block outlines at its silhouette; no frame, no shadow; it overlaps the grid floor at its feet.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 99.9: 2300 by 1294 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)

### Slide 47

**Review notes**

- Worth keeping: Keep the incremental build sequences (17 to 21, 22 to 24), the high-contrast titles, the single dark visual system and the clean product renders such as slides 46 and 47.

**Text**

ANNOUNCING NVIDIA GRACE
CPU Designed for Giant-Scale AI and HPC Accelerated Computing

**Layout**

Single centred composition with no grid or columns. The title and subtitle sit stacked at the top centre, and a large dark circuit board photograph fills the middle and lower-middle of the slide, centred horizontally. There is no footer, slide number, logo bar or visible margin text; the image bleeds to all four edges.

**Visuals**

One full-bleed photograph of a black printed circuit board (the NVIDIA Grace CPU module) shown in a three-quarter perspective view from slightly above and in front, with the board tilted so its long edge runs diagonally across the frame. The board is placed centrally with a wide black surround. Subject: two large square chip packages side by side on the board. The left package is a dark grey, borderless-looking heatsink-less die with a small multicoloured (gold, green, pink and blue iridescent) silicon die in its centre surrounded by a ring of small contact pads. The right package has a light silver-grey metal lid divided into three upper and three lower rectangular segments, with a black NVIDIA eye logo and the word NVIDIA in black capitals on the central lid panel. Around the chips are rows of small black memory modules with green-tinted edges, dark capacitors, copper-coloured mounting rings, a gold-coloured rectangular connector at the upper right corner, and gold-edged finger contacts along the front lower edge. Lighting: dark studio lighting with a soft highlight on the chip lids and metallic edges, the background falling to pure black. Dominant colours: black, dark grey, silver, with gold and green-tinted accents and iridescent colours in the left die. Framing: full-bleed, not cropped at the board, which sits entirely within the frame with black space above and below. No overlay or tint on the photograph. Small NVIDIA marks are printed on the board: a vertical NVIDIA wordmark along the left edge, a small NVIDIA logo at the lower-right corner of the left package, and the eye logo with NVIDIA wordmark on the right package lid.

**Design**

Background: Solid black #000000, with the full-bleed photograph of the circuit board on top (a white #FFFFFF fill sits beneath the images but is fully covered). Black background with white text. Title in bold, all-caps DIN Pro style sans-serif in white #FFFFFF, subtitle in regular-weight DIN Pro sans-serif in white #FFFFFF with normal (mixed) capitalisation and slight letter spacing. Title is about 4.07 percent of slide height (cap height roughly 2.9 percent); subtitle is about 2.72 percent of slide height. Accent colours come only from the photograph (gold connector, green-tinted modules, copper rings). No shapes, rules, rounded corners, shadows or gradients are drawn over the slide; the photograph has no border.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed photograph of the NVIDIA Grace CPU circuit board on black background, board viewed in three-quarter perspective with two large chip packages, memory modules and connectors (Full-bleed, not boxed, no crop of the board, no overlay or tint; background black #000000; board itself dark grey and black with silver chip lids and gold connector edges)
- logo at x 28.5, y 49.3, w 2.1, h 12 [#FFFFFF]: NVIDIA vertical wordmark printed on the left edge of the board (Printed on the PCB, silver-grey, rotated 90 degrees reading upward; sits on the board overlapping the left edge of the left chip package)
- logo at x 47.5, y 61, w 2.2, h 1 [#C0C0C0]: Small NVIDIA logo printed on the lower-right corner of the left chip package (Small silver eye logo with NVIDIA wordmark, low contrast on dark grey package)
- logo at x 55, y 45.8, w 4.8, h 5.8 [#000000]: NVIDIA eye logo and NVIDIA wordmark on the central panel of the right chip lid (Black logo on light silver-grey metal lid; eye logo above, NVIDIA capitals below)
- title at x 34.9, y 7.9, w 30.2, h 4.1 [DIN Pro, Bold, all capitals, slight letter-spacing, sans-serif; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA GRACE
- subtitle at x 27.7, y 12.5, w 44.6, h 2.7 [DIN Pro, Regular, mixed case, slight letter-spacing, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: CPU Designed for Giant-Scale AI and HPC Accelerated Computing

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3165 by 1781 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 34.9, y 7.9, w 30.2, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA GRACE
- text at x 27.7, y 12.5, w 44.6, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: CPU Designed for Giant-Scale AI and HPC Accelerated Computing

### Slide 48

**Text**

ANNOUNCING / THE WORLD’S FASTEST / SUPERCOMPUTER FOR AI / 20 Exaflops of AI / Powered by NVIDIA Grace CPU and / Next Generation NVIDIA GPU / HPC and AI for Scientific and Commercial Apps / Advance Weather, Climate, and Material Science / CSCS / Centro Svizzero di Calcolo Scientifico / Swiss National Supercomputing Centre / Hewlett Packard / Enterprise / NVIDIA / ALPS / CSCS / ETHzürich / Hewlett Packard Enterprise

**Layout**

Left-aligned text block occupies the left third, vertically centred slightly below mid-height, starting at about 6.7% from the left edge. Three partner logos sit in a horizontal row across the upper right above a wide supercomputer cabinet image that spans from about 44% to 97% of the width; no title bar, footer, or slide number is visible.

**Visuals**

A photograph of the ALPS supercomputer: a long row of about eight white cabinet panels, each printed with a panoramic snow-covered alpine mountain photograph (blue sky, white snowy peaks and ridges) on the left portion, transitioning to a white panel with a blue glacier-like pattern and large blue 'ALPS' lettering, with small CSCS and ETHzürich logos beneath the lettering. The rightmost black end cabinet carries a small green Hewlett Packard Enterprise logo and text. The cabinets stand on a dark glossy grey reflective floor, lit from above and the front, with a black background. Composition is a horizontal, full-width-of-slide arrangement, not cropped, sitting within the full-bleed background photo. Logos: CSCS emblem (red and grey diamond cluster) with wordmark and subtitle; Hewlett Packard Enterprise logo (green rectangle outline above white wordmark); NVIDIA logo (green eye emblem and white wordmark) in the top right row.

**Design**

Background: Solid black #000000 gradient fading into dark grey floor (#2A2A2A) at lower half, behind the cabinet photograph. Black background with white text; no visible title bar. Headline 'THE WORLD’S FASTEST SUPERCOMPUTER FOR AI' in white DIN-style sans-serif regular, about 4.1% of slide height for cap height line; 'ANNOUNCING' in bold DIN-style sans-serif about 3.0% of slide height, white. Body bullets in DIN regular white about 2.2% of slide height. Accent colour is NVIDIA green (#76B900) appearing in the logo only. Logos are white wordmarks and coloured emblems: CSCS red #D52B1E and grey, HPE green #01A982 outline, NVIDIA green #76B900. Lines and shapes: none. No corner radii, shadows or gradients on text; the photograph has natural reflections on the floor.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed background image of dark reflective grey floor and black backdrop (3840 by 2160 pixels) (Covers the whole slide; dark floor with soft reflections in lower half, fading to black at top; no overlay.)
- photo at x 43.9, y 32.4, w 52.2, h 35.2 [#FFFFFF]: ALPS supercomputer cabinets with alpine snow panoramas and ALPS lettering, with CSCS and ETHzürich logos on the cabinets, and HPE logo on the end cabinet (Horizontal row of about eight white cabinet panels with snowy alpine photo panels on left, blue glacier pattern and large blue ALPS lettering on right; sits on reflective floor; not boxed or cropped.)
- logo at x 46.9, y 21.6, w 15.5, h 9.2 [#D52B1E]: CSCS logo: red and grey diamond emblem, wordmark 'CSCS' with subtitle 'Centro Svizzero di Calcolo Scientifico / Swiss National Supercomputing Centre' (Emblem is red (#D52B1E) with grey (#8C8C8C) diamonds; wordmark in white sans-serif, subtitle in small white text.)
- logo at x 67.8, y 23.3, w 8.7, h 6.5 [sans-serif, regular; #01A982; left aligned]: Hewlett Packard Enterprise logo (Green (#01A982) outlined rectangle above white wordmark 'Hewlett Packard' and 'Enterprise'.)
- logo at x 78.6, y 22.7, w 10.7, h 7.4 [sans-serif, bold; #76B900; left aligned]: NVIDIA logo (Green (#76B900) eye emblem to the left of white bold uppercase wordmark 'NVIDIA'.)
- title at x 6.7, y 33.4, w 26.7, h 11 [DIN Pro, regular and bold, sans-serif, uppercase; font size 4.07% of slide height; #FFFFFF; left aligned]: ANNOUNCING / THE WORLD’S FASTEST / SUPERCOMPUTER FOR AI ('ANNOUNCING' in DIN Pro Bold at em 2.96; 'THE WORLD’S FASTEST' and 'SUPERCOMPUTER FOR AI' in DIN Pro Regular at em 4.07, line spacing about 4.1% of slide height.)
- body at x 6.7, y 47.7, w 26.8, h 16.6 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: 20 Exaflops of AI / Powered by NVIDIA Grace CPU and / Next Generation NVIDIA GPU / HPC and AI for Scientific and Commercial Apps / Advance Weather, Climate, and Material Science (Five paragraphs with about 4.7% of slide height spacing between paragraphs; 'Powered by NVIDIA Grace CPU and' and 'Next Generation NVIDIA GPU' form one paragraph with a line break; no bullet markers.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 52.1, y 21.6, w 12.5, h 9.2: 595 by 244 pixels
- image at x 78.6, y 22.7, w 10.7, h 7.4: 1288 by 502 pixels
- image at x 67.8, y 23.3, w 8.7, h 6.5: 1042 by 439 pixels
- image at x 46.9, y 21.6, w 5.2, h 9.2: 245 by 244 pixels
- text at x 6.7, y 36.7, w 25.0, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: THE WORLD’S FASTEST
- text at x 6.7, y 41.1, w 26.7, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: SUPERCOMPUTER FOR AI
- text at x 6.7, y 33.4, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 47.7, w 9.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 20 Exaflops of AI
- text at x 6.7, y 52.4, w 19.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Powered by NVIDIA Grace CPU and
- text at x 6.7, y 54.8, w 16.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Next Generation NVIDIA GPU
- text at x 6.7, y 59.6, w 26.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: HPC and AI for Scientific and Commercial Apps
- text at x 6.7, y 64.3, w 26.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Advance Weather, Climate, and Material Science

### Slide 49

**Text**

SUPERCOMPUTING COMMUNITY EMBRACES ARM
“Alps will use NVIDIA’s novel Grace CPU to converge AI technologies and classic supercomputing in one single powerful data center infrastructure.”
-Thomas Schulthess
Director CSCS
Centro Svizzero di Calcolo Scientifico
Swiss National Supercomputing Centre
“Thanks to NVIDIA’s new Grace CPU, we’ll be able to deliver advanced scientific research using high-fidelity 3D simulations and analytics with data sets that are larger than previously possible.”
-Thom Mason
Director LANL
Los Alamos
NATIONAL LABORATORY

**Layout**

Two equal dark quote cards sit side by side in the middle band of the slide, left card starting at about 9.5% and right card at about 53.5% of slide width, both spanning about 35.6% to 71% of slide height. The all-caps title is centred horizontally across the top at about 8% of slide height, with no footer, subtitle or slide number. Each card has a gold opening quote mark at top-left, quote text left-aligned, and a logo bottom-left with the attribution bottom-right.

**Visuals**

Logos only, no charts or photographs. Left card: CSCS logo, a grey metallic interlocking diamond-chevron mark (about 4.1% by 7.3% of slide) followed by the white wordmark 'CSCS' with the small two-line text 'Centro Svizzero di Calcolo Scientifico / Swiss National Supercomputing Centre' beneath it (about 10.0% by 7.3%). Right card: Los Alamos National Laboratory logo, a white circular orbit-and-atom emblem followed by white bold 'Los Alamos' and small spaced caps 'NATIONAL LABORATORY' (about 10.3% by 7.3% at x 55.3%, y 62.7%). Both logos are reversed white on the dark card. Background photograph-like studio floor is described under background.

**Design**

Background: Near-black #000000 at top fading to dark charcoal #2A2A2A on a textured grey studio floor at bottom, full-bleed image covering the whole slide. Black stage-style background with a dark charcoal floor and soft vignette. Title in bold white DIN-style condensed sans-serif capitals, about 4.07% of slide height. Quote text in DIN Pro Regular white sans-serif, about 3.33% of slide height, roughly 1.3 line spacing. Gold quote marks and card borders in muted gold #B3914C. Attribution text in grey #8C8C8C, about 1.98% of slide height. Cards are square-cornered with near-black fill #141414 and a thin muted gold-brown border about 0.2% width, no shadow, no gradient on the cards.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio backdrop image: black upper area fading into a dark grey textured floor with soft light falloff, no subject (Full slide, covers everything, no overlay, no crop shape)
- title at x 24.3, y 7.9, w 51.4, h 4.1 [DINPro-Bold, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: SUPERCOMPUTING COMMUNITY EMBRACES ARM
- shape at x 9.45, y 35.6, w 37.05, h 35.4 [#141414]: Left quote card, rectangle with near-black fill and thin gold border (Stroke muted gold #8C7A55 about 0.2% of slide width, square corners, no shadow)
- shape at x 53.5, y 35.6, w 37.1, h 35.4 [#141414]: Right quote card, rectangle with near-black fill and thin gold border (Stroke muted gold #8C7A55 about 0.2% of slide width, square corners, no shadow)
- logo at x 12.2, y 61.9, w 4.1, h 7.3 [#A0A0A0]: CSCS emblem: grey metallic interlocking diamond-chevron mark (Greyscale metallic gradient, sits on left card)
- logo at x 16.3, y 61.9, w 10, h 7.3 [#FFFFFF]: CSCS wordmark with two-line subtitle: CSCS / Centro Svizzero di Calcolo Scientifico / Swiss National Supercomputing Centre (White reversed text on dark card)
- logo at x 55.3, y 62.7, w 10.3, h 7.3 [#FFFFFF]: Los Alamos National Laboratory logo: white circular orbit emblem, Los Alamos, NATIONAL LABORATORY (White reversed on dark card)
- text at x 11.2, y 39.3, w 0.9, h 3.7 [DINPro-Regular; font size 3.7% of slide height; #B3914C; left aligned]: “
- body at x 11.9, y 39.6, w 32.9, h 14.5 [DINPro-Regular; font size 3.33% of slide height; #FFFFFF; left aligned]: Alps will use NVIDIA’s novel Grace CPU / to converge AI technologies and classic / supercomputing in one single powerful / data center infrastructure. (Line spacing about 3.7% of slide height)
- text at x 33.9, y 50.5, w 0.9, h 3.7 [DINPro-Regular; font size 3.7% of slide height; #B3914C; left aligned]: ”
- text at x 54.6, y 39.5, w 0.9, h 3.7 [DINPro-Regular; font size 3.7% of slide height; #B3914C; left aligned]: “
- body at x 55.5, y 39.8, w 33.9, h 18.1 [DINPro-Regular; font size 3.33% of slide height; #FFFFFF; left aligned]: Thanks to NVIDIA’s new Grace CPU, / we’ll be able to deliver advanced / scientific research using high-fidelity 3D / simulations and analytics with data sets / that are larger than previously possible. (Line spacing about 3.7% of slide height)
- text at x 88.4, y 54.3, w 0.9, h 3.7 [DINPro-Regular; font size 3.7% of slide height; #B3914C; left aligned]: ”
- caption at x 33.7, y 63.9, w 10.4, h 4.4 [DINPro-Regular; font size 1.98% of slide height; #8C8C8C; left aligned]: -Thomas Schulthess / Director CSCS
- caption at x 80.7, y 64, w 7.6, h 4.4 [DINPro-Regular; font size 1.98% of slide height; #8C8C8C; left aligned]: -Thom Mason / Director LANL

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 55.3, y 62.7, w 10.3, h 7.3: 621 by 249 pixels
- image at x 16.3, y 61.9, w 10.0, h 7.3: 1189 by 488 pixels
- image at x 12.2, y 61.9, w 4.1, h 7.3: 489 by 488 pixels
- text at x 24.3, y 7.9, w 51.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: SUPERCOMPUTING COMMUNITY EMBRACES ARM
- text at x 11.2, y 39.3, w 0.9, h 3.7 [DINPro-Regular; font size 3.70; #B3914C]: “
- text at x 54.6, y 39.5, w 0.9, h 3.7 [DINPro-Regular; font size 3.70; #B3914C]: “
- text at x 12.1, y 39.6, w 32.8, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: Alps will use NVIDIA’s novel Grace CPU
- text at x 55.5, y 39.8, w 29.9, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: Thanks to NVIDIA’s new Grace CPU,
- text at x 11.9, y 43.3, w 32.9, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: to converge AI technologies and classic
- text at x 55.6, y 43.4, w 27.3, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: we’ll be able to deliver advanced
- text at x 33.9, y 50.5, w 0.9, h 3.7 [DINPro-Regular; font size 3.70; #B3914C]: ”
- text at x 11.9, y 46.9, w 32.7, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: supercomputing in one single powerful
- text at x 55.6, y 47.0, w 33.9, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: scientific research using high-fidelity 3D
- text at x 88.4, y 54.3, w 0.9, h 3.7 [DINPro-Regular; font size 3.70; #B3914C]: ”
- text at x 11.9, y 50.8, w 21.9, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: data center infrastructure.
- text at x 55.6, y 50.6, w 33.5, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: simulations and analytics with data sets
- text at x 55.6, y 54.6, w 32.8, h 3.3 [DINPro-Regular; font size 3.33; #FFFFFF]: that are larger than previously possible.
- text at x 33.7, y 63.9, w 10.4, h 2.0 [DINPro-Regular; font size 1.98; #8C8C8C]: -Thomas Schulthess
- text at x 80.7, y 64.0, w 6.8, h 2.0 [DINPro-Regular; font size 1.98; #8C8C8C]: -Thom Mason
- text at x 34.2, y 66.3, w 7.0, h 2.0 [DINPro-Regular; font size 1.98; #8C8C8C]: Director CSCS
- text at x 81.2, y 66.4, w 7.1, h 2.0 [DINPro-Regular; font size 1.98; #8C8C8C]: Director LANL

### Slide 50

**Text**

3 CHIPS. YEARLY LEAPS. ONE ARCHITECTURE. / GPU / Ampere / Ampere Next / Ampere Next Next / Grace / Grace Next / CPU / BlueField-4 / BlueField-3 / DPU / BlueField-2 / 2020 / 2021 / 2022 / 2023 / 2024 / 2025

**Layout**

Centered title across the top third of the slide, with a horizontal timeline arrow across the lower part. Three rows of chips (GPU top, CPU middle, DPU lower) are labelled at the left margin (x about 14.6%) and placed by year along a left-to-right axis from 2020 to 2025 with year labels beneath the arrow. Three thin diagonal lines rise from left to right behind the chip rows. No footer, no slide number, no logos.

**Visuals**

Chart-style timeline diagram. Rows: GPU (Ampere, Ampere Next, Ampere Next Next, Grace, Grace Next), CPU (BlueField-4 and Grace-series line), DPU (BlueField-2, BlueField-3). Horizontal white timeline arrow at about y 83.7% from a filled white dot at x 18.3% to an arrowhead at x 82.8%. Year labels 2020 to 2025 sit below the arrow at about y 86%. Each chip is a close-up die photograph of a silicon processor: dark metallic die with a grid of small rectangular blocks and coloured tints (olive-green, orange, gold, purple and red), shown straight-on without perspective, with a thin grey border and no crop. Ampere (Gold-brown grid) sits in row GPU at 2020; Ampere Next at 2022; Ampere Next Next at 2024 row top; Grace (gold grid of cores) at 2023 in GPU row; Grace Next (gold-yellow core array) at 2025; BlueField-2 (purple and red blocks) at 2020 DPU row; BlueField-3 at 2022 DPU row; BlueField-4 (purple-and-orange core array) at 2024 CPU row. Three thin white diagonal lines fade out at their ends, each running from about x 23% to x 80%: upper line from lower-left near (23%, 48%) to upper-right near (79%, 31%); middle line from (23%, 64%) to (79%, 47%); lower line from (23%, 81%) to (79%, 64%). Lighting is even and neutral on the chips; the chips are not otherwise tinted or overlaid.

**Design**

Background: Full-bleed dark photographic gradient: pure black #000000 at the top fading to dark grey #3A3A3A at the bottom with a faint brushed-metal texture. Black-to-charcoal dark stage look. Titles white #FFFFFF in heavy geometric sans-serif DIN Pro Bold, all capitals, with the title about 4.1% of slide height. Row labels and chip names are white #FFFFFF in DIN Pro Regular at about 1.7% of slide height (GPU, CPU and DPU row labels are larger at about 2.2%). Year labels are white #FFFFFF DIN Pro Regular about 2.2%. Accent is the white timeline arrow and dot #FFFFFF. Diagonal lines are thin white hairlines with about 0.1% stroke weight, fading at both ends. Chips have thin grey borders. No corner radii, shadows or boxes.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark gradient background texture (black top to dark grey bottom) (Covers the entire slide behind all other elements; no crop, no overlay.)
- line at x 23, y 30.7, w 57, h 17.9 [#FFFFFF]: Upper diagonal hairline behind GPU row (Thin white line, about 0.1% stroke, fading at both ends, rising from lower-left to upper-right; overlaps the Ampere, Ampere Next and Grace chips region.)
- line at x 23, y 46.9, w 57, h 17.9 [#FFFFFF]: Middle diagonal hairline behind CPU row (Thin white line, about 0.1% stroke, fading at both ends, rising from lower-left to upper-right.)
- line at x 23, y 63.8, w 57, h 17.9 [#FFFFFF]: Lower diagonal hairline behind DPU row (Thin white line, about 0.1% stroke, fading at both ends, rising from lower-left to upper-right.)
- photo at x 19.7, y 35.8, w 5.4, h 7.5: Ampere GPU die photograph (Close-up of silicon die, grid of blocks in olive, orange and red tints, straight-on, boxed with thin grey border.)
- photo at x 40.2, y 29.4, w 5.4, h 7.5: Ampere Next GPU die photograph (Close-up of silicon die, grid in green, orange and purple tints, straight-on, thin grey border.)
- photo at x 60, y 23.3, w 5.4, h 7.5: Ampere Next Next GPU die photograph (Close-up of silicon die, grid in olive and orange tints, straight-on, thin grey border.)
- photo at x 52.1, y 42.4, w 6.6, h 8.4: Grace CPU die photograph (Close-up of silicon die with a dense array of gold-yellow core blocks, straight-on, thin grey border.)
- photo at x 69.2, y 36.7, w 6.6, h 8.4: Grace Next die photograph (Close-up of silicon die with a dense array of gold-yellow core blocks, straight-on, thin grey border.)
- photo at x 19.7, y 69.7, w 4.8, h 7.6: BlueField-2 DPU die photograph (Close-up of silicon die with purple and red blocks and olive regions, straight-on, thin grey border.)
- photo at x 40.3, y 63.4, w 5.6, h 7.6: BlueField-3 DPU die photograph (Close-up of silicon die with purple and red blocks, straight-on, thin grey border.)
- photo at x 57.1, y 57.6, w 7.5, h 6.8: BlueField-4 DPU die photograph (Close-up of silicon die with a grid of purple and orange core blocks, straight-on, thin grey border.)
- line at x 18.3, y 83.5, w 64.5, h 0.5 [#FFFFFF]: Timeline arrow (Horizontal white line about 0.2% stroke with filled triangular arrowhead at the right end at x 82.8%.)
- shape at x 17.8, y 83.1, w 1, h 1 [#FFFFFF]: Timeline start dot (Filled white circle at the left end of the timeline arrow.)
- body at x 25.7, y 7.9, w 48.5, h 4.1 [DIN Pro Bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: 3 CHIPS. YEARLY LEAPS. ONE ARCHITECTURE.
- body at x 14.6, y 39.7, w 2.5, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU
- body at x 25.9, y 37.4, w 3.4, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Ampere
- body at x 46.4, y 31.1, w 5.6, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Ampere Next
- body at x 66.1, y 24.8, w 7.9, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Ampere Next Next
- body at x 59.6, y 44, w 2.5, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Grace
- body at x 76.7, y 38.4, w 4.8, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: Grace Next
- body at x 14.6, y 57, w 2.4, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: CPU
- body at x 65.5, y 59.2, w 5.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: BlueField-4
- body at x 46.6, y 65, w 5.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: BlueField-3
- body at x 14.6, y 72.8, w 2.5, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: DPU
- body at x 25.3, y 71.3, w 5.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; left aligned]: BlueField-2
- body at x 21.1, y 86.3, w 2.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2020
- body at x 31.1, y 86.3, w 2.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2021
- body at x 41.1, y 86.3, w 2.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2022
- body at x 51.2, y 86.3, w 2.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2023
- body at x 61.2, y 86.3, w 2.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2024
- body at x 71.5, y 86.1, w 2.6, h 2.2 [DIN Pro Regular; font size 2.22% of slide height; #FFFFFF; center aligned]: 2025

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 23.0, y 63.8, w 57.0, h 17.9: 1642 by 290 pixels
- image at x 23.0, y 63.8, w 57.0, h 17.9: 1642 by 290 pixels
- image at x 23.0, y 46.9, w 57.0, h 17.9: 1642 by 290 pixels
- image at x 23.0, y 46.9, w 57.0, h 17.9: 1642 by 290 pixels
- image at x 23.0, y 30.7, w 57.0, h 17.9: 1642 by 290 pixels
- image at x 23.0, y 30.7, w 57.0, h 17.9: 1642 by 290 pixels
- image at x 52.1, y 42.4, w 6.6, h 8.4: 414 by 294 pixels
- image at x 69.2, y 36.7, w 6.6, h 8.4: 207 by 147 pixels
- image at x 57.1, y 57.6, w 7.5, h 6.8: 500 by 255 pixels
- image at x 40.3, y 63.4, w 5.6, h 7.6: 400 by 306 pixels
- image at x 19.7, y 35.8, w 5.4, h 7.5: 416 by 328 pixels
- image at x 40.2, y 29.4, w 5.4, h 7.5: 208 by 164 pixels
- image at x 60.0, y 23.3, w 5.4, h 7.5: 104 by 82 pixels
- image at x 19.7, y 69.7, w 4.8, h 7.6: 400 by 358 pixels
- text at x 25.7, y 7.9, w 48.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: 3 CHIPS. YEARLY LEAPS. ONE ARCHITECTURE.
- text at x 66.1, y 24.8, w 7.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Ampere Next Next
- text at x 14.6, y 39.7, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU
- text at x 46.4, y 31.1, w 5.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Ampere Next
- text at x 25.9, y 37.4, w 3.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Ampere
- text at x 76.7, y 38.4, w 4.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Grace Next
- text at x 14.6, y 57.0, w 2.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: CPU
- text at x 59.6, y 44.0, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Grace
- text at x 14.6, y 72.8, w 2.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: DPU
- text at x 65.5, y 59.2, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: BlueField-4
- text at x 46.6, y 65.0, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: BlueField-3
- text at x 71.5, y 86.1, w 2.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2025
- text at x 21.1, y 86.3, w 2.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2020
- text at x 31.1, y 86.3, w 2.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2021
- text at x 41.1, y 86.3, w 2.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2022
- text at x 51.2, y 86.3, w 2.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2023
- text at x 61.2, y 86.3, w 2.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2024
- text at x 25.3, y 71.3, w 5.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: BlueField-2

### Slide 51

**Text**

EXPANDING ARM IN THE CLOUD
CLOUD
NVIDIA AI
NVIDIA GeForce NOW
NVIDIA GPU
AWS Graviton
Bringing Together AWS Graviton2 CPU and NVIDIA GPU in 2H21
Android Gaming and AI Inference in the Cloud
AWS Graviton2 Delivers Significantly Better Price Performance
NVIDIA GPUs Deliver Performance to Scale Streaming
Easiest Way to Move Android Gaming to the Cloud

**Layout**

Single-slide composition with a centred all-caps title across the top, a tall boxed 'CLOUD' panel on the left third, a left-aligned five-line text list in the centre-right, and the AWS and NVIDIA logos stacked in the right column. Margins are generous, with no footer, slide number or date visible.

**Visuals**

Icon and logo group: (1) a green-outlined grid icon, a 4 by 5 array of small square cells, labelled 'NVIDIA GPU' beneath it, in a line-art style on the left of the panel. (2) A line-art illustration in blue-violet strokes of a CPU chip labelled 'AWS Graviton2' with pins on all sides, a lightbulb icon at upper left, a speedometer gauge with a dollar coin at right, labelled 'AWS Graviton' beneath. (3) The AWS logo in white lettering 'aws' with an orange (#FF9900) smile arrow, at upper right of the text list. (4) The NVIDIA logo: green (#76B900) eye emblem on a black-and-green square followed by the white wordmark 'NVIDIA' in heavy sans-serif. No photographs, charts or tables.

**Design**

Background: Full-bleed dark photograph: near-black #000000 at top fading to charcoal grey #2A2A2A on a reflective, scratched studio floor at the bottom. Dark, cinematic look: near-black background with a charcoal floor. Titles and body text are white #FFFFFF; the accent is NVIDIA green #76B900, used for the solid button-style box and the icon outlines. Typeface is DIN Pro (DIN-style grotesque, sans-serif): Bold for the title, Medium for 'CLOUD', Regular for all other text. Title cap height is roughly 4 percent of slide height; body text is about 2.2 percent. Panel is a near-black #121212 rectangle with a thin 1 pixel warm brown-grey border (about #4A4035) and a soft drop shadow beneath. The green box has square corners and no border.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark studio backdrop photograph: black upper area fading into a charcoal grey, slightly reflective floor with faint scratches; no subject; a white full-slide fill sits beneath it (Covers the whole slide; soft vignette darker at top; no overlay or tint beyond the photograph itself)
- shape at x 80.3, y 59.4, w 12.4, h 4.1 [#FFFFFF]: Empty white rectangle, visually hidden beneath the background photograph (Filled white with no stroke; not visible in the rendered slide because the background covers it)
- title at x 33.3, y 7.9, w 33.4, h 4.1 [DIN Pro, Bold, all caps, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: EXPANDING ARM IN THE CLOUD
- shape at x 3.8, y 21.5, w 22.1, h 61.7 [#121212]: Dark rectangular panel holding the cloud stack (Fill #121212, 1 pixel stroke in warm brown-grey (about #4A4035), square corners, soft drop shadow falling below the panel, slight glow on the left edge)
- body at x 12.6, y 24.1, w 4.4, h 2.5 [DIN Pro, Medium, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: CLOUD
- shape at x 4.4, y 28.9, w 20.8, h 9.4 [#76B900]: Solid green rectangle button with two lines of centred white text (Fill #76B900, square corners, no border, sits inside the panel with equal side margins)
- body at x 9.5, y 31.5, w 10.7, h 4.4 [DIN Pro, Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA AI / NVIDIA GeForce NOW (Line spacing about 1.3; 'NVIDIA AI' on the first line, 'NVIDIA GeForce NOW' on the second)
- icon at x 13, y 43.7, w 3.6, h 6.4 [#76B900]: NVIDIA GPU icon: a square grid of 4 by 5 small outlined cells in green lines, on a dark ground (Line-art, stroke about 1 pixel, cells with square corners, no fill)
- caption at x 12.2, y 51.5, w 5.2, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU
- illustration at x 9.5, y 55.4, w 11.6, h 10.1 [#4D7CFE]: AWS Graviton2 illustration: a chip with a square core labelled AWS Graviton2 and pins on all four sides; a lightbulb icon at upper left, and a speedometer gauge with a dollar coin at lower right (Blue-violet line-art (about #4D7CFE) with white inner label text 'AWS Graviton2' on a dark core, stroke about 1 pixel; the gauge has a blue arc and a needle)
- caption at x 11.8, y 66.2, w 5.8, h 1.7 [DIN Pro, Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: AWS Graviton
- body at x 32.4, y 42.6, w 35.1, h 21.2 [DIN Pro, Regular, sentence case; font size 2.22% of slide height; #FFFFFF; left aligned]: Bringing Together AWS Graviton2 CPU and NVIDIA GPU in 2H21 / Android Gaming and AI Inference in the Cloud / AWS Graviton2 Delivers Significantly Better Price Performance / NVIDIA GPUs Deliver Performance to Scale Streaming / Easiest Way to Move Android Gaming to the Cloud (Five separate lines with roughly 4.8 percent of slide height between baselines; no bullet markers)
- logo at x 79.2, y 42.5, w 9.2, h 9.8 [#FF9900]: AWS logo: white lowercase 'aws' wordmark with an orange smile arrow (Arrow in orange (#FF9900) curving under the wordmark from left to right, tip pointing right and up)
- logo at x 74, y 58.2, w 18.6, h 6.2 [#76B900]: NVIDIA logo: green eye emblem on a green square followed by the white wordmark NVIDIA (Estimated bounds from the render; emblem in #76B900 with a black inner band, wordmark in white heavy sans-serif)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 80.3, y 59.4, w 12.4, h 4.1: #FFFFFF
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 4.4, y 28.9, w 20.8, h 9.4: 2497 by 633 pixels
- image at x 9.5, y 55.4, w 11.6, h 10.1: 275 by 135 pixels
- image at x 79.2, y 42.5, w 9.2, h 9.8: 330 by 198 pixels
- image at x 9.7, y 65.5, w 10.1, h 2.7: 1215 by 184 pixels
- image at x 9.7, y 50.9, w 10.1, h 2.7: 1215 by 184 pixels
- image at x 13.0, y 43.7, w 3.6, h 6.4: 430 by 430 pixels
- text at x 33.3, y 7.9, w 33.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: EXPANDING ARM IN THE CLOUD
- text at x 12.6, y 24.1, w 4.4, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: CLOUD
- text at x 12.4, y 31.5, w 4.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA AI
- text at x 9.5, y 33.9, w 10.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA GeForce NOW
- text at x 32.4, y 42.6, w 35.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Bringing Together AWS Graviton2 CPU and NVIDIA GPU in 2H21
- text at x 32.4, y 47.4, w 25.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Android Gaming and AI Inference in the Cloud
- text at x 32.4, y 52.1, w 34.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: AWS Graviton2 Delivers Significantly Better Price Performance
- text at x 32.4, y 56.9, w 30.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: NVIDIA GPUs Deliver Performance to Scale Streaming
- text at x 32.4, y 61.6, w 27.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Easiest Way to Move Android Gaming to the Cloud
- text at x 12.2, y 51.5, w 5.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU
- text at x 11.8, y 66.2, w 5.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AWS Graviton

### Slide 52

**Text**

EXPANDING ARM ECOSYSTEM BEYOND MOBILE
CLOUD
NVIDIA AI / NVIDIA GeForce NOW
NVIDIA GPU
AWS Graviton
SCIENTIFIC COMPUTING
NVIDIA AI / NVIDIA HPC
NVIDIA A100
NVIDIA BlueField-2
Ampere Altra
EDGE AND ENTERPRISE
NVIDIA AI / NVIDIA DeepStream
NVIDIA T4
Marvell OCTEON
PC
NVIDIA AI / NVIDIA RTX
GeForce RTX 30 Series
MediaTek MT819x

**Layout**

Four equal dark panels sit in a row across the lower two-thirds of the slide, with a centred bold title across the top and a horizontal margin of about 4% on each side. Each panel has a centred header at the top, a full-width green bar beneath it, and a stack of centred hardware icons with labels below; no footer or slide number is visible.

**Visuals**

Four rows of small line-art icons and product labels, plus three product photographs. Cloud column: green NVIDIA GPU chip icon labelled NVIDIA GPU, and a blue line illustration of an AWS Graviton2 chip with a speedometer, a lightbulb and a dollar coin, labelled AWS Graviton. Scientific Computing column: two dark green chip icons labelled NVIDIA A100 (dim, outlined) and a purple four-cell icon labelled NVIDIA BlueField-2 (two purple four-cell icons side by side), and a red four-cell icon labelled Ampere Altra. Edge and Enterprise column: green chip icon labelled NVIDIA T4 and a grey four-cell icon labelled Marvell OCTEON. PC column: green chip icon labelled GeForce RTX 30 Series and a purple four-cell icon labelled MediaTek MT819x. Photographs: a white rack server chassis with its lid open, showing a black GPU card and a gold-coloured accelerator card, tilted about 20 degrees and standing on the lower part of the Scientific Computing panel and the floor; a second white server chassis with its lid open, showing a grey card and a dark gold card, tilted in the same way, standing on the lower part of the Edge and Enterprise panel; and a white laptop, open about 100 degrees, with a screen showing a dim, warm-lit first-person game corridor, standing on the floor under the PC panel. All photographs are full-colour, boxed as cut-outs with no border, lit by a soft top light with reflections on the dark floor.

**Design**

Background: Near-black #000000 backdrop with a dark grey reflective floor (#2A2A2A) at the base, full-bleed photograph. Black studio look with white bold sans-serif headings and white regular sans-serif body labels. Title is DIN Pro Bold in white, uppercase, about 4.1% of slide height. Panel headers are DIN Pro Medium in white, uppercase, about 2.5%. Green bars carry DIN Pro Regular text in white, about 2.0%. Product labels are DIN Pro Regular in white, about 1.7%. Accent green #76B900, panels #141414 with thin warm bronze outline #4A3F2C, icon colours green #76B900, purple #6B3FA0, red #D9372B, grey #A0A0A0, blue #3B82F6. No corner radii, shadows or gradients on the panels; the background has a soft vignette.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed studio backdrop: black upper area fading to dark grey reflective floor, with soft light falloff (Covers the whole slide, behind everything else; no overlay)
- shape at x 3.8, y 21.6, w 22, h 61.6 [#141414]: Dark panel, Cloud column (Rectangle, square corners, 0.2% stroke in bronze #4A3F2C, no shadow)
- shape at x 27.3, y 21.6, w 22, h 61.6 [#141414]: Dark panel, Scientific Computing column (Rectangle, square corners, 0.2% stroke in bronze #4A3F2C, no shadow)
- shape at x 50.65, y 21.6, w 22, h 61.6 [#141414]: Dark panel, Edge and Enterprise column (Rectangle, square corners, 0.2% stroke in bronze #4A3F2C, no shadow)
- shape at x 74.15, y 21.6, w 22, h 61.6 [#141414]: Dark panel, PC column (Rectangle, square corners, 0.2% stroke in bronze #4A3F2C, no shadow)
- photo at x 33.2, y 78.7, w 14.65, h 18.2 [#FFFFFF]: White rack server chassis with lid open, black GPU card and gold accelerator card visible, tilted about 20 degrees, cut out (Boxed as cut-out with no border; overlaps the lower edge of the Scientific Computing panel)
- photo at x 56.4, y 78.2, w 15.2, h 18.2 [#FFFFFF]: White rack server chassis with lid open, grey and dark gold cards visible, tilted about 20 degrees, cut out (Boxed as cut-out with no border; overlaps the lower edge of the Edge and Enterprise panel)
- photo at x 80.5, y 77.2, w 12.35, h 17.2 [#FFFFFF]: White laptop open about 100 degrees, screen showing a warm-lit first-person game corridor (Boxed as cut-out, no border; stands on the floor beneath the PC panel)
- shape at x 4.4, y 28.9, w 20.8, h 9.4 [DIN Pro Regular; font size 1.98% of slide height; #76B900; center aligned]: Green bar, Cloud column (Filled rectangle, square corners, no stroke)
- shape at x 27.9, y 28.9, w 20.8, h 9.4 [DIN Pro Regular; font size 1.98% of slide height; #76B900; center aligned]: Green bar, Scientific Computing column (Filled rectangle, square corners, no stroke)
- shape at x 51.3, y 28.9, w 20.8, h 9.4 [DIN Pro Regular; font size 1.98% of slide height; #76B900; center aligned]: Green bar, Edge and Enterprise column (Filled rectangle, square corners, no stroke)
- shape at x 74.8, y 28.9, w 20.8, h 9.4 [DIN Pro Regular; font size 1.98% of slide height; #76B900; center aligned]: Green bar, PC column (Filled rectangle, square corners, no stroke)
- title at x 25.3, y 7.9, w 49.4, h 4.1 [DIN Pro Bold, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: EXPANDING ARM ECOSYSTEM BEYOND MOBILE (Single line)
- body at x 12.6, y 24.1, w 4.4, h 2.5 [DIN Pro Medium, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: CLOUD
- body at x 30.6, y 24.1, w 15.3, h 2.5 [DIN Pro Medium, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: SCIENTIFIC COMPUTING
- body at x 54.1, y 24.1, w 15.2, h 2.5 [DIN Pro Medium, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: EDGE AND ENTERPRISE
- body at x 84.3, y 24.1, w 1.7, h 2.5 [DIN Pro Medium, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: PC
- body at x 9.5, y 31.5, w 10.7, h 4.4 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA AI / NVIDIA GeForce NOW (Two lines on green bar, line 1 NVIDIA AI, line 2 NVIDIA GeForce NOW)
- body at x 35.3, y 31.5, w 5.9, h 4.4 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA AI / NVIDIA HPC (Two lines on green bar)
- body at x 56.7, y 31.5, w 9.9, h 4.4 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA AI / NVIDIA DeepStream (Two lines on green bar)
- body at x 82.3, y 31.5, w 5.7, h 4.4 [DIN Pro Regular; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA AI / NVIDIA RTX (Two lines on green bar)
- icon at x 13, y 43.7, w 3.6, h 6.4 [#76B900]: NVIDIA GPU chip icon, green outline grid of small squares (Line icon, 1 px stroke)
- caption at x 12.2, y 51.5, w 5.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU
- illustration at x 9.5, y 55.4, w 11.6, h 10.1 [#3B82F6]: AWS Graviton2 chip with lightbulb, speedometer and dollar coin, blue line art (Line illustration; chip label reads AWS Graviton2 in white)
- caption at x 11.8, y 66.2, w 5.8, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: AWS Graviton
- icon at x 29, y 43.7, w 3.6, h 6.4 [#2F4A12]: NVIDIA A100 chip icon, dim dark green outline grid (Line icon)
- icon at x 33.2, y 43.7, w 3.6, h 6.4 [#2F4A12]: NVIDIA A100 chip icon, dim dark green outline grid (Line icon)
- caption at x 30.2, y 51.6, w 5.4, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA A100
- icon at x 39.7, y 43.6, w 3.6, h 6.4 [#6B3FA0]: NVIDIA BlueField-2 icon, purple four-cell outline (Line icon)
- icon at x 43.9, y 43.6, w 3.6, h 6.4 [#6B3FA0]: NVIDIA BlueField-2 icon, purple four-cell outline (Line icon)
- caption at x 39.4, y 51.6, w 8.3, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA BlueField-2
- icon at x 36.5, y 58.3, w 3.6, h 6.4 [#D9372B]: Ampere Altra icon, red four-cell outline (Line icon)
- caption at x 35.4, y 66.2, w 5.8, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Ampere Altra
- icon at x 59.9, y 43.7, w 3.6, h 6.4 [#76B900]: NVIDIA T4 chip icon, green outline grid (Line icon)
- caption at x 59.5, y 51.5, w 4.3, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA T4
- icon at x 59.9, y 58.3, w 3.6, h 6.4 [#A0A0A0]: Marvell OCTEON icon, grey four-cell outline (Line icon)
- caption at x 58.1, y 66.2, w 7.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Marvell OCTEON
- icon at x 83.4, y 43.7, w 3.6, h 6.4 [#76B900]: GeForce RTX 30 Series chip icon, green outline grid (Line icon)
- caption at x 80.3, y 51.5, w 9.8, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: GeForce RTX 30 Series
- icon at x 83.4, y 58.3, w 3.6, h 6.4 [#7A5FB0]: MediaTek MT819x icon, purple four-cell outline (Line icon)
- caption at x 81.5, y 66.2, w 7.7, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: MediaTek MT819x

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 4.4, y 28.9, w 20.8, h 9.4: 2497 by 633 pixels
- image at x 51.3, y 28.9, w 20.8, h 9.4: 2497 by 633 pixels
- image at x 74.8, y 28.9, w 20.8, h 9.4: 2496 by 633 pixels
- image at x 27.9, y 28.9, w 20.8, h 9.4: 2497 by 633 pixels
- image at x 9.5, y 55.4, w 11.6, h 10.1: 275 by 135 pixels
- image at x 80.3, y 64.2, w 10.1, h 5.3: 1215 by 360 pixels
- image at x 79.1, y 50.9, w 12.2, h 2.7: 1460 by 184 pixels
- image at x 56.6, y 65.5, w 10.1, h 2.7: 1216 by 184 pixels
- image at x 56.6, y 50.9, w 10.1, h 2.7: 1216 by 184 pixels
- image at x 33.2, y 65.5, w 10.1, h 2.7: 1215 by 184 pixels
- image at x 9.7, y 65.5, w 10.1, h 2.7: 1215 by 184 pixels
- image at x 27.8, y 50.9, w 10.1, h 2.7: 1215 by 185 pixels
- image at x 9.7, y 50.9, w 10.1, h 2.7: 1215 by 184 pixels
- image at x 38.5, y 50.9, w 10.1, h 2.7: 1215 by 185 pixels
- image at x 83.4, y 43.7, w 3.6, h 6.4: 27 by 27 pixels
- image at x 33.2, y 43.7, w 3.6, h 6.4: 14 by 14 pixels
- image at x 29.0, y 43.7, w 3.6, h 6.4: 7 by 7 pixels
- image at x 13.0, y 43.7, w 3.6, h 6.4: 430 by 430 pixels
- image at x 59.9, y 43.7, w 3.6, h 6.4: 54 by 54 pixels
- image at x 36.5, y 58.3, w 3.6, h 6.4: 430 by 430 pixels
- image at x 39.7, y 43.6, w 3.6, h 6.4: 430 by 430 pixels
- image at x 43.9, y 43.6, w 3.6, h 6.4: 430 by 430 pixels
- image at x 59.9, y 58.3, w 3.6, h 6.4: 429 by 429 pixels
- image at x 83.4, y 58.3, w 3.6, h 6.4: 429 by 429 pixels
- text at x 25.3, y 7.9, w 49.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: EXPANDING ARM ECOSYSTEM BEYOND MOBILE
- text at x 12.6, y 24.1, w 4.4, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: CLOUD
- text at x 30.6, y 24.1, w 15.3, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: SCIENTIFIC COMPUTING
- text at x 54.1, y 24.1, w 15.2, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: EDGE AND ENTERPRISE
- text at x 84.3, y 24.1, w 1.7, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: PC
- text at x 12.4, y 31.5, w 4.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA AI
- text at x 35.9, y 31.5, w 4.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA AI
- text at x 59.3, y 31.5, w 4.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA AI
- text at x 82.8, y 31.5, w 4.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA AI
- text at x 9.5, y 33.9, w 10.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA GeForce NOW
- text at x 35.3, y 33.9, w 5.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA HPC
- text at x 56.7, y 33.9, w 9.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA DeepStream
- text at x 82.3, y 33.9, w 5.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA RTX
- text at x 12.2, y 51.5, w 5.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU
- text at x 30.2, y 51.6, w 5.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA A100
- text at x 39.4, y 51.6, w 8.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA BlueField-2
- text at x 59.5, y 51.5, w 4.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA T4
- text at x 80.3, y 51.5, w 9.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GeForce RTX 30 Series
- text at x 11.8, y 66.2, w 5.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: AWS Graviton
- text at x 35.4, y 66.2, w 5.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Ampere Altra
- text at x 58.1, y 66.2, w 7.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Marvell OCTEON
- text at x 81.5, y 66.2, w 7.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: MediaTek MT819x

### Slide 53

**Text**

WAVES OF AI
AI Computing
Cloud
5G Industrial Edge
Robotics

**Layout**

Four equal columns of icon-and-label pairs centred under a single centred title near the top of a full-bleed dark slide; the title sits centred at about 8% from the top, the four column labels share one baseline at about 31% from the top, and the icons sit beneath them at about 40% to 66% of slide height. No footer, no slide number, no visible margins beyond the generous centred column spacing.

**Visuals**

Four line-art icons in thin gold strokes, left to right: (1) AI Computing: a neural network diagram of small circles arranged in four layers, left layer 4 nodes, middle layer 3 nodes, right layer 3 nodes, with thin straight connecting lines between every node in adjacent layers, drawn in #BD9F63 gold on black. (2) Cloud: a single outlined cloud silhouette with a rounded bottom and a small inner curved stroke at the lower right, drawn in thin gold outline, no fill. (3) 5G Industrial Edge: a telecom tower with a central vertical mast, a crossbar with two lateral flat panel antennas, concentric arc signal waves on both sides, and a base plate on a ground line, drawn in thin gold outline. (4) Robotics: a multi-jointed industrial robot arm with circular joints and a gripper, set inside a faint wireframe sphere of triangulated mesh lines, drawn in gold outline. The background is a black-to-dark-grey gradient with a subtle brushed-metal floor texture in the lower half, with a faint vertical light streak below the centre column.

**Design**

Background: Black #000000 at top fading to dark grey #2A2A2A and charcoal textured floor at the bottom, photographic textured surface behind everything.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed background image: black studio backdrop fading to dark grey brushed-metal floor texture with a faint vertical light streak near the centre bottom (Covers the whole slide, behind all other elements; gradient from black top to dark grey #2A2A2A bottom; no crop, no overlay)
- title at x 43.2, y 7.9, w 13.6, h 4.1 [DINPro-Bold, sans-serif, bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: WAVES OF AI (Uppercase, slight letter-spacing)
- body at x 12, y 30.7, w 6.8, h 2 [DINPro-Light, sans-serif, light weight, slight letter-spacing; font size 2.04% of slide height; #BD9F63; center aligned]: AI Computing (Column label above icon 1)
- icon at x 9.5, y 47.9, w 10.8, h 18.3 [#BD9F63]: Neural network diagram: 4-3-3-1-style layered nodes of small circles connected by thin straight lines in gold outline (left column of 4 nodes, middle 3 nodes, right 3 nodes) (Thin stroke about 1 px, circles outlined, no fill, no shadow)
- body at x 34.3, y 30.7, w 2.9, h 2 [DINPro-Light, sans-serif, light weight, slight letter-spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Cloud (Column label above icon 2)
- icon at x 30, y 48.4, w 10.9, h 13 [#BD9F63]: Cloud outline icon with a small inner curved stroke at lower right (Thin gold outline, no fill, rounded bottom, no shadow)
- body at x 52.3, y 30.7, w 9.3, h 2 [DINPro-Light, sans-serif, light weight, slight letter-spacing; font size 2.04% of slide height; #BD9F63; center aligned]: 5G Industrial Edge (Column label above icon 3)
- icon at x 51.5, y 40, w 10.5, h 26.9 [#BD9F63]: Telecom tower with two flat panel antennas on a crossbar, concentric signal arcs on both sides, and a base on a ground line (Thin gold outline, no fill, no shadow)
- body at x 80.4, y 30.7, w 4.4, h 2 [DINPro-Light, sans-serif, light weight, slight letter-spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Robotics (Column label above icon 4)
- icon at x 75.1, y 39.3, w 15.2, h 27.7 [#BD9F63]: Industrial robot arm with circular joints and gripper inside a faint wireframe sphere of triangulated mesh lines (Gold thin-line outline with faint mesh sphere, no fill, sphere overlaps the arm)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 43.2, y 7.9, w 13.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: WAVES OF AI
- text at x 12.0, y 30.7, w 6.8, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: AI Computing
- text at x 34.3, y 30.7, w 2.9, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Cloud
- text at x 52.3, y 30.7, w 9.3, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: 5G Industrial Edge
- text at x 80.4, y 30.7, w 4.4, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Robotics

### Slide 54

**Review notes**

- Suggested repair: Raise the contrast and size of the gold captions on slides 2, 17 to 21, 36 and 54, and enlarge the labels and footnotes inside the diagrams on slides 5, 27, 29 and 33.

**Text**

NVIDIA AI / DATA PREP / TRAIN / SIMULATE / ORCHESTRATE / NVIDIA AI / NVIDIA GPU CLOUD REGISTRY / cuIO / cuDF / cuDNN / cuML / cuGraph / TAO / TensorRT / Triton / NVIDIA CUDA, DOCA, vGPU, Magnum IO

**Layout**

Centred composition on a black-to-dark-grey studio backdrop: title centred at the top, a row of four process boxes (Data Prep, Train, Simulate, Orchestrate) linked by left-to-right arrows with a return loop line across the top, and a wide green stack panel centred below. The four boxes span roughly 27% to 74% of width, with a large empty margin on both sides; no footer or slide number is visible.

**Visuals**

Four outlined square-cornered boxes in a left-to-right flow, each with a white line illustration: (1) DATA PREP: a grid of small rectangles on the left linked by double-headed arrows to a column of stacked rectangular rows on the right; (2) TRAIN: a neural network diagram of three columns of circles (input, hidden, output) connected by thin lines; (3) SIMULATE: a white line-drawn industrial robot arm with a circular orbit path around it; (4) ORCHESTRATE: a 3x3-style grid of small white line icons showing a robot arm, a truck, a wind turbine, a phone, a traffic light, another robot arm, a drone-like device, a document/chart board, and a vehicle with a crane. Solid gold/tan arrows connect boxes 1 to 2, 2 to 3, and 3 to 4 at mid-height. A thin tan line loops from the bottom of box 4 up to the top edge, across to above box 1, and down to an arrow entering box 1. Below, a green rectangle panel (NVIDIA green) contains the stacked software layers described in the elements. A faint dark floor reflection of the green panel appears under it on a dark grey glossy surface.

**Design**

Background: Black-to-dark-grey gradient background (#000000 top to #2B2B2B bottom) with a faint green glow reflection on the floor. Black background (#000000) fading to dark grey floor (#2B2B2B) at the bottom; the green panel is NVIDIA green #76B900 with darker green bars #4A7A00 for the registry and CUDA rows and cells in #4F8500 with thin darker bottom edges #3A6300. Title and labels are white #FFFFFF in a DIN-style humanist sans-serif (DINPro Bold for the title and panel heading, DINPro Medium for box headings, DINPro Regular for body). Title size about 4.1% of slide height, box headings about 1.7%, panel heading about 2.5%. Process boxes have black fill #111111 with thin light grey-tan outline #C8C0A0 about 0.3 pt, square corners, and a subtle shadow; arrows and loop line are tan/gold #C9A45C. Green cells have square corners with slight drop shading.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- title at x 45, y 7.9, w 10, h 4.1 [DINPro-Bold, bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA AI (Sits centred at the top of the slide.)
- shape at x 27.1, y 20.1, w 45.7, h 8.1 [#C9A45C]: Return loop line, tan connector from bottom of ORCHESTRATE box up to top edge, across and down into DATA PREP input arrow (Thin line about 0.2 pt, square corners, stroke colour #C9A45C.)
- shape at x 29.4, y 22.6, w 12, h 13.8 [#111111]: Process box DATA PREP (Black fill #111111, thin outline #C8C0A0 about 0.3 pt, square corners, subtle shadow.)
- illustration at x 30, y 26.4, w 10, h 9.9 [#FFFFFF]: DATA PREP line drawing: grid of small rectangles linked by double-headed arrows to stacked rows (White thin-line drawing on black.)
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DINPro-Medium, medium weight, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: DATA PREP
- shape at x 41.7, y 22.6, w 12, h 13.8 [#111111]: Process box TRAIN (Black fill #111111, thin outline #C8C0A0 about 0.3 pt, square corners, subtle shadow.)
- illustration at x 42.5, y 26.4, w 6.3, h 9.9 [#FFFFFF]: TRAIN line drawing: neural network diagram of circles in three columns connected by lines (White thin-line drawing on black.)
- text at x 43, y 23.6, w 2.8, h 1.7 [DINPro-Medium, medium weight, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: TRAIN
- shape at x 52, y 22.6, w 12, h 13.8 [#111111]: Process box SIMULATE (Black fill #111111, thin outline #C8C0A0 about 0.3 pt, square corners, subtle shadow.)
- illustration at x 52.7, y 26.4, w 8, h 9.9 [#FFFFFF]: SIMULATE line drawing: industrial robot arm on a base with a circular orbit path (White thin-line drawing on black.)
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DINPro-Medium, medium weight, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: SIMULATE
- shape at x 62.7, y 22.6, w 12, h 13.8 [#111111]: Process box ORCHESTRATE (Black fill #111111, thin outline #C8C0A0 about 0.3 pt, square corners, subtle shadow.)
- icon at x 63.8, y 25.9, w 6.1, h 9 [#FFFFFF]: ORCHESTRATE line icons: robot arm, truck, wind turbine, mobile phone, traffic light, robot arm, drone-like device, document board, vehicle with crane (White thin-line icons on black.)
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DINPro-Medium, medium weight, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: ORCHESTRATE
- shape at x 37.7, y 28.9, w 4, h 0.4 [#C9A45C]: Arrow DATA PREP to TRAIN (Thin tan arrow with filled triangular head pointing right.)
- shape at x 49.3, y 28.9, w 4, h 0.4 [#C9A45C]: Arrow TRAIN to SIMULATE (Thin tan arrow with filled triangular head pointing right.)
- shape at x 60.9, y 28.9, w 4, h 0.4 [#C9A45C]: Arrow SIMULATE to ORCHESTRATE (Thin tan arrow with filled triangular head pointing right.)
- shape at x 27.2, y 40.2, w 45.5, h 23.6 [#76B900]: Green stack panel (Solid NVIDIA green #76B900, square corners, drop shadow beneath, sits centred below the process row.)
- text at x 47, y 41.1, w 6, h 2.5 [DINPro-Medium, medium weight; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AI
- shape at x 27.9, y 46.1, w 44.2, h 4.3 [#4A7A00]: Registry bar (Darker green bar #4A7A00, square corners, thin darker bottom edge.)
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular, regular weight, all capitals; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU CLOUD REGISTRY
- shape at x 27.9, y 51.9, w 5.2, h 6 [#4F8500]: Library cell cuIO (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: cuIO
- shape at x 33.5, y 51.9, w 5.2, h 6 [#4F8500]: Library cell cuDF (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDF
- shape at x 39.1, y 51.9, w 5.2, h 6 [#4F8500]: Library cell cuDNN (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 40, y 52.6, w 3.1, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDNN
- shape at x 44.7, y 51.9, w 5.2, h 6 [#4F8500]: Library cell cuML (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 46, y 52.6, w 2.4, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: cuML
- shape at x 50.4, y 51.9, w 5.2, h 6 [#4F8500]: Library cell cuGraph (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 51, y 52.6, w 3.6, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: cuGraph
- shape at x 56, y 51.9, w 5.2, h 6 [#4F8500]: Library cell TAO (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: TAO
- shape at x 61.6, y 51.9, w 5.2, h 6 [#4F8500]: Library cell TensorRT (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 62, y 52.6, w 4.1, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: TensorRT
- shape at x 67.2, y 51.9, w 5.2, h 6 [#4F8500]: Library cell Triton (Square-cornered cell #4F8500 with thin darker bottom edge #3A6300.)
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Triton
- shape at x 27.9, y 57.9, w 44.2, h 4.3 [#4A7A00]: Base bar NVIDIA CUDA, DOCA, vGPU, Magnum IO (Darker green bar #4A7A00, square corners, thin darker bottom edge.)
- text at x 41.4, y 59.3, w 17.1, h 1.7 [DINPro-Regular, regular weight; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA CUDA, DOCA, vGPU, Magnum IO
- shape at x 27, y 75, w 46, h 25 [#3E5A1E]: Floor reflection of green panel (Faint blurred green reflection on the glossy dark grey floor, about 15% opacity, fading downward.)
- shape at x 0, y 0, w 100, h 100 [#000000]: Full-slide dark backdrop (Black to dark grey gradient with a soft floor sheen.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 27.2, y 40.2, w 45.5, h 23.6: 5464 by 1592 pixels
- image at x 63.8, y 25.9, w 6.1, h 9.0: 202 by 168 pixels
- image at x 40.6, y 58.6, w 18.7, h 2.8: 2249 by 192 pixels
- image at x 30.0, y 26.7, w 6.3, h 8.0: 202 by 145 pixels
- image at x 52.7, y 26.9, w 5.9, h 7.8: 198 by 148 pixels
- image at x 42.5, y 45.5, w 14.9, h 2.5: 1791 by 167 pixels
- image at x 42.6, y 26.4, w 3.4, h 8.0: 108 by 143 pixels
- image at x 33.5, y 52.1, w 4.9, h 2.6: 588 by 177 pixels
- image at x 27.9, y 52.1, w 4.9, h 2.5: 588 by 167 pixels
- image at x 44.7, y 52.2, w 4.9, h 2.4: 588 by 163 pixels
- image at x 56.0, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 61.6, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 39.1, y 52.3, w 4.9, h 2.2: 587 by 149 pixels
- image at x 67.2, y 52.3, w 4.9, h 2.1: 588 by 144 pixels
- image at x 50.4, y 52.3, w 4.9, h 2.1: 588 by 143 pixels
- text at x 45.0, y 7.9, w 10.0, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA AI
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: DATA PREP
- text at x 43.0, y 23.6, w 2.8, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: TRAIN
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: SIMULATE
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: ORCHESTRATE
- text at x 47.0, y 41.1, w 6.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: NVIDIA AI
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU CLOUD REGISTRY
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDF
- text at x 40.0, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDNN
- text at x 46.0, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuML
- text at x 51.0, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TAO
- text at x 62.0, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Triton
- text at x 41.4, y 59.3, w 17.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA CUDA, DOCA, vGPU, Magnum IO

### Slide 55

**Text**

ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
DATA PREP
TRAIN
SIMULATE
ORCHESTRATE
NVIDIA AI
NVIDIA GPU CLOUD REGISTRY
cuIO
cuDF
cuDNN
cuML
cuGraph
TAO
TensorRT
Triton
NVIDIA CUDA, DOCA, vGPU, Magnum IO
VMware vSphere
NVIDIA
CERTIFIED
Atos
DELL Technologies
FUJITSU
GIGABYTE
H3C
hp
inspur
Lenovo
QCT
SUPERMICRO

**Layout**

Single centred diagram on a black studio backdrop: the title sits centred across the top at about 8 percent from the top edge, a four-box process loop with gold connectors occupies the upper-middle band, and a central green stack (NVIDIA AI) is aligned on the same vertical centre line with the blue VMware vSphere bar beneath it. A server chassis image sits at lower left overlapping the stack's bottom-left corner, and the NVIDIA CERTIFIED logo and partner logo grids sit in a row below the blue bar, with the partner grid right-aligned to the stack's right edge. No footer or slide number is visible.

**Visuals**

Diagram. Four rectangular process boxes, each with a dark charcoal fill (#1A1A1A) and a thin light-grey-beige border (#B5A98A, about 0.15 percent of slide width), joined left to right by short gold arrows (#C8A96A) with arrowheads pointing right. A gold outline loop (#C8A96A, about 0.1 percent stroke) leaves the right side of ORCHESTRATE, runs up and across the top above the boxes, and returns down to the left edge of DATA PREP with an arrowhead pointing right into DATA PREP, forming a closed cycle. Box 1 DATA PREP contains a white line-art illustration of grid tables and data-flow nodes connected by diagonal arrows. Box 2 TRAIN contains a white line-art neural network diagram of three columns of nodes with connecting lines. Box 3 SIMULATE contains a white line-art six-axis robot arm on a base inside two elliptical orbit arcs. Box 4 ORCHESTRATE contains a grid of nine white line-art icons: an industrial robot, a delivery truck, a wind turbine, a smartphone, a traffic light, a robot arm, a drone, a factory building and a forklift with cargo. Below the boxes is a large green block (#76B900 top band, #4E8A00 inner bands) containing, from top to bottom: the heading NVIDIA AI, a wide bar NVIDIA GPU CLOUD REGISTRY, a row of eight equal tiles (cuIO, cuDF, cuDNN, cuML, cuGraph, TAO, TensorRT, Triton) each in #5A9E00 with a thin darker bottom edge, and a wide bar NVIDIA CUDA, DOCA, vGPU, Magnum IO. A blue bar (#0A6BC4) sits directly beneath the green block and carries VMware vSphere. Lower left is a photograph of a white 1U server chassis at an angle, lid removed, showing a black circuit board with a small chip, a bronze-brown GPU card with a finned heatsink and grey metal fins, lit from above and front with a soft white highlight; it is cut out on a transparent background with no frame and casts a faint reflection on the floor. Lower centre is the NVIDIA logo (green eye mark with NVIDIA wordmark, #76B900 and white) above a green-outlined box reading CERTIFIED in white. Lower right is a two-row logo grid in white: row 1 Atos, DELL Technologies, FUJITSU, GIGABYTE, H3C in a circle; row 2 hp in a circle, inspur, Lenovo in a white rectangle with black text, QCT with a cloud mark, SUPERMICRO in an oval outline.

**Design**

Background: Black (#000000) studio backdrop fading to dark grey (#2A2A2A) floor with a faint blue-green reflection. Black background with a dark grey floor gradient fading to near-black at the bottom, and a faint blue-green light reflection glowing along the floor under the stack. Title text is white, bold, all capitals, DIN Pro Bold style sans-serif, about 4.1 percent of slide height, with wide letter spacing. Box labels are white DIN Pro Medium capitals at about 1.7 percent of slide height. Tile and bar labels are white DIN Pro Regular at about 1.7 percent. Accent colours: NVIDIA green #76B900, darker green #4E8A00, gold outline #C8A96A, blue #0A6BC4. Shapes are square-cornered with no visible shadows. The title is about 4 percent of slide height, body labels about 1.7 percent.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-slide dark studio backdrop: black upper area fading to a dark grey floor with faint blue-green light reflection and scratch texture at bottom (Full-bleed, no crop, no overlay beyond the gradient, behind all elements)
- title at x 23.3, y 7.9, w 53.3, h 4.1 [DINPro-Bold, all capitals, wide letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
- line at x 27.2, y 20.1, w 45.6, h 8.9: Gold closed loop connector from ORCHESTRATE back to DATA PREP (Thin gold stroke #C8A96A, about 0.1 percent of slide width; runs across top of boxes at about 20.1 percent from top, drops at left to DATA PREP and at right to ORCHESTRATE, with arrowhead pointing right into DATA PREP)
- shape at x 29.6, y 22.7, w 7.2, h 13.3 [#1A1A1A]: DATA PREP process box (Charcoal fill with thin beige-grey border #B5A98A, square corners, contains white line-art data-prep illustration)
- icon at x 30, y 26.7, w 6.3, h 8: Data prep line-art illustration: grid tables and nodes connected by arrows (White line art, thin strokes)
- line at x 37.7, y 28.9, w 3.1, h 0.4 [#C8A96A]: Gold arrow from DATA PREP to TRAIN (Thin gold line with right-pointing arrowhead)
- shape at x 40.8, y 22.7, w 7.2, h 13.3 [#1A1A1A]: TRAIN process box (Charcoal fill with thin beige-grey border #B5A98A, square corners)
- icon at x 42.6, y 26.4, w 3.4, h 8: Neural network line-art diagram: three columns of nodes with connecting lines (White line art)
- line at x 48, y 28.9, w 3.1, h 0.4 [#C8A96A]: Gold arrow from TRAIN to SIMULATE (Thin gold line with right-pointing arrowhead)
- shape at x 52.1, y 22.7, w 7.1, h 13.3 [#1A1A1A]: SIMULATE process box (Charcoal fill with thin beige-grey border #B5A98A, square corners)
- icon at x 52.7, y 26.9, w 5.9, h 7.8: Six-axis robot arm line art inside two elliptical orbit arcs on a base (White line art)
- line at x 59.2, y 28.9, w 3.1, h 0.4 [#C8A96A]: Gold arrow from SIMULATE to ORCHESTRATE (Thin gold line with right-pointing arrowhead)
- shape at x 63.3, y 22.7, w 7.2, h 13.3 [#1A1A1A]: ORCHESTRATE process box (Charcoal fill with thin beige-grey border #B5A98A, square corners)
- icon at x 63.8, y 25.9, w 6.1, h 9: Grid of nine white line-art icons: industrial robot, delivery truck, wind turbine, smartphone, traffic light, robot arm, drone, factory, forklift with cargo (White line art)
- shape at x 27.2, y 40.1, w 45.6, h 23.6 [#76B900]: NVIDIA AI stack block (Green (#76B900) outer block with inner darker green (#4E8A00) bands and tiles; square corners; slight light edge)
- title at x 47, y 41.1, w 6, h 2.5 [DINPro-Medium; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AI
- shape at x 27.9, y 44.3, w 44.4, h 5 [#5A9E00]: NVIDIA GPU CLOUD REGISTRY bar (Darker green bar, square corners, thin darker bottom edge)
- body at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU CLOUD REGISTRY
- shape at x 27.9, y 52.1, w 4.9, h 6 [#5A9E00]: cuIO tile (Square-cornered tile with darker bottom edge)
- body at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuIO
- shape at x 33.5, y 52.1, w 4.9, h 6 [#5A9E00]: cuDF tile (Square-cornered tile with darker bottom edge)
- body at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDF
- shape at x 39.1, y 52.1, w 4.9, h 6 [#5A9E00]: cuDNN tile (Square-cornered tile with darker bottom edge)
- body at x 40, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDNN
- shape at x 44.7, y 52.1, w 4.9, h 6 [#5A9E00]: cuML tile (Square-cornered tile with darker bottom edge)
- body at x 46, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuML
- shape at x 50.4, y 52.1, w 4.9, h 6 [#5A9E00]: cuGraph tile (Square-cornered tile with darker bottom edge)
- body at x 51, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuGraph
- shape at x 56, y 52.1, w 4.9, h 6 [#5A9E00]: TAO tile (Square-cornered tile with darker bottom edge)
- body at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: TAO
- shape at x 61.6, y 52.1, w 4.9, h 6 [#5A9E00]: TensorRT tile (Square-cornered tile with darker bottom edge)
- body at x 62, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: TensorRT
- shape at x 67.2, y 52.1, w 4.9, h 6 [#5A9E00]: Triton tile (Square-cornered tile with darker bottom edge)
- body at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Triton
- shape at x 27.9, y 57.6, w 44.4, h 5 [#5A9E00]: NVIDIA CUDA, DOCA, vGPU, Magnum IO bar (Darker green bar, square corners, thin darker bottom edge)
- body at x 41.4, y 59.3, w 17.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA CUDA, DOCA, vGPU, Magnum IO
- shape at x 27.2, y 65.2, w 45.6, h 4.9 [#0A6BC4]: VMware vSphere bar (Blue bar, square corners, directly beneath the green block)
- body at x 46.4, y 66.7, w 7.2, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: VMware vSphere
- photo at x 18.5, y 58.7, w 18.7, h 22.5: Photograph of a white 1U server chassis at an angle with lid removed, showing a black circuit board with a small chip, a bronze-brown GPU card with finned heatsink, and grey metal fins; lit from above and front with soft white highlight; cut out with no frame, casting a faint reflection on the floor, overlapping the lower-left corner of the green stack (No crop frame, transparent cut-out, overlaps the green block and blue bar edge)
- logo at x 38.4, y 71.6, w 6.5, h 2.6 [#76B900]: NVIDIA logo: green eye mark with NVIDIA wordmark (Green (#76B900) and white)
- logo at x 38.7, y 74.6, w 6.5, h 3 [#000000]: NVIDIA CERTIFIED badge: CERTIFIED in white capitals inside a thin white-outlined rectangle (White outline about 0.1 percent of slide width, black fill, square corners)
- logo at x 51.5, y 71.9, w 3.6, h 1.2 [#FFFFFF]: Atos logo (White wordmark)
- logo at x 55, y 71.9, w 5.4, h 1.2 [#FFFFFF]: DELL Technologies logo (White wordmark)
- logo at x 62, y 71.8, w 2.6, h 1.2 [#FFFFFF]: FUJITSU logo (White wordmark)
- logo at x 78, y 71.8, w 3.4, h 1.2 [#FFFFFF]: GIGABYTE logo (White wordmark)
- logo at x 70.6, y 71.8, w 1.4, h 2.2 [#FFFFFF]: H3C logo (White wordmark inside a white circle with black text)
- logo at x 51.5, y 74.8, w 1.4, h 2.4 [#FFFFFF]: hp logo (Lowercase hp mark inside a white circle)
- logo at x 55.5, y 75.6, w 2.2, h 1.1 [#FFFFFF]: inspur logo (White italic wordmark)
- logo at x 60.4, y 75.4, w 2.4, h 1 [#FFFFFF]: Lenovo logo (White rectangle with black Lenovo wordmark)
- logo at x 65.3, y 74.4, w 1.6, h 3.3 [#FFFFFF]: QCT logo: cloud mark above QCT letters (White line cloud with letters)
- logo at x 69.6, y 74.8, w 2.5, h 2.3 [#FFFFFF]: SUPERMICRO logo (White wordmark inside a white oval outline)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 27.2, y 40.2, w 45.5, h 23.6: 5464 by 1592 pixels
- image at x 27.2, y 40.2, w 45.5, h 23.6: 683 by 199 pixels
- image at x 37.3, y 69.7, w 9.2, h 9.6: 647 by 381 pixels
- image at x 63.8, y 25.9, w 6.1, h 9.0: 202 by 168 pixels
- image at x 40.6, y 58.6, w 18.7, h 2.8: 2249 by 192 pixels
- image at x 30.0, y 26.7, w 6.3, h 8.0: 202 by 145 pixels
- image at x 52.7, y 26.9, w 5.9, h 7.8: 198 by 148 pixels
- image at x 44.3, y 65.8, w 11.4, h 3.3: 1372 by 222 pixels
- image at x 42.5, y 45.5, w 14.9, h 2.5: 1791 by 167 pixels
- image at x 42.6, y 26.4, w 3.4, h 8.0: 108 by 143 pixels
- image at x 33.5, y 52.1, w 4.9, h 2.6: 588 by 177 pixels
- image at x 27.9, y 52.1, w 4.9, h 2.5: 588 by 167 pixels
- image at x 44.7, y 52.2, w 4.9, h 2.4: 588 by 163 pixels
- image at x 56.0, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 61.6, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 39.1, y 52.3, w 4.9, h 2.2: 587 by 149 pixels
- image at x 67.2, y 52.3, w 4.9, h 2.1: 588 by 144 pixels
- image at x 50.4, y 52.3, w 4.9, h 2.1: 588 by 143 pixels
- image at x 55.1, y 72.1, w 5.2, h 1.2: 314 by 41 pixels
- image at x 65.3, y 73.8, w 1.7, h 3.6: 204 by 245 pixels
- image at x 69.6, y 74.8, w 2.5, h 2.3: 153 by 78 pixels
- text at x 23.3, y 7.9, w 53.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: DATA PREP
- text at x 43.0, y 23.6, w 2.8, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: TRAIN
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: SIMULATE
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: ORCHESTRATE
- text at x 47.0, y 41.1, w 6.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: NVIDIA AI
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU CLOUD REGISTRY
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDF
- text at x 40.0, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDNN
- text at x 46.0, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuML
- text at x 51.0, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TAO
- text at x 62.0, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Triton
- text at x 41.4, y 59.3, w 17.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA CUDA, DOCA, vGPU, Magnum IO
- text at x 46.4, y 66.7, w 7.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VMware vSphere

### Slide 56

**Text**

ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
DATA PREP
TRAIN
SIMULATE
ORCHESTRATE
NVIDIA AI
NVIDIA GPU CLOUD REGISTRY
cuIO
cuDF
cuDNN
cuML
cuGraph
TAO
TensorRT
Triton
NVIDIA CUDA, DOCA, vGPU, Magnum IO
VMware vSphere
NVIDIA CERTIFIED
Atos Dell Technologies FUJITSU GIGABYTE H3C
hp inspur Lenovo QCT SUPERMICRO
NVIDIA BlueField-2
NVIDIA A100/A30
NVIDIA A40/A10

**Layout**

Centered single-column composition on a black field: the title sits centred across the top at about 8 percent from the top edge, and a four-box process row sits beneath it, followed by a stacked platform diagram centred on the slide with the hardware photo and three circular product inserts anchored at the lower left. Partner logos and the NVIDIA Certified badge sit on the lower right of the stack in two rows aligned to its edges. No footer, page number or source line is visible.

**Visuals**

Full-slide photographic backdrop of a dark studio floor with soft green and blue reflections. A thin gold-outlined loop connector runs from the right end of the ORCHESTRATE box, up above the four boxes, and back to the left end of the DATA PREP box, with small gold arrowheads at each end and between the boxes. Four process boxes, each a dark charcoal square with a light gray outline, contain white line-art icons: DATA PREP shows small stacked data tables connected by lines to a bar-style table grid; TRAIN shows a neural network diagram of three layers of nodes; SIMULATE shows a robot arm over an elliptical motion path; ORCHESTRATE shows a grid of nine small line icons (a robot arm, a truck, a wind turbine, a phone, traffic lights, another robot arm, a workstation, a factory and a forklift). Below is a green stacked diagram: a bright green #76B900 outer block labelled NVIDIA AI, containing a darker green bar labelled NVIDIA GPU CLOUD REGISTRY, a row of eight darker green tiles labelled cuIO, cuDF, cuDNN, cuML, cuGraph, TAO, TensorRT and Triton, and a darker green bar labelled NVIDIA CUDA, DOCA, vGPU, Magnum IO. Beneath it, a blue #0A6FC2 bar labelled VMware vSphere spans the same width. A photograph of a white server tray tilted at an angle, shown with its lid open, sits at the lower left of the stack, overlapping its left edge; it contains a black BlueField card and a gold-coloured GPU card, lit softly from above on a dark background, and it is boxed without a border. Three circular inserts with dark rims are arranged in a row at the lower left: the first, labelled NVIDIA BlueField-2, shows a black network card with a green chip; the second, labelled NVIDIA A100/A30, and the third, labelled NVIDIA A40/A10, each show a gold-brown GPU card on a dark background. The NVIDIA logo in green and white with the word CERTIFIED in a white outlined badge sits at the lower centre. Partner logos at the lower right: row one shows Atos, Dell Technologies, FUJITSU, GIGABYTE and H3C in white; row two shows hp, inspur, Lenovo, QCT (cloud icon) and SUPERMICRO in white.

**Design**

Background: Black #000000 backdrop fading to dark charcoal #1E1E1E at the floor, with faint green and blue reflections, full-bleed photograph.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed studio backdrop photograph: dark floor with soft green and blue reflections, covering the entire slide (Two stacked full-cover images at 3840 by 2160 pixels; no cropping or overlay visible beyond the image itself)
- line at x 27.2, y 20.1, w 45.7, h 9.1 [#B8925A]: Gold loop connector from ORCHESTRATE back to DATA PREP, with arrowheads (Thin 1 pt gold stroke, square corners, runs above the four boxes and down each end to arrowheads at the box edges)
- shape at x 29.6, y 22.6, w 7.2, h 13.3 [#1A1A1A]: DATA PREP process box with white line-art icon (Charcoal fill with 1 pt light gray outline, square corners, no shadow; icon of stacked tables linked to a bar table grid)
- shape at x 40.8, y 22.6, w 7.2, h 13.3 [#1A1A1A]: TRAIN process box with white line-art icon (Charcoal fill with 1 pt light gray outline, square corners, no shadow; icon of neural network nodes)
- shape at x 52, y 22.6, w 7.2, h 13.3 [#1A1A1A]: SIMULATE process box with white line-art icon (Charcoal fill with 1 pt light gray outline, square corners, no shadow; icon of robot arm over elliptical path)
- shape at x 63.2, y 22.6, w 7.2, h 13.3 [#1A1A1A]: ORCHESTRATE process box with white line-art icon (Charcoal fill with 1 pt light gray outline, square corners, no shadow; icon grid of nine small line icons)
- icon at x 29.9, y 25.9, w 6.4, h 9.5 [#FFFFFF]: DATA PREP icon: stacked tables linked to bar table grid, white line art (Thin white strokes on charcoal)
- icon at x 40.9, y 25.9, w 5.4, h 9.5 [#FFFFFF]: TRAIN icon: neural network diagram, white line art (Thin white strokes with circular nodes)
- icon at x 52.8, y 26.5, w 6, h 8.4 [#FFFFFF]: SIMULATE icon: robot arm over elliptical motion path, white line art (Thin white strokes)
- icon at x 63.5, y 25.8, w 6.6, h 9.6 [#FFFFFF]: ORCHESTRATE icon grid: robot arm, truck, wind turbine, phone, traffic lights, robot arm, workstation, factory, forklift, white line art (Nine icons in a three by three grid)
- line at x 37.8, y 28.8, w 2.4, h 0.5 [#B8925A]: Gold arrows between process boxes (Thin gold line with small arrowhead, one between each adjacent pair of boxes)
- shape at x 27.2, y 40.2, w 45.5, h 23.6 [#76B900]: NVIDIA AI outer block, bright green stack (Flat fill, square corners, no shadow; contains the platform tiers below)
- shape at x 27.8, y 44.3, w 44.2, h 4.9 [#4A8A00]: NVIDIA GPU CLOUD REGISTRY bar (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 27.8, y 50, w 5.2, h 6.8 [#4A8A00]: cuIO tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 33.4, y 50, w 5.2, h 6.8 [#4A8A00]: cuDF tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 39, y 50, w 5.2, h 6.8 [#4A8A00]: cuDNN tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 44.6, y 50, w 5.2, h 6.8 [#4A8A00]: cuML tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 50.2, y 50, w 5.2, h 6.8 [#4A8A00]: cuGraph tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 55.8, y 50, w 5.2, h 6.8 [#4A8A00]: TAO tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 61.4, y 50, w 5.2, h 6.8 [#4A8A00]: TensorRT tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 67, y 50, w 5.2, h 6.8 [#4A8A00]: Triton tile (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 27.8, y 57.5, w 44.2, h 4.9 [#4A8A00]: NVIDIA CUDA, DOCA, vGPU, Magnum IO bar (Darker green fill, square corners, thin bottom edge shadow)
- shape at x 27.2, y 65.2, w 45.5, h 4.9 [#0A6FC2]: VMware vSphere bar (Blue fill, square corners, no shadow)
- photo at x 18.5, y 58.7, w 18.5, h 21.3 [#FFFFFF]: Server tray photograph: white chassis tilted open, containing a black BlueField card and a gold GPU card (Boxed, not cropped, soft top lighting on a dark background; overlaps the left edge of the NVIDIA AI block and the VMware bar)
- text at x 23.3, y 7.9, w 53.3, h 4.1 [DIN Pro Bold, sans-serif, uppercase, bold; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DIN Pro Medium, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: DATA PREP
- text at x 43, y 23.6, w 2.8, h 1.7 [DIN Pro Medium, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: TRAIN
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DIN Pro Medium, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: SIMULATE
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DIN Pro Medium, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: ORCHESTRATE
- text at x 47, y 41.1, w 6, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AI
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DIN Pro Regular, sans-serif, uppercase; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU CLOUD REGISTRY
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDF
- text at x 40, y 52.6, w 3.1, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDNN
- text at x 46, y 52.6, w 2.4, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuML
- text at x 51, y 52.6, w 3.6, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: TAO
- text at x 62, y 52.6, w 4.1, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: Triton
- text at x 41.4, y 59.3, w 17.1, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA CUDA, DOCA, vGPU, Magnum IO
- text at x 46.4, y 66.7, w 7.2, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: VMware vSphere
- logo at x 38.4, y 71.6, w 6.5, h 2.4 [#76B900]: NVIDIA logo: green eye mark with NVIDIA wordmark (Green and white on black)
- logo at x 38.9, y 74.5, w 6.5, h 2.9 [DIN Pro Bold, sans-serif, uppercase; #FFFFFF; center aligned]: NVIDIA CERTIFIED badge: word CERTIFIED in white outlined rectangle (White 1 pt outline, square corners)
- logo at x 51.7, y 72, w 3.6, h 1.5 [#FFFFFF]: Atos logo (White wordmark)
- logo at x 55, y 72, w 5.3, h 1.5 [#FFFFFF]: Dell Technologies logo (White wordmark)
- logo at x 62, y 72, w 3.2, h 1.5 [#FFFFFF]: FUJITSU logo (White wordmark)
- logo at x 65.8, y 72, w 4.7, h 1.5 [#FFFFFF]: GIGABYTE logo (White wordmark)
- logo at x 70.8, y 71.6, w 1.4, h 2.2 [#FFFFFF]: H3C logo (White circle with dark wordmark)
- logo at x 51.7, y 75, w 1.4, h 2.2 [#FFFFFF]: hp logo (White hp mark)
- logo at x 55.6, y 75, w 2.2, h 1.5 [#FFFFFF]: inspur logo (White italic wordmark)
- logo at x 60.4, y 75, w 2.4, h 1.5 [#FFFFFF]: Lenovo logo (White box with dark wordmark)
- logo at x 65.3, y 74.8, w 2.2, h 2.5 [#FFFFFF]: QCT logo: cloud icon with QCT wordmark (White line cloud over QCT text)
- logo at x 69.5, y 75, w 2.6, h 1.8 [#FFFFFF]: SUPERMICRO logo (White oval outline with wordmark)
- photo at x 7.8, y 78.2, w 8.2, h 14.5 [#1A1A1A]: Circular insert: NVIDIA BlueField-2 network card with green chip (Circular crop with dark gold-edged rim, black background)
- photo at x 17.5, y 78.2, w 8.2, h 14.5 [#B09060]: Circular insert: NVIDIA A100/A30 gold-brown GPU card (Circular crop with dark gold-edged rim)
- photo at x 27.2, y 78.2, w 8.2, h 14.5 [#B09060]: Circular insert: NVIDIA A40/A10 gold-brown GPU card (Circular crop with dark gold-edged rim)
- text at x 9.7, y 87.8, w 4.3, h 3.3 [DIN Pro Regular, sans-serif; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / BlueField-2 (Two lines)
- text at x 19.8, y 87.8, w 3.5, h 3.3 [DIN Pro Regular, sans-serif; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / A100/A30 (Two lines)
- text at x 29.7, y 87.8, w 3, h 3.3 [DIN Pro Regular, sans-serif; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / A40/A10 (Two lines)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 27.2, y 40.2, w 45.5, h 23.6: 342 by 100 pixels
- image at x 37.3, y 69.7, w 9.2, h 9.6: 647 by 381 pixels
- image at x 63.8, y 25.9, w 6.1, h 9.0: 202 by 168 pixels
- image at x 40.6, y 58.6, w 18.7, h 2.8: 2249 by 192 pixels
- image at x 30.0, y 26.7, w 6.3, h 8.0: 202 by 145 pixels
- image at x 52.7, y 26.9, w 5.9, h 7.8: 198 by 148 pixels
- image at x 44.3, y 65.8, w 11.4, h 3.3: 1372 by 222 pixels
- image at x 42.5, y 45.5, w 14.9, h 2.5: 1791 by 167 pixels
- image at x 42.6, y 26.4, w 3.4, h 8.0: 108 by 143 pixels
- image at x 33.5, y 52.1, w 4.9, h 2.6: 588 by 177 pixels
- image at x 27.9, y 52.1, w 4.9, h 2.5: 588 by 167 pixels
- image at x 44.7, y 52.2, w 4.9, h 2.4: 588 by 163 pixels
- image at x 56.0, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 61.6, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 39.1, y 52.3, w 4.9, h 2.2: 587 by 149 pixels
- image at x 67.2, y 52.3, w 4.9, h 2.1: 588 by 144 pixels
- image at x 50.4, y 52.3, w 4.9, h 2.1: 588 by 143 pixels
- image at x 55.1, y 72.1, w 5.2, h 1.2: 627 by 82 pixels
- image at x 65.3, y 73.8, w 1.7, h 3.6: 204 by 245 pixels
- image at x 69.6, y 74.8, w 2.5, h 2.3: 305 by 155 pixels
- text at x 23.3, y 7.9, w 53.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: DATA PREP
- text at x 43.0, y 23.6, w 2.8, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: TRAIN
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: SIMULATE
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: ORCHESTRATE
- text at x 47.0, y 41.1, w 6.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: NVIDIA AI
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU CLOUD REGISTRY
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDF
- text at x 40.0, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDNN
- text at x 46.0, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuML
- text at x 51.0, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TAO
- text at x 62.0, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Triton
- text at x 41.4, y 59.3, w 17.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA CUDA, DOCA, vGPU, Magnum IO
- text at x 46.4, y 66.7, w 7.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VMware vSphere
- text at x 10.6, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 20.3, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 29.9, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 9.7, y 89.6, w 4.3, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: BlueField-2
- text at x 19.8, y 89.6, w 3.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A100/A30
- text at x 29.7, y 89.6, w 3.0, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A40/A10

### Slide 57

**Text**

ANNOUNCING NVIDIA AERIAL A100
AI-on-5G
ERICSSON
FUJITSU
MAVENIR
Capgemini
Radisys
NVIDIA AERIAL
5G CORE
IPSEC/TLS
DPI
ASAP2 Acceleration
5G RAN
5T FOR 5G
GPU Direct
cuVNF
cuPHY
NVIDIA AERIAL
A100
NVIDIA
BlueField-2
NVIDIA
A100/A30
NVIDIA
A40/A10
chnologies
FUJITSU
GIGABYTE
H3C
Lenovo
QCT
SUPERMICRO

**Layout**

Centred composition on a black stage: the title and subtitle sit centred at the top, then a stacked diagram of a partner panel, a green NVIDIA AERIAL block and a blue bar, with three small product circles and one large product circle standing in front along the lower left and centre. No visible footer, slide number or margins beyond the stage; the content column spans about 27% to 73% of the slide width.

**Visuals**

Diagram and product imagery. (1) A dark partner panel with a thin light outline holding five white partner logos in one row: Ericsson, Fujitsu, Mavenir, Capgemini and Radisys. (2) A stacked architecture diagram: a green (#6CB600) NVIDIA AERIAL block with a title 'NVIDIA AERIAL' and two labelled tiers; the upper tier, labelled '5G CORE', has three darker green (#4D8A00) boxes 'IPSEC/TLS', 'DPI' and 'ASAP2 Acceleration'; the lower tier, labelled '5G RAN', has four darker green boxes '5T FOR 5G', 'GPU Direct', 'cuVNF' and 'cuPHY'. A blue (#0A6CC0) bar sits beneath the green block, partly covered by the product circles. (3) A white server tray (3D render, about 45 degrees, open lid, showing a green-black NVIDIA card and a gold-bronze GPU card) at upper left of the product group. (4) Four circular close-up photographs in a row: a large one centre-right of the green block showing an NVIDIA AERIAL A100 card (black PCB, silver heatsinks, NVIDIA logo on the GPU) with the caption 'NVIDIA AERIAL / A100' in white over its lower part; three small circles at lower left showing NVIDIA BlueField-2 (black card with chip), NVIDIA A100/A30 (gold-bronze passive card) and NVIDIA A40/A10 (gold-bronze card), each with a two-line white caption. Lighting is a dark studio spotlight; dominant colours are black, grey, bronze and white with green and blue accents. The circles are cropped to round masks with thin bronze-gold rims. (5) A row of partner logos in white and grey partly hidden behind the blue bar at lower right: a partially hidden word ending 'chnologies', FUJITSU, GIGABYTE, H3C in a white circle, Lenovo in a white rectangle, QCT with a cloud icon, and SUPERMICRO in an outlined oval.

**Design**

Background: Full-bleed dark rendered studio backdrop: black #000000 at top fading to dark grey #2A2A2A on the floor, with faint green and blue reflections near the bottom edge. Black stage background that fades to dark grey on the floor, with faint green and blue reflections at the bottom. Title text is white (#FFFFFF) DIN Pro Bold, all caps, about 4.1% of slide height; subtitle 'AI-on-5G' is white DIN Pro Regular, about 2.7%. Diagram labels are white DIN Pro Regular or Medium at about 1.5% to 2.7% of slide height. Accents are NVIDIA green #6CB600 and darker green #4D8A00, blue bar #0A6CC0, bronze rims on circles. Shapes are square-cornered with no shadows or gradients except the stage lighting. Panel outline is a thin light beige stroke (#C8BFA8).

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio backdrop render with floor reflection (Covers the whole slide; black top fading to dark grey floor; faint green and blue light at bottom centre.)
- shape at x 27.1, y 20, w 45.8, h 16 [#111111]: Partner panel: dark rectangle holding partner logos (Square corners; thin light beige outline (#C8BFA8, about 1 px); faint green line along bottom edge.)
- shape at x 27.1, y 40, w 45.8, h 23.6 [#6CB600]: NVIDIA AERIAL green block with tiers (Square corners; no shadow; sits behind all chips and labels.)
- shape at x 27.1, y 65, w 45.8, h 5 [#0A6CC0]: Blue bar beneath green block (Square corners; partly covered by the large product circle and logo strip.)
- shape at x 27.6, y 44.4, w 14.5, h 7.2 [#4D8A00]: Chip box IPSEC/TLS (Square corners; slight darker bottom edge.)
- shape at x 42.8, y 44.4, w 14.5, h 7.2 [#4D8A00]: Chip box DPI (Square corners; slight darker bottom edge.)
- shape at x 57.7, y 44.4, w 14.5, h 7.2 [#4D8A00]: Chip box ASAP2 Acceleration (Square corners; slight darker bottom edge.)
- shape at x 27.8, y 55.2, w 10.7, h 7.5 [#4D8A00]: Chip box 5T FOR 5G (Square corners; slight darker bottom edge.)
- shape at x 39, y 55.2, w 10.7, h 7.5 [#4D8A00]: Chip box GPU Direct (Square corners; slight darker bottom edge.)
- shape at x 50.2, y 55.2, w 10.7, h 7.5 [#4D8A00]: Chip box cuVNF (Square corners; slight darker bottom edge.)
- shape at x 61.4, y 55.2, w 10.7, h 7.5 [#4D8A00]: Chip box cuPHY (Square corners; slight darker bottom edge.)
- photo at x 18.5, y 58.7, w 18.5, h 19.6 [#F2F2F2]: 3D render of open white server tray with NVIDIA cards (Angled about 45 degrees, lid open; shows a green-black NVIDIA card and a gold-bronze GPU card; sits behind the large circle; no crop or mask.)
- photo at x 7.8, y 78.2, w 8.2, h 14.6: Circular close-up of NVIDIA BlueField-2 card (Round mask with thin bronze-gold rim; black card with chip; dark shadow beneath.)
- photo at x 17.4, y 78.2, w 8.2, h 14.6: Circular close-up of NVIDIA A100/A30 card (Round mask with thin bronze-gold rim; gold-bronze passive card; dark background.)
- photo at x 27.1, y 78.2, w 8.2, h 14.6: Circular close-up of NVIDIA A40/A10 card (Round mask with thin bronze-gold rim; gold-bronze passive card; dark background.)
- photo at x 38.3, y 59.8, w 19.5, h 34.3: Large circular close-up of NVIDIA AERIAL A100 card (Round mask with thin bronze-gold rim; black PCB, silver heatsinks and connectors; NVIDIA logo on the central GPU; overlaps the green block and blue bar.)
- logo at x 29.3, y 26.4, w 8.2, h 3 [#FFFFFF]: Ericsson logo (wordmark with three-stripe symbol)
- logo at x 39.6, y 25.6, w 5.3, h 4.4 [#FFFFFF]: Fujitsu logo (wordmark with small emblem above)
- logo at x 47.1, y 26.7, w 6.7, h 2.3 [#FFFFFF]: Mavenir logo (wordmark with swoosh)
- logo at x 56, y 26.5, w 7.2, h 2.7 [#FFFFFF]: Capgemini logo (wordmark with ball symbol)
- logo at x 65.2, y 26.8, w 5.7, h 2.6 [#FFFFFF]: Radisys logo (wordmark with R symbol)
- logo at x 57.3, y 71.6, w 3.1, h 1.2 [#FFFFFF]: Partially hidden partner wordmark ending 'chnologies' (Partly covered by the large circle.)
- logo at x 62, y 71.8, w 2.1, h 1.6 [#FFFFFF]: FUJITSU wordmark with emblem
- logo at x 65.8, y 72.3, w 3.2, h 1 [#FFFFFF]: GIGABYTE wordmark
- logo at x 70.8, y 71.6, w 1.4, h 2.2 [#FFFFFF]: H3C logo in white circle
- logo at x 60.4, y 75.3, w 2.4, h 1.3 [#FFFFFF]: Lenovo logo in white rectangle
- logo at x 65.4, y 74.8, w 1.5, h 3 [#FFFFFF]: QCT logo with cloud icon
- logo at x 69.5, y 74.6, w 2.7, h 2.5 [#FFFFFF]: SUPERMICRO logo in outlined oval
- text at x 31.7, y 7.9, w 36.5, h 4.1 [DIN Pro Bold, sans-serif, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA AERIAL A100
- text at x 46.9, y 12.5, w 6.1, h 2.7 [DIN Pro Regular, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: AI-on-5G
- text at x 45.3, y 41.1, w 9.4, h 2.5 [DIN Pro Medium, sans-serif, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AERIAL
- text at x 67.2, y 42.1, w 3.8, h 1.7 [DIN Pro Regular, sans-serif, all caps; font size 1.73% of slide height; #FFFFFF; right aligned]: 5G CORE
- text at x 32.8, y 47.4, w 4.7, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: IPSEC/TLS
- text at x 49.2, y 47.4, w 1.5, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: DPI
- text at x 60.7, y 47.4, w 8.5, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: ASAP2 Acceleration
- text at x 67.8, y 52.9, w 3.3, h 1.7 [DIN Pro Regular, sans-serif, all caps; font size 1.73% of slide height; #FFFFFF; right aligned]: 5G RAN
- text at x 31.4, y 58, w 4.5, h 1.7 [DIN Pro Regular, sans-serif, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: 5T FOR 5G
- text at x 42, y 58, w 4.7, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: GPU Direct
- text at x 54.2, y 58, w 2.8, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuVNF
- text at x 65.4, y 58, w 2.8, h 1.7 [DIN Pro Regular, sans-serif; font size 1.73% of slide height; #FFFFFF; center aligned]: cuPHY
- text at x 42.8, y 85.4, w 10.7, h 2.7 [DIN Pro Medium, sans-serif, all caps; font size 2.72% of slide height; #FFFFFF; center aligned]: NVIDIA AERIAL (Overlaid on the large circle photo.)
- text at x 46.3, y 88.6, w 3.4, h 2.7 [DIN Pro Medium, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: A100 (Second line of the caption on the large circle.)
- text at x 9.7, y 87.8, w 4.3, h 3 [DIN Pro Regular, sans-serif; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / BlueField-2 (Two lines: NVIDIA at x 10.6, BlueField-2 at x 9.7; line spacing about 1.8%.)
- text at x 19.8, y 87.8, w 3.5, h 3 [DIN Pro Regular, sans-serif; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / A100/A30 (Two lines: NVIDIA at x 20.3, A100/A30 at x 19.8.)
- text at x 29.7, y 87.8, w 3, h 3 [DIN Pro Regular, sans-serif; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / A40/A10 (Two lines: NVIDIA at x 29.9, A40/A10 at x 29.7.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 64.9, y 25.4, w 6.1, h 5.7: 218 by 114 pixels
- image at x 29.3, y 26.4, w 8.2, h 3.0: 986 by 200 pixels
- image at x 39.6, y 25.6, w 5.3, h 4.4: 191 by 90 pixels
- image at x 47.1, y 26.7, w 6.7, h 2.3: 400 by 77 pixels
- image at x 65.3, y 73.8, w 1.7, h 3.6: 204 by 245 pixels
- image at x 69.6, y 74.8, w 2.5, h 2.3: 305 by 155 pixels
- text at x 31.7, y 7.9, w 36.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA AERIAL A100
- text at x 46.9, y 12.5, w 6.1, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: AI-on-5G
- text at x 45.3, y 41.1, w 9.4, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: NVIDIA AERIAL
- text at x 67.2, y 42.1, w 3.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5G CORE
- text at x 32.8, y 47.4, w 4.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: IPSEC/TLS
- text at x 49.2, y 47.4, w 1.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: DPI
- text at x 60.7, y 47.4, w 8.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ASAP2 Acceleration
- text at x 67.8, y 52.9, w 3.3, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5G RAN
- text at x 42.8, y 85.4, w 10.7, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: NVIDIA AERIAL
- text at x 46.3, y 88.6, w 3.4, h 2.7 [DINPro-Medium; font size 2.72; #FFFFFF]: A100
- text at x 31.4, y 58.0, w 4.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: 5T FOR 5G
- text at x 42.0, y 58.0, w 4.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: GPU Direct
- text at x 54.2, y 58.0, w 2.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuVNF
- text at x 65.4, y 58.0, w 2.8, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuPHY
- text at x 10.6, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 20.3, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 29.9, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 9.7, y 89.6, w 4.3, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: BlueField-2
- text at x 19.8, y 89.6, w 3.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A100/A30
- text at x 29.7, y 89.6, w 3.0, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A40/A10

### Slide 58

**Text**

ANNOUNCING
GOOGLE CLOUD AND NVIDIA
PARTNER TO DELIVER AI-ON-5G
Anthos-Enabled 5G Edge to Deliver Low-Latency,
Secure and Mission-Critical Edge AI Applications
Enables the Rapid Delivery of New Services and
Applications at the 5G Edge
Provides a Consistent Platform for Application
Deployments from Cloud to the Edge

**Layout**

Text block is left-aligned on the left half of the slide, starting at about 6.7% from the left edge and vertically centred around the middle of the slide (title block starts at about 33.7% from top). The Google Cloud logo sits on the right half, vertically centred near the title block, at about 51.8% from the left. No title bar, footer, slide number or page number is visible; the layout has no grid beyond the two-column split.

**Visuals**

One photographic or textured background image covering the full slide, dark charcoal fading from near-black at the top to a lighter grey (about #3A3A3A) at the bottom with faint brushed-surface streaks. One logo: the Google Cloud wordmark in white, shown as a single line 'Google Cloud' with the 'Google' lettering in a geometric sans-serif and 'Cloud' in the same style, occupying about x 51.8%, y 40.2%, w 38.3%, h 19.6%. No charts, tables, or diagrams.

**Design**

Background: Full-bleed dark charcoal gradient image: black (#000000) at top fading to dark grey (about #3A3A3A) at bottom, with faint brushed texture. Black background (#000000) at the top shading to dark grey at the bottom. All text is white (#FFFFFF). Title is set in DIN Pro Regular in capitals; 'ANNOUNCING' is DIN Pro Bold in capitals. Body copy is DIN Pro Regular in sentence case. Title text is about 4.1% of slide height; body text about 2.2%; 'ANNOUNCING' about 3.0%. Lines are left-aligned with no bullets, no shapes, no borders, no shadows and no corner radii. Accent colour: none; the palette is monochrome.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark textured background image with gradient from black to dark grey (Covers the entire slide; image 3840 by 2160 pixels; no overlay, no crop; bottom of image lightens to about #3A3A3A.)
- logo at x 51.8, y 40.2, w 38.3, h 19.6 [#FFFFFF]: Google Cloud logo wordmark, white (Image 1920 by 553 pixels; placed on the right half of the slide; no border or background box.)
- title at x 6.7, y 33.7, w 10.6, h 3 [DIN Pro Bold, capitals, normal letter-spacing; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING (Line above the main title; single line.)
- title at x 6.7, y 36.9, w 33.5, h 8.5 [DIN Pro Regular, capitals, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; left aligned]: GOOGLE CLOUD AND NVIDIA / PARTNER TO DELIVER AI-ON-5G (Two lines: first line at y 36.9%, second line at y 41.3%; line spacing about 4.4% of slide height.)
- body at x 6.7, y 47.9, w 27.5, h 4.6 [DIN Pro Regular, sentence case, normal weight; font size 2.22% of slide height; #FFFFFF; left aligned]: Anthos-Enabled 5G Edge to Deliver Low-Latency, / Secure and Mission-Critical Edge AI Applications (Two lines with tight line spacing; paragraph gap before next block.)
- body at x 6.7, y 55.1, w 26.7, h 4.6 [DIN Pro Regular, sentence case, normal weight; font size 2.22% of slide height; #FFFFFF; left aligned]: Enables the Rapid Delivery of New Services and / Applications at the 5G Edge (Two lines with tight line spacing; separated from the block above by a blank line.)
- body at x 6.7, y 62.3, w 25.9, h 4.6 [DIN Pro Regular, sentence case, normal weight; font size 2.22% of slide height; #FFFFFF; left aligned]: Provides a Consistent Platform for Application / Deployments from Cloud to the Edge (Two lines with tight line spacing; separated from the block above by a blank line; no bullets.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 51.8, y 40.2, w 38.3, h 19.6: 1920 by 553 pixels
- text at x 6.7, y 36.9, w 30.1, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: GOOGLE CLOUD AND NVIDIA
- text at x 6.7, y 41.3, w 33.5, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: PARTNER TO DELIVER AI-ON-5G
- text at x 6.7, y 33.7, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 47.9, w 27.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Anthos-Enabled 5G Edge to Deliver Low-Latency,
- text at x 6.7, y 50.3, w 27.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Secure and Mission-Critical Edge AI Applications
- text at x 6.7, y 55.1, w 26.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Enables the Rapid Delivery of New Services and
- text at x 6.7, y 57.5, w 15.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Applications at the 5G Edge
- text at x 6.7, y 62.3, w 25.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Provides a Consistent Platform for Application
- text at x 6.7, y 64.7, w 20.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Deployments from Cloud to the Edge

### Slide 59

**Review notes**

- What would change the score: I would split or simplify the dense panels (slides 5, 6, 33, 59) and cut the repeated DGX SuperPOD backdrop clutter behind the text-heavy announcement slides.

**Text**

EVERY USER AND WORKLOAD OF A DATA CENTER IS A SECURITY THREAT

**Layout**

A single centred headline sits near the top of the slide, with a centred diagram block of a cloud, four rows of outlined boxes and connecting arrows below it. The diagram is centred horizontally and the lower part of the slide is an empty dark floor with a faint reflection. There is no footer, logo or slide number.

**Visuals**

A line diagram in thin gold strokes. A cloud outline sits at the top centre (about x 42.4%, y 21.3%, w 8.8%, h 9.9%), with a bundle of four vertical double-headed arrows beneath it (about x 45.2%, y 33.3%, w 3.2%, h 4.4%) pointing to the top row of boxes. The grid has four rows of square outlined boxes, each about 6.4% wide and 5.7% high, with no labels inside the boxes. Row 1 (y about 40.1%) has four boxes at x about 35.6%, 41.9%, 48.4% and 54.8%, joined by horizontal double-headed arrows. Row 2 (y about 49.3%) has two boxes at x about 35.6% and 41.9%, joined by a double-headed arrow. Row 3 (y about 58.4%) has three boxes at x about 35.6%, 41.9% and 48.4%, joined by double-headed arrows between the second and third boxes and between the first and second. Row 4 (y about 67.6%) has five boxes at x about 35.6%, 41.9%, 48.4%, 54.8% and 61.2%, joined by double-headed arrows. Single-headed orthogonal connectors run downward and diagonally between rows: from row 1 box 1 down to row 2 box 1 and across to row 2 box 2 region; from row 1 box 2 to row 2 box 2; from row 1 box 3 two long lines down to row 3 box 3 and to row 4 box 4; from row 1 box 4 down and right to row 4 box 5; from row 2 boxes down to row 3 boxes; from row 3 boxes down to row 4 boxes. Arrowheads are small and filled. The diagram has a faint reflection on the floor beneath row 4. Lighting is a soft spotlight from above, creating a dark, moody scene.

**Design**

Background: Full-bleed photograph of a dark studio floor: black at top graded to charcoal grey #2A2A2A near the bottom, with a faint reflective sheen. Black background fading to dark charcoal grey on the lower third, suggesting a glossy floor. Headline text is white #FFFFFF, all capitals, in a bold geometric sans-serif (DIN Pro Bold style), set at about 4.1% of slide height. Diagram strokes are muted gold #C8A96A with thin lines of about 1 px. Box outlines are gold #B8985A. No shadows, no rounded corners, and the cloud has a rounded outline. The composition is minimal with generous black space above and below the diagram.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark studio background photograph, black top grading to charcoal floor with a faint reflection (Covers the whole slide, sits at the back. Lit from above and fading into a glossy grey floor. A solid white fill is also present behind it, fully covered.)
- title at x 11.7, y 7.9, w 76.6, h 4.1 [DIN Pro Bold, bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: EVERY USER AND WORKLOAD OF A DATA CENTER IS A SECURITY THREAT (Single line, no letter-spacing change visible.)
- icon at x 42.4, y 21.3, w 8.8, h 9.9 [#C8A96A]: Cloud outline icon (Gold outline, about 1 px stroke, no fill (transparent), rounded lobes, with a short inner curve at the lower right.)
- diagram at x 45.2, y 33.3, w 3.2, h 4.4 [#C8A96A]: Bundle of four vertical double-headed arrows linking the cloud to the top row of boxes (Four parallel thin gold lines with small filled arrowheads at both ends, about 0.1% spacing apart.)
- diagram at x 35.6, y 40.1, w 28.8, h 33.1 [#B8985A]: Grid diagram of 14 outlined square boxes with connecting double-headed and single-headed arrows, no labels (Boxes are square outlines with no fill, about 1 px gold stroke, each about 6.4% wide and 5.7% high. Row 1 at y about 40.1% has 4 boxes (x about 35.6, 41.9, 48.4, 54.8). Row 2 at y about 49.3% has 2 boxes (x about 35.6, 41.9). Row 3 at y about 58.4% has 3 boxes (x about 35.6, 41.9, 48.4). Row 4 at y about 67.6% has 5 boxes (x about 35.6, 41.9, 48.4, 54.8, 61.2). Horizontal double-headed arrows join neighbouring boxes within rows. Orthogonal single-headed connectors run from upper boxes down to lower boxes, the longest from row 1 box 3 down to row 4 box 4, and from row 1 box 4 down to row 4 box 5. Arrowheads are small and filled gold. Faint reflection of the boxes appears on the floor below row 4.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 11.7, y 7.9, w 76.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: EVERY USER AND WORKLOAD OF A DATA CENTER IS A SECURITY THREAT

### Slide 60

**Text**

ANNOUNCING NVIDIA MORPHEUS / Post-Process / Tokens / Security / Action / Net-Q / Gateway / Security Policies / Real-Time Telemetry / NVIDIA / BlueField-2 / Infer / Intruder / Activity / Pre-Process / Packets / NVIDIA MORPHEUS / NVIDIA AI / NVIDIA GPU CLOUD REGISTRY / cuIO / cuDF / cuDNN / cuML / cuGraph / TAO / TensorRT / Triton / NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G / VMware vSphere / NVIDIA / CERTIFIED / Atos / DELL Technologies / FUJITSU / GIGABYTE / HPE / hp / inspur / Lenovo / QCT / Supermicro

**Layout**

A large centred title sits across the top at about 8% from the top edge. Below it, the left half holds a vertical stack: a framed NVIDIA Morpheus flow panel above a green NVIDIA AI stack, a blue VMware vSphere bar and a partner logo strip, with a server unit in the bottom-left corner. The right side holds two labelled arrows in the centre and a column of three server racks with a circled BlueField-2 card on the right. No footer, slide number or source line is visible.

**Visuals**

Diagram (Morpheus flow): a dark charcoal rectangle with a thin brass/ochre outline holds five boxes with brass outlines and white labels. Top row left to right: Post-Process Tokens, then Security Action, then Net-Q Gateway, a tall box spanning both rows on the right. Bottom row right to left: Pre-Process Packets, then Infer Intruder Activity. Brass arrows run Post-Process Tokens to Security Action, Security Action to Net-Q Gateway, Net-Q Gateway down-left to Pre-Process Packets, Pre-Process Packets left to Infer Intruder Activity, and Infer Intruder Activity loops up on the far left back into Post-Process Tokens. The panel caption NVIDIA MORPHEUS sits at the bottom centre. A thin green line runs along the bottom edge of the panel. Diagram (stack): a bright green #76B900 block labelled NVIDIA AI at top, containing a darker green #5A9A00 bar NVIDIA GPU CLOUD REGISTRY, a row of seven darker green tiles labelled cuIO, cuDF, cuDNN, cuML, cuGraph, TAO, TensorRT, Triton, a darker green bar NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G, and below it a blue #1E7FD6 bar labelled VMware vSphere. Arrows: two horizontal white arrows labelled Security Policies (pointing right, to the racks) and Real-Time Telemetry (pointing left, to the Morpheus side), both thin white lines with small arrowheads. Illustration (racks): three tall server racks drawn in thin brass outlines on black, each a stack of about 12 units with a small circle and dash in each unit; the middle rack carries a horizontal network line with square connector nodes at the top of the left and right racks. A circular inset with a brass rim sits over the top of the middle rack, showing a close-up of an NVIDIA BlueField-2 DPU card (green-black PCB with a heatsink and gold-edged connector). Photograph (server): a white-grey 2U server tray, angled about 30 degrees, shown open with a black GPU card and a gold-bracketed card visible, lit from above, on a dark reflective floor. Logos: NVIDIA logo with CERTIFIED badge (white outline box) at lower left of the strip; white wordmarks Atos, DELL Technologies, FUJITSU, GIGABYTE, HPE (circle), hp (circle), inspur, Lenovo (in white box with black text), QCT, Supermicro, all white on black.

**Design**

Background: Black #000000 studio gradient fading to dark grey #2A2A2A at the bottom, with a reflective floor. Black #000000 background fading into a charcoal floor. Titles are white #FFFFFF DIN Pro Bold, all caps, centred, about 4.1% of slide height. Body and diagram labels are white #FFFFFF DIN Pro Medium at about 1.5%, and captions are DIN Pro Regular at about 1.2 to 1.7%. Accents are brass/ochre #B8862B for outlines, arrows and rack lines, bright green #76B900 for the NVIDIA AI block, darker green #5A9A00 for inner bars and tiles, and blue #1E7FD6 for the VMware bar. The Morpheus panel is near-black #141414 with a brass outline. Shapes have square corners and no shadows. Racks use thin brass lines with no fill.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Dark studio background: black top fading to charcoal with a reflective floor, full bleed (Full-bleed image covering the slide, opacity 100%)
- title at x 32.5, y 7.9, w 35.6, h 4.1 [DIN Pro Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA MORPHEUS
- shape at x 14, y 21.5, w 33.9, h 33.5 [#141414]: Morpheus panel: dark rectangle with brass outline (Brass #B8862B outline about 0.2% width, green #76B900 line along bottom edge, square corners, no shadow)
- shape at x 18.05, y 24.9, w 7.65, h 9.96 [#141414]: Box: Post-Process Tokens (Brass #B8862B outline, square corners)
- shape at x 29.55, y 24.9, w 7.65, h 9.96 [#141414]: Box: Security Action (Brass #B8862B outline, square corners)
- shape at x 41, y 24.9, w 5, h 23.9 [#141414]: Box: Net-Q Gateway (tall, spans both rows) (Brass #B8862B outline, square corners)
- shape at x 18.05, y 38.8, w 7.65, h 9.96 [#141414]: Box: Infer Intruder Activity (Brass #B8862B outline, square corners)
- shape at x 29.55, y 38.8, w 7.65, h 9.96 [#141414]: Box: Pre-Process Packets (Brass #B8862B outline, square corners)
- line at x 16, y 27, w 25, h 18 [#B8862B]: Brass connector arrows: Post-Process Tokens to Security Action, Security Action to Net-Q Gateway, Net-Q Gateway to Pre-Process Packets, Pre-Process Packets to Infer Intruder Activity, and loop from Infer Intruder Activity back to Post-Process Tokens (Thin brass lines about 0.1% width with small filled arrowheads; the loop runs down the left edge of the boxes)
- text at x 19.4, y 28.4, w 5, h 3 [DIN Pro Medium; font size 1.48% of slide height; #FFFFFF; center aligned]: Post-Process / Tokens
- text at x 31.8, y 28.4, w 3.1, h 3 [DIN Pro Medium; font size 1.48% of slide height; #FFFFFF; center aligned]: Security / Action
- text at x 41.9, y 35.4, w 3.2, h 3.2 [DIN Pro Medium; font size 1.48% of slide height; #FFFFFF; center aligned]: Net-Q / Gateway
- text at x 20.3, y 41.5, w 4.7, h 4.6 [DIN Pro Medium; font size 1.48% of slide height; #FFFFFF; center aligned]: Infer / Intruder / Activity
- text at x 29.6, y 42.4, w 4.7, h 3 [DIN Pro Medium; font size 1.48% of slide height; #FFFFFF; center aligned]: Pre-Process / Packets
- text at x 26.7, y 51.5, w 8.4, h 1.7 [DIN Pro Regular, all caps; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA MORPHEUS
- line at x 50, y 34, w 13.25, h 0.3 [#FFFFFF]: Telemetry arrow pointing right with label Security Policies above (White line about 0.1% width with arrowhead at right end)
- text at x 53.1, y 31.3, w 7.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Security Policies
- line at x 50, y 39.3, w 13.25, h 0.3 [#FFFFFF]: Telemetry arrow pointing left with label Real-Time Telemetry below (White line about 0.1% width with arrowhead at left end)
- text at x 52.1, y 40.8, w 9, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Real-Time Telemetry
- illustration at x 65.4, y 40.7, w 30.9, h 41.6 [#000000]: Three server racks in brass outlines, about 12 units each with circle and dash markers; network line with square nodes above left and right racks (Brass #B8862B thin outlines, no fill; the middle rack is partly covered by the BlueField-2 inset)
- illustration at x 71.65, y 29.4, w 8.05, h 14.3 [#1A1A1A]: Circular inset: NVIDIA BlueField-2 DPU card close-up with brass rim (Circle with brass rim about 0.2% width; card shown dark grey with green-black PCB and heatsink; overlaps the top of the middle rack)
- text at x 73.6, y 38.6, w 4.3, h 3.3 [DIN Pro Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA / BlueField-2
- shape at x 14, y 59.2, w 33.9, h 17.3 [#76B900]: NVIDIA AI block with green header and tiles (Bright green #76B900 outer block; inner bars and tiles darker green #5A9A00 with subtle shadow; square corners)
- text at x 28.8, y 60.1, w 4.2, h 1.7 [DIN Pro Medium; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA AI
- shape at x 15, y 62.4, w 31.9, h 3.4 [#5A9A00]: Bar: NVIDIA GPU CLOUD REGISTRY (Square corners, slight shadow)
- text at x 26.3, y 63.7, w 9.4, h 1.2 [DIN Pro Regular, all caps; font size 1.24% of slide height; #FFFFFF; center aligned]: NVIDIA GPU CLOUD REGISTRY
- shape at x 15, y 66.6, w 31.9, h 4.8 [#5A9A00]: Row of eight tiles: cuIO, cuDF, cuDNN, cuML, cuGraph, TAO, TensorRT, Triton (Eight separate darker green tiles with slight shadow, square corners)
- text at x 15.6, y 68.5, w 1.4, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: cuIO
- text at x 19.6, y 68.5, w 1.6, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: cuDF
- text at x 23.5, y 68.5, w 2.2, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: cuDNN
- text at x 27.9, y 68.5, w 1.7, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: cuML
- text at x 31.6, y 68.5, w 2.6, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: cuGraph
- text at x 36.5, y 68.5, w 1.2, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: TAO
- text at x 39.8, y 68.5, w 2.9, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: TensorRT
- text at x 44.5, y 68.5, w 1.8, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: Triton
- shape at x 15, y 72.4, w 31.9, h 3.6 [#5A9A00]: Bar: NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G (Square corners, slight shadow)
- text at x 23.2, y 73.6, w 15.4, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G
- shape at x 14, y 77.7, w 33.9, h 3.6 [#1E7FD6]: Bar: VMware vSphere (Square corners, faint glow below)
- text at x 28.4, y 79, w 5.1, h 1.2 [DIN Pro Regular; font size 1.24% of slide height; #FFFFFF; center aligned]: VMware vSphere
- photo at x 8.25, y 74.3, w 12.65, h 16.5 [#E8E8E8]: Server unit: white 2U server tray at an angle, open, with black GPU card and gold-bracketed card visible, on a dark reflective floor (Boxed, not cropped, lit from above, overlaps the bottom-left corner of the NVIDIA AI block)
- logo at x 22.5, y 83.4, w 8.5, h 5.2 [#76B900]: NVIDIA logo with CERTIFIED badge (Green NVIDIA eye-and-wordmark over a white outlined CERTIFIED badge)
- logo at x 31.2, y 83.5, w 2, h 1.2 [#FFFFFF]: Atos logo (White wordmark on black)
- logo at x 33.8, y 83.7, w 4.3, h 1.1 [#FFFFFF]: DELL Technologies logo (White wordmark on black)
- logo at x 39.1, y 83.8, w 1.9, h 1 [#FFFFFF]: FUJITSU logo (White wordmark on black)
- logo at x 42, y 83.7, w 2.7, h 1.1 [#FFFFFF]: GIGABYTE logo (White wordmark on black)
- logo at x 45.9, y 83.2, w 1.1, h 1.8 [#FFFFFF]: HPE logo (White circle with dark mark)
- logo at x 31, y 85.5, w 1.2, h 1.8 [#FFFFFF]: hp logo (White circle with dark mark)
- logo at x 34, y 86, w 1.8, h 1 [#FFFFFF]: inspur logo (White italic wordmark)
- logo at x 37.9, y 85.8, w 1.9, h 1 [#E2231A]: Lenovo logo (White box with red text)
- logo at x 41.6, y 85.2, w 1.2, h 1.8 [#FFFFFF]: QCT logo (Cloud outline mark with QCT letters)
- logo at x 44.9, y 85.5, w 2.1, h 1.4 [#FFFFFF]: Supermicro logo (White outline oval with wordmark)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 14.5, y 72.4, w 32.6, h 3.6: 3915 by 242 pixels
- image at x 14.0, y 77.9, w 33.8, h 3.3: 4062 by 222 pixels
- image at x 21.5, y 81.4, w 7.9, h 8.3: 647 by 381 pixels
- image at x 24.7, y 58.4, w 12.5, h 4.9: 1503 by 333 pixels
- image at x 20.8, y 63.2, w 20.2, h 2.1: 2430 by 145 pixels
- image at x 14.4, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 43.5, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 18.6, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 22.7, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 26.9, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 39.4, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 35.2, y 66.6, w 3.8, h 4.8: 453 by 324 pixels
- image at x 31.1, y 66.6, w 3.8, h 4.8: 453 by 323 pixels
- text at x 32.5, y 7.9, w 35.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA MORPHEUS
- text at x 53.1, y 31.3, w 7.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Security Policies
- text at x 19.4, y 28.4, w 5.0, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Post-Process
- text at x 31.8, y 28.4, w 3.1, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Security
- text at x 20.5, y 30.2, w 2.7, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Tokens
- text at x 32.2, y 30.2, w 2.3, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Action
- text at x 52.1, y 40.8, w 9.0, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Real-Time Telemetry
- text at x 42.4, y 35.4, w 2.2, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Net-Q
- text at x 41.9, y 37.1, w 3.2, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Gateway
- text at x 74.4, y 38.6, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 73.6, y 40.4, w 4.3, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: BlueField-2
- text at x 21.0, y 41.5, w 1.8, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Infer
- text at x 31.0, y 42.4, w 4.7, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Pre-Process
- text at x 20.3, y 43.2, w 3.1, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Intruder
- text at x 26.7, y 51.5, w 8.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA MORPHEUS
- text at x 31.9, y 44.1, w 3.0, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Packets
- text at x 20.5, y 45.0, w 2.7, h 1.5 [DINPro-Medium; font size 1.48; #FFFFFF]: Activity
- text at x 28.8, y 60.1, w 4.2, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: NVIDIA AI
- text at x 26.3, y 63.7, w 9.4, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: NVIDIA GPU CLOUD REGISTRY
- text at x 15.6, y 68.5, w 1.4, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: cuIO
- text at x 19.6, y 68.5, w 1.6, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: cuDF
- text at x 23.5, y 68.5, w 2.2, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: cuDNN
- text at x 27.9, y 68.5, w 1.7, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: cuML
- text at x 31.6, y 68.5, w 2.6, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: cuGraph
- text at x 36.5, y 68.5, w 1.2, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: TAO
- text at x 39.8, y 68.5, w 2.9, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: TensorRT
- text at x 44.5, y 68.5, w 1.8, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: Triton
- text at x 23.2, y 73.6, w 15.4, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G
- text at x 28.4, y 79.0, w 5.1, h 1.2 [DINPro-Regular; font size 1.24; #FFFFFF]: VMware vSphere

### Slide 61

**Text**

10.244.0.50 -> 10.244.0.14 / SI: secret_keys / { / "who": "32205660 pVycjWHH", / "thing": "within there ImXxoVGN", / "condition": "Nnpdtcvs 89234632", / "key": "nearly appear n1kLSr8A 41142934 actually QZnPjQyd" / }

**Layout**

Full-bleed dark network-graph visualization with no title, margins or footer. A small tooltip label sits at upper right of centre beside a highlighted edge. A monospace-style JSON-like text block is anchored bottom left, left-aligned at about 0.5% from the left edge and ending near the bottom edge. No slide number is visible.

**Visuals**

Network graph rendered on a black field. About 9 small white-grey circular nodes (roughly 1% of slide width each, light grey outline) are joined by curved edges that fan out from them. Dense bundles of thin light-grey (#B0B0B0, low opacity) arcs run from the upper-left, top-centre hub and lower-left node toward the lower right and right edge. A hub near (38%,24%) has many arcs. Red (#B22222) arcs, roughly 15% of edges, run from the hub to the lower and right areas. One brighter pale-grey/white arc runs from the hub across to a node at the right edge (about 99.7%,45%) and is labelled by the tooltip. A pointer cursor sits at the tooltip start. No chart axes, legend or table. No photograph or logo.

**Design**

Background: Solid black (#000000) with the graph drawn on top. Black background (#000000) with no gradient. Tooltip text is white (#FFFFFF) in a sans-serif (DejaVu Sans-like regular) at about 1.3% of slide height. JSON block text is light grey (#C8C8C8) in a sans-serif (DejaVu Sans-like regular) at about 2.2% of slide height, line spacing about 2.4%. Edges are thin lines with about 0.5 px width, grey (#B0B0B0) at low opacity, red (#B22222) for highlighted paths. Nodes are small filled white (#FFFFFF) circles with grey rim. No shadows, no corner radii, no boxes around text.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- diagram at x 0, y 0, w 100, h 100 [#000000]: Full-slide network graph: about 9 white circular nodes joined by grey and red curved edges on a black field (Edges grey #B0B0B0 at low opacity, about 0.5 px wide, curved arcs; red #B22222 highlighted arcs; nodes white #FFFFFF with grey rim, about 1% of width; a highlighted pale arc from hub (38%,24%) to right edge node (99.7%,45%); a cursor overlaps the tooltip start; covers the full slide)
- caption at x 72, y 25.5, w 11.2, h 3.6 [DejaVu Sans-like sans-serif, regular; font size 1.3% of slide height; #FFFFFF; left aligned]: 10.244.0.50 -> 10.244.0.14 / SI: secret_keys (Two lines, line spacing about 1.7% of height; sits on top of the pale highlighted edge with no box or background)
- body at x 0.5, y 86.5, w 37.5, h 13.2 [DejaVu Sans-like sans-serif, regular; font size 2.2% of slide height; #C8C8C8; left aligned]: { / "who": "32205660 pVycjWHH", / "thing": "within there ImXxoVGN", / "condition": "Nnpdtcvs 89234632", / "key": "nearly appear n1kLSr8A 41142934 actually QZnPjQyd" / } (Six lines of JSON-style text, first line opening brace at left edge, indented keys by about 1.5% width, line spacing about 2.4% of height, no box or background; overlaps the dense grey edge bundles)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 99.9: 2862 by 1549 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)

### Slide 62

**Text**

NVIDIA EGX ENTERPRISE ECOSYSTEM
INFRASTRUCTURE
CANONICAL
Google Cloud
Red Hat
vmware
INDUSTRIAL EDGE
DATA MONSTERS
DEMATIC
everseen
kinetic vision
OSARO
DATA ANALYTICS &
MACHINE LEARNING
CLOUDERA
splunk>
ALLUXIO
kinetica
omni-sci
plotly
DIGITAL TWIN
ALTAIR
Ansys
Bentley Advancing Infrastructure
CATIA
NETALLIED SYSTEMS
ptc
SIMULIA
CYBER SECURITY
Check Point Software Technologies Ltd
CLOUDFLARE
FORTINET
Guardicore
paloalto NETWORKS
5G
Capgemini
ERICSSON
FUJITSU
MAVENIR
Radisys
NVIDIA.
CERTIFIED
Atos
DELL Technologies
FUJITSU
GIGABYTE
H3C
hp
inspur
Lenovo
QCT
SUPERMICRO

**Layout**

Six equal tall vertical columns of the same width and height sit side by side across the middle of the slide, each with a centred gold heading at the top and a stack of logos centred down the column. The main title is centred across the top band, and a row of NVIDIA certification and partner logos sits along the bottom beneath the columns, with a white server sled at lower left of centre. There is no footer, page number or date.

**Visuals**

Six dark vertical panels with thin gold outlines, one per category: Infrastructure with Canonical, Google Cloud, Red Hat and VMware; Industrial Edge with Data Monsters, Dematic, everseen, kinetic vision and OSARO; Data Analytics and Machine Learning with Cloudera, Splunk, Alluxio, Kinetica, Omnisci and Plotly; Digital Twin with Altair, Ansys, Bentley, CATIA, Netallied Systems, PTC and Simulia; Cyber Security with Check Point, Cloudflare, Fortinet, Guardicore and Palo Alto Networks; 5G with Capgemini, Ericsson, Fujitsu, Mavenir and Radisys. All logos are white or light grey and centred in their column. At bottom centre-left is a photographic render of a white server sled tilted about 15 degrees, showing a black GPU card with a black heatsink and fan and a bronze-gold accelerator card lying beside it, slightly overlapping the Industrial Edge and Data Analytics panels at their bottom edges. Beside it is the NVIDIA logo with the word CERTIFIED in a thin outlined box. Bottom right has two rows of partner logos: Atos, Dell Technologies, Fujitsu, Gigabyte and H3C in row one; HP, Inspur, Lenovo, QCT and Supermicro in row two, all white. The backdrop is a dark studio photograph with a black upper area fading to dark charcoal and a glossy reflective floor at the bottom.

**Design**

Background: Photographic studio backdrop, black #000000 at top fading to charcoal #2A2A2A at the bottom with a reflective floor. Black to charcoal backdrop, approximately #000000 at top fading to #2A2A2A at the floor. Panels are near-black #111111 with 1px gold outlines #8A6D3B. Main title is white #FFFFFF, bold DIN-style geometric sans-serif in all caps, about 4 percent of slide height. Column headings are gold #B3914C, medium-weight DIN-style sans-serif in all caps, about 2.5 percent of slide height. Logos are white #FFFFFF. Accent is gold #B3914C. Panel corners are square with no shadow or gradient on the panels.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio backdrop photograph, black at top fading to charcoal with a reflective floor (Covers the entire slide, 3840 by 2160 source, no overlay, no crop)
- shape at x 3.8, y 21.5, w 14.2, h 61.8 [#111111]: Column panel 1 (Infrastructure) (Rectangle, 1px gold outline #8A6D3B, square corners, no shadow)
- shape at x 19.4, y 21.5, w 14.2, h 61.8 [#111111]: Column panel 2 (Industrial Edge) (Rectangle, 1px gold outline #8A6D3B, square corners, no shadow)
- shape at x 35.1, y 21.5, w 14.2, h 61.8 [#111111]: Column panel 3 (Data Analytics and Machine Learning) (Rectangle, 1px gold outline #8A6D3B, square corners, no shadow)
- shape at x 50.7, y 21.5, w 14.2, h 61.8 [#111111]: Column panel 4 (Digital Twin) (Rectangle, 1px gold outline #8A6D3B, square corners, no shadow)
- shape at x 66.4, y 21.5, w 14.2, h 61.8 [#111111]: Column panel 5 (Cyber Security) (Rectangle, 1px gold outline #8A6D3B, square corners, no shadow)
- shape at x 82, y 21.5, w 14.2, h 61.8 [#111111]: Column panel 6 (5G) (Rectangle, 1px gold outline #8A6D3B, square corners, no shadow)
- title at x 30.2, y 7.9, w 39.6, h 4.1 [DIN Pro Bold, sans-serif, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA EGX ENTERPRISE ECOSYSTEM
- body at x 5, y 24.1, w 11.7, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #B3914C; center aligned]: INFRASTRUCTURE
- body at x 20.7, y 24.1, w 11.7, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #B3914C; center aligned]: INDUSTRIAL EDGE
- body at x 35.6, y 24.1, w 13.1, h 5.1 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #B3914C; center aligned]: DATA ANALYTICS & / MACHINE LEARNING (Two lines, line spacing about 1.2)
- body at x 53.5, y 24.1, w 8.7, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #B3914C; center aligned]: DIGITAL TWIN
- body at x 68, y 24.1, w 10.9, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #B3914C; center aligned]: CYBER SECURITY
- body at x 88.3, y 24.1, w 1.6, h 2.5 [DIN Pro Medium, sans-serif, uppercase; font size 2.47% of slide height; #B3914C; center aligned]: 5G
- logo at x 7.3, y 36.7, w 7.3, h 2.1 [#FFFFFF]: Canonical wordmark (White, light weight, circle-in-O mark)
- logo at x 6.2, y 47.5, w 8.3, h 3 [#FFFFFF]: Google Cloud wordmark
- logo at x 7.3, y 59.5, w 7.3, h 3.2 [#FFFFFF]: Red Hat logo with fedora hat mark
- logo at x 7.6, y 72.4, w 6.7, h 2.3 [#FFFFFF]: VMware wordmark
- logo at x 23.6, y 36.8, w 5.8, h 3.2 [#FFFFFF]: Data Monsters logo with grey circle mark
- logo at x 23.6, y 44.2, w 5.8, h 3.7 [#FFFFFF]: Dematic wordmark with vertical bar
- logo at x 23.4, y 54.5, w 6.2, h 2.3 [#FFFFFF]: everseen wordmark
- logo at x 22.7, y 63.7, w 7.5, h 2.3 [#FFFFFF]: kinetic vision wordmark
- logo at x 23.7, y 72.9, w 5.5, h 2.1 [#FFFFFF]: OSARO wordmark
- logo at x 38.7, y 37.2, w 6.9, h 2 [#FFFFFF]: CLOUDERA wordmark
- logo at x 39.8, y 43.9, w 4.8, h 2.3 [#FFFFFF]: splunk> wordmark
- logo at x 38.9, y 50.9, w 6.5, h 2.7 [#FFFFFF]: Alluxio logo with triangle mark and wordmark
- logo at x 39.5, y 58.3, w 5.4, h 2.1 [#FFFFFF]: kinetica wordmark
- logo at x 38.3, y 66, w 7.8, h 1.6 [#FFFFFF]: omni-sci wordmark
- logo at x 39.7, y 72.6, w 4.8, h 3 [#FFFFFF]: plotly logo with bar-chart mark
- logo at x 55, y 37.1, w 5.5, h 2.1 [#FFFFFF]: ALTAIR logo with triangle mark
- logo at x 55.9, y 42.8, w 3.9, h 2.1 [#FFFFFF]: Ansys wordmark
- logo at x 55.4, y 48.5, w 4.8, h 3 [#FFFFFF]: Bentley Advancing Infrastructure logo
- logo at x 55.2, y 54.5, w 5.2, h 2.7 [#FFFFFF]: CATIA logo with 3DS mark
- logo at x 54.3, y 60.6, w 7, h 3.2 [#FFFFFF]: NETALLIED SYSTEMS logo with circular mark
- logo at x 55.9, y 66.7, w 3.7, h 2.7 [#FFFFFF]: ptc logo with cube mark
- logo at x 54.8, y 72.9, w 6.1, h 2.1 [#FFFFFF]: SIMULIA logo with 3DS mark
- logo at x 69.8, y 36.9, w 7.3, h 2.7 [#FFFFFF]: Check Point Software Technologies Ltd logo
- logo at x 69.2, y 45.5, w 8.5, h 2.7 [#FFFFFF]: CLOUDFLARE logo with cloud mark
- logo at x 70, y 54.9, w 6.8, h 1.8 [#FFFFFF]: FORTINET wordmark
- logo at x 69.8, y 63.6, w 7.3, h 2.8 [#FFFFFF]: Guardicore logo with shield mark
- logo at x 70, y 73, w 7, h 2.1 [#FFFFFF]: paloalto NETWORKS logo
- logo at x 85.8, y 37.2, w 6.5, h 2.3 [#FFFFFF]: Capgemini logo with spade mark
- logo at x 85.7, y 45.9, w 6.7, h 2.1 [#FFFFFF]: ERICSSON wordmark with stacked bars
- logo at x 87.3, y 54.9, w 3.5, h 2 [#FFFFFF]: FUJITSU wordmark
- logo at x 86.3, y 64, w 5.5, h 2 [#FFFFFF]: MAVENIR wordmark
- logo at x 86.7, y 73, w 4.6, h 2 [#FFFFFF]: Radisys wordmark
- shape at x 27.3, y 78.7, w 14.5, h 18.2: Server sled with GPU and accelerator card, photographic render (Tilted about 15 degrees, white plastic tray with black GPU card and bronze-gold accelerator card, overlaps bottom edges of Industrial Edge and Data Analytics panels)
- logo at x 42.1, y 87.7, w 6.2, h 2 [#76B900]: NVIDIA logo (eye mark with NVIDIA wordmark) (Green eye mark with white NVIDIA wordmark)
- logo at x 42.5, y 90.3, w 6.2, h 2.7 [#FFFFFF]: CERTIFIED badge (Thin white outlined rectangle with white uppercase CERTIFIED text, square corners)
- logo at x 55, y 88, w 3.9, h 1.6 [#FFFFFF]: Atos logo
- logo at x 58.6, y 88, w 5.5, h 1.6 [#FFFFFF]: Dell Technologies logo
- logo at x 65.8, y 88, w 2.2, h 1.6 [#FFFFFF]: Fujitsu logo
- logo at x 69.7, y 88, w 3.4, h 1.6 [#FFFFFF]: GIGABYTE logo
- logo at x 75, y 87.6, w 1.4, h 2.4 [#FFFFFF]: H3C logo in white circle
- logo at x 55, y 91, w 1.5, h 2.5 [#FFFFFF]: HP logo
- logo at x 59.2, y 91.6, w 2.2, h 1.2 [#FFFFFF]: inspur logo
- logo at x 64.1, y 91.5, w 2.5, h 1.6 [#FFFFFF]: Lenovo logo
- logo at x 69.4, y 90.6, w 1.4, h 2.8 [#FFFFFF]: QCT logo with cloud mark
- logo at x 73.7, y 90.9, w 2.7, h 2.5 [#FFFFFF]: SUPERMICRO logo in outlined oval

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 41.0, y 85.7, w 9.0, h 9.4: 647 by 381 pixels
- image at x 6.1, y 46.7, w 9.5, h 4.9: 1144 by 330 pixels
- image at x 69.7, y 72.4, w 7.5, h 3.7: 184 by 56 pixels
- image at x 38.3, y 65.3, w 7.6, h 3.3: 834 by 200 pixels
- image at x 69.8, y 63.6, w 7.3, h 3.3: 1067 by 330 pixels
- image at x 53.8, y 72.4, w 7.9, h 3.0: 952 by 202 pixels
- image at x 86.6, y 71.9, w 5.0, h 4.6: 218 by 114 pixels
- image at x 39.7, y 71.8, w 4.8, h 4.7: 653 by 360 pixels
- image at x 7.3, y 59.6, w 7.2, h 3.0: 1227 by 290 pixels
- image at x 54.3, y 60.8, w 6.9, h 3.0: 940 by 234 pixels
- image at x 39.8, y 43.2, w 4.8, h 4.3: 318 by 158 pixels
- image at x 23.7, y 44.2, w 5.6, h 3.5: 336 by 118 pixels
- image at x 69.2, y 45.5, w 8.5, h 2.2: 1088 by 156 pixels
- image at x 23.7, y 36.8, w 5.7, h 2.8: 682 by 191 pixels
- image at x 38.9, y 51.0, w 6.5, h 2.5: 711 by 153 pixels
- image at x 39.5, y 58.0, w 5.4, h 3.0: 317 by 98 pixels
- image at x 69.8, y 37.3, w 7.3, h 2.2: 600 by 102 pixels
- image at x 85.8, y 45.7, w 6.6, h 2.4: 797 by 162 pixels
- image at x 55.3, y 42.5, w 5.0, h 2.9: 605 by 196 pixels
- image at x 22.7, y 63.9, w 7.5, h 1.8: 1006 by 133 pixels
- image at x 7.5, y 72.8, w 6.7, h 2.0: 300 by 49 pixels
- image at x 55.4, y 48.9, w 4.8, h 2.7: 175 by 56 pixels
- image at x 7.3, y 37.1, w 7.2, h 1.7: 600 by 80 pixels
- image at x 55.2, y 54.5, w 5.1, h 2.4: 562 by 147 pixels
- image at x 55.0, y 37.2, w 5.5, h 2.0: 330 by 68 pixels
- image at x 38.7, y 37.4, w 6.9, h 1.5: 827 by 101 pixels
- image at x 86.3, y 63.9, w 5.4, h 1.9: 400 by 77 pixels
- image at x 70.0, y 55.2, w 6.8, h 1.5: 409 by 50 pixels
- image at x 87.4, y 54.3, w 3.4, h 2.9: 191 by 90 pixels
- image at x 23.4, y 55.1, w 6.2, h 1.6: 370 by 53 pixels
- image at x 23.7, y 73.1, w 5.5, h 1.7: 300 by 52 pixels
- image at x 56.0, y 66.8, w 3.6, h 2.5: 216 by 85 pixels
- image at x 58.6, y 88.2, w 5.5, h 1.3: 328 by 43 pixels
- image at x 69.2, y 90.1, w 1.8, h 3.8: 213 by 255 pixels
- image at x 73.7, y 91.0, w 2.7, h 2.4: 160 by 81 pixels
- text at x 30.2, y 7.9, w 39.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA EGX ENTERPRISE ECOSYSTEM
- text at x 5.0, y 24.1, w 11.7, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: INFRASTRUCTURE
- text at x 20.7, y 24.1, w 11.7, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: INDUSTRIAL EDGE
- text at x 36.1, y 24.1, w 12.3, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: DATA ANALYTICS &
- text at x 53.5, y 24.1, w 8.7, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: DIGITAL TWIN
- text at x 68.0, y 24.1, w 10.9, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: CYBER SECURITY
- text at x 88.3, y 24.1, w 1.6, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: 5G
- text at x 35.6, y 26.7, w 13.1, h 2.5 [DINPro-Medium; font size 2.47; #B3914C]: MACHINE LEARNING

### Slide 63

**Text**

ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
Enterprise-Ready Suite of AI and Data Science Software
DATA PREP
TRAIN
SIMULATE
ORCHESTRATE
NVIDIA AI ENTERPRISE
NVIDIA GPU CLOUD REGISTRY
cuIO
cuDF
cuDNN
cuML
cuGraph
TAO
TensorRT
Triton
NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G, Morpheus
VMware vSphere
NVIDIA
CERTIFIED
Atos / DELL Technologies / FUJITSU / GIGABYTE / H3C
hp / inspur / Lenovo / QCT / SUPERMICRO
NVIDIA BlueField-2
NVIDIA A100/A30
NVIDIA A40/A10
NVIDIA Aerial A100

**Layout**

Centred single-column composition on a black stage: the title and subtitle sit centred across the top (about 8% from the top edge). Below, a row of four equal boxes (DATA PREP, TRAIN, SIMULATE, ORCHESTRATE) runs left to right, joined by arrows and a gold loop line that returns from ORCHESTRATE to DATA PREP. A centred gold software stack follows, then a blue VMware bar, with partner logos in two rows at the bottom right of centre and four circular product insets along the bottom left. No footer, page number or slide number is visible.

**Visuals**

Diagram: a top process flow of four dark rectangles with thin gold outlines, connected by small gold arrows pointing right (DATA PREP to TRAIN to SIMULATE to ORCHESTRATE). A thin gold line starts at the left edge of DATA PREP's arrow, rises above the boxes, runs across to ORCHESTRATE's right side and descends back into it, forming a loop. Each box holds a white line icon: DATA PREP shows database tables with arrows and a grid of rows; TRAIN shows a neural network diagram of nodes and connecting lines; SIMULATE shows a robotic arm with circular motion arcs; ORCHESTRATE shows a 3x3 grid of icons (factory, truck, wind turbine, phone, traffic light, robotic arm, control panel, forklift, and cloud-like device). Below, a large gold-brown stacked block labelled NVIDIA AI ENTERPRISE has a header bar, a row of eight equal tiles (cuIO, cuDF, cuDNN, cuML, cuGraph, TAO, TensorRT, Triton), and a bottom bar listing NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G and Morpheus. Under it is a horizontal blue bar reading VMware vSphere. A white-grey server chassis photo sits at the left, angled, showing an open tray with a green-gold NVIDIA card and gold heatsink cards. Beneath, an NVIDIA CERTIFIED badge (green eye logo above the word CERTIFIED in a white outlined box) and a grid of partner logos: row 1 Atos, DELL Technologies, FUJITSU, GIGABYTE, H3C; row 2 hp, inspur, Lenovo, QCT, SUPERMICRO. Four circular product photos along the bottom left: NVIDIA BlueField-2 (dark card with a chip), NVIDIA A100/A30 (gold-tan card edge), NVIDIA A40/A10 (gold-tan card edge), NVIDIA Aerial A100 (dark GPU module with a gold heatsink). Photos are dark and lit from the top-left with gold rim highlights.

**Design**

Background: Black #000000 at top fading to dark grey #1E1E1E floor with a warm gold glow (#8A6A34) at bottom centre, full-bleed photographic studio backdrop. Black background (#000000) fading to dark grey floor (#1E1E1E) with a warm gold glow (#8A6A34) at bottom centre. Titles white #FFFFFF in DIN Pro Bold, all caps, about 4.1% of slide height. Subtitle white #FFFFFF in DIN Pro Regular, about 2.7%. Box headings white DIN Pro Medium about 1.7%. Stack text white DIN Pro Regular about 1.7% (Aerial 5G and Morpheus in DIN Pro Black). Accents gold #C8A96A for box outlines, connector arrows and loop line, and gold-brown #8C6D3F to #A9864F for the software stack. VMware bar blue #0068C8. Box fills near-black #111111 with 1px gold outlines #B8925A; no rounded corners, no shadows on boxes, subtle drop shadow beneath the stack. Circular photos have thin gold rims #B8925A.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark studio backdrop: black upper area fading to dark grey floor with a warm gold glow at bottom centre (Full-bleed photograph, covers the slide; lower part reflective floor with gold light pool)
- line at x 27.2, y 20, w 45.7, h 9.2 [#C8A96A]: Gold loop line from ORCHESTRATE back to DATA PREP (Thin 1px gold stroke, rectangular path: top edge at y 20%, vertical drops at x 27.2% and 72.9% to the box mid-height arrows)
- title at x 23.2, y 7.9, w 53.5, h 4.1 [DIN Pro Bold, all caps; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
- subtitle at x 31.1, y 12.5, w 37.7, h 2.7 [DIN Pro Regular; font size 2.72% of slide height; #FFFFFF; center aligned]: Enterprise-Ready Suite of AI and Data Science Software
- shape at x 29.6, y 22.6, w 7.2, h 13.4 [#111111]: DATA PREP box, dark rectangle with gold outline (1px gold outline #B8925A, square corners)
- shape at x 40.8, y 22.6, w 7.1, h 13.4 [#111111]: TRAIN box, dark rectangle with gold outline (1px gold outline #B8925A, square corners)
- shape at x 52, y 22.6, w 7.2, h 13.4 [#111111]: SIMULATE box, dark rectangle with gold outline (1px gold outline #B8925A, square corners)
- shape at x 63.3, y 22.6, w 7.1, h 13.4 [#111111]: ORCHESTRATE box, dark rectangle with gold outline (1px gold outline #B8925A, square corners)
- icon at x 31.1, y 26.4, w 6.3, h 8 [#FFFFFF]: DATA PREP icon: database tables with connecting arrows and a row grid (White line art)
- icon at x 42.6, y 26.4, w 3.4, h 8 [#FFFFFF]: TRAIN icon: neural network diagram of nodes and connecting lines (White line art)
- icon at x 52.7, y 26.9, w 5.9, h 7.8 [#FFFFFF]: SIMULATE icon: robotic arm with circular motion arcs (White line art)
- icon at x 63.8, y 25.9, w 6.1, h 9 [#FFFFFF]: ORCHESTRATE icon: 3x3 grid of factory, truck, wind turbine, phone, traffic light, robotic arm, control panel, forklift and device icons (White line art)
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DIN Pro Medium; font size 1.73% of slide height; #FFFFFF; center aligned]: DATA PREP
- text at x 43, y 23.6, w 2.8, h 1.7 [DIN Pro Medium; font size 1.73% of slide height; #FFFFFF; center aligned]: TRAIN
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DIN Pro Medium; font size 1.73% of slide height; #FFFFFF; center aligned]: SIMULATE
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DIN Pro Medium; font size 1.73% of slide height; #FFFFFF; center aligned]: ORCHESTRATE
- shape at x 36.8, y 28.9, w 15.5, h 0.8 [#C8A96A]: Gold connector arrows between the four process boxes (Three small right-pointing arrowheads on 1px gold lines, one between each pair of boxes)
- shape at x 27.2, y 40.1, w 45.7, h 23.5 [#8C6D3F]: NVIDIA AI ENTERPRISE stacked block: gold-brown panel with header, tile row and bottom bar (Square corners, gold-brown gradient #A9864F to #7A5D32, thin darker edges, subtle shadow beneath)
- text at x 42.7, y 41.1, w 14.5, h 2.5 [DIN Pro Medium; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AI ENTERPRISE
- shape at x 28.1, y 44.4, w 43.8, h 6.1 [#A58350]: NVIDIA GPU CLOUD REGISTRY header bar (Slightly lighter gold-brown panel with thin dark divider lines)
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU CLOUD REGISTRY
- shape at x 27.8, y 50.3, w 44.3, h 7.5 [#A58350]: Row of eight tiles: cuIO, cuDF, cuDNN, cuML, cuGraph, TAO, TensorRT, Triton (Eight equal boxes with 1px dark outlines, square corners, slight bevel)
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDF
- text at x 40, y 52.6, w 3.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDNN
- text at x 46, y 52.6, w 2.4, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuML
- text at x 51, y 52.6, w 3.6, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: TAO
- text at x 62, y 52.6, w 4.1, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Triton
- shape at x 27.8, y 58.1, w 44.3, h 5.4 [#A58350]: Bottom bar of the NVIDIA AI ENTERPRISE stack (Gold-brown panel with thin dark outline)
- text at x 36.9, y 59.3, w 26.6, h 1.7 [DIN Pro Regular with DIN Pro Black for Aerial 5G and Morpheus; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G, Morpheus (Aerial 5G and Morpheus in bold black weight)
- shape at x 27.2, y 65.2, w 45.7, h 4.8 [#0068C8]: VMware vSphere bar (Solid blue bar, square corners, slight dark shadow beneath)
- text at x 46.4, y 66.7, w 7.2, h 1.7 [DIN Pro Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: VMware vSphere
- photo at x 18.5, y 58.7, w 18.5, h 21.3 [#E8E8E8]: Server chassis photo: open white-grey tray with a green-gold NVIDIA card and gold heatsink cards, angled view (Photograph, boxed with no border, overlaps the stack's left edge and the VMware bar)
- logo at x 38.4, y 71.6, w 6.9, h 5.7 [#76B900; left aligned]: NVIDIA logo with CERTIFIED badge (Green eye-shaped NVIDIA mark above the word NVIDIA in white; below, CERTIFIED in white bold capitals inside a white outlined rectangle)
- logo at x 51.7, y 71.6, w 20.5, h 2.6 [#FFFFFF]: Partner logos row 1: Atos, DELL Technologies, FUJITSU, GIGABYTE, H3C (White wordmarks of varying size on black)
- logo at x 51.7, y 74.8, w 20.5, h 2.5 [#FFFFFF]: Partner logos row 2: hp, inspur, Lenovo, QCT, SUPERMICRO (White wordmarks; hp in circle, Lenovo in white box with dark type, QCT with cloud icon, SUPERMICRO in oval outline)
- photo at x 7.8, y 78, w 8.3, h 14.8 [#1A1A1A]: NVIDIA BlueField-2 product photo in circle: dark card with chip and heatsink (Circular crop with thin gold rim #B8925A, overlapping the floor, soft shadow)
- photo at x 17.5, y 78.1, w 8.2, h 14.8 [#A58350]: NVIDIA A100/A30 product photo in circle: gold-tan card edge on dark background (Circular crop with thin gold rim, soft shadow)
- photo at x 27.2, y 78.1, w 8.1, h 14.8 [#A58350]: NVIDIA A40/A10 product photo in circle: gold-tan card edge on dark background (Circular crop with thin gold rim, soft shadow)
- photo at x 36.8, y 78.3, w 8.2, h 14.9 [#1A1A1A]: NVIDIA Aerial A100 product photo in circle: dark GPU module with gold heatsink (Circular crop with thin gold rim, soft shadow)
- text at x 9.7, y 87.8, w 4.3, h 3.3 [DIN Pro Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA BlueField-2 (Two lines: NVIDIA / BlueField-2)
- text at x 19.8, y 87.8, w 3.5, h 3.3 [DIN Pro Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA A100/A30 (Two lines: NVIDIA / A100/A30)
- text at x 29.7, y 87.8, w 3, h 3.3 [DIN Pro Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA A40/A10 (Two lines: NVIDIA / A40/A10)
- text at x 38.4, y 87.9, w 5.2, h 1.5 [DIN Pro Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA Aerial A100 (Two lines: NVIDIA Aerial / A100)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 27.2, y 40.2, w 45.5, h 23.6: 171 by 50 pixels
- image at x 37.3, y 69.7, w 9.2, h 9.6: 647 by 381 pixels
- image at x 35.3, y 58.6, w 29.8, h 2.8: 3576 by 192 pixels
- image at x 63.8, y 25.9, w 6.1, h 9.0: 202 by 168 pixels
- image at x 30.0, y 26.7, w 6.3, h 8.0: 202 by 145 pixels
- image at x 52.7, y 26.9, w 5.9, h 7.8: 198 by 148 pixels
- image at x 44.3, y 65.8, w 11.4, h 3.3: 1372 by 222 pixels
- image at x 42.5, y 45.5, w 14.9, h 2.5: 1791 by 167 pixels
- image at x 42.6, y 26.4, w 3.4, h 8.0: 108 by 143 pixels
- image at x 33.5, y 52.1, w 4.9, h 2.6: 588 by 177 pixels
- image at x 27.9, y 52.1, w 4.9, h 2.5: 588 by 167 pixels
- image at x 44.7, y 52.2, w 4.9, h 2.4: 588 by 163 pixels
- image at x 56.0, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 61.6, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 39.1, y 52.3, w 4.9, h 2.2: 587 by 149 pixels
- image at x 67.2, y 52.3, w 4.9, h 2.1: 588 by 144 pixels
- image at x 50.4, y 52.3, w 4.9, h 2.1: 588 by 143 pixels
- image at x 55.1, y 72.1, w 5.2, h 1.2: 627 by 82 pixels
- image at x 65.3, y 73.8, w 1.7, h 3.6: 204 by 245 pixels
- image at x 69.6, y 74.8, w 2.5, h 2.3: 305 by 155 pixels
- text at x 23.2, y 7.9, w 53.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA EGX ENTERPRISE PLATFORM
- text at x 31.1, y 12.5, w 37.7, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Enterprise-Ready Suite of AI and Data Science Software
- text at x 30.6, y 23.7, w 5.1, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: DATA PREP
- text at x 43.0, y 23.6, w 2.8, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: TRAIN
- text at x 53.4, y 23.6, w 4.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: SIMULATE
- text at x 63.5, y 23.6, w 6.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: ORCHESTRATE
- text at x 42.7, y 41.1, w 14.5, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: NVIDIA AI ENTERPRISE
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU CLOUD REGISTRY
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDF
- text at x 40.0, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDNN
- text at x 46.0, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuML
- text at x 51.0, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TAO
- text at x 62.0, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Triton
- text at x 36.9, y 59.3, w 17.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA CUDA, DOCA, vGPU, Magnum IO,
- text at x 54.5, y 59.3, w 4.2, h 1.7 [DINPro-Black; font size 1.73; #FFFFFF]: Aerial 5G
- text at x 58.6, y 59.3, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ,
- text at x 59.1, y 59.3, w 4.5, h 1.7 [DINPro-Black; font size 1.73; #FFFFFF]: Morpheus
- text at x 46.4, y 66.7, w 7.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VMware vSphere
- text at x 38.4, y 87.9, w 5.2, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA Aerial
- text at x 9.7, y 87.8, w 4.3, h 3.3 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA BlueField-2
- text at x 19.8, y 87.8, w 3.5, h 3.3 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA A100/A30
- text at x 29.7, y 87.8, w 3.0, h 3.3 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA A40/A10
- text at x 40.0, y 89.6, w 1.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A100

### Slide 64

**Text**

Convolutional Network (CNN) / Transformer / Reinforcement Learning / Autoencoders / Long Short-Term Memory (LSTM) / Generative Adversarial Network (GAN)

**Layout**

Six diagrams in a 3 by 2 grid with no slide title, footer or slide number. Top row titles sit at about 21.3% of slide height and bottom row titles at about 51.5%, each title centred above its diagram. Columns are centred at roughly 26%, 50% and 81% of slide width, and the diagrams fill most of the space beneath each title with wide empty margins.

**Visuals**

Six gold line-art technical diagrams, all drawn in thin single-weight strokes with no fill. (1) Convolutional Network (CNN): two rows of boxes and tall vertical slabs with diagonal connecting lines crossing between the rows, ending in a column of narrow stacked bars at right. (2) Transformer: two stacked-block columns, the left one a tall box with horizontal bars and small circle-symbols at its base, the right one a taller box of horizontal bars with a tall stack of blocks above and small circle-symbols at its base, joined by an elbow line from left to right. (3) Reinforcement Learning: a four-quadrant frame; top-left quadrant holds a person icon, a monitor and a grid icon, top-right holds a bar-chart style block and a grid icon, bottom-left holds a grid icon, a person icon and a monitor, bottom-right holds a block with bars and a grid icon, and a right-hand box contains a neural network node graph and a camera-like shape. (4) Autoencoders: a symmetric network of vertical stacks of square cells, narrowing from left to right to a small central bottleneck block and widening again, with crossed lines between layers. (5) Long Short-Term Memory (LSTM): a rectangular frame with horizontal lines passing through, containing small circles, an ellipse, several small rectangular gate boxes, and a circle at the bottom left and another at top right. (6) Generative Adversarial Network (GAN): a horizontal chain of small rectangles and two rounded capsule shapes containing cylinder-like icons, a small square above the right capsule, a small diamond at the far right, and a line returning underneath from the right back to the left. Each diagram has a faint mirrored reflection on the glossy floor below it.

**Design**

Background: Near-black #000000 at the top fading to dark charcoal #2A2A2A glossy floor surface in the lower third, as a full-bleed photograph. Dark cinematic look. The background is near-black at the top (#000000) fading into a dark charcoal floor (#2A2A2A to #3A3A3A) in the lower third, with a glossy reflective surface. Titles are set in DIN Pro Light, regular weight, sentence and title case, about 2.0% of slide height (capitals about 1.4%), with slight letter spacing, colour gold #BD9F63. Diagram lines are gold #BD9F63 at hairline weight, no fills, no shadows, sharp square corners except rounded capsules in the GAN diagram. Accent colour is the same gold throughout.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio background photograph of a black backdrop fading into a glossy charcoal floor with faint reflections of the diagrams (Full-bleed, not cropped or boxed, no overlay; covers the slide. Colours near-black #000000 at top to charcoal #2A2A2A to #3A3A3A at lower third; a faint warm reflection of each diagram appears on the floor below it.)
- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Solid white fill rectangle covering the full slide, hidden beneath the background photograph (Fully obscured by the photograph; no visible effect.)
- title at x 11.4, y 21.3, w 14.8, h 2 [DIN Pro Light, regular weight, sans-serif, title case, slight letter spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Convolutional Network (CNN)
- title at x 47, y 21.3, w 6.3, h 2 [DIN Pro Light, regular weight, sans-serif, title case, slight letter spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Transformer
- title at x 75.3, y 21.3, w 12.2, h 2 [DIN Pro Light, regular weight, sans-serif, title case, slight letter spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Reinforcement Learning
- title at x 15.4, y 51.5, w 6.9, h 2 [DIN Pro Light, regular weight, sans-serif, title case, slight letter spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Autoencoders
- title at x 41.7, y 51.5, w 16.9, h 2 [DIN Pro Light, regular weight, sans-serif, title case, slight letter spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Long Short-Term Memory (LSTM)
- title at x 71.8, y 51.5, w 19.2, h 2 [DIN Pro Light, regular weight, sans-serif, title case, slight letter spacing; font size 2.04% of slide height; #BD9F63; center aligned]: Generative Adversarial Network (GAN)
- diagram at x 9.2, y 27.1, w 19.1, h 14.2 [#BD9F63]: Convolutional Network (CNN) line diagram: two rows of boxes with diagonal connectors and a column of narrow stacked bars at right (Gold #BD9F63 hairline outlines, no fill, sharp corners, centred below its title.)
- diagram at x 45.5, y 24.7, w 9.1, h 19.3 [#BD9F63]: Transformer line diagram: left encoder-style column with bars and circle symbols, right stacked-block column joined by an elbow connector (Gold #BD9F63 hairline outlines, no fill, sharp corners, centred below its title.)
- diagram at x 72.6, y 26.5, w 17.3, h 15.4 [#BD9F63]: Reinforcement Learning line diagram: four-quadrant frame with person, monitor, grid and node-graph icons and a camera-like shape (Gold #BD9F63 hairline outlines, no fill, sharp corners, centred below its title.)
- diagram at x 10.4, y 56.9, w 16.8, h 14.6 [#BD9F63]: Autoencoders line diagram: symmetric stacked-cell network narrowing to a central bottleneck and widening again (Gold #BD9F63 hairline outlines, no fill, sharp corners, centred below its title.)
- diagram at x 43, y 55.5, w 14, h 18 [#BD9F63]: Long Short-Term Memory (LSTM) line diagram: rectangular frame with horizontal lines, gate boxes, circles and an ellipse (Gold #BD9F63 hairline outlines, no fill, sharp corners, centred below its title.)
- diagram at x 70, y 57.9, w 22.8, h 12.8 [#BD9F63]: Generative Adversarial Network (GAN) line diagram: horizontal chain of rectangles and two rounded capsules with cylinder icons, a square above, a diamond at right and a return line (Gold #BD9F63 hairline outlines, no fill, sharp corners except rounded capsules, centred below its title.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 11.4, y 21.3, w 14.8, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Convolutional Network (CNN)
- text at x 47.0, y 21.3, w 6.3, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Transformer
- text at x 75.3, y 21.3, w 12.2, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Reinforcement Learning
- text at x 15.4, y 51.5, w 6.9, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Autoencoders
- text at x 41.7, y 51.5, w 16.9, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Long Short-Term Memory (LSTM)
- text at x 71.8, y 51.5, w 19.2, h 2.0 [DINPro-Light; font size 2.04; #BD9F63]: Generative Adversarial Network (GAN)

### Slide 65

**Text**

NVIDIA’S AI
DLSS
AI Rendering
NATIVE 4K
DLSS 4K
StyleGAN
High-Res Image Generation
GANcraft
3D Scene Generation
GANverse3D
2D to 3D Render
Sim2Real
Quadruped Locomotion
Face Vid2Vid
Audio-Driven Character
Animation
BioMegatron
Medical Language Model
3DGT
3D Ground Truth
SimNet
Physics-Informed AI Model
OrbNet
AI for Quantum Chemistry

**Layout**

A centred title sits at the top of the slide above a 5 by 2 grid of ten equal near-square tiles, with left and right margins of about 3.8% and roughly 2% gaps between tiles. Each tile carries a centred two-line label (bold title over regular subtitle) at its top, and there is no footer or slide number.

**Visuals**

Ten photographic or rendered tiles in a 5 by 2 grid, each with a bronze-grey hairline border and a dark gradient at the top behind its label. Row 1 (left to right): DLSS split comparison of a soldier-like figure in a yellow and camouflage armoured vehicle at a gate, with a left label NATIVE 4K on dark grey and a right green label DLSS 4K; StyleGAN split image with a cat face on the left and a dog face on the right, divided at about the horizontal midpoint; GANcraft voxel-style landscape of green trees, grey rocks, a blue lake and a blocky inset at lower left; GANverse3D split with a grid of real car photographs on the left and a white-lit grid of rendered coloured cars on the right; Sim2Real split with a grey and green rendered quadruped on skateboard-like wheels on the left and a real dark quadruped robot on orange-wheeled skateboard on the right. Row 2 (left to right): Face Vid2Vid split with a real smiling woman on the left and a 3D animated character with blue hair on the right; BioMegatron blurred medical report text with purple and green tags reading TREATMENT and TEST; 3DGT blue industrial frame with green bounding boxes labelled dolly, wheel, wheel and wheel; SimNet colourful fluid-flow streamlines (green, yellow, red, blue) over a black circuit board with heatsinks; OrbNet red and blue molecular orbital lobes above a white and grey ball-and-stick ring molecule with red oxygen atoms on a near-black background. Photos are full-tile crops, not cropped to circles, with no rounded corners.

**Design**

Background: Black #000000 fading to dark grey #2A2A2A at the bottom, with a reflective dark floor surface. Black background with a faint dark grey reflective floor at the bottom. Title and all labels are white (#FFFFFF) in DIN Pro, a condensed grotesque sans-serif: title bold, tile titles medium, subtitles regular. Title cap height about 4% of slide height. Tile titles about 2.5% of slide height and subtitles about 2.0%. Accent colour is NVIDIA green #76B900, used only on the DLSS 4K label. Tile borders are thin hairlines about 1px in bronze-grey #6B5E3E. Tiles have no shadow, no rounded corners and no gradient other than the top darkening. A soft dark shadow sits beneath the bottom row.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Full-slide background fill, black to dark grey gradient (Covers the slide; the floor reflection occupies the lower part below y 85.)
- title at x 44, y 7.9, w 12, h 4.1 [DIN Pro, bold; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA’S AI (Upper case, normal letter-spacing.)
- photo at x 3.8, y 21.7, w 17.2, h 29.1 [#4A4F4A]: DLSS tile: split comparison of armoured figure beside yellow camouflage vehicle at a gate, left NATIVE 4K, right DLSS 4K (Full tile crop, hairline border #6B5E3E, vertical split at midpoint.)
- shape at x 3.8, y 44.9, w 8.6, h 3.7 [#1F1F1F]: NATIVE 4K label bar, left half of DLSS tile (Opaque dark grey bar across lower part of tile.)
- shape at x 12.4, y 44.9, w 8.6, h 3.7 [#76B900]: DLSS 4K label bar, right half of DLSS tile (Opaque NVIDIA green bar.)
- text at x 6.6, y 46.3, w 3, h 1.1 [DIN Pro, bold; font size 1.11% of slide height; #FFFFFF; center aligned]: NATIVE 4K
- text at x 15.5, y 46.3, w 2.4, h 1.1 [DIN Pro, bold; font size 1.11% of slide height; #FFFFFF; center aligned]: DLSS 4K
- text at x 10.9, y 24, w 3.3, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: DLSS
- text at x 9.3, y 26.6, w 6.4, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: AI Rendering
- photo at x 22.8, y 21.7, w 17.1, h 29.1 [#8A8478]: StyleGAN tile: split image of a cat face (left) and a dog face (right) (Full tile crop, hairline border #6B5E3E, split near horizontal midpoint.)
- text at x 28.4, y 24, w 5.8, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: StyleGAN
- text at x 24.5, y 26.6, w 13.7, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: High-Res Image Generation
- photo at x 41.5, y 21.7, w 17.1, h 29.1 [#3C7A3A]: GANcraft tile: voxel-style landscape with green trees, grey rocks, blue lake and a blocky inset (Full tile crop, hairline border #6B5E3E.)
- text at x 47.2, y 24, w 5.7, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: GANcraft
- text at x 44.9, y 26.6, w 10.3, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: 3D Scene Generation
- photo at x 60.1, y 21.8, w 17.1, h 29.1 [#E8E8E8]: GANverse3D tile: grid of real car photos at left, white-lit grid of rendered coloured cars at right (Full tile crop, hairline border #6B5E3E.)
- text at x 64.9, y 24, w 7.8, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: GANverse3D
- text at x 64.8, y 26.6, w 8.1, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: 2D to 3D Render
- photo at x 79, y 21.7, w 17.1, h 29.2 [#6E5E4E]: Sim2Real tile: rendered grey quadruped on orange-wheeled skateboard (left) and real dark quadruped on orange-wheeled skateboard (right) (Full tile crop, hairline border #6B5E3E.)
- text at x 84.6, y 24, w 6, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: Sim2Real
- text at x 81.8, y 26.6, w 11.5, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Quadruped Locomotion
- photo at x 3.8, y 54, w 17.3, h 29.5 [#B07A62]: Face Vid2Vid tile: real smiling woman (left) and 3D animated character with blue hair (right) (Full tile crop, hairline border #6B5E3E, split at midpoint.)
- text at x 8.6, y 56.4, w 7.8, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: Face Vid2Vid
- text at x 6.7, y 59, w 11.9, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Audio-Driven Character
- text at x 10, y 61.1, w 5, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Animation
- photo at x 22.8, y 54, w 17.3, h 29.5 [#2A1F33]: BioMegatron tile: blurred medical report text with purple and green tags reading TREATMENT and TEST (Full tile crop, hairline border #6B5E3E, motion blur on text.)
- text at x 27.3, y 56.4, w 8, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: BioMegatron
- text at x 25.1, y 59, w 12.3, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Medical Language Model
- photo at x 41.5, y 54, w 17.1, h 29.5 [#4A7FA8]: 3DGT tile: blue industrial frame with green bounding boxes labelled dolly, wheel, wheel, wheel (Full tile crop, hairline border #6B5E3E, green box outlines.)
- text at x 48.4, y 56.3, w 3.3, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: 3DGT
- text at x 46, y 59, w 8.1, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: 3D Ground Truth
- photo at x 60.1, y 54, w 17.2, h 29.5 [#2EA02E]: SimNet tile: colourful fluid streamlines over a black circuit board with heatsinks (Full tile crop, hairline border #6B5E3E.)
- text at x 66.3, y 56.3, w 4.6, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: SimNet
- text at x 62, y 59, w 13.3, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: Physics-Informed AI Model
- photo at x 79, y 54, w 17, h 29.5 [#1A1A1A]: OrbNet tile: red and blue molecular orbital lobes over a ball-and-stick ring molecule with red oxygen atoms (Full tile crop on near-black background, hairline border #6B5E3E.)
- text at x 85.4, y 56.3, w 4.5, h 2.5 [DIN Pro, medium; font size 2.47% of slide height; #FFFFFF; center aligned]: OrbNet
- text at x 81.2, y 59, w 12.8, h 2 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: AI for Quantum Chemistry

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 22.8, y 54.2, w 17.1, h 29.1: 353 by 336 pixels
- image at x 41.5, y 21.7, w 17.1, h 29.1: 300 by 286 pixels
- image at x 41.5, y 54.2, w 17.1, h 29.1: 267 by 255 pixels
- image at x 60.1, y 54.6, w 17.1, h 28.7: 911 by 857 pixels
- image at x 79.0, y 55.1, w 17.1, h 28.2: 434 by 384 pixels
- image at x 3.9, y 21.7, w 8.6, h 29.1: 565 by 1080 pixels
- image at x 12.4, y 21.7, w 8.6, h 29.1: 565 by 1080 pixels
- image at x 87.6, y 21.7, w 8.5, h 29.2: 411 by 783 pixels
- image at x 12.4, y 54.1, w 8.6, h 29.1: 260 by 498 pixels
- image at x 3.8, y 54.1, w 8.6, h 29.1: 267 by 510 pixels
- image at x 22.8, y 21.7, w 8.6, h 29.1: 265 by 506 pixels
- image at x 60.1, y 21.8, w 8.6, h 29.1: 539 by 1031 pixels
- image at x 68.7, y 21.8, w 8.6, h 29.1: 354 by 678 pixels
- image at x 31.3, y 21.7, w 8.5, h 29.1: 248 by 463 pixels
- image at x 79.0, y 23.9, w 8.5, h 27.0: 354 by 625 pixels
- image at x 3.8, y 21.7, w 17.2, h 13.3: 495 by 215 pixels
- image at x 3.8, y 21.7, w 17.2, h 13.3: 495 by 215 pixels
- image at x 60.1, y 21.7, w 17.1, h 13.2: 493 by 214 pixels
- image at x 60.1, y 21.7, w 17.1, h 13.2: 493 by 214 pixels
- image at x 3.8, y 54.1, w 17.5, h 12.5: 504 by 203 pixels
- image at x 3.8, y 54.1, w 17.5, h 12.5: 504 by 203 pixels
- image at x 22.8, y 54.1, w 17.2, h 12.5: 494 by 203 pixels
- image at x 22.8, y 54.1, w 17.2, h 12.5: 494 by 203 pixels
- image at x 60.1, y 54.1, w 17.2, h 11.3: 494 by 183 pixels
- image at x 60.1, y 54.1, w 17.2, h 11.3: 494 by 183 pixels
- image at x 41.5, y 21.7, w 17.1, h 11.3: 493 by 183 pixels
- image at x 41.5, y 21.7, w 17.1, h 11.3: 493 by 183 pixels
- image at x 79.0, y 21.7, w 17.1, h 11.3: 493 by 183 pixels
- image at x 79.0, y 21.7, w 17.1, h 11.3: 493 by 183 pixels
- image at x 41.5, y 54.1, w 17.1, h 11.3: 492 by 183 pixels
- image at x 41.5, y 54.1, w 17.1, h 11.3: 492 by 183 pixels
- image at x 79.0, y 54.1, w 17.0, h 11.3: 491 by 183 pixels
- image at x 79.0, y 54.1, w 17.0, h 11.3: 491 by 183 pixels
- image at x 22.8, y 21.7, w 17.1, h 11.0: 493 by 179 pixels
- image at x 22.8, y 21.7, w 17.1, h 11.0: 493 by 179 pixels
- text at x 44.0, y 7.9, w 12.0, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA’S AI
- text at x 10.9, y 24.0, w 3.3, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: DLSS
- text at x 28.4, y 24.0, w 5.8, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: StyleGAN
- text at x 47.2, y 24.0, w 5.7, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: GANcraft
- text at x 64.9, y 24.0, w 7.8, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: GANverse3D
- text at x 84.6, y 24.0, w 6.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: Sim2Real
- text at x 9.3, y 26.6, w 6.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: AI Rendering
- text at x 24.5, y 26.6, w 13.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: High-Res Image Generation
- text at x 44.9, y 26.6, w 10.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 3D Scene Generation
- text at x 64.8, y 26.6, w 8.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 2D to 3D Render
- text at x 81.8, y 26.6, w 11.5, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Quadruped Locomotion
- text at x 8.6, y 56.4, w 7.8, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: Face Vid2Vid
- text at x 27.3, y 56.4, w 8.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: BioMegatron
- text at x 46.1, y 56.4, w 8.0, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: BioMegatron
- text at x 48.4, y 56.3, w 3.3, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: 3DGT
- text at x 66.3, y 56.3, w 4.6, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: SimNet
- text at x 85.4, y 56.3, w 4.5, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: OrbNet
- text at x 6.7, y 59.0, w 11.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Audio-Driven Character
- text at x 25.1, y 59.0, w 12.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Medical Language Model
- text at x 43.9, y 59.0, w 12.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Medical Language Model
- text at x 46.0, y 59.0, w 8.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: 3D Ground Truth
- text at x 62.0, y 59.0, w 13.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Physics-Informed AI Model
- text at x 81.2, y 59.0, w 12.8, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: AI for Quantum Chemistry
- text at x 10.0, y 61.1, w 5.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Animation
- text at x 6.6, y 46.3, w 3.0, h 1.1 [DINPro-Bold; font size 1.11; #FFFFFF]: NATIVE 4K
- text at x 15.5, y 46.3, w 2.4, h 1.1 [DINPro-Bold; font size 1.11; #FFFFFF]: DLSS 4K

### Slide 66

**Text**

NGC PRE-TRAINED MODELS
Production-Quality AI Models
Trained by Experts for Enterprise Deployment
Credentials to Find Models You Trust
Continuously Updated to be State-of-the-Art
Adapt with NVIDIA TAO and Orchestrate
with NVIDIA Fleet Command
Reference AI Code Samples to Ease
Application Development

**Layout**

Text block sits on the left third, vertically centred, left-aligned at about 6.7% from the slide edge; the title is the largest line followed by a subtitle and five bullet-style lines with wrapped continuations. The right side holds a tilted screenshot mockup of the NVIDIA NGC catalog page in perspective, extending toward the right margin. No visible footer, slide number or logo.

**Visuals**

Perspective mockup of a web browser window showing the NVIDIA NGC catalog page for Gaze Estimation, rotated in 3D with its left edge nearer the viewer. Left panel (green header, white card): a green header with an eye-in-frame icon and the label GAZE ESTIMATION; below it fields Application (Gaze detection for a person - point of regard (X, Y, Z) and gaze vector (theta and phi)), Popularity (green bar sparkline), Domain (Computer Vision), Usage (Unrestricted), License (TLT Licence, green link), Training Dataset (Proprietary dataset with more than 220k images), Performance with horizontal green bars labelled T4 (1698 FPS), Xavier (704 FPS) and NX (510 FPS), tag chips CV, Computer Vision, DL, Deep Learning, Gaze, TLT, and a link Expand Credentials. Right page: top bar with NVIDIA NGC | CATALOG logo and a green Download button with dropdown arrow; section headings in green: Model Overview, Model Architecture, Training Algorithm, How to use this model, Input, Output, with grey body paragraphs. A small photograph of a woman with long dark hair looking down, seated in a car interior with a green eye-gaze overlay line, boxed with a thin edge under Training Algorithm. Lighting is soft and dim; dominant colours are dark grey, white and NVIDIA green.

**Design**

Background: Black #000000 with a dark grey reflective floor gradient at the bottom. Black background with a dark grey reflective floor gradient at the bottom. Title in bold white condensed sans-serif (DIN Pro Bold style), body in regular white DIN Pro. Screen mockup in light grey #D9D9D9 with dark header #1A1A1A and accent green #76B900. Title about 4.1% of slide height, body about 2.2% of slide height. Flat rectangular card with thin shadow beneath the mockup.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: background fill (full-bleed black backdrop covering the slide)
- photo at x 0, y 0, w 100, h 100: floor/backdrop image, dark grey reflective studio floor (full-bleed, covers the slide, dark grey with reflections at the bottom)
- illustration at x 47, y 10, w 44, h 75 [#D9D9D9]: tilted NVIDIA NGC Gaze Estimation catalog page mockup with left card panel and right model documentation page, including small photo of woman in car (perspective-rotated, left edge nearer viewer; dark header bar #1A1A1A; green accent #76B900; soft drop shadow below)
- title at x 6.7, y 33.8, w 29.8, h 4.1 [DIN Pro, bold, sans-serif, all capitals; font size 4.07% of slide height; #FFFFFF; left aligned]: NGC PRE-TRAINED MODELS
- subtitle at x 6.7, y 38.4, w 19.8, h 2.7 [DIN Pro, regular, sans-serif; font size 2.72% of slide height; #FFFFFF; left aligned]: Production-Quality AI Models
- body at x 6.7, y 43.9, w 25.4, h 2.2 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: Trained by Experts for Enterprise Deployment
- body at x 6.7, y 48.7, w 20.5, h 2.2 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: Credentials to Find Models You Trust
- body at x 6.7, y 53.4, w 24.6, h 2.2 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: Continuously Updated to be State-of-the-Art
- body at x 6.7, y 58.2, w 22.2, h 4.6 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: Adapt with NVIDIA TAO and Orchestrate / with NVIDIA Fleet Command (two lines, line spacing about 2.4% of slide height)
- body at x 6.7, y 65.3, w 20.1, h 4.6 [DIN Pro, regular, sans-serif; font size 2.22% of slide height; #FFFFFF; left aligned]: Reference AI Code Samples to Ease / Application Development (two lines, line spacing about 2.4% of slide height)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 33.8, w 29.8, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NGC PRE-TRAINED MODELS
- text at x 6.7, y 38.4, w 19.8, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Production-Quality AI Models
- text at x 6.7, y 43.9, w 25.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Trained by Experts for Enterprise Deployment
- text at x 6.7, y 48.7, w 20.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Credentials to Find Models You Trust
- text at x 6.7, y 53.4, w 24.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Continuously Updated to be State-of-the-Art
- text at x 6.7, y 58.2, w 22.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Adapt with NVIDIA TAO and Orchestrate
- text at x 6.7, y 60.6, w 15.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: with NVIDIA Fleet Command
- text at x 6.7, y 65.3, w 20.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Reference AI Code Samples to Ease
- text at x 6.7, y 67.7, w 13.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Application Development

### Slide 67

**Text**

ANNOUNCING
NVIDIA TAO FRAMEWORK
Train | Adapt | Optimize
Customize Pre-Trained Models for
Domain-Specific Applications
Federated Learning Enables Model Training
Collaboration while Protecting Data Privacy
Produce State-of-the-Art Models in Hours
NVIDIA NGC
NVIDIA TAO

**Layout**

Left-aligned text block starts at x 6.7% and sits in the vertical middle band (y 34.7% to 64.7%), with no title at the top of the slide and no footer or slide number. On the right, two circular badges sit side by side around x 42.8% to 73.7%, centred vertically at about y 51%, joined by a short horizontal arrow; their captions sit centred beneath them at y 67.8%. Large empty black margins surround the content.

**Visuals**

Two circular badges joined by an arrow, with a small photographic-style icon group. Left badge (NVIDIA NGC): a dark circular disc with a thin gold-grey rim, containing a stack of three grey metallic cards (front card with a white-outlined neural network diagram of gold nodes and a grey circular check-mark badge at its lower right corner). A thin white horizontal arrow runs from the left circle's right edge to the right circle's left edge, with a small arrowhead at the right end. Right badge (NVIDIA TAO): a dark circular disc with a thin gold-grey rim, containing a circular cycle of three thin white curved arrows around a grey metallic gear at top, a small gold-node neural network diagram at lower left, and a set of grey vertical slider or tuning bars at lower right. Icons are rendered in grey metal with gold accents; lighting is soft and top-lit against the black background. No photograph of people; no chart or table.

**Design**

Background: Black #000000 at top grading to dark charcoal #2A2A2A near the bottom, with a textured dark floor surface (full-bleed image). Black background fading to dark charcoal at the bottom with a faint textured floor and a soft dark shadow beneath the badges. Titles and body text are white #FFFFFF; accent colour is gold #B8A36A on the badge rims and neural nodes, with grey metal #9A9A9A on icons. Typeface is DIN Pro (a DIN-style grotesque, sans-serif): ANNOUNCING in DIN Pro Bold, all-caps, about 2.96% of slide height; NVIDIA TAO FRAMEWORK in DIN Pro Regular, all-caps, about 4.07%; Train | Adapt | Optimize in DIN Pro Regular, about 2.72%; body bullets in DIN Pro Regular, about 2.22%; captions in DIN Pro Regular, about 1.98%. Badge discs are filled #111111 with a 1px gold-grey #8A7A55 rim; connector line is white #FFFFFF about 0.2% of height thick. No corner radii, gradients on shapes, or drop shadows beyond the soft floor shadow.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide white fill behind the background image (covered by the background) (No visible effect; covered entirely by the background image.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark studio background: black top fading to dark grey textured floor with a soft shadow near the badges (3840 by 2160 pixels, full-bleed, not cropped, no overlay; the image is placed twice at identical bounds.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed dark studio background (duplicate placement of the same background image) (3840 by 2160 pixels, full-bleed, not cropped, no overlay.)
- shape at x 42.8, y 40.2, w 12.9, h 22.8 [#111111]: Left circular badge disc (Circle filled #111111 with a thin gold-grey rim approximately #8A7A55, about 0.2% of slide height wide; no shadow.)
- shape at x 60.8, y 40.2, w 12.9, h 22.8 [#111111]: Right circular badge disc (Circle filled #111111 with a thin gold-grey rim approximately #8A7A55, about 0.2% of slide height wide; no shadow.)
- illustration at x 44.4, y 46.3, w 9.2, h 10.5 [#9A9A9A]: Stack of three grey metallic cards with a white-outlined neural network of gold nodes on the front card and a grey check-mark badge at lower right, inside the NVIDIA NGC badge (Image 333 by 212 pixels; overlaps the left badge disc; check badge is a grey circle with a white tick.)
- line at x 56.4, y 51.9, w 3.7, h 0.5 [#FFFFFF]: Short horizontal arrow from the NVIDIA NGC badge to the NVIDIA TAO badge (Thin white line about 0.15% of slide height thick with a small filled arrowhead at the right end pointing into the TAO badge.)
- illustration at x 62.3, y 42.8, w 9.6, h 16.7 [#9A9A9A]: Cycle graphic in the NVIDIA TAO badge: grey gear at top, three curved white arrows forming a loop, gold-node neural network at lower left, and grey slider bars at lower right (Image 364 by 357 pixels; overlaps the right badge disc; arrows are thin white strokes with arrowheads.)
- text at x 6.7, y 34.7, w 10.6, h 3 [DIN Pro Bold, all caps; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING
- title at x 6.7, y 38, w 26.4, h 4.1 [DIN Pro Regular, all caps; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA TAO FRAMEWORK
- subtitle at x 6.7, y 42.6, w 17.5, h 2.7 [DIN Pro Regular, normal case; font size 2.72% of slide height; #FFFFFF; left aligned]: Train | Adapt | Optimize
- body at x 6.7, y 48.1, w 19.4, h 4.6 [DIN Pro Regular, normal case, line spacing about 1.0 with a blank line between paragraphs; font size 2.22% of slide height; #FFFFFF; left aligned]: Customize Pre-Trained Models for / Domain-Specific Applications (Two lines; no bullet markers.)
- body at x 6.7, y 55.3, w 24.6, h 4.6 [DIN Pro Regular, normal case, line spacing about 1.0; font size 2.22% of slide height; #FFFFFF; left aligned]: Federated Learning Enables Model Training / Collaboration while Protecting Data Privacy (Two lines; no bullet markers.)
- body at x 6.7, y 62.5, w 23.3, h 2.2 [DIN Pro Regular, normal case; font size 2.22% of slide height; #FFFFFF; left aligned]: Produce State-of-the-Art Models in Hours (Single line; no bullet markers.)
- caption at x 46.2, y 67.8, w 6, h 2 [DIN Pro Regular, all caps; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA NGC
- caption at x 64.3, y 67.8, w 5.7, h 2 [DIN Pro Regular, all caps; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA TAO

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 62.3, y 42.8, w 9.6, h 16.7: 364 by 357 pixels
- image at x 44.4, y 46.3, w 9.2, h 10.5: 333 by 212 pixels
- text at x 6.7, y 38.0, w 26.4, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: NVIDIA TAO FRAMEWORK
- text at x 6.7, y 34.7, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 42.6, w 17.5, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Train | Adapt | Optimize
- text at x 6.7, y 48.1, w 19.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Customize Pre-Trained Models for
- text at x 6.7, y 50.5, w 16.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Domain-Specific Applications
- text at x 6.7, y 55.3, w 24.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Federated Learning Enables Model Training
- text at x 6.7, y 57.7, w 24.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Collaboration while Protecting Data Privacy
- text at x 6.7, y 62.5, w 23.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Produce State-of-the-Art Models in Hours
- text at x 46.2, y 67.8, w 6.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA NGC
- text at x 64.3, y 67.8, w 5.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA TAO

### Slide 68

**Text**

ANNOUNCING
NVIDIA FLEET COMMAND
Securely Orchestrate AI Fleet at the
Edge of the Network
Control and Manage Millions of AI-Powered
Devices from Any Cloud
Secure from Boot, Attestation, Uplink and
Downlink, to Confidential AI Enclave
Centrally Monitor Health and Remotely Fix
Edge Systems
NVIDIA NGC
NVIDIA TAO
NVIDIA FLEET COMMAND

**Layout**

Two-zone horizontal layout on a dark stage: a left text column starts at about 6.7% from the left edge, with the ANNOUNCING kicker, title, subtitle and three body paragraphs stacked top-to-bottom, vertically centred around 38% to 68% of the height. To the right, three equal circular badges sit on one horizontal axis at about 52% of the height, joined left to right by two short arrows, each with a caption centred below it at about 68% of the height. No title bar, footer, logo or slide number is visible; the top third of the slide is empty black.

**Visuals**

Three equal dark circular badges with thin warm-gold rims, connected by two thin white right-pointing arrows. Badge 1 (NVIDIA NGC): a stack of three grey folder cards with a small neural-network diagram (gold nodes and white lines, roughly 3 by 3 layers) on the front card and a grey circular check mark badge at its lower right corner. Badge 2 (NVIDIA TAO): a grey cog/gear at top centre, a circular arrangement of thin white curved arrows around the badge (top-left arrow pointing up-right, top-right arrow pointing down, bottom arrow pointing left), a small gold neural-network icon at lower left and a grey bar-chart style set of three vertical sliders at lower right. Badge 3 (NVIDIA FLEET COMMAND): a glossy gold sphere at centre with eight thin white arrows radiating outward in all eight directions (up, down, left, right and four diagonals). Imagery is flat-vector with metallic grey and gold tones on black, not photographic.

**Design**

Background: Near-black #000000 at the top fading into dark charcoal #1E1E1E grey with a soft brushed-metal floor texture in the lower half, with a faint dark shadow beneath the badge row.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Full-slide background fill, black gradient to charcoal with brushed texture (Rectangle covering the whole slide, behind everything; top black to lower charcoal #1E1E1E; no border)
- shape at x 40, y 74, w 30, h 10 [#0A0A0A]: Soft floor shadow ellipse under the badge row (Blurred dark ellipse, opacity about 60%, no outline)
- shape at x 42.8, y 40.2, w 12.8, h 22.8 [#111111]: Circular badge 1 (NVIDIA NGC backdrop) (Filled circle, near-black #111111, thin warm-gold rim about 2 px in #8C7B5A fading to light at top left, no shadow)
- shape at x 60.8, y 40.2, w 12.8, h 22.8 [#111111]: Circular badge 2 (NVIDIA TAO backdrop) (Filled circle, near-black #111111, thin warm-gold rim about 2 px in #8C7B5A, no shadow)
- shape at x 78.7, y 40.2, w 12.8, h 22.8 [#111111]: Circular badge 3 (NVIDIA FLEET COMMAND backdrop) (Filled circle, near-black #111111, thin warm-gold rim about 2 px in #8C7B5A, no shadow)
- image at x 44.4, y 46.3, w 9.2, h 10.5 [#9A9A9A]: NGC illustration: three stacked grey folder cards with a gold neural-network icon and grey check badge, inside badge 1 (Placed raster image 333 by 212 px, transparent background, sits over the NGC circle; the check badge overlaps the folder corner)
- image at x 62.3, y 42.8, w 9.6, h 16.7 [#8A8A8A]: TAO illustration: grey cog, circular white arrows, gold neural-network icon and three grey sliders, inside badge 2 (Placed raster image 364 by 357 px, transparent background, sits over the TAO circle)
- image at x 81.1, y 43.1, w 8.3, h 16.6 [#C9A96E]: Fleet Command illustration: gold sphere with eight white radiating arrows, inside badge 3 (Placed raster image 264 by 298 px, transparent background, sits over the Fleet Command circle)
- line at x 56.4, y 51.6, w 3.7, h 0.5 [#FFFFFF]: Arrow from badge 1 to badge 2 (Thin white line about 1 px with small filled arrowhead at right end)
- line at x 74.3, y 51.6, w 3.7, h 0.5 [#FFFFFF]: Arrow from badge 2 to badge 3 (Thin white line about 1 px with small filled arrowhead at right end)
- title at x 6.7, y 34.7, w 10.6, h 3 [DIN Pro Bold, sans-serif, uppercase; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING (Bold grotesque, all caps, normal letter-spacing, sits above the title)
- title at x 6.7, y 38, w 26.3, h 4.1 [DIN Pro Regular, sans-serif, uppercase, normal weight; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA FLEET COMMAND (Regular-weight DIN style grotesque, all caps, single line)
- subtitle at x 6.7, y 42.6, w 24.6, h 5.6 [DIN Pro Regular, sans-serif, sentence case, normal weight; font size 2.72% of slide height; #FFFFFF; left aligned]: Securely Orchestrate AI Fleet at the / Edge of the Network (Two lines, line spacing about 1.1)
- body at x 6.7, y 51.1, w 24.4, h 4.6 [DIN Pro Regular, sans-serif, sentence case, normal weight; font size 2.22% of slide height; #FFFFFF; left aligned]: Control and Manage Millions of AI-Powered / Devices from Any Cloud (Two lines, line spacing about 1.1, paragraph gap before the next block)
- body at x 6.7, y 58.2, w 23.4, h 4.6 [DIN Pro Regular, sans-serif, sentence case, normal weight; font size 2.22% of slide height; #FFFFFF; left aligned]: Secure from Boot, Attestation, Uplink and / Downlink, to Confidential AI Enclave (Two lines, line spacing about 1.1)
- body at x 6.7, y 65.4, w 23.9, h 4.6 [DIN Pro Regular, sans-serif, sentence case, normal weight; font size 2.22% of slide height; #FFFFFF; left aligned]: Centrally Monitor Health and Remotely Fix / Edge Systems (Two lines, line spacing about 1.1)
- caption at x 46.2, y 67.8, w 6, h 2 [DIN Pro Regular, sans-serif, uppercase, normal weight; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA NGC (Label centred under badge 1)
- caption at x 64.3, y 67.8, w 5.7, h 2 [DIN Pro Regular, sans-serif, uppercase, normal weight; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA TAO (Label centred under badge 2)
- caption at x 79, y 67.8, w 12.7, h 2 [DIN Pro Regular, sans-serif, uppercase, normal weight; font size 1.98% of slide height; #FFFFFF; center aligned]: NVIDIA FLEET COMMAND (Label centred under badge 3)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 62.3, y 42.8, w 9.6, h 16.7: 364 by 357 pixels
- image at x 81.1, y 43.1, w 8.3, h 16.6: 264 by 298 pixels
- image at x 44.4, y 46.3, w 9.2, h 10.5: 333 by 212 pixels
- text at x 6.7, y 38.0, w 26.3, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: NVIDIA FLEET COMMAND
- text at x 6.7, y 34.7, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 42.6, w 24.6, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Securely Orchestrate AI Fleet at the
- text at x 6.7, y 45.5, w 13.8, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Edge of the Network
- text at x 6.7, y 51.1, w 24.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Control and Manage Millions of AI-Powered
- text at x 6.7, y 53.5, w 13.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Devices from Any Cloud
- text at x 6.7, y 58.2, w 23.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Secure from Boot, Attestation, Uplink and
- text at x 6.7, y 60.6, w 20.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Downlink, to Confidential AI Enclave
- text at x 6.7, y 65.4, w 23.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Centrally Monitor Health and Remotely Fix
- text at x 6.7, y 67.8, w 7.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Edge Systems
- text at x 46.2, y 67.8, w 6.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA NGC
- text at x 64.3, y 67.8, w 5.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA TAO
- text at x 79.0, y 67.8, w 12.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: NVIDIA FLEET COMMAND

### Slide 69

**Text**

entry:6 / exit:6 / roi2_front dir1:1 dir2:1 / roi2_left dir1:0 dir2:0 / roi1_front dir1:1 dir2:1 / roi1_back dir1:0 dir2:0 / roi1_right dir1:0 dir2:0 / 12 / roi1_back dir1:0 dir2:0 / Extruder Tip / Sealant (x18 in lower panel)

**Layout**

Three rectangular video panels on a black field: two equal panels side by side across the upper half (left panel x 1.6 to 49.6 percent, right panel x 50.3 to 98.3 percent, both y 1.1 to 48.9 percent) and one equal panel centred in the lower half (x 26 to 74 percent, y 50.2 to 98.1 percent). Gutters are about 0.7 percent of width horizontally and about 1.3 percent vertically. No title, footer, or slide number.

**Visuals**

Three camera frames with computer-vision overlays. Upper left: a factory floor with a blue heatmap overlay (blue to yellow-red hotspot near top centre-left) covering the floor, a red line running diagonally from upper left (about x 22 y 17 percent of the panel area) to lower right, and red text 'entry:6' and 'exit:6' near the centre. Several people in blue coats walk on the floor. Upper right: a service garage with two Jeep SUVs on lifts (a silver SUV in the upper centre and a white Jeep Cherokee in the foreground right), a person in a blue coat working under the car at right and another standing centre-left; green bounding boxes and green polygon regions with blue labels overlay the scene. Lower centre: a close view of a car body in silver-grey sheet metal with a robotic sealant extruder (blue and black tool at upper left) depositing pink-red sealant beads along seams; each bead carries a small pink label reading 'Sealant' and a blue label 'Extruder Tip' sits at the tip. Lighting is even overhead fluorescent light in the two garage/factory frames; the sealant frame is evenly lit with cool grey tones. Dominant colours: upper left blue and grey, upper right grey and white with green overlays, lower centre silver with pink overlays. All panels are boxed, not cropped, with sharp rectangular edges and no overlay on the panel frames.

**Design**

Background: Solid black #000000 field behind three framed video panels. Solid black background (#000000) with three hard-edged video rectangles and no rounded corners, shadows or gradients. Overlay text is small sans-serif, red #E01B24 for the entry/exit counts, blue #1F3BFF for the garage labels, green #22C55E for bounding boxes and polygons, and pink #E8387A labels with white text for the sealant tags. Measurement data for this slide reports a full-slide white fill (#FFFFFF) beneath the two full-slide images; the rendered slide shows black between the panels.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 1.6, y 1.1, w 48, h 47.8 [#3A6FD8]: Upper-left video frame: factory floor with people in blue coats, workstations and shelving, with blue-to-yellow heatmap overlay and red entry/exit counting line (Boxed, uncropped, sharp corners, 1920x1080 image; heatmap overlay at about 50 percent opacity; red line #E01B24 about 0.3 percent stroke width running from upper left to lower right.)
- text at x 35.5, y 35, w 5.5, h 4.5 [Sans-serif (Arial-like), regular; font size 1.1% of slide height; #E01B24; center aligned]: entry:6 / exit:6 (Two stacked lines, line spacing about 1.2; sits on the floor over the heatmap.)
- photo at x 50.3, y 1.1, w 48, h 47.8 [#8A8F94]: Upper-right video frame: service garage with silver and white Jeep SUVs on lifts, a worker in blue coat under the white Jeep and another in the centre, with green detection boxes and polygon regions (Boxed, uncropped, sharp corners, 1920x1080 image; green boxes #22C55E about 0.2 percent stroke; overhead fluorescent light; grey and white dominant.)
- text at x 63.8, y 21, w 8, h 3 [Sans-serif (Arial-like), regular; font size 1% of slide height; #1F3BFF; left aligned]: roi2_front / dir1:1 dir2:1 (Two lines, line spacing about 1.0; overlaid on the garage floor.)
- text at x 65, y 28, w 8, h 3 [Sans-serif (Arial-like), regular; font size 1% of slide height; #1F3BFF; left aligned]: roi2_left / dir1:0 dir2:0 (Two lines, line spacing about 1.0.)
- text at x 72, y 33, w 8, h 3 [Sans-serif (Arial-like), regular; font size 1% of slide height; #1F3BFF; left aligned]: roi1_front / dir1:1 dir2:1 (Two lines, line spacing about 1.0.)
- text at x 87, y 33, w 10, h 3 [Sans-serif (Arial-like), regular; font size 1% of slide height; #1F3BFF; left aligned]: roi1_back / dir1:0 dir2:0 (Two lines, line spacing about 1.0.)
- text at x 61.5, y 18, w 2, h 2.5 [Sans-serif (Arial-like), regular; font size 1% of slide height; #1F3BFF; left aligned]: 12 (Small label on the green box around the worker at upper centre.)
- photo at x 26, y 50.2, w 48, h 47.9 [#B8BEC4]: Lower-centre video frame: close view of a silver car body with a robotic sealant extruder depositing pink sealant beads along seams, with labelled detection overlays (Boxed, uncropped, sharp corners, 1920x1080 image; cool even lighting; silver and grey dominant with a blue and black robot arm at upper left.)
- text at x 33.3, y 76.8, w 4.5, h 1.6 [Sans-serif (Arial-like), regular; font size 0.9% of slide height; #FFFFFF; center aligned]: Extruder Tip (White text on a blue #1F5FBF rounded label, about 0.3 percent corner radius.)
- text at x 34, y 30, w 40, h 62 [Sans-serif (Arial-like), regular; font size 0.9% of slide height; #FFFFFF; center aligned]: Sealant (x18) (Eighteen pink #E8387A rounded labels reading 'Sealant' each with white text, placed along the sealant beads at about these positions (percent of slide): (38.4,61.7) (39.6,65.7) (40.8,69.8) (42.0,73.9) (43.2,78.7) (44.7,84.2) (34.9,87.9) (47.3,59.8) (49.5,58.3) (49.2,64.8) (51.3,63.8) (53.6,69.8) (51.3,71.2) (53.5,77.8) (56.0,76.9) (61.1,57.3) (64.2,63.0) (66.7,70.0).)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1920 by 1080 pixels (covers the slide)

### Slide 70

**Text**

NGC PRE-TRAINED MODELS / Production-Quality AI Models / Trained by Experts for Enterprise Deployment / Credentials to Find Models You Trust / Continuously Updated to be State-of-the-Art / Adapt with NVIDIA TAO and Orchestrate / with NVIDIA Fleet Command / Reference AI Code Samples to Ease / Application Development / NVIDIA NGC | CATALOG / Download / EMR CXR AI MODEL / Application / Detect likelihood that a COVID-19 patient in the emergency room will need supplemental oxygen. / Popularity / Domain / Healthcare / Usage / For research purposes only / License / Clara License / Training Dataset / 20 different FL client sites with 16,000 cases. / Performance / AUC - 24 hours (94%) / AUC - 72 hours (91%) / Federated Learning / Deep Learning / Healthcare / Medical Imaging / Covid-19 / Clara / 20 Federated Learning Sites / Expand Credentials / Model Overview / The ultimate goal of this model is to predict the likelihood that a person showing up in the emergency room will need supplemental oxygen, which can aid physicians in determining the appropriate level of care for patients, including ICU placement. / Model Architecture / The model uses a pre-trained ResNet34 [1] for image feature extraction together with a deep & cross network [2] to combine it with EMR features. / Training Algorithm / The models were developed within the EXAM consortium using federated learning. The chest x-ray feature extraction branch of the network was pretrained on >200,000 images from CheXpert dataset (on pneumonia vs. rest task) & fine-tuned on ~500 images from Mass Gen Brigham to predict RALE [3] score to evaluate lung edema on CXR. / CXR / ResNet 34 / CXR Features / Deep & Cross / Blood Test / Oxygen Sat / Blood Pressure / Respiratory Rate / EHR Data / Room Air / Low Flow O2 / High Flow O2 / Ventilator / Death / 24 Hr Post Chest X-Ray Oxygen Prediction / Under Observation / Intensive Care / Input / For data preparation and model input preprocessing, please follow the steps provided in the TUTORIAL.md file under tutorial folder of this MMAR. / Output / The model predicts a patient's oxygen needs based on a chest x-ray and patient vitals and lab values (EMR features) by giving a risk score [0...1].

**Layout**

Text block is left-aligned in the left half, vertically centred on the slide: a bold title with a regular subtitle, then five separate lines of bullet-free statements with equal spacing, starting at x 6.7% and ending near x 36%. A mock-up of the NVIDIA NGC web page sits on the right, in perspective, spanning roughly x 48% to 96.5% and y 11% to 85%, with a credential card overlapping its left edge. No footer, page number or logo is visible.

**Visuals**

A perspective screenshot mock-up of the NVIDIA NGC catalog page for the EMR CXR AI Model. The rear panel shows a light grey web page with a black top bar containing the NVIDIA NGC logo and CATALOG label, a green Download button at top right, and green section headings Model Overview, Model Architecture and Training Algorithm with grey body text. Below the text is a boxed flow diagram on a light grey panel: a grey chest X-ray image labelled CXR, an arrow to a trapezoid labelled ResNet 34, an arrow to a colourful heat map labelled CXR Features (red, yellow and blue blobs), an arrow to a tall rectangle labelled Deep & Cross, and an arrow to a stack of five rectangles labelled Room Air, Low Flow O2, High Flow O2, Ventilator and Death, with a dashed line to Under Observation and Intensive Care. A second rectangle labelled Blood Test, Oxygen Sat, Blood Pressure, Respiratory Rate, EHR Data has a long arrow into Deep & Cross. The front card is a pale-blue-headed panel with a white caduceus icon, EMR CXR AI MODEL heading, a grey Popularity bar chart, and two green horizontal bars for AUC - 24 hours (94%) and AUC - 72 hours (91%). Tag chips show Federated Learning, Deep Learning, Healthcare, Medical Imaging, Covid-19, Clara and 20 Federated Learning Sites. Lighting is soft and even on the screen, and the scene is dark with a glossy reflective black floor beneath the screen. Nothing is cropped.

**Design**

Background: Black (#000000) fading to dark charcoal (#1A1A1A) floor with a reflective metallic surface, behind a perspective screenshot. Black and charcoal background (#000000 to #1A1A1A) with a dark brushed-metal floor. Title is white (#FFFFFF) bold DIN-style sans-serif, all caps, about 4.1% of slide height. Subtitle and bullet statements are white (#FFFFFF) regular DIN-style sans-serif at about 2.2% to 2.7% of slide height, with no bullets and generous spacing between lines. Accent colour inside the mock-up is NVIDIA green (#76B900) and the card header is pale blue (#8CC8EA). Screen has soft drop shadow beneath it. Mock-up has no rounded corners on the page panels and a thin grey border.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Black full-slide background fill (Covers the whole slide, behind everything.)
- photo at x 0, y 0, w 100, h 100 [#1A1A1A]: Dark brushed-metal floor photograph with reflection, bottom of slide (Full-bleed image 3840x2160, lower part darker grey with soft reflection, behind the mock-up.)
- illustration at x 48, y 11, w 48.5, h 74 [#D9D9D9]: Perspective screenshot of NVIDIA NGC catalog page, EMR CXR AI Model (Rotated in perspective, rear plane with soft grey shadow below and to the left, no border radius, overlaps the front card.)
- illustration at x 48.7, y 21.7, w 9.9, h 50.3 [#8CC8EA]: EMR CXR AI MODEL credential card with caduceus icon, Popularity chart, AUC bars and tags (Front card in perspective, pale blue header (#8CC8EA) holding white caduceus icon and heading, light grey body (#E8E8E8), green bars #76B900, grey tag chips, overlaps left edge of rear page with drop shadow.)
- title at x 6.7, y 33.8, w 29.8, h 4.1 [DIN Pro Bold, sans-serif, bold, all caps; font size 4.07% of slide height; #FFFFFF; left aligned]: NGC PRE-TRAINED MODELS
- subtitle at x 6.7, y 38.4, w 19.8, h 2.7 [DIN Pro Regular, sans-serif, regular; font size 2.72% of slide height; #FFFFFF; left aligned]: Production-Quality AI Models
- body at x 6.7, y 43.9, w 25.4, h 2.2 [DIN Pro Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Trained by Experts for Enterprise Deployment (No bullet, single line.)
- body at x 6.7, y 48.7, w 20.5, h 2.2 [DIN Pro Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Credentials to Find Models You Trust (No bullet, single line.)
- body at x 6.7, y 53.4, w 24.6, h 2.2 [DIN Pro Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Continuously Updated to be State-of-the-Art (No bullet, single line.)
- body at x 6.7, y 58.2, w 22.2, h 4.6 [DIN Pro Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Adapt with NVIDIA TAO and Orchestrate / with NVIDIA Fleet Command (Two lines, tight line spacing, no bullet.)
- body at x 6.7, y 65.3, w 20.1, h 4.6 [DIN Pro Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Reference AI Code Samples to Ease / Application Development (Two lines, tight line spacing, no bullet.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 33.8, w 29.8, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NGC PRE-TRAINED MODELS
- text at x 6.7, y 38.4, w 19.8, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Production-Quality AI Models
- text at x 6.7, y 43.9, w 25.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Trained by Experts for Enterprise Deployment
- text at x 6.7, y 48.7, w 20.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Credentials to Find Models You Trust
- text at x 6.7, y 53.4, w 24.6, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Continuously Updated to be State-of-the-Art
- text at x 6.7, y 58.2, w 22.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Adapt with NVIDIA TAO and Orchestrate
- text at x 6.7, y 60.6, w 15.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: with NVIDIA Fleet Command
- text at x 6.7, y 65.3, w 20.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Reference AI Code Samples to Ease
- text at x 6.7, y 67.7, w 13.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Application Development

### Slide 71

**Text**

NVIDIA JARVIS
State-of-the-Art Conversational AI
GPU-Accelerated ASR, NLU, TTS
Interactive Performance
Customize with NVIDIA TAO
Orchestrate with NVIDIA Fleet Command
Scale-Out with NVIDIA Triton
Run in Every Cloud and at the Edge
NVIDIA.NGC | CATALOG
Download
NVIDIA
JARVIS
Application
Accelerated framework for building multimodal conversational AI skills.
Popularity
Domain
Conversational AI
License
Jarvis License
1.0.0-b.2 (Latest) Scan Results
Linux / x86
AA
Deep Learning / Conversational AI / Inference / ASR / TTS / Text to Speech / NLP / Natural Language Processing / Automatic Speech Recognition / Transcription / Dialogue Management / Call Center
Expand Credentials
NVIDIA Jarvis
Jarvis is a fully accelerated application framework for building multimodal conversational AI services that use an end-to-end deep learning pipeline. Developers at enterprises can easily fine-tune state-of-the-art models on their data to achieve a deeper understanding of their specific context and optimize for inference to offer end-to-end real-time services that run in less than 300 milliseconds (ms) and delivers 7x higher throughput on GPUs compared with CPUs.
The Jarvis framework includes pre-trained conversational AI models, tools in the NVIDIA AI Toolkit, and optimized end-to-end services for speech, vision, and natural language understanding (NLU) tasks.
Fusing vision, audio, and other sensor inputs simultaneously provides capabilities such as multi-user, multi-context conversations in applications
CONVERSATION AI
ASR
AUDIO
AUDIO
DIALOG MANAGER
NLU
TTS
RECOMMENDER SYSTEM
Items
CANDIDATE GENERATION
RANKING
Getting Started
This release of Jarvis includes Quick Start scripts to help you get started with Jarvis AI Services. These scripts are meant for deploying the services locally for testing and running the example applications.
gs registry resource download-version nvidia/jarvis/jarvis_quickstart:1.0.0-b.2
Initialize and start Jarvis. The initialization step downloads and prepares Docker images and models. The start script launches the server.
cd jarvis_quickstart_v*
bash jarvis_init.sh
bash jarvis_start.sh
Start a container with sample clients for each service.
bash jarvis_start_client.sh
Next Steps
Jarvis Overview
Jarvis Documentation
Jarvis Developer Forum

**Layout**

Full-bleed dark slide with the text column left-aligned at about 6.7% from the left edge, starting around 33.7% from the top and running down to about 70%; the title block sits in the vertical middle-left and no title bar, footer or slide number is present. The right half holds a single perspective screenshot of the NVIDIA NGC catalog page, tilted in 3D and spanning roughly 49% to 96% of the width and 11% to 85% of the height, with a small green-headed NVIDIA Jarvis card overlapping its left edge.

**Visuals**

A perspective mockup of the NVIDIA NGC catalog web page, angled so the right edge is taller and nearer than the left, sitting on a dark reflective floor. Its dark top bar shows the NVIDIA NGC | CATALOG logo and a green Download button at top right. Left of the page, a separate tilted card with a green header containing the NVIDIA eye logo and the word JARVIS, followed by Application, Popularity (green bar sparkline), Domain, License, scan results and a row of grey tag pills. The main page shows a text block headed NVIDIA Jarvis in green, a grey paragraph, a light-grey boxed diagram and Getting Started with grey code-snippet boxes and a Next Steps list of green links. The diagram inside the boxed panel: a photo of a man in a dark jacket holding a phone at left, with AUDIO arrows (two-way) pointing to a dashed box labelled CONVERSATION AI containing ASR, DIALOG MANAGER, NLU and TTS, each drawn as black-outlined rectangles with small server-stack icons; two-way arrows connect ASR and TTS to DIALOG MANAGER and DIALOG MANAGER to NLU; a single arrow leads right to a dashed box labelled RECOMMENDER SYSTEM containing a database cylinder labelled Items, arrow down to CANDIDATE GENERATION, arrow down to RANKING, with a server icon beside RANKING. The photo is a small rectangle with a man in profile talking on a phone in an office-like setting, mostly dark blue and grey tones, unframed and not cropped.

**Design**

Background: Black #000000 backdrop fading to dark grey #2B2B2B at the floor, with a glossy reflective floor surface beneath the screen; the background photograph covers the entire slide.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide background image of a black studio backdrop with a dark reflective floor, covering the whole slide (Full-bleed, no overlay; floor reflection fades toward the bottom)
- illustration at x 49, y 11, w 47, h 74 [#E9E9E9]: Perspective screenshot of the NVIDIA NGC catalog web page with a dark top bar and light grey page body (Tilted in 3D, right edge taller; drop shadow beneath on the floor; page border light grey)
- shape at x 49.3, y 11, w 45, h 4.5 [#1E1E1E]: Dark top bar of the NGC page mockup (Part of the perspective page)
- logo at x 50, y 15.5, w 8, h 2 [#76B900]: NVIDIA.NGC | CATALOG logo on the page top bar (Green NVIDIA eye mark with white text)
- shape at x 90, y 14.5, w 4.5, h 2.8 [#76B900]: Green Download button with dropdown arrow on the page top right (Rounded corners about 2px; white text Download)
- shape at x 48.7, y 22, w 9.8, h 40 [#FFFFFF]: Tilted JARVIS info card overlapping the left edge of the page (Card with green header block; drop shadow beneath)
- logo at x 51.5, y 24, w 5.5, h 8 [#76B900]: NVIDIA eye logo and JARVIS wordmark in green header of the card (White NVIDIA text and JARVIS text on green)
- illustration at x 59.5, y 33, w 34, h 25 [#F2F2F2]: Architecture diagram of Jarvis: conversation AI pipeline and recommender system, drawn in black line art on light grey panel (Panel with no border, light grey fill; dashed black boxes; black outlined rectangles; two-way arrows)
- photo at x 61.5, y 42, w 6.6, h 9 [#2D3A4A]: Photograph of a man in a dark jacket holding a phone to his ear, indoors (Small unframed rectangle, not cropped, overlapping the diagram panel left edge)
- shape at x 68.8, y 20, w 14.5, h 16 [#FFFFFF]: Dashed black rectangle labelled CONVERSATION AI (Dashed black outline, about 0.2% stroke width)
- shape at x 81.2, y 23.5, w 5.3, h 12 [#FFFFFF]: Dashed black rectangle labelled RECOMMENDER SYSTEM (Dashed black outline)
- diagram at x 69, y 28, w 24, h 20 [#FFFFFF]: Boxes ASR, DIALOG MANAGER, NLU, TTS, CANDIDATE GENERATION, RANKING with two-way and one-way arrows and AUDIO labels (Black outlined rectangles; arrows black; server-stack icons beside ASR, NLU, TTS and RANKING)
- title at x 6.7, y 33.7, w 15.4, h 4.1 [DIN Pro; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA JARVIS (Bold, all capitals, sans-serif)
- subtitle at x 6.7, y 38.3, w 23.3, h 2.7 [DIN Pro; font size 2.72% of slide height; #FFFFFF; left aligned]: State-of-the-Art Conversational AI (Regular weight, sans-serif)
- bullet list at x 6.7, y 43.8, w 23, h 24 [DIN Pro; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU-Accelerated ASR, NLU, TTS / Interactive Performance / Customize with NVIDIA TAO / Orchestrate with NVIDIA Fleet Command / Scale-Out with NVIDIA Triton / Run in Every Cloud and at the Edge (Six lines without bullet markers, spaced about 4.8% of slide height apart, regular weight)
- footer at x 0, y 0, w 0, h 0: none (No footer or page number visible)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 33.7, w 15.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA JARVIS
- text at x 6.7, y 38.3, w 23.3, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: State-of-the-Art Conversational AI
- text at x 6.7, y 43.8, w 18.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU-Accelerated ASR, NLU, TTS
- text at x 6.7, y 48.6, w 13.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Interactive Performance
- text at x 6.7, y 53.3, w 15.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Customize with NVIDIA TAO
- text at x 6.7, y 58.1, w 22.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Orchestrate with NVIDIA Fleet Command
- text at x 6.7, y 62.8, w 16.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Scale-Out with NVIDIA Triton
- text at x 6.7, y 67.6, w 19.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Run in Every Cloud and at the Edge

### Slide 72

**Text**

Settings / ASR Model / None / Translate / En -> Ja / STOP / Jarvis transcription / We're also making tremendous progress in translation and now offer support for five languages. / また、翻訳も飛躍的に進歩しております。 / You can see how fluid the translation is into Japanese. / 現在5カ国語に対応しています。 / And it's running in real time with under one hundred milliseconds latency for each sentence. / 日本語の翻訳の流動性がわかります。 / そして、各文で100ミリ秒未満のレイテンシでリアルタイムで実行されています。

**Layout**

Two-panel application screen filling the full slide. A narrow left settings panel (about 14% of width) sits beside a wide right transcription panel with a header bar across its top. Inside the transcription panel, English text occupies a left column and its Japanese translation a right column, both starting near 12% from the top and left-aligned with generous gutters. Left margin of the content is about 21% and right margin about 3%. There is no title slide heading, footer, page number or slide number.

**Visuals**

None apart from the application interface itself, which is a screenshot of a dark-themed transcription app. Its elements are: a settings panel with an ASR Model dropdown showing None, a Translate dropdown showing En -> Ja, and a green STOP button; a transcription panel showing six paragraphs of English text in the left column and their Japanese translation in the right column. No photograph, chart or logo is present. The screenshot is full-bleed, covering the whole slide with no crop or overlay.

**Design**

Background: Dark charcoal #2B2B2B application window background, covered by the screenshot. Dark charcoal UI theme. Outer background about #2B2B2B. Settings panel fill about #3A3A3A with a header strip of about #444444 containing the label Settings. Transcription panel fill about #404040 with a header strip of about #454545 containing Jarvis transcription, separated from the body by a thin lighter line about #555555. Body text about #F2F2F2 (near white). Labels such as ASR Model and Translate are about #E0E0E0. Accent: the STOP button fill is NVIDIA-style green about #76B900 with white uppercase label. Dropdowns are white boxes #FFFFFF with dark text about #222222 and a black chevron. Typeface is a DIN-style humanist sans-serif, regular weight, for English; Japanese text uses a Gothic sans-serif. Panel title text is about 1.6% of slide height; transcription body text is about 4.2% of slide height, with generous line spacing of about 6.6% of height. Corners are square with a very slight radius of about 0.2%. Subtle drop shadow under the green button. No gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#2B2B2B]: Outer application background (Full-bleed dark charcoal area behind both panels)
- shape at x 2.3, y 1.3, w 14.3, h 98.7 [#3A3A3A]: Settings panel (Rectangular panel with thin border about #4A4A4A, square corners)
- shape at x 2.3, y 1.3, w 14.3, h 5.5 [#444444]: Settings header strip (Strip with bottom divider line about #555555)
- title at x 3.5, y 2.8, w 6, h 2.2 [DIN-style sans-serif, regular, mixed case; font size 1.6% of slide height; #F2F2F2; left aligned]: Settings
- shape at x 18.4, y 1.3, w 78.7, h 98.7 [#404040]: Transcription panel (Rectangular panel with thin border about #4A4A4A, square corners)
- shape at x 18.4, y 1.3, w 78.7, h 5.4 [#454545]: Transcription header strip (Strip with bottom divider line about #555555)
- title at x 19.6, y 2.8, w 11, h 2 [DIN-style sans-serif, regular, mixed case; font size 1.6% of slide height; #F2F2F2; left aligned]: Jarvis transcription
- body at x 4.7, y 9.3, w 6.5, h 2 [DIN-style sans-serif, regular, mixed case; font size 1.6% of slide height; #E0E0E0; left aligned]: ASR Model
- shape at x 4.7, y 12.3, w 9.5, h 2.5 [#FFFFFF]: ASR Model dropdown showing None (White select box with thin grey border and black downward chevron at right)
- body at x 4.7, y 18, w 6.5, h 2 [DIN-style sans-serif, regular, mixed case; font size 1.6% of slide height; #E0E0E0; left aligned]: Translate
- shape at x 4.7, y 20.8, w 9.5, h 2.5 [#FFFFFF]: Translate dropdown showing En -> Ja (White select box with thin grey border and black downward chevron at right)
- shape at x 4.7, y 26.1, w 9.5, h 4.6 [#76B900]: STOP button (Rectangular green button with slight corner radius about 0.2% and faint drop shadow beneath)
- body at x 4.7, y 26.1, w 9.5, h 4.6 [DIN-style sans-serif, regular, all caps, slight letter-spacing; font size 1.6% of slide height; #FFFFFF; center aligned]: STOP
- body at x 21.1, y 11.6, w 34, h 12 [DIN-style sans-serif, regular, mixed case; font size 4.2% of slide height; #F2F2F2; left aligned]: We're also making tremendous progress in translation and now / offer support for five languages. (Line spacing about 6.6% of slide height; paragraph gap about 3%)
- body at x 21.1, y 33, w 34, h 8.5 [DIN-style sans-serif, regular, mixed case; font size 4.2% of slide height; #F2F2F2; left aligned]: You can see how fluid the / translation is into Japanese. (Line spacing about 6.6% of slide height)
- body at x 21.1, y 48.7, w 34, h 18 [DIN-style sans-serif, regular, mixed case; font size 4.2% of slide height; #F2F2F2; left aligned]: And it's running in real time with / under one hundred milliseconds / latency for each sentence. (Line spacing about 6.6% of slide height)
- body at x 58.8, y 11.6, w 35.2, h 12 [Japanese Gothic sans-serif, regular; font size 4.2% of slide height; #F2F2F2; left aligned]: また、翻訳も飛躍的に進歩しております。 / 現在5カ国語に対応しています。 (Line spacing about 6.6% of slide height; Japanese text wraps at character level)
- body at x 58.8, y 33, w 35.2, h 8.5 [Japanese Gothic sans-serif, regular; font size 4.2% of slide height; #F2F2F2; left aligned]: 日本語の翻訳の流動性がわかります。 (Line spacing about 6.6% of slide height)
- body at x 58.8, y 48.7, w 35.2, h 18 [Japanese Gothic sans-serif, regular; font size 4.2% of slide height; #F2F2F2; left aligned]: そして、各文で100ミリ秒未満の / レイテンシでリアルタイムで実行 / されています。 (Line spacing about 6.6% of slide height; Japanese text wraps at character level)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1647 by 926 pixels (covers the slide)

### Slide 73

**Text**

ANNOUNCING
NVIDIA MERLIN
END-TO-END ACCELERATED
RECOMMENDER SYSTEM
GPU-Accelerated ETL, Data Loading,
Training, Inference
Scales Transparently to Target Data Sets
and More Complex Models
Run in Every Cloud and at the Edge
Now Available on NGC

**Layout**

Left-aligned text block occupies the left half of a black, dark-grey gradient stage, vertically centred around the middle of the slide, starting at about 6.7% from the left edge. On the right, a single angled product screenshot of the NVIDIA NGC catalog page is set in perspective and bleeds off the right side of the slide, overlapping a smaller Merlin info card on its left edge. There is no footer, page number or logo beyond those in the screenshot.

**Visuals**

Photograph-style mock-up of a web browser window showing the NVIDIA NGC Catalog page for NVIDIA Merlin, rendered in perspective with the right edge taller than the left and tilted back, on a dark floor with a soft reflection beneath. Top-left of the window: NVIDIA NGC logo and the word CATALOG in white on a near-black bar; top-right: green Download button with a dropdown arrow. A smaller floating card at the left shows a green header with the NVIDIA logo and the word MERLIN in white, then labelled fields: Application (Accelerated framework for building large-scale deep learning recommenders), Popularity (green bar sparkline), Domain (Recommendation Engine), License (Apache License 2.0 in green), 4.0.1-19.11 (Latest) Scan Results, Linux / x86 with an AA badge, tag chips Recommendation Systems, Deep Learning, HugeCTR, Machine Learning, NVTabular, Triton, Merlin, and Expand Details in green. The main panel shows NVIDIA Merlin heading in green with a paragraph of grey body text, then a light grey framed diagram: boxes in green with dark outlines labelled ETL, DATA LOADER, TRAINING, VALIDATION, CANDIDATE GENERATION (inside a dashed rectangle), RANKING, and EMBEDDINGS; arrows connect ETL to DATA LOADER to TRAINING to VALIDATION to CANDIDATE GENERATION to RANKING, with 0(1000) and 0(Billions) labels, a return arrow from VALIDATION-side loop back to ETL, a DATA LAKE cylinder at bottom centre, arrows from DATA LAKE and USE QUERY, and the output 10 RECOMMENDATIONS. Below the diagram: Getting Started in green with grey text and two dark grey code boxes containing docker run command and root@02d56ff0738f:/opt/tritonserver# lines, then Resources in green with links Merlin Overview, Merlin Documentation, Merlin Developer Forum. Lighting is soft and even, dominant colours are black, light grey and NVIDIA green #76B900.

**Design**

Background: Black to dark grey gradient (#000000 to #2A2A2A) with a dark floor surface. Black background with a dark grey gradient toward the floor; headline in white, body in white, accent green #76B900 in the screenshot. Typeface is DIN Pro, a condensed grotesque sans-serif: ANNOUNCING bold, the headline in regular capitals, body in regular weight. Title size about 4.1% of slide height, ANNOUNCING about 3.0%, body about 2.2%. Screenshot card has square corners and a soft drop shadow.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed dark studio background image (Covers the slide, black to dark grey floor with soft reflection at bottom)
- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Background fill covering the slide (Covered by image)
- photo at x 49, y 11, w 45, h 75 [#D9D9D9]: Angled NVIDIA NGC Merlin catalog browser screenshot in perspective with diagram and code boxes (Square corners, soft drop shadow beneath, extends off the right edge area near x 96%)
- photo at x 48.7, y 21.8, w 12.5, h 40 [#76B900]: Merlin information card floating over screenshot left edge (Green header with NVIDIA logo and MERLIN, white and light grey panel, square corners, drop shadow)
- title at x 6.7, y 30.5, w 10.6, h 3 [DIN Pro, bold, all capitals; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING
- title at x 6.7, y 33.7, w 30.5, h 12.9 [DIN Pro, regular, all capitals; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA MERLIN / END-TO-END ACCELERATED / RECOMMENDER SYSTEM (Line spacing about 4.4% of slide height; lines at y 33.7, 38.1, 42.5)
- body at x 6.7, y 49.2, w 23, h 17.9 [DIN Pro, regular, sentence case; font size 2.22% of slide height; #FFFFFF; left aligned]: GPU-Accelerated ETL, Data Loading, / Training, Inference / Scales Transparently to Target Data Sets / and More Complex Models / Run in Every Cloud and at the Edge / Now Available on NGC (Paragraph groups separated by extra space; line pitch about 2.4% within a paragraph)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 33.7, w 16.7, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: NVIDIA MERLIN
- text at x 6.7, y 38.1, w 30.5, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: END-TO-END ACCELERATED
- text at x 6.7, y 42.5, w 26.0, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: RECOMMENDER SYSTEM
- text at x 6.7, y 30.5, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 49.2, w 20.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: GPU-Accelerated ETL, Data Loading,
- text at x 6.7, y 51.6, w 10.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Training, Inference
- text at x 6.7, y 55.2, w 23.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Scales Transparently to Target Data Sets
- text at x 6.7, y 57.6, w 14.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: and More Complex Models
- text at x 6.7, y 61.2, w 19.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Run in Every Cloud and at the Edge
- text at x 6.7, y 64.8, w 12.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Now Available on NGC

### Slide 74

**Text**

NVIDIA MAXINE
SOTA AI to Reinvent Virtual Collaboration
SDKs for Video, Audio, and Augmented Reality
AI-Face Codec 10x Lower Bandwidth vs H.264
Jarvis for Conversational AI
Deploy on Client, in Data Center and Every Cloud
Download Today: developer.nvidia.com/maxine
NVIDIA NGC | CATALOG
Download
NVIDIA MAXINE
Application
GPU-accelerated SDK with state-of-the-art AI features for developers to build virtual collaboration and content creation applications such as video conferencing and live streaming.
Popularity
Domain
Virtual Collaboration
License
Maxine License
1.0-21.04 (Latest) Scan Results
Linux / x86
AA
Deep Learning / Augmented Reality / GAN / Real-time Audio / Real Time Video / AI / Multimedia
Expand Details
NVIDIA Maxine
NVIDIA Maxine™ is a GPU-accelerated SDK with state-of-the-art AI features for developers to build virtual collaboration and content creation applications such as video conferencing and live streaming.
Maxine's AI SDKs - Video Effects, Audio Effects, and Augmented Reality (AR) - are highly optimized and include modular features that can be chained into
Getting Started
You can pull the Maxine container with the following command:
docker run -it --name maxine --gpus=all --shm-size=1g --ulimit memlock=-1 --ulimit stack=67108864 -v ${PWD}:/models -p 8000:8000 -p 8001:8001 -p 8002:8002 nvcr.io/nvidia/maxine:1.0-21.04
The container will open a shell when the run command execution is completed. It should look similar to this:
root@02d56ff0738f:/opt/maxine#
Activate the Maxine conda environment by running the following command:
root@02d56ff0738f:/opt/maxine# source activate maxine
Resources
Maxine Overview
Maxine Documentation
Maxine Developer Forum
MAXINE
Video & AR
Decode | Eye Contact| Virtual Background
Super Resolution | Encode
AV Synch
Audio
Decode | Denoise | Echo Cancellation | Encode
Video
Audio
Video
Audio
Jarvis
ASR | Translation

**Layout**

Text block is left-aligned in the left half of the slide, vertically centred, starting at about 6.6% from the left edge: a title, a subtitle, four bullet-free lines, a blank gap, then a download line. The right half holds a large NVIDIA NGC catalog screenshot angled in 3D perspective, with no title bar, footer or slide number on the slide.

**Visuals**

Illustration of a browser window showing the NVIDIA NGC catalog page for NVIDIA Maxine, rotated in perspective so its left edge is nearer the viewer and it sits on a dark reflective floor. Overlaid on the left of the window is a tall green NVIDIA Maxine info card. Inside the window is a dashed-outline diagram on a light grey panel: a dashed rounded rectangle labelled MAXINE containing a box Video & AR (Decode | Eye Contact| Virtual Background / Super Resolution | Encode) with a green neural-network icon at right, a box AV Synch, and a box Audio (Decode | Denoise | Echo Cancellation | Encode) with a green neural-network icon at right; a microphone icon and a camera icon at left feed Video and Audio arrows into a grey trapezoid icon; arrows run from the trapezoid into Video & AR and Audio, and from these into AV Synch; Video and Audio arrows exit right to a photo of two women with an AI mesh overlay on the left face. Below the dashed box, a dashed box labelled Jarvis (ASR | Translation) with a green icon is connected by up and down arrows. Lighting is soft and even on the screen, with a dark glossy reflection below. Dominant colours are black, light grey, white and NVIDIA green #76B900. The image is not cropped and is not boxed; it is a free-standing angled panel. Text on the slide itself is not overlaid on the image.

**Design**

Background: Solid black #000000 with a dark grey reflective floor gradient at the lower part. Black background with white sans-serif type. Title in bold DIN Pro style, white #FFFFFF, roughly 4% of slide height. Subtitle and bullets in regular DIN Pro style, white #FFFFFF, roughly 2.2% of slide height, with generous line spacing. Download URL in medium weight. Accent colour is NVIDIA green #76B900 used only within the screenshot. Screenshot panel has a soft drop shadow and a slight perspective rotation; no gradients on text.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: full-slide solid background (Covers the whole slide, no border.)
- illustration at x 49, y 11, w 47.5, h 74 [#F2F2F2]: angled screenshot of NVIDIA NGC catalog page for NVIDIA Maxine (Perspective rotation, left edge nearer viewer; dark top bar; soft drop shadow; reflection on floor below; not cropped.)
- shape at x 48.7, y 21.7, w 9.9, h 28 [#76B900]: NVIDIA Maxine green info card (Green header with NVIDIA logo and MAXINE label, white lower panel with grey text; overlaps screenshot left edge; slight drop shadow.)
- shape at x 59.6, y 28, w 33.5, h 26.7 [#EFEFEF]: light grey diagram panel (Rectangle with no visible border, sits over the browser window content.)
- diagram at x 61, y 30.5, w 30, h 22.5 [#FFFFFF]: Maxine architecture diagram with dashed MAXINE container, Video & AR, AV Synch, Audio, Jarvis boxes and arrows (Dashed grey outline around MAXINE box; solid dark grey box outlines; black arrows; green neural-network icons.)
- photo at x 85.6, y 36.4, w 6.2, h 5.1: photo of two women with AI face mesh overlay (Rectangular thumbnail with thin grey border, face overlaid with green mesh lines.)
- title at x 6.7, y 33.8, w 16.3, h 4.1 [DINPro-Bold, bold, uppercase, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA MAXINE
- subtitle at x 6.7, y 38.4, w 27.8, h 2.7 [DINPro-Regular, regular weight, sentence case; font size 2.72% of slide height; #FFFFFF; left aligned]: SOTA AI to Reinvent Virtual Collaboration
- body at x 6.6, y 43.9, w 26.9, h 11.6 [DINPro-Regular, regular weight, sentence case; font size 2.22% of slide height; #FFFFFF; left aligned]: SDKs for Video, Audio, and Augmented Reality / AI-Face Codec 10x Lower Bandwidth vs H.264 / Jarvis for Conversational AI / Deploy on Client, in Data Center and Every Cloud (Four lines with line spacing of about 3.9% of slide height between baselines; no bullet markers.)
- body at x 6.6, y 63.3, w 26.4, h 2.2 [DINPro-Regular for Download Today:, DINPro-Medium for the URL, sentence case; font size 2.22% of slide height; #FFFFFF; left aligned]: Download Today: developer.nvidia.com/maxine

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 33.8, w 16.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA MAXINE
- text at x 6.7, y 38.4, w 27.8, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: SOTA AI to Reinvent Virtual Collaboration
- text at x 6.6, y 43.9, w 25.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: SDKs for Video, Audio, and Augmented Reality
- text at x 6.6, y 47.8, w 25.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: AI-Face Codec 10x Lower Bandwidth vs H.264
- text at x 6.6, y 51.7, w 15.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Jarvis for Conversational AI
- text at x 6.6, y 55.6, w 26.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Deploy on Client, in Data Center and Every Cloud
- text at x 6.6, y 63.3, w 9.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Download Today:
- text at x 16.4, y 63.3, w 16.6, h 2.2 [DINPro-Medium; font size 2.22; #FFFFFF]: developer.nvidia.com/maxine

### Slide 75

**Text**

AI FACE CODEC
EYE CONTACT
MACHINE TRANSLATION
SPEECH RECOGNITION
that's so much better thanks to NVIDIA Maxine.
No es ideal. Ahora vamos a volver a activar todas las características de Maxine.

**Layout**

Full-bleed video frame filling the whole slide, with the subject centred and a black subtitle band across the bottom about 17% of the height. The green four-item label stack sits at the upper right of the frame, about 71% from the left and 20% from the top. There is no title, footer, slide number or logo.

**Visuals**

A photograph of a woman in her thirties, centred and seen from the chest up, looking at the camera with a slight closed-mouth smile. She has dark hair pulled back, a magenta lip colour, and wears a fuzzy blue-grey knit top with a V-neck. Behind her is a plain off-white wall flanked by two dark charcoal metal open shelving units with warm oak-wood shelves. Left shelf: hanging black wire lanterns at top left, a black woven ceramic vase with a eucalyptus-style plant, and a white box at lower left. Right shelf: a polished silver metal ornament, a succulent in a dark bowl, and a cream and tan hardcover book with an ampersand on its spine. Lighting is soft, even, frontal daylight with no hard shadows. Dominant colours are cream #EDEBE0, charcoal #2E2E2E, oak brown #8B5E3C and slate blue #5B6E8C. The photo is full-bleed and uncropped at the top and sides; the bottom is cut by the subtitle band at about the waist. Overlay: a four-row green label stack, each row a filled rectangle of NVIDIA green #76B900 with a 0.5 pt white outline and white uppercase text; the rows touch each other with no gaps and have square corners. Subtitle band: solid black #000000 across the full width.

**Design**

Background: Photograph of a woman in front of a cream wall, full-bleed, with a solid black #000000 subtitle band along the bottom. Video-frame look with a black letterbox band. Overlay labels use NVIDIA green #76B900 fill with white #FFFFFF text. The English subtitle is white #FFFFFF and the Spanish subtitle is green #76B900. Labels are set in a condensed uppercase sans-serif (DIN-style), regular weight, letter-spacing about 0.02 em. Subtitles are a regular-weight Arial/Helvetica-style sans-serif. Label text is about 2.5% of slide height; subtitle text is about 2.7% of slide height. Shapes are square-cornered with no shadows or gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 82.9: Full-bleed photograph of a woman seated in a living room with cream wall and wooden shelving, centred subject with smile (Image covers the slide width; bottom edge cut by black band at about waist level; no border, no rounding)
- shape at x 0, y 82.9, w 100, h 17.1 [#000000]: Black subtitle band (Solid rectangle, opacity 100%, no border, sits over the lower part of the photo)
- shape at x 71.2, y 20.5, w 17.25, h 4.6 [#76B900]: Green label row: AI FACE CODEC (Rectangle with 0.5 pt white stroke, square corners, no shadow, overlays the photo over the upper right shelf)
- shape at x 71.2, y 25.1, w 17.25, h 4.4 [#76B900]: Green label row: EYE CONTACT (Rectangle with 0.5 pt white stroke, square corners, abuts the row above)
- shape at x 71.2, y 29.5, w 17.25, h 4.5 [#76B900]: Green label row: MACHINE TRANSLATION (Rectangle with 0.5 pt white stroke, square corners, abuts the row above)
- shape at x 71.2, y 34, w 17.25, h 4.6 [#76B900]: Green label row: SPEECH RECOGNITION (Rectangle with 0.5 pt white stroke, square corners, abuts the row above)
- body at x 72.2, y 21.6, w 13, h 3 [DIN-style condensed sans-serif, regular, uppercase, letter-spacing about 0.02 em; font size 2.5% of slide height; #FFFFFF; left aligned]: AI FACE CODEC
- body at x 72.2, y 26.2, w 10.5, h 3 [DIN-style condensed sans-serif, regular, uppercase, letter-spacing about 0.02 em; font size 2.5% of slide height; #FFFFFF; left aligned]: EYE CONTACT
- body at x 72.2, y 30.6, w 15.5, h 3 [DIN-style condensed sans-serif, regular, uppercase, letter-spacing about 0.02 em; font size 2.5% of slide height; #FFFFFF; left aligned]: MACHINE TRANSLATION
- body at x 72.2, y 35.1, w 14.5, h 3 [DIN-style condensed sans-serif, regular, uppercase, letter-spacing about 0.02 em; font size 2.5% of slide height; #FFFFFF; left aligned]: SPEECH RECOGNITION
- caption at x 10.5, y 88.5, w 33.4, h 3.2 [Arial/Helvetica-style sans-serif, regular, sentence case; font size 2.7% of slide height; #FFFFFF; left aligned]: that's so much better thanks to NVIDIA Maxine.
- caption at x 10.75, y 93.3, w 56, h 3.2 [Arial/Helvetica-style sans-serif, regular, sentence case; font size 2.7% of slide height; #76B900; left aligned]: No es ideal. Ahora vamos a volver a activar todas las características de Maxine.

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1920 by 1080 pixels (covers the slide)

### Slide 76

**Text**

ANNOUNCING NVIDIA TRITON INFERENCE SERVER
MODELS
Infinite AI Models
CV, ASR, NLU, TTS, RecSys
Multiple Frameworks
TensorFlow, Pytorch,
ONNX, TensorRT
Varying Services
Batch, Real-Time,
Streaming
GPU
CPU
TRITON INFERENCE SERVER
Any Model
Any Framework
Any Service Requirement
CPU or GPU

**Layout**

Full-width centred title in the top band at about 8% from the top, with a large dark isometric illustration panel spanning roughly 21% to 88% horizontally and 25% to 83% vertically. The MODELS text block sits left of the illustration at about 21% from the left edge, with GPU and CPU labels lower left on leader lines; the TRITON INFERENCE SERVER block sits right of the illustration at about 67.5% from the left edge. No footer, page number or logo is visible.

**Visuals**

Isometric illustration on a black background showing three server-rack towers and a central tall tower. Left tower: stacked dark layers with white outline edges, a green (#76B900) base slab. Centre tower (front, tallest in front): a column of stacked slabs from top to bottom in blue (#5B8DEF), light blue (#8ED3F5), cyan-blue (#4FB3E8), magenta-pink (#D98BE6), and purple (#9B6FD9), with a green (#76B900) base slab; a dashed white outline surrounds the tower. Right tower: stacked dark layers with white outline and a green base slab. Behind the towers are outlined black cuboid building blocks. Two chip graphics sit at lower right: a GPU package (silver-gold die on a black slab) at about x 50-59%, y 79-90%, and a CPU package (silver die on blue substrate on a black slab) at about x 58-66%, y 84-99%. Thin white leader lines run from MODELS text to the left tower, from the TRITON INFERENCE SERVER label to the right tower, and from GPU and CPU labels horizontally to the chips. Lighting is soft, dark and even; composition is centred and framed inside a thin grey-bronze border rectangle at about x 3.8%, y 12%, w 92.4%, h 71%.

**Design**

Background: Black (#000000) fading to dark grey (#1A1A1A) with a reflective dark floor. Black background with a subtle dark grey gradient and reflective floor at the bottom. Titles in white (#FFFFFF) DINPro-Bold, uppercase, bold sans-serif, about 4.07% of slide height. Section labels MODELS, TRITON INFERENCE SERVER, GPU, CPU in white DINPro-Medium, uppercase, about 2.65% of slide height. Body text white DINPro-Regular, about 1.91% of slide height, line spacing about 2.3% of slide height. Accents are NVIDIA green #76B900 and blue #5B8DEF. Thin white leader lines about 1px. Panel border thin grey-bronze.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Background fill, black covering the slide (Covers the slide; white fill per measurement is hidden behind the photograph.)
- illustration at x 0, y 0, w 100, h 100 [#101010]: Dark studio background image with isometric server towers, chips and floor reflection (Full-bleed 3840 by 2160 image; photographic dark backdrop with reflective floor.)
- illustration at x 20.9, y 25.1, w 66.6, h 58 [#5B8DEF]: Isometric server towers, building blocks, GPU and CPU chip graphics (Image 5753 by 2819 px; centre tower with blue, light blue, magenta and purple layers and green base; green #76B900 base slabs on side towers; white outline edges; dashed outline around centre tower.)
- title at x 23.6, y 7.9, w 52.7, h 4.1 [DINPro-Bold, sans-serif, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA TRITON INFERENCE SERVER
- title at x 21.4, y 35.7, w 5.8, h 2.7 [DINPro-Medium, sans-serif, uppercase; font size 2.65% of slide height; #FFFFFF; left aligned]: MODELS
- body at x 21.4, y 40.3, w 12.8, h 4.2 [DINPro-Regular, sans-serif; font size 1.91% of slide height; #FFFFFF; left aligned]: Infinite AI Models / CV, ASR, NLU, TTS, RecSys (Line spacing about 2.3% of slide height; lines at y 40.3 and 42.6.)
- body at x 21.4, y 47.2, w 10.2, h 6.2 [DINPro-Regular, sans-serif; font size 1.91% of slide height; #FFFFFF; left aligned]: Multiple Frameworks / TensorFlow, Pytorch, / ONNX, TensorRT (Line spacing about 2.3% of slide height.)
- body at x 21.4, y 56.4, w 8.9, h 6.5 [DINPro-Regular, sans-serif; font size 1.91% of slide height; #FFFFFF; left aligned]: Varying Services / Batch, Real-Time, / Streaming (Line spacing about 2.3% of slide height.)
- title at x 21.5, y 69.6, w 2.9, h 2.7 [DINPro-Medium, sans-serif, uppercase; font size 2.65% of slide height; #FFFFFF; left aligned]: GPU
- title at x 21.4, y 74, w 2.9, h 2.7 [DINPro-Medium, sans-serif, uppercase; font size 2.65% of slide height; #FFFFFF; left aligned]: CPU
- line at x 21.4, y 36.2, w 13.5, h 0.1 [#FFFFFF]: Leader line from MODELS heading to left tower (Thin white 1px line, runs horizontally then diagonally down to the left tower.)
- line at x 21.4, y 72.5, w 35, h 0.1 [#FFFFFF]: Leader line from GPU label to GPU chip (Thin grey-white 1px horizontal line.)
- line at x 21.4, y 76.6, w 38, h 0.1 [#FFFFFF]: Leader line from CPU label to CPU chip (Thin grey-white 1px horizontal line.)
- title at x 67.5, y 50.8, w 19.4, h 2.7 [DINPro-Medium, sans-serif, uppercase; font size 2.65% of slide height; #FFFFFF; left aligned]: TRITON INFERENCE SERVER
- line at x 55, y 54, w 32.5, h 0.1 [#FFFFFF]: Leader line from TRITON INFERENCE SERVER heading to right tower (Thin grey 1px horizontal line.)
- body at x 67.5, y 55.3, w 12, h 8.5 [DINPro-Regular, sans-serif; font size 1.91% of slide height; #FFFFFF; left aligned]: Any Model / Any Framework / Any Service Requirement / CPU or GPU (Line spacing about 2.3% of slide height.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 20.9, y 25.1, w 66.6, h 58.0: 5753 by 2819 pixels
- text at x 23.6, y 7.9, w 52.7, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA TRITON INFERENCE SERVER
- text at x 21.4, y 35.7, w 5.8, h 2.7 [DINPro-Medium; font size 2.65; #FFFFFF]: MODELS
- text at x 67.5, y 50.8, w 19.4, h 2.7 [DINPro-Medium; font size 2.65; #FFFFFF]: TRITON INFERENCE SERVER
- text at x 21.4, y 40.3, w 8.5, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Infinite AI Models
- text at x 21.4, y 42.6, w 12.8, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: CV, ASR, NLU, TTS, RecSys
- text at x 21.4, y 47.2, w 10.2, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Multiple Frameworks
- text at x 21.4, y 49.5, w 10.0, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: TensorFlow, Pytorch,
- text at x 21.5, y 69.6, w 2.9, h 2.7 [DINPro-Medium; font size 2.65; #FFFFFF]: GPU
- text at x 21.4, y 51.8, w 8.0, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: ONNX, TensorRT
- text at x 21.4, y 74.0, w 2.9, h 2.7 [DINPro-Medium; font size 2.65; #FFFFFF]: CPU
- text at x 67.5, y 55.3, w 4.9, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Any Model
- text at x 21.4, y 56.4, w 7.8, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Varying Services
- text at x 67.5, y 57.6, w 7.5, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Any Framework
- text at x 21.4, y 58.7, w 8.9, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Batch, Real-Time,
- text at x 67.5, y 59.9, w 12.0, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Any Service Requirement
- text at x 21.4, y 61.0, w 4.9, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: Streaming
- text at x 67.5, y 62.1, w 5.8, h 1.9 [DINPro-Regular; font size 1.91; #FFFFFF]: CPU or GPU

### Slide 77

**Text**

_(no text on this slide)_

**Layout**

Full-bleed single image with no text, no title, no footer and no slide number. The picture fills the entire slide edge to edge, and a brighter vertical band runs from about 39% to 67% of the width, with the tile grid visible across the full height.

**Visuals**

One full-bleed image of a dense rectangular grid of small square tiles, about 3840 by 2160 pixels in source. Each tile is nearly black and holds a thin, curved, branching motif made of small dots in cyan, light blue, white, red and yellow, resembling a wire or molecular-style pattern. Thin grey-green grid lines separate the tiles. Across the centre, from about x 39% to 67% and full height, the tiles are brighter, their grid lines are pale grey-white and the motifs are more luminous and more densely packed. The tiles at the left and right edges are dimmer and more blue-green. A second, smaller image of about 1080 by 613 pixels is placed at the same full-slide position and shows the same pattern, so the two images overlap exactly. The image is not cropped, has no boxed frame, and has no overlay or text.

**Design**

Background: Solid white fill #FFFFFF, fully covered by the near-black tiled image. Black and near-black background with a white base fill behind the images, which the images cover completely. No typography. Grid lines are thin grey-green, roughly 1 pixel wide at slide scale. Motif dots are about 0.2% of slide height. No shapes, shadows, gradients or corner radii are visible outside the image.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide white base fill, covered by the images (Solid rectangle, not visible because the images cover it entirely.)
- photo at x 0, y 0, w 100, h 100: Full-bleed tiled pattern image, about 3840 by 2160 pixels, dark tiles with coloured curved motifs and a brighter central band (Not cropped and not boxed; sits at the back. Dominant colours near-black #000000 with cyan, blue, white, red and yellow dots and grey-green grid lines. Brighter central band from about x 39% to 67%.)
- photo at x 0, y 0, w 100, h 100: Full-bleed tiled pattern image, about 1080 by 613 pixels, same pattern as the larger image (Placed exactly over the larger image at full slide size, so the two overlap completely; the detail of the larger image is what is visible.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1080 by 613 pixels (covers the slide)

### Slide 78

**Text**

THOUSANDS OF COMPANIES DOING COOL THINGS WITH NVIDIA AI
Analyze 225K
Network Events per Second
Accurately Detect Diseases
in 145M Hearts per Year
Identify Trends in over 300B Pins
for Better Search Results
Tasteful Recommendations
from 600K Restaurants
Personalized Playlists
for over 345M Listeners
Award-Winning Customer Care
Using Real-Time ASR
Real-Time Analytics
on 7B Packages per Year
Intelligent Search with SOTA NLU
for 1.2B Users

**Layout**

Single title line centred across the top of a 4-by-2 grid of eight equal dark cards with thin gold outlines, occupying the middle of the slide. Each card has two centred caption lines at its top and one centred logo below them. The title sits about 8% from the top edge, the grid spans roughly 4% to 96% horizontally, and the bottom row ends near 83% of the height, leaving the lower sixth of the slide as a dark reflective floor with no footer or slide number.

**Visuals**

Eight logo/icon elements, one per card, in reading order. Row 1: Best Buy wordmark in white bold capitals with a white price-tag shape after the Y; GE Healthcare roundel (white monogram in a white circle outline) followed by the white text GE Healthcare; Pinterest white P in a white circle; Postmates white courier-on-bicycle icon with four small white stars above a white Postmates wordmark. Row 2: Spotify white circular sound-wave mark followed by white Spotify wordmark with registered mark; T-Mobile white serif T-Mobile wordmark with trademark mark; United States Postal Service white italic eagle emblem followed by white italic capitals UNITED STATES / POSTAL SERVICE; WeChat white two-speech-bubble icon followed by white WeChat wordmark. No photographs, charts or diagrams. Background is a dark studio-style image with a black top and a grey reflective floor at the bottom.

**Design**

Background black #000000 at the top graduating to dark charcoal grey #2A2A2A on the reflective floor at the bottom. Title text is white #FFFFFF, DINPro-Bold, all capitals, about 4.07% of slide height. Card captions are gold-tan #B1955D, DINPro-Medium, about 1.98% of slide height, centred. Logos are white #FFFFFF. Cards are near-black #111111 rectangles with a thin gold-tan #B1955D outline of about 1 pixel at 2000 px width, square corners, and a soft dark drop shadow along the bottom edge.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Background studio image: black upper area fading into a dark grey reflective floor with faint light streaks at the bottom, full-bleed across the whole slide (Full-bleed 3840 by 2160 pixel image behind all other elements; no overlay visible)
- shape at x 3.8, y 21.5, w 21.95, h 29.5 [#111111]: Card 1 background rectangle (row 1, column 1) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 27.3, y 21.5, w 21.95, h 29.5 [#111111]: Card 2 background rectangle (row 1, column 2) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 50.75, y 21.5, w 21.95, h 29.5 [#111111]: Card 3 background rectangle (row 1, column 3) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 74.2, y 21.5, w 21.95, h 29.5 [#111111]: Card 4 background rectangle (row 1, column 4) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 3.8, y 53.8, w 21.95, h 29.5 [#111111]: Card 5 background rectangle (row 2, column 1) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 27.3, y 53.8, w 21.95, h 29.5 [#111111]: Card 6 background rectangle (row 2, column 2) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 50.75, y 53.8, w 21.95, h 29.5 [#111111]: Card 7 background rectangle (row 2, column 3) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- shape at x 74.2, y 53.8, w 21.95, h 29.5 [#111111]: Card 8 background rectangle (row 2, column 4) (Square corners, 1 px thin gold-tan #B1955D outline, soft shadow at bottom edge)
- body at x 11.4, y 24, w 6.9, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Analyze 225K
- body at x 7.8, y 26.2, w 13.8, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Network Events per Second
- body at x 31.5, y 24, w 13.8, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Accurately Detect Diseases
- body at x 32.3, y 26.2, w 11.9, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: in 145M Hearts per Year
- body at x 53.6, y 24, w 16.5, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Identify Trends in over 300B Pins
- body at x 55.4, y 26.2, w 12.7, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: for Better Search Results
- body at x 78.5, y 24, w 13.8, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Tasteful Recommendations
- body at x 79.5, y 26.2, w 11.5, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: from 600K Restaurants
- body at x 9.1, y 56, w 11.3, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Personalized Playlists
- body at x 8.8, y 58.1, w 11.8, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: for over 345M Listeners
- body at x 30.5, y 56, w 15.8, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Award-Winning Customer Care
- body at x 32.9, y 58.1, w 10.7, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Using Real-Time ASR
- body at x 56.7, y 56, w 10.3, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Real-Time Analytics
- body at x 55.6, y 58.1, w 12.3, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: on 7B Packages per Year
- body at x 76.8, y 56.1, w 16.8, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: Intelligent Search with SOTA NLU
- body at x 81.5, y 58.2, w 7.1, h 2 [DINPro-Medium, sans-serif, regular weight; font size 1.98% of slide height; #B1955D; center aligned]: for 1.2B Users
- logo at x 10.2, y 34.6, w 9.2, h 9.3 [#FFFFFF]: Best Buy wordmark in white bold capitals with white price-tag shape after the Y (Card 1 logo, centred in card)
- logo at x 29.3, y 35.8, w 18, h 7 [#FFFFFF]: GE Healthcare logo: white GE monogram roundel followed by white GE Healthcare text (Card 2 logo, centred in card)
- logo at x 59.3, y 34.8, w 5, h 8.9 [#FFFFFF]: Pinterest white P logo in a white circle (Card 3 logo, centred in card)
- icon at x 80.3, y 32.5, w 9.9, h 13.6 [#FFFFFF]: Postmates courier on bicycle icon with four small stars (Card 4 icon, white, centred above Postmates wordmark)
- logo at x 80.5, y 42.5, w 19, h 5 [sans-serif, regular weight; #FFFFFF; center aligned]: Postmates wordmark in white sans-serif lowercase-and-capital text (Card 4 wordmark below icon)
- logo at x 7.9, y 67.2, w 15, h 8 [#FFFFFF]: Spotify logo: white circular sound-wave mark followed by white Spotify wordmark with registered mark (Card 5 logo, centred in card)
- logo at x 32.1, y 68.2, w 12.5, h 5.4 [#FFFFFF]: T-Mobile wordmark in white serif with trademark mark (Card 6 logo, centred in card)
- logo at x 54.1, y 67.8, w 15.5, h 5.9 [#FFFFFF]: United States Postal Service emblem and white italic capitals UNITED STATES / POSTAL SERVICE (Card 7 logo, centred in card)
- logo at x 75.9, y 64.5, w 18.8, h 13.5 [#FFFFFF]: WeChat logo: white two speech bubbles followed by white WeChat wordmark (Card 8 logo, centred in card)
- title at x 15.7, y 7.9, w 68.6, h 4.1 [DINPro-Bold, sans-serif, bold weight, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: THOUSANDS OF COMPANIES DOING COOL THINGS WITH NVIDIA AI

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 75.9, y 64.5, w 18.8, h 13.5: 1335 by 540 pixels
- image at x 80.3, y 32.5, w 9.9, h 13.6: 400 by 309 pixels
- image at x 29.3, y 35.8, w 18.0, h 7.0: 1024 by 225 pixels
- image at x 7.9, y 67.2, w 15.0, h 8.0: 1536 by 462 pixels
- image at x 54.1, y 67.8, w 15.5, h 5.9: 1536 by 329 pixels
- image at x 10.2, y 34.6, w 9.2, h 9.3: 348 by 198 pixels
- image at x 32.1, y 68.2, w 12.5, h 5.4: 720 by 176 pixels
- image at x 59.3, y 34.8, w 5.0, h 8.9: 600 by 600 pixels
- text at x 15.7, y 7.9, w 68.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: THOUSANDS OF COMPANIES DOING COOL THINGS WITH NVIDIA AI
- text at x 11.4, y 24.0, w 6.9, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Analyze 225K
- text at x 31.5, y 24.0, w 13.8, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Accurately Detect Diseases
- text at x 53.6, y 24.0, w 16.5, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Identify Trends in over 300B Pins
- text at x 78.5, y 24.0, w 13.8, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Tasteful Recommendations
- text at x 7.8, y 26.2, w 13.8, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Network Events per Second
- text at x 32.3, y 26.2, w 11.9, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: in 145M Hearts per Year
- text at x 55.4, y 26.2, w 12.7, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: for Better Search Results
- text at x 79.5, y 26.2, w 11.5, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: from 600K Restaurants
- text at x 9.1, y 56.0, w 11.3, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Personalized Playlists
- text at x 30.5, y 56.0, w 15.8, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Award-Winning Customer Care
- text at x 56.7, y 56.0, w 10.3, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Real-Time Analytics
- text at x 76.8, y 56.1, w 16.8, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Intelligent Search with SOTA NLU
- text at x 8.8, y 58.1, w 11.8, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: for over 345M Listeners
- text at x 32.9, y 58.1, w 10.7, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: Using Real-Time ASR
- text at x 55.6, y 58.1, w 12.3, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: on 7B Packages per Year
- text at x 81.5, y 58.2, w 7.1, h 2.0 [DINPro-Medium; font size 1.98; #B1955D]: for 1.2B Users

### Slide 79

**Text**

ANNOUNCING NVIDIA AI ENTERPRISE PLATFORM
Jarvis
Maxine
Merlin
Morpheus
Isaac
Metropolis
Clara
Drive
NVIDIA AI ENTERPRISE
NVIDIA GPU CLOUD REGISTRY
cuIO
cuDF
cuDNN
cuML
cuGraph
TAO
TensorRT
Triton
NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G, Morpheus
VMware vSphere
NVIDIA
CERTIFIED
Atos
DELL Technologies
FUJITSU
GIGABYTE
H3C
hp
inspur
Lenovo
QCT
SUPERMICRO
NVIDIA
BlueField-2
NVIDIA
A100/A30
NVIDIA
A40/A10
NVIDIA Aerial
A100

**Layout**

A centred vertical stack on a dark stage: a title across the top third, then a framed row of eight product tiles, a gold NVIDIA AI Enterprise panel with five stacked bands, a full-width blue VMware vSphere bar, and a row of certification and partner logos beneath it. Four circular hardware inserts sit in the bottom-left corner over the floor, with a white server chassis above them. The title is centred near the top at about 8% from the top edge, with no slide number or footer visible.

**Visuals**

Eight product tiles in one row inside a thin gold-brown frame. Jarvis: a cartoon blue water-drop mascot with large eyes on a light grey background. Maxine: a head-and-shoulders photo of a smiling woman with dark hair in a grey top against a light wall. Merlin: a hand holding a card near a keyboard with a blurred dark background. Morpheus: abstract glowing red and white network lines on black. Isaac: a white robotic arm above coloured cubes on a dark ground. Metropolis: an aerial street view of a European city with coloured detection boxes labelled BUS, VAN, MOTORBIKE, CYCLIST and PEDESTRIAN. Clara: a translucent grey-green lung scan on black. Drive: a black self-driving car with green accents on a dark road. Each tile is a boxed image with a dark gradient band at the bottom holding the white caption. Below the product tiles, a gold panel with the stacked bands described in the text. Next is a blue bar. Beneath it, an NVIDIA Certified badge in white outline and partner logos in white. Four circular dark inserts show, from left: an NVIDIA BlueField-2 card with a chip on black; an NVIDIA A100/A30 gold-bronze GPU card; an NVIDIA A40/A10 gold-bronze GPU card; an NVIDIA Aerial A100 board with a large chip. The white server chassis with a gold GPU card sits above the inserts, slightly angled, and overlaps the left edge of the gold panel.

**Design**

Background: Near-black #000000 at the top fading to dark grey #2B2B2B on a reflective floor in the lower part, with a faint blue-grey light reflection under the circles. Black background with a dark grey floor gradient in the lower half. Titles are white bold DIN-style sans-serif capitals. Body and tile captions are white regular DIN-style sans-serif. The gold panel uses a brass gradient from about #B08D57 to #7A5C2E with darker separator lines. The VMware bar is solid blue #0A6EC8. Shapes have square corners and soft drop shadows. Thin light border on the product frame. The NVIDIA Certified badge uses a green #76B900 eye mark and white outline text.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide dark stage background photograph with black top and grey floor
- shape at x 27.1, y 20, w 45.8, h 16 [#2A2118]: Product frame rectangle with thin gold-brown border surrounding the eight tiles (stroke about 0.2% of slide height in #A8895A, square corners)
- photo at x 27.7, y 21.3, w 5.2, h 13.5: Jarvis tile: cartoon blue water-drop mascot
- photo at x 33.4, y 21.3, w 5.2, h 12.6: Maxine tile: smiling woman headshot
- photo at x 39, y 21.3, w 5.2, h 13.4: Merlin tile: hand holding card over keyboard
- photo at x 44.6, y 21.2, w 5.2, h 13.5: Morpheus tile: red and white network lines on black
- photo at x 50.2, y 21.2, w 5.2, h 13.7: Isaac tile: robotic arm above coloured cubes
- photo at x 55.8, y 21.2, w 5.2, h 13.5: Metropolis tile: aerial city street with detection boxes
- photo at x 61.4, y 21.2, w 5.2, h 11.9: Clara tile: lung scan in grey-green on black
- photo at x 67, y 21.1, w 5.3, h 13.4: Drive tile: black self-driving car with green accents
- body at x 29.2, y 32.6, w 2.2, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Jarvis
- body at x 34.6, y 32.6, w 2.6, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Maxine
- body at x 40.4, y 32.6, w 2.4, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Merlin
- body at x 45.3, y 32.6, w 3.7, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Morpheus
- body at x 51.8, y 32.6, w 2, h 1.5 [DINPro-Regular; font size 1.54% of slide height; #FFFFFF; center aligned]: Isaac
- body at x 56.6, y 32.6, w 3.9, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Metropolis
- body at x 63, y 32.6, w 2, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Clara
- body at x 68.7, y 32.6, w 1.9, h 1.5 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: Drive
- shape at x 27.1, y 40.1, w 45.8, h 23.5 [#9A7440]: NVIDIA AI Enterprise gold panel with stacked bands (brass gradient #B08D57 to #7A5C2E, square corners, drop shadow)
- body at x 42.7, y 41.1, w 14.5, h 2.5 [DINPro-Medium; font size 2.47% of slide height; #FFFFFF; center aligned]: NVIDIA AI ENTERPRISE
- shape at x 27.9, y 44.3, w 44, h 4.8 [#8C6A3C]: NVIDIA GPU Cloud Registry band (inset band with thin dark separator)
- body at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA GPU CLOUD REGISTRY
- shape at x 27.9, y 50, w 5, h 6.7 [#8C6A3C]: cuIO tile (boxed tile, thin dark outline)
- body at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuIO
- shape at x 33.5, y 50, w 5, h 6.7 [#8C6A3C]: cuDF tile (boxed tile, thin dark outline)
- body at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDF
- shape at x 39.1, y 50, w 5, h 6.7 [#8C6A3C]: cuDNN tile (boxed tile, thin dark outline)
- body at x 40, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuDNN
- shape at x 44.7, y 50, w 5, h 6.7 [#8C6A3C]: cuML tile (boxed tile, thin dark outline)
- body at x 46, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuML
- shape at x 50.4, y 50, w 5, h 6.7 [#8C6A3C]: cuGraph tile (boxed tile, thin dark outline)
- body at x 51, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: cuGraph
- shape at x 56, y 50, w 5, h 6.7 [#8C6A3C]: TAO tile (boxed tile, thin dark outline)
- body at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: TAO
- shape at x 61.6, y 50, w 5, h 6.7 [#8C6A3C]: TensorRT tile (boxed tile, thin dark outline)
- body at x 62, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: TensorRT
- shape at x 67.2, y 50, w 5, h 6.7 [#8C6A3C]: Triton tile (boxed tile, thin dark outline)
- body at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: Triton
- shape at x 27.9, y 57.6, w 44, h 4.9 [#8C6A3C]: Bottom gold band (inset band with thin dark separator)
- body at x 36.9, y 59.3, w 26.1, h 1.7 [DINPro-Regular with DINPro-Black for Aerial 5G and Morpheus; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA CUDA, DOCA, vGPU, Magnum IO, Aerial 5G, Morpheus
- shape at x 27.1, y 65.1, w 45.8, h 4.9 [#0A6EC8]: VMware vSphere blue bar (solid fill, square corners, slight drop shadow)
- body at x 46.4, y 66.7, w 7.2, h 1.7 [DINPro-Regular; font size 1.73% of slide height; #FFFFFF; center aligned]: VMware vSphere
- photo at x 18.4, y 58.7, w 18.6, h 21.8: White server chassis with gold GPU card and exposed circuit board, angled (full colour photo cut out on black, overlaps gold panel left edge)
- logo at x 38.4, y 71.6, w 6.9, h 5.7 [#76B900]: NVIDIA CERTIFIED badge with NVIDIA eye logo and CERTIFIED text in white outline
- logo at x 51.5, y 72, w 20.8, h 5.6 [#FFFFFF]: Partner logos: Atos, DELL Technologies, FUJITSU, GIGABYTE, H3C, hp, inspur, Lenovo, QCT, SUPERMICRO (white monochrome logos in two rows of five)
- photo at x 7.8, y 78.1, w 8.2, h 14.7: NVIDIA BlueField-2 circular insert: DPU card with chip on black (circle, thin gold rim)
- photo at x 17.5, y 78.1, w 8.2, h 14.7: NVIDIA A100/A30 circular insert: gold-bronze GPU card on black (circle, thin gold rim)
- photo at x 27.1, y 78.1, w 8.2, h 14.7: NVIDIA A40/A10 circular insert: gold-bronze GPU card on black (circle, thin gold rim)
- photo at x 36.8, y 78.1, w 8.2, h 14.7: NVIDIA Aerial A100 circular insert: board with large chip on black (circle, thin gold rim)
- body at x 9.7, y 87.8, w 4.3, h 3.3 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA BlueField-2
- body at x 19.8, y 87.8, w 3.5, h 3.3 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA A100/A30
- body at x 29.7, y 87.8, w 3, h 3.3 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA A40/A10
- body at x 38.4, y 87.8, w 5.2, h 3.3 [DINPro-Regular; font size 1.48% of slide height; #FFFFFF; center aligned]: NVIDIA Aerial A100
- title at x 24.4, y 7.9, w 51.3, h 4.1 [DINPro-Bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA AI ENTERPRISE PLATFORM

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 27.7, y 30.9, w 44.6, h 4.0: 1285 by 65 pixels
- image at x 27.7, y 30.9, w 44.6, h 4.0: 1285 by 65 pixels
- image at x 37.3, y 69.7, w 9.2, h 9.6: 647 by 381 pixels
- image at x 35.3, y 58.6, w 29.8, h 2.8: 3576 by 192 pixels
- image at x 50.2, y 21.2, w 5.2, h 13.7: 387 by 565 pixels
- image at x 67.0, y 21.1, w 5.3, h 13.4: 316 by 454 pixels
- image at x 44.6, y 21.2, w 5.2, h 13.5: 314 by 455 pixels
- image at x 27.7, y 21.3, w 5.2, h 13.5: 312 by 455 pixels
- image at x 55.8, y 21.2, w 5.2, h 13.5: 306 by 447 pixels
- image at x 39.0, y 21.3, w 5.2, h 13.4: 310 by 452 pixels
- image at x 33.4, y 21.3, w 5.2, h 12.6: 401 by 534 pixels
- image at x 61.4, y 21.2, w 5.2, h 11.9: 314 by 402 pixels
- image at x 44.3, y 65.8, w 11.4, h 3.3: 1372 by 222 pixels
- image at x 42.5, y 45.5, w 14.9, h 2.5: 1791 by 167 pixels
- image at x 33.5, y 52.1, w 4.9, h 2.6: 588 by 177 pixels
- image at x 27.9, y 52.1, w 4.9, h 2.5: 588 by 167 pixels
- image at x 44.7, y 52.2, w 4.9, h 2.4: 588 by 163 pixels
- image at x 56.0, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 61.6, y 52.3, w 4.9, h 2.2: 588 by 151 pixels
- image at x 39.1, y 52.3, w 4.9, h 2.2: 587 by 149 pixels
- image at x 67.2, y 52.3, w 4.9, h 2.1: 588 by 144 pixels
- image at x 50.4, y 52.3, w 4.9, h 2.1: 588 by 143 pixels
- image at x 55.1, y 72.1, w 5.2, h 1.2: 314 by 41 pixels
- image at x 65.3, y 73.8, w 1.7, h 3.6: 204 by 245 pixels
- image at x 69.6, y 74.8, w 2.5, h 2.3: 153 by 78 pixels
- text at x 24.4, y 7.9, w 51.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA AI ENTERPRISE PLATFORM
- text at x 42.7, y 41.1, w 14.5, h 2.5 [DINPro-Medium; font size 2.47; #FFFFFF]: NVIDIA AI ENTERPRISE
- text at x 51.8, y 32.6, w 2.0, h 1.5 [DINPro-Regular; font size 1.54; #FFFFFF]: Isaac
- text at x 29.2, y 32.6, w 2.2, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Jarvis
- text at x 34.6, y 32.6, w 2.6, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Maxine
- text at x 40.4, y 32.6, w 2.4, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Merlin
- text at x 45.3, y 32.6, w 3.7, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Morpheus
- text at x 56.6, y 32.6, w 3.9, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Metropolis
- text at x 63.0, y 32.6, w 2.0, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Clara
- text at x 68.7, y 32.6, w 1.9, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: Drive
- text at x 43.4, y 46.1, w 13.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA GPU CLOUD REGISTRY
- text at x 29.4, y 52.6, w 1.9, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuIO
- text at x 34.8, y 52.7, w 2.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDF
- text at x 40.0, y 52.6, w 3.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuDNN
- text at x 46.0, y 52.6, w 2.4, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuML
- text at x 51.0, y 52.6, w 3.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: cuGraph
- text at x 57.6, y 52.6, w 1.7, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TAO
- text at x 62.0, y 52.6, w 4.1, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: TensorRT
- text at x 68.4, y 52.6, w 2.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: Triton
- text at x 36.9, y 59.3, w 17.6, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: NVIDIA CUDA, DOCA, vGPU, Magnum IO,
- text at x 54.5, y 59.3, w 4.2, h 1.7 [DINPro-Black; font size 1.73; #FFFFFF]: Aerial 5G
- text at x 58.6, y 59.3, w 0.5, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: ,
- text at x 59.1, y 59.3, w 4.5, h 1.7 [DINPro-Black; font size 1.73; #FFFFFF]: Morpheus
- text at x 46.4, y 66.7, w 7.2, h 1.7 [DINPro-Regular; font size 1.73; #FFFFFF]: VMware vSphere
- text at x 10.6, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 20.3, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 29.9, y 87.8, w 2.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA
- text at x 38.4, y 87.9, w 5.2, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: NVIDIA Aerial
- text at x 9.7, y 89.6, w 4.3, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: BlueField-2
- text at x 19.8, y 89.6, w 3.5, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A100/A30
- text at x 29.7, y 89.6, w 3.0, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A40/A10
- text at x 40.0, y 89.6, w 1.8, h 1.5 [DINPro-Regular; font size 1.48; #FFFFFF]: A100

### Slide 80

**Text**

NVIDIA DRIVE AV
DATA COLLECTING,
TESTING
MAPPING, TRAINING
SIMULATION
AV DRIVING
AV WORLD MODEL
DRIVE
Hyperion
DGX
A100
DRIVE
Constellation
AV on
DRIVE AGX
IX on
DRIVE AGX

**Layout**

Five equal square-cornered picture panels run left to right across the vertical middle of the slide, each with a bold uppercase label at its top and a circular hardware badge with caption below it, linked by gold arrows. A single centred title sits at the top, and a gold loop line returns from the last badge to the first along the bottom of the panel row. No footer, slide number, or logo appears.

**Visuals**

Five rectangular photographs in a row, each with a thin gold-brown border, followed by five circular hardware images with thin gold-brown rims and captions. Photo 1: a black Ford sedan with a green-and-black NVIDIA sensor livery driving on a multi-lane highway under an overpass, sensor rack on the roof, daylight, cool green-grey tones. Photo 2: a dark SUV with green NVIDIA livery on a highway under concrete overpass pillars, daylight, muted grey-green tones. Photo 3: a computer-simulated highway with overpass pillars, glowing green lane lines and teal bounding boxes around vehicles, blue-grey and amber tones. Photo 4: a driving-view render of a highway with cyan and green lane lines and cyan and orange bounding boxes around cars, grey tones. Photo 5: a silver electric concept car viewed from behind with red taillights on a dark road with bright green lane-line curves, black and green tones. Badge 1: a white roof-mounted sensor pod (Hyperion) on a dark background with green electronics. Badge 2: a gold-grey DGX A100 server unit at an angle. Badge 3: two gold-grey DRIVE Constellation units side by side. Badge 4: a green-circuit-board AV on DRIVE AGX module with a gold heatsink and chip. Badge 5: a green-circuit-board IX on DRIVE AGX module with a gold heatsink and chip. Gold arrows connect the badges left to right, and a gold rectangular loop connects the last badge back to the first. Background is a dark grey road-like gradient with soft vignette.

**Design**

Background: Black (#000000) fading to dark grey (#2A2A2A) gradient floor in the lower half of the slide. Black background with a dark grey floor gradient in the lower half, white bold sans-serif title, white medium sans-serif panel labels, white regular sans-serif captions, gold-brown #8C7040 accents for borders, rims and connector lines, and green #76B900 in the photographs. Title is DIN-style bold uppercase at about 4.1% of slide height; labels and captions at about 2.0%. Panels and badges have sharp square corners on the rectangles and perfect circles for the badges, with a thin gold-brown outline and no shadow.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#000000]: Full-slide black background fill (Solid fill covering slide, with dark grey floor gradient in lower half.)
- photo at x 0, y 0, w 100, h 100 [#2A2A2A]: Full-slide background image of dark grey floor and gradient (Full-bleed background image, 3840 by 2160 pixels, behind all elements.)
- title at x 41.2, y 7.9, w 17.6, h 4.1 [DIN Pro, bold, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA DRIVE AV
- photo at x 17.8, y 28.1, w 23.9, h 26 [#4A5A4A]: Photograph: black Ford sedan with green NVIDIA livery on highway under overpass (Rectangular photo with thin gold-brown border, square corners, no shadow.)
- text at x 12.6, y 30.4, w 10.1, h 4.4 [DIN Pro, medium, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: DATA COLLECTING, / TESTING
- photo at x 31.8, y 28.1, w 23.9, h 26 [#5A6A5A]: Photograph: dark SUV with green NVIDIA livery on highway under overpass pillars (Rectangular photo with thin gold-brown border, square corners, no shadow.)
- text at x 28.5, y 30.4, w 10.4, h 2 [DIN Pro, medium, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: MAPPING, TRAINING
- photo at x 45.8, y 28.1, w 23.9, h 26 [#3A4A5A]: Render: simulated highway with overpass pillars, green lane lines and teal bounding boxes (Rectangular render with thin gold-brown border, square corners, no shadow.)
- text at x 46.8, y 30.5, w 6.4, h 2 [DIN Pro, medium, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: SIMULATION
- photo at x 59.4, y 28.1, w 23.9, h 26 [#4A4F55]: Render: driving view of highway with cyan and green lane lines and cyan and orange bounding boxes (Rectangular render with thin gold-brown border, square corners, no shadow.)
- text at x 63.4, y 30.5, w 5.9, h 2 [DIN Pro, medium, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: AV DRIVING
- photo at x 72.9, y 28.1, w 23.9, h 26 [#1A1F24]: Render: silver electric concept car from behind with red taillights and green lane-line curves (Rectangular render with thin gold-brown border, square corners, no shadow.)
- text at x 77.8, y 30.5, w 9.3, h 2 [DIN Pro, medium, uppercase; font size 1.98% of slide height; #FFFFFF; center aligned]: AV WORLD MODEL
- illustration at x 12.2, y 58.4, w 16, h 17.3 [#000000]: Hardware image: DRIVE Hyperion white roof sensor pod (Circular image with thin gold-brown rim, black background, cropped to circle.)
- text at x 15.2, y 64.1, w 4.4, h 4.3 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: DRIVE / Hyperion
- illustration at x 28.2, y 58.4, w 16, h 17.3 [#000000]: Hardware image: DGX A100 server unit (Circular image with thin gold-brown rim, black background, cropped to circle.)
- text at x 32.5, y 64.1, w 2.4, h 4.3 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: DGX / A100
- illustration at x 44.6, y 58.4, w 16, h 17.3 [#000000]: Hardware image: two DRIVE Constellation units (Circular image with thin gold-brown rim, black background, cropped to circle.)
- text at x 46.7, y 64.1, w 6.5, h 4.3 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: DRIVE / Constellation
- illustration at x 61, y 58.4, w 16, h 17.3 [#000000]: Hardware image: AV on DRIVE AGX module (Circular image with thin gold-brown rim, black background, cropped to circle.)
- text at x 63.6, y 64.1, w 5.3, h 4.3 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: AV on / DRIVE AGX
- illustration at x 77.2, y 58.4, w 16, h 17.3 [#000000]: Hardware image: IX on DRIVE AGX module (Circular image with thin gold-brown rim, black background, cropped to circle.)
- text at x 79.9, y 64.1, w 5.3, h 4.3 [DIN Pro, regular; font size 1.98% of slide height; #FFFFFF; center aligned]: IX on / DRIVE AGX
- line at x 23.5, y 61.3, w 53.5, h 0.5 [#8C7040]: Gold arrows connecting badges left to right (Thin gold-brown line with small arrowheads pointing right, between badges.)
- line at x 10.6, y 61.3, w 78.6, h 23.5 [#8C7040]: Gold loop connector from last badge back to first badge (Thin gold-brown rectangular outline running below the badges, with arrowhead entering the first badge from the left and line leaving the last badge on the right.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 41.2, y 7.9, w 17.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA DRIVE AV
- text at x 12.6, y 30.4, w 10.1, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: DATA COLLECTING,
- text at x 28.5, y 30.4, w 10.4, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: MAPPING, TRAINING
- text at x 46.8, y 30.5, w 6.4, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: SIMULATION
- text at x 63.4, y 30.5, w 5.9, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: AV DRIVING
- text at x 77.8, y 30.5, w 9.3, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: AV WORLD MODEL
- text at x 15.3, y 32.7, w 4.4, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: TESTING
- text at x 15.9, y 64.1, w 3.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DRIVE
- text at x 32.6, y 64.1, w 2.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DGX
- text at x 48.4, y 64.1, w 3.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DRIVE
- text at x 64.9, y 64.1, w 3.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: AV on
- text at x 81.3, y 64.1, w 2.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: IX on
- text at x 15.2, y 66.4, w 4.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Hyperion
- text at x 32.5, y 66.4, w 2.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: A100
- text at x 46.7, y 66.4, w 6.5, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Constellation
- text at x 63.6, y 66.4, w 5.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DRIVE AGX
- text at x 79.9, y 66.4, w 5.3, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: DRIVE AGX

### Slide 81

**Review notes**

- Worth studying: A simple bar-style chart with the three generations' TOPS and SPECint figures makes the 'TOPS is the new horsepower' headline visible without extra text.

**Text**

TOPS IS THE NEW
HORSEPOWER
TOPS
250
0
Parker
Xavier
Orin
2018
1 TOPS
7 SPECint
2020
30 TOPS
17 SPECint
2022
254 TOPS
25 SPECint
SPECrate2017_int

**Layout**

Chart-led slide with no visible grid. The title sits left-aligned at mid-height in the left third, with the chart occupying the right half. A timeline of three years runs along a horizontal baseline at about 77% of slide height, with a faint footer at bottom-left, about 4% from the left edge and 94% from the top. No slide number is shown.

**Visuals**

Line chart with three markers on a rising green polyline. Chart title: none printed. Y-axis: vertical label 'TOPS' rotated 90 degrees, with tick labels '0' at baseline and '250' about two-thirds up the axis; no unit beyond TOPS, and no printed range beyond 0 to 250. X-axis: years 2018, 2020, 2022 spaced evenly below a grey horizontal baseline. Series values printed under each year: 2018 is 1 TOPS and 7 SPECint; 2020 is 30 TOPS and 17 SPECint; 2022 is 254 TOPS and 25 SPECint. Markers are small filled green dots at 2018 (about 1 TOPS, near baseline), 2020 (about 30 TOPS, low on the chart) and 2022 (about 254 TOPS, near the 250 tick). Each marker has a module-board photograph above it labelled Parker (2018), Xavier (2020) and Orin (2022). No legend. No highlighted points beyond the markers. Photographs are three small dark circuit-board modules, each showing a square grey chip with a silver heat spreader, rows of small blue and silver connectors along the lower edge and a black power connector at the lower left, shown at a slight angle, unboxed, on the dark background with no overlay.

**Design**

Background: Full-bleed dark photographic texture, black #000000 at the top fading to charcoal #2A2A2A at the bottom. Black background fading to dark charcoal grey toward the bottom edge with a faint scuffed texture. Title in white DIN Pro Bold, uppercase, about 4.1% of slide height. Chart labels and body text in white DIN Pro Regular, about 1.9 to 2.7% of slide height. Accent is bright green #76B900 for the trend line and markers. Baseline is a thin light grey line, about #B0B0B0, around 0.2% of slide height thick. Footer text is grey #9A9A9A. No shapes, corner radii, shadows or borders.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Solid white fill covering the whole slide, hidden beneath the background photograph (Rectangle, no outline, fully obscured by the background image.)
- photo at x 0, y 0, w 100, h 100 [#101010]: Full-bleed dark textured background photograph of a scuffed surface, black at top fading to charcoal at bottom (Image 3840 by 2160 px, not cropped, no overlay, sits behind all other elements.)
- line at x 42.1, y 77.4, w 41.1, h 0.2 [#B0B0B0]: Horizontal chart baseline (x-axis) from 2018 column to 2022 column (Thin light grey stroke, about 0.2% of slide height, no arrowheads.)
- chart at x 45.7, y 37.1, w 31, h 39.3 [#76B900]: Green trend line through three markers at 2018 (1 TOPS), 2020 (30 TOPS) and 2022 (254 TOPS), with a vertical TOPS axis from 0 to 250 (Straight segments joining markers: 2018 at about x 45.7% y 76.4%, 2020 at about x 61.0% y 68.6%, 2022 at about x 76.6% y 37.1%. Line stroke about 0.3% of slide height, bright green #76B900. Markers are small filled green circles about 0.6% of slide height in diameter, with no legend and no highlighted points beyond the markers.)
- photo at x 74.1, y 25.3, w 5.1, h 7.8 [#2B2B2B]: Orin module board photograph, dark circuit board with square grey chip, silver heat spreader, row of blue and silver connectors and black power connector (Image 121 by 104 px, unboxed, no border, no shadow, sits above the 2022 marker.)
- photo at x 57.4, y 56.7, w 5.1, h 7.8 [#2B2B2B]: Xavier module board photograph, dark circuit board with square grey chip, silver heat spreader, row of blue and silver connectors and black power connector (Image 121 by 104 px, unboxed, no border, no shadow, sits above the 2020 marker.)
- photo at x 43.2, y 64.9, w 5.1, h 7.8 [#2B2B2B]: Parker module board photograph, dark circuit board with square grey chip, silver heat spreader, row of blue and silver connectors and black power connector (Image 121 by 104 px, unboxed, no border, no shadow, sits above the 2018 marker.)
- title at x 6.7, y 45.8, w 19.1, h 8.5 [DINPro-Bold, sans-serif, bold, uppercase, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; left aligned]: TOPS IS THE NEW / HORSEPOWER (Two lines, tight leading about 1.1; line break after NEW.)
- body at x 36.3, y 54.6, w 1.4, h 5.9 [DINPro-Regular, sans-serif, regular, uppercase; font size 2.47% of slide height; #FFFFFF; center aligned]: TOPS (Vertical axis title rotated 90 degrees counter-clockwise, reading upward.)
- body at x 38.7, y 35.7, w 2.4, h 2.7 [DINPro-Regular, sans-serif, regular; font size 2.72% of slide height; #FFFFFF; right aligned]: 250 (Y-axis tick label, no tick mark.)
- body at x 40.3, y 76.4, w 0.8, h 2.7 [DINPro-Regular, sans-serif, regular; font size 2.72% of slide height; #FFFFFF; right aligned]: 0 (Y-axis origin label aligned with the baseline.)
- body at x 43.9, y 61.6, w 3.8, h 2.2 [DINPro-Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; center aligned]: Parker (Module name label above the 2018 board photograph.)
- body at x 58.2, y 53.4, w 3.4, h 2.2 [DINPro-Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; center aligned]: Xavier (Module name label above the 2020 board photograph.)
- body at x 75.4, y 22, w 2.4, h 2.2 [DINPro-Regular, sans-serif, regular; font size 2.22% of slide height; #FFFFFF; center aligned]: Orin (Module name label above the 2022 board photograph.)
- body at x 44.3, y 80.6, w 2.9, h 2.5 [DINPro-Regular, sans-serif, regular; font size 2.47% of slide height; #FFFFFF; center aligned]: 2018 (X-axis year label.)
- body at x 59.6, y 80.6, w 2.9, h 2.5 [DINPro-Regular, sans-serif, regular; font size 2.47% of slide height; #FFFFFF; center aligned]: 2020 (X-axis year label.)
- body at x 75.2, y 80.6, w 2.9, h 2.5 [DINPro-Regular, sans-serif, regular; font size 2.47% of slide height; #FFFFFF; center aligned]: 2022 (X-axis year label.)
- body at x 43.5, y 84.3, w 4.6, h 4.1 [DINPro-Regular, sans-serif, regular; font size 1.85% of slide height; #FFFFFF; center aligned]: 1 TOPS / 7 SPECint (Two stacked lines printed under 2018; first line 1 TOPS at x 44.1 y 84.3, second line 7 SPECint at x 43.5 y 86.5.)
- body at x 58.5, y 84.3, w 5.1, h 4.1 [DINPro-Regular, sans-serif, regular; font size 1.85% of slide height; #FFFFFF; center aligned]: 30 TOPS / 17 SPECint (Two stacked lines printed under 2020; first line 30 TOPS at x 59.1 y 84.3, second line 17 SPECint at x 58.5 y 86.5.)
- body at x 74.1, y 84.3, w 5.1, h 4.1 [DINPro-Regular, sans-serif, regular; font size 1.85% of slide height; #FFFFFF; center aligned]: 254 TOPS / 25 SPECint (Two stacked lines printed under 2022; first line 254 TOPS at x 74.4 y 84.3, second line 25 SPECint at x 74.1 y 86.5.)
- footer at x 3.9, y 94.4, w 5, h 1.1 [DINPro-Regular, sans-serif, regular; font size 1.11% of slide height; #9A9A9A; left aligned]: SPECrate2017_int (Source note at bottom-left, small regular weight, no capitals transformation.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 43.2, y 64.9, w 5.1, h 7.8: 121 by 104 pixels
- image at x 74.1, y 25.3, w 5.1, h 7.8: 121 by 104 pixels
- image at x 57.4, y 56.7, w 5.1, h 7.8: 121 by 104 pixels
- text at x 75.4, y 22.0, w 2.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Orin
- text at x 6.7, y 45.8, w 19.1, h 8.5 [DINPro-Bold; font size 4.07; #FFFFFF]: TOPS IS THE NEW HORSEPOWER
- text at x 38.7, y 35.7, w 2.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 250
- text at x 36.3, y 54.6, w 1.4, h 5.9 [DINPro-Regular; font size 2.47; #FFFFFF]: TOPS
- text at x 58.2, y 53.4, w 3.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Xavier
- text at x 43.9, y 61.6, w 3.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Parker
- text at x 40.3, y 76.4, w 0.8, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 0
- text at x 44.3, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2018
- text at x 59.6, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2020
- text at x 75.2, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2022
- text at x 44.1, y 84.3, w 3.3, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 1 TOPS
- text at x 59.1, y 84.3, w 3.8, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 30 TOPS
- text at x 74.4, y 84.3, w 4.4, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 254 TOPS
- text at x 43.5, y 86.5, w 4.6, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 7 SPECint
- text at x 58.5, y 86.5, w 5.1, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 17 SPECint
- text at x 74.1, y 86.5, w 5.1, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 25 SPECint
- text at x 3.9, y 94.4, w 5.0, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: SPECrate2017_int

### Slide 82

**Text**

ANNOUNCING ORIN CENTRAL COMPUTER / 1 Chip – 4 Domains / CLUSTER / INFOTAINMENT / PASSENGER / INTERACTION & MONITORING / AV WITH CONFIDENCE VIEW / FUSA Graphics / OS #1 / Entertainment Graphics & Multimedia / OS #2 / FUSA CV, AR, & Conversational AI / OS #4 / FUSA CV & AR / OS #3 / ORIN VEHICLE COMPUTER / Centralized & Software Defined / Tightly Integrated with AV Applications / Containerized & Easy to Upgrade / SOTA Security and Functional Safety

**Layout**

Four equal cards in a row across the upper-middle of the slide, each about 21 percent wide with even gaps of about 2.3 percent, left margin about 4 percent and right margin about 4 percent. The centred title block sits at the top with the title above a subtitle, and each card has a centred column heading above it. Below the cards, four gold lines converge on a central chip at the bottom centre, with a left-aligned four-line list to its right and a label to its left. No footer, page number or logo band appears on the slide.

**Visuals**

Four framed screenshot or photo panels, each set in a thin dark bronze border. Panel 1 (Cluster): a digital instrument-cluster render on a near-black ground, with a central speedometer glowing red and orange arcs, a large white '120' readout, a '100 %' gauge at left, a '438' readout and a '13:50' clock at bottom. Panel 2 (Infotainment): a blurred dark blue touchscreen interface with app tiles across the top, a search bar, a round dial showing '21.5' and a text prompt reading 'Are you with me'. Panel 3 (Passenger interaction and monitoring): a photo inside a car interior with a woman with long dark hair in a white top on the left looking upward and a man in a dark shirt wearing a seatbelt on the right, with a thin green rectangle drawn around the man's face; daylight from side windows, neutral warm tones. Panel 4 (AV with confidence view): a photo of a Mercedes-Benz steering wheel with the star emblem and a dashboard with blue ambient strip lighting, a road ahead under a pale sky with trees, a green lane-guidance line and a small '38' speed readout on a heads-up display. Below the panels are four green and grey caption bars. A central photograph of the NVIDIA Orin chip sits at bottom centre: a grey metal package with a gold-tinted silicon die, grey heat-spreader edges and a small NVIDIA logo at its lower edge; it is boxed, not cropped, lit from above with a soft reflection on the floor. Four thin gold connector lines run from the bottom of each card down and converge on the top of the chip.

**Design**

Background: Near-black to dark charcoal (#0A0A0A to #2A2A2A) gradient with a reflective floor, from the full-bleed 3840 by 2160 backdrop image. Black to charcoal background with a soft spotlight and reflective floor at the bottom. Titles and body text are white #FFFFFF, with accent green #76B900 on the function bars and grey #7F7F7F on the OS bars. Connector lines and card borders are bronze-gold, about #B8975A. Typeface is DIN Pro, a condensed-proportion grotesque sans-serif. The title is bold capitals at about 4.07 percent of slide height, column headings are regular capitals at about 2.2 percent, and body and bar text is regular at about 2.0 percent. Bars and frames have square corners, with no shadows.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#0A0A0A]: Full-bleed dark studio backdrop image with a black top fading to dark charcoal floor and a faint reflection under the chip; a second full-slide image of the same extent sits behind it (Covers the whole slide; the measured white #FFFFFF fill beneath it is hidden. Not cropped.)
- shape at x 3.8, y 25.4, w 21.9, h 30.5 [#3B3024]: Card frame 1 (Cluster) (Thin bronze-brown border about 0.4 percent wide with square corners, enclosing the screenshot, green bar and grey bar; no fill of its own apart from the border, dark interior.)
- shape at x 27.3, y 25.4, w 21.9, h 30.5 [#3B3024]: Card frame 2 (Infotainment) (Thin bronze-brown border about 0.4 percent wide with square corners.)
- shape at x 50.7, y 25.4, w 21.9, h 30.5 [#3B3024]: Card frame 3 (Passenger interaction and monitoring) (Thin bronze-brown border about 0.4 percent wide with square corners.)
- shape at x 74.2, y 25.4, w 21.9, h 30.5 [#3B3024]: Card frame 4 (AV with confidence view) (Thin bronze-brown border about 0.4 percent wide with square corners.)
- photo at x 4.2, y 26.2, w 21.2, h 20.3 [#0B1A2E]: Screenshot of digital instrument cluster with red and orange glowing arcs, speed readout 120 and clock 13:50 (Boxed, not cropped; the top edge bleeds into the frame's dark interior.)
- photo at x 27.7, y 26.2, w 21.2, h 20.3 [#1B2A40]: Screenshot of infotainment touchscreen UI with app tiles and a dial reading 21.5 (Boxed, slightly rotated perspective view of the screen.)
- photo at x 51.1, y 26.2, w 21.2, h 20.4 [#2B2B2B]: Photo of two people in a car: woman with long dark hair looking up on the left, man in dark shirt wearing a seatbelt on the right, green detection rectangle around his face (Boxed; green outline about 0.2 percent wide, square, around the man's face.)
- photo at x 74.6, y 26.2, w 21.2, h 20.4 [#6E7A8A]: Photo of Mercedes-Benz steering wheel and blue-lit dashboard with a road view and green lane line (Boxed; the Mercedes star is visible at the centre of the steering wheel; a green guidance line runs down the lower right of the road.)
- shape at x 4.2, y 47.3, w 21.2, h 3.9 [#76B900]: Green function bar 1 (Filled rectangle, square corners, no shadow.)
- shape at x 4.2, y 51.6, w 21.2, h 2.5 [#7F7F7F]: Grey OS bar 1 (Filled rectangle, square corners, no shadow.)
- shape at x 27.7, y 47.3, w 21.2, h 3.9 [#76B900]: Green function bar 2 (Filled rectangle, square corners.)
- shape at x 27.7, y 51.6, w 21.2, h 2.5 [#7F7F7F]: Grey OS bar 2 (Filled rectangle, square corners.)
- shape at x 51.1, y 47.3, w 21.2, h 3.9 [#76B900]: Green function bar 3 (Filled rectangle, square corners.)
- shape at x 51.1, y 51.6, w 21.2, h 2.5 [#7F7F7F]: Grey OS bar 3 (Filled rectangle, square corners.)
- shape at x 74.6, y 47.3, w 21.2, h 3.9 [#76B900]: Green function bar 4 (Filled rectangle, square corners.)
- shape at x 74.6, y 51.6, w 21.2, h 2.5 [#7F7F7F]: Grey OS bar 4 (Filled rectangle, square corners.)
- line at x 15.3, y 55, w 32.4, h 19.6 [#B8975A]: Gold connector line from card 1 to chip (About 0.15 percent stroke, angled from under card 1 down-right to the chip top, then vertical; approximate position.)
- line at x 38.3, y 55, w 11.1, h 19.6 [#B8975A]: Gold connector line from card 2 to chip (About 0.15 percent stroke, angled from under card 2 down-right to a shared vertical at the chip top; approximate position.)
- line at x 50.8, y 55, w 10.7, h 19.6 [#B8975A]: Gold connector line from card 3 to chip (About 0.15 percent stroke, angled from under card 3 down-left to a shared vertical at the chip top; approximate position.)
- line at x 52.1, y 55, w 32.4, h 19.6 [#B8975A]: Gold connector line from card 4 to chip (About 0.15 percent stroke, angled from under card 4 down-left to the chip top; approximate position.)
- title at x 28.3, y 7.9, w 43.4, h 4.1 [DIN Pro, bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING ORIN CENTRAL COMPUTER
- subtitle at x 43.5, y 12.5, w 13, h 2.7 [DIN Pro, regular, sentence case; font size 2.72% of slide height; #FFFFFF; center aligned]: 1 Chip – 4 Domains
- body at x 12.1, y 21, w 5.3, h 2.2 [DIN Pro, regular, all capitals; font size 2.22% of slide height; #FFFFFF; center aligned]: CLUSTER
- body at x 33.8, y 21, w 8.8, h 2.2 [DIN Pro, regular, all capitals; font size 2.22% of slide height; #FFFFFF; center aligned]: INFOTAINMENT
- body at x 53.3, y 19.6, w 17.1, h 4.9 [DIN Pro, regular, all capitals; font size 2.22% of slide height; #FFFFFF; center aligned]: PASSENGER / INTERACTION & MONITORING (Two lines; PASSENGER at x 58.2 y 19.6 and INTERACTION & MONITORING at x 53.3 y 22.3.)
- body at x 77.3, y 21, w 15.8, h 2.2 [DIN Pro, regular, all capitals; font size 2.22% of slide height; #FFFFFF; center aligned]: AV WITH CONFIDENCE VIEW
- body at x 11.1, y 48.4, w 7.4, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: FUSA Graphics (Centred on green bar 1.)
- body at x 28.9, y 48.4, w 18.7, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: Entertainment Graphics & Multimedia (Centred on green bar 2.)
- body at x 53.4, y 48.4, w 16.6, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: FUSA CV, AR, & Conversational AI (Centred on green bar 3.)
- body at x 81.7, y 48.4, w 7.1, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: FUSA CV & AR (Centred on green bar 4.)
- body at x 13.3, y 52, w 3, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: OS #1 (Centred on grey bar 1.)
- body at x 36.8, y 52, w 3, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: OS #2 (Centred on grey bar 2.)
- body at x 60.2, y 52, w 3, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: OS #4 (Centred on grey bar 3.)
- body at x 83.7, y 52, w 3, h 2 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; center aligned]: OS #3 (Centred on grey bar 4.)
- photo at x 44.5, y 74.5, w 12.5, h 18.5 [#8A8A8A]: Photograph of the NVIDIA Orin chip package, a grey metal module with a gold-tinted silicon die and NVIDIA logo at lower edge (Boxed, not cropped; the four gold connector lines meet its top edge; slight reflection on the floor below.)
- logo at x 48.5, y 91.5, w 3.5, h 0.9 [#D0D0D0]: NVIDIA logo printed on the chip package (Small, on the lower edge of the chip package.)
- body at x 27.7, y 82.9, w 15, h 2.2 [DIN Pro, regular, all capitals; font size 2.22% of slide height; #FFFFFF; right aligned]: ORIN VEHICLE COMPUTER
- body at x 59.9, y 75.3, w 19, h 17 [DIN Pro, regular, sentence case; font size 1.98% of slide height; #FFFFFF; left aligned]: Centralized & Software Defined / Tightly Integrated with AV Applications / Containerized & Easy to Upgrade / SOTA Security and Functional Safety (Four lines at y 75.3, 79.6, 84.0 and 88.3 with equal spacing of about 4.4 percent of slide height; no bullets.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 4.2, y 47.3, w 21.2, h 3.9: #76B900
- fill at x 4.2, y 51.6, w 21.2, h 2.5: #7F7F7F
- fill at x 27.7, y 47.3, w 21.2, h 3.9: #76B900
- fill at x 27.7, y 51.6, w 21.2, h 2.5: #7F7F7F
- fill at x 51.1, y 47.3, w 21.2, h 3.9: #76B900
- fill at x 51.1, y 51.6, w 21.2, h 2.5: #7F7F7F
- fill at x 74.6, y 47.3, w 21.2, h 3.9: #76B900
- fill at x 74.6, y 51.6, w 21.2, h 2.5: #7F7F7F
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 74.6, y 26.2, w 21.2, h 20.4: 502 by 268 pixels
- image at x 51.1, y 26.2, w 21.2, h 20.4: 1801 by 964 pixels
- image at x 4.2, y 26.2, w 21.2, h 20.3: 831 by 445 pixels
- image at x 27.7, y 26.2, w 21.2, h 20.3: 710 by 382 pixels
- text at x 28.3, y 7.9, w 43.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING ORIN CENTRAL COMPUTER
- text at x 43.5, y 12.5, w 13.0, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 1 Chip – 4 Domains
- text at x 58.2, y 19.6, w 7.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: PASSENGER
- text at x 12.1, y 21.0, w 5.3, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: CLUSTER
- text at x 33.8, y 21.0, w 8.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: INFOTAINMENT
- text at x 77.3, y 21.0, w 15.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: AV WITH CONFIDENCE VIEW
- text at x 53.3, y 22.3, w 17.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: INTERACTION & MONITORING
- text at x 11.1, y 48.4, w 7.4, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: FUSA Graphics
- text at x 28.9, y 48.4, w 18.7, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Entertainment Graphics & Multimedia
- text at x 53.4, y 48.4, w 16.6, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: FUSA CV, AR, & Conversational AI
- text at x 81.7, y 48.4, w 7.1, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: FUSA CV & AR
- text at x 13.3, y 52.0, w 3.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: OS #1
- text at x 36.8, y 52.0, w 3.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: OS #2
- text at x 60.2, y 52.0, w 3.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: OS #4
- text at x 83.7, y 52.0, w 3.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: OS #3
- text at x 27.7, y 82.9, w 15.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: ORIN VEHICLE COMPUTER
- text at x 59.9, y 75.3, w 15.5, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Centralized & Software Defined
- text at x 59.9, y 79.6, w 19.0, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Tightly Integrated with AV Applications
- text at x 59.9, y 84.0, w 16.2, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: Containerized & Easy to Upgrade
- text at x 59.9, y 88.3, w 17.9, h 2.0 [DINPro-Regular; font size 1.98; #FFFFFF]: SOTA Security and Functional Safety

### Slide 83

_Long standard legal text on this slide is summarised, not transcribed; its exact words are in the measured list below._

**Text**

ANNOUNCING
HYPERION 8 AV PLATFORM
State-of-the-Art Advances for
Data Collection, Development and Testing
2x Orin AV Computer
1x Orin IX Computer
4x Orin + 4x MLNX 3D GT Data Recorder
Sensor Suite: 8 Cameras (8MP), 4 Fisheyes (3MP),
3 In-Cabin, 9 Radar, 2 Lidar
Source Access to AV & IX Software Repository
OTA Ready

**Layout**

A single left-aligned text column sits in the left third of the slide, starting at about 6.7% from the left edge, with the kicker ANNOUNCING at about 27.8% from the top, the title below it, then the subtitle and the spec list running down to about 72% of the height. The right two-thirds carry a large rendered car that runs diagonally from upper left to lower right, extending to the right edge. There is no footer, no page number and no logo on the slide.

**Visuals**

One photorealistic 3D rendering of a dark translucent sedan-style autonomous test vehicle, seen from a high three-quarter rear-left angle, with the car body fading into the black background. Its roof carries a large light-grey aerodynamic sensor pod with a chrome lidar dome on top. Six or more NVIDIA-green compute modules sit in a cluster above the front-left wheel area, with a few grey-black camera and radar housings mounted at the corners, along the sides and at the rear. Thin orange wiring harnesses run along the body and connect the modules and sensors. Both wheels are dark with blue-lit rims. Lighting is a soft key light from above and a faint cool rim light; dominant colours are near-black, dark navy, NVIDIA green, silver-grey and orange. The render is full-bleed behind the text, not cropped at the car's main outline, and has no overlay or tint beyond the dark vignette.

**Design**

Background: Near-black #0A0A0A with a dark photographic texture, behind a full-bleed rendered car image. Near-black background with a subtle dark grey texture. Title and all body text are white #FFFFFF. The kicker ANNOUNCING is bold, white #FFFFFF. Accent colour is NVIDIA green #76B900, used only on the compute modules in the render. Typeface is a DIN-style geometric sans-serif: DIN Pro Regular for the title, subtitle and body, DIN Pro Bold for the kicker. Title size is about 4.1% of slide height, subtitle and body about 2.2 to 2.7%. Line and shape styles: no rules or boxes on the slide. Corner radii and gradients: none on the text. The car image has a soft dark shadow under it.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#0A0A0A]: Full-slide dark background texture, near-black with faint grey noise (Full-bleed, no crop, sits at the back under all other elements.)
- illustration at x 36, y 16, w 62, h 72 [#0B1424]: 3D rendering of a dark translucent autonomous test car with roof sensor pod, lidar dome, six green compute modules, camera and radar housings, orange wiring harness and two wheels (Full-bleed to the right and bottom of the slide, car outline fades into the black background with a soft shadow beneath. Roof pod is silver #C8CCD0, compute modules NVIDIA green #76B900, wiring orange #E07B1F, body dark navy #0B1424, wheels dark with blue rim light. No overlay or tint.)
- subtitle at x 6.7, y 27.8, w 10.6, h 3 [DIN Pro Bold, sans-serif, bold weight, all capitals, slight letter-spacing; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING (Single line, sits directly above the title with a small gap.)
- title at x 6.7, y 31, w 28.1, h 4.1 [DIN Pro Regular, sans-serif, regular weight, all capitals, no letter-spacing; font size 4.07% of slide height; #FFFFFF; left aligned]: HYPERION 8 AV PLATFORM (Single line, line spacing about 1.0.)
- subtitle at x 6.7, y 35.7, w 28.3, h 5.6 [DIN Pro Regular, sans-serif, regular weight, mixed case, no letter-spacing; font size 2.72% of slide height; #FFFFFF; left aligned]: State-of-the-Art Advances for / Data Collection, Development and Testing (Two lines, line spacing about 1.1 of the font size, line 2 starts at y 38.6.)
- body at x 6.7, y 44.2, w 28.3, h 28.3 [DIN Pro Regular, sans-serif, regular weight, mixed case, no letter-spacing; font size 2.22% of slide height; #FFFFFF; left aligned]: 2x Orin AV Computer / 1x Orin IX Computer / 4x Orin + 4x MLNX 3D GT Data Recorder / Sensor Suite: 8 Cameras (8MP), 4 Fisheyes (3MP), / 3 In-Cabin, 9 Radar, 2 Lidar / Source Access to AV & IX Software Repository / OTA Ready (Unbulleted list of six paragraphs with about 4.7% of slide height between paragraph starts, each paragraph separated by blank space. Sensor Suite paragraph wraps onto a second line at 60.8. No bullet glyphs.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3272 by 1841 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 6.7, y 31.0, w 28.1, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: HYPERION 8 AV PLATFORM
- text at x 6.7, y 27.8, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 35.7, w 20.5, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: State-of-the-Art Advances for
- text at x 6.7, y 38.6, w 28.3, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Data Collection, Development and Testing
- text at x 6.7, y 44.2, w 11.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 2x Orin AV Computer
- text at x 6.7, y 49.0, w 11.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 1x Orin IX Computer
- text at x 6.7, y 53.7, w 22.1, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 4x Orin + 4x MLNX 3D GT Data Recorder
- text at x 6.7, y 58.4, w 27.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Sensor Suite: 8 Cameras (8MP), 4 Fisheyes (3MP),
- text at x 6.7, y 60.8, w 15.2, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 3 In-Cabin, 9 Radar, 2 Lidar
- text at x 6.7, y 65.6, w 25.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Source Access to AV & IX Software Repository
- text at x 6.7, y 70.3, w 6.0, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: OTA Ready

### Slide 84

**Text**

TOPS IS THE NEW / HORSEPOWER
Atlan
1000
800
600
400
TOPS
Orin
200
Parker
Xavier
0
2018
2020
2022
2024
1 TOPS / 7 SPECint
30 TOPS / 17 SPECint
254 TOPS / 25 SPECint
1000 TOPS / >100 SPECint
SPECrate2017_int

**Layout**

Single-slide chart layout on a full-bleed dark background. The title sits at the left, vertically centred around 46% to 54% of slide height, left edge at 6.7% of width, with the chart occupying the right two-thirds from about 36% to 97% of width. The y-axis value labels are right-aligned in a column at about 38% to 41% of width, the TOPS axis title is rotated 90 degrees at about 36% of width, and the x-axis year labels sit on a single baseline at about 80.6% of height. The footer source line sits bottom-left at 3.9% of width and 94.4% of height. There is no slide number.

**Visuals**

Line chart with four data points, one per product generation, with each point labelled by a board photograph and product name above it. Y-axis: title 'TOPS', labelled ticks 0, 200, 400, 600, 800, 1000, linear scale, range 0 to about 1100 (top of axis not drawn). X-axis: years 2018, 2020, 2022, 2024, categorical, no axis title. Series 'TOPS' (single green line, #76B900, about 2.5 px wide at slide scale) with points: Parker 2018 about 1 TOPS (plotted near 0), Xavier 2020 about 30 TOPS (plotted near 0), Orin 2022 254 TOPS (plotted at about 250), Atlan 2024 1000 TOPS (plotted at about 1000). Plotted values for 2018 and 2020 are not printed as numbers on the chart beyond the caption text, so the plotted height of about 30 TOPS and about 1 TOPS is estimated. Each data point is a filled green circle about 1 percent of slide width in diameter, colour #76B900. Horizontal baseline x-axis is a thin light grey line (#BFBFBF, about 1 px) from about 42.2% to 96.5% of width at about 77.5% of height. Product photographs: four small dark circuit-board modules (Jetson-style boards with a silver square heatsink chip at upper right, blue and white connectors along the lower edge, black power jack at lower left), each about 5.1% by 7.8% of slide, boxed with no border, placed above their data points. No legend. No highlighted points beyond the green markers.

**Design**

Background: Full-bleed dark photographic texture: black #000000 at top grading to dark grey #2B2B2B at bottom, over a white #FFFFFF base fill that the image covers. Dark cinematic look: near-black top fading to dark grey at bottom with a faint textured concrete-like sheen. Title text is white bold uppercase DIN-style sans-serif (DINPro-Bold), roughly 4.1 percent of slide height per line, tight leading. Chart labels and body text are white DIN-style regular sans-serif (DINPro-Regular), about 2.7 percent of slide height for ticks and years, about 1.9 percent for captions. Accent colour is NVIDIA-style green #76B900 used for the line and markers. Footer text is grey #9A9A9A, about 1.1 percent of slide height. No shapes, no rounded corners, no shadows on text; the line and markers are flat.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide base fill, flat white (Covered entirely by the background photograph; no visible effect.)
- photo at x 0, y 0, w 100, h 100 [#1A1A1A]: Full-bleed dark textured background image, black at top fading to dark grey at bottom (3840 by 2160 pixels, full-bleed, no crop shape, no overlay, no rotation.)
- line at x 42.2, y 77.4, w 54.3, h 0.2 [#BFBFBF]: Chart x-axis baseline (Stroke about 1 px, light grey, flat, no arrowheads.)
- line at x 45.7, y 38.3, w 46.4, h 38.1 [#76B900]: Chart data line connecting Parker, Xavier, Orin and Atlan points (Straight polyline segments, about 2.5 px stroke, round joins, green #76B900, no fill, no shadow.)
- shape at x 45.2, y 75.9, w 1, h 1.8 [#76B900]: Data marker for 2018 Parker point (Filled circle about 1 percent of slide width, no outline.)
- shape at x 60.5, y 75.5, w 1, h 1.8 [#76B900]: Data marker for 2020 Xavier point (Filled circle, no outline.)
- shape at x 76, y 67.9, w 1, h 1.8 [#76B900]: Data marker for 2022 Orin point (Filled circle, no outline.)
- shape at x 91.5, y 37.4, w 1, h 1.8 [#76B900]: Data marker for 2024 Atlan point (Filled circle, no outline.)
- illustration at x 43.2, y 64.9, w 5.1, h 7.8 [#1E1E1E]: Parker Jetson-style module photograph (121 by 104 pixels. Dark green-black circuit board viewed at a slight angle, silver square heatsink chip at upper right, blue and white pin connectors along the lower edge, black power jack at lower left, boxed with no border, no overlay.)
- illustration at x 58.5, y 64.4, w 5.1, h 7.8 [#1E1E1E]: Xavier Jetson-style module photograph (121 by 104 pixels. Same board design as Parker, dark circuit board with silver square chip at upper right, blue and white connectors along lower edge, black power jack lower left, no border.)
- illustration at x 72.9, y 56.7, w 5.1, h 7.8 [#1E1E1E]: Orin Jetson-style module photograph (121 by 104 pixels. Same board design, dark circuit board with silver square chip at upper right, blue and white connectors along lower edge, black power jack lower left, no border.)
- illustration at x 89.6, y 26.6, w 5.1, h 7.8 [#1E1E1E]: Atlan Jetson-style module photograph (121 by 104 pixels. Same board design, dark circuit board with silver square chip at upper right, blue and white connectors along lower edge, black power jack lower left, no border.)
- title at x 6.7, y 45.9, w 18.5, h 8.5 [DINPro-Bold, uppercase, tight leading; font size 4.07% of slide height; #FFFFFF; left aligned]: TOPS IS THE NEW / HORSEPOWER
- body at x 43.9, y 61.6, w 3.8, h 2.2 [DINPro-Regular, regular weight; font size 2.22% of slide height; #FFFFFF; center aligned]: Parker
- body at x 59.4, y 61.1, w 3.4, h 2.2 [DINPro-Regular, regular weight; font size 2.22% of slide height; #FFFFFF; center aligned]: Xavier
- body at x 74.3, y 53.5, w 2.4, h 2.2 [DINPro-Regular, regular weight; font size 2.22% of slide height; #FFFFFF; center aligned]: Orin
- body at x 90.6, y 23.3, w 2.9, h 2.2 [DINPro-Regular, regular weight; font size 2.22% of slide height; #FFFFFF; center aligned]: Atlan
- caption at x 36.3, y 54.6, w 1.4, h 5.9 [DINPro-Regular, regular weight, rotated 90 degrees; font size 2.47% of slide height; #FFFFFF; center aligned]: TOPS (Y-axis title, reads bottom to top.)
- body at x 37.9, y 35.7, w 3.2, h 2.7 [DINPro-Regular, regular weight; font size 2.72% of slide height; #FFFFFF; right aligned]: 1000
- body at x 38.7, y 43.8, w 2.4, h 2.7 [DINPro-Regular, regular weight; font size 2.72% of slide height; #FFFFFF; right aligned]: 800
- body at x 38.7, y 51.9, w 2.4, h 2.7 [DINPro-Regular, regular weight; font size 2.72% of slide height; #FFFFFF; right aligned]: 600
- body at x 38.7, y 60.1, w 2.4, h 2.7 [DINPro-Regular, regular weight; font size 2.72% of slide height; #FFFFFF; right aligned]: 400
- body at x 38.7, y 68.2, w 2.4, h 2.7 [DINPro-Regular, regular weight; font size 2.72% of slide height; #FFFFFF; right aligned]: 200
- body at x 40.3, y 76.4, w 0.8, h 2.7 [DINPro-Regular, regular weight; font size 2.72% of slide height; #FFFFFF; right aligned]: 0
- body at x 44.3, y 80.6, w 2.9, h 2.5 [DINPro-Regular, regular weight; font size 2.47% of slide height; #FFFFFF; center aligned]: 2018
- body at x 59.6, y 80.6, w 2.9, h 2.5 [DINPro-Regular, regular weight; font size 2.47% of slide height; #FFFFFF; center aligned]: 2020
- body at x 75.2, y 80.6, w 2.9, h 2.5 [DINPro-Regular, regular weight; font size 2.47% of slide height; #FFFFFF; center aligned]: 2022
- body at x 90.7, y 80.6, w 2.9, h 2.5 [DINPro-Regular, regular weight; font size 2.47% of slide height; #FFFFFF; center aligned]: 2024
- caption at x 43.5, y 84.3, w 4.6, h 4.1 [DINPro-Regular, regular weight; font size 1.85% of slide height; #FFFFFF; center aligned]: 1 TOPS / 7 SPECint
- caption at x 58.5, y 84.3, w 5.1, h 4.1 [DINPro-Regular, regular weight; font size 1.85% of slide height; #FFFFFF; center aligned]: 30 TOPS / 17 SPECint
- caption at x 74.1, y 84.3, w 5.1, h 4.1 [DINPro-Regular, regular weight; font size 1.85% of slide height; #FFFFFF; center aligned]: 254 TOPS / 25 SPECint
- caption at x 89, y 84.3, w 6.2, h 4.1 [DINPro-Regular, regular weight; font size 1.85% of slide height; #FFFFFF; center aligned]: 1000 TOPS / >100 SPECint
- footer at x 3.9, y 94.4, w 5, h 1.1 [DINPro-Regular, regular weight; font size 1.11% of slide height; #9A9A9A; left aligned]: SPECrate2017_int

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 43.2, y 64.9, w 5.1, h 7.8: 121 by 104 pixels
- image at x 58.5, y 64.4, w 5.1, h 7.8: 121 by 104 pixels
- image at x 72.9, y 56.7, w 5.1, h 7.8: 121 by 104 pixels
- image at x 89.6, y 26.6, w 5.1, h 7.8: 121 by 104 pixels
- text at x 90.6, y 23.3, w 2.9, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Atlan
- text at x 6.7, y 45.9, w 18.5, h 8.5 [DINPro-Bold; font size 4.07; #FFFFFF]: TOPS IS THE NEWHORSEPOWER
- text at x 37.9, y 35.7, w 3.2, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 1000
- text at x 38.7, y 43.8, w 2.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 800
- text at x 38.7, y 51.9, w 2.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 600
- text at x 38.7, y 60.1, w 2.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 400
- text at x 36.3, y 54.6, w 1.4, h 5.9 [DINPro-Regular; font size 2.47; #FFFFFF]: TOPS
- text at x 74.3, y 53.5, w 2.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Orin
- text at x 38.7, y 68.2, w 2.4, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 200
- text at x 43.9, y 61.6, w 3.8, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Parker
- text at x 59.4, y 61.1, w 3.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Xavier
- text at x 40.3, y 76.4, w 0.8, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: 0
- text at x 44.3, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2018
- text at x 59.6, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2020
- text at x 75.2, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2022
- text at x 90.7, y 80.6, w 2.9, h 2.5 [DINPro-Regular; font size 2.47; #FFFFFF]: 2024
- text at x 44.1, y 84.3, w 3.3, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 1 TOPS
- text at x 59.1, y 84.3, w 3.8, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 30 TOPS
- text at x 74.4, y 84.3, w 4.4, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 254 TOPS
- text at x 89.7, y 84.3, w 4.9, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 1000 TOPS
- text at x 43.5, y 86.5, w 4.6, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 7 SPECint
- text at x 58.5, y 86.5, w 5.1, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 17 SPECint
- text at x 74.1, y 86.5, w 5.1, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: 25 SPECint
- text at x 89.0, y 86.5, w 6.2, h 1.9 [DINPro-Regular; font size 1.85; #FFFFFF]: >100SPECint
- text at x 3.9, y 94.4, w 5.0, h 1.1 [DINPro-Regular; font size 1.11; #9A9A9A]: SPECrate2017_int

### Slide 85

**Text**

ANNOUNCING
NVIDIA DRIVE ATLAN
The Next Level – Same Programmable
Architecture
Fusing Next Generation AI and BlueField
Industry's First 1,000 TOPS SoC
400 Gbps Networking with Secure Gateway
ASIL-D Safety Island

**Layout**

Single-slide product announcement with a left-aligned text block in the left third and a large chip render in the right half. The text block is vertically centred around the middle of the slide, starting at about 33% from the top and ending near 66%. The left margin is about 6.7% of slide width. There is no title placeholder, footer, logo or slide number visible.

**Visuals**

One 3D render of a chip package tilted in perspective, sitting on a dark reflective floor, occupying the right half of the slide from about x 51% to 87% and y 28% to 81%. It is not cropped and has no box or frame. The die is divided into labelled translucent blocks, back to front: HIGH SPEED IO strip along the top edge; ACCELERATORS block with SECURITY ENGINE at its top-right corner; FUNCTIONAL SAFETY ISLAND block at the upper left; BLUEFIELD block across the upper right; GRACE-NEXT CPU block at the lower left; MEMORY block in the centre; AMPERE-NEXT GPU block at the lower right; MEMORY IO strip along the bottom edge. Each block is a semi-transparent glass-like layer overlaid on a metallic circuit die, with a pastel tint: green, pink, lilac, blue and orange. The edge of the package is brushed silver-grey. Lighting is a soft top-down spotlight that falls off into black; the floor shows a faint grey reflection of the chip. No photographs of people, no logos and no icons appear on the slide.

**Design**

Background: Near-black #000000 at the top fading to dark charcoal #2A2A2A on the floor, with a studio photograph of the chip behind the text and render. Black background fading to dark charcoal toward the bottom, with a subtle grey floor surface. Title and body text are white #FFFFFF. The headline 'NVIDIA DRIVE ATLAN' is a light sans-serif in DIN Pro Regular, all caps, at about 4.1% of slide height. 'ANNOUNCING' is DIN Pro Bold, all caps, at about 3.0% of slide height. The subtitle is DIN Pro Regular at about 2.7% of slide height. Body bullets are DIN Pro Regular at about 2.2% of slide height, in white. Line and shape styles: no borders or rules. The chip render uses translucent overlay blocks with soft edges and no visible corner radius. No shadows or gradient overlays apart from the background falloff.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide studio background image, black with a soft dark grey floor gradient; covers the slide (Dark studio backdrop, no visible edges, behind all other elements)
- illustration at x 51, y 28, w 37, h 52 [#8FA7A0]: 3D render of the NVIDIA DRIVE ATLAN chip package with translucent labelled blocks: HIGH SPEED IO, ACCELERATORS, SECURITY ENGINE, FUNCTIONAL SAFETY ISLAND, BLUEFIELD, GRACE-NEXT CPU, MEMORY, AMPERE-NEXT GPU, MEMORY IO (Tilted perspective render, not cropped, no box; translucent pastel overlays in green, pink, lilac, blue and orange over a silver-grey metallic die edge; soft reflection on the floor below; overlaps the dark background only)
- title at x 6.7, y 33.4, w 10.6, h 3 [DIN Pro, Bold, all caps; font size 2.96% of slide height; #FFFFFF; left aligned]: ANNOUNCING (Sans-serif, letter-spacing normal)
- title at x 6.7, y 36.7, w 21.7, h 4.1 [DIN Pro, Regular, all caps; font size 4.07% of slide height; #FFFFFF; left aligned]: NVIDIA DRIVE ATLAN (Sans-serif, letter-spacing slightly open)
- subtitle at x 6.7, y 41.4, w 26.5, h 5.4 [DIN Pro, Regular; font size 2.72% of slide height; #FFFFFF; left aligned]: The Next Level – Same Programmable / Architecture (Two lines, line spacing about 1.0 of font size)
- body at x 6.7, y 49.9, w 22.5, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Fusing Next Generation AI and BlueField (No bullet markers; paragraph gap about 2.2% of slide height)
- body at x 6.7, y 54.6, w 17.5, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: Industry's First 1,000 TOPS SoC (No bullet markers)
- body at x 6.7, y 59.4, w 23.7, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: 400 Gbps Networking with Secure Gateway (No bullet markers)
- body at x 6.7, y 64.1, w 11.4, h 2.2 [DIN Pro, Regular; font size 2.22% of slide height; #FFFFFF; left aligned]: ASIL-D Safety Island (No bullet markers)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 4320 by 2430 pixels (covers the slide)
- text at x 6.7, y 36.7, w 21.7, h 4.1 [DINPro-Regular; font size 4.07; #FFFFFF]: NVIDIA DRIVE ATLAN
- text at x 6.7, y 33.4, w 10.6, h 3.0 [DINPro-Bold; font size 2.96; #FFFFFF]: ANNOUNCING
- text at x 6.7, y 41.4, w 26.5, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: The Next Level – Same Programmable
- text at x 6.7, y 44.2, w 8.5, h 2.7 [DINPro-Regular; font size 2.72; #FFFFFF]: Architecture
- text at x 6.7, y 49.9, w 22.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Fusing Next Generation AI and BlueField
- text at x 6.7, y 54.6, w 17.5, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: Industry's First 1,000 TOPS SoC
- text at x 6.7, y 59.4, w 23.7, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: 400 Gbps Networking with Secure Gateway
- text at x 6.7, y 64.1, w 11.4, h 2.2 [DINPro-Regular; font size 2.22; #FFFFFF]: ASIL-D Safety Island

### Slide 86

**Text**

A NEW BREED OF TECHNOLOGY COMPANIES
NIO
R Auto
XPENG
Li Auto
IM 智己汽车
CANOO
Faraday Future
VINFAST

**Layout**

Eight equal photo tiles in a 4-column by 2-row grid spanning the slide width, with a centred uppercase title in the top band above the grid. Tiles are about 21.7% wide and 29.1% tall, with left edges at 3.9, 27.4, 50.9 and 74.4 percent and top edges at 21.8 and 54.0 percent, leaving roughly 4% gutters. Each tile's brand logo sits centred in the upper part of its photo. No footer, page number or source line.

**Visuals**

Eight boxed car photographs, each a studio or street product shot of a vehicle, cropped to a landscape rectangle and not full-bleed. Row 1: (1) NIO: purple-grey SUV three-quarter front view, ES8 plate visible, on a light grey-white studio sweep. (2) R Auto: grey-blue concept sedan three-quarter front view on a grey pavement under an overcast sky. (3) XPENG: silver-grey P7 sedan three-quarter front view in front of a stone monument and river with trees and skyline behind, plate reads P7. (4) Li Auto: dark grey SUV three-quarter front view in front of a stone colonnade and steps. Row 2: (5) IM: white-silver crossover three-quarter front view against a pale grey wall. (6) CANOO: white-and-black van-style vehicle front three-quarter view on a white studio backdrop. (7) Faraday Future: silver-grey electric SUV three-quarter front view on a rocky dark hillside at dusk. (8) VinFast: matte black President SUV front three-quarter view on a black backdrop with bronze accents and a President plate. Lighting is soft studio light on the cars, with darker environmental lighting in tiles 3, 7 and 8. Dominant colours across the photos are grey, silver, white and black with some bronze. Logos overlaid on tiles as listed in elements; each logo is white.

**Design**

Background: Black #000000 studio backdrop fading to dark charcoal #1A1A1A on a reflective floor at the bottom. Pure black background with a dark charcoal reflective studio floor at the bottom. Title in white bold uppercase DIN Pro-style humanist sans-serif, about 4.1% of slide height, with slight tracking. Tile logos and the R Auto wordmark in white regular sans-serif. Tile edges have a thin bronze-gold hairline border, about 0.1% of slide height, with square corners and no shadow. Accent colour is bronze gold #8C6A3F. Body text colour #FFFFFF; title colour #FFFFFF.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide studio backdrop: black background with dark reflective floor at the bottom (Covers the whole slide, not cropped; no overlay visible beyond the floor reflection.)
- photo at x 3.9, y 21.8, w 21.7, h 29.1 [#7A7A8A]: NIO ES8 SUV photograph, tile 1 (Boxed, square corners, thin bronze hairline border.)
- photo at x 27.4, y 21.8, w 21.7, h 29.1 [#8E9AA6]: R Auto concept sedan photograph, tile 2 (Boxed, square corners, thin bronze hairline border.)
- photo at x 50.9, y 21.8, w 21.7, h 29.1 [#A0A0A0]: XPENG P7 sedan photograph, tile 3 (Boxed, square corners, thin bronze hairline border.)
- photo at x 74.4, y 21.8, w 21.7, h 29.1 [#5E6266]: Li Auto SUV photograph, tile 4 (Boxed, square corners, thin bronze hairline border.)
- photo at x 3.9, y 54, w 21.7, h 29.1 [#C8CCD2]: IM white crossover photograph, tile 5 (Boxed, square corners, thin bronze hairline border.)
- photo at x 27.4, y 54, w 21.8, h 29.1 [#E6E6E6]: CANOO white van photograph, tile 6 (Boxed, square corners, thin bronze hairline border.)
- photo at x 50.9, y 54, w 21.7, h 29.1 [#4A4E55]: Faraday Future SUV photograph, tile 7 (Boxed, square corners, thin bronze hairline border.)
- photo at x 74.3, y 54.3, w 21.8, h 28.8 [#1A1A1A]: VinFast President SUV photograph, tile 8 (Boxed, square corners, thin bronze hairline border.)
- logo at x 9.9, y 22.3, w 9.7, h 6.5 [#FFFFFF]: NIO logo (white emblem with NIO wordmark) (Overlaid on tile 1, centred, no shadow.)
- logo at x 32.4, y 22.8, w 3.3, h 5.8 [#FFFFFF]: R Auto logo mark (white stylised R) (Overlaid on tile 2 left of the R Auto text.)
- title at x 26.8, y 7.9, w 46.3, h 4.1 [DIN Pro, Bold, uppercase, slight letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: A NEW BREED OF TECHNOLOGY COMPANIES
- logo at x 55.8, y 23.4, w 12.9, h 5.3 [#FFFFFF]: XPENG wordmark (X mark with spaced letters P E N G) (Overlaid on tile 3 top centre.)
- logo at x 78.8, y 23, w 12.9, h 5.3 [#FFFFFF]: Li Auto logo (white stacked-bar mark with Li Auto wordmark) (Overlaid on tile 4 top centre.)
- body at x 36.9, y 24, w 6.1, h 3.7 [DIN Pro, Regular; font size 3.7% of slide height; #FFFFFF; left aligned]: R Auto (Overlaid on tile 2, to the right of the R Auto logo mark.)
- logo at x 10.2, y 55.5, w 9.1, h 3.9 [#FFFFFF]: IM logo (white IM mark with 智己汽车 Chinese wordmark) (Overlaid on tile 5 top centre.)
- logo at x 32.1, y 55.8, w 12.4, h 5.7 [#FFFFFF]: CANOO wordmark (widely spaced letters C A N O O) (Overlaid on tile 6 top centre.)
- logo at x 54.5, y 56, w 13.9, h 5.2 [#FFFFFF]: Faraday Future logo (white diamond-lattice mark with Faraday Future wordmark) (Overlaid on tile 7 top centre.)
- logo at x 83.4, y 54.8, w 3.6, h 5.9 [#FFFFFF]: VinFast emblem (white stylised V) (Overlaid on tile 8 top centre.)
- logo at x 83.2, y 59.8, w 4, h 1 [#FFFFFF]: VINFAST wordmark (widely spaced letters) (Small white text beneath the VinFast emblem on tile 8.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 50.8, y 21.8, w 21.8, h 29.1: 868 by 651 pixels
- image at x 27.4, y 54.0, w 21.8, h 29.1: 1228 by 935 pixels
- image at x 3.9, y 54.0, w 21.7, h 29.1: 1177 by 884 pixels
- image at x 50.9, y 54.0, w 21.7, h 29.1: 996 by 756 pixels
- image at x 3.9, y 21.8, w 21.7, h 29.0: 1374 by 1040 pixels
- image at x 74.4, y 21.8, w 21.7, h 29.0: 1061 by 785 pixels
- image at x 27.4, y 21.8, w 21.7, h 29.0: 1309 by 983 pixels
- image at x 74.3, y 54.3, w 21.8, h 28.8: 1306 by 971 pixels
- image at x 74.4, y 54.0, w 21.8, h 8.1: 627 by 132 pixels
- image at x 74.4, y 54.0, w 21.8, h 8.1: 627 by 132 pixels
- image at x 50.9, y 54.0, w 21.8, h 8.1: 627 by 131 pixels
- image at x 50.9, y 54.0, w 21.8, h 8.1: 627 by 131 pixels
- image at x 3.9, y 21.7, w 21.7, h 8.1: 626 by 131 pixels
- image at x 3.9, y 21.7, w 21.7, h 8.1: 626 by 131 pixels
- image at x 27.4, y 21.7, w 21.7, h 8.1: 626 by 131 pixels
- image at x 27.4, y 21.7, w 21.7, h 8.1: 626 by 131 pixels
- image at x 50.9, y 21.7, w 21.7, h 8.1: 626 by 131 pixels
- image at x 50.9, y 21.7, w 21.7, h 8.1: 626 by 131 pixels
- image at x 74.4, y 21.8, w 21.7, h 8.1: 626 by 131 pixels
- image at x 74.4, y 21.8, w 21.7, h 8.1: 626 by 131 pixels
- image at x 3.9, y 54.0, w 21.7, h 8.1: 626 by 131 pixels
- image at x 3.9, y 54.0, w 21.7, h 8.1: 626 by 131 pixels
- image at x 27.4, y 54.0, w 21.8, h 8.0: 627 by 130 pixels
- image at x 27.4, y 54.0, w 21.8, h 8.0: 627 by 130 pixels
- image at x 54.5, y 56.0, w 13.9, h 5.2: 1200 by 245 pixels
- image at x 32.1, y 55.8, w 12.4, h 5.7: 797 by 208 pixels
- image at x 78.8, y 23.0, w 12.9, h 5.3: 952 by 220 pixels
- image at x 55.8, y 23.4, w 12.9, h 5.3: 530 by 122 pixels
- image at x 9.9, y 22.3, w 9.7, h 6.5: 1200 by 447 pixels
- image at x 10.2, y 55.5, w 9.1, h 3.9: 549 by 132 pixels
- image at x 83.4, y 54.8, w 3.6, h 5.9: 219 by 200 pixels
- image at x 32.4, y 22.8, w 3.3, h 5.8: 196 by 195 pixels
- text at x 26.8, y 7.9, w 46.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: A NEW BREED OF TECHNOLOGY COMPANIES
- text at x 36.9, y 24.0, w 6.1, h 3.7 [DINPro-Regular; font size 3.70; #FFFFFF]: R Auto

### Slide 87

**Text**

THE WORLD’S BIG BRANDS HAVE GIANT OPPORTUNITIES / Mercedes-Benz / VOLVO / HYUNDAI / [Audi rings logo, no text]

**Layout**

A single title is centred horizontally near the top of the slide, with a wide empty band beneath it. Four equal photo boxes sit in one horizontal row across the middle-lower part of the slide, left-aligned to a common top edge at about 38.7% of slide height, with equal gutters of about 1.7% of slide width and roughly equal outer margins of about 3.9% on the left and right. No footer, footnote, or slide number is visible.

**Visuals**

Four boxed car photographs in a row, each with a logo overlaid at its top centre. Box 1 (left): a silver-grey concept sedan in three-quarter front view, facing right, with a large multi-spoke silver alloy wheel, a Mercedes-Benz star grille badge, and a white Mercedes-Benz wordmark with star emblem above it; background is a grey concrete building with dark-framed teal windows; lit by soft daylight; mostly grey and silver tones with a warm copper accent under the bumper. Box 2: a dark navy-blue compact SUV in three-quarter front view facing right, with a five-spoke-style grey alloy wheel and a white VOLVO wordmark letterspaced across the top; background is a dark navy wall with vertical panel lines and a pale grey floor; soft studio lighting; dominant colours navy and slate blue. Box 3: a beige-silver crossover SUV in three-quarter front view facing right, with a patterned alloy wheel, white Hyundai emblem and HYUNDAI wordmark above; background is a gradient from black at top to pale sandy brown and a distant mountain ridge at the bottom right; warm dusk-style light; dominant colours beige, taupe and charcoal. Box 4 (right): a bright blue electric SUV in three-quarter front view facing right, with a chrome-spoke alloy wheel, a black grille with chrome slats, a white Audi four-rings logo at top centre; background is a grey concrete wall with a white floor patch; hard sunlit lighting; dominant colours metallic blue and grey. All four photos are rectangular, unrounded, shown whole (not cropped beyond their frames), with a thin pale grey or light gold hairline border and no overlay or tint on the photos themselves. Full-slide background is a dark studio photograph or gradient, black at top fading to dark charcoal near the bottom, with a faint floor reflection.

**Design**

Background: Black-to-charcoal gradient (#000000 at top to #2A2A2A at bottom) with a faint studio floor photograph behind everything. Black background (#000000) at top grading to charcoal (#2A2A2A) toward the bottom, with a soft dark floor shadow. Title in white (#FFFFFF) DIN Pro Bold, all capitals, sans-serif, about 4.1% of slide height, tracking slightly open. No separate body text. Photo boxes use sharp corners, a thin hairline border in pale grey (#B8B8B8) or muted gold (#9C8A5E), no shadow, no gradient on the frames. Logos are white (#FFFFFF). Car colours: silver #C9CCD0, navy #2E4A63, beige #B9AD98, blue #1F6FB2.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide dark studio background photograph, black at top fading to charcoal floor (Full bleed, no crop, dark vignette, faint floor reflection; back-most layer)
- title at x 20.3, y 7.9, w 59.4, h 4.1 [DINPro-Bold, sans-serif, bold, all capitals; font size 4.07% of slide height; #FFFFFF; center aligned]: THE WORLD’S BIG BRANDS HAVE GIANT OPPORTUNITIES (Single line, letter-spacing slightly open)
- photo at x 3.9, y 38.7, w 21.8, h 29.2 [#C9CCD0]: Mercedes-Benz concept sedan photograph in three-quarter front view on grey concrete building background (Sharp rectangular box, thin pale grey hairline border, no shadow, shown whole)
- logo at x 9.4, y 40.2, w 10.1, h 4.7 [Mercedes-Benz serif wordmark, regular weight; #FFFFFF; center aligned]: Mercedes-Benz three-pointed star emblem with Mercedes-Benz serif wordmark, white (Overlaid on upper part of photo 1)
- photo at x 27.4, y 38.7, w 21.8, h 29.2 [#2E4A63]: Volvo navy compact SUV photograph in three-quarter front view on dark navy wall (Sharp rectangular box, thin pale grey hairline border, no shadow)
- logo at x 32.5, y 44.4, w 15.5, h 3.6 [Volvo Novus-style serif-slab, bold, all capitals, wide letter-spacing; #FFFFFF; center aligned]: VOLVO wordmark, white, letterspaced capitals (Position estimated from slide, overlaid on upper part of photo 2)
- photo at x 50.8, y 38.7, w 21.8, h 29.2 [#B9AD98]: Hyundai beige crossover SUV photograph in three-quarter front view on gradient dusk background with distant mountains (Sharp rectangular box, thin pale grey hairline border, no shadow)
- logo at x 59.3, y 39.5, w 5.2, h 5.5 [Hyundai wordmark, sans-serif, regular, all capitals; #FFFFFF; center aligned]: Hyundai oval emblem above HYUNDAI wordmark, white (Overlaid on upper part of photo 3; emblem and wordmark stacked)
- photo at x 74.3, y 38.7, w 21.9, h 29.2 [#1F6FB2]: Audi blue electric SUV photograph in three-quarter front view on grey concrete wall with white floor patch (Sharp rectangular box, thin pale grey hairline border, no shadow)
- logo at x 82.8, y 40.8, w 5.3, h 3.3 [#FFFFFF; center aligned]: Audi four interlocking rings logo, white (Overlaid on upper part of photo 4)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 74.3, y 38.7, w 21.9, h 29.2: 797 by 592 pixels
- image at x 3.9, y 38.7, w 21.8, h 29.2: 536 by 400 pixels
- image at x 27.4, y 38.7, w 21.8, h 29.2: 1514 by 1139 pixels
- image at x 50.8, y 38.7, w 21.8, h 29.2: 1386 by 1044 pixels
- image at x 74.3, y 38.7, w 21.9, h 13.9: 630 by 225 pixels
- image at x 74.3, y 38.7, w 21.9, h 13.9: 630 by 225 pixels
- image at x 50.8, y 38.6, w 21.8, h 11.4: 629 by 184 pixels
- image at x 50.8, y 38.6, w 21.8, h 11.4: 629 by 184 pixels
- image at x 3.9, y 38.7, w 21.9, h 10.1: 630 by 163 pixels
- image at x 3.9, y 38.7, w 21.9, h 10.1: 630 by 163 pixels
- image at x 27.4, y 38.7, w 22.0, h 7.8: 633 by 126 pixels
- image at x 27.4, y 38.7, w 22.0, h 7.8: 633 by 126 pixels
- image at x 9.4, y 40.2, w 10.1, h 4.7: 1280 by 333 pixels
- image at x 59.3, y 39.5, w 5.2, h 5.5: 310 by 187 pixels
- image at x 82.8, y 40.8, w 5.3, h 3.3: 640 by 222 pixels
- text at x 20.3, y 7.9, w 59.4, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: THE WORLD’S BIG BRANDS HAVE GIANT OPPORTUNITIES

### Slide 88

**Text**

TRANSFORMING 10 TRILLION MILES A YEAR INTO A SERVICE / cruise / ZOOX / DiDi / oxbotica / pony.ai / autox

**Layout**

Centred title in the upper band with six equal photo tiles in a 3 by 2 grid below it, arranged in three columns and two rows with even gutters. The tiles sit on a dark reflective stage with no footer or slide number.

**Visuals**

Six photographs of autonomous vehicles in a 3 by 2 grid, each boxed with a thin dark-brown edge and with a company logo in white over the upper part of the image. Top row, left to right: a Cruise autonomous shuttle with a white and orange-trimmed body, front three-quarter view on a city street at sunset with warm orange backlight and cars behind it; a Zoox pod with a pale teal body, four wheels and tinted glass, side view on a grey pavement in front of trees and city blocks under an overcast sky; a DiDi white sedan with orange stripes and a roof sensor pod, front three-quarter view in a showroom with bright reflective floor and a white car behind. Bottom row, left to right: an Oxbotica blue Ford Mondeo-type saloon with white Oxbotica livery, front three-quarter view on a brick-lined street in daylight, UK plate 0005 OXB; a Pony.ai white Lexus RX SUV with a roof sensor pod, front three-quarter view on a tree-lined road in daylight, pony logo on the grille area; an Autox white Chrysler Pacifica-type minivan with blue side stripe and autox livery, front three-quarter view in front of a glass building with sensor pods on the roof. Logos are white: cruise wordmark, ZOOX wordmark, DiDi logo with wordmark, oxbotica logo with wordmark, pony.ai wordmark, autox logo with wordmark. Photos are rectangular, not cropped in a visible way, and not overlaid with tints except a dark gradient at the top of the Cruise and Zoox tiles.

**Design**

Background: Near-black #000000 to dark grey #1A1A1A gradient with a reflective dark floor at the bottom, behind all elements. Black to dark charcoal background with a soft reflective floor surface at the bottom. Title in bold uppercase sans-serif, white #FFFFFF, about 4 percent of slide height, with wide but normal letter-spacing. Logos are white. Tiles have thin brown-grey edges and no corner radius and no visible shadow beyond a faint dark halo. No accent colours beyond the photographs.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide background fill, white #FFFFFF in the file, covered by the black and dark grey backdrop image (Fill is fully covered by image layers.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide backdrop image, black stage with reflective dark floor (Full-bleed, rectangular, no crop, no corner radius.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide backdrop image, second layer of the black stage with reflective floor (Full-bleed, rectangular, no crop.)
- photo at x 3.9, y 21.7, w 29.6, h 29.1 [#F4F4F4]: Cruise autonomous shuttle photograph, front three-quarter view on city street at sunset (Boxed rectangle, thin dark brown edge, no corner radius, dark gradient at top edge, warm orange backlight.)
- logo at x 15.1, y 23.7, w 7.2, h 3.9 [#FFFFFF]: cruise wordmark, white lowercase (Overlaid on the top of the Cruise photograph.)
- photo at x 35.2, y 21.7, w 29.6, h 29.1 [#7FC4C4]: Zoox pod photograph, side view on grey pavement with trees and city blocks behind (Boxed rectangle, thin dark brown edge, dark gradient at top edge.)
- logo at x 45, y 22.7, w 9.9, h 7.1 [#FFFFFF]: ZOOX wordmark, white spaced capitals (Overlaid on the top of the Zoox photograph.)
- photo at x 66.5, y 21.7, w 29.6, h 29.1 [#FFFFFF]: DiDi white sedan with orange stripes, front three-quarter view in a showroom (Boxed rectangle, thin dark brown edge, no corner radius.)
- logo at x 78, y 24.3, w 6.5, h 3.8 [#FFFFFF]: DiDi logo mark with DiDi wordmark, white (Overlaid on the top of the DiDi photograph.)
- photo at x 3.9, y 54.1, w 29.6, h 29 [#1F3A6B]: Oxbotica blue Ford saloon with white Oxbotica livery, front three-quarter view on a brick street (Boxed rectangle, thin dark brown edge, no corner radius.)
- logo at x 13.7, y 56.5, w 9.9, h 4.1 [#FFFFFF]: oxbotica logo mark with wordmark, white (Overlaid on the top of the Oxbotica photograph.)
- photo at x 35.2, y 54.1, w 29.6, h 29.1 [#E8E8E8]: Pony.ai white Lexus RX SUV with roof sensor pod, front three-quarter view on a tree-lined road (Boxed rectangle, thin dark brown edge, no corner radius.)
- logo at x 46.8, y 57.1, w 6.9, h 3.9 [#FFFFFF]: pony.ai wordmark, white (Overlaid on the top of the Pony.ai photograph.)
- photo at x 66.5, y 54.1, w 29.6, h 29.1 [#F2F2F2]: Autox white minivan with blue side stripe, front three-quarter view in front of a glass building (Boxed rectangle, thin dark brown edge, no corner radius.)
- logo at x 76.6, y 56.6, w 9.3, h 4.7 [#FFFFFF]: autox logo mark with wordmark, white (Overlaid on the top of the Autox photograph.)
- title at x 18.4, y 7.9, w 63.3, h 4.1 [DINPro-Bold, bold sans-serif, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: TRANSFORMING 10 TRILLION MILES A YEAR INTO A SERVICE (Single line, normal letter-spacing.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 35.2, y 54.1, w 29.6, h 29.2: 582 by 314 pixels
- image at x 66.5, y 21.7, w 29.6, h 29.1: 1159 by 643 pixels
- image at x 66.5, y 54.1, w 29.6, h 29.1: 997 by 536 pixels
- image at x 3.9, y 21.7, w 29.6, h 29.1: 1556 by 865 pixels
- image at x 35.2, y 21.7, w 29.6, h 29.1: 2033 by 1124 pixels
- image at x 3.9, y 54.1, w 29.6, h 29.0: 1066 by 588 pixels
- image at x 3.9, y 54.1, w 29.7, h 8.7: 854 by 141 pixels
- image at x 3.9, y 54.1, w 29.7, h 8.7: 854 by 141 pixels
- image at x 66.5, y 54.1, w 29.6, h 8.7: 853 by 141 pixels
- image at x 66.5, y 54.1, w 29.6, h 8.7: 853 by 141 pixels
- image at x 3.9, y 21.7, w 29.7, h 8.6: 854 by 140 pixels
- image at x 3.9, y 21.7, w 29.7, h 8.6: 854 by 140 pixels
- image at x 35.2, y 21.7, w 29.7, h 8.6: 854 by 140 pixels
- image at x 35.2, y 21.7, w 29.7, h 8.6: 854 by 140 pixels
- image at x 66.5, y 21.7, w 29.7, h 8.6: 854 by 140 pixels
- image at x 66.5, y 21.7, w 29.7, h 8.6: 854 by 140 pixels
- image at x 35.2, y 53.9, w 29.7, h 8.3: 854 by 134 pixels
- image at x 35.2, y 53.9, w 29.7, h 8.3: 854 by 134 pixels
- image at x 45.0, y 22.7, w 9.9, h 7.1: 1124 by 450 pixels
- image at x 76.6, y 56.6, w 9.3, h 4.7: 557 by 160 pixels
- image at x 13.7, y 56.5, w 9.9, h 4.1: 451 by 106 pixels
- image at x 15.1, y 23.7, w 7.2, h 3.9: 434 by 131 pixels
- image at x 46.8, y 57.1, w 6.9, h 3.9: 202 by 64 pixels
- image at x 78.0, y 24.3, w 6.5, h 3.8: 389 by 127 pixels
- text at x 18.4, y 7.9, w 63.3, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: TRANSFORMING 10 TRILLION MILES A YEAR INTO A SERVICE

### Slide 89

**Text**

THE INTERNET OF ATOMS / VOLVO / NAVISTAR / tusimple / Plus / einride / LOCOMOTION / VOLVO AUTONOMOUS SOLUTIONS / SELF-DRIVING TRUCK / SCHENKER & EINRIDE / LOCOMOTION

**Layout**

Single-slide grid: a centred all-caps title sits near the top, above a 3-column by 2-row grid of six equal photo tiles spanning roughly 3.9% to 96% of the width, with equal gutters of about 1.7% horizontally and about 3.5% vertically. Tiles are left-aligned to the grid columns at x 3.9, 35.2 and 66.5. There is no footer, slide number or other furniture.

**Visuals**

Six photographs of autonomous or self-driving trucks, each in a rectangular landscape tile with a thin warm-grey hairline border and a faint dark shadow beneath the grid. Top-left tile: a white Volvo FH-series cab with black front bumper and sensor bar, labelled VOLVO AUTONOMOUS SOLUTIONS on the door, parked on grey gravel in front of a red-brick building with windows; daylight, overcast sky. Top-middle tile: a blue Navistar International LT-style tractor pulling a silver grain trailer on a rural road, with silos and a cornfield behind; warm sunlight. Top-right tile: a white Peterbilt tractor with a green trailer labelled tusimple and SELF-DRIVING TRUCK, on a rural road with grass and sky behind; sensor pods on mirrors. Bottom-left tile: a white Kenworth T680-style tractor on a highway at sunset with a warm orange sky and trees; Plus logo overlaid. Bottom-middle tile: a white and dark-grey einride pod-style electric cab with no conventional cab, angled panels with diagonal stripes, labelled DB SCHENKER and einride, on a forest-edged road. Bottom-right tile: a dark grey Kenworth-style tractor with a black trailer labelled LOCOMOTION in white capitals, shown in motion on a motorway with blurred background. Each photo is full-tile, not cropped to a shape, with a dark gradient fading to black at the top edge of each tile for logo legibility. Dominant colours across tiles: white, grey, blue, green and black.

**Design**

Background: Solid black #000000 with a faint dark grey #1A1A1A floor reflection at the bottom edge. Black background with a subtle dark grey floor reflection at the bottom. Title in white bold all-caps DIN-style sans-serif, about 4.1% of slide height, tracked slightly. Logos in white. Tile borders are thin warm-grey hairlines. No accent colour beyond the photographs' own colours. Corners are square and shadows are soft and dark beneath the grid.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Background fill, solid white beneath the full-bleed black image (Covered by the black background image; covers the whole slide.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-slide black background image with dark floor reflection (Full-bleed, no overlay.)
- title at x 36.5, y 7.9, w 27, h 4.1 [DIN Pro, Bold, all caps, slight letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: THE INTERNET OF ATOMS
- photo at x 3.9, y 21.7, w 29.7, h 29.2: Tile 1 (top-left): white Volvo autonomous FH-series truck in front of a red-brick building (Boxed rectangular tile, thin warm-grey hairline border, top edge darkened by gradient.)
- logo at x 12.2, y 25, w 13.1, h 1.8 [#FFFFFF]: VOLVO wordmark, widely letter-spaced white serif capitals (Overlaid on top portion of tile 1.)
- photo at x 35.2, y 21.7, w 29.6, h 29.1: Tile 2 (top-middle): blue Navistar tractor pulling grain trailer on rural road (Boxed tile, thin hairline border, top edge darkened by gradient.)
- logo at x 45.4, y 24.7, w 9.2, h 2.7 [#FFFFFF]: NAVISTAR wordmark, bold italic white capitals (Overlaid on tile 2.)
- photo at x 66.5, y 21.7, w 29.6, h 29.1: Tile 3 (top-right): white Peterbilt self-driving truck with green trailer labelled tusimple and SELF-DRIVING TRUCK (Boxed tile, thin hairline border, top edge darkened by gradient.)
- logo at x 77.2, y 22.6, w 8.1, h 7.4 [#FFFFFF]: tusimple logo: white rounded square with tu, followed by simple in white lowercase (Overlaid on tile 3.)
- photo at x 3.9, y 54, w 29.7, h 29.1: Tile 4 (bottom-left): white Kenworth-style tractor on highway at sunset (Boxed tile, thin hairline border, top edge darkened by gradient.)
- logo at x 14.5, y 56, w 8.5, h 4.5 [#FFFFFF]: Plus logo: white circular icon with three horizontal lines, followed by Plus in white bold sans-serif (Overlaid on tile 4.)
- photo at x 35.2, y 54, w 29.6, h 29.1: Tile 5 (bottom-middle): white einride pod-style electric cab with DB Schenker and einride labels on a forest road (Boxed tile, thin hairline border, top edge darkened by gradient.)
- logo at x 45.6, y 56.5, w 8.7, h 4.1 [#FFFFFF]: einride logo: white square with a black diagonal mark, followed by einride in white lowercase (Overlaid on tile 5; the square is white with a black mark.)
- photo at x 66.5, y 54, w 29.7, h 29.1: Tile 6 (bottom-right): dark Kenworth-style truck with LOCOMOTION trailer in motion on motorway (Boxed tile, thin hairline border, top edge darkened by gradient.)
- logo at x 75.7, y 57.3, w 11.1, h 2.4 [#FFFFFF]: LOCOMOTION wordmark, widely letter-spaced white capitals (Overlaid on tile 6.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 35.2, y 21.7, w 29.7, h 29.2: 805 by 445 pixels
- image at x 66.5, y 54.0, w 29.7, h 29.1: 791 by 437 pixels
- image at x 3.9, y 54.0, w 29.7, h 29.1: 2246 by 1232 pixels
- image at x 3.9, y 21.7, w 29.6, h 29.1: 2015 by 1114 pixels
- image at x 35.2, y 54.0, w 29.6, h 29.1: 808 by 447 pixels
- image at x 66.5, y 21.7, w 29.6, h 29.1: 2194 by 1212 pixels
- image at x 3.9, y 21.6, w 29.7, h 8.8: 854 by 142 pixels
- image at x 3.9, y 21.6, w 29.7, h 8.8: 854 by 142 pixels
- image at x 35.2, y 21.6, w 29.7, h 8.8: 854 by 142 pixels
- image at x 35.2, y 21.6, w 29.7, h 8.8: 854 by 142 pixels
- image at x 66.5, y 21.7, w 29.7, h 8.7: 854 by 141 pixels
- image at x 66.5, y 21.7, w 29.7, h 8.7: 854 by 141 pixels
- image at x 66.5, y 54.0, w 29.7, h 8.7: 854 by 141 pixels
- image at x 66.5, y 54.0, w 29.7, h 8.7: 854 by 141 pixels
- image at x 35.2, y 54.0, w 29.7, h 8.6: 855 by 140 pixels
- image at x 35.2, y 54.0, w 29.7, h 8.6: 855 by 140 pixels
- image at x 3.9, y 54.0, w 29.7, h 8.6: 854 by 140 pixels
- image at x 3.9, y 54.0, w 29.7, h 8.6: 854 by 140 pixels
- image at x 77.2, y 22.6, w 8.1, h 7.4: 800 by 419 pixels
- image at x 45.6, y 56.5, w 8.7, h 4.1: 522 by 139 pixels
- image at x 75.7, y 57.3, w 11.1, h 2.4: 300 by 37 pixels
- image at x 45.4, y 24.7, w 9.2, h 2.7: 1280 by 216 pixels
- text at x 36.5, y 7.9, w 27.0, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: THE INTERNET OF ATOMS

### Slide 90

**Text**

NVIDIA DRIVE DIGITAL TWIN IN OMNIVERSE

**Layout**

Three-column horizontal composition centred on the slide: a column of three small square thumbnails on the left, a large spherical image in the centre-left, a small square steering-wheel icon between the sphere and a large circular photo on the right. The title sits centred at the top, about 8% from the top edge, in one line of all-caps text. Left and right margins are about 15% and 26%; there is no footer, no slide number and no logo. The lower third of the slide is empty dark floor.

**Visuals**

Three square thumbnail images stacked vertically at the left. Top thumbnail: a navy-blue (#1E2A6B) square showing white and pink curved lane-network lines converging to the right, like a road-graph map. Middle thumbnail: a bright green (#33FF66) square showing a semantic-segmentation view of a road with a yellow sign post, a blue car, pink and purple tree and object shapes, and magenta road edges. Bottom thumbnail: a colour photograph of a suburban street intersection with a blue street sign and white road markings, overlaid with translucent cyan wireframe boxes outlining cars. Three thin gold double-headed arrows connect each thumbnail to the central sphere: the top arrow runs diagonally from the top thumbnail down-right to the sphere's upper-left edge, the middle arrow is horizontal, and the bottom arrow runs diagonally up-right from the bottom thumbnail to the sphere's lower-left edge. Centre: a large sphere with a light-grey triangulated wireframe mesh over a grayscale road scene with white trees and bushes, yellow traffic signs, poles and signal lights, cyan lane-boundary lines, magenta lane markings, a dark purple-red road surface, dashed green centre lines and a guard rail along the left. The sphere is slightly translucent and gold-edged. Between the sphere and the right circle is a square black icon, about 8% of slide width, with a thin dark-grey border, containing a light-grey window-pane grid of four panels above a grey steering-wheel symbol. A thin gold circular arc surrounds it, with gold arrowheads at the upper-right and lower-left showing circulation between the sphere and the photo. Right: a circular photograph, cropped to a circle with a thin gold rim, of an autumn rural road in overcast light: grey cloudy sky, bare and orange-yellow autumn trees on both sides, a blue German-style road sign reading Stuttgart with an arrow, a yellow Hertz sign on the right, a silver-grey car ahead, a red car further away, white lane markings, a guard rail on the right, and the dark bonnet and dashboard of the camera vehicle along the bottom edge. Lighting is soft daylight with muted colours, dominant greys, browns and orange-yellow.

**Design**

Background: Near-black #000000 at the top fading to charcoal #2B2B2B at the bottom, with faint brushed-metal texture, full-bleed. Dark cinematic slide: a near-black top area blending into a charcoal lower area with subtle brushed-metal streaks. Title in white bold DIN-style sans-serif, all caps, letter-spaced slightly. Accent colour is a muted gold (#B89A5B) used for arrows and rings. Imagery is high-contrast with cyan (#00C8E8) and yellow (#F5E200) highlights. No corner radii on the thumbnails, which have thin light-grey borders. The sphere and right photo are circles with a thin gold outline. No shadows or gradients on shapes, apart from the soft vignette of the background.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#1A1A1A]: Full-bleed dark background image: black top fading to charcoal bottom with faint brushed-metal texture (Full-slide background image, 3840 by 2160 px, covers the slide, no overlay)
- photo at x 0, y 0, w 100, h 100 [#1A1A1A]: Full-bleed background image layer (second copy) matching the dark gradient background (Full-slide image, 3840 by 2160 px, covers the slide, no visible content beyond the background gradient)
- title at x 27.3, y 7.9, w 45.5, h 4.1 [DINPro-Bold, sans-serif, bold, all capitals, slight letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: NVIDIA DRIVE DIGITAL TWIN IN OMNIVERSE
- photo at x 15.1, y 21.6, w 6.7, h 11.8 [#1E2A6B]: Thumbnail of navy lane-network map: white and pink curved lane lines converging to the right on a navy-blue field (Square image with thin light-grey border, sharp corners, no shadow)
- photo at x 15.1, y 41.1, w 6.7, h 11.8 [#33FF66]: Thumbnail of semantic segmentation view: green ground, blue car, yellow sign post, pink and purple object shapes (Square image with thin light-grey border, sharp corners, no shadow)
- photo at x 15.1, y 60.5, w 6.7, h 11.8 [#5A4A3A]: Thumbnail photo of suburban street intersection with translucent cyan wireframe car boxes overlaid (Square image with thin light-grey border, sharp corners, no shadow)
- line at x 25, y 27.6, w 9.4, h 9.2 [#B89A5B]: Gold double-headed arrow from top thumbnail to sphere upper-left edge (Thin gold line about 1 px, arrowheads at both ends)
- line at x 24.9, y 46.7, w 9.4, h 0.3 [#B89A5B]: Gold double-headed horizontal arrow from middle thumbnail to sphere left edge (Thin gold line about 1 px, arrowheads at both ends)
- line at x 25, y 56.7, w 9.4, h 9.5 [#B89A5B]: Gold double-headed arrow from bottom thumbnail to sphere lower-left edge (Thin gold line about 1 px, arrowheads at both ends)
- illustration at x 37.9, y 25.6, w 24.2, h 43.2 [#777777]: Spherical image: grayscale road scene with yellow signs and cyan and magenta lane lines behind a light-grey triangulated wireframe mesh (Circular crop, thin gold outline, slightly translucent wireframe mesh overlaid, not boxed)
- shape at x 64, y 39.6, w 8, h 14.4 [#111111]: Square black icon with light-grey four-pane window grid above a grey steering wheel (Sharp-cornered square with thin dark-grey border, grey pictogram in #BBBBBB)
- shape at x 63.2, y 38.8, w 9.7, h 16 [#B89A5B]: Thin gold circular arc with arrowheads at upper-right and lower-left surrounding the steering icon (Thin gold circular line about 1 px, arrowheads showing circulation between sphere and photo)
- photo at x 74, y 29.2, w 19.8, h 35.3 [#8A8F94]: Circular photograph of autumn rural road: overcast sky, autumn trees, blue Stuttgart sign, yellow Hertz sign, cars ahead and vehicle bonnet at bottom (Circular crop with thin gold rim, full-colour photograph, no overlay)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- text at x 27.3, y 7.9, w 45.5, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NVIDIA DRIVE DIGITAL TWIN IN OMNIVERSE

### Slide 91

**Text**

ANNOUNCING NVIDIA DRIVE SIM POWERED BY OMNIVERSE
PHYSICALLY ACCURATE SENSORS
CLOUD-NATIVE WORKFLOW
SCALABLE ARCHITECTURE
OPEN | MODULAR | EXTENSIBLE

**Layout**

Full-bleed black slide with a centred all-caps title in the top band and a single wide photographic panel below it, spanning about 92% of the width with a left and right margin of about 4%. Four tagline captions sit in a single row across the bottom inside the photo, left-aligned at four column starts, with the last one right-aligned to the panel's right inset. No footer or slide number is visible.

**Visuals**

Photograph of a dark grey Mercedes-Benz VISION EQS concept car seen from the rear three-quarter view, driving away along an autumn tree-lined road toward the viewer's left; the car is centred slightly left of middle and fills about 35% of the panel width. Red LED-style light strip runs across the rear and a blue light line runs along the upper right flank; a small Mercedes star sits on the tail and 'VISION EQS' is printed in small white letters below it. Surroundings are orange and yellow autumn trees, bare trees, a blue road sign on a grey pole at left, a grey concrete pillar at right, cobbled pavement with fallen leaves, white road markings and a low sun glowing in a pale sky. Lighting is warm low-angle sunlight with soft shadows; dominant colours are amber, orange, grey and charcoal. The photograph is a rectangular box with a thin grey edge, not cropped, and a slight dark gradient darkens its lower edge where the captions sit. Below the panel is a faint reflection of the panel on a black glossy floor.

**Design**

Background: Black #000000 with a dark grey gradient fading to #1A1A1A toward the bottom and a faint glossy floor reflection. Black background with a subtle dark grey gradient at the lower area suggesting a floor; title and captions in white DIN Pro style sans-serif. Title is bold, all caps, about 4.1% of slide height, white #FFFFFF. Captions are medium weight, all caps, about 2.0% of slide height, white #FFFFFF. The photo panel has a thin grey (#5A5A5A) border and a soft drop shadow beneath it. No corner radii, no accent colours in typography.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide background fill, solid white beneath the photographs (Covered by the photographs and black backdrop; no visible white shows.)
- shape at x 0, y 0, w 100, h 100 [#000000]: Black backdrop and floor gradient behind the panel (Gradient from #000000 at top to #1A1A1A at the bottom; faint reflection of the panel in the lower area.)
- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed rendered image of the slide's frame area (backdrop image), covering the whole slide (3840 by 2160 pixels; black and dark grey, no visible content apart from the gradient.)
- photo at x 3.9, y 21.8, w 92.2, h 61.3 [#C8862A]: Photograph of Mercedes-Benz VISION EQS concept car on an autumn road, with captions overlaid at the bottom (Rectangular box, not cropped, thin grey (#5A5A5A) edge, soft drop shadow below; 2171 by 814 pixels; the lower edge darkens slightly to hold the captions.)
- shape at x 3.9, y 67.8, w 92.2, h 15.5 [#1A1A1A]: Dark floor reflection strip of the photo panel (Faint mirrored reflection at low opacity, about 10%, lying under the lower edge of the photo panel; 2656 by 251 pixels.)
- title at x 19.2, y 7.9, w 61.6, h 4.1 [DIN Pro Bold, sans-serif, bold, all caps, no italics, normal letter-spacing; font size 4.07% of slide height; #FFFFFF; center aligned]: ANNOUNCING NVIDIA DRIVE SIM POWERED BY OMNIVERSE
- body at x 7.5, y 79.3, w 17.1, h 2 [DIN Pro Medium, sans-serif, medium weight, all caps, normal letter-spacing; font size 1.98% of slide height; #FFFFFF; left aligned]: PHYSICALLY ACCURATE SENSORS
- body at x 31.6, y 79.3, w 14, h 2 [DIN Pro Medium, sans-serif, medium weight, all caps, normal letter-spacing; font size 1.98% of slide height; #FFFFFF; left aligned]: CLOUD-NATIVE WORKFLOW
- body at x 54.3, y 79.3, w 13.6, h 2 [DIN Pro Medium, sans-serif, medium weight, all caps, normal letter-spacing; font size 1.98% of slide height; #FFFFFF; left aligned]: SCALABLE ARCHITECTURE
- body at x 75, y 79.3, w 17.4, h 2 [DIN Pro Medium, sans-serif, medium weight, all caps, normal letter-spacing; font size 1.98% of slide height; #FFFFFF; right aligned]: OPEN | MODULAR | EXTENSIBLE

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 3.9, y 21.8, w 92.2, h 61.3: 2171 by 814 pixels
- image at x 3.9, y 67.8, w 92.2, h 15.5: 2656 by 251 pixels
- image at x 3.9, y 67.8, w 92.2, h 15.5: 2656 by 251 pixels
- text at x 19.2, y 7.9, w 61.6, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: ANNOUNCING NVIDIA DRIVE SIM POWERED BY OMNIVERSE
- text at x 7.5, y 79.3, w 17.1, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: PHYSICALLY ACCURATE SENSORS
- text at x 31.6, y 79.3, w 14.0, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: CLOUD-NATIVE WORKFLOW
- text at x 54.3, y 79.3, w 13.6, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: SCALABLE ARCHITECTURE
- text at x 75.0, y 79.3, w 17.4, h 2.0 [DINPro-Medium; font size 1.98; #FFFFFF]: OPEN | MODULAR | EXTENSIBLE

### Slide 92

**Text**

RTX Real-time

**Layout**

Full-bleed photograph covering the entire slide with no title, body text, margins or footer; a small rendering-status badge sits in the top-left corner over the image.

**Visuals**

Photograph (rendered CGI image) of the rear three-quarter view of a grey-silver concept sedan, the Mercedes-Benz Vision EQS, driving away from the viewer along a curving road lined with autumn trees. Subject: the car centred slightly left, seen from behind, with a horizontal red LED light strip across the tail and a blue accent line along the side; the Mercedes star badge is on the tail above the text 'VISION EQS'. Setting: left, a large tree with orange-gold leaves; centre background, a tall lamp post and more orange and bare trees; right, a red-and-blue circular 'no parking' sign with a white arrow on a grey pole, a small rectangular sign below it, and a yellow-leafed tree; road markings are white arrows and lines on grey asphalt; the right kerb edge is a light cobbled pavement with fallen leaves. Lighting: low warm sunlight from the front-right, golden highlights on the pavement and car body, bright pale sky at the top. Dominant colours: orange-gold, warm amber, grey-silver, white sky, red and blue accents. Framing: full landscape frame, uncropped, edge to edge. Overlay: a small grey rounded-rectangle badge with a light-bulb icon and the text 'RTX Real-time' in the top-left at about x 0.2 y 0.4 w 6 h 2.2, and a small grey badge with an eye icon beside it at about x 6.7 y 0.4 w 2.8 h 2.2; both are semi-transparent grey UI overlays. A tiny coordinate axis gizmo (red and green lines) sits at the bottom-left corner at about x 0.5 y 93.5 w 1.2 h 4.

**Design**

Background: Photograph of an autumn street scene with a pale white-to-gold sky behind trees (dominant sky colour #F5F2EA). No designed typography or theme; a raw rendering viewport capture. Background is the full photograph. Badge text is small white sans-serif (approximately Segoe UI style) about 1.3% of slide height. Badges have dark grey fill #4A4A4A at about 80% opacity with light grey text #E6E6E6 and rounded corners of about 0.3% of slide height. No shadows, no gradients other than the natural photographic lighting.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed rendered photograph of the rear view of the Mercedes-Benz Vision EQS concept car on an autumn street, with trees, lamp post, no-parking sign and cobbled pavement (Uncropped, edge to edge, no border; the 3840 by 2160 image covers the whole slide; no overlay tint on the photo itself)
- shape at x 0.2, y 0.4, w 6, h 2.2 [#4A4A4A]: Rounded grey status badge containing a light-bulb icon and the text 'RTX Real-time' (Fill #4A4A4A at about 80% opacity, corner radius about 0.3% of slide height, no border, no shadow)
- text at x 1.2, y 1.2, w 4.5, h 1 [Segoe UI, regular sans-serif; font size 1.3% of slide height; #E6E6E6; left aligned]: RTX Real-time (Text is white-grey, centred vertically inside the badge)
- icon at x 0.6, y 0.8, w 0.7, h 1.2 [#E6E6E6]: Light-bulb icon inside the status badge (Simple outline light bulb)
- shape at x 6.7, y 0.4, w 2.8, h 2.2 [#4A4A4A]: Rounded grey badge containing an eye icon (view toggle) (Fill #4A4A4A at about 80% opacity, corner radius about 0.3% of slide height, no border, no shadow)
- icon at x 7.4, y 0.8, w 1.2, h 1.2 [#E6E6E6]: Eye icon in the view-toggle badge (Simple outline eye)
- logo at x 0.5, y 93.5, w 1.2, h 4 [#2EA8E0]: Coordinate axis gizmo with red and green axis lines at bottom-left corner (Thin axis lines, small labels in red and green, semi-transparent overlay)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 99.8, h 100.0: 2174 by 1225 pixels (covers the slide)

### Slide 93

**Text**

NEW NVIDIA TECHNOLOGIES
Omniverse
Isaac Sim
Megatron | Drug Discovery
Quantum Computing
DGX | Grace
BlueField-3 | DOCA 1.0
Jarvis | Merlin
Maxine | Morpheus
NVIDIA AI
EGX Aerial 5G
DRIVE Sim
Hyperion 8
Atlan
Orin
AI
Path-Tracing
USD
Mater
NVIDIA A100/A30
NVIDIA A40/A10
NVIDIA A1
Jarvis
Maxine

**Layout**

Four tall vertical panels of equal width sit in a single row across the slide, evenly spaced with roughly equal margins at left and right, and each panel carries a gold plaque with centred text along its bottom edge. The title NEW NVIDIA TECHNOLOGIES is centred horizontally near the top of the slide in bold capitals, with no footer, logo or slide number.

**Visuals**

Four vertical image panels. Panel 1 (left): a glowing green-teal wireframe sphere with a white robot figure at its centre, labelled ANIMATION, KEYFRAME, RENDERING, NURBS and PHYSICS, with gold arrows at its left edge; the sphere is cropped by the right edge of the panel, and a row of small icons (AI globe, Path-Tracing sphere, blue USD logo, partly visible Material sphere) sits below it. Panel 2: two Bloch-sphere diagrams with axes and red state vectors joined by a blue wavy line, above a gold bracket tree feeding three gold-and-chrome processor modules, above a black circuit board with a large processor package and an NVIDIA-logo chip. Panel 3: a video-call style screen with tiles labelled Jarvis (blue water-drop avatar) and Maxine (portrait of a woman), a third partly visible tile, a gold cabinet with cuID, cuDF and a partly visible cuda tile and NVIDIA C text, a white server tray, and three black circular medallions reading NVIDIA A100/A30, NVIDIA A40/A10 and a cut-off NVIDIA A1. Panel 4: a dark navy car chassis wireframe with a silver roof-mounted sensor unit, green compute modules and orange wiring, lit from the side. Images are full height within their frames and cropped at the panel edges; the framed panels have a dark overlay and a thin gold outline.

**Design**

Background: Black (#000000) studio backdrop fading to charcoal grey (#2A2A2A) at the bottom, with a glossy dark floor reflecting the gold plaques.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Dark studio backdrop, black at top fading to charcoal grey floor (full-bleed 3840 by 2160 image behind everything)
- photo at x 0, y 74.4, w 100, h 15.1 [#2A2A2A]: Glossy floor reflection of the gold plaques (full-width reflection band beneath plaques)
- shape at x 8.75, y 21.6, w 15.75, h 62.8 [#000000]: Panel 1 frame, black rectangle with gold outline (stroke gold #A88A5A about 0.2 percent of slide width, square corners, no shadow)
- photo at x 8.8, y 21.9, w 15.5, h 62.6 [#0B1F1F]: Omniverse sphere with robot figure and labels ANIMATION, KEYFRAME, RENDERING, NURBS, PHYSICS, gold arrows at left edge (cropped at right edge of panel frame, dark overlay)
- icon at x 18.5, y 65.5, w 6.8, h 4.2 [#1E6FD9]: Row of icons: AI globe, Path-Tracing sphere, blue USD logo, partly visible Material sphere (circular icons about 1.8 percent of slide width each, cut off at panel right edge)
- caption at x 15.8, y 68.4, w 1.8, h 1.4 [DINPro-Medium; font size 1.5% of slide height; #FFFFFF; center aligned]: AI
- caption at x 19.8, y 68.4, w 4.5, h 1.4 [DINPro-Medium; font size 1.5% of slide height; #FFFFFF; center aligned]: Path-Tracing
- caption at x 25.7, y 68.4, w 2.2, h 1.4 [DINPro-Medium; font size 1.5% of slide height; #FFFFFF; center aligned]: USD
- caption at x 29.8, y 68.4, w 2.2, h 1.4 [DINPro-Medium; font size 1.5% of slide height; #FFFFFF; left aligned]: Mater
- shape at x 31.1, y 21.6, w 15.75, h 62.8 [#000000]: Panel 2 frame, black rectangle with gold outline (stroke gold #A88A5A about 0.2 percent of slide width, square corners, no shadow)
- illustration at x 31.7, y 25.5, w 14.9, h 12.7 [#000000]: Two Bloch-sphere diagrams with axes and red state vectors joined by a blue wavy line (thin white circles and dashed equators on black, blue wave, no border)
- diagram at x 33.8, y 38.5, w 11.2, h 6.5 [#B8925A]: Gold bracket connectors from a single stem to three processor modules (gold lines about 0.15 percent of slide width, right-angled elbows)
- photo at x 31.2, y 51.2, w 15.5, h 28.8 [#B8925A]: Three gold-and-chrome processor modules with gold cards (three identical modules spaced evenly on black)
- photo at x 31.1, y 56.5, w 15.8, h 16.5 [#000000]: Black circuit board with large processor package and NVIDIA-logo chip (full panel width, cut at bottom edge by plaque area)
- shape at x 53.2, y 21.6, w 15.75, h 62.8 [#000000]: Panel 3 frame, black rectangle with gold outline (stroke gold #A88A5A about 0.2 percent of slide width, square corners, no shadow)
- photo at x 53.3, y 21.8, w 15.5, h 55.5 [#1A1A1A]: Video-call screen with Jarvis avatar tile, Maxine portrait tile and partly visible third tile (cropped at right edge of panel)
- shape at x 56.5, y 37.6, w 12.3, h 18.2 [#A8864E]: Gold cabinet with cuID, cuDF and partly visible cuda tiles and NVIDIA C text (dark gold panel, cropped at right edge)
- shape at x 62.6, y 55.5, w 6.2, h 4.2 [#1E6FD9]: Blue bar below cabinet (solid blue rectangle, cropped at right edge)
- photo at x 54.3, y 58.5, w 13.7, h 14.5 [#E8E8E8]: White server tray with black module (angled tray, soft grey shading)
- photo at x 54.3, y 75.9, w 13.7, h 11.2 [#000000]: NVIDIA A100/A30 black circular medallion with gold card (circular crop, label NVIDIA A100/A30 inside)
- photo at x 63.2, y 75.9, w 13.7, h 11.2 [#000000]: NVIDIA A40/A10 black circular medallion with gold card (circular crop, label NVIDIA A40/A10 inside)
- photo at x 71.9, y 75.9, w 4.5, h 11.2 [#000000]: Cut-off NVIDIA A1 black circular medallion (circular crop, cut by panel edge)
- caption at x 57.3, y 78.5, w 4.5, h 2.2 [DINPro-Medium; font size 1.3% of slide height; #FFFFFF; center aligned]: NVIDIA A100/A30
- caption at x 62.2, y 78.5, w 4.5, h 2.2 [DINPro-Medium; font size 1.3% of slide height; #FFFFFF; center aligned]: NVIDIA A40/A10
- shape at x 75.5, y 21.6, w 15.75, h 62.8 [#000000]: Panel 4 frame, black rectangle with gold outline (stroke gold #A88A5A about 0.2 percent of slide width, square corners, no shadow)
- photo at x 75.6, y 21.9, w 15.5, h 62.5 [#0B1F3A]: Dark navy car chassis wireframe with silver roof sensor unit, green compute modules and orange wiring (cropped at panel edges, side lighting)
- shape at x 9.6, y 76, w 13.75, h 11.1 [#9C7D4C]: Gold plaque panel 1 (solid gold #9C7D4C with lighter top edge, square corners, slight shadow beneath)
- text at x 9.6, y 76, w 13.75, h 11.1 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Omniverse / Isaac Sim (line spacing about 2.5 percent of slide height)
- text at x 14.3, y 79.6, w 4.7, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Omniverse
- text at x 14.6, y 82.1, w 4.2, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Isaac Sim
- shape at x 32.05, y 76, w 13.75, h 11.1 [#9C7D4C]: Gold plaque panel 2 (solid gold #9C7D4C with lighter top edge, square corners, slight shadow beneath)
- text at x 32.05, y 76, w 13.75, h 11.1 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Megatron | Drug Discovery / Quantum Computing / DGX | Grace / BlueField-3 | DOCA 1.0 (four centred lines)
- text at x 33, y 77.2, w 12, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Megatron | Drug Discovery
- text at x 34.5, y 79.6, w 9, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Quantum Computing
- text at x 36.2, y 82.1, w 5.6, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: DGX | Grace
- text at x 33.8, y 84.5, w 10.4, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: BlueField-3 | DOCA 1.0
- shape at x 54.2, y 76, w 13.75, h 11.1 [#9C7D4C]: Gold plaque panel 3 (solid gold #9C7D4C with lighter top edge, square corners, slight shadow beneath)
- text at x 54.2, y 76, w 13.75, h 11.1 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Jarvis | Merlin / Maxine | Morpheus / NVIDIA AI / EGX Aerial 5G (four centred lines)
- text at x 57.8, y 77.1, w 6.7, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Jarvis | Merlin
- text at x 56.7, y 79.6, w 8.8, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Maxine | Morpheus
- text at x 59, y 82, w 4.2, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: NVIDIA AI
- text at x 58.1, y 84.5, w 6, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: EGX Aerial 5G
- shape at x 76.6, y 76, w 13.75, h 11.1 [#9C7D4C]: Gold plaque panel 4 (solid gold #9C7D4C with lighter top edge, square corners, slight shadow beneath)
- text at x 76.6, y 76, w 13.75, h 11.1 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: DRIVE Sim / Hyperion 8 / Atlan / Orin (four centred lines)
- text at x 81, y 77.1, w 4.6, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: DRIVE Sim
- text at x 80.9, y 79.6, w 4.7, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Hyperion 8
- text at x 82.1, y 82, w 2.5, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Atlan
- text at x 82.4, y 84.5, w 1.9, h 1.7 [DINPro-Medium, sans-serif, normal weight; font size 1.73% of slide height; #FFFFFF; center aligned]: Orin
- title at x 35, y 7.9, w 29.9, h 4.1 [DIN Pro Bold, sans-serif, bold, uppercase; font size 4.07% of slide height; #FFFFFF; center aligned]: NEW NVIDIA TECHNOLOGIES

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- fill at x 31.2, y 21.9, w 15.5, h 62.5: #000000
- fill at x 53.3, y 77.4, w 15.5, h 7.0: #000000
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 0.0, y 74.4, w 100.0, h 15.1: 3840 by 326 pixels
- image at x 8.8, y 21.9, w 15.5, h 62.6: 422 by 962 pixels
- image at x 75.6, y 21.9, w 15.5, h 62.5: 1066 by 2430 pixels
- image at x 53.3, y 21.8, w 15.5, h 55.5: 760 by 1536 pixels
- image at x 31.2, y 51.2, w 15.5, h 28.8: 735 by 768 pixels
- image at x 31.7, y 25.5, w 14.9, h 12.7: 741 by 355 pixels
- image at x 54.3, y 75.9, w 13.7, h 11.2: 1650 by 754 pixels
- image at x 76.4, y 75.9, w 13.7, h 11.2: 1650 by 754 pixels
- image at x 32.1, y 76.0, w 13.7, h 11.1: 1650 by 753 pixels
- image at x 9.8, y 76.0, w 13.7, h 11.1: 1650 by 753 pixels
- image at x 53.2, y 71.5, w 15.6, h 7.1: 448 by 115 pixels
- image at x 53.2, y 71.5, w 15.6, h 7.1: 448 by 115 pixels
- image at x 42.1, y 44.2, w 3.8, h 6.0: 228 by 204 pixels
- image at x 32.1, y 44.2, w 3.8, h 6.0: 227 by 204 pixels
- image at x 37.1, y 44.2, w 3.8, h 6.0: 114 by 102 pixels
- text at x 35.0, y 7.9, w 29.9, h 4.1 [DINPro-Bold; font size 4.07; #FFFFFF]: NEW NVIDIA TECHNOLOGIES
- text at x 33.0, y 77.2, w 12.0, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Megatron | Drug Discovery
- text at x 57.8, y 77.1, w 6.7, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Jarvis | Merlin
- text at x 81.0, y 77.1, w 4.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: DRIVE Sim
- text at x 14.3, y 79.6, w 4.7, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Omniverse
- text at x 34.5, y 79.6, w 9.0, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Quantum Computing
- text at x 56.7, y 79.6, w 8.8, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Maxine | Morpheus
- text at x 80.9, y 79.6, w 4.7, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Hyperion 8
- text at x 14.6, y 82.1, w 4.2, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Isaac Sim
- text at x 36.2, y 82.1, w 5.6, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: DGX | Grace
- text at x 59.0, y 82.0, w 4.2, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: NVIDIA AI
- text at x 82.1, y 82.0, w 2.5, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Atlan
- text at x 33.8, y 84.5, w 10.4, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: BlueField-3 | DOCA 1.0
- text at x 58.1, y 84.5, w 6.0, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: EGX Aerial 5G
- text at x 82.4, y 84.5, w 1.9, h 1.7 [DINPro-Medium; font size 1.73; #FFFFFF]: Orin

### Slide 94

**Text**

PRODUCT OF ITALY / TRAIN | ADAPT | OPTMIZ / Here we are / TAO / EXTRA VIRGIN / OLIVE OIL / Mado olive oil is luxury you can drizzle. / Punchy and fresh, it's made from 100% Italian olives, all picked by hand and pressed the same day. It's an olive oil so tasty it can spirit any dish straight to gastronomic heaven. / Also try our olive oil crushed with fresh lemons. / Produced in Italy by Mado Ltd London UK

**Layout**

Full-bleed photographic composition with no title, no footer, no page number and no margins; the subject sits in the lower centre, with the olive oil tin left of centre on a dark marble counter, a chrome grinder to its right, and wall-mounted electrical parts and wooden cabinets framing the upper half. Depth of field is shallow, so the foreground tin is sharp and the background blurs.

**Visuals**

Photograph (3D-rendered kitchen scene), full-bleed. Subject: a rectangular metal olive oil tin labelled TAO EXTRA VIRGIN OLIVE OIL with a green screw cap, standing on a dark green-black speckled marble countertop, with a chrome bell-top pepper or spice grinder with a dark wooden base and gold lettering to its right. Behind and above: a white electrical wall plate with a blank opening at left, a white duplex wall outlet with its mounting screws floating in front of a beige carved stone wall, and a white plastic electrical box floating above the tin, all appearing detached from the wall. Wooden upper cabinets with a shelf overhang the top right, an under-cabinet light strip glows at upper right, and a dark wooden lower cabinet with an open recess sits at right edge. Small ceramic pot, a dark ceramic dish and a white tray appear at left in soft focus. Framing: wide, eye-level, slightly low angle, subject in the lower centre. Lighting: warm interior light from the under-cabinet strip and ambient room light, with soft shadows. Dominant colours: beige and cream stone, warm honey wood browns, dark green marble, white and pale green on the tin, chrome grey. An orange glowing wireframe box outlines the tin and the electrical box, drawn as a thin orange-gold line, overlaying the photo. Not cropped, no tint or overlay beyond the orange outline.

**Design**

Background: Photograph of a kitchen scene in warm beige and wood tones (dominant #C9B79A stone wall behind dark marble counter #1F2B25), covering the whole slide. Photographic, realistic 3D render look with warm, muted palette. No text styling of the slide itself; the only typography is printed on the tin: 'PRODUCT OF ITALY' in small spaced serif-caps or sans caps, 'TRAIN | ADAPT | OPTMIZ' in a dark ribbon banner, 'TAO' in bold condensed black sans caps, body copy in a small dark grey serif or sans, and small print at the bottom. Tin background: off-white #ECE9E0, border of green olives #5DB32A with black leaves #1E1E1E, map of Italy silhouette in black #111111. Accent orange glow #E8922E. Marble counter #1F2B25. Wood tones #6B4524 to #A0692F.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed 3D-rendered photograph of a kitchen counter scene: olive oil tin, chrome grinder, floating electrical wall plate, outlet and electrical box, wooden cabinets and under-cabinet light (Covers the entire slide, not cropped, no border, no rounded corners, no tint; sharp foreground, shallow depth of field in background)
- shape at x 30.8, y 48.9, w 17, h 47 [#E8922E]: Orange glowing wireframe box outlining the olive oil tin and the floating electrical box (Thin orange-gold line roughly 2 px wide with soft glow, rectangular edges, no fill, overlaps the tin and the electrical box)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2300 by 1294 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)

### Slide 95

**Text**

NVIDIA®

**Layout**

Single centred logo lockup on a full-bleed dark background with no title, body text, footer or slide number. The logo sits horizontally centred, slightly above the vertical middle, with the lower third of the slide showing a faded grey floor-like gradient.

**Visuals**

One NVIDIA logo: the green eye-shaped emblem (a stylised eye formed by two interlocking curved shapes, the left half black-on-green and the right half solid green, set inside a green square block) followed by the white wordmark 'NVIDIA' in a bold geometric sans-serif capitals, with a small white registered-trademark symbol ® at the lower right of the wordmark. The logo is not cropped, sits on the black background with no overlay. Behind it, the background image shows a near-black field fading to dark grey (about #2A2A2A) toward the bottom edge with faint brushed-texture scratches, lit from above by a soft spotlight effect. No photograph subject beyond this backdrop.

**Design**

Background: Black (#000000) fading to dark grey (#2A2A2A) toward the bottom, with a faint brushed texture photograph covering the full slide. Black background fading to dark charcoal grey at the bottom; no title or body typography. Logo emblem green about #76B900; wordmark and registered mark white #FFFFFF. No shapes, lines, borders, corner radii, shadows beyond the subtle gradient. Wordmark is a heavy sans-serif with squared terminals.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100 [#000000]: Full-bleed background image: black top fading to dark grey brushed-metal-like floor texture at the bottom (Covers the entire slide behind all other elements; 3840 by 2160 pixels; not cropped; gradient lightens toward the bottom edge.)
- logo at x 28.4, y 38.9, w 41.3, h 13.6 [geometric sans-serif, bold, capitals; #76B900; center aligned]: NVIDIA logo: green eye emblem plus white wordmark 'NVIDIA' and ® mark (Image 2032 by 375 pixels; emblem in green #76B900 with black eye-stripes; wordmark in white #FFFFFF; sits over the photo background; no overlay or tint; wordmark letters are the same height as the emblem block's lower portion; ® mark at lower right of wordmark.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #FFFFFF (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 3840 by 2160 pixels (covers the slide)
- image at x 28.4, y 38.9, w 41.3, h 13.6: 2032 by 375 pixels

## Transcript

Captions (manual) of the recording "GTC Spring 2021 Keynote with NVIDIA CEO Jensen Huang" (https://www.youtube.com/watch?v=eAn_oiZwUXA). Timestamps are minutes and seconds into the recording.

[13:29] I am a creator Blending art and technology To immerse our senses I am a healer Helping us take the next step And see what's possible I am a pioneer Finding life-saving answers And pushing the edge to the outer limits.

[14:41] I am a guardian Defending our oceans Magnificent creatures that call them home I am a protector Helping the earth breathe easier And watching over it for generations to come I am a storyteller Giving emotion to words And bringing them to life. I am even the composer of the music. I am AI

[15:51] Brought to life by NVIDIA, deep learning, and brilliant minds everywhere. There are powerful forces shaping the world's industries. Accelerated computing that we pioneered has supercharged scientific discovery, while providing the computer industry a path forward. Artificial intelligence particularly, has seen incredible advances. With NVIDIA GPUs computers learn, and software writes software no human can. The AI software is delivered as a service from the cloud, performing automation at the speed-of-light. Software is now composed of microservices that scale across the entire data center - treating the data center as a single-unit of computing. AI and 5G are the ingredients to kick start the 4th industrial revolution where automation and robotics can be deployed to the far edges of the world. There is one more miracle we need, the metaverse, a virtual world that is a digital twin of ours.

[17:03] Welcome to GTC 2021 - we are going to talk about these dynamics and more. Let me give you the architecture of my talk. It's organized in four stacks - this is how we work - as a full-stack computing platform company. The flow also reflects the waves of AI and how we're expanding the reach of our platform to solve new problems, and to enter new markets. First is Omniverse - built from the ground-up on NVIDIA's body of work. It is a platform to create and simulate virtual worlds. We'll feature many applications of Omniverse, like design collaboration, simulation, and future robotic factories. The second stack is DGX and high-performance data centers. I'll feature BlueField, new DGXs, new chips, and the new work we're doing in AI, drug discovery, and quantum computing. Here, I'll also talk about Arm and new Arm partnerships. The third stack is one of our most important new platforms - NVIDIA EGX with Aerial 5G. Now, enterprises and industries can do AI and deploy AI-on-5G.

[18:15] We'll talk about NVIDIA AI and Pre-Trained Models, like Jarvis Conversational AI. And finally, our work with the auto industry to revolutionize the future of transportation - NVIDIA Drive. We'll talk about new chips, new platforms and software, and lots of new customers. Let's get started. Scientists, researchers, developers, and creators are using NVIDIA to do amazing things. Your work gets global reach with the installed base of over a billion CUDA GPUs shipped and 250 ExaFLOPS of GPU computing power in the cloud. Two and a half million developers and 7,500 startups are creating thousands of applications for accelerated computing. We are thrilled by the growth of the ecosystem we are building together and will continue to put our heart and soul into advancing it. Building tools for the Da Vincis of our time is our purpose. And in doing so, we also help create the future. Democratizing high-performance computers is one of NVIDIA's greatest contributions to science. With just a GeForce, every student can have a supercomputer.

[19:22] This is how Alex Krizhevsky, Ilya, and Hinton trained AlexNet that caught the world's attention on deep learning. And with GPUs in supercomputers, we gave scientists a time machine. A scientist once told me that because of NVIDIA's work, he can do his life's work in his lifetime. I can't think of a greater purpose. Let me highlight a few achievements from last year. NVIDIA is continually optimizing the full stack. With the chips you have, your software runs faster every year and even faster if you upgrade. On our gold suite of important science codes, we increased performance 13-fold in the last 5 years, and for some, performance doubled every year. NAMD molecular dynamics simulator, for example, was re-architected and can now run across multiple GPUs. Researchers led by Dr. Rommie Amaro at UC San Diego, used this multi-GPU NAMD, running on Oak Ridge Summit supercomputer's 20,000 NVIDIA GPUs, to do the largest atomic simulation ever - 305 million atoms.

[20:28] This work was critical to a better understanding of the COVID-19 virus and accelerated the making of the vaccine. Dr. Amaro and her collaborators won the Gordon Bell Award for this important work. I'm very proud to welcome Dr. Amaro and more than 100,000 of you to this year's GTC - our largest-ever by double. We have some of the greatest computer scientists and researchers of our time speaking here. 3 Turing award winners, 12 Gordon Bell award winners, 9 Kaggle Grand Masters - and even 10 Oscar winners. We're also delighted to have the brightest minds from industry sharing their discoveries. Leaders from every field - healthcare, auto, finance, retail, energy, internet services, every major enterprise IT company. They're bringing you their latest work in COVID research, data science, cybersecurity, new approaches to computer graphics and the most recent advances in AI and robotics. In total, 1,600 talks about the most important technologies of our time, from the leaders in the field that are shaping our world. Welcome to GTC.

[21:34] Let's start where NVIDIA started...computer graphics. Computer graphics is the driving force of our technology. Hundreds of millions of gamers and creators each year seek out the best NVIDIA has to offer. At its core, computer graphics is about simulations - using mathematics and computer science to simulate the interactions of light and material, the physics of objects, particles, and waves; and now simulating intelligence and animation. The science, engineering, and artistry that we dedicate in pursuit of achieving mother nature's physics has led to incredible advances. And allowed our technology to contribute to advancing the basic sciences, the arts, and the industries. This last year, we introduced the 2nd generation of RTX - a new rendering approach that fuses rasterization and programmable shading with hardware-accelerated ray tracing and artificial intelligence. This is the culmination of ten years of research. RTX has reset computer graphics, giving developers a powerful new tool just as rasterization plateaus. Let me show you some amazing footage from games in development. The technology and artistry is amazing.

[22:44] We’re giving the world’s billion gamers an incredible reason to upgrade. RTX is a reset of computer graphics.

[24:41] It has enabled us to build Omniverse - a platform for connecting 3D worlds into a shared virtual world. Ones not unlike the science fiction metaverse first described by Neal Stephenson in his early 1990s novel, Snow Crash, where the metaverse would be collectives of shared 3D spaces and virtually-enhanced physical spaces that are extensions of the internet. Pieces of the early-metaverse vision are already here - massive online social games like Fortnite or user-created virtual worlds like Minecraft. Let me tell you about Omniverse from the perspective of two applications - design collaboration and digital twins. There are several major parts of the platform. First, the Omniverse Nucleus, a database engine that connects users and enables the interchange of 3D assets and scene descriptions. Once connected, designers doing modeling, layout, shading, animation, lighting, special effects or rendering can collaborate to create a scene. The Omniverse Nucleus is described with the open standard USD, Universal Scene Description, a fabulous interchange framework invented by Pixar.

[25:53] Multiple users can connect to Nucleus, transmitting and receiving changes to their world as USD snippets. The 2nd part of Omniverse is the composition, rendering, and animation engine - the simulation of the virtual world. Omniverse is a platform built from the ground up to be physically-based. It is fully path-traced. Physics is simulated with NVIDIA PhysX, materials are simulated with NVIDIA MDL and Omniverse is fully integrated with NVIDIA AI. Omniverse is cloud-native, multi-GPU scalable and runs on any RTX platform and streams remotely to any device. The third part is NVIDIA CloudXR, a stargate if you will. You can teleport into Omniverse with VR and AIs can teleport out of Omniverse with AR. Omniverse was released to open beta in December. Let me show you what talented creators are doing. Creators are doing amazing things with Omniverse.

[27:19] At Foster and Partners, designers in 17 locations around the world, are designing buildings together in their Omniverse shared virtual space. ILM is testing Omniverse to bring together internal and external tool pipelines from multiple studios. Omniverse lets them collaborate, render final shots in real time and create massive virtual sets like holodecks. Ericsson is using Omniverse to do real-time 5G wave propagation simulation, with many multi-path interferences. Twin Earth is creating a digital twin of Earth that will run on 20,000 NVIDIA GPUs. And Activision is using Omniverse to organize their more than 100,000 3D assets into a shared and searchable world. Bentley is the world's leading infrastructure engineering software company. Everything that's constructed - roads and bridges, rail and transit systems, airports and seaports - about 3% of the world's GDP or three-and-a-half trillion dollars a year.

[28:29] Bentley's software is used to design, model, and simulate the largest infrastructure projects in the world. 90% of the world's top 250 engineering firms use Bentley. They have a new platform called iTwin - an exciting strategy to use the 3D model, after construction, to monitor and optimize the performance throughout its life. We are super excited to partner with Bentley to create infrastructure digital twins in Omniverse. Bentley is the first 3rd-party company to be developing a suite of applications on the Omniverse platform. This is just an awesome use of Omniverse, a great example of digital twins and Bentley is the perfect partner. And here's Perry Nightingale from WPP, the largest ad agency in the world, to tell you what they're doing. WPP is the largest marketing services organization on the planet, and because of that, we're also one of the largest production companies in the world That is a major carbon hotspot for us. We've partnered with NVIDIA, to capture locations virtually and bring them to life with studios in Omniverse. Over 10 billion points have turned into a giant mesh in Omniverse.

[29:39] For the first time, we can shoot locations virtually that are as real as the actual places themselves. Omniverse also changes the way we make work. A collaborative platform, that means multiple artists, at multiple points in the pipeline, in multiple parts of the world can collaborate on a single scene. Real time CGI in sustainable studios. Collaboration with Omniverse is the future of film at WPP. One of the most important features of Omniverse is that it obeys the laws of physics. Omniverse can simulate particles, fluids, materials, springs and cables. This is a fundamental capability for robotics. Once trained, the AI and software can be downloaded from Omniverse. In this video, you'll see Omniverse's physics simulation with rigid and soft bodies, fluids, and finite element modeling. And a lot more - enjoy! Omniverse is a physically-based virtual world where robots can learn to be robots.

[32:21] They'll come in all sizes and shapes - box movers, pick and place arms, forklifts, cars, trucks. In the future, a factory will be a robot, orchestrating many robots inside, building cars that are robots themselves. We can use Omniverse to create a virtual factory, train and simulate the factory and its robotic workers inside. The AI and software that run the virtual factory are exactly the same as what will run the actual one. The virtual and physical factories and their robots will operate in a loop. They are digital twins. Connecting to ERP systems, simulating the throughput of the factory, simulating new plant layouts, and becoming the dashboard of the operator - even uplinking into a robot to teleoperate it. BMW may very well be the world's largest custom-manufacturing company. BMW produces over 2 million cars a year. In their most advanced factory, a car a minute. Every car is different. We are working with BMW to create a future factory. Designed completely in digital, simulated from beginning to end in Omniverse, creating a digital twin, and operating a factory where robots and humans work together.

[33:34] Let's take a look at the BMW factory. Welcome to BMW Production, Jensen. I am pleased to show you why BMW sets the standards for innovation and flexibility. Our collaboration with NVIDIA Omniverse and NVIDIA AI leads into a new era of digitalization of automobile production. Fantastic to be with you, Milan. I am excited to do this virtual factory visit with you. We are inside the digital twin of BMW's assembly system, powered by Omniverse. For the first time, we are able to have our entire factory in simulation. Global teams can collaborate using different software packages like Revit, CATIA, or point clouds to design and plan the factory in real time 3D. The capability to operate in a perfect simulation revolutionizes BMW's planning processes. BMW regularly reconfigures its factories to accommodate new vehicle launches. Here we see 2 planning experts located in different parts of

[34:48] the world, testing a new line design in Omniverse. One of them wormholes into an assembly simulation with a motion capture suit, records task movements, while the other expert adjusts the line design - in real time. They work together to optimize the line as well as worker ergonomics and safety. “Can you tell how far I have to bend down there?” “First, I’ll get you a taller one” “Yeah, it’s perfect” We would like to be able to do this at scale in simulation. That's exactly why NVIDIA has Digital Human for simulation. Digital Humans are trained with data from real associates. You can then use Digital Humans in simulation to test new workflows for worker ergonomics and efficiency. Now, your factories employ 57,000 people that share workspace with many robots designed to make their jobs easier. Let's talk about them. You are right, Jensen. Robots are crucial for a modern production system. With NVIDIA Isaac robotics platform, BMW is deploying a fleet of intelligent robots for logistics to improve the material flow in our production.

[35:57] This agility is necessary since we produce 2.5 million vehicles per year, 99% of them are custom. Synthetic data generation and domain randomization available in Isaac are key to bootstrapping machine learning. Isaac Sim generates millions of synthetic images and vary the environment to teach the robots. Domain randomization can generate an infinite permutation of photorealistic objects, textures, orientations and lighting conditions. It is ideal for generating ground truth, whether for detection, segmentation, or depth perception. Let me show you an example of how we can combine it all to operate your factory. With NVIDIA's Fleet Command, your associates can securely orchestrate robots and other devices in the factory from Mission Control. They could monitor in real time complex manufacturing cells, update software over the air, launch robot missions and teleoperate. When a robot needs a helping hand, an alert can be sent to Mission Control and one of your associates can take control to help the robot.

[37:11] We're in the digital twin of one of your factories, but you have 30 others spread across 15 countries. The scale of BMW production is impressive, Milan. Indeed, Jensen, the scale and complexity of our production network requires BMW to constantly innovate. I am happy about the tight collaboration between our two companies. NVIDIA Omniverse and NVIDIA AI give us the chance to simulate all 31 factories in our production network. These new innovations will reduce the planning times, improve flexibility and precision and at the end, produce 30% more efficient planning processes. Milan, I could not be more proud of the innovations that our collaboration is bringing to the Factories of the Future. I appreciate you hosting me for a virtual visit of the digital twin of your BMW Production. It is a work of art! The ecosystem is really excited about Omniverse.

[38:16] This open platform, with USD universal 3D interchange, connects them into a large network of users. We have 12 connectors to major design tools already with another 40 in flight. Omniverse Connector SDK is available for download now. You can see that the most important design tools are already signed-up. Our lighthouse partners are from some of the world's largest industries - Media and Entertainment, Gaming, Architecture, Engineering, and Construction; Manufacturing, Telecommunications, Infrastructure, and Automotive. Computer makers worldwide are building NVIDIA-Certified workstations, notebooks, and servers optimized for Omniverse. And starting this summer, Omniverse will be available for enterprise license. Omniverse - NVIDIA's platform for creating and simulating shared virtual worlds. Data center is the new unit of computing. Cloud computing and AI are driving fundamental changes in the architecture of data centers. Traditionally, enterprise data centers ran monolithic software packages.

[39:21] Virtualization started the trend toward software-defined data centers - allowing applications to move about and letting IT manage from a "single-pane of glass". With virtualization, the compute, networking, storage, and security functions are emulated in software running on the CPU. Though easier to manage, the added CPU load reduced the data center's capacity to run applications, which is its primary purpose. This illustration shows the added CPU load in the gold-colored part of the stack. Cloud computing re-architected data centers again, now to provision services for billions of consumers. Monolithic applications were disaggregated into smaller microservices that can take advantage of any idle resource. Equally important, multiple engineering teams can work concurrently using CI/CD methods. Data center networks became swamped by east-west traffic generated by disaggregated microservices. CSPs tackled this with Mellanox's high-speed low-latency networking. Then, deep learning emerged. Magical internet services were rolled out, attracting more customers, and better engagement than ever.

[40:32] Deep learning is compute-intensive which drove adoption of GPUs. Nearly overnight, consumer AI services became the biggest users of GPU supercomputing technologies. Now, adding Zero-Trust security initiatives makes infrastructure software processing one of the largest workloads in the data center. The answer is a new type of chip for Data Center Infrastructure Processing like NVIDIA's Bluefield DPU. Let me illustrate this with our own cloud gaming service, GeForce Now, as an example. GeForce Now is NVIDIA's GeForce-in-the-cloud service. GeForce Now serves 10 million members in 70 countries. Incredible growth. GeForce Now is a seriously hard consumer service to deliver. Everything matters - speed of light, visual quality, frame rate, response, smoothness, start-up time, server cost, and most important of all, security. We're transitioning GeForce Now to BlueField.

[41:35] With Bluefield, we can isolate the infrastructure from the game instances, and offload and accelerate the networking, storage, and security. The GeForce Now infrastructure is costly. With BlueField, we will improve our quality of service and concurrent users at the same time - the ROI of BlueField is excellent. I'm thrilled to announce our first data center infrastructure SDK - DOCA 1.0 is available today! DOCA is our SDK to program BlueField. There's all kinds of great technology inside. Deep packet inspection, secure boot, TLS crypto offload, RegEX acceleration, and a very exciting capability - a hardware-based, real-time clock that can be used for synchronous data centers, 5G, and video broadcast. We have great partners working with us to optimize leading platforms on BlueField: Infrastructure software providers, edge and CDN providers, cybersecurity solutions, and storage providers - basically the world's leading companies in data center infrastructure. Though we're just getting started with BlueField 2, today we're announcing BlueField 3.

[42:42] 22 billion transistors. The first 400 Gbps networking chip. 16 Arm CPUs to run the entire virtualization software stack - for instance, running VMware ESX. BlueField 3 takes security to a whole new level, fully offloading and accelerating IPSEC and TLS cryptography, secret key management, and regular expression processing. We are on a pace to introduce a new Bluefield generation every 18 months. BlueField 3 will do 400 Gbps and be 10x the processing capability of BlueField 2. And BlueField 4 will do 800 Gbps and add NVIDIA's AI computing technologies to get another 10x boost. 100x in 3 years -- and all of it will be needed. A simple way to think about this is that 1/3rd of the roughly 30 million data center servers shipped each year are consumed running the software-defined data center stack. This workload is increasing much faster than Moore's law.

[43:46] So, unless we offload and accelerate this workload, data centers will have fewer and fewer CPUs to run applications. The time for BlueField has come. At the beginning of the big bang of modern AI, we recognized the need to create a new kind of computer for a new way of developing software. Software will be written by software running on AI computers. This new type of computer will need new chips, new system architecture, new ways to network, new software, and new methodologies and tools. We've invested billions into this intuition, and it has proven helpful to the industry. It all comes together as DGX - a computer for AI. We offer DGX as a fully integrated system, as well as offer the components to the industry to create differentiated options. I am pleased to see so much AI research advancing because of DGX - top universities, research hospitals, telcos, banks, consumer products companies, car makers, and aerospace companies. DGX help their AI researchers - whose expertise is rare, scarce, and their work strategic.

[44:56] It is imperative to make sure they have the right instrument. Simply, if software is to be written by computers, then companies with the best software engineers will also need the best computers. We offer several configurations - all software compatible. The DGX A100 is a building block that contains 5 petaFLOPS of computing and superfast storage and networking to feed it. DGX Station is an AI data center in-a-box designed for workgroups - plugs into a normal outlet. And DGX SuperPOD is a fully integrated, fully network-optimized, AI-data-center-as-a-product. SuperPOD is for intensive AI research and development. NVIDIA's own new supercomputer, called Selene, is 4 SuperPODs. It is the 5th fastest supercomputer and the fastest industrial supercomputer in the world's Top 500. We have a new DGX Station 320G. DGX Station can train large models - 320 gigabytes of super-fast HBM2e connected to 4 A100 GPUs over 8 terabytes per second of memory bandwidth. 8 terabytes transferred in one second.

[46:08] It would take 40 CPU servers to achieve this memory bandwidth. DGX Station plugs into a normal wall outlet, like a big gaming rig, consumes just 1,500 watts, and is liquid-cooled to a silent 37 db. Take a look at the cinematic that our engineers and creative team did. A CPU cluster of this performance would cost about a million dollars today.

[47:34] DGX Station is $149,000 - the ideal AI programming companion for every AI researcher. Today we are also announcing a new DGX SuperPOD. Three major upgrades: The new 80 gigabyte A100 which brings the SuperPOD to 90 terabytes of HBM2 memory, with aggregate bandwidth of 2.2 exabytes per second. It would take 11,000 CPU servers to achieve this bandwidth - about a 250-rack data center - 15 times bigger than the SuperPOD. Second, SuperPOD has been upgraded with NVIDIA BlueField-2. SuperPOD is now the world's first cloud-native supercomputer, multi-tenant shareable, with full isolation and bare-metal performance. And third, we're offering Base Command, the DGX management and orchestration tool used within NVIDIA. We use Base Command to support thousands of engineers, over two hundred teams, consuming a million-plus GPU-hours a week.

[48:43] DGX SuperPOD starts at seven million dollars and scales to sixty million dollars for a full system. Let me highlight 3 great uses of DGX. Transformers have led to dramatic breakthroughs in Natural Language Processing. Like RNN and LSTM, Transformers are designed to inference on sequential data. However, Transformers, more than meets the eyes, are not trained sequentially, but use a mechanism called attention such that Transformers can be trained in parallel. This breakthrough reduced training time, which more importantly enabled the training of huge models with a correspondingly enormous amount of data. Unsupervised learning can now achieve excellent results, but the models are huge. Google's Transformer was 65 million parameters. OpenAI's GPT-3 is 175 billion parameters. That's 3000x times larger in just 3 years. The applications for GPT-3 are really incredible. Generate document summaries.

[49:47] Email phrase completion. GPT-3 can even generate Javascript and HTML from plain English - essentially telling an AI to write code based on what you want it to do. Model sizes are growing exponentially - on a pace of doubling every two and half months. We expect to see multi-trillion-parameter models by next year, and 100 trillion+ parameter models by 2023. As a very loose comparison, the human brain has roughly 125 trillion synapses. So these transformer models are getting quite large. Training models of this scale is incredible computer science. Today, we are announcing NVIDIA Megatron - for training Transformers. Megatron trains giant Transformer models - it partitions and distributes the model for optimal multi-GPU and multi-node parallelism. Megatron does fast data loading, micro batching, scheduling and syncing, kernel fusing. It pushes the limits of every NVIDIA invention - NCCL, NVLink, Infiniband, Tensor Cores.

[50:57] Even with Megatron, a trillion-parameter model will take about 3-4 months to train on Selene. So, lots of DGX SuperPODS will be needed around the world Inferencing giant Transformer models is also a great computer science challenge. GPT-3 is so big, with so many floating-point operations, that it would take a dual-CPU server over a minute to respond to a single 128-word query. And GPT-3 is so large that it doesn't fit in GPU memory - so it will have to be distributed. multi-GPU multi-node inference has never been done. Today, we're announcing the Megatron Triton Inference Server. A DGX with Megatron Triton will respond within a second! Not a minute - a second! And for 16 queries at the same time. DGX is 1000 times faster and opens up many new use-cases, like call-center support, where a one-minute response is effectively unusable. Naver is Korea's #1 search engine.

[52:03] They installed a DGX SuperPOD and are running their AI platform CLOVA to train language models for Korean. I expect many leading service providers around the world to do the same Use DGX to develop and operate region-specific and industry-specific language services. NVIDIA Clara Discovery is our suite of acceleration libraries created for computational drug discovery - from imaging, to quantum chemistry, to gene variant-calling, to using NLP to understand genetics, and using AI to generate new drug compounds. Today we're announcing four new models available in Clara Discovery: MegaMolBART is a model for generating biomolecular compounds. This method has seen recent success with Insilico Medicine using AI to find a new drug in less than two years. NVIDIA ATAC-seq denoising algorithm for rare and single cell epi-genomics is helping to understand gene expression for individual cells. AlphaFold1 is a model that can predict the 3D structure of a protein from the amino acid sequence.

[53:12] GatorTron is the world's largest clinical language model that can read and understand doctors' notes. GatorTron was developed at UoF, using Megatron, and trained on the DGX SuperPOD gifted to his alma mater by Chris Malachowsky, who founded NVIDIA with Curtis and me. Oxford Nanopore is the 3rd generation genomics sequencing technology capable of ultra high throughput in digitizing biology - 1/5 of the SARS-CoV-2 virus genomes in the global database were generated on Oxford Nanopore. Last year, Oxford Nanopore developed a diagnostic test for COVID-19 called LamPORE, which is used by NHS. Oxford Nanopore is GPU-accelerated throughout. DNA samples pass through nanopores and the current signal is fed into an AI model, like speech recognition, but trained to recognize genetic code. Another model called Medaka reads the code and detects genetic variants. Both models were trained on DGX SuperPOD. These new deep learning algorithms achieve 99.9% detection accuracy of single nucleotide variants - this is the gold standard of human sequencing.

[54:24] Pharma is a 1.3 trillion-dollar industry where a new drug can take 10+ years and fails 90% of the time. Schrodinger is the leading physics-based and machine learning computational platform for drug discovery and material science. Schrodinger is already a heavy user of NVIDIA GPUs, recently entering into an agreement to use hundreds of millions of NVIDIA GPU hours on the Google cloud. Some customers can't use the cloud, so today we are announcing a partnership to accelerate Schrodinger's drug discovery workflow with NVIDIA Clara Discovery libraries and NVIDIA DGX. The world's top 20 pharmas use Schrodinger today. Their researchers are going to see a giant boost in productivity. Recursion is a biotech company using leading-edge computer science to decode biology to industrialize drug discovery. The Recursion Operating System is built on NVIDIA DGX SuperPOD for generating, analyzing and gaining insight from massive biological and chemical datasets. They call their SuperPOD the BioHive-1 - it's the most powerful computer at any pharma today.

[55:38] Using deep learning on DGX, Recursion is classifying cell responses after exposure to small molecule drugs. Quantum computing is a field of physics that studies the use of natural quantum behavior - superposition, entanglement, and interference - to build a computer. The computation is performed using quantum circuits that operate on quantum bits - called qubits. Qubits can be 0 or 1, like a classical computing bit, but also in superposition - meaning they exist simultaneously in both states. The qubits can be entangled where the behavior of one can affect or control the behavior of others. Adding and entangling more qubits lets quantum computers calculate exponentially more information. There is a large community around the world doing research in quantum computers and algorithms. Well over 50 teams in industry, academia, and national labs are researching the field. We're working with many of them. Quantum computing can solve Exponential Order Complexity problems, like factoring large numbers for cryptography, simulating atoms and molecules for drug discovery, finding shortest path optimizations, like the traveling salesman problem,

[56:50] The limiter in quantum computing is decoherence, falling out of quantum states, caused by the tiniest of background noise So error correction is essential. It is estimated that to solve meaningful problems, several million physical qubits will be required to sufficiently error correct. The research community is making fast progress, doubling physical Qubits each year, so likely achieving the milestone by 2035 to 2040. Well within my career horizon. In the meantime, our mission is to help the community research the computer of tomorrow with the fastest computer of today. Today, we're announcing cuQuantum - an acceleration library designed for simulating quantum circuits for both Tensor Network Solvers and State Vector Solvers. It is optimized to scale to large GPU memories, multiple GPUs, and multiple DGX nodes. The speed-up of cuQuantum on DGX is excellent. Running the cuQuantum Benchmark, state vector simulation takes 10 days on a dual-CPU server but only 2 hours on a DGX A100. cuQuantum on DGX can productively simulate 10's of qubits.

[58:04] And Caltech, using Contengra/Quimb, simulated the Sycamore quantum circuit at depth 20 in record time using cuQuantum on NVIDIA's Selene supercomputer. What would have taken years on CPUs can now run in a few days on cuQuantum and DGX. cuQuantum will accelerate quantum circuit simulators so researchers can design better quantum computers and verify their results, architect hybrid quantum-classical systems -and discover more Quantum-Optimal algorithms like Shor's and Grover's. cuQuantum on DGX is going to give the quantum community a huge boost. I'm hoping cuQuantum will do for quantum computing what cuDNN did for deep learning. Modern data centers host diverse applications that require varying system architectures. Enterprise servers are optimized for a balance of strong single-threaded performance and a nominal number of cores. Hyperscale servers, optimized for microservice containers, are designed for a high number of cores, low cost, and great energy-efficiency. Storage servers are optimized for large number of cores and high IO throughput.

[59:15] Deep learning training servers are built like supercomputers - with the largest number of fast CPU cores, the fastest memory, the fastest IO, and high-speed links to connect the GPUs. Deep learning inference servers are optimized for energy-efficiency and best ability to process a large number of models concurrently. The genius of the x86 server architecture is the ability to do a good job using varying configurations of the CPU, memory, PCI express, and peripherals to serve all of these applications. Yet processing large amounts of data remains a challenge for computer systems today - this is particularly true for AI models like transformers and recommender systems. Let me illustrate the bottleneck with half of a DGX. Each Ampere GPU is connected to 80GB of super fast memory running at 2 TB/sec. Together, the 4 Amperes process 320 GB at 8 Terabytes per second. Contrast that with CPU memory, which is 1TB large, but only 0.2 Terabytes per second.

[60:27] The CPU memory is 3 times larger but 40 times slower than the GPU. We would love to utilize the full 1,320 GB of memory of this node to train AI models. So, why not something like this? Make faster CPU memories, connect 4 channels to the CPU, a dedicated channel to feed each GPU. Even if a package can be made, PCIe is now the bottleneck. We can surely use NVLINK. NVLINK is fast enough. But no x86 CPU has NVLINK, not to mention 4 NVLINKS. Today, we're announcing our first data center CPU, Project Grace, named after Grace Hopper, a computer scientist and U.S. Navy rear Admiral, who in the '50s pioneered computer programming. Grace is Arm-based and purpose-built for accelerated computing applications of large amounts of data - such as AI. Grace highlights the beauty of Arm. Their IP model allowed us to create the optimal CPU for this application which achieves x-factors speed-up. The Arm core in Grace is a next generation off-the-shelf IP for servers. Each CPU will deliver over 300 SpecInt with a total of over 2,400

[61:45] SPECint_rate CPU performance for an 8-GPU DGX. For comparison, todays DGX, the highest performance computer in the world today is 450 SPECint_rate. 2400 SPECint_rate with Grace versus 450 SPECint_rate today. So look at this again - Before, After, Before, After. Amazing increase in system and memory bandwidth. Today, we're introducing a new kind of computer. The basic building block of the modern data center. Here it is. What I'm about to show you brings together the latest GPU accelerated computing, Mellanox high performance networking, and something brand new. The final piece of the puzzle.

[62:59] The world's first CPU designed for terabyte-scale accelerated computing... her secret codename - GRACE. This powerful, Arm-based CPU gives us the third foundational technology for computing, and the ability to rearchitect every aspect of the data center for AI. We're thrilled to announce the Swiss National Supercomputing Center will build a supercomputer powered by Grace and our next generation GPU. This new supercomputer, called Alps, will be 20 exaflops for AI, 10 times faster than the world's fastest supercomputer today. Alps will be used to do whole-earth-scale weather and climate simulation, quantum chemistry and quantum physics for the Large Hadron Collider. Alps will be built by HPE and is come on-line in 2023. We're thrilled by the enthusiasm of the supercomputing community, welcoming us to make Arm a top-notch scientific computing platform. Our data center roadmap is now a rhythm consisting of 3-chips: CPU, GPU, and DPU.

[64:12] Each chip architecture has a two-year rhythm with likely a kicker in between. One year will focus on x86 platforms. One year will focus on Arm platforms. Every year will see new exciting products from us. The NVIDIA architecture and platforms will support x86 and Arm - whatever customers and markets prefer. Three chips. Yearly Leaps. One Architecture. Arm is the most popular CPU in the world. For good reason - its super energy-efficient. Its open licensing model inspires a world of innovators to create products around it. Arm is used broadly in mobile and embedded today. For other markets like the cloud, enterprise and edge data centers, supercomputing and PCs. Arm is just starting and has great growth opportunities. Each market has different applications and has unique systems, software, peripherals, and ecosystems. For the markets we serve, we can accelerate Arm's adoption.

[65:19] Let's start with the big one - Cloud. One of the earliest designers of Arm CPUs for data centers is AWS - its Graviton CPUs are extremely impressive. Today, we're announcing NVIDIA and AWS are partnering to bring Graviton2 and NVIDIA GPUs together. This partnership brings Arm into the most demanding cloud workloads - AI and cloud gaming. Mobile gaming is growing fast and is the primary form of gaming in some markets. With AWS-designed Graviton2, users can stream Arm-based applications and Android games straight from AWS. It's expected later this year. We are announcing a partnership with Ampere Computing to create a scientific and cloud computing SDK and reference system. Ampere Computing's Altra CPU is excellent - 80 cores, 285 SPECint17, right up there with the highest performance x86. We are seeing excellent reception at supercomputing centers around the world and at Android cloud gaming services.

[66:26] We are also announcing a partnership with Marvell to create an edge and enterprise computing SDK and reference system. Marvell Octeon excels at IO, storage and 5G processing. This system is ideal for hyperconverged edge servers. We're announcing a partnership with Mediatek to create a reference system and SDK for Chrome OS and Linux PC's. Mediatek is the world's largest SOC maker. Combining NVIDIA GPUs and Mediatek SOCs will make excellent PCs and notebooks. AI, computers automating intelligence, is the most powerful technology force of our time. We see AI in four waves. The first wave was to reinvent computing for this new way of doing software - we're all in and have been driving this for nearly 10 years. The first adopters of AI were the internet companies - they have excellent computer scientists, large computing infrastructures, and the ability to collect a lot of training data.

[67:30] We are now at the beginning of the next wave. The next wave is enterprise and the industrial edge, where AI can revolutionize the world's largest industries. From manufacturing, logistics, agriculture, healthcare, financial services, and transportation. There are many challenges to overcome, one of which is connectivity, which 5G will solve. And then autonomous systems. Self-driving cars are an excellent example. But everything that moves will eventually be autonomous. The industrial edge and autonomous systems are the most challenging, but also the largest opportunities for AI to make an impact. Trillion dollar industries can soon apply AI to improve productivity, and invent new products, services and business models. We have to make AI easier to use - turn AI from computer science to computer products. We're building the new computing platform for this fundamentally new software approach - the computer for the age of AI. AI is not just about an algorithm - building and operating AI is a fundamental change in every aspect of software - Andrej Karpathy rightly called it Software 2.0.

[68:47] Machine learning, at the highest level, is a continuous learning system that starts with data scientists developing data strategies and engineering predictive features - this data is the digital life experience of a company. Training involves inventing or adapting an AI model that learns to make the desired predictions. Simulation and validation test the AI application for accuracy, generalization, and potential bias. And finally, orchestrating a fleet of computers, whether in your data center or at the edge in the warehouse, farms, or wireless base stations. NVIDIA created the chips, systems, and libraries needed for end-to-end machine learning - for example, technologies like Tensor Core GPUs, NVLINK, DGX, cuDNN, RAPIDS, NCCL, GPU Direct, DOCA, and so much more. We call the platform NVIDIA AI. NVIDIA AI libraries accelerate every step, from data processing to fleet orchestration. NVIDIA AI is integrated into all of the industry's popular tools and workflows.

[69:52] NVIDIA AI is in every cloud, used by the world's largest companies, and by over 7,500 AI startups around the world. And NVIDIA AI runs on any system that includes NVIDIA GPUs, from PCs and laptops, to workstations, to supercomputers, in any cloud, to our $99 Jetson robot computer. One segment of computing we've not served is enterprise computing. 70% of the world's enterprises run VMware, as we do at NVIDIA. VMware was created to run many applications on one virtualized machine. AI, on the other hand, runs a single job, bare-metal, on multiple GPUs and often multiple nodes. All of the NVIDIA optimizations for compute and data transfer are now plumbed through the VMware stack so AI workloads can be distributed to multiple systems and achieve bare-metal performance. The VMware stack is also offloaded and accelerated on NVIDIA BlueField. NVIDIA AI now runs in its full glory on VMware, which means everything that has been accelerated by NVIDIA AI now runs great on VMware.

[71:03] AI applications can be deployed and orchestrated with Kubernetes running on VMware Tanzu. We call this platform NVIDIA EGX for Enterprise. The enterprise IT ecosystem is thrilled - finally the 300,000 VMware enterprise customers can easily build an AI computing infrastructure that seamlessly integrates into their existing environment. In total, over 50 servers from the world's top server makers will be certified for NVIDIA EGX Enterprise. BlueField 2 offloads and accelerates the VMware stack and does the networking for distributed computing. Enterprise can choose big or small GPUs for heavy-compute or heavy-graphics workloads like Omniverse, or mix and match. All run NVIDIA AI. Enterprise companies make up the world's largest industries and they operate at the edge - in hospitals, factories, plants, warehouses, stores, farms, cities and roads - far from data centers. The missing link is 5G.

[72:05] Consumer 5G is great, but Private 5G is revolutionary. Today, we're announcing the Aerial A100 - bringing together 5G and AI into a new type of computing platform designed for the edge. Aerial A100 integrates the Ampere GPU and BlueField DPU into one card - this is the most advanced PCI express card ever created. So, it's not a surprise that Aerial A100 in an EGX system will be a complete 5G base station. Aerial A100 delivers up to full 20 Gbps and can process up to 9 100Mhz massive MIMO for 64T64R - or 64 transmit and 64 receive antenna arrays - state of the art capabilities. Aerial A100 is software-defined, with accelerated features like PHY, Virtual Network Functions, network acceleration, packet pacing, and line-rate cryptography. Our partners ERICSSON, Fujitsu, Mavenir, Altran, and Radisys will build their total 5G solutions on top of the Aerial library.

[73:17] NVIDIA EGX server with Aerial A100 is the first 5G base-station that is also a cloud-native, secure, AI edge data center. We have brought the power of the cloud to the 5G edge. Aerial also extends the power of 5G into the cloud. Today, we are excited to announce that Google will support NVIDIA Aerial in the GCP cloud. I have an important new platform to tell you about. The rise of microservice-based applications and hybrid-cloud has exposed billions of connections in a data center to potential attack. Modern Zero-Trust security models assume the intruder is already inside and all container-to-container communications should be inspected, even within a node. This is not possible today. The CPU load of monitoring every piece of traffic is simply too great. Today, we are announcing NVIDIA Morpheus - a data center security platform for real-time all-packet inspection. Morpheus is built on NVIDIA AI, NVIDIA BlueField, Net-Q network telemetry software, and EGX.

[74:29] We're working to create solutions with industry leaders in data center security - Fortinet, Red Hat, Cloudflare, Splunk, F5, and Aria Cybersecurity. And early customers - Booz Allen Hamilton, Best Buy, and of course, our own team at NVIDIA. Let me show you how we're using Morpheus at NVIDIA. It starts with a network. Here we see a representation of a network, where dots are servers and lines (the edges) are packets flowing between those servers. Except in this network, Morpheus is deployed. This enables AI inferencing across your entire network, including east/west traffic. The particular model being used here has been trained to identify sensitive information - AWS credentials, GitHub credentials, private keys, passwords. If observed in the packet, these would appear as red lines, and we don't see any of that. Uh oh, what happened. An updated configuration was deployed to a critical business app on this server. This update accidentally removed encryption, and now everything that communicates with that app

[75:34] sends and receives sensitive credentials in the clear. This can quickly impact additional servers. This translates to continuing exposure on the network. The AI model in Morpheus is searching through every packet for any of these credentials, continually flagging when it encounters such data. And rather than using pattern matching, this is done with a deep neural network - trained to generalize and identify patterns beyond static rule sets. Notice all of the individual lines. It's easy to see how quickly a human could be overwhelmed by the vast amount of data coming in. Scrolling through the raw data gives a sense of the massive scale and complexity that is involved. With Morpheus, we immediately see the lines that represent leaked sensitive information. By hovering over one of those red lines, we show complete info about the credential, making it easy to triage and remediate. But what happens when this remediation is necessary? Morpheus enables cyber applications to integrate and collect information for automated incident management and action prioritization.

[76:39] Originating servers, destination servers, actual exposed credentials, and even the raw data is available. This speeds recovery and informs which keys were compromised and need be rotated. With Morpheus, the chaos becomes manageable. The IT ecosystem has been hungry for an AI computing platform that is enterprise and edge ready. NVIDIA AI on EGX with Aerial 5G is the foundation of what the IT ecosystem has been waiting for. We are supported by leaders from all across the IT industry - from systems, infrastructure software, storage and security, data analytics, industrial edge solutions, manufacturing design and automation, to 5G infrastructure. To complete our enterprise offering, we now have NVIDIA AI Enterprise software so businesses can get direct-line support from NVIDIA. NVIDIA AI Enterprise is optimized and certified for VMware, and offers services and support needed by mission-critical enterprises. Deep learning has unquestionably revolutionized computing.

[77:49] Researchers continue to innovate at lightspeed with new models and new variants. We're creating new systems to expand AI into new segments - like Arm, enterprise, or 5G edge. We're also using these systems to do basic research in AI and building new AI products and services. Let me show you some of our work in AI, basic and applied research. DLSS: Deep Learning Super Sampling. StyleGAN: AI high resolution image generator. GANcraft: a neural rendering engine, turning Minecraft into realistic 3D. GANverse3D: turns photographs into animatable 3D models. Face Vid2Vid: a talking-head rendering engine that can reduce streaming bandwidth by 10x, while re-posing the head and eyes. Sim2Real: a quadruped trained in Omniverse, and the AI can run in a real robot - digital twins. SimNet: a Physics Informed Neural Network solver that can simulate large-scale multi-physics. BioMegatron: the largest biomedical language model ever trained.

[78:57] 3DGT: Omniverse synthetic data generation. and OrbNet: a machine learning quantum solver for quantum chemistry. This is just a small sampling of the AI work we're doing at NVIDIA. We're building AIs to use in our products and platforms. We're also packaging up the models to be easily integrated into your applications. These are essentially no-coding open-source applications that you can modify. Now, we're offering NGC pre-trained models, that you can plug into these applications, or ones you develop. These pre-trained models are production quality, trained by experts, and will continue to benefit from refinement. There are new credentials to tell you about the models' development, testing, and use. And each comes with a reference application sample code. NVIDIA pre-trained models are state-of-the-art and meticulously trained, but there is infinite diversity of application domains, environments, and specializations. No one has all the data - sometimes it's rare, sometimes they're trade-secrets. So we created technology for you to fine-tune and adapt NVIDIA pre-trained models for your applications.

[80:06] TAO applies transfer learning on your data to fine-tune our models with your data. TAO has an excellent federated learning system to let multiple parties collectively train a shared model while protecting data privacy. NVIDIA federated learning is a big deal - researchers at different hospitals can collaborate on one AI model while keeping their data separate to protect patient privacy. TAO uses NVIDIA's great TensorRT to optimize the model for the target GPU system. With NVIDIA pre-trained models and TAO, something previously impossible for many, can now be done in hours. Fleet Command is a cloud-native platform for securely operating and orchestrating AI across a distributed fleet of computers - it was purpose-built for operating AI at the edge. Fleet Command running on Certified EGX systems will feature secure boot, attestation, uplink and downlink, to a confidential enclave. From any cloud or on-prem, you can monitor the health of your fleet.

[81:11] Let's take a look at how one customer is using NGC pre-trained models and TAO to fine-tune models and run in our Metropolis smart city application, orchestrated by Fleet Command. No two industrial environments are the same. And conditions routinely change Adapting, managing, and operationalizing AI-enabled applications at the edge for unique, specific sites can be incredibly challenging - requiring a lot of data and time for model training. Here, we're building applications for a factory with multiple problems to solve Understanding how a factory floor space is used over time Ensuring worker safety, with constantly evolving machinery and risk factors Inspecting products on the factory line, where operations change routinely We start with a Metropolis application running 3 pretrained models from NGC. We are up and running in minutes. But since the environment is visually quite different from the data used to train this model, the video analytics accuracy at this specific site isn't great. People are not being accurately recognized and tracked and defects are being missed. Now let's use NVIDIA TAO to solve for this.

[82:15] With this simple UI, we re-train and adapt our pre-trained models with labelled data from the specific environment we're deploying in. We select our datasets. Each is a few 100 images, as opposed to millions of labelled images required if we were to train this from scratch. With NVIDIA Tao we go from 65% to over 90% accuracy. And through pruning & quantization, compute complexity is reduced by 2x - with no reduction in accuracy and real-time performance is maintained. In this example, the result is 3 models specifically trained for our factory - all in just minutes With one-click, we update and deploy these optimized models onto NVIDIA Certified servers with Fleet Command, seamlessly and securely from the cloud. From secure boot to our confidential AI Enclave in GPUs, application data and critical intellectual property remains safe. AI accuracy, system performance and health can be monitored remotely. This establishes a feedback loop for continuous application enhancements. The factory now has an end-to-end framework to adapt to changing conditions - often and easily. We make it easy to adapt and optimize NGC pretrained models with NVIDIA TAO and deploy and orchestrate applications with Fleet Command.

[83:30] We have all kinds of computer vision, speech, language and robotics models, and more coming all the time. Some are the work of our genetics and medical imaging team. For example, this model that predicts supplemental oxygen needs from xX-ray and electronic health records. This is a collaboration of 20 hospitals across 8 countries and 5 continents for COVID-19. Federated learning and NVIDIA TAO was essential to make this possible. The world needs a state-of-the-art conversational AI that can be customized and processed anywhere. Today, we're announcing the availability of NVIDIA Jarvis - a state-of-the-art deep learning AI for speech recognition, language understanding, translations, and speech. End-to-end GPU-accelerated, Jarvis interacts in about 100 milliseconds - listening, understanding, and responding faster than the blink of a human eye. We trained Jarvis for several million GPU-hours, on over 1 billion pages of text, and sixty thousand hours of speech in different languages, accents, environments and lingos.

[84:41] Out of the box, Jarvis achieves a world-class 90% recognition accuracy. You can get even better for your application by refining with your own data using NVIDIA TAO. Jarvis supports 5 languages today - English, Japanese, Spanish, German, French, and Russian. Jarvis does excellent translation, in the Bilingual Evaluation Understudy benchmark, Jarvis scores 40 points for English-to-Japanese, and 50 points for English-to-Spanish. 40 is high quality and state-of-the-art. 50 is considered fluent translation. Jarvis can be customized for domain jargon. We've trained Jarvis for technical and healthcare scenarios. It's easy with TAO. And Jarvis now speaks with expression and emotion that you can control - no more mechanical talk. And lastly, this is a big one - Jarvis can be deployed in the cloud, on EGX in your data center, at the edge in a shop, warehouse, or factory running on EGX Aerial, or inside a delivery robot running on a Jetson computer.

[85:50] Jarvis early access program began last May and our Conversational AI software has been downloaded 45,000 times. Among early users is T-Mobile, the U.S. telecom giant. They're using Jarvis to offer exceptional customer service that demands high-quality and low-latency needed in real-time speech recognition. We're announcing a partnership with Mozilla Common Voice, one of the world's largest multi-language voice datasets, and its openly available to all NVIDIA will use our DGXs to process and train Jarvis with the dataset of 150,000 speakers in 65 languages and offer Jarvis back to the community for free. So go to Mozilla Common Voice and make some recordings! Let's make universal translation possible and help people around the world understand each other. Now let me show you Jarvis. The first part of Jarvis is speech recognition. Jarvis is over 90% accurate out-of-the-box - that's world-class. And you can still use TAO to make it even better for your application, like customizing for healthcare jargon.

[86:58] Chest x-ray shows left retrocardiac opacity, and this may be due to atelectasis, aspiration, or early pneumonia. I have no idea what I said but Jarvis recognized it perfectly. Jarvis translation now supports five languages. Let's do Japanese. "Excuse me, I'm looking for the famous Jangara Ramen shop. It should be nearby, but I don't see it on my map. Can you show me the way? I'm very hungry." That's great. Excellent accuracy. I think. Instantaneous response. You can do German, French, and Russian--with more languages on the way. Jarvis also speaks with feelings. Let's try this - "The more you buy, the more you save!" "The more you buy, the more you save" I think we are going to need more enthusiasm. "The more you buy, the more you save!"

[88:02] NVIDIA Jarvis - state-of-the-art deep learning conversational AI, interactive response, 5 languages, customize with TAO, and deploy from cloud, to edge, to autonomous systems. Recommender systems are the most important machine learning pipeline in the world today. It is the engine for search, ads, on-line shopping, music, books, movies, user-generated content, news. Recommender systems predict your needs and preferences from past interactions with you, your explicit preferences and learned preferences using methods called collaborative and content filtering. Trillions of items to be recommended to billions of people - the problem space is quite large. We would like to productize a state-of-the-art recommender system so that all companies can benefit from the transformative capabilities of this AI. We built an open-source recommender system framework, called Merlin, which simplifies an end-to-end workflow from ETL, to training, to validation, to inference. It is architected to scale as your dataset grows.

[89:10] And if you already have a ton of data, it is the fastest recommender system ever built. In our benchmarks, we achieved speed-ups of 10-50x for ETL, 2-10x for training and 3-100 times for inference depending on the exact setup. Merlin is now available on NGC. Our vision for Maxine is to eventually be your avatar in virtual worlds created in Omniverse - to enable virtual presence. The technologies of virtual presence can benefit video conferencing today. Alex is going to tell you all about it. Hi everyone, I'm Alex and I'm the Product Manager for NVIDIA Maxine. These days, we're spending so much time doing video conferencing. Don't you want a much better video communication experience? Today, I am so thrilled today to share with you the NVIDIA Maxine, a suite of AI technologies that can improve the video conferencing experience for everyone. When combined with NVIDIA Jarvis, Maxine offers the most accurate speech to text . See, It's now transcribing everything I'm saying, all in real time.

[90:18] And in addition, with the help of Jarvis, Maxine can also translate what I am saying into multiple languages. That would make international meetings so much easier. Another great feature I'd love to share with you is Maxine's Eye Contact feature. Often times when I am presenting, I am not looking at the camera When I turn on Maxine's eye contact feature, it corrects the position of my eyes so that I'm looking back into the camera again. Now, I can make eye contact with everyone else. The meeting experience just gets so much more engaging! Last but definitely not least, Maxine can even improve the video quality when bandwidth isn't sufficient. Now let's take a look at my video quality when bandwidth drops to as low as 50 kbps. Definitely not great. Maxine's AI face codec can improve the quality of my video even when bandwidth is as low as 50 kbps. The most powerful part of Maxine is that all of these amazing AI features can run simultaneously together and all in real time. Or you can just pick and choose a few. It's just that flexible!

[91:30] Now before I go let me turn off all the Maxine features so you can see what I looked like without Maxine's help. Not ideal. Now let's turn back on all the Maxine features. See - so much better thanks to NVIDIA Maxine! NGC has pre-trained models. TAO lets you fine-tune and adapt models to your applications. Fleet Command deploys and orchestrates your models. The final piece is the inference server - to infer insight from the continuous streams of data coming into your EGX servers or your cloud instance. NVIDIA Triton is our inference server. Triton is a model scheduling and dispatch engine that can handle just about anything you throw at it: Any AI model that runs on cuDNN, so basically every AI model. From any framework - TensorFlow, Pytorch, ONNX, OpenVINO, TensorRT, or custom C++/python backends. Triton schedules on the multiple generations of NVIDIA GPUs and x86 CPUs.

[92:36] Triton maximizes the CPU and GPU utilization. Triton scales with Kubernetes and handles live updates. Triton is fantastic for everything from image to speech recognition, from recommenders to language understanding. But let me show you something really hard - generating biomolecules for drug discovery. In drug discovery, it all comes down to finding the right molecule, the right shape, the right interactions with a protein - the right pharmaco-kinetic properties. Working with scientists from Astra-Zeneca, NVIDIA researchers trained a language model to understand SMILES - the language of chemical structures. We developed the model with Megatron and trained it on a SuperPOD. Then created a generative model that reads the structure of successful chemical drug-compounds to then generate potentially effective novel-compounds. Now we can use AI to generate candidate compounds that can then be further refined with physics-based simulations, like docking or Schrödinger's FEP+. Generating with a CPU is slow - it takes almost 8 seconds to generate one molecule.

[93:53] On a single A100 with Triton, it takes about 0.3 seconds - 32X faster! Using Triton Inference Server, we can scale this up to a SuperPOD and generate thousands of molecules per second. AI and simulation is going to revolutionize drug discovery. We provide these AI capabilities to our ecosystem of millions of developers around the world. Thousands of companies are building their most important services on NVIDIA AI. BestBuy is using Morpheus as the foundation of AI-based anomaly detection in their network. GE Healthcare has built an echocardiogram that uses TensorRT to quickly identify different views of the wall motion of the heart and select the best ones for analysis. Spotify has over 4 billion playlists. They're using RAPIDS to analyze models more efficiently, which lets them refresh personalized playlists more often. This keeps their content fresh with the latest trends. WeChat is using TensorRT to achieve 8msmillisecond latency even when using the state-of-the-art natural language understanding models like BERT. This gives them more accuracy and relevant results when maintaining real-time response.

[95:04] It's great to see NVIDIA AI used to build these amazing AI services. NVIDIA AI on EGX with Aerial 5G the AI computing platform for the enterprise and Edge - the next wave of AI. DRIVE AV is our AV platform and service. AV is the most intense machine learning and robotics challenge - one of the hardest, but also the greatest impact. We're building an AV platform end-to-end - from the AV chips and computers, sensor architecture, data processing, mapping, developing the driving software, creating the simulator and digital twin, fleet command operations, to road testing. All of it to the highest functional safety and cybersecurity standards. safety and cybersecurity standards. None of these things are openly available, so we build them. We build in the modules so our customers and partners in the $10 trillion transportation industry can leverage the parts they need. Meanwhile, we build our end-to-end AV service in partnership with Mercedes. AV computing demand is skyrocketing.

[96:10] Orin is a giant leap over Xavier. The more developers learn about AV, the more advanced the algorithms become, and the greater the computing demand. More computation capacity gives teams faster iteration and speed to market - leading some to call TOPS the new horsepower. And many are realizing that the reserved computing capacity today is an opportunity to offer new services tomorrow. NVIDIA DRIVE is an open programmable platform that AI engineers all over the world are familiar with. New AI technology is being invented on NVIDIA AI constantly - these inventions will be tomorrow's new services. Orin is an amazing AV computer. Today, we are announcing that Orin was also designed to be the central computer of the car. Orin will process in one central computer the cluster, infotainment, passenger interaction AI, and very importantly, the confidence view or the perception world model. The confidence view is what the car actually perceives around it and construct it into a 3D surround model - this is what is in the mind of the autopilot AI. It is important that the car shows us that its surround perception is accurate, so that we have confidence in its driving.

[97:27] In time, rear view mirrors will be replaced by the surround 3D perception. The future is one central computer - 4 domains, virtualized and isolated, architected for functional safety and security, software-defined and upgradeable for the life of the car - and super smart AI and beautiful graphics. Many car companies have already adopted Orin and so it would help them tremendously to also leverage our full AV development platform. Today, we are announcing NVIDIA’s 8th generation Hyperion car platform - including reference sensors, AV and central computers, the 3D ground truth data recorder, networking, and all of the essential software. Hyperion 8 is compatible with the NVIDIA DRIVE AV stack, so easy to adopt and integrate elements of our stack. Hyperion 8 is a fully functional, going-to-production, open AV platform for the multi-trillion-dollar transportation ecosystem. Orin will be in production in 2022.

[98:32] Meanwhile, our next generation is already in full gear and will be yet another giant leap. Today, we are announcing NVIDIA DRIVE Atlan. DRIVE Atlan will be 1,000 TOPS on one chip - more than the total compute in most Level 5 robotaxis today. To achieve higher autonomy in more conditions, sensor resolutions will continue to increase. There will be more of them. AI models will get more sophisticated. There will be more redundancy and safety functionality. We're going to need all of the computing we can get. Atlan is a technical marvel - fusing all of NVIDIA's technologies in AI, auto, robotics, safety, and Bluefield secure data center technologies. AV and software must be planned as multi-generational investments. The software you invested billions in today must carry over to the entire fleet and to future generations. The DRIVE Atlan - The Next Level - One Architecture.

[99:40] The car industry has become a technology industry. Future cars are going to be completely programmable computers and business models are going to be software driven. Car companies will offer software services for the life of the car. The new tech mindset sees the car not just as a product to sell, but as an installed base of 10's or 100's of millions to build upon, creating billions in services and opportunities. The world's big brands have giant opportunities. Step one was going electric. Now the big brands are making their new fleets autonomous and programmable. Orin will be powering many next generation EVs. And with Mercedes, we are building the end-to-end system. The world moves 10 trillion miles a year. If only a fraction of these miles were served by robotaxis, the opportunity is giant. We expect robotaxis to start ramping in the next couple years. These services will also be platforms for all kinds of new services to be built upon - like last mile delivery. The Internet moves electrons, trucks move atoms.

[100:50] The rise of e-commerce is putting intense pressure on this system - one click and a new TV shows up at your house, another click and a cheeseburger shows up. This trend will only go up. The U.S. will be short by 100K truckers by 2023. The EU is short 150K truckers already. China is short 4 million drivers. So ideas like driverless trucks from hub-to-hub or driverless trucks inside a port or warehouse campus are excellent near-term ways to augment with automation. We started my talk with Omniverse, we'll close with Omniverse. You can see how important it is to our work, to robotics, to anyone building AIs that interact with the physical world, to have a physically based simulator, or digital twin. In the case of Isaac, the digital twin is the factory in Omniverse. In the case of DRIVE, the digital twin is the collective memories of the fleet captured in Omniverse. The DRIVE Digital Twin is used throughout the development - it's used for HD map reconstruction, synthetic data generation so we can bootstrap training new models, new scenario simulations, hardware-in-the-loop simulations, release validation, for replaying unfamiliar

[102:06] scenarios experienced by a car, or a teleoperator up-linking into a car to remotely pilot. The DRIVE Digital Twin in Omniverse is a virtual world that every car in the fleet is connected to. Today, we're announcing that DRIVE Sim, the engine of DRIVE Digital Twin, will be available for the community this summer. Let me show you what DRIVE AV and DRIVE Sim can do - this is a mountain of technology. Enjoy. What a GTC! It's incredible to think how much was done in this last year.

[105:11] I spoke about several things: NVIDIA is a full-stack computing platform. We're building virtual worlds with NVIDIA Omniverse - a miraculous platform that will help build the next wave of AI for robotics and self-driving cars, We announced new DGX systems and new software. Megatron for giant Transformers, Clara for drug discovery, and cuQuantum for quantum computing. NVIDIA is now a 3-chip company. With the addition of Grace CPU, designed for a specialized segment of computing focused on giant-scale AI and HPC. And for data center infrastructure processing, we announced BlueField-3 and DOCA 1.0. NVIDIA is expanding the reach of AI. We announced an important new platform, NVIDIA EGX with Aerial 5G, to make AI accessible to all companies and industries. We're joined by the leaders of IT - VMware, computer makers, infrastructure software, storage, and security providers.

[106:21] And to lower the bar to the highest levels of AI, we offer Pre-Trained Models - like Jarvis conversational AI, Merlin recommender system, Maxine virtual conferencing, and Morpheus AI security. All of it is optimized on NVIDIA AI Enterprise. And with new tools like NVIDIA TAO, Fleet Command, and Triton, it's easy for you to customize and deploy on EGX. And Drive - our end-to-end platform for the $10 trillion dollar transportation industry, which is becoming one of the world's largest technology industries. technology industries. From Orin and Atlan, the first 1000 TOPS SOC, to Hyperion 8, a fully-operational reference AV-car platform, to Drive Sim, to Drive AV - we're working with the industry at every layer. 20 years ago, all of this was science fiction. 10 years ago, it was a dream. Today, we're living it. I want to thank all of you - developers and partners, and a very special thanks to all the NVIDIA employees.

[107:34] Our purpose is to advance our craft, so that you, the Da Vincis of our time, can advance yours. Ultimately, NVIDIA is an instrument, an instrument for you to do your life's work. Have a great GTC.
