# Autodesk Certified Professional (ACP) - AutoCAD Design and Drafting - Learner Guide

**TGS-2023036004 | Design Sketching (BEV-DES-5026-1.1-1) | v9.0 | 22 August 2026**

## Contents

- [How to Use This Guide](#how-to-use-this-guide)
- [Standards, Art Direction and Drawing Trust](#standards,-art-direction-and-drawing-trust)
- [The AutoCAD Precision System](#the-autocad-precision-system)
- [Drawing Management and Revision](#drawing-management-and-revision)
- [Annotation and Stakeholder Story](#annotation-and-stakeholder-story)
- [Authoring and Reuse](#authoring-and-reuse)
- [Layouts, Output and Collaboration](#layouts,-output-and-collaboration)
- [Autodesk Exam Objective Guide](#autodesk-exam-objective-guide)
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
  - [Lab 11 - Drawing Environment, UCS and Recovery](#lab-11---drawing-environment-ucs-and-recovery)
  - [Lab 12 - Annotation Styles, Scales and Schedules](#lab-12---annotation-styles-scales-and-schedules)
  - [Lab 13 - Coordinate Geometry and Construction Objects](#lab-13---coordinate-geometry-and-construction-objects)
  - [Lab 14 - Associative Arrays and Grip-Based Revision](#lab-14---associative-arrays-and-grip-based-revision)
  - [Lab 15 - Named Page Setups, Sheet Sets and Batch Output](#lab-15---named-page-setups-sheet-sets-and-batch-output)
  - [Lab 16 - Shared Review, References and Linked Data](#lab-16---shared-review-references-and-linked-data)
- [Assessment Preparation](#assessment-preparation)
- [References](#references)

## How to Use This Guide

The slide deck is concept-led. This Learner Guide and the individual lab folders carry the detailed procedures, evidence requirements and acceptance criteria.

Work through Labs 1-16 in sequence. Always edit a working copy, preserve the supplied original DWG, and use the JPEG brief in each lab folder as a visual checking reference.

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

## Autodesk Exam Objective Guide

This section covers every leaf objective in Autodesk's December 2025 AutoCAD Design and Drafting Professional outline. It explains the professional decision and evidence expected; the labs provide the detailed interface procedure.

### Domain 1 - Application and Drawing Management

#### 1.1 - Create and manage layers

##### 1.1.a - Assign and manage layer properties

**Tools and controls:** LAYER · LINETYPE · SETBYLAYER

**Professional scenario:** A consultant drawing arrives with inconsistent object colours and no reliable plotting hierarchy.

**Decision controls:**

- Use functional names that reveal discipline and purpose
- Load only approved linetypes and apply them ByLayer
- Coordinate colour, lineweight, transparency and plot style
- Separate visibility control from object ownership

**Acceptance evidence:** A layer audit shows approved names, ByLayer objects and predictable plotted lineweights.

**Primary risk:** Direct object overrides conceal standards defects and make global changes unreliable.

##### 1.1.b - Apply layer property overrides in layout viewports

**Tools and controls:** VPLAYER · Layer Properties · viewport overrides

**Professional scenario:** A coordination sheet needs structural context muted in one viewport but unchanged everywhere else.

**Decision controls:**

- Override only the presentation needed for one viewport
- Distinguish VP Freeze from global Freeze
- Use colour, linetype and lineweight overrides deliberately
- Record why the sheet view differs from the model standard

**Acceptance evidence:** The target viewport communicates hierarchy while model-space and other viewport properties remain unchanged.

**Primary risk:** Global edits made to solve a local presentation issue damage other sheets.

##### 1.1.c - Create and manage layer filters

**Tools and controls:** Layer Properties · property filters · group filters

**Professional scenario:** A 400-layer drawing must expose only fire-protection layers during review.

**Decision controls:**

- Use property filters for rule-based membership
- Use group filters for curated sets
- Search names before building a permanent filter
- Keep filters aligned to the naming convention

**Acceptance evidence:** The filter returns the complete intended set and updates correctly when compliant layers are added.

**Primary risk:** Ad-hoc hiding creates incomplete reviews and undocumented visibility states.

##### 1.1.d - Determine the origin of xref layers from prefixes

**Tools and controls:** XREF · Layer Properties · BIND/INSERT

**Professional scenario:** A layer named SITE|A-WALL conflicts with a host layer and the team must locate its owner.

**Decision controls:**

- Read the vertical-bar prefix as source drawing ownership
- Distinguish live xref layers from bound names
- Avoid renaming away ownership clues
- Trace a layer back to its reference before editing

**Acceptance evidence:** The reviewer identifies the source file and whether the content remains live or has been bound.

**Primary risk:** Editing the wrong source or binding without intent destroys coordination ownership.

#### 1.2 - Manage user coordinate systems

##### 1.2.a - Create and restore a named UCS

**Tools and controls:** UCS · UCSMAN · PLAN

**Professional scenario:** An angled building wing needs repeated orthogonal drafting without rotating the model.

**Decision controls:**

- Name coordinate systems by workface or project purpose
- Restore a UCS before precision drafting
- Pair a UCS with an intentional plan view
- Retire obsolete UCS definitions

**Acceptance evidence:** The named UCS restores the correct origin and axes and produces repeatable coordinates.

**Primary risk:** An unnamed temporary UCS is easy to lose and can contaminate later geometry.

##### 1.2.b - Manage UCS origin and rotation

**Tools and controls:** UCS Origin · Object · Z-axis · 3point

**Professional scenario:** A fabrication detail is rotated 27 degrees relative to the project grid.

**Decision controls:**

- Move the origin near the work to simplify coordinates
- Align axes to reliable geometry
- Use the least ambiguous UCS construction method
- Return to World UCS before handover checks

**Acceptance evidence:** Coordinate readouts and orthogonal input align with the detail while world geometry is preserved.

**Primary risk:** Changing axes without a visible control point causes sign and angle errors.

#### 1.3 - Query and manage drawing object properties

##### 1.3.a - Analyze and modify objects with the Properties palette

**Tools and controls:** PROPERTIES · Quick Properties · SETBYLAYER

**Professional scenario:** Several selected doors look identical but plot differently.

**Decision controls:**

- Separate geometric properties from display properties
- Recognize ByLayer and ByBlock inheritance
- Use multi-selection to expose common values
- Treat *VARIES* as a diagnostic signal

**Acceptance evidence:** The property comparison finds the override and restores the intended inheritance without changing geometry.

**Primary risk:** Visual inspection alone misses hidden overrides and object-specific values.

##### 1.3.b - Query geometry with MEASUREGEOM

**Tools and controls:** MEASUREGEOM Quick · Distance · Radius · Angle · Area

**Professional scenario:** A reviewer must validate clearances, curve radii and net floor area without adding dimensions.

**Decision controls:**

- Choose the query mode that matches the question
- Use Quick for spatial scanning, not final evidence
- Confirm units and precision before interpreting results
- Cross-check composite areas and boundaries

**Acceptance evidence:** Recorded values match the intended objects, units and boundary interpretation.

**Primary risk:** Snapping to the wrong point or using an open boundary yields persuasive but wrong measurements.

##### 1.3.c - Analyze block quantities with COUNT

**Tools and controls:** COUNT · Count palette · count boundary

**Professional scenario:** A floor plan needs a reliable workstation quantity for procurement.

**Decision controls:**

- Count named blocks rather than visual symbols
- Use a boundary to isolate scope
- Review count errors and overlapping instances
- Export or record the result with source context

**Acceptance evidence:** The count identifies the correct block definition, scope and exceptions.

**Primary risk:** Exploded or differently named symbols evade the count and understate quantities.

#### 1.4 - Manage the application environment

##### 1.4.a - Use common palette interface behaviours

**Tools and controls:** Properties · Layers · Tool Palettes · External References

**Professional scenario:** A dual-screen workspace must support layer, property and reference review without obscuring the drawing.

**Decision controls:**

- Dock persistent controls and auto-hide occasional ones
- Anchor palettes without covering drawing evidence
- Resize for readable names and properties
- Use transparency only when the underlying geometry remains legible

**Acceptance evidence:** The workspace keeps critical palettes accessible and the model readable at normal zoom.

**Primary risk:** Floating palettes can hide geometry, add unnecessary actions and create inconsistent demonstrations.

##### 1.4.b - Customize user-interface content

**Tools and controls:** CUI · workspaces · Quick Access Toolbar · tool palettes

**Professional scenario:** A drafting team repeats the same standards commands across every project.

**Decision controls:**

- Customize around repeatable work, not personal novelty
- Separate workspace layout from command content
- Use enterprise-controlled resources where available
- Document and export critical customisation

**Acceptance evidence:** The approved workspace exposes the workflow consistently and can be restored on another machine.

**Primary risk:** Undocumented local customisation disappears during upgrades and fragments team practice.

#### 1.5 - Maintain and manage drawing health

##### 1.5.a - Maintain drawings with AUDIT, RECOVER and RECOVERALL

**Tools and controls:** AUDIT · RECOVER · RECOVERALL

**Professional scenario:** A host drawing crashes on open and contains several external references.

**Decision controls:**

- Use AUDIT when the drawing opens
- Use RECOVER when the drawing cannot open normally
- Use RECOVERALL when references also need repair
- Preserve a pre-repair copy and review the log

**Acceptance evidence:** The chosen recovery scope matches the failure and the repaired set reopens with references accounted for.

**Primary risk:** Repairing the host alone can leave corrupt dependencies and incomplete evidence.

##### 1.5.b - Manage unused content with purge tools

**Tools and controls:** PURGE · -PURGE · Regapps

**Professional scenario:** A template-derived drawing is bloated by unused blocks, layers and styles.

**Decision controls:**

- Inspect purgeable definitions before removing them
- Use nested purge when dependencies are understood
- Treat registered applications separately
- Compare size and reopen behaviour after cleanup

**Acceptance evidence:** Cleanup removes unused definitions without affecting visible or referenced content.

**Primary risk:** Aggressive purge can remove resources expected later in the production workflow.

##### 1.5.c - Restore temporary files with Drawing Recovery Manager

**Tools and controls:** DRAWINGRECOVERY · autosave · backup files

**Professional scenario:** AutoCAD closes unexpectedly after substantial unsaved work.

**Decision controls:**

- Distinguish DWG, BAK and SV$ recovery candidates
- Use timestamps and source paths as evidence
- Open and inspect before replacing the production file
- Save the recovered result under controlled revision naming

**Acceptance evidence:** The chosen recovery file contains the latest valid geometry and is saved without overwriting the last approved revision.

**Primary risk:** Selecting by filename alone can restore an older or incomplete state.

### Domain 2 - Design Annotation and Detailing

#### 2.1 - Create and apply annotation styles

##### 2.1.a - Create, manage and apply annotation styles

**Tools and controls:** STYLE · DIMSTYLE · MLEADERSTYLE

**Professional scenario:** A multi-sheet set contains mixed fonts, arrowheads and leader landings.

**Decision controls:**

- Separate text, dimension and multileader governance
- Use meaningful style names and documented sizes
- Prefer style changes over object overrides
- Validate appearance at intended plotted scales

**Acceptance evidence:** Named styles produce a consistent hierarchy and update dependent annotations predictably.

**Primary risk:** Local overrides make standards drift invisible and expensive to correct.

##### 2.1.b - Create, manage and apply table styles

**Tools and controls:** TABLESTYLE · cell styles · borders

**Professional scenario:** A component schedule must remain readable after rows are added and data refreshed.

**Decision controls:**

- Define title, header and data cell roles
- Control text, fill, alignment and borders by role
- Choose table direction for the sheet reading order
- Keep numeric precision aligned with source data

**Acceptance evidence:** The style preserves hierarchy, alignment and borders across the whole table.

**Primary risk:** Manual cell formatting creates inconsistent updates and broken reading order.

#### 2.2 - Apply annotative scaling to design content

##### 2.2.a - Create and manage drawing scales

**Tools and controls:** SCALELISTEDIT · annotation scale list

**Professional scenario:** A drawing accumulated hundreds of scales from external references.

**Decision controls:**

- Keep scales appropriate to project units
- Remove duplicate or imported xref scales
- Separate object scale from viewport scale
- Name custom scales so their ratio is unambiguous

**Acceptance evidence:** The cleaned list retains required metric or imperial ratios and supports current viewports.

**Primary risk:** Deleting an active scale or mixing unit conventions breaks annotation display.

##### 2.2.b - Manage scales assigned to annotative objects

**Tools and controls:** OBJECTSCALE · annotative property

**Professional scenario:** A note must appear in 1:50 and 1:100 plans but not the 1:20 detail.

**Decision controls:**

- Assign only the scales at which the object should appear
- Remove obsolete scales deliberately
- Review hatch, text, leaders and multileaders together
- Avoid using extra scales to compensate for poor placement

**Acceptance evidence:** The object displays only in intended viewports at a consistent paper height.

**Primary risk:** Indiscriminate scale assignment clutters sheets and multiplies positions.

##### 2.2.c - Manage scale positions of annotative objects

**Tools and controls:** ANNORESET · ANNOMONITOR · grip positions

**Professional scenario:** A multileader clears geometry at 1:50 but collides with a wall at 1:100.

**Decision controls:**

- Treat each scale position as a controlled presentation
- Synchronize positions when one approved location should govern
- Use separate positions only to prevent collisions
- Review all supported scales before sign-off

**Acceptance evidence:** Each scale position is intentional, readable and traceable to the same annotation content.

**Primary risk:** Moving one representation without checking others leaves hidden sheet defects.

##### 2.2.d - Display annotative objects correctly in viewports

**Tools and controls:** ANNOALLVISIBLE · viewport annotation scale · annotative objects

**Professional scenario:** Annotations visible in model space disappear from one plotted viewport.

**Decision controls:**

- Match viewport scale to the intended annotation representation
- Use all-visible only as a diagnostic
- Review blocks, hatches, text, leaders and dimensions
- Lock approved viewports after validation

**Acceptance evidence:** The viewport shows the intended objects at consistent paper sizes without diagnostic overrides.

**Primary risk:** Leaving all-visible enabled masks missing scale assignments.

#### 2.3 - Add annotations to designs

##### 2.3.a - Create and modify text, multileaders and dimensions

**Tools and controls:** MTEXT · MLEADER · DIM · grips

**Professional scenario:** A fabrication detail needs dimensions, a finish note and a callout to a remote feature.

**Decision controls:**

- Choose the annotation type by communication purpose
- Anchor dimensions to real geometry
- Keep leader landing and reading order clear
- Edit content without breaking style governance

**Acceptance evidence:** Each annotation type carries the right meaning and remains associative and readable.

**Primary risk:** Using text as a substitute for measured or linked annotation weakens revision reliability.

##### 2.3.b - Create and modify tables

**Tools and controls:** TABLE · data extraction · data links

**Professional scenario:** A room schedule combines controlled headings with values maintained in a spreadsheet.

**Decision controls:**

- Choose manual, extracted or linked data by ownership
- Use row and column structure that supports review
- Preserve style while inserting or deleting cells
- Refresh linked content before issue

**Acceptance evidence:** The table communicates source ownership and refreshes without losing formatting.

**Primary risk:** Copy-pasted values become stale while still looking authoritative.

### Domain 3 - Author and Edit Drawing Content

#### 3.1 - Reuse and leverage existing design content

##### 3.1.a - Create, manage and edit block definitions

**Tools and controls:** BLOCK · BEDIT · ATTDEF · ATTSYNC

**Professional scenario:** A door symbol needs one governed definition and instance-specific asset data.

**Decision controls:**

- Define a stable base point and insertion behaviour
- Use ByLayer and ByBlock intentionally
- Attach attributes only to data-bearing instances
- Synchronize changed attribute definitions safely

**Acceptance evidence:** All inserts share the approved geometry while attributes retain correct values after definition changes.

**Primary risk:** Redefinition without attribute synchronization leaves inconsistent instances.

##### 3.1.b - Write blocks or objects to an external drawing

**Tools and controls:** WBLOCK · base point · source selection

**Professional scenario:** A tested equipment assembly must become a reusable library component.

**Decision controls:**

- Decide between block source and selected objects
- Choose a meaningful world-space base point
- Set destination units and ownership
- Validate the exported file independently

**Acceptance evidence:** The external DWG inserts at the expected scale, orientation and reference point.

**Primary risk:** A poor base point or unit mismatch makes every future insertion corrective work.

##### 3.1.c - Access blocks and block libraries

**Tools and controls:** Blocks palette · libraries · recent/favourites

**Professional scenario:** A team must insert approved furniture symbols across multiple projects.

**Decision controls:**

- Separate current-drawing blocks from governed libraries
- Use previews as navigation, not approval evidence
- Check insertion units and definition source
- Prefer one trusted definition over near-duplicates

**Acceptance evidence:** Users reach the controlled library and insert the correct definition with predictable units.

**Primary risk:** Convenient recent blocks may be outdated or project-specific.

##### 3.1.d - Use the clipboard for precise reuse

**Tools and controls:** COPYCLIP · COPYBASE · PASTEORIG · CUTBASE

**Professional scenario:** A reviewed detail must transfer to a related drawing at the same coordinates.

**Decision controls:**

- Use a base point when placement relationship matters
- Use original location for coordinated drawings
- Distinguish copy from cut ownership
- Check units and coordinate systems between files

**Acceptance evidence:** The geometry lands at the intended location with no duplicate ownership or scale shift.

**Primary risk:** Ordinary paste uses an arbitrary insertion point and invites alignment error.

#### 3.2 - Create and edit geometry

##### 3.2.a - Create arcs from direction and values

**Tools and controls:** ARC methods · centre · chord · angle · direction

**Professional scenario:** A profile arc is defined by endpoints and included angle rather than a known centre.

**Decision controls:**

- Select a construction method from known design information
- Respect clockwise and counter-clockwise direction
- Use tangency only where design intent requires it
- Verify radius, included angle and endpoints

**Acceptance evidence:** The chosen method reproduces the required curve and continuity from the available values.

**Primary risk:** Guessing a centre can create a visually plausible but dimensionally wrong arc.

##### 3.2.b - Create polylines from existing objects

**Tools and controls:** PEDIT · JOIN · PLINEGEN

**Professional scenario:** Imported boundary segments must become a reliable area and hatch boundary.

**Decision controls:**

- Join only endpoints within an understood tolerance
- Use PEDIT when line and arc segments must become one object
- Set PLINEGEN for intended linetype continuity
- Confirm open or closed status explicitly

**Acceptance evidence:** The resulting polyline is continuous, correctly closed and displays its linetype as intended.

**Primary risk:** A generous join tolerance can bridge unintended gaps and corrupt area results.

##### 3.2.c - Offset existing geometry

**Tools and controls:** OFFSET Layer · Erase · Through · Multiple

**Professional scenario:** A wall face and a clearance envelope must be derived from a controlled centreline.

**Decision controls:**

- Use distance when the separation is governed
- Use Through when a target point governs
- Choose source or current layer ownership
- Use erase and multiple only when the downstream structure is clear

**Acceptance evidence:** Offsets maintain the specified relationship and land on the intended layers.

**Primary risk:** Repeated offsets compound rounding and can produce hidden duplicate geometry.

##### 3.2.d - Define hatch boundaries and boundary sets

**Tools and controls:** HATCH · boundary set · gap tolerance · island detection

**Professional scenario:** A section hatch must fill one component while leaving holes and adjacent parts clear.

**Decision controls:**

- Limit the boundary set in dense drawings
- Use gap tolerance only for known small defects
- Choose island detection from section meaning
- Preserve associativity where geometry will change

**Acceptance evidence:** The hatch respects intended islands, remains associative and does not search irrelevant geometry.

**Primary risk:** High gap tolerance can bridge real openings and misrepresent the section.

##### 3.2.e - Manage associative rectangular, polar and path arrays

**Tools and controls:** ARRAYRECT · ARRAYPOLAR · ARRAYPATH

**Professional scenario:** Fasteners repeat around a flange while supports repeat along a curved path.

**Decision controls:**

- Choose the array type from geometric relationship
- Retain associativity for controlled repetition
- Define count, spacing, fill and alignment deliberately
- Explode only for a documented downstream need

**Acceptance evidence:** Each array exposes the parameters that govern the design pattern and updates predictably.

**Primary risk:** Exploded copies lose the design relationship and hide inconsistent spacing.

#### 3.3 - Edit geometry with grips and multifunctional grips

##### 3.3.a - Access alternate modify commands with grips

**Tools and controls:** hot grips · grip modes · shortcut menu

**Professional scenario:** A line endpoint must move while a block insert must rotate about its base point.

**Decision controls:**

- Use the selected grip as the transformation reference
- Cycle only among commands valid for the object
- Enter exact values with dynamic input
- Prefer command workflows when selection scope is ambiguous

**Acceptance evidence:** The grip action matches the object-specific control and preserves exact values.

**Primary risk:** Dragging by eye creates silent geometric error.

##### 3.3.b - Edit with multiple selected grips

**Tools and controls:** Shift-select grips · stretch sets · base grip

**Professional scenario:** A rectangular opening must widen symmetrically without moving its centreline.

**Decision controls:**

- Select grips that define the intended deformation
- Keep anchored geometry outside the active set
- Use a predictable base grip
- Check connected geometry after the edit

**Acceptance evidence:** The selected grip set produces the intended change and leaves protected geometry fixed.

**Primary risk:** An extra active grip can distort unrelated edges or break connectivity.

##### 3.3.c - Combine dynamic input and multifunctional grips

**Tools and controls:** dynamic input · multifunction grips · numeric fields

**Professional scenario:** A polyline corner requires an exact new segment length and arc conversion.

**Decision controls:**

- Read which field is active before entering a value
- Use Tab to move among geometric parameters
- Select the grip function from object intent
- Verify final properties rather than trusting cursor feedback

**Acceptance evidence:** The edit records the intended parameter values and object type.

**Primary risk:** Typing into the wrong dynamic field changes angle instead of length.

#### 3.4 - Draw and edit with precision

##### 3.4.a - Create and edit objects with dynamic input

**Tools and controls:** DYNMODE · point input · dimension input · prompts

**Professional scenario:** A rotated component must be drawn from exact length and angle values near the cursor.

**Decision controls:**

- Distinguish coordinate fields from dimension fields
- Lock or cycle fields deliberately
- Use dynamic prompts to expose command options
- Confirm values in properties after complex edits

**Acceptance evidence:** The created geometry matches the intended numerical constraints.

**Primary risk:** Visual cursor direction can conceal a negative or alternate-angle entry.

##### 3.4.b - Use object snaps and tracking

**Tools and controls:** OSNAP · overrides · OTRACK · POLAR

**Professional scenario:** A hole centre must align horizontally with one feature and vertically with another.

**Decision controls:**

- Keep running snaps limited to frequently needed points
- Use overrides for exceptional snaps
- Acquire tracking points without creating geometry
- Combine polar and object tracking only when their guides are meaningful

**Acceptance evidence:** The point is derived from exact tracked relationships and survives measurement.

**Primary risk:** Too many running snaps cause cursor capture at the wrong candidate.

##### 3.4.c - Specify absolute, relative and polar coordinates

**Tools and controls:** x,y · @dx,dy · @distance<angle

**Professional scenario:** A profile combines a surveyed start point, orthogonal steps and angled edges.

**Decision controls:**

- Use absolute coordinates for project control
- Use relative Cartesian input for orthogonal offsets
- Use relative polar input for direction and distance
- Relate all methods to the active UCS

**Acceptance evidence:** Each segment uses the coordinate method that directly represents the available design data.

**Primary risk:** Ignoring the active UCS makes correct numbers produce wrong world positions.

### Domain 4 - Configure and Manage Design Output

#### 4.1 - Configure production drawing output

##### 4.1.a - Configure and manage named page setups

**Tools and controls:** PAGESETUP · plotter · CTB/STB · plot area

**Professional scenario:** Twenty layouts must produce consistent A3 PDFs and office printer proofs.

**Decision controls:**

- Name setups by output purpose and sheet standard
- Coordinate device, paper, plot area and orientation
- Apply the approved plot-style strategy
- Test lineweights and options in preview

**Acceptance evidence:** Named setups can be applied repeatedly and produce predictable media, scale and line hierarchy.

**Primary risk:** Layout-by-layout manual settings create hidden output drift.

##### 4.1.b - Create layout viewports

**Tools and controls:** MVIEW · polygonal viewport · object viewport · Insert View

**Professional scenario:** A sheet needs one overall plan and a clipped detail around an irregular room.

**Decision controls:**

- Choose rectangular or non-rectangular boundaries from composition needs
- Create viewports only in paper space
- Use named views where repeatability matters
- Separate viewport boundary layer from plotted content

**Acceptance evidence:** The layout contains purposeful view boundaries with clear sheet ownership.

**Primary risk:** Viewports on a plotting layer can print unwanted frames.

##### 4.1.c - Manage layout viewports

**Tools and controls:** VPCLIP · lock · layer control · viewport scale

**Professional scenario:** A detail viewport must be 1:10, hide ceiling layers and remain stable through review.

**Decision controls:**

- Set and verify exact scale before locking
- Use viewport layer controls for presentation
- Clip only when composition requires it
- Match annotation scale to viewport scale

**Acceptance evidence:** Scale, lock, clip and viewport-specific visibility all survive reopen and plot preview.

**Primary risk:** Unlocked viewports are easily changed by accidental zooming.

#### 4.2 - Plot and publish production drawing output

##### 4.2.a - Define and manage a publish sheet list

**Tools and controls:** PUBLISH · DSD sheet list · page setup override

**Professional scenario:** A 24-sheet issue must produce one ordered PDF using a revised output device.

**Decision controls:**

- Order sheets for stakeholder reading
- Apply overrides only to controlled output variants
- Validate every source layout before batch output
- Save reusable sheet lists with project-relative references

**Acceptance evidence:** The sheet list, order and override yield a complete, consistent package.

**Primary risk:** One stale layout or missing setup can silently compromise the batch.

##### 4.2.b - Configure an Electronic Transmittal package

**Tools and controls:** ETRANSMIT · path options · dependency report

**Professional scenario:** A consultant must receive a portable package that opens without unresolved dependencies.

**Decision controls:**

- Include required references, fonts, plot styles and data links
- Choose path handling for the recipient environment
- Purge only when permitted
- Review the transmittal report before issue

**Acceptance evidence:** The package inventory and test-open confirm all permitted dependencies resolve.

**Primary risk:** Sending only the host DWG produces missing references and unreliable output.

#### 4.3 - Use the Sheet Set Manager

##### 4.3.a - Create sheets within a sheet set

**Tools and controls:** SHEETSET · import layout · new sheet · subsets

**Professional scenario:** A project adds four detail sheets to an existing discipline subset.

**Decision controls:**

- Use subsets to express package structure
- Import only layouts that meet sheet standards
- Create new sheets from governed templates
- Maintain unique sheet numbers and names

**Acceptance evidence:** The new sheets appear in the correct subset with controlled names, numbers and layout sources.

**Primary risk:** Ad-hoc layouts outside the sheet set evade package coordination.

##### 4.3.b - Modify sheet and sheet-set properties

**Tools and controls:** Sheet Set Manager · custom properties · renumbering

**Professional scenario:** A project phase and issue date change across every title block while two sheets are renumbered.

**Decision controls:**

- Distinguish sheet properties from set-wide properties
- Use properties as field sources
- Renumber with downstream references in mind
- Regenerate lists and title data after changes

**Acceptance evidence:** Fields and sheet lists update from governed properties without manual title-block edits.

**Primary risk:** Manual text overrides leave contradictory issue data.

### Domain 5 - Collaboration

#### 5.1 - Provide design feedback

##### 5.1.a - Collaborate with shared drawing files

**Tools and controls:** SHARE · shared views/files · permissions

**Professional scenario:** A client needs browser-based review without receiving editable production files.

**Decision controls:**

- Choose a share method that protects source ownership
- Control who can view, comment or edit
- Communicate revision and expiry context
- Avoid exposing unrelated project data

**Acceptance evidence:** The shared artifact has appropriate access, scope and revision identification.

**Primary risk:** Over-sharing production data creates ownership and confidentiality risk.

##### 5.1.b - Create and manage Traces

**Tools and controls:** TRACE · Trace palette · contributor workflow

**Professional scenario:** A reviewer marks routing changes while the drafter continues production work.

**Decision controls:**

- Use a trace as an overlay, not source-geometry replacement
- Separate contributor feedback from author response
- Resolve or retain feedback with status
- Keep the base drawing authoritative

**Acceptance evidence:** The trace preserves reviewer intent and can be resolved without contaminating base geometry.

**Primary risk:** Redrawing feedback directly into the model loses provenance.

##### 5.1.c - Compare drawing versions

**Tools and controls:** DWGCOMPARE · import differences · filters

**Professional scenario:** Two consultant revisions arrive with unclear change notes.

**Decision controls:**

- Choose the correct baseline and revision
- Filter non-material differences
- Inspect added, removed and changed objects
- Import only approved changes and document the decision

**Acceptance evidence:** The comparison identifies material changes and records which are accepted.

**Primary risk:** Comparing the wrong versions creates false confidence and missed change.

#### 5.2 - Manage references and underlays

##### 5.2.a - Manage xref attach and overlay types

**Tools and controls:** XATTACH · Attach · Overlay

**Professional scenario:** A discipline model must appear in the coordination host but not propagate into every downstream sheet.

**Decision controls:**

- Use Attach when nested propagation is intended
- Use Overlay to prevent nesting beyond one host
- Choose type from coordination ownership
- Review the reference tree for circular risk

**Acceptance evidence:** The reference type produces the intended nesting behaviour with no duplication.

**Primary risk:** Incorrect Attach use can duplicate references or create circular relationships.

##### 5.2.b - Manage reference paths and path types

**Tools and controls:** Reference Manager · full · relative · no path

**Professional scenario:** A project folder must move from a local drive to a shared server and later into eTransmit.

**Decision controls:**

- Use relative paths inside portable project structures
- Use full paths only for stable shared infrastructure
- Use no path when controlled search locations suffice
- Repath and reload before package issue

**Acceptance evidence:** References resolve after relocation using an intentional, documented path strategy.

**Primary risk:** Machine-specific full paths fail for collaborators.

##### 5.2.c - Manipulate image and underlay frames

**Tools and controls:** IMAGEFRAME · PDFFRAME · DWF/DGN frames · clip

**Professional scenario:** A scanned survey underlay must be selectable while authoring but print without its frame.

**Decision controls:**

- Control display and plot behaviour separately
- Keep frames visible during editing when selection is needed
- Clip to the useful evidence area
- Retain enough boundary context for interpretation

**Acceptance evidence:** The underlay remains manageable and plots with the intended boundary treatment.

**Primary risk:** Hidden frames can make references impossible to select or audit.

#### 5.3 - Incorporate external design data into project drawings

##### 5.3.a - Create and manage PDF imports

**Tools and controls:** PDFIMPORT · layers · vector geometry · raster images

**Professional scenario:** A legacy vector PDF must seed editable geometry for a renovation plan.

**Decision controls:**

- Assess whether the PDF contains usable vectors
- Map or create layers intentionally
- Join collinear segments only when safe
- Treat imported geometry as untrusted until checked

**Acceptance evidence:** Imported objects have verified scale, layers, linework and text treatment.

**Primary risk:** Assuming the PDF is dimensionally exact can propagate scan or export distortion.

##### 5.3.b - Create and manage tables using data links

**Tools and controls:** DATALINK · TABLE · Excel link · update

**Professional scenario:** A drawing schedule must reflect a controlled spreadsheet maintained by procurement.

**Decision controls:**

- Define which system owns each value
- Control ranges, formatting and update direction
- Protect linked cells from casual overrides
- Refresh and record source state before issue

**Acceptance evidence:** The linked table refreshes the intended range and preserves readable drawing formatting.

**Primary risk:** Broken paths or unrefreshed links publish stale data.

##### 5.3.c - Display dynamic data using fields

**Tools and controls:** FIELD · object properties · custom properties · sheet-set fields

**Professional scenario:** Title blocks and callouts must show sheet properties, areas and issue dates without retyping.

**Decision controls:**

- Choose a stable data source
- Use fields for values that must follow revisions
- Format units, case and precision consistently
- Update and inspect fields before output

**Acceptance evidence:** Displayed values update from their authoritative objects or properties.

**Primary risk:** Converted-to-text or broken fields retain old values while appearing valid.

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
- `Furniture_Floor_Plan.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Furniture_Floor_Plan.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Furniture_Floor_Plan.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Furniture_Floor_Plan.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Furniture_Floor_Plan.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Furniture_Block_Attributes.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Sink_Layouts.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A1 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A2 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A3 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Sink_Layouts.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A1 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A2 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A3 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Furniture_Floor_Plan.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `Sink_Layouts.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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
- `Sink_Layouts.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `Furniture_Block_Attributes.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A1 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A2 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ISO A3 title block.dwg` - supplied AutoCAD working/source file or technical drawing reference.

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

### Lab 11 - Drawing Environment, UCS and Recovery

**Mapping:** LO1–LO2 · Exam 1.2, 1.4, 1.5 · K1–K2 · A1–A2

**Scenario:** Configure a portable professional workspace, establish named coordinate systems and recover a controlled revision from supplied drawing files.

**Outcome:** A documented AutoCAD workspace and UCS set plus a recovered, audited and versioned drawing.

**Tools:** AutoCAD · CUI · WSCURRENT · UCS · UCSMAN · RECOVER · DRAWINGRECOVERY

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `workspaces.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `drafting-settings.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `Environment.dwg` - supplied AutoCAD working/source file or technical drawing reference.

#### Detailed procedure

1. Open the workspace and drafting-settings samples; record the interface controls that support precision review.

   **Command / tool:** `WSCURRENT · DSETTINGS`

2. Create a project workspace that exposes Properties, Layers and External References without obscuring the model.

   **Command / tool:** `CUI · palettes`

3. Open Environment.dwg and confirm units, world origin and a known reference dimension.

   **Command / tool:** `UNITS · ID · DIST`

4. Create a named UCS aligned to an angled workface and restore it after returning to World UCS.

   **Command / tool:** `UCS · UCSMAN · PLAN`

5. Save a controlled working revision, close it and verify the named UCS and workspace state on reopen.

   **Command / tool:** `SAVEAS`

6. Create a safe test copy and run AUDIT; record the number and type of errors found.

   **Command / tool:** `AUDIT`

7. Compare AUDIT, RECOVER and RECOVERALL and select the appropriate recovery scope for the supplied scenario.

   **Command / tool:** `RECOVER · RECOVERALL`

8. Inspect Drawing Recovery Manager and identify DWG, BAK and SV$ candidates by timestamp and source path.

   **Command / tool:** `DRAWINGRECOVERY`

9. Save the chosen recovery result under a new revision name without overwriting the approved file.

   **Command / tool:** `SAVEAS`

10. Capture workspace, UCS, audit log and recovered-file evidence in the checklist.

   **Command / tool:** `Evidence screenshots`


#### Verification and acceptance

The workspace and named UCS restore correctly; the recovered revision is current, opens cleanly and preserves the approved source.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-11-drawing-environment-ucs-and-recovery/`

### Lab 12 - Annotation Styles, Scales and Schedules

**Mapping:** LO3 · Exam 2.1–2.3 · K3 · A3

**Scenario:** Apply a complete annotation governance system to a technical component sheet and validate every representation in paper space.

**Outcome:** A dimensioned and annotated component sheet with named styles, scale-aware objects and a controlled schedule.

**Tools:** AutoCAD · STYLE · DIMSTYLE · MLEADERSTYLE · TABLESTYLE · OBJECTSCALE · ANNORESET

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `ex8.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ex8-drawing-sheet.pdf` - supplied AutoCAD working/source file or technical drawing reference.
- `title-block.dwg` - supplied AutoCAD working/source file or technical drawing reference.

#### Detailed procedure

1. Open ex8.dwg and compare its visible annotations with the dimensioned drawing sheet.

   **Command / tool:** `OPEN · visual audit`

2. Create named text, dimension, multileader and table styles using one coordinated paper-height policy.

   **Command / tool:** `STYLE · DIMSTYLE · MLEADERSTYLE · TABLESTYLE`

3. Apply linear, aligned, radial, diameter and angular dimensions to the governed geometry.

   **Command / tool:** `DIM`

4. Create concise multileader callouts and align their landings for a deliberate reading order.

   **Command / tool:** `MLEADER · MLEADERALIGN`

5. Assign required 1:20, 1:10 and 1:5 scales only to the annotative objects that need them.

   **Command / tool:** `OBJECTSCALE`

6. Adjust one scale-specific position to avoid a collision, then synchronize another using ANNORESET.

   **Command / tool:** `annotative grips · ANNORESET`

7. Create a schedule with title, header and data cell styles; populate it from controlled drawing values.

   **Command / tool:** `TABLE`

8. Insert the supplied title block and populate live properties with fields where appropriate.

   **Command / tool:** `INSERT · FIELD`

9. Review all target scales through locked paper-space viewports and disable diagnostic all-visible mode.

   **Command / tool:** `ANNOALLVISIBLE · viewport scales`

10. Plot-preview the final sheet and retain style, scale and schedule evidence.

   **Command / tool:** `PLOT Preview`


#### Verification and acceptance

All annotation types are style-governed, scale positions are intentional and the plotted schedule and callouts remain readable.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-12-annotation-styles-scales-and-schedules/`

### Lab 13 - Coordinate Geometry and Construction Objects

**Mapping:** LO1–LO2 · Exam 3.2, 3.4 · K1–K2 · A1–A2

**Scenario:** Construct a mixed technical profile from exact coordinates, arcs, polylines and construction geometry, then validate its measurable relationships.

**Outcome:** A closed, dimensionally verified profile combining Cartesian and polar input with appropriate object types.

**Tools:** AutoCAD · LINE · PLINE · ARC · XLINE · OSNAP · OTRACK · MEASUREGEOM

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `ex1.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ex1-drawing-sheet.pdf` - supplied AutoCAD working/source file or technical drawing reference.
- `ex3.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ex3-drawing-sheet.pdf` - supplied AutoCAD working/source file or technical drawing reference.

#### Detailed procedure

1. Read the supplied drawing sheets and identify which values are absolute coordinates, offsets, distances and angles.

   **Command / tool:** `drawing interpretation`

2. Establish the start point in World UCS and create the first controlled segment with absolute input.

   **Command / tool:** `LINE · x,y`

3. Continue orthogonal features using relative Cartesian coordinates.

   **Command / tool:** `@dx,dy`

4. Create angled features using relative polar input and verify direction against the active UCS.

   **Command / tool:** `@distance<angle`

5. Use object-snap tracking and polar tracking to derive intersections without adding permanent geometry.

   **Command / tool:** `OTRACK · POLAR`

6. Create the curved features with the arc method that matches the supplied centre, chord or angle information.

   **Command / tool:** `ARC`

7. Join eligible segments into a polyline and verify open/closed state and linetype generation.

   **Command / tool:** `PEDIT · JOIN · PLINEGEN`

8. Use xlines or rays on a non-plotting construction layer to project aligned features.

   **Command / tool:** `XLINE · RAY`

9. Measure distance, angle, radius and area and compare against the drawing sheets.

   **Command / tool:** `MEASUREGEOM`

10. Save the completed profile and retain a discrepancy log for any corrected source interpretation.

   **Command / tool:** `SAVEAS`


#### Verification and acceptance

Coordinate methods, arc construction and object types match the supplied information; the final profile closes and measures correctly.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-13-coordinate-geometry-and-construction-objects/`

### Lab 14 - Associative Arrays and Grip-Based Revision

**Mapping:** LO2 · Exam 3.2.e, 3.3 · K2 · A2

**Scenario:** Build repeatable rectangular, polar and path patterns and revise compound geometry with multiple and multifunctional grips.

**Outcome:** An associative pattern study and a revised technical component with documented grip decisions.

**Tools:** AutoCAD · ARRAYRECT · ARRAYPOLAR · ARRAYPATH · grips · dynamic input

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `ex6.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ex6-drawing-sheet.pdf` - supplied AutoCAD working/source file or technical drawing reference.
- `ex7.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `sawblade.dwg` - supplied AutoCAD working/source file or technical drawing reference.

#### Detailed procedure

1. Open ex6.dwg and identify rectangular, radial and path-governed repetition in the design.

   **Command / tool:** `pattern analysis`

2. Create a rectangular associative array with controlled rows, columns and spacing.

   **Command / tool:** `ARRAYRECT`

3. Create a polar associative array and verify centre, item count, fill angle and rotation behaviour.

   **Command / tool:** `ARRAYPOLAR`

4. Create a path array and compare Divide and Measure distribution methods.

   **Command / tool:** `ARRAYPATH`

5. Change each array through its properties and confirm every instance updates as one governed set.

   **Command / tool:** `Properties · array grips`

6. Open sawblade.dwg and reverse-engineer its polar-array parameters from visible evidence.

   **Command / tool:** `Properties`

7. Open ex7.dwg and use one hot grip to cycle Stretch, Move, Rotate, Scale and Mirror modes.

   **Command / tool:** `grip modes`

8. Select multiple grips to revise a symmetric feature while preserving its centreline.

   **Command / tool:** `Shift-select grips`

9. Combine multifunctional grips with dynamic input to set exact lengths, angles or curve states.

   **Command / tool:** `dynamic input`

10. Verify geometry, retain associativity and explain why no array was exploded.

   **Command / tool:** `LIST · Properties`


#### Verification and acceptance

All arrays remain associative with correct parameters; grip edits are exact and protected geometry remains unchanged.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-14-associative-arrays-and-grip-based-revision/`

### Lab 15 - Named Page Setups, Sheet Sets and Batch Output

**Mapping:** LO3–LO4 · Exam 4.1–4.3 · K3–K4 · A3–A4

**Scenario:** Govern a multi-sheet production package through named page setups, controlled viewports, Sheet Set Manager properties and batch publishing.

**Outcome:** A governed office drawing sheet set with reusable page setups, sheet metadata and a verified batch PDF.

**Tools:** AutoCAD · PAGESETUP · MVIEW · SHEETSET · PUBLISH · ETRANSMIT

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `new-office-layout.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `title-block.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `Metal Plate_FINAL.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `Metal Plate_ISO A3.dwt` - supplied AutoCAD working/source file or technical drawing reference.

#### Detailed procedure

1. Open the office and metal-plate files and record each required sheet size, scale and output purpose.

   **Command / tool:** `sheet brief`

2. Create named PDF and proof-print page setups that coordinate device, media, plot area, scale and plot style.

   **Command / tool:** `PAGESETUP`

3. Compose rectangular and non-rectangular viewports and place their frames on a non-plotting layer.

   **Command / tool:** `MVIEW · VPCLIP`

4. Set exact viewport and annotation scales, apply sheet-specific layer overrides and lock approved views.

   **Command / tool:** `viewport properties`

5. Create a sheet set with discipline subsets and import only compliant source layouts.

   **Command / tool:** `SHEETSET`

6. Populate set-wide and sheet-specific properties and display them through title-block fields.

   **Command / tool:** `Sheet Set Manager · FIELD`

7. Renumber two sheets and verify the title block and sheet-list table update.

   **Command / tool:** `sheet properties`

8. Build and save an ordered publish sheet list with the approved page-setup override.

   **Command / tool:** `PUBLISH · DSD`

9. Publish the batch PDF and inspect every page for clipping, scale, lineweight, references and revision.

   **Command / tool:** `PUBLISH · PDF review`

10. Create an eTransmit package and open-test it from the packaged location.

   **Command / tool:** `ETRANSMIT`


#### Verification and acceptance

Named setups and sheet properties drive consistent output; the ordered PDF and portable package pass every review check.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-15-named-page-setups-sheet-sets-and-batch-output/`

### Lab 16 - Shared Review, References and Linked Data

**Mapping:** LO4–LO5 · Exam 5.1–5.3 · K4 · A4–A5

**Scenario:** Coordinate a shared drawing review using Traces and Compare, repair portable references, import PDF geometry and connect tables and fields to governed data.

**Outcome:** A reviewed host drawing with trace evidence, controlled references, verified PDF import and live linked data.

**Tools:** AutoCAD · TRACE · DWGCOMPARE · XREF · PDFIMPORT · DATALINK · FIELD

#### Supplied files

- `lab-reference.jpg` - JPEG visual brief and checking image.
- `new-office-layout-with-xref.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `Landscaping_REV1.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `ex1-drawing-sheet.pdf` - supplied AutoCAD working/source file or technical drawing reference.
- `New Office Proposal_REV1.dwg` - supplied AutoCAD working/source file or technical drawing reference.
- `New Office Proposal_REV2.dwg` - supplied AutoCAD working/source file or technical drawing reference.

#### Detailed procedure

1. Open the host drawing and verify the reference tree, ownership prefixes and saved path types.

   **Command / tool:** `XREF`

2. Repair any unresolved link with a relative path and verify portability from the lab folder.

   **Command / tool:** `Change Path · Reload`

3. Create a controlled review trace that records two stakeholder comments without changing source geometry.

   **Command / tool:** `TRACE`

4. Compare the two office proposal revisions and classify added, removed and modified objects.

   **Command / tool:** `DWGCOMPARE`

5. Record which differences are accepted, rejected or require stakeholder clarification.

   **Command / tool:** `review decision log`

6. Attach the drawing-sheet PDF, control its frame and clip, then assess whether its vectors are suitable for import.

   **Command / tool:** `PDFATTACH · PDFFRAME`

7. Import a controlled area and verify scale, layers, linework and text treatment before reuse.

   **Command / tool:** `PDFIMPORT`

8. Create a data link to a controlled schedule source and insert the linked range as a table.

   **Command / tool:** `DATALINK · TABLE`

9. Add fields for one object property and one drawing or sheet property; update and inspect them.

   **Command / tool:** `FIELD · UPDATEFIELD`

10. Package the host, references and permitted linked evidence and complete the collaboration audit trail.

   **Command / tool:** `ETRANSMIT`


#### Verification and acceptance

Review provenance remains visible, references survive relocation and all imported or linked data is verified against its authoritative source.

- Save the final DWG using the learner's initials and a revision identifier.
- Capture the relevant setting and visible result in the same evidence sequence.
- Complete the lab evidence checklist before submission.

> Full printable guide, checklist and files: `labs/lab-16-shared-review-references-and-linked-data/`

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
