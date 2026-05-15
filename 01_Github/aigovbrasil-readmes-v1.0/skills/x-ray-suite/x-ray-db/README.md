# x-ray-db · Canonical YAML Normalizer

**Category:** X-Ray Suite · **Version:** 2.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Takes any X-Ray output and normalizes it into a 12-block YAML schema ready for downstream agents (Linear, Notion, data pipelines). Machine-readable. ID-preserving.

## Activate when
```
"exporta para yaml"    "normaliza para downstream"    "yaml canônico"
"schema do x-ray"     "saída programática"            "input para agentes"
"padroniza esse output"
```
Also auto-activates on handoff from `x-ray-abs`.

## 3-step quickstart
1. Run `x-ray-abs` to produce a diagnosis
2. Say: `"exporta para yaml"`
3. Receive: canonical YAML with all IDs, phases, gates, roadmap

## Schema (12 blocks)
`metadata` · `project` · `executive_context` · `areas[]` · `artifacts[]` · `frameworks[]` · `modules[]` · `workflows[]` · `pilot_cases[]` · `risks[]` · `roadmap` · `next_steps`

**v2 Canonical Pipeline:** Phases S00–S20 · Gates GATE-S00–GATE-S20 · Deliverables DEL-Sxx-NN

## Pairs with
`x-ray-abs` → `x-ray-db` → `x-ray-orchestrator` → `projects-to-linear`

---
*CMD trigger: `x-ray-db` · `yaml canônico` · auto-handoff from x-ray-abs*
