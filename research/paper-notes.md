# Paper Notes — CDIO Review Kit

## Working idea

Investigate how GitHub workflow evidence and AI-assisted review can support
scalable assessment of engineering teamwork in a CDIO-oriented course while
retaining instructor judgment.

## Motivation

Engineering education increasingly encourages students to use professional
development practices:

- Git;
- issue tracking;
- pull requests;
- code review;
- iterative development;
- project boards;
- AI coding agents.

Traditional assessment often concentrates on the final artifact.

This potentially discards substantial evidence about how engineering work was
conceived, designed, implemented, reviewed, validated and revised.

GitHub makes parts of this process observable.

The challenge is that reviewing this evidence manually across many teams and
assignments is expensive.

AI agents may make systematic evidence review feasible, but assessment should
not simply be delegated to an LLM.

The proposed approach therefore combines:

**computable Git/GitHub indicators + AI-assisted evidence review + instructor
judgment + oral validation.**

## Educational context

The course uses:

- flipped-classroom teaching;
- team-based learning;
- authentic engineering applications;
- GitHub-based teamwork;
- iterative submissions;
- AI agents as legitimate engineering tools.

Students work through six modules.

Approximately every two weeks, another module extends an accumulating project
and report.

The final project provides a second pass in which students revisit the complete
work, improve it, and produce a coherent integrated result.

## Assessment cycle

Each module creates a repeated assessment cycle.

### Thursday

Submission deadline at midnight.

### Friday

Repository-based assessment:

- automated metrics;
- AI-assisted procedural review;
- rubric assessment;
- draft GitHub feedback;
- identification of uncertainties;
- instructor review.

### Monday

Instructor-led team assessment / Q&A.

Questions target aspects that cannot confidently be established from repository
evidence.

This provides an opportunity to examine:

- understanding;
- awareness of teammates' work;
- engineering reasoning;
- validation;
- ownership of AI-assisted work.

### Following module

Lessons from the previous assessment cycle can modify the toolkit.

This produces six iterations of the assessment framework during an authentic
course deployment.

## Potential research questions

1. What evidence of engineering teamwork can be extracted from GitHub workflows?

2. How can quantitative repository indicators and qualitative AI-assisted
   review be combined without reducing teamwork to activity counts?

3. Which assessment tasks can be reliably delegated to an AI agent, and which
   require instructor judgment?

4. Can repository evidence help instructors formulate more targeted oral
   assessment questions?

5. Where does oral assessment reveal understanding or contribution that was not
   visible through GitHub?

6. How much instructor effort is required to validate and correct AI-generated
   assessments and feedback?

7. How does the framework evolve over repeated assessment cycles?

## Important conceptual distinction

This is not an AI-detection framework.

AI use is part of the educational environment.

The relevant learning question is whether students understand, evaluate,
validate and take responsibility for work produced with these tools.

## Possible methodological framing

The development of the toolkit occurs iteratively during authentic teaching.

A possible framing is design-based research / educational design research,
subject to a more thorough review of the appropriate methodology literature.

Each module provides:

design → deployment → observation → instructor validation → reflection →
revision.

Do not settle on the methodological label until the literature has been
reviewed.

## Evidence worth collecting

During each module record:

- approximate instructor review time;
- automated analysis time;
- number/type of generated comments;
- comments accepted unchanged;
- comments edited;
- comments rejected;
- false or misleading agent findings;
- rubric criteria that were easy/hard to automate;
- questions generated for Monday;
- whether those questions proved useful;
- discrepancies between repository inference and oral evidence;
- changes made to the toolkit afterward.

Consider appropriate research ethics/consent requirements before using
identifiable student data for research.

## Relationship to previous work

Connect this work explicitly to previous work on:

- CDIO;
- flipped classroom;
- team-based learning;
- authentic engineering practice;
- GitHub workflows;
- pull-request-based assessment.

The new contribution is not merely using pull requests for feedback.

It is a broader evidence and assessment framework spanning the observable
engineering workflow, augmented by AI-assisted review and instructor
validation.

## Potential contribution

A publishable contribution could include:

1. the pedagogical/evidence framework;
2. the open-source CDIO Review Kit;
3. collaboration and issue-health metrics;
4. the human–AI assessment workflow;
5. observations from six iterative deployments;
6. comparison between repository-derived evidence and oral instructor
   assessment;
7. practical guidance for instructors adopting the approach.

## Claims to avoid without evidence

Do not claim that:

- GitHub activity measures contribution directly;
- AI can grade teamwork autonomously;
- commit counts measure learning;
- repository evidence reveals everything a student understands;
- the system detects inappropriate AI use.

The value of the framework may instead be its ability to organize evidence,
direct instructor attention and make otherwise impractical process assessment
more scalable.
