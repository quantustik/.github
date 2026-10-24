# Quantustik

**Quantustik is a market data service for the S&P 500 — prices, fundamentals, SEC filings, insider and Congress trades, macro indicators and market conditions — for investors and AI agents, through a dashboard, a REST API and an MCP server.**

Every value carries its source and as-of date. Quantustik publishes measured data only, with no predictions and no recommendations.

- **Website:** <https://quantustik.com>
- **Public REST API:** <https://quantustik.com/api/v1/openapi.json> · [Swagger](https://quantustik.com/api/v1/docs)
- **Hosted MCP server:** `https://quantustik.com/mcp` (streamable-HTTP, no key required)
- **Stdio proxy for MCP clients:** [quantustik/mcp-server](https://github.com/quantustik/mcp-server)
- **Developer and agent docs:** [quantustik/quantustik](https://github.com/quantustik/quantustik)
- **For LLMs:** <https://quantustik.com/llms.txt>

Call the REST API with a single `curl`, no signup:

```bash
curl "https://quantustik.com/api/v1/market/fear-greed"
```

> **Market data only — not investment advice.** Nothing here is a recommendation to buy or sell any security.
