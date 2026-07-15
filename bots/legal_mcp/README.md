# Legal Insight Bot

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock legal insights effortlessly with powerful tools!

Dive into the world of legal research with our legal_mcp server. Use our 'search_legislation' tool to explore statutes and case summaries directly from Wikipedia. Need to extract citations? Our 'extract_citations' tool does that seamlessly. For quick comprehension, utilize 'summarize_legal_text' to distill complex legal documents into concise summaries. Ideal for law students, professionals, and anyone seeking clarity in legal matters.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://legal-mcp.mcpize.run/mcp` |
| Landing | https://legal-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "legal_mcp": { "url": "https://legal-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_legislation` | 🆓 free | Search legal topics, statutes and case summaries via Wikipedia. Returns: {results: [{title, snippet, url}]} |
| `extract_citations` | $0.01 | Extract legal-style citations from text using pattern matching. Returns: {citations: [str], count: int} |
| `summarize_legal_text` | $0.01 | Summarize legal text by extracting the first N substantive sentences. Returns: {summary, sentence_count, word_count} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `search_legislation` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`legal` `research` `citations` `summarization` `statutes` `case law` `wikipedia` `tools`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
