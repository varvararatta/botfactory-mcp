# Instant Country Insights

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Access vital country data at lightning speed!

Unlock comprehensive country information with ease! Discover capitals, currencies, and neighboring nations using our API. Perfect for developers, researchers, and businesses needing reliable geographic data. Whether you're building an app or conducting research, our service provides the essential data you need quickly and affordably. Start your global exploration today with just a simple API call!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://country-data-mcp.mcpize.run/mcp` |
| Landing | https://country-data-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "country_data_mcp": { "url": "https://country-data-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `get_country` | $0.01 | Get country info by name or ISO code (e.g. 'Germany', 'DE', 'DEU'). Returns full country details. |
| `search_countries` | 🆓 free | Search countries by name or filter by region. Returns list of matches. |
| `get_neighbors` | 🆓 free | Get all neighboring countries for a given country code (ISO A2 or A3). Returns {neighbors: [{name, code, region}]} |
| `get_by_currency` | $0.01 | Get all countries using a specific currency (e.g. 'EUR', 'USD'). Returns {countries: [...], currency} |
| `health_check` | 🆓 free | Health check. |

**Try it free:** call `search_countries` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`country data` `geographic information` `api` `capitals` `currencies` `neighbors` `developers` `research`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
