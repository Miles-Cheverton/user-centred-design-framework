# Decisions

**Working file:** [decisions.md](../../decisions.md)

Record significant choices that someone may later need to understand or revisit. Routine conversation and every minor edit do not need a decision record.


## First capture

Save a stable DEC ID and the actual or proposed choice. Keep an unsettled choice Proposed. Before treating it as Agreed, record the decision maker, date, reasons and consequences; the first capture is not approval.

## Complete a decision

1. Describe the question and the actual choice.
2. Identify who decided and when.
3. Explain the reasons at a level a future reader can understand.
4. Link the evidence and affected records.
5. Mark Agreed only when there is an actual agreement within the person's authority.

## Fictional example

**DEC-001 — Include post-submission progress in discovery**

The fictional commissioning team agrees to investigate progress information because UN-001 describes difficulty planning while waiting. Changing eligibility policy remains excluded. This changes the scope of investigation; it does not approve a particular interface.

## Fields and sections

Use the small first capture to save a draft. Complete the relevant fields before relying on it; an unfinished record does not establish evidence, agreement or verification.

| Field or section | Needed when | What belongs here |
|---|---|---|
| Decision ID and title | At capture | Stable DEC ID and concise description. |
| Status | At capture; update when agreement changes | Proposed, Agreed, Superseded or Withdrawn. |
| Superseded by | When replacements exist | Exact replacement DEC IDs separated by semicolons; blank on a Superseded decision is a gap. |
| Decision date | Before Agreed | When the choice was actually made; identify an unresolved date rather than inventing one. |
| Decision maker | Before Agreed | Person or accountable role making the choice. |
| Related records | When material records are affected or considered | Exact IDs; include Version for JNY or PRT. |
| Context | Before relying on the decision | Question or circumstances requiring a choice. |
| Choice | At capture | What was chosen or proposed; preserve the distinction. |
| Rationale and alternatives | Before relying on the decision | Reasons, supporting EV/FND/DOC references, material alternatives and trade-offs. DOC citations need exact versions and passages. |
| Consequences | Before relying on the decision | What changes, including accepted limitations or risks. |
| Revisit or replacement | When a meaningful trigger or replacement exists | The event that warrants reconsideration; replacement IDs go in Superseded by. |

## Keep it current

Record a consequential choice when made; update affected owners when their meaning changes. Retain the original decision when superseded or withdrawn. Add replacement decisions with new IDs and list them in Superseded by on the old record. No self-links or cycles. Do not rewrite history to make a past choice look as though it was always the current one.

## Completion check

A future colleague can understand what was chosen, by whom, why, and what it affected.

## Practice basis

[GDS: agile governance](https://www.gov.uk/service-manual/agile-delivery/governance-principles-for-agile-service-delivery) and [Michael Nygard's original decision-record approach](https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions). This template adapts the latter beyond technical architecture. Guidance reviewed: 16 November 2026.
