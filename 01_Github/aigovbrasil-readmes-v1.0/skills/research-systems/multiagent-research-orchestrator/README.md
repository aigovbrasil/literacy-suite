# multiagent-research-orchestrator · Research Pipeline

**Category:** Research Systems · **Version:** current · **Language:** PT-BR / EN
**Owner:** Leonardo Batista

## What it does
Multi-agent orchestration pipeline for first-skill discovery research targeting Brazilian B2B service operators. Coordinates 4 specialist subagents to produce a complete qualification and research system.

## Activate when
```
"coletor de pesquisa"          "formulário de qualificação"
"first-skill discovery"        "segmentar personas"
"blueprint do formulário"      "rubrica de scoring"
"lógica de decisão"            "sistema de qualificação"
"dicionário de variáveis"      "modelo pré vs pós"
"orquestra pesquisa"
```
Also activates when user pastes a persona list and asks to build a qualification system.

## 4 subagents + outputs

| Subagent | Output |
|----------|--------|
| Segmentation | Persona clusters + filter criteria |
| Form Design | Form blueprint (25–40 questions) |
| Schema/Scoring | Variable dictionary + scoring rubric |
| QA | Validation report + case decision logic |

**Package also includes:** Pre/post model · Transcription schema

---
*CMD trigger: `"coletor de pesquisa"` · `"first-skill discovery"` · persona list paste*
