# Findings and observations

**Guidance revision:** 2026-11-26.2

**Working file (via document tracker)** [findings-and-observations.xlsx](../../document-tracker.xlsx)

## First capture

Use FND for a team conclusion. Use EV for an observation or measurement that needs its own citation. Record what the team learnt or observed and its source in one row, whether it came from research or other work.

People analyse evidence and reach conclusions. AI can help record or check their work. [Human analysis before documentation](../evidence-and-interpretation.md#human-analysis-before-documentation)

## Fields

| Field | What to enter |
|---|---|
| ID | Stable FND or EV ID. |
| Finding or observation | State the team's conclusion, or what was observed, said or measured. |
| Evidence and source | Summarise the support, including contrary evidence and limits. Cite the exact source. A finding can cite an existing EV row that leads to it. |
| Status | For a finding, use Draft while the team still needs to agree the wording or check its sources. Use Reviewed when the team has agreed the wording and confirmed the sources were checked. Use Superseded if replaced. Use Withdrawn when the team confirms a finding or observation should no longer be relied on without a replacement. An observation can have a blank status. Verify its source before relying on it. |

For each citation give its SES or DOC ID, the exact version, path or version-specific URL, and a timestamp, page, section or range. Register non-session material in the [source register](../../document-tracker.xlsx). Add relevant group, question, round or design references when they explain scope. Give JNY and PRT references with the version.

If the source differs from the team's wording, bring the exact passage to the team. Attribute external conclusions to their authors in the source register or the relevant review notes. Record a team finding once the team has reached its own conclusion. For an older Draft row that contains a supplier claim, check the cited source and retain the attribution. Keep it out of the team’s findings unless the team adopts it after review. Keep replaced records and cite their exact successor IDs in **Evidence and source**. Flag an unknown successor.

## Check rows below the table

If **Outside table** in row 1 is above zero, check for rows containing any core field below the Excel table, including partial records without an ID or wording. Bring confirmed records into the table and check the dropdowns. If you only have a table extract, report that you could not check below it.

## Withdraw a finding

When the team confirms a finding or independently recorded observation or measurement is invalid, out of scope for continued reliance or otherwise withdrawn without a replacement, set **Status** to **Withdrawn** on its existing FND or EV row. Keep its ID, wording and exact source citation where permitted. In **Evidence and source**, add a short **Withdrawal:** note with the reason and date. Name the person or team who agreed where appropriate. Use withdrawn records for historical explanation only.

Follow the agreed [research retention and withdrawal procedure](../research-protocol.md#retention-and-withdrawal). Where that requires removing identifying words, quotations or source details, redact or remove them from affected copies and retain the permitted non-identifying explanation with the record ID and status. Record source identifiers and locators only where permitted. If a source becomes unavailable, flag the gap and keep the permitted historical record. Never reconstruct removed material.

### Trace withdrawn evidence

Follow [reverse lookups](../record-conventions.md#reverse-lookups) from the withdrawn EV or FND to each affected finding, user need, assumption, decision, requirement and success measure. Also follow RQ IDs in affected findings to the questions they answered. Review Answered questions even though their own rows do not cite FND IDs. Check for a current Reviewed finding that still supports each answer. Follow affected records to dependent claims, such as a decision about an affected need. Establish what support remains, including whether an underlying EV remains valid in its original scope. Check for other grounds before treating a record as unsupported.

Flag affected current claims for the team. When authorised, add a short dated review note, such as “Evidence review pending: FND-505 was withdrawn”, to the existing evidence or rationale field. Keep the recorded status until the team reassesses it. If the withdrawal reveals a limit of the source itself, record that verified limit in the source register, within the applicable permissions.

For example, keep `FND-505` and its citation `DOC-505 v1, page 4`. Add “Withdrawal: the team reviewed the supplier’s claim and found the sample did not cover this service’s users.”

[Worked example tracing a finding to two sessions](../worked-service-handoff.md#trace-a-playback-claim-back-to-its-source)
