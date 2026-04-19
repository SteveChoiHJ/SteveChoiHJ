<!--
==========================================================================
GitHub Profile README — English (single-language version)
==========================================================================
Upload this file as `README.md` in a public repo whose name is identical
to your GitHub username. HTML comments are not rendered.

Pattern:
- Primary language: English
- A Korean version can be added later as README.ko.md and linked from here
  if/when needed, but this file is kept English-only for a consistent tone.
==========================================================================
-->

# Hi, I'm Steve Choi · Aloha, Welcome Aboard 👋

> **A 13-year backend engineer transitioning from secure server development into hybrid-cloud platform engineering.**
> I've built enterprise security services — interfaces, batch jobs, and SaaS microservices —
> and I'm now leading my own platform-redesign work and AI-assisted backend development.
>> 🇰🇷 한국어 커리어 노트는 [CAREER.ko.md](./CAREER.ko.md) 를 참고해 주세요.

---

## 🧭 What I'm focused on right now

- **High-volume log platform redesign** — shifting a single-RDB backend's query load onto an Elasticsearch / OpenSearch + object-storage tiered model.
- **Kubernetes platform engineering** — multi-tenancy, observability (Prometheus / Grafana / OpenTelemetry), GitOps (ArgoCD), IaC (Terraform).
- **AI in the backend** — anomaly detection on security logs, ops-assistant LLM agents, RAG-based knowledge retrieval.
- **From passive to active, from avoidance to accountability, from tasked work to designing and building** — a **step-up engineer** who leaves architecture and decision records (ADRs) behind.

> *Currently exploring — log-platform redesign (RDB → Elasticsearch + object-storage tiering); Kubernetes platform engineering (multi-tenancy, observability, GitOps, IaC); applied AI in the backend (anomaly detection, ops LLM agents, RAG); and the shift from "tasked" to "designing and deciding" — an engineer who leaves ADRs behind.*

<!-- Keep this section focused on the "why" behind each topic rather than a list of buzzwords. -->

---

## 🧩 Career Timeline

<!-- Replace years with real transition dates if any differ. Parallel roles are split into separate rows. -->

| Period | Role | Stack | One-line summary |
|---|---|---|---|
| 2014–2015 (2y) | Java developer on an external project | Java, server-side batch | Kicked off my career building and maintaining enterprise batch systems |
| 2016 (1y) | Internal development & security training | — | Completed in-house dev and infosec training; pivoted into the security domain |
| 2017–2018 (2y) | Security backend engineer (interface / DB) | **C++**, MS-SQL | Designed and operated cross-system interfaces and database layers |
| 2019–2021 (3y) | Security backend engineer | **Java, Spring** | Designed and built features for enterprise security services |
| 2022 (1y) | Project Lead · GDC engagement | Project leadership, distributed delivery | Led a Global Development Center (GDC) partner team — requirements, quality, delivery |
| 2021–2023 (3y, parallel) | Network engineering exposure | **TCP/IP, UDP, Wireshark** | Packet-level analysis and network-interface debugging |
| 2023–present (3.5y) | Cloud · microservices engineer | **Java, Spring Boot / Security, MySQL, Kubernetes** | SaaS cloud development plus operational engineering |

### What this journey gave me

- **Domain depth** — instincts shaped by years of operating security services: incident response, audit logging, and compliance.
- **Cross-team delivery** — from local teams to leading a Global Development Center (GDC) partner, translating requirements across culture and language.
- **Layer breadth** — problems solved from DB → server → network → container orchestration, end to end.

---

## 🛠️ Tech Stack

<!-- A three-tier grouping separates "used it" from "can design with it." -->

**Deep** — *own the design and the problem*
`Java` · `Spring / Spring Boot` · `MySQL` · `MS-SQL` · `REST APIs` · `Server-side batch` · `Incident analysis / RCA` · `Secure backend development`

**Working** — *production operations & maintenance experience*
`Kubernetes` · `C++` · `Linux` · `HTTP/HTTPS` · `Microservices` · `Wireshark` · `TCP/IP` · `Git / GitHub`

**Learning** — *actively studying or piloting*
`Elasticsearch / OpenSearch` · `Hadoop / Spark` · `Observability (Prometheus, Grafana, OpenTelemetry)` · `Terraform · ArgoCD` · `MLOps · Applied LLMs` · `Hybrid Cloud (AWS)` · `Python automation`

---

## 🔬 PoCs in Progress

### 1. (WIP) High-volume Log Platform Redesign
- **Problem** — Query load and latency spikes when the web layer reads logs that accumulate in a single MySQL backend.
- **Approach** — Benchmark four options against the same query set: (a) MySQL partition tuning, (b) Elasticsearch alone, (c) Hadoop alone, (d) Elasticsearch + object-storage tiering.
- **Will publish** — p95 query latency, storage cost, indexing failure rate, and operational complexity, captured as ADRs (Architecture Decision Records).
- **Repo** — shared as disclosure permits: [repo-link-TBD]

### 2. (TBD) Observability Full-Stack Reference
A Spring Boot sample wired with RED metrics, structured logging, and distributed tracing — all in one place as a reference setup.

### 3. (TBD) Security-first GitOps Pipeline
Rebuilding a "developer pipeline" from an "operator and auditor" perspective — ArgoCD + Sigstore/Cosign + Trivy + OIDC-based, secret-less deployment.

---

## 🧱 What I Aim For

- **Driven engineering** — framing the problem, comparing alternatives, and writing the decision down.
- **Working at the edges** — being accountable at the intersection of security, infrastructure, and data.
- **The aesthetics of automation** — script it once, pipeline it twice, platform it when it's structural.

---

## 📫 Contact

- **Email**: [hj.steve.choi@gmail.com]
- **LinkedIn**: [LinkedIn URL]
- **Blog / Notion**: [URL]

<!-- If a public email feels exposed, use GitHub's private email option or keep it on the resume only. -->

---

<sub>This profile is a living document — numbers and links will be replaced as experience and results accumulate. · Last updated: 2026-04-19</sub>
