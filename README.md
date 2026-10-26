# Notch (notch-financial)

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

Notch is an accounts-receivable and accounts-payable automation platform purpose-built for the food and beverage and wholesale distribution industry. It automates invoicing, payment collection, payment processing, and reconciliation, with branded customer payment portals, autopay, and dual-sync accounting / ERP integrations (QuickBooks, NetSuite, Xero, Microsoft Dynamics 365). Notch describes having an API available for integration, but does not publish a public developer reference; the API surfaces modeled here are derived from documented product capabilities and are not reconciled against an official specification.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/notch-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/notch-financial/refs/heads/main/apis.yml)

> Disambiguation: This profile is for **Notch** at [notch.financial](https://www.notch.financial) (AR/AP automation for food & beverage / wholesale distribution). It is **not** Notch Pay ([notchpay.co](https://notchpay.co), an African payment gateway), **not** Notch at [notch.cx](https://www.notch.cx) (AI agents), and **not** the Notch restaurant ordering platform.

## Tags

- Accounts Receivable
- Accounts Payable
- B2B Payments
- Invoicing
- FinTech

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Notch Invoices API

Capability area covering creation, retrieval, and management of invoices and outstanding bills that customers can view and pay. Notch syncs invoice and collections data to connected accounting / ERP systems. No public endpoint reference is documented by Notch; modeled here as an unreconciled capability.

- **Human URL:** [https://www.notch.financial/products/bills-invoice-management](https://www.notch.financial/products/bills-invoice-management)

#### Tags

- Invoices
- Bills
- Accounts Receivable

#### Properties

- [Documentation](https://www.notch.financial/products/bills-invoice-management)
- [OpenAPI](openapi/notch-financial-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notch-financial.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notch-financial.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Notch Payments API

Capability area covering payment collection, processing, autopay / scheduled pull payments, and reconciliation against invoices. Supports card and EFT/ACH payment rails per the product. No public endpoint reference is documented by Notch; modeled here as an unreconciled capability.

- **Human URL:** [https://www.notch.financial/products/payment-processing-software](https://www.notch.financial/products/payment-processing-software)

#### Tags

- Payments
- Collection
- Reconciliation

#### Properties

- [Documentation](https://www.notch.financial/products/payment-processing-software)
- [OpenAPI](openapi/notch-financial-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notch-financial.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notch-financial.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Notch Customers API

Capability area covering customer records that own invoices, payment methods, and portal access for branded self-serve payment. No public endpoint reference is documented by Notch; modeled here as an unreconciled capability.

- **Human URL:** [https://www.notch.financial/products/customer-payment-portal](https://www.notch.financial/products/customer-payment-portal)

#### Tags

- Customers
- CRM
- Accounts

#### Properties

- [Documentation](https://www.notch.financial/products/customer-payment-portal)
- [OpenAPI](openapi/notch-financial-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notch-financial.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notch-financial.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Notch Payment Methods API

Capability area covering stored customer payment methods - credit cards (Visa, Mastercard, Amex) and EFT/ACH - held in PCI-compliant infrastructure and used for autopay. No public endpoint reference is documented by Notch; modeled here as an unreconciled capability.

- **Human URL:** [https://www.notch.financial/products/customer-payment-portal](https://www.notch.financial/products/customer-payment-portal)

#### Tags

- Payment Methods
- Cards
- Autopay

#### Properties

- [Documentation](https://www.notch.financial/products/customer-payment-portal)
- [OpenAPI](openapi/notch-financial-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notch-financial.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notch-financial.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Notch Bank Accounts API

Capability area covering bank accounts used for EFT/ACH electronic fund transfers in payment collection and disbursement. No public endpoint reference is documented by Notch; modeled here as an unreconciled capability.

- **Human URL:** [https://www.notch.financial/products/payment-collection-software](https://www.notch.financial/products/payment-collection-software)

#### Tags

- Bank Accounts
- EFT
- ACH

#### Properties

- [Documentation](https://www.notch.financial/products/payment-collection-software)
- [OpenAPI](openapi/notch-financial-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notch-financial.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notch-financial.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Notch Webhooks API

Capability area covering event notifications and one-way / two-way data sync that keep connected accounting and ERP systems updated with paid bills, outstanding invoices, and collections data in real time. No public webhook reference is documented by Notch; modeled here as an unreconciled capability.

- **Human URL:** [https://www.notch.financial/integrations](https://www.notch.financial/integrations)

#### Tags

- Webhooks
- Events
- Sync

#### Properties

- [Documentation](https://www.notch.financial/integrations)
- [OpenAPI](openapi/notch-financial-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/notch-financial.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/notch-financial.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://ca.linkedin.com/company/notchfinancial)
- [Website](https://www.notch.financial)
- [Documentation](https://www.notch.financial/integrations)
- [Plans](plans/notch-financial-plans-pricing.yml)
- [Rate Limits](rate-limits/notch-financial-rate-limits.yml)
- [Fin Ops](finops/notch-financial-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
