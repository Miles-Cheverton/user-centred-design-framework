# Assumptions

**Working file:** [assumptions.xlsx](../../assumptions.xlsx)

Make unverified beliefs visible and retain what testing establishes about them. Use whenever a belief materially shapes plans or designs before it has sufficient evidence.


## First capture

Enter **ID**, **Assumption**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it.

## Complete a record

1. State the belief precisely enough to investigate.
2. Record what would change if it were wrong and how to check it.
3. Assign an owner and use Untested until assessed.
4. After assessment, record status, date, rationale and evidence together.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | ASM-001 |
| Assumption | All applicants can receive email updates |
| Consequence if wrong | Some people would not receive important updates |
| Check | RQ-001 |
| Owner | User researcher |
| Status | Contradicted |
| Assessed on | 2026-11-16 |
| Rationale | The example study included applicants without dependable email access |
| Supporting record IDs | FND-002 |
| Superseded by |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable assumption ID. |
| Assumption | At capture | The precise belief being relied upon, with its scope. |
| Consequence if wrong | Before use | What would change or fail if it is incorrect. |
| Check | Before use | How the belief will be investigated. May include an RQ ID within the explanation; this is a text field, not an ID-only relationship field. |
| Owner | Before use | Person or role responsible for checking it. |
| Status | Before use | The current assessment. Choices: `Untested`, `Supported`, `Contradicted`, `Inconclusive`, `Superseded`. |
| Assessed on | When known or relevant | Date of the latest assessment, in YYYY-MM-DD form. |
| Rationale | When known or relevant | Why the current assessment was reached or changed. Record uncertainty and missing evidence explicitly. Put replacement IDs in Superseded by rather than relying on prose here. |
| Supporting record IDs | When known or relevant | Zero or more EV or FND IDs supporting the assessment, separated by semicolon plus space. Link the available evidence for Supported, Contradicted or Inconclusive assessments; if none is recorded, flag the assessment as an evidence gap rather than inventing support. |
| Superseded by | When a replacement exists | Zero or more exact replacement ASM ID values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. |

## Keep it current

Retain contradicted assumptions with their original IDs and wording. List all exact replacement ASM IDs in Superseded by when replaced. A contradicted assumption is retained as Contradicted, not automatically Superseded. Supported is limited to the circumstances investigated; it does not mean universally true.

## Completion check

An untested or inconclusive belief cannot be mistaken for an established fact.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/agile-delivery/how-the-discovery-phase-works)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
