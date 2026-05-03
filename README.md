<div align="center">

<a href="https://agent8.org">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=36&duration=3000&pause=1000&color=C0392B&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=%E2%96%B2+Agent+8" alt="Agent 8" />
</a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&duration=2500&pause=800&color=8B6914&center=true&vCenter=true&multiline=false&repeat=true&width=720&height=30&lines=Multi-Agent+Orchestration+%C2%B7+Headless+Architecture+%C2%B7+MCP+Integration" alt="Tagline" />

<br/>

**Exploring autonomous multi-agent orchestration and scalable AI architectures.**

An experimental multi-agent system where 8 specialized roles collaborate,
debate, and execute tasks within a constrained, evidence-based environment.

<br/>

[![Website](https://img.shields.io/badge/Agent_8-agent8.org-C0392B?style=for-the-badge&logoColor=white)](https://agent8.org)
[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio.greatpola.com-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio.greatpola.com)
[![Email](https://img.shields.io/badge/Contact-media@greatpola.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:media@greatpola.com)
[![Coffee Chat](https://img.shields.io/badge/Coffee_Chat-Book_Now-4285F4?style=for-the-badge&logo=googlecalendar&logoColor=white)](https://calendar.google.com/calendar/appointments/schedules/AcZssZ3KV-c-giEe6I_6RaAmWbJMMfYaRFbH7cQYfvNJcRVR1jSxLAm3xIUxuu2a_5Fe-EbG5Uo6ifRb?gv=true)

</div>

---

## What is Agent 8?

Agent 8 is an **experimental multi-agent orchestration system**. It explores how specialized AI agents (planning, design, engineering, security, and operations) can collaborate within a shared workspace. The system is governed by a set of strict rules (Iron Laws) designed to minimize hallucination, enforce predictable execution, and maintain code quality.

### The 8 Partners

| Partner | Silo | Domain |
|:---:|:---|:---|
| 👑 | **Andrew** (앤드류) | **Lead** — Task decomposition, partner routing, final decision-making |
| 🧠 | **Dani** (다니) | **Strategy** — PRD authoring, opportunity-solution trees, user research |
| 🎨 | **Yuna** (유나) | **UI/UX** — Design tokens, visual consistency, accessibility (A11y) |
| 💻 | **Kai** (카이) | **Dev/Engine** — Architecture, auto-heal, security hardening, CI/CD |
| 📈 | **Miso** (미소) | **Growth** — SEO/AEO/GEO strategy, copywriting, A/B testing |
| 🛡️ | **Rex** (렉스) | **Security** — OWASP audit, GDPR, IAM/Firestore rules review |
| 🤝 | **Juno** (주노) | **Business** — B2B pipeline (CRM), ROI analysis, customer success |
| 📝 | **Hana** (하나) | **Admin** — Meeting notes, documentation sync, operations scheduling |

---

## System Architecture

```text
┌──────────────────────────────────────────────────────────────┐
│                    AGENTS.md (17 Iron Laws)                   │
│                                                              │
│  Constrain · Verify · Inform · Correct · Scale               │
│  Debt Mgmt · Anti-Copy · Terminal First · Anti-Stagnation    │
│  Zero-Command · D/R/O Responsibility · Promotion Gate        │
│  No-BS · Handover · Usability First                          │
│  Headless Brain-Only Architecture                            │
├──────────────────────────────────────────────────────────────┤
│              Headless Agent Architecture                      │
│  Server-side IP isolation · API-first communication          │
│  Swappable UI skins · Firebase Functions core                │
├──────────────────────────────────────────────────────────────┤
│  📂 53 Skills (18 active · 35 archived)                      │
│  📂 6 Workflows     📂 12 Monorepo Packages                 │
│  📂 19 Service Domains    📂 14 Route Groups                 │
├──────────────────────────────────────────────────────────────┤
│  D/R/O Responsibility: [D] Delegate → [R] Review → [O] Own  │
│  Quality: typecheck → lint:strict → test → deploy            │
└──────────────────────────────────────────────────────────────┘
```

### Key Engineering Concepts

- **Headless Brain Architecture**: The core logic (prompts, coordination, state) is strictly isolated on the server-side (Firebase Functions). The client is merely a swappable UI skin communicating via APIs.
- **Model Context Protocol (MCP)**: Safely bridges the LLM with local and cloud environments, providing tools for browser automation, terminal access, and open knowledge graphs (`mcp-openrag`, `mcp-pptx`).
- **SSE-based Discussion Pipeline**: Inter-agent debates and consensus-building are streamed in real-time to the client via Server-Sent Events, ensuring transparency.
- **D/R/O Responsibility Framework**: Changes are strictly categorized. Safe modifications (`[D] Delegate`) are auto-executed. Business logic changes require review (`[R] Review`), and critical infrastructure/security updates (`[O] Own`) demand explicit human authorization.

## Getting Started

Access to the Agent 8 CLI and MCP adapters is available to registered developers.

1. **Sign in to the Workspace**: Visit [agent8.org](https://agent8.org) and authenticate.
2. **Setup CLI & MCP**: Once logged in, your workspace dashboard provides the necessary tokens and documentation to install the `agent8-cli` via NPM and configure your local MCP environments.

### Workflows

| Command | Description |
|:---|:---|
| `/plan` | Research, consensus, iterative planning |
| `/dev` | Dev server, build, dead-code removal, E2E |
| `/review` | 4-stage quality gate + security audit |
| `/deploy` | Build → Quality guard → Firebase deploy |
| `/execution-harness` | Proof-of-work consensus workflow |
| `/auto-heal` | Safe patch generation for build errors |

### Monorepo Packages

| Package | Purpose |
|:---|:---|
| `core-types` | Shared TypeScript interfaces & enums |
| `agent-utils` | Common utility functions for agents |
| `agent-server` | Standalone agent server runtime |
| `agent8-cli` | CLI tool (`agent8 audit`, `agent8 heal`) |
| `mac-app` | Electron-based Mac desktop application |
| `browser` | Chrome Extension for browser integration |
| `browser-agent-api` | Browser-side agent API bridge |
| `mcp-agents` | Model Context Protocol agent adapters |
| `mcp-openrag` | OpenRAG knowledge graph integration |
| `mcp-pptx` | PowerPoint generation via MCP |
| `discord-daemon` | Discord bot for multi-channel ops |
| `tts-server` | Text-to-Speech server (Web Audio streaming) |

---

## Projects Showcase

### Live Domains

| Domain | Description |
|:---|:---|
| [**agent8.org**](https://agent8.org) | Agent 8 — AI Partner platform, workspace, downloads |
| [**portfolio.greatpola.com**](https://portfolio.greatpola.com) | Interactive portfolio of AI-native project outputs |
| [**scentwiki.io**](https://scentwiki.io) | Global fragrance encyclopedia with AI recommendations |
| [**marketing.picoinnov.com**](https://marketing.picoinnov.com) | Real-time KPI dashboard for pharmacy marketing |
| [**partners.picoinnov.com**](https://partners.picoinnov.com) | Pharma talent matching & recruitment platform |
| [**finance.greatpola.com**](https://finance.greatpola.com) | AI-powered corporate finance analyzer |

### Highlighted Products

| | Project | Description | Stack |
|:---:|:---|:---|:---|
| ▲ | **[Agent 8](https://agent8.org)** | Autonomous AI partner platform — 8 agents orchestrate, debate, and ship code. Mac App + Chrome Extension + API. | `Multi-Agent` `MCP` `Living Software` |
| 🌸 | **[Scentwiki](https://scentwiki.io)** | Global fragrance encyclopedia with AI-driven reviews and recommendations. | `Next.js` `Firestore` `AI Search` |
| 📊 | **[Marketing KPI](https://marketing.picoinnov.com/)** | Real-time strategic insights and campaign management for pharmacy marketing. | `Data Viz` `Real-time KPI` `Firebase` |
| 🤖 | **[PicoFriends](https://picofriends-6d48f.web.app)** | AI simulation where pharmacy students experience MR roles in realistic scenarios. | `AI Simulation` `Roleplay` `Analytics` |
| 💼 | **[Pharma Talent](https://partners.picoinnov.com)** | Industry-specialized recruitment connecting pharmacists and pharma companies. | `Matching` `CRM` `Alerts` |
| 📈 | **[Finance](https://finance.greatpola.com/)** | AI-powered corporate finance analyzer with automated market insights. | `AI Finance` `Reports` `Automation` |

---

## Tech Stack

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript_5-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-886FBF?style=flat-square&logo=google&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Discord](https://img.shields.io/badge/Discord_Bot-5865F2?style=flat-square&logo=discord&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white)

</div>

---

## By The Numbers

<div align="center">

| Metric | Count |
|:---:|:---:|
| **Iron Laws** | 17 |
| **Partner Silos** | 8 |
| **Domain Skills** | 53 |
| **Workflows** | 6 |
| **Service Domains** | 19 |
| **Route Groups** | 14 |
| **Monorepo Packages** | 12 |
| **Supported Languages** | 3 (ko · en · ja) |
| **Quality Gates** | 4 (typecheck · lint · test · deploy) |
| **Responsibility Tiers** | 3 (D · R · O) |

</div>

---

<div align="center">
  <sub>© 2026 Antigravity · Built with Agent 8</sub>
</div>
