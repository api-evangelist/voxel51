# Voxel51 (voxel51)

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
