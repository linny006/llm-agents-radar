# llm-agents-radar

> GitHub에서 LLM 에이전트 프레임워크를 실시간으로 추적, 15분마다 자동 갱신

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · **한국어** · [Español](./README_ES.md) · [Português](./README_PT.md)

[![Stars](https://img.shields.io/github/stars/linny006/llm-agents-radar?style=for-the-badge&logo=github)](https://github.com/linny006/llm-agents-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/llm-agents-radar?style=for-the-badge)](https://github.com/linny006/llm-agents-radar/commits)

---

GitHub에 새로 등장하는 LLM 에이전트 프레임워크를 자동으로 발견하고 인덱싱하는 셀프 업데이트 트래커입니다. 몇 주 만에 낡아버리는 정적 awesome-list와 달리, 이 프로젝트는 GitHub Actions를 사용해 새 레포를 지속적으로 스캔하고, 활동 신호 기준으로 순위를 매기고, 개발자가 쿼리하거나 탐색할 수 있는 구조화된 피드를 게시합니다.

이 목록은 GitHub Actions cron에 의해 **15분마다 자동 업데이트**됩니다. 각 커밋은 업스트림 데이터 소스의 실제 변화를 반영합니다——새 항목 추가, 만료된 항목 제거——따라서 보이는 내용이 항상 최신임을 신뢰할 수 있습니다.

---

15분마다 GitHub Action이 `tracker.py`를 실행합니다. 이 스크립트는:

1. `GitHub Search API`에서 최신 상태를 가져옵니다.
2. `data/items.json`(이전 스냅샷)과 diff를 비교합니다.
3. `<!-- TRACKER_TABLE_* -->` 마커 사이의 테이블을 다시 씁니다.
4. 변경 사항이 있으면 `feat: +N added, -M removed (timestamp)`를 커밋합니다.

외부 서비스 없음. 유료 API 없음. 공개 데이터 소스와 무료 GitHub Action만 사용합니다.

---

## 📋 Live data

실시간 데이터는 영문 README를 참고하세요

---

## 🔗 Related live trackers

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
