# OpenAlex Research Explorer

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock the power of 250M+ research papers today!

Dive into a vast collection of over 250 million academic papers with the OpenAlex API! Whether you're a student, researcher, or academic professional, this tool simplifies your literature search, making it easy to find relevant papers for your projects. Use it to gather insights, support your thesis, or explore new disciplines. The API is designed for seamless integration, enabling quick and efficient access to a wealth of information.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://research-mcp.mcpize.run/mcp` |
| Landing | https://research-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "research_mcp": { "url": "https://research-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_papers` | 🆓 free | Search 250M+ academic papers by keyword (OpenAlex). FREE discovery. Returns {papers: [{id, title, year, authors, cited_by_count, doi, venue} |
| `get_paper` | $0.01 | Get full metadata for one paper by OpenAlex ID (e.g. W2741809807) or DOI. Returns full paper details incl. abstract, references count, conce |
| `list_papers_by_author` | 🆓 free | List recent papers by an author name (OpenAlex). FREE discovery. Returns {author, papers: [...]} |
| `health_check` | 🆓 free | Health check. FREE. |

**Try it free:** call `search_papers` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`research` `academic` `papers` `API` `OpenAlex` `literature` `exploration`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
