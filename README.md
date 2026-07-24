# ECOMMPAY (ecommpay)

ECOMMPAY is a London-headquartered international payment service provider and direct card acquirer founded in 2012, authorised by the UK Financial Conduct Authority (FRN 607597), PCI DSS Level 1 certified, and holding Visa and Mastercard Principal Membership. It operates its own payment gateway, acquiring, and certified processing platform, serving e-commerce merchants with card processing, alternative and local payment methods, open banking, payouts, multi-currency settlement, and fraud prevention. Its home market is the United Kingdom.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ecommpay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ecommpay/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- Alternative Payment Methods
- Open Banking
- Payouts
- Cross-Border
- Fraud

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

ECOMMPAY's developer surface is API-native but signature-authenticated (HMAC over request parameters with a per-project secret key) rather than OAuth token-based. The two API-reference hosts are Stoplight Elements single-page apps that render their OpenAPI content at runtime through a Stoplight platform node API, so no downloadable OpenAPI/Swagger file could be harvested (0 specs saved).

### ECOMMPAY Payment Page API

Hosted, highly customisable payment form for accepting payments across cards, alternative payment methods, and wallets. Opened with an HMAC-signed request; payment results returned via asynchronous callbacks. JavaScript and mobile SDKs available.

- **Human URL:** [https://developers.ecommpay.com/en/en_PP_about.html](https://developers.ecommpay.com/en/en_PP_about.html)
- **Base URL:** `https://paymentpage.ecommpay.com`

#### Properties

- [Documentation](https://developers.ecommpay.com/en/en_PP_about.html)
- [API Reference](https://developers.ecommpay.com/en/en_PP_API.html)

### ECOMMPAY Gate API

Server-to-server payment API for direct integration with full control of the payment flow — one-time purchases, refunds, payouts, and credential-on-file transactions. Authenticated with a project ID and an HMAC signature; results via asynchronous callbacks.

- **Human URL:** [https://developers.ecommpay.com/en/en_Gate_Integration_About.html](https://developers.ecommpay.com/en/en_Gate_Integration_About.html)
- **Base URL:** `https://api.ecommpay.com/v2`

#### Properties

- [Documentation](https://developers.ecommpay.com/en/en_Gate_Integration_About.html)
- [API Reference](https://api-developers.ecommpay.com/api.html)

### ECOMMPAY Data API

Reporting and data-retrieval API for programmatic access to payment, operation, and reconciliation data over TLS 1.2+, signature-authenticated.

- **Human URL:** [https://developers.ecommpay.com/en/en_dbl_api_overview.html](https://developers.ecommpay.com/en/en_dbl_api_overview.html)
- **Base URL:** `https://data.ecommpay.com/v1`

#### Properties

- [Documentation](https://developers.ecommpay.com/en/en_dbl_api_overview.html)
- [API Reference](https://api-data.ecommpay.com/api.html)

### ECOMMPAY Dashboard

Merchant management interface for controlling, analysing, and managing payments, projects, and reporting.

- **Human URL:** [https://developers.ecommpay.com/en/en_dbl_about.html](https://developers.ecommpay.com/en/en_dbl_about.html)

#### Properties

- [Documentation](https://developers.ecommpay.com/en/en_dbl_about.html)

## Common Properties

- [Website](https://ecommpay.com/)
- [Developer Portal](https://developers.ecommpay.com/)
- [Documentation](https://developers.ecommpay.com/landing-en/)
- [API Reference](https://api-developers.ecommpay.com/api.html)
- [Getting Started](https://developers.ecommpay.com/en/en_getting_started.html)
- [GitHub Organization](https://github.com/ITECOMMPAY)
- [Status Page](https://status.ecommpay.com/)
- [Pricing](https://ecommpay.com/pricing/)
- [Blog](https://ecommpay.com/blog/)
- [Support](https://ecommpay.com/support/)
- [Sign Up](https://dashboard.ecommpay.com/)
- [Terms of Service](https://ecommpay.com/terms-of-use/)
- [Privacy Policy](https://ecommpay.com/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/ecommpay)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
