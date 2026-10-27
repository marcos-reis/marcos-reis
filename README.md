# Hi, I'm Marcos Reis 👋

**Senior Software Engineer | Backend, Distributed Systems & GenAI in Production**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos-reis-santos)
[![Focus](https://img.shields.io/badge/Focus-Event--Driven%20Architecture%20%7C%20Production%20GenAI%20%7C%20FinOps-blue?style=flat-square)](#)
[![Experience](https://img.shields.io/badge/Experience-7%2B%20Years%20in%20Production-emerald?style=flat-square)](#)

I design and build resilient, scalable backend architectures and cost-efficient Generative AI systems that solve real business bottlenecks. With **7+ years of experience** across SaaS scale-ups and B2B consulting, I operate end-to-end — from diagnosing database and latency bottlenecks to architecting event-driven pipelines and deploying agentic workflows with strict FinOps, evaluation, and reliability controls.

> *"Software isn't born ready; it evolves. Through architecture, observability, and automated testing, we make that evolution safe."*

---

### ⚡ What I Do Best (Core Engineering Pillars)

- **Distributed Backend & Event-Driven Architecture (EDA):** High-throughput asynchronous processing (`AWS SQS`, `Redis`, `Kubernetes Workers`), strict idempotency, Circuit Breakers, Claim Check pattern, and multi-tenant SaaS design primarily in **Node.js / TypeScript**, combined with production systems in **Go (Golang)**, **Python**, **C# (.NET)**, and **PHP/Laravel**.
- **Production GenAI & FinOps Engineering:** Multi-stage progressive cost funnels, **Advanced RAG** (Hierarchical Markdown parsing, Semantic Splitting, Query Rewriting, `pgvector` / `Qdrant`), **LLM Gateways** (`LiteLLM` multi-model routing & fallbacks), automated regression **Evals** (*LLM-as-a-Judge*), and **Guardrails** (`NeMo` / PII masking).
- **Forward Deployed Engineering (FDE) & Domain Modernization:** Diving directly into complex business domains (GovTech, FinOps, Creator Economy, Enterprise Comms, ERP) to replace fragile synchronous bottlenecks and manual spreadsheets with auditable, high-availability software.

---

### 🏗️ Featured Architectural Case Studies

Rather than maintaining dozens of generic toy PoCs, this profile showcases **deep architectural case studies, ADRs (Architectural Decision Records), and resilience labs** based on real-world production engineering:

#### 1. 🏛️ [GovTech AI Pipeline — 8-Stage Progressive Funnel & Self-Learning PDF Engine](https://github.com/marcos-reis/govtech-ai-pipeline)
* **The Challenge:** Triaging thousands of daily public tenders (100+ page PDFs) across all 27 Brazilian states without bankrupting the LLM token budget, getting IP-banned by government WAFs, or crashing servers with PyTorch/OCR memory leaks.
* **The Architecture:** Dual zero-token lexical gates (~85% immediate discard), self-learning PDF table extraction by agency CNPJ (*Direct Pass* via C++ `poppler-utils`), Dual Circuit Breakers + 10-IP LRU Proxy Pool, and ephemeral Python RAG workers (`Docling` + `LlamaIndex` + `malloc_trim(0)`).
* **Impact:** **~98% reduction in token costs**, 24/7 autonomous nationwide ingestion, and zero memory leaks on lean AWS EC2 infrastructure.
* 📄 **[Read the 5 ADRs, Mermaid Diagrams & Sanitized Code →](https://github.com/marcos-reis/govtech-ai-pipeline)**

---

### 🛠️ Tech Stack & Tooling

* **Languages & Frameworks:** `Node.js` • `NestJS` • `TypeScript` • `Go (Golang)` • `Python (FastAPI)` • `C# (.NET)` • `PHP (Laravel)` • `React / Next.js`
* **Architecture & Messaging:** `Event-Driven Architecture (EDA)` • `Microservices & Modular Monoliths` • `AWS SQS` • `Redis` • `Circuit Breakers` • `Idempotency` • `REST & Webhooks`
* **GenAI & Data Engineering:** `Agentic Workflows` • `Advanced RAG` • `LlamaIndex` • `Docling` • `LiteLLM` • `Qdrant` • `PostgreSQL (pgvector)` • `Evals (LLM-as-a-Judge)` • `NeMo Guardrails` • `ETL Pipelines`
* **Data, Cloud & DevOps:** `PostgreSQL` • `MySQL` • `MongoDB` • `DynamoDB` • `MinIO / S3` • `AWS (ECS, Lambda, SQS, EC2)` • `GCP (Cloud Run)` • `Kubernetes` • `Docker` • `GitHub Actions`

---

### 🏕️ Beyond the Terminal

I believe the best architectures are built by well-rested minds. When the notebook closes, my focus is 100% on my family, exploring nature, road trips, and recharging by the beach or countryside.

---

<details>
<summary><b>🇧🇷 Versão em Português (Resumo Executivo) — Clique para expandir</b></summary>
<br/>

**Engenheiro de Software Sênior | Backend, Sistemas Distribuídos & GenAI em Produção**

Engenheiro de Software Sênior com **+7 anos de experiência** especializado na arquitetura de plataformas SaaS escaláveis, sistemas orientados a eventos (EDA) e engenharia de IA Generativa em produção. Atuo de ponta a ponta — do diagnóstico de gargalos e desenho arquitetural à sustentação em nuvem — com foco principal em **Node.js / TypeScript**, somado à atuação prática em **Go**, **Python**, **C# (.NET)** e **PHP/Laravel**.

- **Arquitetura Backend & Mensageria:** Desenho de microsserviços e monólitos modulares, processamento assíncrono de alta vazão (`AWS SQS`, `Redis`, `Workers em Kubernetes`), controle estrito de idempotência, resiliência (`Circuit Breakers`, `DLQ/retries`) e desacoplamento de sistemas legados.
- **Engenharia de GenAI & FinOps:** Arquiteturas agênticas, funis progressivos de redução de custo de inferência, **RAG Avançado** (indexação hierárquica em Markdown, divisão semântica, *Query Rewriting*, `pgvector`/`Qdrant`), **LLM Gateways** (`LiteLLM`), **Evals** (*LLM-as-a-Judge*) e segurança/LGPD (`NeMo Guardrails`).
- **Engenharia Forward Deployed (FDE):** Imersão em dores operacionais e de negócio reais para substituir processos manuais e gargalos síncronos por motores transacionais confiáveis e auditáveis.

</details>

---

### 🤝 Let's Connect!

Always open to discussing software architecture, distributed systems, production GenAI, and high-impact engineering opportunities or consulting engagements.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect%20with%20me-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcos-reis-santos)
