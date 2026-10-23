# Evidence guide: where proof lives in a reproduction package

<!--
THIS IS THE PART YOU WRITE (new this week: Unit 1 handed you this file
finished; the scaffolding fades). The skill uses this guide as its map:
for every kind of proof a rubric check names, this file says WHERE to
find it in a package and WHAT GOOD LOOKS LIKE when you do.

Under each family heading below, write:

- Where it lives: the exact places to look. In an eval bundle (which
  section of the package: the issue context, the repo-facts block, the
  claim comment, the repro report and its parts). In live mode (where
  on GitHub or in the draft: the issue thread, the repo's docs, the
  student's draft comment).
- What good looks like: one or two sentences someone else could apply.
  Prefer observable conditions ("the versions named match what the
  issue targets, or the difference is called out") over adjectives
  ("environment is thorough").

A rubric check whose evidence this guide cannot locate is a check
nobody else can execute; the rubric swap showed you what that feels
like. Write the map you wish your grader had.
-->

## Environment

<!-- Where the environment record lives, and what a sufficient one
looks like against the issue's stated target. -->

**Where it lives:** Eval mode: the environment section of the repro report, compared with the version the issue's context names. Live mode: the environment lines in the draft report, compared with the issue thread.
**What good looks like:** OS, runtime version, repo commit or version, and install method are named, and they match what the issue targets, or the difference is called out.


## Steps

<!-- Where the reproduction steps live, and what makes them followable
by a stranger, starting state to trigger. -->

**Where it lives:** Eval mode: the numbered or listed commands in the repro report. Live mode: the steps in the draft report.
**What good looks like:** Starting from a clean checkout, each command can be run in order with no missing file, input, or setup, and the last step triggers the behavior.


## Behavior shown

<!-- Where the artifacts live (output excerpts, logs, screenshots),
and what it means for an artifact to show the issue's behavior rather
than an adjacent one. -->

**Where it lives:** Eval mode: the output excerpts, logs, or screenshots in the repro report, read against the issue's description. Live mode: the same artifacts in the draft.
**What good looks like:** The excerpt shows the same error or symptom the issue names, not an adjacent one. An artifact that shows a different failure fails this even if it looks convincing.


## Honesty

<!-- Where claims and their backing meet: how to tell a report that
says exactly what happened (including an honest cannot-reproduce) from
one that claims more than its evidence shows. -->

**Where it lives:** Eval mode: the report's conclusion read against its own artifacts. Live mode: the conclusion in the draft against the pasted output.
**What good looks like:** The stated outcome is exactly what the evidence shows. An evidenced cannot-reproduce is honest. A claim of reproduction, or of a root cause, with no matching artifact is not.


## Comms

<!-- Where the words meet the repo: the claim comment against the
issue, the comments against the repo's stated templates and
contribution policy (including AI-use disclosure requirements), and
what specific-and-honest looks like next to boilerplate. -->

**Where it lives:** Eval mode: the claim comment and repro comment, read against the issue thread and the repo-facts block (contribution policy, templates, AI-use rules). Live mode: the draft comments against the repo's docs and the issue thread.
**What good looks like:** The claim names the issue's specifics and promises only an investigation. Every requirement the repo states is met, including AI-use disclosure when required. Proof is in the author's own words, not "same as above".

