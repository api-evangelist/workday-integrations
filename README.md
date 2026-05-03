# Workday Integrations (workday-integrations)
Workday provides cloud-based enterprise software for finance, HR, and planning. This APIs.json describes the integration capabilities and APIs available for connecting Workday with other systems.

**URL:** [https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-integrations/refs/heads/main/apis.yml)

## Tags

Cloud, Enterprise Software, ERP, Finance, HCM, HR, Integration

## Timestamps

- **Created:** 2025-03-15
- **Modified:** 2026-05-03

## APIs

### Workday REST API
Modern REST API for accessing Workday business objects including employees, organizations, positions, and more.

**Human URL:** [https://community.workday.com/sites/default/files/file-hosting/restapi/index.html](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)

#### Tags

Enterprise, Finance, HR, REST

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/restapi/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/restapi/openapi.json)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [Rate Limits](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-rate-limiting.html)
- [OpenAPI](openapi/workday-integrations-rest-api-openapi.yml)

### Workday SOAP Web Services
Comprehensive SOAP-based web services for deep integration with Workday including HCM, Financial Management, and custom integrations.

**Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)

#### Tags

Finance, HCM, Integration, SOAP, Web Services

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [WSDL](https://community.workday.com/sites/default/files/file-hosting/productionapi/versions.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/integration/web-services/web-services-authentication.html)
- [Integration Guide](https://doc.workday.com/admin-guide/en-us/integration/integration-overview.html)

### Workday RaaS (Report-as-a-Service)
Access custom and standard Workday reports as web services, enabling report data to be consumed by external systems.

**Human URL:** [https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html](https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html)

#### Tags

Analytics, Custom Reports, Data Export, Reports

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/integration/workday-reports/report-as-a-service-raas.html)
- [Tutorial](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/CIe8xMH~H~b1Cq7IqRfGHQ)
- [Authentication](https://doc.workday.com/admin-guide/en-us/integration/web-services/web-services-authentication.html)
- [OpenAPI](openapi/workday-integrations-raas-openapi.yml)

### Workday Prism Analytics API
API for loading external data into Workday Prism Analytics for advanced reporting and analytics capabilities.

**Human URL:** [https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)

#### Tags

Analytics, Data Loading, External Data, Prism

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- [API Reference](https://community.workday.com/sites/default/files/file-hosting/prism-analytics-api/index.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [OpenAPI](openapi/workday-integrations-prism-analytics-openapi.yml)

## Common Properties

- [Developer Portal](https://community.workday.com/developer)
- [Authentication Guide](https://doc.workday.com/admin-guide/en-us/integration/integration-security/authentication-overview.html)
- [Integration Cloud Platform](https://www.workday.com/en-us/products/platform-product-extensions/workday-integration-cloud.html)
- [Studio](https://doc.workday.com/admin-guide/en-us/integration/workday-studio/workday-studio-overview.html)
- [Community](https://community.workday.com/)
- [Support](https://www.workday.com/en-us/customer-experience/support.html)
- [Status Page](https://status.workday.com/)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [JSON-LD](json-ld/workday-integrations-context.jsonld)
- [JSONSchema](json-schema/workday-integrations-worker-schema.json)
- [JSONSchema](json-schema/workday-integrations-organization-schema.json)
- [JSONSchema](json-schema/workday-integrations-position-schema.json)
- [JSONSchema](json-schema/workday-integrations-compensation-schema.json)
- [JSONSchema](json-schema/workday-integrations-dataset-schema.json)
- [Spectral Rules](rules/workday-integrations-rules.yml)
- [Naftiko Capabilities](capabilities/workforce-data-integration.yaml)
- [Vocabulary](vocabulary/workday-integrations-vocabulary.yml)

## Capabilities

### Workflow Capabilities

- [Workforce Data Integration](capabilities/workforce-data-integration.yaml) — HCM data access + RaaS reporting + Prism Analytics data loading (13 tools)

### Shared Per-API Capabilities

- [REST API](capabilities/shared/rest-api.yaml)
- [RaaS API](capabilities/shared/raas.yaml)
- [Prism Analytics API](capabilities/shared/prism-analytics.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
