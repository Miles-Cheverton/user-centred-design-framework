# Prepare for refinement

## Supply

- **Work item or proposal:** [ID and link, or the text to discuss]
- **Refinement question:** [What the team needs to understand or decide]
- **Relevant version or scope:** [Journey, prototype, user group or service area]

## Prompt

Read README.md, ai-guidance.md and the canonical relationship reference in how-to/record-conventions.md, then the relevant file guides. Prepare a short evidence-backed contribution to the supplied refinement discussion. Read only the records needed for that task.

Assemble established human findings, decisions and open questions. The team performs analysis and determines implications, priorities and criteria; do not derive these from raw research. Flag a source discrepancy for discussion without resolving it through a new AI interpretation.

Locate the related user needs and groups, findings and evidence, relevant decisions, constraints, business rules and non-functional requirements. Inspect the exact journey or prototype version if it is relevant and accessible.

Resolve those relationships using exact allowed ID types and fields; do not join records because their wording is similar. Preserve ID plus Version for journeys and prototypes and follow explicit Superseded by references. For workbooks, read the actual sheet/table, headers and relevant full rows, preserving status and source paths. State partial coverage.

Trace important needs and claims through supporting records to Source ID, Source version or path and Locator in evidence.xlsx. Report inaccessible underlying material distinctly from missing evidence. Keep an NFR's Record status separate from its Verification status; verification results need Evidence IDs. Use the live project’s records as evidence.

Find reverse relationships by querying their owning fields: findings hold Research question IDs, Round or session IDs and Design versions; prototypes hold Proposal IDs. For a round, include findings linked directly to its RND ID or through its SES records. Do not maintain duplicate backlinks. Include substantive contradictory and inconclusive findings, not only support for a preferred answer.

If the question concerns whether needs are met, distinguish user-needs.xlsx evidential Status from user-need-coverage.xlsx Assessment and Delivery decision. Validate assessed claims against EV support, date and exact version/scope. Reconcile each active UN to one current coverage row before claiming project-wide coverage; Summary counts are recorded-row counts across independent dimensions, not completeness or a percentage.

Return:

1. **Purpose:** the user need and intended outcome this work addresses, with references.
2. **Established facts:** the important evidence, decisions and rules that shape the work.
3. **Open questions:** unresolved assumptions, conflicting evidence or missing information that affects the discussion.
4. **Documentation of refinement input:** when requested, express the team's supplied intent or agreed criteria clearly, preserving their meaning and linking the basis. Leave missing choices as questions for the team; do not invent criteria or research implications.

Keep broad user needs separate from the delivery story. Do not invent estimates, priorities, research findings, compliance claims or approval. Do not treat a prototype’s simulated behaviour as a production requirement.

If material records are inaccessible, state the coverage limit and avoid conclusions that depend on them. Keep the result brief enough to use in the meeting.

## Human check

The team checks the evidence and agrees the scope and criteria in its authoritative delivery records. AI drafting does not approve the work item or change a project decision.
