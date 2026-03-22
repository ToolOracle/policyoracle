# 📜 policyOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/policy/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "policyoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/policy/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_policy` | Register an ICT security policy. |
| `list_policies` | List policies with optional status filter. |
| `policy_gap_check` | Check coverage against 12 RTS-required ICT policies. |
| `review_schedule` | Policy review cycle — overdue and upcoming. |
| `approval_tracker` | Policy approval workflow status. |
| `coverage_map` | Map policies to DORA/RTS article requirements. |
| `version_control` | Track policy versions. Set new_version to bump. |
| `attestation` | Record policy attestation. Set add=true. |
| `compliance_score` | Overall policy compliance scoring. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

policyOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/policy/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
