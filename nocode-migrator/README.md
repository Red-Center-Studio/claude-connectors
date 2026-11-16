# No-code app data migrator

Moves the data of a Bubble(R) app to a Cloudflare D1 database and R2 bucket in your own Cloudflare account, with checks at every step. The audit and migration plan are free and need no account.

- **Connector URL:** `https://nc.redcenterstudio.com/mcp`
- **Product page:** https://redcenterstudio.com/products/no-code-migrator/
- **Plans:** Free audit and plan. Paid 30-day passes per app for the migration itself. Prices are on the product page.
- **Sign-in:** The free audit needs no sign-in; the paid migration uses an API key shown once after payment.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it No-code app data migrator and paste `https://nc.redcenterstudio.com/mcp` as the URL.

**Claude Code:**

```bash
claude mcp add --transport http nc-migrator https://nc.redcenterstudio.com/mcp
```

## Links

- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support: hello@redcenterstudio.com
- All Red Center Studio connectors: https://redcenterstudio.com/claude-connectors/
