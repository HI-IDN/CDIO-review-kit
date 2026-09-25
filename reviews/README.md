# Reviews

Assessments go here, one folder per submission tag.

```text
reviews/
  <tag>/                        e.g. v3
    <team>/
      preliminary-rubric.md     agent draft: procedural-review, cognitive-criterion
      collaboration.md          agent draft: collaboration-review
      issue-health.md           agent draft: issue-health
      interview-questions.md    agent draft: interview-prep
      final.md                  agent draft: finalize-assessment
      instructor-assessment.md  instructor's final decision, from the LMS
    criteria/
      <criterion id>.md         cross-team anchors: cognitive-criterion
```

The agent drafts are working documents. They should clearly distinguish
automatically generated observations from instructor decisions.

`instructor-assessment.md` is the instructor's decision as recorded in the
LMS. Agents read them as earlier feedback when
reviewing later tags and never edit them.
