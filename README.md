# Hi, I'm Dev 👋

### Full Stack & Forward-Deployed AI Engineer · Open Source Contributor

I build production-grade AI systems and full-stack products, and increasingly contribute fixes **upstream** to the open-source infrastructure I build on.

My work spans autonomous multi-agent systems, Hybrid RAG, HITL workflows, real-time observability, developer tooling, SDKs, databases, and Web3 infrastructure.

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF66?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)](https://claude.ai)
[![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)](https://chatgpt.com)
[![Grok](https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.ai)

---

## 🌍 Open Source Engineering

Open-source contribution is now a core part of my engineering practice: I investigate real upstream issues, reproduce failures, implement focused fixes, add regression coverage, and work through maintainer CI/review workflows.

### Contribution ledgers

- 🧩 **[Non-Web3 OSS Contributions](https://github.com/devtechedge/non-web3-oss-contributions)** - upstream fixes across AI/agent frameworks, developer tooling, databases, runtimes, and JavaScript/Python infrastructure.
- ⛓️ **[Web3 OSS Contributions](https://github.com/devtechedge/web3-oss-contributions)** - upstream fixes across wallets, SDKs, blockchain tooling, protocol infrastructure, and Web3 developer ecosystems.

### Merged upstream contributions

#### Non-Web3

- ✅ **[pnpm #14754](https://github.com/pnpm/pnpm/pull/14754)** - fixed `pnpm run "/pattern/" --no-bail` so one failing matched script no longer cancels its siblings. Non-recursive pattern runs now continue all selected scripts and report the aggregate failure correctly.
- ✅ **[pnpm #14756](https://github.com/pnpm/pnpm/pull/14756)** - fixed `pnpm update <name>@<version>` dropping the dependency's existing `^` or `~` range operator. Updates now preserve the manifest's range style and correctly retain `npm:` / `jsr:` prefixes, including prerelease ranges.
- ✅ **[pnpm #14753](https://github.com/pnpm/pnpm/pull/14753)** - fixed `lockfile: false` being ignored when `devEngines.packageManager.onFail` was `download`. Automatic package-manager switching now works without creating or updating a project `pnpm-lock.yaml`, with persistence moved to the global environment when appropriate.
- ✅ **[Better Auth #11208](https://github.com/better-auth/better-auth/pull/11208)** - added regression coverage for `/phone-number/verify` OpenAPI `requestBody` generation after a Zod intersection had caused the request body to disappear from generated specs. The runtime was unaffected; the fix locks in the expected generated contract.
- ✅ **[SQLMesh #6040](https://github.com/SQLMesh/sqlmesh/pull/6040)** - fixed a concurrency race in `sqlmesh test` where `ModelTest.create_test()` ran on worker threads while `time_machine` was being started or stopped, causing intermittent `IndexError` failures. Test creation now happens before work is submitted to the pool.
- ✅ **[Biome #11667](https://github.com/biomejs/biome/pull/11667)** - added the `useBetterDomTraversing` nursery lint rule, ported from ESLint Unicorn, to flag unnecessary DOM traversal patterns and provide safe transformations where semantics permit.

#### Web3

- ✅ **[thirdweb JS #8938](https://github.com/thirdweb-dev/js/pull/8938)** - fixed `useTokenQuery` swallowing real token lookup failures and incorrectly turning 401, 429, timeout, and other unexpected errors into `unsupported_token`. Genuine failures now reach the existing error and retry path.
- ✅ **[Anza Kit #2032](https://github.com/anza-xyz/kit/pull/2032)** - corrected the `getPatternMatchCodec` advanced guide to use `number` predicates, matching the current codec typing after the related narrowing fix landed.

### Selected upstream ecosystems

**Non-Web3:** pnpm · Biome · SQLMesh · LangGraph.js · Drizzle ORM · CrewAI · node-postgres · TanStack Router · Better Auth · LiveKit Agents · Jinja · Undici · TypeScript-ESLint · Vitest

**Web3:** Safe · Stellar · Wagmi · RainbowKit · ethers.js · Coinbase Wallet SDK · MetaMask SDK · Reown AppKit · Across Protocol · viem · Solana Web3.js · Ambire

> The dedicated contribution repositories contain the detailed PR ledger, status history, issue claims, closed work, and pipeline decisions. Counts there are maintained as snapshots so the profile itself stays focused on engineering signal rather than becoming a contribution database.

---

## 🚀 Flagship Architectures & Projects

- 🔬 **[Synthesis](https://synthesis-gold.vercel.app/)** - Autonomous multi-agent research: plan → research → synthesize → critique → finalize, with HITL gates, RAG, Reflexion, and live SSE agent graphs ([repo](https://github.com/devtechedge/synthesis)).
- 🛡️ **[AEGIS](https://aegis-agent-api.vercel.app/ui)** - Multi-agent operations cortex: LangGraph supervisor + specialist agents, Hybrid RAG, HITL, streaming SSE, FastAPI ([repo](https://github.com/devtechedge/aegis_vercel)).
- 🧠 **[AAROP](https://aarop.vercel.app)** - Explicit Perceive → Plan → Act → Observe → Reflect → Adapt loop with self-verification, bounded autonomy, and replayable traces ([repo](https://github.com/devtechedge/aarop)).
- ⚖️ **[RegTrace](https://regtrace-ai.vercel.app)** - HITL Web3 compliance copilot mapping packs onto MiCA/VARA with retrieval-bounded findings and article citations ([repo](https://github.com/devtechedge/regulatory_compliance)).
- 🏥 **[Cadence](https://cadence-healthcare.vercel.app/)** - Deep-memory healthcare agent lab: multi-layer patient memory, journey stages, consent-scoped clinician briefs ([repo](https://github.com/devtechedge/healthcare-deep-memory-agents)).
- 🔎 **[Veritas](https://veritas-engine-woad.vercel.app/)** - LangGraph research agent with SSE streaming, Gemini + Tavily when keyed, grounded demo mode otherwise ([repo](https://github.com/devtechedge/veritas-engine)).

---

## 🛠️ Tech Stack

| Category | Tooling, Frameworks & Architecture |
| :--- | :--- |
| **AI Systems & Agents** | Python, LangGraph, LangChain, FastAPI, multi-agent supervisors, explicit state machines, Hybrid RAG / pgvector, HITL gates, SSE telemetry, eval & critique loops, Ollama / local LLMs |
| **Full-stack product surface** | TypeScript, Next.js, React, Tailwind, Drizzle / Prisma, Postgres, Supabase, Docker, Vercel |
| **Backend & observability** | SSE streaming, WebSockets, REST, replayable traces, schema validation, demo/live provider toggles |
| **Also in the toolbox** | Node.js, Bun, Stripe, Solidity / Foundry (Base) when the product needs Web3 |

---

## 🎯 Engineering Philosophy

- **Bounded autonomy:** explicit state, validation, cost-aware routing, and HITL for irreversible actions.
- **Retrieval-bounded truth:** citation-backed RAG with hallucination checks.
- **Observable, upstream, production-ready:** inspectable traces, upstream fixes, and tested full-stack systems.
- **Ship the full stack:** durable Python cores with production-style FastAPI/Next surfaces.

---

## 🔗 OSS Contribution Focus

I contribute to production infrastructure across AI agents, developer tooling, TypeScript/Python ecosystems, databases, SDKs, and Web3 infrastructure.

The focus is on **small, concrete upstream improvements that are reproducible, tested, reviewable, and useful to maintainers and users.**

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dev-ma/)
[![X / Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/DevTechEdge)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/devtechedge)

---

<sub>Building production systems, contributing upstream, and learning in public.</sub>
