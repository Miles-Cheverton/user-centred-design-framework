# Worked example: collection readiness at an equipment depot

All records and data on this page are fictional. The tables show what the team would enter in the existing files. The identifiers and source paths illustrate the relationships.

## Follow the service through the handoff

The team uses a service blueprint because the borrower’s message depends on backstage work. In [user-journeys.xlsx](../user-journeys.xlsx), it registers `JNY-201 v2` with **Represents** set to **Current experience**. Its description covers reservation through collection at one depot. The version’s graphic and text use the same stage name, **Collection readiness**.

| At Collection readiness | Actor, information and action | Basis |
|---|---|---|
| Prescribed process | Depot staff check that equipment is ready before telling borrowers to travel. | `DOC-201`, depot procedure v1, §2 “Collection readiness”. |
| Observed practice | The depot assistant received a reservation number without a readiness status. One borrower arrived while the equipment was still being prepared. | `EV-201` and `EV-202` from two sessions. |
| Proposed future | The depot confirms readiness after checking the equipment. The borrower then receives a separate collection message. | `PROP-201`, an option selected for testing in `DEC-202`. |

## Trace a playback claim back to its source

> In the sessions reviewed, the reservation could reach the depot before staff had confirmed readiness. One borrower arrived before the equipment was ready. **Source: FND-201, Collection readiness.**

The team reviewed the two observations together. It agreed that the handoff could leave readiness unclear, and noted that the sessions did not establish how often this happens or whether the telephone route behaves the same way. AI can check the wording and citations against the team’s recorded conclusion and the authorised sources.

- In [research-findings.md](../research-findings.md), `FND-201` answers `RQ-201` about when borrowers know they can travel. **Design versions** lists `JNY-201 v2`. **Context and limitations** names **Collection readiness** and gives the limits above. **Supporting evidence** lists `EV-201` and `EV-202`.
- In [evidence.xlsx](../evidence.xlsx), `EV-201` points to `SES-201`, exact source `research/transcripts/RND-201/2026-10-07_RND-201_SES-201_collection-test_transcript_v01.txt`, locator `00:06:42–00:07:05`, where the depot assistant describes receiving only a reservation number.
- `EV-202` points to `SES-202`, exact source `research/transcripts/RND-201/2026-10-08_RND-201_SES-202_transcript_v01.txt`, locator `00:09:10–00:09:38`, where the borrower describes arriving before the equipment was ready. The short activity label in the first filename is optional.

## Follow the finding forward to a decision and an outcome check

| Existing record | What it establishes |
|---|---|
| [user-needs.xlsx](../user-needs.xlsx), `UN-201` | Borrowers (`UG-201`) need to know when their equipment is ready so they can plan their trip. Supporting record `FND-201`. |
| [design-proposals.md](../design-proposals.md), `PROP-201` | Separate reservation from readiness messaging. Set **User need IDs** to `UN-201`, **Outcome IDs** to `OUT-201` and **Journey versions** to `JNY-201 v2`. Cite `FND-201` under **Why explore it**. |
| [decisions.md](../decisions.md), `DEC-202` | The service owner agreed to test `PROP-201` on web and telephone routes. The decision cites `FND-201` and `UN-201` and identifies `OUT-201`, fewer trips before equipment is ready, as the intended outcome. |
| [user-need-coverage.xlsx](../user-need-coverage.xlsx) and [success-measures.md](../success-measures.md) | `UN-201` is **Not assessed** for fulfilment and the delivery choice is **Will address**, linked to `DEC-202`. For `OUT-201` in [outcomes.xlsx](../outcomes.xlsx), the team plans to compare early trips before and after the change at the same depot across both channels. The baseline and follow-up results are still open. |

This example ends with an agreed test and a plan to assess the outcome. The next review would attach the test evidence to the assessed version or service scope and record the team’s fulfilment judgement.

## Recover an earlier problem framing

In the fictional document register, `DOC-200` is the original commissioning brief, v1, §1 “Mandate”. In [decisions.md](../decisions.md), `DEC-201` cites that passage and retains the prior wording, “Borrowers cannot reliably reserve equipment online.” The choice records the new framing, “Borrowers cannot reliably tell when equipment is ready to collect, making it harder to plan a trip.” The rationale cites `FND-201`. The consequence is to include depot preparation and telephone support in the investigation. [problem-statement.md](../problem-statement.md) holds the current sentence.

## Research coverage and external material

Compare planned groups in [research-plan.xlsx](../research-plan.xlsx) with actual session rows in [research-sessions.xlsx](../research-sessions.xlsx) and coded group links in [participants.xlsx](../participants.xlsx).

| Round | Planned groups | Actual participation in the example |
|---|---|---|
| `RND-201` | Borrowers (`UG-201`), depot staff (`UG-202`), telephone-only borrowers (`UG-203`) | `SES-201`: depot staff member `PAR-201`. `SES-202`: borrower `PAR-202`. |
| `RND-202` | Depot staff (`UG-202`) and telephone-only borrowers (`UG-203`) | `SES-203`: returning staff member `PAR-201`. No session with a telephone-only borrower is recorded in this example. |

That gives three participations by two people. `UG-203` is the follow-up gap for testing the supported route. Invitation status and contact details belong in approved restricted recruitment records.

In the [document register](../project-background/document-register.xlsx), the team records `DOC-202` for a retained board snapshot maintained by the depot improvement team. **File or URL** in a live project points to that team’s approved, version-specific snapshot. **Date or version** identifies the retained state, for example v1 dated 10 October 2026. **Supplied by** names the depot improvement team. **Use and limitations** says that the researcher viewed the “Readiness handoff” frame, the snapshot covers that frame only, project access is by request, and retention is subject to the owner’s arrangements with the exact limit still to confirm. The board shows the workshop’s proposed process. The finding’s observed claims cite session evidence.
