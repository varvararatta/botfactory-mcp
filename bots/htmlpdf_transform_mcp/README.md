# HTML to Markdown Wizard

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Transform HTML into sleek Markdown effortlessly!

Unlock the power of clean, structured text with our HTML to Markdown transformation tools. Whether you need to convert web content to Markdown for documentation, strip tags for plain text usage, or extract tables for data analysis, this server has you covered. Ideal for developers, content creators, and analysts who demand precision without the hassle of complex APIs. Enjoy seamless, fast transformations with zero authentication required!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://htmlpdf-transform-mcp.mcpize.run/mcp` |
| Landing | https://htmlpdf-transform-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "htmlpdf_transform_mcp": { "url": "https://htmlpdf-transform-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `html_to_markdown` | $0.01 | Convert HTML to clean Markdown. Returns: {markdown, original_length, markdown_length} |
| `html_to_text` | $0.01 | Strip all HTML tags and return clean plain text. Returns: {text, word_count} |
| `extract_tables_from_html` | $0.01 | Extract all tables from HTML as structured data. Returns: {tables: [{headers, rows, row_count}]} |
| `json_to_markdown_table` | $0.01 | Convert list of dicts or list of lists to Markdown table. Returns: {table, rows, columns} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`html` `markdown` `text` `transformation` `tables` `data` `python` `mcp`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
