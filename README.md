# Hi! I'm Abdullah Romli Mubarrok  👋

**Senior Lead IT Developer @ PT Home Credit Indonesia — FinTech** | Jakarta / Depok, Indonesia

I researched and implemented a migration from a PHP monolith to **20+ independently deployed React + TypeScript micro-frontend services**, built 7 of them for loan and repayment collection workflows, and run the operations that keep them alive for **300+ active users** — CI/CD, delivery, on-call incident response and security remediation.

Outside work I build and ship complete products end-to-end: backend, frontend, database, tests, CI/CD, live deploy.

## ⚡ Tech Stack

`React 18/19` `TypeScript` `Next.js App Router` `Module Federation` `Node.js` `NestJS` `Fastify` `Prisma` `Oracle SQL / PL/SQL` `PostgreSQL` `Redis` `PHP` `Python` `GitHub Actions` `Docker` `Linux`

## 🚀 What I'm building now

### 💳 QUPI — fintech wallet + paylater
- **[qupi-backend](https://github.com/adul11s/qupi-backend)** — modular-monolith **NestJS 11 + Prisma** service: double-entry ledger as source of truth (57/57 ledger invariant tests), idempotency with fingerprint binding (409 on mismatch), PIN/OTP hashing with scrypt + salt, global session guard, reconciliation job, outbox pattern, audit log, OpenAPI. Benchmarked honestly: **2,400 requests, 0 errors**. CI runs e2e against **real Postgres + Redis** service containers.
- **[qupi-apps](https://github.com/adul11s/my-fintech-project)** — **Next.js multi-zone micro-frontend** frontend on that API: a container shell composing wallet and credit zones via `rewrites()`, with top-up / transfer / QRIS / tags / paylater flows, a sandbox banner and documented known gaps. The same micro-frontend pattern as the enterprise CRS suite, at portfolio scale.

### 🕌 TPQ Qur'ani — public website + role-based CMS
*Live: [tpq-qurani-portfolio.vercel.app](https://tpq-qurani-portfolio.vercel.app) · API: [tpq-api.onrender.com](https://tpq-api.onrender.com) — source repos private, reviewer access on request.*
- **tpq-web** — **Next.js 16 + React 19 + TypeScript + Tailwind**: bilingual (ID/EN) public site, class profiles, downloadable-resource dashboard, enrollment inquiries, CMS-driven content so staff publish without a deploy. **316 tests** + Playwright e2e.
- **tpq-api** — **Fastify 5 + Prisma 7 + PostgreSQL + Redis + MinIO**: signed-URL downloads, RBAC CMS (CRUD, publish workflow, media, audit trail, retention), 2FA, rate limiting, magic-byte upload validation. **224 integration tests against real Postgres/Redis/MinIO**, not mocks.
- **tpq-docs** — PRD, system/analyst design, QA plan, security review, ADRs and 167 HTML mockups kept as versioned process artefacts.
- CI gates lint → test → build on every push; a scheduled uptime probe checks `/health` every 6 hours.

## 🧩 Other projects

- 👓 **[optic-luxe](https://github.com/adul11s/optic-luxe)** — premium optical e-commerce with AR virtual try-on (Three.js + MediaPipe), POS & inventory — full-stack TypeScript
- 🏨 **[vouch-handover](https://github.com/adul11s/vouch-handover)** — AI-powered night-shift handover service for hotels (Node.js + TypeScript), with an evaluation harness
- ❄️ **[frozenfood-pos](https://github.com/adul11s/frozenfood-pos)** — offline-ready PWA POS for retail (React + TS + Vite)
- 🏫 **[sdit-bustanul-huda](https://github.com/adul11s/sdit-bustanul-huda-frontend)** — full-stack school management system (React 19 + Express + TS)
- 📔 **[diary-teachlife](https://github.com/adul11s/diary-teachlife)** — teacher journaling app

*Every repo above ships with a green CI badge, a README that states plainly what is and isn't finished, and tests that run against real services where it matters.*

## 💼 Open To Work

Senior / Staff **Full-Stack**, **Frontend**, or **Tech Lead** roles — Jakarta (on-site), remote, or overseas with housing provided.

- 📫 abdullahromli11@gmail.com
- 💼 [linkedin.com/in/abdullah-romli-mubarrok](https://www.linkedin.com/in/abdullah-romli-mubarrok/)

![](https://komarev.com/ghpvc/?username=adul11s&style=flat-square&color=2c5364)
