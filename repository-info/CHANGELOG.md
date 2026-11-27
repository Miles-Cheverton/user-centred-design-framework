# Changelog

## Updating an existing project

When a future release requires an upgrade, follow its release notes and the target starter’s [upgrade guidance](../framework-template/how-to/README.md#upgrade-an-existing-project).

## 0.6.1 — 2026-11-27 — project-boundary fix

- All six AI skills start by reading the intended project's `_project-config.md` and resolving its **Working folder** using an exact path or URL. Identical filenames and record IDs do not identify the same project.
- Skills verify actual source and destination locations, reject out-of-project or unverified retrieval results, and report missing evidence rather than searching elsewhere. Explicitly authorised external records and supplied-file tasks remain supported.
- Added practical SharePoint/Copilot setup guidance and a cross-project isolation test. The instructions reduce the risk of mixing evidence between projects; they are not a technical access boundary.

A disposable two-project test used identical filenames and IDs with different content. The correct project was used, unrelated results were rejected, and authorised saves affected only the intended records. The existing evidence quick test and all local links passed. Live Copilot/SharePoint behaviour still needs testing.

This is a guidance-only update. Existing project workbooks and folder structure do not change. Refresh the AI skills and guidance, preserving local adaptations and the working folder in project config.

## 0.6.0 — 2026-11-27 — peer review release

- Consolidated related records while keeping distinct meanings, IDs and evidence links: scope, project people, outcomes and measures, research planning, design artefacts and requirements. The starter has 20 record workbooks and one document tracker.
- Simplified the human guidance, project configuration and six AI skills; removed individual skill revision checks and repeated administration. The tracker remains the authoritative location of live records.
- Cleared fictional starter rows, retaining example identifiers in workbook guidance. Kept four provisional user-need fulfilment totals and moved detailed checks to the integrity skill; added clearer definitions and fixed first-capture counting.
- Added actual user groups represented in research sessions, consistent successor fields for superseded records, and a way to identify constraints that no longer apply. Improved evidence, dependency, decision and overlap guidance.
- Improved skill portability, lightweight structural audits, evidence-impact checks and optional standards-based briefings. Clarified framework-owned guidance and templates versus project-owned records when upgrading.
- Moved reusable research and journey templates away from live record locations. Teams copy only the material they need.

Regression checked on disposable projects: all 24 Excel files opened in LibreOffice; fulfilment totals recalculated against empty, valid and deliberately faulty records; capture/import saves, independent integrity/evidence checks, template links and a guidance-only upgrade rehearsal passed. Desktop Excel, SharePoint and live Claude/Copilot integrations still need peer testing.

This release changes some starter filenames, columns and locations. Use the new starter for a new project. For existing projects, preserve real records and local adaptations; reconcile affected record owners and fields before replacing any guidance or workbook.

## 0.5.5 — 2026-11-26 — peer review release

- Added an Excel document tracker for the current location of project records and additional files. Teams can move a starter record by updating its tracker entry. The guides and skills use the tracker to locate records.
- Added Withdrawn to user needs, research questions, business rules and non-functional requirements. Extended evidence withdrawal and integrity checks to observations and dependent records, including research questions whose answers lose their support.
- Strengthened the fulfilment totals and workbook warnings for incomplete assessments, malformed or repeated IDs, invalid delivery choices and rows partly pasted outside tables. Withdrawn needs are excluded from active totals.
- Clarified how to check the current service version, the roles represented during research, the date and resolution of pending changes, and the alignment of team-added Excel columns. Skills check for matching guidance revisions before saving project changes.
- Added focused research, design testing and decision review diagrams to the repository README and expanded guidance on meeting recordings, hypotheses and delivery handovers.
- Updated the [v0.5.5 upgrade instructions](https://github.com/Miles-Cheverton/user-centred-design-framework/blob/v0.5.5/framework-template/how-to/README.md#upgrade-an-existing-project) for populated and adapted projects, preserving existing records and local workbook additions.

The audit fixes were checked on a fictional discovery-to-beta project. All 29 Excel files opened, 11 workbook stress tests passed in LibreOffice, and local document links, upgrade rehearsals and independent Codex handover and revision-mismatch tests passed. Live Excel, SharePoint, Claude and Copilot operation remains to be tested.

## 0.5.4 — 2026-11-24 — peer review release

- Clarified how withdrawn findings affect current evidence, and where to carry unsaved changes between sessions.
- Added a check for rows outside the Findings and Observations table and strengthened the quick test and in-place upgrade instructions. [v0.5.4 upgrade steps](https://github.com/Miles-Cheverton/user-centred-design-framework/blob/v0.5.4/framework-template/how-to/README.md#upgrade-an-existing-project)

## 0.5.3 — 2026-11-24 — peer review release

- Added team-owned conventions in project config, an adaptation guide and upgrade checks for keeping skills and guidance together.
- Updated user needs totals and warnings for repeated or missing IDs, incomplete rows and invalid pasted values.
- Made cross-session handovers explicit and labelled the quick-test rows as fictional.
- Added Withdrawn to the Findings and Observations workbook. Keep the finding’s ID, reason and source. Follow the [v0.5.3 upgrade guide](https://github.com/Miles-Cheverton/user-centred-design-framework/blob/v0.5.3/framework-template/how-to/README.md#upgrade-an-existing-project) to add the status to an existing workbook.

## 0.5.2 — 2026-11-24 — peer review release

- Added workbook warnings for user need rows outside the table and status or fulfilment values that need checking. Tightened the integrity check and made save results explicit when skills pass work to one another.
- Clarified how to report findings, delivery intent and fulfilment evidence. Added a fictional quick test that reads a separate notes file and checks which skill revision is active.
- Included the upgrade checklist in the starter itself. Follow the [v0.5.2 file list for v0.5.1 and v0.4](https://github.com/Miles-Cheverton/user-centred-design-framework/blob/v0.5.2/framework-template/how-to/README.md#files-to-update-from-v051). Keep populated workbooks and add the optional warning formulas to an existing user needs workbook using the instructions.

## 0.5.1 — 2026-11-23 — updates to AI skills

- All six AI skills now draw on shared guidance for user researchers, content designers, UX designers, service designers, business analysts, product owners, delivery managers and developers. They connect evidence across disciplines, explain trade-offs when asked for advice and distinguish team decisions from recommendations.
- Teams can specify their service standards and delivery approach. The skills check which GDS, international or agile guidance applies to the question.
- Research debrief and meeting examples show how the assistant checks sources after people have discussed the evidence. The assumptions guide shows how to test a hypothesis. Importing a project now excludes the destination from a wider source folder.

### Upgrading from v0.4

1. From the new starter, copy `AI-skills/`, `ai-guidance.md`, `how-to/README.md` and `how-to/files/assumptions.md` into your project. Merge any guidance your team has customised. If you installed separate copies of the skills, refresh those copies too.
2. Merge the starter’s `README.md` and `project-config.md` with your own. Keep the project name, owner and existing locations. Set the starter version to v0.5.1. Add your standards and delivery approach if useful.
3. Keep your existing workbooks and project records. The workbook fields, IDs and folder structure are the same as in v0.4. Run the quick test in `AI-skills/README.md` with an untouched starter workbook to check the setup.

## 0.4 — 2026-11-23 — peer review release

The downloadable starter is the contents of `framework-template/`. The handbook and AI skills live inside it. The licence, release history and sources are in `repository-info/` in the full repository.

### Using the revised starter

- Record team conclusions (FND) and independently citable observations (EV) in `findings-and-observations.xlsx`.
- Keep one current fulfilment assessment per user need. Record differences by channel, group or tested version in **Scope and evidence**.

- Start with the task in the handbook. Workbooks have one **OVERWRITE ME** example inside the table. The example does not count as a live record.
- Set shared locations in `project-config.md`. Choose an AI skill for finding information, documenting agreed work, checking records, preparing a briefing or importing earlier project material. The skills guide includes a common setup test.
- Keep significant design choices and discarded alternatives in Decisions. Link to exact journey and prototype versions. A prototype can stay in an approved tool or a local folder.
- Each research round has one protocol for the plan, materials and human debrief. Retain instruments, source exports, calculations, notes and board snapshots where they can be cited. Recordings and transcripts can stay in approved storage. A comparative session can cite several exact prototype versions.

### Checks and fixes in this release

- Workbook rows expand for long evidence and rationale. Controlled lists reject invalid labels entered directly. When adding records, include them in the named table and check the fulfilment totals against its rows after recalculation.
- The shared AI setup test traces a fictional need to its two sources and checks the empty starter separately. Research and briefing guidance retains disagreements, notes-only sources and unanswered questions.
- Worked examples distinguish booking outcomes from evidence of user understanding. The round protocol asks who recruitment might have missed, including people outside the planned groups.
- Read-only questions, partial or repeated saves, and importing existing material use the same source and ID rules. The guidance explains how to preserve an open design option, a withdrawn source and a superseded rule.

### Upgrading from v0.3.7 or earlier

Work on a copy. Keep the previous version and its source files available until you have checked the new records. Preserve IDs, evidence locations, dates, uncertainty and earlier decisions. Where a column has gone, carry its meaning into the relevant record or link to the retained detail. Check a finding, need and decision end to end before using the new copy.

| Earlier record | Where to carry the information |
|---|---|
| Evidence workbook and Markdown research findings | Use `findings-and-observations.xlsx`. Keep EV and FND IDs distinct. Put the observation or conclusion, exact source version, locator, contrary evidence and limits on the corresponding row. |
| User needs and separate coverage workbook | Match each assessment to its UN ID in `user-needs.xlsx`. Include the old purpose in **Need**. Carry **Assessment** to **Fulfilment** and retain the separate **Delivery decision**. Put the assessed scope, gaps, date, evidence and DEC IDs in **Scope and evidence**. Reconcile unmatched and duplicate IDs before using the totals. |
| Markdown decisions, measures and use cases | Use one row per DEC, MET or UC ID in the corresponding workbook. Carry over decision reasons, alternatives, outcome links, source references and any access or exception paths. Retain version history. |
| Standalone design proposals and older design indexes | Carry forward open options as well as cited or discarded ones. For example, keep the original PROP ID, user need and unanswered test question for a proposed call-handler waiver in a versioned design note. Link it from a Proposed DEC when the team is considering a choice. Link the eventual decision to the retained options and exact design versions. Carry the context, limits, text equivalents and source links into retained version notes or artefacts as appropriate. |
| Document register and project background | Keep the DOC IDs in `project-sources/source-register.xlsx`. Preserve the author or supplier, authority, currency and limits in **Description** where they affect use. Retain the exact version and location relied on. |
| Research plan, sessions and survey working | Carry method, dates and lead into the round protocol. Combine recording and notes references without losing individual links. Keep existing transcript versions and consent references. A single existing **Prototype version** is a valid entry under **Prototype versions**. Preserve group filters and calculation limits in the survey working. |
| Other shortened registers | Keep scope decision IDs in **Why**, conditional behaviour, known or unresolved exceptions and all successor BR IDs on the old row in **Rule**, and constraint change conditions with the constraint. Keep the assessment date, evidence and successor ASM IDs with the original assumption. Preserve current controls and next actions in the risk **Response**, and NFR verification results, scope and evidence in **Verification**. Carry the former NFR replacement IDs into **Requirement** and any relevant UN IDs into **Source**. Keep responsibilities, successor links and other material detail in the owning record or its linked project source. |
| Folders and external files | Existing material can stay where it is. If you move a file, verify all historical citations against the retained version, including path strings in workbooks. Keep participant identities and consent evidence in their approved restricted locations. |

## 0.3.7 — 2026-11-22 — draft for review

- Published the full revised README, including the framework’s purpose, principles, benefits and two examples of proposed skills.

## 0.3.6 — 2026-11-22 — draft for review

- Used the same opening in the GitHub description and repository README.

## 0.3.5 — 2026-11-22 — draft for review

- Explained why the framework exists in the GitHub README and the downloadable template. The getting-started guides link to that explanation.

## 0.3.4 — 2026-11-19 — draft for review

- Added a short guide to getting started and improved the skills for recording discussions and findings and checking project records.
- Renamed the framework guidance folder and removed the simulation, contribution guide and AI usability evaluation from the working tree.

## 0.3.3 — 2026-11-17 — draft for review

- Extended the journey guidance and description to support service blueprints, process maps, actor maps and information flows using the existing register. Label prescribed process, observed practice and proposed future where relevant.
- Added a fictional handoff example linking an exact model stage to a finding, its source, a playback claim, a decision and an open outcome. It also shows cross-round coverage, an external source and a consequential problem reframing.
- Added an optional non-identifying activity label to research-session filenames. Existing filenames, worksheet fields and IDs remain valid.

## 0.3.2 — 2026-11-16 — draft for review

### Added

- Optional research-round companions for discussion guides, survey questionnaires, original responses, working calculations, human analysis notes and Whiteboard references.
- Blank survey-response and survey-analysis workbooks. Native survey exports may remain in their original format; no conversion or manual re-entry is required.
- The confirmed CC BY 4.0 licence, copyright 2026 Miles Cheverton, replacing the previous licence proposal. See the [full licence text](LICENSE). The template carries a short attribution notice.

### Changed

- Guidance and existing skills now distinguish instruments from results, preserve questionnaire and dataset versions, and retain calculation methods, filters, denominators and missing-response treatment.
- Whiteboard guidance retains the live reference and meaningful snapshots alongside human-authored analysis, with explicit coverage and access limits. Boards remain with the research or design activity they support.
- Cited datasets and board snapshots use the existing DOC/EV source relationships. Human discussion and interpretation remain prerequisites to recording findings; AI can perform specified calculations, source checks and faithful documentation.

### Migration

No central register, global ID or existing workbook column changes are required. Add only the round companions useful to the work. Preserve original exports and significant retained versions; do not manufacture historic question mappings, snapshots, respondent identities or human analysis. Existing recordings and transcripts keep their established folders.

## 0.3.1 — 2026-11-16 — draft for review

### Changed

- Made human critical thinking, research analysis and conclusions an explicit prerequisite to AI documentation throughout entry points, research guidance, prompts and skills. AI may tidy established human conclusions, check sources, flag discrepancies and record faithfully; Draft status does not authorise AI synthesis.
- Structured the existing research protocol around human analysis, known synthesis gaps and actual coverage. No additional register, approval log or meeting is required.
- Added a task-based handover route and practical examples for ambiguous agreement, whole-service need coverage, exact design versions, disposable sketches and mixed authority in supplied documents.
- Prioritised decision-changing gaps in integrity reporting, retained dissent and clarified the boundary between source checks and human judgement.
- Revised the fictional role-play to demonstrate these working rules. Its results remain simulated; historical technical checks are not relabelled as tests of this revision.

### Migration

No workbook schema, ID or folder migration is needed. Apply the updated guidance and skills. Existing human findings remain valid records; an AI-originated interpretation does not become a human finding merely by relabelling it. If such material is encountered, preserve its provenance, identify the uncertainty and let the team perform the substantive analysis before relying on it. Do not invent historical review or require re-approval of conclusions people have already reached.

## 0.3.0 — 2026-11-16 — draft for review

### Changed

- Added task-based starting routes, short capture steps and staged completion requirements. Precise definitions remain available as reference.
- Made complete retention of substantive findings, contradictory evidence, unmet needs and significant decisions explicit.
- Removed manually maintained Finding IDs lists from research questions, research rounds and prototype registers. Findings now own question, round/session and exact design-version links.
- Removed duplicated mutable metadata from prototype descriptions and unnecessary reverse links from related records.
- Defined when exploratory journeys and prototypes become retained records: research, consequential decisions, substantive shared review or handover.
- Kept framework maintenance and fictional evaluations separate from ordinary project use.

### Added

- Portable Markdown skills for extracting and maintaining project records, including an integrity check-and-repair procedure with explicit authority and evidence boundaries.
- A use-cases narrative template and guide for describing specific service interactions when useful. This is an optional framework concept, not a prescribed GDS artefact.
- A user-need-coverage workbook and guide, separating assessment of fulfilment from delivery decisions. Formula summaries count recorded assessment rows; they do not establish completeness against the separate user-needs register.
- A research-informed fictional team simulation covering 18 discovery, alpha and beta situations, with a prioritised assessment and explicit limits. SharePoint simultaneous editing is a settled scenario assumption.
- Recorded 0.3.0 calculation checks and an isolated integrity-skill repair test, kept distinct from historical 0.2.0 read-test results and the fictional role-play.

### Migration

Before removing a Finding IDs list, ensure every relationship is retained on the corresponding finding through Research question IDs, Round or session IDs or Design versions. Keep all findings, including contradictions and inconclusive results. Remove duplicate prototype metadata only after checking it agrees with the owning register; resolve conflicts explicitly.

Use-cases are introduced when a service interaction needs describing. User-need coverage contains one current assessment row per active user need, keyed by the existing UN ID. Do not duplicate need wording or equate Evidenced with Met in full. A decision not to address a need requires its own decision record and does not count as fulfilment.

Existing evidence, consent, status and approval conditions still apply before research, review or reliance. Staged capture is permission to start with less information, not to claim completion or certainty prematurely.

## 0.2.0 — 2026-11-16 — draft for review

### Changed

- Standardised ID-reference field names and documented their permitted targets, cardinality and conditions in the existing record-conventions guide.
- Separated evidence source identity, exact version or path, and source locator.
- Added explicit replacement references for superseded records.
- Separated non-functional requirement agreement from verification status.
- Made the current transcript link singular so its review status applies to one specific file.
- Strengthened AI instructions for reading tables, retaining context, following evidence and reporting access limits.

### Added

- A small fictional project and six AI-usability evaluation questions alongside the blank working template.

### Migration

Existing projects should preserve their record IDs and data while adopting the renamed reference columns. Split evidence Source content into Source ID, Source version or path, and Locator; register source sessions or documents where needed. Select the current transcript explicitly, retaining earlier files. Populate Superseded by from known replacement records and flag unknown replacements as gaps.

For non-functional requirements, migrate Proposed, Agreed and Superseded into Record status. Migrate Not assessed, Partially met, Met and Not met into Verification status. The old field cannot establish both states: leave the missing state unresolved until a person checks the relevant agreement or verification evidence. Do not assume that a tested requirement was agreed or that an agreed requirement was met.

The blank starter has been updated. No real project records were migrated. Evaluation scope and observed results were recorded with the fictional project.

## 0.1.0 — 2026-11-16 — draft for review

### Added

- A project starter with one clearly named file per core concept.
- Excel registers for structured records and Markdown templates for material requiring context and reasoning.
- Explicit links between user groups, needs, research, evidence, findings, decisions, designs and outcomes.
- A participant register and session records, with recording and transcript folder conventions.
- Versioned journey and prototype folder patterns.
- A supplied-document register and guidance on interpreting source material.
- Non-functional requirements linked to user needs and applicable standards.
- Focused how-to documentation and model-neutral AI prompts.

### Changed

- Grouped the licence, changelog, contribution guidance and framework sources under how-to-use-this-framework/, separate from the normal project starting point.
- Clarified that framework administration and fictional how-to examples are not project evidence.

### Status

This is the first review draft. Example folder IDs and file patterns are illustrative. No real project evidence or participant data is included.

### Migration

Not applicable: initial release.
