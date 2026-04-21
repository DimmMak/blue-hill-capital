# 🏛️ Blue Hill Capital — Org Chart

> Every brand-named skill → its real hedge fund role.
> Source of truth for "who does what" in the operation.

---

## 📊 The org chart at a glance

```
                                ┌───────────────────┐
                                │     YOU (PM)      │
                                │  Portfolio Mgr.   │
                                └───────┬───────────┘
                                        │
                     ┌──────────────────┼──────────────────┐
                     │                  │                  │
                     ▼                  │                  ▼
         ┌──────────────────────┐       │       ┌──────────────────────┐
         │       MEWTWO         │       │       │   CHIEF OF STAFF     │
         │ (Head of Research)   │       │       │   (Chief of Staff)   │
         │  outbound routing    │       │       │  inbound filtering   │
         └──────────┬───────────┘       │       └──────────────────────┘
                    │                   │                  ▲
                    ▼                   │                  │
         ┌──────────────────────────────┴──────────────────┴─────────┐
         │                      THE SKILL FLEET                       │
         └───────────────────────────────────────────────────────────┘
               │            │            │            │         │
               ▼            ▼            ▼            ▼         ▼
         ┌────────┐   ┌────────┐   ┌────────┐   ┌────────┐ ┌──────────┐
         │ ROYAL  │   │ JOURN- │   │ PROJ-  │   │  TIME  │ │ ARCHIVE  │
         │ RUMBLE │   │ ALIST  │   │  MGR.  │   │ MACHINE│ │   +      │
         │        │   │        │   │        │   │        │ │ CASH-OUT │
         │ Invest │   │Investor│   │  COO / │   │Research│ │  Records │
         │ Commit │   │  Rels. │   │ Project│   │ Library│ │   Mgr +  │
         │        │   │        │   │        │   │        │ │ Back Ofc │
         └────────┘   └────────┘   └────────┘   └────────┘ └──────────┘

 (future skills: accuracy-tracker, trade-journal, catalyst-calendar, dossier, scout)
```

---

## 📋 Master roster

### 🏢 C-SUITE (orchestration layer)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **YOU** | Portfolio Manager (PM) | Makes all decisions. Owns the capital. |
| **mewtwo** | Head of Research | Receives task intent, dispatches to the right skill(s). |
| **chief-of-staff** | Chief of Staff | Filters & ranks escalations. Protects PM's attention. |

---

### 🔬 RESEARCH TIER (the thinking)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **royal-rumble** | Investment Committee | 13-legend blind committee. Produces verdicts. |
| **[future] dossier** | Due Diligence Analyst | Reads curated article packs, framework-checks thesis. |
| **[future] scout** | Idea Generation Analyst | Screens user watchlist for candidates. Hard-killed for scanning the universe. |

---

### 📊 STORAGE / OBSERVABILITY TIER (the memory)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **[future] accuracy-tracker** | Performance Attribution Analyst | Scores past calls vs. reality. |
| **[future] trade-journal** | Trader Diary / Trade Blotter | Post-trade reflection + pattern detection. |
| **[future] catalyst-calendar** | Events Desk | Fed dates, earnings, macro events. |
| **archive** | Records Manager | Session archive with PII redaction. |
| **time-machine** | Research Librarian | Ctrl+F across all archived conversations. |

---

### 📢 COMMUNICATION TIER (the voice)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **journalist** | Investor Relations / Press Office | Marks-style investment memos from rumble output. |

---

### ⚙️ OPERATIONS TIER (back office)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **cash-out** | Closing Officer (Back Office) | End-of-day ritual: archive, push, backup. |
| **project-manager** | Chief Operating Officer (COO) | Owns ROADMAP.md. Triage, prioritization, stale-item flagging across any project. |
| **command-center** | Morning Dashboard / Daily Brief Officer | 9am 4-panel brief: stock news, geopolitics, Gmail, to-dos. Learns taste via weekly retro. |

---

### 🎓 LEARNING / PERSONAL (non-fund but in the stack)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **study-buddy** | Training Coordinator | Live lecture-watching companion. |
| **courserafied** | Training Records Keeper | Parses course material into structured knowledge base. |
| **life-coach** | _(Not a fund role)_ | Discipline / habit coaching. |
| **promptlatro** | _(Not a fund role)_ | Prompt-engineering game. |

---

### 🖥️ DESK-OPS (computer-use family — sibling to *-desk)

| Brand Name | Real Hedge Fund Title | What they do |
|---|---|---|
| **desk-ops/file-mover** | Records Clerk | YAML-rule file mover across folders. Dry-run default. |
| **desk-ops/finder-cleanup** | Records Clerk | Triage report for Downloads/Desktop. Propose-only. |
| **desk-ops/shortcuts-runner** | Operations Assistant | Fires macOS Shortcuts from Claude via `shortcuts` CLI. |
| **desk-ops/photos-organizer** | Records Clerk | _(stub v0.2)_ Album creation + dedupe in Photos.app. |
| **desk-ops/form-filler** | Operations Assistant | _(stub v0.2)_ Generic form-fill in native apps. |

All members share one contract: **propose → confirm → execute → log → undo.**

---

## 🎭 The naming convention

```
Brand name         = kebab-case, fun, memorable (e.g. "royal-rumble")
Real fund title    = yaml "role:" field in each SKILL.md frontmatter
                   = how this role is described on a LinkedIn or CV
```

**You keep the fun. Recruiters see the function.**

---

## 🎯 Usage examples

**Your LinkedIn summary:**
> "Built and operate Blue Hill Capital, a pre-alpha hedge fund, across a 13-role organizational chart: PM, Head of Research, Chief of Staff, Investment Committee (13 legends), IR/Press Office, Performance Attribution, Trader Diary, Events Desk, Due Diligence, Records Manager, Research Librarian, and Back Office. Each role is a versioned Claude skill. Stack runs $2.4k/year."

**Your interview opener:**
> "At Blue Hill, our Investment Committee runs every name through a sealed-subagent blind committee of 13 legendary investor frameworks. The Judge synthesizes a weighted verdict. Our Chief of Staff ranks the output for attention, and our Press Office turns it into Howard Marks-style memos. Every trade lives in git with audit trail."

---

## 📐 What to add when you create a new skill

```yaml
---
name: your-skill-name
version: 0.1.0
role: Real Hedge Fund Job Title       ← always fill this
description: ...
---
```

Then update this file (`ORG-CHART.md`) to add the row.

---

## 🃏 The deepest point

You didn't invent a fund org chart. You **rediscovered** it — because the problems a fund solves are universal (research, attention, memory, communication, ops). Your skill names are playful, but the underlying roles are 100 years old.

**Fun on the outside. Professional on the inside. The best of both.** 🏛️⚔️
