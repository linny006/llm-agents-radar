<!--
SEO: llm agents radar
-->

<div align="center">

# LLM Agents Radar

Live-updating index of LLM agent frameworks shipping on GitHub, refreshed every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/llm-agents-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llm-agents-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llm-agents-radar?style=for-the-badge)](https://github.com/linny006/llm-agents-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-8-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-27 12:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [oldfunk/paper-trading](https://github.com/oldfunk/paper-trading) | 1 | Python | 2026-10-27 | 本地事件驱动型模拟交易框架 |
| 2 | [xy547/bailian-agent-demo](https://github.com/xy547/bailian-agent-demo) | 0 | Python | 2026-10-27 | 阿里云百炼智能体应用（FlowAgent）+ 本地 Streamlit 调用 Demo，附 ai-agent-book 设计思想分析 |
| 3 | [areal-project/AReaL](https://github.com/areal-project/AReaL) | 5877 | Python | 2026-10-27 | The RL Bridge for LLM-based Agent Applications. Made Simple & Flexible. |
| 4 | [mukeshkbj/RegPulse](https://github.com/mukeshkbj/RegPulse) | 0 | TypeScript | 2026-10-27 | Regulatory change impact agent for UK financial firms: NVIDIA Nemotron (Nano + Ultra) on Nebius Token Factory, Tavily se |
| 5 | [memoways/ava-proto1](https://github.com/memoways/ava-proto1) | 0 | TypeScript | 2026-10-27 | Le prototype de l'expérience conversationnelle à partir d'un univers d'un film de fiction |
| 6 | [ljchang/mecha](https://github.com/ljchang/mecha) | 7 | Rust | 2026-10-27 | A standalone agent harness in Rust: a provider-agnostic loop, MCP tools, a path jail and prompt-injection interlock, san |
| 7 | [mensfeld/pocketrb](https://github.com/mensfeld/pocketrb) | 38 | Ruby | 2026-10-27 | Pocket-sized Ruby AI agent framework / LLM assistant with multi-LLM support |
| 8 | [muhammadalicusit56-glitch/otto-cognitive-nudge](https://github.com/muhammadalicusit56-glitch/otto-cognitive-nudge) | 137 | HTML | 2026-10-27 | Smart Promise Tracker AI 2026 – Commit Memory Engine |
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
