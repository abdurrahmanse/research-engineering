# Research Engineering

A comprehensive, structured learning and engineering repository covering software engineering fundamentals, design principles, patterns, architecture, systems design, applied projects, research methodology, and capstone systems.

---

## Author

**Abdur Rahman** — Frontend Developer

- 📱 WhatsApp: [01705952160](https://wa.me/8801705952160)
- ✉️ Email: [abdurrahmansoftw@gmail.com](mailto:abdurrahmansoftw@gmail.com)

---

## Repository Structure

### `00_foundations/` — Core Engineering Foundations
The bedrock concepts every engineer must internalize.

- **`python/`** — Python language mastery
  - `oop/` — Object-oriented programming (classes, inheritance, MRO, polymorphism, descriptors, metaclasses)
  - `typing/` — Static typing, generics, protocols, advanced type manipulation
  - `dataclasses/` — Dataclasses, frozen fields, Pydantic models
  - `decorators/` — Function/class decorators, stacked decorators, built-ins
  - `generators/` — Generator functions, expressions, iterators, async generators
  - `context_managers/` — `@contextmanager`, class-based, `ExitStack`
- **`algorithms/`** — Sorting, searching, recursion, DP, greedy, graph, divide & conquer
- **`data_structures/`** — Arrays, linked lists, trees, hash tables, graphs, heaps
- **`complexity_analysis/`** — Big-O, time/space complexity, amortized analysis
- **`testing/`** — `unittest`, `pytest`, fixtures, mocking, coverage, property-based testing

### `01_solid_principles/` — SOLID Design Principles
The five pillars of object-oriented design.

- `01_single_responsibility_principle/` — Single Responsibility Principle
- `02_open_closed_principle/` — Open/Closed Principle
- `03_liskov_substitution_principle/` — Liskov Substitution Principle
- `04_interface_segregation_principle/` — Interface Segregation Principle
- `05_dependency_inversion_principle/` — Dependency Inversion Principle
- `06_mini_projects/` — 2026-themed small projects (AI chat widget, dark mode, validators, hub, HTTP client)

### `02_patterns/` — Design Patterns
The canonical GoF patterns with real-world applications.

- **`creational/`** — `singleton/`, `factory/`, `builder/`
- **`structural/`** — `adapter/`, `decorator/`, `facade/`
- **`behavioral/`** — `strategy/`, `observer/`, `command/`, `template_method/`, `chain_of_responsibility/`
- **`pattern_compositions/`** — Patterns composed together (strategy + factory, repository + UoW, …)

### `03_refactoring/` — Refactoring & Code Quality
Improving existing code without changing behavior.

- `code_smells/` — Catalog of smells (long method, large class, shotgun surgery, …)
- `extract_method/`, `extract_class/` — Core refactoring techniques
- `dependency_injection/` — Constructor/setter/interface injection, DI containers
- `composition_over_inheritance/` — Favoring composition, mixins, interfaces
- `clean_code/` — Naming, small functions, comments, error handling, style
- `architecture_refactoring/` — Monolith decomposition, layer separation, bounded contexts

### `04_architecture/` — Software Architecture
Architectural styles and patterns at the system level.

- `layered_architecture/` — Presentation / business / persistence layers
- `repository_pattern/` — Generic + specific repositories, unit of work
- `service_layer/` — Application and domain services
- `clean_architecture/` — Entities, use cases, interface adapters, frameworks
- `hexagonal_architecture/` — Domain core, ports, adapters
- `event_driven_architecture/` — Event bus, handlers, sagas

### `05_systems/` — Systems & Production Concerns
What makes software production-ready.

- `configuration_management/` — Env vars, YAML/TOML, Pydantic settings, secrets
- `logging/` — Logging fundamentals, structured logging, loguru, aggregation
- `caching/` — In-memory, Redis, decorator pattern, invalidation, distributed
- `concurrency/` — Threading, multiprocessing, GIL, thread pools
- `async_programming/` — `asyncio`, coroutines, async context managers, queues
- `observability/` — Metrics, tracing (OpenTelemetry), health checks, Prometheus
- `performance_optimization/` — Profiling, memory profiling, benchmarking

### `06_projects/` — Small Frontend + AI Projects (2026)
Hands-on projects synthesizing prior modules. Each is **3–5 small files** and targets
the trends shaping 2026 frontend / AI work.

- `ai_chat_ui_kit/` — Reusable streaming chat UI primitives
- `webllm_browser_inference/` — Run LLMs in-browser via WebGPU + Web Workers
- `realtime_collab_editor/` — CRDT-based multi-cursor editor
- `rag_docs_assistant/` — Docs Q&A with cited answers
- `edge_url_shortener/` — URL shortener on edge functions + KV
- `design_token_pipeline/` — Tokens → CSS vars / Tailwind / native
- `server_components_playground/` — React Server Components patterns
- `ai_image_studio/` — Prompt-to-image with queueing and gallery
- `browser_voice_agent/` — In-browser voice assistant (wake word + STT + TTS)
- `edge_auth_passkeys/` — Passwordless auth with WebAuthn passkeys
- `feature_flag_service/` — Targeting, rollouts, A/B with React hooks
- `streaming_markdown_renderer/` — Incremental, safe markdown streaming

### `07_research/` — Research Engineering
The scientific method applied to engineering work.

- `paper_reproduction/` — Selecting, extracting, implementing, validating papers
- `benchmark_studies/` — Designing benchmarks, datasets, metrics, analysis
- `ablation_studies/` — Component isolation, hyperparameter ablations, reporting
- `experimental_design/` — Hypotheses, variables, sampling, power analysis
- `reproducibility/` — Seeds, environment pinning, data/code versioning
- `research_prototypes/` — Rapid prototyping and idea validation

### `08_capstone/` — Capstone Systems
End-to-end systems that integrate everything.

- `ai_portfolio_generator/` — Resume → AI-written copy → styled static site → deploy
- `realtime_ai_tutor/` — Voice-driven AI tutor with whiteboard and progress
- `edge_native_saas/` — Multi-tenant SaaS on edge (routing, KV, billing, RBAC, OTEL)
- `visual_ai_agent_builder/` — Drag-and-drop agent composition + runtime + evals
- `pwa_offline_notes/` — Offline-first PWA with conflict-free sync
- `realtime_analytics_dashboard/` — Live event-stream dashboard with sub-second updates
- `ai_code_review_bot/` — GitHub App that posts LLM review comments on PRs
- `microfrontend_ecommerce/` — Module-federation storefront with team-owned slices

---

## Conventions

- Every directory contains a `00_README.md` describing the topic and file layout.
- Files are numbered by topic order (`01_…`, `02_…`, …) to suggest a learning sequence.
- Code files use `snake_case`; documentation files use `kebab-case.md`.
- Each module is self-contained and can be studied independently.

## Goals

1. Build deep engineering intuition beyond framework-of-the-day knowledge.
2. Connect fundamentals (data structures, OOP) to architecture (clean, hexagonal).
3. Connect architecture to production (observability, caching, async).
4. Connect production to research (reproducibility, ablations, benchmarks).
5. Ship capstone systems that prove integrated competence.
