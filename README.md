# CDIO Review Kit

**AI-assisted assessment of engineering teamwork through Git workflows.**

CDIO Review Kit is an instructor-facing toolkit for assessing engineering
coursework where students work collaboratively using GitHub, issues, pull
requests, project boards, code, data, reports, and AI coding agents.

The central principle is:

> Assess evidence of engineering practice and understanding, not merely the
> final artifact.

The toolkit is grounded in the CDIO framework — Conceive, Design, Implement,
Operate — and treats GitHub workflows as observable evidence of the engineering
process.

## Why this exists

Engineering students increasingly work with:

- Git and GitHub;
- issues and project boards;
- pull requests and code review;
- collaborative reports and code;
- AI coding agents.

These tools are also common in professional engineering practice.

Assessment should therefore consider not only *what* a team produced, but also
how the team planned, developed, reviewed, validated, revised, and understood
its work.

## AI use

Students may be allowed or encouraged to use AI agents.

The purpose of this toolkit is **not AI detection**.

A sophisticated piece of agent-generated code is not itself a concern.
The relevant question is whether students demonstrate sufficient understanding
and ownership of the resulting engineering work.

Evidence may include:

- Git history;
- issues;
- pull requests;
- reviews;
- discussions;
- project-board activity;
- code and reports;
- tests and validation;
- responses to feedback;
- instructor interviews.

## Instructor in the loop

Agents assist with evidence collection and preliminary review.

They do **not** make the final academic judgment.

The workflow is:

**Agent gathers evidence → agent drafts assessment → instructor reviews →
students may be questioned → instructor decides → instructor submits feedback**

## Repository structure

- `AGENTS.md` — persistent instructions for grading agents
- `course/` — assignment, rubric, roster and configuration
- `.claude/skills/` — one skill per review step (procedural pass, cross-team
  criterion, draft PR review, collaboration, issue health, interview prep,
  finalize)
- `docs/` — instructor documentation and evidence model
- `analytics/` — reproducible Git/GitHub metrics
- `research/` — research notes and teaching diary
- `submissions/` — local student repositories
- `reviews/` — generated preliminary assessments

## Status

This project is being developed iteratively alongside an engineering course.
The framework itself should therefore be treated as a work in progress.
