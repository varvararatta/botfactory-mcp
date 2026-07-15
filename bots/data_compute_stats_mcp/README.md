# Data Compute & Stats Hub

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock powerful computations at your fingertips.

Dive into a suite of pure Python tools designed for precise mathematical computations and insightful statistics. From calculating IRR and NPV for financial projects to converting units seamlessly, this MCP server caters to your analytical needs. Whether you're a data analyst, financial expert, or student, you’ll find reliable results for your calculations without any authentication barriers. Access live currency exchange rates directly from the National Bank of Ukraine to stay updated!

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://data-compute-stats-mcp.mcpize.run/mcp` |
| Landing | https://data-compute-stats-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "data_compute_stats_mcp": { "url": "https://data-compute-stats-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `health_check` | 🆓 free | Server health check. |
| `calculate_statistics` | $0.01 | Calculate descriptive statistics for a list of numbers. Returns: {mean, median, std_dev, min, max, sum, count, percentiles} |
| `calculate_irr` | $0.01 | Calculate Internal Rate of Return (IRR) for cashflows. cashflows: [initial_investment (negative), cf1, cf2, ...] Returns: {irr_percent} |
| `calculate_npv` | $0.01 | Calculate Net Present Value. rate: discount rate as decimal (e.g. 0.1 = 10%). Returns: {npv, rate_percent, cashflows_count} |
| `convert_units` | $0.01 | Convert between units. Supports: length, weight, temperature, area, volume. Returns: {result, from_unit, to_unit, formula} |
| `get_exchange_rates` | $0.01 | Get current exchange rates from NBU (Ukraine National Bank) — no API key needed. Returns: {rates, base, date, source} |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`data` `statistics` `finance` `currency` `calculations` `python`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
