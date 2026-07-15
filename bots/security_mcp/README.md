# Vulnerability Discovery Made Easy

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Uncover vulnerabilities in your code for just $0.01 per call!

With security_mcp, developers can easily identify vulnerabilities in their applications using the OSV.dev database. Whether you're working with npm, PyPI, or Go, our open-source vulnerability lookup tool streamlines the security assessment process. Perfect for security analysts and developers alike, this service empowers teams to maintain robust security hygiene without breaking the bank. Plus, start with a free health check to ensure everything's running smoothly.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://security-mcp.mcpize.run/mcp` |
| Landing | https://security-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "security_mcp": { "url": "https://security-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `search_vulnerabilities` | 🆓 free | Search known vulnerabilities for a package (OSV.dev). FREE discovery. ecosystem: PyPI|npm|Go|Maven|crates.io|RubyGems|NuGet|... Returns {vul |
| `get_vulnerability` | $0.01 | Get full details for one vulnerability by ID (e.g. GHSA-... or CVE-...). Returns affected ranges, references, fixed versions. |
| `check_package` | $0.01 | Check if a specific package version is affected by known vulnerabilities. Returns {vulnerable: bool, vulns: [...]} |
| `health_check` | 🆓 free | Health check. FREE. |

**Try it free:** call `search_vulnerabilities` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`vulnerability` `security` `api` `open-source` `lookup` `dev-tools` `npm` `pypi`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
