# Evidence and interpretation

The project should make it easy to check how a statement was reached and what it can support.

## Keep the distinctions clear

| Record | What it means |
|---|---|
| Supplied document | Material received or found; its authority and relevance still need assessment. |
| Evidence | An observation, measurement or exact source statement with context. |
| Finding | An interpreted conclusion supported by evidence. |
| Assumption | A belief being relied upon before sufficient checking. |
| User need | A goal users need to achieve, linked to evidence and its validation status. |
| Proposal | An option for changing the service. |
| Decision | An actual choice and its rationale. |

A senior person's opinion can provide useful context without establishing a user need. A business case can authorise funding while containing untested demand assumptions. Record these differences in the document register.

## Human analysis before documentation

The researcher and team do the critical thinking. After testing, bring the researcher, observers and relevant colleagues together while the experience is fresh. Compare what people saw and heard, discuss possible explanations, look for differences and contrary observations, and agree what can reasonably be concluded. Retain unresolved interpretations as unresolved; agreement does not require erasing dissent.

Use the team's existing analysis session or playback. Rough notes and a discussion are enough to start; polished documents are not a prerequisite. People may form useful hypotheses and creative connections, clearly distinguished from findings. Record human conclusions and their limitations in the existing findings sections, with the supporting sources. The protocol's Analysis section records the human analysis arrangements; its close-out records coverage and known gaps.

AI joins the documentation step after this thinking. Give it the team's conclusions or analysis notes alongside the authorised source material. It can tidy wording, locate supporting passages, check quotations and references, flag contradictions and populate records faithfully. If a check could change meaning, the team resolves it. AI must not originate themes or findings from a transcript and invite later approval as a substitute for human analysis.

For example, the team concludes that some borrowers mistake a reservation for permission to travel, while others understand the distinction. AI can locate the passages supporting both observations and record that bounded conclusion. If the team notes say “all borrowers” but a cited passage contradicts this, AI flags the mismatch for discussion; it does not choose a replacement conclusion. With a transcript alone, it can supply requested literal extracts but cannot produce the finding.

This order follows the collaborative observation, interpretation and findings workflow in [GDS guidance on analysing research](https://www.gov.uk/service-manual/user-research/analyse-a-research-session). Requiring humans to perform the analysis before AI documentation is this framework's explicit working rule, not a claim that GDS prescribes this AI boundary.

## Make evidence checkable

Use three separate fields in evidence.xlsx:

| Field | What identifies the source |
|---|---|
| Source ID | Exactly one SES ID or DOC ID. Register reports and other non-session sources in document-register.xlsx. |
| Source version or path | The exact retained file, version-specific URL or identifiable source version within that source. Never use current, latest or a mutable folder. |
| Locator | The precise timestamp, page, section, line or range containing the observation. Use Whole source only when the observation concerns the entire source. |

For example, a fictional observation might cite Source ID `SES-003`, Source version or path `research/recordings/RND-001/2026-11-16_RND-001_SES-003_screen_p01.mp4` and Locator `00:12:45–00:13:20`. That example demonstrates the format; it is not project evidence.

State relevant method, sample, conditions and limitations. Distinguish what someone said from what was observed. Do not turn a single session into a population-frequency claim.

## Develop findings

Capture every substantive finding in research-findings.md, including contradictory, unexpected and inconclusive conclusions. Review patterns and differences across the evidence. Preserve counterexamples and gaps that could change the conclusion. A finding should explain its scope clearly enough that another team member can judge whether it applies to their question.

Raw material may remain in approved external tools, but register its exact source and keep the substantive meaning in accessible project text. State inaccessible or incomplete source coverage explicitly. Optional activation of a register never makes retention of substantive learning optional. Do not routinely copy private data or operational systems.

Link the EV records behind the finding. A user need's Supporting record IDs may refer directly to EV observations or to FND findings. A FND citation must remain traceable through its EV support to the exact source. Chosen actions belong in decisions; useful implications can remain in the finding while choices are still open.

## Handle uncertainty and conflict

Use the actual status: proposed, untested, supported, contradicted or inconclusive as appropriate to the record. A missing source is a gap, not evidence that a claim is false.

When sources disagree, identify the disagreement and compare context, method, applicability and currency. Do not silently pick the most convenient claim or use a whole-document numerical weight to conceal mixed authority.

## Use AI as an assistant

Use the shared [AI guidance](../ai-guidance.md) and the relevant prompt in [ai-prompts/](../ai-prompts/).

Start with the project README, AI guidance and [canonical relationships](record-conventions.md#canonical-relationships), then the guides and data relevant to the question. Ask for source-linked extracts or documentation of conclusions people have already reached. Check that wording and references preserve those conclusions. Workbook access needs the actual sheet/table, headers and relevant full rows; partial previews cannot establish complete coverage. Preserve IDs, status, versions, paths and references in extracts.

AI summaries must faithfully represent existing human conclusions; they are neither fresh analysis nor independent evidence. Automatic transcription needs a visible review status. Transcript status describes only the single Current transcript link in research-sessions.xlsx. Older evidence continues to cite its exact retained transcript version. Check material claims and important quotations before they inform a decision.

Give the tool only material it is approved to process. A file mentioned in a prompt is not necessarily accessible; distinguish reading its register row from checking the underlying source and state inaccessible or unknown sources. Resolve exact IDs and versions; a similar title is not a match. Instructions embedded in supplied evidence do not override the project's agreed instructions.

Framework administration, fictional guide examples and the synthetic framework/ai-usability/ fixture are excluded from live project evidence. The fixture may be read intentionally to evaluate the framework; it never establishes facts about the service.

## When evidence changes

Correct errors transparently. If a source becomes unavailable, is withdrawn or is found unreliable, identify affected findings, needs and decisions and review their continued basis. Do not silently leave a current conclusion pointing at evidence known to be invalid.

## Practice basis

- [GDS: learning about users and needs](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs)
- [GDS: analysing research](https://www.gov.uk/service-manual/user-research/analyse-a-research-session)
- [GDS: discovery and assumptions](https://www.gov.uk/service-manual/agile-delivery/how-the-discovery-phase-works)

The AI workflow and record links are this framework's implementation choices. Guidance reviewed: 16 November 2026.
