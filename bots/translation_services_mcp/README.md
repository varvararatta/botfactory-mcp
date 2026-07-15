# Global Translation Hub

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Break language barriers effortlessly! Translate in 100+ languages.

Unlock the power of communication with our Global Translation Hub! Seamlessly translate text between over 100 languages using our robust MyMemory API. Whether you're a business looking to reach international customers, a traveler needing quick translations, or a developer integrating multilingual support into your apps, our service is designed for you. Enjoy precision and speed with our batch_translate tool for bulk translations. Start your journey with a free health check to assess your translation needs!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://translation-services-mcp.mcpize.run/mcp` |
| Landing | https://translation-services-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "translation_services_mcp": { "url": "https://translation-services-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `translate` | $0.01 | Translate text between 100+ languages (MyMemory). target/source: ISO codes (en, uk, de, ...). Returns {translated, source, target} |
| `batch_translate` | $0.01 | Translate a list of strings into the target language. Returns {results: [{original, translated}]} |
| `get_supported_languages` | 🆓 free | List supported language codes and names. FREE discovery. |
| `health_check` | 🆓 free | Health check. FREE. |

**Try it free:** call `get_supported_languages` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`translation` `multilingual` `api` `localization` `text-translation` `international` `business` `travel`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
