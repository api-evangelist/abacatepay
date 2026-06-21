# AbacatePay (abacatepay)

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
