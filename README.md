# Quandoo (quandoo)

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

Quandoo is a restaurant reservations marketplace that connects diners with thousands of restaurants and gives merchants table, reservation, and reputation management tooling. Quandoo publishes the Public Partner API, a multi-purpose REST API (host public-api.prod.quandoo.com, authenticated with the X-Quandoo-AuthToken header) that lets partners check merchant availability, search merchants, read merchant reservation and enquiry settings, create and manage reservations and reservation enquiries, manage customers and reviews, handle reservation tags, and validate phone numbers. Reservation and enquiry creation is idempotent via agent-supplied unique identifiers, and returns HTTP 409 when a slot is no longer bookable. Quandoo offers widget, portal, discovery-widget, and direct integration paths plus an interactive API explorer. Note: Quandoo announced in March 2026 that it will wind down operations, with new bookings ending 30 September 2026; this profile documents the still-live Public Partner API as published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quandoo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quandoo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Reservations
- Booking
- Availability
- Merchants
- Marketplace

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### Quandoo Public Partner API

The Quandoo Public Partner API is a multi-purpose REST API for the Quandoo platform. It lets partners check merchant availability, create reservations and reservation enquiries, read merchant reservation settings, and manage table planning. Reservation creation is idempotent using an agent-specific unique ID. An interactive API explorer is provided for testing endpoints and parameters.

- **Human URL:** [https://docs.quandoo.com/](https://docs.quandoo.com/)
- **Base URL:** `https://public-api.prod.quandoo.com`

#### Tags

- Reservations
- Availability
- Merchants
- Booking

#### Properties

- [Documentation](https://docs.quandoo.com/)
- [Getting Started](https://docs.quandoo.com/interactive-api/)
- [OpenAPI](openapi/quandoo-public-partner-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/quandoo-public-partner-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quandoo-public-partner-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://api.quandoo.com/docs/swagger.html)
- [Authentication](https://docs.quandoo.com/development-environments/)
- [JSON Schema](json-schema/quandoo-public-partner-api-agent-tracking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-area-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-chain-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-changed-review-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-coordinates-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-create-review-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-created-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-created-reservation-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-created-reservation-enquiry-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-created-reservation-enquiry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-created-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-customer-data-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-customer-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-customer-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-customer-review-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-customer-statistics-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-document-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-get-reservation-enquiry-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-get-review-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-get-reviews-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-image-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-link-relation-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-location-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-marketing-setting-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-address-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-availability-days-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-availability-dto-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-availability-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-customer-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-details-dto-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-details-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-reservation-data-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-reservation-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-reservation-enquiry-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-reservation-enquiry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-reservation-settings-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-vault-settings-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-merchant-with-recommendations-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-opening-times-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-data-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-details-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-enquiry-message-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-enquiry-message-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-tag-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-reservation-tags-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-rest-cookie-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-review-dto-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-review-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-standard-opening-times-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-tag-group-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-tracking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-translated-tag-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-update-reservation-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-update-reservation-enquiry-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/quandoo-public-partner-api-update-review-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/quandoo-public-partner-api-agent-tracking-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-area-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-chain-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-changed-review-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-coordinates-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-create-review-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-created-customer-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-created-reservation-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-created-reservation-enquiry-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-created-reservation-enquiry-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-created-reservation-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-customer-data-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-customer-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-customer-response-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-customer-review-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-customer-statistics-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-document-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-get-reservation-enquiry-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-get-review-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-get-reviews-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-image-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-link-relation-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-location-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-marketing-setting-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-address-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-availability-days-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-availability-dto-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-availability-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-customer-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-customer-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-details-dto-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-details-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-reservation-data-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-reservation-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-reservation-enquiry-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-reservation-enquiry-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-reservation-settings-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-reservation-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-subscription-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-vault-settings-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-merchant-with-recommendations-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-opening-times-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-data-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-details-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-enquiry-message-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-enquiry-message-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-tag-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-reservation-tags-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-rest-cookie-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-review-dto-list-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-review-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-standard-opening-times-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-tag-group-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-tracking-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-translated-tag-dto-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-update-reservation-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-update-reservation-enquiry-data-structure.json)
- [JSON Structure](json-structure/quandoo-public-partner-api-update-review-dto-structure.json)
- [Example](examples/quandoo-public-partner-api-agent-tracking-example.json)
- [Example](examples/quandoo-public-partner-api-area-dto-example.json)
- [Example](examples/quandoo-public-partner-api-chain-dto-example.json)
- [Example](examples/quandoo-public-partner-api-changed-review-dto-example.json)
- [Example](examples/quandoo-public-partner-api-coordinates-dto-example.json)
- [Example](examples/quandoo-public-partner-api-create-review-dto-example.json)
- [Example](examples/quandoo-public-partner-api-created-customer-example.json)
- [Example](examples/quandoo-public-partner-api-created-reservation-data-example.json)
- [Example](examples/quandoo-public-partner-api-created-reservation-enquiry-data-example.json)
- [Example](examples/quandoo-public-partner-api-created-reservation-enquiry-example.json)
- [Example](examples/quandoo-public-partner-api-created-reservation-example.json)
- [Example](examples/quandoo-public-partner-api-customer-data-list-example.json)
- [Example](examples/quandoo-public-partner-api-customer-dto-example.json)
- [Example](examples/quandoo-public-partner-api-customer-response-example.json)
- [Example](examples/quandoo-public-partner-api-customer-review-data-example.json)
- [Example](examples/quandoo-public-partner-api-customer-statistics-data-example.json)
- [Example](examples/quandoo-public-partner-api-document-dto-example.json)
- [Example](examples/quandoo-public-partner-api-get-reservation-enquiry-data-example.json)
- [Example](examples/quandoo-public-partner-api-get-review-dto-example.json)
- [Example](examples/quandoo-public-partner-api-get-reviews-dto-example.json)
- [Example](examples/quandoo-public-partner-api-image-dto-example.json)
- [Example](examples/quandoo-public-partner-api-link-relation-dto-example.json)
- [Example](examples/quandoo-public-partner-api-location-dto-example.json)
- [Example](examples/quandoo-public-partner-api-marketing-setting-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-address-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-availability-days-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-availability-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-availability-dto-list-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-customer-data-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-customer-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-details-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-details-dto-list-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-reservation-data-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-reservation-data-list-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-reservation-enquiry-data-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-reservation-enquiry-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-reservation-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-reservation-settings-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-subscription-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-vault-settings-dto-example.json)
- [Example](examples/quandoo-public-partner-api-merchant-with-recommendations-dto-example.json)
- [Example](examples/quandoo-public-partner-api-opening-times-dto-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-data-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-data-list-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-details-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-enquiry-message-data-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-enquiry-message-list-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-tag-dto-example.json)
- [Example](examples/quandoo-public-partner-api-reservation-tags-dto-example.json)
- [Example](examples/quandoo-public-partner-api-rest-cookie-example.json)
- [Example](examples/quandoo-public-partner-api-review-dto-example.json)
- [Example](examples/quandoo-public-partner-api-review-dto-list-example.json)
- [Example](examples/quandoo-public-partner-api-standard-opening-times-dto-example.json)
- [Example](examples/quandoo-public-partner-api-tag-group-dto-example.json)
- [Example](examples/quandoo-public-partner-api-tracking-example.json)
- [Example](examples/quandoo-public-partner-api-translated-tag-dto-example.json)
- [Example](examples/quandoo-public-partner-api-update-reservation-data-example.json)
- [Example](examples/quandoo-public-partner-api-update-reservation-enquiry-data-example.json)
- [Example](examples/quandoo-public-partner-api-update-review-dto-example.json)

## Common Properties

- [Website](https://www.quandoo.com)
- [Documentation](https://docs.quandoo.com/)
- [API Reference](https://docs.quandoo.com/interactive-api/)
- [Support](mailto:developers@quandoo.com)
- [GitHub Organization](https://github.com/quandoo)
- [Spectral Rules](rules/quandoo-public-partner-api-spectral-rules.yml)
- [Vocabulary](vocabulary/quandoo-vocabulary.yml)
- [J S O N- L D](json-ld/quandoo-context.jsonld)
- [Plans](plans/quandoo-plans-pricing.yml)
- [Rate Limits](rate-limits/quandoo-rate-limits.yml)
- [Fin Ops](finops/quandoo-finops.yml)
- [Pricing](https://restaurants.quandoo.com/)
- [Terms of Service](https://restaurants.quandoo.com/en-gb/terms-and-conditions)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
