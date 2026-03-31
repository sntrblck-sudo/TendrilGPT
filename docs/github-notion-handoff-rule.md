# GitHub ↔ Notion handoff rule

This note formalizes the working split between GitHub and Notion inside TendrilGPT.

## Purpose

Keep research, planning, and implementation from bleeding into each other.

## Rule

- Keep **Notion** as the intent and decision layer.
- Move implementation-bearing work into **GitHub** once it becomes concrete.
- After meaningful GitHub progress, write back one short status note in Notion instead of duplicating the full technical record.

## Use Notion for

- why the work matters
- scope and constraints
- acceptance shape
- next best move
- short progress reflection

## Use GitHub for

- code and scripts
- issues and implementation tasks
- branches and pull requests
- technical traceability
- repo-facing documentation tied to the codebase

## Trigger to hand off from Notion to GitHub

Move the work when any of the following becomes true:

- a concrete file or script needs to change
- a repo task can be named clearly
- the work needs a branch, issue, or PR
- technical traceability matters more than conceptual explanation

## Write-back rule

After meaningful implementation progress, return to Notion with one short note:

- what changed
- what remains
- next best move

## Anti-drift rule

Do not keep full implementation detail in Notion once GitHub is the real source of truth.

## Style rule

Keep changes small, legible, and reversible.