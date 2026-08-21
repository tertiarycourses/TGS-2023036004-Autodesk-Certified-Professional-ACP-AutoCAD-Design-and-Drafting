# Lab 16 — Shared Review, References and Linked Data

**Mapping:** LO4–LO5 · Exam 5.1–5.3 · K4 · A4–A5

**Tools:** AutoCAD · TRACE · DWGCOMPARE · XREF · PDFIMPORT · DATALINK · FIELD

**Outcome:** A reviewed host drawing with trace evidence, controlled references, verified PDF import and live linked data.

## Scenario and objective

Coordinate a shared drawing review using Traces and Compare, repair portable references, import PDF geometry and connect tables and fields to governed data.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `new-office-layout-with-xref.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `Landscaping_REV1.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `ex1-drawing-sheet.pdf` — supplied AutoCAD working/source file or technical drawing reference.
- `New Office Proposal_REV1.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `New Office Proposal_REV2.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab16-<initials>.dwg`.

## Detailed procedure

1. Open the host drawing and verify the reference tree, ownership prefixes and saved path types. **Command / tool:** `XREF`
2. Repair any unresolved link with a relative path and verify portability from the lab folder. **Command / tool:** `Change Path · Reload`
3. Create a controlled review trace that records two stakeholder comments without changing source geometry. **Command / tool:** `TRACE`
4. Compare the two office proposal revisions and classify added, removed and modified objects. **Command / tool:** `DWGCOMPARE`
5. Record which differences are accepted, rejected or require stakeholder clarification. **Command / tool:** `review decision log`
6. Attach the drawing-sheet PDF, control its frame and clip, then assess whether its vectors are suitable for import. **Command / tool:** `PDFATTACH · PDFFRAME`
7. Import a controlled area and verify scale, layers, linework and text treatment before reuse. **Command / tool:** `PDFIMPORT`
8. Create a data link to a controlled schedule source and insert the linked range as a table. **Command / tool:** `DATALINK · TABLE`
9. Add fields for one object property and one drawing or sheet property; update and inspect them. **Command / tool:** `FIELD · UPDATEFIELD`
10. Package the host, references and permitted linked evidence and complete the collaboration audit trail. **Command / tool:** `ETRANSMIT`

## Verification and acceptance

Review provenance remains visible, references survive relocation and all imported or linked data is verified against its authoritative source.

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
- two to four screenshots named `lab16-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
