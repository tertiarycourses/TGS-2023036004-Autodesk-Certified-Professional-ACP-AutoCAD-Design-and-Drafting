# Lab 15 — Named Page Setups, Sheet Sets and Batch Output

**Mapping:** LO3–LO4 · Exam 4.1–4.3 · K3–K4 · A3–A4

**Tools:** AutoCAD · PAGESETUP · MVIEW · SHEETSET · PUBLISH · ETRANSMIT

**Outcome:** A governed office drawing sheet set with reusable page setups, sheet metadata and a verified batch PDF.

## Scenario and objective

Govern a multi-sheet production package through named page setups, controlled viewports, Sheet Set Manager properties and batch publishing.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `new-office-layout.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `title-block.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `Metal Plate_FINAL.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `Metal Plate_ISO A3.dwt` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab15-<initials>.dwg`.

## Detailed procedure

1. Open the office and metal-plate files and record each required sheet size, scale and output purpose. **Command / tool:** `sheet brief`
2. Create named PDF and proof-print page setups that coordinate device, media, plot area, scale and plot style. **Command / tool:** `PAGESETUP`
3. Compose rectangular and non-rectangular viewports and place their frames on a non-plotting layer. **Command / tool:** `MVIEW · VPCLIP`
4. Set exact viewport and annotation scales, apply sheet-specific layer overrides and lock approved views. **Command / tool:** `viewport properties`
5. Create a sheet set with discipline subsets and import only compliant source layouts. **Command / tool:** `SHEETSET`
6. Populate set-wide and sheet-specific properties and display them through title-block fields. **Command / tool:** `Sheet Set Manager · FIELD`
7. Renumber two sheets and verify the title block and sheet-list table update. **Command / tool:** `sheet properties`
8. Build and save an ordered publish sheet list with the approved page-setup override. **Command / tool:** `PUBLISH · DSD`
9. Publish the batch PDF and inspect every page for clipping, scale, lineweight, references and revision. **Command / tool:** `PUBLISH · PDF review`
10. Create an eTransmit package and open-test it from the packaged location. **Command / tool:** `ETRANSMIT`

## Verification and acceptance

Named setups and sheet properties drive consistent output; the ordered PDF and portable package pass every review check.

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
- two to four screenshots named `lab15-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
