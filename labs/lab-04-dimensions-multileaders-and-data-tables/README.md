# Lab 04 — Dimensions, Multileaders and Data Tables

**Mapping:** LO3 · K3 · A3

**Tools:** AutoCAD · DIM · QDIM · MLEADER · TABLE · FIELD

**Outcome:** A review sheet with validated dimensions, labels and a structured furniture/component table.

## Scenario and objective

Build a coordinated detailing layer that combines efficient dimensions, callouts and a component schedule.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Floor_Plan.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab04-<initials>.dwg`.

## Detailed procedure

1. Create linear, aligned, angular and radial dimensions only where each type communicates the geometry correctly. **Command / tool:** `DIM`
2. Use Quick Dimension for a repeated chain, then inspect and correct crowded or ambiguous results. **Command / tool:** `QDIM`
3. Edit dimension text only when necessary and preserve the measured value through fields or associative dimensions. **Command / tool:** `DIMREASSOCIATE`
4. Add keynotes with multileaders and align them into a readable callout column. **Command / tool:** `MLEADERALIGN`
5. Create a table style with a clear title, header and data-row hierarchy. **Command / tool:** `TABLESTYLE`
6. Insert a component schedule with item, description, material, size and manufacturer columns. **Command / tool:** `TABLE`
7. Use a field for one drawing property and update it to prove the link is live. **Command / tool:** `FIELD · UPDATEFIELD`
8. Check spelling, unit consistency, overlaps and duplicated information. **Command / tool:** `SPELL · visual check`
9. Plot-preview the sheet at the intended scale and correct any annotation that becomes unreadable. **Command / tool:** `PLOT Preview`
10. Save the final sheet and complete the acceptance checklist. **Command / tool:** `SAVE`

## Verification and acceptance

Dimensions remain associative, leaders are aligned, the table is complete and the plotted sheet is readable.

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
- two to four screenshots named `lab04-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
