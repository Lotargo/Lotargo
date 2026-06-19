<div align="center">

# Oleg Boyko / Lotargo

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=3200&pause=750&color=36BCF7&center=true&vCenter=true&width=940&lines=AI+systems+architecture+%E2%80%A2+low-level+runtime+experiments;RAG+%E2%80%A2+vector+systems+%E2%80%A2+agentic+pipelines;Local-first+AI+tools+with+real+interfaces;From+experimental+ideas+to+working+software" alt="Typing SVG" />

**AI systems architect · low-level AI runtime experiments · RAG/vector systems · local-first AI tooling**

I build AI-oriented systems where the moving parts are visible: custom runtimes, retrieval infrastructure, provider routing, local-first tools, runtime contracts, and verification-focused prototypes.

**Start here:** [Sonata AI dossier](https://github.com/Lotargo/public_sonata_ai_landing) · [Browse dossier](https://lotargo.github.io/public_sonata_ai_landing/) · [Featured systems](#featured-systems) · [Research labs](#research--proofs-of-concept) · [Toolbox](#toolbox)

</div>

---

## In 5 seconds

- **Low-level AI runtimes:** custom tensor/autograd research, GPU/CPU dispatch, quantization paths, and runtime experiments outside mainstream Python frameworks.
- **AI/RAG infrastructure:** retrieval systems, provider routing, agentic pipelines, runtime contracts, and verification-focused orchestration.
- **Local-first tools that run:** public apps and demos with real interfaces, persistent state, export flows, landing pages, and clear operational boundaries.

---

## What I do

- **Low-level AI runtime research** — tensor execution, custom autograd, GPU/CPU dispatch, quantization paths, and training infrastructure outside mainstream Python frameworks.
- **RAG and vector systems** — retrieval, indexing, metadata pipelines, semantic search, database-backed orchestration, and source-aware workflows.
- **Agentic infrastructure** — runtime contracts, reviewer loops, state machines, provider routing, local gateways, and MCP-style tooling.
- **Local-first AI tools** — practical applications with real interfaces, persistent storage, export flows, inspectable behavior, and reproducible local state.
- **Verification-friendly prototypes** — experiments with explicit limits, public evidence, failure modes, and reproducibility packs where possible.

---

## Proof snapshot

| Area | Repository / evidence | Live page |
|---|---|---|
| From-scratch AI runtime | [Sonata AI public evidence dossier](https://github.com/Lotargo/public_sonata_ai_landing) | [Browse dossier](https://lotargo.github.io/public_sonata_ai_landing/) |
| AI provider infrastructure | [Nexus API Balancer](https://github.com/Lotargo/Nexus_API_Balancer) | [Live landing](https://lotargo.github.io/Nexus_API_Balancer/) |
| Agentic document systems | [Academic Pipeline Engine](https://github.com/Lotargo/Academic-Pipeline-Engine) | [Live landing](https://lotargo.github.io/Academic-Pipeline-Engine/) |
| Static browser runtime experiments | [CSS-Server](https://github.com/Lotargo/css-server) | [Live landing](https://lotargo.github.io/css-server/) |
| Local-first AI tooling | [ComfyUI Meta Viewer](https://github.com/Lotargo/ComfyUI-Meta-Viewer) | [Live landing](https://lotargo.github.io/ComfyUI-Meta-Viewer/) |
| Verification mindset | [Verification Lab](https://github.com/Lotargo/verification-lab-1) | — |
| Unusual multi-language systems | [Necromancer](https://github.com/Lotargo/Necromancer) · [Search Routers](https://github.com/Lotargo/Search_Routers) | [Necromancer live](https://lotargo.github.io/Necromancer/) |

---

## Engineering style

I usually prefer:

- state machines over mystery flow
- contracts over vague prompts
- orchestration separated from execution
- provider abstraction over hard lock-in
- local reproducibility over screenshots-only demos
- visible failure modes over silent magic

```text
idea
  -> make the state explicit
  -> split orchestration from execution
  -> add a mock/demo path
  -> make failure modes visible
  -> document the architecture
  -> ship something people can actually run
```

---

## Flagship research

### Sonata AI

**Private low-level AI research platform with a public evidence dossier.**

Sonata implements a custom tensor computation, automatic differentiation, and neural-network training runtime from scratch. The private runtime is built primarily in **Free Pascal**, accelerated with **x86-64 Assembly** and a **CUDA C++ GPU backend**. The public repository is not the source code; it is a curated technical dossier containing selected architecture notes, benchmark evidence, limitations, and claim boundaries.

**Open:** **[Evidence dossier repository](https://github.com/Lotargo/public_sonata_ai_landing)** · **[Browse public dossier](https://lotargo.github.io/public_sonata_ai_landing/)**  
**Status:** Closed-source research platform · public evidence archive  
**Demonstrates:** custom tensor/autograd runtime, GPU execution, INT8 quantization, Mamba-style sequence modeling, symbolic-control experiments, transport framing, and evidence-first documentation.  
**Stack:** Free Pascal, x86-64 Assembly, CUDA C++, custom runtime, GPU kernels, technical dossier.

> Sonata is intentionally presented as a laboratory research platform, not a product launch, production system, or open-source framework.

---

## Featured systems

### Academic Pipeline Engine

**Local agentic workspace for structured document generation.**

**Open:** **[Repository](https://github.com/Lotargo/Academic-Pipeline-Engine)** · **[Live landing](https://lotargo.github.io/Academic-Pipeline-Engine/)**  
**Status:** Public application / local-first agentic workspace  
**Demonstrates:** artifact routing, runtime contracts, Writer/Reviewer loop, FSM orchestration, OCR/web research flow, SQLite history, DOCX/PDF export, and reproducible document pipelines.  
**Stack:** Python 3.12, FastAPI, Next.js, React, TypeScript, SQLite, Poetry, Docker.

---

### Nexus API Balancer

**High-performance AI provider gateway and key balancer.**

**Open:** **[Repository](https://github.com/Lotargo/Nexus_API_Balancer)** · **[Live landing](https://lotargo.github.io/Nexus_API_Balancer/)**  
**Status:** Public infrastructure project  
**Demonstrates:** dynamic model discovery, priority routing, OpenAI-compatible gateway behavior, client isolation, key balancing, MCP support, and Rust service architecture.  
**Stack:** Rust 2024, Tokio, Axum, SQLx, SQLite, JWT, Scalar.

---

### CSS-Server

**Static browser runtime where CSS does the computation.**

**Open:** **[Repository](https://github.com/Lotargo/css-server)** · **[Live landing](https://lotargo.github.io/css-server/)**  
**Status:** Public runtime experiment / static-site boundary test  
**Demonstrates:** DOM-as-memory architecture, CSS evaluation as a computation layer, calculator proof module, static GitHub Pages runtime shell, outbound browser transport, and explicit backend-boundary documentation.  
**Stack:** Rust, Tauri 2, HTML, CSS, SCSS, JavaScript, SQLite, GitHub Pages.

---

### ComfyUI Meta Viewer

**Local gallery and metadata manager for ComfyUI-generated images.**

**Open:** **[Repository](https://github.com/Lotargo/ComfyUI-Meta-Viewer)** · **[Live landing](https://lotargo.github.io/ComfyUI-Meta-Viewer/)**  
**Status:** Public local-first tooling  
**Demonstrates:** prompt extraction, workflow graph inspection, EXIF parsing, folder indexing, object cutouts, fuzzy search, gallery navigation, and persistent local cache.  
**Stack:** Python, Flask, SQLite, Pydantic, Pillow, Vanilla JS, Fuse.js.

---

### Necromancer

**Cyber-occult local AI chat system with a retro CRT interface.**

**Open:** **[Repository](https://github.com/Lotargo/Necromancer)** · **[Live landing](https://lotargo.github.io/Necromancer/)**  
**Status:** Public experimental application  
**Demonstrates:** PostgreSQL-backed accounts/history, FreePascal backend daemon, Lua provider balancer, Pascal sandbox, RAG/search tools, Canvas effects, Web Audio atmosphere, and a highly stylized local AI interface.  
**Stack:** Free Pascal, PHP 8.3, Lua/LuaJIT, PostgreSQL, Docker, JavaScript, Canvas, Web Audio.

---

## Research / Proofs of Concept

These projects are not positioned as production-ready applications. They are experiments, active prototypes, verification artifacts, and architecture probes.

### Verification Lab

**Open:** **[Repository](https://github.com/Lotargo/verification-lab-1)**  
**Status:** Reproducibility lab  
**Research angle:** retrieval-pipeline integrity, analytical correctness, adversarial rejection, singular-state handling, and independently audited SAT/3-SAT solver experiments.  
**Stack:** Python, numerical verification, symbolic checks, SAT/DPLL/CDCL, reproducibility packs.

---

### Search Routers

**Open:** **[Repository](https://github.com/Lotargo/Search_Routers)**  
**Status:** Proof of concept  
**Research angle:** minimal two-stage LLM routing pipeline implemented in Pascal and x86-64 Assembly to test how little runtime support is required for client-side AI routing logic.  
**Stack:** Free Pascal, x86-64 Assembly, Groq API, curl/OpenSSL.

---

### The Living Bunker

**Open:** **[Repository](https://github.com/Lotargo/The-Living-Bunker)**  
**Status:** Active prototype  
**Research angle:** observable multi-agent society sandbox for AI roles, asymmetric perception, constrained communication, repeatable scenarios, and emergent social behavior in a shared world.  
**Stack:** Python, Flask, TypeScript/JavaScript, Groq, Cerebras, Pillow, pytest.

---

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Free%20Pascal-4B6C9B?style=flat-square" alt="Free Pascal" />
  <img src="https://img.shields.io/badge/x86--64%20Assembly-555555?style=flat-square" alt="x86-64 Assembly" />
  <img src="https://img.shields.io/badge/CUDA%20C%2B%2B-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA C++" />
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white" alt="Lua" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## Current direction

I am currently focused on **low-level AI runtime research**, **AI/RAG systems architecture**, **RAG/vector systems**, **database-backed retrieval**, **local developer tools**, **model/provider routing**, **static browser runtime experiments**, and **verification-friendly research prototypes**. Some larger research work remains private until the claims, limitations, and reproducibility boundaries are clear enough for public documentation.

---

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Lotargo&show_icons=true&theme=tokyonight&hide_border=true&hide_title=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lotargo&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

</div>
