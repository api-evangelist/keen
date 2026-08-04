# Keen (keen)

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

Keen is an event analytics platform and API that enables developers to collect, store, analyze, and visualize custom event data. It provides a flexible RESTful API for streaming events, running multi-dimensional queries, and building embedded analytics dashboards for products and internal tools.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Custom Events
- Data Collection
- Embedded Analytics
- Event Analytics

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Keen Event Collection API

The Keen Event Collection API enables developers to send individual or batched events to Keen for storage and analysis. Each event is a JSON object that can contain any arbitrary properties, giving developers full flexibility in defining their data model. The API supports single event recording, multi-event uploads across collections, and inspection of existing collections and properties.

- **Human URL:** [https://keen.io/docs/api/#record-a-single-event](https://keen.io/docs/api/#record-a-single-event)

#### Tags

- Analytics
- Data Collection
- Events
- Ingestion

#### Properties

- [Documentation](https://keen.io/docs/api/#record-a-single-event)
- [OpenAPI](openapi/keen-event-collection-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keen-event-collection-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keen-event-collection-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keen Query API

The Keen Query API provides a comprehensive set of analytical query types including count, sum, average, minimum, maximum, percentile, median, count unique, select unique, funnel, and multi-analysis. Queries support filters, time frames, intervals, group-by, and time zone parameters for flexible multi-dimensional analysis of event data.

- **Human URL:** [https://keen.io/docs/api/#analyses](https://keen.io/docs/api/#analyses)

#### Tags

- Aggregation
- Analytics
- Queries
- Reporting

#### Properties

- [Documentation](https://keen.io/docs/api/#analyses)
- [OpenAPI](openapi/keen-query-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keen-query-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keen-query-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keen Cached Queries API

The Keen Cached Queries API allows developers to create, manage, and retrieve pre-defined queries that are automatically refreshed on a schedule. Cached queries improve performance for frequently accessed analytics by storing pre-computed results, making them ideal for powering dashboards and embedded analytics experiences.

- **Human URL:** [https://keen.io/docs/api/#cached-queries](https://keen.io/docs/api/#cached-queries)

#### Tags

- Analytics
- Caching
- Performance
- Queries

#### Properties

- [Documentation](https://keen.io/docs/api/#cached-queries)
- [OpenAPI](openapi/keen-cached-queries-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keen-cached-queries-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keen-cached-queries-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keen Saved Queries API

The Keen Saved Queries API enables developers to create and manage reusable query definitions. Saved queries store query parameters as named resources that can be retrieved and executed later, enabling consistent analytics across applications and simplifying the management of complex query configurations.

- **Human URL:** [https://keen.io/docs/api/#saved-queries](https://keen.io/docs/api/#saved-queries)

#### Tags

- Analytics
- Queries
- Saved Queries

#### Properties

- [Documentation](https://keen.io/docs/api/#saved-queries)
- [OpenAPI](openapi/keen-saved-queries-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keen-saved-queries-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keen-saved-queries-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keen Data Extraction API

The Keen Data Extraction API enables developers to retrieve raw event data from event collections. It supports filtering, sorting, and pagination of event records and is useful for exporting data for external analysis, auditing, or feeding data into other systems and processing pipelines.

- **Human URL:** [https://keen.io/docs/api/#extractions](https://keen.io/docs/api/#extractions)

#### Tags

- Analytics
- Data
- Events
- Export

#### Properties

- [Documentation](https://keen.io/docs/api/#extractions)
- [OpenAPI](openapi/keen-data-extraction-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keen-data-extraction-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keen-data-extraction-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/keen-io)
- [Website](https://keen.io)
- [Documentation](https://keen.io/docs)
- [A P I Documentation](https://keen.io/docs/api)
- [Getting Started](https://keen.io/docs/getting-started)
- [Blog](https://keen.io/blog)
- [Pricing](https://keen.io/pricing)
- [Git Hub](https://github.com/keen)
- [Login](https://keen.io/login)
- [Sign Up](https://keen.io/signup)
- [Support](https://keen.io/support)
- [S D Ks](https://keen.io/docs/sdks)
- [Status Page](https://status.keen.io)
- [Terms of Service](https://keen.io/terms-of-service)
- [Privacy Policy](https://keen.io/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
