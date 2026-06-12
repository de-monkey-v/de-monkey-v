# Gyuhyeon Lee

Backend-focused developer interested in product servers, schema tooling, and LLM/RAG-based applications.

- Building with Spring Boot, Java, TypeScript, PostgreSQL, and MariaDB
- Interested in chatbot systems, RAG, LLM application architecture, MCP, and AI-assisted development workflows
- Creator of [SchemaHatch](https://schemahatch.com/), a DB diagram and schema workflow tool

[LinkedIn](https://www.linkedin.com/in/gyuhyeon-lee-a2b7743a4/) · [SchemaHatch](https://schemahatch.com/) · [SchemaHatch CLI](https://www.npmjs.com/package/@schemahatch/cli)

[한국어](#korean) | [English](#english)

## Korean

<details open>
<summary><strong>한국어로 보기</strong></summary>

### About

낯선 도메인과 복잡한 기존 흐름을 이해한 뒤, 동작하는 시스템으로 정리하는 일을 좋아하는 backend-focused developer입니다.

서버 개발을 목표로 입사했지만, 초반에는 WPF 데스크톱 UI, C++ 모듈, 레거시 Web demo와 데이터 마이그레이션을 먼저 경험했습니다. 이후 Spring Boot와 Java 기반 제품 서버를 맡으며 API, 데이터 모델, 테스트, 내부 배포, 변경 공유 흐름까지 함께 다루게 됐습니다.

최근에는 LLM과 AI 애플리케이션에도 관심을 두고 공부하고 있습니다. LangChain, LangGraph, RAG, Vector DB, Graph DB를 활용한 LLM 애플리케이션 구성 요소를 실습했고, 앞으로는 챗봇, RAG 기반 지식 검색 시스템, 사내 업무 자동화 도구처럼 백엔드와 LLM이 만나는 영역을 더 깊게 다뤄보고 싶습니다.

### Featured Project: SchemaHatch

[SchemaHatch](https://schemahatch.com/)는 DB diagram과 schema 변경 흐름을 관리하기 위해 만든 개인 프로젝트입니다.

- Project / branch / revision 기반 schema workflow
- Prisma schema, SQL DDL, DBML import
- PostgreSQL introspection
- SQL, DBML, Prisma, JSON export API
- React Flow 기반 ERD workbench
- Public REST API, MCP surface, CLI 제공
- Railway + Cloudflare 기반 배포
- CLI 패키지 `@schemahatch/cli` npm 배포

Site: https://schemahatch.com/  
CLI: https://www.npmjs.com/package/@schemahatch/cli

### What I Work On

**Product Backend**

- Spring Boot 3.x / Java 17 기반 B2B 도메인 제품 서버 개발
- 실제 서비스 기능 API 130개 이상 구현
- Flyway 기준 약 30개 테이블 설계 및 확장
- 인증, 권한, 워크스페이스, 고객/케이스/파일 흐름 중심의 통합 테스트 약 600개 작성
- MariaDB, JPA, QueryDSL 기반 데이터 접근 및 도메인 흐름 구현
- Docker Compose, k3s, Harbor, WSL2 기반 내부 dev/staging 배포 경험
- API 변경사항, Breaking Change, 요청/응답 예시, 프론트엔드 체크리스트를 포함한 패치노트 자동화

**Legacy / Desktop / Native**

- Vue + Spring Boot 기반 레거시 Web demo 전환 및 MDB/MSSQL 데이터 마이그레이션
- WPF UI를 MVVM 기반 레이아웃/컴포넌트 구조로 정리
- C++ DLL 형태의 스레드 기반 증분 백업 모듈 구현
- WinDbg CLI 기반 데스크톱 앱 dump 분석 흐름 구현

**AI / LLM**

- LangChain, LangGraph, RAG, Vector DB, Graph DB 기반 LLM 애플리케이션 구성 요소 실습
- Langfuse, LangSmith를 활용한 LLM 호출 흐름 추적 및 디버깅 경험
- ComfyUI 이미지/영상 생성 workflow를 API 호출 방식으로 활용
- 로컬 TTS/STT 모델을 API 서버 형태로 구성해 음성 인식/합성 연동 흐름 구현
- Codex, Claude Code, MCP, CLI, custom skill을 활용한 개발 자동화

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
LLM, RAG, LangChain, LangGraph, Vector DB, Graph DB, Langfuse, LangSmith, ComfyUI, local TTS/STT API, MCP, CLI, Codex, Claude Code

</details>

## English

<details>
<summary><strong>View in English</strong></summary>

### About

I am a backend-focused developer who enjoys understanding unfamiliar domains and complex existing workflows, then turning them into working systems.

I joined my current career path with the goal of working on server/backend development, but my early work covered adjacent areas first: WPF desktop UI, C++ modules, legacy web demos, and data migration. Later, I took ownership of a Spring Boot and Java-based product server and worked across APIs, data models, tests, internal deployment, and change communication.

Recently, I have been studying LLM and AI application development. I have practiced building blocks such as LangChain, LangGraph, RAG, Vector DB, and Graph DB, and I want to go deeper into the area where backend systems meet LLMs: chatbot systems, RAG-based knowledge retrieval, and internal workflow automation tools.

### Featured Project: SchemaHatch

[SchemaHatch](https://schemahatch.com/) is a personal project for managing DB diagrams and schema change workflows.

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

### What I Work On

**Product Backend**

- Built a Spring Boot 3.x / Java 17 server for a B2B domain product
- Implemented 130+ service APIs
- Designed and extended about 30 database tables with Flyway
- Wrote about 600 integration tests around authentication, authorization, workspace, customer/case, and file flows
- Implemented data access and domain workflows with MariaDB, JPA, and QueryDSL
- Deployed internal dev/staging environments with Docker Compose, k3s, Harbor, and WSL2
- Automated patch notes covering API changes, breaking changes, request/response examples, and frontend checklists

**Legacy / Desktop / Native**

- Converted part of a legacy desktop product into a Vue + Spring Boot web demo and built MDB/MSSQL migration flows
- Refactored WPF UI into MVVM-based layout/component structures
- Implemented a thread-based incremental backup module as a C++ DLL
- Built a WinDbg CLI-based dump analysis flow for desktop app crash files

**AI / LLM**

- Practiced LLM application building blocks with LangChain, LangGraph, RAG, Vector DB, and Graph DB
- Used Langfuse and LangSmith to trace and debug LLM call flows
- Used ComfyUI image/video generation workflows through API calls
- Built API-server-style flows around local TTS/STT models
- Used Codex, Claude Code, MCP, CLI tools, and custom skills for development automation

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
LLM, RAG, LangChain, LangGraph, Vector DB, Graph DB, Langfuse, LangSmith, ComfyUI, local TTS/STT API, MCP, CLI, Codex, Claude Code

</details>
