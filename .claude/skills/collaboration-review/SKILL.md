---
name: collaboration-review
description: Describes observable collaboration in one team (activity distribution, interaction, roles) from analytics and GitHub evidence, and flags patterns for the instructor. Use when the instructor asks about teamwork, contribution or roles in a team.
argument-hint: <tag> <team>
---

# Collaboration Review

Assess observable collaboration patterns for the team.

Begin with computed analytics where available (`analytics/<tag>/`).

Do not treat activity counts as grades.

Consider:

- distribution of commits;
- issues opened and closed;
- pull requests;
- review activity;
- discussion participation;
- activity over time;
- interaction between members;
- apparent division of roles.

Then inspect a small qualitative sample of GitHub interactions.

Prefer interactions that are informative, such as:

- substantial issues;
- PRs with discussion;
- work involving multiple team members;
- major changes;
- abandoned or redirected work.

## Output

Write `reviews/<tag>/<team>/collaboration.md` with these sections:

### Participation pattern

Describe the observable distribution of activity.

### Team interaction

Is there evidence of substantive interaction between members?

### Roles

Are different responsibilities visible?

### Potential discrepancies

Identify unusual patterns requiring instructor investigation.

Do not conclude that a quiet GitHub user contributed nothing.

### Monday questions

Generate targeted questions that could clarify anything GitHub evidence cannot
establish.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`).
