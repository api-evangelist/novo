# Novo (novo)

Novo is a New York- and Miami-based financial technology company, founded in 2016, that operates a digital business-banking platform for small businesses, entrepreneurs, and freelancers. Novo is not itself a chartered bank — it is a service provider to Middlesex Federal Savings, F.A. (Member FDIC), which holds deposits and provides the underlying banking products accessed through Novo's app.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/novo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/novo/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- Neobank
- Small Business Banking
- Fintech
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

Novo publishes **no first-party public developer API** and runs **no developer portal**. Both `developer.novo.co` and `developers.novo.co` fail to resolve, and there is no "Developers" or "API" link anywhere in the site. A host at `api.novo.co` exists but is Novo's private mobile/web application backend (an istio-envoy gateway using proprietary auth headers), not a documented, public, or partner-facing API. No downloadable OpenAPI/Swagger is published.

### Open-Finance Posture

- **First-party API:** None.
- **FDX:** No documented Financial Data Exchange participation.
- **CFPB Section 1033:** No published data-access posture.
- **Aggregator access (the honest reality):** Consumer-permissioned account data is reached by third parties **only through the Plaid aggregator** — Novo is a Depository institution on Plaid (US), with supported products including Auth, Balance, Assets, and Transactions. See [Novo on Plaid](https://plaid.com/institutions/novo/).
- **Banking partner:** Middlesex Federal Savings, F.A. (Member FDIC).

This is an identity-only record. There is genuinely no public API surface to catalog.

## Common Properties

- [Website](https://novo.co)
- [Support](https://novo.co/help)
- [Privacy Policy](https://novo.co/legal/privacy)
- [Terms / Legal](https://novo.co/legal)
- [Blog / Learn](https://novo.co/learn)
- [LinkedIn](https://www.linkedin.com/company/banknovo)
- [Data Access via Plaid](https://plaid.com/institutions/novo/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
