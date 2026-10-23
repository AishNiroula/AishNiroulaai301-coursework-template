# repro-check

A Claude Code skill that grades whether a reproduction package (claim comment + repro report) is ready to post on an upstream issue. It ends with a JSON verdict: accept or reject.

## Files

- SKILL.md: the skill's instructions for Claude
- scope.md: which repo the skill grades against
- rubric.md: my checks table and verdict rule
- references/evidence-guide.md: where each kind of proof lives in a package
- voice-guide.md: my rules for how I write comments upstream

## Checks

environment_recorded, steps_followable, behavior_matches_issue, outcome_honest, claim_specific, conventions_followed, no_piggyback (preferred).

Verdict rule: accept if every required check passes; unclear counts as fail.

## How to run

Copy this folder to ~/.claude/skills/repro-check/, set the Repo: line in scope.md, then:

claude "repro-check: grade my draft claim comment in claim.md for issue <URL>"
