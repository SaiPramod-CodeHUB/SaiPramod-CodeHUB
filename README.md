# Hi, I'm Sai Pramod Reddy Gopireddy

**Senior Java Backend Engineer** | Austin, TX
Distributed Systems · Kafka · Spring Boot · AWS · GenAI

🟢 **Open to Senior / Lead Backend and Full Stack roles** — Java, Spring Boot, microservices, cloud. Remote or Austin.

---

## What I Build

Backend engineer with **9 years** designing and scaling distributed systems across enterprise environments — 3 years in India, 6 in the US. I work at the intersection of **production backend engineering and AI**: reliable, high-throughput systems that are cloud-native and AI-ready.

- **Apple, 2020–2026** — microservices, Kafka pipelines, reactive APIs with Spring WebFlux, AWS infrastructure, Angular and React front ends
- Production results: **50K+ Kafka msgs/day · 99.9%+ availability · 2x API throughput · MTTR 2 hrs → 45 min**
- Owned **P0/P1 incident response and L3 production support** end to end — RCA, runbooks, post-incident reviews
- Led the **Java 17 → 21 migration** across 4+ production services with zero downtime
- Building **GenAI-backed backends** — RAG systems, LLM APIs, vector search, agentic workflows

---

## Tech Stack

| Layer | Technologies |
|---|---|
| **Languages** | Java 8/11/17/21, Python, TypeScript, SQL, Groovy |
| **Backend** | Spring Boot 3, Spring WebFlux, Project Reactor (Mono/Flux), Spring Security, Spring Data JPA, Node.js, FastAPI, Hibernate |
| **Front End** | Angular 18, RxJS, React, Redux, micro-frontends, Jest, React Testing Library, Playwright |
| **AI & GenAI** | LangChain, LangChain4j, Spring AI, ChromaDB, Pinecone, RAG pipelines, prompt engineering, MCP |
| **Messaging** | Apache Kafka, Apache Flink, Temporal, event-driven architecture, async I/O |
| **Cloud & DevOps** | AWS (Lambda, API Gateway, S3, DynamoDB, EC2/ECS, KMS, IAM, CloudWatch), GCP (Pub/Sub, BigQuery, GKE, Cloud Run), Docker, Kubernetes, Terraform, Helm |
| **Databases** | MongoDB, PostgreSQL, Oracle SQL, MySQL, Redis, Cassandra |
| **Observability** | Splunk, Zipkin, OpenTelemetry, Prometheus, Grafana, Micrometer, SonarQube |
| **CI/CD** | Jenkins, GitHub Actions, BuildKite, Spinnaker, Maven, Gradle |

---

## Featured — [ies-eligibility-platform](https://github.com/SaiPramod-CodeHUB/ies-eligibility-platform)

A **multi-jurisdiction benefits eligibility engine** in Java 21 and Spring Boot 3. The interesting part isn't the rules — it's that **nothing in the code names a state**. Three abstractions carry all the variation:

- `Jurisdiction` — the programs an agency offers, what it calls them locally, and the time zone its as-of dates resolve in
- `ThresholdProvider` — effective-dated numbers, a federal baseline with per-jurisdiction overrides
- `ProgramRuleSet` — rules resolved most-specific-wins

Onboarding a new jurisdiction is a YAML block. Code is needed only when its *rules* differ, not its numbers. Asking for a program a jurisdiction doesn't administer returns **409** rather than quietly falling back to federal rules — producing a determination for a benefit the agency cannot issue is the dangerous behaviour.

Every determination returns the rules that fired, each with a reason and a policy reference, so a caseworker can explain any outcome. The AI layer is interface-based with offline defaults, and ungrounded generated notices are rejected by a code path, not a prompt.

**77 tests. `mvn clean verify` needs no database, no broker and no API key.** Portfolio project on synthetic data.

---

## Other Projects

Portfolio projects built on synthetic data — not production systems.

| Project | Stack | What it demonstrates |
|---|---|---|
| [kafka-event-pipeline](https://github.com/SaiPramod-CodeHUB/kafka-event-pipeline) | Spring Boot · Java 21 · Kafka · Resilience4j | Zero data loss, DLQ, circuit breakers, Micrometer metrics |
| [ci-observability-dashboard](https://github.com/SaiPramod-CodeHUB/ci-observability-dashboard) | Java 21 · Spring Boot · Kafka · GraphQL | CI pipeline observability, Kafka consumer, PostgreSQL |
| [rag-document-qa](https://github.com/SaiPramod-CodeHUB/rag-document-qa) | FastAPI · LangChain · ChromaDB · Groq | RAG pipeline, similarity threshold, grounded citations, Prometheus |
| [ai-incident-triage-bot](https://github.com/SaiPramod-CodeHUB/ai-incident-triage-bot) | FastAPI · LangChain · ChromaDB · Splunk | Postmortem RAG, auto-triage on alert fire |

---

## GenAI Learning Journey

| Week | Topic | Status |
|------|-------|--------|
| Week 1–2 | LangChain basics, output parsers, memory | ✅ |
| Week 3 | Prompt engineering — few-shot, CoT, structured output | ✅ |
| Week 4 | RAG fundamentals — embeddings, chunking, retrieval quality | ✅ |
| Week 5 | Production RAG Q&A API | ✅ |
| Week 6 | AI incident triage bot — Splunk webhook integration | ✅ |
| Week 7 | Spring AI — GenAI in the Java/Spring ecosystem | ✅ |
| Week 8 | LangGraph, agents, guardrails | ⏳ |
| Week 9 | Claude Certified Architect exam prep | ⏳ |

**➡️ [View full learning journey](https://github.com/SaiPramod-CodeHUB/genai-learning)**

---

## Certifications

| Certification | Status |
|---|---|
| AI and LLM Fundamentals | ✅ Complete |
| AWS Solutions Architect Associate (SAA-C03) | 🔄 Exam scheduled — Nov 2026 |
| Anthropic Claude Certified Architect — Foundations | ⏳ In prep |

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-saipramodreddygopireddy-blue?logo=linkedin)](https://linkedin.com/in/saipramodreddygopireddy)
[![Email](https://img.shields.io/badge/Email-saipramod0310@gmail.com-red?logo=gmail)](mailto:saipramod0310@gmail.com)
