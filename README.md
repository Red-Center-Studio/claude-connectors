# Claude connectors from Red Center Studio

Remote MCP connectors you add to Claude by URL. Built and run by [Red Center Studio](https://redcenterstudio.com).

| Connector | What it does | Connector URL |
| --- | --- | --- |
| [WebDesk for Claude](webdesk-claude/) | Build and publish a small business website from Claude. Free plan. | `https://mcp.redcenterstudio.com/mcp` |
| [Site Watch](sitewatch/) | Website monitoring in Claude: domain, certificate, DNS and email checks with plain alerts and fixes. Free plan. | `https://mcp.redcenterstudio.com/sitewatch/mcp` |
| [VaultSheet](vaultsheet/) | Fills security questionnaires from your approved answers, word for word, with gaps flagged. Free plan. | `https://mcp.redcenterstudio.com/vaultsheet/mcp` |
| [No-code app data migrator](nocode-migrator/) | Moves a no-code app's data to a Cloudflare D1 database and R2 bucket you own. Free audit. | `https://nc.redcenterstudio.com/mcp` |

Also from the studio, in other repositories:

- [Free website checks and WebDesk for AI agents](https://github.com/Red-Center-Studio/webdesk-mcp): five free website checks with no sign-in, and an API-key server that builds websites for agents.
- [Claude Code plugin marketplace](https://github.com/Red-Center-Studio/claude-plugins): `/plugin marketplace add Red-Center-Studio/claude-plugins`.

## Add a connector to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Paste the connector URL from the table.

**Claude Code:**

```bash
claude mcp add --transport http <name> <connector URL>
```

Each connector folder has its own short guide and a `server.json` for the [official MCP Registry](https://registry.modelcontextprotocol.io).

## Links

- All connectors, with plans: https://redcenterstudio.com/claude-connectors/
- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support: hello@redcenterstudio.com

The connectors themselves are hosted services. This repository holds their public listings, guides and registry entries, not their source code. The files here are MIT licensed.