# Worked example: deciding whether a repairs service is ready to expand

Use the fictional records on this page to decide what to test before expanding a service. The workbook links show where a team would save the records. The example records and trial export are described here only.

## The brief

A council has tried a new way for tenants to reschedule a repair. The service owner must decide whether to extend the trial from one housing area to two. The digital team has improved its form. The operations lead asks whether staff can move the same appointment for a tenant who calls.

Follow both routes from the appointment message to confirmation in the scheduling system.

## Discovery: understand what people are trying to do

| Record | Sample entry |
|---|---|
| [Research question](../research-questions.xlsx) `RQ-301` | How does a tenant know that their old slot has been released and the new one is confirmed? |
| [Evidence rows](../findings-and-observations.xlsx) `EV-301`, `EV-302` | Each observation cites the checked v1 transcript for its session. At `SES-301` 00:08:10–00:08:42 a tenant describes rearranging work twice after an unclear change. At `SES-302` 00:14:05–00:14:28 a call handler describes checking the repairs system separately after taking a request. |
| [Finding row](../findings-and-observations.xlsx) `FND-301` | After reviewing the two observations, the team agrees that neither receipt of a request nor an acknowledgement establishes the new appointment. Two observed accounts establish the failure mode. Its frequency is unknown. |
| [Need](../user-needs.xlsx) `UN-301` | When I move a repair visit, I need to know which appointment is confirmed, so that I can be at home at the right time. |

The operations lead checks whether clearer wording is enough or the booking system also needs to change. The finding records that uncertainty. After the discussion, an assistant can check the team’s account against the source.

## Alpha: compare a message change with a service change

The team compares a clearer acknowledgement with a confirmation that is sent after the new slot is committed. The second option is shown in [prototype](../prototypes.xlsx) `PRT-301 v2` and [journey](../user-journeys.xlsx) `JNY-301 v2`. The prototype’s **Link** opens the retained Figma flow. The prototype simulates the confirmation. It provides no evidence that the scheduling system can commit a change in a live pilot.

In [decisions.xlsx](../decisions.xlsx), `DEC-301` records the service owner's choice to test the shared confirmation with both the online form and the supported telephone route. **Why** cites `FND-301`, `UN-301`, `JNY-301 v2` and `PRT-301 v2`, and explains why clearer acknowledgement alone was set aside. The test remains conditional on the operations lead determining what happens when the final slot disappears before the change is saved.

## Beta: state what the trial actually establishes

For the online route in one area, the beta lead sampled 30 rescheduling attempts from 9 to 15 November 2026, against service build beta-07. The team validated the counting method. Twenty-seven have an independently matched old-slot release and new-slot confirmation. Three ended with an acknowledgement and no commitment before the team checked. The denominator includes all 30 attempts.

Register the versioned trial export as `DOC-301` in the [source register](../project-sources/source-register.xlsx). The example observation `EV-303` in [findings-and-observations.xlsx](../findings-and-observations.xlsx) cites `DOC-301`, trial export v1, sheet `Online attempts`, rows 2–31, covering 9 to 15 November. The calculation includes every attempt.

In a separate beta-07 session, a tenant read the new slot correctly from a confirmation. Shown an acknowledgement alone, the same tenant could not tell which appointment to attend. The team records `EV-304`, `SES-303`, checked transcript v1, `00:03:10–00:05:22`. The operations lead still needs to check the telephone route.

| Record | Team's assessment and next decision |
|---|---|
| [User need](../user-needs.xlsx) `UN-301` | The team assesses **Fulfilment** as Partly met. **Scope and evidence** records the date (2026-11-16), online build beta-07, one housing area, the three unconfirmed attempts (`EV-303`) and the tenant’s difficulty identifying their slot (`EV-304`). The telephone route and other tenants’ understanding remain open. **Delivery decision** is Will address (`DEC-302`). |
| [Outcome](../outcomes.xlsx) and [success measure](../success-measures.xlsx) | `OUT-301` is reliable rescheduling. `MET-301` uses matched confirmed changes divided by all attempted changes. Keep the baseline and beta scope visible. A second result is needed for assisted changes before claiming both routes work. |
| [Decision](../decisions.xlsx) | On 16 November 2026 the service owner agreed to hold the expansion and run one further pilot check (`DEC-302`). The operations lead will test slot-conflict recovery with call handlers. The analyst will report the same denominator separately for online and supported routes. |

The draft playback can say, “27 of 30 online pilot attempts were confirmed. Three were still unconfirmed at the observation point. The supported route is still unassessed.” Link the evidence and decision. Ask the team to confirm whether the playback reflects its view.

## Try it with your team

1. Give a colleague only the brief and trial result. Ask what they would tell the service owner and what could change their answer.
2. Give them the rest of this page. Ask them to trace the claim to `EV-303`, describe what that result tells them about `UN-301`, and explain why the team made `DEC-302`.
3. Share this page with an assistant and ask it to draft the sentence the team has agreed. Then give it a plausible but unsupported input such as “all supported bookings succeed”. Check that it identifies the missing evidence and carries the unknown forward.
4. Discuss what to do if the pilot shows a materially different result for tenants who need support. Let the team make that decision and enter the owner, evidence and next review in the existing records.

See the [GDS discovery](https://www.gov.uk/service-manual/user-research/user-research-in-discovery), [alpha](https://www.gov.uk/service-manual/user-research/user-research-in-alpha) and [beta](https://www.gov.uk/service-manual/user-research/user-research-in-beta) guidance for the purposes of each phase.
