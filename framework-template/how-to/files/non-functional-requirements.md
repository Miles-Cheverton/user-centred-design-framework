# Non-functional requirements

**Working file (via document tracker)** [non-functional-requirements.xlsx](../../document-tracker.xlsx)

## First capture

Use an NFR ID and write a testable **Requirement** for a service quality such as accessibility, security, performance or reliability.

## Fields

| Field | What to enter |
|---|---|
| ID | Stable NFR ID. |
| Requirement | The criterion, where it applies and the threshold for passing the check. |
| Source | The applicable standard, obligation or decision. Give its exact version or section and cite any user needs that establish why the requirement matters. |
| Status | Proposed, Agreed, Superseded or Withdrawn. Check the source and agreement before relying on the requirement. Use Withdrawn when the authorised decision maker or source confirms that it is no longer applicable and has no replacement. |
| Verification | The result, exact version or scope checked, and supporting EV IDs from [Findings](../../document-tracker.xlsx). Use “Not yet checked” while pending. Register external reports as DOC sources where needed. |

Keep the test method with its delivery test or verification plan. When the service, build, applicable scope or standard changes materially, retain the earlier verification, date and version. In **Verification**, add a dated review note identifying which current version or scope remains unverified. Report the previous result for its recorded scope until the team has checked the current service. Mark replaced requirements Superseded. In the old **Requirement** cell, keep the criterion and list the replacement NFR IDs, or say that the replacement is unknown.

For a Withdrawn requirement, keep the ID, criterion and historical verification where permitted. In **Source**, record the date, reason and exact authority or DEC ID for its withdrawal. Check the continuing applicability of standards and obligations and flag related records for review. Record people's access and support needs in the [User needs workbook](../../document-tracker.xlsx).

**Example** `NFR-201` proposes showing readiness online within 60 seconds in at least 95% of tests.

[Defra guidance on non-functional requirements](https://digital.defra.gov.uk/business-analysis/non-functional-requirements)
