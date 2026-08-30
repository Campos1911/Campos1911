# 👋 Hi, I'm Anthoni Campos

Backend Software Engineer and Electrical Engineering student (Computer Engineering focus) at UFES (Federal University of Espírito Santo). I am driven by transforming complex business logic into efficient, resilient, and data-driven distributed systems.

Currently, I work developing backend solutions in production environments, designing API integrations, automating operational processes, and building high-scale architectures using **Node.js, NestJS, TypeScript, and Python**.

---

## 🚀 What I Do

- Design and build robust, high-throughput **REST APIs** and backend distributed architectures
- Implement **resilient payment integrations & Webhook ingestion engines** with strict idempotency
- Engineer asynchronous processing pipelines using **Message Brokers & Queues (BullMQ, Redis)**
- Create **automation workflows** and data pipelines (ETL)
- Implement **Applied AI solutions** (RAG, LLM integrations, AI Agents)
- Focus on clean architecture, ACID data consistency, and database performance tuning

---

## ⭐ Featured Projects

### ⚡ High-Throughput Payment Webhook Engine (2.3k+ req/s)
**Resilient, high-scale async payment webhook engine with dual-layer idempotency and fault recovery.**  
Engine designed to solve real-world payment gateway concurrency challenges, preventing double-spending and database starvation under heavy load bursts.
- **High Performance:** Sustained **+2,300 req/s** throughput and processed **80k+ requests with 0.00% error rate** under k6 spike testing.
- **Dual-Layer Idempotency:** Atomic Redis distributed locks (via Lua scripts) + PostgreSQL transactional row-level locks (`SELECT FOR UPDATE` & unique constraints).
- **Resilience & DLQ:** Automated Exponential Backoff retries, Dead Letter Queue (DLQ) routing for fatal failures, and administrative Replay APIs.
- **L7 Load Balancing:** Nginx reverse proxy (`least_conn`) balancing traffic across multi-replica NestJS producers and decoupled standalone worker consumers.
- **Tech Stack:** NestJS, TypeScript, BullMQ, Redis 7, PostgreSQL 16, Nginx, Docker Compose, k6.
- [🔗 View Repository](https://github.com/Campos1911/balanceamento-de-chamadas-e-fila-nestjs)

---

### 🧠 My Second Brain Hub
**Modular platform for personal productivity, finances, routines, and task management.**  
A centralized, highly scalable ecosystem built to manage everyday operations. Features separated domain modules (financial tracking, training routines) unified under a single robust architecture.
- **Tech Stack:** TypeScript, Node.js.
- [🔗 View Repository](https://github.com/Campos1911/my-second-brain)

---

### 🏋️ Train Tracker (GymTrack)
**A data-driven solution to track real strength evolution at the gym.**  
A structured Full Stack monorepo that manages active training plans, logs sessions in real-time, and tracks load progression history.
- **Tech Stack:** NestJS (Fastify), Prisma, SQLite, Next.js, TailwindCSS, React Query.
- **Key Feature:** Implementation of "Active Plan" logic and structured session versioning.
- [🔗 View Repository](https://github.com/Campos1911/train_tracker)

---

### 🤖 Smart Lead Triage API
**Intelligent backend system for unstructured data processing.**  
Developed an API that transforms raw data into structured business insights using RAG pipelines and AI models, designed with a focus on resilience and scalable architecture.
- **Tech Stack:** NestJS, Prisma, Google Gemini AI, TypeScript.
- [🔗 View Repository](https://github.com/Campos1911/smartLeadTriage)

---

### ⚙️ Scalable NestJS Boilerplate
**Production-ready template focusing on background jobs and security.**  
A complete NestJS architecture template featuring robust queue implementation for asynchronous processing and secure authentication flows.
- **Tech Stack:** NestJS, TypeScript, Message Brokers.
- [🔗 View Repository](https://github.com/Campos1911/templateNestJS)

---

## 💻 Other Repositories of Interest
- **[Personal Financial API](https://github.com/Campos1911/financeiroPessoalBackend):** Backend system to manage financial operations, tracking income, expenses, and budgets.
- **[tratamentoAulasTc](https://github.com/Campos1911/tratamentoAulasTc):** Python data validation scripts to verify database integrity and reconcile non-matching records.
- **[Data Structures (UFES)](https://github.com/Campos1911/estruturaDeDados):** Foundation of algorithmic thinking and memory management, featuring C implementations developed during Engineering school.

---

## 🛠 Tech Stack

**Backend & Architecture:** Node.js, NestJS, TypeScript, Python (FastAPI/Flask), Distributed Systems, Microservices  
**Message Brokers & Queues:** BullMQ, Redis, RabbitMQ  
**Databases & Storage:** PostgreSQL, Redis, MongoDB, Supabase, SQLite, Prisma, TypeORM  
**DevOps & Infrastructure:** Docker & Docker Compose, Nginx (Load Balancing), GCP, Linux, CI/CD (GitHub Actions)  
**Testing & Benchmarking:** k6 (Load & Stress Testing), Jest, Supertest  
**Automation & AI:** n8n, OpenAI API, Google Gemini API, RAG Pipelines  
**Frontend (Support):** Next.js, React, TailwindCSS  

---

## 🌐 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/anthoni-campos)

⭐ Feel free to explore my repositories — feedback and technical discussions are always welcome!
