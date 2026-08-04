# Yotpo (yotpo)

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

Yotpo is an eCommerce retention marketing platform offering Reviews & Ratings, Loyalty & Referrals, Subscriptions, and visual UGC. Each product exposes a documented REST API - the UGC/Reviews and Core APIs under api.yotpo.com (app key plus OAuth utoken) and the Loyalty & Referrals API under loyalty.yotpo.com (program GUID plus API key) - so merchants can sync orders, products, and customers and drive reviews, points, and redemptions programmatically. Yotpo's SMS & Email (SMSBump) products were discontinued on December 31, 2025.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/yotpo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/yotpo/refs/heads/main/apis.yml)

## Tags

- eCommerce
- Reviews
- Loyalty
- Retention Marketing
- UGC

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Yotpo Reviews & Ratings API

Retrieve, create, and moderate product reviews, ratings, bottom-line scores, and Q&A under api.yotpo.com/v1, authenticated with an app key and an OAuth utoken generated from the store secret.

- **Human URL:** [https://apidocs.yotpo.com/reference/welcome](https://apidocs.yotpo.com/reference/welcome)
- **Base URL:** `https://api.yotpo.com`

#### Tags

- Reviews
- Ratings
- UGC

#### Properties

- [Documentation](https://apidocs.yotpo.com/reference/welcome)
- [API Reference](https://apidocs.yotpo.com/reference)
- [OpenAPI](openapi/yotpo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yotpo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yotpo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yotpo Loyalty & Referrals API

Manage loyalty customers, point balances, orders, redemptions, and referral links under loyalty.yotpo.com/api/v2, authenticated with a program GUID and API key.

- **Human URL:** [https://loyaltyapi.yotpo.com/reference/welcome](https://loyaltyapi.yotpo.com/reference/welcome)
- **Base URL:** `https://loyalty.yotpo.com/api/v2`

#### Tags

- Loyalty
- Referrals
- Points

#### Properties

- [Documentation](https://loyaltyapi.yotpo.com/reference/welcome)
- [API Reference](https://loyaltyapi.yotpo.com/reference/authentication)
- [OpenAPI](openapi/yotpo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yotpo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yotpo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yotpo SMS & Email API

Legacy SMS & Email (SMSBump) marketing API for managing contacts, lists, and campaigns. Yotpo permanently discontinued its SMS and Email products on December 31, 2025; documented here for historical completeness.

- **Human URL:** [https://apidocs.yotpo.com/reference](https://apidocs.yotpo.com/reference)
- **Base URL:** `https://api.yotpo.com`

#### Tags

- SMS
- Email
- Marketing

#### Properties

- [Documentation](https://apidocs.yotpo.com/reference)
- [OpenAPI](openapi/yotpo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yotpo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yotpo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yotpo UGC & Visual API

Surfaces user-generated content - review images, widget review data, and LLM-optimized content HTML - for galleries and on-site display, served from the UGC API under api.yotpo.com.

- **Human URL:** [https://apidocs.yotpo.com/reference/welcome](https://apidocs.yotpo.com/reference/welcome)
- **Base URL:** `https://api.yotpo.com`

#### Tags

- UGC
- Visual
- Galleries

#### Properties

- [Documentation](https://apidocs.yotpo.com/reference/welcome)
- [API Reference](https://apidocs.yotpo.com/reference)
- [OpenAPI](openapi/yotpo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yotpo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yotpo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yotpo Subscriptions API

Creates and retrieves recurring subscriptions and subscribers, plus the underlying orders, products, and customers, through the Core API under api.yotpo.com/core/v3/stores/{store_id}, authenticated with an OAuth utoken.

- **Human URL:** [https://core-api.yotpo.com/reference/create-subscription](https://core-api.yotpo.com/reference/create-subscription)
- **Base URL:** `https://api.yotpo.com/core/v3`

#### Tags

- Subscriptions
- Recurring
- eCommerce

#### Properties

- [Documentation](https://core-api.yotpo.com/reference/subscribers)
- [API Reference](https://core-api.yotpo.com/reference/create-subscription)
- [OpenAPI](openapi/yotpo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yotpo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yotpo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Yotpo Webhooks

Subscribes to and manages event webhooks (orders, reviews, fulfillments) via webhook subscriptions under api.yotpo.com/core/v3/stores/{store_id}/webhooks.

- **Human URL:** [https://core-api.yotpo.com/reference](https://core-api.yotpo.com/reference)
- **Base URL:** `https://api.yotpo.com/core/v3`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://core-api.yotpo.com/reference)
- [API Reference](https://core-api.yotpo.com/reference/create-subscription)
- [OpenAPI](openapi/yotpo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/yotpo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/yotpo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/YotpoLtd)
- [LinkedIn](https://www.linkedin.com/company/yotpo)
- [Website](https://www.yotpo.com)
- [Documentation](https://apidocs.yotpo.com/reference)
- [Plans](plans/yotpo-plans-pricing.yml)
- [Rate Limits](rate-limits/yotpo-rate-limits.yml)
- [Fin Ops](finops/yotpo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
