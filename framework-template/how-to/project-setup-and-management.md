# Project setup and management

Use these records to establish the project's purpose, boundaries and intended outcomes, and to maintain its decisions and delivery context. Open the relevant workbook or Markdown file through the [document tracker](../document-tracker.xlsx). Start with what you know. Complete the record as the information becomes useful and follow the [record conventions](../AI-skills/record-conventions.md) for IDs, links and workbook editing.

- [Problem statement](#problem-statement) · [Scope](#scope) · [Project people](#project-people) · [Outcomes and measures](#outcomes-and-measures)
- [Assumptions](#assumptions) · [Constraints](#constraints) · [Dependencies](#dependencies) · [Risks](#risks)
- [Decisions](#decisions) · [Glossary](#glossary)

## Problem statement

**Working file:** `problem-statement.md`

Write one sentence describing who experiences the problem, what is difficult and why it matters. Keep the statement on its own. If the commission names a solution, ask what problem it is meant to solve.

> Applicants cannot tell when their application is likely to be decided, making it difficult to arrange their next steps.

Check the wording with the team against [findings](research-and-evidence.md#findings-and-observations). Retain the original mandate in the [source register](research-and-evidence.md#source-register). For a material change, record the new wording in **Decision** and the earlier wording or version, mandate's DOC ID and passage, and supporting findings in **Why**. Update affected scope, outcomes and research records.

[GDS guidance on discovery](https://www.gov.uk/service-manual/agile-delivery/how-the-discovery-phase-works)

## Scope

**Workbook:** `scope.xlsx`

Use one SCP sequence and one row per item. Start with ID, Item and Scope.

| Field | What to enter |
|---|---|
| ID | Stable SCP ID, for example `SCP-001`. |
| Item | Service, activity, group or boundary. Make it clear what it includes. |
| Scope | In scope or Out of scope. Record the team's established boundary. |
| Why | Rationale and the DEC ID of a recorded decision, when available. |

When the boundary changes, update Scope and Why on the same row, keeping the ID. For material changes, record the previous classification and rationale in [Decisions](#decisions) and cite the DEC ID. Keep unresolved boundaries in a research question or proposed decision while the team agrees them.

## Project people

**Workbook:** `project-people.xlsx`

Capture ID, Name and Relationship to project. Use TM for team members or roles and STK for stakeholders.

| Field | What to enter |
|---|---|
| ID | Stable TM or STK ID matching the relationship. |
| Name | Person, team or Vacant for an unfilled role. |
| Relationship to project | Team member or Stakeholder. |
| Job title | Formal title or position, when known. |
| Email | Work address, where appropriate. |
| Why involved | Responsibility or interest, and organisation where useful. |

### Team members

Record the people and roles delivering the project. Update details as people join, leave or change roles. Record decision-makers and owners against the work itself.

### Stakeholders

Record people or teams with an interest in, influence over or responsibility for the service. Use the team name while an individual contact is unknown. Cite stakeholder input for its context or decisions. Base claims about user needs on [research evidence](research-and-evidence.md).

Give a person a second row only where they hold a distinct relationship. Keep each existing role's ID and avoid merging records solely on names. Keep research participant identities in approved restricted storage.

[GDS service team roles](https://www.gov.uk/service-manual/the-team/what-each-role-does-in-service-team) · [Mapping the user's whole problem](https://www.gov.uk/service-manual/design/map-a-users-whole-problem)

## Outcomes and measures

**Workbook:** `outcomes-and-measures.xlsx`

Use its two tabs. An outcome can have several measures.

### Outcomes

Enter an ID and Outcome, describing what should improve and who benefits.

| Field | What to enter |
|---|---|
| ID | Stable OUT ID. |
| Outcome | Intended change for users or the service. |
| User need IDs | Directly related UN IDs, where known. |

Example: “Fewer borrowers arrive before their equipment is ready.” If the intended outcome changes materially, record the earlier wording and reason in [Decisions](#decisions).

### Success measures

Give the measure a MET ID and name. Link the relevant outcome IDs and define the calculation before use.

| Field | What to enter |
|---|---|
| ID | Stable MET ID. |
| Measure | What you will track, such as the proportion of repair appointments successfully rescheduled. |
| Outcome IDs | The OUT IDs this measure helps assess. |
| Baseline | Starting value, period and supporting EV IDs. Use Not yet established if unknown. |
| Target | Desired value or direction, by when and why. |
| Source and method | Exact DOC or SES references with version and location, calculation, unit, population, period and exclusions. Add owner and review timing where useful. |
| Results | Link to the current result with date, filters or snapshot and relevant EV IDs. Put current information first; note interpretation and link the DEC ID for a material change. Retain earlier dated results where they matter. |

Check that baseline and results cover comparable populations, periods and methods before reporting improvement. Leave an unknown numeric result blank or record that it is not yet established; zero means an observed zero. When a cited measurement or finding becomes invalid, mark the gap in Baseline or Results and ask the team to reassess affected claims. Link any valid remaining evidence and distinguish the earlier reported result from the current verified result. Put DEC references in the fields affected by changes to the measure, target or interpretation.

[GDS guidance on setting performance metrics](https://www.gov.uk/service-manual/measuring-success/how-to-set-performance-metrics-for-your-service)

## Assumptions

**Workbook:** `assumptions.xlsx`

Create an ASM record for a belief the team relies on. Set it to Untested until the team assesses the evidence.

| Field | What to enter |
|---|---|
| ID | Stable ASM ID. |
| Assumption | A checkable belief, with the circumstances where it applies. |
| If wrong | What would change or fail. Complete before relying on the assumption. |
| Status | Untested, Supported, Contradicted, Inconclusive or Superseded. |
| Evidence | Exact EV or FND IDs after assessment, the team's judgement and limits. |
| Superseded by | Exact replacement ASM IDs when superseded. |

Plan checks in [research planning](research-and-evidence.md#research-planning) or delivery work. Keep contradicted beliefs and evidence. For replacements, use the [replacement rule](README.md#when-records-change).

### Test a hypothesis

Write the prediction in Assumption, identifying what change you expect to help, who it should help and why. Before testing, cite the ASM ID in the research round protocol or delivery test. Record the population and scope, comparison, expected supporting or challenging results and the exact MET ID for any [success measure](#success-measures) used.

Example: `ASM-202` predicts that a separate equipment-readiness message will reduce early arrivals. Compare the proportion arriving early with and without the message.

The team sets Status to Supported, Contradicted or Inconclusive after reviewing the results. In Evidence, cite EV or FND IDs, test version or bounded scope and relevant RND, RQ or MET IDs. Record limits. If support is later invalidated, record the gap and keep the status until the team reassesses it.

[GDS guidance on developing hypotheses](https://www.gov.uk/service-manual/measuring-success/how-to-set-performance-metrics-for-your-service#develop-hypotheses-based-on-your-benefits)

## Constraints

**Workbook:** `constraints.xlsx`

| Field | What to enter |
|---|---|
| ID | Stable CON ID. |
| Constraint | Practical limit, what it affects and, if known, who could approve a change or what needs to happen. |
| Source | Exact policy, agreement or decision and section. Cite DOC or DEC IDs when recorded and any uncertainty about applicability. |
| Flexibility | Fixed if the project cannot change it, Flexible if there is a route to change it, Unknown while checking, or No longer applies if removed. |

Confirm source and flexibility before reliance. For removal or renegotiation, put the current limit or applicability first in **Constraint**, preserve the earlier limit and source in a dated note or version history, and cite the decision in **Source**. Set No longer applies only when removal is confirmed, for example “No longer applies; removed on 2026-11-20 by DEC-204”. Review affected records with the team.

Example: The team must use an approved identity service. An alternative needs architecture approval, so flexibility is Flexible.

## Dependencies

**Workbook:** `dependencies.xlsx`

| Field | What to enter |
|---|---|
| ID | Stable DEP ID. |
| Dependency | What is needed, who or what should provide it, and the work it affects (record IDs or qualified external work reference where known). |
| Needed by | Date or milestone, if known. |
| Owner | Person or role who confirms the agreement and follows it through. |
| Status | Unconfirmed, Agreed, In progress, Available, Blocked or No longer needed. Use Available when delivery or access is confirmed. |

Check owner and status before relying on the dependency. For example, the technical lead may own a dependency for another team to provide a test environment and be waiting for confirmation.

[GDS agile governance](https://www.gov.uk/service-manual/agile-delivery/governance-principles-for-agile-service-delivery)

## Risks

**Workbook:** `risks.xlsx`

Describe the cause, what might happen and its effect. For example, recruiting only online may leave phone-related barriers undiscovered.

| Field | What to enter |
|---|---|
| ID | Stable RSK ID. |
| Risk | Uncertain event and its effect on the project or service. |
| Current likelihood | Not assessed, Low, Medium or High under the team's criteria and timeframe. |
| Current impact | Not assessed, Low, Medium or High under the same criteria. |
| Response | **In place** for existing controls and **Next** for planned action and timing. |
| Owner | Person or role accountable for the risk and response. |
| Review date | Next substantive review, when known. |
| Status | Open, Accepted, Occurred or Closed. |

Rate risks using controls already in place and checked. Use Not assessed until ratings are agreed. Review after new evidence or control changes, including accepted risks. If an event occurs, set Occurred, record what happened in Response and link the issue or action being followed up.

[HM Treasury Orange Book](https://www.gov.uk/government/publications/orange-book/the-orange-book-management-of-risk-principles-and-concepts)

## Decisions

**Workbook:** `decisions.xlsx`

Create a DEC record when the team faces a significant choice. Start Proposed while it is open.

| Field | What to enter |
|---|---|
| ID | Stable DEC ID. |
| Decision | What the team proposes or chooses. |
| Status | Proposed, Agreed, Superseded or Withdrawn. Use Agreed when choice, date and accountable decision-maker are confirmed. |
| Date | When the choice was made. |
| Decided by | Person or accountable role that made it. |
| Why | Reasons, material alternatives, accepted objections or limits and supporting IDs. Cite the exact UN IDs served when known, and version and passage for DOC citations. |
| Superseded by | Exact replacement DEC IDs, separated by a semicolon and space. A blank for a superseded decision is a gap. |

### Retain an option before a decision

Keep a recognisable version of an idea or proposal in the design workspace if it needs to be found again. Retain its existing proposal ID, such as `PROP-201`, and [register it as a source](research-and-evidence.md#source-register) when it needs a DOC citation.

When a specific choice goes to the team, record it as Proposed and cite that version or DOC ID in Why. If a material alternative is set aside, record why and who made the choice. Mark a separate proposal Withdrawn if the team withdraws it. To find it later, search for its name or earlier ID and follow the Why references. Use Agreed once the team confirms the choice, date and accountable decision-maker.

### Apply the decision

- Update affected current records and cite the DEC ID. Preserve earlier decisions and their reasons. If a choice alters only part of an earlier decision on the same scope, the new record states the complete current position, including what continues and what changes. Mark the earlier decision Superseded by the new one. Keep historical citations. Record distinct choices separately; open conditions can stay on the relevant row.
- If evidence behind an agreed choice is withdrawn, record the gap in Why and keep its status until the team reviews it.
- For a change in framing, use Decision for the new framing and Why for the mandate, previous wording or version and reason. Update the [problem statement](#problem-statement).
- For a deferred or unaddressed need, cite its UN ID and why. Update the need's [Delivery decision](design-and-development.md#user-needs) and cite the DEC ID in Scope and evidence.

[Worked decision example](worked-examples.md#follow-the-finding-forward-to-a-decision-and-an-outcome-check) · [GDS agile governance](https://www.gov.uk/service-manual/agile-delivery/governance-principles-for-agile-service-delivery) · [Michael Nygard's approach to decision records](https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions)

## Glossary

**Workbook:** `glossary.xlsx`

Use a stable TERM ID, a preferred **Term** and a clear **Definition** of its meaning within the project. Include alternative names or abbreviations people might search for. Retain the ID when improving wording. If the meaning changes, explain what changed and update affected records.

[ONS guidance on plain language](https://service-manual.ons.gov.uk/content/writing-for-users/plain-language)
