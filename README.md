# Doing Work connectors

Public manifests, docs and logos for Doing Work's two hosted MCP connectors. There is no server code here: both connectors use one hosted server at doingwork.work/mcp with OAuth sign-in, so there are no keys or variables to configure.

| Connector | Who it's for | Remote URL | Official MCP Registry |
|---|---|---|---|
| [Home Service Quotes by Doing Work](home-service-quotes/) | Homeowners | `https://doingwork.work/mcp` | `work.doingwork/home` |
| [Field Service Business Platform by Doing Work](field-service-business-platform/) | Home service shops on Doing Work | `https://doingwork.work/mcp` | `work.doingwork/shop` |

- **Home Service Quotes:** get quotes from shops on Doing Work for a home repair or project anywhere in the US. Free for customers and shops, with no lead or referral fees. A shop gets your contact details only when you book it.
- **Field Service Business Platform:** for home service shops on Doing Work. Run the shop from chat: customers, jobs, quotes, invoices, payments, visits and photos, plus customer quote requests.

## Add to an assistant
- Any MCP client that supports remote servers: add `https://doingwork.work/mcp`. One server has both the customer and the shop tools; `.mcp.json` at the repo root lists it.
- Cursor: this repo is a Cursor plugin marketplace (`.cursor-plugin/marketplace.json`), with one plugin per folder.
- Setup for other assistants: https://doingwork.work/agents/install/

## Links
- Docs: https://doingwork.work/connectors/
- Privacy: https://doingwork.work/privacy/ and https://doingwork.work/privacy/connectors/
- Terms: https://doingwork.work/terms/
- Support: contact@doingwork.work

Doing Work (doingwork.work) is not affiliated with doing.work.

Doing Work LLC, 212 W Ironwood Dr Ste D PMB 466, Coeur d'Alene, ID 83814
