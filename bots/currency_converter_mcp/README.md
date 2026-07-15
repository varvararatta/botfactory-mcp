# Instant Currency Converter

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Convert currencies instantly with live rates at your fingertips!

Need to convert currencies on the fly? Our Instant Currency Converter uses live rates from the ECB, ensuring you get the most accurate conversions. Ideal for travelers, online shoppers, and businesses operating globally, this tool is both fast and reliable. With no authentication required and a simple API call, you can easily integrate currency conversion into your applications or websites. Start converting today and make informed financial decisions effortlessly!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://currency-converter-mcp.mcpize.run/mcp` |
| Landing | https://currency-converter-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "currency_converter_mcp": { "url": "https://currency-converter-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `convert` | $0.01 | Convert amount between currencies using live ECB rates. Returns {result, rate, from, to, date} |
| `get_rates` | $0.01 | Get all exchange rates for a base currency. Returns {rates: {EUR: 0.92, ...}} |
| `get_history` | $0.01 | Get historical exchange rates for a currency pair. Returns {rates: {date: rate}} |
| `list_currencies` | 🆓 free | List all supported currencies with names. Returns {currencies: {USD: 'US Dollar',...}} |
| `health_check` | 🆓 free | Health check. |

**Try it free:** call `list_currencies` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`currency` `converter` `live rates` `financial tools` `API` `ECB` `travel`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
