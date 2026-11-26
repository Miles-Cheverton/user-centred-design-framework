# User needs

**Working file (via document tracker)** [user-needs.xlsx](../../document-tracker.xlsx)

## First capture

Enter an **ID** and **Need**. You can leave **Status** blank while making a first capture with fulfilment blank or Not assessed. Describe the goal and why it matters in the user’s words. Include the trigger where it changes the meaning. If a source names a feature, ask what people need to achieve. Use quotation marks only for words you can trace to a participant.

## Fields

| Field | What to enter |
|---|---|
| ID | Stable need ID, for example `UN-001`. |
| User group IDs | One or more exact UG IDs before relying on the need. |
| Need | What people need to do and why. |
| Supporting record IDs | Evidence that the need exists. An Evidenced need requires at least one EV or FND ID and its user group IDs. Follow the record to its source. If its supporting evidence is withdrawn or otherwise invalidated, note the gap in **Scope and evidence** and ask the team whether any remaining evidence supports the need. Keep the recorded status until the team reassesses it. |
| Status | Proposed, Evidenced, Superseded or Withdrawn. This describes the record’s validity and support. Use Withdrawn when the team confirms the need record is no longer valid and has no replacement. |
| Superseded by | Exact replacement UN IDs. Flag an unknown replacement for a Superseded need. Leave blank for a Withdrawn need. |
| Fulfilment | The team’s assessment: Not assessed, Not met, Partly met or Met in full. |
| Scope and evidence | Evidence about fulfilment. Give the tested version or bounded scope, assessment date, FND or EV IDs, and any unmet part. Cite any relevant DEC ID here. Link the delivery work, acceptance criteria and exact build, release or test evidence where they establish the scope assessed. |
| Delivery decision | The team’s intent for this need: Not decided, Will address, Deferred or Will not address. Use Will address when the team has committed to addressing the need. A choice to test or hold can be cited in **Scope and evidence**. If delivery is still open, keep Not decided. |

## Withdraw a need

Keep the UN ID, wording and earlier evidence and assessment where permitted. If the team confirms the record itself is invalid and has no replacement, mark it Withdrawn. In **Scope and evidence**, record the date, reason and any supporting DEC, EV or FND ID. Keep the earlier judgement as history. Exclude Withdrawn needs from active fulfilment counts and review their dependent records. Where a need remains plausible but its evidence has weakened, the team can reassess its status as Proposed. If it is a valid need the team will defer or leave unaddressed, use the **Delivery decision** field.

## Assess whether the service meets the need

Keep one current fulfilment assessment per user need. Record the team’s judgement and the scope it assessed on the same row. A web pilot may meet a need online and leave the telephone route unassessed. Link the DEC ID in **Scope and evidence** for Deferred or Will not address, and for Will address where available. You can capture a decision before assessing fulfilment.

Before relying on an assessment, check the current design or service version, route and context against the recorded scope. A material change can leave the current version unassessed. Retain the earlier judgement, version and source and add a dated assessment review note in **Scope and evidence** identifying the new version or scope still to check. When reporting, identify the earlier scope assessed and the current scope still to check. Let the team decide when evidence supports an updated assessment and save it on the same row.

The totals include Proposed and Evidenced rows, plus first captures with blank status and no fulfilment assessment. Blank fulfilment counts as Not assessed. The totals omit starter, Superseded and Withdrawn rows, repeated IDs, rows missing an ID or need, IDs outside the starter format and unrecognised status or fulfilment values. State which versions or routes the figures cover. The totals reflect recorded assessments. If a withdrawal puts an assessment in doubt, explain that limit before using the totals. Filter **Delivery decision** to see deferred needs or those the team will not address.

After editing, compare the four totals with the active rows. If a preview still shows an old total, recalculate in a spreadsheet editor. Check the row 1 warnings. **Outside table** flags rows with any populated core field below the table. **Check status** and **Check fulfilment** flag invalid status and active fulfilment values. **Check records** flags missing or malformed IDs, duplicate IDs, missing needs, missing group IDs or supporting records for Evidenced needs, missing scope for assessed needs, invalid delivery choices or missing scope for Deferred or Will not address, Superseded needs without replacement IDs and Withdrawn needs without a scope and evidence entry. Read the full evidence and scope before relying on an assessment, even when the warnings are zero. If your team has agreed a different ID format or changed core column positions, adapt the starter formula checks to that mapping or use an independent tally. A non-zero warning means check the affected rows before quoting totals. Use [Check evidence and records](../../AI-skills/check-evidence-and-records/SKILL.md#choose-the-check) to locate issues and check evidence links. Report verified counts with their limits if any problems remain. When the assessment changes, retain earlier evidence, decisions and workbook versions.

[Worked handoff](../worked-service-handoff.md#follow-the-finding-forward-to-a-decision-and-an-outcome-check) · [GDS guidance on learning user needs](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs)
