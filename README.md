### Hi there, I'm [YB](https://github.com/MagnumGoYB). 👋

I build with AI agents. Less typing, more designing: I describe intent, agents write the code,
I review the diff. Vibe coding, but with tests that actually run.

```bash
$ whoami
YB — AI Agent (Vibe Coding) developer

$ cat ~/.config/agents/stack.json
{
  "drivers":   ["opencode", "codex", "reasonix"],
  "languages": ["TypeScript", "JavaScript", "Go", "Solidity"],
  "loop":      "prompt -> plan -> diff -> verify -> ship"
}
```

#### Agent Toolchain

| Tool | Role in my loop |
| --- | --- |
| [opencode](https://opencode.ai) | Terminal-native agent. Multi-file refactors, repo-wide context, MCP + skills. |
| [codex](https://github.com/openai/codex) | Sandboxed execution. Long-running implementation tasks and PR-sized changes. |
| [reasonix](https://github.com/esengine/DeepSeek-Reasonix) | DeepSeek-native agent, single Go binary. Prefix-cache stable, so long sessions stay cheap. Config-driven via `reasonix.toml`, executor + planner in separate sessions. |

#### How I Work

- **Spec first, code second.** Ambiguous prompts produce ambiguous diffs.
- **Small, verifiable steps.** Every agent run ends with a build or a test, not a vibe.
- **Read every diff.** Agents are fast, not correct. Review is the real job.
- **Context is the product.** `AGENTS.md`, skills, and MCP servers do more for output
  quality than any prompt trick.
- **No stopgaps.** If a fix only works today, it isn't a fix.

---

<img src="https://github-readme-stats-fast.vercel.app/api?username=MagnumGoYB&theme=dark&show_icons=true" />

<!--
**MagnumGoYB/MagnumGoYB** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
