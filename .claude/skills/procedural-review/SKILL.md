---
name: procedural-review
description: Pass 1 of a submission review. Scores every PROCEDURAL rubric criterion for one team at its submitted tag. Use when the instructor asks for the procedural pass, first pass or coverage pass for a team.
argument-hint: <tag> <team>   e.g. v3 team-01
---

# Procedural Review

Review the team's repository against all rubric criteria marked `PROCEDURAL`.

## Inputs

- The assignment instructions and rubric for `<tag>`, as configured in `course/config.yml`.
- The criteria marked `PROCEDURAL` in the rubric or its metadata.
- The team's repository under `submissions/`, checked out at `<tag>`. Never review
  `main`; it may have moved on after the deadline.
- Earlier feedback: `reviews/<earlier tag>/<team>/instructor-assessment.md`.

## Steps

Prioritize coverage.

For each criterion:

1. state whether the requirement is met;
2. cite concrete evidence;
3. identify missing or incorrect elements;
4. propose a provisional rubric result, as one of the rubric's rating levels (with its id, where the rubric has ids);
5. indicate uncertainty where appropriate.

Also identify obvious:

- broken code;
- missing files;
- reproducibility problems;
- incorrect paths;
- missing data;
- structural problems.

Do not spend substantial time on cognitive interpretation during this pass.

## Output

Create or update `reviews/<tag>/<team>/preliminary-rubric.md`. Mark it as an
agent draft.

Do not submit GitHub feedback.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`).
