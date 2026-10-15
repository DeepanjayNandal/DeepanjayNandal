# Hi, I'm Deepanjay 👋

**Senior Software Engineer**: Backend & AI Infrastructure. 3+ years building distributed systems, event-driven pipelines, Kubernetes infrastructure, and LLM inference and retrieval systems.

I've done CVE validation work for Google's Android Security team, built Kafka pipelines processing 100k+ daily events, and a 9-layer LLM inference cache.

I work across two areas that don't usually overlap: reverse engineering and security at the systems level, and retrieval and inference infrastructure along with the Kubernetes platforms it runs on.

M.S. Computer Software Engineering, Arizona State University

---

## Featured Projects

**[BitMod: AI Inference Cache & Semantic Reuse Engine](https://github.com/DeepanjayNandal/bitmod)**

Drop-in 9-layer LLM cache proxy with semantic reuse and Bayesian evidence scoring. 76% hit rate on a 50-query benchmark (100% on repeats, 53% on rephrasings). Zero false serves across 375 held-out queries with nothing cached. 90–101x speedup at sub-90ms cached latency over self-hosted LLM calls. 1,363 tests with mypy enforced in CI.

`Python` `FastAPI` `pgvector` `Docker`

**[CaseTally: Legal Search Platform](https://github.com/DeepanjayNandal/casetally)**

Legal RAG platform over 83,706 U.S. Code chunks. Splits plain-English questions into legal issues and searches each one with hybrid PostgreSQL full-text and pgvector retrieval fused by RRF, reaching MRR 0.85 at p50 45ms (from 325ms). Runs on Kubernetes, with KEDA scaling the embedding workers from 0 to 3 on queue depth and zero lost or duplicated work under SIGKILL (3,000/3,000 rows).

`Python` `FastAPI` `PostgreSQL` `pgvector` `Kubernetes` `KEDA`

**[WeVibe: Real-Time Matchmaking Platform](https://github.com/DeepanjayNandal/weVibe-app)**

Real-time iOS dating platform backend built for Appy.yo. Socket.IO and Redis pub/sub for horizontally scalable event delivery, PostGIS geo-filtering, and Gemini AI bio generation on Google Cloud Run.

`Node.js` `TypeScript` `PostgreSQL` `Socket.IO` `Redis` `Google Cloud Run`

**[Elastic Face Recognition](https://github.com/DeepanjayNandal/elastic-face-recognition)**

Cloud and edge ML pipeline across EC2 autoscaling, serverless Lambda, and Greengrass edge inference. Custom SQS queue-depth autoscaler across 15 EC2 instances at 0.96s average latency under 100 concurrent requests, with an edge tier short-circuiting no-face cases and cutting response time 2.3x to 776ms.

`Python` `AWS EC2` `Lambda` `SQS` `IoT Greengrass`

---

## Work

**Discover Excellence**, Software Engineer (Contract). Kafka pipeline processing 100k+ daily behavioral events at sub-40ms p95. Redis personalization layer and fault-tolerant BullMQ job pipeline for an AI eCommerce analytics platform.

**Appy.yo**, Backend Engineer, ASU Capstone. Industry-sponsored capstone delivering the production backend for WeVibe, a real-time iOS matchmaking platform. Built end-to-end with the sponsor across two-week sprints, translating evolving product requirements into a shipped platform.

**Ittiam Systems**, Senior Software Engineer. CVE validation for Google's Android Security team. 50+ security tests authored and merged into AOSP. Used Ghidra and Frida to reach vulnerable code standard testing couldn't.

---

## Connect

[Portfolio](https://deepanjay-dev.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/deepanjay-nandal/) · deepanjay.nandal12@gmail.com
