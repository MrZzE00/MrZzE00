<div align="center">

# Hey, I'm Norbert J.N. 👋

### AI Ops · Building cognitive systems that remember, reason & orchestrate

*I don't just use AI to code - I build systems where AI and humans think together.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/norbert-jeff-nadir/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MrZzE00)

</div>

---

## What I'm About

I'm an **AI Ops* - which means AI isn't a tool I bolt on at the end, it's woven into every layer of how I build, think, and ship.

My current obsession: **giving AI persistent memory and multi-agent reasoning**, while keeping everything **local-first** and under your control. No black-box cloud lock-in. Your data stays yours.

I work at the intersection of **cognitive architectures**, **multi-agent orchestration**, and **developer tooling** - building the infrastructure that makes AI genuinely useful day after day, not just demo after demo.

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
 
### ai-standalone-workshop-FR - The Driver's License for AI Use
 
> *In 2026, the challenge isn't learning to use AI. It's unlearning what you think it does.*
 
A complete AI french literacy workshop packaged as **a single markdown file**. The learner pastes it into any chat AI (Claude, ChatGPT, Gemini, Mistral, Copilot) and the assistant becomes an interactive trainer for 2h30. No installation, no facilitator, no provider lock-in. Aligned with **EU AI Act Article 4** (mandatory AI literacy from August 2, 2026).
 
**How it works:**
- **5 modules** - Mirror (self-diagnosis) → Deconstruction (5 demonstrated AI limits) → Reconstruction (4 prompting patterns) → Compliance (AI Act articles 4, 13, 14) → Certification
- **Provider-agnostic** - pure conversational text, zero external tools, runs in any chat AI
- **Inclusive by design** - SKIP / PAUSE / VOUVOIEMENT commands, accessibility adaptations, no white-collar default in examples
- **Two deliverables** - personal AI License + 6-commitment Charter the learner can keep private or share
**By the numbers:** 1 markdown file · 5 modules · 2h30 self-paced · 522-response corpus informing the pedagogy
 
`Markdown` `Prompt Engineering` `EU AI Act` `Adult Learning` `Provider-agnostic`
 
[![Repo](https://img.shields.io/badge/🔗_ai--standalone--workshop--FR-181717?style=flat-square&logo=github)](https://github.com/MrZzE00/ai-standalone-workshop-FR)

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
- **Orchestration** - visual workflow for 39-agent coordination with webhook triggers
- **FastAPI SSE streaming** - real-time progress as each agent completes its analysis
- **Per-agent persistence** - every intermediate result stored, not just the final report
- **CLI architecture** - parallel domain execution with conditional synthesis

[Detailed approach here](https://orchestration-ia.norbert.md/)

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

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-6366F1?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square&logo=ollama&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-615CED?style=flat-square&logo=qwen&logoColor=white)
![ACT-R](https://img.shields.io/badge/ACT--R-5B21B6?style=flat-square)

**Orchestration & Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=flat-square&logo=tmux&logoColor=white)
![Git worktrees](https://img.shields.io/badge/Git_worktrees-F05032?style=flat-square&logo=git&logoColor=white)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_17-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square)
![pg_trgm](https://img.shields.io/badge/pg__trgm-336791?style=flat-square)
![nomic-embed-text](https://img.shields.io/badge/nomic--embed--text-0F766E?style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Frontend & Deployment**

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

</div>
---

## What's Next

- **Synaptic Enterprise** - evolving from personal memory to team-shared knowledge with multi-tenancy, curation workflows, and privacy-aware promotion systems
- **Advanced RAG** - status : ✅ - Architecture combining cognitive memory with retrieval-augmented generation for cross-project pattern discovery
- **Open Source** - status : ✅ - making local-first AI memory accessible to every developer

---

References:

[2026 - WaxConf - Heroes : save the token, save the world](https://www.waxconf.fr/)

[2026 - Agile en Seine - Heroes : save the token, save the world](https://www.agileenseine.com/programme/heroes-save-the-token-save-the-world/)

[2026 - Agile en Seine - AI in a team: what changes when you stop prompting on your own](https://www.agileenseine.com/programme/lia-en-equipe-ce-qui-change-quand-on-arrete-de-prompter-tout-seul/)

[2026 - VIVATECH - Executive Arena - Explaining AI to 5th graders: I got schooled (and it felt amazing)](https://vivatech.com/sessions/session/0442acd9-4049-f111-8ef3-6045bd9548dc)

[2026 - Programmez! MeetUp - Recruitment in the Age of AI](https://www.linkedin.com/posts/norbert-jeff-nadir_ia-recrutement-aezthique-activity-7442494604244922368-XAwG)

[2025 - Les Echos - Educate: a new role for the company?](https://www.lesechos.fr/idees-debats/leadership-management/eduquer-un-nouveau-role-pour-lentreprise-2195563)

[2025 - Agile en Seine - Anticipated future - Let's orchestrate intelligences](https://youtu.be/D_FZEiPPRms?si=RjsufFcVDHJA7atk)

[2025 - Blog Zenika - Reduce the pace of professionalization, why are we taking action?](https://blog.zenika.com/2025/01/24/reduire-la-marche-de-la-professionnalisation-pourquoi-agissons-nous/)

[2017 - RMSConf - How to train the talents of tomorrow?](https://youtu.be/_BQ4JTZWWXY?si=8lCj3nZNIggQwKZW)

---

<div align="center">

*"The best AI tools don't replace thinking, they remember what you've already thought."*

**Let's build something that remembers.**

</div>
