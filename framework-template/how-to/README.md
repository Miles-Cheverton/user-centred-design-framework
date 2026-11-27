# How to use the project foundations

Use the [document tracker](../document-tracker.xlsx) to find the current record. People think first. AI helps second.

## Frame the work

1. Check [project config](../_project-config.md) for the working folder, standards and local conventions. For AI use, provide the config and exact project folder path or URL, particularly when working in SharePoint.
2. Write the [problem statement](project-setup-and-management.md#problem-statement). Record the agreed [scope](project-setup-and-management.md#scope) and intended [outcomes](project-setup-and-management.md#outcomes).
3. Capture the [user groups](design-and-development.md#user-groups), [needs](design-and-development.md#user-needs) and [project people](project-setup-and-management.md#project-people) relevant to the work. Record unknowns as [assumptions](project-setup-and-management.md#assumptions) or [research questions](research-and-evidence.md#research-questions).
4. [Register the sources](research-and-evidence.md#source-register) the team relies on. Agree where records live. If work is already under way, keep your existing materials and use [Import an existing project](../AI-skills/import-existing-project/SKILL.md) if helpful.

Use only the records you need. Record significant learning and choices during the team's normal work.

## Enter records

Start a record in the first blank row inside the Excel table. Choose a unique ID using the example in the ID header comment or the instruction above the table. Enter what you know, use the dropdown choices and complete required fields before relying on the record. Extend the table as needed. Complete Markdown prompts only when relevant. If an assistant cannot save a change, ask for the target workbook and tab, record ID and field values ready to paste under the actual headings. Check pasted values and keep formulas and dropdowns intact.

## When records change

- Keep the ID for the same record. Put current information first; keep earlier material judgements and reasons in dated notes in the relevant field, linked decisions or version history.
- When a record is superseded, keep the old row and enter known replacement IDs in **Superseded by**, using the exact design ID and version for artefacts. Separate multiple references with a semicolon and space. Leave blank and flag if the replacement is unknown; don't duplicate the references elsewhere. Withdrawn records have no replacement. Keep permitted history and a dated reason in the owning field; [protect withdrawn research material](research-and-evidence.md#retention-and-withdrawal).
- Check current records that depend on a changed, superseded or withdrawn basis. Follow the replacement and verify it supports the same current claim. Do not treat a historical reference as a problem or change a team's judgement without its agreement. [Check affected evidence](research-and-evidence.md#trace-withdrawn-evidence).

## Record guides

| Guide | What it covers |
|---|---|
| [Project setup and management](project-setup-and-management.md) | Problem, scope, people, outcomes, measures, assumptions, constraints, dependencies, risks, decisions and glossary. |
| [Research and evidence](research-and-evidence.md) | Questions, rounds, participants, sessions, materials, findings, sources and human analysis. |
| [Design and development](design-and-development.md) | User groups and needs, use cases, design versions, rules, requirements and assessment. |

The guides explain the fields. For exact IDs, links and integrity checks, see [record conventions](../AI-skills/record-conventions.md).

For AI assistance, use the [skills guide](../AI-skills/README.md) and give the assistant only material approved for it to process.

## Everyday work

| If you need to… | Open… |
|---|---|
| Start or understand a project | [Frame the work](#frame-the-work) |
| Join or adapt a project | [Adapt the starter](#adapt-the-starter) |
| Plan research or organise materials | [Research planning](research-and-evidence.md#research-planning) and [Research protocol](research-and-evidence.md#research-protocol) |
| Record what the team learnt | [Human analysis before documentation](research-and-evidence.md#human-analysis-before-documentation) |
| Follow up a team or stakeholder meeting | [Capture what changed in a meeting](research-and-evidence.md#capture-what-changed-in-a-meeting) |
| Explore or retain a design | [Design artefacts](design-and-development.md#design-artefacts) |
| Specify what the service must do | [Requirements](design-and-development.md#requirements) |
| Assess whether needs are met | [User need assessment](design-and-development.md#assess-whether-the-service-meets-the-need) |
| Record or revisit a decision | [Decisions](project-setup-and-management.md#decisions) |
| Answer a project question | [Find and check an answer](#find-and-check-an-answer) |
| Prepare a review or handover | [Hand over or prepare a review](#hand-over-or-prepare-a-review) |
| Upgrade the framework | [Upgrade an existing project](#upgrade-an-existing-project) |
| Check records or repair an error | [Check evidence and records](../AI-skills/check-evidence-and-records/SKILL.md) |

See [worked examples](worked-examples.md) for how the records connect in practice and the [FAQ](faq.md) for common questions.

## Hand over or prepare a review

Show the team's current position, its evidence and what remains open. Cite exact design versions and record IDs. [Prepare a briefing](../AI-skills/prepare-a-briefing/SKILL.md) can help draft the team's account.

## Find and check an answer

Find the current record via the tracker and read its status and source. [Check the claim](research-and-evidence.md#check-a-claim). For AI assistance, use [Find and explain](../AI-skills/find-and-explain/SKILL.md).

## Adapt the starter

Use the tools and records your team already maintains. A small team might start with user groups, needs, findings and decisions, using session and source registers for SES and DOC citations.

- Keep starter record names in the document tracker. Set **File or URL** to the current path relative to your working folder or approved URL. The visible location is authoritative; a clickable hyperlink is optional. Use **What it holds** for the content and scope. Set **File or URL** to Unused for a deliberately unused record. For split ownership, identify the scope each owner covers and resolve conflicting owners.
- Add useful local files to the tracker; there is no need to list every attachment or repeat source citations. Register a source when a record needs to cite it or track its version. Keep exact evidence versions and permissions.
- Add uniquely named columns inside an Excel table where useful. Keep framework IDs and required headings. Put external references in the existing appropriate source or descriptive field, qualifying the system (for example Jira ABC-12) and link where useful. A local extra column is optional. For information outside the table, verify the ID it belongs to.
- Complete the classification fields in Scope, Project people, Design artefacts and Requirements. Use the named tabs in Outcomes and measures and Research planning. Check affected records and links before changing headings, controls, tables or ID patterns. Document local conventions in [project config](../_project-config.md).

If a save is blocked, note the affected record, source and agreed change in existing team notes. Check the latest record before applying it later.

## Upgrade an existing project

For future releases, follow the release notes. Keep a recoverable copy and compare a separate copy of the new starter with your project.

| Framework guidance and templates | Project-owned records to preserve |
|---|---|
| `how-to/`, `AI-skills/`, `research/templates/` and `journeys/templates/`. Refresh or merge local adaptations. | Project README, config, document tracker, workbooks and actual sources, research rounds, journeys and prototypes. Keep their data, IDs, paths and local fields. |

Do not bulk-copy starter files over your project. Existing round and journey files can stay where they are; there is no retrospective folder move or blanket schema migration. Change record layouts only as needed under the release notes, preserving local mappings and controls. Refresh [installed skills](../AI-skills/README.md#refresh-skills-after-an-upgrade). Check the actual tracker, fields, controls and links. Trace a representative record or use the [quick test](../AI-skills/README.md#quick-test). Update the Starter version in the project README only after checking the upgrade.
