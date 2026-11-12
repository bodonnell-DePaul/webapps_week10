# Data at Global Scale: Performance, Migrations, Incidents & Recovery
## Week 10 Lecture for Web Development Graduate Students

A 180-minute lecture (76 slides) on running data across regions: where it lives and who may write it, how change propagates, how to keep queries fast, how to migrate without downtime, how to detect and run an incident, and how to fail over, rehydrate, and fail back to the primary.

---

## Lecture Slides

The same deck in three formats, all in [`slides/`](slides/). Every slide has speaker notes, and each content slide starts its notes with a time estimate such as `[~3 min]`.

- [PowerPoint](slides/Data-at-Global-Scale.pptx): editable text and diagrams.
- [HTML](slides/Data-at-Global-Scale.html): one self-contained file; open it in a browser, no server or internet connection needed.
- [Marp Markdown](slides/Data-at-Global-Scale.md): source for [Marp](https://marp.app/). Diagram slides use the SVGs in [`slides/assets/`](slides/assets/), so keep that folder next to the file.

To export the Markdown version to PDF with [Marp CLI](https://github.com/marp-team/marp-cli) (needs Node and a Chrome-based browser):

```bash
npx @marp-team/marp-cli --html --allow-local-files --pdf slides/Data-at-Global-Scale.md
```

## Agenda

| Minutes | Segment |
|---:|---|
| 5 | Framing and the running example, Atlas Market |
| 35 | Module 1: Data at global scale |
| 20 | Module 2: Query performance at scale |
| 10 | Break |
| 25 | Module 3: Migrations without downtime |
| 25 | Module 4: Incidents at scale |
| 10 | Break |
| 40 | Module 5: Recover and fail back (ends with a tabletop exercise) |
| 10 | Module 6: Learn: operational review |

## Notes

- Atlas Market is a fictional teaching example. The latency table, query plans, charts, and restore calculations use illustrative numbers, not measurements.
- Sources for the real incidents and systems discussed are cited on the slides and collected in the three reference slides at the end of the deck.
