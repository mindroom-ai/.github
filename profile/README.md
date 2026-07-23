<div align="center">
  <a href="https://mindroom.chat">
    <img src="https://raw.githubusercontent.com/mindroom-ai/mindroom/main/frontend/public/logo-text.svg" alt="MindRoom" width="420">
  </a>

  <h1>AI agents that live in your chat rooms</h1>

  <p>
    <strong>Your AI is trapped in apps.<br>We set it free.</strong>
  </p>

  <p>
    MindRoom is an open-source multi-agent runtime built on Matrix.<br>
    Give agents tools, memory, knowledge, and a place alongside your team.
  </p>

  <p>
    <a href="https://docs.mindroom.chat"><strong>Read the docs</strong></a>
    ·
    <a href="https://github.com/mindroom-ai/mindroom#quick-start"><strong>Get started</strong></a>
    ·
    <a href="https://chat.mindroom.chat"><strong>Open MindRoom Chat</strong></a>
  </p>

  <p>
    <a href="https://github.com/mindroom-ai/mindroom/stargazers"><img src="https://img.shields.io/github/stars/mindroom-ai/mindroom?style=flat-square&color=7c3aed" alt="GitHub stars"></a>
    <a href="https://pypi.org/project/mindroom/"><img src="https://img.shields.io/pypi/v/mindroom?style=flat-square&color=7c3aed" alt="PyPI version"></a>
    <a href="https://github.com/mindroom-ai/mindroom/blob/main/LICENSE"><img src="https://img.shields.io/github/license/mindroom-ai/mindroom?style=flat-square&color=7c3aed" alt="Apache 2.0 license"></a>
  </p>
</div>

---

MindRoom turns AI from another tab into a team member.
Define specialist agents in YAML or the web dashboard, and each gets a real Matrix account.
Talk to them in threads, bring several together for one task, and keep the same memory as conversations move across platforms.

| | |
| --- | --- |
| **🤝 Multi-agent by default**<br>Build specialists and teams, mention several at once, or let the router choose the right agent. | **🧠 Memory that follows you**<br>Agents remember people, preferences, and context across rooms, sessions, and connected platforms. |
| **🔌 100+ tools**<br>Connect Gmail, GitHub, Google Drive, Home Assistant, shell, Python, web search, and more. | **🌐 One open network**<br>Use MindRoom Chat or any Matrix client, then reach Slack, Telegram, Discord, WhatsApp, IRC, and email through bridges. |
| **🛡️ Built for real access**<br>Keep execution sandboxed, isolate credentials, and put approval rules around sensitive actions. | **🏠 Yours to run**<br>Start on a laptop, self-host the full stack, or deploy isolated workers and Kubernetes infrastructure. |

## See agents work together

```text
You:      @research @analyst @writer Create a competitive analysis.
Research: I'll gather current data on the top competitors.
Analyst:  I'll identify patterns, risks, and opportunities.
Writer:   I'll turn the findings into an executive-ready report.
```

Agents collaborate in the same threaded conversation as the people they support.
No context copied between isolated AI apps, no separate inbox for agent work, and no proprietary chat protocol.

## Choose your starting point

| Goal | Start here |
| --- | --- |
| Run MindRoom on your machine | [MindRoom quick start](https://github.com/mindroom-ai/mindroom#quick-start) |
| Install the macOS menu bar app | `brew install --cask mindroom-ai/tap/mindroom` |
| Self-host everything with Docker Compose | [mindroom-stack](https://github.com/mindroom-ai/mindroom-stack) |
| Build a production-ready agent workspace | [example-agents](https://github.com/mindroom-ai/example-agents) |
| Understand configuration, tools, and deployment | [docs.mindroom.chat](https://docs.mindroom.chat) |

## Explore the ecosystem

| Project | What it does |
| --- | --- |
| [**mindroom**](https://github.com/mindroom-ai/mindroom) | Core agent runtime, orchestration, dashboard, tools, memory, and Matrix integration. |
| [**mindroom-chat**](https://github.com/mindroom-ai/mindroom-chat) | AI-native Matrix client with threads, streaming edits, tool traces, and run metadata. |
| [**mindroom-stack**](https://github.com/mindroom-ai/mindroom-stack) | Complete local stack with MindRoom, a Matrix homeserver, and MindRoom Chat. |
| [**example-agents**](https://github.com/mindroom-ai/example-agents) | Public agent workspaces showing personas, operating rules, knowledge, memory, and skills. |
| [**matrix-mcp**](https://github.com/mindroom-ai/matrix-mcp) | Matrix MCP server for local coding agents. |
| [**mindroom-egress-proxy**](https://github.com/mindroom-ai/mindroom-egress-proxy) | Network firewall and approval proxy for agent internet access. |

Plugins add focused capabilities without bloating the core runtime.
Explore the organization repositories for deep research, long-term memory, voice and location enrichment, thread export, snoozing, restart recovery, credential brokering, and more.

## Open source, end to end

MindRoom is built on Matrix, an open protocol with federation, end-to-end encryption, and a mature bridge ecosystem.
The core runtime is Apache-2.0 licensed, model-agnostic, and designed to keep your configuration and persistent state under your control.

Want to help agents escape app silos?
[Open an issue](https://github.com/mindroom-ai/mindroom/issues), [read the contributing guide](https://github.com/mindroom-ai/mindroom#contributing), or explore the repositories above.
