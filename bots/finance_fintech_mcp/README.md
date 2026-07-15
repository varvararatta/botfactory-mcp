# Real-Time Finance Data

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Access live exchange rates and crypto prices effortlessly!

Unlock the power of financial insights with our Finance MCP. Get the latest foreign exchange rates through the Frankfurter API, or dive into cryptocurrency prices with CoinGecko. Perfect for developers and finance enthusiasts who need accurate, real-time data without the hassle of authentication. Whether you're building trading applications or just need quick conversions, our tools are designed for seamless integration. Start exploring today!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://finance-fintech-mcp.mcpize.run/mcp` |
| Landing | https://finance-fintech-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "finance_fintech_mcp": { "url": "https://finance-fintech-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `get_exchange_rates` | $0.01 | Get latest foreign exchange rates for a base currency via Frankfurter API. Returns: {base, date, rates: {EUR: 0.92, ...}} |
| `convert_currency` | $0.01 | Convert amount between currencies using live rates. Returns: {amount, from, to, rate, result} |
| `get_crypto_price` | $0.01 | Get cryptocurrency spot price via CoinGecko (no API key). symbol: btc, eth, sol, etc. Returns: {symbol, id, price, currency} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`finance` `fintech` `crypto` `exchange rates` `api` `data` `real-time` `currency`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
