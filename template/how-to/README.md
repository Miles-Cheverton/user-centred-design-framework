# How to use the project foundations

Use the framework to organise research, user needs and decisions so people and AI assistants can work from the same information. Read [why the framework exists](../README.md#why-the-framework-exists).

Choose the route for the work you are doing. Each file guide starts with the small first capture, then the steps and a fictional example. Field detail comes afterwards.

## Frame the work

1. Write the problem in [problem-statement.md](files/problem-statement.md): who experiences what difficulty and why it matters. Keep solutions out of it.
2. Register source documents as you receive or use them. Start with an ID, title and exact file or URL; add role, currency and limits before relying on a claim. Use the [document-register guide](files/document-register.md).
3. Capture the groups, needs, outcomes, boundaries and responsibilities that are actually known. Use the [record catalogue](../README.md#find-a-record) to find their owners; do not fill unrelated registers to complete a checklist.
4. Put consequential unknowns in [assumptions](files/assumptions.md) or [research questions](files/research-questions.md), without inventing confidence or agreement.

## Capture learning

1. After research, the researcher, observers and relevant team members discuss what happened and perform the analysis together. Compare interpretations, examine contrary observations and reach human conclusions before asking AI to document them. Follow [human analysis before documentation](evidence-and-interpretation.md#human-analysis-before-documentation).
2. Capture **every substantive human finding** in [research-findings.md](files/research-findings.md), including contradictory, unexpected and inconclusive learning. Begin with a stable FND ID, the team's conclusion and Draft status. Draft describes the record's maturity, not permission for AI to invent its meaning.
3. Record supporting observations in [evidence.xlsx](files/evidence.md), with exact Source ID, Source version or path and Locator. AI may check the agreed conclusions against authorised transcripts, tidy wording and populate the records. Return meaning-changing discrepancies to the team.
4. Add context, limitations and relevant question, round/session and exact design-version references. Check the documentation reflects the team's analysis before treating it as Reviewed.
5. Record human-established new or changed [user needs](files/user-needs.md) and [assumption assessments](files/assumptions.md) in their owners. A need starts Proposed until people establish its evidence. Record consequential choices in [decisions.md](files/decisions.md).

Do not keep only findings that support the preferred option. An inconclusive result can change what the team should do next and belongs in the record.

## Prepare research

1. Capture the answerable [research question](files/research-questions.md) and what decision it will inform.
2. Create the [round](files/research-plan.md) and its [protocol](research-protocol.md). Complete its question, method, lead, coverage and procedure before marking it Ready.
3. Before participant research, establish the applicable consent and approved data handling. Create coded [participant records](files/participants.md); retain identities and contact details only in the approved restricted system.
4. When a session happens, record its round, participants, actual design version and consent reference in [research-sessions.xlsx](files/research-sessions.md). Link recordings, notes and the single current transcript; set its review status honestly.
5. Follow [Capture learning](#capture-learning). A round is Complete only when its reviewed findings are available to inform work.

The minimal first capture never substitutes for consent, a usable protocol or evidence needed before relying on a result.

For discussion guides, questionnaires, original survey responses, working calculations and Whiteboards, use [the material-storage route](research-protocol.md#discussion-guides-surveys-and-whiteboards). Keep each with its research round, using only the companions that activity needs. Survey exports keep their original format; analysis notes preserve the team's thinking before AI documentation.

## Explore a design

1. Use normal design tools to sketch and compare ideas. Create a [design proposal](files/design-proposals.md) when an option is substantive enough to retain; start with its ID, proposed change and Draft status.
2. Register a [journey or service model](files/user-journeys.md) or [prototype](files/prototypes.md) when it is used in research, informs a significant decision, receives substantive shared review or is handed over. Give that retained version an exact ID and Version.
3. Preserve its location and an accessible text account of its substantive meaning. A journey needs an equivalent text description; a prototype needs its question, tasks, run instructions and simulation limits.
4. Record substantive learning even when the option is discarded. Put findings in their owner and consequential choices in decisions.md. Retain the versions needed to understand them.

Disposable sketches can stay in the working design tool. They do not require an inventory entry unless they cross the retention threshold above; their substantive learning must still be captured. Find prototypes by their Proposal IDs in the prototype register, and findings by their Design versions in research-findings.md.

When a specific service interaction needs describing, use [use-cases.md](files/use-cases.md). Distinguish a current experience from a proposed one. A use case is activated by that need for detail; it is not a mandatory GDS deliverable or a substitute for user needs and evidence.

## Assess whether needs are met

1. Use [user-need-coverage.xlsx](files/user-need-coverage.md) for one current row per active User need ID. Do not copy the need's wording; user-needs.xlsx owns it.
2. Record what the service meets separately from what the team plans to address. A need's Evidenced status establishes support for the need, not its fulfilment.
3. Before claiming Not met, Partly met or Met in full, record EV support, the assessment date and the exact assessed version or scope. Record remaining gaps; unmet needs remain visible.
4. Record the Delivery decision independently. Deferred or Will not address requires a DEC record with the reason and consequences. A plan to address a need does not mean it is met.
5. Before claiming project-wide coverage, reconcile active UN IDs against exactly one current coverage row each. The summary counts recorded rows by each dimension independently; it does not prove that every need is represented or calculate a meaningful completion percentage.

Update the current row on a new assessment of a stated scope. Preserve the prior basis in EV and DEC records so changed conclusions remain understandable; do not add competing current rows or schedule another review solely for the template.

## Record a decision

1. Capture a stable DEC ID and the actual choice in [decisions.md](files/decisions.md). A choice still under discussion stays Proposed.
2. Before treating it as Agreed, record who made it, when, the reasons, material alternatives and consequences. Link the exact supporting or affected records.
3. Update the affected owning record when its meaning changes: for example scope, a selected option or a requirement. Use explicit Superseded by links for replacements; retain the old rationale.

A requirement being Agreed does not make it Met. Non-functional requirements keep agreement and verification separate, with evidence for verified results.

In a meeting, “we should try morning calls” is a proposal, not agreement. Briefly state the consequential choice, who is making it and any material objection before closing the discussion. Silence, sarcasm or an estimate based on a proposed rule does not establish approval. AI can record the choice actually expressed; it must not manufacture consensus. Use the existing conversation, without a separate approval tracker.

## Hand over or prepare a review

1. Use the current agreed decision to establish what is authorised and what remains conditional. Retrieve linked findings and scope from their owning records.
2. Identify any changed service promise and who must act for it to work, including content, operations and supported channels. Discuss material consequences with the relevant people through existing team activities.
3. Bring the current need assessments, unmet needs and operating conditions. Reconcile all active needs before presenting a whole-service view; do not hide declined or unassessed work.
4. Open the exact retained design version and check that its text, graphic and interaction describe the same experience. State anything that cannot be inspected.
5. Separate retained knowledge from source access: an existing reviewed finding may remain available when its recording cannot be accessed. Explain which decision the access gap affects; do not imply fresh verification or demand reconstruction of every source.

For example: “The team selected PRT-201 v3 for further testing. The latest finding concerns v1; the selected version has not yet been tested. Staff capacity remains a condition.” AI may assemble this from existing records; humans interpret its consequences and decide what happens next. Do not create another maintained handover register or duplicate the source records.

## Find and check an answer

See the [worked service handoff](worked-service-handoff.md) for tracing a playback claim back to a source and following the finding forward to a decision and outcome check. In a playback deck or report, cite the relevant finding, need or decision ID beside the claim or in its source notes. Say where the trail stops and what remains open.

1. Locate the concept in the [record catalogue](../README.md#find-a-record). Use [record conventions](record-conventions.md) for exact IDs and relationships.
2. Read the relevant full record, its status and provenance. Follow a finding or need to the supporting EV records and exact sources. State an unavailable or incompletely checked source as a gap.
3. For AI assistance, start with the project README, [AI guidance](../ai-guidance.md) and [canonical relationships](record-conventions.md#canonical-relationships), then only the relevant guides and records. Choose a model-neutral task in [ai-prompts/](../ai-prompts/).
4. Workbook access needs the actual sheet/table, headers and relevant full rows. Preserve IDs, statuses, versions and source paths in extracts. A partial preview cannot establish full coverage or absence.

Use reverse lookups of owned references to find related records. Do not create hand-maintained backlink lists to make an answer easier to retrieve.

For an authorised capture or update, select a [portable procedure](../skills/README.md). Load only the relevant Markdown procedure and its referenced guides; no particular AI model or provider is required.

## Capture a little, retain what matters

**At capture** means the minimum needed to save a recognisable draft. **Before use** means the remaining information needed before the record is relied on, acted on or shared as an established position. The file guide states any earlier or specific condition, including consent and evidence requirements. A draft with blanks is not a complete or validated record.

Activate a record when its relevant activity happens. “Optional” does not mean optional retention of substantive learning: all substantive findings, user needs, consequential decisions, retained options and their meaning belong in the structure. Raw material may remain in approved tools, but exact sources must be registered and the substantive meaning available as accessible text. State coverage and access gaps rather than implying completeness.

Edit project registers directly in Excel; there is no routine CSV exchange step. Preserve an external survey tool's original export in its supplied format, without re-entry or a competing editable copy. Do not routinely copy a delivery backlog, operational system or private data into the project. Link the authoritative source and capture only the project knowledge needed to understand the work.

Update records at the event: learning after research, a choice when made, and a record when its meaning changes. Use existing team review conversations. The template does not create another reporting cycle.

## Reference guides

Each owner file has a guide under [files/](files/). Use these shared references when needed:

- [Record conventions](record-conventions.md): IDs, owner lookup, canonical relationships, blanks and workbook editing.
- [Allowed values](allowed-values.xlsx): workbook dropdown choices and their meanings.
- [Research protocol](research-protocol.md): preparing, running and closing research.
- [Evidence and interpretation](evidence-and-interpretation.md): observations, conclusions and sources.
- [Versioning and decisions](versioning-and-decisions.md): preserving meaningful records and design versions.

GDS and other primary sources inform the practices. The filenames, fields, IDs and dropdowns are this framework's design choices. Each guide links its supporting sources. All worked examples are fictional, not project evidence.
