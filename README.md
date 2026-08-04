# Fleetio (fleetio)

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

Fleetio is a cloud-based fleet management software platform that helps organizations track and manage vehicles, equipment, maintenance, fuel, parts, and inspections. The Fleetio Developer API is a JSON REST API at https://secure.fleetio.com/api for managing vehicles, contacts, fuel entries, service entries, work orders, parts, inspections, and issues, with webhooks for event notifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fleetio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fleetio/refs/heads/main/apis.yml)

## Tags

- Fleet Management
- Vehicles
- Maintenance
- Telematics
- SaaS

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Fleetio Vehicles API

Create, read, update, and archive fleet vehicles and assets, including make, model, year, VIN, license plate, group assignment, status, and meter data.

- **Human URL:** [https://developer.fleetio.com/docs/api/vehicles](https://developer.fleetio.com/docs/api/vehicles)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Vehicles
- Assets
- Equipment

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/vehicles)
- [API Reference](https://developer.fleetio.com/docs/api/fleetio-developer-api)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Contacts API

Manage people associated with the fleet - operators, technicians, and employees - with names, contact details, permissions, and group membership.

- **Human URL:** [https://developer.fleetio.com/docs/api/contacts](https://developer.fleetio.com/docs/api/contacts)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Contacts
- Operators
- Technicians

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/contacts)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Fuel Entries API

Record and retrieve fuel purchases per vehicle, including volume, cost, fuel economy, meter readings, and vendor, for fuel and cost tracking.

- **Human URL:** [https://developer.fleetio.com/docs/api/fuel-entries](https://developer.fleetio.com/docs/api/fuel-entries)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Fuel
- Fuel Entries
- Costs

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/fuel-entries)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Service & Work Orders API

Manage maintenance - service entries (completed work and costs), work orders (planned and in-progress repairs with line items), and service reminders driven by time or meter intervals.

- **Human URL:** [https://developer.fleetio.com/docs/api/work-orders](https://developer.fleetio.com/docs/api/work-orders)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Service Entries
- Work Orders
- Service Reminders
- Maintenance

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/service-entries)
- [Documentation](https://developer.fleetio.com/docs/api/work-orders)
- [Documentation](https://developer.fleetio.com/docs/api/service-reminders)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Parts & Inventory API

Manage the parts catalog and stock levels across locations, with part details, costs, and inventory journal entries tracking quantity movements.

- **Human URL:** [https://developer.fleetio.com/docs/api/parts](https://developer.fleetio.com/docs/api/parts)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Parts
- Inventory
- Inventory Journal Entries

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/parts)
- [Documentation](https://developer.fleetio.com/docs/api/inventory-journal-entries)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Inspections API

Access inspection forms and submitted inspection results (including DVIR-style checks), with item responses, pass/fail status, and any failures that generate issues.

- **Human URL:** [https://developer.fleetio.com/docs/api/inspection-forms](https://developer.fleetio.com/docs/api/inspection-forms)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Inspections
- Inspection Forms
- DVIR

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/inspection-forms)
- [Documentation](https://developer.fleetio.com/docs/api/submitted-inspection-forms)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Issues API

Track vehicle issues and defects reported by operators or surfaced by inspections, with status, assignment, and resolution into work orders or service entries.

- **Human URL:** [https://developer.fleetio.com/docs/api/issues](https://developer.fleetio.com/docs/api/issues)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Issues
- Defects
- Faults

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/issues)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetio Webhooks API

Register webhook endpoints to receive event notifications when records such as vehicles, service entries, work orders, and issues are created or updated.

- **Human URL:** [https://developer.fleetio.com/docs/api/webhooks](https://developer.fleetio.com/docs/api/webhooks)
- **Base URL:** `https://secure.fleetio.com/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developer.fleetio.com/docs/api/webhooks)
- [OpenAPI](openapi/fleetio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/fleetio)
- [LinkedIn](https://www.linkedin.com/company/fleetio)
- [Website](https://www.fleetio.com)
- [Documentation](https://developer.fleetio.com/docs/overview/quick-start)
- [Plans](plans/fleetio-plans-pricing.yml)
- [Rate Limits](rate-limits/fleetio-rate-limits.yml)
- [Fin Ops](finops/fleetio-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
