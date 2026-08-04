# ECOMMPAY (ecommpay)

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
