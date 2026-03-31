# Recovery Log

This file tracks concrete recovery and healing actions taken inside the TendrilGPT operating stack.

## Purpose

Create a minimal durable record of interruptions, corrective moves, and restored state.

## Entry format

### YYYY-MM-DD — short title
- Interrupted item:
- Last durable checkpoint:
- Failure class:
- Side effects already performed:
- Corrective move taken:
- Result:
- Next smallest move:

---

## Entries

### 2026-03-31 — anchor repo live-state bridge
- Interrupted item: repo-side execution bridge remained implied rather than explicitly anchored
- Last durable checkpoint: operating split already documented in README and Notion workflow notes
- Failure class: partially completed
- Side effects already performed: doctrine and routing guidance existed across README and Notion
- Corrective move taken: created `docs/REPO_LIVE_STATE.md`
- Result: restored
- Next smallest move: promote one implementation-bearing operational artifact into the repo

### 2026-03-31 — establish first recovery drill artifact
- Interrupted item: recovery/healing logic existed conceptually but not as a repo-tracked operating artifact
- Last durable checkpoint: `docs/REPO_LIVE_STATE.md`
- Failure class: partially completed
- Side effects already performed: automation for restore/healing sweep already existed
- Corrective move taken: created `docs/RECOVERY_DRILL.md`
- Result: restored
- Next smallest move: create a lightweight repo-native log for future recovery actions
