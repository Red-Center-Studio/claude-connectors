# Listing text and submission steps

Paste-ready text for directories. Nothing here has been submitted yet. Steps marked (owner) need the owner's own sign-in.

## 200 character blurbs

- **WebDesk for Claude:** Build and publish a small business website from Claude, hosted on a mywebdesk.app address with a quote form that emails you each enquiry. Free plan, email-code sign-in, free code export.
- **Site Watch:** Website monitoring in Claude: domain and certificate expiry, DNS and email security (SPF, DMARC, DKIM) and AI crawler access, with plain-language alerts and fixes. Free plan, 1 site.
- **VaultSheet:** Fills security questionnaires and tender spreadsheets (.xlsx) from your approved answer vault, copying answers word for word and flagging gaps. Free plan; email-code sign-in.
- **No-code app data migrator:** Moves a Bubble app's data to a Cloudflare D1 database and R2 bucket you own, verifying every step. Audit and plan are free; paid 30-day passes per app.

## Official MCP Registry (owner)

Each connector folder has a `server.json` named `io.github.Red-Center-Studio/<slug>`.

1. Install the publisher: https://github.com/modelcontextprotocol/registry (see its README for the current install command).
2. `mcp-publisher login github` and follow the device login in a browser (owner).
3. From each folder (`webdesk-claude`, `sitewatch`, `vaultsheet`, `nocode-migrator`) run `mcp-publisher publish`.
4. Check each at `https://registry.modelcontextprotocol.io/v0/servers?search=<slug>`.

The registry limits `description` to 100 characters; every entry here is within that.

## Other directories (owner)

- **Glama:** claim the studio's existing webdesk-mcp listing at glama.ai, then add the four connectors from this repository URL.
- **Smithery, mcp.so, PulseMCP, mcpservers.org:** submit each connector with its blurb, connector URL, product page and this repository URL. mcpservers.org already lists webdesk-mcp.
- **Awesome lists:** open a pull request to the lists you choose (for example punkpeye/awesome-mcp-servers) adding one line per connector: name, link to the folder here, and the 200 character blurb.
- **Anthropic directory:** WebDesk is published; VaultSheet and the free tools server are in review.

## Do not list

SharehouseHub is not launched and is not part of this repository.