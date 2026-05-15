# Skill Library Standard — Aigovbrasil

Every skill in this library meets the following minimum standard.

## Required files per skill

```
[skill-slug]/
├── SKILL.md          ← Claude-readable (frontmatter + instructions)
├── README.md         ← Human-readable (what/when/how/triggers/outputs)
└── manifest.json     ← Machine-readable metadata
```

## SKILL.md frontmatter (required fields)

```yaml
---
name: skill-name
description: |
  One paragraph. Covers: what it does, when to activate, key triggers,
  what NOT to activate for. Claude reads this on every activation.
---
```

## README.md structure (required sections)

```markdown
# skill-name · Short tagline
**Category:** · **Version:** · **Language:** · **Owner:**

## What it does     (2–4 sentences)
## Activate when    (trigger phrases in code block)
## 3-step quickstart
## Main outputs     (table)
## Do NOT activate for
## Pairs with
```

## manifest.json (minimum fields)

```json
{
  "name": "skill-slug",
  "version": "1.0.0",
  "category": "category-name",
  "language": "PT-BR",
  "owner": "Leonardo Batista",
  "triggers": ["phrase 1", "phrase 2"],
  "outputs": ["output type 1"],
  "sensitivity": "standard"
}
```

## Quality checklist (before publishing)

- [ ] SKILL.md has valid YAML frontmatter
- [ ] Description covers: what, when to activate, when NOT to activate
- [ ] README has all 6 required sections
- [ ] Trigger phrases are specific (not generic)
- [ ] Sensitivity flag applied if health/legal/financial adjacent
- [ ] "Pairs with" points to real skills in this library
- [ ] README is ≤ 400 words
- [ ] No invented data, no unsourced claims
