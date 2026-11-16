# No-code app data migrator

Moves the data of a Bubble(R) app to a Cloudflare D1 database and R2 bucket in your own Cloudflare account, with checks at every step. The audit, the migration plan and a free trial (up to 1,000 records, once per app) are free and need no account.

- **Connector URL:** `https://nc.redcenterstudio.com/mcp`
- **Product page:** https://redcenterstudio.com/products/no-code-migrator/
- **Plans:** Free audit, plan and trial. Paid 30-day passes per app from $39 USD for bigger apps. Prices are on the product page.
- **Sign-in:** The free audit, plan and trial need no sign-in; a pass uses an API key shown once after payment. Tokens for your Cloudflare account and app go on a one-time secure page, never in the chat.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it No-code app data migrator and paste `https://nc.redcenterstudio.com/mcp` as the URL.

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
