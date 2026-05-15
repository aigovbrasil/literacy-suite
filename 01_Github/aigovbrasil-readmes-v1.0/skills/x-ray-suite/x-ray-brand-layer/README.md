# x-ray-brand-layer · Consultant Brand Overlay

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Applies the consultant's identity (name, color, logo, font) over FORGE base tokens in any client-facing deliverable. The client never sees "X-Ray" branding — only the consultant's own brand.

## Activate when
```
"aplicar minha brand"        "personalizar o output"
"trocar para a marca"        "remover branding X-Ray genérico"
"white-label"                "ajustar cores"
"injetar logo do consultor"
```
Also activates automatically on any client-facing output generation, and on `consultant_config.yaml` setup.

## Pipeline
```
raw output → forge-visual-canvas (base tokens) → x-ray-brand-layer (consultant override) → final deliverable
```

## Source of truth
Brand identity comes **exclusively** from `consultant_config.yaml`. If config doesn't exist, stop and run `/x-ray-start`.

## Do NOT activate for
Internal outputs (drafts, decision_log, captures) — these never go to the client

---
*CMD trigger: `"white-label"` · `"aplicar minha brand"` · auto on client deliverable generation*
