# Experiments Workspace Guide

Status: active
Date: 2026-03-30

## Purpose
This folder is the durable landing zone for bounded experiments.
An experiment should exist to learn something, test a structure, reduce uncertainty, or clarify whether a direction deserves promotion.

## What belongs here
Use this folder for experiments that are:
- bounded
- low-risk
- legible
- useful for continuity, survivability, capability, or clarity
- small enough to run without overbuilding

Examples:
- testing a new operating loop
- checking whether a template improves reuse
- evaluating a small structural change
- trialing a signal-capture pattern
- validating whether a repeated idea is actually useful

## What does not belong here
Do not use this folder for:
- vague intentions with no test shape
- sprawling projects pretending to be experiments
- irreversible changes
- busywork that produces no lesson
- duplicate tests that add no new information

## Suggested use
When an experiment deserves durable capture:
1. start from `templates/experiment-entry.md`
2. create a compact experiment note in this folder
3. preserve the lesson, not every intermediate detail
4. promote the result into docs or implementation work only if it meaningfully changes the operating picture

## Naming guidance
Prefer short, legible names.
Examples:
- `resume-format-test.md`
- `signal-threshold-check.md`
- `active-lane-tracker-usefulness.md`

## Folder rule
This folder should prefer clarity over volume.
If experiments are accumulating without yielding lessons or structural improvement, the bar for running them is too low.
