# Lab 14 — Associative Arrays and Grip-Based Revision

**Mapping:** LO2 · Exam 3.2.e, 3.3 · K2 · A2

**Tools:** AutoCAD · ARRAYRECT · ARRAYPOLAR · ARRAYPATH · grips · dynamic input

**Outcome:** An associative pattern study and a revised technical component with documented grip decisions.

## Scenario and objective

Build repeatable rectangular, polar and path patterns and revise compound geometry with multiple and multifunctional grips.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `ex6.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ex6-drawing-sheet.pdf` — supplied AutoCAD working/source file or technical drawing reference.
- `ex7.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `sawblade.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab14-<initials>.dwg`.

## Detailed procedure

1. Open ex6.dwg and identify rectangular, radial and path-governed repetition in the design. **Command / tool:** `pattern analysis`
2. Create a rectangular associative array with controlled rows, columns and spacing. **Command / tool:** `ARRAYRECT`
3. Create a polar associative array and verify centre, item count, fill angle and rotation behaviour. **Command / tool:** `ARRAYPOLAR`
4. Create a path array and compare Divide and Measure distribution methods. **Command / tool:** `ARRAYPATH`
5. Change each array through its properties and confirm every instance updates as one governed set. **Command / tool:** `Properties · array grips`
6. Open sawblade.dwg and reverse-engineer its polar-array parameters from visible evidence. **Command / tool:** `Properties`
7. Open ex7.dwg and use one hot grip to cycle Stretch, Move, Rotate, Scale and Mirror modes. **Command / tool:** `grip modes`
8. Select multiple grips to revise a symmetric feature while preserving its centreline. **Command / tool:** `Shift-select grips`
9. Combine multifunctional grips with dynamic input to set exact lengths, angles or curve states. **Command / tool:** `dynamic input`
10. Verify geometry, retain associativity and explain why no array was exploded. **Command / tool:** `LIST · Properties`

## Verification and acceptance

All arrays remain associative with correct parameters; grip edits are exact and protected geometry remains unchanged.

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
- two to four screenshots named `lab14-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
