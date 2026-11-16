# Record conventions

Research instruments, response exports, calculation working, analysis notes and Whiteboard references live with their round or design activity. They are supporting material, not new global register types. Register a cited non-session dataset or retained board as a DOC source; EV records then identify the exact source version and locator. Q1-style question IDs belong to a particular questionnaire version, and response IDs do not imply participant identities. See [research-materials conventions](research-protocol.md#discussion-guides-surveys-and-whiteboards).

These conventions make the files understandable to people and AI tools. They define exact relationships; they do not decide what the evidence establishes.

## One concept and one maintained home

Each named file owns its concept. Link to another record instead of copying maintained content. Activate records when the relevant activity happens; this does not make retention of substantive learning optional. All substantive findings, needs, consequential decisions and retained options belong in their owners, including contradictory and inconclusive findings and unmet needs. A workbook contains one main Records table; supporting dropdown lists are definitions, not project records.

Enter data directly in Excel or a compatible spreadsheet application. Keep the column names and table structure. Use the next available table row and check that dropdowns still work when extending it. Do not maintain an independently edited CSV copy.

## Stable identifiers and owner lookup

Allocate the next unused ID, such as `UN-001`. IDs identify records, not row positions; sorting must not change them. Do not recycle IDs. This lookup is the authority for locating an ID in this project.

| Prefix | Concept | Owner from project root | Record key |
|---|---|---|---|
| `SCP` | Scope item | [in-scope.xlsx](../in-scope.xlsx) or [out-of-scope.xlsx](../out-of-scope.xlsx) | ID |
| `OUT` | Outcome | [outcomes.xlsx](../outcomes.xlsx) | ID |
| `UG` | User group | [user-groups.xlsx](../user-groups.xlsx) | ID |
| `UN` | User need | [user-needs.xlsx](../user-needs.xlsx) | ID |
| `UC` | Use case | [use-cases.md](../use-cases.md) | ID in section heading |
| `STK` | Stakeholder | [stakeholders.xlsx](../stakeholders.xlsx) | ID |
| `TM` | Team member | [team.xlsx](../team.xlsx) | ID |
| `PAR` | Participant | [participants.xlsx](../participants.xlsx) | Participant ID |
| `CON` | Constraint | [constraints.xlsx](../constraints.xlsx) | ID |
| `DEP` | Dependency | [dependencies.xlsx](../dependencies.xlsx) | ID |
| `ASM` | Assumption | [assumptions.xlsx](../assumptions.xlsx) | ID |
| `RSK` | Risk | [risks.xlsx](../risks.xlsx) | ID |
| `RQ` | Research question | [research-questions.xlsx](../research-questions.xlsx) | ID |
| `RND` | Research round | [research-plan.xlsx](../research-plan.xlsx) | ID |
| `SES` | Research session | [research-sessions.xlsx](../research-sessions.xlsx) | Session ID |
| `EV` | Evidence | [evidence.xlsx](../evidence.xlsx) | ID |
| `FND` | Research finding | [research-findings.md](../research-findings.md) | ID in section heading |
| `JNY` | Journey | [user-journeys.xlsx](../user-journeys.xlsx) | ID + Version |
| `PROP` | Design proposal | [design-proposals.md](../design-proposals.md) | ID in section heading |
| `PRT` | Prototype | [prototypes.xlsx](../prototypes.xlsx) | ID + Version |
| `BR` | Business rule | [business-rules.xlsx](../business-rules.xlsx) | ID |
| `NFR` | Non-functional requirement | [non-functional-requirements.xlsx](../non-functional-requirements.xlsx) | ID |
| `DEC` | Decision | [decisions.md](../decisions.md) | ID in section heading |
| `MET` | Success measure | [success-measures.md](../success-measures.md) | ID in section heading |
| `TERM` | Glossary term | [glossary.xlsx](../glossary.xlsx) | ID |
| `DOC` | Source document | [project-background/document-register.xlsx](../project-background/document-register.xlsx) | ID |

[user-need-coverage.xlsx](../user-need-coverage.xlsx) uses the existing **User need ID** as its row key. It owns one current fulfilment assessment per active need, not the need itself, and creates no new ID prefix. Active needs are the non-Superseded UN records. A missing coverage row is a gap, not an implied Not assessed row.

SCP IDs share one namespace across both scope lists. An item belongs in only one current list; retain its exact ID when moving it. Do not join scope items by similar wording.

Journeys and prototypes use a **composite key: ID plus Version**. For example, `JNY-001 v1` and `JNY-001 v2` are different retained records. The version cell contains `v1`, `v2` and so on. Every reference to a journey or prototype version includes both parts; a bare ID, “current” or “latest” does not resolve one. A higher version number does not mean selected or implemented.

Within one project these prefixes are sufficient. Cross-project citations must identify the other project and source explicitly; they are not local ID matches.

## References, blanks and replacements

ID-only fields contain exact IDs of the allowed types below. Separate multiple references with a semicolon and a space: `UG-001; UG-002`. Keep IDs, paths and descriptions in their own fields. Do not enter `None`, `N/A` or `Not applicable` in an ID field. Match the whole ID and, where required, version. Never resolve a missing ID by a similar title, row number or wording.

A blank optional reference means no relationship has been recorded. It does not prove no relationship exists. A blank required or conditionally required reference is an unresolved gap. Explain the gap in the relevant narrative or review; do not invent a target. “One” means exactly one value; “one or more” requires at least one; “zero or one” and “zero or more” allow blanks unless the stated condition applies.

**Superseded by** contains zero or more exact replacements of the same concept type. Enter every known replacement, separated by `; `; a record can split into several successors. It is required when a replacement exists. A Superseded record with a blank replacement has an unresolved reference gap. Do not infer a successor from recency. No self-links or cycles. Journey and prototype replacements use exact ID plus Version, including when the ID stays the same.

For `document-register.xlsx`, Currency identifies superseded records; for non-functional requirements, Record status does. The other replacement-bearing registers and narratives use Status. An agreed non-functional requirement may still be Not assessed or Not met: Record status and Verification status answer different questions.

Paths in workbook cells are relative to the project root where practical. Use exact version-specific paths or URLs for retained sources. Markdown hyperlinks are relative to their containing document. A restricted link records a location; it does not grant access. Names or roles in Owner, Lead, Provider, Supplied by, Decision maker and reviewer fields are descriptive text, not automatic joins to people registers.

## Canonical relationships

Source paths below are relative to the project root. Pattern paths such as `research/RND-*/protocol.md` refer to the actual matching record folder. Prefix targets resolve through the owner lookup above. “Any listed prefix” permits only a record in that lookup, with an exact version for JNY or PRT. A field marked “text citation” remains prose, but every ID it cites must still resolve exactly. Completion conditions apply to the relationship, not every sentence in that prose. The guide states the first-capture minimum; a relationship needed before use does not have to be invented during capture.

EV is an observation or measurement with a precise source; FND is an interpreted finding supported by EV records. Supporting record IDs may allow either. A reference to a FND does not bypass its supporting evidence. To check a supported claim, follow the relevant chain to `evidence.xlsx` and its **Source ID → Source version or path → Locator**. A source ID or a mutable current-source link alone is insufficient.

| Source file — field or section | Allowed target | How many | Needed when | Meaning |
|---|---|---|---|---|
| `in-scope.xlsx` — Decision ID | `DEC` | zero or one | Optional | Agreed decision establishing inclusion. |
| `out-of-scope.xlsx` — Decision ID | `DEC` | zero or one | Optional | Agreed decision establishing exclusion. |
| `outcomes.xlsx` — Beneficiary IDs | `UG`, `STK` | one or more | Before use | Groups or stakeholders who benefit. |
| `outcomes.xlsx` — User need IDs | `UN` | zero or more | Optional | Directly related needs; do not invent a need to fill the cell. |
| `user-groups.xlsx` — Supporting record IDs | `EV`, `FND` | zero or more | Optional | Observations or findings supporting the group description. |
| `user-needs.xlsx` — User group IDs | `UG` | one or more | Before use | Groups experiencing the need. |
| `user-needs.xlsx` — Supporting record IDs | `EV`, `FND` | zero or more | Status is Evidenced. | Observations or findings supporting the need; follow FND to EV support. |
| `user-needs.xlsx` — Superseded by | `UN` | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `participants.xlsx` — User group IDs | `UG` | one or more | Before use | Groups represented by the participant. |
| `assumptions.xlsx` — Supporting record IDs | `EV`, `FND` | zero or more | Optional | Evidence supporting the assessment; flag missing support for Supported, Contradicted or Inconclusive. |
| `assumptions.xlsx` — Superseded by | `ASM` | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `research-questions.xlsx` — Superseded by | `RQ` | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `research-plan.xlsx` — Research question IDs | `RQ` | one or more | Before use | Questions this round addresses. |
| `research-plan.xlsx` — User group IDs | `UG` | zero or more | The round includes user groups. | Groups included; for no-participant studies, leave blank and explain the scope in the protocol. |
| `research-sessions.xlsx` — Round ID | `RND` | one | Before use | The parent research round. |
| `research-sessions.xlsx` — Participant IDs | `PAR` | zero or more | The session involves participants. | Participants who took part; coded identities only. |
| `research-sessions.xlsx` — Prototype version | `PRT` + exact Version | zero or one | The session tests a prototype. | The exact prototype version actually tested. |
| `evidence.xlsx` — Source ID | `SES`, `DOC` | one | Before use | Source session or registered document. Register non-session sources as DOC first. |
| `user-journeys.xlsx` — User group IDs | `UG` | one or more | Before use | Groups represented by this journey version. |
| `user-journeys.xlsx` — Decision IDs | `DEC` | zero or more | Optional | Selection, discard or replacement decisions; successors belong in Superseded by. |
| `user-journeys.xlsx` — Superseded by | `JNY` + exact Version | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `prototypes.xlsx` — Proposal IDs | `PROP` | zero or more | Optional | Proposals explored by this version. |
| `prototypes.xlsx` — Journey versions | `JNY` + exact Version | zero or more | Optional | Exact journey versions explored. |
| `prototypes.xlsx` — Superseded by | `PRT` + exact Version | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `business-rules.xlsx` — Superseded by | `BR` | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `non-functional-requirements.xlsx` — User need IDs | `UN` | zero or more | Optional | Directly related needs; do not invent a need to justify a control. |
| `non-functional-requirements.xlsx` — Evidence IDs | `EV` | zero or more | Verification status is Partially met, Met or Not met. | Verification observations only. Cite DOC verification reports through EV; FND and paths are not allowed here. |
| `non-functional-requirements.xlsx` — Superseded by | `NFR` | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `project-background/document-register.xlsx` — Superseded by | `DOC` | zero or more | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `constraints.xlsx` — Source | Authority citation; DOC/DEC if referenced, otherwise exact source and section | One text citation | Before use | Identifies why the constraint applies. This is not an ID-only field. |
| `constraints.xlsx` — Change authority or condition | Person, role or condition; DEC if a decision is cited | One explanation | Explain the change authority/condition when known; state why fixed where relevant | Explains who or what can change the constraint; do not infer authority from a stakeholder name. |
| `assumptions.xlsx` — Check | RQ in explanatory text, when a question is recorded | Zero or more RQ citations | Check text required; an RQ citation is optional | Explains how to investigate; supporting observations belong in Supporting record IDs. |
| `research-questions.xlsx` — Decision informed | Decision to be made in prose; DEC if already recorded | Zero or more DEC citations | Decision explanation required; an existing DEC is optional | A research question can precede the decision. Do not invent a DEC to fill a gap. |
| `research-plan.xlsx` — Protocol path | Exact protocol for the row’s RND ID | One path | Before use | Locates the executable round protocol, normally research/RND-001/protocol.md. |
| `research-sessions.xlsx` — Consent reference | Applicable restricted consent evidence | One reference | Required before participant research | Matches the participant/session and permitted use; do not expose contact details. |
| `research-sessions.xlsx` — Recording links | Exact recording-file paths or version-specific URLs | Zero or more | When recordings were collected and remain available | Each file identifies this session and recording part; a folder does not identify a recording. |
| `research-sessions.xlsx` — Current transcript link | Exact current transcript-file path or version-specific URL | Zero or one | Required for Machine-generated, Checked or Corrected; blank for Not applicable or Not available | Transcript status describes this one file only. Historical evidence keeps its own exact older source pointer. |
| `research-sessions.xlsx` — Notes link | Exact session-notes path or URL | Zero or one | When notes were collected and remain available | Locates this session’s notes, not a folder of unrelated notes. |
| `evidence.xlsx` — Source version or path | Exact source file, version-specific URL or identifiable version within Source ID | One | Before use | Pairs with Source ID; preserve the pointer when a newer transcript or document appears. |
| `evidence.xlsx` — Locator | Timestamp, page, section, line or range within Source version or path | One | Before use | Use Whole source only for an observation genuinely about the entire source. |
| `evidence.xlsx` — Context | Method/sample prose; PAR and exact PRT/JNY versions if cited | Zero or more text citations | Context required; IDs only when relevant | Preserves the circumstances actually observed; does not replace the exact source fields. |
| `user-journeys.xlsx` — Graphic path | Graphic for the row’s exact JNY ID + Version | One path | Before use | The visual and text equivalent must describe the same retained version. |
| `user-journeys.xlsx` — Text path | Text description for the row’s exact JNY ID + Version | One path | Before use | Provides the meaning of the graphic in readable text; check both together. |
| `prototypes.xlsx` — Source path or URL | Source directory/file or original-tool location for exact PRT ID + Version | One location | Before use | The retained source must identify the version, not an unqualified changing latest design. |
| `prototypes.xlsx` — Preview URL | Viewable/runnable preview for exact PRT ID + Version | Zero or one | Optional; record when available | A preview link is not proof it was opened or behaviour was tested. |
| `business-rules.xlsx` — Source | Authority citation; DOC/DEC if referenced, otherwise exact source and section | One text citation | Before use | Explains the rule’s authority; it is not an ID-only field or proof the rule is implemented. |
| `non-functional-requirements.xlsx` — Standard or source | Standard/version/section or obligation; DOC/DEC if referenced | One text citation | Before use | Explains applicability. Verification observations belong in Evidence IDs. |
| `project-background/document-register.xlsx` — File or URL | Original document location or authoritative URL | One location | Before use | Register metadata does not replace checking the exact cited source version and passage. |
| `research-findings.md` — Research question IDs | RQ | Zero or more | When answering recorded questions | This file owns the answer-to-question relationship; unexpected findings need no invented RQ. |
| `research-findings.md` — User group IDs | UG | Zero or more | Required when the finding concerns user groups | Groups covered by the evidence, not every group the service might serve. |
| `research-findings.md` — Round or session IDs | RND, SES | Zero or more | Required when based on project rounds or sessions | Locates the study context; evidence still carries exact source provenance. |
| `research-findings.md` — Supporting evidence | EV in explanatory text | One or more for Reviewed; otherwise zero or more | Required before Status is Reviewed | Observations supporting the conclusion. Follow every material EV to its source. |
| `research-findings.md` — Design versions | JNY or PRT + exact Version | Zero or more | When the finding concerns a design | This file owns the finding-to-design relationship. Match the complete ID and version. |
| `research-findings.md` — Superseded by | FND | Zero or more | Required when replacements exist; blank Superseded is a gap | Exact replacement findings; no self-links or cycles. |
| `design-proposals.md` — User need IDs | UN | Zero or more | When related needs are established | Needs the option addresses; blank does not make the proposal evidenced. |
| `design-proposals.md` — Outcome IDs | OUT | Zero or more | When related outcomes are established | Intended benefits; a link is not evidence the benefit has happened. |
| `design-proposals.md` — Journey versions | JNY + exact Version | Zero or more | When journeys are explored | Exact journey versions the proposal concerns. |
| `design-proposals.md` — Why explore it | FND, EV, UN, ASM in text | Zero or more | Cite recorded support where available; expose gaps | Motivation and uncertainty; an assumption does not establish effectiveness. |
| `design-proposals.md` — Design and prototype | Exact non-prototype artefact paths/URLs | Zero or more | When such artefacts are retained | Locate prototypes by reverse lookup of this PROP ID in prototypes.xlsx Proposal IDs; do not maintain a second prototype list. |
| `design-proposals.md` — What to test | RQ, ASM in text | Zero or more | When the question or assumption is recorded | The uncertainty to investigate, not a conclusion about the option. |
| `design-proposals.md` — What we learned | FND in text | Zero or more | Cite findings after evaluation; otherwise state Untested or the missing-findings gap | Conclusions from evaluating this option, with their limits. |
| `design-proposals.md` — Disposition | DEC in text | Zero or more | Required for recorded selection, discard or replacement; otherwise flag missing decision | Explains the actual choice; Selected does not mean implemented. |
| `design-proposals.md` — Superseded by | PROP | Zero or more | Required when replacements exist; blank Superseded is a gap | Exact replacement proposals; no self-links or cycles. |
| `decisions.md` — Related records | Any listed prefix | Zero or more | Optional | Records materially affected or considered. |
| `decisions.md` — Rationale and alternatives | EV, FND, DOC for support; any listed prefix for alternatives | Zero or more text citations | Cite recorded support and alternatives when available; state material gaps | Follow evidence chains; DOC claims need exact version and passage. A choice is not itself proof of a user need. |
| `decisions.md` — Superseded by | DEC | Zero or more | Required when replacements exist; blank Superseded is a gap | Exact replacing decisions; retain the old rationale; no self-links or cycles. |
| `success-measures.md` — Outcome IDs | OUT | One or more | Before use | Outcomes the measure helps assess. |
| `success-measures.md` — Baseline | EV in text | Zero or more | Required when asserting a recorded baseline; otherwise Not yet established | Evidence for the baseline value, period and applicable population. |
| `success-measures.md` — Source and method | DOC + version/location, or SES in text | One or more when a source is established | Required for an established measure; state an unresolved source gap otherwise | Describes how results are collected; chosen data sources need applicability and access checks. |
| `success-measures.md` — Results and interpretation | EV and exact dashboard/report links | Zero or more | Required when asserting recorded results | Record snapshot/date/filter for changing dashboards; EV retains exact provenance. |
| `success-measures.md` — Review decisions | DEC in text | Zero or more | When relevant decisions are recorded | Changes to the measure, target or interpretation. |
| `research/RND-*/protocol.md` — Round ID in heading | RND in research-plan.xlsx | One | Before use | Must match the parent round and folder; does not create a second round record. |
| `research/RND-*/protocol.md` — Research question IDs | RQ | One or more | Before use | Matches the round’s Research question IDs. |
| `research/RND-*/protocol.md` — Participants or data sources | UG, or DOC + exact version in text | One or more relevant references | Required for the groups or existing data sources used | Planned coverage and selection, not actual participant identity. |
| `research/RND-*/protocol.md` — Journey or prototype versions | JNY or PRT + exact Version | Zero or more | Required when a journey or prototype is used | Names the exact materials; sessions record the version actually tested. |
| `research/RND-*/protocol.md` — Participant information and consent material | Exact approved materials/versions or links | One or more | Required for participant research | Materials explaining participation and permitted use. |
| `research/RND-*/protocol.md` — Consent record location | Restricted consent storage | One location | Required for participant research | Explains where session-matchable consent evidence is retained. |
| `research/RND-*/protocol.md` — Approved storage and access | Approved storage locations and permitted roles | One or more locations | Required where research material is retained | A storage permission statement, not a project-record ID join. |
| `journeys/JNY-*/v*/description.md` — Journey ID and version in heading | JNY + exact Version in user-journeys.xlsx | One | Before use | Binds this text to one registered version. |
| `journeys/JNY-*/v*/description.md` — User group IDs | UG | One or more | Before use | Matches the group coverage in the register. |
| `journeys/JNY-*/v*/description.md` — Graphic | Exact visual map path | One | Before use | Same ID and version as this text and the register’s Graphic path. |
| `journeys/JNY-*/v*/description.md` — Sequence: Handoff or backstage dependency | DEP in descriptive text | Zero or more per stage | When a dependency is recorded | Connects a stage to a dependency without replacing its owner record. |
| `journeys/JNY-*/v*/description.md` — Sequence: Difficulty or relevant need | UN in descriptive text | Zero or more per stage | When a related need is established | Connects the experience to the actual need, not an inferred feature requirement. |
| `journeys/JNY-*/v*/description.md` — Sequence: Evidence IDs | EV | Zero or more per stage | Required to support observed claims; proposed stages may be unevidenced | Source observations for the stage; do not present proposed behaviour as observed. |
| `journeys/JNY-*/v*/description.md` — Interpretation and status | ASM and DEC in text | Zero or more | Cite recorded assumptions and decisions where relevant | The register owns Status and Superseded by for this exact version. |
| `prototypes/PRT-*/v*/README.md` — Prototype ID and version in heading | PRT + exact Version in prototypes.xlsx | One | Before use | Binds the description to one registered version. |
| `prototypes/PRT-*/v*/README.md` — Question explored | RQ, UN in text | Zero or more | When relevant questions or needs are recorded | The purpose of this version, not evidence of success. |
| `user-need-coverage.xlsx` — User need ID | UN | One | At capture | Exact existing need and row key; one current coverage row per active UN, without copying the need wording. |
| `user-need-coverage.xlsx` — Evidence IDs | EV | Zero or more | Assessment is Not met, Partly met or Met in full | Evidence of fulfilment within the stated scope, not merely evidence that the need exists. |
| `user-need-coverage.xlsx` — Decision ID | DEC | Zero or one | Delivery decision is Deferred or Will not address; include for Will address when available | Decision record must explain the choice, reason and consequences. Delivery choice is independent of assessment. |
| `user-need-coverage.xlsx` — Assessed version or scope | Exact JNY/PRT + Version if applicable, or a precise dated/bounded service scope | One scoped description | Assessment is Not met, Partly met or Met in full | No unqualified current/latest. A prototype result does not establish live-service fulfilment. |
| `use-cases.md` — User group IDs | UG | One or more before use | Before relying on the case | Groups taking part in this described interaction; a first draft can expose the gap. |
| `use-cases.md` — User need IDs | UN | Zero or more | When related needs are established | User goals served by the interaction; do not infer fulfilment from the description. |
| `use-cases.md` — Supporting record IDs | EV, FND | Zero or more | When support is recorded; needed for claims about observed behaviour | Follow FND through EV to exact source provenance. Proposed interactions remain proposals. |
| `use-cases.md` — Superseded by | UC | Zero or more | When replacements exist; blank Superseded is a gap | Same-type successors under the common replacement rule. |

Other narrative mentions may cite any listed prefix when relevant, but must preserve exact IDs and versions. They do not create a new join rule or overwrite an owning field. The problem statement has no ID relationships: it contains only the statement of the problem.

## Reverse lookups, without duplicate lists

Keep a relationship in its named owning field. To find the other end, query that field using exact tokens, not substring or title matches:

| To find… | Read the owning relationship |
|---|---|
| Findings answering a question | research-findings.md → Research question IDs = exact RQ ID |
| Findings from a round | research-findings.md → Round or session IDs = exact RND ID, or an SES ID whose research-sessions.xlsx Round ID matches that RND |
| Findings about a retained design | research-findings.md → Design versions = exact JNY/PRT ID + Version |
| Sessions in a round | research-sessions.xlsx → Round ID = exact RND ID |
| Sessions testing a prototype | research-sessions.xlsx → Prototype version = exact PRT ID + Version |
| Prototypes exploring a proposal | prototypes.xlsx → Proposal IDs contains the exact PROP ID |
| Current fulfilment assessment of a need | user-need-coverage.xlsx → User need ID = exact UN ID; reconcile one current row per active need |
| Use cases for a need or group | use-cases.md → User need IDs or User group IDs contains the exact ID |
| Decisions based on a finding or affecting an option | decisions.md → actual supporting/affected references; distinguish rationale from a mere mention |

Read the relevant full records and preserve the limits of the relationship. A result about one version does not transfer to another. No matching result is meaningful only after complete relevant coverage; otherwise state that the lookup was incomplete. Do not author inverse Finding IDs lists or duplicate prototype metadata to support these queries.

Update when the work changes: capture learning after research, choices when made and revisions when meaning changes. Use existing team conversations, not a new recurring review ritual. Raw material can stay in approved tools with exact registered source locations and accessible text for substantive meaning; state any access or coverage gap. Do not routinely copy operational systems or private data.

## Need evidence, fulfilment and delivery are different

user-needs.xlsx Status describes support for the need itself. In user-need-coverage.xlsx, Assessment describes fulfilment within Assessed version or scope; Delivery decision describes the team's choice. Do not infer one from another. Not met, Partly met and Met in full need EV support, the actual Assessed on date and an exact scope. Not met and Partly met also need Remaining gap. Deferred and Will not address need a DEC record explaining reason and consequences.

Keep one current coverage row per active UN. Update it when a new scoped assessment or delivery choice is made, preserving historical EV and DEC sources. The Summary sheet counts recorded rows with nonblank UN IDs across two independent dimensions; do not add the dimensions or infer a completion percentage. Before claiming project completeness, reconcile every active UN to exactly one current coverage row and flag missing, duplicate, unknown or superseded references. Summary counts alone cannot establish fulfilment, reference integrity or full project coverage.

## Capture, completion and controlled values

File guides distinguish **At capture**, **Before use** and explicit conditions. Start with the stated small capture, then supply the information needed before acting on or relying on the record. Capture is not evidence, agreement, verification or permission to conduct research. Consent and source-provenance requirements keep their stated timing. Identify unresolved gaps rather than inventing evidence, people, dates or agreement. Use YYYY-MM-DD for dates and a real milestone only where the field permits one, such as Required by or Action due.

Choose the defined dropdown values. [allowed-values.xlsx](allowed-values.xlsx) documents their meanings; each workbook already contains its own dropdowns. Do not add near-synonyms such as Done for Complete. Change a state definition, guide and dropdown together in a reviewed update. An editing date is not a substantive review or observation date.

## Reading and sharing records

Use the repeated section in a Markdown owner for each new record. Replace bracketed instructions before treating it as project data. The starter’s blank rows and template-only folders are not completed records.

An AI or other reader must establish the actual workbook sheet/table, headers and relevant full rows. Preserve IDs, statuses, versions, source paths and reference fields in extracts. A partial preview cannot prove full coverage or absence. Follow provenance for supported claims and identify inaccessible or unknown sources explicitly. Framework administration, guide examples and the synthetic `framework/ai-usability/` fixture are not live project evidence; read the fixture only intentionally for evaluation. See [AI guidance](../ai-guidance.md).

Before sharing a change, check the relevant completion guide, exact references and status. Preserve the distinction between a proposal and an agreement. Check the audience’s access, particularly for research material and personal details.
