# Lab 12 — Annotation Styles, Scales and Schedules

**Mapping:** LO3 · Exam 2.1–2.3 · K3 · A3

**Tools:** AutoCAD · STYLE · DIMSTYLE · MLEADERSTYLE · TABLESTYLE · OBJECTSCALE · ANNORESET

**Outcome:** A dimensioned and annotated component sheet with named styles, scale-aware objects and a controlled schedule.

## Scenario and objective

Apply a complete annotation governance system to a technical component sheet and validate every representation in paper space.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `ex8.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ex8-drawing-sheet.pdf` — supplied AutoCAD working/source file or technical drawing reference.
- `title-block.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab12-<initials>.dwg`.

## Detailed procedure

1. Open ex8.dwg and compare its visible annotations with the dimensioned drawing sheet. **Command / tool:** `OPEN · visual audit`
2. Create named text, dimension, multileader and table styles using one coordinated paper-height policy. **Command / tool:** `STYLE · DIMSTYLE · MLEADERSTYLE · TABLESTYLE`
3. Apply linear, aligned, radial, diameter and angular dimensions to the governed geometry. **Command / tool:** `DIM`
4. Create concise multileader callouts and align their landings for a deliberate reading order. **Command / tool:** `MLEADER · MLEADERALIGN`
5. Assign required 1:20, 1:10 and 1:5 scales only to the annotative objects that need them. **Command / tool:** `OBJECTSCALE`
6. Adjust one scale-specific position to avoid a collision, then synchronize another using ANNORESET. **Command / tool:** `annotative grips · ANNORESET`
7. Create a schedule with title, header and data cell styles; populate it from controlled drawing values. **Command / tool:** `TABLE`
8. Insert the supplied title block and populate live properties with fields where appropriate. **Command / tool:** `INSERT · FIELD`
9. Review all target scales through locked paper-space viewports and disable diagnostic all-visible mode. **Command / tool:** `ANNOALLVISIBLE · viewport scales`
10. Plot-preview the final sheet and retain style, scale and schedule evidence. **Command / tool:** `PLOT Preview`

## Verification and acceptance

All annotation types are style-governed, scale positions are intentional and the plotted schedule and callouts remain readable.

Your submission is accepted when:

- the required DWG opens without an unrepaired error;
- the requested objects, styles, views or outputs match the brief;
- dimensions, scales, paths and page setups are explicitly verified;
- screenshots show both the relevant setting and its result;
- the evidence checklist is complete and filenames identify the learner.

## Troubleshooting

- Unexpected geometry: check the active UCS, object snap, polar tracking, dynamic input and current layer.
- Wrong plotted size: check drawing units, viewport scale, page setup and plot scale independently.
- Missing references: use relative paths, reload from the lab folder and package with eTransmit.
- Annotation not visible: check annotative scale, layer state, viewport override and object properties.

## Evidence to retain

- the final working DWG;
- two to four screenshots named `lab12-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
