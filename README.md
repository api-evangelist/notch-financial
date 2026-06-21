# Notch (notch-financial)

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
