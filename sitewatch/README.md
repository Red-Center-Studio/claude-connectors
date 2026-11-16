# Site Watch

Watches your website and emails you, with the fix, when a domain or certificate is about to expire, DNS or email records (SPF, DMARC, DKIM) change, AI crawlers get blocked or the site goes down.

- **Connector URL:** `https://mcp.redcenterstudio.com/sitewatch/mcp`
- **Product page:** https://redcenterstudio.com/sitewatch/
- **Plans:** Free plan: 1 site, checked monthly, with a monthly health email. Paid plans add daily checks, alerts, hourly uptime and a weekly report. Prices are on the plans page.
- **Sign-in:** You sign in with your email address and a 6-digit code.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it Site Watch and paste `https://mcp.redcenterstudio.com/sitewatch/mcp` as the URL.

**Claude Code:**

```bash
claude mcp add --transport http sitewatch https://mcp.redcenterstudio.com/sitewatch/mcp
```

## Links

- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support: hello@redcenterstudio.com
- All Red Center Studio connectors: https://redcenterstudio.com/claude-connectors/
