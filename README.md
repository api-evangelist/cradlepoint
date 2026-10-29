# Cradlepoint

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

Cradlepoint is a Boise, Idaho-based provider of cloud-managed wireless edge routers, 5G adapters, branch-in-a-box appliances, and the NetCloud platform for enterprise wireless WAN (LTE/5G), in-vehicle networks, branch connectivity, and IoT. Ericsson acquired Cradlepoint in 2020 (closed November 2020 for approximately US$1.1B) and Cradlepoint now operates as the core of Ericsson Enterprise Wireless Solutions, working alongside Ericsson Private 5G and the Ericsson NetCloud SASE offering. Cradlepoint exposes its NetCloud Manager (NCM) platform through a documented RESTful API — NCM API v2 (Swagger 1.2, paired X-CP-API-ID/X-CP-API-KEY + X-ECM-API-ID/X-ECM-API-KEY headers, base https://www.cradlepointecm.com/api/v2/) and a newer NCM API v3 (OpenAPI 3.0, bearer-token authentication) — plus a NetCloud Router SDK for on-router Python applications and webhook destinations for alert delivery. The developer area (developer.cradlepoint.com), customer support article base (customer.cradlepoint.com), and Ericsson Enterprise Wireless docs portal (docs.cradlepoint.com) host the Getting Started guides, API reference, sample collections, and Postman bundles.

**Areas:** Wireless WAN · 5G · LTE · Edge · Branch Networking · SD-WAN · SASE · Router · In-Vehicle · IoT · Cellular · Private 5G

## Cradlepoint on APIs.io

Everything profiled for Cradlepoint is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cradlepoint/](https://apis.io/providers/cradlepoint/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Cradlepoint NetCloud Manager API v3](https://apis.io/apis/cradlepoint/netcloud-manager-api-v3/) — The next-generation NetCloud Manager API. Documented with OpenAPI 3.0, authenticated with bearer tokens, designed for improved performance, stability, and…
- [Cradlepoint NetCloud Alert Webhooks](https://apis.io/apis/cradlepoint/netcloud-webhooks/) — Outbound HTTP destinations (alert_push_destinations) configured via the NCM API or UI to receive real-time JSON alert payloads when NCM alert rules fire…
- [Cradlepoint NetCloud Router SDK](https://apis.io/apis/cradlepoint/netcloud-router-sdk/) — On-router Python SDK and toolchain (the "SDK" / "Router SDK") for building and deploying custom applications onto Cradlepoint routers running NetCloud OS.…
- [Cradlepoint Accounts API](https://apis.io/apis/cradlepoint/cradlepoint-accounts-api/) — Account and subaccount management
- [Cradlepoint AlertPushDestinations API](https://apis.io/apis/cradlepoint/cradlepoint-alertpushdestinations-api/) — Outbound webhook destinations for alert delivery
- [Cradlepoint Alerts API](https://apis.io/apis/cradlepoint/cradlepoint-alerts-api/) — Generated alerts
- [Cradlepoint Groups API](https://apis.io/apis/cradlepoint/cradlepoint-groups-api/) — Logical device groupings
- [Cradlepoint Locations API](https://apis.io/apis/cradlepoint/cradlepoint-locations-api/) — Current and historical router location
- [Cradlepoint NetDevices API](https://apis.io/apis/cradlepoint/cradlepoint-netdevices-api/) — Modems, WAN devices, and network interfaces on routers
- [Cradlepoint Routers API](https://apis.io/apis/cradlepoint/cradlepoint-routers-api/) — Router (edge device) management
- [Cradlepoint Activity Logs API](https://apis.io/apis/cradlepoint/cradlepoint-activity-logs-api/) — Audit / activity logs across accounts
- [Cradlepoint Alert Rules API](https://apis.io/apis/cradlepoint/cradlepoint-alert-rules-api/) — Alert monitoring rule configuration

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cradlepoint Agentic Access](https://apis.io/agentic-access/cradlepoint/cradlepoint-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Cradlepoint NCM Alert](https://apis.io/schemas/cradlepoint/cradlepoint-alert/)
- [Cradlepoint Router](https://apis.io/schemas/cradlepoint/cradlepoint-router/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cradlepoint Context](https://apis.io/jsonld/cradlepoint/cradlepoint-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cradlepoint Vocabulary](https://apis.io/vocabularies/cradlepoint/cradlepoint-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Cradlepoint Alert Webhook Example](https://apis.io/examples/cradlepoint/cradlepoint-alert-webhook-example/)
- [Cradlepoint List Routers Example](https://apis.io/examples/cradlepoint/cradlepoint-list-routers-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [Cradlepoint NetCloud Manager API v2 Accounts API](https://apis.io/collections/cradlepoint/open-cradlepoint-accounts-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts ActivityLogs API](https://apis.io/collections/cradlepoint/open-cradlepoint-activitylogs-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts AlertPushDestinations API](https://apis.io/collections/cradlepoint/open-cradlepoint-alertpushdestinations-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts AlertRules API](https://apis.io/collections/cradlepoint/open-cradlepoint-alertrules-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts Alerts API](https://apis.io/collections/cradlepoint/open-cradlepoint-alerts-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts Groups API](https://apis.io/collections/cradlepoint/open-cradlepoint-groups-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts Locations API](https://apis.io/collections/cradlepoint/open-cradlepoint-locations-api/)
- [Cradlepoint NetCloud Manager API v2](https://apis.io/collections/cradlepoint/open-cradlepoint-netcloud-manager-api-v2/)
- [Cradlepoint NetCloud Manager API v2 Accounts NetDevices API](https://apis.io/collections/cradlepoint/open-cradlepoint-netdevices-api/)
- [Cradlepoint NetCloud Manager API v2 Accounts Routers API](https://apis.io/collections/cradlepoint/open-cradlepoint-routers-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cradlepoint — jsonschema rules](https://apis.io/rules/cradlepoint/cradlepoint-jsonschema-spectral-rules/)
- [Cradlepoint API Rules](https://apis.io/rules/cradlepoint/cradlepoint-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Cradlepoint Authentication](https://apis.io/security/cradlepoint/cradlepoint-authentication/)
- [Cradlepoint Domain Security](https://apis.io/security/cradlepoint/cradlepoint-domain-security/)
- [Cradlepoint Vulnerability Disclosure](https://apis.io/security/cradlepoint/cradlepoint-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cradlepoint Plans Pricing](https://apis.io/plans/cradlepoint/cradlepoint-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cradlepoint Rate Limits](https://apis.io/rate-limits/cradlepoint/cradlepoint-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cradlepoint Finops](https://apis.io/finops/cradlepoint/cradlepoint-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cradlepoint.com)
- [Documentation](https://docs.cradlepoint.com/)
- [Pricing](https://cradlepoint.com/lets-talk/)
- [Support](https://customer.cradlepoint.com/)
- [Blog](https://cradlepoint.com/resources/blog/)

## API Evangelist rating

**Kin Score 36.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 58.0 |
| Contract quality | 58.5 |
| Contract governance | 27.3 |
| Operational transparency | 5.3 |
| Developer ergonomics | 52.4 |
| Access clarity | 7.9 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
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

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cradlepoint/](https://apis.io/providers/cradlepoint/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cradlepoint: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cradlepoint/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
