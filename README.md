# Quandoo

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

Quandoo is a restaurant reservations marketplace that connects diners with thousands of restaurants and gives merchants table, reservation, and reputation management tooling. Quandoo publishes the Public Partner API, a multi-purpose REST API (host public-api.prod.quandoo.com, authenticated with the X-Quandoo-AuthToken header) that lets partners check merchant availability, search merchants, read merchant reservation and enquiry settings, create and manage reservations and reservation enquiries, manage customers and reviews, handle reservation tags, and validate phone numbers. Reservation and enquiry creation is idempotent via agent-supplied unique identifiers, and returns HTTP 409 when a slot is no longer bookable. Quandoo offers widget, portal, discovery-widget, and direct integration paths plus an interactive API explorer. Note: Quandoo announced in March 2026 that it will wind down operations, with new bookings ending 30 September 2026; this profile documents the still-live Public Partner API as published.

**Areas:** Restaurant · Reservations · Booking · Availability · Merchants · Marketplace

## Quandoo on APIs.io

Everything profiled for Quandoo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/quandoo/](https://apis.io/providers/quandoo/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Quandoo Availabilities API](https://apis.io/apis/quandoo/quandoo-availabilities-api/) — The Availabilities API from Quandoo — 2 operation(s) for availabilities.
- [Quandoo Customers API](https://apis.io/apis/quandoo/quandoo-customers-api/) — The Customers API from Quandoo — 3 operation(s) for customers.
- [Quandoo Merchants API](https://apis.io/apis/quandoo/quandoo-merchants-api/) — The Merchants API from Quandoo — 5 operation(s) for merchants.
- [Quandoo Reservation Enquiries API](https://apis.io/apis/quandoo/quandoo-reservation-enquiries-api/) — The Reservation Enquiries API from Quandoo — 3 operation(s) for reservation enquiries.
- [Quandoo Reservation Settings API](https://apis.io/apis/quandoo/quandoo-reservation-settings-api/) — The Reservation Settings API from Quandoo — 1 operation(s) for reservation settings.
- [Quandoo Reservations API](https://apis.io/apis/quandoo/quandoo-reservations-api/) — The Reservations API from Quandoo — 2 operation(s) for reservations.
- [Quandoo Reservations Tags API](https://apis.io/apis/quandoo/quandoo-reservations-tags-api/) — The Reservations Tags API from Quandoo — 1 operation(s) for reservations tags.
- [Quandoo Reviews API](https://apis.io/apis/quandoo/quandoo-reviews-api/) — The Reviews API from Quandoo — 1 operation(s) for reviews.
- [Quandoo Status API](https://apis.io/apis/quandoo/quandoo-status-api/) — The Status API from Quandoo — 1 operation(s) for status.
- [Quandoo Validations API](https://apis.io/apis/quandoo/quandoo-validations-api/) — The Validations API from Quandoo — 1 operation(s) for validations.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Quandoo Agentic Access](https://apis.io/agentic-access/quandoo/quandoo-agentic-access/)

#### JSON Schema (59)

The data models the API reads and writes.

- [AgentTracking](https://apis.io/schemas/quandoo/quandoo-public-partner-api-agent-tracking/)
- [AreaDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-area-dto/)
- [ChainDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-chain-dto/)
- [ChangedReviewDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-changed-review-dto/)
- [CoordinatesDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-coordinates-dto/)
- [CreateReviewDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-create-review-dto/)
- [CreatedCustomer](https://apis.io/schemas/quandoo/quandoo-public-partner-api-created-customer/)
- [CreatedReservation](https://apis.io/schemas/quandoo/quandoo-public-partner-api-created-reservation/)
- [CreatedReservationData](https://apis.io/schemas/quandoo/quandoo-public-partner-api-created-reservation-data/)
- [CreatedReservationEnquiry](https://apis.io/schemas/quandoo/quandoo-public-partner-api-created-reservation-enquiry/)
- [CreatedReservationEnquiryData](https://apis.io/schemas/quandoo/quandoo-public-partner-api-created-reservation-enquiry-data/)
- [CustomerDataList](https://apis.io/schemas/quandoo/quandoo-public-partner-api-customer-data-list/)
- [CustomerDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-customer-dto/)
- [CustomerResponse](https://apis.io/schemas/quandoo/quandoo-public-partner-api-customer-response/)
- [CustomerReviewData](https://apis.io/schemas/quandoo/quandoo-public-partner-api-customer-review-data/)
- [CustomerStatisticsData](https://apis.io/schemas/quandoo/quandoo-public-partner-api-customer-statistics-data/)
- [DocumentDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-document-dto/)
- [GetReservationEnquiryData](https://apis.io/schemas/quandoo/quandoo-public-partner-api-get-reservation-enquiry-data/)
- [GetReviewDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-get-review-dto/)
- [GetReviewsDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-get-reviews-dto/)
- [ImageDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-image-dto/)
- [LinkRelationDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-link-relation-dto/)
- [LocationDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-location-dto/)
- [MarketingSettingDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-marketing-setting-dto/)
- [MerchantAddressDto](https://apis.io/schemas/quandoo/quandoo-public-partner-api-merchant-address-dto/)
- …and 34 more published on APIs.io

#### JSON Structure (59)

Data models expressed in JSON Structure.

- [Quandoo Public Partner Api Agent Tracking Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-agent-tracking-structure/)
- [Quandoo Public Partner Api Area Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-area-dto-structure/)
- [Quandoo Public Partner Api Chain Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-chain-dto-structure/)
- [Quandoo Public Partner Api Changed Review Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-changed-review-dto-structure/)
- [Quandoo Public Partner Api Coordinates Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-coordinates-dto-structure/)
- [Quandoo Public Partner Api Create Review Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-create-review-dto-structure/)
- [Quandoo Public Partner Api Created Customer Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-created-customer-structure/)
- [Quandoo Public Partner Api Created Reservation Data Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-created-reservation-data-structure/)
- [Quandoo Public Partner Api Created Reservation Enquiry Data Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-created-reservation-enquiry-data-structure/)
- [Quandoo Public Partner Api Created Reservation Enquiry Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-created-reservation-enquiry-structure/)
- [Quandoo Public Partner Api Created Reservation Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-created-reservation-structure/)
- [Quandoo Public Partner Api Customer Data List Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-customer-data-list-structure/)
- [Quandoo Public Partner Api Customer Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-customer-dto-structure/)
- [Quandoo Public Partner Api Customer Response Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-customer-response-structure/)
- [Quandoo Public Partner Api Customer Review Data Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-customer-review-data-structure/)
- [Quandoo Public Partner Api Customer Statistics Data Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-customer-statistics-data-structure/)
- [Quandoo Public Partner Api Document Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-document-dto-structure/)
- [Quandoo Public Partner Api Get Reservation Enquiry Data Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-get-reservation-enquiry-data-structure/)
- [Quandoo Public Partner Api Get Review Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-get-review-dto-structure/)
- [Quandoo Public Partner Api Get Reviews Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-get-reviews-dto-structure/)
- [Quandoo Public Partner Api Image Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-image-dto-structure/)
- [Quandoo Public Partner Api Link Relation Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-link-relation-dto-structure/)
- [Quandoo Public Partner Api Location Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-location-dto-structure/)
- [Quandoo Public Partner Api Marketing Setting Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-marketing-setting-dto-structure/)
- [Quandoo Public Partner Api Merchant Address Dto Structure](https://apis.io/json-structure/quandoo/quandoo-public-partner-api-merchant-address-dto-structure/)
- …and 34 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Quandoo Context](https://apis.io/jsonld/quandoo/quandoo-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Quandoo Vocabulary](https://apis.io/vocabularies/quandoo/quandoo-vocabulary/)

#### Examples (59)

Example requests and responses.

- [Quandoo Public Partner Api Agent Tracking Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-agent-tracking-example/)
- [Quandoo Public Partner Api Area Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-area-dto-example/)
- [Quandoo Public Partner Api Chain Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-chain-dto-example/)
- [Quandoo Public Partner Api Changed Review Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-changed-review-dto-example/)
- [Quandoo Public Partner Api Coordinates Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-coordinates-dto-example/)
- [Quandoo Public Partner Api Create Review Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-create-review-dto-example/)
- [Quandoo Public Partner Api Created Customer Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-created-customer-example/)
- [Quandoo Public Partner Api Created Reservation Data Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-created-reservation-data-example/)
- [Quandoo Public Partner Api Created Reservation Enquiry Data Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-created-reservation-enquiry-data-example/)
- [Quandoo Public Partner Api Created Reservation Enquiry Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-created-reservation-enquiry-example/)
- [Quandoo Public Partner Api Created Reservation Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-created-reservation-example/)
- [Quandoo Public Partner Api Customer Data List Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-customer-data-list-example/)
- [Quandoo Public Partner Api Customer Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-customer-dto-example/)
- [Quandoo Public Partner Api Customer Response Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-customer-response-example/)
- [Quandoo Public Partner Api Customer Review Data Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-customer-review-data-example/)
- [Quandoo Public Partner Api Customer Statistics Data Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-customer-statistics-data-example/)
- [Quandoo Public Partner Api Document Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-document-dto-example/)
- [Quandoo Public Partner Api Get Reservation Enquiry Data Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-get-reservation-enquiry-data-example/)
- [Quandoo Public Partner Api Get Review Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-get-review-dto-example/)
- [Quandoo Public Partner Api Get Reviews Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-get-reviews-dto-example/)
- [Quandoo Public Partner Api Image Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-image-dto-example/)
- [Quandoo Public Partner Api Link Relation Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-link-relation-dto-example/)
- [Quandoo Public Partner Api Location Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-location-dto-example/)
- [Quandoo Public Partner Api Marketing Setting Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-marketing-setting-dto-example/)
- [Quandoo Public Partner Api Merchant Address Dto Example](https://apis.io/examples/quandoo/quandoo-public-partner-api-merchant-address-dto-example/)
- …and 34 more published on APIs.io

#### Collections (20)

Postman and Open Collection request collections.

- [Quandoo Public Partner Availabilities API](https://apis.io/collections/quandoo/open-quandoo-availabilities-api/)
- [Quandoo Public Partner Availabilities Customers API](https://apis.io/collections/quandoo/open-quandoo-customers-api/)
- [Quandoo Public Partner Availabilities Merchants API](https://apis.io/collections/quandoo/open-quandoo-merchants-api/)
- [Quandoo Public Partner API](https://apis.io/collections/quandoo/open-quandoo-public-partner-api/)
- [Quandoo Public Partner Availabilities Reservation Enquiries API](https://apis.io/collections/quandoo/open-quandoo-reservation-enquiries-api/)
- [Quandoo Public Partner Availabilities Reservation Settings API](https://apis.io/collections/quandoo/open-quandoo-reservation-settings-api/)
- [Quandoo Public Partner Availabilities Reservations API](https://apis.io/collections/quandoo/open-quandoo-reservations-api/)
- [Quandoo Public Partner Availabilities Reservations Tags API](https://apis.io/collections/quandoo/open-quandoo-reservations-tags-api/)
- [Quandoo Public Partner Availabilities Status API](https://apis.io/collections/quandoo/open-quandoo-status-api/)
- [Quandoo Public Partner Availabilities Validations API](https://apis.io/collections/quandoo/open-quandoo-validations-api/)
- [Quandoo Public Partner Availabilities API](https://apis.io/collections/quandoo/postman-quandoo-availabilities-api/)
- [Quandoo Public Partner Availabilities Customers API](https://apis.io/collections/quandoo/postman-quandoo-customers-api/)
- [Quandoo Public Partner Availabilities Merchants API](https://apis.io/collections/quandoo/postman-quandoo-merchants-api/)
- [Quandoo Public Partner Availabilities Reservation Enquiries API](https://apis.io/collections/quandoo/postman-quandoo-reservation-enquiries-api/)
- [Quandoo Public Partner Availabilities Reservation Settings API](https://apis.io/collections/quandoo/postman-quandoo-reservation-settings-api/)
- [Quandoo Public Partner Availabilities Reservations API](https://apis.io/collections/quandoo/postman-quandoo-reservations-api/)
- [Quandoo Public Partner Availabilities Reservations Tags API](https://apis.io/collections/quandoo/postman-quandoo-reservations-tags-api/)
- [Quandoo Public Partner Availabilities Reviews API](https://apis.io/collections/quandoo/postman-quandoo-reviews-api/)
- [Quandoo Public Partner Availabilities Status API](https://apis.io/collections/quandoo/postman-quandoo-status-api/)
- [Quandoo Public Partner Availabilities Validations API](https://apis.io/collections/quandoo/postman-quandoo-validations-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Quandoo — jsonschema rules](https://apis.io/rules/quandoo/quandoo-jsonschema-spectral-rules/)
- [Quandoo — public partner api rules](https://apis.io/rules/quandoo/quandoo-public-partner-api-spectral-rules/)
- [Quandoo API Rules](https://apis.io/rules/quandoo/quandoo-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Quandoo Authentication](https://apis.io/security/quandoo/quandoo-authentication/)
- [Quandoo Domain Security](https://apis.io/security/quandoo/quandoo-domain-security/)
- [Quandoo Vulnerability Disclosure](https://apis.io/security/quandoo/quandoo-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Quandoo Plans Pricing](https://apis.io/plans/quandoo/quandoo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Quandoo Rate Limits](https://apis.io/rate-limits/quandoo/quandoo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Quandoo Finops](https://apis.io/finops/quandoo/quandoo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.quandoo.com)
- [Documentation](https://docs.quandoo.com/)
- [API reference](https://docs.quandoo.com/interactive-api/)
- [Pricing](https://restaurants.quandoo.com/)
- [Terms of service](https://restaurants.quandoo.com/en-gb/terms-and-conditions)
- [GitHub](https://github.com/quandoo)

## API Evangelist rating

**Kin Score 44.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 69.2 |
| Contract governance | 27.3 |
| Operational transparency | 18.4 |
| Developer ergonomics | 46.4 |
| Access clarity | 28.9 |

**Agent readiness 30.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/quandoo/](https://apis.io/providers/quandoo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Quandoo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/quandoo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
