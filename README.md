# Truist (truist)

Truist Financial Corporation is a U.S. bank holding company headquartered in Charlotte, North Carolina, formed in December 2019 through the merger of BB&T and SunTrust Banks. Its principal subsidiary, Truist Bank, is a North Carolina state-chartered commercial bank and member of the Federal Reserve System, ranking among the largest U.S. commercial banks by assets. Truist runs a first-party Truist Developer Center publishing registration-gated Open Banking APIs in a mock-data sandbox, plus a separate Open Banking data-access portal, and shares consumer data largely through FDX-aligned, tokenized connections and aggregator partnerships (notably Plaid).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/truist/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/truist/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- Open Finance
- FDX
- Payments
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Open Finance Posture

- **First-party developer portal:** [Truist Developer Center](https://developer.truist.com/) (live, HTTP 200) publishes Open Banking APIs. The API catalog is registration-gated and available only in a **Sandbox** environment that returns **mock demo responses** - no public production API and no downloadable OpenAPI/Swagger.
- **Open Banking data-access portal:** [Truist Open Banking API Developer Portal](https://truist-1132.my.site.com/truist/s/) (live, HTTP 200) for consumer-permissioned data sharing.
- **FDX:** Truist uses an **FDX-aligned**, tokenized data-sharing API (documented via its Plaid data-access agreement) that replaces credential sharing.
- **CFPB Section 1033:** Truist states it monitors and complies with evolving personal-financial-data-rights rulemaking; no distinct public 1033 API surface is documented.
- **Aggregator access:** Third-party consumer data access is delivered largely through aggregators (Plaid, and others) rather than an open first-party production API.

## APIs

### Truist Personal and Small Business Accounts API

Open Banking API in the Truist Developer Center covering personal and small-business accounts - account information, balances, and transaction data. Documented in a registration-gated sandbox that returns mock demo responses.

- **Human URL:** [https://developer.truist.com/api/personal-and-small-business-accounts/overview](https://developer.truist.com/api/personal-and-small-business-accounts/overview)

#### Tags

- Accounts
- Balances
- Transactions
- Open Banking

#### Properties

- [Documentation](https://developer.truist.com/api/personal-and-small-business-accounts/overview)
- [Documentation](https://developer.truist.com/api/working-with-truist)
- [API Reference](https://developer.truist.com/api/view-api)

### Truist Open Banking Data Access (FDX-aligned)

Consumer-permissioned data-sharing surface delivered through the Truist Open Banking API Developer Portal and FDX-aligned, tokenized connections (including a Plaid data-access partnership) that replace credential sharing.

- **Human URL:** [https://truist-1132.my.site.com/truist/s/](https://truist-1132.my.site.com/truist/s/)

#### Tags

- Open Banking
- FDX
- Data Aggregation
- Consumer Data

#### Properties

- [Documentation](https://truist-1132.my.site.com/truist/s/)

## Common Properties

- [Website](https://www.truist.com)
- [Developer Portal](https://developer.truist.com/)
- [Portal](https://truist-1132.my.site.com/truist/s/)
- [Documentation](https://developer.truist.com/api/working-with-truist)
- [LinkedIn](https://www.linkedin.com/company/truist)
- [Privacy Policy](https://www.truist.com/privacy)
- [Terms of Service](https://www.truist.com/terms-and-conditions)
- [Support](https://www.truist.com/support)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
