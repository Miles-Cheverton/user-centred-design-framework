# User Needs

**Working file:** [user-needs.xlsx](../../user-needs.xlsx)

Record the goals users need to achieve and why, linked to their evidence. Use when research identifies what people need to achieve, and when assessing design or delivery choices.

Evidenced means the need has support; it does not mean the service meets it. Record fulfilment and delivery choices separately in [user-need-coverage.xlsx](../../user-need-coverage.xlsx), following [its guide](user-need-coverage.md), with one current row per active UN ID and no copied need wording.


## First capture

Enter **ID**, **Need**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it.

## Complete a record

1. Identify the relevant user group.
2. Write Need as 'I need to…' and Purpose as 'So that…', using recognisable user language.
3. Enter EV or FND IDs in Supporting record IDs. EV records are observations; FND records are interpreted findings whose EV support must remain traceable. Use Proposed until the evidence supports the need.
4. Keep features, delivery estimates and task-specific acceptance criteria in their own delivery records.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | UN-001 |
| User group IDs | UG-001 |
| Need | Understand when to expect a decision |
| Purpose | Make plans while waiting |
| Supporting record IDs | FND-001 |
| Status | Evidenced |
| Superseded by |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable user-need ID. |
| User group IDs | Before use | One or more UG IDs for the user groups represented, separated by semicolon plus space. |
| Need | At capture | Completes 'I need to…'; include a trigger only when it changes the meaning. |
| Purpose | Before use | Completes 'So that…' and explains the user's intended outcome. |
| Supporting record IDs | Status is Evidenced | Zero or more EV or FND IDs supporting the need, separated by semicolon plus space. At least one is required before Status can be Evidenced; leave blank for an unevidenced proposal. |
| Status | Before use | The current evidential standing. Choices: `Proposed`, `Evidenced`, `Superseded`. |
| Superseded by | When a replacement exists | Zero or more exact replacement UN ID values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. |

## Keep it current

Keep the ID when refining the same need. Use Superseded for a replaced need and put all exact replacement UN IDs in Superseded by. A blank replacement is an unresolved gap; never infer one from similar wording. Revisit Evidenced needs when contrary evidence emerges.

## Completion check

The need expresses a user goal, has a clear purpose and is not a disguised request for a particular channel or feature.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
