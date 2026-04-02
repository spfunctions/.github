# SimpleFunctions

Context flow for prediction markets — from perception to judgment to execution.

Real-time probabilities from 9,706 prediction markets (Kalshi + Polymarket). 38 MCP tools, 43 CLI commands, REST API. Thesis management, edge detection, what-if scenarios, automated trading strategies, and 24/7 monitoring.

### Get started

```bash
# CLI — 43 commands, no auth needed to explore
npm i -g @spfunctions/cli && sf agent

# MCP — one command for Claude Code / Cursor
claude mcp add simplefunctions --url https://simplefunctions.dev/api/mcp/mcp

# REST — instant data, no auth
curl https://simplefunctions.dev/api/agent/world
```

### Repositories

| Repo | What it is |
|------|-----------|
| [simplefunctions-cli](https://github.com/spfunctions/simplefunctions-cli) | CLI + MCP server. 43 commands, interactive agent, Telegram bot. |
| [awesome-prediction-markets](https://github.com/spfunctions/awesome-prediction-markets) | Curated list of prediction market APIs, tools, datasets for developers. |
| [causal-tree-decomposition](https://github.com/spfunctions/causal-tree-decomposition) | Standalone probability engine. Thesis → weighted confidence. |
| [prediction-market-mcp-example](https://github.com/spfunctions/prediction-market-mcp-example) | Minimal MCP server (~50 lines) for learning. |
| [prediction-market-context](https://github.com/spfunctions/prediction-market-context) | Fetch structured market context for any LLM. |
| [kalshi-price-monitor](https://github.com/spfunctions/kalshi-price-monitor) | Terminal price alert monitor. |

### Links

[Website](https://simplefunctions.dev) · [Docs](https://simplefunctions.dev/docs) · [Agent Guide](https://simplefunctions.dev/docs/guide) · [Blog](https://simplefunctions.dev/blog) · [X/Twitter](https://x.com/patrickfyzjwsdj)
