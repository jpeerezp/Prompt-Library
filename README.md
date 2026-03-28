# 📚 Prompt Library — "The Digital Twin Model"

> **Assessment 1 | Generative AI for Business**

> Student: Jorge Perez

> Business Field: Addresing Match Congestion in Elite Football.

> Model tested on: Claude Sonnet 4.6, GPT-5mini, Gemini 3.

> Last updated: 27/03/2026

---

## What This Library Does

This prompt library supports workflow automation during high-intensity 4–5 day congested match cycles, allowing the board of directors to protect their most valuable assets from injury and avoid million-dollar losses. The "Digital Twin" model optimizes the recovery, neural readiness, and tactical execution of elite football players, who are multi-million-dollar assets of a football club.

Each prompt entry follows the same structure:

- The exact prompt text (with placeholders)

- The workflow task it supports

- The problem it solves

- Its automation potential

- Known risks and mitigations

- Version history

- Test results

---

## 📂 Folder Structure

```
prompt-library/
│
├── README.md                        ← You are here (library index)
│
├── 01-The Digital Twin Foundation/
│   ├── README.md                    ← Section overview
│   ├── P01-The-Digital-Twin-Shell.md
│   ├── P02-The-Physical-Pillar.md
│   ├── P03-The-Technical-and-Tactical-Pillars.md
│   └── P04-The-Cognitive-and-Emotional-Pillars.md
│
├── 02-The High-Performance Microcycle/
│   ├── README.md
│   ├── P05-The-Recovery-Window.md
│   ├── P06-The-Readiness-Convergence.md
│   ├── P07-The-Tactical-Analysis.md
│   └── P08-The-Squad-List.md
│
└── 04-The-Executive-Decision/
    ├── README.md
    ├── P09-The-Dahboard.md
    └── P10-The-Starting-XI.md

```

---

## 📊 Library Summary Table

| ID | Prompt Name | Workflow | Automation Level | Risk Level | Status |
|----|-------------|----------|-----------------|------------|--------|
| P01 | The Digital Twin Shell | Baseline | Medium | Low | ✅ Tested |
| P02 | The Physical Pillar | Baseline | Very High | Low | ✅ Tested |
| P03 | The Technical & Tactical Pillars | Baseline | High | Medium | ✅ Tested |
| P04 | The Cognitive and Emonional Pillars | Baseline | Medium | High | ✅ Tested |
| P05 | The Recovery Window | Analytic | High | Low | ✅ Tested |
| P06 | The Readiness Convergence | Analytic | High | Medium | ✅ Tested |
| P07 | The Tactical Analysis | Analytic | High | High | ✅ Tested |
| P08 | The Squad List | Operational | High | Medium | ✅ Tested |
| P09 | The Dashboard | Operational | Very High | Medium | ✅ Tested |
| P10 | The Starting XI | Executive | High | Medium | ✅ Tested |

**Automation levels:** Very High / High / Medium / Low  
**Risk levels:** High (always needs human review) / Medium (spot-check recommended) / Low (can automate with audit)

---

## 🔗 Prompt Chaining Map

Some prompts in this library are designed to work in sequence. The chains below show how outputs from one prompt feed the next.

```
🧬 THE RECOVERY CHAIN (MD+1 to MD+2)
This sequence identifies the metabolic and mental "decay" post-match to choose the intervention.
└── P01 + P02 (Post-Match Data) → P04 (Emotional/Neural Status) → P05 (Metabolic Recovery Pathway)

⚙️ THE OPERATIONAL CHAIN (MD+2 to MD+3)
This sequence merges the player's biological reality with the coach's tactical requirements.
└── P05 (Recovery Status) + P04 (Mental Status) → P06 (Readiness Convergence) → P07 (Tactical Logistics/Pitch Dimensions)

🚀 THE EXECUTION CHAIN (MD-1 to Kickoff)
The final filter for selecting the travel squad and issuing the stadium "Go" signal.
└── P06 (Convergence) + P07 (Tactical) → P08 (The Squad List) → P09 (Executive Dashboard) → P10 (Final Green Light)
```

---

## ⚙️ Prompting Strategies Used

| Strategy | Prompts | Why chosen |
|----------|---------|------------|
| Image generation | P01 | Ensures output is visually ready without heavy editing |
| RACE framework (Role–Action–Context–Evaluation) | All | Consistent structure; comparable outputs for A/B testing |
| Grounding constraint ("using only...") | P02, P03, P04, P05, P06, P07, P08 | Prevents hallucination in factual/legal contexts |
| JSON output format | P02, P03, P04, P05, P06, P07, P08 | Machine-readable for CRM/API integration |
| Self-critique step | P02, P03, P04 | Model reviews its own output for unsupported inferences |
| HTML output format | P09, P10 | Best method to display text, images and dynamic features |

---

## 📝 Iteration Evidence

All prompt versions are saved in this repository. See individual prompt files for version histories.  
**Commit history = version log** — each commit message describes what changed and why.

| Prompt | Versions | Key improvement |
|--------|----------|-----------------|
| P01 | v1.0 → v1.2 | Added RACE role; edit time 14 min → 2 min |
| P02 | v1.0 → v1.1 | Grounding constraint added after v1.0 hallucinated causes |
| P04 | v1.0 → v1.21 | Grounding constraint added after v1.0 missed data |

---

## 📖 References

- Anthropic (2025). *Prompt Engineering Overview.* docs.claude.ai
- GitHub (2025). *Get Started with Prompt Library.*
- Google (2026). *Prompt Drafting.*
- One Drive (2026). *Dr. Mills - prompt-library-template*
- Barca Innovation Hub (2025). *Digital Twins at Barca — AI to prevent injuries.*
- SportPro (2026). *How digital twins are recreating sport in the virtual world.*
