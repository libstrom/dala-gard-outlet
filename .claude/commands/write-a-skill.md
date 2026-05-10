---
name: write-a-skill
description: Create new agent skills with proper structure, progressive disclosure, and bundled resources. Use when user wants to create, write, or build a new skill.
---

# Writing Skills

Create a `.md` file in `.claude/commands/` named after the command.

## Process

1. Gather requirements — task, use cases, scripts needed?
2. Draft the skill file
3. Review with user

## Template

```md
---
name: skill-name
description: What it does. Use when [triggers].
---

# Skill Name

[Instructions]
```

## Description rules

- Max 1024 chars, third person
- First sentence: capability
- Second sentence: "Use when [triggers]"

## Checklist

- [ ] Description has "Use when..."
- [ ] File concise
- [ ] Examples included
