# Aigovbrasil · Claude Skills Library

**24 production-ready skills** across 8 categories.  
Each skill has a `SKILL.md` (Claude-readable) and a `README.md` (human-readable).

---

## How to install a skill

1. Download the `.skill.zip` from the category folder
2. `claude.ai → Settings → Skills → Add skill → Upload`
3. The skill activates in your account

---

## Quick trigger reference

### 🔬 X-Ray Suite (10 skills) — Full consulting OS

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **x-ray-abs** | `x-ray` · `diagnóstico` · `analise esse negócio` · `gaps` | Scored diagnosis + Mermaid + Decision Question |
| **x-ray-db** | `exporta para yaml` · `yaml canônico` · auto from x-ray-abs | 12-block YAML schema |
| **x-ray-orchestrator** | `/x-ray-start` · `/captura` · `/x-ray-deliver` | Case state + gates G1–G4 |
| **x-ray-client-form** | `/x-ray-deliver form-cliente` · `intake form` · `form D0` | 25-question HTML form |
| **x-ray-brand-layer** | `white-label` · `aplicar minha brand` · client output | Consultant-branded deliverable |
| **x-ray-onboarding-ebook** | `/x-ray-deliver ebook` · `/x-ray-deliver ebook-cliente` | Interactive HTML ebook |
| **x-ray-executive-office** | `/x-ray-deliver dashboard` · `kanban X-Ray` | Kanban execution tracker |
| **x-ray-publish-register** | `/x-ray-publish` · `publicar skill X-Ray` | Notion + Drive registration |
| **x-ray-self-knowledge** | `/x-ray-help` · `qual skill X-Ray usar` | Routing decision |
| **x-ray-skill-packager** | `/x-ray-package` · `empacotar suite X-Ray` | Distributable ZIP |

### ⚙️ CMD Systems (3 skills) — Packaging + improvement + research

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **cmd-01-pps** | `CMD-01-PPS` · `T03+T07+T12` · `W01` · `empacota projeto` | Packaged repo / ZIP |
| **cmd-02-mirp** | `MIRP` · `W01 [skill]` · `T03 [skill]` · `improve skill` | Improved skill + Notion entry |
| **cmd-03-maro** | `CMD-03-MARO` · `MARO` · `coletor de pesquisa` | Research qualification system |

### 🖥 Major OS (4 skills) — Large operating systems

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **praxis-os** | `/praxis` · `/praxis-*` · `new client just signed` | Full consulting session |
| **empower-v4** | `Empower V4` · `analyze Claude conversations` · `maturity score` | AI usage evaluation report |
| **horacio** | `Horácio` · `CMD` · `RAG` · `vault` · `Decision OS` | Decision-ready vault asset |
| **forge-visual-canvas** | `FORGE` · `criar artifact` · `visual canvas studio` | Premium HTML/JSX/SVG/PDF |

### ✍️ Editorial Publishing (3 skills)

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **frankwatching-editor** | `Frankwatching` · Dutch professional content | NL publication-ready article |
| **scripity** | `scripity` · `gerar corpus` · `criar 17 artefatos` | 17-artifact document corpus |
| **live-prompt-pro-converter** | `converta esse prompt` · `prompt engineering` | Optimized prompt |

### 📄 Document Pipelines (1 skill)

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **business-docx-pipeline** | `pipeline documental` · `gera o corpus` · `preciso do PRD` | MRD → BRD → PRD → SOP chain |

### 🔎 Research Systems (2 skills)

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **multiagent-research-orchestrator** | `coletor de pesquisa` · `first-skill discovery` | Qualification + scoring system |
| **workflow-to-skill-magic** | `transforma isso em skill` · `vira skill` | Reusable SKILL.md |

### 🛠 Meta-Skill Tooling (1 skill)

| Skill | Key trigger phrases | Primary output |
|-------|---------------------|----------------|
| **skill-publish-and-register** | `publica a skill` · `salva no notion` | Notion skill library entry |

### ♿ Accessibility (1 skill)

| Skill | Key trigger phrases | Sensitivity |
|-------|---------------------|-------------|
| **adhd-desk-dashboard** | ADHD/TDAH workflow · `mesa de trabalho` · printable dashboard | ⚠️ R-004: cognitive health context |

---

## Archived / quarantine

| Item | Status | Location |
|------|--------|----------|
| `horacio.skill.zip` | Archived — superseded by `horacio-v2` | `_archive/duplicates/` |
| `live-prompt-pro-converter.skill 2.zip` | Archived — identical to primary | `_archive/duplicates/` |
| `ex-oficce.zip` | Quarantined — no SKILL.md found | `_quarantine/review-needed/` |
| `research-protocol-diamond.zip` | Quarantined — non-standard format | `_quarantine/review-needed/` |

---

*Full metadata → [`docs/MASTER_INDEX.md`](../docs/MASTER_INDEX.md)*  
*Installation guide → root [`README.md`](../README.md#how-to-use-this-repo)*
