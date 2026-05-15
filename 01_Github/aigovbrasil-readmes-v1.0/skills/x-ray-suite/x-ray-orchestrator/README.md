# x-ray-orchestrator · Central Case OS

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
The operational co-pilot for the X-Ray consultant. Manages case state, captures decisions/hypotheses/risks, enforces epistemic gates (G1–G4), and dispatches to specialist skills. Never invents facts. Never promotes hypothesis to fact without explicit gate.

## Activate when
```
"/x-ray-start"          "novo cliente X-Ray"     "iniciar caso X-Ray"
"/captura"              "/captura_decisao"        "/captura_hipotese"
"/captura_risco"        "/x-ray-diagnose"         "/x-ray-deliver"
"/x-ray-execute"        "/status do caso"         "session close X-Ray"
```
Also activates on: "diagnóstico estratégico de PME" · "gates G1–G4" · "intake de cliente X-Ray"

## 3-step quickstart
1. Say: `/x-ray-start` (generates `consultant_config.yaml` on first run)
2. Capture: `/captura [fact|decision|hypothesis|risk]`
3. Deliver: `/x-ray-deliver [ebook|form-cliente|dashboard]`

## Core contracts
- Consultant decides. Skill executes.
- No deliverable without recorded confirmation in `decision_log`
- Every session reads `consultant_config.yaml` first

## Do NOT activate for
Skill creation · abstract diagnosis without live case (use `x-ray-abs`) · YAML normalization alone (use `x-ray-db`)

---
*CMD trigger: `/x-ray-start` · `/captura` · `/x-ray-deliver`*
