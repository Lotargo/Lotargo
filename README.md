<div align="center">

# Lotargo

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=3200&pause=750&color=36BCF7&center=true&vCenter=true&width=860&lines=AI+systems+%E2%80%A2+RAG+%E2%80%A2+agentic+pipelines;Local-first+tools+with+real+interfaces;Runtime+contracts+%2B+state+machines+%2B+provider+routing;From+experimental+ideas+to+working+software" alt="Typing SVG" />

**AI/RAG engineer · local-first tooling · verification-focused systems**

I build AI-oriented systems that combine retrieval, orchestration, provider routing, local-first tooling, and verification. My focus is turning experimental ideas into runnable systems with visible architecture, reproducible behavior, and clear failure boundaries.

</div>

---

## What I build

- **Custom RAG and database-backed systems** for retrieval, indexing, metadata pipelines, semantic search, and source-aware orchestration.
- **Agentic systems** with explicit orchestration, reviewer loops, runtime contracts, and quality gates.
- **AI infrastructure** for model/provider routing, key balancing, client isolation, MCP-style tooling, and local gateways.
- **Local-first applications** that keep useful data on the user's machine: galleries, metadata indexes, sandboxes, registries, and export pipelines.
- **Experimental interfaces** where aesthetics and architecture are both part of the product: CRT terminals, simulations, procedural assets, and interactive visual proof.
- **Unusual multi-language stacks** when they make sense: Python, Rust, TypeScript, FreePascal, PHP, Lua, and plain JavaScript all have their place.

> Some of my larger RAG/database research and implementation work is staged in private repositories. Public documentation and reproducibility packs are published gradually as claims, limitations, and safety boundaries become clear.

---

## Featured public work

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">What it demonstrates</th>
    <th align="left">Stack</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/Academic-Pipeline-Engine"><b>Academic Pipeline Engine</b></a><br>
      <a href="https://lotargo.github.io/Academic-Pipeline-Engine/"><img src="https://img.shields.io/badge/landing-live-00D1FF?style=flat-square&logo=githubpages&logoColor=white" alt="Live landing" /></a>
    </td>
    <td>Local agentic workspace for structured document generation: artifact routing, runtime contracts, Writer/Reviewer loop, FSM orchestration, OCR/web research, SQLite history, and DOCX/PDF export.</td>
    <td>Python 3.12, FastAPI, Next.js, React, TypeScript, SQLite, Poetry, Docker</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/Nexus_API_Balancer"><b>Nexus API Balancer</b></a><br>
      <a href="https://lotargo.github.io/Nexus_API_Balancer/"><img src="https://img.shields.io/badge/landing-live-00D1FF?style=flat-square&logo=githubpages&logoColor=white" alt="Live landing" /></a>
    </td>
    <td>High-performance Rust proxy and intelligent key balancer for AI providers with dynamic model discovery, priority routing, OpenAI-compatible gateway, client isolation, and MCP support.</td>
    <td>Rust 2024, Tokio, Axum, SQLx, SQLite, JWT, Scalar</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/ComfyUI-Meta-Viewer"><b>ComfyUI Meta Viewer</b></a><br>
      <a href="https://lotargo.github.io/ComfyUI-Meta-Viewer/"><img src="https://img.shields.io/badge/landing-live-00D1FF?style=flat-square&logo=githubpages&logoColor=white" alt="Live landing" /></a>
    </td>
    <td>Local gallery and metadata manager for ComfyUI images: prompt extraction, workflow graph inspection, EXIF parsing, folder indexing, object cutouts, and persistent SQLite cache.</td>
    <td>Python, Flask, SQLite, Pydantic, Pillow, Vanilla JS, Fuse.js</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/Necromancer"><b>Necromancer</b></a><br>
      <a href="https://lotargo.github.io/Necromancer/"><img src="https://img.shields.io/badge/landing-live-00D1FF?style=flat-square&logo=githubpages&logoColor=white" alt="Live landing" /></a>
    </td>
    <td>Cyber-occult local AI chat system with a retro CRT interface, PostgreSQL-backed accounts/history, FreePascal backend daemon, Lua provider balancer, Pascal sandbox, RAG/search tools, Canvas effects, and Web Audio atmosphere.</td>
    <td>FreePascal, PHP 8.3, Lua/LuaJIT, PostgreSQL, Docker, JavaScript, Canvas, Web Audio</td>
  </tr>
</table>

---

## Research / Proofs of Concept

These projects are not positioned as production-ready applications. They are experiments, active prototypes, verification artifacts, and architecture probes.

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">Research angle</th>
    <th align="left">Stack</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/verification-lab-1"><b>Verification Lab</b></a><br>
      <img src="https://img.shields.io/badge/status-reproducibility%20lab-2ECC71?style=flat-square" alt="Reproducibility lab" />
    </td>
    <td>Reproducible verification laboratory for retrieval-pipeline integrity: analytical correctness, adversarial rejection, singular-state handling, and independently audited SAT/3-SAT solver experiments.</td>
    <td>Python, numerical verification, symbolic checks, SAT/DPLL/CDCL, reproducibility packs</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/Search_Routers"><b>Search Routers</b></a><br>
      <img src="https://img.shields.io/badge/status-proof--of--concept-9B59B6?style=flat-square" alt="Proof of Concept" />
    </td>
    <td>Minimal two-stage LLM routing pipeline implemented in Pascal and x86-64 Assembly to test how little runtime support is required for client-side AI routing logic.</td>
    <td>FreePascal, x86-64 Assembly, Groq API, curl/OpenSSL</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/Lotargo/The-Living-Bunker"><b>The Living Bunker</b></a><br>
      <img src="https://img.shields.io/badge/status-active%20prototype-F39C12?style=flat-square" alt="Active prototype" />
    </td>
    <td>Observable multi-agent society sandbox for testing AI roles, asymmetric perception, constrained communication, repeatable scenarios, and emergent social behavior in a shared world.</td>
    <td>Python, Flask, TypeScript/JavaScript, Groq, Cerebras, Pillow, pytest</td>
  </tr>
</table>

---

## Engineering style

```text
idea
  -> make the state explicit
  -> split orchestration from execution
  -> add a mock/demo path
  -> make failure modes visible
  -> document the architecture
  -> ship something people can actually run
```

I usually prefer systems where the moving parts are visible: state machines over mystery flow, contracts over vague prompts, provider abstraction over hard lock-in, and local reproducibility over screenshots-only demos.

---

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## Current direction

I am currently focused on **AI orchestration**, **RAG/vector systems**, **database-backed retrieval**, **local developer tools**, **model/provider routing**, and **verification-friendly research prototypes**. Some larger research work is staged privately until the claims, limitations, and reproducibility boundaries are clear.

---

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Lotargo&show_icons=true&theme=tokyonight&hide_border=true&hide_title=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lotargo&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

</div>
