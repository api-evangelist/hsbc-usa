# HSBC USA (hsbc-usa)

HSBC USA is the United States arm of HSBC Holdings plc, operating principally through HSBC Bank USA, N.A., a nationally chartered bank supervised by the Office of the Comptroller of the Currency (OCC). After exiting mass-market domestic retail banking in 2022 — selling its East Coast branches and national online deposit business to Citizens and its West Coast branches to Cathay Bank — HSBC refocused its US operations on global wholesale, commercial and corporate banking, global banking and markets, and wealth management for internationally connected clients.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hsbc-usa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hsbc-usa/refs/heads/main/apis.yml)

## Open-Finance / API Posture

HSBC USA does not run a US-specific first-party developer program. Public API access is provided through HSBC's **group-wide corporate and institutional Developer Portal** at [developer.hsbc.com](https://developer.hsbc.com) (which redirects to `develop.hsbc.com`), a registration-gated portal whose transaction-banking API products serve wholesale clients globally, including HSBC USA corporate relationships.

- **Developer portal:** confirmed live (HTTP 200) at `https://developer.hsbc.com`.
- **Spec provenance:** No publicly downloadable OpenAPI/Swagger. API reference and specifications sit behind portal registration/login (`/user/register`, `/user/login`), so nothing was harvested into `openapi/`.
- **FDX / CFPB 1033:** No HSBC-published US FDX participation or Section 1033 data-access posture was located; not asserted here.
- **Consumer data access:** Consumer-permissioned data for remaining US accounts is mediated through third-party aggregators (e.g. Plaid/MX/Akoya/Finicity networks) rather than a documented first-party consumer data-sharing API.

## Tags

- Financial Services
- Banking
- United States
- Corporate Banking
- Transaction Banking
- Wealth Management
- Open Finance
- Payments

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Treasury - Payment Initiation

HSBC group corporate transaction-banking API for initiating outbound payments programmatically, documented on HSBC's Developer Portal and available to wholesale clients including HSBC USA corporate relationships. API reference and specification are behind portal registration/login.

- **Human URL:** [https://develop.hsbc.com/api-overview/treasury-payment-initiation](https://develop.hsbc.com/api-overview/treasury-payment-initiation)

#### Tags

- Payments
- Treasury
- Corporate Banking

#### Properties

- [Documentation](https://develop.hsbc.com/api-overview/treasury-payment-initiation)
- [Portal](https://developer.hsbc.com)

### Omni Collect - Single API

HSBC group corporate collections API consolidating multiple collection and receivables channels behind a single interface, documented on HSBC's Developer Portal for wholesale clients. API reference and specification are behind portal registration/login.

- **Human URL:** [https://develop.hsbc.com/api-overview/omni-collect-single-api](https://develop.hsbc.com/api-overview/omni-collect-single-api)

#### Tags

- Collections
- Receivables
- Corporate Banking

#### Properties

- [Documentation](https://develop.hsbc.com/api-overview/omni-collect-single-api)
- [Portal](https://developer.hsbc.com)

## Common Properties

- [Website](https://www.us.hsbc.com/)
- [Developer Portal](https://developer.hsbc.com)
- [Documentation](https://develop.hsbc.com/apis)
- [GitHub Organization](https://github.com/hsbc)
- [LinkedIn](https://www.linkedin.com/company/hsbc)
- [About](https://www.about.us.hsbc.com)
- [Privacy Policy](https://www.us.hsbc.com/privacy-notice/)
- [Support](https://www.us.hsbc.com/customer-service/)
- [Contact](https://develop.hsbc.com/contact-us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
