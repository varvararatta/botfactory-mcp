# Ukrainian Public Data Hub

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Instant access to crucial Ukrainian data without authentication.

Unlock real-time insights into Ukraine's economy and public services with our comprehensive data APIs. Get official NBU exchange rates, explore public procurement tenders on Prozorro, and geocode Ukrainian addresses effortlessly. Whether you're a business analyst, researcher, or developer, this server equips you with essential tools to make informed decisions and enhance your projects. Dive into the rich landscape of Ukrainian public data today!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://public-data-ukraine-mcp.mcpize.run/mcp` |
| Landing | https://public-data-ukraine-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "public_data_ukraine_mcp": { "url": "https://public-data-ukraine-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `health_check` | 🆓 free | Server health check. |
| `get_exchange_rates` | $0.01 | Get official NBU (National Bank of Ukraine) exchange rates. date format: YYYYMMDD or None for today. Returns: {rates, date, source} |
| `search_prozorro_tenders` | 🆓 free | Search Ukrainian public procurement tenders on Prozorro. Returns: {tenders: [{title, value, status, date_modified}]} |
| `geocode_ukraine` | $0.01 | Geocode Ukrainian address to coordinates using OpenStreetMap Nominatim. Returns: {lat, lon, display_name, region, city} |
| `get_weather_ukraine` | $0.01 | Get current weather for Ukrainian city using Open-Meteo (free, no auth). Returns: {temperature_c, windspeed, weathercode, city} |

**Try it free:** call `search_prozorro_tenders` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`ukraine` `public data` `nbo rates` `prozorro` `geocoding` `open street map` `weather` `no auth`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
