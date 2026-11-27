# Research and evidence

Plan research, retain its sources and record what the team learns. People interpret the evidence and agree conclusions. Use the [document tracker](../document-tracker.xlsx) to find the workbooks below.

- [Plan research](#research-planning) and [prepare a round](#research-protocol).
- [Record participants](#participants) and [sessions](#research-sessions).
- [Analyse evidence](#evidence-and-interpretation) and [record findings and observations](#findings-and-observations).
- [Register sources](#source-register) and [capture learning from meetings](#capture-what-changed-in-a-meeting).

## Research planning

**Workbook:** `research-planning.xlsx`. Use separate Research questions and Research rounds sheets. Each round can address several questions.

### Research questions

Write a question that research can answer. Leave room for an unexpected answer.

| Field | What to enter |
|---|---|
| ID | Stable RQ ID, such as `RQ-001`. |
| Question | What the team needs to learn. |
| Decision informed | What the answer will help the team decide or understand. |
| Status | Open, Investigating, Answered, Superseded or Withdrawn. |
| Superseded by | Exact replacement RQ IDs. Flag an unknown successor for a superseded question. Leave blank for a withdrawn question. |

Plan to answer the question in time for the decision.

| When | Action |
|---|---|
| Work on the question starts | Investigating. |
| A current Reviewed finding supports the answer | Answered. Cite the RQ ID in the finding’s **Evidence and source**. |
| Supporting material is invalidated | [Check affected evidence](#trace-withdrawn-evidence). If support is lost or unclear, keep the status until the team reviews it; add a dated review note in **Decision informed** when authorised. Return to Open or Investigating when agreed. |
| The question is replaced | Superseded; use **Superseded by**. |
| No longer needed, no replacement | Withdrawn; record date, reason and any DEC ID in **Decision informed**. Keep the history. |

### Research rounds

| Field | What to enter |
|---|---|
| ID | Stable RND ID, such as `RND-001`. |
| Research question IDs | One or more RQ IDs the round addresses. |
| User group IDs | Planned UG IDs. For a study without participants, leave blank and explain the scope in the protocol. |
| Status | Proposed, Preparing, Ready, In progress, Analysing, Complete or Cancelled. Use Ready when materials, access and arrangements are in place. |
| Protocol path | One protocol for the round, such as `research/RND-001/protocol.md`. |

Set the status to Analysing while substantive evidence awaits review and Complete once the team finishes its analysis and records the findings. Follow the [round protocol](#research-protocol) and [close the round](#analyse-and-close-the-round).

## Research protocol

Keep one plan per round and link it from the Research rounds sheet. Create a folder for the round, for example `research/RND-001/`. Copy [protocol.md](../research/templates/protocol.md), and only the empty [recordings](../research/templates/recordings/) and [transcripts](../research/templates/transcripts/) folders if approved for your storage. Then copy any optional method templates you need, or link existing materials. Set the actual round ID in the protocol heading. Never copy prior sessions, recordings or participant records as a new round.

### Prepare the round

- Record the method, lead, start date when known, recruitment or source selection and arrangements for the team debrief.
- Consider who the plan might miss, including people who use a different channel, need support or use assistive technology. Plan how to include them where relevant to the question.
- Identify the exact design versions, prepare materials and confirm consent, access and retention. When testing a hypothesis give the ASM ID, any relevant MET ID and the result that would support or challenge it in the protocol or linked delivery test.

### Discussion guides, surveys and Whiteboards

Link the materials you already use in the protocol. Copy only the optional templates you need from [research templates](../research/templates/) into the round folder or existing approved workspace. Keep the exact versions people actually used.

| Material | What to keep |
|---|---|
| [Discussion guide](../research/templates/discussion-guide.md) | Questions, tasks, follow-up prompts and version used. |
| [Survey questionnaire](../research/templates/survey-questionnaire.md) | Exact wording, options, branching and question IDs. Map IDs to export columns and record changes during fieldwork. |
| Original survey export | Original format in approved storage. Link the export. When cited, register the collection period, questionnaire version and filters as a DOC source. |
| [Survey analysis](../research/templates/survey-analysis.xlsx) | One row per result with exact source and locator, method, limits and unit. Give the numerator and denominator where the calculation uses them. |
| Whiteboard | Working board link in the protocol. When cited, retain the exact snapshot or version, register its relevant area and access limits and cite its DOC ID. Keep design boards with their design version. |

Use clear filenames such as `discussion-guide_v01.md` or `2026-11-16_RND-001_whiteboard_v01.png`. An approved tool can hold the saved version.

People choose the calculations and interpret results. AI can run specified calculations. Explain what a percentage counts and how skipped answers affect its denominator. Leave unused numerator or denominator cells blank, and distinguish unknown values from zero. For an anonymous survey, retain the information and consent wording, report coverage at the level the survey supports and count responses separately from people in coded sessions. Link a response ID to a participant only when the protocol permits it and a mapping exists.

### Before and during a participant session

Allocate the session ID and participant code. Provide accessible information, check accessibility arrangements and agree consent before research, covering recording, observers, transcription, AI processing and sharing where applicable. Keep a restricted consent reference that matches the session.

Follow up on what people say, distinguish what happened from your interpretation in the notes, and record material changes or interventions. Collect only material needed for the questions. Where appropriate and permitted, record the participant codes, roles, UG IDs, routes and relevant circumstances actually represented.

## Participants

**Workbook:** `participants.xlsx`. Give each participant a code and record which groups they may represent before linking sessions.

| Field | What to enter |
|---|---|
| Participant ID | Unused PAR code, such as `PAR-001`. Reuse it across sessions when the research arrangements permit linking them. |
| User group IDs | Exact UG IDs for groups the participant may represent; this is not evidence of actual session coverage. |

Keep names, contact details and the identity key in separate restricted storage. A participant code may still identify someone through recordings or consent links. Record relevant recruitment characteristics in approved recruitment or session records. Participants can represent different groups in different sessions, and later changes to the register leave historical coverage as recorded.

## Research sessions

**Workbook:** `research-sessions.xlsx`. Give each session that took place a row associated with exactly one round.

| Field | What to enter |
|---|---|
| Session ID | Stable SES ID, such as `SES-001`. |
| Round ID | Exactly one RND ID. |
| Participant IDs | PAR codes of those who took part. Leave blank for sessions without participants. |
| Date | Session date in YYYY-MM-DD form. |
| Prototype versions | Exact versions tested, such as `PRT-001 v1; PRT-002 v3`. Keep one session row and identify the version each observation concerns. |
| Consent reference | Restricted session consent record when it involves participants. |
| Current transcript link | Exact path or version-specific URL for one transcript. |
| Transcript status | Not applicable, Not available, Machine-generated, Checked or Corrected. |
| Recording and notes links | Exact paths or version-specific URLs. Separate multiple links with a semicolon and a space. |
| User groups represented | Actual known and approved UG IDs represented in this session. Required before claiming that group coverage; leave blank if unknown, unrecordable or not applicable. |

Machine-generated, Checked and Corrected require a current transcript link. Leave the link blank for Not applicable or Not available. Record participant-to-group mappings, roles, routes and circumstances in the notes where relevant and permitted. Do not infer actual groups from recruitment or a participant’s current register entry. A blank group field in a participant session means coverage is unestablished, not that nobody from the group attended.

### Record sessions and discovery chats

Log a session whenever you learn about people's experience of using, providing or supporting the service, including informal discovery chats. Follow the round's consent arrangements. For a conversation about remit, priorities or constraints, use agreed meeting notes and cite the relevant passage. Register the notes when they need a DOC citation. A policy lead explaining a funding limit can inform a [constraint record](project-setup-and-management.md#constraints). See [meeting recording](#capture-what-changed-in-a-meeting).

Three sessions can include repeat participants. For example, PAR-001 in SES-001, PAR-002 in SES-002 and PAR-001 and PAR-003 in SES-003 represent three different people across three sessions. Link each session's own notes or media. A notes-only session uses **Recording and notes links** with Transcript status set to Not applicable.

### Store and name material

Use the round’s own `recordings/` and `transcripts/` folders where approved, or link exact files in restricted storage. Use the actual date, round ID, session ID and original extension, for example:

```text
2026-11-16_RND-001_SES-003_screen_p01.mp4
2026-11-16_RND-001_SES-003_audio_p01.m4a
2026-11-16_RND-001_SES-003_collection-test_transcript_v01.txt
```

Use `p01`, `p02` and so on for recordings and `v01`, `v02` and so on for transcripts. A non-identifying label such as `collection-test` is optional. Use codes in filenames and retain useful timestamps and coded speakers.

### Update transcript references

Use Checked when a person has checked the transcript against the session source, and Corrected when they have saved a corrected version. Update the link and status together. Retain earlier versions where permitted and keep findings linked to the exact version used. Flag invalidated observations or conclusions. If material becomes unavailable, record the permitted non-identifying reason in the session record or notes and [review affected evidence](#trace-withdrawn-evidence).

## Evidence and interpretation

An EV observation records what someone said, did or measured in context. An FND finding records what the team concluded. A source records what the team received or found. [Assumptions and decisions](project-setup-and-management.md) and [needs and requirements](design-and-development.md) draw on evidence and retain its reference.

### Human analysis before documentation

After testing, bring the researcher, observers and relevant colleagues together. Before reading an AI summary, compare observations, possible explanations and counterexamples. Agree what the evidence supports and note disagreements, limits and open questions. Include learning that challenges the preferred option or remains inconclusive.

Once the team reaches conclusions, use [Capture or update records](../AI-skills/capture-or-update-records/SKILL.md) with its notes and any sources approved for AI use. Ask it to find relevant records and exact passages, propose updates and flag discrepancies. Review anything that could change the conclusion. Save the team's agreed wording and update related needs, assumptions or questions when agreed. With raw material alone, AI can locate requested observations or extracts and people still interpret them.

### Analyse and close the round

Record reasoning, what the team reviewed and open questions in the protocol's **Team debrief**, or link the existing notes. For a finding informed by a board, record the reasoning in text and check what the cited snapshot covers.

Compare planned groups with each session’s **User groups represented** and contemporaneous notes about routes, roles and circumstances. For example, PAR-001 represented UG-003 as a call handler in SES-008. Use the notes to confirm any participant-to-group mapping; an aggregate list does not establish every participant’s role. Flag gaps, unknown or restricted coverage, including people missing from the plan. Carry material gaps into research questions. See [worked research coverage](worked-examples.md#research-coverage-and-external-material).

Mark the round Complete when the team has finished its review and recorded its findings. If it could draw no conclusion, explain why in the debrief and retain unanswered questions.

## Findings and observations

**Workbook:** `findings-and-observations.xlsx`. Use an EV for an observation or measurement that needs its own citation and FND for a conclusion reached by the team. This includes evidence from research and other work.

| Field | What to enter |
|---|---|
| ID | Stable FND or EV ID. |
| Finding or observation | The team's conclusion, or what was observed, said or measured. |
| Evidence and source | Support, contrary evidence, limits and exact source. A finding may cite an existing EV row. |
| Status | Draft while wording or source checks need agreement, Reviewed when the team agrees the wording and confirms the sources were checked, Superseded if replaced, Withdrawn if no longer reliable without a replacement. An EV can have blank status. Verify its source before relying on it. |
| Superseded by | Exact replacement FND or EV IDs when superseded. |

### Make evidence checkable

For every citation give the SES or DOC ID, exact file, version or version-specific URL and timestamp, page, section or range. [Register non-session material](#register-a-source). Add relevant group, question, round or design references to make scope clear. Use exact versions for JNY and PRT references. For example, `SES-003` in `2026-11-16_RND-001_SES-003_screen_p01.mp4`, 00:12:45–00:13:20.

Attribute external conclusions to their authors in the source register or relevant notes. Retain that attribution on any older Draft supplier claim and hold it apart from team findings until the team adopts it. If a source differs from the team's wording, bring the exact passage to the team. Keep superseded records and use the [replacement rule](README.md#when-records-change).

### Check rows below the table

Use [Check evidence and records](../AI-skills/check-evidence-and-records/SKILL.md#choose-the-check) to find records accidentally entered outside the table or incomplete records. Bring confirmed records into the table and check dropdowns.

### Withdraw a finding

When the team confirms that an FND or independently cited EV is invalid, out of scope for continued reliance or otherwise withdrawn without replacement, set its existing row to Withdrawn. Keep its ID, wording and exact citation where permitted. In **Evidence and source**, add a **Withdrawal:** note with date, reason and the agreeing person or team where appropriate. Use withdrawn records for historical explanation only. Follow [retention and withdrawal](#retention-and-withdrawal) if material must be removed.

### Trace withdrawn evidence

Use the [reverse lookups](../AI-skills/record-conventions.md#reverse-lookups) to find actual affected claims and trace any materially affected or uncertain dependencies. Check current independent support for the same part and scope of each claim. Stop a branch when the citation was historical or the affected claim has independently verified support for that scope; report why once. Do not stop merely because another citation exists. Follow RQ IDs in affected findings to check the answers too.

Flag materially affected or uncertain claims for team review. When authorised, add a short dated note in their existing evidence or rationale fields, preserving statuses until the team reassesses them. Distinguish historical citations from current reliance on a superseded or withdrawn basis. Record verified source-level limits in the source register within applicable permissions.

For example, retain FND-505 and its DOC-505 v1 page 4 citation where permitted. Record that the team reviewed a supplier claim and withdrew the finding because the sample did not cover the service's users.

### Check a claim

Identify the claim, decision and users, conditions and version it covers. Follow the findings to the underlying sources. Check how and when evidence was gathered, whether it supports the claim and whether other evidence changes the picture. Report what you checked, what you could access and how a gap affects the decision. Give the question or source needed to resolve it. See [AI guidance](../AI-skills/ai-guidance.md) and [trace withdrawn evidence](#trace-withdrawn-evidence).

## Source register

**Workbook:** `project-sources/source-register.xlsx`.

### File a source

Place supporting documents such as a commissioning brief or policy in [project sources](../project-sources/) or their approved location. Keep research and design material with its own activity. File and register it yourself or ask the assistant to do so within an authorised save.

### Register a source

Add a source when a record needs its DOC citation or version or replacement tracking. Reuse an existing DOC ID when the exact source and version match. For renamed copies, verify identical content, origin and version before reusing the ID. Flag uncertain matches. For a new source enter the next unused ID, title and location, with date or version when known. Verify the entry before saving records that cite it.

| Field | What to enter |
|---|---|
| ID | Stable DOC ID, such as `DOC-001`. |
| Title | Source or page title. |
| Description | Content, origin or supplier where useful, what it supports and its limits. |
| File or URL | Exact path or direct URL. |
| Date or version | Version or date used. For a live page, record the access date and retain an approved dated copy where exact wording matters. |
| Superseded by | Exact DOC IDs of known replacements. Keep earlier rows for their citations. |

Register cited survey calculations separately and link the export. On a cited Whiteboard source, give the snapshot version, area and access limits.

### Decide how much weight to give a claim

Consider the author's authority, evidence, date and applicability to this service and its users. An approved commissioning brief can establish a budget while demand estimates need testing. People judge its weight; AI can find exact passages. In findings, put a claim's limitations alongside its DOC citation and exact locator.

When a replacement covers only part of a source, explain which part in **Description**. If an out-of-date source has no known replacement, say so and leave **Superseded by** blank. Check currency with its owner when unclear. If a withdrawal reveals a verified source-level limit, add the affected scope and relevant EV or FND IDs to **Description**.

## Retention and withdrawal

Follow agreed procedures for participant withdrawal and retention periods. Remove affected copies, including retained versions, when required, and redact or remove identifying words, quotations and source details in related records and notes as required. Where permitted, keep stable record IDs, statuses and a non-identifying explanation in the owning record. Keep source IDs and locators only where permitted. Update affected session links and status, note unavailable DOC locations in **Description**, mark affected links unavailable and remove prohibited locators. Never reconstruct removed material.

Limit access to transcripts, recordings and participant data. Use summaries that protect identities for wider sharing. Ask the team to review observations, findings and downstream claims that rely on unavailable or invalidated material. Record the agreed decisions and remaining usable evidence. See [trace withdrawn evidence](#trace-withdrawn-evidence).

## Capture what changed in a meeting

Record selectively when revisiting the reasons for a choice, options or conditions would help the team. Use the delivery board for routine stand-up actions and blockers. Capture significant decisions while the people involved are there. Keep recordings and transcripts in approved storage and follow the organisation's recording, access and retention rules. Use agreed notes and decisions as the starting point for handover.

1. The delivery manager, business analyst or other note-taker captures what the team agreed, why and what is still open.
2. Use [Capture or update records](../AI-skills/capture-or-update-records/SKILL.md) with the notes and, if approved for AI use, the transcript. Ask it to propose changes to decisions, dependencies and other relevant records. It can find exact passages, identify conflicts and fill dates or names where established.
3. Check proposals in the call or with the decision maker. Keep unresolved options open and flag unclear agreement. Record an agreed choice, scope, reason and open conditions in [decisions](project-setup-and-management.md#decisions). Put an open start date in **Why** and link a dependency if outside action is needed. Cite the exact source and transcript timestamp or section where relevant. One DOC entry can support several records.

For example, a stakeholder meeting agrees a choice and discusses a proposed start date. The delivery manager checks the assistant's draft against the decision maker's confirmation and records the choice, rationale and open date.

## Practice basis

- [GDS research in discovery](https://www.gov.uk/service-manual/user-research/user-research-in-discovery)
- [GDS research planning](https://www.gov.uk/service-manual/user-research/plan-user-research-for-your-service)
- [GDS informed consent](https://www.gov.uk/service-manual/user-research/getting-users-consent-for-research)
- [GDS participant privacy](https://www.gov.uk/service-manual/user-research/managing-user-research-data-participant-privacy)
- [GDS research analysis](https://www.gov.uk/service-manual/user-research/analyse-a-research-session)
- [GDS user needs](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs)
- [GDS discovery](https://www.gov.uk/service-manual/agile-delivery/how-the-discovery-phase-works)

The AI workflow and record links are choices made for this framework.
