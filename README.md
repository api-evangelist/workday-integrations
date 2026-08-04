# Workday Integrations (workday-integrations)

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

Workday provides cloud-based enterprise software for finance, HR, and planning. This APIs.json file describes the integration capabilities and APIs available for connecting Workday with other systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml)

## Tags

- Cloud
- Enterprise Software
- ERP
- Finance
- HCM
- HR
- Integration

## Timestamps

- **Created:** 2025-03-15
- **Modified:** 2026-05-19

## APIs

### Workday REST API

Modern REST API for accessing Workday business objects including employees, organizations, positions, and more.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/restapi/index.html](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/v1/{tenant}`

#### Tags

- Enterprise
- Finance
- HR
- REST

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/restapi/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [Rate Limits](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-rate-limiting.html)
- [OpenAPI](openapi/workday-integrations-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-integrations-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-integrations-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday SOAP Web Services

Comprehensive SOAP-based web services for deep integration with Workday including Human Capital Management, Financial Management, and custom integrations.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/{tenant}`

#### Tags

- Finance
- HCM
- Integration
- SOAP
- Web Services

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/versions.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/integration/web-services/web-services-authentication.html)
- [Integration  Guide](https://doc.workday.com/admin-guide/en-us/integration/integration-overview.html)
- [Postman Collection](collections/workday-integrations-prism-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-integrations-prism-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-integrations-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-integrations-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-integrations-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-integrations-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday RaaS (Report-as-a-Service)

Access custom and standard Workday reports as web services, enabling report data to be consumed by external systems.

- **Human URL:** [https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html](https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/customreport2/{tenant}`

#### Tags

- Analytics
- Custom Reports
- Data Export
- Reports

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html)
- [Tutorial](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/CIe8xMH~H~b1Cq7IqRfGHQ)
- [Authentication](https://doc.workday.com/admin-guide/en-us/integration/web-services/web-services-authentication.html)
- [OpenAPI](openapi/workday-integrations-raas-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-integrations-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-integrations-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Prism Analytics API

API for loading external data into Workday Prism Analytics for advanced reporting and analytics capabilities.

- **Human URL:** [https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/prismAnalytics/v2/{tenant}`

#### Tags

- Analytics
- Data Loading
- External Data
- Prism

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- [API Reference](https://community.workday.com/sites/default/files/file-hosting/prism-analytics-api/index.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [OpenAPI](openapi/workday-integrations-prism-analytics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workday-integrations-prism-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-integrations-prism-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer  Portal](https://community.workday.com/developer)
- [Authentication  Guide](https://doc.workday.com/admin-guide/en-us/integration/integration-security/authentication-overview.html)
- [Integration  Cloud  Platform](https://www.workday.com/en-us/products/platform-product-extensions/workday-integration-cloud.html)
- [Studio](https://doc.workday.com/admin-guide/en-us/integration/workday-studio/workday-studio-overview.html)
- [Community](https://community.workday.com/)
- [Support](https://www.workday.com/en-us/customer-experience/support.html)
- [Status Page](https://status.workday.com/)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [JSON-LD](json-ld/workday-integrations-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/workday-integrations-worker-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workday-integrations-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workday-integrations-position-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workday-integrations-compensation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workday-integrations-dataset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral  Rules](rules/workday-integrations-rules.yml)
- [Vocabulary](vocabulary/workday-integrations-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
