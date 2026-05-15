# skill-publish-and-register · Skill Registry

**Category:** Meta-Skill Tooling · **Version:** current · **Language:** PT-BR
**Owner:** Leonardo Batista

## What it does
Orchestrates complete registration of a new skill to the Notion Skill Library: creates the library entry, saves the full SKILL.md as a subpage (canonical repository), and adds a row to the Operational Dashboard. Zero manual steps.

Note: Google Drive MCP does not allow writing — Notion is the canonical registry.

## Activate when
```
"publica a skill"          "regista a skill"
"salva no notion"          "linha de produção da skill"
"skill-publish"            "publish and register"
```
Also auto-activates at the end of any successful skill creation.

## What it creates in Notion
- Library entry (name, version, category, trigger phrases, ICP)
- SKILL.md as subpage (full content preserved)
- Dashboard row (status, date, owner)

## Pairs with
`cmd-02-mirp` (skill improvement before publishing) · `x-ray-publish-register` (X-Ray variant)

---
*CMD trigger: `"publica a skill"` · `"salva no notion"` · auto after skill creation*
