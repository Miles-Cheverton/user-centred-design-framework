# Prompt library

Use these prompts for common tasks in a multidisciplinary UCD team. They work with or without installed skills: the assistant reads the project's actual skill file and its linked guidance. [Set up your AI assistant](README.md#set-up-your-ai-assistant).

1. Copy the prompt you need. Replace the text in square brackets with your project details, including the **exact project folder path or URL**.
2. Reference or attach the approved files the assistant needs. If it cannot open folder links, provide the project config, named skill file, its shared guidance and the relevant records and sources. The assistant must report missing access rather than search elsewhere or guess.
3. Check the answer and sources. People think first; AI helps second. Approve any suggested changes before they are saved.

A prompt is not a technical access restriction. The assistant must verify the actual location of project records. If it cannot save an authorised change safely, it should provide the exact proposed fields ready to paste.

## Understand the project

### Get up to speed on a project

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/prepare-a-briefing/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Help me get up to speed as [role or audience]. Brief me on the current problem, scope, users and needs, key decisions and their evidence, and what remains uncertain or blocked. Point me to the most useful current files and exact records to read next.

Keep this read-only. Distinguish recorded plans from what actually happened.
~~~

### Find an answer

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/find-and-explain/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Find out [question]. Check whether the answer is already in the project records or approved sources. Give the answer, exact source locations and any conflicting or missing evidence. If you cannot establish it, say what you checked and what remains unanswered.

Keep this read-only.
~~~

### Trace the evidence

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/find-and-explain/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Trace [record ID, design version or claim] to its underlying evidence. Show the chain of current record IDs, exact versions, original source locations and relevant passages. Identify evidence that supports or challenges it, what has been superseded or withdrawn, and what is still uncertain.

Keep this read-only.
~~~

## Record what the team has learnt or agreed

### Follow up a research session

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/capture-or-update-records/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

We have already analysed the session. Our agreed conclusions and proposed changes are [team notes]; the permitted sources are [transcript, notes and other approved materials]. Check our conclusions against the sources, locate supporting or conflicting passages, identify overlapping records and unanswered questions, and check that references are correct.

Save only the record changes explicitly agreed in our notes and authorised for saving by this request. Show other suggestions separately for our approval; do not generate findings or needs from the raw transcript. Report what was saved and any remaining gaps.
~~~

### Follow up a meeting

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/capture-or-update-records/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Use our agreed meeting notes [notes] and the approved meeting recording or transcript [source, or none]. Cross-check what was agreed, why, and which existing decisions, assumptions, constraints, scope, risks, dependencies or research questions need updating. Distinguish decisions from discussion and retain relevant alternatives and rationale.

Save only explicitly agreed changes authorised for recording by this request. Flag proposed or disputed changes for us; leave routine delivery actions on our existing board. Report what was saved and what remains open.
~~~

### Assess a document for useful information

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/import-existing-project/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Assess [exact approved document path, URL or attachment] against the existing project records. Identify its purpose, provenance, version, relevance and authority or limitations. Find useful statements, constraints, requirements, existing documented findings, decisions or other information worth recording; show the exact page, section or passage.

For each item, suggest the existing record type, actual owning file and matching ID if any, what should be added or changed, duplication or conflict, and what needs human confirmation. Distinguish the source's claims from team-agreed facts and judgements. Recommend whether to register the source and why. Do not edit any project records.
~~~

### Bring in existing project material

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/import-existing-project/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Review the approved import sources at [exact source folder, file paths, URLs or attachments]. Identify material relevant to the destination project. Reconcile it with current records, retaining source attribution, versions, history and local fields. Suggest only useful records or changes; do not treat raw material as team findings.

Give exact destination files, columns or sections, matching or verified proposed IDs, values and source citations, plus conflicts and inaccessible material. Wait for my approval before saving.
~~~

## Plan and develop the service

### Plan further research

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/ucd-project-assistant/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Help us plan further research for [goal or upcoming round]. Bring together open research questions, uncertain assumptions, design hypotheses, existing findings and actual session coverage by user group, route and circumstance where recorded. Identify questions already answered and the most important gaps.

Suggest focused research questions, the smallest useful test and missing perspectives, explaining why. Keep the plan a proposal for our research team; do not change records.
~~~

### Explore a design proposal

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/ucd-project-assistant/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Help us explore [proposal, with exact artefact or version if available]. Relate it to current user needs, journeys, requirements, business rules, constraints and decisions. Compare plausible alternatives and trade-offs; distinguish tested evidence from hypotheses. Identify potential effects on different user groups, routes and operations.

Suggest what we could test next and what would change our view. Do not select a design or change records.
~~~

### Understand the impact of a change

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/ucd-project-assistant/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Assess the impact of [proposed or confirmed change, with record ID/version if known]. Trace affected current records in both directions, including needs, findings, requirements, design versions, decisions, research questions, risks and dependencies where relevant. Distinguish material impacts from historical references and identify uncertainty.

Give an actionable list of records to review, why and what would need checking or agreeing. Do not update or withdraw records.
~~~

### Prepare work for development

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/prepare-a-briefing/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Prepare a refinement brief for [feature, use case or journey]. Bring together the relevant user needs, their evidence, functional and non-functional requirements, business rules, journey and prototype versions, constraints and dependencies. Show recorded verification and outstanding scope or questions.

Propose concise testable acceptance criteria separately from agreed requirements. Identify what needs clarification with the team. Keep this read-only; do not invent acceptance criteria as agreed.
~~~

### Assess user need fulfilment

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/check-evidence-and-records/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Assess the recorded fulfilment of [user need IDs or all needs within specified scope]. Show the four recorded fulfilment totals for that scope and explain exclusions or invalid rows. For relevant needs, check the underlying assessment evidence against the current user groups, routes, scope and exact design/build versions; identify gaps and changed or untested scope.

Distinguish recorded fulfilment from verified current support and from delivery decisions. Do not assign or change a fulfilment judgement; explain what the team needs to reassess. Keep this read-only.
~~~

### Plan the next sprint

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/prepare-a-briefing/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Help us prepare for sprint planning around [sprint goal or intended outcome]. Bring together the current needs, open research questions, agreed decisions, assumptions, blockers, risks and dependencies. If supplied and approved, compare these with our existing delivery board [path, URL or none].

Suggest a small, evidence-informed set of priorities and explain trade-offs, dependencies and unresolved decisions. Distinguish confirmed commitments from suggestions. Do not assign work, invent dates or edit records.
~~~

## Review, assure and hand over

### Prepare a phase review

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/prepare-a-briefing/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Prepare an evidence-backed outline for our [discovery, alpha, beta or live review] for [audience]. Explain the problem and intended outcomes, what the team learnt, key decisions and their rationale, tests and service changes, and results or measures where recorded. For each important claim show what supports it, what challenges it and what remains uncertain.

Distinguish proposed, tested and delivered work; give exact evidence citations and a concise review narrative. Do not change records or claim formal sign-off.
~~~

### Check against service standards

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/check-evidence-and-records/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Review [service area or phase] against [applicable standard or criterion and version if known]. Use relevant authoritative guidance from the issuing body separately from the project evidence. Identify the applicable requirements, evidence and gaps for each relevant criterion, with exact source references and verified scope.

Distinguish requirements, guidance and professional advice. Flag uncertain applicability or unavailable sources. Keep this read-only; do not claim compliance or formal sign-off without evidence and responsible human review.
~~~

### Prepare a handover

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/prepare-a-briefing/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Prepare a handover for [incoming role or team]. Explain the current problem, scope, user needs, design versions, requirements, decisions and their rationale, current evidence and delivery position, known risks and dependencies, owners and outstanding questions or next steps where recorded.

Point to the actual records and sources. Highlight responsibilities, handoff dependencies and unresolved decisions important to the incoming team. Distinguish current from historical information, agreed from proposed work and recorded status from verified evidence. Keep this read-only.
~~~

### Check project health

~~~text
Use the project at [exact project folder path or URL]. Read its _project-config.md first.
Open and follow AI-skills/check-evidence-and-records/SKILL.md from that project and its linked guidance, whether or not the skill is installed.
Use only the confirmed Working folder and explicitly authorised sources. Report missing access; do not substitute another project.

Run a quick structure check and create or refresh the optional project-health.xlsx in its approved project location. Show current record coverage, recorded statistics, duplicate or malformed IDs, gaps, broken references and suggested review actions. Identify anything inaccessible or unchecked.

Save only the generated report. Do not change project records or infer current fulfilment from counts. Reopen the report to verify it and tell me where it is saved.
~~~
