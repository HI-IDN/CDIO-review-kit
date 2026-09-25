---
name: finalize-assessment
description: Combines the preliminary assessment, reviewed feedback, collaboration indicators and interview notes into a final rationale per criterion for the instructor to approve. Use after the team interview when the instructor asks to finalize a team's assessment.
argument-hint: <tag> <team>
---

# Finalize Assessment

Use:

- preliminary rubric assessment;
- GitHub evidence;
- instructor-reviewed feedback;
- collaboration indicators;
- team interview notes.

Update the rubric assessment.

Clearly distinguish:

- team-level assessment;
- any justified individual discrepancy;
- instructor judgment;
- automatically gathered evidence.

Do not manufacture individual differences merely because GitHub activity counts
differ.

Produce a concise final rationale for each rubric criterion, with its rating level.

The instructor remains responsible for approving the final grade.

## Output

Write `reviews/<tag>/<team>/final.md`. Once the instructor has entered the grade
in the LMS, the recorded result is stored as `reviews/<tag>/<team>/instructor-assessment.md`.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`), then ask the
instructor the Monday questions in `research/diary.md`.
