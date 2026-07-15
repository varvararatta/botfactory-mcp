# Prozorro Tender Monitor

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock real-time insights into Ukrainian public tenders.

Stay ahead in the competitive landscape of Ukrainian public procurement with our Prozorro Tender Monitor. Effortlessly search for tenders using keywords, access detailed tender information, and keep track of recent modifications. Ideal for businesses, contractors, and consultants looking to secure lucrative government contracts. Leverage our APIs and gain a strategic advantage in navigating the Prozorro system.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://prozorro-tender-monitor-mcp.mcpize.run/mcp` |
| Landing | https://prozorro-tender-monitor-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "prozorro_tender_monitor_mcp": { "url": "https://prozorro-tender-monitor-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_tenders` | 🆓 free | Search Ukrainian public tenders by keyword on Prozorro. Returns: {tenders: [...]}. Price: ${TOOL_PRICES["search_tenders"]}/call |
| `get_tender` | $0.01 | Get full tender details by ID. Returns: {title, description, value, status, ...}. Price: ${TOOL_PRICES["get_tender"]}/call |
| `get_recent_tenders` | $0.01 | Get recently modified tenders. hours_back: how far back to look. Returns: {tenders: [...], count}. Price: ${TOOL_PRICES["get_recent_tenders" |
| `get_tender_stats` | 🆓 free | Get general Prozorro marketplace statistics. Returns: {status, note}. FREE — lightweight check, price: $0 |
| `health_check` | 🆓 free | Health check. FREE — price: $0. |

**Try it free:** call `search_tenders` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`prozorro` `tender` `monitor` `procurement` `ukrainian` `government` `insights` `api`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
