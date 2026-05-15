# x-ray-publish-register · X-Ray Skill Registry

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Registers an X-Ray skill to the Notion Skill Library + Google Drive after reader-test validation. Maintains versioning and notifies active B2 clones when a new B1 version is published.

## Activate when
```
"publicar skill X-Ray"       "registrar nova versão"
"publish X-Ray"              "notificar clones consultores"
"atualizar biblioteca"       "/x-ray-publish"
"/x-ray-register"            "save skill to notion"
"subir skill ao Drive"       "release X-Ray"
```
Also auto-activates after successful X-Ray skill creation (handoff from `x-ray-skill-packager`).

## Prerequisites
- Reader-test must pass before publication
- `x-ray-skill-packager` must have produced a valid ZIP

## Do NOT activate for
Generic Anthropic skills (use `skill-publish-and-register`) · unpassed reader-test

---
*CMD trigger: `/x-ray-publish` · `/x-ray-register` · auto-handoff from x-ray-skill-packager*
