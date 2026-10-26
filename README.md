# Superpower (superpower-health)

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
