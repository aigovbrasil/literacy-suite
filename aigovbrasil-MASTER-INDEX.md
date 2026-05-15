# Aigovbrasil · Master Skill Index

**Version:** 1.0 · **Date:** 2026-05-14 · **Active Skills:** 24 · **Owner:** Leonardo Batista

---

| ID | Skill Name | Slug | Category | Active | Sensitivity | Primary Use Case | Key Triggers | Main Outputs | Has SKILL.md | Has README | Notes |
|----|-----------|------|----------|--------|-------------|-----------------|--------------|--------------|--------------|-----------|-------|
| S01 | X-Ray ABS | x-ray-abs | x-ray-suite | ✅ | Standard | Strategic business diagnosis | `x-ray` · `diagnóstico` · `gaps` | Scored GAP map + Mermaid + Decision Q | ✅ | ✅ | v3 + Canonical Engine |
| S02 | X-Ray DB | x-ray-db | x-ray-suite | ✅ | Standard | YAML normalization | `yaml canônico` · auto from x-ray-abs | 12-block YAML | ✅ | ✅ | v2 + pipeline phases |
| S03 | X-Ray Orchestrator | x-ray-orchestrator | x-ray-suite | ✅ | Standard | Live case OS | `/x-ray-start` · `/captura` | Case state + gates | ✅ | ✅ | Requires consultant_config.yaml |
| S04 | X-Ray Client Form | x-ray-client-form | x-ray-suite | ✅ | Standard | Client intake | `/x-ray-deliver form-cliente` | 25-question HTML form | ✅ | ✅ | D0 flow |
| S05 | X-Ray Brand Layer | x-ray-brand-layer | x-ray-suite | ✅ | Standard | White-label output | `white-label` · `aplicar minha brand` | Branded deliverable | ✅ | ✅ | Requires consultant_config.yaml |
| S06 | X-Ray Onboarding Ebook | x-ray-onboarding-ebook | x-ray-suite | ✅ | Standard | Interactive ebook | `/x-ray-deliver ebook` | HTML ebook (2 routes) | ✅ | ✅ | /rogerinho + /toni routes |
| S07 | X-Ray Executive Office | x-ray-executive-office | x-ray-suite | ✅ | Standard | Execution tracker | `/x-ray-deliver dashboard` | Kanban S00–S20 | ✅ | ✅ | 2 modes: consultant + client |
| S08 | X-Ray Publish Register | x-ray-publish-register | x-ray-suite | ✅ | Standard | Skill registry | `/x-ray-publish` | Notion + Drive entry | ✅ | ✅ | Requires reader-test pass |
| S09 | X-Ray Self-Knowledge | x-ray-self-knowledge | x-ray-suite | ✅ | Standard | Suite router | `/x-ray-help` · `qual skill X-Ray` | Routing decision | ✅ | ✅ | Meta-skill |
| S10 | X-Ray Skill Packager | x-ray-skill-packager | x-ray-suite | ✅ | Standard | Suite distribution | `/x-ray-package` | Distributable ZIP | ✅ | ✅ | All 8+ skills in one package |
| S11 | CMD-01-PPS | cmd-01-pps | cmd-systems | ✅ | Standard | Project packaging | `CMD-01-PPS` · `T03+T07+T12` · `W01` | Packaged repo / ZIP | ✅ | ✅ | 20 actions, 15 triggers, 10 workflows |
| S12 | CMD-02-MIRP | cmd-02-mirp | cmd-systems | ✅ | Standard | Skill improvement | `MIRP` · `W01 [skill]` | Improved skill + Notion | ✅ | ✅ | 12-step pipeline |
| S13 | CMD-03-MARO | cmd-03-maro | cmd-systems | ✅ | Standard | Research orchestration | `CMD-03-MARO` · `MARO` | Qualification system | ✅ | ✅ | 4 subagents |
| S14 | Praxis OS | praxis-os | major-os | ✅ | Standard | Consulting OS | `/praxis` · `/praxis-*` | Full consulting session | ✅ | ✅ | 23 agents, 5 phases |
| S15 | Empower V4 | empower-v4-ai-usage-evaluator | major-os | ✅ | Standard | AI usage evaluation | `Empower V4` · `maturity score` | Usage report | ✅ | ✅ | System-level evaluation |
| S16 | Horácio | horacio | major-os | ✅ | Standard | Operational intelligence | `Horácio` · `RAG` · `vault` | Decision-ready vault asset | ✅ | ✅ | v2 active (horacio-v2) |
| S17 | FORGE Visual Canvas | forge-visual-canvas | major-os | ✅ | Standard | Visual artifacts | `FORGE` · `criar artifact` | HTML/JSX/SVG/PDF/PPTX | ✅ | ✅ | 10 visual languages |
| S18 | Frankwatching Editor | frankwatching-editor | editorial-publishing | ✅ | Standard | Dutch editorial | `Frankwatching` · Dutch article | NL publication-ready article | ✅ | ✅ | Dutch professional platform |
| S19 | Scripity | scripity | editorial-publishing | ✅ | Standard | Document corpus | `scripity` · `gerar corpus` | 17 artifacts + 19 frameworks | ✅ | ✅ | Input: YAML metadata |
| S20 | Live Prompt Pro Converter | live-prompt-pro-converter | editorial-publishing | ✅ | Standard | Prompt optimization | `converta esse prompt` | Optimized prompt | ✅ | ✅ | Any language, any model |
| S21 | Business Docx Pipeline | business-docx-pipeline | document-pipelines | ✅ | Standard | Doc corpus pipeline | `pipeline documental` · `preciso do PRD` | MRD→BRD→PRD→SOP chain | ✅ | ✅ | Human approval gates |
| S22 | Multiagent Research Orchestrator | multiagent-research-orchestrator | research-systems | ✅ | Standard | Research qualification | `coletor de pesquisa` · `first-skill discovery` | Qualification + scoring system | ✅ | ✅ | 4 subagents |
| S23 | Workflow to Skill Magic | workflow-to-skill-magic | research-systems | ✅ | Standard | Workflow → skill | `transforma isso em skill` | Reusable SKILL.md | ✅ | ✅ | Non-dev optimized |
| S24 | Skill Publish and Register | skill-publish-and-register | meta-skill-tooling | ✅ | Standard | Notion registry | `publica a skill` · `salva no notion` | Notion library entry | ✅ | ✅ | Auto after skill creation |
| S25 | ADHD Desk Dashboard | adhd-desk-dashboard | accessibility-cognitive-workflows | ✅ | ⚠️ Health-adjacent (R-004) | ADHD-friendly workflow | `mesa de trabalho` · ADHD/TDAH mention | A4 PPTX + PDF + MD + Linear | ✅ | ✅ | Not medical advice |

---

## Archived

| Item | Reason | Location |
|------|--------|----------|
| horacio.skill.zip | Superseded by horacio-v2 (2026-05-08) | `_archive/duplicates/` |
| live-prompt-pro-converter.skill 2.zip | Identical to primary (18,683 bytes) | `_archive/duplicates/` |

## Quarantined

| Item | Reason | Location |
|------|--------|----------|
| ex-oficce.zip | No SKILL.md detected — unknown structure | `_quarantine/review-needed/` |
| research-protocol-diamond.zip | Non-standard format — manual review needed | `_quarantine/review-needed/` |
