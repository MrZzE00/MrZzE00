<div align="center">

# Hey, I'm Norbert J.N. 👋

### AI Native Developer · Building cognitive systems that remember, reason & orchestrate

*I don't just use AI to code - I build systems where AI and humans think together.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/norbert-jeff-nadir/)

</div>

---

## What I'm About

I'm an **AI Native Developer** - which means AI isn't a tool I bolt on at the end, it's woven into every layer of how I build, think, and ship.

My current obsession: **giving AI persistent memory and multi-agent reasoning**, while keeping everything **local-first** and under your control. No black-box cloud lock-in. Your data stays yours.

I work at the intersection of **cognitive architectures**, **multi-agent orchestration**, and **developer tooling** - building the infrastructure that makes AI genuinely useful day after day, not just demo after demo.

References:

[Les Echos - Educate: a new role for the company?](https://www.lesechos.fr/idees-debats/leadership-management/eduquer-un-nouveau-role-pour-lentreprise-2195563)

[Agile en Seine - Anticipated future - Let's orchestrate intelligence](https://youtu.be/D_FZEiPPRms?si=RjsufFcVDHJA7atk)

[Blog Zenika - Reduce the pace of professionalization, why are we taking action?](https://blog.zenika.com/2025/01/24/reduire-la-marche-de-la-professionnalisation-pourquoi-agissons-nous/)

[RMSConf - How to train the talents of tomorrow?](https://youtu.be/_BQ4JTZWWXY?si=8lCj3nZNIggQwKZW)

---

## Featured Projects

### claude-mem-local - Cognitive Memory for AI

> *What if your AI assistant actually remembered what you worked on last week?*

A local-first memory system that gives AI **persistent, searchable, evolving knowledge** across sessions. Built on real cognitive science (ACT-R activation models), not just vector search.

**How it works:**
- **PostgreSQL + pgvector** - semantic memory storage with cosine similarity search
- **ACT-R cognitive model** - memories decay, strengthen, and activate like human memory
- **MCP protocol** - plugs directly into Claude Code (GitHub Copilot, Cursor, JetBrains, Antigravity, VS Code) making every conversation context-aware
- **100% local** - your knowledge never leaves your machine

**By the numbers:** 1,500+ memories stored · 10 categories · semantic retrieval in <100ms

`PostgreSQL 17` `pgvector` `Python` `FastAPI` `Ollama` `MCP`

[![Repo](https://img.shields.io/badge/🔗_claude--memory--local-181717?style=flat-square&logo=github)](https://github.com/MrZzE00/MCP-Claude-mem-local)

---

### synaptic-router - Right Task, Right Model

> *Why send a one-line docstring to the same API as a security audit?*

A hybrid 4-tier LLM router that classifies each prompt by complexity, category, and context size - then routes it to the optimal model. Simple completions stay local and fast. Security reviews and architecture decisions go to Claude. Your API bill finally reflects the actual difficulty of your work.

**How it works:**
- **4-tier routing engine** - BitNet (<100ms) → GLM-4 (code gen) → Qwen (large context) → Claude (critical decisions), selected automatically per prompt
- **Declarative rule system** - safe `field/op/value` conditions with zero `eval()`, security-hardened after a full OWASP Top 10 audit
- **Fail-closed security** - any rule evaluation error routes to the most capable tier, never the least
- **MCP native** - plugs into Claude Code as a tool server, transparent routing on every call

**By the numbers:** 4 tiers · 6 routing rules · 63 tests (21 security) · 0 uses of eval()

`Python` `Ollama` `Anthropic` `MCP` `YAML`

[![Repo](https://img.shields.io/badge/🔗_synaptic--router-181717?style=flat-square&logo=github)](https://github.com/MrZzE00/mcp-synaptic-router)

---

### Multi-Agent Strategic Analysis - 39 Experts, One Orchestrator

> *One AI agent is smart. Thirty-nine specialists orchestrated together are transformative.*

A multi-agent pipeline where a **General Manager** dispatches analysis across **5 strategic domains**, each powered by specialized expert agents - from Chaos Theory to Viable System Model cybernetics.

**Architecture:**
```
                    ┌─── Design & Dependencies (8 agents)
                    ├─── Experience & Identity (8 agents)
General Manager ───┼─── Value Flow & Strategy (8 agents)
                    ├─── People & Growth (8 agents)
                    └─── Structure & Governance (7 agents)
                                    │
                            Chief Reporter ── Final Synthesis
```

**Key design choices:**
- ⚡ **N8N orchestration** - visual workflow for 39-agent coordination with webhook triggers
- **FastAPI SSE streaming** - real-time progress as each agent completes its analysis
- **Per-agent persistence** - every intermediate result stored, not just the final report
- **LangGraph architecture** - parallel domain execution with conditional synthesis

`N8N` `LangGraph` `FastAPI` `Supabase` `SSE Streaming` `Python`

---

## The AI Native Dev Philosophy

```
Traditional Dev          AI Native Dev
─────────────           ──────────────
Write code        →     Co-create with AI agents
Debug manually    →     39 specialized analysts in parallel
Forget context    →     Cognitive memory across sessions
Cloud-dependent   →     Local-first, your data stays yours
One-shot prompts  →     Persistent knowledge that compounds
```

I believe the next wave of developer tooling isn't about better autocomplete - it's about **systems that learn alongside you**. Every bug you fix, every architecture decision, every pattern you discover should make your AI collaborator smarter *for your specific context*.

That's what I'm building.

---

## Tech Stack

<div align="center">

**AI & Cognitive Systems**

![Claude](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-6366F1?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_17-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Frontend & Deployment**

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## What's Next

- **Synaptic Enterprise** - evolving from personal memory to team-shared knowledge with multi-tenancy, curation workflows, and privacy-aware promotion systems
- **Advanced RAG** - Architecture combining cognitive memory with retrieval-augmented generation for cross-project pattern discovery
- **Open Source** - making local-first AI memory accessible to every developer

---

<div align="center">

*"The best AI tools don't replace thinking — they remember what you've already thought."*

**Let's build something that remembers.** 🧠

</div>
