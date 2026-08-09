# Hi 👋, I'm Felipe Godoy

### 💡 Backend & AI Systems Engineer • Python • FastAPI • LLM Applications • RAG • Agentic Workflows • Cloud

---

## 🚀 About Me

I'm a **Computer Science graduate** focused on building reliable backend systems and production-minded AI applications.

My work sits at the intersection of **backend engineering and applied AI**: LLM orchestration, Retrieval-Augmented Generation, controlled agent workflows, cloud-native processing, observability, evaluation, and automation.

I enjoy building systems where AI is part of the actual software architecture — with structured outputs, validation, retries, persistence, cost controls, safety boundaries, and operational visibility — rather than just a model behind a chat interface.

---

## 💘 Featured Product

### Maia — AI Relationship Advisor

**Maia** is an AI-powered relationship advisor that turns complex romantic situations — including optional conversation screenshots — into direct, culturally aware guidance across **27 languages**.

It is a real deployed AI product combining multimodal analysis, localized persona engineering, authentication, safety systems, usage controls, provider failover, private image handling, and cloud infrastructure.

**Engineering highlights:**

* 🧠 **Multi-provider LLM orchestration** with Gemini as the primary generation path and Groq/OpenAI fallback capabilities
* 🖼️ **Multimodal screenshot analysis** using actual image content rather than caption-only substitution
* 🌍 **27-language productization** with locale-specific prompt packs and culturally adapted tone
* 🛡️ **Layered AI safety architecture** with intent routing, text/image moderation, crisis handling, and response sanitization
* 🔐 **Google authentication with Supabase**, authenticated APIs, durable usage controls, and abuse protection
* ☁️ **Cross-cloud AI integration** with Google Cloud and AWS Rekognition using short-lived workload identity credentials
* 🗂️ **Private GCS image lifecycle** with opaque image IDs, registry-backed access, expiration, and cleanup
* 📊 **Usage-aware AI architecture** with separate message, upload, and multimodal analysis quotas
* ⚙️ **Production-oriented backend** with FastAPI, structured logging, health checks, Sentry, Docker, and automated quality gates

**Stack:**
`Python` · `FastAPI` · `React` · `Vite` · `Supabase Auth/PostgreSQL` · `Gemini` · `Groq` · `OpenAI` · `AWS Rekognition` · `GCS` · `Redis` · `Google Cloud Run` · `Docker` · `Sentry` · `PostHog`

🔗 **Live:** [maiatalks.uk](https://maiatalks.uk)

---

## 🧠 Selected Engineering Projects

### 🤖 [SupportOps AI Platform](https://github.com/philgodoy96/supportops-ai-platform)

A production-minded AI support operations backend combining **durable workflow execution, LLM orchestration, RAG, controlled tool calling, human approval, observability, and evaluation**.

**What it demonstrates:**

* LangGraph as a bounded orchestration layer inside durable application-owned execution
* PostgreSQL-backed workflow state with leases, fencing tokens, bounded retries, and recovery
* Application-owned LLM Gateway with provider abstraction and structured outputs
* Versioned prompts, token accounting, and estimated LLM cost tracking
* RAG over internal runbooks with Qdrant as a rebuildable retrieval projection
* Registered tools with durable tool-call audit records
* Human-in-the-loop approval for sensitive operations
* Langfuse observability boundary
* RAGAS-backed evaluation and explicit prompt release governance
* CI, Docker, migrations, tests, ADRs, and architecture documentation

**Stack:**
`Python` · `FastAPI` · `PostgreSQL` · `LangGraph` · `Qdrant` · `OpenAI` · `Langfuse` · `RAGAS` · `Docker` · `GitHub Actions`

---

### ☁️ [CloudDoc AI Pipeline](https://github.com/philgodoy96/clouddoc-ai-pipeline)

A serverless AWS document intelligence pipeline designed around **asynchronous processing, reliability, Infrastructure as Code, and Amazon Bedrock integration**.

**What it demonstrates:**

* Pre-signed document ingestion through Amazon S3
* Event-driven processing with SQS and Lambda
* Dead-letter handling and retry-safe processing
* Amazon Bedrock integration behind an AI provider abstraction
* Structured AI extraction with validation
* DynamoDB-backed job state
* CloudWatch logging and operational visibility
* IAM-aware AWS architecture
* Terraform-managed infrastructure
* GitHub Actions and AWS OIDC-based delivery workflows
* Mock AI providers for deterministic, cost-free automated testing

**Stack:**
`Python` · `AWS Lambda` · `API Gateway` · `S3` · `SQS` · `DynamoDB` · `Amazon Bedrock` · `CloudWatch` · `IAM` · `Terraform` · `GitHub Actions`

---

### 🏥 [ClinicOps SaaS](https://github.com/philgodoy96/clinicops-saas)

A production-minded **multi-tenant clinic management SaaS backend** focused on isolation, authorization, billing reliability, durable jobs, and auditability.

**What it demonstrates:**

* Strict tenant ownership boundaries
* Membership-based RBAC
* First-party authentication and refresh-token lifecycle
* Invitation-based onboarding
* Subscription and invoice state management
* Signed payment webhooks and idempotent event processing
* Durable PostgreSQL-backed background jobs
* Retry policies and failure recovery
* Audit logs separated from operational application logging
* Request and correlation IDs across business workflows

**Stack:**
`Python` · `FastAPI` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `Pydantic` · `Docker` · `pytest` · `GitHub Actions`

---

### 🔎 [Incremental RAG Indexing Platform](https://github.com/philgodoy96/incremental-rag-indexing-platform)

A RAG infrastructure project focused on **incremental indexing, retrieval correctness, citation auditability, provider observability, and evaluation**.

**What it demonstrates:**

* Checksum-driven incremental document ingestion
* Document, section, and chunk versioning
* Embedding reuse for unchanged content
* PostgreSQL + pgvector semantic retrieval
* Query trace persistence
* Grounded answer generation with durable citations
* LLM provider abstraction
* Provider call and usage tracking
* Retrieval evaluation workflows

**Stack:**
`Python` · `FastAPI` · `PostgreSQL` · `pgvector` · `Embeddings` · `LLM APIs` · `Docker` · `pytest`

---

## 🎙️ More Applied AI Work

### [AI Clinic Receptionist Platform](https://github.com/philgodoy96/ai-clinic-receptionist-platform)

Production-style AI receptionist focused on appointment workflows, chat and optional voice integration, deterministic backend-managed state, guardrails, durable background jobs, and operational traceability.

---

## 🛠️ Technical Stack

### 🐍 Backend & APIs

`Python` · `FastAPI` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `Pydantic` · `REST APIs` · `Webhooks` · `Background Jobs` · `RBAC` · `JWT`

### 🧠 AI Engineering

`OpenAI` · `Gemini` · `Groq` · `Amazon Bedrock` · `LLM Orchestration` · `Structured Outputs` · `Prompt Versioning` · `Tool Calling` · `LangGraph` · `RAG` · `Embeddings` · `RAGAS` · `Langfuse`

### 🔎 Retrieval & Data

`PostgreSQL` · `pgvector` · `Qdrant` · `DynamoDB` · `Redis` · `Document Ingestion` · `Semantic Retrieval` · `Vector Search`

### ☁️ Cloud & Infrastructure

`AWS Lambda` · `API Gateway` · `S3` · `SQS` · `DynamoDB` · `Bedrock` · `CloudWatch` · `IAM` · `Google Cloud Run` · `GCS` · `Terraform` · `Docker` · `GitHub Actions` · `CI/CD`

### 🔭 Reliability & Observability

`Structured Logging` · `Request IDs` · `Correlation IDs` · `Audit Logs` · `Retries` · `Idempotency` · `DLQ Patterns` · `Cost Tracking` · `Usage Tracking` · `Langfuse` · `Sentry`

### 🎨 Product & Frontend

`React` · `Vite` · `Supabase` · `PostHog` · `Responsive Product Interfaces`

### 🤝 AI-Assisted Engineering

`Cursor` · `Claude Code` · `GitHub Copilot`

---

## ⚙️ How I Think About Engineering

I care about building systems that are understandable when they fail, not only impressive when they work.

Across my projects, I intentionally emphasize:

* clear architectural boundaries
* reliable and observable backend workflows
* deterministic code around probabilistic AI behavior
* validated model outputs
* controlled agent execution
* idempotency and failure recovery
* cost-aware AI integrations
* evaluation instead of intuition alone
* security and privacy boundaries
* automated testing and CI
* documented architectural decisions and trade-offs
* incremental, reviewable Git history

---

## 📫 How to Reach Me

* 💼 [LinkedIn](https://www.linkedin.com/in/aiwithfelipegodoy/)
* 🐙 [GitHub](https://github.com/philgodoy96)
* ✉️ [felipe.godoy.marques@hotmail.com](mailto:felipe.godoy.marques@hotmail.com)

---

## ⚡ Fun Fact

> I built my first AI agent before I fully understood what an embedding was — then I became obsessed with learning how everything actually works. 😅
