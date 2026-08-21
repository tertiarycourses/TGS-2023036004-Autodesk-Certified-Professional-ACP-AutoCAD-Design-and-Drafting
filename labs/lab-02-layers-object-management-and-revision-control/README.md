# Lab 02 — Layers, Object Management and Revision Control

**Mapping:** LO2 · K2 · A2

**Tools:** AutoCAD · Layer States · Layer Filters · QSELECT · SELECTSIMILAR · LAYMRG

**Outcome:** A revised furniture plan with reusable layer states, filters and a change log.

## Scenario and objective

Organise and revise a drawing using selection methods, layer filters, layer states, overrides and controlled cleanup.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Floor_Plan.dwg` — AutoCAD working/source file recovered from the original PP dataset.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab02-<initials>.dwg`.

## Detailed procedure

1. Open the Lab 2 source copy and create a new revision before making organisational changes. **Command / tool:** `SAVEAS`
2. Use Quick Select to find objects by layer, colour and object type; compare with Select Similar. **Command / tool:** `QSELECT · SELECTSIMILAR`
3. Create discipline-based property filters and a temporary group filter for the current revision task. **Command / tool:** `LAYER FILTER`
4. Save a Presentation layer state and a Coordination layer state with different visibility and plot settings. **Command / tool:** `LAYERSTATE`
5. Apply viewport-ready layer-property overrides to highlight the coordination scope without changing global properties. **Command / tool:** `Layer overrides`
6. Lock reference layers, freeze layers not needed for the task and explain the difference from turning a layer off. **Command / tool:** `LOCK · FREEZE · OFF`
7. Use Hide/Isolate for a short review, then end isolation and prove no objects remain accidentally hidden. **Command / tool:** `ISOLATEOBJECTS · UNISOLATEOBJECTS`
8. Merge only the two duplicate layers named in the brief and confirm the destination layer. **Command / tool:** `LAYMRG`
9. Record before/after layer counts and describe how the changes support team revision capability. **Command / tool:** `Layer Properties evidence`
10. Audit and save the final revision with the completed change log. **Command / tool:** `AUDIT · SAVE`

## Verification and acceptance

Required filters and states restore correctly; no object is lost; the merged layers and revision evidence match the brief.

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
- two to four screenshots named `lab02-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
