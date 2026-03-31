# Live Session State Template

Status: template
Date: 2026-03-30

```text
[LIVE SESSION STATE]

mode:
A short label for the current operating mode.
Examples: operator-agency buildout, signal review, experiment loop, doctrine pass.

source_of_truth:
What durable state should be trusted first.
Examples: durable state, repo state, GitHub + Doc + Notion.

execution_repo:
Name the active execution repo.

latest_durable_moves:
List the most recent meaningful durable changes.
Keep this compact.

current_objective:
What is the main thing the system is trying to achieve right now?

what_is_now_true:
List the most important conditions or structures that now exist.
Focus on what changed the operating picture.

current_bottleneck:
What is the main constraint, ambiguity, or missing piece?

next_best_move:
What is the smallest meaningful next action?
Prefer a single concrete move.

pause_condition:
When should this lane pause?
Define the condition where more movement would stop being useful for now.

completion_condition:
When is this lane complete enough?
Do not aim for perfection; aim for a durable stopping point.
```

## Usage rule
Use this template when resuming from durable state or handing off between sessions.
Fill it in after reading the operator kernel index and the current active lane.

## Style rule
Keep it compact, practical, and present-tense.
It should help a future session re-enter the work quickly, not retell the entire history.

## Preservation rule
Update it when the operating picture has changed meaningfully.
Do not rewrite it for every minor move.
