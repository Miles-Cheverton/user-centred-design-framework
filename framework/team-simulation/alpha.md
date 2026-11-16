# Alpha: exploring possibilities without manufacturing certainty

This fictional role-play of UCD Project Foundations v0.3.0 is not observed research, usability testing, a real AI run or productivity evidence. No live project workbook has been populated. Paths refer to a fictional copy of `template/`.

**0.3.1 revision:** the intended workflow now makes human-led analysis explicit. The team forms findings and assessments before AI checks their sources and documents them. The revised scenes remain fictional; see the [assessment](README.md) for guidance changes and validation limits.

Discovery's DEC-103 authorises bounded exploration, not building the sponsor's booking app. FND-101 supports UN-101, understanding collection arrangements, within limited evidence. FND-102 records conflicting timing preferences. ASM-102 and PROP-101 explore whether “confirmed” hides a readiness gap. UN-102, accessible supported borrowing, and UN-103, cancellation and return responsibilities, remain candidates. Operational feasibility, cost and wider coverage remain unresolved.

The discovery team continues. Its behaviours below are situational, not diagnoses or stereotypes about professions.

## 1. Twelve sketches, one useful leap

Leo produces twelve rough sketches: collection windows, a preparation tracker, a reminder, a telephone script and several visual variations. Ben starts assigning a prototype ID to each. Leo stops sketching to answer questions about missing fields.

> **Leo:** “These three are the same idea drawn badly. Recording them is becoming the work.”
>
> **Ben:** “I want us to remember why we rejected things.”
>
> **Ruth:** “What if the important distinction isn't appointment time? It's whether we can honestly tell someone the equipment is ready.”
>
> **Maya:** “That changes the staff task as well as the message. Let's explore a promise we can keep.”
>
> **Tom:** “A phone call might test that before we build a tracking system.”

Ruth connects ambiguous language, anxious travel and operational readiness. The team values this extrapolation without pretending discovery established its effectiveness.

Using `skills/record-design-option/SKILL.md`, the assistant retains PROP-201 in `design-proposals.md` as the developed replacement for PROP-101: distinguish reservation from readiness, with a contact fallback. PROP-101 becomes `Superseded`, with `Superseded by = PROP-201`; its original rationale remains. PROP-201 refers to ASM-102 and tests usefulness and staff feasibility.

PRT-201 v1 is registered in `prototypes.xlsx` when chosen for research. `Proposal IDs` points to PROP-201; `Journey versions` points to JNY-201 v1. DEC-201 records the choice of approach to test. Disposable layout variations need no separate rows. A rejected tracking-dashboard idea still contributes substantive learning: it would imply a level of operational visibility not established. That reasoning belongs in the proposal and decision, rather than another abandoned-options register.

**What works; smallest improvement.** The retention threshold already protects exploration. The failure is Ben interpreting completeness as diligence. Add one contrasting example to the existing design-option guide: an unshared sketch can disappear; a rejected idea that changes the team's reasoning must leave its learning behind. Real teams must judge that boundary together. [Hill-Scott's practitioner account](https://designnotes.blog.gov.uk/2021/03/02/three-things-product-teams-need-from-designers/) warns that design gatekeeping can encourage minimal compliance; it does not establish this particular remedy's effectiveness.

## 2. The link opens, but it opens the wrong design

After sessions using a retained PRT-201 v1 snapshot, Leo creates v2 for substantive review. His external preview URL is then overwritten by work towards v3. Meanwhile, Maya's JNY-201 v1 graphic gains a telephone branch without its text description being revised.

> **Amira:** “Can the assistant explain the flow we tested for Sana?”
>
> **Assistant, mistaken attempt:** “Users tested the readiness message and telephone fallback shown here.”
>
> **Jo:** “That fallback wasn't in the test version. The link works, but the claim doesn't.”
>
> **Leo:** “You're right. I reused the preview. I didn't mean to change the evidence.”
>
> **Priya:** “Keep the session record as it happened. We need to identify the design, not rewrite the session to fit it.”

A working URL does not prove historical identity. The assistant must retract its inaccurate summary and distinguish inspected material from recorded claims.

`research-sessions.xlsx` keeps `Prototype version = PRT-201 v1` for SES-201 and SES-202. The retained v1 source establishes that version. Findings use `Design versions = PRT-201 v1`; no inverse finding list is added to the prototype register. `prototypes.xlsx` remains the owner of `Source path or URL`, `Preview URL`, `Status` and `Superseded by`.

Under `check-project-integrity`, an exact known path may be repaired; missing interactions cannot be guessed from v3. Leo retrieves the reviewed v2 source. Maya restores the original JNY-201 v1 graphic from its snapshot and starts a working revision, destined for JNY-201 v2. Matching `Graphic path` and `Text path` values alone cannot establish equivalent meaning.

**What works; smallest improvement.** Exact versions expose the mismatch, but only human knowledge catches the initial false claim. Add a retained-version handover check to the existing guide: open the source and preview, identify the version, and compare material branches with the text. Avoid registering every autosave. The unanswered question is how cheaply a real team can do this across its chosen tools.

## 3. A wording argument reveals a service decision

Tom's existing status field is `confirmed`. Ruth objects to using “Your equipment is ready” when the system only knows a reservation exists. Her criticism lands as a criticism of Tom's competence.

> **Ruth:** “We can't tell people it's ready when we don't know.”
>
> **Tom:** “I didn't propose lying. That's the status the system has.”
>
> **Dan:** “Can we separate what the database calls it from what we can promise?”
>
> **Ruth:** “Yes. I should have challenged the promise, not your implementation.”
>
> **Tom:** “Then let's show the reservation clearly and make readiness a separate event. We still need to test whether staff can provide it.”

Ruth and Tom repair the misunderstanding and pair on the next candidate. Maya asks what happens if readiness information never arrives. The assistant must not rate colleagues' personalities or appoint a winner.

The assistant uses `record-decision` for DEC-202 only after the humans agree: a reservation message must not assert physical readiness. `decisions.md` records the choice, alternatives and operational consequence. It does not convert Tom's current system limitation into an immutable service policy. If the team records a constraint, its source and flexibility must reflect what is actually known.

PROP-201 records the new question and uncertainty. PRT-201 v3's README explains that readiness is simulated and that no live depot connection exists. Its register holds the version and relationships; the README does not duplicate lifecycle status. This lets a developer understand what to build experimentally without treating a demonstration as a working capability.

**What works; smallest improvement.** Separate proposal, decision and prototype limitations prevent an implementation detail silently becoming policy. They cannot ensure content joins early enough. Add “Which words make a promise another part of the service must fulfil?” to the existing substantive design-review example. Use existing pairing and review time. [GDS designers' accounts](https://designnotes.blog.gov.uk/2022/03/25/a-day-in-the-life-of-an-interaction-designer-at-gds/) describe content pairing and developer collaboration; they are practitioner accounts, not evidence that a prescribed ceremony suits every team.

## 4. A promising result becomes an argument about agreement

In the constructed research, SES-201 shows a volunteer understanding the reservation/readiness distinction in v1, while still worrying about unpredictable travel. SES-202 exposes a screen-reader barrier that prevents completion. These examples are fictional observations, not a sample from which prevalence can be estimated.

> **Leo:** “The main idea worked. Can we call it validated and fix accessibility next?”
>
> **Priya:** “There is useful evidence for the distinction. That isn't evidence for the whole route.”
>
> **Amira:** “Nobody objected to selecting it yesterday.”
>
> **Jo:** “I didn't speak. I wasn't sure whether the selection decision had already been made.”
>
> **Amira:** “It hadn't. Thanks for saying that. Let's record what we know and decide what selection means.”

A failed AI response would turn enthusiasm into consensus and demote the barrier. Priya and the team instead discuss the sessions together: which observations support the distinction, what prevented completion and what remains uncertain. They reach the bounded comprehension conclusion and the completion-barrier conclusion themselves. The assistant must not generate those interpretations first and offer them for approval.

After this analysis, `record-research-finding` retains the team's conclusions as FND-201, the bounded comprehension benefit, and FND-202, the completion barrier and remaining variation. The assistant checks the authorised source passages against the supplied conclusions, flagging discrepancies for the team rather than resolving their meaning. `evidence.xlsx` contains selected EV-201 and EV-202 observations, with exact `Source ID`, `Source version or path`, `Locator`, `Context` and `Limitations`. The findings identify SES-201/202 and PRT-201 v1. They preserve contrary material and refer to discovery's FND-102 without claiming the new work resolved timing preferences.

Priya and the team check that the recorded wording preserves their analysis; the assistant records `Reviewed` only after that review. They determine that UN-102 can now become `Evidenced` with the relevant supporting record: the need exists. That does not mean it has been met. Candidate v3 remains untested with borrowers, however persuasive its improvements appear.

**What works; smallest improvement.** The schema preserves disagreement, but a polished “consensus” narrative can bypass it. Add a short prompt to existing decision capture: “What material objection or uncertainty changes this choice?” Do not require everyone to approve every entry. [Edmondson's field study](https://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Group_Performance/Edmondson%20Psychological%20safety.pdf) associates psychological safety with team learning; it does not show that adding a documentation field creates safety.

## 5. Operations joins late, and access is mistaken for absence

Nia misses the design meeting while covering collections. She later explains that a readiness call may depend on a person who is also unloading returned equipment. Meanwhile, the assistant cannot open a restricted research recording.

> **Nia:** “I support clearer messages. I can't promise somebody will make that call whenever equipment is prepared.”
>
> **Maya:** “Our map made that step look automatic.”
>
> **Assistant, appropriate response:** “The reviewed finding is available; I cannot independently inspect its restricted recording.”
>
> **Ben:** “So is consent missing?”
>
> **Priya:** “No. Access and consent are different questions. I'll check the authorised session record; we won't copy participant material into a wider folder.”

Inaccessibility establishes neither missing consent nor independent verification of the original material through a summary.

Nia and the team discuss what this dependency means and the limits of the staff account. After they draw the operational conclusion, the assistant registers the discussion as supplied material, DOC-201, through `project-background/document-register.xlsx`. EV-203 records its relevant observation and locator; FND-203 retains their conclusion with its limitations. This is a staff account, not a retrospectively invented participant session. If subsequent research involves Nia as a participant, that requires the applicable research arrangements separately.

Maya finishes and retains JNY-201 v2 with matching graphic and text: preparation and communication depend on staff availability, with a contact fallback. `add-use-case` captures UC-201 in `use-cases.md`, arranging borrowing through supported contact, including the unanswered “no response” branch. DEC-203 records that automatic notification is not established; this does not prove the manual alternative feasible.

**What works; smallest improvement.** The framework can hold operational knowledge alongside user evidence without confusing their origins. It cannot make absent colleagues available. Add one existing-review question: “Who must do something for this journey to work, and have we heard from them?” Preserve unanswered dependencies in their existing owner; do not add attendance policing or a second action tracker.

## 6. The alpha decision is useful without being all green

Sana needs a funding recommendation. The assistant assembles a concise summary from the owning files.

> **Sana:** “Do you recommend beta?”
>
> **Amira:** “A bounded beta direction, yes. We have not established readiness to put it in front of the public.”
>
> **Tom:** “We need an operable staff process and an accessible supported route, not just a selected prototype.”
>
> **Priya:** “And v3 still needs borrower testing. Cancellation and returns remain open.”
>
> **Sana:** “Record that direction with those conditions. Bring the capacity, cost and release boundary back for a separate decision.”

DEC-204 in `decisions.md` is therefore an agreed direction with explicit preconditions, not deployment approval or a service-assessment result. PRT-201 v3 may be `Selected` as the candidate; v2 is `Superseded` by that exact version. JNY-201 v2 describes a proposed experience. Neither status means implemented.

Priya, Maya and the team assess the needs against the evidence and agree UN-101 is `Partly met` and UN-102 is `Not met`, both scoped to PRT-201 v1. Only then does `assess-user-need-coverage` record their judgements with the relevant EV references. Each assessed row needs the actual review date within the fictional project. `Remaining gap` retains the timing/operational uncertainty and inaccessible completion route respectively. Both delivery choices are `Will address`. UN-103 remains `Not assessed` / `Not decided`. No claim about v3 or the live service follows from these rows.

**What works; smallest improvement.** Separate fulfilment and delivery choices resist optimistic reporting. The summary must reconcile all active needs, not merely count populated rows. Add one phase-decision example showing a selected direction with unmet preconditions. [GDS alpha guidance](https://www.gov.uk/service-manual/agile-delivery/how-the-alpha-phase-works) supports exploring approaches and deciding whether and how to proceed; this fictional recommendation establishes neither readiness nor compliance.

## Alpha findings

Severity means potential consequence here, not a measured defect rate.

These issues were identified by the original simulation. The [0.3.1 guidance changes](README.md#guidance-changes-in-031) address the working instructions; real-team validation remains outstanding.

| Finding | Severity | Smallest change | Real validation needed |
|---|---|---|---|
| **A1. Retention becomes a demand to document every sketch.** | Medium | Add a disposable-sketch versus retained-learning example to the existing guide. | Observe whether teams preserve learning without interrupting ideation. |
| **A2. A working preview or version label masks a different design.** | High | Add an open-and-identify check, including material graphic/text branches, at retained handover. | Try mutable design tools, exports and inaccessible interactions with real teams. |
| **A3. A content dispute hides an operational promise.** | High | Ask which words require another part of the service to act. | Observe whether early pairing exposes promises and reduces rework. |
| **A4. Silence becomes consensus; positive synthesis hides barriers.** | High | Capture material objections and decision-changing uncertainty in existing decision context. | Test whether less influential colleagues can correct summaries without social penalty. |
| **A5. Absent operations and restricted evidence produce false certainty.** | High | Ask who performs each critical step; distinguish access, consent and evidence limits. | Check restricted-source handling and realistic part-time staff participation. |
| **A6. Selected designs and partial coverage become beta approval.** | High | Add a bounded phase-decision example and reconcile coverage to active needs. | Ask independent readers what is authorised, demonstrated and still unresolved. |

## Continuity handover to beta

- **Direction:** PROP-201 supersedes PROP-101, preserving its rationale while developing the readiness distinction and supported contact. JNY-201 v2 is the aligned proposed journey. PRT-201 v3 is the selected candidate, untested with borrowers; SES-201/202 and FND-201/202 concern PRT-201 v1.
- **Knowledge:** FND-201 supports bounded comprehension benefit. FND-202 retains the accessibility failure and variation. FND-203 records operational learning from DOC-201, with no invented research session. Discovery's conflicting timing preferences remain relevant.
- **Needs:** UN-101 is evidenced, partly met in v1; UN-102 is evidenced, not met in v1; both will be addressed. UN-103 remains proposed and unassessed. None is established as fulfilled by a live service.
- **Authority:** DEC-204 agrees a conditional beta direction. Before simulated public use, beta must explicitly establish staff capacity/process feasibility, cost and resources, accessible supported-route verification and the release boundary, and record the resulting human decision.
- **Open work:** test v3; address wider inclusion, cancellation/returns, operating costs and outcome baselines. The framework's integrity check cannot settle these by completing cells.
