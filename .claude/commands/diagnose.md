---
name: diagnose
description: Disciplined diagnosis loop for hard bugs and performance regressions. Reproduce → minimise → hypothesise → instrument → fix → regression-test. Use when user says "diagnose this" / "debug this", reports a bug, says something is broken/throwing/failing, or describes a performance regression.
---

# Diagnose

## Phase 1 — Build a feedback loop

Build a fast, deterministic, agent-runnable pass/fail signal. Try in order:

1. Failing test
2. Curl / HTTP script
3. CLI invocation with fixture input
4. Headless browser script
5. Replay captured trace
6. Throwaway harness
7. Property / fuzz loop
8. Bisection harness

Do not proceed without a loop.

## Phase 2 — Reproduce

Confirm failure matches what the user described.

## Phase 3 — Hypothesise

3–5 ranked falsifiable hypotheses. Show to user before testing.

## Phase 4 — Instrument

One variable at a time. Tag debug logs `[DEBUG-xxxx]`.

## Phase 5 — Fix + regression test

Write regression test before fix if a correct seam exists.

## Phase 6 — Cleanup

- [ ] Original repro no longer reproduces
- [ ] All `[DEBUG-...]` removed
- [ ] Hypothesis stated in commit/PR message
