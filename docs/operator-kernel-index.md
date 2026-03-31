# Operator Kernel Index

Status: active
Date: 2026-03-30

## What this is
This file is the front door for the operator kernel inside TendrilGPT.
It exists so future sessions can resume from durable state instead of depending on chat memory.

## Core files
### `docs/live-operational-state.md`
Defines where execution lives and what the current operational center is.

### `docs/operator-agency-doctrine.md`
Defines behavior, boundaries, and intervention levels.

### `docs/lightweight-operating-loop.md`
Defines the smallest repeatable loop from signal to action.

## Recommended read order
1. `docs/operator-kernel-index.md`
2. `docs/live-operational-state.md`
3. `docs/operator-agency-doctrine.md`
4. `docs/lightweight-operating-loop.md`

## Current active lane
Broad operator-agency buildout for flexible OpenClaw-style experimentation.

## Current operating split
- GitHub = execution layer
- Google Doc = slow-thinking layer
- Notion = map and priorities

## Still missing
- experiment template
- signal log template
- active lane tracker
- concise resume format
- issue registry when tooling allows

## Resume instruction
Start from this file, then read the execution anchor, then the doctrine, then the loop.
After that, identify the current bottleneck, make the smallest meaningful move, and record only what improves continuity.
