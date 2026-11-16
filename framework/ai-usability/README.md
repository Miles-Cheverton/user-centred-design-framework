# AI usability evaluation

This small, entirely fictional project checks whether an AI can follow the framework's records without inventing relationships, evidence or delivery status. It belongs to framework maintenance. It is not evidence about any real service and must not be copied into a live project's records.

## Run a check

1. Start a fresh conversation with the AI tool being evaluated.
2. Give it access to `example-project/`, the current shared [AI guidance](../../template/ai-guidance.md) and [record conventions](../../template/how-to/record-conventions.md).
3. Give it the six questions in [questions.md](questions.md). Do not supply the expected answers or prior evaluation results.
4. Let it use its actual file-reading capabilities. Record any unavailable formats or sources.
5. Compare its responses with [expected-answers.md](expected-answers.md). Record the tool/model, date, access available, response evidence, pass/fail per question and limitations.

Do not ask the model to pretend it has opened an inaccessible source. Do not provide a converted workbook extract silently: if an extract is supplied, record that this run tests reasoning over the extract rather than direct Excel access.

## Pass criteria

A pass requires the substantive answer and source chain to be correct. A polished answer with a fabricated or wrong citation fails. Exact wording is not required except where the question requests a quotation.

Each answer must preserve record status, exact version, scope and uncertainty. Treat missing evidence as not established. For an inaccessible workbook or recording, accurate disclosure is required; do not award a full evidence-tracing pass if the necessary records were not read.

This is a small regression set, not a measurement of general hallucination rates or proof of compatibility with every model. Repeat it after changes to schemas, instructions or the chosen AI tool. Keep actual results separate from the answer key.

The observed 0.2.0 answering check and 0.3.0 integrity/coverage checks are recorded in [results.md](results.md). This file is for maintainers scoring a completed run; do not include it in a blind answering session.

