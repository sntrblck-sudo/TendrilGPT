# Recovery Drill

This is the first concrete repo-tracked follow-through under the repo live-state rule.

## Purpose

Turn recovery and healing from a vague intention into a repeatable operating behavior.

## Objective

When work stalls, breaks, or gets interrupted, resume from a durable checkpoint and restore a healthy state with minimal noise and minimal repeated side effects.

## Failure modes to watch

- task stops mid-stream
- implementation remains trapped in planning layers
- repo work is discussed but not promoted into GitHub
- automation exists without a clear repair target
- current priorities drift away from executable follow-through

## Healthy state checklist

A healthy state means:

- the latest concrete implementation step exists in GitHub
- recovery can identify the last durable checkpoint
- status can be reflected back into Notion without duplicating execution
- interruptions do not cause blind retries
- small corrective moves are preferred over broad resets

## Recovery drill

1. Identify the last confirmed durable checkpoint.
2. Classify the interruption:
   - stalled
   - broken
   - partially completed
   - blocked on approval
3. Check for side effects already performed.
4. Choose the smallest safe corrective move.
5. Record the result as one of:
   - restored
   - partially restored
   - blocked
   - superseded
6. Sync a concise status note back to the mapping layer.

## Recovery note template

- Date:
- Interrupted item:
- Last durable checkpoint:
- Failure class:
- Side effects already performed:
- Corrective move taken:
- Result:
- Next smallest move:

## First application

Current first application of this drill:
- bridge repo state into explicit live operation
- keep Notion as map rather than execution layer
- use GitHub first for the next implementation-bearing move

## Next implementation targets

1. Add a lightweight backlog file or issue-equivalent inside the repo.
2. Add a small status log for completed recovery actions.
3. Promote one additional active work item into repo-tracked execution.
