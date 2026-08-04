# Dexcom (dexcom)

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

Dexcom is a leading medical device company that develops, manufactures, and distributes continuous glucose monitoring (CGM) systems for people with diabetes. The company's wearable sensors stream real-time glucose data to mobile apps, dedicated receivers, and connected health platforms. Dexcom exposes a public developer program that lets approved third parties retrieve CGM data (estimated glucose values, events, calibrations, alerts, devices, and data range) through an OAuth 2.0 secured REST API, with a sandbox for development and a production environment for live patient data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Continuous Glucose Monitoring
- Diabetes
- Digital Health
- Glucose
- Healthcare
- Medical Devices
- Wearables

## Timestamps

- **Created:** 2026-05-04
- **Modified:** 2026-05-19

## APIs

### Dexcom Developer API

REST API for retrieving Dexcom continuous glucose monitoring data on behalf of authorized end users. Authentication is OAuth 2.0 authorization code flow; sandbox and production hosts are separate. Resources include estimated glucose values (EGVs), events, calibrations, alerts, devices, and data range. Intended for research, clinical, and consumer applications that integrate Dexcom CGM data with other digital health experiences.

- **Human URL:** [https://developer.dexcom.com/](https://developer.dexcom.com/)
- **Base URL:** `https://api.dexcom.com`

#### Tags

- CGM
- Glucose
- Healthcare
- REST

#### Properties

- [Documentation](https://developer.dexcom.com/)
- [Getting Started](https://developer.dexcom.com/get-started)
- [API Reference](https://developer.dexcom.com/docs/dexcomv3/endpoint-overview)
- [Authentication](https://developer.dexcom.com/docs/dexcom/authentication/)
- [Sandbox](https://sandbox-api.dexcom.com)
- [Terms of Service](https://developer.dexcom.com/terms-of-use)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/openapi/dexcom-dexcom-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-egv-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-egvs-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-event-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-events-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-calibration-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-calibrations-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-alert-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-alerts-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-alert-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-alert-setting-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-device-record-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-devices-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-data-range-moment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-data-range-window-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-data-range-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-token-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-token-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-glucose-unit-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-rate-unit-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-trend-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-egv-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-event-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-event-status-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-alert-name-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-alert-state-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-transmitter-generation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-schema/dexcom-api-date-time-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-egv-record-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-egvs-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-event-record-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-events-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-calibration-record-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-calibrations-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-alert-record-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-alerts-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-alert-schedule-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-alert-setting-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-device-record-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-devices-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-data-range-moment-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-data-range-window-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-data-range-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-token-request-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-token-response-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-glucose-unit-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-rate-unit-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-trend-type-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-egv-status-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-event-type-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-event-status-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-alert-name-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-alert-state-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-transmitter-generation-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-structure/dexcom-api-date-time-structure.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-egv-record-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-egvs-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-event-record-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-events-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-calibration-record-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-calibrations-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-alert-record-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-alerts-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-alert-schedule-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-alert-setting-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-device-record-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-devices-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-data-range-moment-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-data-range-window-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-data-range-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-token-request-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-token-response-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-glucose-unit-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-rate-unit-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-trend-type-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-egv-status-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-event-type-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-event-status-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-alert-name-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-alert-state-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-transmitter-generation-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/examples/dexcom-api-date-time-example.json)
- [Postman Collection](collections/dexcom-dexcom-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dexcom-dexcom-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/dexcom)
- [Website](https://www.dexcom.com/)
- [Developer Portal](https://developer.dexcom.com/)
- [Documentation](https://developer.dexcom.com/)
- [Getting Started](https://developer.dexcom.com/get-started)
- [Authentication](https://developer.dexcom.com/docs/dexcom/authentication/)
- [Sandbox](https://sandbox-api.dexcom.com)
- [Terms of Service](https://www.dexcom.com/terms-of-use)
- [Privacy Policy](https://www.dexcom.com/privacy-policy)
- [Support](https://www.dexcom.com/contact)
- [GitHub Organization](https://github.com/dexcom)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/rules/dexcom-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/vocabulary/dexcom-vocabulary.yml)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/dexcom/refs/heads/main/json-ld/dexcom-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [Integrations](https://www.dexcom.com/en-us/apps)
- [L L Ms Txt](https://developer.dexcom.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
