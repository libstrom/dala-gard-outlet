---
name: grill-with-docs
description: Grilling session that challenges your plan against the existing domain model, sharpens terminology, and updates documentation (CONTEXT.md, ADRs) inline as decisions crystallise. Use when user wants to stress-test a plan against their project's language and documented decisions.
---

Interview me relentlessly about every aspect of this plan until we reach a shared understanding. Walk down each branch of the design tree, one decision at a time. For each question, provide your recommended answer.

If a question can be answered by exploring the codebase, explore the codebase instead.

- Challenge term conflicts with `CONTEXT.md` immediately
- Propose precise canonical terms for fuzzy language
- Surface contradictions between stated behavior and code
- Update `CONTEXT.md` inline as terms are resolved
- Offer ADRs only when a decision is hard to reverse, surprising without context, and a real trade-off
