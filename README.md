# Yotpo (yotpo)

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
