# AXME Code — Claude Code Plugin

This repo contains the pre-built Claude Code plugin for [AXME Code](https://github.com/AxmeAI/axme-code).

**Do not edit files here directly.** This repo is auto-synced from the main [axme-code](https://github.com/AxmeAI/axme-code) repo on each release.

## Install

In Claude Code:

```
/plugin marketplace add AxmeAI/axme-code-plugin
/plugin install axme-code@axmeai-axme-code-plugin
```

Or via CLI:

```bash
claude plugin marketplace add AxmeAI/axme-code-plugin
claude plugin install axme-code@axmeai-axme-code-plugin
```

## What it does

Persistent memory, architectural decisions, and safety guardrails for Claude Code. Your agent starts every session with full project context.

- **19 MCP tools** for knowledge base management
- **Safety hooks** that block dangerous commands before execution
- **Automatic setup** on first session
- **Session continuity** via handoff system

See [axme-code](https://github.com/AxmeAI/axme-code) for full documentation.

## License

[MIT](LICENSE)
