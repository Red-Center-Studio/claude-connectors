# VaultSheet

Fills security questionnaires, due diligence questionnaires and tender spreadsheets (.xlsx, .xlsm) from a vault of answers your team has approved. It copies answers word for word and never writes one itself, flags weak matches for a person to review, leaves gaps blank, keeps the workbook's styles and macros, and adds an audit sheet.

- **Connector URL:** `https://mcp.redcenterstudio.com/vaultsheet/mcp`
- **Product page:** https://redcenterstudio.com/vaultsheet/
- **Plans:** Free plan: 2 questionnaire runs a month of up to 150 rows, 25 approved answers, 1 vault, 1 person. Paid plans (Solo, Team, Agency) add more people, vaults, answers and runs. Prices are on the plans page.
- **Sign-in:** You sign in with your email address and a 6-digit code. Uploaded and filled workbooks are deleted within 24 hours.

## Add it to Claude

**Claude on the web or desktop:** Settings, then Connectors, then Add custom connector. Name it VaultSheet and paste `https://mcp.redcenterstudio.com/vaultsheet/mcp` as the URL.

**Claude Code:**

```bash
claude mcp add --transport http vaultsheet https://mcp.redcenterstudio.com/vaultsheet/mcp
```

## Links

- Privacy policy: https://redcenterstudio.com/privacy/
- Terms: https://redcenterstudio.com/terms/
- Support: hello@redcenterstudio.com
- All Red Center Studio connectors: https://redcenterstudio.com/claude-connectors/
