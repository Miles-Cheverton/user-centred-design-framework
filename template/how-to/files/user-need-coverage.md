# User need coverage

**Working file:** [user-need-coverage.xlsx](../../user-need-coverage.xlsx)

Record whether each user need is met within a specific version or service scope, separately from what the team has decided to address. user-needs.xlsx owns the need and whether it is evidenced; this workbook owns its current fulfilment assessment. Do not copy the need's wording.

People make the fulfilment judgement using evidence and the whole service context. AI may retrieve the team's assessment, check its references, calculate recorded totals and populate the row; it must not decide that a need is met or infer that judgement from a passing component test.

## First capture

Enter **User need ID** and **Assessment**. Use an existing UN ID and start at Not assessed until evidence supports another value. Keep one current row per active need. Do not prefill unused rows. This capture does not establish fulfilment or a delivery decision.

## Complete a record

1. Read the exact UN record in user-needs.xlsx. Check that there is not already a current coverage row for it.
2. Define the exact version or bounded service scope being assessed. A prototype result does not establish live-service fulfilment.
3. For Not met, Partly met or Met in full, record supporting EV IDs, the actual assessment date and Assessed version or scope. Follow each EV to its source. Evidence that the need exists is not evidence that it is met.
4. Record the Remaining gap for Not met or Partly met. Keep unmet needs visible, including those the team cannot or chooses not to address.
5. Set Delivery decision independently. Deferred and Will not address require an exact DEC ID whose record explains the reason and consequences. Will address is a delivery choice, not a fulfilment claim.
6. Before reporting whole-project coverage, reconcile active UN records to exactly one current row each. Resolve missing, duplicate, unknown or superseded references; do not turn a missing row into an assumed Not assessed value.

## Fictional example

This example is a first capture only, not project evidence. The blank fields have not been assessed or recorded.

| Field | Example |
|---|---|
| User need ID | UN-001 |
| Assessment | Not assessed |
| Evidence IDs |  |
| Remaining gap |  |
| Delivery decision | Not decided |
| Decision ID |  |
| Assessed version or scope |  |
| Assessed on |  |

The need can be Evidenced in user-needs.xlsx while its coverage remains Not assessed here. If later evidence shows it is only partly met, record that scoped assessment and gap even if the delivery decision is Deferred.

**Whole-service example:** a keyboard interaction passes its defined test, but the telephone support route fails during staffed hours. After discussing both results, the team assesses the supported-borrowing need as Partly met for that service scope. AI records that judgement, the evidence and the remaining gap. The component's successful verification does not automatically meet the user need. If the team has not assessed the combined experience, AI retains Not assessed and identifies the question for them.

## Fields

**At capture** saves the first row. **Before use** means before relying on it as the current project position. The explicit assessment and decision conditions always apply; do not invent missing evidence, dates or choices.

| Field | Needed when | What to enter |
|---|---|---|
| User need ID | At capture | Exactly one existing UN ID from user-needs.xlsx. This is the row key: keep one current coverage row per user need, with no additional synthetic ID and no copied need wording. Reconcile active UN records separately; a missing row is not Not assessed. |
| Assessment | At capture | How fully the need is met within the assessed version or scope. Start a newly created coverage row as Not assessed until evidence supports an assessed claim. Do not prefill unused rows or infer this value from a delivery choice. Choices: `Not assessed`, `Not met`, `Partly met`, `Met in full`. |
| Evidence IDs | Assessment is Not met, Partly met or Met in full | Zero or more EV IDs supporting this fulfilment assessment, separated by semicolon plus space. At least one is required for Not met, Partly met or Met in full. Evidence that a need exists does not itself show it has been met. Retain historical EV records when updating the current row. |
| Remaining gap | Assessment is Not met or Partly met | What remains unmet within the assessed scope. Required for Not met or Partly met; be specific about the unsupported task, circumstance or user group. Do not infer a delivery decision from this gap. |
| Delivery decision | Before use | The current decision about addressing this need, independently of the assessment. A gap is not a decision; choose Not decided when no decision has been made, and retain the underlying decision history. Choices: `Not decided`, `Will address`, `Deferred`, `Will not address`. |
| Decision ID | Delivery decision is Deferred or Will not address | Zero or one DEC ID recording the delivery choice. Required for Deferred or Will not address; record it for Will address when available. Retain the historical DEC record when the current choice changes; do not put decision prose here. |
| Assessed version or scope | Assessment is Not met, Partly met or Met in full | One precise version or bounded service scope to which the assessment applies, for example PRT-001 v1 or a dated live-service scope. Required for assessed claims. Never use current or latest alone; a prototype result does not establish live-service fulfilment. |
| Assessed on | Assessment is Not met, Partly met or Met in full | The date this current assessment was reached, in YYYY-MM-DD form. Required for Not met, Partly met or Met in full. Do not invent a date or reuse an older assessment date for a newly assessed version. |

## Read the summary

The Summary sheet counts recorded rows with nonblank User need IDs. It shows the Assessment and Delivery decision dimensions independently over the same rows. Do not add those counts together or turn them into a completion percentage.

Not assessed counts existing rows marked Not assessed; it does not count needs missing from the workbook. Duplicate or invalid IDs can distort the counts. The summary is therefore not proof of project completeness. Reconcile the active needs and current rows before making that claim. Read the actual Records table and relevant full rows to check evidence and scope; summary totals alone cannot establish that an assessment is valid.

A useful readout is: “Four active needs; three assessment rows and one missing. Of the recorded rows, one is met, one partly met and one not assessed. The team has declined one item of work; that choice does not count as fulfilment.” Include affected groups and consequential choices from their owning records. Do not narrow the population to hide unmet or declined needs.

## Keep it current

Update the current row when a new assessment is reached for a stated version or scope, or when the delivery choice actually changes. Preserve the old basis in the original EV and DEC records; do not overwrite those sources to match today's conclusion. Do not add competing current rows, duplicate need wording or synthetic coverage IDs.

If the need is superseded, follow its explicit replacements and reconcile the current coverage rows to the active needs. Retain relevant historical evidence and decision meaning in their owners. Use existing research and decision events; this workbook does not create a new review ceremony.

## Completion check

The need exists, its current row is unique, and an assessed claim has exact evidence, scope and date. Assessment and Delivery decision remain independent. Deferred or Will not address has a decision explaining the reason and consequences. Any project-wide summary states the reconciliation and coverage limits.

Use [record conventions](../record-conventions.md) for IDs and exact relationships. [Allowed values](../allowed-values.xlsx) defines the dropdowns; the workbook already contains them.

## Practice basis

[GDS: start by learning user needs](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs). The coverage record, field names and assessment choices are this framework's implementation choices, not a prescribed GDS spreadsheet.
