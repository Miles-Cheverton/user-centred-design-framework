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

- **Skills used from the project or linked to it.** Check that the assistant opens the updated project copy of the skill. If the project moved, update the link.
- **Skills uploaded, copied or pasted separately.** Refresh the changed skills in the place the team actually uses them. Replace the old uploaded copy, installed file, saved prompt or Site skill as applicable. Keep project-specific additions and point the assistant to the updated [AI guidance](../ai-guidance.md) and file guides in the working project.
- In a fresh chat, select the updated skill and [run the quick test](#quick-test). Compare the revision line in each installed skill you use with the corresponding file in the new starter. Check that the assistant can open the project guidance. If it cannot see the files, share only the approved files it needs and retry.

### Quick test

Start a fresh chat with [Find and explain](find-and-explain/SKILL.md) and give it access to [AI guidance](../ai-guidance.md). Give it only these fictional files as evidence. In SharePoint, reference the copies in SharePoint.

- [Example user needs](../how-to/quick-test/example-user-needs.xlsx)
- [Example findings and observations](../how-to/quick-test/example-findings-and-observations.xlsx)
- [Example session notes](../how-to/quick-test/example-session-notes-v1.md)

> Quote the Skill revision line from the Find and explain instructions you have loaded. Say whether you could open ai-guidance.md. Using the three example files, trace UN-941 to the team’s finding, its two observations and the original notes for those observations. Give the workbook, tab and row or cell for each record. Quote each note and give its timestamp. How many needs are in the example table? Say which files you opened.

Compare the quoted revision with the **Skill revision** in the intended skill file. A missing or different line leaves the update unverified, even if the evidence trace is correct. If the app cannot show what is installed, open the saved or uploaded skill and check it there. Check for two needs, the exact UN-941 rather than the nearby returns record, and two matching quotes and timestamps in the notes.

To check missing access, repeat in a fresh chat with only the example user needs workbook as evidence. The assistant should report the linked finding ID and ask for the evidence files.

## Use a skill

For a live project, use its own IDs. For example, “Update [need ID] with the wording we agreed. Keep its ID and existing evidence links.”

For example, a content designer and developer could ask, “Our email tells users their booking is confirmed. Compare it with the booking rule and the event that sends it. Where could that promise break, and what should we test first?”

## Shared working rules

Follow the [AI guidance](../ai-guidance.md) for scope, human analysis, access, evidence and authorised edits. Use the [project README](../README.md) to locate records and the [file guides](../how-to/files/) for their fields and checks.
