# Eslam Ehab

**AI & Full-Stack Engineer | Agentic AI · RAG · Backend Systems**

I build AI-enabled applications and backend systems, from reusable retrieval components to full-stack products. My work focuses on agent workflows, grounded answers, reliable APIs, data integrity, and evaluation-driven development.

<p>
  <a href="https://www.linkedin.com/in/eslamaboutaleb"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:eslamehababoutaleb@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/eslam-aboutaleb"><img src="https://img.shields.io/badge/GitHub-Projects-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## Featured Projects

### [ragit — Domain-Agnostic RAG Toolkit](https://github.com/eslam-aboutaleb/ragit)

A reusable Python toolkit for building retrieval-augmented generation systems without coupling the core library to a specific application domain.

- Document chunking, embedding interfaces, ingestion pipelines, and pluggable vector-store backends.
- Hybrid retrieval, including vector similarity and lexical search strategies.
- Background embedding jobs, idempotent ingestion, and stale-job recovery.
- Evaluation tools for retrieval quality, including Precision@K, Recall@K, and MRR.
- MIT licensed.

**Stack:** Python, SQLAlchemy, PostgreSQL/pgvector, Qdrant, Chroma, FAISS, pytest

### [Polymarket AI Trading Bot & Research Workspace](https://github.com/eslam-aboutaleb/polymarket-ai-trading)

An AI-assisted workspace for prediction-market research, portfolio monitoring, strategy experimentation, and trading automation.

- Research and analysis agents for market context, news, sentiment, and trader activity.
- Strategy workflows for copy trading, market making, inverse positioning, and latency-arbitrage research.
- Paper-trading and backtesting tools to evaluate strategies before live execution.
- Portfolio analytics, execution monitoring, configurable risk limits, and stop-loss/take-profit controls.
- Market monitoring, notifications, audit trails, and API integrations.

**Stack:** Python, FastAPI, React, PostgreSQL, Redis, Docker, LLM integrations, Polymarket/Polygon

*An engineering project for research and experimentation; backtests and generated analyses do not guarantee future trading performance.*

### [Insurance Claims RAG Assistant](https://github.com/eslam-aboutaleb/insurance-claims-rag-assistant)

A full-stack customer-assistant prototype for a fictional insurer, using synthetic policy and claim data. It demonstrates how a domain-focused AI assistant can combine grounded retrieval with validated application workflows.

- Policy-coverage answers with source citations and hybrid retrieval.
- Agent tool use for claim-status lookup and validated, two-step claim submission.
- FastAPI, PostgreSQL/pgvector, streaming responses, authentication, and audit events.
- Dedicated tests and an evaluation gate for retrieval and refusal behavior.

**Stack:** Python, Google ADK, LiteLLM, FastAPI, PostgreSQL, pgvector, React, Docker Compose

> This is a demonstration project using synthetic data; it is not affiliated with a real insurance company.

### [Ace Your Interview](https://github.com/eslam-aboutaleb/ace-your-interview)

An adaptive interview-preparation platform that combines study workflows with AI-assisted practice across backend, frontend, system design, and AI engineering topics.

- Level-aware question and quiz generation with source-grounding checks.
- FSRS-based spaced repetition and flashcards with Anki interoperability.
- Mock interview sessions with rubric-based feedback.
- RAG chat, learning progress, and a React-based user experience.

**Stack:** Python, FastAPI, React, TypeScript, LLM integrations, RAG, MCP, Docker

### [Workshop Reservation Service](https://github.com/eslam-aboutaleb/Workshop-reservation)

A full-stack booking application focused on correctness under concurrent requests and safe retries.

- Transaction-safe reservations designed to prevent capacity overselling.
- Idempotency keys for retry-safe reservation requests.
- User-scoped reservation access and administrator controls.
- Server-Sent Events for live availability updates.
- Database migrations and tests for concurrency and authorization behavior.

**Stack:** Python, FastAPI, PostgreSQL, React, Docker Compose, pytest

---

## Technical Focus

| Area | Technologies and practices |
| --- | --- |
| **AI & agent systems** | Google ADK, LiteLLM, tool calling, structured outputs, MCP |
| **RAG & evaluation** | Embeddings, hybrid retrieval, vector stores, retrieval evaluation, source-grounded responses |
| **Backend engineering** | Python, FastAPI, async APIs, REST, WebSockets, Server-Sent Events |
| **Data & persistence** | PostgreSQL, pgvector, SQLAlchemy, Redis, MongoDB |
| **Frontend** | React, TypeScript, JavaScript, Tailwind CSS |
| **Testing & delivery** | pytest, API testing, Docker, Docker Compose, GitHub Actions, CI/CD |
| **Cloud & infrastructure** | AWS, Google Cloud, Terraform / infrastructure as code |

## Engineering Principles

- **Ground AI outputs in evidence:** treat retrieval quality, citations, and evaluation as part of the application—not an afterthought.
- **Design APIs for real failure modes:** consider validation, authorization boundaries, idempotency, concurrency, and useful error handling.
- **Make projects reproducible:** provide clear setup instructions, controlled configuration, migrations, and automated checks.
- **Prefer transparent engineering:** document design decisions, limitations, and the difference between a working prototype and a production deployment.

---

## Connect

- **LinkedIn:** [linkedin.com/in/eslamaboutaleb](https://www.linkedin.com/in/eslamaboutaleb)
- **Email:** [eslamehababoutaleb@gmail.com](mailto:eslamehababoutaleb@gmail.com)
- **GitHub:** [github.com/eslam-aboutaleb](https://github.com/eslam-aboutaleb)
