# Keen (keen)
Keen is an event analytics platform and API that enables developers to collect, store, analyze, and visualize custom event data. It provides a flexible RESTful API for streaming events, running multi-dimensional queries, and building embedded analytics dashboards for products and internal tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/keen/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Analytics, Event Analytics, Custom Events, Data Collection, Embedded Analytics

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-28

## APIs

### Keen Event Collection API
The Keen Event Collection API enables developers to send individual or batched events to Keen for storage and analysis. Each event is a JSON object that can contain any arbitrary properties, giving developers full flexibility in defining their data model. The API supports single event recording, multi-event uploads across collections, and inspection of existing collections and properties.

**Human URL:** [https://keen.io/docs/api/#record-a-single-event](https://keen.io/docs/api/#record-a-single-event)

#### Tags:

 - Analytics, Data Collection, Events, Ingestion

#### Properties

- [Documentation](https://keen.io/docs/api/#record-a-single-event)
- [OpenAPI](openapi/keen-event-collection-api-openapi.yml)

### Keen Query API
The Keen Query API provides a comprehensive set of analytical query types including count, sum, average, minimum, maximum, percentile, median, count unique, select unique, funnel, and multi-analysis. Queries support filters, time frames, intervals, group-by, and time zone parameters for flexible multi-dimensional analysis of event data.

**Human URL:** [https://keen.io/docs/api/#analyses](https://keen.io/docs/api/#analyses)

#### Tags:

 - Analytics, Queries, Aggregation, Reporting

#### Properties

- [Documentation](https://keen.io/docs/api/#analyses)
- [OpenAPI](openapi/keen-query-api-openapi.yml)

### Keen Cached Queries API
The Keen Cached Queries API allows developers to create, manage, and retrieve pre-defined queries that are automatically refreshed on a schedule. Cached queries improve performance for frequently accessed analytics by storing pre-computed results, making them ideal for powering dashboards and embedded analytics experiences.

**Human URL:** [https://keen.io/docs/api/#cached-queries](https://keen.io/docs/api/#cached-queries)

#### Tags:

 - Analytics, Queries, Caching, Performance

#### Properties

- [Documentation](https://keen.io/docs/api/#cached-queries)
- [OpenAPI](openapi/keen-cached-queries-api-openapi.yml)

### Keen Saved Queries API
The Keen Saved Queries API enables developers to create and manage reusable query definitions. Saved queries store query parameters as named resources that can be retrieved and executed later, enabling consistent analytics across applications and simplifying the management of complex query configurations.

**Human URL:** [https://keen.io/docs/api/#saved-queries](https://keen.io/docs/api/#saved-queries)

#### Tags:

 - Analytics, Queries, Saved Queries

#### Properties

- [Documentation](https://keen.io/docs/api/#saved-queries)
- [OpenAPI](openapi/keen-saved-queries-api-openapi.yml)

### Keen Data Extraction API
The Keen Data Extraction API enables developers to retrieve raw event data from event collections. It supports filtering, sorting, and pagination of event records and is useful for exporting data for external analysis, auditing, or feeding data into other systems and processing pipelines.

**Human URL:** [https://keen.io/docs/api/#extractions](https://keen.io/docs/api/#extractions)

#### Tags:

 - Analytics, Events, Data, Export

#### Properties

- [Documentation](https://keen.io/docs/api/#extractions)
- [OpenAPI](openapi/keen-data-extraction-api-openapi.yml)

## Common Properties

- [Website](https://keen.io)
- [Documentation](https://keen.io/docs)
- [APIDocumentation](https://keen.io/docs/api)
- [GettingStarted](https://keen.io/docs/getting-started)
- [Blog](https://keen.io/blog)
- [Pricing](https://keen.io/pricing)
- [GitHub](https://github.com/keen)
- [Login](https://keen.io/login)
- [Signup](https://keen.io/signup)
- [Support](https://keen.io/support)
- [SDKs](https://keen.io/docs/sdks)
- [StatusPage](https://status.keen.io)
- [TermsOfService](https://keen.io/terms-of-service)
- [PrivacyPolicy](https://keen.io/privacy-policy)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
