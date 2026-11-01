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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sense is a ClimateTech company founded in 2013 that provides home energy intelligence through a high-resolution electrical monitoring device installed in residential electrical panels. The Sense platform captures real-time electricity usage data and uses machine learning to disaggregate power consumption into individual device-level signatures, enabling homeowners to understand exactly which appliances are using electricity and when. The API provides access to real-time power consumption and solar production data via a WebSocket realtime feed, and historical trend data via a REST interface covering daily, weekly, monthly, and annual usage breakdowns. Sense also supports device detection data, grid exchange metrics, and push notifications through integrations including Amazon Alexa. The company pivoted in 2025 to embed its machine learning technology directly into next-generation smart meters deployed by utility partners, expanding its reach to tens of millions of homes without requiring standalone hardware purchases.

**Areas:** Energy · Home Energy Monitoring · IoT · Smart Home · Electricity · Solar · Device Detection · Real-Time Data · Climate Tech

## Sense on APIs.io

Everything profiled for Sense is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sense/](https://apis.io/providers/sense/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Sense Realtime API](https://apis.io/apis/sense/sense-realtime-api/) — The Sense Realtime API delivers live electricity usage data via a WebSocket connection, streaming second-by-second power consumption readings for the whole…
- [Sense Authentication API](https://apis.io/apis/sense/sense-authentication-api/) — Authenticate and manage sessions
- [Sense Devices API](https://apis.io/apis/sense/sense-devices-api/) — Device-level energy data and device information
- [Sense History API](https://apis.io/apis/sense/sense-history-api/) — Historical energy usage and solar production data
- [Sense Monitors API](https://apis.io/apis/sense/sense-monitors-api/) — Monitor overview, status, and device detection
- [Sense Users API](https://apis.io/apis/sense/sense-users-api/) — User-level timeline and usage data

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Sense Agentic Access](https://apis.io/agentic-access/sense/sense-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Sense Device](https://apis.io/schemas/sense/sense-device/)
- [Sense Realtime Payload](https://apis.io/schemas/sense/sense-realtime-payload/)
- [Sense Usage History](https://apis.io/schemas/sense/sense-usage-history/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Sense Context](https://apis.io/jsonld/sense/sense-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Sense API Vocabulary](https://apis.io/vocabularies/sense/sense-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Sense Authenticate Request](https://apis.io/examples/sense/sense-authenticate-request/)
- [Sense Authenticate Response](https://apis.io/examples/sense/sense-authenticate-response/)
- [Sense Realtime Payload](https://apis.io/examples/sense/sense-realtime-payload/)
- [Sense Solar History Response](https://apis.io/examples/sense/sense-solar-history-response/)
- [Sense Usage History Response](https://apis.io/examples/sense/sense-usage-history-response/)

#### Collections (5)

Postman and Open Collection request collections.

- [Sense Client Authentication API](https://apis.io/collections/sense/open-sense-authentication-api/)
- [Sense Client Authentication Devices API](https://apis.io/collections/sense/open-sense-devices-api/)
- [Sense Client Authentication History API](https://apis.io/collections/sense/open-sense-history-api/)
- [Sense Client Authentication Monitors API](https://apis.io/collections/sense/open-sense-monitors-api/)
- [Sense Client Authentication Users API](https://apis.io/collections/sense/open-sense-users-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Sense — jsonschema rules](https://apis.io/rules/sense/sense-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Sense Authentication](https://apis.io/security/sense/sense-authentication/)
- [Sense Domain Security](https://apis.io/security/sense/sense-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sense Plans Pricing](https://apis.io/plans/sense/sense-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Sense Rate Limits](https://apis.io/rate-limits/sense/sense-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Sense Finops](https://apis.io/finops/sense/sense-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sense.com)
- [Documentation](https://help.sense.com)
- [Pricing](https://sense.com/homes/buy-monitor/)
- [Blog](https://blog.sense.com)
- [Status](https://status.sense.com)

## API Evangelist rating

**Kin Score 34.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 59.3 |
| Contract governance | 9.8 |
| Operational transparency | 28.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 18.4 |

**Agent readiness 22.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 13.9** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sense/](https://apis.io/providers/sense/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sense: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sense/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
