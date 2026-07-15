# Global Public Holidays API

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Access public holiday data for over 100 countries with ease!

Streamline your applications with the Global Public Holidays API, offering instant access to holiday data for over 100 countries. Perfect for developers, businesses, and planners seeking accurate holiday information without the hassle of authentication. Use it to enhance calendars, plan marketing campaigns, or manage staffing schedules. With the nager.at API, you can ensure your projects are always up-to-date with the latest public holiday information.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://public-holidays-mcp.mcpize.run/mcp` |
| Landing | https://public-holidays-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "public_holidays_mcp": { "url": "https://public-holidays-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `get_holidays` | $0.01 | Get public holidays for a country. country_code: ISO 2-letter (US, DE, UA, GB...). Returns {holidays: [{date, name, type}], country, year} |
| `is_holiday` | 🆓 free | Check if a specific date is a public holiday. check_date: YYYY-MM-DD. Returns {is_holiday, holiday_name, country, date} |
| `next_holiday` | 🆓 free | Get the next upcoming public holiday for a country. Returns {name, date, days_until, country} |
| `working_days` | $0.01 | Count working days between two dates excluding holidays and weekends. Returns {working_days, total_days, holidays_in_range, weekends} |
| `health_check` | 🆓 free | Health check. |

**Try it free:** call `is_holiday` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`public holidays` `nager.at` `api` `global` `calendar` `data` `holiday`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
