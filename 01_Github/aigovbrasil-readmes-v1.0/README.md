# Aigovbrasil

**AI governance, Claude skills, workflow guides, and AI literacy resources for non-technical professionals.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills: 24](https://img.shields.io/badge/Claude%20Skills-24-brightgreen)](#claude-skills-library)
[![Language: PT-BR / EN](https://img.shields.io/badge/Language-PT--BR%20%2F%20EN-lightgrey)](#)

---

## Overview

Aigovbrasil is a docs-first repository of Claude skills, AI literacy guides, workflow tools, and AI governance resources built for non-technical professionals who use AI daily for real work.

The thesis: **the next competitive advantage will not be using AI. It will be operating AI with fluency.**

This repo is the operational infrastructure behind that thesis — a library of reusable Claude skills, documented workflows, and governance frameworks designed for knowledge workers, consultants, founders, and analysts.

---

## Who this repository is for

- Knowledge workers using Claude daily for business tasks
- Consultants who need repeatable, traceable AI workflows
- Analysts and operators building structured AI systems
- Non-technical founders integrating AI into their operations
- AI literacy advocates and educators
- Anyone who needs Claude to behave like a system, not a chatbox

---

## What this repository includes

| Type | Count | Description |
|------|-------|-------------|
| Claude Skills | 24 | Production-ready `.skill.zip` packages |
| Skill categories | 8 | Organized by function and use case |
| Docs | 5 | Standards, index, operating manual, governance |
| Assets | 1 | Interactive AI literacy ebook (HTML) |
| Tools | 1 | Batch skill builder package |

---

## Repository structure

```
aigovbrasil/
├── README.md                     ← This file
├── LICENSE                       ← MIT License
├── .gitignore
│
├── docs/
│   ├── MASTER_INDEX.md           ← Complete skill index (25 columns)
│   ├── OPS_PRINT_MASTER_INDEX.md ← Print-ready operations reference
│   ├── REPO_OPERATING_MANUAL.md  ← How to use and maintain this repo
│   ├── SKILL_LIBRARY_STANDARD.md ← Skill quality standard
│   └── AI_GOVERNANCE_DISCLAIMER.md
│
├── skills/
│   ├── README.md                 ← Skill library index
│   ├── x-ray-suite/              ← 10 skills: full consulting OS
│   ├── cmd-systems/              ← 3 skills: packaging + improvement + research
│   ├── major-os/                 ← 4 skills: Praxis, Empower, Horácio, FORGE
│   ├── editorial-publishing/     ← 3 skills: Frankwatching, Scripity, live-prompt
│   ├── document-pipelines/       ← 1 skill: business-docx-pipeline
│   ├── research-systems/         ← 2 skills: MAO + workflow-to-skill-magic
│   ├── meta-skill-tooling/       ← 1 skill: skill-publish-and-register
│   └── accessibility-cognitive-workflows/ ← 1 skill: adhd-desk-dashboard
│
├── assets/
│   └── html/
│       └── ebook-interativo.html ← A-Z AI Literacy & AI Fluency ebook
│
├── tools/
│   └── batch-skill-builder/      ← Python batch normalizer for skill packages
│
├── reports/
│   ├── batch/                    ← Batch build reports
│   └── validation/               ← QA validation reports
│
├── _archive/
│   ├── original-zips/            ← Source ZIPs preserved
│   └── duplicates/               ← Archived duplicate skill variants
│
└── _quarantine/
    └── review-needed/            ← Assets pending manual review
```

---

## Claude Skills library

24 production-ready skills across 8 categories. Each skill has a `SKILL.md` (Claude-readable), `README.md` (human-readable), and `manifest.json`.

| Category | Skills | Primary use |
|----------|--------|-------------|
| **X-Ray Suite** | 10 | Full consulting OS: diagnosis → delivery |
| **CMD Systems** | 3 | Project packaging, skill improvement, research orchestration |
| **Major OS** | 4 | Praxis OS, Empower V4, Horácio, FORGE Visual Canvas |
| **Editorial Publishing** | 3 | Frankwatching, Scripity, Prompt Converter |
| **Document Pipelines** | 1 | Business document corpus generator |
| **Research Systems** | 2 | Multi-agent research, workflow-to-skill converter |
| **Meta-Skill Tooling** | 1 | Skill registration and publishing |
| **Accessibility** | 1 | ADHD/TDAH-friendly workflow dashboards |

→ See [`skills/README.md`](skills/README.md) for the complete index with triggers.

---

## Daily AI work use cases

```
"I need to diagnose a client's business"
→ x-ray-abs + x-ray-orchestrator

"I want to package my files for GitHub"
→ cmd-01-pps: T03+T07+T12

"I have a skill I want to improve and register"
→ cmd-02-mirp: W01 [skill-name]

"I need a premium visual artifact or ebook"
→ forge-visual-canvas

"I'm evaluating my AI usage quality"
→ empower-v4-ai-usage-evaluator

"I need an article in Frankwatching format"
→ frankwatching-editor

"I have a workflow I repeat every week"
→ workflow-to-skill-magic
```

---

## AI governance and AI literacy scope

This repository addresses AI governance at the practitioner level:

- **EU AI Act Article 4** — AI literacy as a legal obligation (in effect since Feb 2, 2025)
- **Operational AI fluency** — using AI as a system, not a chatbox
- **Epistemic discipline** — fact ≠ hypothesis ≠ inference in every output
- **Responsible skill design** — safety boundaries, sensitivity flags, no medical advice
- **Claude Skills standard** — follows Anthropic's public skill format (SKILL.md + metadata + instructions)

---

## Master index

→ [`docs/MASTER_INDEX.md`](docs/MASTER_INDEX.md) — all 24 skills with full metadata, triggers, categories, status, and sensitivity levels.

---

## How to use this repo

**To install a skill in Claude.ai:**
1. Download the `.skill.zip` file from the relevant category folder
2. Go to claude.ai → Settings → Skills → Add skill
3. Upload the `.skill.zip` file
4. The skill is now active in your account

**To use the batch builder:**
```bash
python tools/batch-skill-builder/skill_builder_batch.py \
  --input ./skills/[category] \
  --output ./reports/batch/[run-name] \
  --overwrite
```

**To find the right skill:**
→ See trigger phrases in each skill's README, or consult `x-ray-self-knowledge` for X-Ray suite routing.

---

## Safety and legal disclaimer

Skills in this repository are tools for knowledge workers. They do not provide medical, legal, or financial advice.

- `adhd-desk-dashboard` — designed for cognitive accessibility. Does not replace professional assessment.
- All X-Ray skills — used for business consulting support. Outputs require human review before client delivery.
- EU AI Act compliance — users are responsible for their own AI literacy obligations under applicable law.

Full disclaimer: [`docs/AI_GOVERNANCE_DISCLAIMER.md`](docs/AI_GOVERNANCE_DISCLAIMER.md)

---

## License

MIT License — see [`LICENSE`](LICENSE) for full text.  
Copyright (c) 2026 Aigovbrasil

---

## Contact

**Owner:** Leonardo Batista · AI Workflow Researcher · LLM Governance Analyst  
**Platform:** Review Journal  
**GitHub:** [aigovbrasil](https://github.com/aigovbrasil)
