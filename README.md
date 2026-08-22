# HMRC UK Tax Authority (hmrc)

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

HM Revenue and Customs (HMRC) provides over 115 APIs through the HMRC Developer Hub for UK tax compliance including Making Tax Digital for VAT and Income Tax, PAYE, customs declarations, corporation tax, and construction industry scheme. APIs use OAuth 2.0 and support both REST and XML protocols with a sandbox testing environment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Government
- Making Tax Digital
- Regulatory
- Tax
- UK

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### HMRC VAT (Making Tax Digital) API

The HMRC VAT (Making Tax Digital) API enables software to submit VAT returns, retrieve VAT obligations, liabilities, payments, penalties, and customer details in compliance with UK Making Tax Digital requirements. Uses OAuth 2.0 authentication with fraud prevention headers required.

- **Human URL:** [https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0](https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0)
- **Base URL:** `https://api.service.hmrc.gov.uk`

#### Tags

- Government
- Making Tax Digital
- REST
- Tax
- UK
- VAT

#### Properties

- [Documentation](https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0)
- [Reference](https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/vat-api/1.0/oas/page)
- [Authentication](https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation)
- [OpenAPI](openapi/hmrc-vat-mtd-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hmrc-vat-mtd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hmrc-vat-mtd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HMRC Self Assessment API

The HMRC Self Assessment APIs enable software to submit and manage self assessment tax returns, income sources, and tax calculations for individuals and sole traders under Making Tax Digital for Income Tax.

- **Human URL:** [https://developer.service.hmrc.gov.uk/api-documentation/docs/api](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- **Base URL:** `https://api.service.hmrc.gov.uk`

#### Tags

- Government
- Income Tax
- REST
- Self Assessment
- Tax
- UK

#### Properties

- [Documentation](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- [Authentication](https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation)
- [Postman Collection](collections/hmrc-vat-mtd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hmrc-vat-mtd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HMRC PAYE (Pay As You Earn) API

The HMRC PAYE APIs enable payroll software to submit employer payroll data, retrieve tax codes and employee records, and manage PAYE submissions for Real Time Information (RTI) reporting.

- **Human URL:** [https://developer.service.hmrc.gov.uk/api-documentation/docs/api](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- **Base URL:** `https://api.service.hmrc.gov.uk`

#### Tags

- Government
- PAYE
- Payroll
- REST
- Tax
- UK

#### Properties

- [Documentation](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- [Authentication](https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation)
- [Postman Collection](collections/hmrc-vat-mtd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hmrc-vat-mtd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HMRC Customs Declarations API

The HMRC Customs Declarations APIs enable customs software to submit import and export declarations, manage authorizations, and integrate with the UK Customs Declaration Service (CDS) for trade compliance.

- **Human URL:** [https://developer.service.hmrc.gov.uk/api-documentation/docs/api](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- **Base URL:** `https://api.service.hmrc.gov.uk`

#### Tags

- Customs
- Excise
- Government
- REST
- Tax
- UK
- XML

#### Properties

- [Documentation](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- [Authentication](https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation)
- [Postman Collection](collections/hmrc-vat-mtd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hmrc-vat-mtd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HMRC Corporation Tax API

The HMRC Corporation Tax APIs enable accounting software to submit corporation tax returns, retrieve liabilities, manage payments, and access tax calculation data for UK businesses.

- **Human URL:** [https://developer.service.hmrc.gov.uk/api-documentation/docs/api](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- **Base URL:** `https://api.service.hmrc.gov.uk`

#### Tags

- Business
- Corporation Tax
- Government
- REST
- Tax
- UK

#### Properties

- [Documentation](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- [Authentication](https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation)
- [Postman Collection](collections/hmrc-vat-mtd.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hmrc-vat-mtd.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/hmrc)
- [LinkedIn](https://www.linkedin.com/company/hmrc)
- [Portal](https://developer.service.hmrc.gov.uk/)
- [Documentation](https://developer.service.hmrc.gov.uk/api-documentation/docs/api)
- [Authentication](https://developer.service.hmrc.gov.uk/api-documentation/docs/authorisation)
- [Getting Started](https://developer.service.hmrc.gov.uk/api-documentation/docs/using-the-hub)
- [Terms of Service](https://www.gov.uk/api-documentation/docs/terms-of-use)
- [Status Page](https://api-platform-status.production.tax.service.gov.uk/)
- [Support](https://developer.service.hmrc.gov.uk/)
- [Website](https://www.gov.uk/government/organisations/hm-revenue-customs)
- [OpenAPI](openapi/hmrc-vat-mtd-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/hmrc-vat-return-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/hmrc-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
