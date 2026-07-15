# SEO Keyword Insights

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock powerful SEO insights with advanced keyword analysis.

Elevate your marketing strategy with our Marketing MCP server. Analyze SEO keywords, extract meta tags, and assess word frequencies to refine your content. Ideal for marketers, content creators, and SEO specialists looking to optimize their online presence. Use our tools to identify high-impact keywords and enhance your site's visibility effortlessly.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://marketing-mcp.mcpize.run/mcp` |
| Landing | https://marketing-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "marketing_mcp": { "url": "https://marketing-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `analyze_seo_keywords` | $0.01 | Extract top SEO keywords from marketing copy using term frequency. Returns: {keywords: [{word, score}], total_words} |
| `extract_meta_tags` | $0.01 | Fetch a page and extract HTML meta tags (title, description, og:*). Returns: {title, description, og_title, og_description, meta: {name: con |
| `word_frequency` | $0.01 | Count word frequencies in text for content/marketing analysis. Returns: {words: [{word, count, pct}], total} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`seo` `keywords` `meta tags` `marketing` `analysis`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
