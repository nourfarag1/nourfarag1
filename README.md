<h1 align="center">Hi, I'm Noureldin 👋</h1>
<h3 align="center">Software Engineer · Backend & Distributed Systems</h3>
 
---
 
## 👨‍💻 About Me
 
I'm a Software Engineer with a Computer Engineering background, currently building backend systems and infrastructure at a B2B SaaS company in Cairo.
 
My day-to-day involves working across a **.NET microservices architecture** — designing background job pipelines, integrating third-party services, building multi-tenant data flows, and occasionally getting my hands dirty with Linux servers, Docker, and CI/CD pipelines. I'm also working on a personal project in **Go** to deliberately push beyond my comfort zone and learn cloud-native patterns from scratch.
 
I think of myself less as a framework specialist and more as someone who solves backend problems — the language and tooling are just the means. Some of the most interesting work I've done had less to do with writing code and more to do with figuring out *what* to build, *where* things should run, and *how* different pieces of a system should talk to each other.
 
I have enough frontend exposure (Angular) to collaborate closely with frontend developers and understand the full picture, but backend and systems work is where I belong.
 
---
 
## 🛠 Tech Stack
 
- **Backend:** REST APIs, CQRS/MediatR, Background Job Orchestration (Hangfire, Quartz.NET), Multi-tenant Architecture, Clean Architecture
- **Languages:** C# · Python · Go *(learning)*
- **Infrastructure:** Docker · Linux · Nginx · MinIO · RabbitMQ · Redis
- **Observability:** Grafana · OpenTelemetry · Serilog
- **Platforms & Tools:** Azure DevOps CI/CD · IIS · Git
- **Databases:** SQL Server · PostgreSQL
---
 
## 📌 Projects
 
### 🔍 [PulseCheck](https://github.com/nourfarrag1/pulsecheck) *(In Progress)*
A website status monitoring SaaS built in **Go/Gin**, designed from scratch as a self-directed learning project covering the full backend infrastructure stack.
 
- Containerized API, background worker, PostgreSQL, and Redis using Docker Compose
- Integrating Nginx as a reverse proxy to isolate internal services from the public internet
- Next: Kubernetes orchestration, load balancing, and distributed caching
> The point of this project isn't the product — it's deliberately learning infrastructure patterns I don't get to use at work every day.
 
---
 
### 🧠 [Vdect — Real-Time Violence Detection System](https://github.com/nourfarag1/Real-Time-Violence-Detection-API)
Graduation project where I served as **technical lead** for a 5-person team. The system detects violence in live video streams using a multi-service pipeline.
 
- Architected a **RabbitMQ + MinIO** data pipeline to stream and buffer video chunks for AI classification
- Re-engineered the inference pipeline into a **hybrid local/cloud model** to solve deployment and latency constraints
- Two interconnected repositories: [API/Orchestration](https://github.com/nourfarag1/Real-Time-Violence-Detection-API) · [Microservices Pipeline](https://github.com/nourfarag1/Violence-Detection-AI-Services) — each with full architecture diagrams and documentation
---
 
### ⚙️ Production Work *(Proprietary — highlights only)*
 
A few things I've built in production that aren't open source:
 
- **Automated DB Backup & Sync System** — Cross-server backup orchestration between Windows production and test environments using MinIO file transfer, internal HTTP signalling, and Hangfire scheduling. Replaced a fully manual RDP-based workflow.
- **Payment Integration** — Full PayTabs payment lifecycle for an online registration feature: price calculation, promo code redemption with multi-tenant isolation, and idempotency logging.
- **Cross-Microservices Job Architecture** — Designed a dynamic Hangfire queue routing system so a single job server could serve multiple microservices projects without duplicating infrastructure.
---
 
## 💡 How I Think About Engineering
 
There's a difference between being a *developer* and being a *software engineer*, and I think about that distinction a lot.
 
A developer writes the code. A software engineer figures out what needs to exist, why, and how all the pieces fit together — then writes the code, or directs someone (or something) else to write it.
 
The work I'm most proud of isn't the lines of code I wrote — it's the problems I had to map out before touching the keyboard. How do two servers transfer files without direct access to each other? How do you make a job scheduler serve multiple services without duplicating it everywhere? How do you design a video pipeline that doesn't collapse under latency constraints?
 
I want to keep working on problems like those. The stack is secondary.
 
---
 
## 📫 Get in Touch
 
- 💼 [LinkedIn](https://www.linkedin.com/in/nourfarag1)
- 📧 [Gmail](mailto:nourfarrag.nh@gmail.com)
---
 
⭐ Feel free to explore the repositories below — the ones worth reading have proper READMEs with architecture diagrams and decision logs.
 
