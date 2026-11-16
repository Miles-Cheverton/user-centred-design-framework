# Non Functional Requirements

**Working file:** [non-functional-requirements.xlsx](../../non-functional-requirements.xlsx)

Record service-wide, checkable requirements for qualities such as accessibility, security and reliability. Use for checkable service-wide requirements such as accessibility, security, performance and reliability.


## First capture

Enter **ID**, **Requirement**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it.

## Complete a record

1. Write a criterion with enough scope, conditions and threshold to check.
2. Identify the applicable standard/version, obligation or agreed source.
3. Link a user need where there is a direct relationship; do not manufacture needs to justify every control.
4. Set Record status to Proposed or Agreed according to the actual agreement, independently of testing.
5. Set Verification status to Not assessed until checked. Partially met, Met and Not met require EV IDs in Evidence IDs. Register verification reports as DOC sources and cite their exact results through evidence.xlsx.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | NFR-001 |
| Requirement | The application journey can be completed using a keyboard without a pointing device |
| User need IDs | UN-002 |
| Standard or source | Applicable accessibility standard recorded by the team |
| Verification method | Manual keyboard test of every step and error path |
| Evidence IDs |  |
| Record status | Proposed |
| Verification status | Not assessed |
| Superseded by |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable requirement ID. |
| Requirement | At capture | A precise criterion with applicable scope, conditions and threshold. |
| User need IDs | When known or relevant | Zero or more UN IDs for directly related user needs, separated by semicolon plus space. Leave blank if no direct relationship has been established; do not invent a need. |
| Standard or source | Before use | Authority pointer in plain text: the applicable standard and version, obligation or agreed decision, including its relevant section. May include a DOC or DEC ID or URL; this is not an ID-only relationship field. |
| Verification method | Before use | How meeting the criterion will be checked. |
| Evidence IDs | Verification status is Partially met, Met or Not met | Zero or more EV IDs for verification observations, separated by semicolon plus space. At least one is required when Verification status is Partially met, Met or Not met. Register verification reports as DOC sources and cite them through evidence.xlsx; do not enter FND IDs, paths or report names here. |
| Record status | Before use | Whether the requirement is proposed, agreed or superseded. This is independent of whether the service meets it. Choices: `Proposed`, `Agreed`, `Superseded`. |
| Verification status | Before use | Current result of checking this requirement against its stated criterion. Use Not assessed until checked; Partially met, Met and Not met require linked Evidence IDs. Agreement alone does not establish compliance. Choices: `Not assessed`, `Partially met`, `Met`, `Not met`. |
| Superseded by | When a replacement exists | Zero or more exact replacement NFR ID values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. |

## Keep it current

Reassess when the service, standard or operating context changes. If replaced, set Record status to Superseded and record exact replacement NFR IDs in Superseded by. Keep user access and support needs in user-needs.xlsx; task-specific acceptance criteria remain with delivery stories.

## Completion check

The criterion is testable, applicable and traceable. Record status describes agreement; Verification status describes the actual check. An Agreed requirement is not automatically Met.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [Defra Digital Service Manual](https://digital.defra.gov.uk/business-analysis/non-functional-requirements)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
