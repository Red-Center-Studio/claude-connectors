# Claude connectors from Red Center Studio

Remote MCP connectors you add to Claude by URL. Built and run by [Red Center Studio](https://redcenterstudio.com).

| Connector | What it does | Connector URL |
| --- | --- | --- |
| [WebDesk for Claude](webdesk-claude/) | Build and publish a small business website from Claude. Free plan. | `https://mcp.redcenterstudio.com/mcp` |
| [Site Watch](sitewatch/) | Website monitoring in Claude: domain, certificate, DNS and email checks with plain alerts and fixes. Free plan. | `https://mcp.redcenterstudio.com/sitewatch/mcp` |
| [VaultSheet](vaultsheet/) | Fills security questionnaires from your approved answers, word for word, with gaps flagged. Free plan. | `https://mcp.redcenterstudio.com/vaultsheet/mcp` |
| [Bubble to Cloudflare App & Data Migrator](nocode-migrator/) | Moves a Bubble® app's UI, backend, D1 database, and R2 files into your Cloudflare account. Free audit and 10-page preview. | `https://nc.redcenterstudio.com/mcp` |

Also from the studio, in other repositories:

- [Bubble to Cloudflare Migrator plugin & walkthrough](https://github.com/Red-Center-Studio/bubble-to-cloudflare-migrator): standalone plugin config, walkthrough video, and parity examples for Claude Code and Antigravity.
- [Free website checks and WebDesk for AI agents](https://github.com/Red-Center-Studio/webdesk-mcp): five free website checks with no sign-in, and an API-key server that builds websites for agents.
- [Claude Code plugin marketplace](https://github.com/Red-Center-Studio/claude-plugins): `/plugin marketplace add Red-Center-Studio/claude-plugins`.

## Add a connector to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Paste the connector URL from the table.

**Claude Code:**

```bash
claude mcp add --transport http <name> <connector URL>
```

Each connector folder has its own short guide and a `server.json` for the [official MCP Registry](https://registry.modelcontextprotocol.io).

## How it works / what it costs / what you own

- **App Mover** (https://redcenterstudio.com/app-mover/): Free audit, migration plan, and 10-page interactive preview (no key). Full rebuilds including matching data pass, 2 rebuild rounds, and 30-day fix window: Small `$159 USD` (up to 10 pages), Standard `$299 USD` (up to 30 pages), Large `$389 USD` (up to 80 pages; 81 to 250 add `$3 USD`/page; over 250 custom quote), Developer mode `$45 USD`.
- **Data Migrator** (https://redcenterstudio.com/app-mover/?tab=data#run): Free 1,000-record trial (7 days, once per app); 30-day passes: Starter `$39 USD` (10,000 records, 1 GB files), Migration `$69 USD` (100,000 records, 5 GB files), Large `$199 USD` (500,000 records, 50 GB files).
- **What you own**: Everything deploys to your own Cloudflare account (Workers, D1, R2) as TypeScript, React, Hono, and Drizzle code with zero platform lock-in.

## Links

- App Mover: https://redcenterstudio.com/app-mover/
- Data Migrator: https://redcenterstudio.com/app-mover/?tab=data#run
- All connectors, with plans: https://redcenterstudio.com/claude-connectors/
- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support and security contact: hello@redcenterstudio.com

The connectors themselves are hosted services. This repository holds their public listings, guides and registry entries, not their source code. The files here are MIT licensed; see [LICENSE](LICENSE).

Bubble® is a registered trademark of Bubble Group, Inc. Red Center Studio is not affiliated with, endorsed by, or certified by Bubble Group, Inc., Cloudflare, Inc., or Anthropic, PBC.