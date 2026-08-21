# Autodesk Certified Professional (ACP) - AutoCAD Design and Drafting - Learner Guide

**TGS-2023036004 | Design Sketching (BEV-DES-5026-1.1-1) | v8.0 | 22 August 2026**

## Contents

- [How to Use This Guide](#how-to-use-this-guide)
- [Standards, Art Direction and Drawing Trust](#standards,-art-direction-and-drawing-trust)
- [The AutoCAD Precision System](#the-autocad-precision-system)
- [Drawing Management and Revision](#drawing-management-and-revision)
- [Annotation and Stakeholder Story](#annotation-and-stakeholder-story)
- [Authoring and Reuse](#authoring-and-reuse)
- [Layouts, Output and Collaboration](#layouts,-output-and-collaboration)
- [Detailed Labs](#detailed-labs)
  - [Lab 01 - Drawing Standards and Project Setup](#lab-01---drawing-standards-and-project-setup)
  - [Lab 02 - Layers, Object Management and Revision Control](#lab-02---layers-object-management-and-revision-control)
  - [Lab 03 - Annotation Standards and Stakeholder Story](#lab-03---annotation-standards-and-stakeholder-story)
  - [Lab 04 - Dimensions, Multileaders and Data Tables](#lab-04---dimensions-multileaders-and-data-tables)
  - [Lab 05 - Advanced Geometry and Precision Editing](#lab-05---advanced-geometry-and-precision-editing)
  - [Lab 06 - Blocks, Attributes and Data Extraction](#lab-06---blocks-attributes-and-data-extraction)
  - [Lab 07 - Layouts, Viewports and Page Setups](#lab-07---layouts-viewports-and-page-setups)
  - [Lab 08 - Publish, Plot and eTransmit](#lab-08---publish-plot-and-etransmit)
  - [Lab 09 - Xrefs, Underlays and Drawing Comparison](#lab-09---xrefs-underlays-and-drawing-comparison)
  - [Lab 10 - Integrated Sink Documentation Capstone](#lab-10---integrated-sink-documentation-capstone)
- [Assessment Preparation](#assessment-preparation)
- [References](#references)

## How to Use This Guide

The slide deck is concept-led. This Learner Guide and the individual lab folders carry the detailed procedures, evidence requirements and acceptance criteria.

Work through Labs 1-10 in sequence. Always edit a working copy, preserve the recovered original DWG, and use the JPEG brief in each lab folder as a visual checking reference.

AutoCAD commands can be launched from the ribbon, palettes, shortcut menu or command line. The guide names the command so learners can work across interface arrangements.

## Standards, Art Direction and Drawing Trust

Art direction becomes operational when the drawing declares units, origin, scale, layer naming, lineweight hierarchy, annotation system, sheet convention and revision status.

A standard is a testable agreement. Record what must remain consistent, who owns the source, how exceptions are approved and what evidence proves the rule was applied.

For every source or Xref, distinguish visual context from editable ownership. Referencing preserves accountability; copying geometry can hide source changes and create conflicting truth.

## The AutoCAD Precision System

Accuracy comes from a system: drawing units, UCS, object snaps, polar/object-snap tracking, dynamic input, typed coordinates or distances, fit-for-purpose object types, and explicit measurement.

Model scale, insertion scale, viewport scale and plot scale are separate controls. A wrong model should not be corrected by manipulating paper output.

Use ID, DIST, LIST, Properties and plot preview as independent checks. Visual appearance alone is not evidence of dimensional accuracy.

## Drawing Management and Revision

Layers organise by function or purpose. Off hides temporarily; Freeze suppresses regeneration and can improve performance; Lock protects objects while preserving context.

Property filters and group filters help navigate complex drawings. Layer states restore named review/plot conditions, while viewport overrides control sheet-specific presentation.

Use Audit and Purge deliberately. Investigate warnings, remove only confirmed unused definitions, preserve a revision before cleanup and verify references after the operation.

## Annotation and Stakeholder Story

A stakeholder should be able to orient, read the primary dimensions, follow callouts to decisions, check schedules and identify the current revision without searching the sheet.

Named text, dimension, multileader and table styles are organisational assets. Annotative properties help one object remain readable across required viewport scales.

Revision clouds, delta notes and drawing comparison make change visible. Wipeouts can improve legibility but must never conceal required geometry or evidence.

## Authoring and Reuse

Polylines are connected, measurable paths; splines model controlled smooth curves; regions support area properties and Boolean operations; xlines and rays are construction references.

Use the least destructive modification that communicates design intent. Associative arrays preserve relationships; multifunctional grips expose object-specific edits.

Blocks are reusable definitions; groups are temporary selection relationships. Attributes attach instance data to blocks, and Data Extraction turns that data into schedules.

## Layouts, Output and Collaboration

Model space contains full-size design geometry. Paper space composes controlled sheets through title blocks, viewports, scales, layer overrides and page setups.

Publish only current layouts, inspect every output page at full size, and use eTransmit to package dependencies with documented path handling.

Attach and Overlay have different nesting behaviour. Relative paths are usually portable inside a disciplined project tree; every package must be open-tested from its final location.

## Learning Outcomes and TSC Mapping

- LO1: Define the application of emerging design visualization standards in AutoCAD art direction and sketching.
- LO2: Develop the organisation's drawing and sketching capabilities using methods for revising 2D and 3D technical drawings.
- LO3: Develop organisation-specific drawing standards that use storytelling and annotation to engage stakeholders.
- LO4: Lead the integration of emerging drawing technologies and suitable methods in alignment with organisational growth.
- LO5: Inspire stakeholders to explore traditional and contemporary approaches to drawing and sketching.

### Knowledge

- **K1:** Emerging design visualization standards
- **K2:** Methods to revise two-dimensional and three-dimensional technical drawings
- **K3:** Elements of storytelling and stakeholder engagement through drawings
- **K4:** Key emerging technologies for drawing and sketching

### Abilities

- **A1:** Define the art direction and sketching style for the organisation
- **A2:** Define and guide the development of drawing and sketching capabilities
- **A3:** Develop standards for organisational drawing and sketching
- **A4:** Lead selection of suitable drawing technology and methods aligned with growth
- **A5:** Inspire exploration of traditional and contemporary drawing approaches

## Detailed Labs

### Lab 01 - Drawing Standards and Project Setup

**Mapping:** LO1 · K1 · A1

**Scenario:** Translate a design brief into a documented AutoCAD setup covering units, visual style, naming, layers and evidence standards.

**Outcome:** A standards-ready furniture plan with a completed drawing-standard record and verified setup evidence.

**Tools:** AutoCAD · UNITS · LAYER · PROPERTIES · Named UCS

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Floor_Plan.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Open the supplied Furniture_Floor_Plan.dwg and save a working copy named lab01-<initials>.dwg.

   **Command / tool:** `SAVEAS`

2. Read the project brief and record the intended discipline, audience, drawing purpose and required deliverables.

   **Command / tool:** `Lab brief`

3. Open Drawing Units; confirm the length type, precision, insertion scale and angle convention required by the brief.

   **Command / tool:** `UNITS`

4. Inspect extents and measure two known elements to confirm the drawing scale is credible before editing.

   **Command / tool:** `ZOOM Extents · DIST`

5. Create a named UCS for the principal drawing orientation and restore World UCS for comparison.

   **Command / tool:** `UCS · Named`

6. Define the layer naming, colour, linetype, lineweight and plot expectations in the standards record.

   **Command / tool:** `LAYER`

7. Check object properties for representative walls, fixtures and annotations; record any exceptions.

   **Command / tool:** `PROPERTIES`

8. Set a visual review style that makes lineweight and object hierarchy easy to inspect.

   **Command / tool:** `LWDISPLAY`

9. Purge only confirmed unused definitions, then audit the file and save a new revision.

   **Command / tool:** `PURGE · AUDIT`

10. Capture the Units, Layer Properties, UCS and measured-dimension evidence required by the checklist.

   **Command / tool:** `Evidence screenshots`


#### Verification and acceptance

Units, scale, UCS, naming and layer rules are documented; the drawing opens without errors and passes the lab checklist.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-01-drawing-standards-and-project-setup/`

### Lab 02 - Layers, Object Management and Revision Control

**Mapping:** LO2 · K2 · A2

**Scenario:** Organise and revise a drawing using selection methods, layer filters, layer states, overrides and controlled cleanup.

**Outcome:** A revised furniture plan with reusable layer states, filters and a change log.

**Tools:** AutoCAD · Layer States · Layer Filters · QSELECT · SELECTSIMILAR · LAYMRG

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Floor_Plan.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Open the Lab 2 source copy and create a new revision before making organisational changes.

   **Command / tool:** `SAVEAS`

2. Use Quick Select to find objects by layer, colour and object type; compare with Select Similar.

   **Command / tool:** `QSELECT · SELECTSIMILAR`

3. Create discipline-based property filters and a temporary group filter for the current revision task.

   **Command / tool:** `LAYER FILTER`

4. Save a Presentation layer state and a Coordination layer state with different visibility and plot settings.

   **Command / tool:** `LAYERSTATE`

5. Apply viewport-ready layer-property overrides to highlight the coordination scope without changing global properties.

   **Command / tool:** `Layer overrides`

6. Lock reference layers, freeze layers not needed for the task and explain the difference from turning a layer off.

   **Command / tool:** `LOCK · FREEZE · OFF`

7. Use Hide/Isolate for a short review, then end isolation and prove no objects remain accidentally hidden.

   **Command / tool:** `ISOLATEOBJECTS · UNISOLATEOBJECTS`

8. Merge only the two duplicate layers named in the brief and confirm the destination layer.

   **Command / tool:** `LAYMRG`

9. Record before/after layer counts and describe how the changes support team revision capability.

   **Command / tool:** `Layer Properties evidence`

10. Audit and save the final revision with the completed change log.

   **Command / tool:** `AUDIT · SAVE`


#### Verification and acceptance

Required filters and states restore correctly; no object is lost; the merged layers and revision evidence match the brief.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-02-layers-object-management-and-revision-control/`

### Lab 03 - Annotation Standards and Stakeholder Story

**Mapping:** LO3 · K3 · A3

**Scenario:** Create an annotation system that leads a stakeholder from overview to decision-critical detail.

**Outcome:** An annotated plan with text, dimensions, multileaders, hatches and revision communication governed by named styles.

**Tools:** AutoCAD · STYLE · DIMSTYLE · MLEADERSTYLE · HATCH · REVCLOUD

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Floor_Plan.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Open the source drawing and identify the three messages the stakeholder must understand first.

   **Command / tool:** `Stakeholder brief`

2. Create or verify a text style with the required font, height rule and width factor.

   **Command / tool:** `STYLE`

3. Create a dimension style for the project units, precision, arrowheads, text placement and tolerances.

   **Command / tool:** `DIMSTYLE`

4. Create a multileader style with a consistent landing, arrowhead and content hierarchy.

   **Command / tool:** `MLEADERSTYLE`

5. Apply concise callouts that state the decision, not merely the object name.

   **Command / tool:** `MLEADER`

6. Use hatches with controlled scale and origin to distinguish material or scope without obscuring geometry.

   **Command / tool:** `HATCH · HATCHEDIT`

7. Add a revision cloud and delta note to make one documented change visible.

   **Command / tool:** `REVCLOUD`

8. Use a wipeout only where it improves readability and confirm frame/display settings do not hide required geometry.

   **Command / tool:** `WIPEOUT`

9. Run an annotation-scale review at two intended viewport scales.

   **Command / tool:** `CANNOSCALE`

10. Capture the styles, annotation hierarchy and stakeholder reading order in the evidence sheet.

   **Command / tool:** `Evidence screenshots`


#### Verification and acceptance

Annotations are legible at the required scales, styles are reusable, and the drawing tells a clear review story.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-03-annotation-standards-and-stakeholder-story/`

### Lab 04 - Dimensions, Multileaders and Data Tables

**Mapping:** LO3 · K3 · A3

**Scenario:** Build a coordinated detailing layer that combines efficient dimensions, callouts and a component schedule.

**Outcome:** A review sheet with validated dimensions, labels and a structured furniture/component table.

**Tools:** AutoCAD · DIM · QDIM · MLEADER · TABLE · FIELD

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Floor_Plan.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Create linear, aligned, angular and radial dimensions only where each type communicates the geometry correctly.

   **Command / tool:** `DIM`

2. Use Quick Dimension for a repeated chain, then inspect and correct crowded or ambiguous results.

   **Command / tool:** `QDIM`

3. Edit dimension text only when necessary and preserve the measured value through fields or associative dimensions.

   **Command / tool:** `DIMREASSOCIATE`

4. Add keynotes with multileaders and align them into a readable callout column.

   **Command / tool:** `MLEADERALIGN`

5. Create a table style with a clear title, header and data-row hierarchy.

   **Command / tool:** `TABLESTYLE`

6. Insert a component schedule with item, description, material, size and manufacturer columns.

   **Command / tool:** `TABLE`

7. Use a field for one drawing property and update it to prove the link is live.

   **Command / tool:** `FIELD · UPDATEFIELD`

8. Check spelling, unit consistency, overlaps and duplicated information.

   **Command / tool:** `SPELL · visual check`

9. Plot-preview the sheet at the intended scale and correct any annotation that becomes unreadable.

   **Command / tool:** `PLOT Preview`

10. Save the final sheet and complete the acceptance checklist.

   **Command / tool:** `SAVE`


#### Verification and acceptance

Dimensions remain associative, leaders are aligned, the table is complete and the plotted sheet is readable.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-04-dimensions-multileaders-and-data-tables/`

### Lab 05 - Advanced Geometry and Precision Editing

**Mapping:** LO1–LO2 · K1, K2 · A1, A2

**Scenario:** Author and revise technical geometry with polylines, arcs, polygons, splines, regions, construction geometry and precision tools.

**Outcome:** A precise 2D component study plus an isometric view using fit-for-purpose object types.

**Tools:** AutoCAD · PLINE · ARC · POLYGON · SPLINE · REGION · UCS · OSNAP

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Floor_Plan.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Set object snaps, polar tracking and dynamic input for the supplied geometry brief.

   **Command / tool:** `OSNAP · POLAR · DYNMODE`

2. Create a closed polyline outline with one straight and one arc segment; verify closure and area.

   **Command / tool:** `PLINE · LIST`

3. Create a polygon by centre/radius and another by edge; compare control and revision behaviour.

   **Command / tool:** `POLYGON`

4. Create a spline using fit points, then edit its control vertices to refine the silhouette.

   **Command / tool:** `SPLINE · SPLINEDIT`

5. Use xlines and rays as non-plotting construction references on a dedicated layer.

   **Command / tool:** `XLINE · RAY`

6. Convert the closed outlines into regions and demonstrate Union and Subtract on copies.

   **Command / tool:** `REGION · UNION · SUBTRACT`

7. Use grips, multifunctional grips, Move, Rotate, Offset, Mirror, Stretch, Trim and Extend on measured edits.

   **Command / tool:** `GRIPS · MODIFY tools`

8. Create a rectangular or polar associative array and edit its parameters after placement.

   **Command / tool:** `ARRAYRECT · ARRAYPOLAR`

9. Switch to isometric drafting, cycle isoplanes and add an isocircle for the component study.

   **Command / tool:** `ISODRAFT · F5 · ELLIPSE Isocircle`

10. Verify coordinates and dimensions, then save the finished component sheet.

   **Command / tool:** `ID · DIST · SAVE`


#### Verification and acceptance

Objects use suitable types, edits remain accurate, construction geometry is separated and the isometric view is coherent.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-05-advanced-geometry-and-precision-editing/`

### Lab 06 - Blocks, Attributes and Data Extraction

**Mapping:** LO4 · K4 · A4

**Scenario:** Develop reusable content that carries organisational data and supports consistent schedules.

**Outcome:** A small furniture block library with attributes and an extracted component schedule.

**Tools:** AutoCAD · BLOCK · WBLOCK · ATTDEF · EATTEDIT · DATAEXTRACTION

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Block_Attributes.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Open the source file and inventory the furniture objects that should become reusable definitions.

   **Command / tool:** `BEDIT / source review`

2. Choose logical base points and create named blocks using the project naming rule.

   **Command / tool:** `BLOCK`

3. Write one approved block to an external DWG for controlled reuse.

   **Command / tool:** `WBLOCK`

4. Define ITEM, DESCRIPTION, MATERIAL and MANUFACTURER attributes with suitable prompts and defaults.

   **Command / tool:** `ATTDEF`

5. Insert several block instances and enter distinct attribute values.

   **Command / tool:** `INSERT`

6. Edit one block definition and confirm all instances update without losing attribute values.

   **Command / tool:** `BEDIT · BSAVE`

7. Synchronise attribute definitions and repair any out-of-date instances.

   **Command / tool:** `ATTSYNC`

8. Extract block and attribute data into an AutoCAD table.

   **Command / tool:** `DATAEXTRACTION`

9. Group a temporary review set and explain why a group is not a reusable block definition.

   **Command / tool:** `GROUP`

10. Save the library, schedule and evidence of the data relationship.

   **Command / tool:** `SAVE`


#### Verification and acceptance

Blocks reuse cleanly, attributes persist through edits and the extracted schedule matches the inserted instances.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-06-blocks-attributes-and-data-extraction/`

### Lab 07 - Layouts, Viewports and Page Setups

**Mapping:** LO3 · K3 · A1, A2, A3

**Scenario:** Build ISO A1, A2 and A3 layouts with correct page setups, title blocks, viewport views and locked scales.

**Outcome:** A coordinated three-sheet sink drawing set that mirrors the original practical-assessment workflow.

**Tools:** AutoCAD · LAYOUT · PAGESETUP · MVIEW · VPORTS · SCALELISTEDIT

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Sink_Layouts.dwg` - recovered AutoCAD source file.
- `ISO A1 title block.dwg` - recovered AutoCAD source file.
- `ISO A2 title block.dwg` - recovered AutoCAD source file.
- `ISO A3 title block.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Open Sink_Layouts.dwg and save a working copy in the Lab 7 folder.

   **Command / tool:** `SAVEAS`

2. Inspect model-space extents, saved views and the current ISO A2 layout.

   **Command / tool:** `ZOOM Extents · VIEW`

3. Create a named page setup for each required ISO expanded sheet size and verify plot units and orientation.

   **Command / tool:** `PAGESETUP`

4. Copy the ISO A2 layout twice and rename the copies ISO A1 and ISO A3.

   **Command / tool:** `LAYOUT Copy · Rename`

5. Assign the correct page setup to ISO A1, ISO A2 and ISO A3.

   **Command / tool:** `PAGESETUP`

6. Insert each supplied title-block drawing at 0,0 on the Border layer in paper space.

   **Command / tool:** `-INSERT 0,0`

7. Create three equal viewports on ISO A2 and place them on the Viewports layer.

   **Command / tool:** `MVIEW`

8. Set Top, Front and Right views, apply 1:8 scale, Hidden visual style and lock the viewports.

   **Command / tool:** `VIEW · ZOOM 1/8xp · LOCK`

9. Create one SE Isometric viewport on ISO A3 at 1:5 using Shaded or Realistic style and lock it.

   **Command / tool:** `MVIEW · SE Isometric · 1/5xp`

10. Preview all sheets, verify title blocks and save the coordinated drawing set.

   **Command / tool:** `PLOT Preview · SAVE`


#### Verification and acceptance

All three layouts use the correct sheet, border and viewport settings; scales and view locks match the brief.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-07-layouts-viewports-and-page-setups/`

### Lab 08 - Publish, Plot and eTransmit

**Mapping:** LO3–LO4 · K3, K4 · A3, A4

**Scenario:** Configure repeatable output and package the drawing set with all required dependencies.

**Outcome:** A published PDF sheet set and a verified eTransmit package with a transmittal report.

**Tools:** AutoCAD · PUBLISH · PLOT · ETRANSMIT · Page Setup Manager

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Sink_Layouts.dwg` - recovered AutoCAD source file.
- `ISO A1 title block.dwg` - recovered AutoCAD source file.
- `ISO A2 title block.dwg` - recovered AutoCAD source file.
- `ISO A3 title block.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Open the completed layout drawing and run a dependency check before publishing.

   **Command / tool:** `XREF · FONTALT awareness`

2. Import or create the approved page setups and apply them consistently to the sheet set.

   **Command / tool:** `PAGESETUP Import`

3. Open Publish, order the sheets and remove any model-space sheet not required by the brief.

   **Command / tool:** `PUBLISH`

4. Set the PDF output options, plot stamp rule and layer-information requirement.

   **Command / tool:** `Publish Options`

5. Preview each sheet and correct clipping, lineweight, colour and scale defects before output.

   **Command / tool:** `Preview`

6. Publish the multi-sheet PDF and inspect every page at full size.

   **Command / tool:** `PUBLISH`

7. Open eTransmit and review all referenced files, fonts, plot styles and support paths.

   **Command / tool:** `ETRANSMIT`

8. Choose a package structure that keeps the drawing portable and records path handling.

   **Command / tool:** `Transmittal Setup`

9. Create the ZIP package and verify it contains the current DWG, title blocks and transmittal report.

   **Command / tool:** `Create Transmittal`

10. Record hashes/file sizes and save the final evidence checklist.

   **Command / tool:** `Finder / checksum evidence`


#### Verification and acceptance

The PDF contains all required sheets and the eTransmit package opens as a complete, current drawing set.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-08-publish-plot-and-etransmit/`

### Lab 09 - Xrefs, Underlays and Drawing Comparison

**Mapping:** LO4 · K4 · A4

**Scenario:** Coordinate external drawings and review changes while preserving clear ownership and portable references.

**Outcome:** A host coordination drawing with controlled Xrefs/underlays and a documented comparison review.

**Tools:** AutoCAD · XREF · ATTACH · OVERLAY · PDFATTACH · DWGCOMPARE

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Furniture_Floor_Plan.dwg` - recovered AutoCAD source file.
- `Sink_Layouts.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Create a new host drawing and save it in the Lab 9 folder before attaching references.

   **Command / tool:** `NEW · SAVEAS`

2. Attach Furniture_Floor_Plan.dwg as an Xref using a relative path, insertion 0,0,0, scale 1 and rotation 0.

   **Command / tool:** `XREF Attach`

3. Overlay Sink_Layouts.dwg and explain why Overlay avoids nested-reference propagation.

   **Command / tool:** `XREF Overlay`

4. Inspect Xref layer prefixes and apply a host-only layer override for review visibility.

   **Command / tool:** `LAYER`

5. Unload and reload one reference; then repath it to a relative location without losing placement.

   **Command / tool:** `XREF Unload · Reload · Change Path`

6. Attach the supplied JPEG reference as a raster underlay on a dedicated non-plotting layer.

   **Command / tool:** `IMAGEATTACH`

7. Clip or fade the underlay only enough to support review without hiding host geometry.

   **Command / tool:** `IMAGECLIP · IMAGEADJUST`

8. Create a controlled revision copy, change three items and run Drawing Compare.

   **Command / tool:** `DWGCOMPARE`

9. Classify changes as added, removed or modified and record the required stakeholder response.

   **Command / tool:** `Compare review`

10. Package the host and references and verify all relative links resolve from the package folder.

   **Command / tool:** `ETRANSMIT`


#### Verification and acceptance

References resolve using controlled paths, ownership remains clear and the compare record accurately identifies changes.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-09-xrefs-underlays-and-drawing-comparison/`

### Lab 10 - Integrated Sink Documentation Capstone

**Mapping:** LO1–LO5 · K1–K4 · A1–A5

**Scenario:** Complete the recovered sink-layout dataset as a professional drawing package and lead a short stakeholder review.

**Outcome:** A standards-based sink drawing set with layouts, title blocks, viewports, component table, publish package and review evidence.

**Tools:** AutoCAD · Complete professional workflow

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `Sink_Layouts.dwg` - recovered AutoCAD source file.
- `Furniture_Block_Attributes.dwg` - recovered AutoCAD source file.
- `ISO A1 title block.dwg` - recovered AutoCAD source file.
- `ISO A2 title block.dwg` - recovered AutoCAD source file.
- `ISO A3 title block.dwg` - recovered AutoCAD source file.

#### Detailed procedure

1. Review the capstone brief and define the intended visual hierarchy, sheet standards and stakeholder questions.

   **Command / tool:** `Capstone brief`

2. Create ISO A1, A2 and A3 layouts with the correct page setups and title blocks at 0,0.

   **Command / tool:** `LAYOUT · PAGESETUP · INSERT`

3. Create and lock the required Top, Front, Right and SE Isometric viewports at the specified scales.

   **Command / tool:** `MVIEW · 1:8 · 1:5`

4. Apply the organisational layer and annotation standards developed in earlier labs.

   **Command / tool:** `Layer states · styles`

5. Create a component schedule listing visible sink components, dimensions, materials and manufacturer details.

   **Command / tool:** `TABLE · attributes/data extraction`

6. Use revision communication to identify one design decision that needs stakeholder confirmation.

   **Command / tool:** `REVCLOUD · MLEADER`

7. Run drawing-health, missing-reference, scale and plot-preview checks.

   **Command / tool:** `AUDIT · XREF · PLOT Preview`

8. Publish a multi-sheet PDF and create an eTransmit ZIP of the current package.

   **Command / tool:** `PUBLISH · ETRANSMIT`

9. Present the drawing story in three minutes: overview, decision-critical details and requested approval.

   **Command / tool:** `Stakeholder review`

10. Submit the DWG, published PDF, package inventory and completed evidence checklist.

   **Command / tool:** `Submission`


#### Verification and acceptance

The drawing set meets the capstone acceptance criteria and the learner can justify each standard, technology and communication decision.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-10-integrated-sink-documentation-capstone/`

## Assessment Preparation

Written Assessment (WA-SAQ) — 4 open-ended questions covering K1–K4, 60 minutes, open book.

Practical Performance (PP) — 5 hands-on tasks covering A1–A5, 120 minutes, open book.

The WA retains four open-ended questions mapped to K1-K4. The PP retains five tasks mapped to A1-A5 and uses the recovered Sink_Layouts/title-block dataset.

Review the concept sections for knowledge questions. For the PP, rehearse the complete Lab 7 and Lab 10 workflow while explaining why each page setup, viewport, scale, title block and component-table decision is appropriate.

## References

- Autodesk Certified Professional in AutoCAD for Design and Drafting: https://www.autodesk.com/certification/all-certifications/autocad-design-drafting-professional
- Autodesk AutoCAD certification-preparation course (updated December 2025): https://www.autodesk.com/learn/ondemand/course/autocad-design-drafting-cert-prep
- Autodesk AutoCAD Help: https://help.autodesk.com/view/ACD/2026/ENU/
- Tertiary course page and published outcomes: https://www.tertiarycourses.com.sg/wsq-autodesk-certified-professional-acp-autocad-design-and-drafting.html
- Legacy trainer slides v7, legacy Learner Guide v2, Drive WA/PP v1, and the recovered original PP dataset.
