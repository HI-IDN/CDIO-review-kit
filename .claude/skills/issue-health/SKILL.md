---
name: issue-health
description: Reviews how a team used issues during one module (scope, linkage, lifetime, abandoned plans) and suggests coaching feedback. Use when the instructor asks about issues, planning or the project board for a team.
argument-hint: <tag> <team>
---

# Issue Health Review

Review issues created or active during the module period that ends at `<tag>`.
The module dates come from `course/config.yml`.

Calculate or inspect:

- number created;
- number closed;
- number remaining open;
- issue lifetime;
- linkage to PRs/commits;
- use of subissues/checklists;
- duplicate or overlapping issues;
- apparently abandoned issues.

Qualitatively assess whether issues are generally:

- appropriately scoped;
- too broad;
- too fragmented;
- useful for coordination;
- merely administrative.

Where planning changed, check whether the team documented why.

Do not penalize abandoned plans simply because they changed.

Instead, look for evidence that the team recognized and documented the change.

Suggest coaching feedback where appropriate.

## Output

Write `reviews/<tag>/<team>/issue-health.md`.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`).
