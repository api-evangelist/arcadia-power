# Arcadia (arcadia-power)

Arcadia is a clean-energy access and energy-intelligence company that operates **Arc**, a utility data platform giving developers programmatic access to utility bills, statements, meters, 15-minute interval usage data, tariff rates, and provider metadata across thousands of US and international utilities. Arc combines the **Plug API** for utility data, **Arcadia Connect** for hosted credential collection and MFA, **Signal** for tariff and rate calculations, and webhooks for asynchronous events. Arcadia powers solar and storage modeling, EV charging, energy management, property management, and carbon accounting for customers including Ford, EVgo, Enphase, Oracle, UPS, Conagra, Penske, and ~25% of the Fortune 500. In April 2026 Arcadia acquired ENGIE Impact, adding utility bill management, energy procurement advisory, and sustainability reporting capabilities.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/arcadia-power/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Energy, Clean Energy, Utility Data, Climate, Sustainability, Carbon Accounting, Solar, Storage, EV Charging, Decarbonization, Energy Intelligence

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Arcadia Plug API
Flagship developer surface of Arc — programmatic access to utility accounts, statements, meters, 15-minute interval data, sites, providers, files, and webhooks. OAuth 2.0 client-credentials authentication; versioned via the `Arcadia-Version` header (default `2024-02-21`).

**Human URL:** [https://docs.arcadia.com/reference/introduction](https://docs.arcadia.com/reference/introduction)

**Base URL:** `https://api.arcadia.com/plug`

- [Documentation](https://docs.arcadia.com/reference/introduction)
- [Getting Started](https://docs.arcadia.com/docs/api-quick-start-guide)
- [OpenAPI](openapi/arcadia-plug-api-openapi.yml)
- [JSON Schema — Statement](json-schema/arcadia-statement-schema.json)
- [JSON Schema — Meter](json-schema/arcadia-meter-schema.json)
- [JSON Schema — Interval](json-schema/arcadia-interval-schema.json)
- [JSON-LD](json-ld/arcadia-power-context.jsonld)
- [Naftiko Capability — Accounts](capabilities/plug-accounts.yaml)
- [Naftiko Capability — Statements](capabilities/plug-statements.yaml)
- [Naftiko Capability — Meters](capabilities/plug-meters.yaml)
- [Naftiko Capability — Intervals](capabilities/plug-intervals.yaml)

### Arcadia Connect API
Hosted credential-collection web experience that handles utility-account onboarding — credential capture, MFA, one-time passcodes, and credential refresh — without requiring partners to handle utility passwords directly.

**Human URL:** [https://docs.arcadia.com/docs/connect-guide](https://docs.arcadia.com/docs/connect-guide)

- [Documentation](https://docs.arcadia.com/docs/connect-guide)
- [Naftiko Capability — Credentials](capabilities/connect-credentials.yaml)

### Arcadia Signal API
Tariff and energy-rate data and calculations for cost-benefit analyses, bill audits, project forecasting, and financial modeling. Powers the Tariff & Energy Rate Calculator product.

**Human URL:** [https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start](https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start)

- [Documentation](https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start)
- [Naftiko Capability — Tariffs](capabilities/signal-tariffs.yaml)

### Arcadia Webhooks API
List, retrieve, and resend webhooks for asynchronous Plug platform events including statement availability, meter activation, interval data readiness, and credential lifecycle changes. Arcadia recommends webhooks over polling for production integrations.

**Human URL:** [https://docs.arcadia.com/reference/list-webhooks](https://docs.arcadia.com/reference/list-webhooks)

- [Naftiko Capability — Webhook Events](capabilities/webhooks-events.yaml)

### Arcadia Utility Cloud API (Legacy)
Predecessor REST API maintained for backward compatibility. New integrations should use the Plug API.

**Human URL:** [https://docs.arcadia.com/v1.0-Utility-Cloud/docs/api-quick-start-guide](https://docs.arcadia.com/v1.0-Utility-Cloud/docs/api-quick-start-guide)

## Common Properties

- [Portal — arcadia.com](https://www.arcadia.com)
- [Documentation — docs.arcadia.com](https://docs.arcadia.com/)
- [Documentation — Arc Platform](https://www.arcadia.com/arc)
- [GettingStarted](https://docs.arcadia.com/docs/api-quick-start-guide)
- [Documentation — Arcadia Data Model](https://docs.arcadia.com/docs/arcadia-data-model)
- [Documentation — Plug API Reference](https://docs.arcadia.com/reference/introduction)
- [Documentation — Signal Quick Start](https://docs.arcadia.com/v2022-12-21-Signal/docs/quick-start)
- [Documentation — Arcadia Connect Guide](https://docs.arcadia.com/docs/connect-guide)
- [Documentation — LLMs.txt for AI agents](https://docs.arcadia.com/llms.txt)
- [SignUp — Dashboard](https://dashboard.arcadia.com)
- [GitHubOrganization](https://github.com/arcadiapower)
- [Blog](https://www.arcadia.com/blog)
- [Press](https://www.arcadia.com/press)
- [LinkedIn](https://www.linkedin.com/company/arcadiapower)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Arcadia Plug API](openapi/arcadia-plug-api-openapi.yml)

### JSON Schema

- [Arcadia Statement Schema](json-schema/arcadia-statement-schema.json)
- [Arcadia Meter Schema](json-schema/arcadia-meter-schema.json)
- [Arcadia Interval Schema](json-schema/arcadia-interval-schema.json)

### JSON-LD

- [Arcadia Power Context](json-ld/arcadia-power-context.jsonld)

### Capabilities (Naftiko)

- [Plug — Accounts](capabilities/plug-accounts.yaml)
- [Plug — Statements](capabilities/plug-statements.yaml)
- [Plug — Meters](capabilities/plug-meters.yaml)
- [Plug — Intervals](capabilities/plug-intervals.yaml)
- [Connect — Credentials](capabilities/connect-credentials.yaml)
- [Signal — Tariffs](capabilities/signal-tariffs.yaml)
- [Webhooks — Events](capabilities/webhooks-events.yaml)

### Commercial artifacts

- [Plans / Pricing](plans/arcadia-power-plans-pricing.yml)
- [Rate Limits](rate-limits/arcadia-power-rate-limits.yml)
- [FinOps Definition](finops/arcadia-power-finops.yml)
- [API Evangelist Review](review.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
