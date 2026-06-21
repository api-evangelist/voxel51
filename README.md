# Voxel51 (voxel51)

Voxel51 builds FiftyOne, the open-source toolkit for building high-quality computer-vision and multimodal datasets and models. FiftyOne's primary interface is a Python SDK (datasets, samples, views, and the FiftyOne App) rather than a broad public REST API. FiftyOne Enterprise adds a Management SDK and an authenticated API connection that lets the SDK operate over the network instead of a direct database connection.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/voxel51/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/voxel51/refs/heads/main/apis.yml)

## Tags

- AI
- Computer Vision
- Datasets
- Machine Learning
- Python SDK

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### FiftyOne SDK (Python)

The open-source FiftyOne Python SDK is the primary interface for building and curating visual AI datasets - creating Datasets and Samples, slicing data with Views and aggregations, computing embeddings and similarity, running evaluations, and launching the interactive FiftyOne App. Distributed via pip (Apache-2.0); it is a Python library, not a remote REST API.

- **Human URL:** [https://docs.voxel51.com/api/fiftyone.html](https://docs.voxel51.com/api/fiftyone.html)

#### Tags

- Python SDK
- Datasets
- Computer Vision
- Open Source

#### Properties

- [Documentation](https://docs.voxel51.com/)
- [API Reference](https://docs.voxel51.com/api/fiftyone.html)
- [OpenAPI](openapi/voxel51-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/voxel51/fiftyone)
- [Postman Collection](collections/voxel51.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voxel51.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FiftyOne Enterprise Management SDK / API

FiftyOne Enterprise (formerly Teams) adds the fiftyone.management Python module for administering users, service accounts, API keys, dataset permissions, user groups, and cloud credentials. It operates over an authenticated API connection (FIFTYONE_API_URI + FIFTYONE_API_KEY) so SDK calls run against the central FiftyOne Enterprise API rather than a direct MongoDB connection. The wire protocol is an internal GraphQL/orchestration surface consumed by the SDK; Voxel51 does not publish a general-purpose public REST API contract.

- **Human URL:** [https://docs.voxel51.com/enterprise/management_sdk.html](https://docs.voxel51.com/enterprise/management_sdk.html)

#### Tags

- Enterprise
- Management SDK
- API Connection
- Administration

#### Properties

- [Documentation](https://docs.voxel51.com/enterprise/management_sdk.html)
- [API Reference](https://docs.voxel51.com/enterprise/api_connection.html)
- [OpenAPI](openapi/voxel51-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/voxel51/fiftyone)
- [Postman Collection](collections/voxel51.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voxel51.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FiftyOne Plugins & Operators

The plugin and operator framework extends FiftyOne with custom Python (and JavaScript/React) functionality - new App panels, operators, and integrations that run inside the FiftyOne App and SDK. Plugins are authored against the FiftyOne Python/JS APIs and registered with the local or Enterprise deployment; they are not exposed as a standalone public HTTP API.

- **Human URL:** [https://docs.voxel51.com/plugins/index.html](https://docs.voxel51.com/plugins/index.html)

#### Tags

- Plugins
- Operators
- Extensibility
- Python SDK

#### Properties

- [Documentation](https://docs.voxel51.com/plugins/index.html)
- [API Reference](https://docs.voxel51.com/plugins/developing_plugins.html)
- [OpenAPI](openapi/voxel51-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub](https://github.com/voxel51/fiftyone-plugins)
- [Postman Collection](collections/voxel51.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/voxel51.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/voxel51)
- [LinkedIn](https://www.linkedin.com/company/voxel51)
- [Website](https://voxel51.com)
- [Documentation](https://docs.voxel51.com)
- [Plans](plans/voxel51-plans-pricing.yml)
- [Rate Limits](rate-limits/voxel51-rate-limits.yml)
- [Fin Ops](finops/voxel51-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
