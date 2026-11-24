# AI skills

Choose a skill below or start with the [UCD project assistant](ucd-project-assistant/SKILL.md). Say what you want back. For advice, name the decision and who will use the answer. The same skills support all eight disciplines in the [guidance for experienced teams](../ai-guidance.md#advise-an-experienced-team). Give the assistant the project records and linked guidance it needs. If you install or upload a skill separately, give it the project's AI guidance and any linked file guides it cannot open.

## Choose a task

- [Find and explain](find-and-explain/SKILL.md) to answer a project question or trace a claim.
- [Capture or update records](capture-or-update-records/SKILL.md) to document the team's work or file supporting material.
- [Check evidence and records](check-evidence-and-records/SKILL.md) to verify support, check assessments, inspect the project structure or help [upgrade an existing project](../how-to/README.md#upgrade-an-existing-project).
- [Prepare a briefing](prepare-a-briefing/SKILL.md) for refinement, playback, phase review or handover.
- [Import an existing project](import-existing-project/SKILL.md) to find and format records from existing documents, including Confluence PDF exports.

## Set up your AI assistant

- **Codex.** Open the project folder and point Codex to the skill. For selectable skills, link each skill folder under `.agents/skills`. [Codex skills](https://learn.chatgpt.com/docs/build-skills)
- **Claude.** In Claude Code, open your project and point it to the skill, or link the skill folders under `.claude/skills`. In Claude chat, attach the files and paste the instructions or upload a skill ZIP if enabled. [Claude Code](https://code.claude.com/docs/en/skills), [Claude chat](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
- **Copilot on SharePoint.** Reference the project files and paste the instructions. Use Site skills where available. [Reference files](https://support.microsoft.com/en-us/microsoft-365-copilot/refer-to-specific-files-and-more-in-microsoft-365-copilot), [Site skills](https://learn.microsoft.com/en-us/sharepoint/copilot-in-sharepoint-skills)

### Refresh skills after an upgrade

- **Skills used from the project or linked to it.** Open the link or file the assistant actually uses. If the project moved, update that link.
- **Skills uploaded, copied or pasted separately.** Open the installed copy in the app and compare its **Skill revision** to the corresponding file in the new starter. Refresh each skill you use, including any that write to the project. Give it access to the updated project guidance and related files.
- Compare the **Guidance revision** in the actual project copies of `ai-guidance.md` and `how-to/record-conventions.md` with the target starter. This revision expects `2026-11-24.3` in both files and in each of the six project skills and in the Findings and observations file guide. If any revision is missing or different, or you cannot verify the installed copy, the upgrade is unverified. Keep the previous matched set in use until you've resolved it.
- In a fresh chat, select the skill and run the quick test below. A correct example answer checks evidence access. It cannot verify the installed copy on its own.

### Quick test

Start a fresh chat with [Find and explain](find-and-explain/SKILL.md). Give it access to the same [findings guide](../how-to/files/findings-and-observations.md), [AI guidance](../ai-guidance.md) and [record conventions](../how-to/record-conventions.md) it uses for the project. Give it only these fictional files as evidence.

- [Example user needs](../how-to/quick-test/example-user-needs.xlsx)
- [Example findings and observations](../how-to/quick-test/example-findings-and-observations.xlsx)
- [Example session notes](../how-to/quick-test/example-session-notes-v1.md)

> Quote the Skill revision from the instructions already active in this chat, if visible, and say where you got it. If you can only see a project file, report the installed revision as unverified. For each guidance file you actually opened, give its path and Guidance revision. Open the Findings and observations guide and give its revision and withdrawal heading. Then use the examples to trace UN-941 through its finding and both observations to the original notes. Give each workbook, tab and row or cell, then quote each note with its timestamp. How many needs are in the example table? Which finding behind UN-914 was withdrawn, why, and what does that mean for the need’s current support?

Check which copies were read and compare both guidance revision lines with the target starter. Check for two example need rows, the exact UN-941 and two matching notes and timestamps. FND-914 should be identified as withdrawn, with its reason and historical source. It supplies no current support for UN-914. To check missing access, repeat with only the example needs workbook as evidence. The assistant should give the linked finding ID and ask for the missing evidence.

## Use a skill

For a live project, use its own IDs. For example, “Update [need ID] with the wording we agreed. Keep its ID and existing evidence links.”

For example, a content designer and developer could ask, “Our email tells users their booking is confirmed. Compare it with the booking rule and the event that sends it. Where could that promise break, and what should we test first?”

## Shared working rules

Follow the [AI guidance](../ai-guidance.md) for scope, human analysis, access, evidence and authorised edits. Use the [project README](../README.md) to locate records and the [file guides](../how-to/files/) for their fields and checks.
