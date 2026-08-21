# Lab 10 — Integrated Sink Documentation Capstone

**Mapping:** LO1–LO5 · K1–K4 · A1–A5

**Tools:** AutoCAD · Complete professional workflow

**Outcome:** A standards-based sink drawing set with layouts, title blocks, viewports, component table, publish package and review evidence.

## Scenario and objective

Complete the recovered sink-layout dataset as a professional drawing package and lead a short stakeholder review.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Sink_Layouts.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `Furniture_Block_Attributes.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `ISO A1 title block.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `ISO A2 title block.dwg` — AutoCAD working/source file recovered from the original PP dataset.
- `ISO A3 title block.dwg` — AutoCAD working/source file recovered from the original PP dataset.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab10-<initials>.dwg`.

## Detailed procedure

1. Review the capstone brief and define the intended visual hierarchy, sheet standards and stakeholder questions. **Command / tool:** `Capstone brief`
2. Create ISO A1, A2 and A3 layouts with the correct page setups and title blocks at 0,0. **Command / tool:** `LAYOUT · PAGESETUP · INSERT`
3. Create and lock the required Top, Front, Right and SE Isometric viewports at the specified scales. **Command / tool:** `MVIEW · 1:8 · 1:5`
4. Apply the organisational layer and annotation standards developed in earlier labs. **Command / tool:** `Layer states · styles`
5. Create a component schedule listing visible sink components, dimensions, materials and manufacturer details. **Command / tool:** `TABLE · attributes/data extraction`
6. Use revision communication to identify one design decision that needs stakeholder confirmation. **Command / tool:** `REVCLOUD · MLEADER`
7. Run drawing-health, missing-reference, scale and plot-preview checks. **Command / tool:** `AUDIT · XREF · PLOT Preview`
8. Publish a multi-sheet PDF and create an eTransmit ZIP of the current package. **Command / tool:** `PUBLISH · ETRANSMIT`
9. Present the drawing story in three minutes: overview, decision-critical details and requested approval. **Command / tool:** `Stakeholder review`
10. Submit the DWG, published PDF, package inventory and completed evidence checklist. **Command / tool:** `Submission`

## Verification and acceptance

The drawing set meets the capstone acceptance criteria and the learner can justify each standard, technology and communication decision.

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
- two to four screenshots named `lab10-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
