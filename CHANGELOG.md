# Changelog

All notable changes to this list are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [v2026.05.06] — 2026-05-06

### Massive 2026 refresh — modern AI ecosystem

After 8 years of incremental updates, the list got a comprehensive refresh to cover the post-LLM era (foundation models, agents, RAG, MCP, AI coding tools, etc).

#### Added

- **🇦🇺 Australia AI Scene** — bootcamps, hiring, visa pathways, AU companies, meetups
- **Foundation Models & APIs** — Claude, GPT, Gemini, Llama, Qwen, DeepSeek, Mistral
- **AI Coding Tools** — Cursor, Claude Code, Copilot, Aider, Continue, Cline, Bolt.new, v0
- **Agent Frameworks & MCP** — LangGraph, CrewAI, AutoGen, OpenAI Swarm, Pydantic AI, Anthropic MCP, smolagents, Letta
- **RAG & Vector Databases** — LangChain, LlamaIndex, Pinecone, Weaviate, Qdrant, Chroma, Milvus, pgvector
- **LLM Inference & Hosting** — vLLM, Ollama, llama.cpp, Together, Groq, Modal, RunPod
- **LLM Ops & Observability** — LangSmith, Helicone, Phoenix, Braintrust, Langfuse, Promptfoo
- **Fine-Tuning & Training** — Axolotl, Unsloth, TRL, LLaMA Factory, Lit-GPT
- **Foundational Papers** section — Attention, BERT, GPT-3, CoT, ReAct, Toolformer, RAG
- **Modern courses** — Karpathy Zero to Hero, HF NLP/Agents, Anthropic Courses, LangChain Academy
- **Modern books** — Chip Huyen AI Engineering, Sebastian Raschka, Probabilistic ML
- **Modern newsletters/podcasts** — Latent Space, The Batch, Dwarkesh Podcast, No Priors, TLDR AI

#### Changed

- README structure reorganized with 19-section ToC
- Maintainer attribution added at top (JR Academy, Australia, P3 model)
- Companies section restructured into Foundation Labs / Infrastructure / Vertical / Robotics
- Conferences section refreshed (added NeurIPS, ICML, AI Engineer Summit)
- Tools sections deduplicated and consolidated
- AU Communities section enhanced

#### Fixed

- Typo "JR Acacademy" → "JR Academy" in license
- Wrong domain `jracademy.com.au` → `jiangren.com.au` in Brisbane entry
- Maintainer email updated from personal to `hello@jiangren.com.au`
- Many obviously dead 2017-era links removed (api.ai, Mimetic, Vesper, SkipFlag, etc)

### Added: Maintenance infrastructure

- `MAINTENANCE.md` — internal playbook for maintenance cadence and growth strategy
- `CONTRIBUTING.md` — modernized contribution guidelines
- `CODE_OF_CONDUCT.md` — Contributor Covenant 2.1
- `CHANGELOG.md` — this file
- `.github/workflows/awesome-lint.yml` — PR linting
- `.github/workflows/link-check.yml` — weekly dead-link detection
- `.github/ISSUE_TEMPLATE/` — structured issue forms
- `.github/pull_request_template.md` — PR checklist
- `.github/FUNDING.yml` — sponsorship config

---

## [v1.x] — 2017-2025

The list was created in July 2017 and grew through community PRs to 543 stars and 122 forks. Many incremental additions across courses, companies, tools, and bot development frameworks. See git log for detailed history.

---

## Versioning

Going forward we use **calendar versioning** (`YYYY.MM.DD`) for releases. Each meaningful refresh gets a tagged release with notes summarizing additions/removals.

[v2026.05.06]: https://github.com/hades217/awesome-ai/releases/tag/v2026.05.06
