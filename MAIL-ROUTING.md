# jaxiof.org ↔ Gmail routing

All public and Admin mail uses **JaxInandOutdoorSG@gmail.com** and the **JAX IOF** Gmail labels.
Website origin: https://jaxiof.org/

When a desk or form sends mail, include a short subject prefix so filing can match it.

| Website / desk | Path | Subject prefix | Gmail label |
|---|---|---|---|
| Contact | /contact | `[JAX IOF Contact]` | JAX IOF/Contact |
| Report Site Issues | /contact/report | `[JAX IOF Site Issues]` | JAX IOF/Site Issues |
| Ship an Order | /account/olivia-ships | `[JAX IOF Ships]` | JAX IOF/Ships |
| Reach | /account/olivia-reach | `[JAX IOF Reach]` | JAX IOF/Reach |
| Grants | /account/olivia-grants | `[JAX IOF Grants]` | JAX IOF/Grants |
| Donation thank-you | /account/gift, /donate | `[JAX IOF Donation]` | JAX IOF/Donation Acknowledgments |
| Tax letters | /account/tax | `[JAX IOF Tax]` | JAX IOF/Tax Letters |
| Events | /account/events, /events | `[JAX IOF Event]` | JAX IOF/Event Notices |
| Security watch | /account/olivia-security | `[JAX IOF Security]` | JAX IOF/Security Alerts |
| Stripe checkout | /donate, /cart | Stripe payment subjects | JAX IOF/Payments |
| Cloudflare / domains | jaxiof.org, jaxiof.com | — | JAX IOF/Website |
| Sponsors | /account/collaborators | `[JAX IOF Sponsor]` | JAX IOF/Sponsors & Collaborators |
| Vendors | ops mail | `[JAX IOF Vendor]` | JAX IOF/Vendors |

BCC JaxInandOutdoorSG@gmail.com on every outbound desk email so Sent + Inbox copies file themselves.

Autonomous filing:
- On every new inbound message to JaxInandOutdoorSG@gmail.com
- Daily sweep at 07:30 America/New_York
