# Milvus (milvus)

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

Milvus is an Apache 2.0 open-source vector database. It exposes a versioned REST API alongside gRPC and language SDKs (Python, Go, Java, Node.js). Maintained by Zilliz; LF AI & Data Foundation graduated project.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/milvus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/milvus/refs/heads/main/apis.yml)

## Tags

- Vector Database
- AI
- Embeddings
- Open Source
- Cloud-Native

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Milvus REST API v2

Milvus v2 REST API covers collections, partitions, vectors, search, query, indexes, and role/RBAC management. Authentication: Bearer token formed from `username:password` when auth is enabled (off by default in self-hosted dev).

- **Human URL:** [https://milvus.io/api-reference/restful/v2.5.x/About.md](https://milvus.io/api-reference/restful/v2.5.x/About.md)
- **Base URL:** `http://{milvus_host}:19530/v2/vectordb`

#### Tags

- REST
- Collections
- Vectors
- Index
- Partitions

#### Properties

- [Documentation](https://milvus.io/api-reference/restful/v2.5.x/About.md)
- [Authentication](https://milvus.io/api-reference/restful/v2.5.x/About.md)
- [SDK](https://github.com/milvus-io/pymilvus)
- [SDK](https://github.com/milvus-io/milvus-sdk-go)
- [SDK](https://github.com/milvus-io/milvus-sdk-java)
- [SDK](https://github.com/milvus-io/milvus-sdk-node)
- [Postman Collection](collections/milvus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/milvus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Milvus gRPC API

gRPC is the canonical, high-throughput interface to Milvus. The official SDKs are gRPC-based; the REST API is a thin wrapper for non-Go/Python/Java clients.

- **Human URL:** [https://milvus.io/docs/grpc.md](https://milvus.io/docs/grpc.md)
- **Base URL:** `grpc://{milvus_host}:19530`

#### Tags

- gRPC
- High Throughput

#### Properties

- [Documentation](https://milvus.io/docs/)
- [Postman Collection](collections/milvus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/milvus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/the-milvus-project)
- [Website](https://milvus.io/)
- [Portal](https://milvus.io/docs/)
- [Source Code](https://github.com/milvus-io/milvus)
- [Foundation](https://lfaidata.foundation/projects/milvus/)
- [Commercial Offering](https://zilliz.com/)
- [Plans](plans/milvus-plans-pricing.yml)
- [Rate Limits](rate-limits/milvus-rate-limits.yml)
- [Fin Ops](finops/milvus-finops.yml)
- [L L Ms Txt](https://milvus.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
