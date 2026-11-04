# Contribution: API docs don't include example `curl` commands

**Contribution Number:** 2
**Student:** Aishwarya Niroula
**Issue:** https://github.com/ascherj/pathreview/issues/117
**Pull Request:** none (the repository is archived and read-only)

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

```
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

### Unit 5: [one line on the tool work]

[TODO: what you built (the scout, your strategy), what broke or fell
short, what changed because of it.]

### Unit 6: [one line on the tool work]

[TODO: the voice-guard and your voice guide. Known so far: Claude Code
refused to start with "Your organization has disabled Claude subscription
access for Claude Code", so the guard's wiring test could not run until
an API key was set up.]

### Unit 7: [one line on the tool work]

[TODO: the ship-gate and your manifest.]

### Unit 8: [one line on the tool work]

[TODO: the monitor: what it read, what it drafted, what you did with the
draft.]

---

## Why I Chose This Issue

Issue #117 asks for example `curl` commands in `docs/API.md`, which
describes each endpoint but shows no example invocations, so a developer
setting the project up for the first time can't quickly check that the
API works. It is labeled docs, good first issue and tier-1, names the one
file involved, and estimates 2-3 hours, so by my own reading it is
bounded work.

I commented on the issue on Jul 13, 2026, saying I wanted to work on it
and add `curl` examples for each documented endpoint. [TODO: paste the
link to YOUR comment.] Many other people also asked to work on it, and the
repository is archived and read-only, so no pull request can be opened.
That is why this is an extra round and not my graded contribution.

[TODO: where you found it, which issues your scout graded, what its
verdict and difficulty note said about this one, and an honest read of
how the scout did.]

**Toolkit**
- Tool: issue-scout (your scout: your search strategy, your rubric),
  and how you used it
- What it produced: [TODO: the scan and its verdict on this issue]
- Difficulties: [TODO: where it fell short, or "none met"]
- What changed: [TODO: what you patched or would update, or "nothing"]

---

## Understanding the Issue

### Problem Description

`docs/API.md` describes each endpoint but has no example invocations, so
someone setting the project up can't quickly verify the API is working.

### Expected Behavior

Each documented endpoint has a copy-pasteable `curl` example that works
against a local dev server.

### Current Behavior

The endpoints are described in prose with no example commands.

### Affected Components

`docs/API.md`. [TODO: add the server or route files you check the
examples against.]

**Toolkit**
- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Reproduction Process

### Environment Setup

[TODO: your OS, versions, and how you set the project up.]

### Steps to Reproduce

1. Clone the repo and open `docs/API.md`.
2. Run `grep -c curl docs/API.md`.
3. Observed: [TODO: your actual result; the issue says there are no
   examples.]

### Reproduction Evidence

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

### Analysis

[Your analysis of the root cause: what is causing the issue, traced
to the files and functions involved.]

### Proposed Solution

[High-level description of your fix approach, and what you are
deliberately NOT changing.]

### Implementation Plan

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

### [Date]

[Entry]

### [Date]

[Entry]

**Toolkit**
- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Pull Request

**PR Link:** none, the repository is archived and read-only

**PR Description:** [not applicable]

**Maintainer Feedback:**

- [Date]: [feedback received, or "none yet"]

**Status:** Closed: no PR possible

**Toolkit**
- Tool:
- What it produced:
- Difficulties:
- What changed:

---

## Learnings and Reflections

### Technical Skills Gained

[What you learned technically, named concretely.]

### Challenges Overcome

[What was hard and how you solved it; point at the real events, the
Toolkit blocks above are full of them.]

### What I'd Do Differently Next Time

[Reflection on your process.]

---

## Resources Used

- https://github.com/ascherj/pathreview/issues/117
