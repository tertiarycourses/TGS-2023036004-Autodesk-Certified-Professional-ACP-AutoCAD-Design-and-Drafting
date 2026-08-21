# Lab 01 — Drawing Standards and Project Setup

**Mapping:** LO1 · K1 · A1

**Tools:** AutoCAD · UNITS · LAYER · PROPERTIES · Named UCS

**Outcome:** A standards-ready furniture plan with a completed drawing-standard record and verified setup evidence.

## Scenario and objective

Translate a design brief into a documented AutoCAD setup covering units, visual style, naming, layers and evidence standards.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Floor_Plan.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab01-<initials>.dwg`.

## Detailed procedure

1. Open the supplied Furniture_Floor_Plan.dwg and save a working copy named lab01-<initials>.dwg. **Command / tool:** `SAVEAS`
2. Read the project brief and record the intended discipline, audience, drawing purpose and required deliverables. **Command / tool:** `Lab brief`
3. Open Drawing Units; confirm the length type, precision, insertion scale and angle convention required by the brief. **Command / tool:** `UNITS`
4. Inspect extents and measure two known elements to confirm the drawing scale is credible before editing. **Command / tool:** `ZOOM Extents · DIST`
5. Create a named UCS for the principal drawing orientation and restore World UCS for comparison. **Command / tool:** `UCS · Named`
6. Define the layer naming, colour, linetype, lineweight and plot expectations in the standards record. **Command / tool:** `LAYER`
7. Check object properties for representative walls, fixtures and annotations; record any exceptions. **Command / tool:** `PROPERTIES`
8. Set a visual review style that makes lineweight and object hierarchy easy to inspect. **Command / tool:** `LWDISPLAY`
9. Purge only confirmed unused definitions, then audit the file and save a new revision. **Command / tool:** `PURGE · AUDIT`
10. Capture the Units, Layer Properties, UCS and measured-dimension evidence required by the checklist. **Command / tool:** `Evidence screenshots`

## Verification and acceptance

Units, scale, UCS, naming and layer rules are documented; the drawing opens without errors and passes the lab checklist.

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
- two to four screenshots named `lab01-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
