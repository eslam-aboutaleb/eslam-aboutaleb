<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1F6FEB,100:58A6FF&height=220&section=header&text=Eslam%20Ehab&fontSize=70&fontColor=ffffff&fontAlignY=35&desc=Senior%20AI%20%2F%20Fullstack%20Engineer&descSize=18&descAlignY=55&animation=fadeIn&duration=2000" width="100%"/>

# Eslam Ehab

**Senior AI / Fullstack Engineer — GenAI Systems, Agentic Architectures, RAG, Cloud-Native Backends**

I design and ship production AI products end to end: multi-agent orchestration, retrieval-augmented
generation, evaluation harnesses, and the FastAPI / Spring Boot / React / cloud infrastructure that
runs them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eslamaboutaleb)
[![Email](https://img.shields.io/badge/Email-eslamehababoutaleb@gmail.com?style=flat-square&logo=gmail&logoColor=white)](mailto:eslamehababoutaleb@gmail.com)

---

## Focus Areas

<table>
<tr>
<td width="50%" valign="top">

**Agentic AI**
- Multi-agent systems & orchestration
- Function calling / tool use
- Structured outputs
- Prompt & context engineering
- MCP, A2A protocol
- Provider routing (LiteLLM)

</td>
<td width="50%" valign="top">

**RAG & Evaluation**
- Retrieval-Augmented Generation
- Embeddings & vector search
- Hybrid / semantic retrieval
- Chunking & ingestion pipelines
- Answer-quality evaluation (RAGAS)
- Tracing & observability (LangSmith)

</td>
</tr>
<tr>
<td valign="top">

**Backend Engineering**
- FastAPI, async Python
- REST, WebSocket, SSE streaming
- Auth, authorization, idempotency
- Microservices & background workers
- Automated testing

</td>
<td valign="top">

**Cloud & Delivery**
- GCP — Vertex AI, Cloud Run, Cloud Storage
- AWS — EC2, Lambda, S3
- Terraform / IaC
- Docker, CI/CD pipelines
- GitHub Actions, Jenkins

</td>
</tr>
</table>

---

## Selected Projects

### Polymarket AI Trading
**Agentic trading · FastAPI · React · gRPC · Docker**

AI-assisted trading automation for Polymarket: copy-trading, market-making, inverse bot,
latency arbitrage, whale monitoring, stop-loss/take-profit, LLM-powered market analysis,
and backtesting over a FastAPI + React + gRPC stack.

- 25 services, 16 API route modules, 27 domain models
- Real-time WebSocket market data and Binance signal ingestion
- Kelly sizing, pre-trade risk gates, PnL reconciliation
- Backtesting engine with copy-trade, indicator, and custom strategies
- Docker Compose, pre-commit (ruff + prettier), 90%+ backend test coverage

[Repository](https://github.com/eslam-aboutaleb/polymarket-ai-trading)

---

### Insurance Claims RAG Assistant
**Agentic RAG · Google ADK · pgvector · FastAPI · React**

Full-stack conversational assistant for the insurance claims domain. A Google ADK `LlmAgent` routes
policyholder questions to a set of tools — grounded policy RAG, claim status lookup, and validated
claim submission — over a pgvector store, with LiteLLM handling provider routing.

- Grounded answers with source citations and prompt-injection defenses
- Streaming responses over SSE with tool-call transparency
- JWT + HTTP-only cookie auth, rate limiting, idempotent claim submission
- Alembic migrations, hybrid retrieval, RAG evaluation harness
- Docker Compose, React + Tailwind frontend

[Repository](https://github.com/eslam-aboutaleb/insurance-claims-rag-assistant)

---

### Ace Your Interview
**Adaptive learning platform · FastAPI · gRPC · MCP · React PWA**

Adaptive interview-preparation platform spanning Backend, Frontend, System Design and AI Stack
tracks, with strict grounded generation that cites the source material behind every question.

- Level-aware question and quiz generation with source validation and retries
- Adaptive engine tracking attempts, weak areas and topic mastery
- Mock interview sessions with rubric-based feedback and reports
- Provider-agnostic LLM settings, MCP gateway, gRPC service boundary
- Google / GitHub OAuth, STT/TTS voice, PWA, Mermaid + code rendering

[Repository](https://github.com/eslam-aboutaleb/ace-your-interview)

---

### Workshop Reservation Service
**Concurrency-safe backend · FastAPI · PostgreSQL · SSE · React**

Reservation service built around the hard parts of booking systems: capacity limits under
concurrent load, ownership enforcement, and safe client retries.

- Transaction-safe reservations that never oversell capacity
- `Idempotency-Key` handling for safe request retries
- Server-Sent Events for live availability updates
- Strict per-user reservation ownership, environment-scoped admin roles
- Alembic migrations and a pytest suite covering concurrency and auth isolation

[Repository](https://github.com/eslam-aboutaleb/Worshop-reservation)

---

### Interview Prep Platform
**LLM application · Gemini · FastAPI · React · Docker**

Interview-question generation and management platform: personalized question sets, full CRUD,
progress tracking and statistics, served through FastAPI and a React/Tailwind frontend on
Docker Compose with nginx.

[Repository](https://github.com/eslam-aboutaleb/Interview-Helper-Agent)

---

## Technical Skills

| Area | Technologies |
| --- | --- |
| **Languages** | Python, Java, TypeScript, JavaScript, C |
| **AI frameworks** | Google ADK, LangGraph, LangChain, LiteLLM, MCP, A2A Protocol |
| **Agent engineering** | Multi-agent systems, agent orchestration, function calling, structured outputs, prompt & context engineering |
| **RAG & evaluation** | Vector search, embeddings, RAG agents, RAGAS, LangSmith, ChromaDB |
| **Backend** | FastAPI, Spring Boot, Flask, REST APIs, microservices, AsyncIO, WebSockets, SSE |
| **Frontend** | React, Tailwind CSS, HTML5, CSS3 |
| **Cloud & AI platforms** | GCP (Vertex AI, Cloud Run, Cloud Storage, Agent Engine), AWS (EC2, Lambda, S3) |
| **Infrastructure** | Terraform, IaC, Docker, CI/CD |
| **Data** | PostgreSQL, pgvector, Redis |

---

## Education

- **MBA, AI in Business** — AAST
- **B.Sc. Mechatronics Engineering** — October 6 University

## Certifications

- **ISTQB Certified Tester, Foundation Level (CTFL)**
- **ISTQB Certified Tester, Agile Extension (CTFL-AT)**
- **Professional Google Cloud Architect**

## Languages

English · Arabic

---

## Connect

- **Email** — [eslamehababoutaleb@gmail.com](mailto:eslamehababoutaleb@gmail.com)
- **LinkedIn** — [linkedin.com/in/eslamaboutaleb](https://www.linkedin.com/in/eslamaboutaleb)
- **GitHub** — [github.com/eslam-aboutaleb](https://github.com/eslam-aboutaleb)
