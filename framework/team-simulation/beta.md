# Beta: delivering the whole service under pressure

This fictional v0.3.0 walkthrough is not a team trial. Dialogue, records, dates and results are invented. Paths refer to a hypothetical `template/` copy; live registers remain unchanged. SharePoint coauthoring resolves simultaneous editing in this scenario. The review inspected the coverage workbook, guides and skills; it did not run them against a live service.

**0.3.1 revision:** people now explicitly analyse research and judge need fulfilment before AI checks sources, tidies their conclusions and records them. These revised scenes are fictional illustrations of the updated guidance, not observed results.

The [alpha handover](alpha.md) selects PRT-201 v3 as a candidate, not a tested or deployed service. JNY-201 v2 describes reservation, readiness and telephone preparation; returns remain incomplete. DEC-204 requires operational feasibility, resources, accessible support and release boundaries to be resolved. UN-101 is Partly met against PRT-201 v1, UN-102 is Evidenced but Not met against that prototype, and UN-103 remains Proposed and Not assessed. 

GDS describes beta as developing and improving a service with users; this simulation therefore includes operating arrangements. [GDS beta guidance](https://www.gov.uk/service-manual/agile-delivery/how-the-beta-phase-works). Research grounding and limitations are in [sources.md](sources.md).

## B1. A useful meeting becomes a useful change

Before public use, fictional borrower sessions SES-301 and SES-302 test the exact PRT-201 v3 snapshot. Priya and the team discuss their observations and conclude that the evidence supports bounded progression, not full fulfilment. Staff separately rehearse the depot process. The team then verifies the implemented `beta-1` web and supported routes and establishes staffing, capacity and costs for the limited release. DOC-302 records that verification and resource agreement; EV-301 identifies its results and limits. These checks are distinct from prototype testing. Sana makes DEC-301: permit `beta-1` at one depot during staffed hours, with named support and an explicit stop condition. This fictional decision does not claim a service assessment passed.

At the first beta research playback, Priya brings fresh observations of borrowers who interpret a reservation as permission to travel.

> **Nia:** “An item can be reserved while it is still out on loan. I cannot promise it will be here tomorrow.”
>
> **Leo:** “Then another confirmation screen will not solve this. We need a promise the depot can actually keep.”
>
> **Ruth:** “Let's say what is reserved, then explain when they can safely travel.”
>
> **Amira:** “Agreed: test that change with the preparation process. Do not announce it as solved.”

Priya leads the team's analysis: they compare observations, discuss Nia's explanation and retain the different timing preferences from alpha. They reach the finding themselves and distinguish it from the next experiment. The team then authorises `extract-project-records`: the discussion is DOC-301 in `project-background/document-register.xlsx`; borrower observations keep their SES sources in `evidence.xlsx`. `record-research-finding` documents their conclusion as FND-301, checking the supplied wording against authorised source passages. If only a raw testing transcript had been supplied, the assistant would retain source material or literal observations as requested and leave conclusions for human analysis. Amira's explicit agreement supports `record-decision` for DEC-302; silence from absent colleagues does not.

Maya's insight connects the message to a depot action. Tom and Ruth pair on the existing delivery item; they do not copy its acceptance criteria into three registers. The finding's **Supporting evidence**, **Context and limitations** and **Implications** preserve the rationale.

**Framework result:** separate owners and staged capture help turn research into action without demanding a polished report. This reflects GDS's practitioner account of embedded research and shared analysis, rather than proving this template's effectiveness. [GDS research practice](https://gds.blog.gov.uk/2013/08/30/how-we-do-user-research-in-agile-teams/).

**Smallest improvement:** add one worked playback example to the existing meeting route. Humans confirm the consequential interpretation during playback; AI saves the agreed records afterwards. 

## B2. Shared records do not guarantee shared meaning

Ben captures BR-301 in `business-rules.xlsx`: call borrowers in the morning before collection. He marks it **Proposed**, drawing on some borrowers' preferences. Tom reads the concise rule while estimating work and assumes it is the agreed operating approach. Nia has not discussed what morning calls would mean for depot preparation.

> **Tom:** “I've estimated the callback work against the rule Ben recorded.”
>
> **Ben:** “It is proposed. I needed something concrete for us to discuss.”
>
> **Priya:** “The finding also says morning calls do not suit some borrowers. That uncertainty has not been shared.”
>
> **Nia:** “That is when we prepare equipment. Could people choose a contact window instead?”
>
> **Dan:** “Let's discuss that in the review already booked. No separate approval tracker.”

Asked to explain the apparent agreement, the assistant follows BR-301's **Source** and **Status**, then the finding's supporting evidence and limitations. It reports that the proposed rule has no recorded approval. It does not treat Ben's authorship, populated fields or Tom's estimate as authority. Using `record-project-item`, it can clarify the source and proposed status when authorised; changing the operating rule remains a human decision.

Nia's idea connects user preferences to staffing rather than merely choosing between two documents. The team retains the proposed rule and its uncertainty, discusses the alternative in the existing design proposal, and tests the arrangement before considering approval. The delivery item retains the estimation assumption. 

**Framework result:** separate evidence, proposal and authority fields expose the misunderstanding. Correct shared records alone cannot ensure readers notice status or understand consequences for another role.

**Smallest improvement:** add a proposed-rule example to the existing review route: before relying on a consequential statement, confirm what it authorises and who must act differently. Use existing conversations and records.

## B3. The interface passes; a borrower still cannot collect

Jo's keyboard fixes pass their defined checks. Tom proposes marking UN-102 Met in full. Meanwhile the telephone script still calls the reservation a “confirmed collection”; on a busy morning nobody answers the support line. A borrower travels before equipment is prepared.

> **Tom:** “The acceptance criteria pass. What additional engineering work are we holding this for?”
>
> **Jo:** “I think the criteria only cover the form. I wasn't sure whether I was allowed to challenge the release summary.”
>
> **Nia:** “The phone message sends people here early. That is not in your form.”
>
> **Tom:** “You're right about the boundary. Show me the failed handoff; let's fix that together.”

Delivery items, non-functional requirements and user needs answer different questions. In `non-functional-requirements.xlsx`, the defined keyboard criterion may have **Record status = Agreed** and **Verification status = Met**, supported by its report's EV record. That does not automatically meet UN-102 or establish service-wide accessibility.

Priya, Maya and the team discuss what the evidence establishes across both routes and judge UN-102 Partly met. Using `assess-user-need-coverage`, the assistant then records their judgement in the actual eight fields:

| Field | Fictional human assessment |
|---|---|
| User need ID | UN-102 |
| Assessment | Partly met |
| Evidence IDs | EV-304; EV-305 |
| Remaining gap | Supported telephone route fails during staffed periods; the shared script misstates collection readiness. |
| Delivery decision | Will address |
| Decision ID | DEC-302 |
| Assessed version or scope | beta-1: one depot, web and telephone, staffed hours |
| Assessed on | 2026-11-09 — simulated assessment date |

Priya and Maya check that the saved record faithfully reflects the team's assessment. AI does not propose a fulfilment judgement for them to rubber-stamp or change it because a test is green. Ruth and Nia repair the wording and handoff together. Jo's contribution needs an actual receptive response, not another mandatory field. Psychological safety research associates safety with learning behaviour; it does not show that a template creates it. [Edmondson study](https://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Group_Performance/Edmondson%20Psychological%20safety.pdf).

**Smallest improvement:** add this component-pass/need-gap example to the coverage guide. The release conversation explicitly welcomes contradictory operating evidence without scoring who raised it.

## B4. A reassuring total hides people

For the sponsor update, Dan reads the Summary sheet as “coverage complete”. There are three recorded rows. A fourth active need, UN-301, was captured from research but has no assessment row: borrowers running a regular programme need to plan repeated borrowing before committing volunteers. The service currently allows only the next booking.

> **Dan:** “All three rows have a decision. We have dealt with every need.”
>
> **Ben:** “There are four active needs. A decision is not a fulfilment result.”
>
> **Amira:** “Could we move the repeated-booking need out of scope and leave it off this view?”
>
> **Sana:** “We can limit this release. We still need to show whose problem remains.”

The assistant retracts its mistaken simulated draft, “three of three covered”, after checking the workbook. Summary counts nonblank **User need ID** rows; its independent assessment and delivery counts do not establish a complete population, and there is no completeness percentage. Duplicate rows could also inflate totals. Missing rows are gaps, not silently counted as Not assessed.

The team reconciles every active need before presenting a service-level view. After analysing the research, the humans judge UN-301 **Not met**; the assistant records their assessment with EV-310, the remaining gap, scope and date. Sana makes DEC-303: **Will not address** repeated-series planning in `beta-2`, recording the stock-allocation rationale, consequences and a revisit trigger. This trade-off does not waive applicable obligations. Changing delivery scope does not erase the need or turn it into a success.

**Framework result:** the existing two dimensions prevent “won't do” becoming “met”, provided people use them honestly. They cannot prevent selective presentations. The GDS designer account warns that gatekeeping can encourage minimum compliance; a heavier checklist would risk reinforcing this behaviour. [GDS practitioner account](https://designnotes.blog.gov.uk/2021/03/02/three-things-product-teams-need-from-designers/).

**Smallest improvement:** the existing coverage skill should offer a short reconciled statement: recorded population, missing assessments, unmet groups and consequential choices. Do not add arbitrary partial-credit percentages or hide inconvenient needs.

## B5. The apparently complete evidence chain breaks

A replacement researcher reviews the planned `beta-2` update. One recording is inaccessible, a transcript link now opens a corrected version, and an old finding still concerns PRT-201 v1. Dan asks the assistant to “tidy the links and confirm we can proceed”.

> **Dan:** “Priya already reviewed this. Do we really need to repeat it?”
>
> **Priya:** “Not all of it. The original transcript confused ‘return’ and ‘reserve’ in one important passage.”
>
> **Ruth:** “That changes whether we know the cancellation wording works.”
>
> **Maya:** “Keep the previous conclusion visible. Ask what the correction changes, rather than starting again.”

`check-project-integrity` follows **Source ID → Source version or path → Locator** in `evidence.xlsx`. `research-sessions.xlsx`'s **Current transcript link** is not historical proof of what an old EV cited. The assistant reports which sources it actually read. It cannot silently substitute a current document, assume a missing recording disproves a finding, or transfer prototype evidence to the operating release.

The team locates the retained prior transcript. Priya and colleagues discuss the corrected passage and decide whether it changes their conclusion. The AI can show the textual discrepancy but cannot reanalyse its significance or supply the replacement finding. An authorised path correction is safe only if the exact intended target is uniquely established. A changed human interpretation needs its own evidence and reviewed record. The old finding retains its context; replacements use **Superseded by**. Where access remains unavailable, the earlier scoped finding is retained with a verification limitation, not presented as freshly checked.

**Framework result:** provenance and version fields support selective recovery. They do not guarantee access or stop colleagues exchanging material outside the shared record. Research on one company's remote collaboration found more siloed communication; it motivates testing handovers, not assuming all distributed teams fail. [Microsoft collaboration study](https://www.microsoft.com/en-us/research/publication/the-effects-of-remote-work-on-collaboration-among-information-workers/).

**Smallest improvement:** add a failed-access example to the handover route: retained knowledge, source access limits and the one decision affected. Prioritise the decision-changing gap; do not demand reconstruction of every recording.

## B6. A conditional release decision, with useful uncertainty

After operating changes and further research, the team analyses the observations together and assesses `beta-2`. In their fictional judgement, EV-307 supports UN-101 in the bounded service scope. EV-308 still shows telephone-support failures. EV-309 supports only part of the now-evidenced UN-103: cancellation and return responsibilities remain unclear in one channel. They do not conclude that OUT-101 has improved over an established baseline.

> **Amira:** “The readiness change works well enough to continue the limited service. Can we expand now?”
>
> **Nia:** “Only if the support arrangement survives the rota change. Today's result used an extra person.”
>
> **Jo:** “Then the release scope needs to include that operating condition.”
>
> **Sana:** “Keep the limited scope. Expansion stays conditional on sustained support and the unresolved checks.”

The assistant formats the team's comparison, checks its references and records Sana's actual choice as DEC-304 through `record-decision`. It does not originate the assessment, decide release, certify standards, or promote a proposal to agreement. Tom explains the technical change; Nia explains the operating condition; Ruth and Priya explain the remaining user uncertainty. Dan uses the existing delivery work to coordinate responses.

The current fictional coverage is four rows at the same bounded `beta-2` scope: UN-101 **Met in full**; UN-102 and UN-103 **Partly met / Will address**; UN-301 **Not met / Will not address** under DEC-303. Each substantive assessment retains EV references and its simulated assessment date; earlier evidence and decisions remain. Met in full is a judgement about the stated scope, not every possible future circumstance. The Summary describes these recorded rows, not overall project success.

**Smallest improvement:** one concise handover route should assemble the current decision, operating assumptions, consequential unmet needs and source limitations from their owners. It should not create another maintained status report. A new colleague should be able to trace one uncertain claim back to evidence and identify who must decide, without reading every guide.

## Findings and real validation required

Severity indicates potential consequence.

These issues were identified by the original simulation. The [0.3.1 guidance changes](README.md#guidance-changes-in-031) address the working instructions; real-team validation remains outstanding.

| Finding | Severity | Minimal change to test | Real validation |
|---|---|---|---|
| B1 — Interpretation can be lost between research and delivery. | Medium | Playback example in the existing capture route. | Observe a team convert mixed meeting/research material without losing disagreement or duplicating work. |
| B2 — A shared proposed rule is mistaken for agreement. | High | Confirm authority and operational consequences in the existing review. | Observe whether a mixed team distinguishes a proposal, an estimate and an agreed operating rule. |
| B3 — Feature acceptance can be mistaken for fulfilment. | High | Whole-service counterexample in the coverage guide. | Ask a mixed team to assess a passing interface with a failing supported route; observe whether junior concerns affect the decision. |
| B4 — Recorded-row counts invite population and checkbox gaming. | High | Reconciled narrative using the existing skill. | Give reviewers missing/duplicate rows and a declined need; check their conclusion and retained denominator. |
| B5 — Stale or inaccessible evidence can become false certainty. | High | Access/version recovery example in the handover route. | Transfer a project with one corrected transcript and one inaccessible source; check what is honestly claimed. |
| B6 — A tidy handover can hide operating conditions. | High | Task-based handover drawn from existing owners. | New colleague locates one release condition and its decision-changing uncertainty without a second status register. |

A limited service continues under a human decision; expansion, sustained capacity, broader inclusion and outcome improvement remain unresolved. The framework can preserve evidence and make choices inspectable. Its value depends on humans making room for challenge and applying judgement; neither the files nor the assistant can manufacture that culture.
