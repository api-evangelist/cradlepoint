# Cradlepoint (cradlepoint)

Cradlepoint is a Boise, Idaho-based provider of cloud-managed wireless edge routers, 5G adapters, branch-in-a-box appliances, and the NetCloud platform for enterprise wireless WAN (LTE/5G), in-vehicle networks, branch connectivity, and IoT. Ericsson acquired Cradlepoint in 2020 (closed November 2020 for approximately US$1.1B) and Cradlepoint now operates as the core of Ericsson Enterprise Wireless Solutions, working alongside Ericsson Private 5G and the NetCloud SASE offering. Cradlepoint exposes its NetCloud Manager (NCM) platform through a documented RESTful API — NCM API v2 (Swagger 1.2, paired `X-CP-API-ID` / `X-CP-API-KEY` + `X-ECM-API-ID` / `X-ECM-API-KEY` headers, base `https://www.cradlepointecm.com/api/v2/`) and a newer NCM API v3 (OpenAPI 3.0, bearer-token authentication) — plus a NetCloud Router SDK for on-router Python applications and webhook destinations for alert delivery.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/cradlepoint/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Wireless WAN, 5G, LTE, Edge, Branch Networking, SD-WAN, SASE, Routers, In-Vehicle, IoT, Cellular, Private 5G, NetCloud, Ericsson

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Cradlepoint NetCloud Manager API v2

RESTful API to the NetCloud Manager (NCM) platform. Accounts, routers, groups, alerts, alert rules, alert push destinations (webhooks), activity logs, locations and historical locations, net devices, users, subscriptions, and firmware. Base URL `https://www.cradlepointecm.com/api/v2/`. Authentication is paired keys: `X-CP-API-ID` / `X-CP-API-KEY` (account-level Cradlepoint API keys for usage tracking) plus `X-ECM-API-ID` / `X-ECM-API-KEY` (NCM tenant keys generated from the NCM Tools tab; carry the Administrator / Full Access / Read-Only / Diagnostic role). Documented with Swagger 1.2.

**Human URL:** [https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview](https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview)

- [Documentation — NCM API v2 Overview](https://customer.cradlepoint.com/s/article/NCM-APIv2-Overview)
- [Documentation — Ericsson Docs Portal](https://docs.cradlepoint.com/r/NCM-APIv2-Overview)
- [Getting Started Guide](https://customer.cradlepoint.com/s/article/NetCloud-API-Getting-Started-Guide)
- [Developer Portal](https://developer.cradlepoint.com/)
- [Sample Code](https://github.com/cradlepoint/api-samples)
- [OpenAPI](openapi/cradlepoint-netcloud-manager-api-v2-openapi.yml)
- [Naftiko Capability — Routers](capabilities/netcloud-manager-routers.yaml)
- [Naftiko Capability — Alerts](capabilities/netcloud-manager-alerts.yaml)
- [Naftiko Capability — Net Devices](capabilities/netcloud-manager-net-devices.yaml)
- [Naftiko Capability — Accounts](capabilities/netcloud-manager-accounts.yaml)
- [JSON Schema — Router](json-schema/cradlepoint-router-schema.json)
- [JSON Schema — Alert](json-schema/cradlepoint-alert-schema.json)
- [JSON-LD Context](json-ld/cradlepoint-context.jsonld)

### Cradlepoint NetCloud Manager API v3

The next-generation NCM API. Documented with OpenAPI 3.0, authenticated with bearer tokens, designed for improved performance, stability, and usability over v2. Coexists with v2 during a multi-year transition window.

**Human URL:** [https://customer.cradlepoint.com/s/article/NetCloud-Manager-API-v3](https://customer.cradlepoint.com/s/article/NetCloud-Manager-API-v3)

### Cradlepoint NetCloud Alert Webhooks

Outbound HTTP destinations (`alert_push_destinations`) configured via the NCM API or UI to receive real-time JSON alert payloads when NCM alert rules fire (router offline, signal degradation, configuration change, subscription expiration, threshold breach).

**Human URL:** [https://developer.cradlepoint.com/documentation/webhooks](https://developer.cradlepoint.com/documentation/webhooks)

### Cradlepoint NetCloud Router SDK

On-router Python SDK and toolchain for building and deploying custom applications onto Cradlepoint routers running NetCloud OS. Read router configuration, GPIO, GPS, modem signal, and connection state; package and deploy apps across a fleet via NCM.

**Human URL:** [https://github.com/cradlepoint/sdk-samples](https://github.com/cradlepoint/sdk-samples)

## Authentication (NCM API v2)

```bash
curl -v -X GET \
  -H "X-CP-API-ID:$X_CP_API_ID" \
  -H "X-CP-API-KEY:$X_CP_API_KEY" \
  -H "X-ECM-API-ID:$X_ECM_API_ID" \
  -H "X-ECM-API-KEY:$X_ECM_API_KEY" \
  -H "Content-Type:application/json" \
  https://www.cradlepointecm.com/api/v2/routers/
```

## Common Resources

- [Website](https://cradlepoint.com)
- [Products](https://cradlepoint.com/products/)
- [NetCloud Service](https://cradlepoint.com/products/netcloud-service/)
- [NetCloud SASE](https://cradlepoint.com/products/netcloud-sase/)
- [Private 5G](https://cradlepoint.com/products/private-5g/)
- [Developer Portal](https://developer.cradlepoint.com/)
- [Documentation Portal](https://docs.cradlepoint.com/)
- [Customer Support / Knowledge](https://customer.cradlepoint.com/)
- [GitHub](https://github.com/cradlepoint)
- [Ericsson Enterprise Wireless Solutions](https://www.ericsson.com/en/enterprise-wireless-solutions)
- [Blog](https://cradlepoint.com/resources/blog/)

## Commercial Surface

- [Plans and Pricing](plans/cradlepoint-plans-pricing.yml) — quote-based NetCloud Essentials / Advanced / Advanced Plus + SASE + Private 5G add-ons
- [Rate Limits](rate-limits/cradlepoint-rate-limits.yml) — server-side throttling, 429/503 backoff guidance
- [FinOps](finops/cradlepoint-finops.yml) — FOCUS-aligned subscription view
- [Spectral Rules](rules/cradlepoint-rules.yml) — NCM v2 API conventions
- [Vocabulary](vocabulary/cradlepoint-vocabulary.yml) — wireless WAN, edge, NetCloud, SASE, telemetry, governance

## Maintainer

Kin Lane &lt;kin@apievangelist.com&gt;
