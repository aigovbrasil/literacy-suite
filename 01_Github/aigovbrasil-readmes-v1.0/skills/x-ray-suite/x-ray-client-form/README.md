# x-ray-client-form · Client Intake Form

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Generates a standalone HTML form (25 questions) for the consultant's client to complete — without needing to understand Claude. Client responds, copies the JSON output, and sends it back. Consultant imports into `x-ray-orchestrator`.

## Activate when
```
"gerar form de intake do cliente"   "formulário X-Ray"
"intake form Toni"                  "/x-ray-deliver form-cliente"
"criar form HTML para o cliente"    "form D0"
"diagnóstico inicial 8 minutos"
```
Also activates when consultant wants to send intake via WhatsApp link.

## Flow (D0 → D2)
```
D0  Consultant sends HTML to client (WhatsApp or GitHub Pages URL)
D0  Client answers 25 questions (~8 min) → copies JSON
D1  Consultant: /x-ray-start --import-json [paste]
D1  x-ray-orchestrator fills source_of_truth.md, opens Gate G1
D2  Proceed to diagnosis (Phase 02)
```

## Do NOT activate for
Internal consultant forms (use `ask_user_input_v0`) · generic non-X-Ray forms

---
*CMD trigger: `/x-ray-deliver form-cliente` · `"intake form"` · `"form D0"`*
