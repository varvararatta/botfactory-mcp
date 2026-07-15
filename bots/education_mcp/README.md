# Explore Knowledge Resources

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unleash your learning potential with curated educational content.

Dive deep into educational topics through comprehensive resources from Wikipedia and Open Library. Whether you're a student seeking quick info or a lifelong learner wanting structured reading lists, our dual-source research MCP simplifies your search. With zero authentication required, you can instantly access summaries, articles, and books, allowing you to enhance your knowledge and understanding on a variety of subjects. Perfect for educators, students, and curious minds alike!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://education-mcp.mcpize.run/mcp` |
| Landing | https://education-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "education_mcp": { "url": "https://education-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_wikipedia` | 🆓 free | Search Wikipedia articles for educational content. Returns: {results: [{title, snippet, url}]} |
| `get_article_summary` | $0.01 | Get Wikipedia article summary/extract by title. Returns: {title, extract, url} |
| `search_open_library` | 🆓 free | Search Open Library for books and educational materials. Returns: {books: [{title, author, year, key}]} |
| `build_reading_list` | $0.01 | Build a structured reading list for a topic — Wikipedia articles + Open Library books. Returns: {topic, articles: [{title, extract, url}], b |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `search_wikipedia` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`education` `wikipedia` `open-library` `reading-lists` `research` `learning` `knowledge`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
