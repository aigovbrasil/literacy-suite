# x-ray-executive-office · Execution Dashboard

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Generates an interactive Kanban-style dashboard for tracking X-Ray case execution. Shows phases S00–S20, gates G0–G12, and decomposed tasks. Two modes: consultant (edit) and client (read-only, no sensitive data).

## Activate when
```
"executive office X-Ray"     "dashboard de execução"
"sprint tracker do caso"     "kanban X-Ray"
"/x-ray-deliver dashboard"   "acompanhar progresso do caso"
"visão executiva do plano"   "tracker de fases canônicas"
```

## Two modes
| Mode | Who sees it | Features |
|------|-------------|----------|
| Consultant | Rogerinho/Leonardo | Full view + edit + sensitive data |
| Client | Toni | Read-only, clean, no X-Ray internal data |

## Do NOT activate for
Creating Linear issues (use `projects-to-linear`) · abstract strategic analysis (use `x-ray-abs`)

---
*CMD trigger: `/x-ray-deliver dashboard` · `"kanban X-Ray"` · `"sprint tracker"`*
