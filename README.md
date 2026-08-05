### Hi there, I'm [YB](https://github.com/MagnumGoYB). 👋
### 你好，我是 [YB](https://github.com/MagnumGoYB)。

I build with AI agents: I describe intent, agents write the code, and I review every diff.
Less typing, more designing. Vibe coding, backed by tests that actually run.

我使用 AI Agent 开发：我描述意图，Agent 编写代码，我审查每一份 diff。
少些重复输入，多些设计思考。Vibe Coding，但每次都用真实的测试来验证。

```bash
$ whoami
YB — AI Agent (Vibe Coding) developer

$ cat ~/.config/agents/stack.json
{
  "drivers":   ["opencode", "reasonix", "codex"],
  "languages": ["Go", "TypeScript", "JavaScript", "Solidity"],
  "capabilities": [
    "local-agent-memory",
    "token-cost-observability"
  ],
  "delivery": ["cli", "homebrew"],
  "verification": ["test-or-build", "diff-review"],
  "loop": "☕ coffee -> 💬 prompt -> 🧭 plan -> 💻 code -> 🔍 diff -> ✅ verify -> 🚀 ship -> 😴 sleep -> 🔁 repeat"
}
```

#### Agent Toolchain / Agent 工具链

| Tool | Role in my loop / 在我的工作流中的角色 |
| --- | --- |
| [opencode](https://opencode.ai) | Terminal-native agent for multi-file refactors, repo-wide context, MCP, and skills.<br>终端原生 Agent，适合多文件重构、全仓上下文、MCP 与技能扩展。 |
| [reasonix](http://reasonix.io/) | DeepSeek-native agent in a single Go binary. Stable prefix caching keeps long sessions efficient; `reasonix.toml` separates executor and planner sessions.<br>DeepSeek 原生 Agent，单个 Go 二进制文件。稳定的前缀缓存让长会话保持高效，`reasonix.toml` 将执行与规划会话分离。 |
| [codex](https://github.com/openai/codex) | Sandboxed execution for long-running implementation work and PR-sized changes.<br>通过沙箱执行长时任务与 PR 级别的代码变更。 |

#### Open Source / 开源参与

Projects I use in my AI-native development workflow.
以下是在 AI Agent 开发工作流中常用的开源项目。

| Project / 项目 | Use / 使用方向 |
| --- | --- |
| [OpenCode](https://opencode.ai) | Agent workflows, skills, MCP integrations, and developer feedback.<br>Agent 工作流、技能、MCP 集成与开发者反馈。 |
| [DeepSeek-Reasonix](http://reasonix.io/) | Configuration, agent workflows, evaluation, and prompt-cache efficiency.<br>配置、Agent 工作流、评测与提示词缓存效率。 |

#### How I Work / 我的工作方式

- **Spec first, code second.** Ambiguous prompts produce ambiguous diffs.<br>**先定义规格，再编写代码。** 模糊的提示只会产生模糊的 diff。
- **Small, verifiable steps.** Every agent run ends with a build or test, not a vibe.<br>**小步、可验证。** 每次 Agent 运行都以构建或测试结束，而非凭感觉。
- **Read every diff.** Agents are fast, not correct. Review is the real job.<br>**审查每一份 diff。** Agent 很快，但不一定正确；审查才是真正的工作。
- **Context is the product.** `AGENTS.md`, skills, and MCP servers improve output quality more than prompt tricks.<br>**上下文本身就是产品。** `AGENTS.md`、技能与 MCP 服务器比提示词技巧更能提升产出质量。
- **No stopgaps.** If a fix only works today, it is not a fix.<br>**拒绝权宜之计。** 一个只能解决今天问题的修复，不是真正的修复。

---

<img src="https://github-readme-stats-fast.vercel.app/api?username=MagnumGoYB&theme=dark&show_icons=true" />

<!--
**MagnumGoYB/MagnumGoYB** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
