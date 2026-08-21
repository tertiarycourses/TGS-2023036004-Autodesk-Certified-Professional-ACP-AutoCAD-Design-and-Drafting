# Lab 07 — Layouts, Viewports and Page Setups

**Mapping:** LO3 · K3 · A1, A2, A3

**Tools:** AutoCAD · LAYOUT · PAGESETUP · MVIEW · VPORTS · SCALELISTEDIT

**Outcome:** A coordinated three-sheet sink drawing set that mirrors the original practical-assessment workflow.

## Scenario and objective

Build ISO A1, A2 and A3 layouts with correct page setups, title blocks, viewport views and locked scales.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Sink_Layouts.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ISO A1 title block.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ISO A2 title block.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ISO A3 title block.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab07-<initials>.dwg`.

## Detailed procedure

1. Open Sink_Layouts.dwg and save a working copy in the Lab 7 folder. **Command / tool:** `SAVEAS`
2. Inspect model-space extents, saved views and the current ISO A2 layout. **Command / tool:** `ZOOM Extents · VIEW`
3. Create a named page setup for each required ISO expanded sheet size and verify plot units and orientation. **Command / tool:** `PAGESETUP`
4. Copy the ISO A2 layout twice and rename the copies ISO A1 and ISO A3. **Command / tool:** `LAYOUT Copy · Rename`
5. Assign the correct page setup to ISO A1, ISO A2 and ISO A3. **Command / tool:** `PAGESETUP`
6. Insert each supplied title-block drawing at 0,0 on the Border layer in paper space. **Command / tool:** `-INSERT 0,0`
7. Create three equal viewports on ISO A2 and place them on the Viewports layer. **Command / tool:** `MVIEW`
8. Set Top, Front and Right views, apply 1:8 scale, Hidden visual style and lock the viewports. **Command / tool:** `VIEW · ZOOM 1/8xp · LOCK`
9. Create one SE Isometric viewport on ISO A3 at 1:5 using Shaded or Realistic style and lock it. **Command / tool:** `MVIEW · SE Isometric · 1/5xp`
10. Preview all sheets, verify title blocks and save the coordinated drawing set. **Command / tool:** `PLOT Preview · SAVE`

## Verification and acceptance

All three layouts use the correct sheet, border and viewport settings; scales and view locks match the brief.

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
- two to four screenshots named `lab07-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
