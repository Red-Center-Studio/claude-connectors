# Bubble to Cloudflare App & Data Migrator

Moves a Bubble® app's full UI, Cloudflare Workers backend, D1 database, and R2 files into your own Cloudflare account, with checks at every step. The audit, migration plan, 10-page live preview (core pages first), and data-only free trial (up to 1,000 records, once per app) are free and need no account.

- **Connector URL:** `https://nc.redcenterstudio.com/mcp`
- **App Mover (UI, backend, and data rebuild):** https://redcenterstudio.com/app-mover/
- **Data Migrator (schema, records, files, privacy rules, redirects):** https://redcenterstudio.com/app-mover/?tab=data#run
- **Standalone plugin & walkthrough video:** https://github.com/Red-Center-Studio/bubble-to-cloudflare-migrator

## How it works / what it costs / what you own

- **How it works:** Upload your `.bubble` export (secrets stripped in transit) or connect credentials via a one-time secure `/connect` link, preview up to 10 core pages free, then deploy into your own Cloudflare account (Workers, D1, R2) with automated checks at every step.
- **What it costs (USD):** Free audit, plan, 10-page interactive preview, and 1,000-record data trial (7 days). Data-only 30-day passes: Starter `$39 USD` (10k records, 1 GB), Migration `$69 USD` (100k records, 5 GB), Large `$199 USD` (500k records, 50 GB). Full App Mover builds (including matching data pass, 2 rebuild rounds, and 30-day fix window): Small `$159 USD` (up to 10 pages), Standard `$299 USD` (up to 30 pages), Large `$389 USD` (up to 80 pages; 81 to 250 add `$3 USD`/page; over 250 custom quote), Developer mode `$45 USD`, Done-for-you from `$499 USD`.
- **What you own:** 100% of the generated TypeScript, React, Hono, and Drizzle code running in your own Cloudflare account, with no ongoing platform fee.
- **After the move:** Paying starts the full build straight away, and service keys are optional and can be added any time afterwards. Some moved apps need small touch-ups, and the owner can keep improving the app with their own AI coding agent (Claude Code, Antigravity and similar) using the polish prompt that comes with a paid build. Work is saved 30 days from the last activity on a paid move (7 days for a free preview).
- **Sign-in & security:** The free audit, plan, 10-page preview, and trial need no sign-in; paid runs use an API key shown once after payment. Tokens and app exports go on a one-time secure page, never in the chat. Report security issues to `hello@redcenterstudio.com`.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it Bubble to Cloudflare App & Data Migrator and paste `https://nc.redcenterstudio.com/mcp` as the URL.

**Claude Code:**

```bash
claude mcp add --transport http nc-migrator https://nc.redcenterstudio.com/mcp
```

Or install the plugin: `/plugin marketplace add Red-Center-Studio/claude-plugins` then `/plugin install nocode-migrator@red-center-studio`.

## Links

- App Mover: https://redcenterstudio.com/app-mover/
- Data Migrator: https://redcenterstudio.com/app-mover/?tab=data#run
- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- License: MIT ([LICENSE](../LICENSE))
- Support and security contact: hello@redcenterstudio.com
- All Red Center Studio connectors: https://redcenterstudio.com/claude-connectors/

Bubble® is a registered trademark of Bubble Group, Inc. Red Center Studio is not affiliated with, endorsed by, or certified by Bubble Group, Inc., Cloudflare, Inc., or Anthropic, PBC.
