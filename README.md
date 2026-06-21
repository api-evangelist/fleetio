# Fleetio (fleetio)

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
