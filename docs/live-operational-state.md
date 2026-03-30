# Formalize TendrilGPT as live operational state

Status: proposed
Date: 2026-03-30

## Intent
Confirm `sntrblck-sudo/TendrilGPT` as the active execution repo for the current operator-agency buildout.

## Operating split
- GitHub = execution layer, files, changes, branches, PRs, implementation work
- Google Doc = doctrine, architecture snapshots, durable notes, reflections
- Notion = map, active priorities, bridge/index

## Durable anchors
- Google Doc: `Nova / OpenClaw Operating Notes`
- Notion: `Active priorities: current operating picture`
- Notion: `Integration note: GitHub + Docs operating bridge`

## Acceptance criteria
- [ ] TendrilGPT is explicitly named as the live operational state
- [ ] Cross-links to the Google Doc and Notion bridge are preserved in repo notes
- [ ] The first concrete upgrade lanes are named and scoped
- [ ] Future implementation-bearing work is promoted into GitHub rather than left only in chat

## First concrete upgrade lanes
1. Doctrine hardening
   - Add a durable operator-agency note in `docs/`
   - Keep role boundaries and intervention thresholds legible

2. Lightweight autonomy loop scaffolding
   - Define a minimal safe loop for capture -> distill -> act -> reflect
   - Keep actions reversible and low-risk by default

3. Experiment / signal structure
   - Add simple folders or templates for experiments, signals, and reusable prompts
   - Prefer small durable structure over broad abstract planning

## Suggested follow-through
- Convert this file into a GitHub issue when issue creation is available
- Optionally add repo links back to the Google Doc and Notion pages
