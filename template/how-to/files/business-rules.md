# Business Rules

**Working file:** [business-rules.xlsx](../../business-rules.xlsx)

Record the policy and operational conditions governing what the service does. Use for eligibility, routing, calculation and exception rules governing the service.


## First capture

Enter **ID**, **Condition**, **Required behaviour**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it.

## Complete a record

1. State the condition and required behaviour explicitly.
2. Identify the source and distinguish a proposed rule from an approved one.
3. Record known exceptions or the fact that they remain unresolved.
4. Link complex rule interactions to a clear decision table or authoritative specification.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | BR-001 |
| Condition | An application has entered assessment |
| Required behaviour | Further amendments are routed to the assessment team |
| Exceptions | Not yet established |
| Source | DOC-003 |
| Status | Proposed |
| Superseded by |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable rule ID. |
| Condition | At capture | The situation in which the rule applies. |
| Required behaviour | At capture | What must happen when the condition holds. |
| Exceptions | When known or relevant | Known exceptions; 'None confirmed' is not proof that none exist. |
| Source | Before use | Authority pointer in plain text: the applicable policy, document/version, agreement, decision or authoritative URL and its relevant section. May include a DOC or DEC ID, but this is not an ID-only relationship field. State any uncertainty about applicability. |
| Status | Before use | Whether the rule is a proposal or currently authorised. Choices: `Proposed`, `Approved`, `Superseded`. |
| Superseded by | When a replacement exists | Zero or more exact replacement BR ID values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. |

## Keep it current

Retain the history of replaced rules and link the decision or policy change. Review affected journeys and designs when a rule changes.

When a rule is replaced, put exact replacement BR IDs in Superseded by and retain the old source and rationale. A blank replacement on a Superseded rule is an unresolved gap.

## Completion check

The rule has authority or is clearly proposed; organisational preferences have not been presented as law.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [Department for Transport service documentation](https://department-for-transport-streetmanager.github.io/street-manager-docs/articles/business-rules-version-2-00-service.html)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
