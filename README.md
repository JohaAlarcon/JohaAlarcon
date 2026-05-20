# 👩‍💻 Johana Alarcón Moya

  **Data Engineer · Full-Stack Engineer · AI-Driven Automation Specialist**

  [Portfolio](https://johana-engineer.framer.ai/) • [LinkedIn](https://www.linkedin.com/in/johana-alarcon-40113360/) •
  [Platzi](https://platzi.com/p/Joalcon4/)

  ---

  ## 💬 About Me
  Hi! I'm **Johana** — an **Electronic Engineer** turned **Data Engineer** turned **Full-Stack Engineer**, with strong
  roots in project management and a relentless bias toward shipping. I built my career designing serverless **GCP** data
  platforms that move millions of records a day, and over the last two years I've extended that practice into
  **production marketplace engineering**: **TypeScript** monorepos, **NestJS** APIs, **Next.js** apps,
  **PostgreSQL/Prisma**, payment gateways, real-time messaging, and infra-as-Docker on bare-metal cloud.


  ---

  ## 🏆 Highlights

  ### Data Engineering & AI
  - **Cloud-Native Pipelines on GCP**: end-to-end design and deployment using Cloud Functions, Cloud Run, Workflows,
  Pub/Sub, Cloud Storage, and managed PostgreSQL — handling millions of records daily.
  - **Automation Orchestration**: large-scale scraping, bulk PDF downloads, OCR, and DB loading with **n8n** and **Google
   Workflows**.
  - **OCR & AI Services**: **Tesseract** (Cloud Run) + **OpenAI** APIs for text extraction, summarization, embeddings,
  and topic classification on >50K legislative documents.
  - **Secure Microservices**: FastAPI + Docker, secured by dynamic Cloud Run ID-tokens for credential-free
  service-to-service calls.
  - **Knowledge Graphs**: semantic graphs of legislative projects, authors, and topics using `text-embedding-3-small`.
  - **Cost & Security Optimization**: fine-grained IAM, VPC connectors, and storage class tuning — cut GCP spend ~40%
  while keeping compliance intact.

  ### Production Marketplace Engineering (Momenta)
  - **Full-stack ownership**: 940+ commits across a **Turborepo monorepo** with a **NestJS** API and **three Next.js
  apps** (buyer web, host portal, admin panel).
  - **Payments**: integrated **Wompi** (Colombia's leading gateway) end-to-end — card pre-auth + capture/void, **PSE**,
  **Nequi**, webhooks with **idempotency**, refunds, and timeout queues.
  - **Asynchronous infrastructure**: **BullMQ** queues on Redis for WhatsApp dispatch, payment timeouts, weekly host
  payouts, gift-card delivery, and email rendering.
  - **Real-time messaging**: **WebSocket** infrastructure for guest↔host chat with unread counters and counter-offer
  flows.
  - **Channels**: **WhatsApp Business API** (Meta Cloud) with NAMED template params, **Resend** transactional email with
  pre-rendered HTML, **GA4** funnel tracking + Consent Mode v2.
  - **Database**: **PostgreSQL** managed across dev/stage/prod via **Prisma** (DB-first workflow, schema-qualified
  migrations, backups before every prod write).
  - **Infra**: **Docker** + **Dokploy** on **Hetzner**, **AWS S3** for media + legal documents (with SHA-256 policy
  hashing and deletion protection), Sentry monitoring, rate limiting, cache-control hardening.
  - **SEO migration**: 301 redirects from a legacy Squarespace catalog to live experiences, canonical-URL hygiene,
  structured prefetch for public pages.

  ---

  ## 🛠️  Skills

  | Area | Tech & Tools |
  | :--- | :--- |
  | **Languages** | Python (Advanced), **TypeScript** (Advanced), SQL (Advanced), JavaScript |
  | **Backend** | **NestJS**, **FastAPI**, REST, WebSockets, Zod validation |
  | **Frontend** | **Next.js** (App Router, RSC), **React**, **React Query** (TanStack v5), **Zustand**, **Tailwind**,
  **shadcn/ui**, atomic design |
  | **Data Engineering** | GCP (Cloud Run, Cloud Functions, Workflows, Pub/Sub, Cloud Storage), Docker, dbt, Apache
  Airflow, CrateDB |
  | **Databases** | **PostgreSQL** (managed + self-hosted), **Prisma ORM**, Snowflake, MySQL, SQLite, Redis |
  | **Async & Messaging** | **BullMQ**, Redis Streams, WebSockets, cron jobs |
  | **Payments & Integrations** | **Wompi** (Colombia — cards, PSE, Nequi, webhooks, refunds), **WhatsApp Business API**
  (Meta Cloud), **Resend**, Google OAuth, **GA4** + Consent Mode v2 |
  | **Automation / Orchestration** | **n8n**, Google Workflows |
  | **NLP & AI** | OpenAI GPT, `text-embedding-3-small`, spaCy, LangChain |
  | **OCR** | Tesseract (+ custom Cloud Run wrapper) |
  | **Infra & DevOps** | Docker, **Hetzner**, **Dokploy**, **AWS S3**, Sentry, VPC, IAM, GitHub Actions,
  Husky/lint-staged |
  | **Testing** | **Vitest**, Jest, **Playwright** (E2E), integration testing on real DBs |
  | **Data Viz / BI** | Metabase, Looker Studio, Power BI, Kepler.gl |
  | **Dev Tools** | Git, GitHub, **Turborepo**, **pnpm workspaces**, Poetry, VS Code, **Claude Code** |

  ---

  ## 🌱 Currently Learning
  - Advanced **LangGraph / CopilotKit** patterns for agentic workflows.
  - **Vertex AI** pipelines for scalable model serving on GCP.
  - **Next.js 16 Cache Components** and PPR (Partial Prerendering).
  - **React 19** composition patterns (compound components, server actions).

  ---

  ## 👩‍💼 Professional Experience

  ### **Full-Stack Engineer @ Pyxus Ft Momenta**
  *2025 – Present · Bogotá (Remote)*
  - Engineer shipping a multi-tenant **experiences marketplace** (buyer + host + admin) on a Turborepo monorepo:
  NestJS API + 3 Next.js apps + Prisma/PostgreSQL.
  - Designed and integrated the full **Wompi payments** pipeline (card pre-auth, capture/void, PSE, Nequi, webhooks with
  idempotency, refunds) feeding a BullMQ-driven booking and gift-card flow.
  - Built **real-time messaging** between guests and hosts (WebSockets + unread-count denormalization + admin
  conversation monitor with CSV export).
  - Built **host payouts** as a weekly BullMQ cron with PDF statement generation and Resend email dispatch.
  - Operated production: SSH + Docker on Hetzner via Dokploy, S3 buckets per env, schema-qualified Postgres migrations
  across dev/stage/prod with backup-first protocol.
  - Migrated SEO from a legacy Squarespace catalog (301 redirects, canonical URLs, GA4 Consent Mode v2 rollout).

  ### **Data Engineer · AI & Cloud Automation Specialist @ iMakia / Kitsune**
  *Oct 2023 – Present*
  - Architected a **GCP serverless data platform** powering legislative-intelligence products across LATAM.
  - Implemented multi-stage ETL/ELT pipelines with Cloud Run + Workflows, cutting manual processing time by **80%**.
  - Deployed OCR & NLP microservices (Tesseract + OpenAI) generating metadata, summaries, and embeddings for **>50K**
  documents.
  - Led cost-optimization (storage tiering + idle-instance scheduling): monthly GCP spend **$1.2k → $700**.

  ### **Service Center Director @ ISEC SA**
  *Apr 2022 – May 2023*
  - Managed electronic-security projects for public & private sector clients (incl. Ecopetrol).
  - Introduced data-driven KPIs (Excel + Power BI), boosting SLA adherence by **15%**.

  ### **Project Professional & Support Engineer @ ISEC SA**
  *Feb 2012 – Mar 2022*
  - Oversaw maintenance of **>1,000** surveillance devices; reduced MTTR by **25%**.
  - Championed root-cause analysis culture across field teams.

  ---

  ## 📚 Certifications
  - **Big Data Certified Professional** — Talento Tech MINTIC (Oct 2024)
  - **Data Analytics Certified Professional** — Talento Tech MINTIC (Oct 2024)
  - **Project Management Master** — ENEB (May 2023)
  - **Data Analysis with Python** — Platzi (Jun 2023)

  ---

  ## 🌐 Community
  - **PyLadies Bogotá** — Active Member
  - **Python Colombia** — Contributor
  - Volunteer — **JS Conf CO 2023**, **PyCon CO 2024**
  - Creator — **FastAPI Workshop Chapter**

  ---

  ## 📫 Contact
  - **Email:** johana.alarcon.tech@gmail.com
  - **Location:** Bogotá, Colombia
  - **Phone:** +57 317 292 1350
