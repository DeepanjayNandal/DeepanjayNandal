# Hi, I'm Deepanjay 👋

**Senior Software Engineer** — Backend & AI Infrastructure. 3+ years building distributed systems, event-driven pipelines, and LLM inference and retrieval systems.

I've built CVE validation infrastructure for Google's Android Security team, Kafka pipelines processing 100k+ daily events, and a 9-layer LLM inference cache.

I work across two areas that don't usually overlap: reverse engineering and security at the systems level, and retrieval and inference infrastructure.

M.S. Computer Software Engineering — Arizona State University

---

## Featured Projects

**[BitMod — AI Inference Cache & Semantic Reuse Engine](https://github.com/DeepanjayNandal/bitmod)**

Drop-in 9-layer LLM cache proxy with semantic reuse and Bayesian evidence scoring. 76% hit rate on a 50-query benchmark (100% on repeats, 53% on rephrasings). Zero false serves across 375 held-out queries with nothing cached. 90–101x speedup at sub-90ms cached latency over self-hosted LLM calls. 1,363 tests with mypy enforced in CI.

`Python` `FastAPI` `pgvector` `Docker`

**[CaseTally — Legal Search Platform](https://github.com/DeepanjayNandal/casetally)**

Hybrid legal RAG platform over 83,706 U.S. Code chunks using PostgreSQL full-text search and HNSW-indexed pgvector, with LLM query rewriting improving MRR by 10%. Retrieval at p50 18ms and p95 36ms without rewriting, measured by a Precision@3 / Recall@5 / MRR evaluation harness.

`Python` `FastAPI` `PostgreSQL` `pgvector` `Full-Text Search`

**[WeVibe — Real-Time Matchmaking Platform](https://github.com/DeepanjayNandal/weVibe-app)**

Real-time iOS dating platform backend built for Appy.yo. Socket.IO and Redis pub/sub for horizontally scalable event delivery, PostGIS geo-filtering, and Gemini AI bio generation on Google Cloud Run.

`Node.js` `TypeScript` `PostgreSQL` `Socket.IO` `Redis` `Google Cloud Run`

**[Elastic Face Recognition](https://github.com/DeepanjayNandal/elastic-face-recognition)**

Cloud and edge ML pipeline across EC2 autoscaling, serverless Lambda, and Greengrass edge inference. Custom SQS queue-depth autoscaler across 15 EC2 instances at 0.96s average latency under 100 concurrent requests, with an edge tier short-circuiting no-face cases and cutting response time 2.3x to 776ms.

`Python` `AWS EC2` `Lambda` `SQS` `IoT Greengrass`

---

## Work

**Ittiam Systems** — Senior Software Engineer. CVE validation infrastructure for Google's Android Security team. 50+ security tests authored and merged into AOSP. Pioneered Ghidra-based binary analysis approach adopted team-wide.

**Discover Excellence** — Software Engineer (Contract). Kafka pipeline processing 100k+ daily behavioral events at sub-40ms p95. Redis personalization layer and fault-tolerant BullMQ job pipeline for an AI eCommerce analytics platform.

**Appy.yo** — Backend Engineer, ASU Capstone. Industry-sponsored capstone delivering the production backend for WeVibe, a real-time iOS matchmaking platform. Built end-to-end with the sponsor across two-week sprints, translating evolving product requirements into a shipped platform.

---

## Connect

[Portfolio](https://deepanjay-dev.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/deepanjay-nandal/) · deepanjay.nandal12@gmail.com
