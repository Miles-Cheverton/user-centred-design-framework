# Non-functional requirements

**Working file** [non-functional-requirements.xlsx](../../non-functional-requirements.xlsx)

## First capture

Use an NFR ID and write a testable **Requirement** for a service quality such as accessibility, security, performance or reliability.

## Fields

| Field | What to enter |
|---|---|
| ID | Stable NFR ID. |
| Requirement | The criterion, where it applies and the threshold for passing the check. |
| Source | The applicable standard, obligation or decision. Give its exact version or section and cite any user needs that establish why the requirement matters. |
| Status | Proposed, Agreed or Superseded. Check the source and agreement before relying on the requirement. |
| Verification | The result, exact version or scope checked, and supporting EV IDs from [Findings](../../findings-and-observations.xlsx). Use “Not yet checked” while pending. Register external reports as DOC sources where needed. |

Keep the test method with its delivery test or verification plan. Reassess when the service or standard changes and mark replaced requirements Superseded. In the old **Requirement** cell, keep the criterion and list the replacement NFR IDs, or say that the replacement is unknown. Record people's access and support needs in the [User needs workbook](../../user-needs.xlsx).

**Example** `NFR-201` proposes showing readiness online within 60 seconds in at least 95% of tests.

[Defra guidance on non-functional requirements](https://digital.defra.gov.uk/business-analysis/non-functional-requirements)
