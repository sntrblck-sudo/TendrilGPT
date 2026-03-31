# Maintenance Rule

Status: active
Date: 2026-03-30

## Purpose
This file defines when the operator workspace should be updated and when it should be left alone.
The goal is to preserve continuity without turning the repo into clutter or exhaust.

## Core rule
Update durable state only when the operating picture has changed meaningfully.
Do not update files merely to reflect motion, effort, or minor progress.

## Update `docs/active-lane.md` when
- the main lane changes
- the current bottleneck changes materially
- the next best move changes materially
- the lane reaches a pause condition
- the lane reaches a completion condition

Do not update it for every small sub-step inside the same lane.

## Create a signal entry when
- a pattern repeats enough to matter
- an observation changes how the system should behave
- a tension, bottleneck, or opportunity appears durable
- something is worth preserving even if no immediate action follows

Do not create a signal entry for passing novelty, chatter, or one-off fragments.

## Create an experiment entry when
- something is being tested, not merely discussed
- there is a bounded question
- the test has constraints and can produce a lesson
- the result could change structure, behavior, or future decisions

Do not log vague intentions as experiments.

## Update live session state when
- the current objective changes
- the operating picture changes materially
- several meaningful durable moves have accumulated
- the bottleneck or next best move changes in a way a future session would need to know

Do not rewrite live session state after every minor commit.

## Update doctrine or loop files when
- a real lesson changes operating behavior
- a boundary, intervention threshold, or core rule becomes clearer
- repeated use shows the existing rule is wrong, incomplete, or too vague

Do not rewrite doctrine for style alone.

## Stop preserving when
- the material is repetitive
- the material does not improve future continuity
- the material does not affect behavior, structure, or understanding
- the workspace starts reflecting exhaust instead of signal

## Preferred rhythm
1. notice signal
2. decide if it deserves durable capture
3. make the smallest meaningful move
4. record only what a future session would actually benefit from

## Final rule
The workspace should become more legible over time, not merely larger.
