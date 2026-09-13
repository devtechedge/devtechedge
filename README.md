# Hi, I'm Dev 👋

### Full Stack AI Native Engineer · Open Source Contributor

I build production-grade AI and full-stack systems, while contributing fixes upstream to the infrastructure I build on.

My work spans autonomous multi-agent systems, explicit state machines, Hybrid RAG, memory and evaluation, observability, developer tooling, distributed systems, and Web3 infrastructure.

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178B9?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF6E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)](https://claude.ai)
[![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)](https://chatgpt.com)

---

## 🌍 Open Source Engineering

### OSS Contributions

**[OSS Contributions](https://github.com/devtechedge/oss-contributions)** is the canonical ledger of my upstream open-source work across developer tooling, frameworks, databases, runtimes, infrastructure, wallets, SDKs, and blockchain software.

The repository is intentionally structured as a contribution portfolio rather than a simple list of links: it separates merged work, active work, provenance, upstream issue context, implementation details, and repository-level coverage.

### Selected merged contributions

<table>
<tr><td><img src="https://github.com/anza-xyz.png?size=32" width="28" height="28" alt="Anza"></td><td>✅ <strong><a href="https://github.com/anza-xyz/kit/pull/2032">Anza Kit #2032</a></strong> — corrected the <code>getPatternMatchCodec</code> advanced guide to match current codec typing.</td></tr>
<tr><td><img src="https://github.com/better-auth.png?size=32" width="28" height="28" alt="Better Auth"></td><td>✅ <strong><a href="https://github.com/better-auth/better-auth/pull/11208">Better Auth #11208</a></strong> — added regression coverage for missing OpenAPI <code>requestBody</code> generation after a Zod intersection.</td></tr>
<tr><td><img src="https://github.com/biomejs.png?size=32" width="28" height="28" alt="Biome"></td><td>✅ <strong><a href="https://github.com/biomejs/biome/pull/11667">Biome #11667</a></strong> — added the <code>useBetterDomTraversing</code> nursery lint rule with safe transformations where semantics permit.</td></tr>
<tr><td><img src="https://github.com/brianc.png?size=32" width="28" height="28" alt="node-postgres"></td><td>✅ <strong><a href="https://github.com/brianc/node-postgres/pull/3772">node-postgres #3772</a></strong> — fixed <code>Connection.sync()</code> incorrectly setting the internal <code>_ending</code> flag, preventing false suppression of subsequent socket errors.</td></tr>
<tr><td><img src="https://github.com/pnpm.png?size=32" width="28" height="28" alt="pnpm"></td><td>✅ <strong><a href="https://github.com/pnpm/pnpm/pull/14754">pnpm #14754</a></strong> — fixed non-recursive pattern runs with <code>--no-bail</code> so matching scripts continue executing and failures are aggregated correctly.</td></tr>
<tr><td><img src="https://github.com/pnpm.png?size=32" width="28" height="28" alt="pnpm"></td><td>✅ <strong><a href="https://github.com/pnpm/pnpm/pull/14756">pnpm #14756</a></strong> — preserved existing dependency range operators and protocol prefixes during <code>pnpm update</code>.</td></tr>
<tr><td><img src="https://github.com/pnpm.png?size=32" width="28" height="28" alt="pnpm"></td><td>✅ <strong><a href="https://github.com/pnpm/pnpm/pull/14753">pnpm #14753</a></strong> — fixed <code>lockfile: false</code> being ignored during automatic package-manager switching.</td></tr>
<tr><td><img src="https://github.com/SQLMesh.png?size=32" width="28" height="28" alt="SQLMesh"></td><td>✅ <strong><a href="https://github.com/SQLMesh/sqlmesh/pull/6040">SQLMesh #6040</a></strong> — fixed a concurrency race in <code>sqlmesh test</code> involving <code>time_machine</code> and worker threads.</td></tr>
<tr><td><img src="https://github.com/thirdweb-dev.png?size=32" width="28" height="28" alt="thirdweb"></td><td>✅ <strong><a href="https://github.com/thirdweb-dev/js/pull/8938">thirdweb JS #8938</a></strong> — fixed <code>useTokenQuery</code> collapsing real token lookup failures into <code>unsupported_token</code> instead of using the existing error/retry path.</td></tr>
</table>

### Current upstream work

The OSS Contributions ledger also tracks active issue-driven work before it is merged, with the target repository, issue/PR provenance, implementation status, and current upstream state kept separate from merged accomplishments.

---

## 🧭 Contribution Focus

**AI & developer infrastructure:** Python · TypeScript · agent systems · state machines · RAG · memory · evaluation · observability · CI/CD · developer tooling

**Web3 infrastructure:** wallet SDKs · blockchain clients · smart-contract tooling · RPC boundaries · transaction handling · protocol integrations

**Engineering approach:** reproduce first → isolate the failure mode → implement the smallest coherent fix → add regression coverage → validate against the upstream contract → submit with explicit provenance.

---

## 🚀 Flagship Architectures & Projects

- 🔬 **[Synthesis](https://synthesis-gold.vercel.app/)** — autonomous multi-agent research with planning, research, synthesis, critique, HITL gates, RAG, Reflexion, and live SSE agent graphs ([repo](https://github.com/devtechedge/synthesis)).
- 💼 **[Jobrow](https://jobrow.vercel.app)** — live register of still-open US tech roles sourced from employer ATS boards, with search, filters, closed-role tracking, and a public JSON API ([repo](https://github.com/devtechedge/job-board)).
- ⛓️ **[Lattice](https://lattice-devtechedge1.vercel.app)** — Web3 jobs platform aggregating blockchain and crypto roles with salary observatory, talent directory, gigs, and hiring intelligence ([repo](https://github.com/devtechedge/lattice)).
- 🪐 **[Pulsar](https://devtechedge.github.io/pulsar/)** — decentralized AI compute protocol interface with Base smart contracts, staking flows, wallet connectivity, 3D visualization, tokenomics, and Foundry-tested contracts ([repo](https://github.com/devtechedge/pulsar)).
- 🧠 **[AAROP](https://aarop.vercel.app)** — explicit Perceive → Plan → Act → Observe → Reflect → Adapt loop with self-verification, bounded autonomy, and replayable traces ([repo](https://github.com/devtechedge/aarop)).
- ⚖️ **[RegTrace](https://regtrace-ai.vercel.app)** — HITL Web3 compliance copilot mapping packs onto MiCA/VARA with retrieval-bounded findings and article citations ([repo](https://github.com/devtechedge/regulatory_compliance)).
- 🏥 **[Cadence](https://cadence-healthcare.vercel.app/)** — deep-memory healthcare agent lab with layered patient memory, journey stages, and consent-scoped clinician briefs ([repo](https://github.com/devtechedge/healthcare-deep-memory-agents)).
- 🔎 **[Veritas](https://veritas-engine-woad.vercel.app)** — LangGraph research agent with SSE streaming, grounded demo mode, and external retrieval when configured ([repo](https://github.com/devtechedge/veritas-engine)).
- 🔥 **[Chaos Simulator](https://chaos-simulation.vercel.app)** — real-time chaos engineering dashboard with fault injection, self-healing services, animated service topology, scenario orchestration, telemetry, and recovery analysis ([repo](https://github.com/devtechedge/chaos-simulator)).

---

## 🛠️ Tech Stack

| Category | Tooling, Frameworks & Architecture |
| :--- | :--- |
| **AI systems & agents** | Python, LangGraph, LangChain, LangServe, FastAPI, explicit agentic state machines, multi-agent supervisors, HITL interrupts, bounded autonomy, Reflexion / critique loops, tool-use / ReAct, durable checkpoints |
| **RAG, memory & evaluation** | Hybrid RAG, pgvector, BM25, TF-IDF, JSONB embeddings, cosine retrieval, sentence-transformers, long-term memory, retrieval-bounded generation, eval gates, LLM-as-judge, LangSmith |
| **LLMs, tools & integrations** | Gemini, OpenAI-compatible providers, Groq, Ollama / local LLMs, Tavily, Telegram Bot API, MCP-oriented tool buses, Google Workspace integrations |
| **Frontend & product** | TypeScript, React, Next.js, TanStack Start, Vite, Tailwind CSS, shadcn/ui, Lucide, Motion / Framer Motion, Recharts, Three.js, React Three Fiber, HTML5 Canvas, SVG |
| **Data, auth & backend** | PostgreSQL, Supabase, Neon, PGLite, SQLite, Prisma, Drizzle ORM, SQLAlchemy, Pydantic, Zod, Better Auth, REST, Server Actions, API routes |
| **Realtime & observability** | SSE, WebSockets, Socket.io, replayable traces, structured telemetry, OpenTelemetry-shaped tracing, live/demo provider switching |
| **Web3 & smart contracts** | Solidity, OpenZeppelin, Foundry, Base, viem, wagmi, RainbowKit, ethers.js, wallet SDKs, blockchain / wallet infrastructure |
| **Infrastructure & testing** | Node.js, Bun, Express, Docker, Vercel, GitHub Actions, Vitest, pytest, Playwright, TypeScript compiler, Biome, security hardening and threat-model documentation |

---

## 🎯 Engineering Philosophy

- **Bounded autonomy:** explicit state, validation, cost-aware routing, and HITL for irreversible actions.
- **Retrieval-bounded truth:** citation-backed RAG with validation and evaluation gates.
- **Observable systems:** inspectable traces, structured telemetry, reproducible failures, and meaningful regression tests.
- **Upstream mindset:** improve the infrastructure being used, not just the application sitting on top of it.
- **Provenance first:** every OSS contribution is tied to its actual upstream issue/PR state; merged, active, and planned work are never conflated.

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dev-ma/)
[![X / Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/DevTechEdge)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/devtechedge)

---
