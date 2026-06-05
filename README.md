# Arcadia (arcadia-power)

Arcadia is a clean-energy access and energy-intelligence company that operates Arc, a utility data platform giving developers programmatic access to utility bills, statements, meters, interval (15-minute) usage data, tariff rates, and provider metadata across thousands of US and international utilities. Arc combines the Plug API for utility data, Arcadia Connect for hosted credential collection and MFA, Signal for tariff and rate calculations, and webhooks for asynchronous events. Arcadia powers solar and storage modeling, EV charging, energy management, property management, and carbon accounting for customers including Ford, EVgo, Enphase, Oracle, UPS, Conagra, Penske, and ~25% of the Fortune 500. In April 2026 Arcadia acquired ENGIE Impact, adding utility bill management, energy procurement advisory, and sustainability reporting capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/arcadia-power/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/arcadia-power/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Energy
- Clean Energy
- Utility Data
- Climate
- Sustainability
- Carbon Accounting
- Solar
- Storage
- EV Charging
- Decarbonization
- Energy Intelligence

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Arcadia Plug API

The Arcadia Plug API is the flagship developer surface of the Arc data platform — programmatic access to utility bill, statement, meter, interval, site, and provider data sourced from thousands of US and international utilities. Plug powers solar/storage modeling, EV charging, energy management, property management, and carbon accounting use cases. OAuth 2.0 client-credentials authentication; versioned via the Arcadia-Version header (current default 2024-02-21).

- **Human URL:** [https://docs.arcadia.com/reference/introduction](https://docs.arcadia.com/reference/introduction)
- **Base URL:** `https://api.arcadia.com/plug`

#### Tags

- Energy
- Utility Data
- Clean Energy
- Bills
- Meters
- Intervals

#### Properties

- [Documentation](https://docs.arcadia.com/reference/introduction)
- [Getting Started](https://docs.arcadia.com/docs/api-quick-start-guide)
- [OpenAPI](openapi/arcadia-plug-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/arcadia-plug-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcadia-plug-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/arcadia-statement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcadia-meter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcadia-interval-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/arcadia-power-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Arcadia Connect API

Arcadia Connect is a hosted credential-collection web experience that handles utility account onboarding — credential capture, MFA flows, one-time passcodes, and credential refresh — without requiring partners to handle utility passwords directly. The accompanying Connect API generates encoded session URLs and exposes credential lifecycle endpoints (create, update, refresh, disable).

- **Human URL:** [https://docs.arcadia.com/docs/connect-guide](https://docs.arcadia.com/docs/connect-guide)

#### Tags

- Energy
- Utility Data
- Authentication
- Credentials
- Onboarding

#### Properties

- [Documentation](https://docs.arcadia.com/docs/connect-guide)
- [Postman Collection](collections/arcadia-plug-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcadia-plug-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arcadia Signal API

Arcadia Signal provides utility tariff and energy rate data and calculations for use in cost-benefit analyses, bill audits, project forecasting, and financial modeling. Signal powers the Tariff & Energy Rate Calculator product and supports customers building solar, storage, EV charging, and demand-response economics.

- **Human URL:** [https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start](https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start)

#### Tags

- Energy
- Utility Data
- Tariff
- Rates
- Real-Time

#### Properties

- [Documentation](https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start)
- [Postman Collection](collections/arcadia-plug-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcadia-plug-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arcadia Webhooks API

List, retrieve, and resend webhooks for asynchronous Plug platform events including statement availability, meter activation, interval data readiness, and credential lifecycle changes. Arcadia recommends webhooks over polling for production integrations.

- **Human URL:** [https://docs.arcadia.com/reference/list-webhooks](https://docs.arcadia.com/reference/list-webhooks)

#### Tags

- Energy
- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.arcadia.com/reference/list-webhooks)
- [Postman Collection](collections/arcadia-plug-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcadia-plug-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arcadia Utility Cloud API (Legacy)

The legacy Utility Cloud REST API — predecessor to the Plug API — still documented for existing integrations. New integrations should use the Plug API; the Utility Cloud version remains available for backward compatibility.

- **Human URL:** [https://docs.arcadia.com/v1.0-Utility-Cloud/docs/api-quick-start-guide](https://docs.arcadia.com/v1.0-Utility-Cloud/docs/api-quick-start-guide)

#### Tags

- Energy
- Utility Data
- Legacy

#### Properties

- [Documentation](https://docs.arcadia.com/v1.0-Utility-Cloud/docs/api-quick-start-guide)
- [Documentation](https://docs.arcadia.com/v1.0-Utility-Cloud/reference/introduction)
- [Postman Collection](collections/arcadia-plug-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcadia-plug-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.arcadia.com)
- [Documentation](https://docs.arcadia.com/)
- [Documentation](https://www.arcadia.com/arc)
- [Getting Started](https://docs.arcadia.com/docs/api-quick-start-guide)
- [Documentation](https://docs.arcadia.com/docs/arcadia-data-model)
- [Sign Up](https://dashboard.arcadia.com)
- [GitHub Organization](https://github.com/arcadiapower)
- [Blog](https://www.arcadia.com/blog)
- [Changelog](https://docs.arcadia.com/changelog)
- [Privacy Policy](https://www.arcadia.com/privacy-policy)
- [Terms of Service](https://www.arcadia.com/terms-of-service)
- [LinkedIn](https://www.linkedin.com/company/arcadiapower)
- [Press](https://www.arcadia.com/press)
- [Documentation](https://docs.arcadia.com/reference/introduction)
- [Documentation](https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start)
- [Documentation](https://docs.arcadia.com/docs/connect-guide)
- [Documentation](https://docs.arcadia.com/reference/introduction)
- [Documentation](https://docs.arcadia.com/llms.txt)
- [Plans](plans/arcadia-power-plans-pricing.yml)
- [Rate Limits](rate-limits/arcadia-power-rate-limits.yml)
- [Fin Ops](finops/arcadia-power-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
