# Research Sessions

**Working file:** [research-sessions.xlsx](../../research-sessions.xlsx)

Connect each actual research session to its round, participants, consent and source material. Use for individual interviews, usability tests or other actual sessions within a planned round.


## First capture

Enter **Session ID**, **Round ID**, **Date**. Keep unknowns visible; do not invent them. This saves a first record, not an established or complete position. Complete the applicable fields below before acting on or relying on it. Applicable consent is required before participant research begins; the small capture is not permission to start.

## Complete a record

1. Allocate a SES ID and link the parent RND ID.
2. Use participant codes and record the applicable consent reference before participant research.
3. Record the exact prototype version when testing a design.
4. Link exact recording files and notes. Put only one file in Current transcript link and set Transcript status for that file.
5. Leave Current transcript link blank for Not applicable or Not available. Machine-generated, Checked and Corrected each require the exact linked file.

## Fictional example

This example demonstrates the format only. It is not project evidence and is not preloaded into the workbook. It shows a developed record; the first capture can be smaller. Empty cells mean not recorded.

| Field | Example |
|---|---|
| Session ID | SES-003 |
| Round ID | RND-001 |
| Participant IDs | PAR-001 |
| Date | 2026-11-16 |
| Prototype version | PRT-001 v1 |
| Consent reference | Restricted consent record for SES-003 |
| Recording links | research/recordings/RND-001/2026-11-16_RND-001_SES-003_screen_p01.mp4 |
| Current transcript link | research/transcripts/RND-001/2026-11-16_RND-001_SES-003_transcript_v01.txt |
| Transcript status | Machine-generated |
| Notes link |  |

## Fields

The timing below separates quick capture from a usable record. **Before use** means before acting on or relying on the record. Specific conditions still apply; capture does not establish consent, evidence, agreement or verification. A blank means not recorded, not false, zero or none.

| Field | Needed when | What to enter |
|---|---|---|
| Session ID | At capture | Stable session ID. |
| Round ID | At capture | Exactly one RND ID for the parent research round, for example RND-001. |
| Participant IDs | The session involves participants | Zero or more PAR IDs for participants who took part, separated by semicolon plus space. Required for sessions involving participants; otherwise leave blank. Never enter names or contact details. |
| Date | At capture | Session date in YYYY-MM-DD form. |
| Prototype version | The session tests a prototype | One exact prototype ID and version tested, for example PRT-001 v1. Required when a prototype is tested; otherwise leave blank. Never use an unversioned ID or the word latest. |
| Consent reference | The session involves participants, before research begins | Reference to the applicable consent evidence; required before participant research. |
| Recording links | When known or relevant | Zero or more exact recording-file paths or version-specific URLs, separated by semicolon plus space. Each path identifies the session and recording part; do not substitute a folder or a changing latest link. |
| Current transcript link | Transcript status is Machine-generated, Checked or Corrected | One exact path or version-specific URL for the current transcript. Required when Transcript status is Machine-generated, Checked or Corrected; otherwise leave blank. Retain older transcript files separately and preserve evidence links to the exact version originally used. |
| Transcript status | Before use | Review state of the single file in Current transcript link. It does not describe older transcript versions. Not applicable and Not available require a blank Current transcript link. Choices: `Not applicable`, `Not available`, `Machine-generated`, `Checked`, `Corrected`. |
| Notes link | When known or relevant | One exact session-notes path or URL when notes were collected; otherwise leave blank. |

## Keep it current

When a transcript is corrected, point Current transcript link to the corrected file and update Transcript status together. Keep older versions where permitted. Evidence must continue to cite the exact version originally used; do not silently redirect its source pointer. Follow retention or withdrawal requirements; mark unavailable material clearly and reassess dependent evidence.

## Completion check

The session can be traced to its round and permitted source material; machine-generated text is not presented as checked.

Use [record conventions](../record-conventions.md) for stable IDs, references, dates and workbook editing. Permitted values and meanings are documented in [allowed-values.xlsx](../allowed-values.xlsx); dropdowns are already built into each workbook.

## Practice basis

- [GDS Service Manual](https://www.gov.uk/service-manual/user-research/getting-users-consent-for-research)

The field schema is this framework's implementation choice, not a prescribed GDS spreadsheet. Guidance reviewed for this starter: 16 November 2026.
