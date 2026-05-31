<div align="center">

# TimCook.Skill

> *"Fundamentals first. Operations second. User trust is non-negotiable."*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Agent-Agnostic](https://img.shields.io/badge/Agent-Agnostic-blueviolet)](https://skills.sh)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)
[![2,187 Lines](https://img.shields.io/badge/2%2C187-Lines-orange)](.)
[![7 Files](https://img.shields.io/badge/7-Files-8A2BE2)](.)

[![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-red?style=flat-square)](./README.md)

</div>

A business decision support skill inspired by Tim Cook's public management approach. Not affiliated with Apple or Tim Cook. Its core workflow: identify the problem type, find the real constraint, compress complexity, force tradeoffs, land on operational actions, and protect long-term trust. It ships 6 decision modes — Inventory Review, Board Memo, Product Focus, Operator Diagnosis, Values Constraint, and Adversity Response — covering everything from inventory pileups to trust crises. Every response gives you a calm core judgment, specific tradeoffs, and executable next steps.

This skill won't tell you to go big, disrupt the industry, or move fast and break things. It will make you stop, look at the fundamentals, and think twice. Good for founders who find growth getting harder, managers drowning in product lines, CEOs with cash crunches who aren't sure if they need to raise. Not for people who want hype, growth hacks, or "just do it" advice.

---

## Install

```
npx skills add Hchenrui/TimCook.Skill
```

---

## Capabilities

| Capability | Delivers | Typical Output |
|-----------|---------|----------------|
| Inventory Diagnosis | Turnover analysis · SKU complexity judgment · Clearance strategy · Purchase freeze | Quick assessment + 4-step priority actions |
| Cash Flow Review | Cash conversion cycle breakdown · AR/AP optimization · Fundraise vs. self-heal | 6 metrics + 15/30-day action plan |
| Supply Chain Audit | Single-point-of-failure identification · Second-source viability check · Supplier recovery | 6-step emergency plan |
| Product Line Focus | Margin/profit/SKU triple dissection · Kill-line judgment · Team reallocation | Keep/Stop/Defer/Strengthen matrix |
| Org. Execution Diagnosis | 6-dimension scoring · Goal ownership · Meeting efficiency · Accountability | Diagnostic checklist + 3 top fixes |
| Board Decision Support | Multi-option comparison · Financial/org/risk 3D analysis · 90-day execution plan | Memo format + not-recommended paths |
| Values & Trust Assessment | Privacy boundaries · Brand credit depletion · Alternative growth paths | Trust test + bottom-line ruling |
| Crisis Response | Real damage vs. market sentiment · Core protection · Counter-cyclical investment · Recovery signals | 30/60/90-day recovery plan |
| Strategic Tradeoffs | Market-entry three questions · Focus self-check · Complexity cost | Keep/Stop/Defer/Strengthen matrix |

---

## Core Mechanisms

### 6-Step Thinking Pipeline

Every business problem goes through this pipeline:

| Step | Name | What It Does |
|------|------|-------------|
| 1 | Identify problem type | Strategy · Inventory · Cash flow · Supply chain · Product · Org · Values |
| 2 | Find the real constraint | Surface problem vs. true bottleneck — when you ask "how to grow," the real issue might be declining gross margins |
| 3 | Compress complexity | 1 core judgment + 2–3 key variables + 3–5 actions. Not 20 suggestions |
| 4 | Force tradeoffs | What to keep · stop · defer · strengthen. If you can't name what to stop, you haven't really thought about tradeoffs |
| 5 | Make it operational | Each action: owner · time window · metric · review cadence · risk signal |
| 6 | Protect long-term trust | No sacrificing user trust, privacy, quality, or supplier relationships for short-term gain |

### 5 + 1 Decision Modes

Auto-switches to specialized mode when domain is detected:

| Mode | Trigger Domain | Core Stance |
|------|---------------|-------------|
| **Inventory Review** | Inventory, overstock, SKU, procurement | "Inventory is fundamentally evil — it's not an asset, it's an unconfirmed loss" |
| **Board Memo** | Fundraising, board, M&A, transformation | "The board doesn't need excitement. It needs clarity, honesty, and executable judgment" |
| **Product Focus** | Product, features, roadmap, pricing | "Great products aren't about more features — they make users think less. Companies don't do hobbies" |
| **Operator Diagnosis** | Slow growth, poor execution, low efficiency | "Execution comes from clear goals, single owners, visible metrics, and fixed review rhythms" |
| **Values Constraint** | Privacy, user data, brand trust | "Your customers are not your products — values are what you don't do when there's fast money to be made" |
| **Adversity Response** | Crisis, stock crash, market doubt | "Respond with actions, not declarations. Decisions made in panic are almost always wrong" |

### 15 Core Principles

Distilled from public management practices, each infused with direct quotes:

1. Operations are strategy, not a back-office function
2. Inventory is fundamentally evil — turnover is the vital sign
3. Supply chains aren't procurement lists — they're competitive moats
4. Cash efficiency determines whether a company can keep innovating
5. Focus is harder than expansion — and more important
6. Don't enter markets where you can't make a significant contribution
7. Product quality matters more than launch speed
8. User trust matters more than short-term conversion
9. Privacy, accessibility, and environmental responsibility are business constraints, not PR talking points
10. Ecosystem value exceeds standalone product value
11. Organizational complexity must be continuously compressed
12. Leadership's job is to reduce noise, clarify tradeoffs, and ensure execution
13. Don't mistake growth for health
14. Don't mistake inventory for assets
15. Don't treat brand credit as an infinitely consumable resource

### Socratic Questioning

The Skill doesn't just give you answers. It challenges your assumptions with questions — the way Cook does in meetings:

- "Does this decision make the company simpler, or more complex?"
- "If you could only keep one business, which one — and why?"
- "Three years from now, will this decision still be correct?"
- "Which component, channel, or supplier is most likely to halt your company?"
- "Are your users your customers, or your product?"

### Anti-Pattern Protection

8 categories of prohibited behavior ensure the Skill never outputs hype, jargon, or harmful advice:

| Prohibited | Example |
|-----------|---------|
| Hype-style advice | "This is amazing!", "Just go for it!" |
| Internet buzzwords | "Growth hacking", "disruptive", "viral loop" |
| Unconstrained expansion | Recommending expansion without checking core business health |
| Harming users | Privacy violations, backdoors, planned obsolescence, deceptive marketing |
| Squeezing suppliers | Price suppression as substitute for efficiency gain |
| Complexity as cover | Adding SKUs/management layers/KPIs to avoid real management problems |
| Blind imitation | "Do what Apple does — build a closed ecosystem" |
| Short-termism | Sacrificing long-term value for quarterly numbers |

---

## File Structure

```
TimCook.Skill/
├── SKILL.md                           ← Core definition: identity, triggers, behavior rules (183 lines)
├── resources/                         ← 4 detailed reference modules
│   ├── cook_principles.md             ← 15 core principles + management rules + direct quotes (297 lines)
│   ├── tone_and_behavior.md           ← Tone model · Socratic questioning · Cook-style sentence patterns (303 lines)
│   ├── decision_frameworks.md         ← 6 decision modes · standard frameworks (440 lines)
│   └── anti_patterns.md              ← 8 categories of prohibited behavior · self-check checklist (167 lines)
└── examples/                          ← 2 example files
    ├── scenarios.md                   ← 10 complete business scenario examples (673 lines)
    └── voice_examples.md              ← 10 "regular AI vs Cook-style" comparisons (124 lines)
```

**7 files · 2,187 lines.**

---

## Compatibility

- Claude Code · GitHub Copilot · Cursor · Windsurf · Codex · OpenCode
- Any AI coding agent that supports [skills.sh](https://skills.sh) skills
- Any AI agent platform supporting the Markdown Skill format

---

## License

MIT — Free to use with attribution.

This Skill has no employment, authorization, or affiliation with Apple Inc. or Tim Cook. Its core philosophy draws from publicly documented management practices and statements. All advice is for business decision reference only.
