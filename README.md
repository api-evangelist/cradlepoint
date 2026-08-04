# Cradlepoint (cradlepoint)

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

Cradlepoint is a Boise, Idaho-based provider of cloud-managed wireless edge routers, 5G adapters, branch-in-a-box appliances, and the NetCloud platform for enterprise wireless WAN (LTE/5G), in-vehicle networks, branch connectivity, and IoT. Ericsson acquired Cradlepoint in 2020 (closed November 2020 for approximately US$1.1B) and Cradlepoint now operates as the core of Ericsson Enterprise Wireless Solutions, working alongside Ericsson Private 5G and the Ericsson NetCloud SASE offering. Cradlepoint exposes its NetCloud Manager (NCM) platform through a documented RESTful API — NCM API v2 (Swagger 1.2, paired X-CP-API-ID/X-CP-API-KEY + X-ECM-API-ID/X-ECM-API-KEY headers, base https://www.cradlepointecm.com/api/v2/) and a newer NCM API v3 (OpenAPI 3.0, bearer-token authentication) — plus a NetCloud Router SDK for on-router Python applications and webhook destinations for alert delivery. The developer area (developer.cradlepoint.com), customer support article base (customer.cradlepoint.com), and Ericsson Enterprise Wireless docs portal (docs.cradlepoint.com) host the Getting Started guides, API reference, sample collections, and Postman bundles.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cradlepoint/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cradlepoint/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Wireless WAN
- 5G
- LTE
- Edge
- Branch Networking
- SD-WAN
- SASE
- Routers
- In-Vehicle
- IoT
- Cellular
- Private 5G
- NetCloud
- Ericsson

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Cradlepoint NetCloud Manager API v2

RESTful API for the NetCloud Manager (NCM) platform. Programmatic access to accounts, routers, groups, configuration_managers, alerts and alert_rules, alert_push_destinations, activity_logs, locations and historical_locations, net_devices, net_device_signal_samples, net_device_usage_samples, net_device_health, net_device_metrics, router_alerts, router_lans, router_state_samples, users, subscriptions, and firmware. Base URL https://www.cradlepointecm.com/api/v2/. Authentication uses two paired key sets sent as headers on every request — X-CP-API-ID / X-CP-API-KEY (account-level Cradlepoint API keys, for usage tracking) and X-ECM-API-ID / X-ECM-API-KEY (NCM-tenant API keys generated from the NCM Tools tab; carry the Administrator / Full Access / Read-Only / Diagnostic role grants). Supports GET, POST, PUT, PATCH, DELETE; not every method is supported on every resource. Documented with Swagger 1.2.

- **Human URL:** [https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview](https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview)
- **Base URL:** `https://www.cradlepointecm.com/api/v2/`

#### Tags

- NetCloud
- Routers
- Wireless WAN
- Edge
- Cellular

#### Properties

- [Documentation](https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview)
- [Documentation](https://docs.cradlepoint.com/r/NCM-APIv2-Overview)
- [Getting Started](https://customer.cradlepoint.com/s/article/NetCloud-API-Getting-Started-Guide)
- [Developer](https://developer.cradlepoint.com/)
- [OpenAPI](openapi/cradlepoint-netcloud-manager-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cradlepoint-netcloud-manager-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cradlepoint-netcloud-manager-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman](https://developer.cradlepoint.com/documentation/samples) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Sample Code](https://github.com/cradlepoint/api-samples)
- [JSON Schema](json-schema/cradlepoint-router-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cradlepoint-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cradlepoint-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Cradlepoint NetCloud Manager API v3

The next-generation NetCloud Manager API. Documented with OpenAPI 3.0, authenticated with bearer tokens, designed for improved performance, stability, and usability over API v2. Coexists with v2 during a multi-year transition window; v3 covers core router, device, alert, group, and account operations.

- **Human URL:** [https://customer.cradlepoint.com/s/article/NetCloud-Manager-API-v3](https://customer.cradlepoint.com/s/article/NetCloud-Manager-API-v3)

#### Tags

- NetCloud
- Routers
- 5G

#### Properties

- [Documentation](https://customer.cradlepoint.com/s/article/NetCloud-Manager-API-v3)
- [Developer](https://developer.cradlepoint.com/)
- [Sample Code](https://github.com/cradlepoint/api-samples)
- [Postman Collection](collections/cradlepoint-netcloud-manager-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cradlepoint-netcloud-manager-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cradlepoint NetCloud Alert Webhooks

Outbound HTTP destinations (alert_push_destinations) configured via the NCM API or UI to receive real-time JSON alert payloads when NCM alert rules fire (router offline, signal degradation, configuration change, subscription expiration, threshold breach). Each destination is a URL + optional auth headers; payload includes account, router, alert type, timestamp, and contextual metadata.

- **Human URL:** [https://developer.cradlepoint.com/documentation/webhooks](https://developer.cradlepoint.com/documentation/webhooks)

#### Tags

- Webhooks
- Events
- Alerts

#### Properties

- [Documentation](https://developer.cradlepoint.com/documentation/webhooks)
- [Documentation](https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview)
- [Postman Collection](collections/cradlepoint-netcloud-manager-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cradlepoint-netcloud-manager-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cradlepoint NetCloud Router SDK

On-router Python SDK and toolchain (the "SDK" / "Router SDK") for building and deploying custom applications onto Cradlepoint routers running NetCloud OS. Lets developers write Python apps that read router configuration, GPIO, GPS, modem signal, and connection state, and that can be packaged and deployed across a fleet via NCM. Sample apps in cradlepoint/sdk-samples cover GPS forwarding, modem diagnostics, serial passthrough, MQTT publishing, and more.

- **Human URL:** [https://github.com/cradlepoint/sdk-samples](https://github.com/cradlepoint/sdk-samples)

#### Tags

- SDK
- Edge
- Python
- Routers

#### Properties

- [SDK](https://github.com/cradlepoint/sdk-samples)
- [Documentation](https://customer.cradlepoint.com/s/article/NCOS-Router-SDK-Developers-Guide)
- [Language](https://www.python.org/)
- [Postman Collection](collections/cradlepoint-netcloud-manager-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cradlepoint-netcloud-manager-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://cradlepoint.com)
- [Company](https://cradlepoint.com/about-us/)
- [Products](https://cradlepoint.com/products/)
- [Net Cloud](https://cradlepoint.com/products/netcloud-service/)
- [Net Cloud S A S E](https://cradlepoint.com/products/netcloud-sase/)
- [Private5 G](https://cradlepoint.com/products/private-5g/)
- [Developer](https://developer.cradlepoint.com/)
- [Documentation](https://docs.cradlepoint.com/)
- [Support](https://customer.cradlepoint.com/)
- [Git Hub](https://github.com/cradlepoint)
- [A P I Samples](https://github.com/cradlepoint/api-samples)
- [S D K Samples](https://github.com/cradlepoint/sdk-samples)
- [Container Samples](https://github.com/cradlepoint/container-samples)
- [Blog](https://cradlepoint.com/resources/blog/)
- [News](https://cradlepoint.com/news-events/)
- [Pricing](https://cradlepoint.com/lets-talk/)
- [Careers](https://cradlepoint.com/about-us/careers/)
- [Contact](https://cradlepoint.com/lets-talk/)
- [Ericsson](https://www.ericsson.com/en/enterprise-wireless-solutions)
- [Twitter](https://twitter.com/cradlepoint)
- [LinkedIn](https://www.linkedin.com/company/cradlepoint)
- [YouTube](https://www.youtube.com/@Cradlepoint)
- [Plans](plans/cradlepoint-plans-pricing.yml)
- [Rate Limits](rate-limits/cradlepoint-rate-limits.yml)
- [Fin Ops](finops/cradlepoint-finops.yml)
- [Vocabulary](vocabulary/cradlepoint-vocabulary.yml)
- [Spectral Rules](rules/cradlepoint-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
