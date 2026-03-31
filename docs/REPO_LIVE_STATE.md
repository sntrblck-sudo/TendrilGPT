# Repo Live State

This file formalizes TendrilGPT as the live execution layer of the operating stack.

## Role in the stack

- **GitHub** = live execution layer
- **Google Docs** = slow-thinking layer for doctrine, architecture, and durable reflections
- **Notion** = map, current priorities, and connective tissue

## Why this file exists

The operating split was already defined, but the repo needed an explicit anchor that turns that split into an actionable rule.

## Live-state rule

When work becomes concrete enough to change a file, define a workflow, track a technical follow-through, or create an implementation artifact, it should move into this repository rather than remaining only in chat, Docs, or Notion.

## Minimal bridge protocol

1. Think in chat.
2. Distill durable doctrine into Google Docs or Notion.
3. When a change becomes executable, promote it into GitHub as one of:
   - a file change
   - a script
   - a tracked repo doc
   - a branch or pull request
4. Feed the outcome back into Docs or Notion only as a concise status or lesson.

## Recovery rule

After interruption, resume from the last confirmed durable checkpoint.
Do not repeat side effects blindly.
Write a short recovery note when a task stops mid-stream.

## Healthy state

The stack is healthy when:

- active implementation work has a repo home
- doctrine remains readable and selective
- Notion reflects current priorities without becoming the execution layer
- automations reduce drift instead of adding noise
- recovery after interruption is defined, not improvised

## Immediate operating consequence

The next implementation-bearing work item should be created in GitHub first, then referenced back into Docs or Notion.
