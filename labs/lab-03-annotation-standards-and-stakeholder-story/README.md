# Lab 03 — Annotation Standards and Stakeholder Story

**Mapping:** LO3 · K3 · A3

**Tools:** AutoCAD · STYLE · DIMSTYLE · MLEADERSTYLE · HATCH · REVCLOUD

**Outcome:** An annotated plan with text, dimensions, multileaders, hatches and revision communication governed by named styles.

## Scenario and objective

Create an annotation system that leads a stakeholder from overview to decision-critical detail.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Floor_Plan.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab03-<initials>.dwg`.

## Detailed procedure

1. Open the source drawing and identify the three messages the stakeholder must understand first. **Command / tool:** `Stakeholder brief`
2. Create or verify a text style with the required font, height rule and width factor. **Command / tool:** `STYLE`
3. Create a dimension style for the project units, precision, arrowheads, text placement and tolerances. **Command / tool:** `DIMSTYLE`
4. Create a multileader style with a consistent landing, arrowhead and content hierarchy. **Command / tool:** `MLEADERSTYLE`
5. Apply concise callouts that state the decision, not merely the object name. **Command / tool:** `MLEADER`
6. Use hatches with controlled scale and origin to distinguish material or scope without obscuring geometry. **Command / tool:** `HATCH · HATCHEDIT`
7. Add a revision cloud and delta note to make one documented change visible. **Command / tool:** `REVCLOUD`
8. Use a wipeout only where it improves readability and confirm frame/display settings do not hide required geometry. **Command / tool:** `WIPEOUT`
9. Run an annotation-scale review at two intended viewport scales. **Command / tool:** `CANNOSCALE`
10. Capture the styles, annotation hierarchy and stakeholder reading order in the evidence sheet. **Command / tool:** `Evidence screenshots`

## Verification and acceptance

Annotations are legible at the required scales, styles are reusable, and the drawing tells a clear review story.

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
- two to four screenshots named `lab03-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
