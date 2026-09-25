---
name: draft-pr-review
description: Drafts GitHub feedback on a team's submission as a PENDING review that is never submitted. Use when the instructor asks for PR comments, line comments or a draft GitHub review for a team.
argument-hint: <tag> <team> [PR number]
---

# Draft GitHub Review

Prepare instructor feedback for the submission.

START A PENDING REVIEW.

DO NOT SUBMIT THE REVIEW.

## Inputs

- `reviews/<tag>/<team>/preliminary-rubric.md`: base the feedback on the rubric findings.
- Earlier feedback in `reviews/<earlier tag>/<team>/instructor-assessment.md`: do not
  repeat a point the instructor already made unless the team ignored it, and then say so.

## Steps

Use line comments when feedback concerns specific lines.

Use broader comments when the issue concerns:

- architecture;
- methodology;
- organization;
- interpretation;
- multiple files.

Use GitHub suggested changes for small, clear, local improvements.

Prefer questions when demonstrating understanding is more important than simply
providing the answer.

Good:

"Why is the complete dataset normalized before the train/test split here?
Consider what information from the test set becomes available during training."

Avoid:

"This is obviously AI-generated."

Also provide a short overall review containing:

- main strengths;
- most important improvements;
- unresolved questions.

The instructor will edit and submit all feedback.

## Finish

Append an entry to `research/agent-log.md` (see `AGENTS.md`), with a link to the
pending review.
