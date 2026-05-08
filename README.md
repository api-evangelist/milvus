# Milvus (milvus)

Milvus is an Apache 2.0 open-source vector database. It exposes a versioned REST API alongside gRPC and language SDKs (Python, Go, Java, Node.js). Maintained by Zilliz; LF AI & Data Foundation graduated project.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/milvus/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=milvus-api-evangelist&utm_content=repo)

## Type
- **x-type:** opensource

## APIs
- **Milvus REST API v2** - `/v2/vectordb` on port 19530. Collections, partitions, vectors, search, query, indexes, RBAC.
- **Milvus gRPC API** - Canonical high-throughput interface on the same host:port; SDKs are gRPC-based.

## Tags
- Vector Database, AI, Embeddings, Open Source, Cloud-Native

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://milvus.io/)
- [Documentation](https://milvus.io/docs/)
- [Source (Apache 2.0)](https://github.com/milvus-io/milvus)
- [LF AI & Data Foundation](https://lfaidata.foundation/projects/milvus/)
- [Commercial Cloud: Zilliz](https://zilliz.com/)
- [Plans](plans/milvus-plans-pricing.yml)
- [RateLimits](rate-limits/milvus-rate-limits.yml)
- [FinOps](finops/milvus-finops.yml)

## Notes
- FOSS, no commercial API surface — see Zilliz Cloud for managed offering.
- Auth is off by default in self-hosted dev; enable via Bearer `username:password` token.
- v1 REST endpoints exist but are deprecated — use v2.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
