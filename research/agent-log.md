# Agent Log

One entry per agent session, newest last, written by the agent at the end of
the session. It is the factual counterpart to `diary.md`: the diary holds the
instructor's thoughts, this log holds what agents did.

Each entry records:

- **Date** and **submission tag**;
- **Task**: what the instructor asked for;
- **Done**: what the agent did, with files, commits and PRs;
- **Changed working material**: any change to `AGENTS.md`, `.claude/skills/`,
  `course/config.yml` or rubric metadata, and why;
- **Judgment calls**: decisions the agent made that the instructor should check;
- **Left for the instructor**: open decisions;
- **Diary prompts**: questions the instructor might answer in `diary.md`.
