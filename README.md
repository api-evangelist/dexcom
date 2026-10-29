# Dexcom

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

Dexcom is a leading medical device company that develops, manufactures, and distributes continuous glucose monitoring (CGM) systems for people with diabetes. The company's wearable sensors stream real-time glucose data to mobile apps, dedicated receivers, and connected health platforms. Dexcom exposes a public developer program that lets approved third parties retrieve CGM data (estimated glucose values, events, calibrations, alerts, devices, and data range) through an OAuth 2.0 secured REST API, with a sandbox for development and a production environment for live patient data.

**Areas:** Continuous Glucose Monitoring · Diabetes · Digital Health · Glucose · Healthcare · Medical Devices · Wearables

## Dexcom on APIs.io

Everything profiled for Dexcom is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/dexcom/](https://apis.io/providers/dexcom/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Dexcom Alerts API](https://apis.io/apis/dexcom/dexcom-alerts-api/) — Alert events generated by the user's CGM display device.
- [Dexcom Authentication API](https://apis.io/apis/dexcom/dexcom-authentication-api/) — OAuth 2.0 authorization and token operations.
- [Dexcom Calibrations API](https://apis.io/apis/dexcom/dexcom-calibrations-api/) — User calibration entries from fingerstick blood glucose meter readings.
- [Dexcom Data Range API](https://apis.io/apis/dexcom/dexcom-data-range-api/) — Earliest and latest record times available for the authorized user.
- [Dexcom Devices API](https://apis.io/apis/dexcom/dexcom-devices-api/) — Information about the user's CGM transmitters and display devices.
- [Dexcom Estimated Glucose Values API](https://apis.io/apis/dexcom/dexcom-estimated-glucose-values-api/) — Time-series CGM glucose readings for the authorized user.
- [Dexcom Events API](https://apis.io/apis/dexcom/dexcom-events-api/) — User-entered events such as carbohydrate intake, insulin doses, exercise, and health events.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Dexcom Agentic Access](https://apis.io/agentic-access/dexcom/dexcom-agentic-access/)

#### JSON Schema (27)

The data models the API reads and writes.

- [AlertName](https://apis.io/schemas/dexcom/dexcom-api-alert-name/)
- [AlertRecord](https://apis.io/schemas/dexcom/dexcom-api-alert-record/)
- [AlertSchedule](https://apis.io/schemas/dexcom/dexcom-api-alert-schedule/)
- [AlertSetting](https://apis.io/schemas/dexcom/dexcom-api-alert-setting/)
- [AlertState](https://apis.io/schemas/dexcom/dexcom-api-alert-state/)
- [AlertsResponse](https://apis.io/schemas/dexcom/dexcom-api-alerts-response/)
- [CalibrationRecord](https://apis.io/schemas/dexcom/dexcom-api-calibration-record/)
- [CalibrationsResponse](https://apis.io/schemas/dexcom/dexcom-api-calibrations-response/)
- [DataRangeMoment](https://apis.io/schemas/dexcom/dexcom-api-data-range-moment/)
- [DataRangeResponse](https://apis.io/schemas/dexcom/dexcom-api-data-range-response/)
- [DataRangeWindow](https://apis.io/schemas/dexcom/dexcom-api-data-range-window/)
- [DateTime](https://apis.io/schemas/dexcom/dexcom-api-date-time/)
- [DeviceRecord](https://apis.io/schemas/dexcom/dexcom-api-device-record/)
- [DevicesResponse](https://apis.io/schemas/dexcom/dexcom-api-devices-response/)
- [EGVRecord](https://apis.io/schemas/dexcom/dexcom-api-egv-record/)
- [EgvStatus](https://apis.io/schemas/dexcom/dexcom-api-egv-status/)
- [EgvsResponse](https://apis.io/schemas/dexcom/dexcom-api-egvs-response/)
- [EventRecord](https://apis.io/schemas/dexcom/dexcom-api-event-record/)
- [EventStatus](https://apis.io/schemas/dexcom/dexcom-api-event-status/)
- [EventType](https://apis.io/schemas/dexcom/dexcom-api-event-type/)
- [EventsResponse](https://apis.io/schemas/dexcom/dexcom-api-events-response/)
- [GlucoseUnit](https://apis.io/schemas/dexcom/dexcom-api-glucose-unit/)
- [RateUnit](https://apis.io/schemas/dexcom/dexcom-api-rate-unit/)
- [TokenRequest](https://apis.io/schemas/dexcom/dexcom-api-token-request/)
- [TokenResponse](https://apis.io/schemas/dexcom/dexcom-api-token-response/)
- …and 2 more published on APIs.io

#### JSON Structure (27)

Data models expressed in JSON Structure.

- [Dexcom Api Alert Name Structure](https://apis.io/json-structure/dexcom/dexcom-api-alert-name-structure/)
- [Dexcom Api Alert Record Structure](https://apis.io/json-structure/dexcom/dexcom-api-alert-record-structure/)
- [Dexcom Api Alert Schedule Structure](https://apis.io/json-structure/dexcom/dexcom-api-alert-schedule-structure/)
- [Dexcom Api Alert Setting Structure](https://apis.io/json-structure/dexcom/dexcom-api-alert-setting-structure/)
- [Dexcom Api Alert State Structure](https://apis.io/json-structure/dexcom/dexcom-api-alert-state-structure/)
- [Dexcom Api Alerts Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-alerts-response-structure/)
- [Dexcom Api Calibration Record Structure](https://apis.io/json-structure/dexcom/dexcom-api-calibration-record-structure/)
- [Dexcom Api Calibrations Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-calibrations-response-structure/)
- [Dexcom Api Data Range Moment Structure](https://apis.io/json-structure/dexcom/dexcom-api-data-range-moment-structure/)
- [Dexcom Api Data Range Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-data-range-response-structure/)
- [Dexcom Api Data Range Window Structure](https://apis.io/json-structure/dexcom/dexcom-api-data-range-window-structure/)
- [Dexcom Api Date Time Structure](https://apis.io/json-structure/dexcom/dexcom-api-date-time-structure/)
- [Dexcom Api Device Record Structure](https://apis.io/json-structure/dexcom/dexcom-api-device-record-structure/)
- [Dexcom Api Devices Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-devices-response-structure/)
- [Dexcom Api Egv Record Structure](https://apis.io/json-structure/dexcom/dexcom-api-egv-record-structure/)
- [Dexcom Api Egv Status Structure](https://apis.io/json-structure/dexcom/dexcom-api-egv-status-structure/)
- [Dexcom Api Egvs Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-egvs-response-structure/)
- [Dexcom Api Event Record Structure](https://apis.io/json-structure/dexcom/dexcom-api-event-record-structure/)
- [Dexcom Api Event Status Structure](https://apis.io/json-structure/dexcom/dexcom-api-event-status-structure/)
- [Dexcom Api Event Type Structure](https://apis.io/json-structure/dexcom/dexcom-api-event-type-structure/)
- [Dexcom Api Events Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-events-response-structure/)
- [Dexcom Api Glucose Unit Structure](https://apis.io/json-structure/dexcom/dexcom-api-glucose-unit-structure/)
- [Dexcom Api Rate Unit Structure](https://apis.io/json-structure/dexcom/dexcom-api-rate-unit-structure/)
- [Dexcom Api Token Request Structure](https://apis.io/json-structure/dexcom/dexcom-api-token-request-structure/)
- [Dexcom Api Token Response Structure](https://apis.io/json-structure/dexcom/dexcom-api-token-response-structure/)
- …and 2 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Dexcom Context](https://apis.io/jsonld/dexcom/dexcom-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Dexcom Vocabulary](https://apis.io/vocabularies/dexcom/dexcom-vocabulary/)

#### Examples (17)

Example requests and responses.

- [Dexcom Api Alert Record Example](https://apis.io/examples/dexcom/dexcom-api-alert-record-example/)
- [Dexcom Api Alert Schedule Example](https://apis.io/examples/dexcom/dexcom-api-alert-schedule-example/)
- [Dexcom Api Alert Setting Example](https://apis.io/examples/dexcom/dexcom-api-alert-setting-example/)
- [Dexcom Api Alerts Response Example](https://apis.io/examples/dexcom/dexcom-api-alerts-response-example/)
- [Dexcom Api Calibration Record Example](https://apis.io/examples/dexcom/dexcom-api-calibration-record-example/)
- [Dexcom Api Calibrations Response Example](https://apis.io/examples/dexcom/dexcom-api-calibrations-response-example/)
- [Dexcom Api Data Range Moment Example](https://apis.io/examples/dexcom/dexcom-api-data-range-moment-example/)
- [Dexcom Api Data Range Response Example](https://apis.io/examples/dexcom/dexcom-api-data-range-response-example/)
- [Dexcom Api Data Range Window Example](https://apis.io/examples/dexcom/dexcom-api-data-range-window-example/)
- [Dexcom Api Device Record Example](https://apis.io/examples/dexcom/dexcom-api-device-record-example/)
- [Dexcom Api Devices Response Example](https://apis.io/examples/dexcom/dexcom-api-devices-response-example/)
- [Dexcom Api Egv Record Example](https://apis.io/examples/dexcom/dexcom-api-egv-record-example/)
- [Dexcom Api Egvs Response Example](https://apis.io/examples/dexcom/dexcom-api-egvs-response-example/)
- [Dexcom Api Event Record Example](https://apis.io/examples/dexcom/dexcom-api-event-record-example/)
- [Dexcom Api Events Response Example](https://apis.io/examples/dexcom/dexcom-api-events-response-example/)
- [Dexcom Api Token Request Example](https://apis.io/examples/dexcom/dexcom-api-token-request-example/)
- [Dexcom Api Token Response Example](https://apis.io/examples/dexcom/dexcom-api-token-response-example/)

#### Collections (15)

Postman and Open Collection request collections.

- [Dexcom Developer Alerts API](https://apis.io/collections/dexcom/open-dexcom-alerts-api/)
- [Dexcom Developer Alerts Authentication API](https://apis.io/collections/dexcom/open-dexcom-authentication-api/)
- [Dexcom Developer Alerts Calibrations API](https://apis.io/collections/dexcom/open-dexcom-calibrations-api/)
- [Dexcom Developer Alerts Data Range API](https://apis.io/collections/dexcom/open-dexcom-data-range-api/)
- [Dexcom Developer Alerts Devices API](https://apis.io/collections/dexcom/open-dexcom-devices-api/)
- [Dexcom Developer API](https://apis.io/collections/dexcom/open-dexcom-dexcom-api/)
- [Dexcom Developer Alerts Estimated Glucose Values API](https://apis.io/collections/dexcom/open-dexcom-estimated-glucose-values-api/)
- [Dexcom Developer Alerts Events API](https://apis.io/collections/dexcom/open-dexcom-events-api/)
- [Dexcom Developer Alerts API](https://apis.io/collections/dexcom/postman-dexcom-alerts-api/)
- [Dexcom Developer Alerts Authentication API](https://apis.io/collections/dexcom/postman-dexcom-authentication-api/)
- [Dexcom Developer Alerts Calibrations API](https://apis.io/collections/dexcom/postman-dexcom-calibrations-api/)
- [Dexcom Developer Alerts Data Range API](https://apis.io/collections/dexcom/postman-dexcom-data-range-api/)
- [Dexcom Developer Alerts Devices API](https://apis.io/collections/dexcom/postman-dexcom-devices-api/)
- [Dexcom Developer Alerts Estimated Glucose Values API](https://apis.io/collections/dexcom/postman-dexcom-estimated-glucose-values-api/)
- [Dexcom Developer Alerts Events API](https://apis.io/collections/dexcom/postman-dexcom-events-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Dexcom — jsonschema rules](https://apis.io/rules/dexcom/dexcom-jsonschema-spectral-rules/)
- [Dexcom API Rules](https://apis.io/rules/dexcom/dexcom-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Dexcom Authentication](https://apis.io/security/dexcom/dexcom-authentication/)
- [Dexcom Domain Security](https://apis.io/security/dexcom/dexcom-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Dexcom Scopes](https://apis.io/scopes/dexcom/dexcom-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Dexcom Plans Pricing](https://apis.io/plans/dexcom/dexcom-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Dexcom Rate Limits](https://apis.io/rate-limits/dexcom/dexcom-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Dexcom Finops](https://apis.io/finops/dexcom/dexcom-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.dexcom.com/)
- [Documentation](https://developer.dexcom.com/)
- [Getting started](https://developer.dexcom.com/get-started)
- [Support](https://www.dexcom.com/contact)
- [Terms of service](https://www.dexcom.com/terms-of-use)
- [Privacy policy](https://www.dexcom.com/privacy-policy)
- [GitHub](https://github.com/dexcom)

## API Evangelist rating

**Kin Score 32.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 30.8 |
| Contract governance | 27.3 |
| Operational transparency | 7.9 |
| Developer ergonomics | 25.0 |
| Access clarity | 26.3 |

**Agent readiness 28.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
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
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 32.8** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/dexcom/](https://apis.io/providers/dexcom/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Dexcom: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/dexcom/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
