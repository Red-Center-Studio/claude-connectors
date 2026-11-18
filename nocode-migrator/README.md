# Bubble to Cloudflare App & Data Migrator

Moves a Bubble® app's full UI, Cloudflare Workers backend, D1 database, and R2 files into your own Cloudflare account, with checks at every step. The audit, migration plan, 3-page live preview, and data-only free trial (up to 1,000 records, once per app) are free and need no account.

- **Connector URL:** `https://nc.redcenterstudio.com/mcp`
- **Product page:** https://redcenterstudio.com/products/no-code-migrator/
- **Standalone plugin & walkthrough video:** https://github.com/Red-Center-Studio/bubble-to-cloudflare-migrator
- **Plans:** Free audit, plan, 3-page preview, and 1,000-record trial. Data-only 30-day passes start from $39 USD; full-app rebuilds (including the matching data pass) start from $129 USD. Full pricing is on the product page.
- **Sign-in:** The free audit, plan, 3-page preview, and trial need no sign-in; paid runs use an API key shown once after payment. Tokens and app exports go on a one-time secure page, never in the chat.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it Bubble to Cloudflare App & Data Migrator and paste `https://nc.redcenterstudio.com/mcp` as the URL.

**Claude Code:**

```bash
claude mcp add --transport http nc-migrator https://nc.redcenterstudio.com/mcp
```

Or install the plugin: `/plugin marketplace add Red-Center-Studio/claude-plugins` then `/plugin install nocode-migrator@red-center-studio`.

## Links

- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support: hello@redcenterstudio.com
- All Red Center Studio connectors: https://redcenterstudio.com/claude-connectors/
