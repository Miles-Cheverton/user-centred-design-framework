# AI prompts

Choose a prompt for a specific task and give it to the AI tool available to your team. These are ordinary Markdown instructions, with no dependency on a particular model.

| Task | Prompt |
|---|---|
| Answer a question using the project’s records | [answer-project-question.md](answer-project-question.md) |
| Prepare a focused contribution to refinement | [prepare-for-refinement.md](prepare-for-refinement.md) |
| Find important gaps in the evidence supporting a proposal or decision | [identify-evidence-gaps.md](identify-evidence-gaps.md) |

## Use a prompt

1. Read the project [README](../README.md), [ai-guidance.md](../ai-guidance.md) and the [canonical relationship reference](../how-to/record-conventions.md#canonical-relationships).
2. Replace the task placeholders with the actual question and scope.
3. Read the relevant file guides and give the AI approved access to the necessary records, or provide suitable extracts. Workbook extracts must retain headers and relevant full rows, including IDs, statuses, versions and source paths. State the extract's coverage.
4. Check its references and whether it faithfully represents conclusions people have already reached. Return meaning-changing discrepancies to the team.
5. Use the result in the team’s normal conversation and decision process.

Opening this folder does not automatically configure an AI tool. Some tools cannot read Excel, recordings, graphics or interactive prototypes. The prompt requires the AI to state those limitations.

Use exact typed references from the relationship table. Do not infer joins from similar names or text, and do not read unrelated files to compensate for an unresolved reference. Use the live project’s records as evidence.

The prompts retrieve established knowledge, check consistency and prepare documentation. Human critical thinking and analysis come first: do not use these prompts to generate research themes, findings, implications or needs from raw transcripts, even as drafts for approval. Follow [human analysis before documentation](../how-to/evidence-and-interpretation.md#human-analysis-before-documentation). They do not confer permission to publish, contact people, change decisions or alter external systems. Apply the user’s explicit task instruction and the project’s access arrangements.

When improving a prompt, change it around a real task or observed failure. Keep the expected answer short enough to use during normal work. Do not optimise it around a particular model’s private instructions.

## Capturing or updating records

These prompts support focused questions. For authorised record capture, updates or integrity checks, use the relevant [portable procedure](../skills/README.md). It is ordinary Markdown that any capable model can read; load only the selected procedure and its references. The task still determines what actions are authorised.
