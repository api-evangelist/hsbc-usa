# HSBC USA (hsbc-usa)

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
