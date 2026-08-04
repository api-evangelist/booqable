# Booqable (booqable)

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

Booqable is equipment and inventory rental management software for rental businesses - it handles online bookings, product and stock-item inventory, orders, scheduling and availability, documents and invoicing, payments, and a customer-facing online store. Booqable exposes a documented REST API (v4, "Boomerang") that follows the JSON:API specification. Requests are directed to a company-specific host, `https://{company}.booqable.com/api/4`, and authenticated with an access token (Bearer) or a signed single-use request. A legacy v1 API remains documented.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/booqable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/booqable/refs/heads/main/apis.yml)

## Tags

- Rental Management
- Inventory
- Equipment Rental
- Bookings
- Orders
- E-commerce
- JSON:API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Booqable Orders API

Create, list, search, fetch, and update rental orders. Start a new order from a template, add products and stock, and drive the order through its booking and status lifecycle. The central resource of the Booqable rental model.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Orders
- Rentals
- Bookings

#### Properties

- [Documentation](https://developers.booqable.com/) — [Documentation](https://developers.booqable.com/)
- [API Reference](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/booqable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Booqable Order Fulfillment API

Reserve, book, start, and stop the fulfillment of order lines, and move an order between statuses. Covers order fulfillments (book, specify, start, stop), order status transitions, and the line items that make up an order.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Fulfillment
- Reservations
- Lifecycle

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Products API

Manage the rentable and sellable products in the catalog - create, list, search, fetch, update, and archive products, including trackable, bulk, consumable, and service types with pricing and tax configuration.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Products
- Catalog
- Inventory

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Product Groups API

Manage product groups - the parent records that hold one or more product variations and their shared pricing, images, and metadata. Create, list, search, fetch, update, and archive product groups.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Product Groups
- Variations
- Catalog

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Customers API

Manage the people and companies that place rental orders - create, list, search, fetch, update, and archive customers, along with their contact details, addresses, tax profile, and merge fields.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Customers
- CRM
- Contacts

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Stock Items API

Manage the individually identifiable units of trackable products - create, list, fetch, and update stock items and read their plannings, plus barcodes for scanning items in and out.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Stock Items
- Inventory
- Tracking

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Availability API

Check what inventory is available for a given period before booking - query availabilities, inventory availabilities, and inventory levels by location, and list the plannings that reserve inventory against orders.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Availability
- Planning
- Scheduling

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Documents & Invoices API

Manage the financial documents attached to orders - invoices, quotes, contracts, and packing slips - via the documents resource, and read the payments and payment methods recorded against them.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Documents
- Invoices
- Payments

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Bundles & Collections API

Group products for merchandising and packaged rentals - manage bundles and their bundle items, and organize catalog items into collections for the online store.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Bundles
- Collections
- Merchandising

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Webhooks API

Subscribe to Booqable events so external systems are notified when orders, customers, products, and other resources change. Webhooks deliver server-to-endpoint HTTPS POST callbacks; there is no public WebSocket transport.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Booqable Settings & Locations API

Configure the account-level records that orders reference - physical locations, tax rates, coupons and discounts, employees, and free-form notes on any resource.

- **Human URL:** [https://developers.booqable.com/](https://developers.booqable.com/)
- **Base URL:** `https://{company}.booqable.com/api/4`

#### Tags

- Locations
- Tax Rates
- Coupons

#### Properties

- [Documentation](https://developers.booqable.com/)
- [OpenAPI](openapi/booqable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/booqable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Common Properties

- [GitHub Organization](https://github.com/booqable)
- [LinkedIn](https://www.linkedin.com/company/booqable)
- [Website](https://booqable.com)
- [Documentation](https://developers.booqable.com/)
- [Plans](plans/booqable-plans-pricing.yml)
- [Rate Limits](rate-limits/booqable-rate-limits.yml)
- [Fin Ops](finops/booqable-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
