---
title: "How Force Merge Compaction Nearly Doubled Milvus Search QPS"
url: "https://milvus.io/blog/force-merge-compaction-milvus-qps.md"
date: "2026-07-01"
author: "Zilliz / Milvus"
feed_url: "https://milvus.io/blog"
---
Force Merge Compaction is a Milvus feature that consolidates small sealed segments into larger ones, significantly improving search performance for static, read-heavy collections. In a controlled experiment with 1 million 768-dimensional vectors, the technique raised search QPS from about 3,000 to about 5,600-6,000.
