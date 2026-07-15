# Ukrainian Postal Tracker

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Effortlessly track your Nova Poshta shipments in real time.

Stay updated on your shipments with our Ukrainian postal tracking tool for Nova Poshta. Use the track_shipment API to get live status updates, including delivery dates and locations. Perfect for businesses and individuals alike, this service helps you manage your shipments effectively. Whether you're a seller needing to inform customers or a buyer tracking your order, our API delivers precise information at a minimal cost. Experience seamless tracking with zero authentication required.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://ua-postal-tracking-mcp.mcpize.run/mcp` |
| Landing | https://ua-postal-tracking-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "ua_postal_tracking_mcp": { "url": "https://ua-postal-tracking-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `track_shipment` | $0.01 | Track shipment by Nova Poshta tracking number (TTN). Returns: {status, status_code, city_from, city_to, weight, delivery_date} |
| `find_warehouse` | 🆓 free | Find Nova Poshta warehouses in a city. Returns: {warehouses: [{description, address, schedule, number}]} |
| `get_delivery_cost` | $0.01 | Estimate Nova Poshta delivery cost between cities. Returns: {cost_uah, city_from, city_to, weight_kg} |
| `health_check` | 🆓 free | Health check. |

**Try it free:** call `find_warehouse` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`ukrainian` `postal` `tracking` `nova poshta` `api` `shipping` `logistics` `real-time`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
