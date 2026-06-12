# Gyuhyeon Lee

Backend engineer who builds beyond the server: product APIs, database design, data migration, desktop UI, native modules, deployment workflows, and AI-assisted tooling.

[한국어](#korean) | [English](#english)

## Korean

<details open>
<summary><strong>한국어로 보기</strong></summary>

### 소개

저는 Spring Boot와 Java 기반 제품 서버 개발을 중심으로 시작했지만, 필요한 문제가 생기면 클라이언트, 데스크톱 UI, C++ 모듈, 데이터 마이그레이션, 인프라, AI 자동화까지 직접 파고드는 개발자입니다.

제품 서버에서는 DB 설계, API 구현, 테스트, 내부 배포, 패치노트 자동화까지 개발 흐름 전반을 경험했습니다. 동시에 레거시 데스크톱 제품의 Web demo 전환, WPF UI 구조 개선, C++ DLL 모듈 구현, DB diagram 개인 프로젝트, LLM/AI 도구 활용까지 폭넓게 다뤄왔습니다.

### 해본 일

- Spring Boot 3.x / Java 17 기반 B2B 도메인 제품 서버 개발
- 실제 서비스 기능 API 130개 이상 구현
- Flyway 기준 약 30개 테이블 설계 및 확장
- 인증, 권한, 워크스페이스, 고객/케이스/파일 도메인 통합 테스트 약 600개 작성
- MariaDB, JPA, QueryDSL 기반 데이터 접근 및 도메인 흐름 구현
- MinIO, Resend, Redis, Kafka 등 인프라 연동 경험
- Docker Compose, k3s, Harbor, WSL2 기반 내부 dev/staging 배포 경험
- API 변경사항, Breaking Change, 요청/응답 예시, 프론트엔드 체크리스트를 포함한 패치노트 자동화
- MFC/C++ 기반 레거시 데스크톱 제품의 Vue + Spring Boot Web demo 전환 및 MDB/MSSQL 데이터 마이그레이션
- WPF UI를 MVVM 기반 레이아웃/컴포넌트 구조로 정리해 반복적인 디자인 수정 대응 개선
- C++ DLL 형태의 스레드 기반 증분 백업 모듈 구현
- WinDbg CLI 기반 데스크톱 앱 dump 분석 흐름 구현
- Codex, Claude Code, MCP, CLI, custom skill을 활용한 개발 자동화
- 약 15명 규모의 사내 AI 활용 교육 모임 운영

### Featured Project: SchemaHatch

SchemaHatch는 DB diagram과 schema 변경 흐름을 관리하기 위해 만든 개인 프로젝트입니다.

- Project / branch / revision 기반 schema 관리 흐름
- Prisma schema, SQL DDL, DBML import
- PostgreSQL introspection
- SQL, DBML, Prisma, JSON export API
- React Flow 기반 ERD workbench
- public REST API, MCP surface, CLI 제공
- Railway + Cloudflare 기반 배포
- CLI 패키지 `@schemahatch/cli` npm 배포

Site: https://schemahatch.com/  
CLI: https://www.npmjs.com/package/@schemahatch/cli

### Tech Stack

**Languages**  
Java, TypeScript, JavaScript, C#, C++, SQL

**Backend / API**  
Spring Boot, Java 17, Spring JPA, QueryDSL, REST API, NestJS, Prisma

**Database / Infra**  
MariaDB, PostgreSQL, MSSQL, MDB, Redis, Kafka, MinIO, Docker Compose, k3s, Harbor, WSL2, Railway, Cloudflare

**Client / Desktop**  
React, Next.js, Vue, WPF, MVVM, Qt, React Flow

**AI / Automation**  
Codex, Claude Code, MCP, CLI, RAG, LangChain, LangGraph, Vector DB, Graph DB, Langfuse, LangSmith, ComfyUI, local TTS/STT API

### 일하는 방식

- 먼저 문제와 사용자 흐름을 파악한 뒤 API, DB, UI, 배포 중 어디를 바꿔야 하는지 정리합니다.
- AI 도구를 적극적으로 활용하지만, 테스트와 실제 동작 확인으로 검증하는 방식을 중요하게 생각합니다.
- 처음 해보는 영역도 필요한 만큼 학습해 구현하고, 이후에는 다시 구조와 경계를 돌아보며 개선점을 찾습니다.

</details>

## English

<details>
<summary><strong>View in English</strong></summary>

### About

I am a backend engineer whose core experience is building Spring Boot and Java-based product servers, but I often work beyond the server when the product needs it: client-side flows, desktop UI, C++ modules, data migration, deployment workflows, and AI-assisted automation.

I have worked across database design, API implementation, integration testing, internal deployment, and release-note automation. I have also built a web demo from a legacy desktop product, improved WPF UI structure, implemented a C++ DLL module, created a DB diagram product, and explored LLM/AI tooling in practical development workflows.

### What I Have Worked On

- Built a Spring Boot 3.x / Java 17 server for a B2B domain product
- Implemented 130+ service APIs
- Designed and extended about 30 database tables with Flyway
- Wrote about 600 integration tests for authentication, authorization, workspace, customer/case, and file flows
- Implemented data access and domain workflows with MariaDB, JPA, and QueryDSL
- Integrated infrastructure components such as MinIO, Resend, Redis, and Kafka
- Deployed internal dev/staging environments with Docker Compose, k3s, Harbor, and WSL2
- Automated patch notes covering API changes, breaking changes, request/response examples, and frontend checklists
- Converted part of a legacy MFC/C++ desktop product into a Vue + Spring Boot web demo and built MDB/MSSQL migration flows
- Refactored WPF UI into MVVM-based layout/component structures to handle repeated design changes more efficiently
- Implemented a thread-based incremental backup module as a C++ DLL
- Built a WinDbg CLI-based dump analysis flow for desktop app crash files
- Used Codex, Claude Code, MCP, CLI tools, and custom skills for development automation
- Led an internal AI usage learning group with about 15 participants

### Featured Project: SchemaHatch

SchemaHatch is a personal project for managing DB diagrams and schema change workflows.

- Project / branch / revision-based schema workflow
- Prisma schema, SQL DDL, and DBML import
- PostgreSQL introspection
- SQL, DBML, Prisma, and JSON export APIs
- React Flow-based ERD workbench
- Public REST API, MCP surface, and CLI
- Deployed with Railway and Cloudflare
- CLI package `@schemahatch/cli` published to npm

Site: https://schemahatch.com/  
CLI: https://www.npmjs.com/package/@schemahatch/cli

### Tech Stack

**Languages**  
Java, TypeScript, JavaScript, C#, C++, SQL

**Backend / API**  
Spring Boot, Java 17, Spring JPA, QueryDSL, REST API, NestJS, Prisma

**Database / Infra**  
MariaDB, PostgreSQL, MSSQL, MDB, Redis, Kafka, MinIO, Docker Compose, k3s, Harbor, WSL2, Railway, Cloudflare

**Client / Desktop**  
React, Next.js, Vue, WPF, MVVM, Qt, React Flow

**AI / Automation**  
Codex, Claude Code, MCP, CLI, RAG, LangChain, LangGraph, Vector DB, Graph DB, Langfuse, LangSmith, ComfyUI, local TTS/STT API

### How I Work

- I start by understanding the problem and user flow, then decide whether the change belongs in the API, database, UI, deployment flow, or automation layer.
- I actively use AI tools, but I care about validating the result with tests and real behavior.
- When I encounter an unfamiliar area, I learn enough to build, then revisit the structure and boundaries to find what should improve next.

</details>
