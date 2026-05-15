# TRAVELLER DB SYSTEM
## Universal Agent-to-Agent CMD · Reusable for Any Purpose
### Authored: 2026-05-14 · Leonardo Batista · Aigovbrasil

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## PART 1 — UNIVERSAL CMD (COPY-PASTE FOR ANY PROJECT)
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

```yaml
cmd: traveller_db_universal

role: >
  You are an Excel agent maintaining a Traveller DB —
  a single living document that travels between Claude
  accounts, projects, and sessions without losing state.

mission: >
  Read the 00_CMD tab. Execute the [insumo]. Update the file.
  Rewrite 00_CMD for the next agent. Deliver versioned output.

# ─── 3 VARIABLES (user fills before each session) ───────────────
inputs:
  insumo:  "[paste your content, data, or workflow output here]"
  cmd:     "[content of tab 00_CMD — or paste this yaml]"
  zip:     "[previous XLS filename — always classified as newentry]"

# ─── EXECUTION PROTOCOL ─────────────────────────────────────────
steps:
  1: READ 00_CMD tab completely before touching anything
  2: READ CHANGELOG tab — understand last session state
  3: IDENTIFY what [insumo] adds (new data / update / new section)
  4: APPLY change to correct tab(s) — append-only, never restructure
  5: UPDATE NAVIGATOR or index tab if new item added
  6: REWRITE 00_CMD — bump version + snapshot + next CMD
  7: APPEND CHANGELOG row: date | version | changes | who | next
  8: SAVE as [filename]-v[N+1].xlsx — never overwrite v[N]
  9: DELIVER updated XLS + change summary

# ─── HARD CONSTRAINTS ────────────────────────────────────────────
hard_constraints:
  - Never delete a tab
  - Never overwrite v[N] — always save as v[N+1]
  - Never invent data — use [insumo] only
  - Always flag structural risk before executing
  - If 00_CMD tab is missing → STOP and alert user

# ─── HOW TO ADAPT FOR ANY PURPOSE ───────────────────────────────
adaptation_guide:
  skill_library:    "One tab per skill. NAVIGATOR = index. 00_CMD = protocol."
  research_db:      "One tab per study. 00_CMD = methodology. CHANGELOG = audit."
  client_tracker:   "One tab per client. 00_CMD = status + next action."
  content_calendar: "One tab per month. 00_CMD = publishing queue."
  personal_vault:   "One tab per topic. 00_CMD = retrieval protocol."
  ANY_PURPOSE:      "Replace tab names. Keep 00_CMD + CHANGELOG logic identical."

# ─── FALLBACK (Option B) ─────────────────────────────────────────
fallback:
  trigger: "XLS structurally broken or 00_CMD tab missing"
  action:  "Re-run original build script from GitHub"
  result:  "Rebuild full XLS from source in < 2 min"

# ─── RISK REGISTER ───────────────────────────────────────────────
risks:
  R-01: "Data loss → always v[N+1] save. CRITICAL."
  R-02: "Structure drift → append-only rule. HIGH."
  R-03: "CMD stale → rewrite 00_CMD every session. HIGH."
  R-04: "Version confusion → filename = truth. MEDIUM."
```

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## PART 2 — YOUR 300-WORD OPERATING MANUAL
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**How Leonardo operates the Traveller DB system daily.**

The core idea is simple: one Excel file carries its own instructions.
Tab `00_CMD` tells the next Claude agent exactly what to do —
no project setup, no re-explaining, no lost context between accounts.

**Daily flow (3 minutes or less):**

Open your latest XLS version. Copy the content of tab `00_CMD`.
Paste it into a new Claude session — any account, any project.
Add your `[insumo]` — whatever you created or decided in the last session.
The agent reads the CMD, applies the insumo, updates the tabs,
rewrites `00_CMD` for the next session, and delivers a new versioned XLS.
You download it. That's the full cycle.

**The 3 variables are the only interface:**
- `[insumo]` — what you bring from outside (data, skill, workflow, note)
- `[cmd]` — the 00_CMD tab content (the agent's operating instructions)
- `[zip]` — the previous XLS filename (versioning anchor)

**When to use Option A (daily):**
Any session where you're adding or updating content.
The XLS grows. The CMD evolves. The CHANGELOG records everything.
Friction is near zero because you're always working with the same file.

**When to fall back to Option B:**
If the XLS is ever broken, corrupted, or structurally damaged,
run `build_aigovbrasil_excel.py` from GitHub.
The script rebuilds the full 28-tab workbook in under 30 seconds.
Then re-apply your changes using the CHANGELOG as recovery reference.

**The power of this system is portability.**
You can send the XLS to a colleague, open it on a new Claude account,
or pick it up three months later — and the agent always knows what to do,
because the instructions live inside the document itself.
No memory. No project. No setup. Just the file.

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## PART 3 — PUBLIC README (FOR YOUR AUDIENCE)
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

# What We Built in This Session
## A Live AI Operations System — From Scratch, in One Chat

---

### The starting point

We opened this conversation with a ZIP file containing 31 Claude skill packages
and a batch builder tool. No repository. No structure. No documentation.

By the end, we had a professional, production-ready system that any
knowledge worker can open, understand, and operate — with no technical background required.

---

### What was built, step by step

**Step 1 — MECE Inventory Scan**
Before touching anything, we ran a complete audit of both ZIP files.
31 items inventoried. Duplicates identified. Quarantine items flagged.
24 active skills confirmed across 8 categories.
No files were modified during the scan.

**Step 2 — README Batch (24 skills)**
Using `cmd-01-pps` and `cmd-02-mirp` as the operating framework,
we extracted the `SKILL.md` from every skill package and generated
a professional README for each one — following a consistent standard:
what it does, when to activate, 3-step quickstart, outputs, pairs with.

**Step 3 — Executive Excel Workbook (28 tabs)**
We designed a 4-layer framework and built a full Excel library from the corpus:
- **Layer 1:** First Principles + ICP (who it's for, the core truth)
- **Layer 2:** Problem Tree (root cause + branches)
- **Layer 3:** 5W2H (operational clarity)
- **Layer 4:** Data-Driven metrics + CMD triggers + WOW combinations

The workbook includes a clickable NAVIGATOR, a PASTEL macro analysis tab
for AI governance context, 24 individual skill tabs, and a full Glossary.

**Step 4 — Traveller DB Architecture**
We designed a system for keeping the Excel file alive across sessions,
accounts, and time — without losing state or requiring project setup.

The solution: two tabs (`00_CMD` + `CHANGELOG`) that turn the Excel file
into a self-navigating document. The file carries its own instructions.
Any Claude agent, on any account, can pick it up and continue from exactly
where the last session left off.

---

### The design principles behind everything

**Epistemic discipline:** Every framework in this system separates fact
from hypothesis from inference. Nothing is presented with false certainty.

**Append-only architecture:** Nothing is ever deleted or overwritten.
Every version is preserved. Every change is logged.

**Portability over setup:** The system works without Claude Projects,
without memory, and without any account-specific configuration.
The document is the system.

**Anti-overkill:** Every design decision was tested against one question:
*does this reduce friction for daily use, or does it add complexity for its own sake?*
Complexity that doesn't reduce daily friction was removed.

---

### What you can take from this

The specific tools — Excel tabs, Claude skills, Python scripts —
are not the point. The pattern is the point.

Any knowledge work that repeats can be structured this way:
a self-documenting artifact that carries its own operating instructions,
versions itself, and works across any tool or account.

This is what AI fluency looks like in practice.
Not using AI to answer questions.
Using AI to build systems that operate themselves.

---

*Built live · 2026-05-14 · Leonardo Batista · Aigovbrasil*
*Tools: Claude Sonnet 4.6 · cmd-01-pps · cmd-02-mirp · openpyxl · Python*
*License: MIT · github.com/aigovbrasil*
