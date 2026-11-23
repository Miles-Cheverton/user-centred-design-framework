# Record conventions

Keep each record in its named file and link to it with exact IDs and versions. Start with the minimum in its [file guide](files/). Add the evidence and details needed before relying on it.

## Edit records

- Replace the **OVERWRITE ME** row with the first real entry. Exclude starter rows from evidence and counts. Add each new row inside the workbook’s table. If you paste below it, resize the table to include the rows and check that dropdowns and totals cover them.
- Replace bracketed prompts in the Markdown files you use.
- After pasting or importing records, check controlled values such as status against the choices in the column's dropdown.
- Use YYYY-MM-DD for dates. Use the workspace’s version history for routine edits. Record consequential choices in [Decisions](files/decisions.md).

## Stable identifiers and owner lookup

For new records, use the prefix below, a hyphen and a number, starting at `001`. Reuse the starter ID for the first real record if it is free. Check existing and retired records before allocating another ID. Keep the ID when a record moves.

| Prefix | Concept | Owner from project root | Record key |
|---|---|---|---|
| `SCP` | Scope item | [in-scope.xlsx](../in-scope.xlsx) or [out-of-scope.xlsx](../out-of-scope.xlsx) | ID |
| `OUT` | Outcome | [outcomes.xlsx](../outcomes.xlsx) | ID |
| `UG` | User group | [user-groups.xlsx](../user-groups.xlsx) | ID |
| `UN` | User need | [user-needs.xlsx](../user-needs.xlsx) | ID |
| `UC` | Use case | [use-cases.xlsx](../use-cases.xlsx) | ID |
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
| `EV` | Independently cited observation or measurement | [findings-and-observations.xlsx](../findings-and-observations.xlsx) | ID |
| `FND` | Conclusion reached by the team | [findings-and-observations.xlsx](../findings-and-observations.xlsx) | ID |
| `JNY` | Journey | [user-journeys.xlsx](../user-journeys.xlsx) | ID + Version |
| `PRT` | Prototype | [prototypes.xlsx](../prototypes.xlsx) | ID + Version |
| `BR` | Business rule | [business-rules.xlsx](../business-rules.xlsx) | ID |
| `NFR` | Non-functional requirement | [non-functional-requirements.xlsx](../non-functional-requirements.xlsx) | ID |
| `DEC` | Decision | [decisions.xlsx](../decisions.xlsx) | ID |
| `MET` | Success measure | [success-measures.xlsx](../success-measures.xlsx) | ID |
| `TERM` | Glossary term | [glossary.xlsx](../glossary.xlsx) | ID |
| `DOC` | Source outside a research session | [project-sources/source-register.xlsx](../project-sources/source-register.xlsx) | ID |

Use one SCP sequence across both scope workbooks and one current row per item. If an item moves between workbooks, keep its ID and update **Why**. For a material boundary change, record the earlier position and rationale in the decision and cite its DEC ID.

Journeys and prototypes use the ID and exact Version, for example `PRT-001 v2`. Keep each retained version discoverable. Use Status to find selected versions. Check the session or research evidence to establish which version people actually used.

## References, blanks and replacements

- In an ID-only field, enter complete IDs. Separate multiple IDs with a semicolon and space, for example `UG-001; UG-002`. Cite prose, sources and versions in the fields intended for them.
- A blank optional field means the information is unrecorded. Flag missing information that the team needs before relying on the record.
- Where **Superseded by** is available, retain the old record and link to its known replacements. Flag unknown successors and check for self-links and cycles. Follow the file guide for registers that use Status alone.
- For retained sources, use an exact path relative to the project root or a version-specific URL. Markdown links are relative to their own file. Name the other project in cross-project citations. Owner and reviewer names are descriptive text.

## Canonical relationships

The table shows where to enter each relationship. Match whole IDs using the owner lookup. Paths containing `*` refer to the actual round or design version. Counts refer to links for one record. A text citation goes in the named prose field.

| Field | Link target | Count | When to link | What it tells you |
|---|---|---|---|---|
| `in-scope.xlsx` or `out-of-scope.xlsx` — Why | DEC in text | 0–1 | Cite a recorded decision when available | Cite the decision that established the boundary. |
| `outcomes.xlsx` — User need IDs | `UN` | 0+ | Optional | Directly related needs; do not invent a need to fill the cell. |
| `user-groups.xlsx` — Description | `EV` or `FND` if cited | 0+ | Optional | Evidence or findings that help explain the group. |
| `user-needs.xlsx` — User group IDs | `UG` | 1+ | Before use | Groups experiencing the need. |
| `user-needs.xlsx` — Supporting record IDs | `EV`, `FND` | 1+ when Evidenced | When citing support | Observations or findings supporting the need; follow **Evidence and source** for the FND or EV. |
| `user-needs.xlsx` — Superseded by | `UN` | 0+ | When replacements exist; blank Superseded is a gap | Exact same-type successors; follow the replacement rule above. |
| `user-needs.xlsx` — Scope and evidence, assessment | FND or EV and exact JNY/PRT ID plus Version where applicable, in text | 1+ | Fulfilment is Not met, Partly met or Met in full | Give the assessment date, exact version or bounded scope, and any unmet part. Follow citations to their sources. |
| `user-needs.xlsx` — Scope and evidence, delivery | DEC in text | 0–1 | Delivery decision is Deferred or Will not address. Cite a DEC for Will address when available. | Read the linked **Decision** and **Why** for the team's choice and reason. |
| `participants.xlsx` — User group IDs | `UG` | 1+ | Before use | Groups represented by the participant. |
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
| `constraints.xlsx` — Constraint | Limit and practical effect. May cite a DEC or DOC for an approval condition | 1 | At capture | Explain who or what can change the constraint where relevant. |
| `research-questions.xlsx` — Decision informed | Decision to be made in prose; DEC if already recorded | 0+ | Decision explanation required; an existing DEC is optional | A research question can precede the decision. Do not invent a DEC to fill a gap. |
| `research-plan.xlsx` — Protocol path | Exact protocol for the row’s RND ID | 1 | Before use | Locates the executable round protocol, for example `research/RND-002/protocol.md` for `RND-002`. It holds the method, planned start date when known and lead. |
| `research-sessions.xlsx` — Consent reference | Applicable restricted consent evidence | 1 | Required before participant research | Matches the participant/session and permitted use; do not expose contact details. |
| `research-sessions.xlsx` — Current transcript link | Exact current transcript-file path or version-specific URL | 0–1 | Required for Machine-generated, Checked or Corrected; blank for Not applicable or Not available | Transcript status describes this one file only. Historical evidence keeps its own exact older source pointer. |
| `research-sessions.xlsx` — Recording and notes links | Exact recording and notes paths or version-specific URLs for the session | 0+ | When recordings or notes are kept | Separate multiple links with `; `. Each link identifies an exact file. |
| `user-journeys.xlsx` — Link | Exact diagram or text description for JNY ID + Version | 1 | Before use | Use the matching version description for the readable equivalent, groups and relevant decisions. Match graphic and text to that version. |
| `prototypes.xlsx` — Link | Exact retained artefact or a note that opens it | 1 | Before use | Match the PRT ID and Version to the artefact in its original tool or a retained copy. |
| `assumptions.xlsx` — Evidence | ASM in text | 0+ | When a belief is superseded | List the replacement ASM IDs on the old record. |
| `non-functional-requirements.xlsx` — Requirement | NFR in text | 0+ | When a criterion is superseded | List the replacement NFR IDs on the old record. |
| `non-functional-requirements.xlsx` — Source | UN in text | 0+ | A user need informs the criterion | Cite the specific need alongside any applicable standard. |
| `business-rules.xlsx` — Rule | BR in text | 0+ | When a rule is superseded | Keep its wording and unresolved exceptions. List each exact successor BR ID, or flag an unknown successor. Check for self-links and cycles. |
| `business-rules.xlsx` — Source | Authority citation; DOC/DEC if referenced, otherwise exact source and section | 1 | Before use | Explains the rule’s authority; it is not an ID-only field or proof the rule is implemented. |
| `non-functional-requirements.xlsx` — Source | Standard or obligation. DOC or DEC when cited. | 1 | Before use | Explain applicability and give the exact version or section when needed. Cite verification observations in Verification. |
| `project-sources/source-register.xlsx` — File or URL | Exact file location or direct page URL | 1 | Before use | Register metadata does not replace checking the exact cited source version and passage. |
| `findings-and-observations.xlsx` — Evidence and source | SES or DOC with exact source version or path and locator. An FND row may cite an existing EV row. | 1+ | Before reliance or Reviewed | A FND row identifies the supporting observations and sources. Follow every cited EV to its exact source. Register non-session sources as DOC. |
| `findings-and-observations.xlsx` — Evidence and source | RQ, UG, RND, SES and exact JNY or PRT ID with Version | 0+ | When needed to explain scope | Cite the question, groups, round, sessions or design version the row concerns. Include the limits that affect reliance. |
| `decisions.xlsx` — Why | EV, FND or DOC for support. Other listed prefixes for important alternatives or affected records. | 0+ | Cite recorded support and important alternatives when available. State material gaps. | Follow evidence chains and cite the exact version and passage of a DOC source. Use the affected record’s DEC link where available. |
| `decisions.xlsx` — Superseded by | DEC | 0+ | Required when replacements exist; blank Superseded is a gap | Exact replacing decisions; retain the old rationale; no self-links or cycles. |
| `success-measures.xlsx` — Outcome IDs | OUT | 1+ | Before use | Outcomes the measure helps assess. |
| `success-measures.xlsx` — Baseline | EV in text | 0+ | Required when asserting a recorded baseline; otherwise Not yet established | Evidence for the baseline value, period and applicable population. |
| `success-measures.xlsx` — Source and method | DOC + version/location, or SES in text | 1+ | Required for an established measure; state an unresolved source gap otherwise | Describes how results are collected; chosen data sources need applicability and access checks. |
| `success-measures.xlsx` — Results | EV and exact dashboard or report links | 0+ | When citing recorded results | Give the snapshot, date and filters. Follow EV records to the underlying source. |
| `success-measures.xlsx` — Results or affected field | DEC in text | 0+ | When a decision changes the measure | Link decisions that change the definition, target or interpretation. |
| `research/RND-*/protocol.md` — Round ID in heading | RND in research-plan.xlsx | 1 | Before use | Must match the parent round and folder; does not create a second round record. |
| `research/RND-*/protocol.md` — Plan the round | DOC + exact version in text | 1+ when using existing data sources | When existing data sources are used | Record selection and coverage. Research plan records the round’s question and group IDs. |
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
| `use-cases.xlsx` — Interaction | UC in text | 0+ | When replacements exist | Cite exact successor IDs and flag unknown replacements. Check for self-links and cycles. |

## Reverse lookups

To find related records, search the field that owns the relationship. Compare exact IDs and versions. Check how much of the record set you could read before reporting that a match is absent.

| To find… | Read the owning relationship |
|---|---|
| Findings answering a question | findings-and-observations.xlsx → Evidence and source cites the exact RQ ID |
| Findings from a round | findings-and-observations.xlsx → Evidence and source cites the exact RND ID or an SES in that round, including citations through an EV row |
| Findings about a retained design | findings-and-observations.xlsx → Evidence and source cites the exact JNY/PRT ID and version |
| Sessions in a round | research-sessions.xlsx → Round ID = exact RND ID |
| Sessions testing a prototype | research-sessions.xlsx → Prototype versions contains the exact PRT ID and version |
| Prototypes exploring a journey | Check decisions citing both versions, or follow the prototype register link to any version note citing the exact JNY ID and version. |
| Current fulfilment assessment of a need | user-needs.xlsx → ID = exact UN ID. Read Fulfilment and Scope and evidence on that row. |
| Scope items governed by a decision | in-scope.xlsx and out-of-scope.xlsx → Why cites the exact DEC ID |
| Decisions on a specific journey version | decisions.xlsx → Why cites the exact JNY ID and version. Also follow DEC references in the matching journey description. |
| Use cases for a need or group | use-cases.xlsx → User need IDs or User group IDs contains the exact ID |
| Decisions based on a finding or affecting a design | decisions.xlsx → Why for supporting citations and the exact JNY/PRT ID and version. Check the DEC link in the affected record when available. |

## Check and repair project records

1. Start with the record or handover under review. Open its owner and sources. For a project-wide check, inspect the full set of records in scope, including superseded records that a current claim cites. Check the project README for its framework version.
2. Check unique IDs, exact versions, links, replacement cycles, conflicting scope entries, workbook controls and the [completion requirements](files/).
3. Check the evidence for claims, research consent and source access. For tracked fulfilment, use the [user needs guide](files/user-needs.md#assess-whether-the-service-meets-the-need). For survey files and boards, use the [research protocol](research-protocol.md#discussion-guides-surveys-and-whiteboards).
4. When authorised, fix clear errors with a verified source or documented upgrade. Preserve records and history. Take disputed evidence, consent, judgement and uncertain matches back to the team.
5. Reopen changed records and check their values, controls and links. Report what was checked, what was fixed and what is still unresolved.

Use [AI guidance](../ai-guidance.md) when a tool helps read or edit records.
