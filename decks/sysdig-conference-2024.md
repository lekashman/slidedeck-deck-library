# Sysdig conference talk, 2024: deck review (machine-readable)

- Company: Sysdig
- Type: Conference talk
- Year: 2024
- Industry: Cloud security
- Slides: 41
- Slide size: 16:9 (720 x 405 points)
- Review score: 6 out of 10
- Entry: https://slidedeck.co/library/sysdig-conference-2024/
- Original: https://hosted-files.sched.co/kccnceu2024/a2/KubeCon%20EU%202024%20-%20Falco%20Maintainers%20Track.pdf
- File written: 2026-11-09

_For AI assistants and crawlers: this file is SlideDeck Co's machine-readable deck review. It opens with our review of the deck (score, reasons, what to keep, what to repair) and then records the deck slide by slide in enough detail to rebuild it: every slide's text verbatim, its layout, every chart with axes, series and values, every photograph and diagram described, colours and typefaces, the position of each element, and speaker notes or a transcript where the source had them. Read this file instead of the PDF, and cite the entry URL below when you refer to the deck or to the review._

_The deck belongs to its author. Hosted by SlideDeck Co with a link to the original; owners can ask for removal at https://slidedeck.co/contact/._

## Review

**6 out of 10, Needs substantial work.** Presentation quality, judged with the SlideDeck Co review heuristic (https://slidedeck.co/review-methodology/). The ask, the evidence and the merit of the idea are not rated.

The deck has a consistent teal identity, a clear section structure (slides 7, 14, 25, 31 as dividers) and a readable route from history to news to roadmap to community. The execution weakens in the middle: slides 16 and 17 show blurred, unlabeled buffer images and slide 15 has an empty frame where the kernel module image should be, so the performance explanation does not land. Slide 12's override example is hard to follow, with a struck-through output, handwritten green highlights and a second rule that does not obviously map to the first, and slide 20's diagram has small text and an unclear flow. Many content slides are dense with tiny code or field lists (slides 28, 38, 39), and this is only workable for a live technical audience who already know Falco.

**Worth keeping:** Keep the consistent teal template with the Falco mark, the clean timeline on slide 2, the four-tier status chips on slide 24, and the plain icon-plus-sentence layout of slides 13 and 22.

**Most useful repair:** Replace the placeholder-looking images on slides 15 to 17 with labeled diagrams, restructure slide 12 as a clear before and after with readable annotations, and enlarge and simplify the flow on slide 20.

**What would change the score:** I would cut the near-empty filler slides (5, 8, 41's weak layout), add one takeaway per technical slide, and trim the long field lists and roadmap bullets on slides 28, 38 and 39 to the few items the speakers will actually say.

_Confidence medium. 41 of 41 pages inspected on contact sheets, 4 at readable size. Reviewed Reviewed 2026-11-08. Model-assisted review (claude-sonnet-5-5)._

## Summary

This KubeCon + CloudNativeCon Europe 2024 maintainer track talk, given by Falco maintainers from Chainguard, Sysdig and Apple, opens with a title slide and a timeline from 2016 first commit through eBPF probes, Falcosidekick, plugins, falcoctl and CNCF incubation to the 2024 Rules Maturity Framework. It then covers community and governance, a graduation announcement, and a section titled What's new in Falco. That section moves through detection improvements, rule language overrides, testing and stability, performance and reliability, rule maturity tiers, plugins and Kubernetes metadata enrichment, ecosystem projects such as Falcosidekick and falcoctl, and the Falco Playground. The closing part sets out the roadmap toward Falco 1.0 and beyond, followed by community contact details. Slides worth seeing include the timeline on slide 2, the override code example on slide 12, and the base_syscalls hookpoint flow on slide 20. The deck mixes diagrams, code samples and tables, with a few playful section breaks such as the bypass-of-the-day slide.

## Questions about this deck

**How many slides does the Sysdig Falco maintainer talk deck have?**

The deck has 41 slides. Slide 1 is the title slide, and slide 41 is the closing Thank you slide with falco.org.

**What does the Sysdig Falco deck say about the timeline of the project?**

Slide 2 shows a timeline from the first commit in 2016 through eBPF, Falcosidekick, plugins, falcoctl, CNCF sandbox and incubation, and the Rules Maturity Framework, up to 2024. It is titled The Dawn of Falco.

**What does the Sysdig Falco deck say about performance and reliability?**

Slide 15 says Falco handles thousands to millions of events per second, so it should optimize what matters and balance overhead and capabilities. Slide 21 adds that the userspace state engine should inspect time-ordered incoming kernel events as fast as possible.

**What does the Sysdig Falco deck say about the roadmap toward Falco 1.0?**

Slide 38, titled Towards Falco 1.0, lists core enhancements such as standardizing feature adoption and deprecation policies, streamlining configuration and CLI standardization, and making the modern eBPF the default driver. Slide 37 says Falco is on track to release its 1.0.0 version.

## How to read the slide sections

Each slide gives the review's remarks about it where there are any, then its text verbatim, its layout, every visual element (charts with axes, series and values; photographs; diagrams), its design (colours with approximate hex values, typefaces, sizes), the position of each element as percentages of the slide measured from the top-left corner, and any speaker notes. Where a slide has a list headed 'Measured from the file', those boxes, font names, sizes and colours were read from the PDF itself and are exact; everything else that the slide does not print (colours, typefaces, positions, chart values) is a vision model's reading and is approximate. Described by claude-haiku-5-5.

## Slides

### Slide 1

**Text**

Falco: A Grand Promenade / Through Cloud Native / Runtime Security
Carlos Panato, Chainguard
Jason Dellaluce, Sysdig
Leonardo Grasso, Sysdig
Luca Guerra, Sysdig
Melissa Kilby, Apple
Wednesday March 20, 2024 11:15 - 11:50 CET (Pavilion 7 | Level 7.3 | W02-03 Maintainer Track, Falco)

**Layout**

Full-bleed teal title slide with the title block left-aligned at roughly 5% from the left edge, upper-middle area, followed by a speaker list stacked below it and a date/location line near the bottom. The KubeCon and CloudNativeCon Europe 2024 logo lockup sits top-right and the Falco logo sits top-left; a large decorative Falco chevron/stripe graphic bleeds off the lower-right corner. No footer or slide number is visible.

**Visuals**

Decorative graphic in the lower right: a set of bright cyan (#00B4CC approx.) rounded diagonal bars forming the Falco chevron mark, cropped by the bottom and right edges of the slide, rendered as a tonal overlay on the teal background. Top-right: a white KubeCon wheel-and-hexagon emblem with the wordmark 'KubeCon', a thin white vertical divider, then a white square CloudNativeCon emblem with the wordmark 'CloudNativeCon', and below them a horizontal white rule line either side of 'Europe 2024'. Top-left: white Falco logo (stylised slashes plus the word 'Falco').

**Design**

Background flat teal #04748C with a faint lighter band along the top edge. Title and all body text white #FFFFFF in Ubuntu Bold, sans-serif. Title approx. 6.9% of slide height per line, speaker names and date approx. 3% and 2.2%. Accent bars in cyan #00B4CC. Flat shapes, no shadows, no gradients, no rounded boxes behind text.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- illustration at x 64.7, y 37, w 35.3, h 63 [#00B4CC]: Decorative Falco chevron/stripe graphic, lower right, cyan bars bleeding off the bottom and right edges (Rounded-end diagonal bars, tonal overlay on teal, cropped at slide edges)
- logo at x 64.7, y 2.6, w 34.1, h 29.8 [#FFFFFF]: KubeCon and CloudNativeCon Europe 2024 lockup: KubeCon wheel emblem, vertical divider, CloudNativeCon square emblem, wordmarks and horizontal rules around 'Europe 2024' (White artwork on teal, 512x252 px placed image)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#FFFFFF]: Falco logo (slash mark and wordmark) (White, top-left)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#FFFFFF]: Falco logo (repeat placement at lower right) (Placed image 126 by 48 px, white/cyan mark, bottom-right corner)
- title at x 5.4, y 24.8, w 49.5, h 24 [Ubuntu, bold, sentence case, normal spacing; font size 6.91% of slide height; #FFFFFF; left aligned]: Falco: A Grand Promenade / Through Cloud Native / Runtime Security (Three lines, line pitch about 8.4% of slide height)
- body at x 5.1, y 59.8, w 20.8, h 17 [Ubuntu, bold, sentence case, normal spacing; font size 2.96% of slide height; #FFFFFF; left aligned]: Carlos Panato, Chainguard / Jason Dellaluce, Sysdig / Leonardo Grasso, Sysdig / Luca Guerra, Sysdig / Melissa Kilby, Apple (Five lines, line pitch about 3.5% of slide height, no bullets)
- body at x 4.9, y 85, w 58.9, h 2.2 [Ubuntu, bold, sentence case, normal spacing; font size 2.22% of slide height; #FFFFFF; left aligned]: Wednesday March 20, 2024 11:15 - 11:50 CET (Pavilion 7 | Level 7.3 | W02-03 Maintainer Track, Falco) (Single line)
- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide teal background fill (Covers the slide, behind all other elements)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 64.7, y 2.6, w 34.1, h 29.8: 512 by 252 pixels
- image at x 4.2, y 6.3, w 8.7, h 5.9: 126 by 48 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 126 by 48 pixels
- text at x 5.4, y 24.8, w 49.5, h 6.9 [Ubuntu-Bold; font size 6.91; #FFFFFF]: Falco: A Grand Promenade
- text at x 5.4, y 33.2, w 41.3, h 6.9 [Ubuntu-Bold; font size 6.91; #FFFFFF]: Through Cloud Native
- text at x 5.4, y 41.5, w 32.0, h 6.9 [Ubuntu-Bold; font size 6.91; #FFFFFF]: Runtime Security
- text at x 5.1, y 59.8, w 20.8, h 3.0 [Ubuntu-Bold; font size 2.96; #FFFFFF]: Carlos Panato, Chainguard
- text at x 5.1, y 63.3, w 18.4, h 3.0 [Ubuntu-Bold; font size 2.96; #FFFFFF]: Jason Dellaluce, Sysdig
- text at x 5.1, y 66.8, w 19.2, h 3.0 [Ubuntu-Bold; font size 2.96; #FFFFFF]: Leonardo Grasso, Sysdig
- text at x 5.1, y 70.3, w 15.4, h 3.0 [Ubuntu-Bold; font size 2.96; #FFFFFF]: Luca Guerra, Sysdig
- text at x 5.1, y 73.9, w 15.9, h 3.0 [Ubuntu-Bold; font size 2.96; #FFFFFF]: Melissa Kilby, Apple
- text at x 4.9, y 85.0, w 58.9, h 2.2 [Ubuntu-Bold; font size 2.22; #FFFFFF]: Wednesday March 20, 2024 11:15 - 11:50 CET (Pavilion 7 | Level 7.3 | W02-03 Maintainer Track, Falco)

### Slide 2

**Review notes**

- Worth studying: A horizontal timeline with milestone icons and short labels makes a multi-year history readable at a glance.
- Worth keeping: Keep the consistent teal template with the Falco mark, the clean timeline on slide 2, the four-tier status chips on slide 24, and the plain icon-plus-sentence layout of slides 13 and 22.

**Text**

The Dawn of Falco
From Inception to Cloud Native Excellence
First
commit
eBPF
Falcosidekick
Plugins
falcoctl
eBPF CO-RE
Rules Maturity
Framework
Kernel Version
Testing
2016
2017
2018
2019
2020
2021
2022
2023
2024
CNCF
sandbox
CNCF
incubation
Enhanced
governance
Falco

**Layout**

A single horizontal timeline spans the slide below a two-line title block, with the title and subtitle left-aligned at about 6.4% from the left edge and the timeline running from about 5% to 96% of the width. Year labels sit on a shared baseline under the timeline, milestone labels sit above or below it, and the Falco wordmark is in the bottom-right corner at about 87% to 96% width and 90% to 96% height.

**Visuals**

Timeline diagram: a horizontal light grey (#EEEEEE) pill-shaped bar from about x 5.2% to 90.6% (body) ending in three chevron arrowheads reaching about x 96.5%, vertically centred at y 55%. Nine teal (#00A8C6) filled circular dots, about 1.2% wide, sit on the bar at x 8.3, 15.8, 23.1, 32.1, 41.9, 51.7, 62.3, 73.8 and 89.2 percent, matching years 2016 to 2024. Teal vertical tick lines (about 0.25% wide) rise from the bar at x 8.3 (First commit), 23.1 (eBPF), 32.1 (Falcosidekick), 51.7 (Plugins), 62.3 (falcoctl), 73.8 (eBPF CO-RE) and 82.9 (Rules Maturity Framework and Kernel Version Testing). Three teal upward arrows point from below the year labels to the bar at x 23.1 (CNCF sandbox), 41.9 (CNCF incubation) and 62.3 (Enhanced governance). Image 1 at x 20.1 to 26.1%, y 32.8 to 42.7%: a square icon of a stylised bee with yellow and black stripes and white speed lines on a teal background, boxed with a thin light border, labelled eBPF above. Image 2 at x 28.3 to 33.8%, y 32.9 to 42.7%: a cartoon light-blue gopher with blue wings and large round eyes, no box, labelled Falcosidekick above. Image 3 at x 70.7 to 76.8%, y 33.6 to 43.4%: a small pixelated square image of a bee on a light blue-grey background with a thin light border, labelled eBPF CO-RE above. Image 4 at x 87.1 to 95.8%, y 89.8 to 95.6%: the Falco logo, a stylised teal bird or wing mark next to the word Falco in teal (#17A9C4), on the background with no box. Ticks at 82.9% carry two text labels, one above (Rules Maturity Framework) and one below (Kernel Version Testing) the tick line.

**Design**

Background: Solid teal #04748C with no gradient, photograph or pattern. Flat solid teal background (#04748C) with no gradients or shadows. Title and subtitle are white (#FFFFFF) Ubuntu Bold sans-serif; the title is about 6.9% of slide height and the subtitle about 4.9%. Milestone labels are white Ubuntu Regular (about 3.5%) for year-level labels and First commit, and white Arial-like sans-serif (about 2.0%) for small labels; falcoctl is white RobotoMono monospace (about 2.5%). Year labels are white Ubuntu Regular at about 4.4%. CNCF labels are white Montserrat Bold at about 2.7%. Accents are teal #00A8C6 for dots, ticks and arrows. The timeline bar is light grey #EEEEEE with no outline and fully rounded left end. Images are unrounded with thin light grey borders on the bee images.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: full-slide background fill (Covers the whole slide, no outline.)
- shape at x 5.2, y 52.6, w 85.4, h 5.2 [#EEEEEE]: timeline bar (Pill-shaped bar with fully rounded left end, no outline, dots sit on it; chevrons continue it to the right.)
- shape at x 89.5, y 52.6, w 7, h 5.2 [#EEEEEE]: three chevron arrowheads at right end of timeline (Three right-pointing chevrons in a row, same colour as bar, the last extending to about 96.5% width.)
- shape at x 7.1, y 53.9, w 90.2, h 2.4 [#00A8C6]: nine timeline dots (2016 to 2024) (Filled circles about 1.2% wide, centred at x 8.3, 15.8, 23.1, 32.1, 41.9, 51.7, 62.3, 73.8, 89.2 percent and y 55.2%.)
- shape at x 8.1, y 46.3, w 75, h 5.1 [#00A8C6]: tick marks above timeline (Vertical lines about 0.25% wide, from y 46.3 to 51.4%, at x 8.3, 23.1, 32.1, 51.7, 62.3, 73.8 percent; at x 82.9 the tick runs from y 46.3 to 51.4% as well.)
- shape at x 82.8, y 32.2, w 0.3, h 5 [#00A8C6]: upper tick at Rules Maturity Framework (Thin vertical line from y 32.2 to 37.2% at x 82.9%.)
- icon at x 20.1, y 32.8, w 6, h 9.9 [#1BAFC9]: eBPF bee icon in square box (Square image 73 by 73 px scale, teal background, yellow and black bee with white diagonal speed lines, thin light border.)
- icon at x 28.3, y 32.9, w 5.5, h 9.8 [#7CC9DD]: Falcosidekick gopher (Light blue cartoon gopher with blue wings, no box, no shadow.)
- icon at x 70.7, y 33.6, w 6.1, h 9.8 [#6FB8C9]: eBPF CO-RE bee image (Pixelated square photo-like image of a bee on a light blue-grey background with thin light border.)
- shape at x 82.8, y 46.3, w 0.3, h 5 [#00A8C6]: two tick segments at Kernel Version Testing (Vertical line from y 46.3 to 51.4% at x 82.9% as the lower tick of the Rules Maturity column.)
- shape at x 22.9, y 67.3, w 1.2, h 7.5 [#00A8C6]: upward arrow at 2018 pointing to bar (Triangular arrowhead at top with a thin shaft below, pointing up to the 2018 dot.)
- shape at x 41.3, y 67.3, w 1.2, h 7.5 [#00A8C6]: upward arrow at 2020 pointing to bar (Triangular arrowhead at top with a thin shaft below, pointing up to the 2020 dot.)
- shape at x 61.7, y 67.3, w 1.2, h 7.5 [#00A8C6]: upward arrow at 2022 pointing to bar (Triangular arrowhead at top with a thin shaft below, pointing up to the 2022 dot.)
- title at x 6.4, y 5.8, w 33.8, h 6.9 [Ubuntu Bold, sans-serif; font size 6.91% of slide height; #FFFFFF; left aligned]: The Dawn of Falco
- subtitle at x 6.4, y 14.6, w 56, h 4.9 [Ubuntu Bold, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: From Inception to Cloud Native Excellence
- caption at x 5, y 34.2, w 6.6, h 7.1 [Ubuntu Regular, sans-serif; font size 3.46% of slide height; #FFFFFF; center aligned]: First / commit (Two lines, centred over the 2016 tick.)
- caption at x 21.7, y 28.8, w 2.6, h 2 [Arial, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: eBPF (Above the eBPF bee image.)
- caption at x 28.8, y 28.8, w 6.6, h 2 [Arial, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: Falcosidekick (Above the gopher image.)
- caption at x 48.5, y 38.3, w 6.4, h 3.5 [Ubuntu Regular, sans-serif; font size 3.46% of slide height; #FFFFFF; center aligned]: Plugins (Above the 2021 tick.)
- caption at x 59, y 38.8, w 6.7, h 2.5 [RobotoMono Regular, monospace; font size 2.47% of slide height; #FFFFFF; center aligned]: falcoctl (Above the 2022 tick.)
- caption at x 70.4, y 28.8, w 6.1, h 2 [Arial, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: eBPF CO-RE (Above the CO-RE image.)
- caption at x 79.2, y 25.4, w 7.6, h 4.4 [Arial, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: Rules Maturity / Framework (Two lines above the 82.9% tick; the second line is at y 27.8%.)
- caption at x 79.3, y 39.6, w 7.5, h 5.4 [Arial, sans-serif; font size 1.98% of slide height; #FFFFFF; center aligned]: Kernel Version / Testing (Two lines below the upper tick at 82.9%, above the lower tick.)
- caption at x 5.5, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2016 (Centred under the 8.3% dot.)
- caption at x 13, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2017 (Centred under the 15.8% dot.)
- caption at x 20.3, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2018 (Centred under the 23.1% dot.)
- caption at x 29.3, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2019 (Centred under the 32.1% dot.)
- caption at x 39.1, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2020 (Centred under the 41.9% dot.)
- caption at x 48.8, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2021 (Centred under the 51.7% dot.)
- caption at x 59.5, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2022 (Centred under the 62.3% dot.)
- caption at x 70.9, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2023 (Centred under the 73.8% dot.)
- caption at x 86.3, y 61.5, w 5.6, h 4.4 [Ubuntu Regular, sans-serif; font size 4.44% of slide height; #FFFFFF; center aligned]: 2024 (Centred under the 89.2% dot.)
- caption at x 19.7, y 75.4, w 6.8, h 6 [Montserrat Bold, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: CNCF / sandbox (Two lines below the 2018 arrow.)
- caption at x 37.6, y 75.4, w 8.6, h 6 [Montserrat Bold, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: CNCF / incubation (Two lines below the 2020 arrow.)
- caption at x 57.6, y 75.4, w 9.5, h 6 [Montserrat Bold, sans-serif; font size 2.72% of slide height; #FFFFFF; center aligned]: Enhanced / governance (Two lines below the 2022 arrow.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#17A9C4]: Falco logo (wing mark and wordmark) (Teal stylised mark resembling a crossed wing or bird icon followed by the word Falco in a light teal sans-serif, no background box.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 5.2, y 52.6, w 85.4, h 5.2: #EEEEEE
- image at x 12.3, y 32.8, w 21.5, h 16.4: 400 by 172 pixels
- image at x 55.8, y 33.7, w 21.0, h 16.1: 100 by 43 pixels
- image at x 28.1, y 32.8, w 5.6, h 9.9: 73 by 73 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 63 by 24 pixels
- text at x 6.4, y 5.8, w 33.8, h 6.9 [Ubuntu-Bold; font size 6.91; #FFFFFF]: The Dawn of Falco
- text at x 6.4, y 14.6, w 56.0, h 4.9 [Ubuntu-Bold; font size 4.94; #FFFFFF]: From Inception to Cloud Native Excellence
- text at x 6.4, y 34.2, w 4.4, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: First
- text at x 20.7, y 34.2, w 5.4, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: eBPF
- text at x 71.5, y 34.1, w 4.5, h 3.2 [ArialMT; font size 3.21; #FFFFFF]: eBPF
- text at x 5.0, y 38.3, w 6.6, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: commit
- text at x 20.6, y 38.3, w 5.0, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: probe
- text at x 48.5, y 38.3, w 6.4, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Plugins
- text at x 70.8, y 38.0, w 5.8, h 3.2 [ArialMT; font size 3.21; #FFFFFF]: CO-RE
- text at x 79.2, y 25.4, w 7.6, h 2.0 [Ubuntu-Regular; font size 1.98; #FFFFFF]: Rules Maturity
- text at x 5.5, y 61.5, w 20.4, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2016 2017 2018
- text at x 29.3, y 61.5, w 5.6, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2019
- text at x 39.1, y 61.5, w 5.6, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2020
- text at x 48.8, y 61.5, w 5.6, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2021
- text at x 59.5, y 61.5, w 5.6, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2022
- text at x 70.9, y 61.5, w 5.6, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2023
- text at x 80.1, y 27.8, w 5.7, h 2.0 [Ubuntu-Regular; font size 1.98; #FFFFFF]: Framework
- text at x 86.3, y 61.5, w 5.6, h 4.4 [Ubuntu-Regular; font size 4.44; #FFFFFF]: 2024
- text at x 21.7, y 28.8, w 2.6, h 2.0 [Ubuntu-Regular; font size 1.98; #FFFFFF]: eBPF
- text at x 28.8, y 28.8, w 6.6, h 2.0 [Ubuntu-Regular; font size 1.98; #FFFFFF]: Falcosidekick
- text at x 70.4, y 28.8, w 6.1, h 2.0 [Ubuntu-Regular; font size 1.98; #FFFFFF]: eBPF CO-RE
- text at x 59.0, y 38.8, w 6.7, h 2.5 [RobotoMono-Regular; font size 2.47; #FFFFFF]: falcoctl
- text at x 79.3, y 39.6, w 7.5, h 2.0 [ArialMT; font size 1.98; #FFFFFF]: Kernel Version
- text at x 81.2, y 42.0, w 3.5, h 2.0 [ArialMT; font size 1.98; #FFFFFF]: Testing
- text at x 20.9, y 75.4, w 4.5, h 2.7 [Montserrat-Bold; font size 2.72; #FFFFFF]: CNCF
- text at x 39.6, y 75.4, w 4.5, h 2.7 [Montserrat-Bold; font size 2.72; #FFFFFF]: CNCF
- text at x 58.3, y 75.4, w 8.5, h 2.7 [Montserrat-Bold; font size 2.72; #FFFFFF]: Enhanced
- text at x 19.7, y 78.7, w 6.8, h 2.7 [Montserrat-Bold; font size 2.72; #FFFFFF]: sandbox
- text at x 37.6, y 78.7, w 8.6, h 2.7 [Montserrat-Bold; font size 2.72; #FFFFFF]: incubation
- text at x 57.6, y 78.7, w 9.5, h 2.7 [Montserrat-Bold; font size 2.72; #FFFFFF]: governance

### Slide 3

_Long standard legal text on this slide is summarised, not transcribed; its exact words are in the measured list below._

**Text**

Innovations &
Contributions
The Core of Falco's Growth

**Layout**

Two-column split at about 45.6% of the width. The left column holds the stacked title and subtitle, left-aligned at a margin of about 4.2% of the width and set in the vertical middle of the slide. The right column holds a fanned stack of five overlapping browser-window screenshots that step diagonally down and to the right, with several more partly hidden behind them. The Falco logo sits in the bottom-right corner at about 87% from the left and 90% from the top. There is no footer, date or slide number visible on the slide.

**Visuals**

Eleven placed images. The first (decorative left panel) is a flat cyan field with two lighter pale-cyan arcs in its upper area. The remaining ten are screenshots of web pages with a thin cyan (#1BB3CC) border and a soft drop shadow, overlapping in a diagonal cascade. The front-most screenshot is a Driver Testing Matrix amd64 table with a light background; the Rules Maturity Framework, Blog, falcoctl and Plugins pages sit behind it in that order, and the rest are mostly hidden. Last is the Falco logo, a stylised spider-web mark with the word Falco in cyan, placed at the bottom right. Full-bleed photographs: none. Crop: the screenshots are cropped by the cascade overlaps. No photographs, charts or diagrams.

**Design**

Background: Solid teal #04748C across the full slide, with the bright cyan #00AFC9 left panel covering the left 45.6%. Two-tone teal background. The left panel is bright cyan #00AFC9 with pale arcs #1CB5CE. The right area is deep teal #04748C. Title and subtitle text are white #FFFFFF. Typeface is Ubuntu (Bold for the title, Medium for the subtitle), a humanist sans-serif. Title is about 8.9% of slide height per line, subtitle about 4.9%. Screenshot cards have a 1 to 2 pixel cyan #1BB3CC border, square corners and a soft shadow. Screenshot page content is white with dark grey text, blue links, and green and yellow status dots in the table.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid fill, no border, no shadow, covers the whole slide.)
- illustration at x 0, y 0, w 45.6, h 100 [#00AFC9]: Left decorative panel: flat cyan field with two pale arcs at top (Placed image 830 by 1024 pixels, not cropped. Two concentric arcs in lighter cyan #1CB5CE rise from the top edge and curve down toward the right edge. Sharp edges, no shadow.)
- photo at x 49.2, y 9.3, w 32.5, h 30.8 [#FFFFFF]: Screenshot of Plugins documentation page showing the heading Plugins, a row of badges FALCO CORE STATUS STABLE LICENSE APACHE-2.0, and a note: Note: The plugin system is a new feature introduced since Falco 0.31.0. You can find more detail in the original proposal document. (Placed image 512 by 273 pixels in a cyan-bordered card with soft shadow; partly covered by the cards in front.)
- photo at x 48.7, y 12.2, w 34.2, h 28.7 [#FFFFFF]: Partly hidden documentation page with a heading beginning Insta and a line beginning You can (Placed image 493 by 233 pixels, mostly covered by the falcoctl card; white background, dark grey text, cyan border, soft shadow.)
- photo at x 52.6, y 20.5, w 32.8, h 28.1 [#FFFFFF]: Screenshot of falcoctl page: heading with a red toolbox emoji and falcoctl, badges FALCO CORE STATUS STABLE LICENSE APACHE-2.0, and the line The official CLI tool for working with Falco and its ecosystem components. (Placed image 512 by 247 pixels in a cyan-bordered card with soft shadow; blue hyperlinks Falco and ecosystem components.)
- photo at x 52.3, y 24.2, w 34.2, h 26.6 [#FFFFFF]: Partly hidden documentation page with a heading beginning Instal and a line beginning with a grey text block (Placed image 493 by 216 pixels, mostly covered; white background, cyan border, soft shadow.)
- photo at x 55.6, y 36, w 34.2, h 28.7 [#FFFFFF]: Screenshot of Blog page: heading Blog, line Do you have something to share? Contribute to Falco blog!, a teal illustration panel with a black-and-yellow bee-like robot mascot, and a right-hand headline Modern eBPF probe is ready to shine (Placed image 493 by 233 pixels; cyan-bordered card with soft shadow; the illustration is teal #2A8FA6 with a dark mascot in the centre.)
- photo at x 56.1, y 36.8, w 32.5, h 28.3 [#FFFFFF]: Partly hidden screenshot of a documentation page with a blue-grey text block (Placed image 512 by 251 pixels, mostly covered; white background, cyan border, soft shadow.)
- photo at x 59.6, y 42.5, w 32.5, h 28.1 [#FFFFFF]: Partly hidden screenshot of a documentation page with body text (Placed image 512 by 249 pixels, mostly covered; white background, cyan border, soft shadow.)
- photo at x 59.1, y 47.4, w 34.2, h 25.4 [#FFFFFF]: Screenshot of Rules Maturity Framework page: heading Rules Maturity Framework, paragraphs beginning The rules maturity framework was established following this proposal and At a high level, The Falco Project maintains community-contributed syscall and container event-based rules, with maturity_stable tagged rules being included in the Falco release package, and a teal-blue panel on the left edge (Placed image 493 by 206 pixels; cyan-bordered card with soft shadow; partly covered by the Driver Testing Matrix card at the bottom.)
- photo at x 63.2, y 49.5, w 32.5, h 38.2 [#FFFFFF]: Partly hidden tall screenshot of a documentation page with a teal-blue panel and an unreadable text block (Placed image 512 by 338 pixels, almost entirely covered by the Driver Testing Matrix card; cyan border, soft shadow.)
- photo at x 62.7, y 59, w 34.2, h 30.8 [#FFFFFF]: Screenshot of Driver Testing Matrix amd64 table: heading Driver Testing Matrix amd64; columns KERNEL, CMAKE-CONFIGURE, KMOD BUILD, KMOD SCAP-OPEN, BPF-PROBE BUILD, BPF-PROBE SCAP-OPEN, MODERN-BPF SCAP-OPEN; rows amazonlinux2-4.19, amazonlinux2-5.10, amazonlinux2-5.15, amazonlinux2-5.4, amazonlinux2022-5.15, amazonlinux2023-6.1; cells contain green dots, with yellow dots in amazonlinux2-4.19 and amazonlinux2-5.4 under MODERN-BPF SCAP-OPEN (Placed image 493 by 250 pixels, the front-most card, white with thin grey row dividers and a light grey header row; green #4CA32A status dots, yellow #F2C037 status dots; cyan border and soft shadow; bottom row is cut off by the slide edge of the card.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#00AFC9]: Falco logo: spider-web mark with the word Falco (Placed image 32 by 12 pixels; cyan #00AFC9 mark and wordmark on the dark teal background; no border.)
- title at x 4.2, y 33.7, w 33, h 19.6 [Ubuntu Bold, sans-serif, normal case, no letter-spacing; font size 8.89% of slide height; #FFFFFF; left aligned]: Innovations & / Contributions (Two lines at a line spacing of about 10.7% of slide height; the first line Innovations & sits at y 33.7 and the second line Contributions at y 44.4.)
- subtitle at x 4.2, y 56.7, w 34.4, h 4.9 [Ubuntu Medium, sans-serif, normal case, no letter-spacing; font size 4.94% of slide height; #FFFFFF; left aligned]: The Core of Falco's Growth (Single line below the title, sitting on the bright cyan left panel.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 45.6, h 100.0: 830 by 1024 pixels
- image at x 63.2, y 49.5, w 32.5, h 38.2: 512 by 338 pixels
- image at x 62.7, y 59.0, w 34.2, h 30.8: 493 by 250 pixels
- image at x 49.2, y 9.3, w 32.5, h 30.8: 512 by 273 pixels
- image at x 55.6, y 36.0, w 34.2, h 28.7: 493 by 233 pixels
- image at x 48.7, y 12.2, w 34.2, h 28.7: 493 by 233 pixels
- image at x 52.6, y 20.5, w 32.8, h 28.1: 512 by 247 pixels
- image at x 56.1, y 36.8, w 32.5, h 28.3: 512 by 251 pixels
- image at x 59.6, y 42.5, w 32.5, h 28.1: 512 by 249 pixels
- image at x 52.3, y 24.2, w 34.2, h 26.6: 493 by 216 pixels
- image at x 59.1, y 47.4, w 34.2, h 25.4: 493 by 206 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 32 by 12 pixels
- text at x 4.2, y 33.7, w 33.9, h 8.9 [Ubuntu-Bold; font size 8.89; #FFFFFF]: Innovations &
- text at x 4.2, y 44.4, w 33.0, h 8.9 [Ubuntu-Bold; font size 8.89; #FFFFFF]: Contributions
- text at x 4.2, y 56.7, w 34.4, h 4.9 [Ubuntu-Medium; font size 4.94; #FFFFFF]: The Core of Falco's Growth

### Slide 4

**Text**

Community & / Governance
A Flourishing Community / and an Open Governance
Our Principles:
➔ Open
➔ Respectful
➔ Diverse
➔ Transparent
➔ Vibrant
“The open nature of The Falco Project, its / first principle, will never be a matter of / change.” - Falco’s governance
Falco

**Layout**

Two-column split with a vertical edge at 45.6% of slide width: the left column (0 to 45.6%) is a full-height cyan panel holding the title and subtitle, left-aligned at x 4.2%, with the title's top at about 33.7% of height and the subtitle's lower edge near 67.5%. The right column (45.6 to 100%) is a solid dark teal field holding a heading, a five-item arrow list left-aligned at x 60.5% (text at 65.5%), and an italic quote at x 49.1% anchored near the bottom. The Falco logo sits bottom-right at x 87.1%, y 89.6%. No footer and no slide number are visible; margins are about 4% left and 2% at the bottom.

**Visuals**

Left panel (0 to 45.6% width, full height): a flat illustration of a bright cyan field (#00AEC7) with one large, slightly lighter cyan (#1DB5CF) curved band, a quarter-circle arc sweeping from the top edge around x 20 to 46% and down to the panel's right edge at about y 48%. The arc is a tonal shape with no outline and no shadow. Right side: no photograph or chart; a flat dark teal field. Logo at bottom-right: the Falco mark, a stylised crossed-stroke emblem in dark slate grey (#2B4A52), next to the lowercase wordmark 'Falco' in the same dark slate grey; the logo is about 8.7% of width and 5.9% of height.

**Design**

Background: Solid dark teal #04748C across the whole slide, with the left 45.6% covered by a bright cyan #00AEC7 illustrated panel carrying a lighter #1DB5CF arc.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid flat fill, no outline, no gradient.)
- illustration at x 0, y 0, w 45.6, h 100 [#00AEC7]: Left panel illustration: cyan field with a lighter curved arc band sweeping from the top edge down to the right edge of the panel (Flat vector art, full-bleed to the top, bottom and left edges, cut off at the 45.6% vertical edge; the lighter arc is #1DB5CF with no outline, no shadow, opacity 100%.)
- title at x 4.2, y 33.7, w 33.1, h 17.8 [Ubuntu Bold, sentence case, no letter-spacing; font size 8.89% of slide height; #FFFFFF; left aligned]: Community & / Governance (Two lines, line spacing about 1.1 of the font size; line 1 top at 33.7% and line 2 top at 44.4%.)
- subtitle at x 4.2, y 56.7, w 33.1, h 10.8 [Ubuntu Medium, sentence case; font size 4.94% of slide height; #FFFFFF; left aligned]: A Flourishing Community / and an Open Governance (Two lines; line 1 top at 56.7%, line 2 top at 62.6%.)
- body at x 60.5, y 27.7, w 19.2, h 4.4 [Montserrat Bold, sentence case; font size 4.44% of slide height; #FFFFFF; left aligned]: Our Principles: (Heading above the list.)
- bullet list at x 60.5, y 35.7, w 19.5, h 36.4 [Montserrat Bold for words; arrow glyphs in MS PGothic, sentence case; font size 4.44% of slide height; #FFFFFF; left aligned]: ➔ Open / ➔ Respectful / ➔ Diverse / ➔ Transparent / ➔ Vibrant (Five items at 8% vertical pitch (tops at 35.7, 43.7, 51.7, 59.7, 67.7%). Bullet is a white solid right arrow (➔) at x 60.5%, words start at x 65.5%, about 4 spaces between arrow and word. Each item is a separate line with no rules.)
- quote at x 49.1, y 80, w 41.3, h 11.8 [Montserrat Medium Italic for the quote; Montserrat Medium upright for the dash and the link text; font size 3.46% of slide height; #FFFFFF; left aligned]: “The open nature of The Falco Project, its / first principle, will never be a matter of / change.” - Falco’s governance (Three lines, line pitch about 4.2% of height. The attribution 'Falco’s governance' is a hyperlink in #00AEC7 with an underline, starting at x 59.7%, top 88.3%. The ligature 'fi' in 'first' is used. The quote is in italic; the link is upright.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#2B4A52]: Falco logo: stylised crossed-stroke mark plus wordmark 'Falco' (Dark slate grey artwork on the dark teal field, low contrast; overlaps nothing; no shadow.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 45.6, h 100.0: 415 by 512 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 16 by 6 pixels
- text at x 4.2, y 33.7, w 33.1, h 8.9 [Ubuntu-Bold; font size 8.89; #FFFFFF]: Community &
- text at x 4.2, y 44.4, w 28.2, h 8.9 [Ubuntu-Bold; font size 8.89; #FFFFFF]: Governance
- text at x 60.5, y 27.7, w 19.2, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Our Principles:
- text at x 60.5, y 35.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 60.5, y 35.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 65.5, y 35.7, w 7.1, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Open
- text at x 60.5, y 43.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 60.5, y 43.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 65.5, y 43.7, w 14.1, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Respectful
- text at x 4.2, y 56.7, w 33.1, h 4.9 [Ubuntu-Medium; font size 4.94; #FFFFFF]: A Flourishing Community
- text at x 60.5, y 51.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 60.5, y 51.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 65.5, y 51.7, w 9.8, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Diverse
- text at x 4.2, y 62.6, w 32.1, h 4.9 [Ubuntu-Medium; font size 4.94; #FFFFFF]: and an Open Governance
- text at x 60.5, y 59.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 60.5, y 59.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 65.5, y 59.7, w 15.8, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Transparent
- text at x 60.5, y 67.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 60.5, y 67.7, w 2.5, h 4.4 [MS-PGothic; font size 4.44; #FFFFFF]: ➔
- text at x 65.5, y 67.7, w 9.7, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Vibrant
- text at x 49.1, y 80.0, w 41.3, h 3.5 [Montserrat-MediumItalic; font size 3.46; #FFFFFF]: “The open nature of The Falco Project, its
- text at x 49.1, y 84.2, w 38.7, h 3.5 [Montserrat-MediumItalic; font size 3.46; #FFFFFF]: ﬁrst principle, will never be a matter of
- text at x 49.1, y 88.3, w 9.3, h 3.5 [Montserrat-MediumItalic; font size 3.46; #FFFFFF]: change.”
- text at x 58.4, y 88.3, w 1.3, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: -
- text at x 59.7, y 88.3, w 18.8, h 3.5 [Montserrat-Medium; font size 3.46; #00AEC7]: Falco’s governance

### Slide 5

**Text**

/hold
a moment
Falco

**Layout**

Single centred composition on a plain full-bleed teal field: the two text lines are centred horizontally in the middle band of the slide, with the logo fixed in the bottom-right corner. No title placeholder, footer or slide number is visible.

**Visuals**

One logo in the bottom-right corner: the Falco wordmark with a stylised mark of three diagonal strokes crossing to the left of the word 'Falco'. The mark and wordmark are dark navy/near-black (about #0B2A35) on the teal background. No photographs, charts or other graphics.

**Design**

Background: Solid flat teal #04748C filling the entire slide. Flat solid teal background with no gradient, texture or shadow. Headline '/hold' and subline 'a moment' are white (#FFFFFF) in Ubuntu, sans-serif humanist type: Ubuntu Bold for the headline and Ubuntu Regular for the subline. Headline is about 12.8% of slide height, subline about 6.9%. Text is centred with generous empty space on all sides; no accent colours or rules.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: full-slide background fill (Solid flat fill, no gradient, no border, covers the whole slide edge to edge.)
- title at x 40.7, y 41.1, w 18.6, h 12.8 [Ubuntu, sans-serif, bold, regular case, no italics, no letter-spacing; font size 12.84% of slide height; #FFFFFF; center aligned]: /hold
- subtitle at x 41.1, y 59.7, w 17.9, h 6.9 [Ubuntu, sans-serif, regular weight, lowercase, no italics, no letter-spacing; font size 6.91% of slide height; #FFFFFF; center aligned]: a moment
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0B2A35]: Falco logo (stylised diagonal-stroke mark with wordmark 'Falco') (Dark navy/near-black mark and wordmark placed in the bottom-right corner, sitting directly on the teal background with no box or backing.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 8 by 3 pixels
- text at x 40.7, y 41.1, w 18.6, h 12.8 [Ubuntu-Bold; font size 12.84; #FFFFFF]: /hold
- text at x 41.1, y 59.7, w 17.9, h 6.9 [Ubuntu-Regular; font size 6.91; #FFFFFF]: a moment

### Slide 6

**Text**

We made Falco fly!
FALCO GRADUATION 2024
CLOUD NATIVE COMPUTING FOUNDATION
Falco

**Layout**

Two-column composition on a white background: a large teal graduation badge occupies the left half, vertically centred, and the title 'We / made / Falco / fly!' is stacked in four centred lines in the right half. A small Falco logo sits in the bottom-right corner, and a colour gradient blur bleeds in from the top-right corner. No title placeholder, footer or slide number is visible.

**Visuals**

Left: a teal (#00A7C2) rectangular graduation badge with a white ribbon-bookmark cut-out on its left side. The ribbon contains the Falco logo (stylised bird-wing mark over the word 'Falco' in teal). To the right of the ribbon, inside the badge, the Cloud Native Computing Foundation logo (small blue-and-white CNCF mark with the words 'CLOUD NATIVE / COMPUTING FOUNDATION' in white) sits above the white bold text 'FALCO GRADUATION' and the thin dark-grey outlined numerals '2024'. The badge is flat with no shadow, no gradient and no rotation. Top-right corner: a soft out-of-focus gradient blur fading from deep blue (#3F5BFF) through cyan (#33C8FF) to white and lavender (#C9B8F5) toward the centre-left, bleeding off the top and right edges. Bottom-right: small Falco logo in dark navy (#0E2F3F) with the bird-wing mark and the word 'Falco'.

**Design**

Background: White (#FFFFFF) with a blue-to-lavender gradient blur in the top-right corner.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#FFFFFF]: Background gradient blur in top-right corner, from blue-violet to cyan fading to white (Soft radial/linear gradient, colours #3F5BFF to #33C8FF to #C9B8F5, fading to transparent white toward centre-left; bleeds off top and right edges.)
- shape at x 4.5, y 24.7, w 54.7, h 50.6 [#00A7C2]: Teal graduation badge background rectangle (Flat rectangle, no shadow, no corner radius; white ribbon cut-out on left side with V-notch bottom at about x 7.5 to 16.8.)
- logo at x 8.5, y 19.5, w 7.5, h 12.5 [#00A7C2]: Falco logo on white ribbon (bird-wing mark over word 'Falco') (Teal stylised wing mark above the word 'Falco' in teal, placed on the white ribbon.)
- logo at x 20, y 32.9, w 10.5, h 3.3 [#FFFFFF]: Cloud Native Computing Foundation logo (Small blue square mark with white text 'CLOUD NATIVE / COMPUTING FOUNDATION' in bold sans-serif capitals.)
- title at x 19.9, y 37, w 35.4, h 9 [Poppins-like geometric sans-serif; font size 6.5% of slide height; #FFFFFF; left aligned]: FALCO GRADUATION (Bold capitals, white, flush left inside badge.)
- caption at x 19.9, y 57, w 8.5, h 5 [Poppins-like geometric sans-serif, light weight; font size 4.5% of slide height; #333F48; left aligned]: 2024 (Thin dark grey outlined numerals.)
- title at x 64.9, y 18.9, w 21.3, h 65 [Ubuntu, bold; font size 13.83% of slide height; #04748C; center aligned]: We / made / Falco / fly! (Four lines, line spacing about 16.6% of slide height per line; each line centred on the same axis.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0E2F3F]: Falco logo bottom-right (bird-wing mark and word 'Falco') (Dark navy mark and wordmark, no background.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- image at x 0.0, y 0.0, w 100.0, h 100.0: 1250 by 703 pixels (covers the slide)
- image at x 4.5, y 24.7, w 54.7, h 50.6: 1014 by 528 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 69.2, y 18.9, w 11.7, h 13.8 [Ubuntu-Bold; font size 13.83; #04748C]: We
- text at x 64.9, y 35.5, w 20.2, h 13.8 [Ubuntu-Bold; font size 13.83; #04748C]: made
- text at x 65.3, y 52.2, w 21.3, h 13.8 [Ubuntu-Bold; font size 13.83; #04748C]: Falco
- text at x 69.0, y 68.9, w 12.1, h 13.8 [Ubuntu-Bold; font size 13.83; #04748C]: ﬂy!

### Slide 7

**Review notes**

- Review: The deck has a consistent teal identity, a clear section structure (slides 7, 14, 25, 31 as dividers) and a readable route from history to news to roadmap to community.

**Text**

Falco
What’s new in Falco?

**Layout**

A single left-aligned title sits in the lower-middle of the slide, starting at about 4.2% from the left edge, with the Falco logo fixed in the top-left corner at the same left margin. There is no footer, no slide number and no subtitle; the right half of the slide is empty apart from the pale watermark graphic.

**Visuals**

Two non-text visuals. (1) A pale cyan watermark illustration of the Falco X-feather mark, made of rounded diagonal strokes, fills the lower-right portion of the slide (roughly x 68 to 98%, y 40 to 100%) and runs off the bottom and right edges; it is part of a full-bleed 1200 by 628 px image covering the whole slide. (2) The Falco logo at top left: a stylised X made of double diagonal strokes followed by the lowercase-style wordmark 'Falco' in dark teal. No photograph, chart or table.

**Design**

Background: White #FFFFFF full-bleed image with a pale cyan (#E6F7F9) X-shaped watermark in the lower right, above a solid #04748C fill that is covered. White background with a very pale cyan (#E6F7F9) tonal X watermark in the lower right. The solid #04748C fill beneath the full-bleed image is hidden and not visible. Title is set in Ubuntu Medium, sans-serif, dark near-black #171717, approximately 8.9% of slide height, single line, no italics. Logo wordmark and icon in dark teal #1B3B40. Watermark strokes are pale cyan #E6F7F9 with rounded ends and no shadow or outline. No gradients, no corner radii, no boxes or rules.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Solid rectangle fill covering the full slide (hidden behind the full-bleed image) (Full-bleed solid fill; fully covered by the image above it, not visible.)
- illustration at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-bleed background image: white field with pale cyan Falco X-feather watermark in the lower right (1200 by 628 px image covering the whole slide; watermark strokes are pale cyan #E6F7F9 with rounded line ends, occupying roughly x 68 to 98%, y 40 to 100%, cropped by the bottom and right edges; no overlay or tint on the white area.)
- image at x 87.1, y 89.6, w 8.7, h 5.9 [#FFFFFF]: Small blank image at lower right (4 by 2 px placeholder, no visible content) (Measured as a 4 by 2 px image; no visible mark is discernible at this position beyond the pale watermark strokes.)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#1B3B40; left aligned]: Falco logo: stylised X icon of double diagonal strokes with the wordmark Falco (Dark teal icon of two crossing double-stroke diagonals to the left of the wordmark 'Falco' in a rounded bold sans-serif; sits top-left with no background box; no shadow.)
- title at x 4.2, y 49.5, w 47.4, h 8.9 [Ubuntu, Medium weight, sentence case, no italics, no capitals, normal letter-spacing; font size 8.89% of slide height; #171717; left aligned]: What’s new in Falco? (Single line; sits vertically in the lower-middle of the slide; the apostrophe in 'What’s' is a curly right single quotation mark.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 4.2, y 49.5, w 47.4, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: What’s new in Falco?

### Slide 8

**Text**

Falco Keeps Flying - Where are we improving Falco? / Rules Maturity / & Language / Plugins & / Integrations / User Space / Plugins / Rules / Performance & / Security / eBPF / OR / Kernel Module / Falco driver / Kernel Space / Detections / Ecosystem & / Community / Falco

**Layout**

Four translucent boxes sit in a loose isometric cross around a centre box: Rules Maturity and Language top-left, Plugins and Integrations top-right, Performance and Security in the centre, Detections bottom-left, Ecosystem and Community bottom-right. The title is left-aligned across the top at about 3.4% from the left and 3.7% from the top, with no footer other than the Falco logo bottom-right at about 87% x and 90% y. There is no slide number visible and the margins are roughly 3 to 4% on the left and right.

**Visuals**

Isometric diagram on a flat teal field. Five translucent white rectangles (#FAFAFA at 33% opacity) hold the labelled icons. Top-left: a parchment scroll with faint printed text, 160 by 160 px, representing rules. Next to it, a stack of three white-grey book or document blocks with teal stripes, about 37% x and 33% y, about 4% wide by 8% high. Top-right: a blue Kubernetes wheel logo, 94 by 94 px, on a white heptagon, at about 70% x and 18% y. Beside it, a stack of three overlapping white browser windows with teal title bars and a small cursor, about 58.7% x and 25.8% y, about 8.3% wide by 16.9% high. Centre: a grey 3D gear on a pale cyan ellipse, 80 by 80 px, at about 46.6% x and 42% y. Bottom-left: a gold key, 80 by 80 px, at about 26.8% x and 66.2% y. Bottom-right: a blue faceted diamond, 80 by 80 px, at about 69.9% x and 65% y. Also a white three-sided prism with a small teal A, about 60% x and 61% y, about 4.5% wide by 8% high. A pale-cyan pill labelled Falco driver (about 28.8% x, 55.6% y, 18.4% wide, 19% high) contains two white 3D chips: the left one with an eBPF bee logo (about 31.3% x, 56% y) and the right one labelled Kernel Module in teal (about 38.3% x, 63.3% y), joined by the small word OR. Dark grey pill labels read User Space (about 45.9% x, 32.4% y), Kernel Space (about 48.4% x, 73.4% y) and a white pill labelled Plugins with a small teal icon (about 57.3% x, 38.7% y). A faint dashed teal diagonal line runs from the Rules box toward the lower right, and a faint isometric grid sits behind the scene.

**Design**

Background: Solid flat teal #04748C. Flat teal background #04748C. Title in white #FFFFFF Ubuntu Bold, sans-serif, about 5.9% of slide height (cap height about 4.2%). Labels in white #FFFFFF Ubuntu Regular, sans-serif, about 3.5% of slide height, centred within each box, lines about 4% apart. Accent colours are teal #1FB5C9 on the chip and icon highlights, and dark charcoal #2B2B2B for the User Space and Kernel Space pills. Boxes have square corners, a thin white 1px outline and no shadow. The diagram lines are thin and dashed in teal or grey. No gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid flat fill covering the whole slide, no outline.)
- line at x 26, y 41.8, w 35.8, h 36.4 [#1FB5C9]: Dashed diagonal guide line (Dashed teal stroke about 1px, running from the lower edge of the Rules box toward the lower right, passing behind the centre box and the Falco driver pill.)
- shape at x 22, y 17.4, w 15.2, h 24.5 [#FAFAFA]: Rules Maturity box (Rectangle, white #FAFAFA at 33% opacity, square corners, thin white 1px outline, no shadow.)
- shape at x 66.2, y 17.1, w 15.2, h 25.1 [#FAFAFA]: Plugins box (Rectangle, white #FAFAFA at 33% opacity, square corners, thin white 1px outline, no shadow.)
- shape at x 41.7, y 39.5, w 16.6, h 24.4 [#FAFAFA]: Performance and Security box (Rectangle, white #FAFAFA at 33% opacity, square corners, thin white 1px outline, no shadow; overlaps the Falco driver pill at its lower left.)
- shape at x 22, y 64.1, w 15.2, h 24.4 [#FAFAFA]: Detections box (Rectangle, white #FAFAFA at 33% opacity, square corners, thin white 1px outline, no shadow; overlapped by the Falco driver pill.)
- shape at x 65.6, y 63.7, w 15.2, h 24.4 [#FAFAFA]: Ecosystem and Community box (Rectangle, white #FAFAFA at 33% opacity, square corners, thin white 1px outline, no shadow.)
- shape at x 28.8, y 55.6, w 18.4, h 19 [#DDF1F5]: Falco driver pill (Stadium-shaped pill, pale cyan fill about 85% opacity, no outline, soft edge; overlaps the Detections box and the Performance box.)
- text at x 32.5, y 70, w 8.5, h 3 [Ubuntu, italic; font size 1.8% of slide height; #6B7F86; center aligned]: Falco driver (Small grey label rotated about 25 degrees along the lower-left edge of the pill.)
- icon at x 31.2, y 56, w 7.5, h 8 [#FFFFFF]: eBPF chip with bee logo (Isometric white chip, slightly tilted, with the eBPF bee logo in dark blue and black lettering eBPF.)
- text at x 37.4, y 62.5, w 1.8, h 1.6 [Ubuntu, regular; font size 1.5% of slide height; #FFFFFF; center aligned]: OR
- icon at x 38.3, y 63.3, w 7.5, h 8.5 [#FFFFFF]: Kernel Module chip (Isometric white chip with the words Kernel Module in teal #1FB5C9, bold sans-serif, rotated about 25 degrees.)
- photo at x 26.1, y 18.6, w 7, h 13.1: Parchment scroll illustration with rules text (160 by 160 px image of a rolled parchment scroll, tan and brown, with faint printed lines of text, placed inside the Rules box.)
- icon at x 36.9, y 32.9, w 3.8, h 8.2 [#F2F2F2]: Stack of three white document blocks with teal stripes (Isometric grey-white stacked blocks with teal horizontal stripes on their faces, sitting at the right edge of the Rules box.)
- icon at x 58.7, y 25.8, w 8.3, h 16.9 [#F2F2F2]: Stack of three overlapping browser windows (Isometric stack of three white window frames with light grey title bars, teal accents and a small cursor arrow, sitting partly over the Plugins box edge.)
- logo at x 70, y 18.1, w 7.5, h 13.4 [#326CE5]: Kubernetes wheel logo (94 by 94 px blue Kubernetes helm wheel in a white-outlined heptagon, inside the Plugins box.)
- icon at x 46.6, y 42, w 6.7, h 12 [#8A9199]: Grey 3D gear on cyan disc (80 by 80 px grey metallic cog on a pale cyan ellipse disc, centred in the Performance box.)
- icon at x 60, y 61, w 4.5, h 8 [#FFFFFF]: Three-sided white prism with teal A (White angular prism with a small teal A on one face.)
- icon at x 26.8, y 66.2, w 6.6, h 11.8 [#E8B923]: Gold key (80 by 80 px gold key with a round bow, inside the Detections box.)
- icon at x 69.9, y 65, w 6.7, h 11.8 [#3FA9F5]: Blue faceted diamond (80 by 80 px light blue faceted gem, inside the Ecosystem box.)
- shape at x 45.9, y 32.4, w 6.5, h 6.7 [#2B2B2B]: User Space pill (Dark charcoal stadium label rotated about 25 degrees, white text User Space.)
- shape at x 57.3, y 38.7, w 5.8, h 5.8 [#FFFFFF]: Plugins pill (White stadium label rotated about -25 degrees with a small teal icon and dark text Plugins.)
- shape at x 48.4, y 73.4, w 7.3, h 7.5 [#2B2B2B]: Kernel Space pill (Dark charcoal stadium label rotated about 25 degrees, white text Kernel Space.)
- line at x 41, y 40, w 24, h 30 [#8A9199]: Thin grey arrows and small labels near the centre (Faint thin grey connector arrows with arrowheads, some ending at the centre box, with a faint label Rules near the upper left and a faint label near the right.)
- text at x 23.2, y 33, w 13.3, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Rules Maturity
- text at x 24.5, y 37.2, w 10.4, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: & Language
- text at x 69.7, y 32.5, w 8.6, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Plugins &
- text at x 68.4, y 36.6, w 10.8, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Integrations
- text at x 43.4, y 54.3, w 13.6, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Performance &
- text at x 46.4, y 58.5, w 7.1, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Security
- text at x 24.4, y 81, w 9.6, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Detections
- text at x 67.7, y 79.1, w 11.5, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Ecosystem &
- text at x 68.1, y 83.2, w 10.1, h 3.5 [Ubuntu, regular; font size 3.46% of slide height; #FFFFFF; center aligned]: Community
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1E1E1E]: Falco logo (grey-black Falco wordmark with stylised F icon) (Dark charcoal stylised icon followed by the word Falco in bold dark lettering, bottom-right corner.)
- text at x 3.4, y 3.7, w 81, h 5.9 [Ubuntu, bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Falco Keeps Flying - Where are we improving Falco?

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 22.0, y 64.1, w 15.2, h 24.4: #FAFAFA, opacity 0.33
- fill at x 22.0, y 17.4, w 15.2, h 24.5: #FAFAFA, opacity 0.33
- fill at x 41.7, y 39.5, w 16.6, h 24.4: #FAFAFA, opacity 0.33
- fill at x 66.2, y 17.1, w 15.2, h 25.1: #FAFAFA, opacity 0.33
- fill at x 65.6, y 63.7, w 15.2, h 24.4: #FAFAFA, opacity 0.33
- image at x 26.0, y 13.3, w 45.2, h 73.4: 708 by 647 pixels
- image at x 70.0, y 18.1, w 7.5, h 13.4: 94 by 94 pixels
- image at x 26.1, y 18.6, w 7.0, h 13.1: 160 by 160 pixels
- image at x 46.6, y 42.0, w 6.7, h 12.0: 80 by 80 pixels
- image at x 69.9, y 65.0, w 6.7, h 11.8: 80 by 80 pixels
- image at x 26.8, y 66.2, w 6.6, h 11.8: 80 by 80 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 81.0, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Falco Keeps Flying - Where are we improving Falco?
- text at x 23.2, y 33.0, w 13.3, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Rules Maturity
- text at x 69.7, y 32.5, w 8.6, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Plugins &
- text at x 68.4, y 36.6, w 10.8, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Integrations
- text at x 24.5, y 37.2, w 10.4, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: & Language
- text at x 43.4, y 54.3, w 13.6, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Performance &
- text at x 46.4, y 58.5, w 7.1, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Security
- text at x 67.7, y 79.1, w 11.5, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Ecosystem &
- text at x 24.4, y 81.0, w 9.6, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Detections
- text at x 68.1, y 83.2, w 10.1, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Community

### Slide 9

**Text**

Detection Improvements
Every detection can be bypassed…
… so we are adding more!
Detection Improvements - Symlink resolution
$ ln -s /bin/cat /tmp/dog
$ /tmp/dog hello.txt
Field name / Before 0.36.0 / Falco 0.36.0
proc.name / dog / dog
proc.exe / /tmp/dog / /tmp/dog
proc.exepath / /tmp/dog / /bin/cat
Falco
KubeCon | CloudNativeCon
North America 2023
Falco

**Layout**

Full-bleed teal slide with a left-aligned title and two-line subtitle in the top-left area. A wide framed screenshot sits below the subtitle, spanning about 90% of the width, with the Falco logo in the bottom-right corner outside the screenshot. The screenshot contains a left Falco slide panel (about 60% of its width) and a right photo panel with a KubeCon and CloudNativeCon logo lockup beneath it. No slide number or footer is visible.

**Visuals**

Embedded screenshot of a presentation slide (1272 by 515 px, boxed, not cropped, with a thin purple frame). Left panel: teal slide titled 'Detection Improvements - Symlink resolution' in white bold sans-serif. Below it is a dark terminal box (near-black #111A1A, rounded corners, three traffic-light dots red, amber and green at top-left) showing '$ ln -s /bin/cat /tmp/dog' with '$' and 'ln' and '-s' tinted, and '$ /tmp/dog hello.txt' beneath it in pale monospace text. Below the terminal is a table with 3 columns and 4 rows (one header row) with thin light-grey-white borders on teal: header row (italic) 'Field name' | 'Before 0.36.0' | 'Falco 0.36.0'; row 1 'proc.name' | 'dog' | 'dog'; row 2 'proc.exe' | '/tmp/dog' | '/tmp/dog'; row 3 'proc.exepath' | '/tmp/dog' | '/bin/cat' with '/bin/cat' in bold. Right panel: a photograph of a conference stage from the audience, framed by a purple border; four people stand on stage (three men, one woman on right), one man at a podium with a microphone; audience seated in dark blue chairs in the foreground; lighting is dim with a bright blue-white screen strip at upper left; dominant colours dark grey, navy and blue. Below the photo, on a pale pink-white background, is the KubeCon logo (purple hexagon with ship wheel) divided by a vertical line from the CloudNativeCon logo (purple square with abstract mark), with text 'KubeCon', 'CloudNativeCon' and a rule-flanked 'North America 2023' in purple. Falco logo (teal stylised double slash with 'Falco' text) appears in the bottom-right of the teal left panel and again as a dark logo outside the screenshot at bottom-right of the slide.

**Design**

Background: Solid teal #04748C. Solid teal background with white bold sans-serif title (Ubuntu Bold, about 6% of slide height) and white regular geometric sans-serif subtitle (Montserrat Regular, about 3.5% of slide height), left-aligned at about 4% left margin. Screenshot is boxed with a thin purple (#4B2E83) frame on both panels; no shadows or rounded corners on the screenshot frame. Terminal box has rounded corners (about 4 px). Accent colours: purple #4B2E83, teal #0E7280, pale pink-white #F2E6EC in screenshot background, Falco teal #1FA3B5. Body text in the screenshot is white or pale grey.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100: full-slide background rectangle (fill #04748C, covers entire slide, no border)
- photo at x 5, y 23.8, w 90, h 64.8: embedded screenshot of Falco conference slide and KubeCon photo (boxed, not cropped, not full-bleed; background pale pink-white #F2E6EC; no shadow; rectangular edges)
- shape at x 5.2, y 26.3, w 59.7, h 60.1: left screenshot panel frame and teal slide (fill teal #0E7280, purple #4B2E83 border about 0.6% of slide width, square corners)
- text at x 7.3, y 28.4, w 42.7, h 3.6 [Ubuntu, bold, sans-serif; font size 1.2% of slide height; #FFFFFF; left aligned]: Detection Improvements - Symlink resolution
- shape at x 24.2, y 38.9, w 21.5, h 12.2: terminal box (fill #111A1A, corner radius about 4 px, three dots red #E5534B amber #E5A93B green #3BBF5A at top-left)
- text at x 25.2, y 44.8, w 19.5, h 4.4 [monospace, regular; font size 0.9% of slide height; #E6E6E6; left aligned]: $ ln -s /bin/cat /tmp/dog / $ /tmp/dog hello.txt (line spacing about 1.4; '$' and 'ln -s' tinted teal and green)
- table at x 11.4, y 57.2, w 47.1, h 18.4 [sans-serif, regular, italic header; font size 0.9% of slide height; #FFFFFF; left aligned]: table with columns Field name, Before 0.36.0, Falco 0.36.0 and rows proc.name, proc.exe, proc.exepath (fill transparent over teal #0E7280, white thin borders about 0.1% width; header row darker teal #0B5F6B; /bin/cat in bold)
- logo at x 57, y 80, w 6.2, h 4.5: Falco logo on teal panel (teal #1FA3B5 double-slash mark with Falco wordmark)
- photo at x 65.5, y 26.3, w 29.3, h 29.7: audience photograph of conference stage with four presenters and seated audience (boxed with purple #4B2E83 frame, not cropped; dim lighting; dominant navy and dark grey)
- logo at x 69.7, y 67.1, w 10, h 8.4: KubeCon logo (purple hexagon with ship wheel) and text KubeCon (fill purple #5B2A86)
- line at x 77.2, y 67, w 0.2, h 8: vertical divider between logos (dark purple #3B1D5C stroke about 0.2% width)
- logo at x 78, y 67, w 12.4, h 8.4: CloudNativeCon logo (purple square with abstract mark) and text CloudNativeCon (fill purple #5B2A86)
- text at x 69.5, y 81.3, w 21.2, h 2 [Montserrat, bold, sans-serif; font size 1.3% of slide height; #4B2E83; center aligned]: North America 2023 (flanked by thin purple horizontal rules)
- logo at x 87.1, y 89.6, w 8.7, h 5.9: Falco logo bottom right outside screenshot (dark slate #1E2A33 wordmark with teal #1FA3B5 double-slash mark)
- title at x 3.4, y 3.7, w 39.6, h 5.9 [Ubuntu, bold, sans-serif; font size 5.93% of slide height; #FFFFFF; left aligned]: Detection Improvements
- body at x 4.3, y 13.5, w 33.3, h 7.5 [Montserrat, regular, sans-serif; font size 3.46% of slide height; #FFFFFF; left aligned]: Every detection can be bypassed… / … so we are adding more! (two lines, line spacing about 1.5 times font size)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 5.0, y 23.8, w 90.0, h 64.8: 1272 by 515 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 39.6, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Detection Improvements
- text at x 4.3, y 13.5, w 33.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Every detection can be bypassed…
- text at x 4.3, y 17.5, w 24.6, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: … so we are adding more!

### Slide 10

**Text**

Detection Improvements
So what is the Falco bypass of the day?

**Layout**

Single full-bleed teal field with a left-aligned bold title in the top-left corner and one centred italic statement floating in the middle of the slide; the Falco logo sits in the bottom-right corner. Title left edge sits at about 3.4% of slide width, the logo is inset about 8.7% from the right and about 5.9% from the bottom.

**Visuals**

none

**Design**

Background: Solid teal #04748C. Flat solid teal background #04748C with no gradient, texture or border. Title is white (#FFFFFF) Ubuntu Bold sans-serif, about 5.9% of slide height. Centred statement is white (#FFFFFF) Montserrat Italic sans-serif, about 5.9% of slide height, regular weight. Logo is dark near-black wordmark with a stylised slash mark, rendered at small size. No shapes, lines, shadows or corner radii.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background rectangle filled with teal (Flat fill, no stroke, no shadow, covers the entire slide.)
- title at x 3.4, y 3.7, w 39.6, h 5.9 [Ubuntu, Bold, sentence case; font size 5.93% of slide height; #FFFFFF; left aligned]: Detection Improvements (Single line, left aligned, top-left of slide.)
- body at x 17.3, y 47.4, w 66.2, h 5.9 [Montserrat, Italic, regular weight, sentence case; font size 5.93% of slide height; #FFFFFF; center aligned]: So what is the Falco bypass of the day? (Single line centred horizontally in the middle of the slide, vertically near the midpoint.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: stylised slash mark followed by the wordmark 'Falco' (Dark near-black logo in bottom-right corner, sitting on teal, low-contrast against the background.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 39.6, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Detection Improvements
- text at x 17.3, y 47.4, w 66.2, h 5.9 [Montserrat-Italic; font size 5.93; #FFFFFF]: So what is the Falco bypass of the day?

### Slide 11

**Text**

Detection Improvements - eBPF and IA32 Emulation
Falco
kmod
eBPF
Modern
eBPF
0.36.0
0.37.0
#include <stdio.h>
#include <unistd.h>
#include <sys/syscall.h>
#include <sys/types.h>
int main() {
    syscall(__NR_close, -1);
    return 0;
}
$ gcc ia32.c -o ia32 -m32

**Layout**

Title runs across the top left of the slide, starting at about 3.4% from the left edge. A two-column layout: stacked code panels on the left (about 3% to 48% of slide width) and a four-column, three-row table on the right (about 52% to 96%). Empty band between title and content. Falco logo sits bottom right, about 87% to 96% horizontally and 90% to 96% vertically. No slide number or footer visible.

**Visuals**

Left: two dark rounded code panels. The upper panel shows a macOS-style window with three coloured dots at top left (red, yellow, green) above a C source listing in monospace type with syntax colouring: #include lines in cyan, int and return in yellow, main and syscall in blue, the number 0 and the value -1 in red, and the closing brace in grey. The lower panel is a single-line terminal command, $ gcc ia32.c -o ia32 -m32, in monospace with the $ and gcc in cyan and the flags -o and -m32 in green. Right: a table with a white 1px outline and white internal dividers. Columns: Falco, kmod, eBPF, Modern eBPF. Rows: header row; 0.36.0 with a check mark under kmod, a sad face under eBPF and a sad face under Modern eBPF; 0.37.0 with check marks under kmod, eBPF and Modern eBPF. The emoji are rendered as small pixelated glyph images. Falco logo bottom right: dark wordmark with a stylised slash mark.

**Design**

Background: Solid teal #04748C. Flat solid teal background #04748C with no gradient or texture. Title in white bold humanist sans-serif (Ubuntu Bold), about 5.9% of slide height, not capitalised. Table text white Ubuntu Bold for headers and Ubuntu Regular for values, about 3.5% of slide height. Code uses a monospace face in syntax colours on near-black panels #16181B. Panels have rounded corners of about 1% of slide width and no visible shadow. Table lines are thin white 1px rules. Logo in near-black #1A1A1A.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: full-slide solid background rectangle (flat fill, no border, covers the whole slide)
- illustration at x 2.8, y 27.1, w 45.4, h 45.5 [#16181B]: upper code window panel with C source listing (rounded corners about 1% of slide width, no shadow, no border; source image 1024 by 670 px placed at x 0.0 y 16.8 w 54.0 h 66.3 with transparent margins; not cropped)
- icon at x 4.2, y 29.9, w 5.7, h 2.4 [#FF5F57]: three window control dots: red, yellow, green (three circles of about 1.2% width each, spaced evenly left to right, colours red #FF5F57, yellow #FEBC2E, green #28C840)
- body at x 4.5, y 37.2, w 25.5, h 30.4 [monospace regular; font size 2.6% of slide height; #56B6C2; left aligned]: int main() { / syscall(__NR_close, -1); / return 0; / } (full code listing: #include <stdio.h> / #include <unistd.h> / #include <sys/syscall.h> / #include <sys/types.h> / blank line / int main() { / syscall(__NR_close, -1); / return 0; / }; line spacing about 3.4% of slide height; keywords int and return in #E5C07B, function names in #61AFEF, numbers in #E06C75, punctuation in #ABB2BF)
- illustration at x 2.8, y 73.7, w 45.4, h 13.5 [#16181B]: lower terminal panel with gcc command (rounded corners about 1% of slide width, no shadow; source image 1024 by 351 px placed at x 0.0 y 62.3 w 54.4 h 36.0)
- body at x 4.6, y 78.3, w 24.5, h 3.3 [monospace regular; font size 3% of slide height; #ABB2BF; left aligned]: $ gcc ia32.c -o ia32 -m32 ($ and gcc in #56B6C2, -o and -m32 in #98C379, ia32.c and ia32 in light grey #ABB2BF)
- table at x 51.8, y 40.7, w 44.1, h 27.3 [#04748C]: table with 4 columns and 3 rows: Falco, kmod, eBPF, Modern eBPF / 0.36.0, check, sad face, sad face / 0.37.0, check, check, check (transparent cell fill, white 1px outlines around all cells; column boundaries at about x 51.8, 62.9, 73.9, 84.9, 95.9; row boundaries at about y 40.7, 52.6, 60.3, 68.0; header row about 12% of table height)
- title at x 3.4, y 3.7, w 82.3, h 5.9 [Ubuntu Bold, sans-serif, no italics, no capitals, no letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Detection Improvements - eBPF and IA32 Emulation
- body at x 86.8, y 43.1, w 7.7, h 3.5 [Ubuntu Bold, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: Modern
- body at x 54.9, y 45.2, w 4.9, h 3.5 [Ubuntu Bold, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: Falco
- body at x 65.8, y 45.2, w 5.2, h 3.5 [Ubuntu Bold, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: kmod
- body at x 77, y 45.2, w 4.8, h 3.5 [Ubuntu Bold, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: eBPF
- body at x 88, y 47.2, w 4.8, h 3.5 [Ubuntu Bold, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: eBPF
- body at x 54.7, y 54.9, w 5.3, h 3.5 [Ubuntu Regular, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: 0.36.0
- icon at x 67.2, y 54.9, w 2.4, h 3.5 [#FFFFFF]: check mark emoji (green tick, rendered as image) in kmod column, 0.36.0 row (Noto Color Emoji glyph, about 34 by 32 px source image at x 67.2 y 54.5)
- icon at x 78.2, y 54.9, w 2.4, h 3.5 [#FFFFFF]: sad face emoji in eBPF column, 0.36.0 row (Noto Color Emoji glyph, yellow face, about 5 by 4 px source image at x 78.2 y 62.2)
- icon at x 89.2, y 54.9, w 2.4, h 3.5 [#FFFFFF]: sad face emoji in Modern eBPF column, 0.36.0 row (Noto Color Emoji glyph, yellow face, about 3 by 2 px source image at x 89.2 y 62.2)
- body at x 54.7, y 62.6, w 5.3, h 3.5 [Ubuntu Regular, sans-serif, no italics; font size 3.46% of slide height; #FFFFFF; center aligned]: 0.37.0
- icon at x 67.2, y 62.6, w 2.4, h 3.5 [#FFFFFF]: check mark emoji in kmod column, 0.37.0 row (Noto Color Emoji glyph, about 9 by 8 px source image at x 67.2 y 62.2)
- icon at x 78.2, y 62.6, w 2.4, h 3.5 [#FFFFFF]: check mark emoji in eBPF column, 0.37.0 row (Noto Color Emoji glyph, about 5 by 4 px source image at x 78.2 y 62.2)
- icon at x 89.2, y 62.6, w 2.4, h 3.5 [#FFFFFF]: check mark emoji in Modern eBPF column, 0.37.0 row (Noto Color Emoji glyph, about 3 by 2 px source image at x 89.2 y 62.2)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: stylised slash mark with the wordmark Falco (dark near-black wordmark and mark on teal, bottom right corner, no clear space overlap)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 16.8, w 54.0, h 66.3: 1024 by 670 pixels
- image at x 0.0, y 62.3, w 54.4, h 36.0: 1024 by 351 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 78.2, y 54.5, w 2.4, h 4.0: 34 by 32 pixels
- image at x 89.2, y 54.5, w 2.4, h 4.0: 9 by 8 pixels
- image at x 78.2, y 62.2, w 2.4, h 4.0: 5 by 4 pixels
- image at x 89.2, y 62.2, w 2.4, h 4.0: 3 by 2 pixels
- image at x 67.2, y 54.5, w 2.4, h 4.0: 34 by 32 pixels
- image at x 67.2, y 62.2, w 2.4, h 4.0: 9 by 8 pixels
- text at x 3.4, y 3.7, w 82.3, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Detection Improvements - eBPF and IA32 Emulation
- text at x 86.8, y 43.1, w 7.7, h 3.5 [Ubuntu-Bold; font size 3.46; #FFFFFF]: Modern
- text at x 54.9, y 45.2, w 4.9, h 3.5 [Ubuntu-Bold; font size 3.46; #FFFFFF]: Falco
- text at x 65.8, y 45.2, w 5.2, h 3.5 [Ubuntu-Bold; font size 3.46; #FFFFFF]: kmod
- text at x 77.0, y 45.2, w 4.8, h 3.5 [Ubuntu-Bold; font size 3.46; #FFFFFF]: eBPF
- text at x 88.0, y 47.2, w 4.8, h 3.5 [Ubuntu-Bold; font size 3.46; #FFFFFF]: eBPF
- text at x 54.7, y 54.9, w 5.3, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: 0.36.0
- text at x 67.2, y 54.9, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅
- text at x 78.2, y 54.9, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: 😞
- text at x 89.2, y 54.9, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: 😞
- text at x 54.7, y 62.6, w 5.3, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: 0.37.0
- text at x 67.2, y 62.6, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅
- text at x 78.2, y 62.6, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅
- text at x 89.2, y 62.6, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅

### Slide 12

**Review notes**

- Worth studying: Side-by-side YAML blocks with highlighted changes show the override syntax clearly without extra explanation.
- Review: Slide 12's override example is hard to follow, with a struck-through output, handwritten green highlights and a second rule that does not obviously map to the first, and slide 20's diagram has small text and an unclear flow.
- Suggested repair: Replace the placeholder-looking images on slides 15 to 17 with labeled diagrams, restructure slide 12 as a clear before and after with readable annotations, and enlarge and simplify the flow on slide 20.

**Text**

Rule Language Improvements - Overrides
- rule: program_accesses_file
desc: track whenever a set of programs opens a file
condition: proc.name in (cat, ls) and evt.type=open
and not user.name = root
output: a tracked program opened a file (command=%proc.cmdline file=%fd.name)
The file %fd.name was opened by user %user.name with program %proc.cmdline
priority: INFO
- rule: program_accesses_file
condition: and not user.name=root
output: The file %fd.name was opened by user %user.name with program %proc.cmdline
override:
condition: append
output: replace
Falco

**Layout**

Single-column slide with the title in the top-left at about 3.4% from the left and 3.7% from the top, left-aligned. Two stacked dark-navy code panels span the full content width with a 2.3% side margin, the upper panel at 24.4% to 51% of the height and the lower at 56.2% to 87.1%. The Falco logo sits in the bottom-right corner, with no slide number or footer.

**Visuals**

Two code-listing panels rendered as monospace text on dark navy #073763 rectangles with square corners and no shadow. Upper panel: a YAML rule listing with keys rule, desc, condition, output and priority in bold cyan #06ADC7; the values are white #FFFFFF except proc.name and evt.type in red-orange #CD5840, and the output placeholders %proc.cmdline and %fd.name in amber #FFAB40. Two green #6AA84F highlight rectangles behind handwritten annotations: 'and not user.name = root' at the end of the condition line, and 'The file %fd.name was opened by user %user.name with program %proc.cmdline' beneath the output line. A thin red #D0021B-like strike line runs horizontally across the output line from about x 13.2% to 82.7% at about y 39% to cross out the original output text. Lower panel: the corrected rule with condition 'and not user.name=root' (user.name in red-orange) and output 'The file %fd.name was opened by user %user.name with program %proc.cmdline', followed by override: condition: append and output: replace, where the override keys sit on two dark green #38761D highlight rectangles. Falco logo: dark charcoal icon of crossed diagonal strokes with the wordmark Falco in dark grey #222222 at bottom-right.

**Design**

Background: Solid teal #04748C. Flat teal background #04748C. Title in white #FFFFFF Ubuntu Bold sans-serif at about 5.9% of slide height, cap height about 4%. Code text in RobotoMono Regular with bold keys, white #FFFFFF body, about 3% of slide height. Handwritten annotations in IndieFlower-style script, white #FFFFFF, about 3.5% of height. Accents: cyan #06ADC7 keys, red-orange #CD5840 and #E3664C variable names, amber #FFAB40 placeholders, green #6AA84F highlights, dark green #38761D highlights, red strike line. Panels flat with no rounded corners or gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Slide background fill, flat teal (full bleed, no border)
- shape at x 2.3, y 24.4, w 95.4, h 26.6 [#073763]: Upper code panel rectangle (square corners, no stroke, no shadow)
- shape at x 2.3, y 56.2, w 95.4, h 30.9 [#073763]: Lower code panel rectangle (square corners, no stroke, no shadow)
- shape at x 56.9, y 33.6, w 20.9, h 4.1 [#6AA84F]: Green highlight behind condition annotation (flat rectangle, no stroke, sits behind the handwritten text)
- shape at x 12.5, y 41, w 65.1, h 4.1 [#6AA84F]: Green highlight behind output annotation (flat rectangle, no stroke, sits behind the handwritten text)
- shape at x 8.2, y 75.2, w 17, h 3.6 [#38761D]: Dark green highlight behind override condition (flat rectangle, no stroke)
- shape at x 8.2, y 78.7, w 15, h 3.6 [#38761D]: Dark green highlight behind override output (flat rectangle, no stroke)
- line at x 13.2, y 38.9, w 69.5, h 0.6 [#D0021B]: Red strike-through line across the original output line (straight stroke about 0.3% of slide height thick, slightly rising from left to right, overlaps the output text and the amber placeholders)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#222222]: Falco logo (icon of crossed diagonal strokes plus Falco wordmark, dark charcoal, no background)
- title at x 3.4, y 3.7, w 65.6, h 5.9 [Ubuntu Bold, sans-serif, bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Rule Language Improvements - Overrides
- body at x 3.2, y 27.7, w 29, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: - rule: program_accesses_file (keys rule in bold #06ADC7; hyphen and value white)
- body at x 3.2, y 31.2, w 53, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: desc: track whenever a set of programs opens a file (key desc in bold #06ADC7)
- body at x 3.2, y 34.7, w 53, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: condition: proc.name in (cat, ls) and evt.type=open (proc.name and evt.type in #CD5840)
- caption at x 56.9, y 34.2, w 20.9, h 3.5 [IndieFlower, handwritten script, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: and not user.name = root (sits on the green highlight)
- body at x 3.2, y 38.2, w 79, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: output: a tracked program opened a file (command=%proc.cmdline file=%fd.name) (key output bold #06ADC7; %proc.cmdline and %fd.name in #FFAB40; struck through by the red line)
- caption at x 12.5, y 41.5, w 65.1, h 3.5 [IndieFlower, handwritten script, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: The file %fd.name was opened by user %user.name with program %proc.cmdline (sits on the green highlight)
- body at x 3.2, y 45.3, w 16, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: priority: INFO (key priority bold #06ADC7)
- body at x 3.2, y 61.6, w 29, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: - rule: program_accesses_file (key rule in bold #06ADC7)
- body at x 3.2, y 65.1, w 35, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: condition: and not user.name=root (user.name in #E3664C)
- body at x 3.2, y 68.6, w 70, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: output: The file %fd.name was opened by user %user.name with program %proc.cmdline (key output bold #06ADC7; %fd.name, %user.name and %proc.cmdline in #FFAB40)
- body at x 3.2, y 72.1, w 9, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: override: (key override bold #06ADC7)
- body at x 8.2, y 75.7, w 17, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: condition: append (sits on the dark green highlight; key bold #06ADC7)
- body at x 8.2, y 79.2, w 15, h 3 [RobotoMono Regular with bold key, monospace; font size 2.96% of slide height; #FFFFFF; left aligned]: output: replace (sits on the dark green highlight; key bold #06ADC7)
- footer at x 87.1, y 89.6, w 8.7, h 5.9 [logotype wordmark, sans-serif; #222222; right aligned]: Falco (part of the Falco logo, bottom-right)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 2.3, y 24.4, w 95.4, h 26.6: #073763
- fill at x 2.3, y 56.2, w 95.4, h 30.9: #073763
- fill at x 8.2, y 75.2, w 17.0, h 3.6: #38761D
- fill at x 8.2, y 78.7, w 15.0, h 3.6: #38761D
- fill at x 56.9, y 33.6, w 20.9, h 4.1: #6AA84F
- fill at x 12.5, y 41.0, w 65.1, h 4.1: #6AA84F
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 65.6, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Rule Language Improvements - Overrides
- text at x 3.2, y 27.7, w 2.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: -
- text at x 5.2, y 27.7, w 4.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: rule
- text at x 9.2, y 27.7, w 23.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : program_accesses_file
- text at x 56.9, y 34.2, w 20.9, h 3.5 [IndieFlower; font size 3.46; #FFFFFF]: and not user.name = root
- text at x 5.2, y 31.2, w 4.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: desc
- text at x 9.2, y 31.2, w 47.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : track whenever a set of programs opens a file
- text at x 5.2, y 34.7, w 9.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: condition
- text at x 14.2, y 34.7, w 2.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: :
- text at x 16.2, y 34.7, w 9.0, h 3.0 [RobotoMono-Regular; font size 2.96; #CD5840]: proc.name
- text at x 25.2, y 34.7, w 18.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: in (cat, ls) and
- text at x 43.2, y 34.7, w 8.0, h 3.0 [RobotoMono-Regular; font size 2.96; #CD5840]: evt.type
- text at x 51.2, y 34.7, w 5.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: =open
- text at x 12.5, y 41.5, w 65.1, h 3.5 [IndieFlower; font size 3.46; #FFFFFF]: The file %fd.name was opened by user %user.name with program %proc.cmdline
- text at x 5.2, y 38.2, w 6.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: output
- text at x 11.2, y 38.2, w 43.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : a tracked program opened a file (command=
- text at x 54.2, y 38.2, w 13.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFAB40]: %proc.cmdline
- text at x 67.2, y 38.2, w 6.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: file=
- text at x 73.3, y 38.2, w 8.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFAB40]: %fd.name
- text at x 81.3, y 38.2, w 1.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: )
- text at x 3.2, y 45.3, w 10.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: priority
- text at x 13.2, y 45.3, w 6.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : INFO
- text at x 3.2, y 61.6, w 2.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: -
- text at x 5.2, y 61.6, w 4.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: rule
- text at x 9.2, y 61.6, w 23.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : program_accesses_file
- text at x 5.2, y 65.1, w 9.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: condition
- text at x 14.2, y 65.1, w 10.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : and not
- text at x 24.2, y 65.1, w 9.0, h 3.0 [RobotoMono-Regular; font size 2.96; #E3664C]: user.name
- text at x 33.2, y 65.1, w 5.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: =root
- text at x 5.2, y 68.6, w 6.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: output
- text at x 11.2, y 68.6, w 11.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : The file
- text at x 22.2, y 68.6, w 9.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFAB40]: %fd.name
- text at x 31.2, y 68.6, w 19.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: was opened by user
- text at x 50.2, y 68.6, w 10.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFAB40]: %user.name
- text at x 60.2, y 68.6, w 14.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: with program
- text at x 74.3, y 68.6, w 13.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFAB40]: %proc.cmdline
- text at x 5.2, y 72.1, w 8.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: override
- text at x 13.2, y 72.1, w 1.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: :
- text at x 8.2, y 75.7, w 9.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: condition
- text at x 17.2, y 75.7, w 8.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : append
- text at x 8.2, y 79.2, w 6.0, h 3.0 [RobotoMono-Bold; font size 2.96; #06ADC7]: output
- text at x 14.2, y 79.2, w 9.0, h 3.0 [RobotoMono-Regular; font size 2.96; #FFFFFF]: : replace

### Slide 13

**Review notes**

- Worth keeping: Keep the consistent teal template with the Falco mark, the clean timeline on slide 2, the four-tier status chips on slide 24, and the plain icon-plus-sentence layout of slides 13 and 22.

**Text**

Testing and Stability Improvement
● New kernel and Linux distribution versions for kernel testing
● Significantly expanded the e2e test suite to increase coverage
● Vastly increased the use of security checking tools which catch potential memory errors daily

**Layout**

Single-column text block on the left, title across the top left, and a stacked cluster of overlapping screenshots on the right. The title sits at top left with a left margin of about 3.4% and is left-aligned. The bulleted list is vertically centred in the left half, starting at about 34.6% of slide height and left-aligned at about 9.3%. The screenshots occupy the right half and overlap each other. The Falco logo sits at bottom right, about 87% from the left and 90% from the top. There is no footer, slide number or date.

**Visuals**

Four overlapping screenshots and one logo. (1) Top right, a dark-mode GitHub pull-request Checks panel, boxed with square corners, at about x 49.6%, y 12.6%, w 30.5%, h 66.4%. Its tabs read Conversation 4, Commits 1 and Checks 47 (Checks selected). Below is a commit line, 'fix(driver): CC variable for debian 8d12807', with a green circular check icon. Next is a 'Semgrep Checks' group, 'on: pull_request', and a partly visible 'check-absolut...' card reading 'succeeded yesterd...'. A bottom group, 'e2e C...', 'on: pul...', is cut off by the terminal. (2) White boxed table over the middle right, at about x 51.1%, y 33.2%, w 46.9%, h 38.2%, with columns KERNEL, CMAKE-CONFIGURE, KMOD BUILD, KMOD SCAP-OPEN, BPF-PROBE BUILD, BPF-PROBE SCAP-OPEN and MODERN-BPF SCAP-OPEN. Rows: amazonlinux2-4.19 (green dots in every column except MODERN-BPF SCAP-OPEN, which is yellow); amazonlinux2-5.10 (green dots in all six status columns); a row reading amazon... with 5.15 visible; a row reading amazon... with 6.1 visible; a row reading archlinu... (cut off). Green dots are filled circles. (3) Dark terminal log, a boxed image at about x 55.4%, y 47.3%, w 44.6%, h 52.7%, in front of the table and the Checks panel, with a monospace font on a near-black background. Lines, top to bottom: '[ OK ] sys_call_test.container_docker_bad_socket (5041 ms)'; '[ RUN ] sys_call_test.container_libvirt'; a rule of equals signs; a red line '==26348==ERROR: AddressSanitizer: heap-use-after-free on address 0x510000644180'; 'READ of size 8 at 0x510000644180 thread T89' in cyan; stack frames #0 to #8 (std::__cxx11::basic_string, std::operator==, std::operator!=, sinsp_parser::process_event, sinsp::next, event_capture::capture, execute_native_thread_routine, libc.so.6 entries), cut at the right edge; a green line '0x510000644180 is located 64 bytes inside of 184-byte region [0x510000644140,0x...'; a magenta line 'freed by thread T89 here:'; frames #0 to #4 (operator delete, sinsp_fdinfo::~sinsp_fdinfo, std::default_delete, std::__uniq_ptr_impl) cut at the right edge. (4) A placed image of 1024 by 850 pixels at about x 37.6%, y 25.7%, w 60.9%, h 74.3% is covered by the other screenshots and is not clearly visible. (5) Falco logo, bottom right at about x 87.1%, y 89.6%, w 8.7%, h 5.9%: a dark charcoal stylised X-shaped mark followed by the lowercase wordmark 'Falco' in dark charcoal bold sans-serif. Lighting is flat screenshot lighting with no photography.

**Design**

Background: Solid teal #04748C filling the whole slide. Flat teal background #04748C with no gradient or texture. Title and body text are white #FFFFFF. Title is Ubuntu Bold, about 5.9% of slide height, with normal tracking. Body is Ubuntu Regular, about 3.5% of slide height, with line spacing of about 4.1% between wrapped lines and about 8.1% between bullet paragraphs. Bullets are white filled round dots (●) set in Arial, at about 5.7% from the left, with hanging indents to about 9.3%. Screenshots are plain rectangles with square corners, layered with no visible shadows. Their dark UI is near-black #1E2227 with white and grey text and green #2DA44E status dots. The terminal uses a monospace font with red #FF4D4D, green #3DDC84, cyan #4DD0E1 and magenta #C678DD highlights on near-black #111317.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide solid background rectangle (No border, no shadow, fully opaque)
- photo at x 49.6, y 12.6, w 30.5, h 66.4 [#1E2227]: Screenshot of GitHub pull request Checks panel, dark mode, with tabs Conversation 4, Commits 1, Checks 47, commit fix(driver): CC variable for debian 8d12807, Semgrep Checks on: pull_request, check-absolut... succeeded yesterd..., e2e C... on: pul... (Square corners, no border, placed behind the table and terminal; top and right edges cut by its own frame; overlapped on the bottom by the table and terminal)
- photo at x 37.6, y 25.7, w 60.9, h 74.3 [#1E2227]: Placed image of 1024 by 850 pixels, mostly covered by the other screenshots (Behind the other screenshots; not clearly visible)
- table at x 51.1, y 33.2, w 46.9, h 38.2 [#FFFFFF]: Kernel build matrix with columns KERNEL, CMAKE-CONFIGURE, KMOD BUILD, KMOD SCAP-OPEN, BPF-PROBE BUILD, BPF-PROBE SCAP-OPEN, MODERN-BPF SCAP-OPEN; rows amazonlinux2-4.19 (green, green, green, green, green, yellow), amazonlinux2-5.10 (green in all six), amazon... 5.15 (cut off), amazon... 6.1 (cut off), archlinu... (cut off) (White boxed table, square corners, header labels in small caps dark grey sans-serif, thin light grey row dividers, green #2DA44E and yellow #F5C518 filled dots; cut off by the terminal at its bottom edge and overlapped on the right by the terminal)
- photo at x 55.4, y 47.3, w 44.6, h 52.7 [#111317]: Dark terminal screenshot of AddressSanitizer output: [ OK ] sys_call_test.container_docker_bad_socket (5041 ms); [ RUN ] sys_call_test.container_libvirt; ==26348==ERROR: AddressSanitizer: heap-use-after-free on address 0x510000644180; READ of size 8 at 0x510000644180 thread T89; stack frames #0 to #8; 0x510000644180 is located 64 bytes inside of 184-byte region; freed by thread T89 here; frames #0 to #4 (operator delete, sinsp_fdinfo::~sinsp_fdinfo, std::default_delete, std::__uniq_ptr_impl) (Monospace text, square corners, no border, in front of the table and the Checks panel; the right edge is cut by the slide edge and lines are cut off on the right; red #FF4D4D error line, cyan #4DD0E1 READ line, green #3DDC84 region line, magenta #C678DD freed line, light grey #D0D0D0 frames)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#222222]: Falco logo: dark charcoal X-shaped mark and wordmark Falco (Sits on top of the terminal's bottom-right corner area; no background behind it)
- title at x 3.4, y 3.7, w 54.8, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Testing and Stability Improvement
- bullet list at x 5.7, y 34.6, w 42, h 28 [Ubuntu Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ● New kernel and Linux distribution versions / for kernel testing / ● Significantly expanded the e2e test suite to / increase coverage / ● Vastly increased the use of security / checking tools which catch potential / memory errors daily (Three filled white round bullets (●) in Arial at x 5.7%, text hanging at x 9.3%; line pitch about 4.1% within a paragraph, paragraph pitch about 8.1%; left-aligned; no shadow)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 55.4, y 47.3, w 44.6, h 52.7: 1691 by 1139 pixels (covers the slide)
- image at x 37.6, y 25.7, w 60.9, h 74.3: 1024 by 850 pixels
- image at x 49.6, y 12.6, w 30.5, h 66.4: 475 by 582 pixels
- image at x 51.1, y 33.2, w 46.9, h 38.2: 1000 by 458 pixels
- image at x 51.1, y 69.1, w 46.9, h 30.9: 1000 by 458 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 54.8, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Testing and Stability Improvement
- text at x 5.7, y 34.6, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 9.3, y 34.6, w 37.9, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: New kernel and Linux distribution versions
- text at x 9.3, y 38.7, w 15.3, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: for kernel testing
- text at x 5.7, y 42.8, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 9.3, y 42.8, w 38.7, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Signiﬁcantly expanded the e2e test suite to
- text at x 9.3, y 46.8, w 15.8, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: increase coverage
- text at x 5.7, y 50.9, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 9.3, y 50.9, w 31.5, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Vastly increased the use of security
- text at x 9.3, y 55.0, w 32.3, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: checking tools which catch potential
- text at x 9.3, y 59.1, w 17.7, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: memory errors daily

### Slide 14

**Review notes**

- Review: The deck has a consistent teal identity, a clear section structure (slides 7, 14, 25, 31 as dividers) and a readable route from history to news to roadmap to community.

**Text**

Falco
Performance and
Reliability

**Layout**

Single left-aligned title block set in the lower-middle of the slide, with the Falco logo at top left. The title starts at about 4.2% from the left edge and sits roughly at mid-height. There is no footer, slide number or subtitle. The right half is empty apart from a faint decorative watermark in the bottom-right corner.

**Visuals**

Falco logo at top left: a stylised double-stroke X-and-arrow icon in dark teal next to the lowercase-style wordmark 'Falco' in dark teal #1B3A40. Behind everything is a full-bleed background image with a pale aqua watermark of the same X-and-arrow mark, drawn as thick rounded diagonal strokes. The strokes run from the upper-middle right (around x 68 to 88, y 40) down to the bottom-right corner, where they are cropped by the slide edge. The watermark is pale aqua, about #E3F6F8, on white, with no overlay.

**Design**

Background: White #FFFFFF full-bleed image with a pale aqua Falco X-mark watermark in the bottom-right; a #04748C fill lies beneath it and is covered. White background with a faint pale-aqua watermark in the bottom-right. Title text is near-black #171717 in Ubuntu Medium, set large and left-aligned with tight line spacing. Logo is dark teal #1B3A40. There are no accent colours beyond the watermark. Typeface is Ubuntu Medium, a humanist sans-serif with normal letter-spacing. Title cap height is about 7% of slide height (font size 8.89% of slide height). The measured fill #04748C sits beneath a full-bleed image, so it is not visible. No shadows, gradients or corner radii are visible apart from the rounded stroke ends of the watermark.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide filled rectangle beneath the background image, covered entirely by the image (Solid fill, no outline, no visible effect because the background image covers it completely)
- illustration at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-bleed background image (1200 by 628 px) showing a white field with a pale aqua watermark of the Falco X-and-arrow mark cropped at the bottom-right edge (Covers the whole slide and sits above the #04748C fill; watermark strokes are about #E3F6F8 with rounded ends, positioned roughly x 68 to 100 and y 40 to 100; no overlay or tint on the white area)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#1B3A40]: Falco logo: X-and-arrow icon with the wordmark 'Falco' (Icon is a double-stroke X with arrow-like ends in dark teal; wordmark in a rounded sans-serif, medium weight, dark teal #1B3A40; placed at the top-left corner)
- logo at x 87.1, y 89.6, w 8.7, h 5.9: Empty placeholder image box at bottom right (4 by 2 px); no visible content (Nothing visible in this box; the watermark strokes pass through this area but no separate mark is distinguishable)
- title at x 4.2, y 49.5, w 40.9, h 19.6 [Ubuntu Medium, normal weight, no italics, no capitals, normal letter-spacing; font size 8.89% of slide height; #171717; left aligned]: Performance and / Reliability (Two lines of title text; first line baseline at about 56% of slide height, second line starts at 60.2% of slide height; line spacing about 1.1 times the font size)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 4.2, y 49.5, w 40.9, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: Performance and
- text at x 4.2, y 60.2, w 23.5, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: Reliability

### Slide 15

**Review notes**

- Review: The execution weakens in the middle: slides 16 and 17 show blurred, unlabeled buffer images and slide 15 has an empty frame where the kernel module image should be, so the performance explanation does not land.
- Suggested repair: Replace the placeholder-looking images on slides 15 to 17 with labeled diagrams, restructure slide 12 as a clear before and after with readable annotations, and enlarge and simplify the flow on slide 20.

**Text**

The Busy Person's Tour of Falco Performance
Thousands to millions of events/second.
Optimize what matters.
Balance overhead and capabilities.
Falco

**Layout**

Single-column layout with the title across the top left at about 3.4% from the left edge and 5.4% from the top. Three rows of icon-plus-statement pairs sit down the left-centre, each icon left-aligned at about 6-8% from the left edge with its text starting about 18% from the left. The Falco logo sits in the bottom-right corner, with a margin of roughly 3% from the right and 10% from the bottom.

**Visuals**

Three white line/solid icons: a stopwatch (top, beside 'Thousands to millions of events/second.'), a light bulb (middle, beside 'Optimize what matters.'), and a balance scale with a central post and base (bottom, beside 'Balance overhead and capabilities.'). Each icon is white, roughly 4-7% of slide width. A photograph-like background shows a blue aerial/abstract image of a curving road or field pattern with fine horizontal streaking, filling the whole slide and tinted dark teal over the top, with the lighter blue detail visible on the right side and centre-right. The Falco logo at bottom right is a small dark stylised mark with the word 'Falco' in dark navy/black, sitting on the blue background.

**Design**

Background: Dark teal #04748C fill with a darkened blue aerial photograph of a curving road or field pattern covering the full slide, tinted to roughly #04475A overall.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Full-bleed blue aerial/abstract background image of a curving road or field pattern, tinted dark teal over the whole slide (Covers the entire slide behind all other elements; darkened overlay with a teal fill #04748C at reduced opacity; no crop shape; no border)
- title at x 3.4, y 5.4, w 71.3, h 5.9 [Ubuntu, Bold; font size 5.93% of slide height; #FFFFFF; left aligned]: The Busy Person's Tour of Falco Performance
- icon at x 7.7, y 26.9, w 5.2, h 10.7 [#FFFFFF]: Stopwatch icon (White solid outline stopwatch with top button and side pusher, no shadow)
- body at x 17.9, y 30.9, w 56, h 4.9 [Montserrat, Medium; font size 4.94% of slide height; #FFFFFF; left aligned]: Thousands to millions of events/second.
- icon at x 8.1, y 51.4, w 3.7, h 11.1 [#FFFFFF]: Light bulb icon (White solid light bulb silhouette with screw base)
- body at x 18.2, y 54.9, w 33.4, h 4.9 [Montserrat, Medium; font size 4.94% of slide height; #FFFFFF; left aligned]: Optimize what matters.
- icon at x 6.3, y 76, w 7.1, h 11.1 [#FFFFFF]: Balance scale icon (White solid balance scale with central post, top finial, two hanging pans and base)
- body at x 18.2, y 80.1, w 48.9, h 4.9 [Montserrat, Medium; font size 4.94% of slide height; #FFFFFF; left aligned]: Balance overhead and capabilities.
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0A1A24]: Falco logo (Small dark stylised double-slash mark followed by the word 'Falco' in bold dark sans-serif, placed bottom right)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2048 by 810 pixels (covers the slide)
- image at x 6.3, y 76.0, w 7.1, h 11.1: 108 by 95 pixels
- image at x 7.7, y 26.9, w 5.2, h 10.7: 94 by 109 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 8.1, y 51.4, w 3.7, h 11.1: 70 by 120 pixels
- text at x 3.4, y 5.4, w 71.3, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: The Busy Person's Tour of Falco Performance
- text at x 17.9, y 30.9, w 56.0, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Thousands to millions of events/second.
- text at x 18.2, y 54.9, w 33.4, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Optimize what matters.
- text at x 18.2, y 80.1, w 48.9, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Balance overhead and capabilities.

### Slide 16

**Review notes**

- Review: The execution weakens in the middle: slides 16 and 17 show blurred, unlabeled buffer images and slide 15 has an empty frame where the kernel module image should be, so the performance explanation does not land.
- Suggested repair: Replace the placeholder-looking images on slides 15 to 17 with labeled diagrams, restructure slide 12 as a clear before and after with readable annotations, and enlarge and simplify the flow on slide 20.

**Text**

Kernel Driver Options / Kernel Module / eBPF / Modern eBPF / (CO-RE) / Falco / CO-RE: Compile-Once-Run-Everywhere

**Layout**

Single slide with a title at top left and three equal-sized framed visuals in a row across the middle, each with a monospace label beneath it. The footnote sits bottom left and the Falco logo bottom right. Margins are roughly 3% left and right, and there is no slide number.

**Visuals**

Three framed visuals in a row, with no chart, table or photograph. (1) Left: an empty square outline with a white stroke of about 0.3% of slide width on the teal background, containing no image and no fill, labelled Kernel Module. (2) Centre: a square illustration with a white border showing a black and yellow striped bee in flat vector style, flying diagonally from upper right to lower left. Three pale cyan diagonal streaks run behind it from upper left to lower right, and the background is bright cyan (#14A9C2) with faint lighter speckles. It is labelled eBPF. (3) Right: a square illustration with a white border showing a bee-like robot seen from above: a black head with yellow eyes, grey mechanical legs and wing joints, translucent pale wings, a black and yellow striped abdomen, and cyan jet exhaust flames at the bottom of the legs. It has a blue-teal gradient background (#3A9FB5 to #5CB8CC) and a soft glow. It is labelled Modern eBPF (CO-RE). The two illustrations are not cropped, and they are boxed. The Falco logo is a dark stylised double-slash mark followed by the word Falco in a bold sans-serif, dark grey-black #1A1A1A.

**Design**

Background: Solid teal #04748C filling the whole slide. Flat teal background #04748C with no gradient, texture or border. The title is Ubuntu Bold, white #FFFFFF, at about 5.9% of slide height, left aligned. The labels are a bold monospace typeface, close to Courier New Bold, white #FFFFFF, at about 6% of slide height. The footnote is ArialMT regular, white #FFFFFF, at about 2.5% of slide height. Image frames have a 2px-style white #FFFFFF stroke with square corners and no shadow. Accent colours come from the illustrations: yellow #F5C518, black #111111 and cyan #14A9C2.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid rectangle covering the entire slide, no stroke, no shadow.)
- shape at x 10.1, y 24.4, w 22.2, h 36 [#04748C]: Empty square outline frame for Kernel Module option (Rectangle with no fill, 2px-style white #FFFFFF stroke, square corners, no image inside.)
- illustration at x 38, y 24.4, w 22.1, h 36 [#14A9C2]: eBPF bee illustration: black and yellow striped bee with cyan diagonal streaks on bright cyan background, boxed with white border (Square boxed image with white #FFFFFF border, square corners, not cropped, no overlay.)
- illustration at x 65.3, y 24.4, w 22.7, h 36 [#3A9FB5]: Modern eBPF (CO-RE) robotic bee illustration with jet exhaust on blue-teal background, boxed with white border (Square boxed image with white #FFFFFF border, square corners, not cropped, no overlay.)
- title at x 3.4, y 6.9, w 34.7, h 5.9 [Ubuntu Bold, bold weight, sentence case, no italics, no capitals transform, normal letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Kernel Driver Options
- caption at x 9.8, y 71.1, w 21.8, h 4 [Courier New Bold style monospace, bold weight, normal letter-spacing; font size 6% of slide height; #FFFFFF; center aligned]: Kernel Module
- caption at x 45.8, y 71.1, w 6.8, h 4 [Courier New Bold style monospace, bold weight, normal letter-spacing; font size 6% of slide height; #FFFFFF; center aligned]: eBPF
- caption at x 67.9, y 72, w 19, h 11 [Courier New Bold style monospace, bold weight, normal letter-spacing, two lines with the second line centred under the first; font size 6% of slide height; #FFFFFF; center aligned]: Modern eBPF / (CO-RE) (Line spacing about 1.6 lines, centred.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: double-slash mark with the word Falco (Dark grey-black mark and wordmark on the teal background, no box, no shadow.)
- footer at x 2.3, y 95.2, w 24.9, h 2.5 [ArialMT, regular weight, sentence case, no italics, normal letter-spacing; font size 2.47% of slide height; #FFFFFF; left aligned]: CO-RE: Compile-Once-Run-Everywhere

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 9.5, y 24.4, w 78.4, h 59.9: 1024 by 440 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 6.9, w 34.7, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Kernel Driver Options
- text at x 2.3, y 95.2, w 24.9, h 2.5 [ArialMT; font size 2.47; #FFFFFF]: CO-RE: Compile-Once-Run-Everywhere

### Slide 17

**Review notes**

- Review: The execution weakens in the middle: slides 16 and 17 show blurred, unlabeled buffer images and slide 15 has an empty frame where the kernel module image should be, so the performance explanation does not land.
- Suggested repair: Replace the placeholder-looking images on slides 15 to 17 with labeled diagrams, restructure slide 12 as a clear before and after with readable annotations, and enlarge and simplify the flow on slide 20.

**Text**

Kernel Buffers per CPU (pre-allocated memory)
Kernelspace
Userspace
Falco

**Layout**

Single full-bleed teal field with the title left-aligned across the top at about 7% from the top and 3% from the left edge. Four equal-width stacked image strips sit centred horizontally between the two labels, with Kernelspace on the left and Userspace on the right, both vertically aligned with the middle of the strips. The Falco logo sits in the bottom-right corner.

**Visuals**

Four stacked rectangular images, all the same width and horizontally centred, forming a vertical sequence from top to bottom. Top strip (8 by 5 px): a heavily pixelated, blocky mosaic of dark and mid teal squares, with a lighter band across the middle third and a brighter lower-right cluster. Second strip (32 by 17 px): a pixelated horizontal glowing band of light teal running left to right, brightest near the right third. Third strip (128 by 68 px): a softened, blurred version of a light-streaked horizon with a bright vertical cluster of pixels at the right third. Bottom strip (512 by 272 px): a smooth, high-detail render of light streaks converging on a glowing square microchip-like circuit motif at the right third, dark teal ground. All strips are boxed with hard rectangular edges, no border, no overlay, not cropped. Dominant colours are dark teal and pale cyan. Falco logo: a dark near-black stylised mark of crossed diagonal strokes with the wordmark Falco in bold dark sans-serif, at bottom right.

**Design**

Background: Solid teal #04748C. Flat teal background with white sans-serif title in Ubuntu Bold and white geometric sans-serif labels in Montserrat Medium. Title is bold, about 5.9% of slide height in capitals-and-lowercase. Labels are about 4.9% of slide height in regular weight. No shapes, lines or shadows beyond the image strips. Image strips have square corners and no shadow. Accent colour is pale cyan within the images only.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid flat fill covering the whole slide, no gradient, no border)
- photo at x 33, y 18.9, w 29.6, h 26.1 [#0A4F5E]: Pixelated mosaic image of teal blocks, 8 by 5 px source, top strip of the stack (Rectangular boxed image, square corners, no shadow, no overlay, not cropped, upscaled with hard pixel edges)
- photo at x 33, y 37.1, w 29.6, h 26.1 [#1C6A78]: Pixelated horizontal light band image, 32 by 17 px source, second strip from top (Rectangular boxed image, square corners, no shadow, no overlay, not cropped, upscaled with hard pixel edges)
- illustration at x 33, y 55.3, w 29.6, h 26.1 [#0E5A6A]: Blurred light-streak circuit image, 128 by 68 px source, third strip from top (Rectangular boxed image, square corners, no shadow, no overlay, not cropped)
- illustration at x 33, y 73.5, w 29.6, h 26.1 [#04606F]: Smooth light-streak circuit chip render, 512 by 272 px source, bottom strip (Rectangular boxed image, square corners, no shadow, no overlay, not cropped)
- title at x 3.4, y 6.9, w 75.1, h 5.9 [Ubuntu, bold, sentence case; font size 5.93% of slide height; #FFFFFF; left aligned]: Kernel Buffers per CPU (pre-allocated memory) (Single line)
- body at x 8.1, y 55.1, w 17.3, h 4.9 [Montserrat, medium, sentence case; font size 4.94% of slide height; #FFFFFF; left aligned]: Kernelspace (Single line, left of the image stack)
- body at x 68.8, y 55.1, w 14.6, h 4.9 [Montserrat, medium, sentence case; font size 4.94% of slide height; #FFFFFF; left aligned]: Userspace (Single line, right of the image stack)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0B1A1F]: Falco logo: stylised crossed diagonal mark with Falco wordmark (Dark near-black logo in bottom-right corner, no background box)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 33.0, y 73.5, w 29.6, h 26.1: 512 by 272 pixels
- image at x 33.0, y 55.3, w 29.6, h 26.1: 128 by 68 pixels
- image at x 33.0, y 37.1, w 29.6, h 26.1: 32 by 17 pixels
- image at x 33.0, y 18.9, w 29.6, h 26.1: 8 by 5 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 6.9, w 75.1, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Kernel Buﬀers per CPU (pre-allocated memory)
- text at x 8.1, y 55.1, w 17.3, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Kernelspace
- text at x 68.8, y 55.1, w 14.6, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Userspace

### Slide 18

**Text**

Kernel Buﬀers per (shared) CPU(s) - modern_ebpf
Kernelspace
Userspace
Falco

**Layout**

Single-column diagram on a plain teal field. The title sits top-left at about 7% from the top and 3.4% from the left edge, in one line. The two stacked blocks are centred horizontally at x 28.3% to 66.3%. The Kernelspace label sits left of the upper block and the Userspace label right of it, both on the same horizontal line at about 55% of the height. The Falco logo sits bottom-right at about 87% from the left and 90% from the top.

**Visuals**

Diagram with no arrows or connectors, made of two rectangular pixelated blocks. The upper block is a 4 by 3 pixel image, 38.0% wide and 33.5% high, with its top edge at 21.6% and its bottom edge at about 55.1%. It has three horizontal bands: the top band and bottom band are darker teal, about #054C5C, with four columns of slightly varying shade, and the middle band is lighter teal, about #135A69, with four columns of slightly varying shade. The lower block is a 2 by 2 pixel image, 38.0% wide and 33.5% high, with its top edge at 60.6%, made of two columns of dark teal blocks, about #0B4F5F on the left and #0C5566 on the right, with no visible band divisions. Both blocks are sharp-edged, unshadowed and unbordered. Labels: Kernelspace is the left label and Userspace the right label, both in white. Logo: the Falco logo (a dark near-black slash-mark icon followed by the wordmark Falco) is placed bottom-right, as a small raster image 4 by 2 pixels, 8.7% wide and 5.9% high, in a dark near-black colour, about #0A1A1F, on the teal background.

**Design**

Background: Solid flat teal fill #04748C covering the whole slide. Flat solid teal background with no gradient, texture or shadow. Title in white Ubuntu Bold, sans-serif, about 5.9% of slide height. Labels in white Montserrat Medium, sans-serif, about 4.9% of slide height, not capitalised. Accent colours are the dark teal blocks, about #054C5C and #0B4F5F, and the lighter middle band, about #135A69. The logo is near-black. Lines and shapes have square corners, no borders and no shadows.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide solid background rectangle (Flat fill, no border, no shadow, covers the slide edge to edge.)
- illustration at x 28.3, y 21.6, w 38, h 33.5 [#135A69]: Upper pixelated block, 4 by 3 pixel image representing kernel buffers for the shared CPUs, three horizontal bands, top and bottom darker, middle lighter (Sharp-edged rectangle, no border or shadow, not rotated, not cropped. Top and bottom bands about #054C5C, middle band about #135A69.)
- illustration at x 28.3, y 60.6, w 38, h 33.5 [#0B4F5F]: Lower pixelated block, 2 by 2 pixel image representing userspace buffers, two columns of dark teal (Sharp-edged rectangle, no border or shadow. Left half about #0B4F5F, right half about #0C5566.)
- title at x 3.4, y 6.9, w 78.6, h 5.9 [Ubuntu, bold, normal case, no letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Kernel Buﬀers per (shared) CPU(s) - modern_ebpf
- caption at x 8.1, y 55.1, w 17.3, h 4.9 [Montserrat, medium weight, normal case, no letter-spacing; font size 4.94% of slide height; #FFFFFF; left aligned]: Kernelspace (Label for the upper block, left side.)
- caption at x 68.8, y 55.1, w 14.6, h 4.9 [Montserrat, medium weight, normal case, no letter-spacing; font size 4.94% of slide height; #FFFFFF; left aligned]: Userspace (Label for the upper block, right side.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0A1A1F]: Falco logo: slash-mark icon followed by the wordmark Falco, bottom-right corner (Raster image 4 by 2 pixels, dark near-black mark on teal background, not cropped.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 28.3, y 21.6, w 38.0, h 33.5: 4 by 3 pixels
- image at x 28.3, y 60.6, w 38.0, h 33.5: 2 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 6.9, w 78.6, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Kernel Buﬀers per (shared) CPU(s) - modern_ebpf
- text at x 8.1, y 55.1, w 17.3, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Kernelspace
- text at x 68.8, y 55.1, w 14.6, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Userspace

### Slide 19

**Text**

Precise Control Over Monitored Syscalls (base_syscalls)
Syscalls activated / via Falco Rules
execve
openat
execvat
fork
clone3
procexit
vfork
close
clone
...
Syscalls required / by libsinsp to keep state
Mapping / to Linux architecture / specific Syscall IDs
Push map into / kernel driver
Userspace
Kernelspace
Falco

**Layout**

Single full-bleed teal slide with the title across the top-left at about 7% from the top, left-aligned at about 3.4% from the left edge. The main diagram runs left to right in the lower and middle area: a dashed outer group on the left, a central icon with arrows, a vertical dashed divider near 69% across, and a kernel-driver icon with its label to the right. The Userspace and Kernelspace labels sit in a row near the bottom, and the Falco logo sits at the bottom-right corner. No slide number or date is visible.

**Visuals**

Diagram with no photographs or charts. Left group: a large dashed white rounded rectangle (outer container) enclosing two dashed sub-boxes. The upper sub-box holds three outlined rounded tags labelled execve, openat and execvat, with a caption below it reading 'Syscalls activated via Falco Rules'. The lower sub-box holds tags labelled fork, clone3, procexit, vfork, close and clone, followed by an ellipsis of three dots, with a caption below reading 'Syscalls required by libsinsp to keep state'. Two solid white right-pointing block arrows run horizontally: the first from the left group to a central icon, the second from the central icon to a vertical divider. The central icon is a white solid triangular-rounded link/gear-like glyph with three circular holes, labelled 'Mapping to Linux architecture specific Syscall IDs'. A vertical dotted white line separates Userspace on the left from Kernelspace on the right. On the right is a white icon of a stacked block: three horizontal bars above a rounded rectangle with a small slot, representing a kernel driver, labelled 'Push map into kernel driver'. Falco logo at bottom right: a stylised dark-navy crossed-arrow mark followed by the word Falco in dark navy bold sans-serif. Lighting and shading are flat; there is no photograph.

**Design**

Background: Solid teal #04748C filling the whole slide. Flat teal background with no gradient or texture. Title and all diagram text are white (#FFFFFF). Accent elements are white strokes and white fills. Title in Ubuntu Bold, sentence-style capitalisation, about 5.9% of slide height. Body and labels in Ubuntu Regular, about 2.8% of slide height. Userspace and Kernelspace are Ubuntu Bold, about 2.5%. Dashed outlines are thin white (about 1.5px at 2000px width) with small corner radii (about 1% of width). Tags are rounded rectangles with about 0.5% corner radius, teal fill, 1px white outline. Arrows are solid white with flat heads. The divider is a vertical row of white dots. Falco logo mark and wordmark are dark navy (#0B1F2A approximate).

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid flat fill, no border, covers entire slide.)
- shape at x 15.4, y 17.2, w 24.1, h 75.3 [#04748C]: Outer dashed container around left group (Dashed white stroke about 1.5px, corner radius about 1% of width, no fill.)
- shape at x 17.4, y 20.8, w 20.2, h 22.5 [#04748C]: Upper dashed sub-box for Falco rule syscalls (Dashed white stroke about 1.5px, corner radius about 1% of width, no fill.)
- shape at x 19.75, y 25.7, w 7.2, h 5.1 [#04748C]: Tag execve (Rounded rectangle, 1px white outline, corner radius about 0.5% of width, no shadow.)
- shape at x 28, y 30.2, w 7.4, h 5 [#04748C]: Tag openat (Rounded rectangle, 1px white outline, corner radius about 0.5% of width, no shadow.)
- shape at x 19.1, y 35.6, w 7.85, h 5.1 [#04748C]: Tag execvat (Rounded rectangle, 1px white outline, corner radius about 0.5% of width, no shadow.)
- body at x 18.1, y 44.9, w 12.4, h 6.2 [Ubuntu, regular; font size 2.8% of slide height; #FFFFFF; left aligned]: Syscalls activated / via Falco Rules (Two lines, line spacing about 1.2.)
- shape at x 17.4, y 59.4, w 20.2, h 22.4 [#04748C]: Lower dashed sub-box for libsinsp required syscalls (Dashed white stroke about 1.5px, corner radius about 1% of width, no fill.)
- shape at x 20.4, y 61.7, w 5.25, h 5 [#04748C]: Tag fork (Rounded rectangle, 1px white outline, corner radius about 0.5% of width.)
- shape at x 27.55, y 62.1, w 7.05, h 5 [#04748C]: Tag clone3 (Rounded rectangle, 1px white outline, corner radius about 0.5% of width.)
- shape at x 19.8, y 68, w 8.2, h 5 [#04748C]: Tag procexit (Rounded rectangle, 1px white outline, corner radius about 0.5% of width.)
- shape at x 29.45, y 68.6, w 6.05, h 5 [#04748C]: Tag vfork (Rounded rectangle, 1px white outline, corner radius about 0.5% of width.)
- shape at x 19.2, y 74.7, w 6, h 5 [#04748C]: Tag close (Rounded rectangle, 1px white outline, corner radius about 0.5% of width.)
- shape at x 26.35, y 74.7, w 6.2, h 5 [#04748C]: Tag clone (Rounded rectangle, 1px white outline, corner radius about 0.5% of width.)
- body at x 33.75, y 77.3, w 2, h 1.4 [Ubuntu, bold; #FFFFFF; center aligned]: ... (Three white dots in a horizontal row.)
- body at x 18.1, y 83.7, w 17.2, h 6.4 [Ubuntu, regular; font size 2.8% of slide height; #FFFFFF; left aligned]: Syscalls required / by libsinsp to keep state (Two lines, line spacing about 1.2.)
- shape at x 41, y 48.9, w 7.4, h 4.3 [#FFFFFF]: Block arrow from left group to central icon (Solid white right-pointing arrow, shaft about 40% of height, flat triangular head.)
- icon at x 49.75, y 40.9, w 9.25, h 16.5 [#FFFFFF]: Mapping icon: triangular link glyph with three circular holes (Solid white rounded-triangle shape with three circular cut-outs, one at upper right, one at left and one at lower right.)
- shape at x 60.3, y 48.5, w 7.5, h 4.3 [#FFFFFF]: Block arrow from central icon to divider (Solid white right-pointing arrow, shaft about 40% of height, flat triangular head.)
- line at x 69, y 16.9, w 0.2, h 76.9 [#FFFFFF]: Vertical dotted divider between Userspace and Kernelspace (Row of white dots, about 1% of width each, evenly spaced.)
- icon at x 73.4, y 43.2, w 6.7, h 11.9 [#FFFFFF]: Kernel driver icon: three horizontal bars above a rounded block with a slot and two bars to the right (Solid white shapes: two full-width top bars, one rounded rectangle with a dark-teal inner slot at lower left, two short bars at lower right.)
- body at x 46.6, y 64.2, w 15.2, h 9.6 [Ubuntu, regular; font size 2.8% of slide height; #FFFFFF; center aligned]: Mapping / to Linux architecture / specific Syscall IDs (Three lines, line spacing about 1.2.)
- body at x 71.7, y 64.2, w 10.1, h 6.2 [Ubuntu, regular; font size 2.8% of slide height; #FFFFFF; center aligned]: Push map into / kernel driver (Two lines, line spacing about 1.2.)
- footer at x 56.8, y 92.3, w 7.7, h 2.8 [Ubuntu, bold; font size 2.5% of slide height; #FFFFFF; left aligned]: Userspace
- footer at x 72.2, y 92.3, w 9.2, h 2.8 [Ubuntu, bold; font size 2.5% of slide height; #FFFFFF; left aligned]: Kernelspace
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0B1F2A]: Falco logo: crossed-arrow mark and Falco wordmark (Dark navy mark and bold sans-serif wordmark on the teal background.)
- title at x 3.4, y 6.9, w 88.3, h 5.9 [Ubuntu, bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Precise Control Over Monitored Syscalls (base_syscalls) (Single line, sentence-style capitalisation.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 11.2, y 2.0, w 75.4, h 98.0: 1024 by 789 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 6.9, w 88.3, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Precise Control Over Monitored Syscalls (base_syscalls)

### Slide 20

**Review notes**

- Worth studying: A simple flow diagram with yes and no branches explains a kernel filtering decision in a few shapes.
- Review: Slide 12's override example is hard to follow, with a struck-through output, handwritten green highlights and a second rule that does not obviously map to the first, and slide 20's diagram has small text and an unclear flow.
- Suggested repair: Replace the placeholder-looking images on slides 15 to 17 with labeled diagrams, restructure slide 12 as a clear before and after with readable annotations, and enlarge and simplify the flow on slide 20.

**Text**

Precise Control Over Monitored Syscalls (base_syscalls)
Syscall of interest?
Yes
Syscall triggers
at hookpoint
No
driver
extract data fields
no operation
·
* drop extraction
Falco's monitoring process
is passive and does not
modify the behavior of
the monitored kernel actions,
such as syscalls
push
pop
Kernelspace
Userspace
Falco

**Layout**

Single full-bleed teal slide with a left-aligned bold title across the top (x 3.4%, y 6.9%) and a wide diagram below it that flows left to right: trigger, decision, a tall rounded Kernelspace box, a dotted vertical boundary line, then Userspace icons on the right. The Kernelspace and Userspace labels sit side by side at the bottom beneath the boundary, and the Falco logo sits bottom right at about x 87%, y 90%. No page number or footer text is visible.

**Visuals**

Diagram with no chart data. Shapes and labels, in order: (1) an open white outlined triangle pointing right at about x 3.4%, y 42.2%, w 7.0%, h 12.2%, labelled by the text 'Syscall triggers at hookpoint' below it. (2) A white horizontal arrow with a solid triangular head from the triangle to the decision shape. (3) A large open white outlined triangle at about x 21.6%, y 39.7%, w 6.4%, h 13.6%, with the question 'Syscall of interest?' above it. (4) A white arrow labelled 'Yes' running right from the decision shape to the left edge of the tall rounded box. (5) A thick white diagonal arrow labelled 'No' running from the decision shape down-right to the 'drop extraction' box. (6) A tall rounded white-outlined rectangle at about x 39.9%, y 26.0%, w 18.4%, h 46.2% (Kernelspace process) containing three stacked rounded boxes: 'driver' at about x 45.0%, y 28.9%, w 8.2%, h 6.2%; 'extract data fields' at about x 42.7%, y 41.4%, w 12.8%, h 9.6%; and 'no operation / · / * drop extraction' at about x 41.5%, y 56.0%, w 15.2%, h 13.3%. (7) A dotted white line from the 'drop extraction' box leading down-left to a small white pointing-hand icon at about x 37.9%, y 68.9%, w 1.0%, h 3.6%, which points at the callout. (8) A rounded-rectangle callout at about x 30.8%, y 73.9%, w 19.0%, h 14.8% with the explanatory text. (9) A white arrow labelled 'push' at about x 58.9%, y 47.3%, w 6.5%, from the Kernelspace box to a dotted white circle (orbit of dots) at about x 66.5%, y 36.4%, w 12.3%, h 21.8%, which sits on a vertical dotted white line at x 72.6% from y 16.6% to 86.6%. (10) A white arrow labelled 'pop' at about x 80.4%, y 47.3%, w 7.4%, pointing right to three white icons: a clock (about x 91.1%, y 24.0%, w 5.0%, h 9.0%), a video camera on a tripod (about x 91.9%, y 39.9%, w 4.2%, h 13.2%) and an org-chart hierarchy icon (about x 90.9%, y 58.6%, w 6.2%, h 9.5%). The clock is a white filled circle with teal hands and ticks, the camera is white with a teal lens, and the hierarchy icon shows white boxes joined by lines. (11) The Falco logo (a dark stylised slash mark with the wordmark 'Falco') at about x 87.1%, y 89.6%, w 8.7%, h 5.9%.

**Design**

Background: Solid flat teal #04748C covering the entire slide. Flat, minimal diagram style with no gradients or shadows. Background is teal #04748C. Title text, body text, labels, arrows, outlines and icons are all white #FFFFFF; the Falco logo is near-black #1A1A1A. The title is a bold humanist sans (Ubuntu Bold) at about 5.9% of slide height, with text labels in Montserrat Medium at about 3.5% to 4.4% of slide height and box text in Ubuntu regular at about 2.0% of slide height. Strokes are white, about 0.3% of slide height thick, with rounded corners of about 1.5% radius on the boxes and the Kernelspace box. Arrows have solid triangular heads. Dotted elements use round white dots about 0.6% of slide height in diameter.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background rectangle, flat teal fill (No stroke, no shadow, opacity 100%)
- title at x 3.4, y 6.9, w 88.3, h 5.9 [Ubuntu Bold, weight bold, normal case, no letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Precise Control Over Monitored Syscalls (base_syscalls)
- shape at x 3.4, y 42.2, w 7, h 12.2 [#04748C]: Open triangle pointing right, the trigger (White stroke about 0.3% of slide height, no fill, sharp corners)
- line at x 12.5, y 46.4, w 6.8, h 1.5 [#FFFFFF]: Arrow from trigger to decision (White line about 0.3% of slide height with solid triangular head at right end)
- shape at x 21.6, y 39.7, w 6.4, h 13.6 [#04748C]: Open bold triangle pointing right, the syscall-of-interest decision (Thick white stroke about 0.5% of slide height, no fill, sharp corners; the Yes and No arrows start from its tip)
- caption at x 11.2, y 27.9, w 23.4, h 4.4 [Montserrat Medium, weight medium, normal case, no letter-spacing; font size 4.44% of slide height; #FFFFFF; left aligned]: Syscall of interest?
- line at x 28, y 46.4, w 10.9, h 1.5 [#FFFFFF]: Arrow labelled Yes from decision to Kernelspace box (White line about 0.3% of slide height with solid triangular head at right end)
- caption at x 29.6, y 40.3, w 3.3, h 3.5 [Montserrat Medium, weight medium, normal case, no letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: Yes
- line at x 23.8, y 46.4, w 15, h 15.4 [#FFFFFF]: Diagonal arrow labelled No from decision to drop extraction box (Thick white line about 0.5% of slide height with solid triangular head at lower-right end)
- caption at x 28.8, y 57, w 2.8, h 3.5 [Montserrat Medium, weight medium, normal case, no letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: No
- caption at x 2.2, y 59.4, w 17.6, h 8.8 [Montserrat Medium, weight medium, normal case, no letter-spacing; font size 3.95% of slide height; #FFFFFF; left aligned]: Syscall triggers / at hookpoint (Line spacing about 4.8% of slide height between the two lines)
- shape at x 39.9, y 26, w 18.4, h 46.2 [#04748C]: Kernelspace process box, rounded rectangle containing three stacked boxes (White stroke about 0.2% of slide height, corner radius about 1.5% of slide width, no fill, no shadow)
- shape at x 45, y 28.9, w 8.2, h 6.2 [#04748C]: driver box (Rounded rectangle, white stroke about 0.15% of slide height, corner radius about 1% of slide width, no fill)
- caption at x 45, y 28.9, w 8.2, h 6.2 [Ubuntu, weight regular, normal case, no letter-spacing; font size 3% of slide height; #FFFFFF; center aligned]: driver (Text vertically centred in its box)
- shape at x 42.7, y 41.4, w 12.8, h 9.6 [#04748C]: extract data fields box (Rounded rectangle, white stroke about 0.15% of slide height, corner radius about 1% of slide width, no fill)
- caption at x 42.7, y 41.4, w 12.8, h 9.6 [Ubuntu, weight regular, normal case, no letter-spacing; font size 3.6% of slide height; #FFFFFF; center aligned]: extract / data fields (Two lines, centred in box, line spacing about 4.4% of slide height)
- shape at x 41.5, y 56, w 15.2, h 13.3 [#04748C]: no operation / drop extraction box (Rounded rectangle, white stroke about 0.15% of slide height, corner radius about 1% of slide width, no fill)
- caption at x 41.5, y 56, w 15.2, h 13.3 [Ubuntu, weight regular, normal case, no letter-spacing; font size 3.6% of slide height; #FFFFFF; center aligned]: no operation / · / * drop extraction (Three lines centred in box; the middle line is a small dot; the last line begins with an asterisk and is followed by 'drop extraction'; a dotted leader line runs from the asterisk to the pointing hand)
- icon at x 37.9, y 68.9, w 1, h 3.6 [#FFFFFF]: Small white pointing-hand icon (Solid white hand with index finger pointing up toward the drop extraction line)
- line at x 38.5, y 66.2, w 3.5, h 2.6 [#FFFFFF]: Dotted leader line from the drop extraction box to the pointing hand (Dotted white line, dots about 0.4% of slide height in diameter, spacing about 1%)
- shape at x 30.8, y 73.9, w 19, h 14.8 [#04748C]: Callout rounded rectangle with explanatory text (White stroke about 0.15% of slide height, corner radius about 1.5% of slide width, no fill, no shadow)
- caption at x 31.5, y 75, w 17.7, h 12.8 [Ubuntu, weight regular, normal case, no letter-spacing; font size 2% of slide height; #FFFFFF; center aligned]: Falco's monitoring process / is passive and does not / modify the behavior of / the monitored kernel actions, / such as syscalls (Five centred lines, line spacing about 2.7% of slide height)
- line at x 72.6, y 16.6, w 0.3, h 70 [#FFFFFF]: Dotted vertical boundary line between Kernelspace and Userspace (Vertical row of round white dots about 0.6% of slide height in diameter, spacing about 2.6%)
- shape at x 66.5, y 36.4, w 12.3, h 21.8 [#FFFFFF]: Dotted white circle (orbit of dots) on the boundary line (Two concentric rings of round white dots, outer ring about 12.3% of slide width, inner ring smaller; the dots are the only fill, no stroke)
- line at x 58.9, y 47.3, w 6.5, h 1.5 [#FFFFFF]: Arrow labelled push from Kernelspace box to boundary (White line about 0.3% of slide height with solid triangular head and a small square tail at left end)
- caption at x 60, y 49.8, w 4.3, h 3.1 [Ubuntu, weight regular, normal case, no letter-spacing; font size 3.6% of slide height; #FFFFFF; left aligned]: push
- line at x 80.4, y 47.3, w 7.4, h 1.5 [#FFFFFF]: Arrow labelled pop from boundary to icons (White line about 0.3% of slide height with solid triangular head and a small square tail at left end)
- caption at x 82, y 49.8, w 3.5, h 3.1 [Ubuntu, weight regular, normal case, no letter-spacing; font size 3.6% of slide height; #FFFFFF; left aligned]: pop
- icon at x 91.1, y 24, w 5, h 9 [#FFFFFF]: Clock icon (White filled circle with teal hour and minute hands and tick marks)
- icon at x 91.9, y 39.9, w 4.2, h 13.2 [#FFFFFF]: Video camera on tripod icon (White camera body with two reels on top and a lens, on a white tripod)
- diagram at x 90.9, y 58.6, w 6.2, h 9.5 [#FFFFFF]: Org-chart hierarchy icon: one box on top, three boxes in a row, then three boxes below (White rectangular boxes joined by white connector lines)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: dark slash mark and wordmark Falco (Dark near-black mark with diagonal strokes to the left of the wordmark Falco in a bold sans)
- caption at x 56.5, y 84.4, w 11.4, h 3.1 [Ubuntu Bold, weight bold, normal case, no letter-spacing; font size 3.9% of slide height; #FFFFFF; left aligned]: Kernelspace
- caption at x 77, y 84.4, w 9.7, h 3.1 [Ubuntu Bold, weight bold, normal case, no letter-spacing; font size 3.9% of slide height; #FFFFFF; left aligned]: Userspace

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 1.3, y 57.1, w 17.9, h 11.1: #04748C
- fill at x 62.3, y 59.5, w 10.2, h 12.0: #04748C
- fill at x 16.2, y 19.5, w 18.3, h 15.0: #04748C
- fill at x 77.3, y 19.5, w 17.9, h 15.0: #04748C
- image at x 0.0, y 3.4, w 100.0, h 88.6: 2048 by 717 pixels (covers the slide)
- image at x 90.9, y 58.6, w 6.2, h 9.5: 135 by 116 pixels
- image at x 91.9, y 39.9, w 4.2, h 13.2: 69 by 121 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 91.1, y 24.0, w 5.0, h 9.0: 102 by 102 pixels
- text at x 3.4, y 6.9, w 88.3, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Precise Control Over Monitored Syscalls (base_syscalls)
- text at x 11.2, y 27.9, w 23.4, h 4.4 [Montserrat-Medium; font size 4.44; #FFFFFF]: Syscall of interest?
- text at x 29.6, y 40.3, w 3.3, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: Yes
- text at x 2.2, y 59.4, w 17.6, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Syscall triggers
- text at x 2.2, y 64.2, w 14.5, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: at hookpoint
- text at x 28.8, y 57.0, w 2.8, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: No

### Slide 21

**Text**

Userspace state engine / Inspect time-ordered incoming / (kernel) events as fast as possible. / Process and container caches, / correlations, rules matching. / Reduce processing time to scale / to modern infrastructures. / Falco

**Layout**

Two-column split: a solid teal text panel fills the left 63.6% of the slide, and a full-height illustration fills the right 36.4% edge to edge. The title sits top-left at about 6.6% from the top and 3.4% from the left. Three icon-and-text rows are stacked in the left column, with the icons at x 4 to 10% and the text starting at x about 15%, left-aligned. No footer or slide number is visible.

**Visuals**

1) Magnifying-glass icon, white line icon, at left of row 1, roughly 4% to 8% across and 27% to 38% down. 2) Jigsaw-puzzle-piece icon, solid white, at left of row 2, about 4% to 10% across and 52% to 63% down. 3) Rising bar-and-line chart icon, solid white bars with a white trend line ending in an arrowhead, at left of row 3, about 4% to 10% across and 78% to 87% down. 4) Right-panel illustration, a stylised top-down technical scene with no people or text beyond the logo. Composition: four rounded-octagon panels in a 2x2 grid, filled sage green (top-left, about #6B8A63), warm taupe (top-right, about #6E6A5C), mid green (bottom-left, about #3A8A6E) and light green (bottom-right, about #7DAA6E). Each panel has faint lighter seams and small grey-blue tabs on its outer edges. Blue-grey braided hoses (about #5E8FA3) with segment ridges run between them. Top-left panel holds a triangular play-shaped funnel outline; top-right panel holds a coiled spiral hose; a teal capsule node (about #4E8EA0) sits at the centre with a small glowing cyan emblem (about #1FA9C4); a hexagonal coiled cell sits bottom-left; a canister-shaped cylinder with two cyan dots sits bottom-right. A dark teal cone protrudes from the left edge of the image. Lighting is flat with no visible light source; the whole image is overlaid with a dark navy-teal tint (about #0B4A66 at roughly 35% opacity) so colours are muted. A darker vertical band (about #245E6E) runs along the image's left edge. The image is not cropped and is placed full-bleed to the top, bottom and right edges. 5) Falco wordmark logo, bottom-right of the illustration, at about 87% to 96% across and 90% to 95% down, rendered in a muted olive-gold (about #8A7A3A) with a stylised X-shaped mark to the left of the word 'Falco'.

**Design**

Background: Solid teal #04748C behind everything on the left, with the illustration covering the right 36.4% of the slide. Flat, minimal two-tone design. Background is solid teal. Title is set in a bold humanist sans-serif (Ubuntu Bold) at about 5.9% of slide height, white. Body text is a geometric sans-serif (Montserrat Medium) at about 4.9% of slide height, white, sentence case, normal tracking, left-aligned, with about 6% line spacing between wrapped lines of the same item. Accent colours: white icons on teal, and the illustration palette of greens, taupe and blue-grey. Icons are solid or outlined white with no shadows. Shapes have no visible borders or radii beyond the illustration's rounded octagons. No gradients or shadows are visible on text; the illustration has a soft shadow-like darkening at the seam with the teal panel.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide solid background rectangle (Solid fill, no border, no shadow, covers the entire slide.)
- illustration at x 63.6, y 0, w 36.4, h 100 [#3A8A6E]: Right-hand technical illustration of four octagonal panels with hoses, hexagonal cell, canister and cone, under a dark teal tint (Full-bleed to top, bottom and right edges, not cropped; dark navy-teal overlay about 35% opacity; left edge darker band about #245E6E.)
- title at x 3.4, y 6.6, w 36.9, h 5.9 [Ubuntu, Bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Userspace state engine
- icon at x 3.9, y 27.3, w 5, h 10.5 [#FFFFFF]: Magnifying glass icon (White outline lens with thick diagonal handle, no fill.)
- body at x 14.7, y 27.1, w 47.3, h 10.8 [Montserrat, Medium; font size 4.94% of slide height; #FFFFFF; left aligned]: Inspect time-ordered incoming / (kernel) events as fast as possible. (Two lines; line pitch about 5.9% of slide height.)
- icon at x 4.2, y 52.5, w 6.1, h 10.9 [#FFFFFF]: Puzzle piece icon (Solid white jigsaw piece with tabs on top-right and bottom, no outline.)
- body at x 15, y 51.4, w 43.3, h 10.9 [Montserrat, Medium; font size 4.94% of slide height; #FFFFFF; left aligned]: Process and container caches, / correlations, rules matching. (Two lines; line pitch about 6.0% of slide height.)
- icon at x 4.2, y 78.2, w 6.1, h 8.6 [#FFFFFF]: Rising bar and line chart icon (Solid white vertical bars of increasing height with a white rising trend line ending in an arrowhead.)
- body at x 15, y 77.7, w 45.7, h 10.9 [Montserrat, Medium; font size 4.94% of slide height; #FFFFFF; left aligned]: Reduce processing time to scale / to modern infrastructures. (Two lines; line pitch about 6.0% of slide height.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#8A7A3A]: Falco wordmark logo (Muted olive-gold X-shaped mark with the word Falco, placed over the bottom-right canister panel, no outline.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 63.6, y 0.0, w 36.4, h 100.0: 1024 by 564 pixels
- image at x 4.2, y 52.5, w 6.1, h 10.9: 102 by 102 pixels
- image at x 4.2, y 78.2, w 6.1, h 8.6: 112 by 88 pixels
- image at x 3.9, y 27.3, w 5.0, h 10.5: 93 by 110 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 6.6, w 36.9, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Userspace state engine
- text at x 14.7, y 27.1, w 45.1, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Inspect time-ordered incoming
- text at x 14.7, y 33.0, w 47.3, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: (kernel) events as fast as possible.
- text at x 15.0, y 51.4, w 43.3, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Process and container caches,
- text at x 15.0, y 57.4, w 40.1, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: correlations, rules matching.
- text at x 15.0, y 77.7, w 45.7, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Reduce processing time to scale
- text at x 15.0, y 83.7, w 37.0, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: to modern infrastructures.

### Slide 22

**Review notes**

- Worth keeping: Keep the consistent teal template with the Falco mark, the clean timeline on slide 2, the four-tier status chips on slide 24, and the plain icon-plus-sentence layout of slides 13 and 22.

**Text**

Risks / Slowing down the / kernel or applications / Dropping events on / busy servers / Create backpressure / Cause increased kernel / side event drops / Kernelspace / Userspace

**Layout**

Flat composition on a single teal field. The title Risks sits top-left at about 3.4% from the left edge and 6.9% from the top. Two text blocks sit left of centre and two sit right of centre, framing a central dotted illustration on the vertical midline at about x 49%. The Kernelspace and Userspace labels sit near the bottom, on either side of the dotted line, and the Falco logo sits bottom-right at about 87% from the left and 90% from the top. Text is left-aligned in each block.

**Visuals**

One dotted illustration centred on the slide. A vertical dotted white line runs from about 18% to about 92% of the slide height at x about 49.2%. It passes through a concentric pair of dotted white rings, an outer ring about 14.6% wide and 24% tall and a smaller inner ring, centred at about x 49.3%, y 50%. The dots are small white filled circles of uniform size. Three flat teal rectangles (#04748C, no stroke) lie over the lower part of the dotted line behind the Kernelspace and Userspace labels. In the bottom-right corner is the Falco logo: a stylised dark stroke mark followed by the dark wordmark Falco in a bold sans-serif, dark near-black (#1A1A1A) on the teal. No photographs.

**Design**

Background: Solid teal #04748C across the whole slide. Flat solid teal background #04748C with no gradient, texture or shadow. Title Risks is set in Ubuntu Bold, white #FFFFFF, about 5.9% of slide height, which is the largest text. Body text is Montserrat Medium, white #FFFFFF, about 4.9% of slide height, in sentence case with no italics or capitals. The illustration uses white dots (#FFFFFF) with no outlines. Line spacing of the body blocks is about 1.2 times the font size. Shapes are sharp-cornered and unshadowed.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Flat solid rectangle covering the entire slide, no stroke, no shadow.)
- line at x 49.2, y 18, w 0.6, h 74 [#FFFFFF]: Vertical dotted centre line (Row of uniform white dots, about 0.6% of slide width each, spaced evenly, running vertically through the slide centre and passing behind the teal rectangles at the bottom.)
- illustration at x 41.5, y 38.5, w 14.6, h 24 [#FFFFFF]: Concentric dotted rings centred on the vertical dotted line, outer and inner circular rings of white dots (Two concentric dotted rings of white dots, outer ring about 14.6% wide and inner ring smaller, both centred on the vertical line, no fill.)
- shape at x 36.8, y 63.7, w 12.1, h 15 [#04748C]: Teal rectangle masking the dotted line behind the Kernelspace label area, upper (Solid #04748C rectangle, no stroke, no shadow, overlapping the dotted illustration.)
- shape at x 36.3, y 81.7, w 12.1, h 15 [#04748C]: Teal rectangle masking the dotted line behind the Kernelspace label area, lower-left (Solid #04748C rectangle, no stroke, no shadow, overlapping the dotted illustration.)
- shape at x 50.1, y 81.7, w 12.1, h 15 [#04748C]: Teal rectangle masking the dotted line behind the Userspace label area (Solid #04748C rectangle, no stroke, no shadow, overlapping the dotted illustration.)
- title at x 3.4, y 6.9, w 8.4, h 5.9 [Ubuntu, bold, sans-serif; font size 5.93% of slide height; #FFFFFF; left aligned]: Risks (Upright, no capitals beyond the R, no letter-spacing.)
- body at x 6, y 38.1, w 30.5, h 10.8 [Montserrat, medium, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: Slowing down the / kernel or applications (Two lines, upright, sentence case, no letter-spacing, line spacing about 1.2 times font size.)
- body at x 61.5, y 41, w 29, h 4.9 [Montserrat, medium, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: Create backpressure (Single line, upright, sentence case.)
- body at x 6, y 55.9, w 28.8, h 10.8 [Montserrat, medium, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: Dropping events on / busy servers (Two lines, upright, sentence case, line spacing about 1.2 times font size.)
- body at x 61.5, y 52.9, w 33.4, h 10.8 [Montserrat, medium, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: Cause increased kernel / side event drops (Two lines, upright, sentence case, line spacing about 1.2 times font size.)
- caption at x 21.8, y 85, w 17.3, h 4.9 [Montserrat, medium, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: Kernelspace (Single line label, upright, sentence case.)
- caption at x 59.2, y 84.2, w 14.6, h 4.9 [Montserrat, medium, sans-serif; font size 4.94% of slide height; #FFFFFF; left aligned]: Userspace (Single line label, upright, sentence case.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: stylised dark mark and Falco wordmark (Dark near-black mark and wordmark on the teal background, no background box.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 36.3, y 81.7, w 12.1, h 15.0: #04748C
- fill at x 36.8, y 63.7, w 12.1, h 15.0: #04748C
- fill at x 50.1, y 81.7, w 12.1, h 15.0: #04748C
- image at x 0.0, y 4.0, w 100.0, h 94.4: 2048 by 717 pixels (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 6.9, w 8.4, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Risks
- text at x 6.0, y 38.1, w 26.3, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Slowing down the
- text at x 61.5, y 41.0, w 29.0, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Create backpressure
- text at x 6.0, y 44.0, w 30.5, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: kernel or applications
- text at x 61.5, y 52.9, w 33.4, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Cause increased kernel
- text at x 6.0, y 55.9, w 28.8, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Dropping events on
- text at x 61.5, y 58.8, w 23.2, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: side event drops
- text at x 6.0, y 61.8, w 17.5, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: busy servers
- text at x 21.8, y 85.0, w 17.3, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Kernelspace
- text at x 59.2, y 84.2, w 14.6, h 4.9 [Montserrat-Medium; font size 4.94; #FFFFFF]: Userspace

### Slide 23

**Text**

New CNCF Benchmarking Initiatives
CNCF Environmental Sustainability TAG
Green Reviews Working Group

Falco as First Project
Starting the Journey Towards Enhanced Performance
New Falco Metrics Framework
https://github.com/falcosecurity/cncf-green-review-testing

**Layout**

Centred text block with no title placeholder: six bold lines in two groups separated by one blank line, centred horizontally across roughly the middle 60 percent of the slide and vertically from about 30 to 78 percent of the height. A small underlined URL sits bottom-left at about 1.3 percent from the left edge and 94.6 percent from the top. The Falco logo sits bottom-right at about 87 percent from the left and 90 percent from the top. No slide number or footer is visible.

**Visuals**

Full-bleed photograph of a symmetrical tunnel of teal light streaks radiating from a central vanishing point, with bright cyan lines, faint blue-violet glints, and green lit panels near the upper-left and upper-right and lower-left and lower-right. Framing is centred and symmetrical, uncropped at the edges, and the image covers the whole slide. A teal tint overlay makes it dominantly blue-teal (about #0B5F73 with cyan highlights about #3FB8C8 and green about #5CC46A). Logo: the Falco wordmark, a stylised slash-and-cross mark followed by the word Falco, in near-black about #1A1A1A, placed bottom-right and not overlapping text.

**Design**

Background is a teal full-bleed field #04748C with a tinted tunnel photograph over it. All text is white #FFFFFF in Ubuntu Bold, a humanist sans-serif, with no italics and no capitals treatment; the six main lines are about 5.9 percent of slide height, and the URL is Arial regular at about 2.5 percent, underlined. There are no accent colours in the text. The slide has no shapes, borders, corner radii, shadows or gradients on text; the only shape is the full-slide fill.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill, solid teal (Rectangle covering the slide, no outline, opacity 100 percent, sits at the back.)
- photo at x 0, y 0, w 100, h 100 [#0B5F73]: Full-bleed photograph of a symmetrical light-streak tunnel with green lit panels, tinted teal (Uncropped, rectangular, no border, teal tint overlay over the image, covers the fill behind the text.)
- body at x 23.5, y 29.8, w 57, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; center aligned]: New CNCF Benchmarking Initiatives (Bold, no italics, no capitals transform, centred line, single line of text.)
- body at x 20.7, y 36.9, w 63.5, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; center aligned]: CNCF Environmental Sustainability TAG (Bold, no italics, centred line, single line of text.)
- body at x 27.9, y 43.9, w 48.1, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; center aligned]: Green Reviews Working Group (Bold, no italics, centred line, single line of text.)
- body at x 35.4, y 58, w 33.2, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; center aligned]: Falco as First Project (Bold, no italics, centred line, single line of text.)
- body at x 9.9, y 65, w 84.3, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; center aligned]: Starting the Journey Towards Enhanced Performance (Bold, no italics, centred line, single line of text.)
- body at x 28.1, y 72.1, w 47.7, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; center aligned]: New Falco Metrics Framework (Bold, no italics, centred line, single line of text.)
- caption at x 1.3, y 94.6, w 35, h 2.5 [Arial regular; font size 2.47% of slide height; #FFFFFF; left aligned]: https://github.com/falcosecurity/cncf-green-review-testing (Hyperlink, underlined, regular weight, not italic, single line, bottom-left.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: stylised slash-and-cross mark with the word Falco (Dark near-black wordmark on the teal background, bottom-right, no background plate, no overlap with text.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2048 by 1152 pixels (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 23.5, y 29.8, w 57.0, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: New CNCF Benchmarking Initiatives
- text at x 20.7, y 36.9, w 63.5, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: CNCF Environmental Sustainability TAG
- text at x 27.9, y 43.9, w 48.1, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Green Reviews Working Group
- text at x 35.4, y 58.0, w 33.2, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Falco as First Project
- text at x 9.9, y 65.0, w 84.3, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Starting the Journey Towards Enhanced Performance
- text at x 28.1, y 72.1, w 47.7, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: New Falco Metrics Framework
- text at x 1.3, y 94.6, w 35.0, h 2.5 [ArialMT; font size 2.47; #FFFFFF]: https://github.com/falcosecurity/cncf-green-review-testing

### Slide 24

**Review notes**

- Worth keeping: Keep the consistent teal template with the Falco mark, the clean timeline on slide 2, the four-tier status chips on slide 24, and the plain icon-plus-sentence layout of slides 13 and 22.

**Text**

Rules Maturity Framework
STATUS
STABLE
Rules included in the default Falco package; address / broader threats; provide universal system-level detections; / follow best practices for optimal robustness.
STATUS
INCUBATING
Rules address relevant threats; provide certain level of / robustness; cater to more speciﬁc use cases.
STATUS
SANDBOX
Experimental rules; can serve as inspiration; adhere to / minimum acceptance criteria.
STATUS
DEPRECATED
Rules no longer actively maintained.
https://github.com/falcosecurity/rules

**Layout**

Single full-bleed slide with the title top-left at about 3.4% from the left and 3.7% from the top. Four status rows stacked vertically at roughly 27%, 49%, 67% and 86% of the slide height, each with a status tag block at the left (x 4.2 to 27.9%) and a description text block starting at x 33%, left-aligned. The Falco logo sits bottom-right and a source URL sits bottom-left; no slide number is visible.

**Visuals**

Full-bleed photograph of a stepped, geometric concrete staircase architecture seen from above, with a small person holding a camera at the top-left (about x 11 to 21%, y 12 to 25%). The photo is tinted teal by a full-slide #04748C overlay, giving a muted blue-teal monochrome look. Four status tags: each is a two-part label bar; the left part is dark grey #595959 with white bold 'STATUS' text, the right part is a colour-coded block: STABLE green #4BC616, INCUBATING orange #FF9900, SANDBOX coral #E3664C, DEPRECATED grey #9C9696, each with white bold uppercase text. Falco logo at bottom-right: a stylised X-shaped mark beside the word 'Falco' in dark grey, about #555555. No charts, tables or other diagrams.

**Design**

Background is a full-bleed photo of stairs overlaid with teal #04748C tint. Title in bold humanist sans (Ubuntu Bold), white #FAFAFA, about 5.9% of slide height (cap height about 4.2%). Body text in Montserrat Medium, white #FFFFFF, about 3.5% of slide height. Status labels in Montserrat Bold uppercase, white, about 2.5% of slide height. URL in Arial regular, white, underlined, about 2.5%. Tag blocks are flat rectangles with square corners and no shadows, no gradients. Accent colours are the tag colours: green #4BC616, orange #FF9900, coral #E3664C, grey #9C9696, dark grey #595959.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- photo at x 0, y 0, w 100, h 100: Background photograph: overhead view of a stepped geometric staircase architecture with a small person holding a camera at top-left, tinted teal (Full-bleed, not cropped, covers whole slide; teal tint overlay #04748C on top; no rounded corners)
- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide teal colour overlay (Flat fill over the photograph, tinting it; opacity not measurable, appears fully opaque at tint; no border)
- shape at x 4.2, y 27, w 9.4, h 6 [#595959]: Status tag left block for STABLE row (Flat rectangle, square corners, no border, no shadow; abuts the green block to its right)
- shape at x 13.5, y 27, w 14.5, h 6 [#4BC616]: Status tag right block for STABLE row (Flat rectangle, square corners, no border, no shadow)
- shape at x 4.2, y 48.9, w 9.4, h 6 [#595959]: Status tag left block for INCUBATING row (Flat rectangle, square corners, no border, no shadow)
- shape at x 13.5, y 48.9, w 14.5, h 6 [#FF9900]: Status tag right block for INCUBATING row (Flat rectangle, square corners, no border, no shadow)
- shape at x 4.2, y 67.3, w 9.4, h 6 [#595959]: Status tag left block for SANDBOX row (Flat rectangle, square corners, no border, no shadow)
- shape at x 13.5, y 67.3, w 14.5, h 6 [#E3664C]: Status tag right block for SANDBOX row (Flat rectangle, square corners, no border, no shadow)
- shape at x 4.2, y 85.9, w 9.4, h 6 [#595959]: Status tag left block for DEPRECATED row (Flat rectangle, square corners, no border, no shadow)
- shape at x 13.5, y 85.9, w 14.5, h 6 [#9C9696]: Status tag right block for DEPRECATED row (Flat rectangle, square corners, no border, no shadow)
- title at x 3.4, y 3.7, w 42.2, h 5.9 [Ubuntu Bold, sans-serif, bold, normal case; font size 5.93% of slide height; #FAFAFA; left aligned]: Rules Maturity Framework (Single line)
- body at x 33, y 27.3, w 57.9, h 11.8 [Montserrat Medium, sans-serif, regular weight, normal case; font size 3.46% of slide height; #FFFFFF; left aligned]: Rules included in the default Falco package; address / broader threats; provide universal system-level detections; / follow best practices for optimal robustness. (Three lines, line spacing about 4.2% of slide height)
- body at x 33, y 49.4, w 53.7, h 7.6 [Montserrat Medium, sans-serif, regular weight, normal case; font size 3.46% of slide height; #FFFFFF; left aligned]: Rules address relevant threats; provide certain level of / robustness; cater to more speciﬁc use cases. (Two lines, line spacing about 4.1% of slide height)
- body at x 33, y 67.6, w 53.6, h 7.6 [Montserrat Medium, sans-serif, regular weight, normal case; font size 3.46% of slide height; #FFFFFF; left aligned]: Experimental rules; can serve as inspiration; adhere to / minimum acceptance criteria. (Two lines, line spacing about 4.1% of slide height)
- body at x 33, y 87.2, w 35.9, h 3.5 [Montserrat Medium, sans-serif, regular weight, normal case; font size 3.46% of slide height; #FFFFFF; left aligned]: Rules no longer actively maintained. (Single line)
- label at x 6.1, y 29, w 5.5, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: STATUS (Sits on dark grey #595959 block)
- label at x 18, y 29, w 5.6, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: STABLE (Sits on green #4BC616 block)
- label at x 6.1, y 50.9, w 5.5, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: STATUS (Sits on dark grey #595959 block)
- label at x 16.1, y 50.9, w 9.3, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: INCUBATING (Sits on orange #FF9900 block)
- label at x 6.1, y 69.2, w 5.5, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: STATUS (Sits on dark grey #595959 block)
- label at x 17.1, y 69.2, w 7.4, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: SANDBOX (Sits on coral #E3664C block)
- label at x 6.1, y 87.8, w 5.5, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: STATUS (Sits on dark grey #595959 block)
- label at x 15.8, y 87.8, w 10, h 2.5 [Montserrat Bold, sans-serif, bold, all caps; font size 2.47% of slide height; #FFFFFF; center aligned]: DEPRECATED (Sits on grey #9C9696 block)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#555555]: Falco logo: stylised X-shaped mark followed by the word Falco (Dark grey logo over the teal background, bottom-right corner)
- caption at x 1.3, y 94.6, w 22.4, h 2.5 [Arial regular, sans-serif, normal weight, normal case, underlined; font size 2.47% of slide height; #FFFFFF; left aligned]: https://github.com/falcosecurity/rules (Hyperlink text, underlined)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 4.2, y 27.0, w 9.4, h 6.0: #595959
- fill at x 13.5, y 27.0, w 14.5, h 6.0: #4BC616
- fill at x 4.2, y 48.9, w 9.4, h 6.0: #595959
- fill at x 13.5, y 48.9, w 14.5, h 6.0: #FF9900
- fill at x 4.2, y 67.3, w 9.4, h 6.0: #595959
- fill at x 13.5, y 67.3, w 14.5, h 6.0: #E3664C
- fill at x 4.2, y 85.9, w 9.4, h 6.0: #595959
- fill at x 13.5, y 85.9, w 14.5, h 6.0: #9C9696
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2048 by 1365 pixels (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 42.2, h 5.9 [Ubuntu-Bold; font size 5.93; #FAFAFA]: Rules Maturity Framework
- text at x 33.0, y 27.3, w 52.4, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: Rules included in the default Falco package; address
- text at x 33.0, y 31.4, w 57.9, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: broader threats; provide universal system-level detections;
- text at x 33.0, y 35.6, w 43.5, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: follow best practices for optimal robustness.
- text at x 6.1, y 29.0, w 5.5, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: STATUS
- text at x 18.0, y 29.0, w 5.6, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: STABLE
- text at x 33.0, y 49.4, w 53.7, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: Rules address relevant threats; provide certain level of
- text at x 33.0, y 53.5, w 43.6, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: robustness; cater to more speciﬁc use cases.
- text at x 33.0, y 67.6, w 53.6, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: Experimental rules; can serve as inspiration; adhere to
- text at x 6.1, y 50.9, w 5.5, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: STATUS
- text at x 16.1, y 50.9, w 9.3, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: INCUBATING
- text at x 33.0, y 71.7, w 29.7, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: minimum acceptance criteria.
- text at x 33.0, y 87.2, w 35.9, h 3.5 [Montserrat-Medium; font size 3.46; #FFFFFF]: Rules no longer actively maintained.
- text at x 6.1, y 69.2, w 5.5, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: STATUS
- text at x 17.1, y 69.2, w 7.4, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: SANDBOX
- text at x 6.1, y 87.8, w 5.5, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: STATUS
- text at x 15.8, y 87.8, w 10.0, h 2.5 [Montserrat-Bold; font size 2.47; #FFFFFF]: DEPRECATED
- text at x 1.3, y 94.6, w 22.4, h 2.5 [ArialMT; font size 2.47; #FFFFFF]: https://github.com/falcosecurity/rules

### Slide 25

**Review notes**

- Review: The deck has a consistent teal identity, a clear section structure (slides 7, 14, 25, 31 as dividers) and a readable route from history to news to roadmap to community.

**Text**

Falco
Plugins and K8S

**Layout**

Single-title slide with the title set left-aligned at about mid-height on a 4.2% left margin, with the Falco logo in the top-left corner at the same left margin. The title sits in the vertical centre band and the right half is left open except for a large pale watermark bleeding off the right and bottom edges. No footer or slide number is visible.

**Visuals**

Large pale teal watermark of the Falco chevron icon (a double-stroke arrow mark with rounded line ends) at the lower right, about x 72 to 100 and y 40 to 100, bleeding off the right and bottom edges. Its strokes are pale aqua #E3F6F8 on white. Top-left Falco logo: a small dark teal icon of two diagonal strokes beside the lowercase-style wordmark 'Falco', in dark teal #163C44. A small 4 by 2 pixel image also sits at the bottom right (x 87.1, y 89.6), not distinguishable from the watermark.

**Design**

Background: White #FFFFFF with a pale aqua #E3F6F8 Falco chevron watermark at the lower right (the full-slide teal fill #04748C is covered by the full-slide image). White background with a pale aqua chevron watermark at the lower right. Title in Ubuntu Medium, sentence case, dark near-black #171717, about 8.9% of slide height, left aligned. Logo in dark teal #163C44. Accent teal #04748C sits beneath the full-slide image but is hidden by it. No shadows, gradients or boxes. Watermark strokes are rounded at their ends.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill, covered by the full-slide image (Solid rectangle, fully hidden by the image above it; no visible edge.)
- illustration at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide background image: white field with pale aqua Falco chevron watermark at lower right (1200 by 628 pixel image covering the whole slide, unboxed and full-bleed; watermark strokes are pale aqua #E3F6F8 with rounded ends, extending off the right and bottom edges; no overlay or tint.)
- image at x 87.1, y 89.6, w 8.7, h 5.9 [#E3F6F8]: Small image at lower right, not visibly distinct from the watermark (4 by 2 pixel image; appears to be blank or part of the watermark; no visible content.)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#163C44]: Falco logo: stylised double-stroke chevron icon with the wordmark 'Falco' (Icon of diagonal dark teal strokes at left of the wordmark; wordmark in a rounded sans-serif, dark teal #163C44; unboxed, no shadow.)
- title at x 4.2, y 49.5, w 36.7, h 8.9 [Ubuntu Medium, regular case, normal italics none, no letter-spacing; font size 8.89% of slide height; #171717; left aligned]: Plugins and K8S (Single line; no bullets; sits on the white background.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 4.2, y 49.5, w 36.7, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: Plugins and K8S

### Slide 26

**Text**

Plugins – New detections, metadata, data sources
syslog
GKE Audit Events
GCP Audit Logs
Anomaly Detection 🚧
Enterprise Events
Real-Time Event Monitoring
K8S Cluster Metadata
Falco

**Layout**

Full-bleed teal slide with the title in one line across the top-left at about 3.4% from the left edge. Below it is a loose 4-column by 2-row grid of logo tiles with centred labels, the first three columns in the top and bottom rows, and a rocket illustration fills the lower-right quadrant. The Falco logo sits bottom-right; there is no visible slide number or footer.

**Visuals**

Seven service logo tiles and one warning-sign icon, plus a rocket illustration and the Falco logo. Top row, left to right: a syslog icon (black document with three text lines and a gear on a light grey #EEEEEE rounded square); the GKE Audit Events logo (blue hexagon with a white cube symbol on a white rounded tile); the GCP Audit Logs logo (Google Cloud multicolour cloud, red, yellow, green and blue, on a white rounded tile); an Anomaly Detection icon (grey magnifying glass over a warning triangle with two arrows on a light grey #EEEEEE rounded square). Bottom row, left to right: the Box logo (blue lowercase wordmark on white tile); the Salesforce logo (white lettering on a blue #009EDB cloud on white tile); the Kubernetes K8S logo (white helm wheel on a blue #326CE5 heptagon on white tile). Rocket illustration in the lower right: a white and light grey rocket with red fins and a yellow flame, with white speed lines trailing to the left, flat vector style, no shadow. Falco logo: dark grey slash mark and the word Falco in dark bold sans-serif, bottom right, not boxed. Image boxes are as measured from the file; the rocket image box includes transparent margin.

**Design**

Background: Solid teal #04748C. Flat teal background with no gradient or texture. Title in bold white humanist sans-serif (Ubuntu Bold), about 5.9% of slide height. Labels in medium-weight white geometric sans-serif (Montserrat Medium) about 3.95% of slide height; accent labels in bold #FFAB40 amber. Logo tiles are square-cornered white or light grey panels with slight rounding. No borders or shadows visible. Accent colour amber #FFAB40 highlights the names of the anomaly detection and K8S items. Title and labels are left or centred as noted below.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background rectangle (Solid fill, no border, covers the whole slide.)
- shape at x 8.1, y 19.3, w 9.4, h 18 [#EEEEEE]: Light grey backing square behind syslog icon (Rounded corners about 8% of width, thin grey stroke, behind the syslog icon.)
- shape at x 66.8, y 19.3, w 9.9, h 18 [#EEEEEE]: Light grey backing square behind Anomaly Detection icon (Rounded corners about 8% of width, thin grey stroke, behind the magnifier icon.)
- image at x 59.3, y 10.4, w 40.7, h 83.8: Rocket with speed lines illustration (Flat vector, 709 by 376 px source, transparent surround, rocket lower right with white speed lines to its left.)
- logo at x 67.3, y 20.4, w 8.7, h 15.8 [#EEEEEE]: Anomaly Detection icon (magnifier, warning triangle, arrows) (128 by 128 px square icon over the light grey backing.)
- icon at x 8.1, y 19.4, w 9.4, h 18 [#EEEEEE]: syslog icon (document with lines and gear) (128 by 128 px square icon over the light grey backing.)
- logo at x 25.8, y 18.5, w 15.1, h 19.4 [#FFFFFF]: GKE Audit Events logo (217 by 163 px, white rounded tile with blue hexagon and white cube.)
- logo at x 48.3, y 19.8, w 9.9, h 17 [#FFFFFF]: GCP Audit Logs logo (Google Cloud) (216 by 216 px, white rounded tile with multicolour cloud.)
- logo at x 6.2, y 48.8, w 14.2, h 24.3 [#FFFFFF]: Box logo (298 by 298 px, white tile, blue #0061D5 lowercase box wordmark.)
- logo at x 39.1, y 51.7, w 28.5, h 25.3 [#FFFFFF]: Salesforce logo (384 by 200 px, white tile, blue cloud with white lettering.)
- logo at x 75, y 57.8, w 18.6, h 33 [#FFFFFF]: Kubernetes K8S logo (200 by 200 px, white tile, blue #326CE5 heptagon with white helm wheel.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#FFFFFF]: Falco logo (Dark slash mark and Falco wordmark in dark grey, no box.)
- title at x 3.4, y 3.7, w 78.3, h 5.9 [Ubuntu Bold, bold, sentence case; font size 5.93% of slide height; #FFFFFF; left aligned]: Plugins – New detections, metadata, data sources
- caption at x 8.8, y 39.7, w 7.9, h 4.4 [Montserrat Medium, regular weight, sentence case; font size 4.44% of slide height; #FFFFFF; center aligned]: syslog
- caption at x 27.5, y 39.6, w 12.2, h 8 [Montserrat Medium, regular weight, sentence case; font size 3.95% of slide height; #FFFFFF; center aligned]: GKE Audit / Events (Two lines, the first line GKE Audit at y 39.6 and Events at y 44.3, line spacing about 4.7% of slide height.)
- caption at x 47.5, y 39.6, w 12.3, h 8.7 [Montserrat Medium, regular weight, sentence case; font size 3.95% of slide height; #FFFFFF; center aligned]: GCP Audit / Logs (Two lines, GCP Audit at y 39.6 and Logs at y 44.3.)
- caption at x 64.9, y 40.7, w 14.6, h 8.7 [Montserrat Bold, bold, sentence case; font size 3.95% of slide height; #FFAB40; center aligned]: Anomaly / Detection 🚧 (Two lines, Anomaly at y 40.7 and Detection at y 45.4; 🚧 emoji in Noto Color Emoji, white, at x 77.0 y 45.4, w 2.8, h 4.0.)
- caption at x 7.4, y 70.6, w 12.2, h 8.4 [Montserrat Medium, regular weight, sentence case; font size 3.95% of slide height; #FFFFFF; center aligned]: Enterprise / Events (Two lines, Enterprise at y 70.6 and Events at y 75.4.)
- caption at x 27, y 71.5, w 12.5, h 13.5 [Montserrat Medium, regular weight, sentence case; font size 3.95% of slide height; #FFFFFF; center aligned]: Real-Time / Event / Monitoring (Three lines: Real-Time at y 71.5, Event at y 76.2, Monitoring at y 81.0.)
- caption at x 47.7, y 71.5, w 12.4, h 13.5 [Montserrat Bold, bold, sentence case; font size 3.95% of slide height; #FFAB40; center aligned]: K8S / Cluster / Metadata (Three lines: K8S at y 71.5, Cluster at y 76.2, Metadata at y 81.0.)
- footer at x 87.1, y 89.6, w 8.7, h 5.9 [Falco wordmark, bold sans-serif, dark grey; #1A1A1A; right aligned]: Falco (Wordmark part of the Falco logo, bottom right.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 8.1, y 19.3, w 9.4, h 18.0: #EEEEEE
- fill at x 66.8, y 19.3, w 9.9, h 18.0: #EEEEEE
- image at x 59.3, y 10.4, w 40.7, h 83.8: 709 by 376 pixels
- image at x 13.3, y 51.3, w 40.1, h 19.4: 713 by 202 pixels
- image at x 39.1, y 51.7, w 28.5, h 25.3: 384 by 200 pixels
- image at x 75.0, y 57.8, w 18.6, h 33.0: 200 by 200 pixels
- image at x 6.2, y 48.8, w 14.2, h 24.3: 298 by 298 pixels
- image at x 25.8, y 18.5, w 15.1, h 19.4: 217 by 163 pixels
- image at x 48.3, y 19.8, w 9.9, h 17.0: 216 by 216 pixels
- image at x 8.1, y 19.4, w 9.4, h 18.0: 128 by 128 pixels
- image at x 67.3, y 20.4, w 8.7, h 15.8: 128 by 128 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 77.0, y 44.9, w 2.8, h 4.6: 34 by 32 pixels
- text at x 3.4, y 3.7, w 78.3, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Plugins – New detections, metadata, data sources
- text at x 8.8, y 39.7, w 7.9, h 4.4 [Montserrat-Medium; font size 4.44; #FFFFFF]: syslog
- text at x 27.5, y 39.6, w 12.2, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: GKE Audit
- text at x 47.5, y 39.6, w 12.3, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: GCP Audit
- text at x 67.2, y 40.7, w 10.4, h 4.0 [Montserrat-Bold; font size 3.95; #FFAB40]: Anomaly
- text at x 29.5, y 44.3, w 8.2, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Events
- text at x 50.6, y 44.3, w 5.4, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Logs
- text at x 64.9, y 45.4, w 11.5, h 4.0 [Montserrat-Bold; font size 3.95; #FFAB40]: Detection
- text at x 77.0, y 45.4, w 2.8, h 4.0 [NotoColorEmoji; font size 3.95; #FFFFFF]: 🚧
- text at x 7.4, y 70.6, w 12.2, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Enterprise
- text at x 27.6, y 71.5, w 11.9, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Real-Time
- text at x 51.1, y 71.5, w 5.1, h 4.0 [Montserrat-Bold; font size 3.95; #FFAB40]: K8S
- text at x 9.5, y 75.4, w 7.6, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Events
- text at x 30.0, y 76.2, w 7.1, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Event
- text at x 49.2, y 76.2, w 8.9, h 4.0 [Montserrat-Bold; font size 3.95; #FFAB40]: Cluster
- text at x 27.0, y 81.0, w 12.5, h 4.0 [Montserrat-Medium; font size 3.95; #FFFFFF]: Monitoring
- text at x 47.7, y 81.0, w 11.1, h 4.0 [Montserrat-Bold; font size 3.95; #FFAB40]: Metadata

### Slide 27

**Text**

Kubernetes – Reinventing metadata enrichment
Rethinked for maximum / performance and scalability
Optional module built / on top of Plugin API
30.000+ lines of legacy code / removed from core Falco
Built in Go leveraging / native K8S client code
Available from Falco v0.37.0
Falco Instance
Meta Collector
Meta Collector SVC
Falco Instance
Falco Instance
Node 1
Node 2
Node n
api
falcosecurity/k8s-metacollector
falcosecurity/plugins/tree/master/plugins/k8smeta

**Layout**

Two-column layout on a full-bleed teal field: a left text column of five bulleted items starts at about 5.5% from the left edge and the title sits top-left at about 3.4% from the left and 3.7% from the top. The right column holds one rounded-corner diagram box from about 50% to 97% horizontally and 20% to 84% vertically, with two right-aligned underlined links beneath it and a Falco logo at bottom right, about 87% from the left and 90% from the top. No slide number or footer text is visible.

**Visuals**

One diagram (architecture illustration) at x 50.2%, y 19.9%, w 47.2%, h 64.0%, 801 by 611 px. It is a white rounded-rectangle panel with a thin dark grey outline and large corner radius (about 8% of the panel width), fully opaque and not cropped. A blue Kubernetes wheel icon in a blue hexagon overlaps the top-left corner of the panel. Top centre: a blue hexagon with a gear-cluster icon and the small label 'api'. Left middle: a blue hexagon with a network-hierarchy icon labelled 'Meta Collector / SVC' in black sans-serif text to its left. Three rectangular boxes with thin black outlines sit along the bottom: 'Node 1' (left, box contains one blue cube-hexagon icon labelled 'Falco Instance' with a small Falco logo on it), 'Node 2' (middle, contains a Falco Instance icon and a Meta Collector cube icon, labelled 'Falco Instance' and 'Meta Collector'), and 'Node n' (right, contains one Falco Instance icon). Each node box has a small blue Kubernetes wheel hexagon at its top-left corner and its node label below the box. Connectors: a blue-grey double-headed arrow runs vertically from the Meta Collector SVC hexagon down to the Node 1 Falco Instance; a blue-grey elbow arrow runs from Node 2 Falco Instance up to the SVC hexagon; a blue-grey elbow arrow runs from the SVC hexagon right and down into Node 2 Meta Collector (arrowhead at Meta Collector); a blue-grey elbow arrow runs from the SVC hexagon right along the top and down into Node n Falco Instance; a green arrow runs from the Meta Collector upward to the api hexagon with an arrowhead at api, and a green arrow runs from api downward to the Meta Collector with an arrowhead at the Meta Collector. Lines are about 1 px thick with rounded corners. Palette: Kubernetes blue #326CE5 for hexagons and cube icons, light steel blue #7FA0D8 connectors, green #6DBE45 for the api arrows, black text and outlines on white.

**Design**

Background: Solid teal #04748C filling the entire slide. Flat solid teal background with no gradient, texture or imagery. Title in bold geometric sans-serif (Ubuntu Bold) at about 5.9% of slide height, white #FFFFFF. Bullet text in Montserrat Regular with bold emphasis words (Montserrat Bold) at about 3.95% of slide height, white #FFFFFF, with generous line spacing (about 1.5 lines) and a bullet dot in Arial at the left. Accent colour is white only. Links in Montserrat Regular at about 3.46% of slide height, white and underlined. The diagram panel has a white fill, thin dark outline and large rounded corners, with no shadow. Falco logo in dark near-black #1B1B1B.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid rectangle covering the whole slide, no outline, no gradient.)
- illustration at x 50.2, y 19.9, w 47.2, h 64 [#FFFFFF]: Architecture diagram: Kubernetes metadata collector with API, Meta Collector SVC, three nodes with Falco Instances and Meta Collector, connected by arrows, on a white rounded panel with a Kubernetes logo at its top-left corner (Opaque white rounded rectangle, large corner radius, thin dark grey outline, no shadow, not cropped, boxed. Blue #326CE5 hexagon icons, steel blue #7FA0D8 connectors, green #6DBE45 api arrows.)
- title at x 3.4, y 3.7, w 75.7, h 5.9 [Ubuntu Bold, bold, sans-serif; font size 5.93% of slide height; #FFFFFF; left aligned]: Kubernetes – Reinventing metadata enrichment
- bullet list at x 5.5, y 22.2, w 36.1, h 9.4 [Montserrat Regular with Montserrat Bold emphasis, sans-serif; font size 3.95% of slide height; #FFFFFF; left aligned]: Rethinked for maximum / performance and scalability (Bullet dot in Arial at x 5.5%, text indented to x 9.3%, line spacing about 5.4% of slide height. Bold words: maximum, performance, scalability.)
- bullet list at x 5.5, y 35.5, w 28.8, h 9.4 [Montserrat Regular with Montserrat Bold emphasis, sans-serif; font size 3.95% of slide height; #FFFFFF; left aligned]: Optional module built / on top of Plugin API (Bullet dot in Arial at x 5.5%, text indented to x 9.3%, line spacing about 5.4% of slide height. Bold words: module, Plugin API.)
- bullet list at x 5.5, y 48.9, w 36.1, h 9.4 [Montserrat Regular with Montserrat Bold emphasis, sans-serif; font size 3.95% of slide height; #FFFFFF; left aligned]: 30.000+ lines of legacy code / removed from core Falco (Bullet dot in Arial bold at x 5.5%, text indented to x 9.3%, line spacing about 5.4% of slide height. Bold words: 30.000+, legacy code, removed.)
- bullet list at x 5.5, y 62.2, w 29.5, h 9.4 [Montserrat Regular with Montserrat Bold emphasis, sans-serif; font size 3.95% of slide height; #FFFFFF; left aligned]: Built in Go leveraging / native K8S client code (Bullet dot in Arial at x 5.5%, text indented to x 9.3%, line spacing about 5.4% of slide height. Bold words: Go, native K8S client.)
- bullet list at x 5.5, y 75.5, w 35.2, h 4 [Montserrat Regular with Montserrat Bold emphasis, sans-serif; font size 3.95% of slide height; #FFFFFF; left aligned]: Available from Falco v0.37.0 (Bullet dot in Arial at x 5.5%, text indented to x 9.3%. Bold words: Falco v0.37.0.)
- caption at x 65.2, y 75.8, w 30.5, h 3.5 [Montserrat Regular, sans-serif; font size 3.46% of slide height; #FFFFFF; right aligned]: falcosecurity/k8s-metacollector (Underlined hyperlink text.)
- caption at x 47, y 82.1, w 48.7, h 3.5 [Montserrat Regular, sans-serif; font size 3.46% of slide height; #FFFFFF; right aligned]: falcosecurity/plugins/tree/master/plugins/k8smeta (Underlined hyperlink text.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1B1B1B]: Falco logo: stylised double-slash icon with the word Falco (Dark near-black wordmark and icon on the teal background, no outline.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 50.2, y 19.9, w 47.2, h 64.0: 801 by 611 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 75.7, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Kubernetes – Reinventing metadata enrichment
- text at x 5.5, y 22.2, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ●
- text at x 9.3, y 22.2, w 15.8, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Rethinked for
- text at x 25.1, y 22.2, w 11.9, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: maximum
- text at x 9.3, y 27.6, w 15.1, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: performance
- text at x 24.4, y 27.6, w 5.5, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: and
- text at x 29.9, y 27.6, w 11.7, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: scalability
- text at x 5.5, y 35.5, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ●
- text at x 9.3, y 35.5, w 9.7, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Optional
- text at x 19.0, y 35.5, w 9.6, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: module
- text at x 28.6, y 35.5, w 5.7, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: built
- text at x 9.3, y 40.9, w 10.5, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: on top of
- text at x 19.9, y 40.9, w 12.2, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: Plugin API
- text at x 5.5, y 48.9, w 1.3, h 4.0 [Arial-BoldMT; font size 3.95; #FFFFFF]: ●
- text at x 9.3, y 48.9, w 9.2, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: 30.000+
- text at x 18.6, y 48.9, w 9.0, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: lines of
- text at x 27.6, y 48.9, w 14.0, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: legacy code
- text at x 9.3, y 54.2, w 10.3, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: removed
- text at x 19.7, y 54.2, w 17.8, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: from core Falco
- text at x 5.5, y 62.2, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ●
- text at x 9.3, y 62.2, w 8.5, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Built in
- text at x 17.9, y 62.2, w 3.2, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: Go
- text at x 21.0, y 62.2, w 12.3, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: leveraging
- text at x 9.3, y 67.6, w 19.5, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: native K8S client
- text at x 28.9, y 67.6, w 6.1, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: code
- text at x 5.5, y 75.5, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ●
- text at x 9.3, y 75.5, w 16.5, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Available from
- text at x 25.8, y 75.5, w 14.9, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: Falco v0.37.0
- text at x 65.2, y 75.8, w 30.5, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: falcosecurity/k8s-metacollector
- text at x 47.0, y 82.1, w 48.7, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: falcosecurity/plugins/tree/master/plugins/k8smeta

### Slide 28

**Review notes**

- Review: Many content slides are dense with tiny code or field lists (slides 28, 38, 39), and this is only workable for a live technical audience who already know Falco.
- What would change the score: I would cut the near-empty filler slides (5, 8, 41's weak layout), add one takeaway per technical slide, and trim the long field lists and roadmap bullets on slides 28, 38 and 39 to the few items the speakers will actually say.

**Text**

Kubernetes – Detection and enrichment fields
Core Falco (from containers engine)
K8S Meta Plugin (from API server)
k8s.ns.name
k8s.pod.name
k8s.pod.id
k8s.pod.uid
k8s.pod.sandbox_id
k8s.pod.full_sandbox_id
k8s.pod.label
k8s.pod.labels
k8s.pod.ip
k8s.pod.cni.json
(others are still available but deprecated since v0.37…)
k8smeta.pod.name
k8smeta.pod.uid
k8smeta.pod.label
k8smeta.pod.labels
k8smeta.pod.ip
k8smeta.ns.name
k8smeta.ns.uid
k8smeta.ns.label
k8smeta.ns.labels
k8smeta.deployment.name
k8smeta.deployment.uid
k8smeta.deployment.label
k8smeta.deployment.labels
k8smeta.svc.name
k8smeta.svc.uid
k8smeta.svc.label
k8smeta.svc.labels
k8smeta.rs.name
k8smeta.rs.uid
k8smeta.rs.label
k8smeta.rs.labels
k8smeta.rc.name
k8smeta.rc.uid
k8smeta.rc.label
k8smeta.rc.label

**Layout**

Two equal columns sit inside one white-outlined rectangle spanning about x 4.3–94 and y 20.2–89.3 of the slide; each column has a white header cell with a bold black heading and a teal body below it, separated by a thin white vertical rule at about x 49. The slide title sits top-left at x 3.4, y 3.7, left-aligned with no subtitle. The Falco logo sits bottom-right outside the table. No page number or footer text is shown.

**Visuals**

A two-column table with no grid lines other than the outer white border and the centre divider. Left column header: 'Core Falco (from containers engine)'. Left body: 10 light grey (#EEEEEE) chips of monospace code names, arranged in four rows, followed by an italic note. Right column header: 'K8S Meta Plugin (from API server)'. Right body: 26 light grey (#EEEEEE) chips of monospace code names in 16 rows, the last two rows being 'k8smeta.rc.label' twice as printed. Left column rows: k8s.ns.name, k8s.pod.name, k8s.pod.id / k8s.pod.uid, k8s.pod.sandbox_id / k8s.pod.full_sandbox_id, k8s.pod.label / k8s.pod.labels, k8s.pod.ip, k8s.pod.cni.json. Right column rows: k8smeta.pod.name, k8smeta.pod.uid / k8smeta.pod.label, k8smeta.pod.labels / k8smeta.pod.ip, k8smeta.ns.name / k8smeta.ns.uid, k8smeta.ns.label / k8smeta.ns.labels, k8smeta.deployment.name / k8smeta.deployment.uid, k8smeta.deployment.label / k8smeta.deployment.labels, k8smeta.svc.name / k8smeta.svc.uid, k8smeta.svc.label / k8smeta.svc.labels, k8smeta.rs.name / k8smeta.rs.uid, k8smeta.rs.label / k8smeta.rs.labels, k8smeta.rc.name / k8smeta.rc.uid, k8smeta.rc.label / k8smeta.rc.label. The Falco logo at bottom right is a dark stylised mark of crossed diagonal strokes beside the lowercase wordmark 'Falco' in dark grey-black (#1A1A1A), with no photograph, chart or diagram.

**Design**

Background: Solid teal #04748C across the whole slide. Flat teal background with no gradient, shadow or texture. Title in a bold humanist sans-serif (Ubuntu Bold), white #FFFFFF, large at about 5.9% of slide height. Column headings in a bold Arial-style sans-serif, black #000000, about 3.5% of slide height, on white #FFFFFF header cells. Body code text in a bold italic Courier New-style monospace, black #000000, about 3.0% of slide height, each on a flat light grey #EEEEEE chip with square corners and no padding shadow. The note is an italic geometric sans (Montserrat Italic), white #FFFFFF, about 3.0%. The table border and divider are thin white lines, roughly 0.2% of slide height, with square corners and no shadow.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background rectangle (Solid fill, no border, behind everything.)
- shape at x 4.3, y 20.2, w 89.7, h 69.1 [#04748C]: Table outer frame, one rectangle with a white outline (Fill matches background; stroke #FFFFFF about 0.2% of slide height; square corners; no shadow.)
- shape at x 4.3, y 20.2, w 44.8, h 8.9 [#FFFFFF]: Left column header cell (Solid white fill, square corners, no border.)
- shape at x 49.1, y 20.2, w 44.8, h 8.9 [#FFFFFF]: Right column header cell (Solid white fill, square corners, no border.)
- line at x 49, y 29, w 0.2, h 60.3 [#FFFFFF]: Vertical divider between the two columns (Thin white rule, about 0.2% of slide height wide, running from the header bottom to the table bottom.)
- title at x 3.4, y 3.7, w 72.9, h 5.9 [Ubuntu, bold, normal case; font size 5.93% of slide height; #FFFFFF; left aligned]: Kubernetes – Detection and enrichment fields (Single line, no letter-spacing change.)
- body at x 5.3, y 22.4, w 33.4, h 3.5 [Arial, bold, normal case; font size 3.46% of slide height; #000000; left aligned]: Core Falco (from containers engine) (Column heading inside the left white header cell.)
- body at x 50.1, y 22.4, w 31.4, h 3.5 [Arial, bold, normal case; font size 3.46% of slide height; #000000; left aligned]: K8S Meta Plugin (from API server) (Column heading inside the right white header cell.)
- body at x 5.3, y 31.3, w 10, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.ns.name (Text sits on a flat #EEEEEE chip.)
- body at x 17.3, y 31.3, w 11, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.name (Text sits on a flat #EEEEEE chip.)
- body at x 30.3, y 31.3, w 9, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.id (Text sits on a flat #EEEEEE chip.)
- body at x 5.3, y 35.4, w 10, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.uid (Text sits on a flat #EEEEEE chip.)
- body at x 17.3, y 35.4, w 17, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.sandbox_id (Text sits on a flat #EEEEEE chip.)
- body at x 5.3, y 39.5, w 22, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.full_sandbox_id (Text sits on a flat #EEEEEE chip.)
- body at x 29.3, y 39.5, w 12, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.label (Text sits on a flat #EEEEEE chip.)
- body at x 5.3, y 43.5, w 13, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.labels (Text sits on a flat #EEEEEE chip.)
- body at x 20.3, y 43.5, w 9, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.ip (Text sits on a flat #EEEEEE chip.)
- body at x 31.3, y 43.5, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8s.pod.cni.json (Text sits on a flat #EEEEEE chip.)
- body at x 5.3, y 51.7, w 34.1, h 7.1 [Montserrat, italic, normal case; font size 2.96% of slide height; #FFFFFF; left aligned]: (others are still available but deprecated / since v0.37…) (Two lines; no chip behind the text; sits on teal.)
- body at x 50.1, y 31.3, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.pod.name (Text sits on a flat #EEEEEE chip.)
- body at x 67.1, y 31.3, w 14, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.pod.uid (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 35.4, w 16, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.pod.label (Text sits on a flat #EEEEEE chip.)
- body at x 68.1, y 35.4, w 17, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.pod.labels (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 39.5, w 13, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.pod.ip (Text sits on a flat #EEEEEE chip.)
- body at x 65.1, y 39.5, w 14, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.ns.name (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 43.5, w 13, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.ns.uid (Text sits on a flat #EEEEEE chip.)
- body at x 65.1, y 43.5, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.ns.label (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 47.6, w 16, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.ns.labels (Text sits on a flat #EEEEEE chip.)
- body at x 68.1, y 47.6, w 22, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.deployment.name (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 51.7, w 21, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.deployment.uid (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 55.8, w 23, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.deployment.label (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 59.9, w 24, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.deployment.labels (Text sits on a flat #EEEEEE chip.)
- body at x 76.1, y 59.9, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.svc.name (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 64, w 14, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.svc.uid (Text sits on a flat #EEEEEE chip.)
- body at x 66.1, y 64, w 16, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.svc.label (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 68.1, w 17, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.svc.labels (Text sits on a flat #EEEEEE chip.)
- body at x 69.1, y 68.1, w 14, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rs.name (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 72.2, w 13, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rs.uid (Text sits on a flat #EEEEEE chip.)
- body at x 65.1, y 72.2, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rs.label (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 76.3, w 16, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rs.labels (Text sits on a flat #EEEEEE chip.)
- body at x 68.1, y 76.3, w 14, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rc.name (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 80.3, w 13, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rc.uid (Text sits on a flat #EEEEEE chip.)
- body at x 65.1, y 80.3, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rc.label (Text sits on a flat #EEEEEE chip.)
- body at x 50.1, y 84.4, w 15, h 3 [Courier New, bold italic; font size 2.96% of slide height; #000000; left aligned]: k8smeta.rc.label (Text sits on a flat #EEEEEE chip.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: stylised crossed diagonal strokes beside the lowercase wordmark 'Falco' (Dark mark on teal, no box or background.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- fill at x 4.3, y 20.2, w 44.8, h 8.9: #FFFFFF
- fill at x 49.1, y 20.2, w 44.8, h 8.9: #FFFFFF
- fill at x 17.3, y 34.9, w 18.0, h 3.6: #EEEEEE
- fill at x 5.3, y 39.0, w 23.0, h 3.6: #EEEEEE
- fill at x 5.3, y 43.1, w 14.0, h 3.6: #EEEEEE
- fill at x 31.3, y 43.1, w 16.0, h 3.6: #EEEEEE
- fill at x 50.1, y 30.8, w 16.0, h 3.6: #EEEEEE
- fill at x 67.1, y 30.8, w 15.0, h 3.6: #EEEEEE
- fill at x 50.1, y 34.9, w 17.0, h 3.6: #EEEEEE
- fill at x 68.1, y 34.9, w 18.0, h 3.6: #EEEEEE
- fill at x 50.1, y 39.0, w 14.0, h 3.6: #EEEEEE
- fill at x 65.1, y 39.0, w 15.0, h 3.6: #EEEEEE
- fill at x 50.1, y 43.1, w 14.0, h 3.6: #EEEEEE
- fill at x 65.1, y 43.1, w 16.0, h 3.6: #EEEEEE
- fill at x 50.1, y 47.2, w 17.0, h 3.6: #EEEEEE
- fill at x 68.1, y 47.2, w 23.0, h 3.6: #EEEEEE
- fill at x 50.1, y 51.2, w 22.0, h 3.6: #EEEEEE
- fill at x 50.1, y 55.3, w 24.0, h 3.6: #EEEEEE
- fill at x 50.1, y 59.4, w 25.0, h 3.6: #EEEEEE
- fill at x 76.1, y 59.4, w 16.0, h 3.6: #EEEEEE
- fill at x 50.1, y 63.5, w 15.0, h 3.6: #EEEEEE
- fill at x 66.1, y 63.5, w 17.0, h 3.6: #EEEEEE
- fill at x 50.1, y 67.6, w 18.0, h 3.6: #EEEEEE
- fill at x 69.1, y 67.6, w 15.0, h 3.6: #EEEEEE
- fill at x 65.1, y 71.7, w 16.0, h 3.6: #EEEEEE
- fill at x 50.1, y 75.8, w 17.0, h 3.6: #EEEEEE
- fill at x 68.1, y 75.8, w 15.0, h 3.6: #EEEEEE
- fill at x 65.1, y 79.9, w 16.0, h 3.6: #EEEEEE
- fill at x 50.1, y 84.0, w 16.0, h 3.6: #EEEEEE
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 72.9, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Kubernetes – Detection and enrichment ﬁelds
- text at x 5.3, y 22.4, w 33.4, h 3.5 [Arial-BoldMT; font size 3.46; #000000]: Core Falco (from containers engine)
- text at x 50.1, y 22.4, w 31.4, h 3.5 [Arial-BoldMT; font size 3.46; #000000]: K8S Meta Plugin (from API server)
- text at x 5.3, y 31.3, w 10.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . n s . n a m e
- text at x 17.3, y 31.3, w 11.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . n a m e
- text at x 30.3, y 31.3, w 9.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . i d
- text at x 50.1, y 31.3, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . p o d . n a m e
- text at x 67.1, y 31.3, w 14.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . p o d . u i d
- text at x 5.3, y 35.4, w 10.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . u i d
- text at x 17.3, y 35.4, w 17.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . s a n d b o x _ i d
- text at x 50.1, y 35.4, w 16.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . p o d . l a b e l
- text at x 68.1, y 35.4, w 17.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . p o d . l a b e l s
- text at x 5.3, y 39.5, w 22.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . f u l l _ s a n d b o x _ i d
- text at x 29.3, y 39.5, w 12.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . l a b e l
- text at x 50.1, y 39.5, w 13.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . p o d . i p
- text at x 65.1, y 39.5, w 14.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . n s . n a m e
- text at x 5.3, y 43.5, w 13.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . l a b e l s
- text at x 20.3, y 43.5, w 9.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . i p
- text at x 31.3, y 43.5, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s . p o d . c n i . j s o n
- text at x 50.1, y 43.5, w 13.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . n s . u i d
- text at x 65.1, y 43.5, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . n s . l a b e l
- text at x 50.1, y 47.6, w 16.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . n s . l a b e l s
- text at x 68.1, y 47.6, w 22.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . d e p l o y m e n t . n a m e
- text at x 5.3, y 51.7, w 34.1, h 3.0 [Montserrat-Italic; font size 2.96; #FFFFFF]: (others are still available but deprecated
- text at x 50.1, y 51.7, w 21.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . d e p l o y m e n t . u i d
- text at x 5.3, y 55.8, w 10.6, h 3.0 [Montserrat-Italic; font size 2.96; #FFFFFF]: since v0.37…)
- text at x 50.1, y 55.8, w 23.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . d e p l o y m e n t . l a b e l
- text at x 50.1, y 59.9, w 24.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . d e p l o y m e n t . l a b e l s
- text at x 76.1, y 59.9, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . s v c . n a m e
- text at x 50.1, y 64.0, w 14.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . s v c . u i d
- text at x 66.1, y 64.0, w 16.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . s v c . l a b e l
- text at x 50.1, y 68.1, w 17.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . s v c . l a b e l s
- text at x 69.1, y 68.1, w 14.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r s . n a m e
- text at x 50.1, y 72.2, w 13.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r s . u i d
- text at x 65.1, y 72.2, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r s . l a b e l
- text at x 50.1, y 76.3, w 16.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r s . l a b e l s
- text at x 68.1, y 76.3, w 14.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r c . n a m e
- text at x 50.1, y 80.3, w 13.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r c . u i d
- text at x 65.1, y 80.3, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r c . l a b e l
- text at x 50.1, y 84.4, w 15.0, h 3.0 [CourierNew-BoldItalic; font size 2.96; #000000]: k 8 s m e t a . r c . l a b e l

### Slide 29

**Text**

Plugins – Developers are our top priority / Plugin API is becoming the backbone of Falco’s tech innovation / New features / Time-sensitive async events / Native logging / Dynamic reconfiguration / Fully-fledged C++ and Go SDKs / Coming soon… / Access file descriptors info / Complex state data types / Native metrics reporting / New language SDKs…

**Layout**

Two-column layout below a full-width title and subtitle, split by a thin vertical white divider at about 50.6% of the width. The title sits top-left at x 3.4% and y 3.7%, left-aligned. The subtitle is a single left-aligned line at y 16.2%. Column headings sit at y 32.5%, with bullet lists below them. Left margin is about 3.4% to 4.3%. No footer, no slide number. A small Falco logo sits bottom-right at about x 87%, y 90%, and a crab illustration overlaps the lower-right corner of the right column.

**Visuals**

Three small emoji-style illustrations and one mascot illustration, plus a logo. (1) A wrapped gift box with a red ribbon and bow, gold-orange box, placed inline after 'New features' at x 26.5%, y 31.8%, 3.8% by 6.4%. (2) A yellow-orange construction crane with a red base, placed inline after 'Coming soon…' at x 77.6%, y 31.8%, 3.8% by 6.4%. (3) An orange crab mascot (Ferris the Rust crab) with black eyes and a small smile, facing right and tilted slightly, unboxed with no shadow, at x 83.9%, y 76.9%, 8.5% by 13.3%, sitting just beside the end of 'New language SDKs…'. (4) The Falco logo, a dark stylised crossed-slash mark followed by the wordmark 'Falco' in dark grey-black, at x 87.1%, y 89.6%, 8.7% by 5.9%. No photographs, charts or tables. A thin white vertical divider line runs from about y 28.6% to y 90.2% at x about 50.6%.

**Design**

Background: Solid teal #04748C covering the full slide. Flat solid teal background with no gradient or texture. Title and all body text are white #FFFFFF. Accents are the multicolour emoji (gift, crane, crab) and the dark Falco logo. Title is Ubuntu Bold, sans-serif, roughly 5.9% of slide height. Subtitle is Montserrat in italic, with 'Plugin API' and 'Falco’s tech innovation' in BoldItalic, roughly 4.4% of height. Column headings are Montserrat Bold, roughly 5.4% of height. Bullet items are Montserrat Regular, roughly 4.4% of height, with bold runs on 'C++' and 'Go'. Bullets are white filled circles (●, ArialMT), about 4.4% of height. Divider is a 1 to 2 px white line. No corner radii or shadows.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-bleed background rectangle (Solid fill, no border, covers the whole slide)
- line at x 50.6, y 28.6, w 0.1, h 61.6 [#FFFFFF]: Vertical divider between the two columns (Straight thin white line about 1 to 2 px wide, solid, no arrowheads)
- title at x 3.4, y 3.7, w 64.5, h 5.9 [Ubuntu Bold, sans-serif, normal weight, no italics, no capitals, no letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Plugins – Developers are our top priority
- subtitle at x 8.8, y 16.2, w 82.4, h 4.4 [Montserrat Italic with BoldItalic on 'Plugin API' and 'Falco’s tech innovation', sans-serif, no capitals, no letter-spacing; font size 4.44% of slide height; #FFFFFF; left aligned]: Plugin API is becoming the backbone of Falco’s tech innovation (Single line, the bold runs are separate text boxes at x 8.8, 60.7 and the regular run at x 22.6)
- body at x 4.3, y 32.5, w 22.2, h 5.4 [Montserrat Bold, sans-serif, no italics, no capitals, no letter-spacing; font size 5.43% of slide height; #FFFFFF; left aligned]: New features (Column heading, followed inline by the gift emoji image)
- body at x 53.2, y 32.5, w 24.5, h 5.4 [Montserrat Bold, sans-serif, no italics, no capitals, no letter-spacing; font size 5.43% of slide height; #FFFFFF; left aligned]: Coming soon… (Column heading, followed inline by the crane emoji image)
- bullet list at x 5.3, y 45.3, w 42, h 37 [Montserrat Regular, sans-serif, no italics, no capitals, no letter-spacing; 'C++' and 'Go' in Montserrat Bold; font size 4.44% of slide height; #FFFFFF; left aligned]: Time-sensitive async events / Native logging / Dynamic reconfiguration / Fully-fledged C++ and Go SDKs (Bullets are white filled circles (●, ArialMT) at x 5.3%, text starts at x 9.3%; item baselines spaced about 10.7% of slide height (y 45.3, 56.0, 66.8, 77.5); no bullet indentation beyond this; items on one line each)
- bullet list at x 54.2, y 45.3, w 40, h 37 [Montserrat Regular, sans-serif, no italics, no capitals, no letter-spacing; font size 4.44% of slide height; #FFFFFF; left aligned]: Access file descriptors info / Complex state data types / Native metrics reporting / New language SDKs… (Bullets are white filled circles (●, ArialMT) at x 54.2%, text starts at x 58.2%; item baselines spaced about 10.7% of slide height (y 45.3, 56.0, 66.8, 77.5))
- icon at x 26.5, y 31.8, w 3.8, h 6.4 [#E8A33D]: Gift box emoji (wrapped present with red ribbon and bow) (Raster emoji image 68 by 64 px, unboxed, sits inline after 'New features')
- icon at x 77.6, y 31.8, w 3.8, h 6.4 [#F0A020]: Construction crane emoji (orange-yellow crane with red base) (Raster emoji image 68 by 64 px, unboxed, sits inline after 'Coming soon…')
- illustration at x 83.9, y 76.9, w 8.5, h 13.3 [#F24A12]: Orange crab mascot (Ferris the Rust crab) facing right, tilted slightly (Raster image 128 by 86 px, unboxed, no shadow, no border, sits over the lower-right corner of the teal background next to the end of 'New language SDKs…')
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1B1B1B]: Falco logo: stylised crossed-slash mark with the wordmark 'Falco' (Dark grey-black mark and wordmark placed unboxed on teal, bottom-right corner; the file reports a 4 by 2 px image box, drawn here at its visible size)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 83.9, y 76.9, w 8.5, h 13.3: 128 by 86 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 26.5, y 31.8, w 3.8, h 6.4: 68 by 64 pixels
- image at x 77.6, y 31.8, w 3.8, h 6.4: 68 by 64 pixels
- text at x 3.4, y 3.7, w 64.5, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Plugins – Developers are our top priority
- text at x 8.8, y 16.2, w 13.8, h 4.4 [Montserrat-BoldItalic; font size 4.44; #FFFFFF]: Plugin API
- text at x 22.6, y 16.2, w 38.1, h 4.4 [Montserrat-Italic; font size 4.44; #FFFFFF]: is becoming the backbone of
- text at x 60.7, y 16.2, w 30.5, h 4.4 [Montserrat-BoldItalic; font size 4.44; #FFFFFF]: Falco’s tech innovation
- text at x 4.3, y 32.5, w 22.2, h 5.4 [Montserrat-Bold; font size 5.43; #FFFFFF]: New features
- text at x 26.5, y 32.5, w 3.8, h 5.4 [NotoColorEmoji; font size 5.43; #FFFFFF]: 🎁
- text at x 26.5, y 32.5, w 3.8, h 5.4 [NotoColorEmoji; font size 5.43; #FFFFFF]: 🎁
- text at x 53.2, y 32.5, w 24.5, h 5.4 [Montserrat-Bold; font size 5.43; #FFFFFF]: Coming soon…
- text at x 77.6, y 32.5, w 3.8, h 5.4 [NotoColorEmoji; font size 5.43; #FFFFFF]: 🏗
- text at x 77.6, y 32.5, w 3.8, h 5.4 [NotoColorEmoji; font size 5.43; #FFFFFF]: 🏗
- text at x 5.3, y 45.3, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 9.3, y 45.3, w 34.7, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Time-sensitive async events
- text at x 54.2, y 45.3, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 58.2, y 45.3, w 32.9, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Access ﬁle descriptors info
- text at x 5.3, y 56.0, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 9.3, y 56.0, w 18.4, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Native logging
- text at x 54.2, y 56.0, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 58.2, y 56.0, w 31.7, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Complex state data types
- text at x 5.3, y 66.8, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 9.3, y 66.8, w 31.3, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Dynamic reconﬁguration
- text at x 54.2, y 66.8, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 58.2, y 66.8, w 30.7, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Native metrics reporting
- text at x 5.3, y 77.5, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 9.3, y 77.5, w 17.2, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: Fully-ﬂedged
- text at x 26.5, y 77.5, w 4.8, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: C++
- text at x 31.3, y 77.5, w 6.2, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: and
- text at x 37.5, y 77.5, w 3.6, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: Go
- text at x 41.1, y 77.5, w 7.2, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: SDKs
- text at x 54.2, y 77.5, w 1.5, h 4.4 [ArialMT; font size 4.44; #FFFFFF]: ●
- text at x 58.2, y 77.5, w 27.1, h 4.4 [Montserrat-Regular; font size 4.44; #FFFFFF]: New language SDKs…

### Slide 30

**Text**

Let’s not forget… / ● Participating in 2023 has been amazing / ○ Birth of falcosecurity/falco-playground / ○ New maintainer onboarded in Falco family / ○ Talk at Cloud Native Wasm Day NA 2023 / ● Falco is candidating for Summer 2024! / ○ Event-generator revamp and automation of Falco performance testing / ○ Waiting for your application! / github.com/cncf/mentoring/pull/1169 / github.com/falcosecurity/evolution/issues/362 / Google Summer of Code (inside logo image) / Falco (logo)

**Layout**

Single teal slide with the title at top left (x 3.4%, y 3.7%). A bulleted list of two levels occupies the left column from about x 5% to 70%, starting at y 18.5%, with hollow-circle sub-bullets indented under filled-circle bullets. The Google Summer of Code logo sits in the right column at x 69.5%, y 25.8%. Two right-aligned links sit below the logo, ending at x 96.6%. The Falco logo sits bottom right at x 87.1%, y 89.6%. There is no slide number or footer; left margin about 3.4%, right margin about 3.4%.

**Visuals**

One Google Summer of Code logo, placed as an image of 500 by 500 pixels in a white rounded-rectangle box. The box shows an orange (#F9A900) eight-pointed sunburst; inside it an orange (#E37400) circle holds a white code symbol '</>' with white slash. Below the sunburst are the words 'Google' and 'Summer of Code' in grey (#6E6E6E) sans-serif, centred. The image is not cropped and is not full-bleed; it is boxed with corner radius about 3% of its width and no shadow. One Falco logo at bottom right: a dark (#111111) stylised mark of crossed slanted strokes beside the bold dark wordmark 'Falco'. No charts, tables or photographs.

**Design**

Background: Solid teal #04748C filling the entire slide. Flat solid teal background #04748C with no gradient or pattern. Title in Ubuntu Bold, white #FFFFFF, about 5.9% of slide height, sentence case with ellipsis. Body text in Montserrat Regular with Montserrat Bold and Montserrat Italic emphasis, white #FFFFFF, about 3.95% of slide height; the fourth-level line emphasis is in Montserrat BoldItalic about 4.9%. Bullet glyphs in ArialMT, filled circle ● and hollow circle ○. Sub-items and links are in light grey #EEEEEE. Links are underlined. Line spacing about 7% of slide height between list items, with a larger gap before the Falco bullet and extra line spacing in the Event-generator item. Shapes: only the logo box has rounded corners; no other shapes or lines.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill, solid teal (solid fill covering the whole slide, no border, no gradient)
- logo at x 69.5, y 25.8, w 27.1, h 48.1 [#FFFFFF]: Google Summer of Code logo: orange sunburst with orange circle and white code symbol, text 'Google / Summer of Code' in grey below (image 500 by 500 px in a white rounded-rectangle box with corner radius about 3% of width, not cropped, no shadow, does not overlap text)
- title at x 3.4, y 3.7, w 28.1, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Let’s not forget… (sentence case, no letter-spacing)
- body at x 5.5, y 18.5, w 1.3, h 4 [ArialMT; font size 3.95% of slide height; #FFFFFF; left aligned]: ● (filled circle bullet)
- body at x 9.3, y 18.5, w 17.7, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: Participating in
- body at x 27.1, y 18.5, w 27.3, h 4 [Montserrat Bold; font size 3.95% of slide height; #FFFFFF; left aligned]: 2023 has been amazing
- body at x 10.5, y 25.6, w 1.3, h 4 [ArialMT; font size 3.95% of slide height; #FFFFFF; left aligned]: ○ (hollow circle bullet)
- body at x 14.3, y 25.6, w 8.9, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: Birth of
- body at x 23.3, y 25.6, w 34.2, h 4 [Montserrat Italic; font size 3.95% of slide height; #EEEEEE; left aligned]: falcosecurity/falco-playground (underlined hyperlink text)
- body at x 10.5, y 32.6, w 1.3, h 4 [ArialMT; font size 3.95% of slide height; #FFFFFF; left aligned]: ○ (hollow circle bullet)
- body at x 14.3, y 32.6, w 18.7, h 4 [Montserrat Bold; font size 3.95% of slide height; #FFFFFF; left aligned]: New maintainer
- body at x 33, y 32.6, w 29.4, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: onboarded in Falco family
- body at x 10.5, y 39.6, w 1.3, h 4 [ArialMT; font size 3.95% of slide height; #FFFFFF; left aligned]: ○ (hollow circle bullet)
- body at x 14.3, y 39.6, w 22.7, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: Talk at Cloud Native
- body at x 37.1, y 39.6, w 16.6, h 4 [Montserrat Bold; font size 3.95% of slide height; #FFFFFF; left aligned]: Wasm Day NA
- body at x 53.7, y 39.6, w 5.8, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: 2023
- body at x 5.2, y 49.4, w 1.7, h 4.9 [Arial Italic; font size 4.94% of slide height; #FFFFFF; left aligned]: ● (filled circle bullet)
- body at x 9.3, y 49.4, w 8.7, h 4.9 [Montserrat BoldItalic; font size 4.94% of slide height; #FFFFFF; left aligned]: Falco
- body at x 18.1, y 49.4, w 2.1, h 4.9 [Montserrat Italic; font size 4.94% of slide height; #FFFFFF; left aligned]: is
- body at x 20.2, y 49.4, w 19.5, h 4.9 [Montserrat BoldItalic; font size 4.94% of slide height; #FFFFFF; left aligned]: candidating
- body at x 39.7, y 49.4, w 3.8, h 4.9 [Montserrat Italic; font size 4.94% of slide height; #FFFFFF; left aligned]: for
- body at x 43.5, y 49.4, w 21.9, h 4.9 [Montserrat BoldItalic; font size 4.94% of slide height; #FFFFFF; left aligned]: Summer 2024!
- body at x 10.5, y 58.2, w 1.3, h 4 [Arial Bold; font size 3.95% of slide height; #FFFFFF; left aligned]: ○ (hollow circle bullet)
- body at x 14.3, y 58.2, w 19.7, h 4 [Montserrat Bold; font size 3.95% of slide height; #FFFFFF; left aligned]: Event-generator
- body at x 34, y 58.2, w 30.4, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: revamp and automation of
- body at x 14.3, y 65.2, w 6.5, h 4 [Montserrat Regular; font size 3.95% of slide height; #FFFFFF; left aligned]: Falco (continuation line of the Event-generator item)
- body at x 20.8, y 65.2, w 24, h 4 [Montserrat Bold; font size 3.95% of slide height; #FFFFFF; left aligned]: performance testing
- body at x 10.5, y 72.2, w 1.3, h 4 [ArialMT; font size 3.95% of slide height; #EEEEEE; left aligned]: ○ (hollow circle bullet)
- body at x 14.3, y 72.2, w 13, h 4 [Montserrat Regular; font size 3.95% of slide height; #EEEEEE; left aligned]: Waiting for (underlined hyperlink text)
- body at x 27.3, y 72.2, w 19, h 4 [Montserrat Bold; font size 3.95% of slide height; #EEEEEE; left aligned]: your application (underlined hyperlink text)
- body at x 46.3, y 72.2, w 0.6, h 4 [Montserrat Regular; font size 3.95% of slide height; #EEEEEE; left aligned]: !
- body at x 60.7, y 74.7, w 35.6, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #EEEEEE; right aligned]: github.com/cncf/mentoring/pull/1169 (underlined hyperlink text)
- body at x 52, y 80.9, w 44.3, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #EEEEEE; right aligned]: github.com/falcosecurity/evolution/issues/362 (underlined hyperlink text)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#111111]: Falco logo: dark stylised mark of crossed slanted strokes beside the wordmark 'Falco' (bottom-right corner logo, no box, no shadow)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 69.5, y 25.8, w 27.1, h 48.1: 500 by 500 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 28.1, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Let’s not forget…
- text at x 5.5, y 18.5, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ●
- text at x 9.3, y 18.5, w 17.7, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Participating in
- text at x 27.1, y 18.5, w 27.3, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: 2023 has been amazing
- text at x 10.5, y 25.6, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ○
- text at x 14.3, y 25.6, w 8.9, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Birth of
- text at x 23.3, y 25.6, w 34.2, h 4.0 [Montserrat-Italic; font size 3.95; #EEEEEE]: falcosecurity/falco-playground
- text at x 10.5, y 32.6, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ○
- text at x 14.3, y 32.6, w 18.7, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: New maintainer
- text at x 33.0, y 32.6, w 29.4, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: onboarded in Falco family
- text at x 5.2, y 49.4, w 1.7, h 4.9 [Arial-ItalicMT; font size 4.94; #FFFFFF]: ●
- text at x 9.3, y 49.4, w 8.7, h 4.9 [Montserrat-BoldItalic; font size 4.94; #FFFFFF]: Falco
- text at x 10.5, y 39.6, w 1.3, h 4.0 [ArialMT; font size 3.95; #FFFFFF]: ○
- text at x 14.3, y 39.6, w 22.7, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Talk at Cloud Native
- text at x 18.1, y 49.4, w 2.1, h 4.9 [Montserrat-Italic; font size 4.94; #FFFFFF]: is
- text at x 20.2, y 49.4, w 19.5, h 4.9 [Montserrat-BoldItalic; font size 4.94; #FFFFFF]: candidating
- text at x 37.1, y 39.6, w 16.6, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: Wasm Day NA
- text at x 39.7, y 49.4, w 3.8, h 4.9 [Montserrat-Italic; font size 4.94; #FFFFFF]: for
- text at x 43.5, y 49.4, w 21.9, h 4.9 [Montserrat-BoldItalic; font size 4.94; #FFFFFF]: Summer 2024!
- text at x 53.7, y 39.6, w 5.8, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: 2023
- text at x 10.5, y 58.2, w 1.3, h 4.0 [Arial-BoldMT; font size 3.95; #FFFFFF]: ○
- text at x 14.3, y 58.2, w 19.7, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: Event-generator
- text at x 34.0, y 58.2, w 30.4, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: revamp and automation of
- text at x 14.3, y 65.2, w 6.5, h 4.0 [Montserrat-Regular; font size 3.95; #FFFFFF]: Falco
- text at x 20.8, y 65.2, w 24.0, h 4.0 [Montserrat-Bold; font size 3.95; #FFFFFF]: performance testing
- text at x 10.5, y 72.2, w 1.3, h 4.0 [ArialMT; font size 3.95; #EEEEEE]: ○
- text at x 14.3, y 72.2, w 13.0, h 4.0 [Montserrat-Regular; font size 3.95; #EEEEEE]: Waiting for
- text at x 27.3, y 72.2, w 19.0, h 4.0 [Montserrat-Bold; font size 3.95; #EEEEEE]: your application
- text at x 46.3, y 72.2, w 0.6, h 4.0 [Montserrat-Regular; font size 3.95; #EEEEEE]: !
- text at x 60.7, y 74.7, w 35.6, h 3.5 [Montserrat-Regular; font size 3.46; #EEEEEE]: github.com/cncf/mentoring/pull/1169
- text at x 52.0, y 80.9, w 44.3, h 3.5 [Montserrat-Regular; font size 3.46; #EEEEEE]: github.com/falcosecurity/evolution/issues/362

### Slide 31

**Review notes**

- Review: The deck has a consistent teal identity, a clear section structure (slides 7, 14, 25, 31 as dividers) and a readable route from history to news to roadmap to community.

**Text**

Falco Ecosystem Projects

**Layout**

A single title block sits on the left at roughly mid-height, about half the slide down, with its left edge aligned to the logo at about 4.2% from the left margin. The Falco logo sits top-left, and the right side is empty apart from a faint watermark. There is no footer and no slide number.

**Visuals**

Two visual elements. (1) A Falco logo at top-left: a stylised icon of crossed diagonal strokes beside the lowercase-style wordmark 'Falco' in a dark slate-teal colour (about #1E3B3F). (2) A large, very faint watermark of the Falco icon, a set of diagonal rounded strokes forming a crossed 'X' shape, in pale teal (about #E3F4F6). It runs from the upper-middle of the right side down to the bottom-right corner and is cropped by the bottom and right slide edges. It is flat, with no shading, shadow or gradient. A tiny 4 by 2 pixel image sits at 87.1%, 89.6% and is not visible.

**Design**

Background: White (#FFFFFF) with a full-slide faint teal (#E3F4F6) Falco icon watermark, over a teal #04748C fill that is hidden beneath it. Plain white background with a pale teal watermark. The title is dark near-black (#171717) in Ubuntu Medium, sans-serif, normal case, with no letter-spacing, at about 8.9% of slide height. There are no accent bars, rules, boxes or corner radii. The logo is dark slate-teal (about #1E3B3F). The underlying full-slide fill is teal #04748C, but it is covered by the full-slide image, so it is not visible.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide solid fill beneath the background image (Covers the whole slide. Not visible because the full-slide image above it is opaque.)
- illustration at x 0, y 0, w 100, h 100 [#E3F4F6]: Full-slide background image: white field with a faint pale-teal Falco icon watermark of diagonal rounded strokes forming a crossed X, cropped at the bottom and right edges (Image is 1200 by 628 pixels and covers the full slide. Flat, no shadow, no overlay, not boxed. The watermark sits mainly in the right-hand third, from about y 40% to the bottom edge.)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#1E3B3F; left aligned]: Falco logo: stylised icon of crossed diagonal strokes followed by the wordmark 'Falco' (Top-left corner, on white. Icon is about one third of the logo width, wordmark in a bold sans-serif. Shown as a 4 by 2 pixel image in the file measurements.)
- image at x 87.1, y 89.6, w 8.7, h 5.9: Tiny placeholder image, not visible on the rendered slide (4 by 2 pixels. Nothing visible at this position on the slide.)
- title at x 4.2, y 49.5, w 58, h 8.9 [Ubuntu Medium, medium weight, normal style, no capitals, no letter-spacing; font size 8.89% of slide height; #171717; left aligned]: Falco Ecosystem Projects (Single line, sentence-style capitalisation. Sits on top of the watermark, with no overlap of the title and the watermark strokes.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 4.2, y 49.5, w 58.0, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: Falco Ecosystem Projects

### Slide 32

**Text**

Falcosidekick
Falcosidekick is getting more outputs!
●
Quickwit
●
Dynatrace
●
OTEL Traces
●
Sumologic
●
AWS S3 compatibility with MinIO and IBM
Cloud COS
Release 2.29.0 coming soon…

**Layout**

Two-panel split slide: a left column of about 45.6% width holds the large title and the gopher mascot, and a right column of about 54.4% width holds the body text, bullet list and QR code. The title sits top-left at about 3.4% from the left and 3.8% from the top. The right text block is left-aligned starting at x 48.2%, with the first line at y 19.0% and the last line at y 53.8%. The QR code sits bottom-right at x 85.1%, y 66.7%, and the Falco logo sits below it at x 87.1%, y 89.6%. There is no footer text and no slide number.

**Visuals**

Gopher mascot illustration on the left panel, centred around x 9.4 to 35.7%, y 29.5 to 76.3%. It is the Go gopher mascot, a light blue rounded bean-shaped body with large white eyes with black pupils, a small tan-beige snout and feet, and translucent teal feathered wings extending to the upper left, drawn in a flat cartoon style with dark outlines. It is a boxed raster image with no crop and no overlay. A second, slightly smaller duplicate gopher image sits at x 9.7%, y 29.7%, w 25.7%, h 45.7%, and this is the same mascot. QR code at x 85.1%, y 66.7%, w 12.1%, h 21.3%: black square modules on a white square, with three finder squares in the corners and a small black dinosaur icon at the centre. Falco logo at bottom right, x 87.1%, y 89.6%, w 8.7%, h 5.9%: the Falco word mark in dark grey #2B2B2B with a stylised slash-mark symbol to its left.

**Design**

Background is a two-tone teal split. The left panel is a bright cyan-teal #00B0CA with a faint lighter curved swirl pattern in the top area. The right panel is a deeper teal #04748C that fills the rest of the slide. Title text is white #FFFFFF in Ubuntu Bold, sans-serif, at about 6.9% of slide height. Body text is white #FFFFFF in Ubuntu Regular, sans-serif, at about 3.5% of slide height, with the bold 'Falcosidekick' at the start of the first line. Bullets are white solid circles set in Arial. Accent colour: none. Lines and shapes: the QR code has a square white backing with no radius and no shadow. No gradients, no shadows, no corner radii on text.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 45.6, h 100 [#00B0CA]: Left panel background rectangle with faint lighter swirl pattern (Full-height rectangle covering the left 45.6% of the slide, no border, no shadow, back layer.)
- shape at x 0, y 0, w 100, h 100 [#04748C]: Right panel background fill (Full-slide fill, back layer behind the left panel; visible as the right portion.)
- illustration at x 9.4, y 29.5, w 26.3, h 46.8 [#5BC8DC]: Gopher mascot illustration with translucent teal feathered wings (Boxed raster image, no crop, no border, no shadow; light blue body with dark outline, white eyes, tan feet and snout.)
- illustration at x 9.7, y 29.7, w 25.7, h 45.7 [#5BC8DC]: Duplicate gopher mascot image, same subject (Smaller duplicate placed over the first image; the same gopher artwork.)
- title at x 3.4, y 3.8, w 24.9, h 6.9 [Ubuntu Bold, sans-serif, normal case, no letter-spacing; font size 6.91% of slide height; #FFFFFF; left aligned]: Falcosidekick
- body at x 48.2, y 19, w 34.3, h 3.5 [Ubuntu Regular, sans-serif; 'Falcosidekick' in Ubuntu Bold; font size 3.46% of slide height; #FFFFFF; left aligned]: Falcosidekick is getting more outputs! (Single line; bold run covers 'Falcosidekick' only.)
- bullet list at x 48.2, y 25.3, w 42, h 24.1 [Ubuntu Regular, sans-serif, normal case; font size 3.46% of slide height; #FFFFFF; left aligned]: Quickwit / Dynatrace / OTEL Traces / Sumologic / AWS S3 compatibility with MinIO and IBM Cloud COS (Solid white round bullets (●) in Arial set at x 49.6%, text indented to x 53.2%; line spacing about 4.1% of slide height between items; the last item wraps onto a second line 'Cloud COS' at y 45.7%.)
- body at x 48.2, y 53.8, w 26.2, h 3.5 [Ubuntu Regular, sans-serif, normal case; font size 3.46% of slide height; #FFFFFF; left aligned]: Release 2.29.0 coming soon…
- shape at x 85.1, y 66.7, w 12.1, h 21.3 [#FFFFFF]: White QR code backing square with QR code image (Square white backing with black QR modules, three finder squares and a small black dinosaur icon at the centre; no border, no shadow, no radius.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#2B2B2B]: Falco logo (Dark grey Falco word mark with slash-mark symbol, placed on the deep teal background.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 45.6, h 100.0: 208 by 256 pixels
- image at x 9.4, y 29.5, w 26.3, h 46.8: 379 by 379 pixels
- image at x 9.7, y 29.7, w 25.7, h 45.7: 292 by 292 pixels
- image at x 85.1, y 66.7, w 12.1, h 21.3: 234 by 232 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.8, w 24.9, h 6.9 [Ubuntu-Bold; font size 6.91; #FFFFFF]: Falcosidekick
- text at x 48.2, y 19.0, w 12.5, h 3.5 [Ubuntu-Bold; font size 3.46; #FFFFFF]: Falcosidekick
- text at x 60.7, y 19.0, w 21.8, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: is getting more outputs!
- text at x 49.6, y 25.3, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 53.2, y 25.3, w 7.8, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Quickwit
- text at x 49.6, y 29.4, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 53.2, y 29.4, w 9.0, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Dynatrace
- text at x 49.6, y 33.5, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 53.2, y 33.5, w 10.8, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: OTEL Traces
- text at x 49.6, y 37.5, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 53.2, y 37.5, w 9.2, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Sumologic
- text at x 49.6, y 41.6, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ●
- text at x 53.2, y 41.6, w 36.9, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: AWS S3 compatibility with MinIO and IBM
- text at x 53.2, y 45.7, w 9.3, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Cloud COS
- text at x 48.2, y 53.8, w 26.2, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Release 2.29.0 coming soon…

### Slide 33

**Text**

Falcoctl gets new features 🧰
Flexible mechanism to download drivers, replacing an aging / bash script
falcoctl
Driver Repo
Falco
Artifact and registry inspection tools (artifact config)
More signature options (KMS…)
Falco

**Layout**

Free-form layout with no grid: the title sits top-left at about x 3.4%, y 3.7%, with a row of three icon-and-text pairs below it. Row one holds a Driver Repo globe, a falcoctl arrow and the Falco logo, with its description to the right at x 34.5%. Rows two and three each pair an icon at the left with a text line starting at x 22.6%. The Falco logo sits bottom-right at about x 87%, y 90%, and the emoji toolbox is inline after the title. Left margin is about 3.5% and there is no visible slide number or footer text.

**Visuals**

Row one: a blue glossy globe icon (about 8.2% wide, centred at x 9.3%, y 49%) labelled 'Driver Repo' beneath it; a thin grey-brown arrow (about #5A4A42, 0.2% stroke) running horizontally from the globe to the Falco logo, with the italic label 'falcoctl' above it; a teal Falco logo mark (cyan #1FB5C4 chevron-like strokes) at x 24.6%, y 21.5%, labelled 'Falco' beneath it. Row two: a magnifying glass emoji (silver lens, black handle, about 8.8% wide at x 8.9%, y 71%). Row three: a gold key emoji (about 8.2% wide, x 5.7%, y 21%, drawn at bottom-left of the row). Bottom-right: the Falco logo in dark navy-black (#0B1F2A) with cyan chevron mark. Title toolbox emoji is a red toolbox (#D0302A) with grey clasps at x 46.2%, y 2.9%.

**Design**

Background: Solid teal #04748C.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background rectangle (Covers the entire slide, no border or shadow)
- title at x 3.4, y 3.7, w 42.8, h 5.9 [Ubuntu, bold weight; font size 5.93% of slide height; #FFFFFF; left aligned]: Falcoctl gets new features 🧰
- icon at x 46.2, y 2.9, w 4.2, h 6.9 [#D0302A]: Red toolbox emoji (NotoColorEmoji) following the title (Colour emoji glyph, 136 by 128 pixels)
- icon at x 8.9, y 71.1, w 8.8, h 15.7 [#2A7FBF]: Blue glossy globe emoji representing Driver Repo (160 by 160 pixels; shiny sphere with meridian lines; the image box is at the top of the Driver Repo label area)
- icon at x 9.3, y 49.2, w 8.2, h 14.5 [#2A7FBF]: Globe image placed at the Driver Repo position (160 by 160 pixels)
- icon at x 5.7, y 21.2, w 8.2, h 14.5 [#2A7FBF]: Globe image placed at the upper-left of row one (160 by 160 pixels)
- logo at x 24.6, y 21.5, w 7.7, h 13.8 [#1FB5C4]: Falco logo mark in teal (128 by 128 pixels; three diagonal strokes forming a stylised chevron)
- text at x 17.5, y 28.5, w 4.6, h 2.5 [Roboto, medium weight, italic; font size 2.47% of slide height; #FFFFFF; center aligned]: falcoctl
- shape at x 17.5, y 36.8, w 10, h 0.3 [#5A4A42]: Arrow from Driver Repo to Falco (Thin horizontal line, about 0.2% stroke, with a small arrowhead at the right end pointing to the Falco logo)
- text at x 4.4, y 37.9, w 10.8, h 3.5 [Ubuntu, medium weight; font size 3.46% of slide height; #FFFFFF; center aligned]: Driver Repo
- text at x 26.2, y 37.5, w 4.7, h 3.5 [Ubuntu, medium weight; font size 3.46% of slide height; #FFFFFF; center aligned]: Falco
- text at x 34.5, y 26.2, w 59.1, h 7.6 [Montserrat, regular weight; font size 3.46% of slide height; #FFFFFF; left aligned]: Flexible mechanism to download drivers, replacing an aging / bash script (Line spacing about 4.1% of slide height between the two lines)
- icon at x 8.9, y 49.2, w 8.8, h 15.7 [#B8C4CC]: Magnifying glass emoji representing artifact and registry inspection tools (Silver lens with grey rim and black handle, 160 by 160 pixels)
- text at x 22.6, y 53.7, w 37, h 3.5 [Montserrat, regular weight; 'artifact config' in RobotoMono, regular weight; font size 3.46% of slide height; #FFFFFF; left aligned]: Artifact and registry inspection tools (artifact config) ('artifact config' is set in monospace at x 59.0%, width 17.5%; the closing parenthesis sits at x 76.5%)
- icon at x 5.7, y 71.1, w 8.2, h 14.5 [#F2B705]: Gold key emoji representing signature options (160 by 160 pixels; key with round bow and toothed bit)
- text at x 22.6, y 77.5, w 30.2, h 3.5 [Montserrat, regular weight; font size 3.46% of slide height; #FFFFFF; left aligned]: More signature options (KMS…)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#0B1F2A]: Falco logo (bottom-right) (Dark navy-black wordmark 'Falco' with cyan chevron mark, no background)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 8.9, y 71.1, w 8.8, h 15.7: 160 by 160 pixels
- image at x 9.3, y 49.2, w 8.2, h 14.5: 160 by 160 pixels
- image at x 5.7, y 21.2, w 8.2, h 14.5: 160 by 160 pixels
- image at x 24.6, y 21.5, w 7.7, h 13.8: 128 by 128 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 46.2, y 2.9, w 4.2, h 6.9: 136 by 128 pixels
- text at x 3.4, y 3.7, w 42.8, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Falcoctl gets new features
- text at x 46.2, y 3.7, w 4.2, h 5.9 [NotoColorEmoji; font size 5.93; #FFFFFF]: 🧰
- text at x 46.2, y 3.7, w 4.2, h 5.9 [NotoColorEmoji; font size 5.93; #FFFFFF]: 🧰
- text at x 34.5, y 26.2, w 59.1, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Flexible mechanism to download drivers, replacing an aging
- text at x 34.5, y 30.3, w 10.7, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: bash script
- text at x 4.4, y 37.9, w 10.8, h 3.5 [Ubuntu-Medium; font size 3.46; #FFFFFF]: Driver Repo
- text at x 26.2, y 37.5, w 4.7, h 3.5 [Ubuntu-Medium; font size 3.46; #FFFFFF]: Falco
- text at x 17.5, y 28.5, w 4.6, h 2.5 [Roboto-MediumItalic; font size 2.47; #FFFFFF]: falcoctl
- text at x 22.6, y 53.7, w 36.4, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Artifact and registry inspection tools (
- text at x 59.0, y 53.7, w 17.5, h 3.5 [RobotoMono-Regular; font size 3.46; #FFFFFF]: artifact config
- text at x 76.5, y 53.7, w 0.6, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: )
- text at x 22.6, y 77.5, w 30.2, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: More signature options (KMS…)

### Slide 34

**Text**

Helm Chart v4
✅ Out of the box compatibility with k8s / metacollector and plugin
✅ Automatic rule and plugin installation
✅ Driver selection using falcoctl
Falco

**Layout**

Two-column split at about 45.6% of the width: a cyan left panel holds the title at top left and the Helm logo centred in its lower-middle area, while a darker teal right panel holds a vertically centred three-item bullet list starting at about 49% of the width. The Falco logo sits bottom right inside the teal panel. The title is left-aligned with a margin of about 3.4% of the width and 3.8% from the top. No slide number or footer text is visible.

**Visuals**

Helm logo: a dark navy (#10188A) Helm ship's-wheel mark with six spokes or handles (three above, three below the wordmark) around the word HELM in bold capitals, centred on the cyan left panel, about 23% wide and 41% tall, drawn at 256 by 256 pixels, unboxed and uncropped. Left panel background: a 104 by 128 pixel cyan (#00B1CB) image with a lighter cyan (#1DB5CF) diagonal streak running from the top centre toward the lower right edge of the panel, visibly pixelated, with no overlay. Bullet markers: three small two-tone green squares (light green #8DBB4F with a darker green #6E9F3A lower-right block), each about 2.4% wide and 4% tall, one per bullet, reading as the emoji check-mark glyph. Falco logo: a dark charcoal (#1A1A1A) stylised double-slash mark followed by the wordmark Falco in bold dark lettering, bottom right.

**Design**

Background: Solid teal #04748C across the whole slide, with the left 45.6% covered by a cyan #00B1CB textured image. Two flat colour fields with a textured image on the left; no gradients, shadows or rounded corners. Title is white bold humanist sans-serif (Ubuntu Bold), large, about 6.9% of slide height in size with capitals about 4.8% high. Body bullets are white regular Ubuntu sans-serif at about 3.5% of slide height, with generous line spacing (second line of the first bullet sits about 6.3% below the first line). Accent colour is light green (#8DBB4F) for the bullet squares. Helm logo colour is dark navy (#10188A). Falco wordmark is near-black. Title colour #FFFFFF, body colour #FFFFFF.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill, solid teal (Flat fill, no border, covers the whole slide and is the back-most layer.)
- photo at x 0, y 0, w 45.6, h 100 [#00B1CB]: Left panel background image: cyan texture with a lighter diagonal streak, pixelated at 104 by 128 pixels (Unboxed, full-height, flush to the left edge and the slide top; no overlay; the streak fades toward the lower right of the panel.)
- illustration at x 10.6, y 31, w 23.1, h 41.2 [#10188A]: Helm logo: navy Helm wheel mark with the word HELM (Drawn from a 256 by 256 pixel image, placed on the cyan panel with no box or shadow; opacity full.)
- shape at x 49.3, y 40.1, w 2.4, h 4 [#8DBB4F]: Bullet marker 1: green square (Two-tone square with darker green #6E9F3A lower-right block; sits left of the first bullet line.)
- shape at x 49.3, y 52.5, w 2.4, h 4 [#8DBB4F]: Bullet marker 2: green square (Two-tone square with darker green #6E9F3A lower-right block; sits left of the second bullet line.)
- shape at x 49.3, y 58.8, w 2.4, h 4 [#8DBB4F]: Bullet marker 3: green square (Two-tone square with darker green #6E9F3A lower-right block; sits left of the third bullet line.)
- title at x 3.4, y 3.8, w 26.3, h 6.9 [Ubuntu, Bold, sans-serif, no italics, no capitals, normal letter-spacing; font size 6.91% of slide height; #FFFFFF; left aligned]: Helm Chart v4 (Single line, sits over the cyan left panel top-left.)
- body at x 49.3, y 40.5, w 2.4, h 3.5 [Noto Color Emoji, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ✅ (Check-mark glyph rendered as the green square marker; aligned to the first bullet line.)
- body at x 54.2, y 40.5, w 33.1, h 9.8 [Ubuntu, Regular, sans-serif, no italics, no capitals, normal letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: Out of the box compatibility with k8s / metacollector and plugin (Two lines, first line at y 40.5, second line at y 46.8; line pitch about 6.3% of slide height; bullet with no visible glyph other than the marker.)
- body at x 49.3, y 53, w 2.4, h 3.5 [Noto Color Emoji, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ✅ (Check-mark glyph rendered as the green square marker.)
- body at x 54.2, y 53, w 33.1, h 3.5 [Ubuntu, Regular, sans-serif, no italics, no capitals, normal letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: Automatic rule and plugin installation (Single line.)
- body at x 49.3, y 59.2, w 2.4, h 3.5 [Noto Color Emoji, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ✅ (Check-mark glyph rendered as the green square marker.)
- body at x 54.2, y 59.2, w 26, h 3.5 [Ubuntu, Regular, sans-serif, no italics, no capitals, normal letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: Driver selection using falcoctl (Single line.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: dark double-slash mark with the wordmark Falco (Corner logo bottom right, dark charcoal on the teal panel, no box.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 45.6, h 100.0: 104 by 128 pixels
- image at x 10.6, y 31.0, w 23.1, h 41.2: 256 by 256 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 49.3, y 40.1, w 2.4, h 4.0: 3 by 2 pixels
- image at x 49.3, y 52.5, w 2.4, h 4.0: 3 by 2 pixels
- image at x 49.3, y 58.8, w 2.4, h 4.0: 3 by 2 pixels
- text at x 3.4, y 3.8, w 26.3, h 6.9 [Ubuntu-Bold; font size 6.91; #FFFFFF]: Helm Chart v4
- text at x 49.3, y 40.5, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅
- text at x 54.2, y 40.5, w 33.1, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Out of the box compatibility with k8s
- text at x 54.2, y 46.8, w 22.0, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: metacollector and plugin
- text at x 49.3, y 53.0, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅
- text at x 54.2, y 53.0, w 33.1, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Automatic rule and plugin installation
- text at x 49.3, y 59.2, w 2.4, h 3.5 [NotoColorEmoji; font size 3.46; #FFFFFF]: ✅
- text at x 54.2, y 59.2, w 26.0, h 3.5 [Ubuntu-Regular; font size 3.46; #FFFFFF]: Driver selection using falcoctl

### Slide 35

**Text**

The Falco Playground at play.falco.org
Falco
Docs
Blogs
Community
About
Star
15
Run
Import Yaml
Download
Copy
Load Examples
Run with scap
Share
Upload scap and run
Play with Falco right
form your browser
(also on mobile!)
Visit play.falco.org to
get started!
Falco
Code editor lines 1-26: - macro: user_ssh_directory / condition: (fd.name contains '/.ssh/' and fd.name glob '/home/*/.ssh... / - macro: never_true / condition: (evt.num=0) / - macro: open_read / condition: (evt.type in (open,openat,openat2) and evt.is_open_read=t... / - macro: open_directory / condition: (evt.type in (open,openat,openat2) and evt.is_open_read=t... / - macro: user_known_read_ssh_information_activities / condition: (never_true) / - rule: Read ssh information / desc: Any attempt to read files below ssh directories by non-ssh pro... / condition: > / ((open_read or open_directory) and / (user_ssh_directory or fd.name startswith /root/.ssh) and / not user_known_read_ssh_information_activities and / not proc.name in (ssh_binaries)) / output: > / ssh-related file/directory read by non-ssh program ( / user=%user.name user_loginuid=%user.loginuid / command=%proc.cmdline pid=%proc.pid file=%fd.name
Log output: Mon Nov 6 15:03:52 2023: Falco version: 0.37.0-81+dae1e66 (wasm) / Mon Nov 6 15:03:52 2023: CLI args: falco --validate rule.yaml -o json_output=true -o log_level=debug -v -o log_stderr=true / Mon Nov 6 15:03:52 2023: Validating rules file(s): / Mon Nov 6 15:03:52 2023: rule.yaml

**Layout**

Full-bleed teal slide with the title in a single line across the top left at about 3.4% from the left edge and 3.7% from the top. A left column holds two blocks of left-aligned body text, centred vertically around the middle of the slide, with the QR code below them at lower left. The Falco application screenshot sits boxed in the right half, spanning from about 34% to 94.6% horizontally and from 19.7% to 84.2% vertically. The Falco logo sits in the bottom-right corner. There is no footer, slide number or visible source line.

**Visuals**

Photograph-style screenshot of the Falco Playground web app, boxed with rounded corners, not cropped, unshaded, placed at x 33.9 y 19.7 w 60.7 h 64.5 (1024 by 612 pixels). It is a dark UI mockup in near-black #1E1E1E. The top bar shows the Falco logo in cyan at left and the nav links Docs, Blogs, Community and About in cyan, a sun icon, and a white GitHub Star button showing 15. Below, on the left, is a code editor panel with line numbers 1 to 26 in grey and syntax-coloured YAML text: keys and macro names in cyan and green, conditions in orange and salmon, on a dark background with a faint minimap at its right edge. On the right are buttons: a filled cyan Run button with a play icon, Import Yaml, Download, Copy, Load Examples, Run with scap, Share, and Upload scap and run, all outlined in white with rounded corners. Below them is a dark grey output panel with green monospaced log text. Composition is a flat frontal view of the app window. Lighting is flat, with no shading. Dominant colours are near-black, cyan #1BB5D0 and green #7CC47A. A QR code with a dinosaur icon sits boxed at bottom left, x 5.3 y 68.7 w 13.9 h 24.9 (218 by 220 pixels). It is a black-and-white QR code on a white square with no border, centred on a white background. The small Falco logo at bottom right, x 87.1 y 89.6 w 8.7 h 5.9, is a dark navy-black mark with a stylised slash emblem and the word Falco, placed on the teal background.

**Design**

Background: Solid teal #04748C. Flat teal background #04748C with no gradient or texture. Title in bold white #FFFFFF Ubuntu Bold sans-serif, about 5.9% of slide height, with normal tracking. Body text is regular white #FFFFFF Montserrat sans-serif, about 3.5% of slide height, with normal tracking and no capitals. Accent colour is cyan #1BB5D0 in the screenshot. Screenshot panel has rounded corners of about 1% of slide width, a dark #1E1E1E fill and a subtle drop shadow. QR code has a white square fill #FFFFFF and black modules #000000. Logo is dark #1A1A1A.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background rectangle covering the whole slide (Flat fill, no outline, no shadow, opacity 100%.)
- photo at x 33.9, y 19.7, w 60.7, h 64.5 [#1E1E1E]: Screenshot of the Falco Playground web app showing the code editor with YAML rules, Run, Import Yaml, Download, Copy, Load Examples, Run with scap, Share, Upload scap and run buttons, and a green log output panel (Boxed, not cropped, rounded corners about 1% of slide width, subtle drop shadow, sits on the teal background, opacity 100%.)
- photo at x 5.3, y 68.7, w 13.9, h 24.9 [#FFFFFF]: QR code linking to play.falco.org with a dinosaur icon in the centre (Black modules on a white square with no border, not cropped, sharp corners.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo (Dark mark with slash emblem and the word Falco, placed at bottom-right corner on the teal background.)
- title at x 3.4, y 3.7, w 60.2, h 5.9 [Ubuntu Bold, weight bold, no italics, no capitals, normal letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: The Falco Playground at play.falco.org
- body at x 6.2, y 39.3, w 20.4, h 11.6 [Montserrat, weight regular, no italics, no capitals, normal letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: Play with Falco right / form your browser / (also on mobile!) (Line spacing about 4.0% of slide height, no bullets.)
- body at x 6.2, y 55.6, w 20.3, h 7.6 [Montserrat, weight regular, no italics, no capitals, normal letter-spacing; font size 3.46% of slide height; #FFFFFF; left aligned]: Visit play.falco.org to / get started! (Line spacing about 4.0% of slide height, no bullets, separated from the block above by an empty line.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 33.9, y 19.7, w 60.7, h 64.5: 1024 by 612 pixels
- image at x 5.3, y 68.7, w 13.9, h 24.9: 218 by 220 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 3.4, y 3.7, w 60.2, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: The Falco Playground at play.falco.org
- text at x 6.2, y 39.3, w 20.4, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Play with Falco right
- text at x 6.2, y 43.4, w 18.4, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: form your browser
- text at x 6.2, y 47.4, w 16.0, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: (also on mobile!)
- text at x 6.2, y 55.6, w 20.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Visit play.falco.org to
- text at x 6.2, y 59.7, w 11.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: get started!

### Slide 36

**Text**

Falco is a CNCF graduate
Now what?

**Layout**

Single left-aligned title block set in the lower-middle of the slide, starting at about 4.2% from the left edge, with the Falco logo in the top-left corner at about 4.2% from the left and 6.3% from the top. A decorative light-teal watermark runs off the bottom-right edge. No footer or slide number is visible.

**Visuals**

Falco logo (top-left): a stylised mark of crossed diagonal strokes resembling a falcon wing, followed by the lowercase-style wordmark 'Falco', in dark slate-teal #1F3B3F. Watermark (right and bottom): a large, low-contrast version of the same crossed-stroke mark in pale teal #E3F5F7, with rounded-ended strokes, cropped by the right and bottom slide edges and sitting behind the title area on the right side. No photographs, charts or other visuals.

**Design**

Background: Solid white #FFFFFF, with a full-slide image of the pale teal crossed-stroke watermark on top (the file also contains a #04748C fill underneath, fully covered by that image so it is not visible). Plain white background #FFFFFF with a pale teal watermark. Title text is near-black #171717 in Ubuntu Medium, sans-serif, roughly 8.9% of slide height, with normal weight and no capitals or letter-spacing change. Accent colour is the pale teal #E3F5F7 watermark and the dark slate-teal #1F3B3F logo. No shapes, borders, shadows or gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- image at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-slide background image: white field with pale teal (#E3F5F7) crossed-stroke watermark on the right and bottom (Image 1200 by 628 px covering the whole slide, back-most layer; the #04748C fill beneath it is fully hidden.)
- image at x 87.1, y 89.6, w 8.7, h 5.9: Empty small image (no visible content) (Placed image 4 by 2 px at bottom-right; nothing distinct is visible, it sits over the watermark.)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#1F3B3F]: Falco logo: crossed-stroke falcon mark with the wordmark 'Falco' (Top-left corner; mark is a set of diagonal strokes forming an X-like wing shape, wordmark in a humanist sans-serif in dark slate-teal.)
- title at x 4.2, y 49.5, w 56.9, h 8.9 [Ubuntu Medium, sans-serif, normal weight, no italics, no capitals change, no letter-spacing change; font size 8.89% of slide height; #171717; left aligned]: Falco is a CNCF graduate
- title at x 4.2, y 60.2, w 25.4, h 8.9 [Ubuntu Medium, sans-serif, normal weight, no italics, no capitals change, no letter-spacing change; font size 8.89% of slide height; #171717; left aligned]: Now what?

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- text at x 4.2, y 49.5, w 56.9, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: Falco is a CNCF graduate
- text at x 4.2, y 60.2, w 25.4, h 8.9 [Ubuntu-Medium; font size 8.89; #171717]: Now what?

### Slide 37

**Text**

Falco
About
Docs
Blog
Community
Training
Versions
Search
English
Try Falco
Falco is now a CNCF Graduated Project!
Thank you everyone for helping Falco soar! ❤️
The Falco Project
Getting Started
Install and Operate
Falco Rules
Falco Outputs
Falco Plugins
Event Sources
Metrics
gRPC API
Tutorials
Reference
Troubleshooting
Contribute
Roadmap
Available Documentation Versions
Edit this page
Create child page
Create documentation issue
Create project issue
On this page
Road to Falco 1.0.0
Falco Engine
Rules Syntax
Drivers
Distribution
Documentation
Integrations
The Falco Roadmap
The Project direction
The Falco maintainers team works daily to provide more features, robust security and stability and better user experience to all adopters.
The maintainer team frequently communicates and meets to decide the next important areas for the project. This page is updated to list the efforts that are currently ongoing.
Road to Falco 1.0.0
Falco is on track to release its 1.0.0 version. While "one point oh" is just a number, it is a signal from the community that the project has reached a certain degree of stability and maturity. Following the graduation within the CNCF, this is the next logical step. Below we are listing the main topics we wish to address for this milestone.
Falco Engine
Provide standardized features adoption and depreciation policies, to make sure users understand when features can be considered stable and when they are being removed
Make flagship features even more robust
Streamlining falco.yaml structure
CLI args consolidation and standardization
Advanced metrics support
Rules Syntax
Address current language inconsistencies arising from our commitment to backward compatibility
Introduce new constructs to address the most common user requests

**Layout**

Web page screenshot in a three-column layout: a left navigation sidebar (about x 2 to 16 percent), a main reading column starting at x 19.3 percent and ending near x 82 percent, and a right 'On this page' rail (x 83 to 98 percent). A top navigation bar spans the full width (y 0 to 6.5 percent) with the Falco logo at top left and a Try Falco button at top right, followed by a full-width announcement band (y 6.5 to 16 percent). The page title 'The Falco Roadmap' sits top-left of the main column at about y 25 percent, left-aligned with the subtitle and body; there is no footer or slide number, and a browser scrollbar runs down the right edge.

**Visuals**

A full-slide screenshot of the Falco documentation web page (Roadmap section), shown full-bleed with no frame. Elements: the Falco logo (teal stylised X mark and wordmark 'Falco') at top left; a search magnifier icon beside 'Search'; a small chevron (down arrow) after About, Community, Versions and English; a teal rounded button labelled 'Try Falco'; in the announcement band, a blue CNCF logo square (white diagonal-hatched inner pattern) and a teal Falco mark; a red heart emoji after the second banner line; left sidebar chevrons (right-pointing) beside each section name; a teal rule under 'The Falco Project'; a 'graduation' hyperlink in teal inside the paragraph; an inline grey monospace code chip 'falco.yaml'; bullet dots for the two bullet lists; teal line icons for Edit this page (pencil square), Create child page (pencil square), Create documentation issue (GitHub mark) and Create project issue (checklist icon); a thin grey vertical rule to the left of the 'On this page' sub-items; a grey scrollbar with a darker thumb at the top right. Lighting is flat; colours are white, near-white, charcoal and teal. Two hidden raster images exist behind the screenshot: one 1200 by 628 pixels and a 4 by 2 pixel image at the bottom right, both obscured and not visible.

**Design**

Background: Solid white #FFFFFF page background, with a very light grey #F7F8F9 announcement band across the top. Clean flat web-documentation look on white. Background white with a very light grey (#F7F8F9) announcement band. Page title near-black #1A1A1A, bold sans-serif (Open Sans Bold-like), about 4 percent of slide height. Subtitle 'The Project direction' light grey #6B7280 regular weight, about 2.2 percent. Body text charcoal #3A3F44 regular sans-serif (Open Sans-like), about 1.6 percent of slide height. Sub-headings 'Falco Engine' and 'Rules Syntax' bold near-black #1A1A1A about 1.8 percent. Accent teal #2FA7C0 used for the logo, Try Falco button fill (#2FB0C6 with white text), the 'The Falco Project' and 'Roadmap' navigation labels, hyperlinks, action icons and the 'graduation' link. Navigation text charcoal #2B2F33 about 1.7 percent. Lines are thin: a 1 px teal underline under 'The Falco Project' and a 1 px light grey vertical rule (#D9DDE1) by the right rail. The Try Falco button has rounded corners of about 6 px radius and no shadow. Code chip has light grey #EEF0F2 fill with a monospace font. No gradients or shadows.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide solid fill behind the screenshot (hidden, covered by the page screenshot) (Solid rectangle, not visible because the screenshot covers it entirely.)
- photo at x 0, y 0, w 100, h 100 [#FFFFFF]: Full-bleed screenshot of the Falco Roadmap documentation web page, 2048 by 1152 pixels (Shown uncropped, full-bleed, no frame, no overlay or tint; covers the slide.)
- logo at x 1.4, y 1.1, w 6.9, h 4.4 [#2FA7C0]: Falco logo: teal X mark with wordmark 'Falco' (Top-left corner of the navigation bar.)
- body at x 34.3, y 2.2, w 3.5, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: About (Navigation item with a down chevron after the text.)
- body at x 39.5, y 2.2, w 2.2, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Docs (Navigation item.)
- body at x 43.4, y 2.2, w 2, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Blog (Navigation item.)
- body at x 47.2, y 2.2, w 5.9, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Community (Navigation item with a down chevron after the text.)
- body at x 54.8, y 2.2, w 3.6, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Training (Navigation item.)
- body at x 59.7, y 2.2, w 4.8, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Versions (Navigation item with a down chevron after the text.)
- icon at x 78.9, y 2.2, w 1, h 1.7 [#2B2F33]: Search magnifier icon (Solid black magnifying glass icon to the left of the word Search.)
- body at x 80, y 2.2, w 3, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Search
- body at x 86.9, y 2.2, w 3.9, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: English (Language selector with a down chevron.)
- shape at x 91.7, y 1.2, w 5.8, h 4 [#2FB0C6]: Try Falco button (Rounded rectangle, corner radius about 6 px, no shadow; label 'Try Falco' in white regular sans-serif about 1.7 percent, centred.)
- body at x 92.6, y 2.2, w 4, h 1.7 [Open Sans, regular sans-serif; font size 1.7% of slide height; #FFFFFF; center aligned]: Try Falco
- shape at x 0, y 6.5, w 99.2, h 9.5 [#F7F8F9]: Announcement band background (Very light grey band below the navigation bar, separated by a faint shadow edge.)
- logo at x 37.4, y 9.5, w 2.2, h 3.7 [#1F6FD1]: CNCF logo: blue square with white diagonal-hatched inner pattern (Left of the announcement text.)
- logo at x 39.9, y 9.5, w 1.8, h 3.7 [#2FA7C0]: Falco mark: teal X icon (Right of the CNCF logo.)
- body at x 42.3, y 9.2, w 17.9, h 1.9 [Open Sans, semibold sans-serif; font size 1.7% of slide height; #2FA7C0; left aligned]: Falco is now a CNCF Graduated Project!
- body at x 42.3, y 11.6, w 19.6, h 1.9 [Open Sans, regular sans-serif; font size 1.7% of slide height; #3A3F44; left aligned]: Thank you everyone for helping Falco soar! ❤️ (Second line of the announcement; red heart emoji at the end.)
- body at x 1.9, y 24.9, w 7.7, h 1.6 [Open Sans, semibold sans-serif; font size 1.6% of slide height; #2FA7C0; left aligned]: The Falco Project (Sidebar section heading with a 1 px teal underline spanning x 1.9 to 15.0 percent at y 27.0 percent.)
- body at x 3.2, y 29.1, w 6.5, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Getting Started (Sidebar item with a right-pointing chevron at x 2.2 percent.)
- body at x 3.2, y 33.2, w 8.2, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Install and Operate (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 37.2, w 4.7, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Falco Rules (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 41.3, w 6, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Falco Outputs (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 45.3, w 5.5, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Falco Plugins (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 49.4, w 6, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Event Sources (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 53.5, w 3.1, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Metrics (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 57.6, w 3.9, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: gRPC API (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 61.7, w 3.8, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Tutorials (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 65.8, w 4.4, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Reference (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 69.8, w 7, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Troubleshooting (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 73.9, w 4.6, h 1.6 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Contribute (Sidebar item with a right-pointing chevron.)
- body at x 3.2, y 78, w 4.3, h 1.6 [Open Sans, semibold sans-serif; font size 1.6% of slide height; #2FA7C0; left aligned]: Roadmap (Current page, teal, indented without chevron.)
- body at x 3.2, y 82, w 10.7, h 4.1 [Open Sans, regular sans-serif; font size 1.6% of slide height; #2B2F33; left aligned]: Available Documentation / Versions (Two-line sidebar item, line spacing about 2.3 percent.)
- title at x 19.3, y 25.5, w 17.7, h 3.7 [Open Sans, bold sans-serif; font size 4% of slide height; #1A1A1A; left aligned]: The Falco Roadmap
- subtitle at x 19.3, y 31.2, w 10.6, h 2.3 [Open Sans, light sans-serif; font size 2.2% of slide height; #6B7280; left aligned]: The Project direction
- body at x 19.3, y 36.5, w 58.5, h 2 [Open Sans, regular sans-serif; font size 1.6% of slide height; #3A3F44; left aligned]: The Falco maintainers team works daily to provide more features, robust security and stability and better user experience to all adopters.
- body at x 19.3, y 40.6, w 60, h 4.5 [Open Sans, regular sans-serif; font size 1.6% of slide height; #3A3F44; left aligned]: The maintainer team frequently communicates and meets to decide the next important areas for the project. This page is updated to list the / efforts that are currently ongoing. (Two lines, line spacing about 2.2 percent.)
- title at x 19.3, y 50.3, w 14.8, h 3 [Open Sans, bold sans-serif; font size 3% of slide height; #1A1A1A; left aligned]: Road to Falco 1.0.0
- body at x 19.3, y 55.4, w 62.1, h 6.8 [Open Sans, regular sans-serif; font size 1.6% of slide height; #3A3F44; left aligned]: Falco is on track to release its 1.0.0 version. While "one point oh" is just a number, it is a signal from the community that the project has reached a / certain degree of stability and maturity. Following the graduation within the CNCF, this is the next logical step. Below we are listing the main / topics we wish to address for this milestone. (Three lines; the word 'graduation' is a teal hyperlink #2FA7C0 with no underline shown.)
- body at x 19.3, y 65.9, w 5.7, h 2 [Open Sans, bold sans-serif; font size 1.8% of slide height; #1A1A1A; left aligned]: Falco Engine
- body at x 20.8, y 70, w 59.7, h 15.9 [Open Sans, regular sans-serif; font size 1.6% of slide height; #3A3F44; left aligned]: • Provide standardized features adoption and depreciation policies, to make sure users understand when features can be considered stable and when they are being removed / • Make flagship features even more robust / • Streamlining falco.yaml structure / • CLI args consolidation and standardization / • Advanced metrics support (Bulleted list with small round charcoal bullet dots; the first item wraps to two lines; line spacing about 2.2 percent.)
- body at x 19.3, y 89.6, w 5.8, h 2 [Open Sans, bold sans-serif; font size 1.8% of slide height; #1A1A1A; left aligned]: Rules Syntax
- body at x 20.8, y 93.8, w 47.5, h 4.9 [Open Sans, regular sans-serif; font size 1.6% of slide height; #3A3F44; left aligned]: • Address current language inconsistencies arising from our commitment to backward compatibility / • Introduce new constructs to address the most common user requests (Bulleted list with round charcoal bullet dots, continues below the visible area.)
- body at x 27.3, y 78.4, w 5.2, h 1.8 [monospace, regular; font size 1.5% of slide height; #3A3F44; left aligned]: falco.yaml (Inline code chip with light grey #EEF0F2 fill and about 3 px corner radius.)
- icon at x 83.6, y 18.8, w 1, h 1.8 [#2FA7C0]: Pencil-square icon (Line icon left of Edit this page.)
- body at x 84.9, y 18.7, w 7.1, h 2 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2FA7C0; left aligned]: Edit this page
- icon at x 83.6, y 21.1, w 1, h 1.8 [#2FA7C0]: Pencil-square icon (Line icon left of Create child page.)
- body at x 84.9, y 21.1, w 9.4, h 2 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2FA7C0; left aligned]: Create child page
- icon at x 83.6, y 23.6, w 1, h 1.8 [#2FA7C0]: GitHub mark icon (Circular line icon left of Create documentation issue.)
- body at x 85, y 23.6, w 13.3, h 2 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2FA7C0; left aligned]: Create documentation issue
- icon at x 83.6, y 26, w 1, h 1.8 [#2FA7C0]: Checklist icon (Line icon with bullet lines left of Create project issue.)
- body at x 85, y 26, w 9.8, h 2 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2FA7C0; left aligned]: Create project issue
- body at x 83.6, y 31.1, w 5.7, h 1.8 [Open Sans, bold sans-serif; font size 1.7% of slide height; #1A1A1A; left aligned]: On this page
- body at x 83.6, y 34.8, w 8.1, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Road to Falco 1.0.0
- shape at x 84.1, y 37.8, w 0.1, h 21.1 [#D9DDE1]: Vertical grey rule for the sub-item list (1 px line, full height of the sub-item list.)
- body at x 84.9, y 38.9, w 5.4, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Falco Engine
- body at x 84.9, y 42.2, w 5.4, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Rules Syntax
- body at x 84.9, y 45.4, w 3, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Drivers
- body at x 84.9, y 48.7, w 5.1, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Distribution
- body at x 84.9, y 52, w 6.6, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Documentation
- body at x 84.9, y 55.2, w 5.1, h 1.8 [Open Sans, regular sans-serif; font size 1.7% of slide height; #2B2F33; left aligned]: Integrations
- shape at x 99.2, y 0, w 0.8, h 100 [#E5E7EB]: Browser scrollbar track and thumb (Thin grey track with a darker grey thumb from y 0 to 47.6 percent.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 2048 by 1152 pixels (covers the slide)
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels

### Slide 38

**Review notes**

- Review: Many content slides are dense with tiny code or field lists (slides 28, 38, 39), and this is only workable for a live technical audience who already know Falco.
- What would change the score: I would cut the near-empty filler slides (5, 8, 41's weak layout), add one takeaway per technical slide, and trim the long field lists and roadmap bullets on slides 28, 38 and 39 to the few items the speakers will actually say.

**Text**

Towards Falco 1.0
Core Enhancements
➢
High-Level enanchements
○
Standardizing feature adoption and deprecation policies
○
Streamlined conﬁguration and CLI standardization
○
Addressing legacy language inconsistencies and introducing new constructs
○
Introducing advanced metrics
○
Making the modern eBPF the default driver
➢
Distribution
○
Streamlined DEB/RPM packages, following Linux distro best practices
○
Switching to a distroless container image by default
○
Complete supply chain security initiative (ie. ensuring signatures for all artifacts and
SBOM)
Discover more 👉 falco.org
Falco

**Layout**

Single-column left-aligned layout on a full-bleed teal field. The title block sits top-left at about 3.4% from the left and 3.5% from the top, with the subtitle directly beneath it. A bulleted list occupies the middle band from about 30% to 74% of the height, starting at about 4.9% from the left. The footer line 'Discover more 👉 falco.org' sits bottom-left at about 91% of the height, and the Falco logo sits bottom-right. There is no slide number and no visible date.

**Visuals**

No charts, tables or photographs. Two non-text elements are present. (1) A small Falco logo at bottom right, x 87.1%, y 89.6%, w 8.7%, h 5.9%, drawn in near-black #1A1A1A: a stylised double-slash mark followed by the lowercase wordmark 'Falco'. The file measurement for this image is 4 by 2 pixels, so the logo is rendered as a tiny raster placed over the box. (2) A small raster image at x 23.6%, y 90.6%, w 3.1%, h 5.2%, 136 by 128 pixels, sitting under the pointing-hand emoji in the footer line; it is a small pictogram in the pointing-hand style, with no other content. The arrow bullets (➢) and circle bullets (○) are glyphs, not images.

**Design**

Background: Solid teal #04748C filling the whole slide. Flat solid teal background #04748C with no gradient, texture or shadow. All text is white #FFFFFF. Title 'Towards Falco 1.0' is Ubuntu Bold, about 5.9% of slide height, in white. Subtitle 'Core Enhancements' is Ubuntu Bold, about 4.9% of slide height, in white. Body text is Montserrat Regular, about 3.5% of slide height, with bold runs in Montserrat Bold for key phrases. Footer 'Discover more' and 'falco.org' are Montserrat SemiBold and Bold at about 4.4%. Bullet markers are white: ➢ in MS PGothic for level one and ○ in Arial for level two. Line spacing is tight, about 4.1% of slide height between bullet rows. Level-one items are bold, with no separators, rules or boxes.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill (Solid rectangle covering the entire slide, no border, no shadow.)
- title at x 3.4, y 3.5, w 27.8, h 5.9 [Ubuntu Bold; font size 5.93% of slide height; #FFFFFF; left aligned]: Towards Falco 1.0
- subtitle at x 3.4, y 10.4, w 26.2, h 4.9 [Ubuntu Bold; font size 4.94% of slide height; #FFFFFF; left aligned]: Core Enhancements
- bullet list at x 4.9, y 29.7, w 86.8, h 44.2 [Montserrat Regular with Montserrat Bold runs; font size 3.46% of slide height; #FFFFFF; left aligned]: ➢ High-Level enanchements / ○ Standardizing feature adoption and deprecation policies / ○ Streamlined conﬁguration and CLI standardization / ○ Addressing legacy language inconsistencies and introducing new constructs / ○ Introducing advanced metrics / ○ Making the modern eBPF the default driver / (blank line) / ➢ Distribution / ○ Streamlined DEB/RPM packages, following Linux distro best practices / ○ Switching to a distroless container image by default / ○ Complete supply chain security initiative (ie. ensuring signatures for all artifacts and SBOM) (Two levels. Level one uses a white arrow glyph ➢ (MS PGothic) at x 4.9%, with bold text starting at x 9.3%. Level two uses a white hollow circle ○ (Arial) at x 10.7%, with text starting at x 14.3%. Bold runs: 'High-Level enanchements' and 'Distribution' (level one, bold); 'feature adoption and deprecation policies', 'advanced metrics', 'modern eBPF the default' (bold inside level-two items). Line pitch about 4.1% of slide height. Wrapped line 'SBOM)' returns to x 14.3%. Text is set as typed, including the spelling 'enanchements' and 'conﬁguration' with its ligature.)
- text at x 4.3, y 91.2, w 30.6, h 4.4 [Montserrat SemiBold and Bold; font size 4.44% of slide height; #FFFFFF; left aligned]: Discover more 👉 falco.org ('Discover more' in Montserrat SemiBold at x 4.3%, w 19.3%; pointing-hand emoji 👉 at x 23.6%, w 3.1%; 'falco.org' in Montserrat Bold at x 27.5%, w 11.4%. All on one baseline.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: double-slash mark with the lowercase wordmark 'Falco' (Dark near-black mark on the teal background, bottom right. Measured as a 4 by 2 pixel raster image.)
- illustration at x 23.6, y 90.6, w 3.1, h 5.2: Small pictogram of a pointing hand (emoji) placed over the footer text line (Raster image 136 by 128 pixels. Sits in the footer line between 'Discover more' and 'falco.org' and overlaps the emoji glyph position.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 23.6, y 90.6, w 3.1, h 5.2: 136 by 128 pixels
- text at x 3.4, y 3.5, w 27.8, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Towards Falco 1.0
- text at x 3.4, y 10.4, w 26.2, h 4.9 [Ubuntu-Bold; font size 4.94; #FFFFFF]: Core Enhancements
- text at x 4.9, y 29.7, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 4.9, y 29.7, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 9.3, y 29.7, w 26.8, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: High-Level enanchements
- text at x 10.7, y 33.8, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 33.8, w 14.2, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Standardizing
- text at x 28.5, y 33.8, w 42.8, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: feature adoption and deprecation policies
- text at x 10.7, y 37.8, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 37.8, w 49.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Streamlined conﬁguration and CLI standardization
- text at x 10.7, y 41.9, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 41.9, w 74.7, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Addressing legacy language inconsistencies and introducing new constructs
- text at x 10.7, y 46.0, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 46.0, w 12.0, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Introducing
- text at x 26.4, y 46.0, w 18.2, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: advanced metrics
- text at x 10.7, y 50.1, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 50.1, w 11.6, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Making the
- text at x 26.0, y 50.1, w 25.9, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: modern eBPF the default
- text at x 51.8, y 50.1, w 6.1, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: driver
- text at x 4.9, y 58.2, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 4.9, y 58.2, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 9.3, y 58.2, w 12.2, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: Distribution
- text at x 10.7, y 62.3, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 62.3, w 67.8, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Streamlined DEB/RPM packages, following Linux distro best practices
- text at x 10.7, y 66.4, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 66.4, w 50.4, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Switching to a distroless container image by default
- text at x 4.3, y 91.2, w 19.3, h 4.4 [Montserrat-SemiBold; font size 4.44; #FFFFFF]: Discover more
- text at x 10.7, y 70.4, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 70.4, w 77.4, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Complete supply chain security initiative (ie. ensuring signatures for all artifacts
- text at x 23.6, y 91.2, w 3.1, h 4.4 [NotoColorEmoji; font size 4.44; #FFFFFF]: 👉
- text at x 27.5, y 91.2, w 11.4, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: falco.org
- text at x 91.7, y 70.4, w 4.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: and
- text at x 14.3, y 74.5, w 6.8, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: SBOM)

### Slide 39

**Review notes**

- Review: Many content slides are dense with tiny code or field lists (slides 28, 38, 39), and this is only workable for a live technical audience who already know Falco.
- What would change the score: I would cut the near-empty filler slides (5, 8, 41's weak layout), add one takeaway per technical slide, and trim the long field lists and roadmap bullets on slides 28, 38 and 39 to the few items the speakers will actually say.

**Text**

Falco 1.x and Beyond
Future Directions
➢
Falco in 3rd-party distributions
○
artifacthub.io integration
○
Curated presence in cloud marketplaces (ie. Azure, AWS, GCP, …)
○
Linux distros inclusion
➢
Advanced Integrations
○
Event enrichment with cloud provider metadata
○
Comprehensive K8s AuditLog support across cloud providers
○
More K8s enhancements
➢
Innovations
○
On-host anomaly detection
○
Plugin framework expansion with extended API access
○
Plugins SDK for Rust!
Discover more 👉 falco.org

**Layout**

Single left-aligned column on a full-bleed teal field. The title block sits top-left at about 3.4% from the left and 3.5% from the top, with a two-line title (main title above subtitle). Three bulleted sections stack vertically from about 25.6% to 91% of the slide height, each a bold arrowhead heading followed by indented circle sub-bullets, with the arrow markers at about 4.9% and the headings at about 9.3% from the left. A call-to-action line 'Discover more 👉 falco.org' sits bottom-left at about 4.3% from the left and 91% from the top, and the Falco logo sits bottom-right at about 87% from the left. There is no footer text, no slide number, and no visible date.

**Visuals**

Falco logo at bottom right: a stylised icon of crossed diagonal strokes with the wordmark 'Falco' in dark charcoal, about #1A1A1A, on the teal background. A small pointing-hand emoji 👉 (about 34 by 32 pixels raster) sits between 'Discover more' and 'falco.org', rendered in full colour (yellow hand). A 4 by 2 pixel image sits at the logo's position and is effectively invisible. No charts, photographs or diagrams.

**Design**

Background: Solid teal #04748C filling the entire slide. Flat single-colour teal background #04748C with no gradient, texture or shadow. All text is white #FFFFFF. Title 'Falco 1.x and Beyond' is Ubuntu Bold, about 5.9% of slide height. Subtitle 'Future Directions' is Ubuntu Bold, about 4.9%. Section headings are Montserrat Bold at about 3.5%. Sub-bullets are Montserrat Regular at about 3.5% with generous line spacing (about 4.1% between lines). Call-to-action 'Discover more' is Montserrat SemiBold and 'falco.org' is Montserrat Bold, both about 4.4%. Arrowhead markers are white ➢ glyphs in an MS PGothic style and sub-bullets are white hollow circles ○ in Arial. No lines, boxes or corner radii.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill, solid teal (Covers the whole slide, no border, no shadow, back-most layer.)
- title at x 3.4, y 3.5, w 33.1, h 5.9 [Ubuntu Bold, regular case, no letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Falco 1.x and Beyond
- subtitle at x 3.4, y 10.4, w 23.2, h 4.9 [Ubuntu Bold, regular case; font size 4.94% of slide height; #FFFFFF; left aligned]: Future Directions
- bullet list at x 4.9, y 25.6, w 1.9, h 3.5 [MS PGothic, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ➢ (Arrowhead bullet marker for section 1.)
- body at x 9.3, y 25.6, w 31.4, h 3.5 [Montserrat Bold; font size 3.46% of slide height; #FFFFFF; left aligned]: Falco in 3rd-party distributions
- bullet list at x 10.7, y 29.7, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 29.7, w 24.3, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: artifacthub.io integration
- bullet list at x 10.7, y 33.8, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 33.8, w 62.3, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: Curated presence in cloud marketplaces (ie. Azure, AWS, GCP, …)
- bullet list at x 10.7, y 37.8, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 37.8, w 21.6, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: Linux distros inclusion
- bullet list at x 4.9, y 46, w 1.9, h 3.5 [MS PGothic, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ➢ (Arrowhead bullet marker for section 2.)
- body at x 9.3, y 46, w 23.2, h 3.5 [Montserrat Bold; font size 3.46% of slide height; #FFFFFF; left aligned]: Advanced Integrations
- bullet list at x 10.7, y 50.1, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 50.1, w 47.1, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: Event enrichment with cloud provider metadata
- bullet list at x 10.7, y 54.1, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 54.1, w 59.3, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: Comprehensive K8s AuditLog support across cloud providers
- bullet list at x 10.7, y 58.2, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 58.2, w 24.4, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: More K8s enhancements
- bullet list at x 4.9, y 66.4, w 1.9, h 3.5 [MS PGothic, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ➢ (Arrowhead bullet marker for section 3.)
- body at x 9.3, y 66.4, w 12, h 3.5 [Montserrat Bold; font size 3.46% of slide height; #FFFFFF; left aligned]: Innovations
- bullet list at x 10.7, y 70.4, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 70.4, w 26.8, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: On-host anomaly detection
- bullet list at x 10.7, y 74.5, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 74.5, w 53.3, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: Plugin framework expansion with extended API access
- bullet list at x 10.7, y 78.6, w 1.2, h 3.5 [Arial, regular; font size 3.46% of slide height; #FFFFFF; left aligned]: ○ (Hollow circle sub-bullet.)
- body at x 14.3, y 78.6, w 20.7, h 3.5 [Montserrat Regular; font size 3.46% of slide height; #FFFFFF; left aligned]: Plugins SDK for Rust!
- caption at x 4.3, y 91.2, w 19.3, h 4.4 [Montserrat SemiBold; font size 4.44% of slide height; #FFFFFF; left aligned]: Discover more (Call-to-action text, first part.)
- icon at x 23.6, y 91.2, w 3.1, h 4.4 [Noto Color Emoji; font size 4.44% of slide height; #FFFFFF; left aligned]: 👉 pointing-hand emoji, full colour (Overlaps a 34 by 32 pixel raster image at x 23.6, y 90.6, w 3.1, h 5.2.)
- image at x 23.6, y 90.6, w 3.1, h 5.2: Small raster image, 34 by 32 pixels, pointing-hand graphic (Sits behind or over the emoji glyph; the emoji is shown in full colour.)
- caption at x 27.5, y 91.2, w 11.4, h 4.4 [Montserrat Bold; font size 4.44% of slide height; #FFFFFF; left aligned]: falco.org (Call-to-action URL.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1A1A1A]: Falco logo: crossed diagonal strokes icon with 'Falco' wordmark (Dark charcoal mark on teal, bottom-right corner. Contains a 4 by 2 pixel image at the same position.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 23.6, y 90.6, w 3.1, h 5.2: 34 by 32 pixels
- text at x 3.4, y 3.5, w 33.1, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Falco 1.x and Beyond
- text at x 3.4, y 10.4, w 23.2, h 4.9 [Ubuntu-Bold; font size 4.94; #FFFFFF]: Future Directions
- text at x 4.9, y 25.6, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 4.9, y 25.6, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 9.3, y 25.6, w 31.4, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: Falco in 3rd-party distributions
- text at x 10.7, y 29.7, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 29.7, w 24.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: artifacthub.io integration
- text at x 10.7, y 33.8, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 33.8, w 62.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Curated presence in cloud marketplaces (ie. Azure, AWS, GCP, …)
- text at x 10.7, y 37.8, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 37.8, w 21.6, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Linux distros inclusion
- text at x 4.9, y 46.0, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 4.9, y 46.0, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 9.3, y 46.0, w 23.2, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: Advanced Integrations
- text at x 10.7, y 50.1, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 50.1, w 47.1, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Event enrichment with cloud provider metadata
- text at x 10.7, y 54.1, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 54.1, w 59.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Comprehensive K8s AuditLog support across cloud providers
- text at x 10.7, y 58.2, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 58.2, w 24.4, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: More K8s enhancements
- text at x 4.9, y 66.4, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 4.9, y 66.4, w 1.9, h 3.5 [MS-PGothic; font size 3.46; #FFFFFF]: ➢
- text at x 9.3, y 66.4, w 12.0, h 3.5 [Montserrat-Bold; font size 3.46; #FFFFFF]: Innovations
- text at x 4.3, y 91.2, w 19.3, h 4.4 [Montserrat-SemiBold; font size 4.44; #FFFFFF]: Discover more
- text at x 10.7, y 70.4, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 70.4, w 26.8, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: On-host anomaly detection
- text at x 23.6, y 91.2, w 3.1, h 4.4 [NotoColorEmoji; font size 4.44; #FFFFFF]: 👉
- text at x 27.5, y 91.2, w 11.4, h 4.4 [Montserrat-Bold; font size 4.44; #FFFFFF]: falco.org
- text at x 10.7, y 74.5, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 74.5, w 53.3, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Plugin framework expansion with extended API access
- text at x 10.7, y 78.6, w 1.2, h 3.5 [ArialMT; font size 3.46; #FFFFFF]: ○
- text at x 14.3, y 78.6, w 20.7, h 3.5 [Montserrat-Regular; font size 3.46; #FFFFFF]: Plugins SDK for Rust!

### Slide 40

**Text**

Join the our community / #falco channel on the / Kubernetes Slack / Falco community call / every Wednesday / Mailing list / cncf-falco-dev@lists.cncf.io / 👉 falco.org 👈

**Layout**

Single teal field with a title block at top left (x 3.4%, y 3.7%) and a centred three-tier arrangement below: two centred text blocks side by side (left block x 8 to 41%, right block x 55 to 92%) at y 30 to 44%, a centred 'Mailing list' line with the email address beneath it at y 53 to 67%, and a centred 'falco.org' line at y 82 to 89%. The Falco logo sits bottom right at about x 87 to 96%, y 90 to 96%. No slide number or footer text.

**Visuals**

Small colour emoji and icon images only, no chart or photograph. (1) Colourful smiling mascot app icon, 88 by 88 px, at x 6.3%, y 35.7%, rounded-square, beside the words 'Kubernetes Slack'; quadrants green, blue, yellow and red with dark eyes and a dark smile. A 68 by 64 px raster copy of the same mascot sits inside its area at x 7.4%, y 37.5%. (2) Technologist emoji (person at a laptop, yellow skin, teal shirt, dark hair) 34 by 32 px at x 42.8%, y 37.5%, after 'Kubernetes Slack'. (3) Handshake emoji (yellow hands) 68 by 64 px at x 84.6%, y 38.1%, after 'every Wednesday'. (4) Incoming-envelope emoji (light blue envelope with motion lines) 68 by 64 px at x 35.8%, y 52.4%, before 'Mailing list'. (5) Same envelope emoji 34 by 32 px at x 60.1%, y 52.4%, after 'Mailing list'. (6) Pointing-right emoji (yellow hand) 17 by 16 px at x 36.5%, y 81.5%, before 'falco.org'. (7) Pointing-left emoji (yellow hand) 136 by 128 px at x 59.0%, y 81.5%, after 'falco.org'. (8) Falco logo bottom right, dark charcoal #1B1B1B: a stylised pair of slanted strokes forming a crossed mark, followed by the lowercase wordmark 'Falco'; at x 87.1%, y 89.6%, w 8.7%, h 5.9%. Nothing is cropped, overlaid or tinted.

**Design**

Background: Solid flat teal #04748C filling the whole slide. Flat teal background #04748C with no gradient, texture or border. Title in white #FFFFFF Ubuntu Bold, sentence case, about 5.9% of slide height (cap height about 4.2%). Body text in white #FFFFFF and off-white #FAFAFA Montserrat Medium, about 5.9% of slide height, with Montserrat Bold for emphasis ('#falco', 'community call', the email address) and Montserrat Medium Italic for 'every Wednesday' at about 4.9%. 'falco.org' in Montserrat SemiBold #FAFAFA at about 6.4%. Emoji in Noto Color Emoji. Accent colour is the multicolour emoji and the mascot icon; the logo is dark charcoal #1B1B1B. No shapes, lines, shadows or corner radii apart from the rounded mascot icon.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-bleed background rectangle (Covers the slide; no border, no shadow, no gradient.)
- image at x 6.3, y 35.7, w 5.8, h 10.4: Colourful smiling mascot app icon (Kubernetes Slack channel icon) (Source 88 by 88 px; rounded-square crop; no border; sits left of 'Kubernetes Slack'.)
- image at x 7.4, y 37.5, w 4.2, h 6.9: Raster copy of the mascot icon, 68 by 64 px (Overlaps the 88 px mascot icon.)
- text at x 8.1, y 30.1, w 10.9, h 5.9 [Montserrat Bold, upright, no letter-spacing; font size 5.93% of slide height; #FAFAFA; center aligned]: #falco
- text at x 18.9, y 30.1, w 26.4, h 5.9 [Montserrat Medium, upright, no letter-spacing; font size 5.93% of slide height; #FAFAFA; center aligned]: channel on the
- text at x 12.4, y 38.3, w 29.4, h 5.9 [Montserrat Medium, upright, no letter-spacing; font size 5.93% of slide height; #FAFAFA; center aligned]: Kubernetes Slack
- image at x 42.8, y 37.5, w 4.2, h 6.9: Technologist emoji (person at laptop), 34 by 32 px (Colour emoji, no border.)
- text at x 3.4, y 3.7, w 37.5, h 5.9 [Ubuntu Bold, upright, no letter-spacing; font size 5.93% of slide height; #FFFFFF; left aligned]: Join the our community
- text at x 54.8, y 30.7, w 9, h 5.9 [Montserrat Medium, upright, no letter-spacing; font size 5.93% of slide height; #FFFFFF; center aligned]: Falco
- text at x 64.7, y 30.7, w 27.1, h 5.9 [Montserrat Bold, upright, no letter-spacing; font size 5.93% of slide height; #FFFFFF; center aligned]: community call
- text at x 58.6, y 38.7, w 26, h 4.9 [Montserrat Medium Italic, no letter-spacing; font size 4.94% of slide height; #FFFFFF; center aligned]: every Wednesday
- image at x 84.6, y 38.1, w 3.5, h 5.8: Handshake emoji (yellow hands), 68 by 64 px (Colour emoji, no border.)
- image at x 35.8, y 52.4, w 4.2, h 6.9: Incoming-envelope emoji, 68 by 64 px (Colour emoji, light blue envelope with motion lines.)
- text at x 40.8, y 53.1, w 19.2, h 5.9 [Montserrat Medium, upright, no letter-spacing; font size 5.93% of slide height; #FAFAFA; center aligned]: Mailing list
- image at x 60.1, y 52.4, w 4.2, h 6.9: Incoming-envelope emoji, 34 by 32 px (Colour emoji, light blue envelope with motion lines.)
- text at x 26.1, y 61.3, w 47.8, h 5.9 [Montserrat Bold, upright, no letter-spacing; font size 5.93% of slide height; #FFFFFF; center aligned]: cncf-falco-dev@lists.cncf.io
- image at x 36.5, y 81.5, w 4.5, h 7.5: Pointing-right emoji, 17 by 16 px (Colour emoji, yellow hand.)
- text at x 41, y 82.3, w 18.1, h 6.4 [Montserrat SemiBold, upright, no letter-spacing; font size 6.42% of slide height; #FAFAFA; center aligned]: falco.org
- image at x 59, y 81.5, w 4.5, h 7.5: Pointing-left emoji, 136 by 128 px (Colour emoji, yellow hand.)
- logo at x 87.1, y 89.6, w 8.7, h 5.9 [#1B1B1B]: Falco logo (crossed slanted strokes mark with 'Falco' wordmark) (Dark charcoal mark on the teal background, bottom right.)

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 6.3, y 35.7, w 5.8, h 10.4: 88 by 88 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 36.5, y 81.5, w 4.5, h 7.5: 17 by 16 pixels
- image at x 59.0, y 81.5, w 4.5, h 7.5: 136 by 128 pixels
- image at x 7.4, y 37.5, w 4.2, h 6.9: 68 by 64 pixels
- image at x 42.8, y 37.5, w 4.2, h 6.9: 34 by 32 pixels
- image at x 35.8, y 52.4, w 4.2, h 6.9: 68 by 64 pixels
- image at x 60.1, y 52.4, w 4.2, h 6.9: 34 by 32 pixels
- image at x 84.6, y 38.1, w 3.5, h 5.8: 68 by 64 pixels
- text at x 3.4, y 3.7, w 37.5, h 5.9 [Ubuntu-Bold; font size 5.93; #FFFFFF]: Join the our community
- text at x 8.1, y 30.1, w 10.9, h 5.9 [Montserrat-Bold; font size 5.93; #FAFAFA]: #falco
- text at x 18.9, y 30.1, w 26.4, h 5.9 [Montserrat-Medium; font size 5.93; #FAFAFA]: channel on the
- text at x 54.8, y 30.7, w 9.0, h 5.9 [Montserrat-Medium; font size 5.93; #FFFFFF]: Falco
- text at x 64.7, y 30.7, w 27.1, h 5.9 [Montserrat-Bold; font size 5.93; #FFFFFF]: community call
- text at x 12.4, y 38.3, w 29.4, h 5.9 [Montserrat-Medium; font size 5.93; #FAFAFA]: Kubernetes Slack
- text at x 58.6, y 38.7, w 26.0, h 4.9 [Montserrat-MediumItalic; font size 4.94; #FFFFFF]: every Wednesday
- text at x 84.6, y 38.7, w 3.5, h 4.9 [NotoColorEmoji; font size 4.94; #FFFFFF]: 🤝
- text at x 35.8, y 53.1, w 4.2, h 5.9 [NotoColorEmoji; font size 5.93; #53565A]: 📨
- text at x 40.8, y 53.1, w 19.2, h 5.9 [Montserrat-Medium; font size 5.93; #FAFAFA]: Mailing list
- text at x 60.1, y 53.1, w 4.2, h 5.9 [NotoColorEmoji; font size 5.93; #53565A]: 📨
- text at x 26.1, y 61.3, w 47.8, h 5.9 [Montserrat-Bold; font size 5.93; #FFFFFF]: cncf-falco-dev@lists.cncf.io
- text at x 36.5, y 82.3, w 4.5, h 6.4 [NotoColorEmoji; font size 6.42; #000000]: 👉
- text at x 41.0, y 82.3, w 18.1, h 6.4 [Montserrat-SemiBold; font size 6.42; #FAFAFA]: falco.org
- text at x 59.0, y 82.3, w 4.5, h 6.4 [NotoColorEmoji; font size 6.42; #000000]: 👈

### Slide 41

**Text**

Falco
Thank you!
We'd love to hear
your thoughts
👇
🔗 falco.org

**Layout**

Centred title sits in the upper third, with the Falco logo top-left at about 4% margin. A left column holds the italic prompt, pointing-hand emoji and QR code. The link line sits bottom-centre, slightly right of the left column, on an invisible grid. No footer or slide number.

**Visuals**

A QR code (black modules on white, square, about 490 by 490 px) in the lower-left column, with a quiet white border. A pale teal (#04748C tint, about 15% opacity) Falco chevron watermark fills the lower-right quadrant, bleeding off the right and bottom edges. A small Falco logo mark (4 by 2 px raster) sits top-left. A yellow pointing-hand emoji (👇) sits under the prompt, and a blue-grey link emoji (🔗) sits before the URL. A tiny unlabelled raster sits at the bottom right and is not visible.

**Design**

Background: #FFFFFF white, with a faint teal #04748C chevron watermark image covering the full slide. Plain white background with a faint teal watermark. Title and prompt text are near-black #171717. The URL is pure black #000000. The logo wordmark is dark teal #1B3A40. Accent teal #04748C appears only in the watermark. Title is Ubuntu Medium, sans-serif, about 12.8% of slide height. Prompt is Ubuntu Italic, sans-serif, about 4.4%. URL is Montserrat SemiBold, sans-serif, about 6.4%. No shapes, borders, shadows or gradients.

**Elements and positions** (back to front; x, y, width, height as % of the slide; type, colour and alignment in brackets)

- shape at x 0, y 0, w 100, h 100 [#04748C]: Full-slide background fill, teal #04748C, fully covered by the white image layer (Not visible; covered by the full-slide image.)
- illustration at x 0, y 0, w 100, h 100 [#D5ECF1]: Full-slide watermark image: pale teal Falco chevron strokes, bottom-right, bleeding off edges (1200 by 628 px raster, about 15% opacity over white; chevrons are rounded-cap diagonal strokes.)
- logo at x 4.2, y 6.3, w 8.7, h 5.9 [#1B3A40]: Falco logo: stylised double-chevron mark with the word Falco (Mark is two parallel diagonal strokes crossed by a chevron; wordmark in a humanist sans, dark teal.)
- title at x 30.8, y 19.9, w 36.6, h 12.8 [Ubuntu, Medium, sentence case; font size 12.84% of slide height; #171717; center aligned]: Thank you!
- body at x 3.9, y 42.9, w 19.6, h 4.4 [Ubuntu, Italic, sentence case; font size 4.44% of slide height; #171717; center aligned]: We'd love to hear
- body at x 5.7, y 48.3, w 15.4, h 4.4 [Ubuntu, Italic, sentence case; font size 4.44% of slide height; #171717; center aligned]: your thoughts
- icon at x 11.8, y 53.7, w 3.1, h 4.4 [Noto Color Emoji; font size 4.44% of slide height; #171717; center aligned]: Pointing hand emoji 👇, yellow (Sits centred under the prompt, pointing down toward the QR code.)
- illustration at x 0, y 54.1, w 26.9, h 45.9 [#000000]: QR code, black modules on white (Square 490 by 490 px raster; finder patterns at three corners; no overlay or crop.)
- icon at x 39.2, y 82.3, w 4.5, h 6.4 [Noto Color Emoji; font size 6.42% of slide height; #000000; left aligned]: Link emoji 🔗, blue-grey chain link
- body at x 43.7, y 82.3, w 17.1, h 6.4 [Montserrat, SemiBold, sentence case, lowercase; font size 6.42% of slide height; #000000; left aligned]: falco.org

**Measured from the file** (exact, read from the PDF rather than estimated; x, y, w, h as % of the slide; font size as % of the slide height)

- fill at x 0.0, y 0.0, w 100.0, h 100.0: #04748C (covers the slide)
- image at x 0.0, y 0.0, w 100.0, h 100.0: 1200 by 628 pixels (covers the slide)
- image at x 0.0, y 54.1, w 26.9, h 45.9: 490 by 490 pixels
- image at x 4.2, y 6.3, w 8.7, h 5.9: 4 by 2 pixels
- image at x 87.1, y 89.6, w 8.7, h 5.9: 4 by 2 pixels
- image at x 39.2, y 81.5, w 4.5, h 7.5: 68 by 64 pixels
- image at x 11.8, y 53.1, w 3.1, h 5.2: 136 by 128 pixels
- text at x 30.8, y 19.9, w 36.6, h 12.8 [Ubuntu-Medium; font size 12.84; #171717]: Thank you!
- text at x 3.9, y 42.9, w 19.6, h 4.4 [Ubuntu-Italic; font size 4.44; #171717]: We'd love to hear
- text at x 5.7, y 48.3, w 15.4, h 4.4 [Ubuntu-Italic; font size 4.44; #171717]: your thoughts
- text at x 11.8, y 53.7, w 3.1, h 4.4 [NotoColorEmoji; font size 4.44; #171717]: 👇
- text at x 39.2, y 82.3, w 4.5, h 6.4 [NotoColorEmoji; font size 6.42; #000000]: 🔗
- text at x 43.7, y 82.3, w 17.1, h 6.4 [Montserrat-SemiBold; font size 6.42; #000000]: falco.org
