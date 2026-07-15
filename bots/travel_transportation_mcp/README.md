# Global Travel Insights

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock essential travel data at your fingertips!

Travel smarter with real-time insights on countries, weather, and currency conversions. Use our APIs to get up-to-date information on capital cities, climate conditions, and budget management. Whether you're a globetrotter planning your next adventure or a travel agent seeking accurate details, our tools empower you to make informed decisions effortlessly. No authentication is required, making access seamless and fast.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://travel-transportation-mcp.mcpize.run/mcp` |
| Landing | https://travel-transportation-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "travel_transportation_mcp": { "url": "https://travel-transportation-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `get_country_info` | $0.01 | Get travel country facts: capital, region, income level via World Bank API. code: ISO 3166-1 alpha-2 (US, FR, UA). Returns country profile f |
| `get_weather` | $0.01 | Get current weather for a city worldwide via Open-Meteo + OSM geocoding. Returns: {city, lat, lon, temperature_c, windspeed_kmh, weather_cod |
| `convert_travel_currency` | $0.01 | Convert travel budget between currencies using live Frankfurter rates. Returns: {amount, from, to, result, rate, date} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`travel` `weather` `currency` `country info` `transportation` `budgeting` `real-time` `API`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
