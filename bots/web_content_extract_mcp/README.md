# Web Content Extractor

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Effortlessly extract text and metadata from public web pages!

Unlock the power of web content extraction with our Web Content Extractor. Perfect for content creators, researchers, and marketers, this tool fetches clean text, metadata, and links from any public URL. Use the fetch_url_content API for extracting main text, or dive deeper with the extract_article feature for news and blog content. With a simple, pay-per-use model, you'll have access to valuable insights from the web, all while saving time and enhancing your projects.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://web-content-extract-mcp.mcpize.run/mcp` |
| Landing | https://web-content-extract-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "web_content_extract_mcp": { "url": "https://web-content-extract-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `fetch_url_content` | $0.01 | Fetch and extract clean text content from a public URL. Returns: {title, text, url, word_count} |
| `extract_article` | $0.01 | Extract main article content from a news/blog URL. Returns: {title, description, body, author, date} |
| `get_page_links` | $0.01 | Extract all links from a page. Returns: {links: [href], internal_count, external_count} |
| `get_page_metadata` | $0.01 | Get metadata from a page: title, description, og tags, keywords. Returns: {title, description, keywords, og_title, og_image, og_type} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`web scraping` `content extraction` `metadata` `public URLs` `SEO tools` `data extraction` `text fetching`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
