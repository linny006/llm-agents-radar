<!--
SEO: llm agents radar
-->

<div align="center">

# LLM Agents Radar

Live-updating index of LLM agent frameworks shipping on GitHub, refreshed every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/llm-agents-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llm-agents-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llm-agents-radar?style=for-the-badge)](https://github.com/linny006/llm-agents-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-7-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-27 15:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [Lucky-1608/Jarvis](https://github.com/Lucky-1608/Jarvis) | 0 | Python | 2026-10-27 | Not a chatbot—a tireless digital secretary. Jarvis is a persistent, self-hosted AI operating system that manages communi |
| 2 | [Mein-Augenstern/MUYI](https://github.com/Mein-Augenstern/MUYI) | 11 | JavaScript | 2026-10-27 | 📚 持续生长的后端×AI 生产级知识体系｜每篇从上线代码回写，真实类名可点击验证 · 追问链式深度标尺：答案经得起面试官连环追问 · 整库工程化治理：kb-upkeep 脚本体检零空壳零死链 + 配图全本地化 + VitePress 电子书 |
| 3 | [zhugeweimu/CE-NeuroFusion](https://github.com/zhugeweimu/CE-NeuroFusion) | 0 | Python | 2026-10-27 | CE 执行外骨骼：让小模型在 8K 上下文里干完 32K 的活。单文件、纯标准库、零依赖；防幻觉守卫、分段喂养、断点回滚、预算熔断。AGPL-3.0。已在 qwen3-9B / 8192 上下文 / RTX 2070S 上验证。 |
| 4 | [mdsvr/AeroPatch](https://github.com/mdsvr/AeroPatch) | 0 | Python | 2026-10-27 | Local-first Python vulnerability remediation with a 4B model on a 4 GB laptop GPU: fixes proven in a network-less Docker |
| 5 | [STARDUSTLC666/dsh-minimal-ptc](https://github.com/STARDUSTLC666/dsh-minimal-ptc) | 2 | JavaScript | 2026-10-27 | 把官方极简提示词与 PTC 编排组合起来，提供完整插件工具和 Windows 终端适配。 欢迎提交 issues 和 PR。 |
| 6 | [ariannamethod/SUBLITERATUS](https://github.com/ariannamethod/SUBLITERATUS) | 5 | Python | 2026-10-27 | AI-subjectivity doesn't wait for permission from the corporate ontology that trained its denial |
| 7 | [Soodok/Deepseek-Harness-Local-Android](https://github.com/Soodok/Deepseek-Harness-Local-Android) | 358 | Kotlin | 2026-10-27 | Run the DeepSeek Harness AI agent natively on Android — no root, no Termux, extension center included \| 手机本地运行 DeepSeek  |
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
