# Lab 08 — Publish, Plot and eTransmit

**Mapping:** LO3–LO4 · K3, K4 · A3, A4

**Tools:** AutoCAD · PUBLISH · PLOT · ETRANSMIT · Page Setup Manager

**Outcome:** A published PDF sheet set and a verified eTransmit package with a transmittal report.

## Scenario and objective

Configure repeatable output and package the drawing set with all required dependencies.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Sink_Layouts.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `ISO A1 title block.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `ISO A2 title block.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `ISO A3 title block.dwg` — AutoCAD working/source file recovered from the original PP dataset.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab08-<initials>.dwg`.

## Detailed procedure

1. Open the completed layout drawing and run a dependency check before publishing. **Command / tool:** `XREF · FONTALT awareness`
2. Import or create the approved page setups and apply them consistently to the sheet set. **Command / tool:** `PAGESETUP Import`
3. Open Publish, order the sheets and remove any model-space sheet not required by the brief. **Command / tool:** `PUBLISH`
4. Set the PDF output options, plot stamp rule and layer-information requirement. **Command / tool:** `Publish Options`
5. Preview each sheet and correct clipping, lineweight, colour and scale defects before output. **Command / tool:** `Preview`
6. Publish the multi-sheet PDF and inspect every page at full size. **Command / tool:** `PUBLISH`
7. Open eTransmit and review all referenced files, fonts, plot styles and support paths. **Command / tool:** `ETRANSMIT`
8. Choose a package structure that keeps the drawing portable and records path handling. **Command / tool:** `Transmittal Setup`
9. Create the ZIP package and verify it contains the current DWG, title blocks and transmittal report. **Command / tool:** `Create Transmittal`
10. Record hashes/file sizes and save the final evidence checklist. **Command / tool:** `Finder / checksum evidence`

## Verification and acceptance

The PDF contains all required sheets and the eTransmit package opens as a complete, current drawing set.

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
- two to four screenshots named `lab08-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
