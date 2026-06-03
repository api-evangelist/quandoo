# Quandoo (quandoo)

Quandoo is a restaurant reservations marketplace that connects diners with thousands of restaurants and gives merchants table, reservation, and reputation management tooling. Quandoo publishes the Public Partner API, a multi-purpose REST API (host public-api.prod.quandoo.com, authenticated with the X-Quandoo-AuthToken header) that lets partners check merchant availability, search merchants, read merchant reservation and enquiry settings, create and manage reservations and reservation enquiries, manage customers and reviews, handle reservation tags, and validate phone numbers. Reservation and enquiry creation is idempotent via agent-supplied unique identifiers, and returns HTTP 409 when a slot is no longer bookable. Quandoo offers widget, portal, discovery-widget, and direct integration paths plus an interactive API explorer. Note: Quandoo announced in March 2026 that it will wind down operations, with new bookings ending 30 September 2026; this profile documents the still-live Public Partner API as published.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/quandoo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Reservations, Booking, Availability, Merchants, Marketplace

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### Quandoo Public Partner API

The Quandoo Public Partner API is a multi-purpose REST API for the Quandoo platform. It lets partners check merchant availability, create reservations and reservation enquiries, read merchant reservation settings, and manage table planning. Reservation creation is idempotent using an agent-specific unique ID. An interactive API explorer is provided for testing endpoints and parameters.

**Human URL:** [https://docs.quandoo.com/](https://docs.quandoo.com/)

**Base URL:** `https://public-api.prod.quandoo.com`

#### Tags:

 - Reservations, Availability, Merchants, Booking

#### Properties

- [Documentation](https://docs.quandoo.com/)
- [GettingStarted](https://docs.quandoo.com/interactive-api/)
- [OpenAPI](openapi/quandoo-public-partner-api-openapi.yml)
- [APIReference](https://api.quandoo.com/docs/swagger.html)
- [Authentication](https://docs.quandoo.com/development-environments/)
- 59 [JSONSchema](json-schema/) artifacts
- 59 [JSONStructure](json-structure/) artifacts
- 59 [Example](examples/) artifacts
- 10 [NaftikoCapability](capabilities/) artifacts

## Common Properties

- [Website](https://www.quandoo.com)
- [Documentation](https://docs.quandoo.com/)
- [APIReference](https://docs.quandoo.com/interactive-api/)
- [Support](mailto:developers@quandoo.com)
- [GitHubOrganization](https://github.com/quandoo)
- [SpectralRules](rules/quandoo-public-partner-api-spectral-rules.yml)
- [Vocabulary](vocabulary/quandoo-vocabulary.yml)
- [JSON-LD](json-ld/quandoo-context.jsonld)
- [Plans](plans/quandoo-plans-pricing.yml)
- [RateLimits](rate-limits/quandoo-rate-limits.yml)
- [FinOps](finops/quandoo-finops.yml)
- [Pricing](https://restaurants.quandoo.com/)
- [TermsOfService](https://restaurants.quandoo.com/en-gb/terms-and-conditions)

## Features

| Name | Description |
|------|-------------|
| Availability Search | Check merchant availability days and time slots and search bookable merchants by place, location, date, time, and capacity. |
| Reservation Management | Create, retrieve, and update reservations with idempotent creation keyed on an agent-specific unique ID. |
| Reservation Enquiries | Create and manage reservation enquiries (for larger groups) including reading enquiry messages and updating status. |
| Merchant Settings | Read merchant reservation and enquiry settings such as capacities, areas, online reservation interval, and credit-card-vault requirements. |
| Reviews | Read, create, and update customer reviews tied to reservations. |
| Phone Validation | Validate customer phone numbers before submitting a reservation. |
| Multiple Integration Paths | Widget, portal, discovery-widget, and direct integration options plus an interactive API explorer. |

## Use Cases

| Name | Description |
|------|-------------|
| Embedded Booking Experiences | Build diner-facing booking flows that search merchants, check availability, and create reservations on top of Quandoo inventory. |
| Group Enquiry Handling | Route large-party requests to the enquiry workflow when group size exceeds the merchant minimum for enquiries. |
| Merchant Operations | Let restaurant operators manage reservations, customers, tags, and reviews for their venue. |
| Channel Attribution | Distinguish marketplace covers from free own-channel covers (widget, Google, social) for cost attribution. |

## Integrations

| Name | Description |
|------|-------------|
| Booking Widget | Embeddable Quandoo booking widget for merchant websites and apps. |
| Google Network | Reservations sourced through the Google network. |
| Social Media | Booking integrations across social media channels. |
| Discovery Widget | Restaurant discovery widget for surfacing bookable merchants. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Quandoo Public Partner API](openapi/quandoo-public-partner-api-openapi.yml) — 24 operations, 60 schemas, derived from the official Quandoo Swagger (api.quandoo.com/swagger.json)

### JSON Schema

- 59 schema files in [json-schema/](json-schema/), one per OpenAPI component schema.

### JSON Structure

- 59 structure files in [json-structure/](json-structure/), converted from the JSON Schema set.

### JSON-LD

- [Quandoo Context](json-ld/quandoo-context.jsonld) — linked-data context with 176 property terms and schema.org alignments.

### Examples

- 59 example payloads in [examples/](examples/), one per schema.

## Capabilities

Naftiko capabilities organized as self-contained per-surface definitions, each exposing both a REST and an MCP adapter.

| Capability | Operations | MCP Tools |
|------------|-----------|-----------|
| [Status](capabilities/quandoo-public-partner-api-status.yaml) | 1 | 1 |
| [Customers](capabilities/quandoo-public-partner-api-customers.yaml) | 3 | 3 |
| [Merchants](capabilities/quandoo-public-partner-api-merchants.yaml) | 5 | 5 |
| [Availabilities](capabilities/quandoo-public-partner-api-availabilities.yaml) | 2 | 2 |
| [Reservation Enquiries](capabilities/quandoo-public-partner-api-reservation-enquiries.yaml) | 4 | 4 |
| [Reservation Settings](capabilities/quandoo-public-partner-api-reservation-settings.yaml) | 1 | 1 |
| [Reservations](capabilities/quandoo-public-partner-api-reservations.yaml) | 3 | 3 |
| [Reservations Tags](capabilities/quandoo-public-partner-api-reservations-tags.yaml) | 1 | 1 |
| [Reviews](capabilities/quandoo-public-partner-api-reviews.yaml) | 3 | 3 |
| [Validations](capabilities/quandoo-public-partner-api-validations.yaml) | 1 | 1 |

## Vocabulary

- [Quandoo Vocabulary](vocabulary/quandoo-vocabulary.yml) — Unified taxonomy mapping 10 resources, 7 actions, 10 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Quandoo Public Partner API Spectral Rules](rules/quandoo-public-partner-api-spectral-rules.yml) — 31 rules across info, paths, operations, tags, parameters, request bodies, responses, schemas, security, HTTP method, and quality categories enforcing Quandoo API conventions.

## Plans & Cost

- [Plans & Pricing](plans/quandoo-plans-pricing.yml) — Subscription + per-cover commission model (API Commons Plans 0.1).
- [Rate Limits](rate-limits/quandoo-rate-limits.yml) — Token-scoped access, idempotency and conflict semantics (API Commons Rate Limits 0.1).
- [FinOps](finops/quandoo-finops.yml) — FOCUS-aligned billing model and meters (FinOps Framework 1.0).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
