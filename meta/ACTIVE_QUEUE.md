# Active Queue

This is the lightweight execution queue for implementation-bearing work in TendrilGPT.

## Purpose

Provide one repo-native place for the next concrete moves so active work enters execution cleanly.

## Queue rules

- Keep only a few items active at once.
- Prefer the smallest meaningful next move.
- When an item is completed, move the result into the repo and record recovery-relevant outcomes in `meta/RECOVERY_LOG.md` when appropriate.
- Do not duplicate long planning here; link or reference the relevant doctrine instead.

## Status labels

- queued
- in_progress
- blocked
- done
- superseded

## Current active items

### 1. Establish a minimal execution rhythm
- Status: queued
- Why it matters: turns the repo from a static archive into a living execution surface
- Smallest next move: create a simple cadence note or issue routine for promoting one concrete task at a time
- References: `docs/REPO_LIVE_STATE.md`, `docs/RECOVERY_DRILL.md`

### 2. Define one recurring health checkpoint format
- Status: queued
- Why it matters: makes healing sweeps easier to evaluate against a stable standard
- Smallest next move: add a tiny health-check template with pass/fail criteria
- References: `docs/RECOVERY_DRILL.md`, `meta/RECOVERY_LOG.md`

### 3. Promote one non-recovery operational task into the repo
- Status: queued
- Why it matters: proves the repo can hold forward-moving work, not just repair logic
- Smallest next move: choose one current priority and create its first concrete artifact in GitHub
- References: `meta/ACTIVE_QUEUE.md`

## Completion pattern

When closing an item:
1. mark status
2. note the concrete artifact created or updated
3. add a recovery log entry if the item involved interruption, healing, or state restoration
4. surface only a concise map update back into Notion
