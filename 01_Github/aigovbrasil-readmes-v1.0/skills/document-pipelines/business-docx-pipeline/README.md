# business-docx-pipeline · Document Corpus Pipeline

**Category:** Document Pipelines · **Version:** current · **Language:** PT-BR / EN
**Owner:** Leonardo Batista

## What it does
Transforms raw business context (brief, research, idea, notes) into a canonical document corpus with dependency validation, epistemic traceability, and human approval gates. Supports MRD → BRD → PRD → SOP → Runbook → Roadmap → Backlog chains.

## Activate when
```
"cria documentação"          "monta o playbook"
"gera o corpus"              "preciso do PRD"
"pipeline documental"        "transforma esse briefing em docs"
"estrutura esse projeto"     "gera o workbook"
"cria a skill de documentos"
```

## Dependency chain
```
Business Brief → MRD → BRD → PRD → SOP → Runbook → Roadmap → Backlog
     (each step validates inputs from previous before proceeding)
```

## Quality gates
- Human approval required before each major document
- Epistemic labels on all claims (fact / inference / hypothesis)
- Financial spreadsheet and Linear prompt generated on request

## Pairs with
`scripity` (corpus generation) · `projects-to-linear` (backlog export) · `cmd-01-pps` (packaging)

---
*CMD trigger: `"pipeline documental"` · `"gera o corpus"` · `"preciso do PRD"`*
