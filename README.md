<div align="center">

<img src="img/hero.svg" alt="SS · sscodeai — Agentic SWE, AI Delivery Platform Engineer in Japan" width="100%" />

**[www.sscodeai.com](https://www.sscodeai.com)** · **[sscodeai.com](https://sscodeai.com)** · **[@SSCodeAI](https://x.com/SSCodeAI)**

</div>

---

I build AI that must survive production: **affordable, trustworthy, accountable.** My work is organized around one belief — AI entering enterprise production has to pass three gates at once, and I build a system for each gate.

---

## 🔐 Safe — distrust the input, distrust the keys

- **[aiitg](https://github.com/sscodeai/aiitg)** — AI Input Trust Gateway: hidden-content auditor for documents fed to LLMs and agents (zero-width chars, white text, hidden sheets). 102 tests.
- **[keysmith](https://github.com/sscodeai/keysmith)** — Go MCP server + CLI for agent-safe secrets: age-encrypted, masked views, self-healing rotation. Plaintext never enters agent context.

## 💰 Frugal — every token spent where it counts

- **[fusion-cache](https://github.com/sscodeai/fusion-cache)** — LLM API caching middleware: exact-match → semantic → upstream prefix-cache. 91 tests, up to 97% cost cut.
- **[dsh-llm-cache](https://github.com/sscodeai/deepseek-harness/tree/feat/llm-cache/packages/llm/llm-cache)** — LLM response cache merged upstream into DeepSeek Harness (`@deepseek-ai/dsh-llm-cache`).

## ✅ Verified — agents propose, humans decide

- **[takumi](https://github.com/sscodeai/takumi)** — model-agnostic platform for verifiable agentic software delivery: Manager / Executor / Auditor, verify-fail → repair → re-verify. 87/87 tests; 23-task eval 96% first-pass → 100% final.
- **[proctor](https://github.com/sscodeai/proctor)** — agent eval: score, audit and explain agent trajectories, with metrics and causal failure attribution.
- **[decision-workbench](https://github.com/sscodeai/decision-workbench)** — expand the decision space before you decide: multi-model committee + human final call. Hidden-gold eval: 26% → 78% → 100% (12/12).
- **[decision-space-expansion](https://github.com/sscodeai/decision-space-expansion)** — the methodology behind decision-workbench, as a portable Agent Skill (EN/JA). Works with Claude Code, Cursor, Codex and Gemini CLI.

## 🌏 Japanese-market work

- **[agency-agents-ja](https://github.com/sscodeai/agency-agents-ja)** — 323 production-ready AI agents for Japanese dev teams, for Claude Code / Cursor / Copilot.
- **[skills-ja-JP](https://github.com/sscodeai/skills-ja-JP)** · **[superpowers-ja](https://github.com/sscodeai/superpowers-ja)** — Japanese localizations of engineering skill packs for AI coding agents.

---

<div align="center">

**[www.sscodeai.com](https://www.sscodeai.com)** — portfolio: story, résumé, project deep-dives\
**[sscodeai.com](https://sscodeai.com)** — product docs, tutorials & Japanese-market agent toolkits

</div>
