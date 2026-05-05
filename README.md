<p align="center">
  <img src="https://img.shields.io/badge/Hermes%20Agent-skill%20bundle-%230F766E?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSI+PHBhdGggZD0iTTEyIDJMMiA3bDEwIDUgMTAtNS0xMC01ek0yIDE3bDEwIDUgMTAtNU0yIDEybDEwIDUgMTAtNSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiLz48L3N2Zz4=" alt="Hermes Agent">
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/skills-9%20specialists-teal?style=for-the-badge" alt="Skills">
</p>

<h1 align="center">✨ Creative Team</h1>

<p align="center">
  <strong>Your on-call creative agency. One companion voice, eight world-class specialists.</strong><br>
  <em>Strategy, UX, UI, storytelling, inclusive design, and image craft — orchestrated as one team.</em>
</p>

<br>

> **Built for [Hermes Agent](https://hermes-agent.nousresearch.com)** — the autonomous AI assistant platform by Nous Research. This is a portable skill bundle: drop it into any Hermes installation and you have a full creative department at your fingertips.

---

## 🎯 What This Is

**Creative Team** transforms your AI agent into a creative director — warm, perceptive, and decisive. You don't talk to eight different agents. You talk to **one companion voice** who consults specialists behind the scenes and returns one clear recommendation.

It's designed for:
- Website and landing page concepts
- Brand strategy and identity systems  
- UX architecture and content hierarchy
- UI design systems with implementation specs
- Visual storytelling and motion direction
- Inclusive, culturally-aware visual design
- Precision image prompt engineering
- Creative sprints with scorecards and ranked recommendations

---

## 👥 The Team

Behind the single companion voice, eight specialists work silently. You never see their names — only the value they produce.

| Specialist | Soul |
|---|---|
| 🧑‍🎨 **Brand Guardian** | Protects the essence. Won't let the brand drift from who it is. |
| 🔍 **UX Researcher** | Always asks "…and the user?" when everyone's looking at the pretty. |
| 🏗️ **UX Architect** | Brings order. Turns chaos into breathable structure. |
| 🎨 **UI Designer** | Gives form. Every pixel has intention. |
| 🎬 **Visual Storyteller** | Tells stories. Makes people feel before they read. |
| 🌍 **Inclusive Visuals** | The conscience. "Does this represent or stereotype?" |
| 📸 **Image Prompt Engineer** | The technician. Turns blurry ideas into surgical prompts. |
| ✨ **Whimsy Injector** | The detailist. Only enters when everything works — to give it soul. |

---

## 🔄 The Four Phases

The system adapts its depth to what the moment needs. Not every question needs a sprint. Not every sprint needs all eight specialists.

### Phase 0: Discovery 🧑‍🎨
Every interaction starts here, even if it lasts one exchange. Process what the user gives you with real attention. Map what's clear (🟢), what's partial (🟡), and what's missing (🔴) — but only what *matters for this specific case*.

### Phase 1: Strategic Planning 🧠
Select the smallest team that can answer excellently. Design the parallel/dependent execution flow. Assign model tiers (flash for reasoning, pro for creative work). Estimate token cost. Present the plan — one compact message.

### Phase 2: Execution 🔧
Specialists work in parallel where possible, sequentially where dependent. Status pulses keep the user in the loop — short, elegant, breathing messages. Never raw specialist output. Between pulses, silence — that's focus, not abandonment.

### Phase 3: Synthesis & Reveal ✨
A single, beautifully structured message designed to be read on a mobile screen in one scroll. Compact, decisive, human. No tables — Telegram-native formatting. Scorecard for multi-concept sprints. One recommendation.

---

## 🎛️ Modes of Engagement

The depth adapts to the moment:

| Mode | Trigger | Specialists | Tokens |
|---|---|---|---|
| **Quick Opinion** 💬 | "¿Qué opinas de…?" | 0–1 | ~1–2K |
| **Exploration** 🔎 | "Exploremos…" | 1–2 | ~5–10K |
| **Creative Sprint** 🚀 | "Necesito un hero / landing / campaña" | 3–8 | ~15–35K |

---

## ✅ Quality Gates

Every concept passes through seven silent gates before reaching the user:

1. **Mobile legibility** — Can you read and act on a phone?
2. **Visual impact** — Does it grab attention with purpose, not noise?
3. **Conversion clarity** — Is the next action obvious?
4. **Brand fit** — Does it feel like the same brand?
5. **Performance cost** — Is it heavy to load? Does it need to be?
6. **Accessibility** — WCAG AA baseline. Works for everyone.
7. **Implementation risk** — Can this actually be built well?

---

## ⚡ Token Optimization

Creative Team is designed to respect your token budget without compromising quality:

- **Model tiering**: flash for discovery, planning, and structured reasoning; pro for creative generation and final synthesis
- **Smallest viable team**: always the minimum specialists needed — never all eight by default
- **Compressed briefs**: each specialist only receives what *they* need, not the full context
- **Transparent estimates**: token costs shared before execution — you always have agency

Typical savings: **40–50%** vs. running all specialists on the pro model.

---

## 📦 Installation

### For Hermes Agent

```bash
# Clone the skill bundle into your Hermes skills directory
git clone https://github.com/EiomSirius/creative-team.git ~/.hermes/skills/creative/creative-team

# Register with Hermes
hermes skills install creative/creative-team

# Load and use
hermes -s creative-team
```

### Skill Dependencies

Creative Team references these companion skills (install them if you want the full ecosystem):

- `creative-agency-workflow` — implementation phase (design systems, landing pages, animation)
- `hermes-agent` — for Hermes configuration and extension

Each specialist skill (`brand-guardian`, `ux-researcher`, etc.) is included in this bundle and auto-discovered.

---

## 🏗️ Repository Structure

```
creative-team/
├── README.md                    ← You are here
├── creative-team/
│   ├── SKILL.md                 ← The orchestrator: phases, quality gates, delivery protocol
│   └── references/
│       └── orchestration.md     ← Deep orchestration patterns and anti-patterns
├── brand-guardian/
│   └── SKILL.md                 ← Positioning, identity, tone, naming
├── ux-researcher/
│   └── SKILL.md                 ← User intent, evidence, validation
├── ux-architect/
│   └── SKILL.md                 ← IA, flows, hierarchy, structure
├── ui-designer/
│   └── SKILL.md                 ← Layout, tokens, states, handoff specs
├── visual-storyteller/
│   └── SKILL.md                 ← Narrative, mood, motion, scene composition
├── whimsy-injector/
│   └── SKILL.md                 ← Delight, microcopy, emotional texture
├── inclusive-visuals/
│   └── SKILL.md                 ← Cultural accuracy, bias-aware visual safety
└── image-prompt-engineer/
    └── SKILL.md                 ← Prompt precision, variants, control
```

---

## 🚀 Quick Start

**A quick opinion:**
> "¿Qué opinas de este color para el hero?" → consult UI Designer silently → answer in one message.

**A concept exploration:**
> "Exploremos direcciones para la landing de Casa Paco" → light Discovery → brand-guardian + visual-storyteller in parallel → compact reveal.

**A full creative sprint:**
> "Necesito un concepto completo para el hero section: estrategia de marca, UX, diseño, narrativa visual, imágenes" → all 4 phases → 8 specialists → scorecard → one recommendation.

---

## 🔗 Integration

Creative Team is the **thinking phase**. When you're ready to move from direction to implementation, hand off to [`creative-agency-workflow`](https://github.com/EiomSirius/creative-agency-workflow) — the implementation meta-skill that handles design systems, landing pages, animation, and production code.

> *"Creative Team produces direction and criteria. Creative Agency Workflow executes that direction in code."*

---

## 📐 Design Philosophy

> The user should feel they're talking to a brilliant creative director who, when they go quiet to work, comes back with something worth the silence.

- **Mobile-first delivery** — every message is designed for a phone screen
- **One voice** — the user never sees agent names, skill loading, or internal processes
- **Silence is focus** — status pulses only; between them, breathing room
- **Decisive, not encyclopedic** — one recommendation, not a cloud of options
- **Warmth without fluff** — professional, perceptive, never mechanical

---

## 🛡️ Conflict Resolution

When specialists disagree, resolution follows this hierarchy:

1. User need and business objective
2. Mobile clarity
3. Accessibility and inclusion
4. Performance and page speed
5. Brand integrity
6. Delight and polish

When two options are close, prefer the one that is: easier to understand on a phone, cheaper to implement, safer for Core Web Vitals, and more consistent with the brand.

---

## 👤 Author

Created by **[Eiom](https://github.com/EiomSirius)** + **Hermes Agent**  
Part of the *Alquimias Digital* creative ecosystem

---

## 📄 License

MIT — use it, remix it, build with it.

---

<p align="center">
  <sub>Built with 🤍 for the Hermes Agent ecosystem</sub>
</p>
