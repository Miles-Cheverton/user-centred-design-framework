# Worked examples

These fictional scenarios show how the records relate. Use the [document tracker](../document-tracker.xlsx) to find your equivalent working records.

## Collection readiness at an equipment depot
Follow a finding from two sessions to the decision it informed. The transcripts, map and board are fictional.

### Follow the service through the handoff

In Design artefacts, `JNY-201 v2`, type Journey or map, links to a blueprint of reservation through collection at one depot. The text and graphic call the handoff **Collection readiness**. The description records **Current experience** and links to the graphic and `DEC-202`.

| At Collection readiness | Actor, information and action | Basis |
|---|---|---|
| Prescribed process | Depot staff check that equipment is ready before telling borrowers to travel. | `DOC-201`, depot procedure v1, §2 “Collection readiness”. |
| Observed practice | The depot assistant received a reservation number without a readiness status. One borrower arrived while the equipment was still being prepared. | `EV-201` and `EV-202` from two sessions. |
| Proposed future | The depot confirms readiness after checking the equipment. The borrower then receives a separate collection message. | The option selected for testing in `DEC-202`. |

### Trace a playback claim back to its source

> In the sessions reviewed, the reservation could reach the depot before staff had confirmed readiness. One borrower arrived before the equipment was ready. **Source: FND-201, Collection readiness.**

The team reviewed both observations and recorded the finding as **Reviewed**. Frequency and the telephone route are open questions. AI can check the wording and citations against authorised sources after the team agrees the conclusion.

- In `findings-and-observations.xlsx`, `FND-201` answers `RQ-201` about when borrowers know they can travel. **Evidence and source** names **Collection readiness** on `JNY-201 v2`, records the limits above, and cites `EV-201` and `EV-202`.
- In the same workbook, `EV-201` points to `SES-201`, exact source `research/RND-201/transcripts/2026-10-07_RND-201_SES-201_collection-test_transcript_v01.txt`, locator `00:06:42–00:07:05`, where the depot assistant describes receiving only a reservation number.
- `EV-202` points to `SES-202`, exact source `research/RND-201/transcripts/2026-10-08_RND-201_SES-202_transcript_v01.txt`, locator `00:09:10–00:09:38`, where the borrower describes arriving before the equipment was ready. The optional label in the first filename is `collection-test`. The EV rows make both observations independently citable.

### Follow the finding forward to a decision and an outcome check

| Existing record | What it establishes |
|---|---|
| `user-needs.xlsx`, `UN-201` | Borrowers (`UG-201`) need to know when their equipment is ready so they can plan their trip. Supporting record `FND-201`. **Fulfilment** is Not assessed. **Delivery decision** is Not decided. `DEC-202` in **Scope and evidence** records what the team agreed to test. |
| `decisions.xlsx`, `DEC-202` | On 12 October 2026 the service owner agreed to test a separate readiness message on web and telephone routes. **Why** cites the collection handoff in `JNY-201 v2`, `FND-201` and `UN-201`. The team considered changing the reservation wording alone. `OUT-201` records the intended outcome of fewer early trips. |
| `outcomes-and-measures.xlsx`, Success measures, `MET-201` | **Outcome IDs** links to `OUT-201` on the Outcomes sheet. **Source and method** describes comparing early trips before and after the change at the same depot across both channels. The baseline and results are still open. |

After testing, the team adds its judgement, tested scope, date and evidence to the same need row.

### Recover an earlier problem framing

The example team registers its original commissioning brief as `DOC-200`, v1, §1 “Mandate”. In `decisions.xlsx`, `DEC-201` records the new framing in **Decision**, “Borrowers cannot reliably tell when equipment is ready to collect, making it harder to plan a trip.” **Why** cites that mandate passage and `FND-201` and retains the prior wording, “Borrowers cannot reliably reserve equipment online.” The team extends the investigation to depot preparation and telephone support. The team puts the current sentence in `problem-statement.md`.

### Research coverage and external material

Compare planned groups on the Research rounds sheet of `research-planning.xlsx` with **User groups represented** in `research-sessions.xlsx` and the coded roles in session notes.

| Round | Planned groups | Actual participation in the example |
|---|---|---|
| `RND-201` | Borrowers (`UG-201`), depot staff (`UG-202`), telephone-only borrowers (`UG-203`) | `SES-201`: User groups represented `UG-202`; the notes identify `PAR-201` in their depot staff role. `SES-202`: `UG-201`; the notes identify `PAR-202` as a borrower. |
| `RND-202` | Depot staff (`UG-202`) and telephone-only borrowers (`UG-203`) | `SES-203`: User groups represented `UG-202`; the returning participant `PAR-201` represented the staff role. No telephone-only borrower role is recorded for this round. |

That gives three participations by two people. `UG-203` is the follow-up gap for testing the supported route. Invitation status and contact details belong in approved restricted recruitment records.

The round protocol links to the working board. In the source register, `DOC-202` links to the depot team’s board snapshot, v1 dated 10 October 2026. The **Description** identifies the proposed process in its “Readiness handoff” frame. Access is by request. Before keeping a copy, the team agrees a retention period with the board owner. The research sessions support the claims about what happened at the depot.

## Deciding whether a repairs service is ready to expand
Follow a decision about expanding a service and the evidence that supports or challenges it. The trial export is fictional.

### The brief

A council has tried a new way for tenants to reschedule a repair. The service owner must decide whether to extend the trial from one housing area to two. The digital team has improved its form. The operations lead asks whether staff can move the same appointment for a tenant who calls.

Follow both routes from the appointment message to confirmation in the scheduling system.

### Discovery: understand what people are trying to do

| Record | Sample entry |
|---|---|
| Research planning, Research questions, `RQ-301` | How does a tenant know that their old slot has been released and the new one is confirmed? |
| Observation rows `EV-301`, `EV-302` | Each observation cites the checked v1 transcript for its session. At `SES-301` 00:08:10–00:08:42 a tenant describes rearranging work twice after an unclear change. At `SES-302` 00:14:05–00:14:28 a call handler describes checking the repairs system separately after taking a request. |
| Finding row `FND-301` | **Reviewed.** After reviewing the two observations, the team agrees that neither receipt of a request nor an acknowledgement establishes the new appointment. Two observed accounts establish the failure mode. Its frequency is unknown. |
| Need `UN-301` | When I move a repair visit, I need to know which appointment is confirmed, so that I can be at home at the right time. |

The operations lead checks whether clearer wording is enough or the booking system also needs to change. The finding records that uncertainty. After the discussion, an assistant can check the team’s account against the source.

### Alpha: compare a message change with a service change

The team compares a clearer acknowledgement with a confirmation that is sent after the new slot is committed. The second option is shown in Design artefacts as `PRT-301 v2` (Prototype) and `JNY-301 v2` (Journey or map). The prototype’s **Link** opens the retained Figma flow. The prototype simulates the confirmation. It provides no evidence that the scheduling system can commit a change in a live pilot.

In `decisions.xlsx`, `DEC-301` records the service owner's choice to test the shared confirmation with both the online form and the telephone route. **Why** cites `FND-301`, `UN-301`, `JNY-301 v2` and `PRT-301 v2`, and explains why clearer acknowledgement alone was set aside. The test remains conditional on the operations lead determining what happens when the final slot disappears before the change is saved.

In `requirements.xlsx`, the team could capture `FR-301` with Type Functional and Requirement “Confirm a rescheduled repair visit after committing the new slot and releasing the old one.” Source cites `UN-301` and `DEC-301`. Status is Proposed while the team agrees the behaviour, and Verification is Not yet checked.

### Beta: state what the trial actually establishes

For the online route in one area, the beta lead sampled 30 rescheduling attempts from 9 to 15 November 2026, against service build beta-07. The team validated the counting method. Twenty-seven have an independently matched old-slot release and new-slot confirmation. Three ended with an acknowledgement and no commitment before the team checked. The denominator includes all 30 attempts.

Register the versioned trial export as `DOC-301` in the source register. The example observation `EV-303` in `findings-and-observations.xlsx` cites `DOC-301`, trial export v1, sheet `Online attempts`, rows 2–31, covering 9 to 15 November. The calculation includes every attempt.

In a separate beta-07 session, a tenant read the new slot correctly from a confirmation. Shown an acknowledgement alone, the same tenant could not tell which appointment to attend. The team records `EV-304`, `SES-303`, checked transcript v1, `00:03:10–00:05:22`. The operations lead still needs to check the telephone route.

| Record | Team's assessment and next decision |
|---|---|
| User need `UN-301` | `FND-301` supports the need and goes in **Supporting record IDs**. The team assesses **Fulfilment** as Partly met. **Scope and evidence** records the date (2026-11-16), online build beta-07, one housing area, the three unconfirmed attempts (`EV-303`) and the tenant’s difficulty identifying their slot (`EV-304`). The telephone route and other tenants’ understanding remain open. **Delivery decision** is Not decided. `DEC-302` records holding the expansion and running another pilot check. |
| Outcomes and measures | `OUT-301` is reliable rescheduling on the Outcomes sheet. `MET-301` on Success measures uses matched confirmed changes divided by all attempted changes. Keep the baseline and beta scope visible. A second result is needed for telephone changes before claiming both routes work. |
| Decision | On 16 November 2026 the service owner agreed to hold the expansion and run one further pilot check (`DEC-302`). The operations lead will test slot-conflict recovery with call handlers. The analyst will report the same denominator separately for online and telephone routes. |

The team can add this bounded result and `EV-303` to the **Verification** field of `FR-301` when it checks the applicable functional requirement. Keep the test scope, date and unassessed telephone route visible.

The draft playback can say, “27 of 30 online pilot attempts were confirmed. Three were still unconfirmed at the observation point. The telephone route is still unassessed.” Link the evidence and decision. Ask the team to confirm whether the playback reflects its view.

### Try it with your team

1. Give a colleague only the brief and trial result. Ask what they would tell the service owner and what could change their answer.
2. Give them the rest of this page. Ask them to trace the claim to `EV-303`, describe what that result tells them about `UN-301`, and explain why the team made `DEC-302`.
3. Share this page with an assistant and ask it to draft the sentence the team has agreed. Then give it a plausible but unsupported input such as “all telephone bookings succeed”. Check that it identifies the missing evidence and carries the unknown forward.
4. Discuss what to do if the pilot shows a materially different result for tenants who need support. Let the team make that decision and enter the owner, evidence and next review in the existing records.

See the [GDS discovery](https://www.gov.uk/service-manual/user-research/user-research-in-discovery), [alpha](https://www.gov.uk/service-manual/user-research/user-research-in-alpha) and [beta](https://www.gov.uk/service-manual/user-research/user-research-in-beta) guidance for the purposes of each phase.
