# Rubric: is this reproduction package ready to post?

<!--
THIS IS THE PART YOU WRITE. The skill in SKILL.md executes whatever
checks you define here. It ships empty on purpose: the judgment is your
work.

A filled rubric must contain:

1. At least one row in the checks table. Each row needs all four
   columns:
   - Check: a short name (used in the output JSON).
   - Evidence: exactly what to look at, and where in the package. Name
     the part (the claim comment, the repro report's environment
     record, the artifacts read against the issue's description, the
     repo-facts block) or a location from your
     references/evidence-guide.md. "The report" is not a source; "the
     output excerpt read against the error the issue describes" is.
   - Pass condition: a decision rule about the OUTCOME that someone
     else could apply and get your answer. Judge the thing itself (does
     the artifact show the issue's behavior?), never the write-up's
     shape (how many steps it has, how long it is, whether it uses a
     template's headings). Structure-shaped checks are what make
     graders disagree with themselves.
   - Weight: `required` (a fail here holds the package) or `preferred`
     (never changes the verdict).

2. A verdict rule below the table: how the check grades combine into
   accept (ready) or reject (hold), including how `unclear` is
   treated. The verdict space is binary. If you write no rule for
   `unclear`, the skill treats it as fail.

Cover what actually gets bad packages posted. The lecture named the
proof families: the environment is recorded, the steps are complete
and followable, the behavior shown matches the issue (not an adjacent
one), the outcome is stated honestly (an evidenced cannot-reproduce is
a pass, a confident wrong-target is not), and the words respect the
repo's conventions. A rubric that ignores a family will fail eval
packages designed around that family.
-->

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
| environment_recorded | The environment record in the repro report (OS, language/runtime version, repo commit or version, install method), read against the version the issue targets | Pass if the report names the runtime and repo version actually used and they match the issue's target, or the report calls out the difference. Fail if the environment is missing, vague ("latest"), or silently differs from the issue's target. | required |
| steps_followable | The commands or actions in the repro report, read from starting state to trigger | Pass if a stranger could run them in order from a clean checkout and reach the trigger without guessing a missing command, file, or input. Fail if a step is missing or relies on unstated setup. | required |
| behavior_matches_issue | The output, log, or screenshot excerpt in the report, read against the exact error or behavior the issue describes | Pass if the excerpt shows the same behavior the issue describes (same error, same symptom). Fail if it shows an adjacent or different behavior, or no artifact is shown. | required |
| outcome_honest | The report's stated outcome read against its own evidence | Pass if the claim is exactly what the evidence supports. An evidenced cannot-reproduce passes. Fail if it claims reproduction or a root cause the evidence does not show. | required |
| claim_specific | The claim comment read against the issue thread | Pass if the claim names the issue's specifics and promises only an investigation and a report, never a fix or a date. Fail if it is boilerplate or promises a fix or timeline. | required |
| conventions_followed | The comments read against the repo-facts block (contribution policy, templates, AI-use rules) | Pass if every requirement the repo states for comments is met, including AI-use disclosure when the policy requires it. Fail if a stated requirement is skipped, such as no disclosure where one is required. | required |
| no_piggyback | The repro comment read against other comments in the thread | Pass if the proof is in the author's own words and own output. Fail if it only agrees with someone else's reproduction ("same as above, can confirm"). | preferred |

## Verdict rule

<!-- State how the grades above combine into accept or reject, and how
unclear is treated. Example shape (write your own): "accept if every
required check passes; preferred checks never change the verdict;
unclear counts as fail." -->

Accept if every required check passes. Preferred checks never change
the verdict. An unclear grade on a required check counts as a fail,
because a package a grader cannot verify is not ready to post.
