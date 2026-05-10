---
name: setup-matt-pocock-skills
description: Sets up an `## Agent skills` block in AGENTS.md/CLAUDE.md and `docs/agents/` so the engineering skills know this repo's issue tracker (GitHub or local markdown), triage label vocabulary, and domain doc layout. Run before first use of `to-issues`, `to-prd`, `triage`, `diagnose`, `tdd`, `improve-codebase-architecture`, or `zoom-out`.
disable-model-invocation: true
---

# Setup Matt Pocock's Skills

Scaffold per-repo config for the engineering skills.

## Process

1. Explore: check for `CLAUDE.md`/`AGENTS.md`, `docs/agents/`, `CONTEXT.md`, `docs/adr/`
2. Ask three questions one at a time:
   - **A**: Issue tracker (GitHub, GitLab, local markdown, other)
   - **B**: Triage label strings (defaults or custom)
   - **C**: Domain doc layout (single-context or multi-context)
3. Edit existing `CLAUDE.md` or `AGENTS.md`; append/update `## Agent skills` block
4. Write `docs/agents/issue-tracker.md`, `triage-labels.md`, `domain.md`
5. Tell user setup is complete
