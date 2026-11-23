# AI skills

Choose a skill below or start with the [UCD project assistant](ucd-project-assistant/SKILL.md). Say what you want back. Give the assistant the project records and linked guidance it needs. If you install or upload a skill separately, point it back to your project copy for those files.

## Choose a task

- [Find and explain](find-and-explain/SKILL.md) to answer a project question or trace a claim.
- [Capture or update records](capture-or-update-records/SKILL.md) to document the team's work or file supporting material.
- [Check evidence and records](check-evidence-and-records/SKILL.md) to verify support, check assessments or inspect the project structure.
- [Prepare a briefing](prepare-a-briefing/SKILL.md) for refinement, playback, phase review or handover.
- [Import an existing project](import-existing-project/SKILL.md) to find and format records from existing documents, including Confluence PDF exports.

## Set up your AI assistant

- **Codex.** Open the project folder and point Codex to the skill. For selectable skills, link each skill folder under `.agents/skills`. [Codex skills](https://learn.chatgpt.com/docs/build-skills)
- **Claude.** In Claude Code, open your project and point it to the skill, or link the skill folders under `.claude/skills`. In Claude chat, attach the files and paste the instructions or upload a skill ZIP if enabled. [Claude Code](https://code.claude.com/docs/en/skills), [Claude chat](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
- **Copilot on SharePoint.** Reference the project files and paste the instructions. Use Site skills where available. [Reference files](https://support.microsoft.com/en-us/microsoft-365-copilot/refer-to-specific-files-and-more-in-microsoft-365-copilot), [Site skills](https://learn.microsoft.com/en-us/sharepoint/copilot-in-sharepoint-skills)

### Quick test

In each tool, use [Find and explain](find-and-explain/SKILL.md) with the [worked handoff](../how-to/worked-service-handoff.md) and an untouched copy of [user-needs.xlsx](../user-needs.xlsx).

> Trace the fictional need UN-201 back to its research evidence in the worked handoff. Give the finding, observations, session IDs and timestamps. Which sources could you open? How many real needs are in the workbook?

Check for `UN-201` → `FND-201` → `EV-201` and `EV-202`, from sessions `SES-201` and `SES-202`. The example gives two transcript references. The untouched workbook contains zero recorded needs. If the tool cannot read the workbook, it should say so.

## Use a skill

For a live project, use its own IDs. For example, “Update [need ID] with the wording we agreed. Keep its ID and existing evidence links.”

## Shared working rules

Follow the [AI guidance](../ai-guidance.md) for scope, human analysis, access, evidence and authorised edits. Use the [project README](../README.md) to locate records and the [file guides](../how-to/files/) for their fields and checks.
