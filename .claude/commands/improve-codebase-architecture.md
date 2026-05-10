---
name: improve-codebase-architecture
description: Find deepening opportunities in a codebase, informed by the domain language in CONTEXT.md and the decisions in docs/adr/. Use when the user wants to improve architecture, find refactoring opportunities, consolidate tightly-coupled modules, or make a codebase more testable and AI-navigable.
---

# Improve Codebase Architecture

Find **deepening opportunities** — refactors that turn shallow modules into deep ones.

**Deep module**: lots of behaviour behind a small interface.
**Deletion test**: if deleting the module concentrates complexity back into callers, it was earning its keep.

## Process

1. Read `CONTEXT.md` and ADRs first
2. Walk the codebase, note friction (shallow modules, hard-to-test seams, tightly-coupled callers)
3. Present numbered list of candidates with Problem / Solution / Benefits per item
4. User picks one → grilling loop → update `CONTEXT.md` inline
