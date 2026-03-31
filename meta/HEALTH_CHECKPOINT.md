# Health Checkpoint

This file defines the minimal recurring health checkpoint for the TendrilGPT operating stack.

## Purpose

Give restore, healing, and execution sweeps a stable pass/fail standard.

## When to use

Use at:
- daily or active-session review
- recovery after interruption
- periodic healing sweeps
- moments when the system feels active but unclear

## Pass / fail criteria

### PASS
- there is a clear current execution surface in GitHub
- the next concrete move is identifiable
- active work is not trapped only in chat, Docs, or Notion
- recovery state is understandable from durable artifacts
- no obvious duplicate or conflicting active structures exist

### SOFT FAIL
- priorities exist but no concrete repo move is active
- the queue exists but has not advanced
- recovery logic exists but recent actions are not logged
- status is understandable only by rereading chat

### HARD FAIL
- implementation-bearing work has no durable repo home
- interruption erased the next move
- repeated retries risk duplicating side effects
- control layers disagree about what is current
- recovery requires improvisation rather than checkpointed resumption

## Minimal checkpoint template

- Date:
- Checkpoint type: daily / recovery / healing / weekly
- Current execution surface:
- Current active item:
- Last durable checkpoint:
- Health result: pass / soft fail / hard fail
- Smallest corrective move:
- Artifact created or updated:
- Notes:

## Correction rule

If the result is soft fail or hard fail, take the smallest safe corrective move that restores clarity or execution.
Do not respond with broad restructuring unless the failure is structural.

## Current expected baseline

A healthy baseline currently includes:
- `docs/REPO_LIVE_STATE.md`
- `docs/RECOVERY_DRILL.md`
- `meta/RECOVERY_LOG.md`
- `meta/ACTIVE_QUEUE.md`
- `meta/EXECUTION_RHYTHM.md`
- `meta/HEALTH_CHECKPOINT.md`

## Next move

Use this checkpoint to promote one non-recovery operational task into the repo so the system proves forward motion beyond self-maintenance.
