# Use cases

**Working file:** [use-cases.md](../../use-cases.md)

A use case describes how a person achieves a goal through a specific service interaction. Use one when it helps the team understand behaviour, alternatives or handoffs. A user need states the goal and purpose; a journey describes a wider experience across stages. This framework does not treat use cases as a compulsory GDS deliverable.

## First capture

Save a UC ID, the goal and whether the case describes a current or proposed experience. A short Draft can capture the interaction before every branch is understood.

## Complete a case

1. Identify the actor or group, goal and trigger.
2. Link established user groups and needs; expose missing understanding rather than inventing IDs.
3. Describe the main user/service steps in plain language.
4. Add the alternatives or failures that change what the team needs to design, test or support.
5. Record the intended outcome, supporting evidence and unresolved behaviour. Use Reviewed only after an actual review.

## Fictional example

This example is guidance only, not project evidence.

**UC-001 — Choose an equipment collection time**  
**Status:** Draft  
**Represents:** Proposed experience  
**User group IDs:** UG-001  
**User need IDs:** UN-002

The borrower has an equipment request ready for collection. They open the collection arrangements, review available timing options, choose one and receive confirmation. If no option works, they can request help through an alternative channel. How staff handle that request is unresolved. The intended outcome is that the borrower understands and can follow their collection arrangements; the proposal has not yet demonstrated that outcome.

## Fields and sections

| Field or section | Needed when | What belongs here |
|---|---|---|
| UC ID and title | At capture | Stable UC ID and the user’s goal. |
| Status | At capture; update on review or replacement | Draft, Reviewed or Superseded. |
| Represents | At capture | Current experience or Proposed experience. A proposal is not an observation. |
| User group IDs | Before relying on the case | Exact UG IDs for the people involved. |
| User need IDs | When related needs are established | Exact UN IDs; keep the need’s maintained wording in its register. |
| Supporting record IDs | When evidence exists; before asserting observed behaviour | EV or FND IDs, preserving source limitations. A reviewed proposal need not pretend to be evidenced behaviour. |
| Superseded by | When replacements exist | Exact UC IDs separated by semicolons; a superseded record with no known replacement remains a gap. No self-links or cycles. |
| Trigger and preconditions | Before relying on the case | Starting event and relevant conditions; identify assumptions. |
| Main interaction | First capture may be brief; develop before review | Meaningful user and service steps across applicable channels. |
| Alternatives, failures and recovery | Before review where they affect the interaction | Important branches and explicit unresolved behaviour. |
| Intended outcome | Before relying on the case | What the person should achieve; do not claim it is achieved without evidence. |

## Keep it current

Refine the same UC when the goal and scope remain the same. Retain meaningful superseded cases with explicit replacements. Do not duplicate the journey graphic, prototype status or complete policy rules here; use their owning records where those concepts are needed.

## Completion check

A colleague can understand the actor, goal, trigger, main steps, meaningful alternatives and intended outcome, and can tell which behaviour is current, proposed or unresolved.

Use [record conventions](../record-conventions.md) for IDs and relationships. This file format is the framework’s design choice, not a prescribed GDS document.
