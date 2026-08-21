# Lab 06 — Blocks, Attributes and Data Extraction

**Mapping:** LO4 · K4 · A4

**Tools:** AutoCAD · BLOCK · WBLOCK · ATTDEF · EATTEDIT · DATAEXTRACTION

**Outcome:** A small furniture block library with attributes and an extracted component schedule.

## Scenario and objective

Develop reusable content that carries organisational data and supports consistent schedules.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Block_Attributes.dwg` — AutoCAD working/source file recovered from the original PP dataset.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab06-<initials>.dwg`.

## Detailed procedure

1. Open the source file and inventory the furniture objects that should become reusable definitions. **Command / tool:** `BEDIT / source review`
2. Choose logical base points and create named blocks using the project naming rule. **Command / tool:** `BLOCK`
3. Write one approved block to an external DWG for controlled reuse. **Command / tool:** `WBLOCK`
4. Define ITEM, DESCRIPTION, MATERIAL and MANUFACTURER attributes with suitable prompts and defaults. **Command / tool:** `ATTDEF`
5. Insert several block instances and enter distinct attribute values. **Command / tool:** `INSERT`
6. Edit one block definition and confirm all instances update without losing attribute values. **Command / tool:** `BEDIT · BSAVE`
7. Synchronise attribute definitions and repair any out-of-date instances. **Command / tool:** `ATTSYNC`
8. Extract block and attribute data into an AutoCAD table. **Command / tool:** `DATAEXTRACTION`
9. Group a temporary review set and explain why a group is not a reusable block definition. **Command / tool:** `GROUP`
10. Save the library, schedule and evidence of the data relationship. **Command / tool:** `SAVE`

## Verification and acceptance

Blocks reuse cleanly, attributes persist through edits and the extracted schedule matches the inserted instances.

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
- two to four screenshots named `lab06-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
