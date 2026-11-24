# How to use the project foundations

Start with the task in front of you. Use the [record catalogue](../README.md#find-a-record) if you already know what you need to find.

## Frame the work

1. Set the [working folder](../project-config.md). Bring in existing records with [Import an existing project](../AI-skills/import-existing-project/SKILL.md) when useful.
2. Write the [problem statement](files/problem-statement.md). Say who experiences the difficulty and why it matters.
3. Capture known users, outcomes and responsibilities. Record what is [in scope](../in-scope.xlsx) and [out of scope](../out-of-scope.xlsx), and why. [Register the sources](files/source-register.md) the team relies on.
4. Record important unknowns as [assumptions](files/assumptions.md) or [research questions](files/research-questions.md).

Agree where the team keeps the current record for each kind of information. Use [project config](../project-config.md#other-project-locations) to note any that live elsewhere. For example, keep delivery status on the team’s board and link to it from the relevant framework record.

## Capture learning

1. Before reading an AI summary, give the researcher, observers and other colleagues space to say what stood out. [Compare interpretations](evidence-and-interpretation.md#human-analysis-before-documentation) and note what the team concluded, where people disagree and what is still open.
2. While the group is still together, use [Capture or update records](../AI-skills/capture-or-update-records/SKILL.md) with those notes and any transcript or other sources approved for AI use. Ask it to draft the updates, find existing records that match and point to relevant passages the group may have missed. For example, it might flag a timestamp where a participant took a different route.
3. Discuss anything that could change the interpretation. Retain disagreements in the debrief and include any that limit a finding on its row. Save the agreed [findings](files/findings-and-observations.md) with exact sources, including contrary or inconclusive learning. Update related [user needs](files/user-needs.md), assumptions or research questions when the team agrees.

When sharing research more widely, use a summary that protects participants’ identities.

## Prepare research

Link the [questions](files/research-questions.md) and a short [protocol](research-protocol.md) from the [round](files/research-plan.md). Prepare the method and consent, and link the materials you use. Record the [sessions that take place](files/research-sessions.md), then analyse the evidence with the team.

## Explore a design

Retain the exact [journey](files/user-journeys.md) or [prototype](files/prototypes.md) versions used in research, review, decisions or handover. Use a [use case](files/use-cases.md) to describe a specific interaction. For an early policy or offline option, keep a version of the team’s design note or board when it will be useful later. [How to retain an option and trace the choice](files/decisions.md#retain-an-option-before-a-decision). Capture what the team learns in [findings](files/findings-and-observations.md).

## Assess whether needs are met

Use the existing [user need row](files/user-needs.md#assess-whether-the-service-meets-the-need) for the team’s fulfilment assessment, tested scope and evidence. Record its delivery choice independently. Use the workbook totals with the assessed scope and open gaps.

## Record a decision

Use the [decision guide](files/decisions.md) to record the choice, rationale, evidence and who made it. Update the records it affects. Keep earlier choices discoverable when a decision changes.

## Capture what changed in a meeting

1. Ask the delivery manager, business analyst or other person taking notes to capture significant choices, reasons and open questions. Use the same approach for a stakeholder call, design review or stand-up. Keep routine actions in the delivery backlog.
2. Give [Capture or update records](../AI-skills/capture-or-update-records/SKILL.md) those notes and, if available, the transcript approved for AI use. Ask it to draft changes to decisions, dependencies or other relevant records. It can find an exact passage, flag a mismatch and fill in a date or name when the source establishes it.
3. Review the draft in the call or with the decision maker. Record an agreed choice with its scope, reason and any open conditions. Keep proposals open and flag unclear agreement for confirmation. Put an open start date in the decision’s **Why**. Link a dependency if an outside team or system needs to act first. Link to the exact source and timestamp or section. Use one [source register entry](files/source-register.md) for a source cited by several records.

## Hand over or prepare a review

Show the team’s current position, the evidence it rests on and what is still open. Cite exact design versions and relevant record IDs. Use [Prepare a briefing](../AI-skills/prepare-a-briefing/SKILL.md) to draft from those records.

## Find and check an answer

Find the record and read it with its status and source. [Check the claim](evidence-and-interpretation.md#check-a-claim) against the actual evidence and report any gaps. For AI assistance, use [Find and explain](../AI-skills/find-and-explain/SKILL.md).

## Capture a little, retain what matters

Capture the first useful record when the work happens. Fill in the details required by its file guide before relying on it. Use the team’s existing reviews to check significant findings and choices. When you run [Check evidence and records](../AI-skills/check-evidence-and-records/SKILL.md) for project integrity, it flags duplicate IDs and shows where they occur.

## Upgrade an existing project

1. Read the **Starter version** in your project README and use the [file list for your starting version](#files-to-update-from-v051). Keep a copy or a restorable version of any files you’ll change. Extract the new ZIP into a separate folder outside the project. Never extract it over the project or replace the project folder.
2. Apply only the files listed for that upgrade. Keep existing workbooks, IDs and evidence unless the release gives specific migration steps. If your copy of a file matches the old starter, you can replace that file with the new one. If you’ve customised it, compare the old starter, your copy and the new starter. For example, keep your project name, owner and review details in the README and add the new guidance and links. Keep working paths and local settings in project config. If you can’t tell what a change would replace, leave that file in place for review.
3. [Refresh the skills where you use them](../AI-skills/README.md#refresh-skills-after-an-upgrade). Compare one existing need, its finding and source, and any linked decision or assessment with your pre-upgrade copy. Use the quick test in the new skills guide to check the assistant setup. Once these checks pass, update the **Starter version** in the project README.

If you stop partway through, compare the listed files with the new starter and finish the work that remains. Use the backup or version history to recover an affected file, and check for any newer team edits before restoring it.

### Files to update from v0.5.1

Use these paths relative to the project folder. Compare or merge customised files before you copy anything.

- **Project guidance.** `README.md`, `project-config.md` and `ai-guidance.md`.
- **Skills.** `AI-skills/README.md` and the six existing `SKILL.md` files. Keep any skills your team added.
- **Handbook.** `how-to/README.md`, `how-to/record-conventions.md`, `how-to/worked-beta-readiness.md` and `how-to/worked-service-handoff.md`.
- **File guides.** Under `how-to/files/`, update `decisions.md`, `findings-and-observations.md`, `source-register.md` and `user-needs.md`.
- **Quick test.** Add `how-to/quick-test/example-user-needs.xlsx`, `how-to/quick-test/example-findings-and-observations.xlsx` and `how-to/quick-test/example-session-notes-v1.md`.
- **User needs workbook.** Keep your populated workbook. To add the three warning counts, copy the formula text from each of cells F1 to H1 in the new starter into the same cell in your existing `userNeeds` workbook table’s sheet. Copy the text from the formula bar so the table references resolve locally. Check that F1 to H1 are available in your copy before using them. If your table has a different name or those cells are in use, use the integrity check until you can adapt the formulas. The warnings are optional for existing projects.

For an upgrade directly from v0.4, also update `how-to/files/assumptions.md`. The working workbook layouts are the same in both versions. For earlier versions, use the [v0.4 migration notes](https://github.com/Miles-Cheverton/user-centred-design-framework/blob/v0.4/repository-info/CHANGELOG.md#upgrading-from-v037-or-earlier) first.

## Reference guides

- [Record conventions](record-conventions.md) for IDs, links and workbook editing.
- [Research protocol](research-protocol.md) for planning, consent and research materials.
- [Evidence and interpretation](evidence-and-interpretation.md) for analysis and citations.
- [Collection-readiness handoff](worked-service-handoff.md) and [beta readiness decision](worked-beta-readiness.md) for worked examples.
