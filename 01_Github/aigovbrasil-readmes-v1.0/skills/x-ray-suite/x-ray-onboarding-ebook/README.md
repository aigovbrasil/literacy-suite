# x-ray-onboarding-ebook · Interactive HTML Ebook

**Category:** X-Ray Suite · **Version:** 1.0.0 · **Language:** PT-BR
**Owner:** Leonardo Batista · **License:** X-Ray Commercial Suite

## What it does
Generates a standalone interactive HTML ebook in two routes:
- `/rogerinho` — Consultant onboarding (suite download, setup guide)
- `/toni` — Client deliverable (diagnosis results, no Claude dependency)

## Activate when
```
"gerar ebook X-Ray"          "criar ebook de onboarding"
"ebook do consultor"         "ebook do cliente Toni"
"/x-ray-deliver ebook"       "/x-ray-deliver ebook-cliente"
"deliverable HTML X-Ray"     "onboarding interativo da suite"
```

## Two routes
| Route | Audience | Content |
|-------|----------|---------|
| `/rogerinho` | Consultant (new buyer) | Suite download + setup + skill map |
| `/toni` | Client (final) | Diagnosis results, action plan, no X-Ray branding |

## Do NOT activate for
Simple PDFs (use `forge-visual-canvas` + pdf skill) · single-section outputs · presentations (use pptx skill)

---
*CMD trigger: `/x-ray-deliver ebook` · `/x-ray-deliver ebook-cliente`*
