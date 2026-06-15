# Milvus (milvus)

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
