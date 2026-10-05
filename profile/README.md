<div align="center">

<a href="https://mindroom.chat">
  <picture>
    <source media="(prefers-reduced-motion: no-preference)" srcset="https://raw.githubusercontent.com/mindroom-ai/mindroom/main/assets/logo/logo-mark-animated.svg" />
    <img src="https://raw.githubusercontent.com/mindroom-ai/mindroom/main/assets/logo/logo-mark.svg" alt="MindRoom" width="140" />
  </picture>
</a>

# MindRoom

**AI agents that know you and your work, in a chat app anyone can use.**

Open source under Apache 2.0 · Any model, local or cloud · Self-host the whole stack

[Website](https://mindroom.chat) · [Docs](https://docs.mindroom.chat) · [Showcase](https://docs.mindroom.chat/showcase/) · [MindRoom Chat](https://chat.mindroom.chat) · [Hosted](https://mindroom.chat/#hosted)

<a href="https://github.com/mindroom-ai/mindroom/stargazers"><img src="https://img.shields.io/github/stars/mindroom-ai/mindroom?style=flat-square&color=7c3aed" alt="GitHub stars"></a>
<a href="https://pypi.org/project/mindroom/"><img src="https://img.shields.io/pypi/v/mindroom?style=flat-square&color=7c3aed" alt="PyPI version"></a>
<a href="https://github.com/mindroom-ai/mindroom/blob/main/LICENSE"><img src="https://img.shields.io/github/license/mindroom-ai/mindroom?style=flat-square&color=7c3aed" alt="Apache 2.0 license"></a>

</div>

https://github.com/user-attachments/assets/f8325b3c-7ed0-4cd7-bc77-0c4cd74f226e

MindRoom gives you a personal agent for your calendar, notes, trips, and homelab, and shared agents for your team's email, documents, and code.
Every agent is a real user on [Matrix](https://matrix.org/), the open chat standard, so you talk to it in [MindRoom Chat](https://github.com/mindroom-ai/mindroom-chat), in any other Matrix client, or in Slack, Telegram, WhatsApp, and Discord through bridges.
Pick a local model for your private life or a frontier model for hard problems, and self-host the whole stack or run only the agents on your own computer.

**Run it on any computer**

```bash
uvx mindroom run
```

Needs [uv](https://docs.astral.sh/uv/getting-started/installation/) and a model: an API key, a subscription login such as Codex, or a local model.

**Or use the macOS app**

```bash
brew install --cask mindroom-ai/tap/mindroom
```

A native app that runs your agents on your Mac in the background, with one-click local models.
Needs an Apple silicon Mac with macOS 14 or later.

Chat with your agents on the [web](https://chat.mindroom.chat), on the [Mac](https://docs.mindroom.chat/installation/macos-app/), on [iPhone and iPad](https://apps.apple.com/us/app/mindroom-ai/id6760272172), and on Android (in beta).
Rather not run it yourself? [Try hosted MindRoom](https://mindroom.chat/#hosted).

## See it in action

<table>
<tr>
<td width="50%" valign="top">
<a href="https://docs.mindroom.chat/showcase/#ask-approve-done"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/5e389c59-c81a-4f70-9c5d-de7406ff95f4" /><img src="https://github.com/user-attachments/assets/bc6194b1-9398-47f5-b649-2ea17dbb6b9f" alt="A review dialog where the user approves an agent's calendar booking" /></picture></a>
<p><b>Approve before it acts</b><br />Actions you choose wait for your OK, with the exact arguments in view.</p>
</td>
<td width="50%" valign="top">
<a href="https://docs.mindroom.chat/showcase/#one-thread-the-whole-team"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/635ce3ef-217d-494a-a8e5-01e3dd78454d" /><img src="https://github.com/user-attachments/assets/fbd1295d-025d-41d1-9ee8-0cc674706b98" alt="Three colleagues see the same agent thread side by side" /></picture></a>
<p><b>The whole team, one thread</b><br />Colleagues share an agent in a thread and see every answer stream in live.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://docs.mindroom.chat/showcase/#canvases"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/7fc2bc01-1ec5-40d1-971f-5e6f33ba0f18" /><img src="https://github.com/user-attachments/assets/8eb3e6d8-8e9f-4ebb-a51b-bbb5913536e3" alt="Two agent canvases: a week grid of free meeting slots and a weekend trip planner with a budget" /></picture></a>
<p><b>Canvases you can click</b><br />An agent lays out free slots or a trip budget beside the chat and acts on what you pick.</p>
</td>
<td width="50%" valign="top">
<a href="https://docs.mindroom.chat/showcase/#it-drives-you-take-the-wheel"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/ddf9402f-a451-4f50-b070-1b50aab739c8" /><img src="https://github.com/user-attachments/assets/6b7a2673-d9b9-446a-b9a7-4e4240241489" alt="The agent hands over the passkey step next to its browser on the order page" /></picture></a>
<p><b>It drives, you take the wheel</b><br />Watch an agent work in its own browser and take over when it needs your passkey.</p>
</td>
</tr>
</table>

More in the [showcase](https://docs.mindroom.chat/showcase/) and the [MindRoom README](https://github.com/mindroom-ai/mindroom#see-it-in-action).
The recordings use a fictional company and scripted model responses.

## Why MindRoom

<table>
<tr>
<td width="50%" valign="top">

**🔌 [Connected to your tools and documents](https://docs.mindroom.chat/#agents-that-know-you-and-your-work)**<br />
Personal agents and shared team agents connect to 100+ tools, including email, calendar, Slack, Jira, GitHub, and any MCP server, and search your own documents.
Even from a server across the world, they can use a computer you pair.

</td>
<td width="50%" valign="top">

**🔒 [Private where it matters](https://docs.mindroom.chat/#private-where-it-matters)**<br />
Pick a model per agent: a local one for your most personal data, a frontier one for coding.
With local memory and your own server, nothing that agent sees leaves your home, and what you tell a private agent stays out of shared ones.

</td>
</tr>
<tr>
<td valign="top">

**🧠 [Memory that keeps improving](https://docs.mindroom.chat/#they-remember-and-keep-improving)**<br />
Agents keep what matters from every conversation, get better as more people use them, and can turn work they repeat into reusable skills.

</td>
<td valign="top">

**🛡️ [Safe to give real access](https://docs.mindroom.chat/#safe-to-give-real-access)**<br />
One-tap approval for the actions you choose, sandboxed code execution, and end-to-end encryption on Matrix, the open standard governments use for secure messaging.

</td>
</tr>
<tr>
<td valign="top">

**💬 [A chat app built for agents](https://docs.mindroom.chat/#a-chat-app-built-for-agents)**<br />
MindRoom builds its own client for the web, Mac, iPhone, iPad, and Android (in beta), so agents can show live tool traces, ask for approval, open interactive canvases, join voice calls, and work in a real browser you can take over.

</td>
<td valign="top">

**🌉 [Works where you already are](https://docs.mindroom.chat/#works-where-you-already-are)**<br />
Bridges bring the same agents to Slack, Telegram, WhatsApp, and Discord, and an MCP gateway brings them to Claude Code and Codex.

</td>
</tr>
</table>

## Start here

| Goal | Start here |
| --- | --- |
| Run MindRoom on your computer and chat in MindRoom Chat | [Quick start](https://github.com/mindroom-ai/mindroom#quick-start) |
| Run your agents on a Mac with the native app | [macOS app guide](https://docs.mindroom.chat/installation/macos-app/) |
| Self-host everything with Docker Compose | [mindroom-stack](https://github.com/mindroom-ai/mindroom-stack) |
| Give an agent its own NixOS machine | [lxc-nixos](https://github.com/mindroom-ai/lxc-nixos) |
| Let us run it for you | [Hosted MindRoom](https://mindroom.chat/#hosted) |
| Learn configuration, tools, and deployment | [docs.mindroom.chat](https://docs.mindroom.chat) |

## Projects

| Project | What it does |
| --- | --- |
| [**mindroom**](https://github.com/mindroom-ai/mindroom) | The agent runtime: orchestration, dashboard, 100+ tools, memory, knowledge bases, and the Matrix integration. |
| [**mindroom-chat**](https://github.com/mindroom-ai/mindroom-chat) | The chat app built for agents, with threads, streaming replies, tool traces, approvals, canvases, and the agent's browser. |
| [**mindroom-stack**](https://github.com/mindroom-ai/mindroom-stack) | A Docker Compose stack with MindRoom, a Matrix homeserver, and MindRoom Chat. |
| [**lxc-nixos**](https://github.com/mindroom-ai/lxc-nixos) | A NixOS flake that runs the whole stack in an Incus container an agent can manage itself. |
| [**example-agents**](https://github.com/mindroom-ai/example-agents) | An example agent workspace with a persona, operating rules, knowledge, memory, and skills. |
| [**matrix-mcp**](https://github.com/mindroom-ai/matrix-mcp) | A Matrix MCP server for local coding agents. |
| [**mindroom-egress-proxy**](https://github.com/mindroom-ai/mindroom-egress-proxy) | A network firewall and approval proxy for agent internet access. |
| [**agent-vault**](https://github.com/mindroom-ai/agent-vault) | MindRoom's fork of Infisical's Agent Vault, a credential broker that keeps API keys out of agent processes. |
| [**mindroom-nio**](https://github.com/mindroom-ai/mindroom-nio) | MindRoom's fork of matrix-nio, the Python Matrix client library the runtime is built on. |
| [**homebrew-tap**](https://github.com/mindroom-ai/homebrew-tap) | The Homebrew tap for the macOS app. |

<details>
<summary><b>Matrix and client forks</b></summary>

| Project | What it does |
| --- | --- |
| [**mindroom-tuwunel**](https://github.com/mindroom-ai/mindroom-tuwunel) | MindRoom's fork of the Tuwunel Matrix homeserver, used by mindroom-stack. |
| [**mindroom-synapse**](https://github.com/mindroom-ai/mindroom-synapse) | MindRoom's fork of Synapse for high-frequency edit streaming. |
| [**lk-jwt-service**](https://github.com/mindroom-ai/lk-jwt-service) | MindRoom's fork of the MatrixRTC authorization service for voice calls. |
| [**mindroom-librechat**](https://github.com/mindroom-ai/mindroom-librechat) | A LibreChat fork that shows MindRoom's server-side tool calls as native tool cards. |

</details>

## Plugins

Plugins add tools, skills, event hooks, OAuth providers, prompt enrichment, and safety policies without touching the core runtime, and they reload while MindRoom keeps running.
See [Plugins](https://docs.mindroom.chat/plugins/) to install, configure, and build them.

| Plugin | What it adds |
| --- | --- |
| [**agent-vault-bridge-plugin**](https://github.com/mindroom-ai/agent-vault-bridge-plugin) | Routes agent shell API calls through Agent Vault so credentials never enter the agent process. |
| [**deep-research-plugin**](https://github.com/mindroom-ai/deep-research-plugin) | Runs bounded, multi-round web research on the agent's configured model and returns cited reports. |
| [**location-enrich-plugin**](https://github.com/mindroom-ai/location-enrich-plugin) | Adds real-time Dawarich location and movement context to agent prompts. |
| [**openviking-plugin**](https://github.com/mindroom-ai/openviking-plugin) | Provides automatic long-term memory extraction, recall, and management through OpenViking. |
| [**ping-hook-plugin**](https://github.com/mindroom-ai/ping-hook-plugin) | Shows the smallest useful event-hook plugin with a direct `!ping-hook` response. |
| [**response-audit-jev-plugin**](https://github.com/mindroom-ai/response-audit-jev-plugin) | Uses JEV or an LLM to check completed answers for citation and source-use issues, then requests corrections in the same thread. |
| [**restart-resume-plugin**](https://github.com/mindroom-ai/restart-resume-plugin) | Wakes tagged idle threads after MindRoom restarts, then clears their restart tags. |
| [**shell-guard-plugin**](https://github.com/mindroom-ai/shell-guard-plugin) | Intercepts and blocks configured dangerous shell tool calls before execution. |
| [**thread-goal-plugin**](https://github.com/mindroom-ai/thread-goal-plugin) | Keeps persistent thread goals available across context compaction and restarts. |
| [**thread-snooze-plugin**](https://github.com/mindroom-ai/thread-snooze-plugin) | Resolves threads temporarily and wakes them automatically at a chosen time. |
| [**voice-enrich-plugin**](https://github.com/mindroom-ai/voice-enrich-plugin) | Adds private speech-to-text guidance to prompts without changing visible messages. |

## Contribute

MindRoom is open source and built on Matrix, an open protocol with federation, end-to-end encryption, and a mature bridge ecosystem.
[Open an issue](https://github.com/mindroom-ai/mindroom/issues), read the [contributing notes](https://github.com/mindroom-ai/mindroom#contributing), or star the [main repository](https://github.com/mindroom-ai/mindroom) to follow along.
