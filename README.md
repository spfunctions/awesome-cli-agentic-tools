# Awesome CLI Agentic Tools

> Curated list of command-line tools, SDKs, and frameworks for building AI agents.

Browse the full directory at [sparkco.ai](https://sparkco.ai).

---

## Contents

- [Prediction Market Tools](#prediction-market-tools)
  - [By Sparkco](#by-sparkco)
  - [Community](#community)
- [Agent Frameworks](#agent-frameworks)
- [Coding Agents](#coding-agents)
- [Browser Agents](#browser-agents)
- [Developer CLIs](#developer-clis)
- [Operations CLIs](#operations-clis)
- [BI & Data CLI Tools](#bi--data-cli-tools)
- [Why CLI?](#why-cli)
- [Contributing](#contributing)

---

## Prediction Market Tools

The deepest collection of prediction market CLIs, SDKs, and agent frameworks on the internet.

### By Sparkco

| Tool | Description | Install | Language |
|------|-------------|---------|----------|
| [@spfunctions/cli](https://github.com/spfunctions/cli) | 50 commands: scan, edges, watch, agent mode. Kalshi + Polymarket. | `npm i -g @spfunctions/cli` | TypeScript |
| [@spfunctions/prediction-market-mcp](https://github.com/spfunctions/prediction-market-mcp) | MCP server with 4 tools. Works with Claude, Cursor, VS Code. | `npx @spfunctions/prediction-market-mcp` | TypeScript |
| [simplefunctions-ai](https://github.com/spfunctions/simplefunctions-ai) | Python SDK. World model, 30k+ markets, thesis engine. | `pip install simplefunctions-ai` | Python |
| [prediction-market-mcp-example](https://github.com/spfunctions/prediction-market-mcp-example) | Minimal MCP server example for prediction market data. | `git clone` | TypeScript |
| [kalshi-price-monitor](https://github.com/spfunctions/kalshi-price-monitor) | Real-time price monitoring and alerts for Kalshi markets. | `git clone` | TypeScript |
| [prediction-market-context](https://github.com/spfunctions/prediction-market-context) | Structured prediction market context for any LLM. | `git clone` | TypeScript |
| [causal-tree-decomposition](https://github.com/spfunctions/causal-tree-decomposition) | Standalone causal tree engine. Zero dependencies. | `git clone` | TypeScript |
| [create-prediction-market-agent](https://github.com/spfunctions/create-prediction-market-agent) | Scaffold agent projects: LangChain, CrewAI, OpenAI, vanilla TS. | `npx create-prediction-market-agent` | TypeScript |
| [world-state-action](https://github.com/spfunctions/world-state-action) | GitHub Action for CI/CD world state injection. | `uses: spfunctions/world-state-action@v1` | TypeScript |
| [polymarket-sports-mm](https://github.com/spfunctions/polymarket-sports-mm) | Sports market making bot for Polymarket. | `git clone` | Python |
| [langchain-prediction-markets](https://github.com/spfunctions/langchain-prediction-markets) | LangChain tools for prediction market data. | `npm i langchain-prediction-markets` | TypeScript |
| [openai-agents-prediction-markets](https://github.com/spfunctions/openai-agents-prediction-markets) | OpenAI function-calling tools for prediction markets. | `npm i openai-agents-prediction-markets` | TypeScript |
| [vercel-ai-prediction-markets](https://github.com/spfunctions/vercel-ai-prediction-markets) | Vercel AI SDK tools for prediction markets. | `npm i vercel-ai-prediction-markets` | TypeScript |
| [crewai-prediction-markets](https://github.com/spfunctions/crewai-prediction-markets) | CrewAI tools for prediction markets. | `pip install crewai-prediction-markets` | Python |
| [agent-world-awareness](https://github.com/spfunctions/agent-world-awareness) | One-line world awareness for any agent. | `npm i agent-world-awareness` | TypeScript |
| [prediction-market-edge-detector](https://github.com/spfunctions/prediction-market-edge-detector) | Edge detection across 30k+ markets. | `git clone` | TypeScript |

### Community

| Tool | Stars | Description | Install | Language |
|------|-------|-------------|---------|----------|
| [prediction-market-analysis](https://github.com/nweii/prediction-market-analysis) | 2,800 | Largest public dataset + analysis framework for prediction markets. | `git clone` | Python |
| [pmxt](https://github.com/Polymarket/pmxt) | 1,400 | CCXT for prediction markets. Unified API across exchanges. | `pip install pmxt` | Python |
| [Polymarket Agents](https://github.com/Polymarket/agents) | 800 | Official Polymarket agent framework for autonomous trading. | `git clone` | Python |
| [kalshi-ai-trading-bot](https://github.com/elizaOS/kalshi-ai-trading-bot) | 342 | AI trading bot for Kalshi with Grok-4 integration. | `git clone` | Python |
| [polymarket-mcp-server](https://github.com/berlinbra/polymarket-mcp-server) | 335 | 45-tool MCP server for Polymarket data and trading. | `git clone` | TypeScript |
| [polybot](https://github.com/polybot-nexus/polybot) | 200 | Reverse-engineer strategies, find arbitrage on Polymarket. | `git clone` | Python |
| [PredictOS](https://github.com/PredictOS/predictos) | 200 | All-in-one multi-agent framework for prediction markets. | `git clone` | Python |
| [dr-manhattan](https://github.com/dr-manhattan-dev/dr-manhattan) | 181 | CCXT for prediction markets with market-making support. | `pip install dr-manhattan` | Python |
| [polyterm](https://github.com/polyterm/polyterm) | 162 | Polymarket in your terminal. Browse and trade from CLI. | `cargo install polyterm` | Rust |
| [CloddsBot](https://github.com/CloddsBot/cloddsbot) | 158 | Autonomous AI agent trading across 1000+ markets. | `git clone` | Python |
| [polymarket-pipeline](https://github.com/polymarket-pipeline/pipeline) | 154 | Event-driven AI news-to-trade pipeline for Polymarket. | `git clone` | Python |
| [gnosis/prediction-market-agent](https://github.com/gnosis/prediction-market-agent) | 150 | AI agent that bets on prediction markets to benchmark reasoning. | `git clone` | Python |
| [kalshi-trading-bot-cli](https://github.com/kalshi-trading/bot-cli) | 149 | AI-native Kalshi CLI with Kelly sizing and risk management. | `git clone` | Python |
| [kalshi-python](https://github.com/KalshiEx/kalshi-python) | 100 | Official Kalshi Python SDK for market data and trading. | `pip install kalshi-python` | Python |
| [gnosis/pm-agent-tooling](https://github.com/gnosis/prediction-market-agent-tooling) | 100 | Benchmark and deploy prediction market agents. | `pip install prediction-market-agent-tooling` | Python |

---

## Agent Frameworks

| Tool | Stars | Description | Install | Language |
|------|-------|-------------|---------|----------|
| [LangChain](https://github.com/langchain-ai/langchain) | 126k | Most adopted agent framework. Chains, tools, memory. | `pip install langchain` | Python |
| [MetaGPT](https://github.com/geekan/MetaGPT) | 45k | Multi-agent software company simulation. | `pip install metagpt` | Python |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 44.6k | Role-based multi-agent crews with delegated tasks. | `pip install crewai` | Python |
| [AutoGen](https://github.com/microsoft/autogen) | 35k | Multi-agent conversations by Microsoft Research. | `pip install autogen` | Python |
| [DSPy](https://github.com/stanfordnlp/dspy) | 20k | Programming, not prompting. Optimized LM pipelines. | `pip install dspy-ai` | Python |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | 15k | Official OpenAI agent framework with function calling. | `pip install openai-agents` | Python |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | 10k | Type-safe agent API built on Pydantic. | `pip install pydantic-ai` | Python |
| [Mastra](https://github.com/mastra-ai/mastra) | 8k | TypeScript-first agent framework with built-in tools. | `npm i mastra` | TypeScript |
| [Smolagents](https://github.com/huggingface/smolagents) | 5k | HuggingFace minimal agents. Simple, composable. | `pip install smolagents` | Python |

---

## Coding Agents

| Tool | Stars | Description | Install | Language |
|------|-------|-------------|---------|----------|
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 50k | Autonomous software engineer. Code, test, deploy. | `pip install openhands` | Python |
| [Cline](https://github.com/cline/cline) | 30k | VS Code extension with terminal access. Autonomous coding. | `code --install-extension saoudrizwan.claude-dev` | TypeScript |
| [Aider](https://github.com/paul-gauthier/aider) | 25k | Git-aware AI pair programmer in your terminal. | `pip install aider-chat` | Python |
| [SWE-Agent](https://github.com/princeton-nlp/SWE-agent) | 15k | Resolves real GitHub issues autonomously. | `pip install swe-agent` | Python |

---

## Browser Agents

| Tool | Stars | Description | Install | Language |
|------|-------|-------------|---------|----------|
| [Browser Use](https://github.com/browser-use/browser-use) | 50k | Open-source browser agent library. See, click, type. | `pip install browser-use` | Python |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | 10k | Vision-driven browser navigation for AI agents. | `pip install skyvern` | Python |
| [Playwright MCP](https://github.com/anthropics/playwright-mcp) | 3k | Playwright browser automation exposed as MCP tools. | `npx @anthropic/playwright-mcp` | TypeScript |

---

## Developer CLIs

| Tool | Stars | Description | Install | Language |
|------|-------|-------------|---------|----------|
| [GitHub CLI (gh)](https://github.com/cli/cli) | 37k | Repos, PRs, issues, Actions — all from the terminal. | `brew install gh` | Go |
| [Vercel CLI](https://github.com/vercel/vercel) | 12k | Deploy, manage, and inspect Vercel projects. | `npm i -g vercel` | TypeScript |
| [Stripe CLI](https://github.com/stripe/stripe-cli) | 5k | Payments, webhooks, and Stripe resource management. | `brew install stripe/stripe-cli/stripe` | Go |
| [ElevenLabs CLI](https://github.com/elevenlabs/elevenlabs-python) | 2k | TTS, STT, voice cloning, and audio generation. | `pip install elevenlabs` | Python |
| [Supabase CLI](https://github.com/supabase/cli) | 1k | Database, Auth, Storage, and Edge Functions management. | `brew install supabase/tap/supabase` | Go |
| [AgentMail CLI](https://github.com/agentmail-toolkit/agentmail) | — | Email inboxes and transactional email for AI agents. | `pip install agentmail` | Python |

---

## Operations CLIs

| Tool | Stars | Description | Install | Language |
|------|-------|-------------|---------|----------|
| [gogcli](https://github.com/gog/gogcli) | 6.7k | Google Workspace CLI — Docs, Sheets, Drive, Calendar. | `brew install gogcli` | Go |
| [hledger](https://github.com/simonmichael/hledger) | 4.4k | Plain text double-entry accounting. Scriptable, composable. | `brew install hledger` | Haskell |
| [crm-cli](https://github.com/crm-cli/crm-cli) | 72 | CLI customer relationship management. Contacts, deals, notes. | `pip install crm-cli` | Python |

---

## BI & Data CLI Tools

SQL engines, CSV toolkits, and data transformation CLIs for agentic BI workflows.

### By Sparkco

| Tool | Description | Install | Language |
|------|-------------|---------|----------|
| [@spfunctions/bi](https://github.com/spfunctions/bi) | Agent-friendly BI CLI. Query CSV/JSON/Parquet with SQL via DuckDB. 4 commands: `head`, `schema`, `query`, `convert`. | `npm i -g @spfunctions/bi` | TypeScript |

### Community

| Tool | Stars | Description | Install | Language |
|---|---|---|---|---|
| [DuckDB](https://github.com/duckdb/duckdb) | 28k | In-process SQL OLAP database. Parquet, CSV, JSON out of the box. | `brew install duckdb` | C++ |
| [pgcli](https://github.com/dbcli/pgcli) | 12k | Postgres CLI with auto-complete and syntax highlighting. | `pip install pgcli` | Python |
| [xsv](https://github.com/BurntSushi/xsv) | 10k | Fast CSV toolkit. Index, search, split, join, stats. | `cargo install xsv` | Rust |
| [dbt](https://github.com/dbt-labs/dbt-core) | 10k | SQL-first data transformation framework. ELT best practices. | `pip install dbt-core` | Python |
| [Datasette](https://github.com/simonw/datasette) | 9.5k | Instant JSON API and web UI for any SQLite database. | `pip install datasette` | Python |
| [Miller (mlr)](https://github.com/johnkerl/miller) | 9k | Like awk, sed, cut for CSV, TSV, and JSON. Stream processing. | `brew install miller` | Go |
| [usql](https://github.com/xo/usql) | 9k | Universal SQL CLI. Postgres, MySQL, SQLite, DuckDB, 40+ drivers. | `go install github.com/xo/usql@latest` | Go |
| [VisiData](https://github.com/saulpw/visidata) | 8k | Terminal spreadsheet multitool. Explore, sort, filter, pivot. | `pip install visidata` | Python |
| [csvkit](https://github.com/wireservice/csvkit) | 6k | Suite of CLI tools for converting to and working with CSV. | `pip install csvkit` | Python |
| [OctoSQL](https://github.com/cube2222/octosql) | 5k | Query CSV, JSON, Parquet, MySQL, Postgres with a single SQL. | `go install github.com/cube2222/octosql/cmd/octosql@latest` | Go |
| [sqlite-utils](https://github.com/simonw/sqlite-utils) | 2k | CLI for manipulating SQLite. Insert, transform, query, extract. | `pip install sqlite-utils` | Python |

---

## Why CLI?

| | CLI | MCP |
|---|---|---|
| **Token overhead** | 0 tokens | 500-2,000 tokens / tool |
| **Reliability** | ~100% | ~72% success rate |
| **Speed** | Direct execution | JSON-RPC round trip |
| **Composability** | Unix pipes | Pre-defined parameters |

We still index MCP servers. Use what works for your agent.

---

## Contributing

Know a CLI tool we're missing? [Open an issue](https://github.com/spfunctions/awesome-cli-agentic-tools/issues/new?title=Tool+submission:+&labels=tool-submission) or submit a PR.

### Format

```markdown
| [Tool Name](https://github.com/org/repo) | Stars | One-line description. | `install command` | Language |
```

---

## License

[CC0 1.0 Universal](LICENSE)

Built by [Sparkco](https://sparkco.ai). Prediction market tools powered by [SimpleFunctions](https://simplefunctions.dev).
