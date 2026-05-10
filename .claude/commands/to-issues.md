---
name: to-issues
description: Break a plan, spec, or PRD into independently-grabbable issues on the project issue tracker using tracer-bullet vertical slices. Use when user wants to convert a plan into issues, create implementation tickets, or break down work into issues.
---

# To Issues

Break a plan into independently-grabbable vertical slices.

Run `/setup-matt-pocock-skills` if issue tracker / label vocabulary hasn't been provided.

## Vertical slice rules

- Each slice delivers a narrow but COMPLETE path through every layer
- A completed slice is demoable or verifiable on its own
- Prefer many thin slices over few thick ones
- HITL = human interaction required; AFK = agent can complete autonomously

## Process

1. Gather context from conversation + any referenced issue
2. Explore codebase if needed; use domain glossary
3. Draft slices with Title / Type / Blocked by / User stories
4. Quiz user on granularity and dependencies
5. Publish issues in dependency order with `ready-for-agent` label
