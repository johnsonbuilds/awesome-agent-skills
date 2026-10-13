---
name: aident-loadout
description: "Aident Loadout — connect Codex, Claude Code, Cursor, ChatGPT and other MCP clients to 1,000+ apps and 400+ Skills through one reusable setup with Vault-protected credentials and Audit"
version: 1.0.0
author: Aident AI
license: MIT
platforms: [linux, macos, windows]
metadata:
  hermes:
    tags: [mcp, integrations, apps, skills, vault, audit, automation]
---

# Aident Loadout

Give your AI agents real capabilities: 1,000+ apps through one reusable setup. Connect accounts once and reuse them across Codex, Claude Code, Cursor, ChatGPT, Claude Desktop, OpenClaw, Hermes Agent, and other MCP clients.

## Source

- Homepage: https://aident.ai
- Remote MCP: https://loadout.aident.ai/mcp
- GitHub (skill, MIT): https://github.com/Aident-AI/aident-skill
- Docs: https://docs.aident.ai/loadout/overview
- CLI: `@aident-ai/cli`

## What It Does

- **1,000+ apps** across development, research, sales, content and operations
- **400+ expert-built Skills** for research, outreach, content and ops
- **Set up once, use in every agent** via remote MCP (Streamable HTTP + OAuth)
- **Aident Vault** keeps OAuth and API keys away from the model
- **Cost preflight and Audit** so you see what will run and what ran

## Installation

### Claude Code

```bash
claude mcp add --transport http aident https://loadout.aident.ai/mcp
```

### Coding agents (Codex, Claude Code, Cursor, OpenCode, OpenClaw, Hermes, Antigravity)

Paste the setup prompt:

```
Follow https://aident.ai/SETUP.md
```

### CLI

```bash
npm i -g @aident-ai/cli
aident login
```

## Pricing

Freemium: free pay-as-you-go start; Pro $9.90/mo; Team $59/mo.

## Safety notes

Credentials stay in Aident Vault. Loadout shows action cost before running. Audit records what ran, from which agent, whether it succeeded, and what it cost.
