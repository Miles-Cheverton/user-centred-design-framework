# Prototypes

**Working file:** [prototypes.xlsx](../../prototypes.xlsx)

Index retained prototype versions and connect them to the proposals and journeys they explore. Register a version when it is used in research, informs a significant decision, receives substantive shared review or is handed over.


## First capture

Enter **ID**, **Version**, **Name**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it. Register a retained version when used in research, informing a significant decision, receiving substantive shared review or handed over. Disposable sketches can stay in normal tools, but retain any substantive learning.

## Complete a record

1. Allocate a PRT ID and identify the specific version. ID plus Version is the row identity; a bare PRT ID does not select one.
2. Link the proposal and journey being explored.
3. Provide the original source or design-tool link and a preview where available.
4. Complete the version README with the question explored, tasks, run instructions, simulated behaviour and limitations. Its one link to this register avoids duplicate metadata.
5. Capture the team's substantive findings after human analysis in research-findings.md, with the exact prototype in Design versions. Find sessions by Prototype version in research-sessions.xlsx; do not maintain inverse lists.

At retained handover or research use, open the source and preview and identify the exact version actually shown. Check it matches the README, relevant journey and intended interaction. A preview URL that now shows v3 cannot demonstrate what was tested in v1. Retain an appropriate snapshot or version-specific source, and disclose interactions or source material that cannot be inspected.

For example, five disposable button-layout sketches need no five inventory entries. A version tested with participants does need a retained record; the team's finding about the wording remains even if that design is discarded. A human idea can be captured as a proposal without pretending it is an established research conclusion.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | PRT-001 |
| Version | v1 |
| Name | Application progress concept |
| Proposal IDs | PROP-001 |
| Journey versions | JNY-001 v1 |
| Status | Draft |
| Source path or URL | prototypes/PRT-001/v1/source/ |
| Preview URL |  |
| Superseded by |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable prototype ID. |
| Version | At capture | Specific retained version, for example v1. |
| Name | At capture | A concise prototype name. |
| Proposal IDs | When known or relevant | Zero or more PROP IDs for the design proposals explored, separated by semicolon plus space. |
| Journey versions | When known or relevant | Zero or more exact journey IDs and versions explored, for example JNY-001 v1; JNY-002 v2. Separate entries with semicolon plus space; never use unversioned IDs or latest. |
| Status | Before use | The state of this prototype version. Choices: `Draft`, `Ready for research`, `Tested`, `Selected`, `Discarded`, `Superseded`. |
| Source path or URL | Before use | Location of source files or the original design-tool file. |
| Preview URL | When known or relevant | Runnable or viewable preview, when available. |
| Superseded by | When a replacement exists | Zero or more exact replacement PRT ID and version values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. Use PRT-001 v2, not an unversioned ID. |

## Keep it current

Findings must reference the version actually tested. Use Superseded by for all exact successor PRT IDs and versions; do not infer a replacement from a higher version number. Retain relevant discarded versions and the decision explaining why. A Selected prototype is not evidence of a deployed service.

## Completion check

An authorised team member can locate the exact version and understand what it does and does not demonstrate.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/design/making-prototypes)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
