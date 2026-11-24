# Findings and observations

**Guidance revision:** 2026-11-24.3

**Working file** [findings-and-observations.xlsx](../../findings-and-observations.xlsx)

## First capture

Use FND for a team conclusion. Use EV for an observation or measurement that needs its own citation. Record what the team learnt or observed and its source in one row, whether it came from research or other work.

People analyse evidence and reach conclusions. AI can help record or check their work. [Human analysis before documentation](../evidence-and-interpretation.md#human-analysis-before-documentation)

## Fields

| Field | What to enter |
|---|---|
| ID | Stable FND or EV ID. |
| Finding or observation | State the team's conclusion, or what was observed, said or measured. |
| Evidence and source | Summarise the support, including contrary evidence and limits. Cite the exact source. A finding can cite an existing EV row that leads to it. |
| Status | For a finding, use Draft while the team still needs to agree the wording or check its sources. Use Reviewed when the team has agreed the wording and confirmed the sources were checked. Use Superseded if replaced. Use Withdrawn when the team decides to stop relying on a finding. An observation can have a blank status. Verify its source before relying on it. |

For each citation give its SES or DOC ID, the exact version, path or version-specific URL, and a timestamp, page, section or range. Register non-session material in the [source register](../../project-sources/source-register.xlsx). Add relevant group, question, round or design references when they explain scope. Give JNY and PRT references with the version.

If the source differs from the team's wording, bring the exact passage to the team. Attribute external conclusions to their authors in the source register or the relevant review notes. Record a team finding once the team has reached its own conclusion. For an older Draft row that contains a supplier claim, check the cited source and retain the attribution. Keep it out of the team’s findings unless the team adopts it after review. Keep replaced records and cite their successors in **Evidence and source** when useful.

## Check rows below the table

If **Outside table** in row 1 is above zero, check for records with an ID or wording below the Excel table. Bring confirmed records into the table and check the dropdowns. If you only have a table extract, report that you could not check below it.

## Withdraw a finding

When the team confirms a finding should no longer be relied on, set **Status** to **Withdrawn** on its existing FND row. Keep its ID, wording and exact source citation. In **Evidence and source**, add a short **Withdrawal:** note with the reason. Include the date and the person or team who agreed if that helps explain the change. A withdrawn finding stays available for history. Use it only to explain what was recorded and why it changed. Use the [reverse lookup](../record-conventions.md#reverse-lookups) for records that cite it. For each current claim that relies on it, list the record and note what evidence remains. When authorised, add a short note such as “Evidence review pending: FND-505 was withdrawn” in the affected record’s existing evidence or rationale field. Keep its status until the team reassesses it. If the withdrawal reveals a limit of the source itself, record the verified limit in the source register.

For example, keep `FND-505` and its citation `DOC-505 v1, page 4`. Add “Withdrawal: the team reviewed the supplier’s claim and found the sample did not cover this service’s users.”

[Worked example tracing a finding to two sessions](../worked-service-handoff.md#trace-a-playback-claim-back-to-its-source)
