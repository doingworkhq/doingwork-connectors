# Home Service Quotes by Doing Work

Get quotes from shops on Doing Work for a home repair or project, right from Cursor. Free for customers and shops. Doing Work never charges lead or referral fees and never sets a price.

## What it does
- Describe the job in plain words, with the address, and add at least one photo.
- Send one request to the shops on Doing Work that serve your address and do that kind of work.
- Read each shop's reply in its own words and prices.
- Book one shop. If that shop asks for a deposit, you get a pay link for the amount it set.

Photos have location data removed before they are stored. A shop gets your name and email, and your phone if you give it, only when you book it.

## Connect
The plugin adds the remote MCP server `https://doingwork.work/mcp`. On first use, Cursor opens "Sign in with Doing Work". Enter your email, open the sign-in link we email you, then choose Allow. Sign-in is OAuth 2.1 with dynamic client registration and PKCE, so there is no key to configure. Signing in with your email creates your account.

## Tools
| Tool | What it does |
|---|---|
| network_info | How requests work: area, kinds of work, limits and the free pledge. Read only. |
| homeowner_createRequest | Starts a draft request: the work in your own words, the address and what you need. |
| homeowner_addPhoto | Adds a photo to a draft. |
| homeowner_sendRequest | Sends the request to matching shops. Ask the user first. |
| homeowner_listRequests | Lists your requests. Read only. |
| homeowner_getRequest | Reads your request and every reply so far. Read only. |
| homeowner_pickReply | Books one shop's reply and shares your contact details with that shop. Ask the user first. |
| homeowner_withdrawRequest | Withdraws a request you have not booked. |
| homeowner_reportNoShow | Tells Doing Work the booked shop did not show up. |

## Try it
- "My water heater is leaking. Can you get me quotes?"
- "Get a few roofers to look at a leak over my garage."
- "Did anyone reply on my fence job?"

## Limits
US addresses only. If no shop on Doing Work near you takes that kind of work yet, your request stays open and you can withdraw it any time. Requests you don't book are deleted after 90 days.

## Links
- Docs: https://doingwork.work/connectors/
- Setup for other assistants: https://doingwork.work/agents/install/
- Privacy: https://doingwork.work/privacy/ and https://doingwork.work/privacy/connectors/
- Terms: https://doingwork.work/terms/
- Support: contact@doingwork.work
- Doing Work LLC, 212 W Ironwood Dr Ste D PMB 466, Coeur d'Alene, ID 83814
