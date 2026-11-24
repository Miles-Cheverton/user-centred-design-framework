---
name: import-existing-project
description: Find and format records for importing an existing UCD project from agreed sources, including Confluence pages and PDF exports.
---

# Import an existing project

**Skill revision:** 2026-11-24.3

Use the matching revision of `ai-guidance.md` and `how-to/record-conventions.md`. If either is older or unavailable, report the gap before changing project records.

## Copy-and-paste example

> Use AI-skills/import-existing-project/SKILL.md. Review the Confluence PDF exports I supplied. Propose the project records they support, cite the exact sources and show me what needs checking.

## Establish the destination and sources

For updates to the framework files in an existing project, use [Help with a framework upgrade](../check-evidence-and-records/SKILL.md#help-with-a-framework-upgrade).

Confirm the working copy, then identify the sources for this import.

1. Use the files, page links or folders supplied for this request.
2. Otherwise, use **Import source folder** in the [project config](../../project-config.md) if set.
3. If neither is available, ask for the source files or folder.

Before scanning a folder, compare its resolved location with the confirmed **Working folder**. Resolve a local dot relative to the config file in the working copy. If the working folder sits inside the source folder, exclude it and all its contents from source discovery, including links that resolve into it. Compare exact paths or the storage provider's folder hierarchy. Read the working copy separately when matching existing records or saving updates.

If the source and working folder are the same, or you cannot tell which part of the source contains the working copy, ask for a specific source folder or files before scanning it.

For a folder import, [look for relevant additional files](../../ai-guidance.md#include-additional-project-files) in the selected source folder. When the user supplies individual files, use that set. Skip framework templates, worked examples and training files when importing project records. Identify which versions you can inspect. With no access to the destination, propose updates with destination matches and IDs marked unverified. For a whole-project import, check the sources against the [record catalogue](../../README.md#find-a-record). [AI guidance](../../ai-guidance.md#start-with-the-task)

## Read Confluence PDF exports

- Use contents and headings to identify original pages. Follow their sections across PDF page breaks.
- Cite the export file and PDF page, original page title and section, plus the Confluence URL, page version or date where available. Keep the original record date separate from the export date. [Source register guide](../../how-to/files/source-register.md)
- Check extracted tables, images or confusing passages against the rendered PDF. Use permitted OCR for scans and verify material text against the image. Report unreadable content, missing attachments and inaccessible links.

## Reconcile and format the records

1. Extract the documented meaning, status and date. Preserve what people proposed, concluded or agreed. Capture literal observations from raw research and flag where people still need to analyse it. Attribute an external conclusion to its author and exact source. Keep it in the source record or raise it for the team to assess. Create a team finding or need only when the project team has established one.
   Use the [guidance for experienced teams](../../ai-guidance.md#advise-an-experienced-team) to judge what each source can establish. An approved policy can establish a rule, a prototype shows intended behaviour, and release notes identify a change to a build. Each answers a different question. Retain the authority, scope and date when two disciplines describe the same change. Flag any material conflict for the team.
2. Group repeat accounts while retaining material citations and external IDs. Match against the destination and reuse confirmed IDs. Keep earlier decisions and contrary evidence. Flag uncertain matches, conflicting versions and unresolved replacements.
3. Use [Capture or update records](../capture-or-update-records/SKILL.md) to propose or save records in the owning files within the user's authorisation, including any source entries needed for DOC citations. Use its [attachment filing procedure](../capture-or-update-records/SKILL.md#file-a-chat-attachment) when asked to retain supplied files. Include the destination, verified ID if available and exact source. For a whole-project import, show what types you found, what was absent in the checked sources and what remained inaccessible.
