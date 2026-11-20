# Bubble to Cloudflare App & Data Migrator

Moves a Bubble® app's full UI, Cloudflare Workers backend, D1 database, and R2 files into your own Cloudflare account, with checks at every step. The audit, migration plan, 10-page live preview (core pages first), and data-only free trial (up to 1,000 records, once per app) are free and need no account.

- **Connector URL:** `https://nc.redcenterstudio.com/mcp`
- **Product page:** https://redcenterstudio.com/products/no-code-migrator/
- **Standalone plugin & walkthrough video:** https://github.com/Red-Center-Studio/bubble-to-cloudflare-migrator
- **Plans:** Free audit, plan, 10-page preview, and 1,000-record trial. Data-only 30-day passes start from $39 USD; full-app rebuilds (including the matching data pass) start from $129 USD. Full pricing is on the product page.
- **After the move:** Paying starts the full build straight away, and service keys are optional and can be added any time afterwards. Some moved apps need small touch-ups, and the owner can keep improving the app with their own AI coding agent (Claude Code, Antigravity and similar) using the polish prompt that comes with a paid build. Work is saved 30 days from the last activity on a paid move (7 days for a free preview).
- **Sign-in:** The free audit, plan, 10-page preview, and trial need no sign-in; paid runs use an API key shown once after payment. Tokens and app exports go on a one-time secure page, never in the chat.

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
