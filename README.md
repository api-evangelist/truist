# Truist (truist)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
