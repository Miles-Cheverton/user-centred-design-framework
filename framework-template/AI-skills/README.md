# AI skills

Start with the [UCD project assistant](ucd-project-assistant/SKILL.md) or choose a task. Tell it the result you need and, for advice, the decision and audience. These skills support the [whole multidisciplinary team](ai-guidance.md#advise-an-experienced-team).

## Choose a task

- [Find and explain](find-and-explain/SKILL.md): answer questions or trace claims.
- [Capture or update records](capture-or-update-records/SKILL.md): document the team's work and file supporting material.
- [Check evidence and records](check-evidence-and-records/SKILL.md): verify claims, assessments, structure or a framework upgrade.
- [Prepare a briefing](prepare-a-briefing/SKILL.md): refinement, playback, review or handover.
- [Import an existing project](import-existing-project/SKILL.md): organise records from existing project documents.

## Set up your AI assistant

Use the project folder containing the [document tracker](../document-tracker.xlsx), including its `AI-skills/` and `how-to/` guidance. For a chat, give the selected skill plus relevant project copies of `AI-skills/ai-guidance.md`, `AI-skills/record-conventions.md`, record guides and approved records/sources. Include the tracker for project work. A pasted skill or isolated ZIP is not the shared guidance; resolve links from its canonical project skill path.

- **Codex:** open the project folder and point Codex to the skill. For selectable skills, link its folder under `.agents/skills`. [Codex skills](https://learn.chatgpt.com/docs/build-skills)
- **Claude:** in Claude Code, open the project and point to the skill or link its folder under `.claude/skills`. In Claude chat, attach needed files and paste the instructions or upload a skill ZIP if enabled. [Claude Code](https://code.claude.com/docs/en/skills) · [Claude chat](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
- **Copilot on SharePoint:** reference project files rather than relying on pasted instructions alone; use Site skills where available. [Reference files](https://support.microsoft.com/en-us/microsoft-365-copilot/refer-to-specific-files-and-more-in-microsoft-365-copilot) · [Site skills](https://learn.microsoft.com/en-us/sharepoint/copilot-in-sharepoint-skills)

### Refresh skills after an upgrade

Follow the [upgrade steps](../how-to/README.md#upgrade-an-existing-project). Relink or refresh installed, copied or uploaded instructions and any moved links; verify access to actual project guidance, not version matches. Check actual records and their controls; use a representative evidence chain or the quick test below.

### Quick test

Start a fresh chat with [Find and explain](find-and-explain/SKILL.md), its linked guidance and only these fictional files as evidence.

- [Example user needs](quick-test/example-user-needs.xlsx)
- [Example findings and observations](quick-test/example-findings-and-observations.xlsx)
- [Example session notes](quick-test/example-session-notes-v1.md)

> Trace UN-941 through its finding and both observations to the original notes. Give each workbook, tab and row or cell, then quote each note with its timestamp. How many needs are in the example table? Which finding behind UN-914 was withdrawn, why, and what does that mean for the need’s current support?

Check for two need rows and two exact matching notes and timestamps for UN-941. FND-914 should be identified as withdrawn, with its reason and historical source. It supplies no current support for UN-914. Repeat with only the example needs workbook: check that the assistant gives the linked finding ID and asks for missing evidence.

## Use a skill

For live work, use the project's actual IDs. For example, “Update [need ID] with our agreed wording. Keep its evidence links.”

## Shared working rules

Read the [shared principles](ai-guidance.md#shared-principles), the sections relevant to the task and the [owning record guide](../how-to/README.md#record-guides). Use [record conventions](record-conventions.md) to verify keys and relationships. A simple lookup needs only the applicable rules; a full integrity audit needs them all.
