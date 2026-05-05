# Dexcom (dexcom)
Dexcom is a leading medical device company that develops, manufactures, and distributes continuous glucose monitoring (CGM) systems for people with diabetes. The company's wearable sensors stream real-time glucose data to mobile apps, dedicated receivers, and connected health platforms. Dexcom exposes a public developer program that lets approved third parties retrieve CGM data (estimated glucose values, events, calibrations, alerts, devices, and data range) through an OAuth 2.0 secured REST API, with a sandbox for development and a production environment for live patient data.

**URL:** [Visit APIs.json URL](https://developer.dexcom.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Continuous Glucose Monitoring, Diabetes, Digital Health, Glucose, Healthcare, Medical Devices, Wearables

## Timestamps

- **Created:** 2026-05-04
- **Modified:** 2026-05-05

## APIs

### Dexcom Developer API
REST API for retrieving Dexcom continuous glucose monitoring data on behalf of authorized end users. Authentication is OAuth 2.0 authorization code flow; sandbox and production hosts are separate. Resources include estimated glucose values (EGVs), events, calibrations, alerts, devices, and data range. Intended for research, clinical, and consumer applications that integrate Dexcom CGM data with other digital health experiences.

**Human URL:** [https://developer.dexcom.com/](https://developer.dexcom.com/)

#### Tags:

 - CGM, Glucose, Healthcare, REST

#### Properties

- [Documentation](https://developer.dexcom.com/)
- [GettingStarted](https://developer.dexcom.com/get-started)
- [APIReference](https://developer.dexcom.com/docs/dexcomv3/endpoint-overview)
- [Authentication](https://developer.dexcom.com/docs/dexcom/authentication/)
- [Sandbox](https://sandbox-api.dexcom.com)
- [TermsOfService](https://developer.dexcom.com/terms-of-use)
- [OpenAPI](openapi/dexcom-dexcom-api.yml)

## Common Properties

- [Website](https://www.dexcom.com/)
- [DeveloperPortal](https://developer.dexcom.com/)
- [Documentation](https://developer.dexcom.com/)
- [GettingStarted](https://developer.dexcom.com/get-started)
- [Authentication](https://developer.dexcom.com/docs/dexcom/authentication/)
- [Sandbox](https://sandbox-api.dexcom.com)
- [TermsOfService](https://www.dexcom.com/terms-of-use)
- [PrivacyPolicy](https://www.dexcom.com/privacy-policy)
- [Support](https://www.dexcom.com/contact)
- [GitHubOrganization](https://github.com/dexcom)
- [SpectralRules](rules/dexcom-rules.yml)
- [Vocabulary](vocabulary/dexcom-vocabulary.yml)
- [JSON-LD](json-ld/dexcom-context.jsonld)
- [NaftikoCapability — CGM Data Access Workflow](capabilities/cgm-data-access.yaml)
- [NaftikoCapability — Dexcom Developer API (Shared)](capabilities/shared/dexcom-api.yaml)

## Features

| Name | Description |
|------|-------------|
| Continuous Glucose Monitoring Data | Retrieve estimated glucose values (EGVs) at 5-minute intervals across G6, G7, Dexcom ONE, and ONE+ systems. |
| User-Entered Events | Access user-logged carbs, insulin, exercise, and health events alongside CGM data. |
| Calibrations | Read fingerstick BG meter calibration entries for transmitters that require them. |
| Alerts | Read CGM display device alerts (high, low, urgent low, rise, fall, no readings, out-of-range). |
| Device Inventory | List the user's transmitters and display devices, including alert schedules and settings. |
| Data Range | Discover earliest and latest record times for efficient incremental sync. |
| Multi-Region Hosts | Production hosts in the US (api.dexcom.com), EU (api.dexcom.eu), and Japan (api.dexcom.jp). |
| Sandbox Environment | Test against simulated CGM data without real Dexcom credentials at sandbox-api.dexcom.com. |
| OAuth 2.0 Authorization Code | Standards-based user consent and token issuance with offline_access (refresh) support. |

## Use Cases

| Name | Description |
|------|-------------|
| Diabetes Self-Management Apps | Consumer apps that visualize glucose trends alongside insulin, food, and activity logs. |
| Clinical Decision Support | Provider tools that aggregate CGM data into time-in-range and ambulatory glucose profile (AGP) views. |
| Clinical Research | Studies analyzing glycemic patterns, intervention response, or device performance across cohorts. |
| Coaching and Behavior Change | Health-coaching platforms correlating CGM signals with meals, workouts, and sleep. |
| AI-Assisted Glucose Management | LLM and agentic systems that reason over CGM history via MCP tools to recommend actions. |
| Connected Health Platforms | Aggregators (Apple Health, Validic, Tidepool, etc.) that ingest Dexcom data alongside other wearables. |

## Integrations

| Name | Description |
|------|-------------|
| Apple Health | Dexcom apps publish CGM data into Apple Health on iOS. |
| Tidepool | Open diabetes data platform that ingests Dexcom data for clinical and research use. |
| Validic | Healthcare data aggregator with documented Dexcom API integration. |
| Nightscout | Community-maintained DIY CGM dashboard supporting Dexcom data flows. |
| Garmin / Fitbit / Wearables | Companion apps and watch faces display Dexcom values streamed via Dexcom's apps. |

## Solutions

| Name | Description |
|------|-------------|
| Dexcom G7 | Latest-generation 10-day all-in-one disposable CGM with the smallest, thinnest sensor and direct-to-watch streaming. |
| Dexcom G6 | 10-day CGM with separate transmitter and sensor; widely supported across partner integrations. |
| Dexcom ONE / ONE+ | Simplified CGM tier targeted at intermittent CGM users in select markets. |
| Dexcom Stelo | Over-the-counter glucose biosensor for non-insulin users (US). |
| Clarity | Cloud reporting for patients and clinicians with AGP, time-in-range, and pattern recognition. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Dexcom Developer API](openapi/dexcom-dexcom-api.yml) — OpenAPI 3.0.3 spec covering OAuth 2.0 token endpoints and the six v3 CGM data endpoints (EGVs, events, calibrations, alerts, devices, dataRange) with named Microcks examples on every operation.

### JSON Schema

27 standalone JSON Schema files extracted from the OpenAPI components. Highlights:

- [EGV Record](json-schema/dexcom-api-egv-record-schema.json)
- [Event Record](json-schema/dexcom-api-event-record-schema.json)
- [Calibration Record](json-schema/dexcom-api-calibration-record-schema.json)
- [Alert Record](json-schema/dexcom-api-alert-record-schema.json)
- [Device Record](json-schema/dexcom-api-device-record-schema.json)
- [Data Range Response](json-schema/dexcom-api-data-range-response-schema.json)
- [Token Request](json-schema/dexcom-api-token-request-schema.json) / [Token Response](json-schema/dexcom-api-token-response-schema.json)

### JSON Structure

27 JSON Structure (json-structure.org) files mirroring every JSON Schema with strict typing (datetime, int32, int64, double).

### JSON-LD

- [Dexcom Context](json-ld/dexcom-context.jsonld) — JSON-LD 1.1 context with 17 type declarations and 49 property terms aligned to schema.org, dcterms, and a dex: namespace.

### Examples

27 example payload files generated from the JSON Schemas, one per schema.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Dexcom Developer API](capabilities/shared/dexcom-api.yaml) — 8 operations covering OAuth 2.0 token exchange/refresh and the six v3 CGM resources, with REST (port 8101) and MCP (port 9101) adapters.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|---------------|-------|---------|
| [Dexcom CGM Data Access](capabilities/cgm-data-access.yaml) | Dexcom Developer API | 6 | Digital health developers, diabetes researchers, CGM-aware AI agents |

## Vocabulary

- [Dexcom Vocabulary](vocabulary/dexcom-vocabulary.yml) — Unified taxonomy mapping 6 resources, 3 actions, 1 workflow, and 3 personas across the operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Dexcom Spectral Rules](rules/dexcom-rules.yml) — 31 rules across info, paths, operations, parameters, responses, schemas, security, tags, and Microcks/example categories enforcing Dexcom API conventions.

## Maintainers

**FN:** API Evangelist

**URL:** https://apievangelist.com
