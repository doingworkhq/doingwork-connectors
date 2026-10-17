# Home Service Quotes by Doing Work

Get quotes from local shops for a home repair or project, right from Cursor. Free for homeowners.

## What it does
- Describe the job in plain words and add photos.
- Check the job summary and address before any shop is found.
- See local shops with a short reason for each, and remove any you don't want.
- Approve the exact message and shop list before anything is sent.
- Read quotes in the order they arrive.

We don't sell your contact info, and your phone won't blow up with calls. Shops see your first name, town and job details, and only get your phone and email if you pick them.

## Connect
The plugin adds the remote MCP server `https://app.doingwork.work/mcp/home`. On first use, Cursor opens "Sign in with Doing Work" on app.doingwork.work. Enter your email and the 6-digit code we email you, then choose Allow. Cursor never sees the code. Sign-in is OAuth 2.1 with dynamic client registration and PKCE, so there is no key to configure. You can also choose read-only access, which can only list your requests and read quotes.

## Tools
| Tool | What it does |
|---|---|
| quote_request_list | Lists your quote requests. Read only. |
| quote_request_status | Reads the quotes shops sent. Read only. |
| quote_request_update | Describes the job in a draft request. |
| quote_request_add_photo | Adds a job photo. |
| quote_request_confirm_summary | Confirms the job summary, after a preview. |
| quote_request_find_shops | Saves a short list of local shops. Contacts no one. |
| quote_request_approve_and_send | Emails the shops you approved, after a preview and your confirmation. |
| quote_request_pick_shop | Hires one shop, after a preview and your confirmation. Shares your phone and email with that shop and closes the request. Can't be undone. |

## Try it
- "My water heater is leaking. Can you get me quotes?"
- "Find a few local roofers to look at a leak over my garage."
- "Did anyone send a quote on my fence job?"

## Limits
US only. Shop coverage depends on your area and the trade; the connector says so when it finds none.

## Links
- Docs: https://doingwork.work/connectors/
- Setup for other assistants: https://doingwork.work/agents/install/
- Privacy: https://doingwork.work/privacy/ and https://doingwork.work/privacy/connectors/
- Terms: https://doingwork.work/terms/
- Support: contact@doingwork.work
- Doing Work LLC, 212 W Ironwood Dr Ste D PMB 466, Coeur d'Alene, ID 83814
