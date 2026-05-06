# SimpleFunctions

Prediction-market infrastructure for agents, researchers, and operators.

SimpleFunctions starts at `sf`: a local CLI for querying live Kalshi + Polymarket state, exporting structured JSON for coding agents, and gating prediction-market workflows from the shell. The HTTP/Data API is the network surface. SDKs and agent runtimes should wrap the same contracts. MCP is a compatibility adapter for MCP-only hosts.

## Start here

```bash
npm i -g @spfunctions/cli
sf status --json
sf world --json
sf describe --all --json
```

- CLI: https://simplefunctions.dev/cli
- Docs: https://docs.simplefunctions.dev
- llms.txt: https://simplefunctions.dev/llms.txt
- Public package catalog: https://simplefunctions.dev/opensource

## Repositories by job

| Job | Repositories |
| --- | --- |
| Primary product surface | [`simplefunctions-cli`](https://github.com/spfunctions/simplefunctions-cli) |
| API clients | [`simplefunctions-python`](https://github.com/spfunctions/simplefunctions-python) |
| Institutional examples | [`sf-institutional-alpha-demo`](https://github.com/spfunctions/sf-institutional-alpha-demo) |
| Benchmarks | [`major-model-benchmark`](https://github.com/spfunctions/major-model-benchmark), [`prediction-market-model-benchmark`](https://github.com/spfunctions/prediction-market-model-benchmark) |
| Agent/framework adapters | [`langchain-prediction-markets`](https://github.com/spfunctions/langchain-prediction-markets), [`openai-agents-prediction-markets`](https://github.com/spfunctions/openai-agents-prediction-markets), [`vercel-ai-prediction-markets`](https://github.com/spfunctions/vercel-ai-prediction-markets), [`crewai-prediction-markets`](https://github.com/spfunctions/crewai-prediction-markets), [`prediction-market-mcp-example`](https://github.com/spfunctions/prediction-market-mcp-example) |
| Utilities | [`agent-world-awareness`](https://github.com/spfunctions/agent-world-awareness), [`prediction-market-context`](https://github.com/spfunctions/prediction-market-context), [`prediction-market-edge-detector`](https://github.com/spfunctions/prediction-market-edge-detector), [`prediction-market-uncertainty`](https://github.com/spfunctions/prediction-market-uncertainty), [`prediction-market-regime`](https://github.com/spfunctions/prediction-market-regime), [`causal-tree-decomposition`](https://github.com/spfunctions/causal-tree-decomposition), [`polymarket-ticker-resolver`](https://github.com/spfunctions/polymarket-ticker-resolver), [`kalshi-orderbook-viewer`](https://github.com/spfunctions/kalshi-orderbook-viewer), [`kalshi-price-monitor`](https://github.com/spfunctions/kalshi-price-monitor), [`world-state-action`](https://github.com/spfunctions/world-state-action), [`create-prediction-market-agent`](https://github.com/spfunctions/create-prediction-market-agent) |
| Research and demos | [`ttt-conv-memory`](https://github.com/spfunctions/ttt-conv-memory), [`Memento`](https://github.com/spfunctions/Memento), [`claude-arena`](https://github.com/spfunctions/claude-arena), [`claude-trading`](https://github.com/spfunctions/claude-trading), [`harness`](https://github.com/spfunctions/harness), [`polymarket-sports-mm`](https://github.com/spfunctions/polymarket-sports-mm) |
| Lists and reading | [`prediction-markets-reading`](https://github.com/spfunctions/prediction-markets-reading), [`Awesome-Prediction-Market-Tools`](https://github.com/spfunctions/Awesome-Prediction-Market-Tools), [`awesome-prediction-markets`](https://github.com/spfunctions/awesome-prediction-markets), [`awesome-cli-agentic-tools`](https://github.com/spfunctions/awesome-cli-agentic-tools) |

## Surface order

1. CLI first: humans, scripts, Claude Code, Codex, cron, local workflows.
2. HTTP/Data API second: services, notebooks, dashboards, remote workers.
3. Clients/adapters: wrappers over the same objects.
4. MCP last: compatibility layer for MCP-only hosts.

