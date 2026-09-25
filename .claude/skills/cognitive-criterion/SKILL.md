---
name: cognitive-criterion
description: Pass 2 of a submission review. Scores ONE cognitive or judgment-heavy rubric criterion across ALL teams at once so it is read the same way everywhere. Use when the instructor asks to review a criterion across teams or to calibrate a criterion.
argument-hint: <tag> <criterion id or name>   e.g. v3 C4
---

# Cross-Team Cognitive Criterion Review

Review ONE specified cognitive rubric criterion across ALL submitted teams.

Do not evaluate unrelated criteria.

## Inputs

- The assignment instructions and rubric for `<tag>`, as configured in `course/config.yml`.
- The criterion and its rating levels from the rubric.
- Every team's repository under `submissions/`, checked out at `<tag>`.
- How the instructor read similar criteria before:
  `reviews/<earlier tag>/*/instructor-assessment.md`.

## Steps

For every team:

1. collect relevant evidence;
2. identify what is clearly demonstrated;
3. identify what is only partially demonstrated;
4. identify important assumptions or limitations students failed to discuss;
5. propose a provisional rubric level, as one of the rubric's rating levels (with its id, where the rubric has ids).

After examining all teams, identify:

- one or more strong anchor examples;
- middle/adequate examples;
- weak examples;
- borderline cases requiring instructor judgment.

Use these anchors to check that the criterion has been interpreted consistently.

Do not rank students merely for the purpose of creating a distribution.
A team meeting the criterion should receive the appropriate result regardless
of how other teams performed.

## Output

Add the criterion's result to each team's `reviews/<tag>/<team>/preliminary-rubric.md`,
and write the anchors to `reviews/<tag>/criteria/<criterion id>.md`.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`).
