---
name: check-evidence-and-records
description: Use when explicitly asked to verify a claim, assessment or standard, check structural integrity, create or refresh a project health report, repair records or help upgrade the framework; also refresh an existing health report after verified record updates.
---

# Check evidence and records

For project work, open the specified project’s `_project-config.md` first. Resolve its **Working folder** using the [project boundary rules](../ai-guidance.md#confirm-the-project-boundary). Use only that confirmed folder and specifically authorised external sources; never search other projects by filename or ID. If the folder is unclear, ask for its exact path or URL; a task limited to supplied files may continue within that set. Resolve links from the canonical project path `AI-skills/check-evidence-and-records/SKILL.md`, not the installed or copied skill location. Read the project’s `AI-skills/ai-guidance.md` [shared principles](../ai-guidance.md#shared-principles) and the applicable sections of `AI-skills/record-conventions.md` and record guides. If essential shared guidance is unavailable, say so; draft affected changes instead of saving. Continue independent, permitted work, including tasks limited to supplied files.

People establish findings, needs, fulfilment and decisions. Never invent records, IDs, sources or agreement. Respect access, consent and authorisation; cite exact sources and limits. Save only authorised changes, and report Saved and verified, Not saved or Save unverified. Follow [project health after record changes](../ai-guidance.md#refresh-an-existing-project-health-report) when saving project records; read-only work does not refresh it.

## Copy-and-paste example

> Use AI-skills/check-evidence-and-records/SKILL.md. Check this project's records for duplicate or missing IDs, gaps in evidence and requirements without a valid test result. Report exact locations and what needs attention.

## Choose the check

Identify the claim, decision or project area and [confirm the scope](../ai-guidance.md#start-with-the-task). Choose the appropriate checks:

| Check | Method |
|---|---|
| Claim, proposal or decision | [Ground claims](../ai-guidance.md#ground-claims); check source, scope and exact versions. |
| Professional practice or standard | [Check applicable guidance](../ai-guidance.md#check-which-guidance-applies) and compare to project evidence. Reserve formal sign-off for responsible people. |
| User need assessment or requirement verification | [Assess whether needs are met](../ai-guidance.md#assess-whether-needs-are-met). Distinguish recorded totals, agreement, fulfilment, delivered scope and test evidence; identify changed or untested scope. |
| Withdrawn or invalid evidence | [Trace withdrawn evidence](../record-conventions.md#trace-withdrawn-evidence), including dependent claims and Answered questions. |
| Quick structure check | Inspect actual owners, all rows, IDs/duplicates, required fields, classifications/controlled values and dropdown/table controls, wrong sheets, orphan/outside-table rows, replacement gaps/cycles, dangling record IDs, links and independently counted recorded totals including excluded rows. Do not open raw sources or infer current evidence/fulfilment. |
| Project health report | [Create or refresh project-health.xlsx](#create-or-refresh-a-project-health-report) on request, or refresh an existing report after verified record updates. Default to a quick structure check; use a full evidence check for the report if requested. |
| Full project integrity | [Check and repair project records](../record-conventions.md#check-and-repair-project-records). Inspect actual owner/schema, all populated rows, duplicates, orphan/malformed IDs, invalid classifications and status values, misplaced records, links, required fields, controls, source and version gaps. Do not depend on workbook diagnostic formulas. |

For a project-wide check, scan all current owners and relevant record guides, including both sheets of multi-sheet registers and rows outside named tables. Put duplicate alerts near the top with every confirmed location. Report a quick check as structure only, with excluded rows/reasons and possible outdated current bases needing evidence review; a full check follows actual sources and material current dependencies, distinguishing historical references. Inspect needed sources within scope or report access gaps.

Repair only agreed, established errors with authorisation; verify using [save and report](../ai-guidance.md#save-and-report). Leave new interpretations, decisions and fulfilment judgements to people.

## Create or refresh a project health report

Create the optional `project-health.xlsx` only when asked. Refresh it on request or [after verified project record changes](../ai-guidance.md#refresh-an-existing-project-health-report) when a genuine report already exists. Use the confirmed Working folder or explicitly mapped, approved report location; respect an Unused or unresolved mapping. An explicit report request authorises generating the report, not editing the source records. It is a **dated, derived snapshot, not a source of truth**; do not require the team to maintain it by hand.

Run a quick structure check across the [current owners and records](../record-conventions.md#check-and-repair-project-records) for automatic or ordinary refresh, or a full check if requested for the report. Re-read actual records on every refresh, including additional relevant records mapped by the team, rather than copying previous report counts. Exclude the generated report itself (even if listed in the tracker), templates and fictional material. Use only authorised sources. Create two clearly named sheets:

### Project overview

Label the overview “Project health — generated report”. Show the confirmed project name and exact working folder path/URL, check date and time (with time zone), check mode, project stage if known, checked scope and access limitations. Label statistics as recorded unless the underlying evidence was checked. Use two tables:

- **Record coverage** — Record or sheet; Actual location; Population; Recorded rows; Notes. List each canonical record owner, including each relevant sheet of combined workbooks and the problem statement; include adopted/mapped owners when relevant. Use **Populated** (real entries, no missing required information found in the checked scope), **Partially populated** (real entries but missing information needed for the stage/status/claim, or entries only outside the table), **Empty** (accessible, no real records), **Intentionally unused** (documented, for example in the tracker), or **Inaccessible** (missing, unavailable or not fully inspectable). Optional blanks are not defects. Count actual populated table rows, including incomplete rows; exclude starter examples, and report populated outside-table rows or duplicates separately in Notes and issues. Counts are rows, not necessarily unique valid IDs. A filled Markdown record can be marked Populated without a row count. Use Unknown, not zero, if a total cannot be verified; label any known partial count and its scope.
- **Project statistics** — Metric; Recorded value; Actual source (owner/sheet); Scope or limits. Include useful metrics where records support them.

| Area | Useful recorded statistics |
|---|---|
| User needs | Need Status (including blank/invalid values separately), the [four fulfilment totals](../ai-guidance.md#assess-whether-needs-are-met) and Delivery decision separately; report excluded/invalid rows and distinguish recorded from verified fulfilment. |
| Research | Rounds and sessions; planned groups versus actual **User groups represented** in sessions for the relevant rounds; outstanding research questions by status. Unknown coverage stays unknown; do not infer it from the participant register. |
| Requirements | Agreed functional and non-functional requirements by valid ID/Type pairing; report invalid classifications separately. Missing or explicitly outstanding Verification; distinguish a recorded result from actual test evidence. |
| Assumptions, dependencies, risks and decisions | Untested assumptions, outstanding or blocked dependencies, open risks and proposed decisions; flag stage-relevant review needs without inventing decisions, risk judgements or due dates. |

Use additional existing records only if useful to the team's question. Report zero only when you checked the complete relevant accessible set. Do not calculate an overall quality or completion score, assume all records are required, or include unnecessary personal or restricted evidence.

### Issues and gaps

Use **Priority**, **Record ID**, **Location**, **Issue**, **Recommended action**. Record confirmed structural problems and useful stage-relevant gaps with exact source locations (workbook, sheet, row and field when available). Use High for issues that may mislead a current claim or action, Medium for meaningful missing or incomplete information, and Low for minor tidy-up; these are suggested priorities, not formal risk ratings. Distinguish invalid records from optional work and possible evidence gaps from verified defects. Do not invent IDs or conclusions. If no issue is confirmed, state that and the checked scope. Use the team's existing records for decisions or actions it chooses to take; do not turn this report into an action register.

Before refreshing an existing file, confirm it is the generated report for this project, not an unrelated workbook. Replace its current snapshot and issues rather than append or retain stale counts. Preserve underlying project records; do not silently overwrite a custom or unrelated report. If the report cannot be safely saved, identify the target and report Not saved; for an explicit report request, return the equivalent tables ready to paste. If saved, reopen and verify both sheets, current totals, scope and location. In chat, give the report link/path, checked scope, key issues and save result for an explicit request; for an automatic refresh, briefly report the refresh result separately from the record saves.

## Help with a framework upgrade

Follow [upgrade steps](../../how-to/README.md#upgrade-an-existing-project) and release notes. Identify the working copy and target starter; make a recoverable copy and stage any ZIP outside the live project. Never extract or bulk-copy a starter over live records. Use the [framework/project file distinction](../../how-to/README.md#upgrade-an-existing-project). Refresh guidance and templates, merging local changes; preserve project-owned files and links. Preserve team files, IDs, data, controls and local equivalents. Only migrate records when necessary and authorised; confirm their current owner in the tracker before retiring a copy.

Afterwards check actual fields, controls and links, trace a representative record or run the [quick test](../README.md#quick-test), and [refresh installed skills](../README.md#refresh-skills-after-an-upgrade). Report any incompatibility. Update the Starter version in the project README once the upgrade is complete. A version label alone never blocks work on compatible records.

## Report the result

Lead with the issue and effect. Cite actual workbook, sheet, row, ID and field where available. State coverage limits, verified repairs and unresolved gaps; identify checks that would resolve them. Keep the report proportionate to the requested scope.
