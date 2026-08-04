# Moneyhub (moneyhub)

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

Moneyhub is a UK open banking and open finance platform, headquartered in London with offices in Bristol and Ljubljana, that lets banks, pension providers, wealth managers, insurers and fintechs embed account aggregation, transaction data enrichment, financial insight and account-to-account payment initiation into their own products. It is regulated by the FCA as an AISP, PISP and CISP.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/moneyhub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/moneyhub/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Open Banking
- Open Finance
- Account-to-Account
- Payment Initiation
- Data Aggregation
- AISP
- PISP
- Fintech

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Moneyhub Data & Intelligence API

The Moneyhub Data API (v2.0) is a RESTful, JSON, bearer-token API for Open Banking account aggregation and financial intelligence: connect accounts, read balances, holdings, standing orders, statements and enriched transactions, and run categorisation, affordability, spending analysis, savings goals and standard financial statements. Published as a Swagger 2.0 definition served from the live API host at `https://api.moneyhub.co.uk/swagger.json`.

- **Human URL:** [https://docs.moneyhubenterprise.com/reference](https://docs.moneyhubenterprise.com/reference)
- **Base URL:** `https://api.moneyhub.co.uk/v2.0`

#### Properties

- [Documentation](https://docs.moneyhubenterprise.com/docs/introduction)
- [API Reference](https://moneyhub.github.io/api-docs/)
- [Getting Started](https://docs.moneyhubenterprise.com/docs/getting-started)
- [OpenAPI](openapi/moneyhub-data-api-swagger.json) — Swagger 2.0, harvested verbatim

### Moneyhub Open Banking Payments API

Moneyhub's Open Banking Payments API initiates account-to-account payments (Payment Initiation Service) over the UK Faster Payments rails as a cheaper, near-instant alternative to cards, direct debits and standing orders. Payments, standing orders, recurring and reverse payments are authorised through Moneyhub's OpenID Connect / OAuth2 identity layer using dedicated payment scopes. The flow is documented but no standalone downloadable OpenAPI is published for the payment-initiation surface.

- **Human URL:** [https://www.moneyhub.com/apis/open-banking-payments](https://www.moneyhub.com/apis/open-banking-payments)
- **Base URL:** `https://identity.moneyhub.co.uk/oidc`

#### Properties

- [Documentation](https://www.moneyhub.com/apis/open-banking-payments)
- [Smart Payments](https://www.moneyhub.com/payments-open-payment-api)
- [API Reference](https://moneyhub.github.io/api-docs/)
- [Authentication (OpenID configuration)](https://identity.moneyhub.co.uk/oidc/.well-known/openid-configuration)

## Common Properties

- [Website](https://www.moneyhub.com/)
- [Developer Portal](https://docs.moneyhubenterprise.com/)
- [Documentation](https://docs.moneyhubenterprise.com/docs/introduction)
- [API Reference](https://moneyhub.github.io/api-docs/)
- [Getting Started](https://docs.moneyhubenterprise.com/docs/getting-started)
- [Authentication](https://identity.moneyhub.co.uk/oidc/.well-known/openid-configuration)
- [GitHub Organization](https://github.com/moneyhub)
- [LinkedIn](https://www.linkedin.com/company/moneyhub)
- [Blog](https://www.moneyhub.com/blog)
- [Sign Up / Contact](https://www.moneyhub.com/contact)
- [Terms of Service](https://moneyhub.com/policies/global-terms-of-use/)
- [Privacy Policy](https://www.moneyhub.com/privacy-policy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
