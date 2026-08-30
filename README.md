<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0D1117,55:0E7490,100:2DD4BF&text=Shakti%20Prasad%20Ram&fontColor=F8FAFC&fontSize=42&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20GenAI%20%E2%80%A2%20Backend%20%E2%80%A2%20Technical%20SEO&descAlignY=58&animation=fadeIn" alt="Shakti Prasad Ram — Software Engineer" />
</div>

<div align="center">
  <a href="https://shakti-portfolio-xi.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-0F766E?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/shaktiram22">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:shaktiram.lucifer@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<p align="center">
  <strong>SDE I / SDE II-focused engineer building reliable AI products, observable backend systems, and search-ready web platforms.</strong>
</p>

## Engineering beyond the demo

I build the parts that make software dependable after the happy path: tenant boundaries, background delivery, idempotency, failure recovery, local-first privacy, measurable performance, and release verification.

My current work sits at the intersection of:

- **GenAI and agent orchestration** — RAG, vector retrieval, tool-driven agents, OpenAI/Codex integration, OpenClaw workflows, delegation, validation, and approval gates.
- **Backend and distributed systems** — Node.js, Fastify, Express, Python, FastAPI, MongoDB, Redis Streams/Pub/Sub, SSE, RBAC, JWT, transactional outbox, and local SDK evaluation.
- **Observability and delivery** — OpenTelemetry, Prometheus, Grafana, structured logging, Docker, CI, load testing, and failure drills.
- **Technical SEO and edge deployment** — Astro, structured data, canonical URLs, sitemaps, Core Web Vitals, PWA/offline behavior, CSP, and Cloudflare Pages.
- **Systems engineering** — Linux interfaces, Python CLI/GTK tooling, C++ networking, concurrency, sockets, and LRU caching.

> I prefer evidence over adjectives: tested failure modes, explicit security boundaries, reproducible benchmarks, and honest limitations.

## Current direction: approval-first AI orchestration

```text
Ask → Plan → Delegate → Execute → Validate → Deliver
```

I am exploring local AI mission-control systems where agents use typed tools, delegate bounded work, preserve durable task history, and pause before consequential actions. The focus is not just autonomous execution—it is controllable, inspectable execution.

<div align="center">
  <img src="https://img.shields.io/badge/OpenAI-Agent_Systems-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI agent systems" />
  <img src="https://img.shields.io/badge/OpenClaw-Orchestration-0F766E?style=flat-square" alt="OpenClaw orchestration" />
  <img src="https://img.shields.io/badge/RAG-Retrieval_%2B_Generation-0891B2?style=flat-square" alt="Retrieval augmented generation" />
  <img src="https://img.shields.io/badge/Agents-Approval_First-F59E0B?style=flat-square" alt="Approval-first agents" />
</div>

## Selected engineering work

| Project | What it demonstrates | Core stack |
| --- | --- | --- |
| [**Northstar Feature Flag Platform**](https://github.com/Shaktiprasadram22/feature-flag-platform) | Multi-tenant control/data planes, deterministic rollouts, transactional outbox, Redis delivery, SSE, local SDK decisions, RBAC, observability, E2E and load tests | TypeScript, Fastify, MongoDB, Redis, React, OTel, Docker |
| [**DeviceLab**](https://github.com/Shaktiprasadram22/device-lab) | 30 private browser hardware tests, 9 guided inspections, local reports, offline PWA, accessible UX, and static edge deployment with no application backend | Astro, TypeScript, IndexedDB, Web APIs, Cloudflare Pages |
| [**ASUS TUF RGB**](https://github.com/Shaktiprasadram22/asus-tuf-rgb) | Dependency-free Linux hardware control through upstream kernel interfaces, safe session writes, verified profiles, GTK UI, and systemd integration | Python, GTK 4, Linux sysfs, systemd |
| [**UMS RAG Chatbot**](https://github.com/Shaktiprasadram22/Ums_chatbot_01) | University knowledge retrieval with semantic search and context-aware responses across a full-stack application | React, Express, Python, LangChain, FAISS, OpenAI |
| [**Multi-threaded Proxy Server**](https://github.com/Shaktiprasadram22/MultiThreadedProxyServer) | Concurrent socket handling and a thread-safe LRU cache in a systems-level HTTP proxy | Modern C++, POSIX sockets, threads |
| [**SentinelDataCore**](https://github.com/Shaktiprasadram22/SentinelDataCore) | Authenticated REST APIs, bulk operations, role boundaries, persistence, and application-level caching | Node.js, Express, MongoDB, JWT |

### Measured systems evidence

The Northstar platform includes reproducible local benchmarks—not production SLO claims:

- **1,269,098 local SDK evaluations/second** across a 1,000,000-evaluation run.
- **6.09 ms p95** for authenticated configuration reads.
- **254.27 ms p95** commit-to-local-SDK propagation after isolating a Redis blocking-connection bottleneck.

The repository includes the benchmark commands, host context, thresholds, failure scenarios, ADRs, and trade-offs behind those numbers.

## Toolbox

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,cpp,nodejs,fastapi,react,nextjs,astro" alt="Languages and frameworks: TypeScript, JavaScript, Python, C++, Node.js, FastAPI, React, Next.js, Astro" />
  <br />
  <img src="https://skillicons.dev/icons?i=mongodb,redis,docker,linux,cloudflare,grafana,git,github,githubactions" alt="Infrastructure and tools: MongoDB, Redis, Docker, Linux, Cloudflare, Grafana, Git, GitHub, GitHub Actions" />
</div>

<br />

| Area | What I work with |
| --- | --- |
| **AI systems** | RAG pipelines, embeddings, vector search, prompt/tool contracts, agent routing, evaluation, approval-first orchestration |
| **Backend** | REST APIs, SSE, background jobs, caching, authentication, authorization, multi-tenancy, event delivery |
| **Reliability** | Idempotency, retry/DLQ, last-known-good state, health checks, metrics, traces, logs, load tests |
| **Web products** | React, Astro, accessible UI, browser APIs, IndexedDB, PWA, privacy-first client processing |
| **SEO and edge** | Crawlable static architecture, Schema.org, metadata, canonical/sitemap strategy, Cloudflare Pages, performance budgets |

## How I approach a system

```text
Correctness first
  ├── define ownership and trust boundaries
  ├── make failure and recovery explicit
  ├── measure the critical path
  ├── automate the release gate
  └── document what the system cannot guarantee
```

## GitHub activity

<div align="center">
  <img width="96%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Shaktiprasadram22&theme=github_dark" alt="Shakti's GitHub contribution summary" />
</div>

<div align="center">
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Shaktiprasadram22&theme=github_dark" alt="Shakti's GitHub statistics" />
  <img height="175" src="https://streak-stats.demolab.com?user=Shaktiprasadram22&hide_border=true&background=0D1117&ring=2DD4BF&fire=F59E0B&currStreakLabel=2DD4BF&sideLabels=CBD5E1&dates=64748B&currStreakNum=F8FAFC&sideNums=F8FAFC" alt="Shakti's contribution streak" />
</div>

## Let’s build something real

I am interested in software engineering, GenAI/backend, platform, and AI-agent work where system design and implementation both matter.

<div align="center">
  <a href="mailto:shaktiram.lucifer@gmail.com">
    <img src="https://img.shields.io/badge/Discuss_an_opportunity-Email_me-0F766E?style=for-the-badge" alt="Email Shakti about an opportunity" />
  </a>
</div>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:2DD4BF,50:0E7490,100:0D1117" alt="" />
</div>
