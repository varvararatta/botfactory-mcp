# Real Estate Insights

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock real estate potential with precise location data.

Dive into the world of real estate with our powerful location intelligence tools. Use OpenStreetMap Nominatim to effortlessly search for property addresses and get accurate geocoding for any location. Gain valuable insights into country market contexts, including population, area, and currency, essential for making informed investment decisions. Ideal for real estate agents, investors, and market analysts looking for reliable data to enhance their property research.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://real-estate-mcp.mcpize.run/mcp` |
| Landing | https://real-estate-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "real_estate_mcp": { "url": "https://real-estate-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_locations` | 🆓 free | Search places/addresses for real estate research via OpenStreetMap Nominatim. Returns: {results: [{name, lat, lon, type, country}]} |
| `geocode_address` | $0.01 | Geocode a property address to coordinates. Returns: {lat, lon, display_name, city, country, postcode} |
| `get_market_context` | $0.01 | Country context for real estate analysis: population, area, capital, currencies. country_code: ISO 3166-1 alpha-2 (e.g. UA, US). Returns mar |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `search_locations` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`real estate` `geocoding` `location intelligence` `OSM` `market analysis` `property research` `investing` `data`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
