# Swift DNS Lookup

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Get fast and reliable DNS resolutions with ease!

Unlock the power of DNS lookups with our DNS Lookup service using Google DNS-over-HTTPS. Whether you're a developer needing quick DNS resolutions for A, AAAA, MX, TXT, CNAME, or NS records, or a business ensuring your domain configurations are correct, this tool has you covered. With zero authentication required, it’s perfect for anyone needing instant results. Enjoy a health check feature for free to keep your service running smoothly.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://dns-lookup-mcp.mcpize.run/mcp` |
| Landing | https://dns-lookup-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "dns_lookup_mcp": { "url": "https://dns-lookup-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `resolve_dns` | $0.01 | Resolve DNS records. record_type: A, AAAA, MX, TXT, CNAME, NS. params: name (str): The domain name to resolve. record_type (str): The type o |
| `list_dns_types` | 🆓 free | List supported DNS record types for resolve_dns. return format: dict: A dictionary containing the list of supported DNS record types. |
| `health_check` | 🆓 free | Server health check. return format: dict: A dictionary indicating the health status of the server. |

**Try it free:** call `list_dns_types` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`dns` `lookup` `google` `https` `records` `api` `developer`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
