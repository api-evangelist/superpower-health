# Superpower (superpower-health)

Superpower is a consumer preventive-health and longevity membership that provides an annual comprehensive blood draw across 100+ biomarkers, AI-driven result interpretation, biological age scoring, personalized action plans, and a care team, delivered through web and mobile apps. As of the catalog date Superpower does not publish a public or partner developer API; this catalog documents the product surface honestly rather than fabricating endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/superpower-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/superpower-health/refs/heads/main/apis.yml)

## Tags

- Health
- Longevity
- Lab Testing
- Biomarkers
- Preventive Health
- Consumer Health
- No Public API

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Superpower Biomarker Testing

Annual comprehensive blood testing across 100+ biomarkers in 21 categories (hormones, longevity, immune, inflammation, nutrients, toxins) collected via Quest Diagnostics locations or at-home phlebotomy. This is a consumer product capability; no public API is documented for ordering tests or retrieving results programmatically.

- **Human URL:** [https://superpower.com/](https://superpower.com/)
- **Base URL:** `https://superpower.com`

#### Tags

- Lab Testing
- Biomarkers
- Blood Work

#### Properties

- [Documentation](https://superpower.com/)
- [OpenAPI](openapi/superpower-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/superpower-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/superpower-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Superpower Results & Health Scores

Result interpretation surfaced as 17 health scores plus a biological age calculation derived from measured biomarkers and computed ratios/indices. Exposed only inside the member app; no documented public API.

- **Human URL:** [https://superpower.com/](https://superpower.com/)
- **Base URL:** `https://superpower.com`

#### Tags

- Health Scores
- Biological Age
- Results

#### Properties

- [Documentation](https://superpower.com/)
- [OpenAPI](openapi/superpower-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/superpower-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/superpower-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Superpower AI Health Chat

SuperpowerAI chat assistant that lets members explore their lab data and protocols with clinical context. A consumer feature only; no public chat or completion API is documented.

- **Human URL:** [https://superpower.com/](https://superpower.com/)
- **Base URL:** `https://superpower.com`

#### Tags

- AI
- Health Coach
- Chat

#### Properties

- [Documentation](https://superpower.com/)
- [OpenAPI](openapi/superpower-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/superpower-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/superpower-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Superpower Action Plans

Personalized diet, lifestyle, and supplement action plans generated from a member's biomarkers and goals. In-app only; no documented public API for retrieving or managing plans.

- **Human URL:** [https://superpower.com/](https://superpower.com/)
- **Base URL:** `https://superpower.com`

#### Tags

- Protocols
- Personalization
- Recommendations

#### Properties

- [Documentation](https://superpower.com/)
- [OpenAPI](openapi/superpower-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/superpower-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/superpower-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Superpower Wearable & Records Sync

Inbound sync of wearable and health-app data (Oura, Whoop, Apple Health) plus uploaded past lab results and medical records. Superpower is reported to use the third-party Vital aggregator to ingest this data; it is a consumer of Vital's API and does not publish its own developer API for these integrations.

- **Human URL:** [https://superpower.com/](https://superpower.com/)
- **Base URL:** `https://superpower.com`

#### Tags

- Wearables
- Integrations
- Health Data

#### Properties

- [Documentation](https://superpower.com/)
- [OpenAPI](openapi/superpower-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/superpower-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/superpower-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/superpower-health)
- [Website](https://superpower.com/)
- [Documentation](https://superpower.com/faqs)
- [Plans](plans/superpower-health-plans-pricing.yml)
- [Rate Limits](rate-limits/superpower-health-rate-limits.yml)
- [Fin Ops](finops/superpower-health-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
