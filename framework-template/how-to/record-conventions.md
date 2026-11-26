# Record conventions

**Guidance revision:** 2026-11-26.2

The [document tracker](../document-tracker.xlsx) identifies where the team's current records live. The starter filenames in this guide identify each record type; their links open the tracker workbook. Resolve each record type through the tracker and project config when a file has moved, changed name or is owned in another tool. Check conflicting locations with the team before relying on or editing either. Start with the minimum in its [file guide](files/), using exact IDs and versions. Add the evidence and details needed before relying on it.

## Edit records

- Replace the **OVERWRITE ME** row with the first real entry. Exclude starter rows from evidence and counts. Use the first empty row in the Excel table under the headings. The empty rows provided vary by workbook. When the table is full, resize it before adding rows, or resize it to include rows already pasted below it. Check that its dropdowns and any totals cover the new rows.
- [Keep any extra workbook columns](../ai-guidance.md#read-and-preserve-extra-workbook-columns) and their formulas or controls.
- Replace bracketed prompts in the Markdown files you use.
- After pasting or importing records, check controlled values such as status against the choices in the column's dropdown.
- Use YYYY-MM-DD for dates. Use the workspace’s version history for routine edits. Record consequential choices in [Decisions](files/decisions.md).

## Stable identifiers and owner lookup

For new records, use the prefix below in uppercase, a hyphen and a number of at least three digits, starting at `001`. Check the full ID for the correct owner, spelling and stray whitespace, including invisible spaces. Respect explicitly documented local ID conventions and mappings when a team has adapted the starter. Reuse the starter ID for the first real record if it is free. Check existing and retired records before allocating another ID. Keep the ID when a record moves.

| Prefix | Concept | Default owner from project root | Record key |
|---|---|---|---|
| `SCP` | Scope item | [in-scope.xlsx](../document-tracker.xlsx) or [out-of-scope.xlsx](../document-tracker.xlsx) | ID |
| `OUT` | Outcome | [outcomes.xlsx](../document-tracker.xlsx) | ID |
| `UG` | User group | [user-groups.xlsx](../document-tracker.xlsx) | ID |
| `UN` | User need | [user-needs.xlsx](../document-tracker.xlsx) | ID |
| `UC` | Use case | [use-cases.xlsx](../document-tracker.xlsx) | ID |
| `STK` | Stakeholder | [stakeholders.xlsx](../document-tracker.xlsx) | ID |
| `TM` | Team member | [team.xlsx](../document-tracker.xlsx) | ID |
| `PAR` | Participant | [participants.xlsx](../document-tracker.xlsx) | Participant ID |
| `CON` | Constraint | [constraints.xlsx](../document-tracker.xlsx) | ID |
| `DEP` | Dependency | [dependencies.xlsx](../document-tracker.xlsx) | ID |
| `ASM` | Assumption | [assumptions.xlsx](../document-tracker.xlsx) | ID |
| `RSK` | Risk | [risks.xlsx](../document-tracker.xlsx) | ID |
| `RQ` | Research question | [research-questions.xlsx](../document-tracker.xlsx) | ID |
| `RND` | Research round | [research-plan.xlsx](../document-tracker.xlsx) | ID |
| `SES` | Research session | [research-sessions.xlsx](../document-tracker.xlsx) | Session ID |
| `EV` | Independently cited observation or measurement | [findings-and-observations.xlsx](../document-tracker.xlsx) | ID |
| `FND` | Conclusion reached by the team | [findings-and-observations.xlsx](../document-tracker.xlsx) | ID |
| `JNY` | Journey | [user-journeys.xlsx](../document-tracker.xlsx) | ID + Version |
| `PRT` | Prototype | [prototypes.xlsx](../document-tracker.xlsx) | ID + Version |
| `BR` | Business rule | [business-rules.xlsx](../document-tracker.xlsx) | ID |
| `NFR` | Non-functional requirement | [non-functional-requirements.xlsx](../document-tracker.xlsx) | ID |
| `DEC` | Decision | [decisions.xlsx](../document-tracker.xlsx) | ID |
| `MET` | Success measure | [success-measures.xlsx](../document-tracker.xlsx) | ID |
| `TERM` | Glossary term | [glossary.xlsx](../document-tracker.xlsx) | ID |
| `DOC` | Source outside a research session | [project-sources/source-register.xlsx](../document-tracker.xlsx) | ID |

Use one SCP sequence across both scope workbooks and one current row per item. If an item moves between workbooks, keep its ID and update **Why**. For a material boundary change, record the earlier position and rationale in the decision and cite its DEC ID.

Journeys and prototypes use the ID and exact Version, for example `PRT-001 v2`. Keep each retained version discoverable. Use Status to find selected versions. Check the session or research evidence to establish which version people actually used.

## References, blanks and replacements

- In an ID-only field, enter complete IDs. Separate multiple IDs with a semicolon and space, for example `UG-001; UG-002`. Cite prose, sources and versions in the fields intended for them.
- A blank optional field means the information is unrecorded. Flag missing information that the team needs before relying on the record.
- Where **Superseded by** is available, retain the old record and link to its known replacements. Flag unknown successors and check for self-links and cycles. Follow the file guide for registers that use Status alone. Where a team withdraws a need, question, rule, requirement, finding or observation without a replacement, use Withdrawn and retain the ID and permitted reason in its existing text field. Withdrawn is historical and requires no successor. Use the owning guide for its meaning and any dependent-record checks.
- For retained sources, use an exact path relative to the project root or a version-specific URL. Markdown links are relative to their own file. Name the other project in cross-project citations. Owner and reviewer names are descriptive text.

## Canonical relationships

The table shows where to enter each relationship. Match whole IDs using the owner lookup. Paths containing `*` refer to the actual round or design version. Counts refer to links for one record. A text citation goes in the named prose field.

| Field | Link target | Count | When to link | What it tells you |
|---|---|---|---|---|
| `in-scope.xlsx` or `out-of-scope.xlsx` — Why | DEC in text | 0–1 | Cite a recorded decision when available | Cite the decision that established the boundary. |
| `outcomes.xlsx` — User need IDs | `UN` | 0+ | Optional | Directly related needs; do not invent a need to fill the cell. |
| `user-groups.xlsx` — Description | `EV` or `FND` if cited, UG for related historic and current groups | 0+ | When useful or a group changes materially | Explain the group and record the date and exact group IDs for significant splits or combinations. |
| `user-needs.xlsx` — User group IDs | `UG` | 1+ | Before use | Groups experiencing the need. |
| `user-needs.xlsx` — Supporting record IDs | `EV`, `FND` | 1+ when Evidenced | When citing support | Observations or findings supporting the need; follow **Evidence and source** for the FND or EV. |
| `user-needs.xlsx` — Superseded by | `UN` | 0+ | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `user-needs.xlsx` — Scope and evidence, assessment | FND or EV and exact design/build or JNY/PRT ID plus Version where applicable, in text | 1+ | Fulfilment is Not met, Partly met or Met in full | Give the assessment date, exact version or bounded scope, and any unmet part. Check whether it applies to the current scope. Link actual release or test evidence where cited. |
| `user-needs.xlsx` — Scope and evidence, delivery | DEC in text | 0–1 | Delivery decision is Deferred or Will not address. Cite a DEC for Will address when available. | Read the linked **Decision** and **Why** for the team's choice and reason. |
| `participants.xlsx` — User group IDs | `UG` | 1+ | Before use | Groups linked to the participant. Confirm which role and groups the participant actually represented in each session from its notes and evidence. |
| `assumptions.xlsx` — Evidence | `EV`, `FND` in text | 0+ | Cite recorded evidence when assessed. Flag material gaps. | Exact supporting IDs and a short reason for the assessment. |
| `research-questions.xlsx` — Superseded by | `RQ` | 0+ | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `research-plan.xlsx` — Research question IDs | `RQ` | 1+ | Before use | Questions this round addresses. |
| `research-plan.xlsx` — User group IDs | `UG` | 0+ | The round includes user groups. | Groups included; for no-participant studies, leave blank and explain the scope in the protocol. |
| `research-sessions.xlsx` — Round ID | `RND` | 1 | Before use | The parent research round. |
| `research-sessions.xlsx` — Participant IDs | `PAR` | 0+ | The session involves participants. | Participants who took part; coded identities only. |
| `research-sessions.xlsx` — Prototype versions | `PRT` + exact Version | 0+ | The session tests one or more prototypes. | Enter each version actually tested, separated by a semicolon and a space. Link an observation to the version it concerns. |
| `non-functional-requirements.xlsx` — Verification | EV in text | 1+ | When recording a check result | Cite the observations supporting the result for its exact version or scope. Trace verification reports through EV to their exact sources. |
| `project-sources/source-register.xlsx` — Superseded by | `DOC` | 0+ | When a replacement is known | Exact replacement DOC IDs. Retain the earlier record for historical citations. |
| `constraints.xlsx` — Source | Authority citation; DOC/DEC if referenced, otherwise exact source and section | 1 | Before use | Identifies why the constraint applies. This is not an ID-only field. |
| `constraints.xlsx` — Constraint | Limit and practical effect. May cite a DEC or DOC for an approval condition | 1 | At capture and when changed | Explain who or what can change the constraint. Give a dated applicability note with the DEC ID when renegotiated or removed. |
| `research-questions.xlsx` — Decision informed | Decision to be made in prose; DEC if already recorded | 0+ | Decision explanation required; an existing DEC is optional | A research question can precede the decision. Do not invent a DEC to fill a gap. |
| `research-plan.xlsx` — Protocol path | Exact protocol for the row’s RND ID | 1 | Before use | Locates the executable round protocol, for example `research/RND-002/protocol.md` for `RND-002`. It holds the method, planned start date when known and lead. |
| `research-sessions.xlsx` — Consent reference | Applicable restricted consent evidence | 1 | Required before participant research | Matches the participant/session and permitted use; do not expose contact details. |
| `research-sessions.xlsx` — Current transcript link | Exact current transcript-file path or version-specific URL | 0–1 | Required for Machine-generated, Checked or Corrected; blank for Not applicable or Not available | Transcript status describes this one file only. Historical evidence keeps its own exact older source pointer. |
| `research-sessions.xlsx` — Recording and notes links | Exact recording and notes paths or version-specific URLs for the session | 0+ | When recordings or notes are kept | Separate multiple links with `; `. The session notes establish which roles, groups and circumstances participants actually represented. |
| `user-journeys.xlsx` — Link | Exact diagram or text description for JNY ID + Version | 1 | Before use | Use the matching version description for the readable equivalent, groups and relevant decisions. Match graphic and text to that version. |
| `prototypes.xlsx` — Link | Exact retained artefact or a note that opens it | 1 | Before use | Match the PRT ID and Version to the artefact in its original tool or a retained copy. |
| `assumptions.xlsx` — Evidence | ASM in text | 0+ | When a belief is superseded | List the replacement ASM IDs on the old record. |
| `non-functional-requirements.xlsx` — Requirement | NFR in text | 0+ | When a criterion is superseded | List the replacement NFR IDs on the old record. |
| `non-functional-requirements.xlsx` — Source | UN in text | 0+ | A user need informs the criterion | Cite the specific need alongside any applicable standard. |
| `business-rules.xlsx` — Rule | BR in text | 0+ | When a rule is superseded | Keep its wording and unresolved exceptions. List each exact successor BR ID, or flag an unknown successor. Check for self-links and cycles. |
| `business-rules.xlsx` — Source | Authority citation; DOC/DEC if referenced, otherwise exact source and section | 1 | Before use | Explains the rule’s authority; it is not an ID-only field or proof the rule is implemented. |
| `non-functional-requirements.xlsx` — Source | Standard or obligation. DOC or DEC when cited. | 1 | Before use | Explain applicability and give the exact version or section when needed. Cite verification observations in Verification. |
| `project-sources/source-register.xlsx` — File or URL | Exact file location or direct page URL | 1 | Before use | Register metadata does not replace checking the exact cited source version and passage. |
| `findings-and-observations.xlsx` — Evidence and source | SES or DOC with exact source version or path and locator. An FND row may cite an existing EV row. | 1+ where retention permits | Before reliance, when Reviewed or Withdrawn | Identify the observations and sources. For a withdrawal, keep the permitted citation and reason, or explain permitted data removal. Follow each cited EV to its exact source. Register cited non-session sources as DOC. |
| `findings-and-observations.xlsx` — Evidence and source | RQ, UG, RND, SES and exact JNY or PRT ID with Version | 0+ | When needed to explain scope; required RQ ID when answering a research question | Cite the question, groups, round, sessions or design version the row concerns. An Answered question must have usable support from a current Reviewed FND that cites that RQ. Include limits. |
| `decisions.xlsx` — Why | EV, FND or DOC for support. Other listed prefixes for important alternatives or affected records. | 0+ | Cite known needs the choice is meant to serve, recorded support and material alternatives when available. State material gaps. | Follow evidence chains and cite the exact version and passage of a DOC source. Use the affected record’s DEC link where available. |
| `decisions.xlsx` — Superseded by | DEC | 0+ | Required when replacements exist; blank Superseded is a gap | Exact replacing decisions; retain the old rationale; no self-links or cycles. |
| `success-measures.xlsx` — Outcome IDs | OUT | 1+ | Before use | Outcomes the measure helps assess. |
| `success-measures.xlsx` — Baseline | EV in text | 0+ | Required when asserting a recorded baseline; otherwise Not yet established | Evidence for the baseline value, period and applicable population. |
| `success-measures.xlsx` — Source and method | DOC + version/location, or SES in text | 1+ | Required for an established measure; state an unresolved source gap otherwise | Describes how results are collected; chosen data sources need applicability and access checks. |
| `success-measures.xlsx` — Results | EV and exact dashboard or report links | 0+ | When citing recorded results | Give the snapshot, date and filters. Follow EV records to the underlying source. |
| `success-measures.xlsx` — Results or affected field | DEC in text | 0+ | When a decision changes the measure | Link decisions that change the definition, target or interpretation. |
| `research/RND-*/protocol.md` — Round ID in heading | RND in research-plan.xlsx | 1 | Before use | Must match the parent round and folder; does not create a second round record. |
| `research/RND-*/protocol.md` — Plan the round | DOC + exact version in text | 1+ when using existing data sources | When existing data sources are used | Record selection and coverage. Research plan records the round’s question and group IDs. |
| `research/RND-*/protocol.md` — Plan the round or delivery test | ASM and MET IDs in text | 0+ | When testing a hypothesis or using a success measure | Identify the assumption, what the test would support or challenge, and the measure used. |
| `research/RND-*/protocol.md` — Materials used (journey or prototype versions) | JNY or PRT + exact Version | 0+ | Required when a journey or prototype is used | Names the planned materials. Sessions record each version actually tested. |
| `research/RND-*/protocol.md` — Consent and storage (participant information and consent material) | Exact approved materials/versions or links | 1+ | Required for participant research | Materials explaining participation and permitted use. |
| `research/RND-*/protocol.md` — Consent and storage (consent record location) | Restricted consent storage | 1 | Required for participant research | Explains where session-matchable consent evidence is retained. |
| `research/RND-*/protocol.md` — Consent and storage (approved storage and access) | Approved storage locations and permitted roles | 1+ | Required where research material is retained | A storage permission statement, not a project-record ID join. |
| `research/RND-*/protocol.md` — Materials used | Exact file or link, DOC ID for cited non-session material | 0+ | When material was used | Identify the version and locator of retained evidence. |
| `journeys/JNY-*/v*/description.md` — Journey ID and version in heading | JNY + exact Version in user-journeys.xlsx | 1 | Before use | Binds this text to one registered version. |
| `journeys/JNY-*/v*/description.md` — User group IDs | UG | 1+ | Before use | Identifies the groups covered by the description and graphic for this version. |
| `journeys/JNY-*/v*/description.md` — Graphic | Exact visual map path or version-specific URL | 1 | Before use | The graphic matches the ID and version of this description. |
| `journeys/JNY-*/v*/description.md` — Sequence: Handoff or backstage dependency | DEP in descriptive text | 0+ | When a dependency is recorded | Connects a stage to a dependency without replacing its owner record. |
| `journeys/JNY-*/v*/description.md` — Sequence: Difficulty or relevant need | UN in descriptive text | 0+ | When a related need is established | Connects the experience to the actual need, not an inferred feature requirement. |
| `journeys/JNY-*/v*/description.md` — Sequence: Evidence IDs | EV or FND | 0+ | For claims about observed behaviour | Follow the cited record to the observation and source for this stage. |
| `journeys/JNY-*/v*/description.md` — Interpretation and status | ASM and DEC in text | 0+ | Cite recorded assumptions and decisions where relevant | The register owns Status for this exact version. |
| Optional prototype note | PRT + exact Version and link to the retained artefact | 1 | When the note is used | Gives context or access instructions for that version. |
| Optional prototype note | JNY + Version, DEC, RQ or UN in text | 0+ | When useful | Connects the version to related journeys, decisions, questions or needs. |
| `use-cases.xlsx` — User group IDs | UG | 1+ | Before relying on the case | Groups taking part in this described interaction; a first draft can expose the gap. |
| `use-cases.xlsx` — User need IDs | UN | 0+ | When related needs are established | User goals served by the interaction; do not infer fulfilment from the description. |
| `use-cases.xlsx` — Interaction | EV or FND in text | 0+ | For claims about observed behaviour | Follow the IDs to the exact source. |
| `use-cases.xlsx` — Interaction | Exact delivery item or acceptance criteria link | 0+ | When handing work into development | Connect the described behaviour to the work without duplicating the delivery record. Link verification or actual release evidence in the relevant need or requirement. |
| `use-cases.xlsx` — Interaction | UC in text | 0+ | When replacements exist | Cite exact successor IDs and flag unknown replacements. Check for self-links and cycles. |

## Reverse lookups

To find related records, search the field that owns the relationship. Compare exact IDs and versions. Check both directions, including when a finding owns a relationship to an answered question. Check how much of the record set you could read before reporting that a match is absent.

| To find… | Read the owning relationship |
|---|---|
| Records citing a finding or observation | Match the exact FND or EV ID in the citation fields under [Canonical relationships](#canonical-relationships), including **Supporting record IDs** and **Scope and evidence** in User Needs, and **Why** in Decisions. Check whether each reference supports a current claim or only records history. |
| Findings answering a question | findings-and-observations.xlsx → Evidence and source cites the exact RQ ID. Verify that an Answered RQ has at least one applicable Reviewed FND with usable underlying evidence. If the evidence is withdrawn, check the question even though its row contains no FND ID. |
| Findings from a round | findings-and-observations.xlsx → Evidence and source cites the exact RND ID or an SES in that round, including citations through an EV row |
| Findings about a retained design | findings-and-observations.xlsx → Evidence and source cites the exact JNY/PRT ID and version |
| Sessions in a round | research-sessions.xlsx → Round ID = exact RND ID |
| Sessions testing a prototype | research-sessions.xlsx → Prototype versions contains the exact PRT ID and version |
| Groups actually reached in a session | research-sessions.xlsx → Participant IDs and Recording and notes links. Check which role, group, route and circumstances the participant actually represented in that session. |
| Prototypes exploring a journey | Check decisions citing both versions, or follow the prototype register link to any version note citing the exact JNY ID and version. |
| Decisions about a need | decisions.xlsx → Why cites the exact UN ID. Also check DEC links on the need row. A shared finding alone does not establish a decision’s link to another need. |
| Current fulfilment assessment of a need | user-needs.xlsx → ID = exact UN ID. Read Fulfilment and Scope and evidence on that row. |
| Scope items governed by a decision | in-scope.xlsx and out-of-scope.xlsx → Why cites the exact DEC ID |
| Decisions on a specific journey version | decisions.xlsx → Why cites the exact JNY ID and version. Also follow DEC references in the matching journey description. |
| Use cases for a need or group | use-cases.xlsx → User need IDs or User group IDs contains the exact ID |
| Decisions based on a finding or affecting a design | decisions.xlsx → Why for supporting citations and the exact JNY/PRT ID and version. Check the DEC link in the affected record when available. |

## Trace withdrawn evidence

When a team withdraws an FND or EV, keep its ID and the recorded reason. Preserve source details only where the approved research arrangements permit this. Follow the actual owning fields to:

1. Find every record that cites the exact withdrawn ID, including dependent findings, needs, decisions, assumptions, business rules, requirements, success measures, journeys and use cases. Match IDs within structured fields and text citations, including links to other approved tools.
2. Repeat the lookup for each affected record ID where another claim depends on it. Follow the dependency chain through findings and other affected records, avoiding repeated records or cycles. For each affected finding, also read the RQ IDs in its **Evidence and source** and check whether another applicable Reviewed finding with usable evidence supports each Answered question. Include any unresolved question linked to the decision under review.
3. Identify each current claim that relies on the withdrawn material, its owning record and location, remaining usable evidence, and whether the team has independently reassessed that evidence. Retain historical citations as history. Report which parts of the chain were inaccessible or uncertain.
4. Where authorised, append a brief dated evidence-review note in the affected record's existing evidence or rationale field. For a research question use **Decision informed**. Retain recorded statuses while the team reviews the impact. A remaining citation alone does not confirm that the claim still holds.

Apply the same review where correction of an EV, a superseded finding, changed scope or authorised data removal puts a claim in doubt. Do not restore data that was deliberately removed. [Findings guide](files/findings-and-observations.md#withdraw-a-finding)

## Check and repair project records

1. Start with the record or handover under review. Open its confirmed owner and sources. For a project-wide check, read **Starter version** in the project README. Use the [document tracker](../document-tracker.xlsx) and project config to check expected owners, conflicting copies and whether relevant links work. Inspect the records in scope, including superseded or withdrawn records that a current claim cites. Check actual owners outside the starter where adopted. An unused starter file or an unlisted optional file is not a gap.
2. Check for duplicate or malformed record keys, incomplete and orphan rows, exact versions, links, replacement cycles, conflicting scope entries, rows pasted below tables, workbook controls and the [completion requirements](files/). Distinguish optional blanks from fields needed for a status or claim. Keep extra columns and verify any alignment outside the table by ID. Compare pasted values with the controlled choices. Check whether active assessed needs include user groups, supporting evidence, assessment scope and the required delivery decision basis. Compare recorded assessments with independent totals and review incomplete or malformed records even if workbook warnings show zero. Check whether Withdrawn records give the permitted reason and historical records are distinguished from current claims. Report actual gaps with the workbook, sheet, row and field.
3. Check the evidence for claims, research consent and source access. Check affected records for withdrawn evidence, answered questions without usable findings, actual session coverage and review of changed assessment or verification scope. Use the [user needs guide](files/user-needs.md#assess-whether-the-service-meets-the-need), [research protocol](research-protocol.md#analyse-and-close-the-round) and [withdrawal lookup](#trace-withdrawn-evidence).
4. When authorised, fix clear errors with a verified source or documented upgrade. Preserve records and history. Take disputed evidence, consent, judgement and uncertain matches back to the team.
5. Reopen changed records and check their values, controls and links. Report what was checked, what was fixed and what is still unresolved.

### Check for duplicate IDs

- Scan all record fields in the full owning sheet in scope, including superseded and withdrawn records. Check populated rows below the table, including metadata-only rows missing an ID or wording. Flag them as outside the table and include their IDs, where present, in duplicate checks. For IDs, check the expected prefix and numeric format or the team's documented local mapping. Flag incorrect or invisible whitespace, wrong owner prefixes and malformed IDs. Skip empty rows, formatting-only rows and **OVERWRITE ME** examples.
- A key is normally the ID. Check the two scope workbooks together for repeated `SCP` IDs. For journeys and prototypes, only a repeated ID and version together is a duplicate. [Record keys](#stable-identifiers-and-owner-lookup)
- Report each duplicated key with the workbook, sheet and row number of every occurrence. Where possible, point out records that refer to the ambiguous key. Leave IDs and links as they are until the team confirms the correct repair. Carry the locations into any affected lookup, edit or briefing.

Use [AI guidance](../ai-guidance.md) when a tool helps read or edit records.
