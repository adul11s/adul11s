# Hi! I'm Abdullah Romli Mubarrok  👋

**Senior Lead IT Developer @ PT Home Credit Indonesia — FinTech** | Jakarta / Depok, Indonesia

I researched and implemented a migration from a PHP monolith to **20+ independently deployed React + TypeScript micro-frontend services**, built 7 of them for loan and repayment collection workflows, and run the operations that keep them alive for **300+ active users** — CI/CD, delivery, on-call incident response and security remediation.

Outside work I build and ship complete products end-to-end: backend, frontend, database, tests, CI/CD, live deploy.

**Portfolio & case studies → [abdullah-romli-portfolio.vercel.app](https://abdullah-romli-portfolio.vercel.app)** · **CV → [PDF](https://abdullah-romli-portfolio.vercel.app/cv.pdf)**

## ⚡ Tech Stack

`React 18/19` `TypeScript` `Next.js App Router` `Module Federation` `Node.js` `NestJS` `Fastify` `Prisma` `Oracle SQL / PL/SQL` `PostgreSQL` `Redis` `PHP` `Python` `GitHub Actions` `Docker` `Linux`

## 🚀 Flagship work

### 💳 QUPI — fintech wallet + paylater
- **[qupi-backend](https://github.com/adul11s/qupi-backend)** · [v1.0.0](https://github.com/adul11s/qupi-backend/releases/tag/v1.0.0) · MIT — modular-monolith **NestJS 11 + Prisma** service: double-entry ledger as the source of truth (**57/57 invariant tests**), idempotency keys bound to request fingerprints (409 on mismatch, never a double charge), PIN/OTP hashed with scrypt + per-record salt, global session guard, reconciliation job, outbox pattern, audit log, OpenAPI. Benchmarked honestly: **2,400 requests, 0 errors**. e2e runs against **real Postgres + Redis** service containers in CI.
- **[qupi-apps](https://github.com/adul11s/qupi-apps)** · [v1.0.0](https://github.com/adul11s/qupi-apps/releases/tag/v1.0.0) · MIT — **Next.js multi-zone micro-frontend** on that API: a container shell composing wallet and credit zones via `rewrites()`, one typed `packages/api-client` contract, a sandbox banner and documented known gaps. The same micro-frontend pattern as the enterprise CRS suite, at portfolio scale.

### 🕌 TPQ Qur'ani — public website + role-based CMS *(live)*
*Site: [tpq-qurani-portfolio.vercel.app](https://tpq-qurani-portfolio.vercel.app) · API: [tpq-api.onrender.com](https://tpq-api.onrender.com/health) — source repos private to keep client content out of public view; **reviewer access on request**.*
- **tpq-web** — **Next.js 16 + React 19 + TypeScript + Tailwind**: bilingual (ID/EN) public site, class profiles, downloadable-resource dashboard, enrollment inquiries, CMS-driven content so staff publish without a deploy. **316 tests** + Playwright e2e.
- **tpq-api** — **Fastify 5 + Prisma 7 + PostgreSQL + Redis + MinIO**: signed-URL downloads, RBAC CMS (CRUD, publish workflow, media, audit trail, retention), 2FA, rate limiting, magic-byte upload validation. **224 integration tests against real Postgres/Redis/MinIO**, not mocks.
- **tpq-docs** — PRD, system/analyst design, QA plan, security review, ADRs and 167 HTML mockups kept as versioned process artefacts.
- CI gates lint → test → build on every push; a scheduled uptime probe checks `/health` every 6 hours.

## 🧩 Other projects

- 👓 **[optic-luxe](https://github.com/adul11s/optic-luxe)** · [v1.0.0](https://github.com/adul11s/optic-luxe/releases/tag/v1.0.0) · MIT — premium optical e-commerce with AR virtual try-on (Three.js + MediaPipe), POS and inventory; 44 database integration tests against a PostgreSQL service container
- 🏨 **[vouch-handover](https://github.com/adul11s/vouch-handover)** · [v1.0.0](https://github.com/adul11s/vouch-handover/releases/tag/v1.0.0) · MIT — AI night-shift handover service for hotels, with a cross-night reconciler, prompt-injection defence and an evaluation harness
- ❄️ **[frozenfood-pos](https://github.com/adul11s/frozenfood-pos)** — offline-ready PWA point of sale (React + TS + Vite, Google Sheets backend)
- 🏫 **[sdit-bustanul-huda](https://github.com/adul11s/sdit-bustanul-huda-frontend)** — school management system for an Indonesian Islamic school (React 19 + Express + TypeScript)
- 📔 **[diary-teachlife](https://github.com/adul11s/diary-teachlife)** — teacher journaling app with a read-only parent view

## ✅ How to verify any claim in this profile in two minutes

1. Open [qupi-backend](https://github.com/adul11s/qupi-backend) → the **CI badge** and the **v1.0.0 release notes** are the receipts for the ledger and benchmark numbers.
2. Open [tpq-qurani-portfolio.vercel.app](https://tpq-qurani-portfolio.vercel.app) → the site is running now; [tpq-api.onrender.com/health](https://tpq-api.onrender.com/health) returns `{"status":"ok"}` (cold start on the free tier can take ~20s).
3. Check the commit history — including this profile — anything stated here traces to a commit, a test count or a live endpoint.

*Every repo above has a green CI badge, a README that states plainly what is and isn't finished, and tests that run against real services where it matters.*

## 💼 Open To Work

Senior / Staff **Full-Stack**, **Frontend**, or **Tech Lead** roles — Jakarta (on-site), remote, or overseas with relocation support.

- 📫 **abdullahromli11@gmail.com**
- 💼 [linkedin.com/in/abdullah-romli-mubarrok](https://www.linkedin.com/in/abdullah-romli-mubarrok/)
- 🌐 [abdullah-romli-portfolio.vercel.app](https://abdullah-romli-portfolio.vercel.app)

![](https://komarev.com/ghpvc/?username=adul11s&style=flat-square&color=2c5364)
