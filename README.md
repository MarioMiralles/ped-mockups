# PenisEnlargementDeath.com: three design concepts (#82)

Static mockups for Maria and Dr. Loria to choose from, built 2026-11-20 around Maria's final copy
(email of 2026-11-19/20). Same layout as the De La Noval and Casa Ocho concept galleries.

| Path | Concept |
| --- | --- |
| `index.html` | Gallery of the three concepts |
| `case-file/` | 1 · The Case File: investigative news report, Newsreader + IBM Plex, cream and deep red, docket card, petition timeline, full-width layout matching the header and footer: key-facts strip under the headline, then paired rows (intro + contents, video + topics, Dallas story + court card and timeline), two-column cases and questions, three-column risks |
| `patient-guide/` | 2 · Patient Safety Guide: deep teal/mint/amber, Plus Jakarta Sans + Source Serif 4, video beside the headline, case tabs, risk icon cards, tickable/printable question checklist |
| `three-cities/` | 3 · Three Cities: dark documentary style, Anton + Inter, map hero (Dallas, Paris, Bangkok), numbered chapters, letterbox video |
| `assets/Varkony-v-Moore-First-Amended-Petition.pdf` | The petition Maria attached (the "[LINK TO PETITION PDF]" in the copy) |
| `assets/shots/` | Gallery card screenshots (1440×900) |

## Notes
- Copy is Maria's, verbatim. Added only: section labels, court-filing details and the treatment dates
  (petition ¶¶ 67–71: records dated Jun 25, Jul 22, Aug 12 and Sep 3, 2025).
- The video section is shown as a marked placeholder; on the live site it stays hidden until the video exists.
- Dr. Loria's photo is a placeholder box. Pages carry `noindex`. Fonts load from Google Fonts; everything else is inline.
- Checked at 1440 and 390 wide with Playwright; no horizontal overflow on mobile.

## Viewing
Plain HTML, no build step. Open `index.html`, or `python3 -m http.server` from this folder.
