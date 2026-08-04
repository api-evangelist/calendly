# Calendly (calendly)

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
