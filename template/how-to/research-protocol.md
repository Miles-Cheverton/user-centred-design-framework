# Research protocol

Use this guide to prepare, conduct and close a focused research round. Each round has a row in research-plan.xlsx and an executable protocol at `research/RND-001/protocol.md`, using its actual round ID.

## Prepare the round

1. Select the research questions and the decisions they inform.
2. Choose methods suited to those questions. Explain the choice in the round protocol.
3. Identify the required user groups or other data sources. Include relevant access needs, assisted routes and differences in circumstances.
4. Define recruitment criteria and the intended coverage. A sample size is a reasoned choice for the method, not a fixed template quota.
5. Allocate a lead and prepare the activities, tasks or discussion guide.
6. Identify the exact journey or prototype versions to be used.
7. Agree how data will be collected, stored, accessed, analysed, shared and retained.

The round protocol has six sections: decision to inform; participants or data sources; procedure; consent and data handling; analysis; sharing and action.

## Before a participant session

- Allocate a participant code and session ID. Keep names, contact details and any identity key separately restricted.
- Provide accessible information about the activity and obtain the applicable informed consent.
- Make recording, observers, transcription, AI processing and sharing arrangements clear where applicable.
- Record a consent reference that can be matched to this session's material.
- Check the materials, accessibility arrangements and recording setup.

A consent reference is not permission for every later use. Work within the actual agreement, including any restrictions.

## During the session

Follow the method and protocol while responding appropriately to the participant. Distinguish observed behaviour, the participant's words and researcher interpretation in notes. Avoid leading questions or helping a participant through a problem unless the method calls for it; record material interventions.

Capture only what is necessary to answer the research questions. A recording is useful when its permitted purpose justifies collecting it.

## Store and name material

Use the project folders within approved research storage:

```text
research/recordings/RND-001/
research/transcripts/RND-001/
```

Examples:

```text
2026-11-16_RND-001_SES-003_screen_p01.mp4
2026-11-16_RND-001_SES-003_audio_p01.m4a
2026-11-16_RND-001_SES-003_transcript_v01.txt
```

Use the actual date, round and session IDs. Recording segments use p01, p02 and so on; transcript revisions use v01, v02. Keep the real file extension produced by the tool. Names and emails do not appear in filenames.

Update research-sessions.xlsx with exact Recording links, a single Current transcript link, and Transcript status for that one transcript. Machine-generated, Checked and Corrected require the linked file; Not applicable and Not available require a blank Current transcript link. Preserve useful timestamps and coded speaker labels. A machine-generated transcript may contain errors and must not silently become checked evidence.

When a transcript is corrected, retain its new version and update Current transcript link and Transcript status together. Retain earlier versions where permitted. An EV record continues to cite its exact original source version or path and locator; changing the session's current transcript must not silently change historical evidence.

## Analyse and close the round

1. Bring the researcher, observers and relevant colleagues together after sessions, using the team's existing analysis arrangements. People review observations, discuss patterns and alternative explanations, and establish conclusions, uncertainty and substantive disagreement. AI does not conduct this analysis or generate findings for approval.
2. Preserve the human conclusions in rough notes or discussion records. Once available, AI may tidy them, locate exact supporting passages and flag discrepancies against authorised sources. People resolve discrepancies that could change meaning; checking a transcript does not independently verify its recording.
3. Record selected observations in evidence.xlsx with an exact Source ID, Source version or path, Locator and relevant context. Source ID is one SES or DOC; register a non-session source as DOC first.
4. Capture every substantive human finding in research-findings.md, including differences, uncertainty, contradictory and inconclusive results. Put question, round/session and exact design-version links there. Check that the documentation preserves the team's conclusions before marking Reviewed.
5. Discuss what the findings mean for actual choices and record decisions separately. Needs, assumptions and proposals cite relevant support from their own records; do not copy inverse lists.
6. In the protocol's existing close-out, record what the team analysed and any known unsynthesised material or unresolved interpretations. Distinguish groups identified, planned and actually heard from using the group, round and session records. No new coverage register or sign-off meeting is required.
7. Mark the round Complete only when substantive learning has been captured and reviewed findings are available to inform work. Known material still awaiting analysis keeps the round Analysing. A completed round may retain unanswered questions and inconclusive findings; completion does not establish comprehensive knowledge of every user.

An integrity check can identify a known missing finding or unresolved reference. It cannot certify that no unshared human insight exists. See [human analysis before documentation](evidence-and-interpretation.md#human-analysis-before-documentation).

## Retention and withdrawal

Agree retention and access arrangements with the organisation. Follow the agreed procedure when consent is withdrawn or material is no longer needed. Remove affected copies and review dependent evidence where required. Git or storage version history does not create permission to retain personal data indefinitely.

The public starter contains fictional examples and blank records. Real participant records, recordings and transcripts belong in appropriately restricted working storage. Coded participants are pseudonymous when a recording or identity key can identify them.

## Practice basis

- [GDS: plan user research](https://www.gov.uk/service-manual/user-research/plan-user-research-for-your-service)
- [GDS: informed consent](https://www.gov.uk/service-manual/user-research/getting-users-consent-for-research)
- [GDS: managing research data and participant privacy](https://www.gov.uk/service-manual/user-research/managing-user-research-data-participant-privacy)
- [GDS: analyse a research session](https://www.gov.uk/service-manual/user-research/analyse-a-research-session)

Folder names and ID conventions are this framework's implementation choices. Guidance reviewed: 16 November 2026.
