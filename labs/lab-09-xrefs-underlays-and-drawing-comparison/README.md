# Lab 09 — Xrefs, Underlays and Drawing Comparison

**Mapping:** LO4 · K4 · A4

**Tools:** AutoCAD · XREF · ATTACH · OVERLAY · PDFATTACH · DWGCOMPARE

**Outcome:** A host coordination drawing with controlled Xrefs/underlays and a documented comparison review.

## Scenario and objective

Coordinate external drawings and review changes while preserving clear ownership and portable references.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `Furniture_Floor_Plan.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `Sink_Layouts.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab09-<initials>.dwg`.

## Detailed procedure

1. Create a new host drawing and save it in the Lab 9 folder before attaching references. **Command / tool:** `NEW · SAVEAS`
2. Attach Furniture_Floor_Plan.dwg as an Xref using a relative path, insertion 0,0,0, scale 1 and rotation 0. **Command / tool:** `XREF Attach`
3. Overlay Sink_Layouts.dwg and explain why Overlay avoids nested-reference propagation. **Command / tool:** `XREF Overlay`
4. Inspect Xref layer prefixes and apply a host-only layer override for review visibility. **Command / tool:** `LAYER`
5. Unload and reload one reference; then repath it to a relative location without losing placement. **Command / tool:** `XREF Unload · Reload · Change Path`
6. Attach the supplied JPEG reference as a raster underlay on a dedicated non-plotting layer. **Command / tool:** `IMAGEATTACH`
7. Clip or fade the underlay only enough to support review without hiding host geometry. **Command / tool:** `IMAGECLIP · IMAGEADJUST`
8. Create a controlled revision copy, change three items and run Drawing Compare. **Command / tool:** `DWGCOMPARE`
9. Classify changes as added, removed or modified and record the required stakeholder response. **Command / tool:** `Compare review`
10. Package the host and references and verify all relative links resolve from the package folder. **Command / tool:** `ETRANSMIT`

## Verification and acceptance

References resolve using controlled paths, ownership remains clear and the compare record accurately identifies changes.

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
- two to four screenshots named `lab09-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
