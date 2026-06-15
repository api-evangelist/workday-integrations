# Workday Integrations (workday-integrations)

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
