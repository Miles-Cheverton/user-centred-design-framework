# Record conventions

Use only the sections relevant to the task. Locate live owners via the [document tracker](../document-tracker.xlsx); starter names identify record types. Apply documented local equivalents. Use the relevant [record guide](../how-to/README.md#record-guides) for fields and statuses.

## Edit records

- Add records in the first empty named-table row under the headings; use the ID examples in column header comments or the instruction above the table, not as records. Ignore genuine legacy OVERWRITE ME example rows. Extend the table and its controls when needed.
- Check actual headers, allowed values and IDs before editing; recheck pasted values. Preserve [extra columns](ai-guidance.md#read-and-preserve-extra-workbook-columns), controls and unrelated records.
- Complete relevant Markdown prompts. Use YYYY-MM-DD for dates. Keep current information first; append dated historical notes or link longer notes. Preserve earlier evidence and wording in version history and record consequential choices in [Decisions](../how-to/project-setup-and-management.md#decisions).

## Stable identifiers and owner lookup

For new records, use the prefix below in uppercase, a hyphen and a number of at least three digits, starting at `001`. Check the full ID for the correct owner, spelling and stray whitespace, including invisible spaces. Respect explicitly documented local ID conventions and mappings when a team has adapted the starter. Check existing and retired records before allocating another ID. Keep the ID when a record moves.

| Prefix | Concept | Default owner from project root | Record key |
|---|---|---|---|
| `SCP` | Scope item | `scope.xlsx` | ID |
| `OUT` | Outcome | `outcomes-and-measures.xlsx` · Outcomes | ID |
| `UG` | User group | `user-groups.xlsx` | ID |
| `UN` | User need | `user-needs.xlsx` | ID |
| `UC` | Use case | `use-cases.xlsx` | ID |
| `STK` | Stakeholder | `project-people.xlsx` | ID |
| `TM` | Team member | `project-people.xlsx` | ID |
| `PAR` | Participant | `participants.xlsx` | Participant ID |
| `CON` | Constraint | `constraints.xlsx` | ID |
| `DEP` | Dependency | `dependencies.xlsx` | ID |
| `ASM` | Assumption | `assumptions.xlsx` | ID |
| `RSK` | Risk | `risks.xlsx` | ID |
| `RQ` | Research question | `research-planning.xlsx` · Research questions | ID |
| `RND` | Research round | `research-planning.xlsx` · Research rounds | ID |
| `SES` | Research session | `research-sessions.xlsx` | Session ID |
| `EV` | Independently cited observation or measurement | `findings-and-observations.xlsx` | ID |
| `FND` | Conclusion reached by the team | `findings-and-observations.xlsx` | ID |
| `JNY` | Journey or map | `design-artefacts.xlsx` | ID + Version |
| `PRT` | Prototype | `design-artefacts.xlsx` | ID + Version |
| `BR` | Business rule | `business-rules.xlsx` | ID |
| `FR` | Functional requirement | `requirements.xlsx` | ID |
| `NFR` | Non-functional requirement | `requirements.xlsx` | ID |
| `DEC` | Decision | `decisions.xlsx` | ID |
| `MET` | Success measure | `outcomes-and-measures.xlsx` · Success measures | ID |
| `TERM` | Glossary term | `glossary.xlsx` | ID |
| `DOC` | Source outside a research session | `project-sources/source-register.xlsx` | ID |

Use one SCP sequence and one current row per scope item. When the team changes its scope, keep the ID and update **Scope** and **Why** on that row. For a material boundary change, record the earlier position and rationale in the decision and cite its DEC ID.

Journeys and prototypes use the ID and exact Version, for example `PRT-001 v2`. Keep each retained version discoverable. Use Status to find selected versions. Check the session or research evidence to establish which version people actually used.

## Classification and status rules

In the combined workbooks, identify each row using its ID, classification and, for design artefacts, its exact version. Use the full owning table to check IDs before filtering by type. A filter is a view of records in that table.

| Workbook | Required classification | ID and status rules |
|---|---|---|
| [Scope](../how-to/project-setup-and-management.md#scope) | **Scope**: In scope or Out of scope | SCP ID; one current row per item. Record an unresolved boundary in the team's questions or pending work until its classification is confirmed. |
| [Project people](../how-to/project-setup-and-management.md#project-people) | **Relationship to project**: Team member or Stakeholder | TM for Team member, STK for Stakeholder. A person may have distinct role records. Keep each role's ID and do not merge automatically based on names. |
| [Design artefacts](../how-to/design-and-development.md#design-artefacts) | **Type**: Journey or map, or Prototype | JNY for Journey or map, PRT for Prototype. Journey or map: Draft, Reviewed, Selected, Discarded, Superseded. Prototype: Draft, Ready for research, Tested, Selected, Discarded, Superseded. The key is ID + Version. |
| [Requirements](../how-to/design-and-development.md#requirements) | **Type**: Functional or Non-functional | FR for Functional, NFR for Non-functional. Both use Proposed, Agreed, Superseded, Withdrawn. Verification is checked separately from Status. |

Check each live row against its prefix, required classification and allowed status, including values entered by pasting or importing. Report blanks, invalid combinations and conflicts with their locations. Confirm which classification or ID is wrong before repairing a mismatch. Preserve separate ID sequences for TM/STK, JNY/PRT and FR/NFR. Where a genuinely different type of requirement replaces an existing one, retain the old record as Superseded and set **Superseded by** to the replacement ID. Leave disputed records open for team review.

## Workbooks with separate sheets

The document tracker identifies one location per workbook. Open the named sheet and its Excel table for the specific record type.

| Workbook | Named sheets | Relationship |
|---|---|---|
| [Outcomes and measures](../how-to/project-setup-and-management.md#outcomes-and-measures) | Outcomes (table `outcomes`, OUT), Success measures (table `successMeasures`, MET) | A measure cites outcome IDs. An outcome can have several measures. |
| [Research planning](../how-to/research-and-evidence.md#research-planning) | Research questions (table `researchQuestions`, RQ), Research rounds (table `researchPlan`, RND) | A round cites research question IDs. A question may be investigated in several rounds. |

Check all relevant sheets for the task, including populated rows outside their tables. Before declaring a record absent or unique, check sibling sheets for misplaced IDs. Check ID prefixes and each table's own fields and status rules. Preserve the other sheet and its table when saving. Keep session and participant records in their separate owning workbooks.

## References, blanks and replacements

- In an ID-only field, enter complete IDs. Separate multiple IDs with a semicolon and space, for example `UG-001; UG-002`. Cite prose, sources and versions in the fields intended for them.
- A blank optional field means the information is unrecorded. Flag missing information that the team needs before relying on the record.
- When a record is Superseded, retain its original ID and meaning; enter the exact successor(s) in **Superseded by**. Use complete IDs (JNY/PRT ID + Version for design artefacts). Do not repeat replacement links in prose. Flag unknown successors, wrong types, self-links and cycles. UN, RQ, DEC, DOC, ASM, BR, FR/NFR, FND/EV, UC and design artefacts have this field. For group splits/merges use dated prose in Description; do not invent a replacement field.
- If a team confirms overlapping needs are equivalent, keep the better-established agreed ID and link the duplicate as Superseded by it. Retain original evidence and copy or link agreed relevant supporting evidence to the survivor; do not transfer fulfilment or delivery decisions automatically. Check possible matches with the team before creating a duplicate. A genuinely separate new candidate can stay Proposed with the potential overlap noted in Scope and evidence. For a partial change to a decision, agree and record the complete continuing position in the new DEC, including unchanged parts and relevant records/sources, then supersede the old DEC.
- Withdrawn is historical and requires no successor: retain the ID and permitted reason where the owning guide specifies. Check current claims that actually rely on invalidated or superseded records; historical citations are not a defect. For partly replaced sources, read the recorded replacement scope.
- Use local framework IDs for record identity. Qualify previous or external IDs with their source/tool in existing Source, Evidence or descriptive fields, or a team-added column mapped by ID. Do not put foreign IDs in canonical ID relationships.

- For retained sources, use an exact path relative to the project root or a version-specific URL. Markdown links are relative to their own file. Use a cross-project source or comparison only when specifically authorised; name the other project and never assume its facts apply here. Owner and reviewer names are descriptive text.

## Canonical relationships

Use the owner lookup for exact IDs. Resolve workbooks through the tracker and match the actual named fields. In ID-only fields use semicolon-separated IDs. Other fields can contain citations in text. A design citation always includes ID + Version. Follow each cited record to its underlying source. Below are the owning fields, their targets and when to record a link. The [record guides](../how-to/README.md#record-guides) describe the remaining fields and completion rules.

| Owner — field | Target or reference | When needed |
|---|---|---|
| Scope — Why | DEC; governing source | Established or materially changed boundaries; retain earlier scope in the decision. |
| Outcomes (Outcomes and measures) — User need IDs | UN | Related needs, if established. |
| User groups — Description | EV/FND; related UG | When useful; cite dated group splits/combinations. |
| User needs — User group IDs | UG | Before use. |
| User needs — Supporting record IDs | EV/FND | Evidenced requires a current Reviewed FND with usable support or source-verified usable EV agreed by the team; Draft alone is insufficient. |
| User needs — Superseded by | UN | Replacement need(s). |
| User needs — Scope and evidence | EV/FND; exact build or JNY/PRT + Version, where applicable | Assessed fulfilment: dated result, groups/routes/context, scope and unmet part. |
| User needs — Scope and evidence | DEC | Required for Deferred or Will not address; cite for Will address when available. Read Decision and Why to distinguish intent from fulfilment. |
| Participants — User group IDs | UG | Before use; does not establish roles actually represented in sessions. |
| Assumptions — Evidence; Superseded by | EV/FND; replacement ASM | Evidence and reason when assessed; exact successor in Superseded by. |
| Constraints — Source; Constraint; Flexibility | Exact authority/section, DOC/DEC where relevant | Authority before relying on limit; practical effect and approval conditions; mark No longer applies when confirmed and record dated reason. |
| Dependencies — Dependency | Affected FR/UN/DEC or other record IDs, milestone/delivery-work reference where known | What is needed, who provides it and work blocked or affected. |
| Research questions (Research planning) — Decision informed; Superseded by | Decision in prose, DEC if recorded; replacement RQ IDs | Decision explanation required; replacement if superseded. Do not invent a decision ID. |
| Research rounds (Research planning) — Research question IDs; User group IDs; Protocol path | RQ; UG; exact protocol for RND ID | Questions and protocol before use; groups when relevant. No-participant study: explain scope in protocol. |
| Research sessions — Round ID; Participant IDs; User groups represented; Prototype versions | RND; PAR; UG; PRT + Version | Round required; coded attendees, actual represented groups and exact tested versions when known. Blank represented groups means unknown; map codes to groups in notes when needed. |
| Research sessions — Consent reference | Restricted matching consent evidence | Before participant research. |
| Research sessions — Current transcript link | Current exact transcript path/version-specific URL | Required for Machine-generated, Checked or Corrected; blank for Not applicable/Not available. Historical citations retain earlier exact source. |
| Research sessions — Recording and notes links | Exact session paths/version-specific URLs | When retained; notes support actual role-to-group mappings, routes and circumstances. Separate links with semicolon and space. |
| Findings and observations — Evidence and source | SES/DOC exact version/file and locator; EV for FND | Before relying on evidence or setting Reviewed. For Withdrawn, keep permitted citation and reason or permitted explanation of deletion. Non-session sources use DOC. |
| Findings and observations — Evidence and source | RQ, UG, RND, SES, JNY/PRT + Version | When needed for scope; RQ required for an Answered question, supported by current Reviewed FND with usable evidence. |
| Findings and observations — Superseded by | Replacement FND/EV of the appropriate type | On supersession. |
| Design artefacts — Link (Journey or map) | Exact matching JNY diagram or description + Version | Before use; check graphic and text convey the same version. |
| Design artefacts — Link (Prototype) | Exact PRT version artefact or note that opens it | Before use; check original tool or retained copy. |
| Design artefacts — Superseded by | Replacement JNY/PRT ID + Version | On supersession; matching type. |
| Use cases — User group IDs; User need IDs | UG; UN | Groups before reliance; established related needs if known. |
| Use cases — Interaction; Superseded by | EV/FND; FR or delivery/acceptance link; replacement UC | Observed claims; handoff to development; successor in Superseded by. Do not duplicate delivery records or infer fulfilment from description. |
| Business rules — Source; Superseded by | Exact governing authority/section, DOC/DEC where relevant; replacement BR | Authority before use; successor in Superseded by; retain original wording and unresolved exceptions. |
| Requirements — Source | Applicable authority/section/version (DOC when cited); UN/UC/BR/DEC when established | Required basis before reliance on agreed FR/NFR; distinguish criterion from rationale. |
| Requirements — Superseded by | Replacement FR/NFR | On supersession; flag unknown successor. |
| Requirements — Verification | EV with date, exact test/build/design version or bounded scope; relevant test/acceptance links | When recording a check; trace to underlying source, distinguish previous result from current verification. |
| Decisions — Why; Superseded by | EV/FND/DOC, affected/alternative records and known UN; replacement DEC | Cite available evidence, alternatives and rationale, including limits; replacement if superseded. |
| Success measures (Outcomes and measures) — Outcome IDs | OUT | Before use. |
| Success measures — Baseline | EV | Evidence for asserted value, period and population; otherwise Not yet established. |
| Success measures — Source and method | DOC exact version/location or SES | Established measure; report unresolved source gap. |
| Success measures — Results | EV and exact report/dashboard link | When recorded: date, snapshot and filters. |
| Success measures — Results or affected field | DEC | When a decision changes definition, target or interpretation. |
| Source register — File or URL; Superseded by | Exact source location; replacement DOC | Before reliance; replacement when known, keep historical source. |

For Markdown artefacts, use the same IDs as the register and the actual guide/template headings.

| Artefact — field | Target or reference | When needed |
|---|---|---|
| `research/RND-*/protocol.md` — heading; Plan the round | Matching RND; DOC + version; ASM and MET for hypothesis/test | Match parent round; source selection/coverage when using existing data; assumption, expected result and measure for hypothesis. |
| Protocol — Materials used | JNY/PRT + Version; exact material paths/URLs, DOC for cited non-session source | Identify planned/used versions; session records own actual tested version. |
| Protocol — Consent and storage | Exact participant information and consent materials; restricted consent location and approved storage/roles | Participant research; storage/roles for retained materials. |
| `journeys/JNY-*/v*/description.md` — heading; User group IDs; Graphic | Matching JNY + Version; UG; exact graphic path/version-specific URL | Before use. |
| Journey description — Sequence: Handoff or backstage dependency; Difficulty or relevant need; Evidence IDs | DEP; UN; EV/FND | Relevant established dependencies/needs; evidence for observed claims. |
| Journey description — Interpretation and status | ASM/DEC | Where relevant; the register owns version Status. |
| Optional prototype note | Matching PRT + Version, retained artefact link; related JNY + Version, DEC/RQ/UN | When used; related records when useful. |

## Reverse lookups

Search the owning fields above for whole IDs and exact versions. Trace both directions, including indirect references and text citations; report access gaps. In particular:

- Find measures in **Success measures → Outcome IDs** (OUT); rounds in **Research rounds → Research question IDs** (RQ). Check sibling sheets for misplaced records.
- Find answers via **Findings and observations → Evidence and source** citing the RQ; an Answered question needs a usable current Reviewed finding, even when no FND appears in the question row. Find round findings through RND, SES in that round, or EV; design findings through exact JNY/PRT versions.
- Find actual session coverage through **Research sessions → User groups represented**, Participant IDs and Recording and notes links; distinguish groups participants may represent from those actually represented. Blank is unknown.
- For decisions about needs, scope, requirements and design versions, check **Decisions → Why** and the affected row's DEC link; a shared finding alone does not link another need to the decision. For prototypes exploring journeys, check decisions citing both exact versions or the prototype note's journey link.
- For current need assessment read **Fulfilment**, **Scope and evidence** and **Delivery decision**. For requirements read **Type**, **Status**, **Source** and **Verification** separately. For withdrawn FND/EV, follow all dependent citations below.

## Trace withdrawn evidence

Keep withdrawn IDs, permitted reasons and historical citations. Do not recover removed material. Check Superseded records similarly where a current claim still materially relies on an earlier basis.

1. Find records citing the exact withdrawn or invalid EV/FND or other affected basis record (direct references in structured fields, text and approved tools). Distinguish historical references, material current dependence and uncertainty. Report current affected claims, their locations and remaining usable evidence; historical citations are not defects.
2. Follow a material dependency onward only if the affected part loses its current support or support is uncertain. Where independently verified evidence still supports that same claim and scope, note that support and stop that branch. Avoid repeated records and cycles; do not assume that a remaining citation establishes support. Leave judgements to the team.
3. For affected findings, read RQ IDs in **Evidence and source**; check each affected Answered question for another current Reviewed finding with usable support. Include any unresolved question affecting the decision under review.
4. When authorised, append a dated review note in the existing rationale/evidence field (Decision informed for RQ; Verification or Source for requirements). Preserve recorded statuses until people reassess. Report gaps, including inaccessible or uncertain links.

Apply this check to an invalid source, corrected observation, changed scope or confirmed withdrawal. [Findings guide](../how-to/research-and-evidence.md#withdraw-a-finding)

## Check and repair project records

Use the tracker, actual registers and relevant record guides. Identify competing owners or broken links. Unused starter registers and unlisted optional materials are not defects. For a requested or automatically refreshed [project health report](check-evidence-and-records/SKILL.md#create-or-refresh-a-project-health-report), report population and access by owner or sheet as well as actual issues.

A **quick structure check** inspects actual record rows, owner/schema, IDs and keys, required fields, classifications, controlled values, workbook dropdowns and table controls, misplaced/orphan rows, replacements/cycles, referenced record IDs, links and recorded totals (including excluded rows). It does not open underlying research or other raw sources, assess current fulfilment or establish that evidence is usable. Report this limit. Flag possible reliance on superseded or withdrawn records for evidence review without assuming historical citations are defects. A full integrity check also verifies actual source evidence, applicability and affected claims.

- Check all populated rows and relevant sibling sheets, including rows outside tables, incomplete records and metadata-only orphans. Check fields, types, controlled statuses, IDs, replacements/cycles, required information, links, versions and workbook controls. Check [extra columns](ai-guidance.md#read-and-preserve-extra-workbook-columns) against IDs. Distinguish optional blanks from information needed for a stage, status or claim.
- Check conflicting scope/classifications, wrong-sheet records, approved consent, actual research coverage and exact current evidence. Flag material current reliance on Superseded or Withdrawn bases and give successor(s) if known; distinguish historical citations. Flag Selected design versions if their current basis is missing, not just because a DEC link is absent. Trace material withdrawal effects and affected Answered questions. Check need existence, fulfilment, evidence, scope and delivery decisions separately; compare recorded totals with independent counts and report excluded rows/reasons and which claims are currently supported. Check requirement verification against actual version and scope.
- Repair only authorised, established errors. Preserve records/history and leave new findings, interpretations and disputed choices to the team. Reopen changes to verify values, controls and links. Report confirmed problems with exact locations and any coverage limits.

### Check for duplicate IDs

Scan full owning rows, including retired and populated outside-table rows. Skip blank or genuine legacy example rows. Check expected prefix, numeric format/documented local mapping and stray or invisible whitespace. A key is normally the ID; for design artefacts use ID + Version. Check both types in combined workbooks and appropriate sibling sheets. Distinct roles and versions are not duplicates; conflicts for the same key are. Report each duplicated key and every workbook, sheet and row occurrence, plus affected citations where known. Leave disputed IDs and dependent records unchanged until resolved.

Use [AI guidance](ai-guidance.md) when a tool helps read or edit records.
