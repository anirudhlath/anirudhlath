<h1 align="center">Hi 👋, I'm Anirudh Lath</h1>
<h3 align="center">Software Engineer III @ Walmart (VIZIO SmartCast) — Generative AI & Agentic AI</h3>

<p align="center">
I build production LLM systems: autonomous tool-calling agents, Retrieval-Augmented Generation (RAG) with vector search, real-time LLM guardrails, and evaluation infrastructure for an in-house voice assistant on VIZIO Smart TVs.
</p>

## What I work on

- 🤖 **Agentic AI** — server-side tool registries, structured outputs, multi-step tool-calling agents (Vertex AI / Gemini)
- 🛡️ **LLM safety & guardrails** — semantic guardrail engines (embeddings + vector search + LLM-judge fallback), adversarial red-teaming, refusal attribution
- 📊 **LLM evaluation** — eval platforms, A/B harnesses, LLM-as-judge scoring, eval-driven development
- ⚙️ **Systems & platform** — C++17 declarative UI engine, Rust language tooling (LSP), FastAPI/WebSocket backends, Azure
- 📄 Patent pending: context-based input interfaces for smart TVs (US 2025/0231778 A1)

## Featured projects

- **[alfred](https://github.com/anirudhlath/alfred)** — local-first multi-agent voice assistant: dual-process architecture (local Ollama SLM fast path + Claude agentic tool-use loop), LLM-generated automation triggers, three-layer memory with embedding search, DeepEval evaluation suite. Python, FastAPI, Redis, MQTT — with a companion [SwiftUI iOS client](https://github.com/anirudhlath/alfred-ios) and [Home Assistant microservice](https://github.com/anirudhlath/alfred-home-service).
- **[meta-mcp](https://github.com/anirudhlath/meta-mcp)** — Model Context Protocol (MCP) router that selects tools using embeddings, semantic search, and RAG over a Qdrant vector database. Python, FastAPI, Qdrant, Docker.
- **[moneta](https://github.com/anirudhlath/moneta)** — personal-finance engine where the LLM is a classifier gating decisions, never a source of money values: LLM-gated recurring detection with a human review queue, RSU-vesting-aware net worth, deferred-interest warnings. Python 3.13, SQLAlchemy async, LiteLLM.
- **[taxscan](https://github.com/anirudhlath/taxscan)** — sales-tax deduction analyzer: Gmail receipt extraction, LLM classification with enforced structured outputs (json_schema + $defs inlining), fuzzy receipt-transaction matching. Python 3.13, SQLModel, LiteLLM.
- **[dj-ledfx](https://github.com/anirudhlath/dj-ledfx)** — beat-synced LED lighting engine driven by Pioneer Pro DJ Link: 60fps effect renderer with per-device latency compensation, Prometheus/Grafana observability. Python, FastAPI, React.
- **[genai-image-studio](https://github.com/anirudhlath/genai-image-studio)** — DreamBooth fine-tuning and image-generation web service. PyTorch, FastAPI, Gradio, Docker.
- **[AsyncCardStack](https://github.com/anirudhlath/AsyncCardStack)** — modern async/await SwiftUI card-stack library.

## Reach me

- 💼 [linkedin.com/in/anirudhlath](https://www.linkedin.com/in/anirudhlath/)
- 📫 anirudhlath@outlook.com
- ⚡ Fun fact: I'm a filmmaker and an artist too!
