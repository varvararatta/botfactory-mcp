# Earthquake Monitoring Hub

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Stay updated with real-time earthquake data at your fingertips.

Our Earthquake Monitor harnesses the USGS earthquake feed to provide you with up-to-the-minute information on recent seismic activities. Perfect for researchers, safety agencies, and anyone interested in global seismic events, you can filter earthquakes by magnitude and timeframe. With tools to list recent quakes and highlight significant ones, it’s an essential resource for disaster preparedness and awareness. Monitor the earth's movements effortlessly and stay informed wherever you are.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://earthquake-monitor-mcp.mcpize.run/mcp` |
| Landing | https://earthquake-monitor-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "earthquake_monitor_mcp": { "url": "https://earthquake-monitor-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `list_recent_quakes` | 🆓 free | List recent earthquakes. period: hour|day|week. Optional min_magnitude filter. |
| `significant_quakes` | $0.01 | Significant earthquakes only. period: week|month. |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `list_recent_quakes` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`earthquake` `monitoring` `USGS` `real-time` `data` `safety` `research`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
