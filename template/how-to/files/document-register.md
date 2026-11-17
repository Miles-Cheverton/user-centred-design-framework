# Document Register

**Working file:** [project-background/document-register.xlsx](../../project-background/document-register.xlsx)

Describe supplied documents and explain their authority, currency and limitations. Use when project documents are supplied, discovered or replaced.

This existing register also identifies non-session project sources, including a survey dataset, working results or a retained Whiteboard state. They stay in the activity's approved storage; the register's location under project-background does not require moving them there or creating another register. Register a source when retained or relied on, not every disposable edit.


## First capture

Enter **ID**, **Title**, **File or URL**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it.

## Complete a record

1. Preserve the source's title, version and original location.
2. Describe what it contains and who supplied it.
3. Assess its principal role and currentness.
4. Explain which claims carry weight and which remain assumptions or proposals; one document can contain both.

For a survey source, identify the original export and questionnaire version, collection period and any filters. A working calculation is a distinct source when cited; its method points back to the exact original dataset. For a board, record its purpose, live location, the retained state actually used and access limits. Use existing Role and Use and limitations fields honestly: research material is not automatically a reviewed finding. Exact versions and locators belong in each citing EV record.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | DOC-001 |
| Title | Initial service proposal |
| Description | Commissioning brief with a funding envelope and suggested app |
| File or URL | project-background/originals/initial-service-proposal.pdf |
| Supplied by | Commissioning team |
| Date or version | v1 |
| Role | Agreed direction |
| Currency | Current |
| Use and limitations | Use the agreed funding envelope; investigate demand assumptions and the proposed app |
| Superseded by |  |

Here, “Agreed direction” establishes the funded work, not proof of every claim in the brief. The team still analyses whether the suggested app addresses a real need. Record that distinction in Use and limitations; AI can locate the claims and their sources, but must not convert funding approval into user evidence.

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable document ID. |
| Title | At capture | The document's own title. |
| Description | Before use | A short description of what it contains. |
| File or URL | At capture | Original file location or authoritative URL. |
| Supplied by | When known or relevant | Who supplied or owns the document. |
| Date or version | When known or relevant | The source's date or version, if known. |
| Role | Before use | The document's principal role; qualify mixed content in limitations. Choices: `Authoritative requirement`, `Agreed direction`, `Research evidence`, `Proposal`, `Background context`, `Unassessed`. |
| Currency | Before use | Whether it is current for this project. Choices: `Current`, `Superseded`, `Unknown`. |
| Use and limitations | Before use | Which claims to rely on, which to test and what the document does not establish. |
| Superseded by | When a replacement exists | Zero or more exact replacement DOC ID values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. |

## Keep it current

For a consequential source held elsewhere, use **Supplied by** to identify the owner or maintaining team. Use **File or URL** and **Date or version** for the exact source. In **Use and limitations**, state who can access it, any known retention or sharing conditions, and which part the team could check. See the [worked board example](../worked-service-handoff.md#research-coverage-and-external-material).

Set Currency to Superseded and list all exact replacement DOC IDs in Superseded by when sources are replaced. A blank replacement on a Superseded document is an unresolved gap. Preserve material disagreements rather than silently dismissing contradictory evidence. Original files remain unchanged unless their owner issues a replacement.

## Completion check

A reader can tell what to rely on, for which purpose, and with what limitations.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/agile-delivery/how-the-discovery-phase-works)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
