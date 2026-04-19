
# Steve Choi · 한국어 커리어 노트

> **보안 서버 개발에서 출발해, 하이브리드 클라우드 플랫폼 엔지니어링으로 시야를 넓히는 중인 13년차 개발자입니다.**
> 엔터프라이즈 보안 서비스의 인터페이스·배치·마이크로서비스를 만들어 왔고,
> 지금은 플랫폼 개선 설계와 AI를 활용한 백엔드 고도화를 주도해 보고 있습니다.

영문 메인 프로필은 [README.md](./README.md) 에 있습니다. 이 문서는 한국어 독자를 위한 상세 보조 노트입니다.

---

## 🧭 지금의 관심사

- **대용량 로그 플랫폼 개선 설계** — RDB 단일 저장 구조의 부하를 Elasticsearch / OpenSearch + Object Storage 계층화 전환
- **쿠버네티스 기반 플랫폼 엔지니어링** — 멀티테넌시, Observability(Prometheus / Grafana / OpenTelemetry), GitOps(ArgoCD), IaC(Terraform)
- **AI를 활용한 백엔드 설계** — 보안 로그 이상 탐지, 운영 지원형 LLM 에이전트, RAG 기반 지식 검색
- **수동에서 "능동"으로, 회피보단 "책임"으로, "설계"하는 일로, "구현"하는 일로** — 아키텍처와 의사결정 기록(ADR)을 남기는 STEP UP 엔지니어

---

## 🧩 커리어 타임라인

| 기간 | 역할 | 주요 기술 | 한 줄 요약 |
|---|---|---|---|
| 2014–2015 (2년) | 외부 프로젝트 Java 개발자 | Java, 서버 배치 | 엔터프라이즈 배치 시스템 개발·운영 유지보수 |
| 2016 (1년) | 개발·보안 교육 과정 | — | 사내 개발 역량 + 정보보안 교육 이수, 보안 도메인 전환 |
| 2017–2018 (2년) | 보안 서버 개발자 (인터페이스·DB) | **C++**, MS-SQL | 시스템 인터페이스·데이터베이스 설계·운영 |
| 2019–2021 (3년) | 보안 서버 개발자 | **Java, Spring** | 보안 서비스 백엔드 기능 설계·개발 |
| 2022 (1년) | PL · GDC 리딩 | 프로젝트 관리, 원격 협업 | Global Development Center(GDC) 협력사 리딩, 요구사항 전달·품질 관리 |
| 2021–2023 (3년, 병행) | 네트워크 개발 경험 | **TCP/IP, UDP, Wireshark** | 패킷 레벨 분석·네트워크 인터페이스 디버깅 |
| 2023–현재 (3.5년) | Cloud · 마이크로서비스 엔지니어 | **Java, Spring Boot / Security, MySQL, Kubernetes** | SaaS Cloud 개발 + 운영 엔지니어링 |

### 이 여정에서 얻은 것

- **도메인 깊이** — 보안 서비스 운영에서 쌓인 장애 대응·감사 로그·컴플라이언스 감각
- **협업 범위** — 국내 팀 개발부터 GDC(Global Development Center) 리딩까지, 요구사항을 다른 문화·언어로 전달하는 경험
- **레이어 넓이** — DB → 서버 → 네트워크 → 컨테이너 오케스트레이션까지 전 레이어의 문제를 본 경험

---

## 🛠️ 기술 스택

**Deep — 설계·문제해결 주도 가능**
`Java` · `Spring / Spring Boot` · `MySQL` · `MS-SQL` · `REST API` · `서버 배치` · `장애 분석·RCA` · `보안 서버 개발 전반`

**Working — 실전 운영·유지보수 경험**
`Kubernetes` · `C++` · `Linux` · `HTTP/HTTPS` · `마이크로서비스 아키텍처` · `Wireshark` · `TCP/IP` · `Git / GitHub`

**Learning — 현재 학습·PoC 중**
`Elasticsearch / OpenSearch` · `Hadoop / Spark` · `Observability (Prometheus, Grafana, OpenTelemetry)` · `Terraform · ArgoCD` · `MLOps · LLM 응용` · `Hybrid Cloud (AWS)` · `Python 자동화`

---

## 🔬 진행 중인 PoC · 포트폴리오

### 1. (WIP) 대용량 로그 플랫폼 개선 설계
- **문제** — MySQL 단일 저장 구조에 누적된 로그의 웹 조회 시 쿼리 부하·지연 발생
- **접근** — (a) MySQL 파티셔닝 최적화 / (b) Elasticsearch 단독 / (c) Hadoop 단독 / (d) ES + Object Storage 계층화 — 네 가지 안을 같은 쿼리 세트로 벤치마크
- **기록 예정** — 검색 지연, 스토리지 비용, 색인 실패율, 운영 난이도 — ADR(Architecture Decision Record) 형식으로 정리
- **링크** — 소개 가능한 선에서 [repo-link-예정]

### 2. (TBD) Observability 풀스택 샘플
Spring Boot 샘플 앱에 RED 메트릭 + 구조화 로그 + 분산 트레이스를 한꺼번에 붙인 레퍼런스 구성.

### 3. (TBD) 보안 관점의 GitOps 파이프라인
ArgoCD + Sigstore / Cosign + Trivy + OIDC 기반 secret-less 배포 — "개발자 파이프라인"을 "운영·감사관 관점"으로 다시 짜기.

---

## 🧱 지향점

- **주도적 엔지니어링** — 문제 정의·대안 비교·의사결정 기록까지 남기는 엔지니어
- **경계에서 일하기** — 보안 × 인프라 × 데이터의 교차점에서 책임 있는 사람이 되기
- **자동화의 효율** — 풀었으면 스크립트로, 반복되면 파이프라인으로, 구조적이면 플랫폼으로

---

## 📫 Contact

- **Email**: [hj.steve.choi@gmail.com]
- **LinkedIn**: [LinkedIn URL]
- **Blog / Notion**: [URL]

---

<sub>이 문서는 영문 메인 프로필([README.md](./README.md))의 한국어 보조 노트입니다. 경험과 결과가 쌓이면 수치·링크로 교체됩니다. · 최근 업데이트: 2026-04-19</sub>
