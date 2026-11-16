# Versioning and decisions

Keep the current position clear while retaining the history needed to understand research and consequential choices.

## Records and working edits

Update at the event: capture learning after research, record a consequential choice when made, and amend a record when its meaning changes. Use existing team conversations; this guide does not add a review ritual.

Use the working storage's version history for routine edits. Record substantive observation, assessment and decision dates in the fields that need them; a file's last-edited date is not evidence of a substantive review.

Keep a record's ID when it still identifies the same thing. Create a new record when its identity or meaning changes materially, and link the replacement. Never recycle an ID.

Use the explicit Superseded by field wherever the record supports supersession. List every exact replacement of the same type, separated by `; `; a record may split into several successors. The field is required when a replacement exists. Superseded with a blank replacement is an unresolved gap, not permission to guess. No self-links or cycles. See [canonical relationships](record-conventions.md#canonical-relationships).

Scope items keep their IDs when moved between in-scope.xlsx and out-of-scope.xlsx. Each item appears in only one current list. The decision explains the move.

## Meaningful design versions

Use a journey or prototype ID for a distinct concept. Competing alternatives receive different IDs. Revisions of the same concept keep the ID.

Register and retain a named journey or prototype version when it is used in research, informs a significant decision, receives substantive shared review or is handed over:

```text
journeys/JNY-001/v1/map.svg
journeys/JNY-001/v1/description.md
prototypes/PRT-001/v1/README.md
prototypes/PRT-001/v1/source/
```

Update the corresponding register with the exact version and paths. ID plus Version identifies the row; always cite both, such as `JNY-001 v1` or `PRT-001 v2`. Superseded by also uses both parts. A higher number does not establish selection or implementation. A journey's text equivalent and graphic must describe the same version. A prototype README records what can be explored, how to run or inspect it and what is simulated.

Disposable sketches can stay in normal design tools without an inventory entry. Capture all substantive learning even when an idea is discarded; retain enough meaning and source context to understand it. Raw artefacts may remain in approved tools with registered exact locations and accessible text.

Routine edits do not require copying every file into a new version folder. Once a version is cited by research or a decision, preserve its meaning. Record corrections explicitly.

## Current, selected and historical are different

- A current-experience journey describes an existing service and needs supporting observation.
- A proposed-experience journey describes an idea.
- Selected identifies a chosen direction; it does not establish implementation.
- Tested identifies an evaluated version; it does not establish that all quality criteria are met.
- Discarded and superseded options remain historical references where their retention is useful and permitted.

Keep the decision or reason for discarding a worthwhile option. This helps avoid repeating the same investigation without understanding what was learned.

## Decision records

Record significant choices with who decided, when, the reasons, alternatives and consequences. When a decision is replaced, retain it as Superseded and put all exact replacement DEC IDs in Superseded by. Findings and proposals use their own equivalent fields. Do not rewrite a past agreement to resemble today's choice.

## Research files

Recording parts use p01, p02 and so on. Transcript revisions use v01, v02. Current transcript link identifies one file and Transcript status applies only to that file. Correcting a transcript updates those two fields together. Older EV records preserve their exact Source ID, Source version or path and Locator; they do not automatically redirect to the current transcript.

Historical retention remains subject to consent, privacy and the organisation's retention arrangements. A version-control system is not a reason to retain restricted data after it should be removed.

## Template releases and project records

The public repository versions the reusable starter. The project's working records describe an actual service. Updating the starter does not automatically replace an existing project's records.

Framework administration, guide examples and the synthetic framework/ai-usability/ fixture are not service evidence. They may be used intentionally for framework evaluation without entering the live project evidence chain.

When adopting a new template release, read the change log and apply only the relevant structural changes while preserving IDs, evidence and decisions. Document a meaningful local schema change in the project README or decision record.

## Practice basis

- [GDS: making prototypes](https://www.gov.uk/service-manual/design/making-prototypes)
- [GDS: experience maps](https://www.gov.uk/service-manual/user-research/creating-an-experience-map)
- [GDS: research-data management](https://www.gov.uk/service-manual/user-research/managing-user-research-data-participant-privacy)
- [Decision-record approach](https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions)

The IDs, folders and version labels are this framework's implementation choices. Guidance reviewed: 16 November 2026.
