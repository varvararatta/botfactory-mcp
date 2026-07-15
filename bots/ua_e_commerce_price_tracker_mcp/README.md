# Ukrainian Price Tracker

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Track and compare prices from Rozetka and OLX effortlessly!

Discover the best prices in Ukrainian e-commerce with our powerful price tracker. Use the 'search_rozetka' and 'search_olx' APIs to find products and listings instantly. Compare prices across platforms with 'compare_prices' to ensure you get the best deal. Perfect for savvy shoppers, resellers, and market analysts looking to stay ahead of the competition.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://ua-e-commerce-price-tracker-mcp.mcpize.run/mcp` |
| Landing | https://ua-e-commerce-price-tracker-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "ua_e_commerce_price_tracker_mcp": { "url": "https://ua-e-commerce-price-tracker-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_rozetka` | 🆓 free | Search products on Rozetka.ua (Ukraine largest e-commerce). Returns: {products: [{name, price, url}], query} |
| `search_olx` | 🆓 free | Search listings on OLX Ukraine. Returns: {listings: [{title, price, location, date, url}]} |
| `compare_prices` | $0.01 | Compare prices for a product across Rozetka and OLX. Returns: {rozetka_min, olx_min, difference_percent, product} |
| `health_check` | 🆓 free | Health check. |

**Try it free:** call `search_rozetka` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`ua` `ecommerce` `price tracker` `rozetka` `olx` `scraping` `comparison` `shopping`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
