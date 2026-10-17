# Doing Work connectors

Public manifests, docs and logos for Doing Work's two hosted MCP connectors. There is no server code here: both connectors run on app.doingwork.work and use OAuth sign-in, so there are no keys or variables to configure.

| Connector | Who it's for | Remote URL | Official MCP Registry |
|---|---|---|---|
| [Home Service Quotes by Doing Work](home-service-quotes/) | Homeowners | `https://app.doingwork.work/mcp/home` | `work.doingwork/home` |
| [Field Service Business Platform by Doing Work](field-service-business-platform/) | Home service shops on Doing Work | `https://app.doingwork.work/mcp/shop` | `work.doingwork/shop` |

- **Home Service Quotes:** get quotes from local shops for a home repair or project anywhere in the US. Free for homeowners, and free for shops to quote. We don't sell your contact info, and shops only get your phone and email if you pick them.
- **Field Service Business Platform:** for home service shops on Doing Work. See today's jobs and draft quotes and invoices from chat. Drafts wait for the owner's review; nothing goes to a customer from chat.

## Add to an assistant
- Any MCP client that supports remote servers: add the URL above. `.mcp.json` at the repo root lists both.
- Cursor: this repo is a Cursor plugin marketplace (`.cursor-plugin/marketplace.json`), with one plugin per folder.
- Setup for other assistants: https://doingwork.work/agents/install/

## Links
- Docs: https://doingwork.work/connectors/
- Privacy: https://doingwork.work/privacy/ and https://doingwork.work/privacy/connectors/
- Terms: https://doingwork.work/terms/
- Support: contact@doingwork.work

Doing Work (doingwork.work) is not affiliated with doing.work.

Doing Work LLC, 212 W Ironwood Dr Ste D PMB 466, Coeur d'Alene, ID 83814
