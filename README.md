# AbacatePay (abacatepay)

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

AbacatePay is a Brazilian payment gateway built for developers and indie hackers, focused on instant Pix payments. Its REST API lets you create billings and charges, generate and check Pix QR Codes, manage customers and coupons, request withdrawals, and receive webhooks - charging a flat per-transaction Pix fee with funds available immediately.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/abacatepay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/abacatepay/refs/heads/main/apis.yml)

## Tags

- Payments
- Pix
- Brazil
- FinTech
- Developers

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### AbacatePay Billing and Charges API

Create one-time and recurring billings (charges) backed by a shareable checkout URL, supporting Pix and other payment methods, products, coupons, and customer association, plus listing of existing billings.

- **Human URL:** [https://docs.abacatepay.com/pages/v1/introduction](https://docs.abacatepay.com/pages/v1/introduction)
- **Base URL:** `https://api.abacatepay.com/v1`

#### Tags

- Billing
- Charges
- Checkout

#### Properties

- [Documentation](https://docs.abacatepay.com/pages/payment/create)
- [API Reference](https://docs.abacatepay.com/pages/reference/introduction)
- [OpenAPI](openapi/abacatepay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/abacatepay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/abacatepay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AbacatePay Pix QR Code API

Create dynamic Pix QR Codes (BR Code copy-and-paste and base64 image), check payment status, and simulate payments in dev mode for instant Pix collection.

- **Human URL:** [https://docs.abacatepay.com/pages/v1/introduction](https://docs.abacatepay.com/pages/v1/introduction)
- **Base URL:** `https://api.abacatepay.com/v1`

#### Tags

- Pix
- QR Code
- Instant Payments

#### Properties

- [Documentation](https://docs.abacatepay.com/pages/payment/create)
- [API Reference](https://docs.abacatepay.com/pages/reference/introduction)
- [OpenAPI](openapi/abacatepay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/abacatepay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/abacatepay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AbacatePay Customers API

Create and list customers (clients) with name, cellphone, email, and Brazilian tax ID (CPF/CNPJ) for association with billings and charges.

- **Human URL:** [https://docs.abacatepay.com/pages/client/create](https://docs.abacatepay.com/pages/client/create)
- **Base URL:** `https://api.abacatepay.com/v1`

#### Tags

- Customers
- Clients

#### Properties

- [Documentation](https://docs.abacatepay.com/pages/client/create)
- [API Reference](https://docs.abacatepay.com/pages/reference/introduction)
- [OpenAPI](openapi/abacatepay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/abacatepay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/abacatepay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AbacatePay Coupons API

Create and list discount coupons with percentage or fixed-amount discount kinds, redemption limits, and metadata for use in billings and checkout.

- **Human URL:** [https://docs.abacatepay.com/pages/reference/introduction](https://docs.abacatepay.com/pages/reference/introduction)
- **Base URL:** `https://api.abacatepay.com/v1`

#### Tags

- Coupons
- Discounts

#### Properties

- [Documentation](https://docs.abacatepay.com/pages/reference/introduction)
- [API Reference](https://docs.abacatepay.com/pages/reference/introduction)
- [OpenAPI](openapi/abacatepay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/abacatepay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/abacatepay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AbacatePay Withdraw API

Request withdrawals (payouts) of available balance to a Pix key, and retrieve or list withdrawal transactions by external ID.

- **Human URL:** [https://docs.abacatepay.com/pages/reference/introduction](https://docs.abacatepay.com/pages/reference/introduction)
- **Base URL:** `https://api.abacatepay.com/v1`

#### Tags

- Withdraw
- Payout
- Pix

#### Properties

- [Documentation](https://docs.abacatepay.com/pages/reference/introduction)
- [API Reference](https://docs.abacatepay.com/pages/reference/introduction)
- [OpenAPI](openapi/abacatepay-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/abacatepay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/abacatepay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AbacatePay Webhooks

Outbound webhook event notifications (billing.created, billing.paid, billing.refunded, billing.failed, subscription.created, subscription.canceled) delivered with a webhookSecret query string and HMAC-SHA256 signature for verification.

- **Human URL:** [https://docs.abacatepay.com/pages/v1/webhooks](https://docs.abacatepay.com/pages/v1/webhooks)
- **Base URL:** `https://api.abacatepay.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.abacatepay.com/pages/v1/webhooks)

## Common Properties

- [GitHub Organization](https://github.com/AbacatePay)
- [LinkedIn](https://www.linkedin.com/company/abacatepay)
- [Website](https://www.abacatepay.com)
- [Documentation](https://docs.abacatepay.com)
- [Plans](plans/abacatepay-plans-pricing.yml)
- [Rate Limits](rate-limits/abacatepay-rate-limits.yml)
- [Fin Ops](finops/abacatepay-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
