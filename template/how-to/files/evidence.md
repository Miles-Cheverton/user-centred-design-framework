# Evidence

**Working file:** [evidence.xlsx](../../evidence.xlsx)

Record selected observations and measurements with enough provenance to check them. Use for observations or measurements worth retaining because they support findings, decisions or evaluation.

AI may extract a requested literal observation or locate a passage, with its exact source. People decide what the observations mean through [human analysis](../evidence-and-interpretation.md#human-analysis-before-documentation); an observation register is not permission for AI to infer themes, needs or findings.


## First capture

Enter **ID**, **Observation**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it. The observation cannot support a claim until its exact source and context are recorded.

## Complete a record

1. Record what was observed, without turning the observation into a general conclusion.
2. Enter exactly one SES or DOC in Source ID. Register reports and other non-session sources in document-register.xlsx first.
3. Identify the immutable file or source version in Source version or path and the exact timestamp, page, section or range in Locator. Never substitute a current or latest pointer.
4. Record the relevant date, method, sample and version.
5. State limitations that change how the observation can be used.

For survey evidence, Source ID is the DOC record for the exact dataset or working calculation cited. Locate the observation by sheet/table, question ID, response IDs or cell/range as appropriate. Record questionnaire version, collection period, filters, base count and missing-answer treatment in Context or the cited working method. Do not use a changing dashboard total as a fixed source or infer population prevalence from an unrepresentative sample.

For Whiteboard evidence, use the DOC source and exact retained snapshot/version, then a frame, labelled region or item locator. Distinguish a participant's original observation from a team's interpretation on the board. Cite the original session or dataset where available; the board does not independently verify it. An inaccessible or partly legible board needs an explicit limit, not an invented interpretation.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | EV-001 |
| Observation | The participant looked for an expected decision date after submitting |
| Source ID | SES-003 |
| Source version or path | research/recordings/RND-001/2026-11-16_RND-001_SES-003_screen_p01.mp4 |
| Locator | 00:12:45 |
| Observed on | 2026-11-16 |
| Context | Moderated test of PRT-001 v1 with PAR-001 |
| Limitations | One observed session; does not establish prevalence |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable evidence ID. |
| Observation | At capture | What was observed or measured; keep interpretation separate. |
| Source ID | Before use | Exactly one SES or DOC ID identifying the source session or registered document. Use a DOC record for a report or other non-session source; do not enter a file path or URL here. |
| Source version or path | Before use | One exact immutable file path, version-specific URL or identifiable source version within Source ID. Required for every observation; never use current, latest or a mutable folder. Keep this pointer unchanged when a newer source version appears. |
| Locator | Before use | One precise timestamp, page, section, line or range locating the observation within the exact source version. Required; use Whole source only when the observation concerns the entire source. |
| Observed on | When known or relevant | When the event or measurement occurred, if known. |
| Context | Before use | Relevant method, sample, service or prototype version. |
| Limitations | When known or relevant | Important bounds on what this evidence can establish. |

## Keep it current

Preserve the exact cited source pointer when a new source version appears. Correct transcription or citation errors transparently. If a source is withdrawn, deleted or found unreliable, flag the affected evidence and review dependent findings.

## Completion check

Another authorised reader could locate the source and distinguish the observation from interpretation.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/user-research/analyse-a-research-session)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
