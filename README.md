# Sense

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sense is a ClimateTech company founded in 2013 that provides home energy intelligence through a high-resolution electrical monitoring device installed in residential electrical panels. The Sense platform uses machine learning to disaggregate whole-home power consumption into individual device-level signatures, enabling homeowners to understand exactly which appliances consume electricity and when. The company announced in late 2025 that it would stop selling the standalone Sense Monitor, pivoting to embed its technology directly into next-generation smart meters deployed by utility partners across the United States.

## APIs

The Sense platform exposes two primary API surfaces for programmatic access to energy data:

**Sense Client API** — A REST API at `https://api.sense.com/apiservice/api/v1/` providing access to historical trend data, device detection results, monitor health, and account information. Supports time scales of day, week, month, year, and billing cycle.

**Sense Realtime API** — A WebSocket feed at `wss://clientrt.sense.com/monitors/{monitor_id}/realtimefeed` delivering live electricity usage data including whole-home wattage, solar production, grid exchange, and real-time device on/off status.

## Authentication

Both APIs use bearer token authentication. Clients authenticate with username and password credentials against the Client API to receive an access token and refresh token. The access token is passed as an `Authorization: bearer {token}` header for REST calls and as a query parameter for the WebSocket connection. Multi-factor authentication (MFA) is supported.

## Status

- Status Page: https://status.sense.com
- Support: https://help.sense.com
- Blog: https://blog.sense.com

## Links

- Website: https://sense.com
- LinkedIn: https://www.linkedin.com/company/senseenergy
- X: https://x.com/sense
- GitHub (community API library): https://github.com/scottbonline/sense

## Maintainers

**Kin Lane** — kin@apievangelist.com
