# Lab 11 — Drawing Environment, UCS and Recovery

**Mapping:** LO1–LO2 · Exam 1.2, 1.4, 1.5 · K1–K2 · A1–A2

**Tools:** AutoCAD · CUI · WSCURRENT · UCS · UCSMAN · RECOVER · DRAWINGRECOVERY

**Outcome:** A documented AutoCAD workspace and UCS set plus a recovered, audited and versioned drawing.

## Scenario and objective

Configure a portable professional workspace, establish named coordinate systems and recover a controlled revision from supplied drawing files.

## Supplied files

- `lab-reference.jpg` — the JPEG visual brief/checking image.
- `workspaces.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `drafting-settings.dwg` — supplied AutoCAD working/source file or technical drawing reference.
- `Environment.dwg` — supplied AutoCAD working/source file or technical drawing reference.

## Before you begin

1. Work only on a copy of each supplied DWG.
2. Keep the original file in this folder unchanged so you can restart.
3. Confirm the intended units and drawing scale before editing.
4. Save your working copy as `lab11-<initials>.dwg`.

## Detailed procedure

1. Open the workspace and drafting-settings samples; record the interface controls that support precision review. **Command / tool:** `WSCURRENT · DSETTINGS`
2. Create a project workspace that exposes Properties, Layers and External References without obscuring the model. **Command / tool:** `CUI · palettes`
3. Open Environment.dwg and confirm units, world origin and a known reference dimension. **Command / tool:** `UNITS · ID · DIST`
4. Create a named UCS aligned to an angled workface and restore it after returning to World UCS. **Command / tool:** `UCS · UCSMAN · PLAN`
5. Save a controlled working revision, close it and verify the named UCS and workspace state on reopen. **Command / tool:** `SAVEAS`
6. Create a safe test copy and run AUDIT; record the number and type of errors found. **Command / tool:** `AUDIT`
7. Compare AUDIT, RECOVER and RECOVERALL and select the appropriate recovery scope for the supplied scenario. **Command / tool:** `RECOVER · RECOVERALL`
8. Inspect Drawing Recovery Manager and identify DWG, BAK and SV$ candidates by timestamp and source path. **Command / tool:** `DRAWINGRECOVERY`
9. Save the chosen recovery result under a new revision name without overwriting the approved file. **Command / tool:** `SAVEAS`
10. Capture workspace, UCS, audit log and recovered-file evidence in the checklist. **Command / tool:** `Evidence screenshots`

## Verification and acceptance

The workspace and named UCS restore correctly; the recovered revision is current, opens cleanly and preserves the approved source.

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
- two to four screenshots named `lab11-evidence-01.jpg`, `-02.jpg`, and so on;
- any published PDF or eTransmit ZIP required by the lab;
- the completed `EVIDENCE-CHECKLIST.md` or printed PDF.
