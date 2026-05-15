# CMD-02-MIRP · Modify-Improve-Register-Publish

**Category:** CMD Systems · **Version:** 1.0.0 · **Language:** PT-BR / EN
**Owner:** Leonardo Batista · **License:** Proprietary (X-RAY OS)

## What it does
12-step deterministic pipeline that transforms any skill into a production-ready CMD-format package: ID taxonomy (A01–A20, T01–T15, W01–W10), 5W2H docs, combinable triggers, Notion registration, version-tagged ZIP.

## Activate when
```
"CMD-02-MIRP"    "MIRP"    "/mirp [skill-name]"
"improve skill"  "register skill"  "publish skill"
"CMD-ify"        skill uploaded for enhancement
```

## 3 most used combos

| Combo | What it does | Time |
|-------|-------------|------|
| `W01` | Full 12-step pipeline | 2 min |
| `T03` | Fast enhance (taxonomy + package) | 30s |
| `T04` | Register existing skill to Notion | 20s |

## Full pipeline (W01)
Scan → Extract triggers → Generate IDs → 5W2H → WOW combos → Tabular → Rewrite → Examples → Package ZIP → Register Notion → Publish → Log

## Pairs with
`cmd-01-pps` (repo packaging) · `skill-publish-and-register` (Notion sync) · `x-ray-skill-packager` (X-Ray suite)

---
*CMD trigger: `"MIRP"` · `W01 [skill-name]` · `T03 [skill-name]` · `T04 [skill-name]`*
