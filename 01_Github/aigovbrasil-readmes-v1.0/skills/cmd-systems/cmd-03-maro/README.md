# CMD-03-MARO · Multi-Agent Research Orchestrator

**Category:** CMD Systems · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista

## What it does
Orchestrates 4 specialist subagents (segmentation, form design, schema/scoring, QA) for first-skill discovery research targeting Brazilian B2B service operators. Produces: form blueprint, variable dictionary, transcription schema, scoring rubric, case decision logic, pre/post model.

## Activate when
```
"CMD-03-MARO"                 "MARO"
"coletor de pesquisa"         "formulário de qualificação"
"first-skill discovery"       "segmentar personas"
"orquestra pesquisa"          "multi-agent research"
T01–T15 trigger IDs
```
Also activates when user pastes a persona list requesting a qualification system.

## 4 subagents

| Agent | Role |
|-------|------|
| Segmentation | Defines persona clusters and filters |
| Form Design | Creates qualification form blueprint |
| Schema/Scoring | Builds scoring rubric and decision logic |
| QA | Validates output against all inputs |

## Output package
Form blueprint · Variable dictionary · Transcription schema · Scoring rubric · Case decision logic · Pre/post model

---
*CMD trigger: `"CMD-03-MARO"` · `"MARO"` · `"coletor de pesquisa"` · `T01–T15`*
