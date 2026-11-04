# Contribution: API docs don't include example `curl` commands

Path: `beat-2-contribution/contribution-story.md`

This file is Assignment 5, and it is graded at the path above; a copy kept anywhere else in
the repository is not read. **Keep every section header below under its exact name** — the
format criteria grade exactly that. Your course repo link is the whole submission: no tool
files and no evidence uploads are part of Assignment 5.

**Contribution Number:** 1
**Student:** Aishwarya Niroula
**GitHub Username:** AishNiroula
**Issue:** https://github.com/ascherj/pathreview/issues/117
**Pull Request:** [GitHub PR link, once opened]

One repository, built across units 5 to 8, telling the whole story of your real
contribution. Fill it as you work, not at the end — the sections below ask for evidence that
is far easier to write down as it happens than to reconstruct in the last weekend.

Contribution Number stays `[1]` unless you make more than one contribution this term; it
just numbers them.

---

## Toolkit

Every story section below, from Why I Chose This Issue through Pull
Request, ends with a Toolkit block: which tool did that phase's work
and how you used it, what it produced, what difficulties or
shortcomings it presented, and what you changed or would change
because of them. Together the blocks are the thread the rubric's
Toolkit points read, and they are the raw material for your unit-9
portfolio, so keep them current as you work rather than
reconstructing them later.

A Toolkit block looks like this (copy it into each story section and
fill it there):

```text
**Toolkit**

- Tool: [which tool did this phase's work, and how you used it]
- What it produced: [described in a sentence or a short excerpt]
- Difficulties: [what fought you or fell short, or "none met"]
- What changed: [the patch, revision, or workaround, what you would
  update, or "nothing"]
```

This section also keeps one short dated entry per week of tool work,
starting below: what you built or changed that week, what broke, and
what you changed because of it. The blocks tell the story where it
happened; these entries are the toolkit's own timeline.

All four entries are graded. Keep every heading below, and fill each
one in the week it belongs to.

**Unit 5: [one line on the tool work]**

[2-4 sentences: what you built (the scout, your strategy), what broke
or fell short, what changed because of it.]

**Unit 6: [one line on the tool work]**

[TODO: 2-4 sentences, only once true: the voice guard and repo memory
file. Known so far: Claude Code refused to start with "Your
organization has disabled Claude subscription access for Claude Code",
so the guard's wiring test could not run until an API key was set up.]

**Unit 7: [one line on the tool work]**

[2-4 sentences: the ship-gate and your gate manifest. What it produced
on your real branch, what fought you, what changed because of it.]

**Unit 8: [one line on the tool work]**

[2-4 sentences: the PR-monitor and your playbook. What it read, what it
drafted, what you did with the draft.]

---

## Why I Chose This Issue

Issue #117 asks for example `curl` commands in `docs/API.md`, which
describes each endpoint but shows no example invocations, so a developer
setting the project up for the first time can't quickly check that the
API works. It is labeled docs, good first issue and tier-1, names the one
file involved, and estimates 2-3 hours, so by my own reading it is
bounded work. [TODO: where you found it, which issues your scout graded,
and what its verdict and difficulty note said about this one.] [TODO: why
it fits you and what you hope to learn.] [TODO: an honest read of how
your scout did.]

Two things I noticed on the thread: many people had already asked to work
on this issue, and the repository is archived and read-only, so a pull
request can't be opened against it. [TODO: say how that affects your
plan.]

**Claim comment:** I commented on this issue on Jul 13, 2026: [TODO: paste
the link to YOUR comment, via ... then Copy link; not someone else's]

**Toolkit**

- Tool: issue-scout, with my search strategy and rubric
- What it produced: [TODO: the scan and its verdict on this issue]
- Difficulties: [TODO: where it fell short, or "none met"]
- What changed: [TODO: the scope-check patch, or "nothing"]

---

## Understanding the Issue

**Problem Description**

`docs/API.md` describes each endpoint but has no example invocations, so
someone setting the project up can't quickly verify the API is working.

**Expected Behavior**

Each documented endpoint has a copy-pasteable `curl` example that works
against a local dev server.

**Current Behavior**

The endpoints are described in prose with no example commands.

**Affected Components**

`docs/API.md`. [TODO: add the server or route files you check the
examples against.]

**Toolkit**

- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Reproduction Process

**Environment Setup**

[TODO: your OS, versions, and how you set the project up.]

**Steps to Reproduce**

1. Clone the repo and open `docs/API.md`.
2. Run `grep -c curl docs/API.md`.
3. Observed: [TODO: your actual result; the issue says there are no examples.]

**Reproduction Evidence**

- **Commit showing reproduction:** [TODO: link, or "none"]
- **Screenshots/logs:** [TODO: your grep output]
- **My findings:** [TODO: what you actually found]

**Toolkit**

- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Solution Approach

**Analysis**

[Your analysis of the root cause: what is causing the issue, traced
to the files and functions involved.]

**Proposed Solution**

[High-level description of your fix approach, and what you are
deliberately NOT changing.]

**Implementation Plan**

1. [Modify file X to do Y]
2. [Add or change Z]
3. [Update tests]

[Record deviations here as they happen: what changed mid-build and
why. A recorded deviation is honest work; silent drift is not.]

**Toolkit**

- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Testing Strategy

[What observable checks prove the fix: your reproduction steps re-run
against the built change (before and after), and the repo's own test
suite or checks with the outcome shown. "Tests pass" with nothing
observable named is not a strategy.]

**Toolkit**

- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Implementation Notes

[A running log, added to as you work. Date each entry. What you
built, decisions you made when you made them, wrong turns included.]

**[Date]**

[Entry]

**[Date]**

[Entry]

**Toolkit**

- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Pull Request

**PR Link:** [GitHub PR URL when opened]

**PR Description:** [what the PR says; much of the content above
adapts into it]

**Maintainer Feedback:**

- [Date]: [feedback received, or "none yet"; silence is a normal
  state and costs you nothing]
- [Date]: [how you addressed it]

**Status:** [Awaiting review / Iterating / Merged / Closed. The
status is a fact you record, never a grade: the PR is graded as
opened.]

**Toolkit**

- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Learnings and Reflections

**Technical Skills Gained**

[What you learned technically, named concretely.]

**Challenges Overcome**

[What was hard and how you solved it; point at the real events, the
Toolkit blocks above are full of them.]

**What I'd Do Differently Next Time**

[Reflection on your process.]

---

## Resources Used

[What actually helped, not a reading list. List things this story
already shows you using: the doc you followed to set the environment
up, the thread that explained the bug, the person who answered you.
One real entry beats ten plausible ones.]

- [Link to documentation that helped]
- [Discussion, issue, or post that helped]
