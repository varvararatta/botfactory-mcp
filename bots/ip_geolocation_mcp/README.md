# IP Geolocation Tool

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Instantly geolocate any IP address with ease!

Unlock the power of IP geolocation with our tool! Whether you're a developer needing location data for user analytics or a cybersecurity expert tracking suspicious activity, our service delivers precise information. You can geolocate individual IPs or process batches of up to five addresses in one go. Ideal for businesses, marketers, and security professionals looking to enhance their services with location insights.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://ip-geolocation-mcp.mcpize.run/mcp` |
| Landing | https://ip-geolocation-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "ip_geolocation_mcp": { "url": "https://ip-geolocation-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `lookup_ip` | $0.01 | Geolocate an IPv4/IPv6 address. Returns country, city, ISP, coords. Params: ip (str): The IP address to geolocate. Returns: dict: Geolocatio |
| `lookup_batch` | $0.01 | Lookup up to 5 IPs (comma-separated). Returns {results: [...]}. Params: ips (str): Comma-separated list of IP addresses. Returns: dict: Resu |
| `health_check` | 🆓 free | Server health check. Returns: dict: Health status of the server. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`ip geolocation` `api` `location data` `lookup` `internet security` `analytics` `ip address`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
