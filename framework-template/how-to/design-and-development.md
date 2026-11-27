# Design and development

Use these records to connect what people need with the service the team designs, builds and tests. Open the workbooks through the [document tracker](../document-tracker.xlsx). Keep delivery items, detailed tests and design files in the tools your team already uses, and retain the links needed to check the evidence.

- [User groups](#user-groups) and [user needs](#user-needs)
- [Use cases](#use-cases) and [design artefacts](#design-artefacts)
- [Business rules](#business-rules) and [requirements](#requirements)
- [Assess whether the service meets the need](#assess-whether-the-service-meets-the-need)

## User groups

Working file `user-groups.xlsx`.

Enter an ID and recognisable name. Describe people through how they use, provide or experience the service, including supported channels and relevant access barriers.

| Field | What to enter |
|---|---|
| ID | Stable UG ID, for example `UG-001`. |
| Name | Short, recognisable group name. |
| Description | Who belongs and the relevant circumstances or role. Cite EV or FND IDs where helpful and flag provisional descriptions. |

Refine the description as evidence develops, keeping the ID for the same group. For a material split or combination, keep the earlier rows and descriptions. Record the date and reciprocal UG IDs in **Description**, and cite any related DEC ID. For example, “Split into UG-014 and UG-015 on 2026-11-20” and “Split from UG-003 on 2026-11-20”. Keep historical links to the groups represented at the time. Ask the team to review which current records should use the new IDs.

[GDS guidance on learning user needs](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs)

## User needs

Working file `user-needs.xlsx`.

Enter an ID and need. Describe what the user needs to achieve and why, in their words where possible. Include the trigger where it changes the meaning. If a source names a feature, ask what people need to achieve. Use quotation marks for traceable participant wording only. First captures can have blank Status and blank or Not assessed Fulfilment.

| Field | What to enter |
|---|---|
| ID | Stable UN ID. |
| User group IDs | One or more exact UG IDs before relying on the need. |
| Need | What people need to do and why. |
| Supporting record IDs | Evidence that the need exists. Evidenced needs require one or more UG IDs and a current Reviewed FND or usable, source-verified EV the team agrees supports the need. Draft findings alone do not suffice. |
| Status | Proposed, Evidenced, Superseded or Withdrawn. Reflect the validity and support for the need. |
| Superseded by | Exact replacement UN IDs. Flag an unknown replacement for a Superseded need. Leave blank for Withdrawn. |
| Fulfilment | The team's assessment. Not assessed, Not met, Partly met or Met in full. |
| Scope and evidence | Assessment date, tested version or bounded scope, EV or FND IDs and any unmet part. Cite relevant DEC IDs and link the delivery work, acceptance criteria and exact build, release or test evidence where they establish the assessed scope. |
| Delivery decision | The team's intent. Not decided, Will address, Deferred or Will not address. |

Use Will address once the team has committed to addressing the need. A choice to test or hold can be recorded in **Scope and evidence**. Keep Not decided while the delivery decision is open.

### Resolve overlapping needs

Check possible matches first. If the candidate may be the same need, bring the possible match to the team before creating another row. A genuinely separate candidate can stay Proposed with “Possible overlap with UN-…” in **Scope and evidence**. Once the team agrees a merge, keep the established ID and add relevant verified supporting citations. Keep the other row’s original wording, evidence and assessment, mark it Superseded and enter the survivor in **Superseded by**. Review affected current links and assessment scope; do not transfer fulfilment automatically.

### Withdraw a need

If supporting evidence is withdrawn or invalidated, note the gap in **Scope and evidence** and ask the team whether remaining evidence supports the need. Keep the recorded status until the team reassesses it. A need that remains plausible with weaker evidence can become Proposed.

Use Withdrawn when the team confirms the need itself is no longer valid and has no replacement. Retain the UN ID, wording, earlier evidence and assessment where permitted. Record the date, reason and any supporting DEC, EV or FND ID in **Scope and evidence**. Keep the judgement as history and review dependent records. Use **Delivery decision** for valid needs the team defers or will leave unaddressed.

### Assess whether the service meets the need

Keep one current, team-agreed assessment per need. Use the actual service or design evidence, not the delivery intention. Distinguish prototype behaviour from delivered service.

| Fulfilment | When to use it |
|---|---|
| Not assessed | No applicable scope has been assessed. |
| Not met | The tested applicable scope shows no positive fulfilment. Untested scope remains unknown. |
| Partly met | Evidence supports fulfilment in some applicable in-scope groups, routes or circumstances, but others fail or remain untested. |
| Met in full | Evidence supports fulfilment across all applicable in-scope groups, routes and circumstances. |

Use **Scope and evidence** to distinguish assessed, unmet and untested scope, with date, version and citations. For example, a web pilot meeting a need online while telephone remains untested is Partly met when both routes are in scope. Link the DEC ID for Deferred or Will not address, and for Will address where available. Delivery intent is separate.

Before relying on an assessment, check the current design or service version, route and context against its recorded scope. After a material change, keep the earlier judgement, version and source and add a dated review note to **Scope and evidence** identifying the scope or version still to check. Report the earlier assessed scope and the current gap. Save a changed assessment on the same row once the team agrees it. Put the current assessment and scope first, retaining earlier dated evidence, decisions and workbook versions.

The four workbook totals show recorded fulfilment, not verified counts. Each counts table rows with an ID and need wording, and a Status of Proposed or Evidenced. Blank Fulfilment counts as Not assessed. A first capture with blank Status and blank or Not assessed Fulfilment also counts as Not assessed. Superseded, Withdrawn or unrecognised statuses and unrecognised fulfilment values are excluded.

The totals are provisional: a duplicate, incomplete or unsupported record may still count, and invalid or incomplete rows may be excluded. Check current evidence, scope and row counts with [Check evidence and records](../AI-skills/check-evidence-and-records/SKILL.md#choose-the-check) before using totals in a review. Recalculate when supported and compare with actual rows. If only cached totals are available, report that limitation. State versions, routes and evidence limits. Filter Delivery decision to see deferred or unaddressed needs.

See the [worked handoff](worked-examples.md#follow-the-finding-forward-to-a-decision-and-an-outcome-check).

## Use cases

Working file `use-cases.xlsx`.

Describe a specific interaction, such as rearranging a repair visit. Start with Draft and choose whether you are recording the current or proposed experience.

| Field | What to enter |
|---|---|
| ID | Stable UC ID. |
| Use case | Short name for the user's goal. |
| User group IDs | Exact UG IDs for the people taking part. |
| User need IDs | Exact UN IDs where the related needs are established. |
| Represents | Current experience or Proposed experience. |
| Interaction | Trigger, preconditions, user and service steps, important alternatives or recovery routes, and intended result. Cite EV or FND records for observed behaviour. Link related journey or prototype versions when useful. |
| Status | Draft, Reviewed or Superseded. Reviewed means the team checked the description. Check Represents before treating it as current behaviour. |
| Superseded by | Exact replacement UC IDs when superseded. |

When a proposed interaction goes into delivery, link the relevant FR IDs, backlog item, acceptance criteria and, when available, released build or exact version and test results in **Interaction**. Keep observed behaviour distinguishable from the intended result. Check the version and scope before treating test results as evidence, and update the related UN assessment once the team agrees it.

Keep earlier cases and use the [replacement rule](README.md#when-records-change).

## Design artefacts

Working file `design-artefacts.xlsx`.

Retain the exact journey, service map or prototype version used in research, a significant decision, substantive review or handover. Record learning from disposable sketches in [Findings and observations](research-and-evidence.md#findings-and-observations).

| Field | What to enter |
|---|---|
| ID | Stable JNY ID for a journey or map, or PRT ID for a prototype. Keep it for revisions of the same artefact and use distinct IDs for competing alternatives. |
| Type | Journey or map or Prototype. Match the ID prefix to the type. |
| Version | Exact retained revision, such as `v1`. Identify artefacts by ID and Version together (for example `PRT-001 v1`). |
| Link | Exact map or matching text description for JNY. Exact artefact or a note that opens it for PRT. Add the link before relying on that version. |
| Status | Journey or map uses Draft, Reviewed, Selected, Discarded or Superseded. Prototype uses Draft, Ready for research, Tested, Selected, Discarded or Superseded. |
| Superseded by | Exact replacement JNY or PRT ID and Version together when superseded, for example `PRT-001 v3`. |

Choose the status applicable to the type. The Status dropdown includes both types' values; check the Type, ID and Status match. Selected records a design choice. Check its recorded basis or flag missing selection evidence for review. Keep implementation and deployment evidence at its own source.

### Check the map and its description

Use a journey to show the experience, a blueprint for backstage work, a process map for actions and decisions, an actor map for responsibilities, or an information flow for information needs.

For a new retained journey version, copy the [version description](../journeys/templates/version/description.md) and [graphical outline](../journeys/templates/version/map.svg) if useful into `journeys/JNY-001/v1/` (use the actual ID and version), or link an existing exact map and description. Record its purpose, groups and boundaries. Label stages and handoffs, distinguish prescribed, observed and proposed steps, and cite relevant rules, evidence or retained designs. Flag disagreements and link significant selection, discard or replacement decisions. Use **Superseded by** in the artefacts register for the exact replacement version when superseded. Before research or handover, open the graphic and description together and check that versions, staff actions and supported routes match. The author resolves discrepancies.

### Check the retained prototype version

Link to the exact retained Figma flow, coded prototype, slides, paper prototype photos or other artefact. If later edits would change the link's contents, retain the version through a saved revision, copy or dated capture in approved storage. Keep local files in [prototypes](../prototypes/) if useful, adding version folders where needed.

When the link needs context, add a short note with the exact artefact, starting point, setup, what it does and what it simulates or leaves out. Include relevant journey versions or decisions. A capture can show screens or steps; use the original version or session evidence to establish what people could do. If there is no access to it, state what the note or capture allowed you to check.

Link the [session records](research-and-evidence.md#research-sessions) to every prototype version actually shown. Cite the relevant version in **Evidence and source** on observations and findings after team analysis. Retain versions, including discarded ones, that explain significant decisions or learning.

[GDS guidance on experience maps](https://www.gov.uk/service-manual/user-research/creating-an-experience-map) · [GDS guidance on making prototypes](https://www.gov.uk/service-manual/design/making-prototypes)

## Business rules

Working file `business-rules.xlsx`.

Record the governing condition, authority and exceptions in a rule. It can inform several [functional requirements](#functional-requirements).

| Field | What to enter |
|---|---|
| ID | Stable BR ID. |
| Rule | Condition, required behaviour, known exceptions and any unresolved exceptions or decisions. Link a decision table for interacting rules. |
| Source | Exact policy, specification, agreement or decision and relevant section. Include a DOC or DEC ID when recorded and uncertainty about applicability. |
| Status | Proposed, Approved, Superseded or Withdrawn. Confirm the source and approval before relying on it. |
| Superseded by | Exact replacement BR IDs when superseded. |

Start with Proposed while approval is unresolved. Preserve earlier wording, exceptions and source, and follow the [replacement rule](README.md#when-records-change). Cite the old and new rules in any material change decision.

When the authorised decision maker or source confirms the rule no longer applies and has no replacement, mark it Withdrawn. Retain its ID, rule, exceptions and source. Record the date, reason and exact authority or DEC ID in **Source**. Check continuing obligations and flag affected designs and decisions for review.

For example, BR-201 proposes permitting a collection message only after depot staff confirm that the equipment is ready. DEC-202 records the scope of the test.

[Department for Transport business rules example](https://department-for-transport-streetmanager.github.io/street-manager-docs/articles/business-rules-version-2-00-service.html)

## Requirements

Working file `requirements.xlsx`.

Record a testable behaviour or quality criterion. Status records the team's agreement and Verification records the test result. Start with Proposed where agreement or applicability is unresolved.

| Field | What to enter |
|---|---|
| ID | Stable FR or NFR ID matching the type. |
| Type | Functional or Non-functional. |
| Requirement | Behaviour or quality criterion, its applicable conditions and what would pass the check. |
| Source | For FR, relevant UN, UC, BR or DEC IDs. For NFR, the applicable standard, obligation or decision and relevant user needs. Give external sources' exact version or section and DOC ID where needed. |
| Status | Proposed, Agreed, Superseded or Withdrawn. Check the source and agreement before relying on the requirement. |
| Verification | Result, exact version or scope checked and supporting EV IDs. Use “Not yet checked” while pending. Register external reports as DOC sources where needed. |
| Superseded by | Exact replacement FR or NFR IDs when superseded. |

### Functional requirements

Describe observable behaviour the service must provide, including conditions, alternative or failure behaviour. Link the user need, use case, rule or decision informing the behaviour. Keep governing conditions, authority and exceptions in the business rule, and cite its ID in **Source**. The team agrees the requirements. Reference the delivery item and acceptance criteria where maintained elsewhere.

For example, FR-201 proposes sending a borrower a collection message when equipment is ready, while BR-201 establishes the condition for sending it.

### Non-functional requirements

Describe a measurable aspect of service quality, such as accessibility, security, performance or reliability. State the applicable scope and threshold for passing the check. Record people's access and support needs in [User needs](#user-needs).

For example, NFR-201 proposes showing readiness online within 60 seconds in at least 95% of tests.

[Defra guidance on non-functional requirements](https://digital.defra.gov.uk/business-analysis/non-functional-requirements)

### Update and verify a requirement

Keep the test method with the delivery test or verification plan. When the service, build, applicable scope or standard changes materially, retain the earlier verification, date and version. Put the current review needed or result first in **Verification** with its date and scope; retain earlier dated verification. Report the earlier result for its recorded scope until the team has verified the current service.

Use the [replacement rule](README.md#when-records-change) for changed requirements. A material reclassification can require a new ID prefix: retain the original and link the replacement.

If the authorised decision maker or source confirms a requirement no longer applies and has no replacement, mark it Withdrawn. Retain the ID, criterion and permitted historical verification. Record the date, reason and exact authority or DEC ID in **Source**. Check continuing standards and obligations and flag affected records for review.
