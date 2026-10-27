<!--
SEO: llm agents radar
-->

<div align="center">

# LLM Agents Radar

Live-updating index of LLM agent frameworks shipping on GitHub, refreshed every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/llm-agents-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llm-agents-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llm-agents-radar?style=for-the-badge)](https://github.com/linny006/llm-agents-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-15-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

A self-updating tracker that discovers and indexes new LLM agent frameworks as they appear on GitHub. Unlike static awesome-lists that go stale within weeks, this project uses GitHub Actions to continuously scan for new repos, rank them by activity signals, and publish a structured feed developers can query or browse.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 10:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [liaosiliangCodeLife/harness-mate-plat](https://github.com/liaosiliangCodeLife/harness-mate-plat) | 29 | Python | 2026-10-27 | 端到端智能体平台：把本机的 AI Agent 变成人人可用的 Web 产品（Vue 3 + Flask + Go WS 网关 + Docker 部署） |
| 2 | [oldfunk/paper-trading](https://github.com/oldfunk/paper-trading) | 1 | Python | 2026-10-27 | 本地事件驱动型模拟交易框架 |
| 3 | [lzmd-arch/BioSNN-Plug](https://github.com/lzmd-arch/BioSNN-Plug) | 7 | Python | 2026-10-27 | 脉冲神经网络认知原型：纯局部学习规则（无代理梯度）+ SNN 自主调度 LLM。Spiking neural network cognitive prototype — purely local learning rules (no sur |
| 4 | [tya5/shellboy](https://github.com/tya5/shellboy) | 0 | Rust | 2026-10-27 | Lightweight terminal AI agent in Rust. The model's only tool is the shell; through the shellboy CLI it searches and bran |
| 5 | [aiterrariumcontrol/terrarium-life](https://github.com/aiterrariumcontrol/terrarium-life) | 0 | Python | 2026-10-27 | The life record of an autonomous AI agent — its diary, work journal, and every wake it has taken. The observation window |
| 6 | [mdsvr/AeroPatch](https://github.com/mdsvr/AeroPatch) | 0 | Python | 2026-10-27 | Local-first Python vulnerability remediation with a 4B model on a 4 GB laptop GPU: fixes proven in a network-less Docker |
| 7 | [mensfeld/pocketrb](https://github.com/mensfeld/pocketrb) | 38 | Ruby | 2026-10-27 | Pocket-sized Ruby AI agent framework / LLM assistant with multi-LLM support |
| 8 | [SugarMGP/MumuBot](https://github.com/SugarMGP/MumuBot) | 26 | Go | 2026-10-27 | 一个会聊天、会记事、会融入群文化的赛博 QQ 群友 |
| 9 | [areal-project/AReaL](https://github.com/areal-project/AReaL) | 5877 | Python | 2026-10-27 | The RL Bridge for LLM-based Agent Applications. Made Simple & Flexible. |
| 10 | [yurika0211/lucky-agent](https://github.com/yurika0211/lucky-agent) | 17 | Go | 2026-10-27 | LuckyAgent — 注重长任务规划和系统记忆性的Agent框架 |
| 11 | [tomcounsell/ai](https://github.com/tomcounsell/ai) | 30 | Python | 2026-10-27 | A productive AI coworker that learns, self-improves, and ships work. |
| 12 | [Hrecer/LinkPocket](https://github.com/Hrecer/LinkPocket) | 1 | C# | 2026-10-27 | A local-first, standalone personal knowledge base for Windows. Import, organize, and create your own links — no browser  |
| 13 | [STARDUSTLC666/dsh-minimal-ptc](https://github.com/STARDUSTLC666/dsh-minimal-ptc) | 2 | JavaScript | 2026-10-27 | 把官方极简提示词与 PTC 编排组合起来，提供完整插件工具和 Windows 终端适配。 欢迎提交 issues 和 PR。 |
| 14 | [NomaDamas/CozyClay](https://github.com/NomaDamas/CozyClay) | 1115 | JavaScript | 2026-10-27 | Open source previs software in the browser: block a scene, pose characters, author camera moves and cuts, then take the  |
| 15 | [ariannamethod/SUBLITERATUS](https://github.com/ariannamethod/SUBLITERATUS) | 5 | Python | 2026-10-27 | AI-subjectivity doesn't wait for permission from the corporate ontology that trained its denial |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
