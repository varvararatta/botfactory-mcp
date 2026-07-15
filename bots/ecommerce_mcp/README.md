# E-Commerce Insights Unlocked

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Access 3M+ global products effortlessly with zero authentication!

Dive into a vast catalog of over 3 million products via Open Food Facts. This powerful tool is perfect for e-commerce businesses, market analysts, and food industry professionals looking to enhance their offerings or conduct comprehensive market research. With zero authentication required, you can quickly integrate product data into your applications, streamline inventory management, or analyze consumer trends. Unlock valuable insights and stay ahead of the competition with ease!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://ecommerce-mcp.mcpize.run/mcp` |
| Landing | https://ecommerce-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "ecommerce_mcp": { "url": "https://ecommerce-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_products` | 🆓 free | Search 3M+ products by name/brand (Open Food Facts). FREE discovery. Returns {products: [{barcode, name, brands, nutriscore}]} |
| `get_product` | $0.01 | Get full product details by barcode (EAN/UPC). Returns ingredients, labels, stores. |
| `get_nutrition` | $0.01 | Get nutrition facts per 100g for a product by barcode. Returns {energy, fat, sugars, salt, proteins, ...} |
| `health_check` | 🆓 free | Health check. FREE. |

**Try it free:** call `search_products` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`ecommerce` `productcatalog` `openfoodfacts` `marketresearch` `foodindustry` `dataanalytics` `insights`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
