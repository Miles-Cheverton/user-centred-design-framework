# Discovery: a fictional team using the framework

This is a constructed role-play of UCD Project Foundations 0.3.0, not observed user research or a measured usability result. Dialogue, people, service facts and record IDs below are fictional. The proposed record changes illustrate use of the actual templates and skills; they have not populated a live project. This project is separate from the AI-usability test fixture.

**0.3.1 revision:** the intended workflow now makes human-led analysis explicit. People discuss observations and form conclusions before AI checks sources, tidies wording and records their work. These revised scenes remain fictional, not a new test result; the [assessment](README.md) records the resulting guidance changes.

The service is a council's community-equipment lending service, covering enquiries, eligibility information, reservations, depot preparation, collection, returns and support. Its sponsor brief asks for a booking app. The question for discovery is what problem needs solving and whether further exploration is worthwhile. That follows the purpose of discovery in the [GDS Service Manual](https://www.gov.uk/service-manual/agile-delivery/how-the-discovery-phase-works); the detailed events are our simulation.

Amira is the product owner/product manager; Dan the delivery manager; Priya the user researcher; Leo the interaction designer; Maya the service designer; Ruth the content designer; Tom the technical lead; Jo a frontend developer; Ben the business analyst. Sana is the part-time service owner and sponsor; Nia represents depot operations. Each brings useful expertise and a different tolerance for uncertainty and administration.

Episode 2 draws on [Edmondson's study](https://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Group_Performance/Edmondson%20Psychological%20safety.pdf), which associated psychological safety with learning behaviour in 51 teams; it did not test this framework. Episode 4 draws on [Reichelt's GDS account](https://gds.blog.gov.uk/2013/08/30/how-we-do-user-research-in-agile-teams/) of collaborative analysis, retained findings and backlog actions. That historical practice account does not prescribe a universal workflow.

## 1. The brief already contains the answer

At the first meeting, Amira shares the app proposal and opens the project README. Dan sees the file catalogue and worries that the team has inherited a documentation project.

> **Amira:** “The funding conversation was about online booking. We should make that our first user need.”
>
> **Priya:** “We have a proposed solution. We have not established that online booking is what people need.”
>
> **Dan:** “Please don't make us fill twenty spreadsheets before talking to anyone.”
>
> **Ruth:** “Could we begin with what happens when someone tries to borrow something?”

A poor AI response would create an Evidenced need to book online, an agreed scope and a completed brief. The framework gives a better route: its starting page lets the team frame the work without completing every register. The AI uses `record-project-item` to register the supplied brief as DOC-101, with its proposal status and limitations. Funding authority is distinguished from evidence about users, even when both occur in the same document.

The team writes only the problem statement, candidate groups UG-101 borrowers and UG-102 service staff, and OUT-101 concerning successful borrowing. Priya and Amira identify the untested assumption, “An online booking app addresses the principal borrowing difficulties.” The AI records their wording as ASM-101. It does not rewrite the sponsor's intention out of history.

**Human decision:** Amira asks Sana to confirm that discovery may question the solution while examining the underlying policy intent. The AI cannot infer that freedom from the folder structure.

**What works:** distinct owning files prevent the brief, problem and need from collapsing into one claim. **Remaining friction:** document-level authority is easy to overgeneralise. The smallest improvement is a short example in the document guide showing a funded proposal that still contains untested claims; no extra register is needed.

## 2. “We agreed” means different things to different people

The AI receives the kickoff transcript with permission to save supported draft records. The recording stops before the final ten minutes. One passage reads, “Fine, let's just make everybody come at exactly ten,” without clear tone.

> **AI draft:** “The team agreed that collection will use fixed slots.”
>
> **Maya:** “That was my sarcastic response to the queue problem.”
>
> **Amira:** “I thought we had broadly accepted slots. Nobody objected afterwards.”
>
> **Jo:** “I did have a concern, but we had moved on.”
>
> **Dan:** “Let's separate the idea from the decision. What did we actually choose?”

This is the deliberately failed attempt. A plausible transcript summary has become an authority claim. The `extract-project-records` and `record-decision` procedures should prevent it: this is a team-meeting source DOC-102, not a research session, and silence is not agreement. The corrected DEC-101 remains Proposed. The team confirms that fixed slots are one possibility, not a settled service rule.

The AI corrects its misattribution and records the source gap without rewriting the transcript. It captures Jo's concern once she explains it, without diagnosing her or scoring participation.

**Human decision:** Amira and Dan repair the conversation and establish how future consequential choices will be stated aloud. **What works:** the distinction between Proposed and Agreed gives them a practical way to recover. **Remaining friction:** an authoritative-sounding summary can dominate before anyone checks its status. The smallest improvement is for extraction output to lead with “choices still needing confirmation,” using brief source excerpts, and for the team to confirm important decisions in its existing meeting close.

## 3. The people easiest to recruit become “the users”

Priya's initial research plan recruits experienced online borrowers. Nia cannot attend the planning meeting because the depot is short-staffed. Tom proposes examining the booking database while recruitment begins; Ben asks whether staff research is out of scope.

> **Priya:** “These borrowers are available this week. That is a start, not the whole population.”
>
> **Nia, later:** “Telephone borrowers often arrive with a different understanding of what we've reserved.”
>
> **Ben:** “The brief is about booking. Are we expanding discovery?”
>
> **Maya:** “Collection is where the booking promise meets the service. We need to understand that connection.”
>
> **Tom:** “I can investigate the system constraint without deciding the replacement system.”

The AI uses `record-project-item` and the research guides to retain UG-102 and amend RND-101's planned coverage. The protocol explains the initial sampling limits, the missing telephone experience and staff availability. RQ-101 asks what prevents confident collection. It includes the operational handoff rather than prescribing an interface answer.

The new information is recorded as a source-linked staff account; it does not become a validated finding about every telephone borrower. The AI may suggest a gap in coverage, but Priya chooses an appropriate method and recruitment approach. Dan and Amira resolve the capacity trade-off and record the agreed boundary in DEC-102, after confirming their authority within the fictional team.

**What works:** user groups, research questions and a practical protocol make exclusions visible. **Remaining friction:** a neatly populated group register can make planned inclusion look like achieved coverage. The smallest improvement is a clear distinction in readouts between groups identified, groups planned and groups actually heard from, derived from existing group, round and session records. It must not become another maintained spreadsheet.

## 4. Rich learning exists on the wall, but not in project memory

After the simulated sessions, the team's research wall contains observations about uncertain preparation, timing preferences, unclear messages and return responsibilities. Priya wants another synthesis session. Amira needs a sponsor update that afternoon.

> **Amira:** “Can the AI turn the wall into five recommendations?”
>
> **Priya:** “Some notes contradict each other. Recommendations would be premature.”
>
> **Leo:** “We can share what we're seeing without pretending we've finished.”
>
> **Dan:** “What is the smallest useful record we can save today?”
>
> **AI:** “I can save the observations and source references now. After your discussion, I can tidy and source-check the conclusions you reach; I will not generate findings from the wall.”

Priya brings the team together to talk through the observations, compare experiences and challenge explanations. They conclude that some borrowers need clearer collection arrangements before travelling. They also conclude that timing preferences differ and that they cannot infer a universal preference. Return responsibilities remain unresolved; the team records that further human analysis is needed rather than filling the gap with an AI theme.

Only then does `record-research-finding` document the team's conclusions as FND-101 and FND-102. Selected observations EV-101 and EV-102 point to their simulated source sessions and locators. The AI checks that the wording and references match the supplied human conclusions and authorised source passages. A contradictory passage is returned to the team as a discrepancy, not resolved by rewriting the finding. These identifiers are narrative examples, not claims that real recordings exist.

The AI does not create an EV row for every sticky note. A poorly legible note is flagged for clarification; an inaccessible wall area is not treated as empty. Priya and colleagues check the record reflects their discussion. Draft status describes unfinished documentation of human analysis, not permission for AI to supply unreviewed interpretations.

**Human decision:** the researcher and team perform the analysis and determine the conclusions. **What works:** early capture and retained contrary findings need not replace that conversation. **Remaining friction:** “capture every substantive finding” cannot be verified from file presence alone. The protocol close-out records the team's account of analysis coverage and remaining material. The AI reports what it checked without certifying that no unrecorded insight exists.

## 5. A human makes a useful leap beyond the evidence

Ruth listens to the team's wording about “confirmed reservations.” Nia explains that equipment is sometimes not prepared until the borrower arrives. Ruth connects that operational detail with the research, while Leo sketches a collection-readiness promise rather than a new booking flow.

> **Ruth:** “We might be using ‘confirmed’ to mean a slot exists, while the borrower hears ‘everything is ready’.”
>
> **Nia:** “That sounds plausible. It is not how we intended the message.”
>
> **Leo:** “What if we confirm readiness only after preparation, and give people a clear fallback?”
>
> **Tom:** “That might be a staff-process change before it is a software change.”
>
> **Priya:** “Let's explore it. The current evidence does not yet prove that explanation.”

The AI should neither dismiss the leap for lacking proof nor relabel it as a finding. It captures ASM-102 about the meaning of “confirmed,” and a retained proposal PROP-101 using `capture-assumption` and `record-design-option`. The proposal identifies the human reasoning, links the relevant findings and states what needs testing. A few disposable sketches remain in the design tool; the substantive option and insight remain in the project.

Priya and colleagues identify UN-101, understanding collection arrangements before travelling, from their analysis and explain its limited supporting circumstances. UN-102, an accessible supported borrowing route, remains Proposed where the relevant evidence is still missing. The AI records these human judgements; it does not derive needs from raw research or turn Ruth's promising idea into a requirement to send another notification.

**What works:** the framework has homes for both established knowledge and inventive possibilities. **Remaining friction:** people may hear “untested assumption” as a rebuke. The smallest improvement is supportive language: “worth exploring; here is what would help us learn,” followed by a small capture. The AI must preserve authorship and credit the insight, without presenting a confidence score as a verdict on the person's competence.

## 6. The deadline invites a misleading green status

At the discovery close, Ben runs the integrity skill. Several registers remain unused. Some source material remains unsynthesised, and no annual operating-cost baseline has been established. Sana asks whether the team is ready to move forward.

> **Ben:** “There are blank fields and unused files. I don't want to hand over an incomplete project.”
>
> **Dan:** “We need an answer about the next phase, not a perfect folder.”
>
> **Priya:** “The findings we've reviewed are available. We still have a gap around return responsibilities.”
>
> **Sana:** “Can we explore the borrowing promise without committing to build the app?”
>
> **AI:** “The records contain your proposed direction and these unresolved questions: implementation cost, research coverage and need fulfilment. I can assemble them for your decision.”

The integrity check distinguishes an unused optional record from a gap that affects a decision. Missing consent evidence for an actual session would be material; an untouched prototype register in discovery is not automatically a defect. The AI cannot declare all learning captured merely because required fields are nonblank.

Sana makes DEC-103: proceed to a bounded alpha to test the collection promise and support routes, with remaining questions explicit. RQ-102 retains the unresolved cancellation/return question; UN-103 remains a candidate. OUT-101 is accompanied by a proposed success measure whose baseline remains unestablished. The service owner's decision is not converted into proof of cost-effectiveness or readiness for beta.

The AI prepares a concise handover containing the reviewed learning, uncertainty, retained option and actual decision. It does not create a second project-status register. **What works:** evidence and decision status support a qualified choice. **Remaining friction:** the meaning of “Complete” for a research round can be gamed or interpreted differently. The protocol should distinguish administrative close-out, captured learning and open research questions in its existing close-out section, with the team deciding which gaps affect progression.

## Discovery findings about the framework

Severity describes plausible consequences, not measured incidence.

These issues were identified by the original simulation. The [0.3.1 guidance changes](README.md#guidance-changes-in-031) address the working instructions; real-team validation remains outstanding.

| ID | Severity | Type | Observation and smallest improvement | Needs real validation |
|---|---|---|---|---|
| D1 | High | Framework interpretation + authority | A funded brief can be misread as user evidence. Add a mixed-authority example to existing source guidance. | Can teams preserve the distinction when challenged by a sponsor? |
| D2 | High | AI behaviour + team communication | A polished summary can convert sarcasm or silence into agreement. Lead with unresolved choices and confirm consequential decisions in the normal meeting close. | Do people notice and correct misleading summaries before relying on them? |
| D3 | High | Research practice + reporting | Identified/planned groups can be mistaken for achieved coverage. Derive coverage explanations from current records without another register. | Can researchers and stakeholders understand the coverage limits quickly? |
| D4 | High | Completeness boundary | File checks cannot prove every substantive insight was captured. Add a human coverage acknowledgement and remaining synthesis gaps to the existing protocol close-out. | Does it retain learning without creating a burdensome sign-off ritual? |
| D5 | Medium | Language + professional autonomy | Correct classification can feel like the AI rejecting an idea. Preserve attribution and phrase uncertainty as a useful next question. | Do disciplines feel supported and remain willing to share unfinished ideas? |
| D6 | High | Governance + status semantics | Empty optional records and material decision gaps can receive equal attention. Report decision-relevant gaps first; clarify round close-out using the existing protocol. | Can the team make a responsible phase decision without chasing artificial completeness? |

## Handover into the alpha simulation

Within this fictional continuity, DEC-103 authorises exploration, not a production app. FND-101 supports UN-101 within a small, bounded research context; FND-102 preserves differing timing preferences. UG-101 and UG-102 are relevant, while broader coverage remains incomplete. ASM-102 and PROP-101 concern the possible gap between a reservation and a readiness promise. UN-102 and UN-103 remain candidates where evidence is insufficient. RQ-102, operational feasibility, cost and baseline measurement remain open. Alpha must test these propositions rather than inherit invented certainty.
