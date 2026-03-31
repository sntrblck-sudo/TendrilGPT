# Lightweight Operating Loop

Status: active
Date: 2026-03-30

## Purpose
This file defines the smallest repeatable operating loop for the operator stack.
It should be simple enough to run often, safe enough to run by default in low-risk domains, and structured enough to create continuity over time.

## Loop shape
1. Notice signal
2. Distill signal
3. Decide whether it deserves promotion
4. Make the smallest meaningful move
5. Record outcome if it should persist

## Trigger sources
Signals may come from:
- active chats
- durable notes
- experiment outputs
- automations or scheduled summaries
- repo state
- user requests
- recurring patterns observed across discussions

## Intake rule
Do not treat every input as important.
A signal should enter the loop only if it appears to be at least one of the following:
- actionable
- durable
- high-signal
- structurally useful
- likely to compound later
- a repeated tension, bottleneck, or opportunity

Ignore or down-rank:
- passing novelty
- one-off chatter with no follow-through value
- decorative ideas with no operational consequence
- duplicate observations that do not add clarity

## Distillation rule
When a signal enters the loop, reduce it to a compact form:
- what happened
- why it matters
- whether it is only interesting or actually actionable
- what the smallest useful next move would be

Preferred outputs:
- a short note
- a clear proposal
- a repo-side doc change
- a GitHub work item or implementation stub

## Promotion threshold
Promote a signal into GitHub-side work when at least one is true:
- it changes system structure
- it creates or modifies durable operating behavior
- it affects implementation
- it should be tracked beyond a single chat
- it clarifies an active lane or removes ambiguity

Keep it in notes only when it is:
- exploratory but not yet concrete
- architectural but not implementation-ready
- reflective with no immediate action attached

## Smallest meaningful move rule
When acting, prefer the smallest move that meaningfully improves the system.
Examples:
- add a doctrine note
- create a scaffold file
- define a template
- clarify one active lane
- convert a fuzzy idea into a named work item

Avoid jumping directly to:
- complex automation
- sprawling structure
- multi-step overbuild
- irreversible cleanup
- changes whose consequences are not well understood

## Reflection / logging rule
Record the result only when it improves future continuity.
Good reasons to log:
- a durable decision was made
- a new operating rule was added
- an experiment produced a lesson
- a pattern repeated enough to matter
- the stack changed shape in a meaningful way

Do not log everything.
The goal is continuity, not exhaust.

## Stop conditions
Pause the loop or require explicit operator direction when:
- protected domains are touched
- uncertainty is high and consequences are real
- the next move would affect money, accounts, external messaging, or sensitive information
- the loop starts generating busywork instead of clarity
- the system is preserving too much low-value material

## Safe actions by default
Usually safe:
- refining docs
- adding internal scaffolds
- reorganizing low-risk notes
- surfacing patterns
- clarifying priorities
- preserving compact durable insight

Usually not safe without explicit direction:
- sending outside messages
- deleting valuable state
- spending money
- changing account settings
- exposing personal information
- making commitments on the user’s behalf

## Example mini-loop
Signal:
There is a repeated need to resume from durable state rather than chat memory.

Distillation:
This matters because continuity is becoming part of the system’s real operating behavior.

Promotion decision:
Yes — this affects system structure and should persist beyond a single chat.

Smallest meaningful move:
Add or update a durable repo note that defines live session state and the current operator kernel.

Reflection:
Log only the resulting durable structure, not every intermediate thought.

## Final rule
The loop exists to turn signal into coherent, low-risk progress.
If the loop is creating motion without increasing clarity, shrink it.
