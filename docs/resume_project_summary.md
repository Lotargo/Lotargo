# Приложение к резюме: краткое описание GitHub-проектов

**Олег Бойко / Lotargo**

Дата подготовки: 7 июля 2026

Документ предназначен для HR, технического интервьюера или ревьюера как быстрый обзор репозиториев без необходимости открывать каждый проект отдельно.
Формулировки сделаны в безопасном формате: что делает проект, какой стек использован и какую инженерную ценность он показывает.

Для приватных репозиториев описание намеренно не раскрывает закрытый исходный код, приватные ключи, внутренние данные или детали, которые не нужны для приложения к резюме.

## Сводка

| Показатель | Значение |
|---|---:|
| Всего репозиториев | 49 |
| Публичных | 13 |
| Приватных | 36 |
| Основной фокус | AI/RAG, агенты, low-level runtime, tooling, verification |

## Ключевые направления портфолио

- **Low-level AI runtime:** Sonata AI, Tensor Machine, AGI-lite и связанные лаборатории показывают интерес к собственным runtime, tensor/autograd execution, symbolic verification и low-level optimization.
- **AI/RAG infrastructure:** Nexus API Balancer, Universal AI Gateway, Custom Hybrid RAG, Tensor Machine и mnemora-telegram закрывают слой retrieval, provider routing, MCP, memory и agent workflows.
- **Agentic products and tools:** Academic Pipeline Engine, Dev0, The Living Bunker, ComfyUI Meta Viewer и Telegram-проекты показывают переход от исследований к интерфейсам, workflow и проверяемым MVP.
- **Verification and reproducibility:** verification-lab-1, Project-Chimera и связанные экспериментальные ветки фиксируют подход: проверяемые пакеты, explicit limits, adversarial tests и отчеты.

## Проекты, которые стоит подсвечивать в резюме

### Sonata_AI

- **Доступ:** Private
- **Стек:** Pascal / Assembly / CUDA C++
- **Кратко:** Закрытая low-level AI research platform: tensor runtime, lazy autograd, neural training runtime, Mamba/MoE/TT experiments, binary protocol and GPU backend.
- **Что показывает:** From-scratch AI runtime, ручное управление памятью, GPU/CPU dispatch, доказательное R&D.

### Tensor-Machine

- **Доступ:** Private
- **Стек:** Rust / GPLv3
- **Кратко:** Programmable low-latency RAG engine: DSL -> IR -> bytecode -> Tensor VM, hybrid retrieval, MCP tools, Arrow/FlatBuffer, CPU/SIMD/WebGPU paths.
- **Что показывает:** RAG как vector-relational execution system, системное проектирование retrieval-инфраструктуры.

### AGI-lite

- **Доступ:** Private
- **Стек:** Python / Lisp / Prolog
- **Кратко:** Neuro-symbolic/evolutionary research engine для synthesis/search: AST generation, mutation, crossover, formal censors, penalty functions и verification loop.
- **Что показывает:** Algorithm synthesis, symbolic validation, experiment logging, исследование ограничений машинного рассуждения.

### Nexus_API_Balancer

- **Доступ:** Public
- **Стек:** Rust / Apache 2.0
- **Кратко:** Высокопроизводительный AI provider gateway: OpenAI-compatible API, dynamic model registry, key rotation, client isolation, priority routing, MCP support.
- **Что показывает:** Rust backend, async networking, provider abstraction, инфраструктура для LLM-приложений.

### Private---Universal-AI-Gateway

- **Доступ:** Private
- **Стек:** Python / AGPLv3
- **Кратко:** OpenAI-compatible gateway and agent runtime: provider rotation, key pools, fallback chains, ReAct/Cognitive Ladder/vMoE agents, MCP tools and Smart Search.
- **Что показывает:** Multi-provider LLM orchestration, agent patterns, FastAPI infrastructure, resilient AI gateway design.

### Private---Dev0-AI-Powered-Modular-Development-Platform

- **Доступ:** Private
- **Стек:** Python / AGPLv3
- **Кратко:** Glass-box AI software factory: превращает задачу в runnable MVP через planning, retrieval, generation, stitching, compilation, verification, replay and observability.
- **Что показывает:** AI coding agents, typed stages, Qdrant/Redis/FastAPI, verification-driven generation.

### Academic-Pipeline-Engine

- **Доступ:** Public
- **Стек:** Python / AGPLv3
- **Кратко:** Локальный agentic workspace для структурированных документов: artifact routing, runtime contracts, Writer/Reviewer loop, FSM, OCR/web research, DOCX/PDF export.
- **Что показывает:** AI-assisted document automation, FastAPI/Next.js, quality gates, export QA, SQLite registry.

### Private---MCP---Next-Generation

- **Доступ:** Private
- **Стек:** Go / Apache 2.0
- **Кратко:** MCP-NG: Docker-first modular MCP meta-server with Host Proxy Engine, Admin UI, hot reload, multi-language SDK/tool support and HTTP/SSE + stdio transports.
- **Что показывает:** MCP infrastructure, Go services, host/container boundary design, tooling platform.

### Aegis-Core

- **Доступ:** Private
- **Стек:** Python / MIT
- **Кратко:** API security framework using Moving Target Defense and Cyber Deception: encrypted request container, endpoint obfuscation, WAF layer, decoys and rate limiting.
- **Что показывает:** Security architecture, FastAPI, OpenAPI validation, proactive defense patterns.

### ComfyUI-Meta-Viewer

- **Доступ:** Public
- **Стек:** JavaScript / Flask / SQLite / AGPLv3
- **Кратко:** Local web app для просмотра и управления metadata изображений ComfyUI: prompts, workflow graph, EXIF, folder scan, search, gallery и object cutout.
- **Что показывает:** Local-first tooling, metadata extraction, SQLite persistence, image workflow UX.

### The-Living-Bunker

- **Доступ:** Public
- **Стек:** Python / Flask / TypeScript
- **Кратко:** AI-society sandbox: автономные агенты в общем мире, роли, асимметричное восприятие, ограниченная коммуникация и observability-first UI.
- **Что показывает:** Agent simulation, LLM orchestration, controlled scenarios, debugging UI для поведения агентов.

### verification-lab-1

- **Доступ:** Public
- **Стек:** Python / MIT
- **Кратко:** Лаборатория воспроизводимых экспериментов: integrity checks, adversarial rejection, typed singularity handling, SAT/3-SAT verification packs.
- **Что показывает:** Верификация, воспроизводимость, failure modes, подготовка архивов с результатами и отчетами.

### Search_Routers

- **Доступ:** Public
- **Стек:** Assembly / Pascal / MIT
- **Кратко:** Proof-of-concept двухэтапного LLM routing pipeline на Pascal и x86-64 Assembly: strategy router, scope router, JSON contracts, Groq API.
- **Что показывает:** Низкоуровневая реализация AI-routing вне обычного Python/JS стека.

### TZ_Triumf

- **Доступ:** Public
- **Стек:** Python / Three.js
- **Кратко:** Исследовательский пайплайн 3D-реконструкции лица по 1-3 фото: DECA/FLAME, standalone Flame2023Decoder, экспорт OBJ/GLB/PLY, диагностика mesh и web-viewer.
- **Что показывает:** Computer vision / 3D pipeline, работа с mesh, UV/texture/mask workflow, тесты и техническая документация.

### private--music_upscaler

- **Доступ:** Private
- **Стек:** Python / Django
- **Кратко:** AudioSR Pro: AI-powered music upscaling platform with Django backend, AudioSR/PyTorch processing, metadata/cover handling and music-library UI.
- **Что показывает:** AI audio processing, Django, CUDA/CPU fallback, product UI inspired by streaming services.

## Публичные репозитории

| Репозиторий | Стек / язык | Последнее обновление | О чём проект | Что показывает |
|---|---|---|---|---|
| **TZ_Usmanova** | CSS / HTML / JS | 3 часа назад | Статическая multipage-реконструкция фитнес-лендинга Usmanova Fit: чистовая сборка в submission, адаптивные страницы, галереи, формы, lightbox и GitHub Pages deploy. | Frontend-верстка, адаптивность, восстановление сайта по публичному референсу, подготовка проверяемого результата для тестового задания. |
| **TZ_Triumf** | Python / Three.js | 5 часов назад | Исследовательский пайплайн 3D-реконструкции лица по 1-3 фото: DECA/FLAME, standalone Flame2023Decoder, экспорт OBJ/GLB/PLY, диагностика mesh и web-viewer. | Computer vision / 3D pipeline, работа с mesh, UV/texture/mask workflow, тесты и техническая документация. |
| **lotargo.github.io** | HTML | 4 дня назад | GitHub Pages-портфолио: публичная витрина проектов, лендинги, навигация по доказательным материалам и демонстрационным страницам. | Умение упаковывать инженерные проекты в понятную публичную презентацию. |
| **css-server** | JavaScript / Rust / Tauri | На прошлой неделе | Экспериментальный статический runtime, где браузер, DOM и CSS используются как вычислительная среда; калькулятор и network lab выступают proof-module. | Нестандартное системное мышление, edge-first подход, статические приложения без backend-зависимости. |
| **Lotargo** | GitHub Profile README | 2 недели назад | Профильный README и входная точка портфолио: кратко объясняет специализацию в AI/RAG, low-level runtime, agentic tooling и verification-oriented прототипах. | Самопрезентация, структура портфолио, техническая навигация для рекрутера или ревьюера. |
| **public_sonata_ai_landing** | HTML / Docs | 2 недели назад | Публичное evidence dossier для закрытой платформы Sonata AI: архитектура, ограничения, benchmark evidence, autograd, GPU backend, quantization и Mamba-style experiments. | Доказательное оформление закрытого R&D без публикации исходного кода. |
| **verification-lab-1** | Python / MIT | 2 недели назад | Лаборатория воспроизводимых экспериментов: integrity checks, adversarial rejection, typed singularity handling, SAT/3-SAT verification packs. | Верификация, воспроизводимость, failure modes, подготовка архивов с результатами и отчетами. |
| **The-Living-Bunker** | Python / Flask / TypeScript | 2 недели назад | AI-society sandbox: автономные агенты в общем мире, роли, асимметричное восприятие, ограниченная коммуникация и observability-first UI. | Agent simulation, LLM orchestration, controlled scenarios, debugging UI для поведения агентов. |
| **Search_Routers** | Assembly / Pascal / MIT | 2 недели назад | Proof-of-concept двухэтапного LLM routing pipeline на Pascal и x86-64 Assembly: strategy router, scope router, JSON contracts, Groq API. | Низкоуровневая реализация AI-routing вне обычного Python/JS стека. |
| **Nexus_API_Balancer** | Rust / Apache 2.0 | 2 недели назад | Высокопроизводительный AI provider gateway: OpenAI-compatible API, dynamic model registry, key rotation, client isolation, priority routing, MCP support. | Rust backend, async networking, provider abstraction, инфраструктура для LLM-приложений. |
| **Necromancer** | PHP / Pascal / Lua / PostgreSQL | 2 недели назад | Стилизованный AI-oracle/chat system с CRT/occult UI, Pascal TCP backend, PostgreSQL, Argon2id, Lua key balancer, local RAG и sandbox execution. | Мульти-языковая архитектура, sockets, безопасность, UI-атмосфера и инструментальный AI backend. |
| **Academic-Pipeline-Engine** | Python / AGPLv3 | 2 недели назад | Локальный agentic workspace для структурированных документов: artifact routing, runtime contracts, Writer/Reviewer loop, FSM, OCR/web research, DOCX/PDF export. | AI-assisted document automation, FastAPI/Next.js, quality gates, export QA, SQLite registry. |
| **ComfyUI-Meta-Viewer** | JavaScript / Flask / SQLite / AGPLv3 | 2 недели назад | Local web app для просмотра и управления metadata изображений ComfyUI: prompts, workflow graph, EXIF, folder scan, search, gallery и object cutout. | Local-first tooling, metadata extraction, SQLite persistence, image workflow UX. |

## Приватные репозитории

| Репозиторий | Стек / язык | Последнее обновление | О чём проект | Что показывает |
|---|---|---|---|---|
| **Sonata_AI** | Pascal / Assembly / CUDA C++ | Вчера | Закрытая low-level AI research platform: tensor runtime, lazy autograd, neural training runtime, Mamba/MoE/TT experiments, binary protocol and GPU backend. | From-scratch AI runtime, ручное управление памятью, GPU/CPU dispatch, доказательное R&D. |
| **AGI-lite** | Python / Lisp / Prolog | 3 дня назад | Neuro-symbolic/evolutionary research engine для synthesis/search: AST generation, mutation, crossover, formal censors, penalty functions и verification loop. | Algorithm synthesis, symbolic validation, experiment logging, исследование ограничений машинного рассуждения. |
| **Tensor-Machine** | Rust / GPLv3 | 4 дня назад | Programmable low-latency RAG engine: DSL -> IR -> bytecode -> Tensor VM, hybrid retrieval, MCP tools, Arrow/FlatBuffer, CPU/SIMD/WebGPU paths. | RAG как vector-relational execution system, системное проектирование retrieval-инфраструктуры. |
| **turbo-calc** | Common Lisp / LuaJIT / Prolog / APL | 4 дня назад | Hermes Compute Bus: binary-protocol compute router для symbolic, logical, vector, graph, DSP и mini quantum-simulation workloads. | TCBP protocol, opcode routing, heterogeneous runtimes, process isolation и compact payload design. |
| **gpu-pool-sim** | HTML / JS / MIT | На прошлой неделе | Симулятор локального AI GPU pool: ASR/text2text queues, heterogeneous workers, preemption, external API fallback, rate/budget constraints. | Capacity planning, resource scheduling, architecture validation before deployment. |
| **mnemora-telegram** | TypeScript / Next.js / Supabase | На прошлой неделе | Telegram-native AI workspace: memory, documents, skills, MCP tools, Telegram Web App UI, bot webhook, Supabase/pgvector storage. | Product architecture for AI assistants, Telegram integration, full-stack MVP planning. |
| **Search_Routers.bak** | Assembly | 2 недели назад | Архивная/резервная версия low-level LLM routing эксперимента Search_Routers. | Сохранение исследовательской ветки, воспроизводимость и сравнение реализаций. |
| **Project-Chimera** | Python | 2 недели назад | Экспериментальная зона для связки symbolic/numeric verification components: solver harnesses, bridges, test scenarios and research glue code. | Исследовательская интеграция Prolog/Lisp/APL/Python-подходов, верификация и прототипирование. |
| **private--cosmo** | Python | 3 недели назад | Закрытая рабочая зона для космологических/научных экспериментов и анализа данных, связанная с визуализацией и проверкой гипотез. | Scientific Python, data analysis, exploratory research. |
| **Custom-hybrid-RAG-** | C++ | 3 июня | C++ prototype кастомного hybrid RAG: low-level retrieval experiments, routing, source handling and performance-oriented search pipeline. | Эксперименты с retrieval core вне Python-фреймворков, latency-oriented engineering. |
| **Private---Dev0-AI-Powered-Modular-Development-Platform** | Python / AGPLv3 | 3 июня | Glass-box AI software factory: превращает задачу в runnable MVP через planning, retrieval, generation, stitching, compilation, verification, replay and observability. | AI coding agents, typed stages, Qdrant/Redis/FastAPI, verification-driven generation. |
| **Private---MCP---Next-Generation** | Go / Apache 2.0 | 2 июня | MCP-NG: Docker-first modular MCP meta-server with Host Proxy Engine, Admin UI, hot reload, multi-language SDK/tool support and HTTP/SSE + stdio transports. | MCP infrastructure, Go services, host/container boundary design, tooling platform. |
| **Library-Slide-Editor** | JavaScript | 2 июня | Web-инструмент для редактирования слайдов/библиотечных материалов и подготовки визуальных документов. | Frontend tooling, document UI, редакторские workflow. |
| **Aegis-Core** | Python / MIT | 2 июня | API security framework using Moving Target Defense and Cyber Deception: encrypted request container, endpoint obfuscation, WAF layer, decoys and rate limiting. | Security architecture, FastAPI, OpenAPI validation, proactive defense patterns. |
| **swagger-new-1** | Python | 2 июня | Вспомогательный API/OpenAPI prototype для проверки FastAPI/Swagger схем, документации и контрактов endpoint-ов. | API design, autogenerated docs, contract-first backend practice. |
| **Private---Sentio-Engine** | Python / MIT | 2 июня | Decoupled emotional-state microservice for AI/NPC systems: FastAPI, Protobuf API, personality configs, emotional decay and MongoDB event memory. | Stateful AI middleware, service isolation, configurable persona simulation. |
| **Verne-** | JavaScript / Apache 2.0 | 2 июня | Вспомогательный JavaScript/web prototype; используется как экспериментальная площадка для интерфейсных и продуктовых идей. | Frontend prototyping, быстрые демо, UI-эксперименты. |
| **Nodes_music_UI** | TypeScript | 2 июня | Нодовый интерфейс для проектирования музыкальных структур: блоки intro/verse/chorus, связи, параметры энергии/стиля и AI-assisted composition workflow. | Graph UI, React/TypeScript-подход, tooling для генеративной музыки. |
| **Private---Atlantic-Asynchronous-Market-Analysis-Platform** | Python / MIT | 2 июня | Asynchronous market analysis platform: multi-agent missions, CQRS-inspired write/read paths, Kafka worker, ChromaDB + SQLite cascading memory and Streamlit UI. | Multi-agent analytics, async processing, RAG memory, Dockerized services. |
| **medical_dashboard** | Python | 2 июня | Full-stack medical data dashboard with AI document processing, FastAPI backend, PostgreSQL/SQLModel, Docling extraction and report generation utilities. | Applied backend, document processing, healthcare-style data management UI. |
| **Amalgam.v.0.01** | Rust | 2 июня | Early Rust prototype for system/runtime experiments around unified execution, orchestration or data-processing components. | Rust prototyping, systems experimentation, architecture groundwork. |
| **The-Living-Bunker-Godot** | GDScript | 2 июня | Godot frontend/body for The Living Bunker: visual simulation client connected to a Python backend brain, with console and world interaction. | Game-engine integration, AI simulation UI, Godot + backend split. |
| **Private---Universal-AI-Gateway** | Python / AGPLv3 | 2 июня | OpenAI-compatible gateway and agent runtime: provider rotation, key pools, fallback chains, ReAct/Cognitive Ladder/vMoE agents, MCP tools and Smart Search. | Multi-provider LLM orchestration, agent patterns, FastAPI infrastructure, resilient AI gateway design. |
| **Open--Telegram-Bot** | Python | 2 июня | Production-oriented Telegram bot with LLM integration, voice messages, Whisper STT, Edge-TTS, MongoDB sessions, adaptive persona and rate limiting. | Production-style bot architecture, aiogram, speech pipeline, persistent conversational state. |
| **Music-suno** | TypeScript / React / FastAPI | 8 мая | Node-based Music Studio concept for generative composition: graph-based song blocks, AI agent, Lyria/Gemini integration and animated UI. | Generative music product design, React Flow, frontend/backend integration. |
| **dev_ai_v.0.01** | Go | 26 апреля | Ранний Go-прототип AI-assisted development/runtime tooling; экспериментальная база для более поздних агентных платформ. | Go services, developer tooling, early architecture exploration. |
| **suno_music** | Python / Markdown | 25 марта | Suno Music Production Lab: organized prompt/lyrics repository for Suno AI v4.5, genre folders, instruction handbook and agent workflow notes. | Prompt engineering, creative workflow systematization, reusable music metadata. |
| **private--music_upscaler** | Python / Django | 1 марта | AudioSR Pro: AI-powered music upscaling platform with Django backend, AudioSR/PyTorch processing, metadata/cover handling and music-library UI. | AI audio processing, Django, CUDA/CPU fallback, product UI inspired by streaming services. |
| **private--mega-lo-mania-v2-go-engine** | Go | 21 февраля | Closed Go engine/prototype for a strategy/simulation game inspired by Mega-Lo-Mania-style mechanics. | Game logic, simulation systems, Go backend/engine architecture. |
| **private--tg-rag-1** | Go | 17 февраля | Telegram RAG prototype in Go: bot interface, retrieval flow and lightweight assistant architecture. | Go bot development, RAG integration, messaging UX. |
| **Private--Sonata-remastered** | Python | 31 декабря 2025 | Python-side remastered/experimental branch around Sonata concepts, likely used for alternative experiments, wrappers or validation scripts. | Rapid experimentation, reference checks and bridge code around low-level AI runtime ideas. |
| **Atlantic-Asynchronous-Market-Analysis-Platform-** | Python / MIT | 19 декабря 2025 | Earlier/alternate Atlantic branch for asynchronous market analysis, multi-agent missions, memory and report generation. | Versioned architecture evolution, analytics platform prototyping. |
| **Cosmic-Canvas-WMAP-CMB-Data-Analyzer** | Python | 19 декабря 2025 | Scientific data-analysis project for WMAP/CMB cosmological data, visualization and exploratory research workflows. | Scientific Python, data visualization, physics/cosmology-oriented analysis. |
| **Private---Aegis-Core** | Python / MIT | 19 декабря 2025 | Private/earlier branch of Aegis Core API security framework with MTD/deception concepts. | Security R&D branch management, API gateway prototyping. |
| **Private---Academic-Pipeline-Engine** | Python / MIT | 19 декабря 2025 | Private/earlier branch of Academic Pipeline Engine for agentic document generation and export automation. | Evolution from private prototype to public portfolio-ready app. |
| **Private---AI-Agent-Based-Autonomous-Development-Platform_non-stable** | Python | 3 ноября 2025 | Unstable early autonomous development platform: agent-based software generation, experimentation with planning/build/verification loops. | Early R&D toward Dev0-style autonomous software factory. |

## Короткая формулировка для резюме

Разработал серию AI/RAG и agentic-инструментов: от low-level tensor/autograd runtime и programmable RAG engine до OpenAI-compatible gateways, MCP-инфраструктуры, AI software factory, Telegram AI workspace, document automation pipeline и verification lab. В проектах демонстрируются backend/frontend-разработка, Rust/Go/Python/Pascal/Lisp/Prolog/Assembly-эксперименты, работа с LLM providers, retrieval, state machines, runtime contracts, GPU/CPU execution, export pipelines и reproducibility-oriented инженерный подход.

## Примечание

Этот Markdown-файл является редактируемой версией приложения к резюме. Его можно использовать как основу для более короткой версии в CV, отдельной страницы портфолио или описания проектов в сопроводительном письме.
