# Dependencies

**Working file:** [dependencies.xlsx](../../dependencies.xlsx)

Record what the project needs another party or system to provide. Use when successful work relies on something another party must provide.


## First capture

Enter **ID**, **Dependency**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it.

## Complete a record

1. Describe exactly what is needed and from whom.
2. Record the real timing constraint or milestone.
3. Assign an owner to confirm the agreement and follow progress.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | DEP-001 |
| Dependency | A test environment for the identity service |
| Provider | Identity platform team |
| Required by | Before integration testing |
| Owner | Technical lead |
| Status | Unconfirmed |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable dependency ID. |
| Dependency | At capture | The deliverable, capability or agreement required. |
| Provider | Before use | Who is expected to provide it. |
| Required by | When known or relevant | A known date or milestone; do not invent a date. |
| Owner | Before use | The person or role following it through. |
| Status | Before use | Current dependency state. Choices: `Unconfirmed`, `Agreed`, `In progress`, `Available`, `Blocked`, `No longer needed`. |

## Keep it current

Update status from actual provider information or observed availability. A promise is not proof that a dependency is available.

## Completion check

The dependency has a clear provider and an owner, with a meaningful status.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/agile-delivery/governance-principles-for-agile-service-delivery)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
