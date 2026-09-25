---
name: interview-prep
description: Prepares a few high-value questions for the instructor's Monday team interview from the preliminary assessment, each tied to the evidence that motivated it. Use when the instructor asks for interview or Monday questions for a team.
argument-hint: <tag> <team>
---

# Team Assessment / Interview Preparation

Using the preliminary assessment in `reviews/<tag>/<team>/`, prepare a small
number of high-value questions for the instructor's team interview.

The purpose is to examine things that repository evidence cannot establish.

Prioritize questions about:

- important engineering decisions;
- concepts that may not be fully understood;
- surprising implementation choices;
- agent-generated work requiring explanation;
- validation;
- team roles;
- review of other members' work;
- abandoned or redirected issues;
- earlier instructor feedback the team did not act on.

Avoid trivia.

Prefer questions such as:

"Walk me through why the team chose this approach."

"What would happen if this assumption changed?"

"How did you verify the result produced here?"

"What did you change after the agent produced the initial implementation?"

"What was Student B's role in this part?"

"What happened to issue #X?"

Record which repository evidence motivated each question.

## Output

Write `reviews/<tag>/<team>/interview-questions.md`.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`), then ask the
instructor the Friday questions in `research/diary.md`.
