# Lab 13 — Coordinate Geometry and Construction Objects

**Mapping:** LO1–LO2 · Exam 3.2, 3.4 · K1–K2 · A1–A2

**Tools:** AutoCAD · LINE · PLINE · ARC · XLINE · OSNAP · OTRACK · MEASUREGEOM

**Outcome:** A closed, dimensionally verified profile combining Cartesian and polar input with appropriate object types.

## Scenario and objective

Construct a mixed technical profile from exact coordinates, arcs, polylines and construction geometry, then validate its measurable relationships.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `ex1.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ex1-drawing-sheet.pdf` — supplied AutoCAD working/source file or technical drawing reference.
- `ex3.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ex3-drawing-sheet.pdf` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab13-<initials>.dwg`.

## Detailed procedure

1. Read the supplied drawing sheets and identify which values are absolute coordinates, offsets, distances and angles. **Command / tool:** `drawing interpretation`
2. Establish the start point in World UCS and create the first controlled segment with absolute input. **Command / tool:** `LINE · x,y`
3. Continue orthogonal features using relative Cartesian coordinates. **Command / tool:** `@dx,dy`
4. Create angled features using relative polar input and verify direction against the active UCS. **Command / tool:** `@distance<angle`
5. Use object-snap tracking and polar tracking to derive intersections without adding permanent geometry. **Command / tool:** `OTRACK · POLAR`
6. Create the curved features with the arc method that matches the supplied centre, chord or angle information. **Command / tool:** `ARC`
7. Join eligible segments into a polyline and verify open/closed state and linetype generation. **Command / tool:** `PEDIT · JOIN · PLINEGEN`
8. Use xlines or rays on a non-plotting construction layer to project aligned features. **Command / tool:** `XLINE · RAY`
9. Measure distance, angle, radius and area and compare against the drawing sheets. **Command / tool:** `MEASUREGEOM`
10. Save the completed profile and retain a discrepancy log for any corrected source interpretation. **Command / tool:** `SAVEAS`

## Verification and acceptance

Coordinate methods, arc construction and object types match the supplied information; the final profile closes and measures correctly.

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
- two to four screenshots named `lab13-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
