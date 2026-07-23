# EverBank (everbank)

EverBank, N.A. is a Jacksonville, Florida based national bank (Member FDIC) focused on high-yield consumer deposits, business and treasury banking, and commercial lending, serving customers nationwide online plus financial centers in Florida, California, and New York. The bank operated as TIAA Bank from 2017 until 2023, when an investor group acquired it and it reverted to the EverBank brand as an independent institution.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/everbank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/everbank/refs/heads/main/apis.yml)

## Open Finance & API Posture

Like most US banks, EverBank publishes **no first-party public developer API and no developer portal**. Probes of `developer.everbank.com` and `apis.everbank.com` fail DNS resolution; `api.everbank.com` returns HTTP 404 with no documented API. The public site markets only consumer, business, and commercial banking products — there is no "for developers" section, API reference, or downloadable OpenAPI/Swagger.

US open finance is voluntary and fragmented (no single mandated open-banking contract as in the UK/AU). For EverBank the honest reality is **aggregator-mediated access**: consumer-permissioned account data is reached in practice through third-party financial data aggregators (Plaid, MX, Finicity, Akoya) rather than a first-party bank API. No documented Financial Data Exchange (FDX) participation or published CFPB Section 1033 data-access posture was located as of this review, and neither is asserted here.

This is an identity-only record. See `review.yml` for the full reviewer finding.

## Tags

- Financial Services
- Banking
- United States
- National Bank
- Deposits
- Commercial Banking
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public first-party APIs are documented by EverBank. `apis[]` is intentionally empty rather than padded with unverified entries.

## Common Properties

- [Website](https://www.everbank.com/)
- [About](https://www.everbank.com/about)
- [Blog / Newsroom](https://www.everbank.com/about/news)
- [Security](https://www.everbank.com/security)
- [Support](https://www.everbank.com/support)
- [Terms of Use](https://www.everbank.com/legal/terms-use)
- [Privacy Policy](https://privacy-central.securiti.ai/#/notices/b47ec243-ddfe-430d-8d01-17047bea9f8d)
- [LinkedIn](https://www.linkedin.com/company/everbank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
