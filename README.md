<h1 align="center">Hi, I'm Pratik Nikat 👋</h1>

<p align="center">
  <b>Engineering Trainee @ Intangles Lab</b> · Backend & distributed systems · Building AI agents
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/pratiknikat"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/Pratik034575706"><img src="https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white" alt="X"></a>
  <a href="mailto:pratiknikat07@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Pune,_India-555?style=flat&logo=googlemaps&logoColor=white" alt="Pune, India">
</p>

---

### About me

I'm a backend engineer with **1.7+ years** of experience building backend systems: event pipelines, real-time services, and the infrastructure under them. At work I build industrial IoT backends. Outside work I build developer tools, mostly around observability and AI agents that do real engineering work.

- 🏢 Engineering Trainee at **Intangles Lab**, building industrial IoT backend services
- 🧠 Interested in distributed systems, observability, and LLM agents
- 🎓 B.Tech in Computer Science, **PCCOE Pune** (2025)
- 📫 Open to interesting backend, infra, and AI-tooling work. Email me at **pratiknikat07@gmail.com**

---

### 💼 Experience

**Engineering Trainee · [Intangles Lab](https://www.intangles.ai)** · Pune · *Jun 2025 – Present* (Software Engineer Intern, Mar – Jun 2025)
- Backend services in Node.js for an industrial IoT platform, built on Kafka, RabbitMQ, and MQTT
- Storage across PostgreSQL / TimescaleDB, MongoDB, and Elasticsearch, with a focus on time-series data and query performance
- Microservice design and inter-service messaging in a high-volume telemetry environment

**Full Stack Developer · Champhunt** · Remote (California, USA) · *May 2024 – Dec 2024*
- Built features for a fantasy-cricket and social platform on the MERN stack: real-time group chat, story sharing, and tiered subscriptions
- Scaled the platform to 10,000+ concurrent users
- Containerized services with Docker and set up Jenkins CI/CD, which cut deploy time by about 60%

---

### 🚀 What I've been building

#### Modlex: observability and incident management with an AI investigator
One place for logs, metrics, traces, session replay, error tracking, and on-call. When an alert fires, an **AI investigation agent** queries logs, traces, metrics, and infra state, then writes a root-cause analysis. Every step it takes is visible.
- Alert ingestion from PagerDuty, Datadog, Prometheus, Grafana, CloudWatch, and more, with fingerprint dedup and cross-service correlation
- On-call schedules, escalation policies, runbook matching, auto-remediation with human approval, and AI-written postmortems
- OTLP ingestion in **Go** (Kafka → ClickHouse), Node.js microservices, React / Next.js frontends, an MCP server and a CLI, deployed with Kubernetes, Helm, and Terraform

`Go` `TypeScript` `Node.js` `ClickHouse` `Kafka` `Redis` `MongoDB` `OpenTelemetry` `Kubernetes` `Claude / Bedrock`

#### mini4: an autonomous bug-fixing agent
Click **"Fix with mini4"** on a Jira, Linear, or GitHub ticket. In an isolated container on the customer's own AWS account, mini4 **reproduces the bug as a failing test**, fixes it, verifies the fix in a clean environment, gets an independent review, and opens a PR that explains the change. Developers can then ask `@mini4 why…?` on the PR.
- Multi-tenant control plane with Postgres row-level security, RBAC, and a hash-chained audit log
- GitHub App, Jira Forge app, Linear, and ClickUp integrations, with signed work orders between the control plane and a **Go** runner
- Code and memory stay in the customer's AWS (EC2 + S3 under their KMS key). The control plane only sees metadata

`TypeScript` `Fastify` `Next.js` `PostgreSQL` `Drizzle` `Go` `AWS` `Terraform` `Claude Code`

<sub>Both repos are private. I'm happy to walk through them on a call.</sub>

---

### 🛠️ Tech stack

**Languages**<br>
<img src="https://skillicons.dev/icons?i=go,ts,js,py,cpp,swift,dart" alt="Languages">

**Backend & messaging**<br>
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,fastapi,kafka,rabbitmq" alt="Backend">

**Frontend & mobile**<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,flutter" alt="Frontend and mobile">

**Data**<br>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,elasticsearch" alt="Data"><img src="assets/icons/clickhouse.svg" alt="ClickHouse" title="ClickHouse"><img src="assets/icons/timescaledb.svg" alt="TimescaleDB" title="TimescaleDB">

**Cloud, infra & observability**<br>
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,ansible,githubactions,jenkins,prometheus,grafana,linux" alt="Infra">

**AI & agents:** Claude API / Amazon Bedrock, OpenAI, Model Context Protocol (MCP), Claude Code, agent evals

---

<p align="center"><i>Always up for a conversation about distributed systems, observability, or AI agents. Feel free to reach out.</i></p>
