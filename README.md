# ⚡ VibeFoundry — Autonomous Agent Infrastructure

Building deterministic **Design Systems**, **Application Security**, and **Self-Healing Browser QA** infrastructure for autonomous coding agents (**Claude Code**, **OpenAI Codex**, **Cursor**, **Windsurf**, and **MCP**).

---

## 🛠️ The VibeFoundry Open-Source Suite

| Project | Category | CLI / MCP Quickstart | What It Solves |
| :--- | :--- | :--- | :--- |
| 🎨 **[unslop](https://github.com/avivgerz-hue/unslop)** | **UI Design Systems & Anti-Slop Engine** | `npx unslop init` | Eliminates generic "AI Slop" interfaces. Extracts live Design DNA from any URL, audits WCAG contrast & Tailwind v4 tokens, and enforces studio-grade design physics via `SKILL.md` & MCP. |
| 🛡️ **[vibe-shield](https://github.com/avivgerz-hue/vibe-shield)** | **AI Code Security & MCP Auditor** | `npx vibe-shield scan` | High-speed static security analyzer catching the exact vulnerabilities AI agents introduce: leaked `NEXT_PUBLIC_` keys, unguarded API routes, missing Supabase RLS, and poisoned MCP skills. |
| 👻 **[ghost-qa](https://github.com/avivgerz-hue/ghost-qa)** | **Autonomous Headless Browser QA** | `npx ghost-qa test` | Stops coding agents from shipping broken UI blind. Spins up headless Chromium across Desktop & Mobile with a 5-Trap Engine (Console, Network, Layout, A11y, Perf) and Native MCP Server. |

---

## 🔄 The Autonomous Agent Reliability Loop

```text
  ┌─────────────────────────────────────────────────────────────────────┐
  │ 1. DESIGN (unslop)                                                  │
  │    Enforces studio typography, semantic color tokens & spatial grid │
  └──────────────────────────────────┬──────────────────────────────────┘
                                     ▼
  ┌─────────────────────────────────────────────────────────────────────┐
  │ 2. VERIFY AT RUNTIME (ghost-qa)                                     │
  │    Headless Chromium crawls localhost & traps Console/Net/A11y bugs │
  └──────────────────────────────────┬──────────────────────────────────┘
                                     ▼
  ┌─────────────────────────────────────────────────────────────────────┐
  │ 3. HARDEN SECURITY (vibe-shield)                                    │
  │    Audits API auth guards, secret entropy, RLS policies & MCP files │
  └─────────────────────────────────────────────────────────────────────┘
