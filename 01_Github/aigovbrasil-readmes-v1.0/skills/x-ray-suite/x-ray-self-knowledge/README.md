# x-ray-self-knowledge · X-Ray Suite Router

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Precision router for the X-Ray suite. Given any problem or question, returns the exact skill to use. Prevents wrong-skill invocation. Inspired by Anthropic's product-self-knowledge, adapted for X-Ray.

## Activate when
```
"qual skill X-Ray usar para [task]"   "como funciona a suite X-Ray"
"o que faz cada skill X-Ray"          "diferença entre x-ray-orchestrator e x-ray-abs"
"documentação interna X-Ray"          "mapa da suite X-Ray"
"X-Ray help"                          "/x-ray-help"
"self-knowledge"
```
Also activates when two X-Ray skills seem to overlap — consult this router before guessing.

## Core principles
1. Precision over guessing — if two skills look right, read both and choose
2. Distinguish layers — DEV (Anthropic) vs B1 (Leonardo) vs B2 (consultant clone) vs C (client)
3. Name the skill invoked and its version

## Do NOT activate for
Anthropic product questions (use `product-self-knowledge`) · executing tasks directly

---
*CMD trigger: `"/x-ray-help"` · `"qual skill X-Ray"` · `"self-knowledge"`*
