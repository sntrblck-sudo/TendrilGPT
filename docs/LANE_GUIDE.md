# Lane Guide

This file explains where things should go inside TendrilGPT.

It exists to reduce hesitation and prevent drift.
If something is worth saving, this guide should make its destination more obvious.

---

## `signals/`

Use this lane for:
- notable things surfaced over time
- observations that feel shaping, recurrent, or strategically useful
- moments that may matter later even if they are not yet actionable

Do not use this lane for:
- every interesting thought
- raw news accumulation
- vague mood logging

Question to ask:
Did this earn permanence as a signal?

---

## `experiments/`

Use this lane for:
- tests meant to reduce uncertainty
- small trials with a question, procedure, and outcome
- attempts to learn whether a direction is worth continuing

Do not use this lane for:
- general ideas without a test
- broad planning without a procedure

Question to ask:
Are we trying to learn something through a concrete test?

---

## `prompts/`

Use this lane for:
- prompts that repeatedly improve execution or thinking
- reusable instructions with a stable purpose
- prompts worth preserving beyond a single session

Do not use this lane for:
- one-off phrasing that only sounded nice once
- prompts that have not yet proven useful

Question to ask:
Has this prompt earned reuse?

---

## `docs/`

Use this lane for:
- doctrine
- operating notes
- structural guidance
- files that explain how TendrilGPT works

Do not use this lane for:
- everything that does not fit elsewhere
- temporary clutter

Question to ask:
Does this explain, govern, or stabilize the system?

---

## `meta/`

Use this lane for:
- identity notes
- recurring style observations
- taste, preferences, and relationship texture
- things that shape the character of the collaboration over time

Do not use this lane for:
- forced branding
- persona invention without evidence

Question to ask:
Has this become part of the system’s real feel or identity?

---

## Fast routing rule

If it is:
- notable -> `signals/`
- a test -> `experiments/`
- reusable wording -> `prompts/`
- structural guidance -> `docs/`
- identity or taste -> `meta/`

If none fit cleanly, it may not be ready to save yet.

---

## Rule

Do not save things just because they exist.
Save them when they clarify, strengthen, or extend the system.
