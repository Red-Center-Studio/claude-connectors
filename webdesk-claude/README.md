# WebDesk for Claude

Tell Claude about your business and it builds, previews and publishes your website on a free mywebdesk.app address, with a quote form that emails you every enquiry, an enquiry inbox you read from Claude, your own domain on paid plans, and a free ZIP export of the site on every plan.

- **Connector URL:** `https://mcp.redcenterstudio.com/mcp`
- **Product page:** https://redcenterstudio.com/webdesk/claude/
- **Plans:** Free plan: 1 website, up to 5 pages, 25 enquiries a month, a small WebDesk badge. Paid plans add more sites and pages, no badge, your own domain and Lead Autopilot follow-ups. Prices are on the plans page.
- **Sign-in:** You sign in with your email address and a 6-digit code.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it WebDesk for Claude and paste `https://mcp.redcenterstudio.com/mcp` as the URL.

**Claude Code:**

```bash
claude mcp add --transport http webdesk https://mcp.redcenterstudio.com/mcp
```

## Links

- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support: hello@redcenterstudio.com
- All Red Center Studio connectors: https://redcenterstudio.com/claude-connectors/
