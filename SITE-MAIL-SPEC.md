# jaxiof.org site ↔ Gmail — implement in App Builder

Public mail never says Olivia, Super Admin, or desk names. From: JaxInandOutdoorSG@gmail.com. BCC the plus-address. Reply in the same thread.

## /contact
Topic required: General → +contact `[JAX IOF Contact]`
Partner/Sponsor → +sponsor `[JAX IOF Sponsor]`
Volunteer → +volunteer `[JAX IOF Volunteer]`
Class question → +events `[JAX IOF Event]`
Site issue → +issues `[JAX IOF Site Issues]`
Vendor → +vendor `[JAX IOF Vendor]`
SLA line: response within 1 business day; urgent (904) 759-3703.

## /get-involved Volunteer Desk
Role: Classroom Aide | Instructor | Event Hoster | Range | Store | Church | Organization | Sponsor | Individual
Aide/Instructor/Hoster → +volunteer `[JAX IOF Volunteer]`
Range/Store/Church/Organization/Sponsor → +sponsor `[JAX IOF Sponsor]`
Record the person on /account/collaborators. Gmail keeps the thread only.

## /forms No-Show
To registrant + BCC +events. Subject `[JAX IOF Event] No-show`. Body: class, date, calendar link.

## /events/notifications (email channel)
Classes & events → `[JAX IOF Event]` +events — same facts as app/text: class, date, time, place, https://jaxiof.org/events/calendar
Donations → `[JAX IOF Donation]` +donate — amount, date, EIN 42-3768113 (matches Stripe Payments mail, different folder)
Site issues → `[JAX IOF Site Issues]` +issues
Shop drops → `[JAX IOF Shop]` (availability). After ship → `[JAX IOF Ships]` tracking.
Foundation updates opt-in → `[JAX IOF Newsletter]` +newsletter. Named ask → `[JAX IOF Reach]` +reach. Never mix.

## /account/events create
One action: publish calendar, send `[JAX IOF Event]`, BCC +events. Grok creates Google Calendar when date/time parse.

## SMTP later
Send forms through this Gmail so Sent is the log. Until then BCC plus-addresses.
