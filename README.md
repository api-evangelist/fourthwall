# Fourthwall (fourthwall)

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

Fourthwall is a creator commerce platform for building a branded online shop and storefront, selling physical merch, digital products, memberships, and accepting donations and gifts. It exposes a public Storefront API (storefront token) for headless product/collection/cart experiences and a Platform / Open API (Basic Auth API key or OAuth) for managing orders, products, promotions, gifting, memberships, and webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fourthwall/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fourthwall/refs/heads/main/apis.yml)

## Tags

- Creator Commerce
- Ecommerce
- Merch
- Storefront
- Memberships
- Donations
- Print on Demand

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Fourthwall Storefront Products API

Public, storefront-token-authenticated read access to a shop's product (offer) catalog for building headless and custom storefronts, including fetching a product by slug.

- **Human URL:** [https://docs.fourthwall.com/storefront/overview](https://docs.fourthwall.com/storefront/overview)
- **Base URL:** `https://storefront-api.fourthwall.com/v1`

#### Tags

- Storefront
- Products
- Offers
- Catalog

#### Properties

- [Documentation](https://docs.fourthwall.com/storefront/overview)
- [API Reference](https://docs.fourthwall.com/storefront-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Storefront Collections API

Public storefront access to a shop's collections - list all collections, get a collection by slug, and list the products within a collection - plus shop information for headless commerce front ends.

- **Human URL:** [https://docs.fourthwall.com/storefront/overview](https://docs.fourthwall.com/storefront/overview)
- **Base URL:** `https://storefront-api.fourthwall.com/v1`

#### Tags

- Storefront
- Collections
- Catalog

#### Properties

- [Documentation](https://docs.fourthwall.com/storefront/overview)
- [API Reference](https://docs.fourthwall.com/storefront-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Storefront Cart & Checkout API

Create and manage a storefront cart (create, get, add, change quantity, remove items) then redirect the shopper to Fourthwall's hosted, PCI-compliant checkout to complete the purchase.

- **Human URL:** [https://docs.fourthwall.com/storefront/overview](https://docs.fourthwall.com/storefront/overview)
- **Base URL:** `https://storefront-api.fourthwall.com/v1`

#### Tags

- Storefront
- Cart
- Checkout

#### Properties

- [Documentation](https://docs.fourthwall.com/storefront/overview)
- [API Reference](https://docs.fourthwall.com/storefront-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Orders API

Platform (Open) API for retrieving a shop's orders - list all orders, get an order by id or friendly id, mark digital downloads as downloaded, and create fulfillments and external orders. Authenticated with a shop API key (Basic Auth) or OAuth.

- **Human URL:** [https://docs.fourthwall.com/open-api/](https://docs.fourthwall.com/open-api/)
- **Base URL:** `https://api.fourthwall.com/open-api/v1.0`

#### Tags

- Orders
- Platform
- Fulfillment

#### Properties

- [Documentation](https://docs.fourthwall.com/open-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Products API

Platform API for managing products (offers), inventory, digital products, and collections - create, list, get, archive products, update availability and lifecycle state, and set the products in a collection.

- **Human URL:** [https://docs.fourthwall.com/open-api/](https://docs.fourthwall.com/open-api/)
- **Base URL:** `https://api.fourthwall.com/open-api/v1.0`

#### Tags

- Products
- Offers
- Collections
- Platform

#### Properties

- [Documentation](https://docs.fourthwall.com/open-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Gifting & Giveaways API

Platform API for community gifting and giveaways - configure gifting, create gifting checkouts, run and finish gift draws, create and finish giveaways and giveaway links, and look up Twitch gift purchases.

- **Human URL:** [https://docs.fourthwall.com/open-api/](https://docs.fourthwall.com/open-api/)
- **Base URL:** `https://api.fourthwall.com/open-api/v1.0`

#### Tags

- Gifting
- Giveaways
- Twitch
- Platform

#### Properties

- [Documentation](https://docs.fourthwall.com/open-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Promotions API

Platform API for shop promotions and discounts - create a promotion, list all promotions, get a promotion by id, and update an existing promotion.

- **Human URL:** [https://docs.fourthwall.com/open-api/](https://docs.fourthwall.com/open-api/)
- **Base URL:** `https://api.fourthwall.com/open-api/v1.0`

#### Tags

- Promotions
- Discounts
- Platform

#### Properties

- [Documentation](https://docs.fourthwall.com/open-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Memberships API

Platform API (BETA) for recurring memberships - list membership tiers, list members, and get an individual member. Subscription lifecycle changes are surfaced through webhooks (SUBSCRIPTION_PURCHASED / EXPIRED / CHANGED).

- **Human URL:** [https://docs.fourthwall.com/open-api/](https://docs.fourthwall.com/open-api/)
- **Base URL:** `https://api.fourthwall.com/open-api/v1.0`

#### Tags

- Memberships
- Subscriptions
- Members
- Platform

#### Properties

- [Documentation](https://docs.fourthwall.com/open-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fourthwall Webhooks API

Platform API for managing webhook subscriptions - create, list, get, update, and delete webhook configurations, and read delivered webhook events. Payloads are HMAC-SHA256 signed and cover order, product, donation, subscription, promotion, membership, and abandoned-cart events.

- **Human URL:** [https://docs.fourthwall.com/open-api/](https://docs.fourthwall.com/open-api/)
- **Base URL:** `https://api.fourthwall.com/open-api/v1.0`

#### Tags

- Webhooks
- Events
- Platform

#### Properties

- [Documentation](https://docs.fourthwall.com/open-api/)
- [OpenAPI](openapi/fourthwall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fourthwall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fourthwall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/FourthwallHQ)
- [LinkedIn](https://www.linkedin.com/company/fourthwall)
- [Website](https://fourthwall.com/)
- [Documentation](https://docs.fourthwall.com)
- [Plans](plans/fourthwall-plans-pricing.yml)
- [Rate Limits](rate-limits/fourthwall-rate-limits.yml)
- [Fin Ops](finops/fourthwall-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
