# Git Diff Analyzer

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Unlock the power of git diffs and PRs in seconds!

With Git Diff Analyzer, analyzing git diffs and GitHub pull requests has never been easier. Use our public API to get instant insights into code changes, identify risks, and streamline your review process. Perfect for developers, project managers, and teams looking to maintain code quality. With a simple $0.003 per analysis, you can optimize your version control workflow effortlessly.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://git-diff-mcp.mcpize.run/mcp` |
| Landing | https://git-diff-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "git_diff_mcp": { "url": "https://git-diff-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `analyze_diff` | $0.01 | Analyze git diff text. Returns stats, changed files, risk level. |
| `get_pr_info` | $0.01 | Get PR stats from public GitHub repo. Returns title, additions, deletions, files. |
| `detect_sensitive` | $0.01 | Detect potential secrets/credentials in diff. Returns warnings and risk level. |
| `health_check` | 🆓 free | Health check. |

**Try it free:** call `health_check` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`git` `diff` `github` `api` `analysis` `dev-tools` `software`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
