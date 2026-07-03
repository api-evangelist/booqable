# Booqable (booqable)

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
