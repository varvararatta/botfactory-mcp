# Text Intelligence Hub

![MCP](https://img.shields.io/badge/MCP-server-blue) ![x402](https://img.shields.io/badge/x402-USDC%20on%20Base-green) ![pricing](https://img.shields.io/badge/freemium-try%20free-orange)

> Harness NLP power without the hassle!

Unleash the potential of your text data with Text Intelligence. Our pure Python NLP tools allow you to detect language, analyze sentiment, extract keywords, and summarize text effortlessly. Businesses, researchers, and developers will find immense value in our user-friendly APIs that require no authentication or external dependencies. Perfect for content creators and marketers looking to enhance their text analysis capabilities.

## 🔌 Connect

| Gateway | URL |
|---|---|
| MCP endpoint | `https://text-intelligence-mcp.mcpize.run/mcp` |
| Landing | https://text-intelligence-mcp.mcpize.run |

```jsonc
// Add to your MCP client config (Claude Desktop, Cursor, etc.)
{
  "mcpServers": {
    "text_intelligence_mcp": { "url": "https://text-intelligence-mcp.mcpize.run/mcp" }
  }
}
```

## 🧰 Tools

| Tool | Price | Description |
|---|---|---|
| `detect_language` | 🆓 free | Detect language of text using character frequency analysis. Returns: {language, confidence, method} |
| `analyze_sentiment` | $0.01 | Analyze sentiment of text (positive/negative/neutral). Returns: {score, label, confidence} |
| `extract_keywords` | $0.01 | Extract top keywords from text using TF scoring. Returns: {keywords: [{word, score}], total_words} |
| `find_duplicates` | $0.01 | Find duplicate or near-duplicate texts using Jaccard similarity. Returns: {duplicates: [{text1_idx, text2_idx, similarity}]} |
| `summarize_text` | $0.01 | Extractive summarization — picks most important sentences. Returns: {summary, sentences_used, original_length} |
| `health_check` | 🆓 free | Server health check. |

**Try it free:** call `detect_language` — no payment, no API key. Paid tools settle
automatically via [x402](https://www.x402.org/) (USDC on Base) through the MCPize gateway.

## 💸 Pricing

Freemium: discovery tools are **free**, core tools are **pay-per-call** in USDC.
No subscription, no signup — agents pay only for what they use.

## 🏷️ Tags

`nlp` `text analysis` `language detection` `sentiment` `keywords` `summarization`

---
*Hosted on [MCPize](https://mcpize.com). Auto-generated listing.*
