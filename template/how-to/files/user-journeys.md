# User Journeys

**Working file:** [user-journeys.xlsx](../../user-journeys.xlsx)

Index journeys and other retained service models with their matching text equivalents. Use the existing register and versioned folders when a journey, service blueprint, process map, actor map or information flow is the right way to show the service.

Choose a model around the question. Use a journey for what people experience, a blueprint for how backstage work shapes that experience, a process map for activities and decisions, an actor map for responsibilities, or an information flow for who needs what information and when. Use recognisable labels for stages and handoffs. Describe the type, purpose, boundaries and relevant actors in the [version description](../../journeys/JNY-001/v1/description.md).


## First capture

Enter **ID**, **Version**, **Name**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it. Register a retained version when used in research, informing a significant decision, receiving substantive shared review or handed over. Disposable sketches can stay in normal tools, but retain any substantive learning.

## Complete a record

1. Register a version when used in research, informing a significant decision, receiving substantive shared review or handed over. Allocate a JNY ID to a distinct journey or competing alternative.
2. Set **Represents** for the version’s main purpose. Use **Current experience** for a model of the existing service, including a comparison of current prescribed and observed practice. Use **Proposed experience** when the main subject is a future option. In the description, label each part **Prescribed process**, **Observed practice** or **Proposed future** as applicable. Cite the governing document for a prescribed step, evidence for a claim about observed practice, and the human proposal for an intended change. Identify uncertainty where records or observations differ.
3. Save the visual and its accurate text equivalent under the same retained version.
4. Put selection, discard or replacement decisions in Decision IDs. Put exact successor journey IDs and versions in Superseded by.

Before research use or handover, open both the graphic and text and check their exact version and meaning agree, including supported channels and staff actions. If a graphic adds a telephone step that the text omits, the author resolves the intended journey before others rely on it. AI may flag the difference, not choose which service experience is correct. A meaningful alternative becomes its own retained option; a corrected description remains linked to the version it actually describes.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| ID | JNY-001 |
| Version | v1 |
| Name | Waiting for an application decision |
| User group IDs | UG-001 |
| Represents | Proposed experience |
| Status | Draft |
| Graphic path | journeys/JNY-001/v1/map.svg |
| Text path | journeys/JNY-001/v1/description.md |
| Decision IDs |  |
| Superseded by |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| ID | At capture | Stable journey ID; competing alternatives receive separate IDs. |
| Version | At capture | Specific retained version, for example v1. |
| Name | At capture | A concise journey name. |
| User group IDs | Before use | One or more UG IDs for the user groups represented, separated by semicolon plus space. |
| Represents | Before use | The main subject of the retained model. Choices: `Current experience`, `Proposed experience`. Label prescribed, observed and proposed elements in the version description when they appear together. |
| Status | Before use | The state of this version. Choices: `Draft`, `Reviewed`, `Selected`, `Discarded`, `Superseded`. |
| Graphic path | Before use | Location of the visual map for this version. |
| Text path | Before use | Location of the matching text equivalent. |
| Decision IDs | When known or relevant | Zero or more DEC IDs recording selection, discard or replacement decisions for this exact journey version, separated by semicolon plus space. Put successor journey versions in Superseded by. |
| Superseded by | When a replacement exists | Zero or more exact replacement JNY ID and version values of the same record type, separated by semicolon plus space. Required when a replacement exists. If Superseded but the replacement is unknown, leave blank and flag an unresolved reference gap; never invent a successor. No self-links or cycles. Use JNY-001 v2, not an unversioned ID. |

## Keep it current

Keep one ID for revisions of the same journey. Each retained row is identified by ID plus Version; refer to both. A higher version number does not establish the selected version. Preserve versions meeting the retention threshold, including discarded options that explain substantive learning. Selected does not mean implemented, and Discarded material must not be presented as the current direction.

## Completion check

The map and text describe the same version, with a clear user group, purpose, boundaries and status. Each state and material handoff has a clear label. See the [worked service handoff](../worked-service-handoff.md).

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/user-research/creating-an-experience-map)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
