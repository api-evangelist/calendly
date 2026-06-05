# Calendly (calendly)

Calendly is a scheduling automation platform that helps individuals, teams, and organizations automate the meeting lifecycle by removing the back-and-forth of scheduling. Their developer platform provides APIs for programmatically managing scheduling workflows, receiving real-time event notifications via webhooks, and embedding scheduling interfaces directly into third-party applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/calendly/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Appointments
- Automation
- Booking
- Calendars
- Meetings
- Scheduling

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-19

## APIs

### Calendly Scheduling API

The Calendly Scheduling API (v2) is a RESTful API that allows developers to programmatically manage scheduling workflows. It provides endpoints for managing users, organizations, event types, scheduled events, invitees, and routing forms. The API uses JSON for request and response bodies, standard HTTP methods, and supports authentication via personal access tokens and OAuth 2.1.

- **Human URL:** [https://developer.calendly.com/api-docs](https://developer.calendly.com/api-docs)
- **Base URL:** `https://api.calendly.com`

#### Tags

- Appointments
- Automation
- Booking
- Calendars
- Meetings
- Scheduling

#### Properties

- [Documentation](https://developer.calendly.com/api-docs)
- [OpenAPI](openapi/calendly-scheduling-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/calendly-scheduling-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/calendly-scheduling-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Calendly Webhook API

The Calendly Webhook API enables developers to receive real-time notifications when scheduling events occur in Calendly. By creating webhook subscriptions, applications can automatically receive data whenever invitees schedule, cancel, or reschedule meetings. This eliminates the need for polling the API and allows for event-driven integrations that respond immediately to changes in scheduling activity.

- **Human URL:** [https://developer.calendly.com/api-docs](https://developer.calendly.com/api-docs)
- **Base URL:** `https://api.calendly.com`

#### Tags

- Events
- Notifications
- Scheduling
- Webhooks

#### Properties

- [Documentation](https://developer.calendly.com/api-docs)
- [AsyncAPI](asyncapi/calendly-webhook-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/calendly-scheduling-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/calendly-scheduling-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Calendly Embed API

The Calendly Embed API allows developers to integrate Calendly scheduling pages directly into their websites and applications. It supports inline embeds, popup widgets, and popup text options, giving developers flexibility in how they present scheduling interfaces to users. The Embed API enables customization of the embedded experience and provides JavaScript callbacks for tracking when events are scheduled, allowing seamless integration of Calendly booking flows within third-party applications.

- **Human URL:** [https://developer.calendly.com/](https://developer.calendly.com/)
- **Base URL:** `https://api.example.com`

#### Tags

- Embedding
- Scheduling
- Web Components
- Widgets

#### Properties

- [Documentation](https://developer.calendly.com/)
- [Postman Collection](collections/calendly-scheduling-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/calendly-scheduling-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/calendly)
- [LinkedIn](https://www.linkedin.com/company/calendly)
- [Portal](https://developer.calendly.com/)
- [Documentation](https://developer.calendly.com/api-docs)
- [Website](https://calendly.com/)
- [Privacy Policy](https://calendly.com/privacy)
- [Terms of Service](https://calendly.com/terms)
- [Blog](https://calendly.com/blog)
- [Login](https://calendly.com/login)
- [JSON-LD](json-ld/calendly-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/calendly-event-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/calendly-scheduled-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/calendly-invitee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [L L Ms Txt](https://developer.calendly.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
