# Reusable project skills

Choose a skill, then give the assistant the task and the project files it needs. If the tool has no skill picker, point it to the linked Markdown file.

## Choose a task

| Task | Skill |
|---|---|
| Record human conclusions from a meeting or check them against a research transcript | [Extract project records](extract-project-records/SKILL.md) |
| Capture or refine a user need | [Add a user need](add-user-need/SKILL.md) |
| Describe a specific service interaction | [Add a use case](add-use-case/SKILL.md) |
| Record the team's research finding and check its source references | [Record a research finding](record-research-finding/SKILL.md) |
| Make an untested belief visible | [Capture an assumption](capture-assumption/SKILL.md) |
| Record a significant proposed or agreed choice | [Record a decision](record-decision/SKILL.md) |
| Add another clearly identified structured record | [Record a project item](record-project-item/SKILL.md) |
| File discussion guides, surveys, response exports, calculation working or Whiteboards | [Record a project item — research materials](record-project-item/SKILL.md#research-materials) |
| Retain a meaningful design option or version | [Record a design option](record-design-option/SKILL.md) |
| Record the team's assessment of whether a need is met | [Assess user-need coverage](assess-user-need-coverage/SKILL.md) |
| Find gaps and inconsistencies, and repair authorised issues | [Check project integrity](check-project-integrity/SKILL.md) |

## Use a skill

Say what to work on, name the source or record, and specify the result you want. For example:

- “Check the evidence links for FND-201 and show me anything missing.”
- “Draft the finding the team reached in these analysis notes. Check its references against the supplied transcript.”
- “Update UN-201 with the wording we agreed in this meeting. Keep its ID and existing evidence links.”

Read the [project README](../README.md) to confirm the working location and use the [AI guidance](../ai-guidance.md). Open the selected skill, the owning file's [guide](../how-to/files/) and the relevant [record conventions](../how-to/record-conventions.md) for IDs and relationships.

## Shared working rules

1. Preserve the meaning and review status of the team's conclusions and decisions. For research findings, use [human conclusions](../how-to/evidence-and-interpretation.md#human-analysis-before-documentation) from discussion, notes or existing records. With raw material alone, locate or capture requested literal observations with source references and say what needs team analysis.
2. Check the current owning record and source before changing either. Read relevant workbook rows with their headers and verify exact IDs and versions. Keep the existing ID for the same record and allocate a new one only after checking it is free. Report partial access and unresolved references.
3. Save the bounded change when authorised. Preserve existing rows, tables and dropdowns. Reopen the affected record to verify the values and links. If the records are readable but the destination cannot be edited, return an unsaved draft with the destination, ID if verified, and field values. Leave a new ID pending if uniqueness cannot be checked.
4. Report the records changed or drafted, their source references and what still needs the team's input. Keep consequential disagreements or unknowns with the owning record.

For a discussion guide, survey, response export or Whiteboard, start with the [round's material guidance](../how-to/research-protocol.md#discussion-guides-surveys-and-whiteboards) and the [research materials procedure](record-project-item/SKILL.md#research-materials).
