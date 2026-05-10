---
name: prototype
description: Build a throwaway prototype to flush out a design before committing to it. Routes between two branches — a runnable terminal app for state/business-logic questions, or several radically different UI variations toggleable from one route. Use when the user wants to prototype, sanity-check a data model or state machine, mock up a UI, explore design options, or says "prototype this", "let me play with it", "try a few designs".
---

# Prototype

Throwaway code that answers a question. Pick the right branch:

- **Logic question** → tiny interactive terminal app
- **UI question** → multiple variants on one route, switchable via URL param

## Rules

1. Clearly marked as throwaway
2. One command to run
3. No persistence (state in memory)
4. No polish — no tests, no error handling beyond runnable
5. Surface the full state after every action
6. Delete or absorb when done — capture the *answer* in a commit message, ADR, or issue
