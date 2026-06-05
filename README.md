# Dexcom (dexcom)

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
