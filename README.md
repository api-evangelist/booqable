# Booqable

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

Booqable is equipment and inventory rental management software for rental businesses - it handles online bookings, product and stock-item inventory, orders, scheduling and availability, documents and invoicing, payments, and a customer-facing online store. Booqable exposes a documented REST API (v4, "Boomerang") that follows the JSON:API specification. Requests are directed to a company-specific host, https://{company}.booqable.com/api/4, and authenticated with an access token (Bearer) or a signed single-use request. A legacy v1 API remains documented. The API lets developers manage orders, products, product groups, customers, stock items, availability and plannings, documents, payments, and webhooks.

**Areas:** Rental Management · Inventory · Equipment Rental · Booking · Order · E-Commerce · JSON:API

## Booqable on APIs.io

Everything profiled for Booqable is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/booqable/](https://apis.io/providers/booqable/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Booqable Availability API](https://apis.io/apis/booqable/booqable-availability-api/) — Inventory availability, levels, and plannings.
- [Booqable Bundles & Collections API](https://apis.io/apis/booqable/booqable-bundles-collections-api/) — Merchandising groups and store collections.
- [Booqable Customers API](https://apis.io/apis/booqable/booqable-customers-api/) — People and companies that place orders.
- [Booqable Documents API](https://apis.io/apis/booqable/booqable-documents-api/) — Invoices, quotes, contracts, and payments.
- [Booqable Order Fulfillment API](https://apis.io/apis/booqable/booqable-order-fulfillment-api/) — Booking, starting, stopping, and transitioning orders and their lines.
- [Booqable Orders API](https://apis.io/apis/booqable/booqable-orders-api/) — Rental orders and their lifecycle.
- [Booqable Product Groups API](https://apis.io/apis/booqable/booqable-product-groups-api/) — Parent records grouping product variations.
- [Booqable Products API](https://apis.io/apis/booqable/booqable-products-api/) — Rentable and sellable catalog products.
- [Booqable Settings API](https://apis.io/apis/booqable/booqable-settings-api/) — Locations, tax rates, coupons, employees, and notes.
- [Booqable Stock Items API](https://apis.io/apis/booqable/booqable-stock-items-api/) — Individually identifiable units of trackable products.
- [Booqable Webhooks API](https://apis.io/apis/booqable/booqable-webhooks-api/) — Event subscriptions delivering HTTPS callbacks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Booqable Agentic Access](https://apis.io/agentic-access/booqable/booqable-agentic-access/)

#### Collections (12)

Postman and Open Collection request collections.

- [Booqable API (v4 Boomerang)](https://apis.io/collections/booqable/open-booqable/)
- [Booqable API (v4 "Boomerang") Availability API](https://apis.io/collections/booqable/open-booqable-availability-api/)
- [Booqable API (v4 "Boomerang") Availability Bundles & Collections API](https://apis.io/collections/booqable/open-booqable-bundles-collections-api/)
- [Booqable API (v4 "Boomerang") Availability Customers API](https://apis.io/collections/booqable/open-booqable-customers-api/)
- [Booqable API (v4 "Boomerang") Availability Documents API](https://apis.io/collections/booqable/open-booqable-documents-api/)
- [Booqable API (v4 "Boomerang") Availability Order Fulfillment API](https://apis.io/collections/booqable/open-booqable-order-fulfillment-api/)
- [Booqable API (v4 "Boomerang") Availability Orders API](https://apis.io/collections/booqable/open-booqable-orders-api/)
- [Booqable API (v4 "Boomerang") Availability Product Groups API](https://apis.io/collections/booqable/open-booqable-product-groups-api/)
- [Booqable API (v4 "Boomerang") Availability Products API](https://apis.io/collections/booqable/open-booqable-products-api/)
- [Booqable API (v4 "Boomerang") Availability Settings API](https://apis.io/collections/booqable/open-booqable-settings-api/)
- [Booqable API (v4 "Boomerang") Availability Stock Items API](https://apis.io/collections/booqable/open-booqable-stock-items-api/)
- [Booqable API (v4 "Boomerang") Availability Webhooks API](https://apis.io/collections/booqable/open-booqable-webhooks-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Booqable Authentication](https://apis.io/security/booqable/booqable-authentication/)
- [Booqable Domain Security](https://apis.io/security/booqable/booqable-domain-security/)
- [Booqable Trust Center](https://apis.io/security/booqable/booqable-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Booqable Plans Pricing](https://apis.io/plans/booqable/booqable-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Booqable Rate Limits](https://apis.io/rate-limits/booqable/booqable-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Booqable Finops](https://apis.io/finops/booqable/booqable-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://booqable.com)
- [Documentation](https://developers.booqable.com/)
- [Blog](https://booqable.com/blog/)
- [GitHub](https://github.com/booqable)

## API Evangelist rating

**Kin Score 29.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 48.0 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 32.1 |
| Access clarity | 15.8 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/booqable/](https://apis.io/providers/booqable/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Booqable: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/booqable/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
