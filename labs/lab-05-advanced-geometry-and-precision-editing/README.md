# Lab 05 — Advanced Geometry and Precision Editing

**Mapping:** LO1–LO2 · K1, K2 · A1, A2

**Tools:** AutoCAD · PLINE · ARC · POLYGON · SPLINE · REGION · UCS · OSNAP

**Outcome:** A precise 2D component study plus an isometric view using fit-for-purpose object types.

## Scenario and objective

Author and revise technical geometry with polylines, arcs, polygons, splines, regions, construction geometry and precision tools.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Floor_Plan.dwg` — AutoCAD working/source file recovered from the original PP dataset.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab05-<initials>.dwg`.

## Detailed procedure

1. Set object snaps, polar tracking and dynamic input for the supplied geometry brief. **Command / tool:** `OSNAP · POLAR · DYNMODE`
2. Create a closed polyline outline with one straight and one arc segment; verify closure and area. **Command / tool:** `PLINE · LIST`
3. Create a polygon by centre/radius and another by edge; compare control and revision behaviour. **Command / tool:** `POLYGON`
4. Create a spline using fit points, then edit its control vertices to refine the silhouette. **Command / tool:** `SPLINE · SPLINEDIT`
5. Use xlines and rays as non-plotting construction references on a dedicated layer. **Command / tool:** `XLINE · RAY`
6. Convert the closed outlines into regions and demonstrate Union and Subtract on copies. **Command / tool:** `REGION · UNION · SUBTRACT`
7. Use grips, multifunctional grips, Move, Rotate, Offset, Mirror, Stretch, Trim and Extend on measured edits. **Command / tool:** `GRIPS · MODIFY tools`
8. Create a rectangular or polar associative array and edit its parameters after placement. **Command / tool:** `ARRAYRECT · ARRAYPOLAR`
9. Switch to isometric drafting, cycle isoplanes and add an isocircle for the component study. **Command / tool:** `ISODRAFT · F5 · ELLIPSE Isocircle`
10. Verify coordinates and dimensions, then save the finished component sheet. **Command / tool:** `ID · DIST · SAVE`

## Verification and acceptance

Objects use suitable types, edits remain accurate, construction geometry is separated and the isometric view is coherent.

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
- two to four screenshots named `lab05-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
