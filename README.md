# Awesome Artificial Intelligence

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/hades217/awesome-ai?style=social)](https://github.com/hades217/awesome-ai/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/hades217/awesome-ai)](https://github.com/hades217/awesome-ai/commits/master)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

**🌐 Language**: [English](README.md)（current） · [简体中文](README.zh.md)

> A community-curated list of artificial intelligence resources — foundation models, agent frameworks, AI coding tools, courses, companies, jobs, and country-specific AI scenes (USA, China, Australia, Malaysia, Singapore).

Maintained since 2017 by [Lightman Wang](https://github.com/hades217) ([LinkedIn](https://www.linkedin.com/in/lightman-wang/)).

Contributions welcome — open a PR or [start a discussion](https://github.com/hades217/awesome-ai/discussions). See [CONTRIBUTING.md](CONTRIBUTING.md).

**Legend**: ⭐ Editor's pick · 🔥 Hot in 2026 · 🆕 New this year · 🇨🇳 Chinese-focused · 🇦🇺 Australia-focused

---

## ⭐ Editor's Picks 2026

> If you only have 30 minutes — start here. Opinionated picks, updated each quarter.

| Category | Picks |
|---|---|
| 🤖 **Frontier models** | [Claude Opus 4.7](https://www.anthropic.com/claude) (reasoning + agentic) · [GPT-5.5](https://openai.com/api/) (polished) · [Gemini 3 Pro](https://ai.google.dev/) (multimodal) · [Grok 4](https://x.ai/) (real-time web) |
| 🔓 **Best open weights** | [Llama 4](https://llama.meta.com/) (general) · [Qwen3](https://qwenlm.github.io/) (multilingual) · [DeepSeek V3.2](https://www.deepseek.com/) (reasoning) · [Mistral Large 3](https://mistral.ai/) |
| 💻 **AI coding** | [Claude Code](https://www.anthropic.com/claude-code) (CLI) · [Cursor](https://www.cursor.com/) (IDE) · [Codex CLI](https://github.com/openai/codex) (OpenAI) · [Aider](https://aider.chat/) (open-source) |
| 🤝 **Agent framework** | [Claude Agent SDK](https://docs.anthropic.com/en/api/agent-sdk) · [LangGraph](https://langchain-ai.github.io/langgraph/) · [Anthropic MCP](https://modelcontextprotocol.io/) · [Pydantic AI](https://ai.pydantic.dev/) |
| 📚 **RAG starter** | [pgvector](https://github.com/pgvector/pgvector) (prototypes) · [Qdrant](https://qdrant.tech/) (self-hosted prod) · [Pinecone](https://www.pinecone.io/) (managed) |
| ⚡ **Inference** | [Ollama](https://ollama.com/) (local) · [vLLM](https://github.com/vllm-project/vllm) (production) · [Together AI](https://www.together.ai/) / [Groq](https://groq.com/) (hosted) |
| 📊 **Observability** | [LangSmith](https://www.langchain.com/langsmith) (LangChain shop) · [Helicone](https://www.helicone.ai/) (open-source) · [Braintrust](https://www.braintrust.dev/) (eval-first) |
| 🎓 **Free course** | [Karpathy's Zero to Hero](https://karpathy.ai/zero-to-hero.html) · [HuggingFace Agents Course](https://huggingface.co/learn/agents-course) |
| 📰 **Newsletter** | [Latent Space](https://www.latent.space/) (engineering) · [The Batch](https://www.deeplearning.ai/the-batch/) (overview) · [Import AI](https://importai.substack.com/) (policy) |
| 📖 **Book** | *[AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/)* (Chip Huyen, 2025) · *[Build a LLM From Scratch](https://www.manning.com/books/build-a-large-language-model-from-scratch)* (Sebastian Raschka) |
| 🧬 **Must-read paper** | [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) — the Transformer |

→ See full sections below for alternatives, runners-up, and emerging tools.

---

## Contents

1. [🤖 Foundation Models & APIs](#-foundation-models--apis)
2. [💻 AI Coding Tools](#-ai-coding-tools)
3. [🤝 Agent Frameworks & MCP](#-agent-frameworks--mcp)
4. [📚 RAG & Vector Databases](#-rag--vector-databases)
5. [⚡ LLM Inference & Hosting](#-llm-inference--hosting)
6. [📊 LLM Ops & Observability](#-llm-ops--observability)
7. [🎯 Fine-Tuning & Training](#-fine-tuning--training)
8. [🛠️ Development Frameworks](#%EF%B8%8F-development-frameworks)
9. [🎓 Courses & Learning Paths](#-courses--learning-paths)
10. [📖 Books, Papers & Blogs](#-books-papers--blogs)
11. [🏢 Companies & Research Labs](#-companies--research-labs)
12. [🧠 Personal AI Tools](#-personal-ai-tools)
13. [🎨 Specialized AI Tools](#-specialized-ai-tools) — Image, Video, Audio, Writing, Health, Finance
14. [📰 News, Newsletters & Podcasts](#-news-newsletters--podcasts)
15. [🎤 Events & Conferences](#-events--conferences)
16. [💼 AI Jobs](#-ai-jobs)
17. [🌐 AI Communities by City](#-ai-communities-by-city)
18. [🌍 AI Scene by Country](#-ai-scene-by-country) — USA, China, Australia, Malaysia, Singapore
19. [🤖 Robotics & Embodied AI](#-robotics--embodied-ai)
20. [Contributing](#contributing)

---

## 🤖 Foundation Models & APIs

### Frontier (closed-source) APIs

* [**Anthropic Claude**](https://www.anthropic.com/claude) ⭐ — Claude Opus 4.7 / Sonnet 4.6 / Haiku 4.5. Best reasoning + agentic + long-context (1M tokens). Strong code generation.
* [**OpenAI GPT**](https://openai.com/api/) ⭐ — GPT-5.5 / GPT-5 / o3 / o3-mini reasoning models. Most polished general-purpose API.
* [**Google Gemini**](https://ai.google.dev/) ⭐ — Gemini 3 Pro / Flash. Best multimodal + 2M-token context + native tool use.
* [**xAI Grok**](https://x.ai/) — Grok 4 with real-time web access via X data.
* [**Cohere**](https://cohere.com/) — Command R+ / R7B; enterprise RAG-focused LLMs.
* [**Mistral Large 3**](https://mistral.ai/) — European frontier model; strong code + multilingual.
* [**Perplexity Sonar API**](https://www.perplexity.ai/api/) — search-grounded LLM.
* [**Reka Core**](https://www.reka.ai/) — multimodal frontier model.

### Open-weights models 🔥

* [**Meta Llama 4**](https://llama.meta.com/) ⭐ — Llama 4 family (text + vision); the de facto open baseline.
* [**Qwen3 (Alibaba)**](https://qwenlm.github.io/) ⭐ 🇨🇳 — Qwen3 dense + MoE; strongest multilingual open model.
* [**DeepSeek**](https://www.deepseek.com/) ⭐ 🇨🇳 — DeepSeek V3.2 / R1 reasoning. Frontier-level open model.
* [**GLM 4.6 (Zhipu)**](https://github.com/THUDM/GLM-4) 🇨🇳 (7k ⭐) — bilingual model from Tsinghua.
* [**Mistral Open Models**](https://mistral.ai/technology/#models) — Mixtral, Mistral Small/Medium 3.
* [**Microsoft Phi-4**](https://azure.microsoft.com/en-us/products/phi) — small but strong models.
* [**Hugging Face Hub**](https://huggingface.co/) ⭐ — central hub for 500k+ open-source models.
* [**Kimi K2 (Moonshot)**](https://github.com/MoonshotAI/Kimi-K2) 🇨🇳 (11k ⭐) — open MoE from Moonshot; long-context champion.

### Multimodal & Specialized 🆕

* [**Sora 2 (OpenAI)**](https://openai.com/sora/) — text-to-video; highest fidelity in 2026.
* [**Veo 3 (Google)**](https://deepmind.google/technologies/veo/) — video generation with native audio.
* [**Stable Diffusion 3.5**](https://stability.ai/) — open image generation.
* [**Flux 1.1 Pro / Flux Kontext**](https://blackforestlabs.ai/) ⭐ — best-in-class open image gen + editing.
* [**Recraft V3**](https://www.recraft.ai/) — design-grade image generation.
* [**ElevenLabs**](https://elevenlabs.io/) ⭐ — voice cloning + multilingual TTS.
* [**Cartesia Sonic**](https://www.cartesia.ai/) 🆕 — sub-100ms voice generation for real-time agents.
* [**Hume EVI**](https://www.hume.ai/) — emotion-aware voice AI.
* [**Whisper Large v3**](https://openai.com/research/whisper) — open-source speech-to-text.
* [**Suno v4 / Udio**](https://www.suno.ai/) — music generation.

---

## 💻 AI Coding Tools

> AI assistants for writing, reviewing, refactoring code. The most disrupted developer category in 2025-2026.

* [**Claude Code**](https://www.anthropic.com/claude-code) ⭐ 🔥 — Anthropic's CLI for software engineering with Claude. Most-used CLI agent in 2026.
* [**Cursor**](https://www.cursor.com/) ⭐ 🔥 — AI-first code editor; fork of VS Code.
* [**Codex CLI (OpenAI)**](https://github.com/openai/codex) 🆕 (80k ⭐) — OpenAI's open-source CLI coding agent.
* [**GitHub Copilot**](https://github.com/features/copilot) — original AI pair programmer; now agent + Workspace + Spark.
* [**Windsurf**](https://codeium.com/windsurf) — Codeium's AI editor (acquired by Cognition).
* [**Aider**](https://aider.chat/) (44k ⭐) — open-source AI pair programmer in your terminal.
* [**Continue**](https://continue.dev/) (33k ⭐) — open-source AI coding assistant for VS Code / JetBrains.
* [**Cline**](https://github.com/cline/cline) (61k ⭐) — autonomous coding agent for VS Code.
* [**Zed AI**](https://zed.dev/ai) 🆕 — high-performance editor with native AI agent.
* [**Augment Code**](https://www.augmentcode.com/) — context-aware enterprise coding assistant.
* [**Cody (Sourcegraph)**](https://sourcegraph.com/cody) — code AI with full-codebase context.
* [**Codeium / Windsurf**](https://codeium.com/) — free AI autocomplete.
* [**Tabnine**](https://www.tabnine.com/) — privacy-focused; on-prem option.
* [**Devin (Cognition)**](https://devin.ai/) — autonomous SWE agent (paid, hosted).
* [**Bolt.new**](https://bolt.new/) — full-stack web app generation in browser.
* [**v0 (Vercel)**](https://v0.dev/) — AI UI generator with React/Next.js output.
* [**Lovable**](https://lovable.dev/) — AI app builder.
* [**Replit Agent**](https://replit.com/) — AI app generation in Replit.
* [**Deepnote**](https://deepnote.com/) — AI-first Jupyter alternative with native data integrations and a built-in agent.
* [Tura](https://github.com/Tura-AI/tura) — Local, open-source coding agent that understands a repository before changing it.

---

## 🤝 Agent Frameworks & MCP

> Build LLM agents that plan, use tools, and execute multi-step tasks. **2026's hottest category**.

### Agent Frameworks

* [**Claude Agent SDK**](https://docs.anthropic.com/en/api/agent-sdk) ⭐ 🆕 — Anthropic's official agent SDK with skills, memory, sandboxing.
* [**LangGraph**](https://langchain-ai.github.io/langgraph/) ⭐ (31k ⭐) — graph-based agent orchestration; production-ready.
* [**Anthropic Skills**](https://www.anthropic.com/news/skills) 🆕 — modular agent skills protocol.
* [**Pydantic AI**](https://ai.pydantic.dev/) ⭐ — type-safe agent framework; clean Python API.
* [**CrewAI**](https://www.crewai.com/) (51k ⭐) — role-based multi-agent framework.
* [**AutoGen (Microsoft)**](https://github.com/microsoft/autogen) (58k ⭐) — multi-agent conversation framework.
* [**OpenAI Swarm**](https://github.com/openai/swarm) (21k ⭐) — lightweight multi-agent orchestration.
* [**LlamaIndex Agents**](https://docs.llamaindex.ai/en/stable/module_guides/deploying/agents/) — agent runtime.
* [**Vercel AI SDK**](https://sdk.vercel.ai/) ⭐ — React/Next.js agent SDK.
* [**smolagents (Hugging Face)**](https://github.com/huggingface/smolagents) (27k ⭐) — minimal code-acting agent library.
* [**Strands Agents (AWS)**](https://github.com/strands-agents/sdk-python) 🆕 (6k ⭐) — AWS open-source agent SDK.
* [**Bedrock AgentCore**](https://aws.amazon.com/bedrock/agentcore/) 🆕 — AWS managed agent runtime.
* [**Letta (formerly MemGPT)**](https://github.com/letta-ai/letta) (22k ⭐) — agents with persistent memory.
* [**Inspect AI (UK AISI)**](https://inspect.aisi.org.uk/) — agent eval framework from UK AI Safety Institute.

### Model Context Protocol (MCP) 🔥

* [**Model Context Protocol Spec**](https://modelcontextprotocol.io/) ⭐ — Anthropic's open protocol for AI tool use. Industry standard since 2024.
* [**Anthropic MCP Servers**](https://github.com/modelcontextprotocol/servers) (85k ⭐) — official MCP servers (filesystem, fetch, GitHub, Postgres, Brave).
* [**MCP Python SDK**](https://github.com/modelcontextprotocol/python-sdk) (23k ⭐) — build MCP servers in Python.
* [**MCP TypeScript SDK**](https://github.com/modelcontextprotocol/typescript-sdk) (12k ⭐) — build MCP servers in TS.
* [**Awesome MCP Servers**](https://github.com/punkpeye/awesome-mcp-servers) ⭐ (86k ⭐) — community MCP server list.
* [**FastMCP**](https://github.com/jlowin/fastmcp) (25k ⭐) — Pythonic MCP server framework.

### Browser & Computer Use 🆕

* [**Anthropic Computer Use**](https://www.anthropic.com/news/3-5-models-and-computer-use) ⭐ — Claude controls your computer.
* [**OpenAI Atlas**](https://openai.com/atlas) 🆕 — OpenAI's agentic browser.
* [**Browser Use**](https://github.com/browser-use/browser-use) (92k ⭐) — open-source browser automation for agents.
* [**Skyvern**](https://github.com/Skyvern-AI/skyvern) (22k ⭐) — automate browser workflows with vision LLMs.
* [**Playwright MCP**](https://github.com/microsoft/playwright-mcp) (32k ⭐) — Playwright as an MCP server.
* [**Stagehand (Browserbase)**](https://github.com/browserbase/stagehand) (22k ⭐) — Playwright + AI for reliable agents.

---

## 📚 RAG & Vector Databases

> Retrieval-Augmented Generation: ground LLM answers in your data.

### RAG Frameworks

* [**LangChain**](https://www.langchain.com/) ⭐ (136k ⭐) — most popular framework for LLM apps and RAG.
* [**LlamaIndex**](https://www.llamaindex.ai/) ⭐ (49k ⭐) — data framework for LLM applications, RAG-focused.
* [**Haystack (deepset)**](https://haystack.deepset.ai/) (25k ⭐) — open-source LLM framework.
* [**RAGFlow**](https://github.com/infiniflow/ragflow) 🔥 (80k ⭐) — open-source RAG engine with deep document understanding.
* [**Cognita (TrueFoundry)**](https://github.com/truefoundry/cognita) — open-source RAG framework.
* [**Verba (Weaviate)**](https://github.com/weaviate/Verba) — RAG chatbot UI on Weaviate.
* [**Pathway**](https://github.com/pathwaycom/pathway) — real-time RAG and AI pipelines.

### Vector Databases

* [**pgvector**](https://github.com/pgvector/pgvector) ⭐ (21k ⭐) — Postgres extension; default for prototypes.
* [**Qdrant**](https://qdrant.tech/) ⭐ (31k ⭐) — open-source vector search engine in Rust; production-ready.
* [**Pinecone**](https://www.pinecone.io/) ⭐ — managed vector database; serverless option.
* [**Weaviate**](https://weaviate.io/) (16k ⭐) — open-source vector database with hybrid search.
* [**Chroma**](https://www.trychroma.com/) (28k ⭐) — embeddings database for AI apps; great DX for prototypes.
* [**Milvus**](https://milvus.io/) (44k ⭐) — open-source vector database for production.
* [**LanceDB**](https://lancedb.com/) — serverless / embedded vector database.
* [**Turbopuffer**](https://turbopuffer.com/) 🆕 — serverless vector DB on object storage.
* [**Vespa**](https://vespa.ai/) — search and recommendation with vector support.

### Embedding Models

* [**OpenAI text-embedding-3 / 4**](https://platform.openai.com/docs/guides/embeddings) — text-embedding-3-small/large.
* [**Cohere Embed v3 / v4**](https://cohere.com/embed) — multilingual embedding models.
* [**Voyage AI**](https://www.voyageai.com/) ⭐ — top-quality general embeddings (acquired by MongoDB).
* [**BGE (BAAI)**](https://huggingface.co/BAAI) 🇨🇳 — open-source embeddings, leaderboard contender.
* [**Sentence Transformers**](https://www.sbert.net/) — open-source embeddings library.
* [**Nomic Embed**](https://www.nomic.ai/embed) — open-source long-context embeddings.
* [**Mixedbread (mxbai-embed)**](https://www.mixedbread.ai/) — open-source embeddings.

---

## ⚡ LLM Inference & Hosting

* [**Ollama**](https://ollama.com/) ⭐ (171k ⭐) — run LLMs locally with one command.
* [**LM Studio**](https://lmstudio.ai/) — desktop GUI for local LLMs.
* [**Off Grid AI Desktop**](https://getoffgridai.co/desktop) — open-source (AGPL) macOS desktop app for fully offline local LLM chat, image generation, and dictation.
* [**llama.cpp**](https://github.com/ggerganov/llama.cpp) ⭐ (108k ⭐) — efficient LLM inference in C++.
* [**vLLM**](https://github.com/vllm-project/vllm) ⭐ (79k ⭐) — high-throughput LLM serving for production.
* [**SGLang**](https://github.com/sgl-project/sglang) 🆕 (27k ⭐) — fast structured-output inference engine.
* [Text Generation Inference (TGI)](https://github.com/huggingface/text-generation-inference) — Hugging Face's production server (archived; consider vLLM or SGLang).
* [**Together AI**](https://www.together.ai/) ⭐ — fast inference API for open models.
* [**Groq**](https://groq.com/) ⭐ — extremely fast LPU-based inference.
* [**Fireworks AI**](https://fireworks.ai/) — production inference platform.
* [**Replicate**](https://replicate.com/) — run open-source models in the cloud.
* [**UnoRouter**](https://unorouter.com/) — OpenAI-compatible gateway: one API key for 200+ models across OpenAI, Anthropic, Google and more, with usage-based pricing.
* [**Modal**](https://modal.com/) — serverless GPU for AI workloads.
* [**RunPod**](https://www.runpod.io/) — GPU cloud for AI.
* [**Lambda Cloud**](https://lambdalabs.com/) — GPU cloud focused on AI.
* [**Cerebras Inference**](https://inference.cerebras.ai/) 🆕 — wafer-scale fastest inference.

---

## 📊 LLM Ops & Observability

* [**LangSmith**](https://www.langchain.com/langsmith) ⭐ — debugging, testing, monitoring; default for LangChain shops.
* [**Helicone**](https://www.helicone.ai/) ⭐ (6k ⭐) — open-source LLM observability.
* [**Langfuse**](https://langfuse.com/) (27k ⭐) — open-source LLM engineering platform; eval + traces.
* [**Phoenix (Arize)**](https://phoenix.arize.com/) — open-source LLM observability in a notebook.
* [**Braintrust**](https://www.braintrust.dev/) ⭐ — eval-first observability for AI products.
* [**Weights & Biases (W&B Weave)**](https://wandb.ai/site/weave) — experiment tracking + LLM tracing.
* [**Promptfoo**](https://www.promptfoo.dev/) (21k ⭐) — open-source LLM eval framework.
* [**OpenLIT**](https://openlit.io/) — OpenTelemetry-native LLM observability.
* [**Opik (Comet)**](https://github.com/comet-ml/opik) 🆕 — open-source LLM eval + tracing.
* [**Inspect AI**](https://inspect.aisi.org.uk/) 🆕 — UK AISI's agent eval framework.

---

## 🎯 Fine-Tuning & Training

* [**Axolotl**](https://github.com/axolotl-ai-cloud/axolotl) ⭐ (12k ⭐) — easy fine-tuning of LLMs (LoRA, QLoRA, full).
* [**Unsloth**](https://unsloth.ai/) ⭐ (64k ⭐) — 2x faster LLM fine-tuning, less memory.
* [**Hugging Face TRL**](https://huggingface.co/docs/trl/index) (18k ⭐) — RLHF, DPO, PPO trainers.
* [**LLaMA Factory**](https://github.com/hiyouga/LLaMA-Factory) (71k ⭐) — unified LLM fine-tuning.
* [**Lit-GPT (Lightning AI)**](https://github.com/Lightning-AI/litgpt) — pretrain, fine-tune, serve LLMs.
* [**ColossalAI**](https://github.com/hpcaitech/ColossalAI) (41k ⭐) — large-scale training.
* [**veRL (ByteDance)**](https://github.com/volcengine/verl) 🆕 — RL training for LLMs.

---

## 🛠️ Development Frameworks

### Deep Learning Frameworks

* [**PyTorch**](https://pytorch.org/) ⭐ — by Meta; the de facto research framework.
* [**TensorFlow**](https://www.tensorflow.org/) — by Google; production focus.
* [**JAX**](https://github.com/google/jax) (36k ⭐) — by Google; functional, GPU/TPU.
* [**Keras 3**](https://keras.io/) — multi-backend high-level API.
* [**MLX (Apple)**](https://github.com/ml-explore/mlx) (26k ⭐) — array framework optimized for Apple Silicon.
* [**MAX / Mojo (Modular)**](https://www.modular.com/) — Python-superset language for AI performance.

### Python LLM Libraries

* [**Hugging Face Transformers**](https://github.com/huggingface/transformers) ⭐ (160k ⭐) — state-of-the-art models.
* [**LangChain**](https://github.com/langchain-ai/langchain) (136k ⭐) — LLM application framework.
* [**LlamaIndex**](https://github.com/run-llama/llama_index) (38k ⭐) — LLM data framework.
* [**Pydantic AI**](https://ai.pydantic.dev/) — type-safe agent framework.
* [**Instructor**](https://python.useinstructor.com/) ⭐ — structured outputs from LLMs.
* [**LiteLLM**](https://github.com/BerriAI/litellm) ⭐ (46k ⭐) — unified API for 100+ LLMs.
* [**Outlines**](https://github.com/outlines-dev/outlines) (14k ⭐) — guided / structured generation.
* [**DSPy**](https://github.com/stanfordnlp/dspy) ⭐ (34k ⭐) — programming (not prompting) LLMs.
* [**scikit-learn**](https://scikit-learn.org/) — classic ML in Python.
* [**Ray**](https://github.com/ray-project/ray) (42k ⭐) — distributed Python; underlies vLLM and many frameworks.

### TypeScript / JavaScript

* [**Vercel AI SDK**](https://sdk.vercel.ai/) ⭐ — React/Next.js AI app SDK.
* [**LangChain.js**](https://github.com/langchain-ai/langchainjs) — LangChain for JS.
* [**Mastra**](https://mastra.ai/) 🆕 (24k ⭐) — TS framework for agents, evals, workflows.
* [**TensorFlow.js**](https://www.tensorflow.org/js) — browser ML.

### Bot SDKs

* [**Anthropic SDK**](https://github.com/anthropics/anthropic-sdk-python) — official Claude SDK.
* [**OpenAI SDK**](https://github.com/openai/openai-python) (31k ⭐) — official OpenAI SDK.
* [**Discord.py**](https://github.com/Rapptz/discord.py) — Discord bot SDK.
* [**Slack Bolt**](https://github.com/slackapi/bolt-python) — Slack app framework.
* [**python-telegram-bot**](https://github.com/python-telegram-bot/python-telegram-bot) — Telegram bot SDK.
* [**Wechaty**](https://github.com/wechaty/wechaty) 🇨🇳 — WeChat bot framework.

### Datasets

* [**Hugging Face Datasets**](https://huggingface.co/datasets) ⭐ — central dataset hub.
* [**Common Crawl**](https://commoncrawl.org/) — web-scale data.
* [**Kaggle Datasets**](https://www.kaggle.com/datasets) — competition + reference datasets.
* [**Papers With Code Datasets**](https://paperswithcode.com/datasets) — benchmark datasets.
* [**The Pile**](https://pile.eleuther.ai/) — 800GB dataset for LLMs.
* [**FineWeb (HuggingFace)**](https://huggingface.co/datasets/HuggingFaceFW/fineweb) 🆕 — 15T-token cleaned web dataset.

---

## 🎓 Courses & Learning Paths

### Foundational ML / AI (Classics — still worth doing)

* [Machine Learning](https://www.coursera.org/learn/machine-learning) — *Stanford / Andrew Ng* — the classic.
* [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) — *deeplearning.ai* — neural nets, CNNs, RNNs, transformers.
* [CS231n: Convolutional Neural Networks](http://cs231n.stanford.edu/) — *Stanford* — CV gold standard.
* [CS224N: NLP with Deep Learning](http://web.stanford.edu/class/cs224n/) — *Stanford* — NLP foundations.
* [Practical Deep Learning for Coders](https://course.fast.ai/) — *fast.ai / Jeremy Howard* — top-down practical.
* [3Blue1Brown — Neural Networks](https://www.3blue1brown.com/topics/neural-networks) — visual deep dive.

### Modern LLM / Generative AI 🔥

* [**Karpathy's Neural Networks: Zero to Hero**](https://karpathy.ai/zero-to-hero.html) ⭐ — build neural nets, GPT, tokenizers from scratch. Best free LLM course.
* [**Hugging Face Agents Course**](https://huggingface.co/learn/agents-course) ⭐ — building LLM agents end-to-end.
* [**Hugging Face NLP Course**](https://huggingface.co/learn/nlp-course) — free, transformer-focused.
* [**Anthropic Courses**](https://github.com/anthropics/courses) — official courses on prompting, tool use, RAG, agents.
* [**LangChain Academy**](https://academy.langchain.com/) — LangChain and LangGraph courses.
* [**LLM Bootcamp (Full Stack DL)**](https://fullstackdeeplearning.com/llm-bootcamp/) — practical LLM app dev.
* [**Generative AI for Everyone**](https://www.deeplearning.ai/courses/generative-ai-for-everyone/) — *Andrew Ng* — non-technical intro.
* [**CS336: Language Modeling from Scratch**](https://stanford-cs336.github.io/) — *Stanford* — build a real LLM.

### Career-focused Bootcamps

* [Springboard AI/ML Career Track](https://www.springboard.com/courses/ai-machine-learning-career-track/) — US-focused online bootcamp with mentor.
* [Bloomtech (formerly Lambda School)](https://bloomtech.com/) — US online bootcamp.
* [Insight Data Science Fellows](https://insightfellows.com/) — fellowship for PhDs entering industry.
* [Maven AI Engineering Cohorts](https://maven.com/topics/artificial-intelligence) — cohort-based courses by industry experts.
* [Zero to Mastery — AI/ML Career Path](https://zerotomastery.io/career-paths/) — online ML bootcamp.
* [General Assembly Data Science Immersive](https://generalassemb.ly/) — full-time bootcamp, multiple cities.
* [JR Academy AI Engineer Bootcamp](https://jiangren.com.au/curriculum/ai-engineer-bootcamp) — project-based 6-month bootcamp covering MCP, RAG, agents, deployment.
* [JR Academy Vibe Coding](https://jiangren.com.au/learn/vibe-coding) — modern AI-augmented development with Cursor / Claude Code.
* [JR Academy Web Full-Stack Bootcamp](https://jiangren.com.au/program-course/web-code-bootcamp-or-learn-to-code-1) — Next.js / NestJS / AWS project bootcamp.
* [Recurse Center](https://www.recurse.com/) — self-directed programmer retreat (NYC).

### AI Engineer Specialization (Free Learning Hubs)

> Self-directed learning paths specifically for the AI Engineer role.

* [AI Engineer Roadmap (roadmap.sh)](https://roadmap.sh/ai-engineer) — community-curated step-by-step roadmap.
* [AI Engineer Reading List (Latent Space)](https://www.latent.space/p/2025-papers) — Swyx's annual must-read papers.
* [Generative AI Handbook (Will Brown)](https://genai-handbook.github.io/) — practical handbook.
* [Build LLM-Powered Apps (Hamel Husain)](https://hamel.dev/) — practical writing on LLM eval and ops.
* [Deep Learning AI — AI Engineering Specialization](https://www.deeplearning.ai/courses/) — Andrew Ng's structured paths.
* [JR Academy AI Engineer Hub](https://jiangren.com.au/learn/ai-engineer) — free chapter-based learning path: MCP, RAG, agents, deployment, with hands-on labs.
* [JR Academy Prompt Master Hub](https://jiangren.com.au/learn/prompt-master) — free prompt engineering chapter-based hub.
* [Awesome AI Engineer (community list)](https://github.com/dair-ai/Mathematics-for-ML) — math foundations.

### Specialized Topics

* [Reinforcement Learning Course](https://www.davidsilver.uk/teaching/) — *David Silver / DeepMind*.
* [CS285: Deep RL](http://rail.eecs.berkeley.edu/deeprlcourse/) — *UC Berkeley*.
* [Artificial Intelligence for Robotics](https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373) — *Sebastian Thrun*.

### Free Aggregators

* [Made With ML](https://madewithml.com/) — production ML foundations.
* [AI Engineer Roadmap](https://roadmap.sh/ai-engineer) — community-curated path.
* [Awesome MLOps](https://github.com/visenger/awesome-mlops) — production ML resources.

---

## 📖 Books, Papers & Blogs

### Books — Modern (2024-2026) 🔥

* [**AI Engineering**](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — *Chip Huyen* ⭐ — the definitive book on production LLM apps.
* [**Build a Large Language Model (From Scratch)**](https://www.manning.com/books/build-a-large-language-model-from-scratch) — *Sebastian Raschka* — pedagogical GPT build.
* [**Hands-On Large Language Models**](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/) — *Jay Alammar & Maarten Grootendorst*.
* [**Designing Machine Learning Systems**](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — *Chip Huyen* — production ML.

### Books — Foundations

* [Deep Learning](https://www.deeplearningbook.org/) — *Goodfellow, Bengio, Courville* — the foundational textbook.
* [Reinforcement Learning: An Introduction (2nd ed)](http://incompleteideas.net/book/the-book-2nd.html) — *Sutton & Barto*.
* [Hands-On ML with Scikit-Learn, Keras & TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) — *Aurélien Géron*.
* [Probabilistic Machine Learning](https://probml.github.io/pml-book/) — *Kevin Murphy* — rigorous reference.
* [The Hundred-Page Machine Learning Book](http://themlbook.com/) — *Andriy Burkov* — concise.

### Papers — Why Each Matters

> Read these to understand the field, in roughly chronological order.

* [**Attention Is All You Need (2017)**](https://arxiv.org/abs/1706.03762) ⭐ — introduced the Transformer; basis of every modern LLM.
* [**BERT (2018)**](https://arxiv.org/abs/1810.04805) — bidirectional Transformers; pretraining objective that powered NLP for 4 years.
* [**GPT-3 (2020)**](https://arxiv.org/abs/2005.14165) — "Language Models are Few-Shot Learners" — proved scaling works; in-context learning.
* [**Scaling Laws (2020)**](https://arxiv.org/abs/2001.08361) — formalized loss vs compute/params/data; the law that drove GPT-4 sizing.
* [**RAG (2020)**](https://arxiv.org/abs/2005.11401) — original retrieval-augmented generation paper.
* [**Chain-of-Thought (2022)**](https://arxiv.org/abs/2201.11903) — "let's think step by step" prompting unlocked reasoning.
* [**InstructGPT / RLHF (2022)**](https://arxiv.org/abs/2203.02155) — RLHF made models follow instructions; basis of ChatGPT.
* [**Chinchilla (2022)**](https://arxiv.org/abs/2203.15556) — corrected scaling laws; train smaller on more tokens.
* [**LLaMA (2023)**](https://arxiv.org/abs/2302.13971) — Meta's open-weights move that birthed the open ecosystem.
* [**ReAct (2022)**](https://arxiv.org/abs/2210.03629) — Reasoning + Acting prompt template; basis of modern agents.
* [**Toolformer (2023)**](https://arxiv.org/abs/2302.04761) — LLMs that learn to use tools; precursor to function calling.
* [**LoRA (2021)**](https://arxiv.org/abs/2106.09685) — low-rank adaptation; how everyone fine-tunes affordably.
* [**Direct Preference Optimization (2023)**](https://arxiv.org/abs/2305.18290) — DPO; simpler RLHF replacement.
* [**Mixtral of Experts (2024)**](https://arxiv.org/abs/2401.04088) — practical MoE that opened the era of efficient large models.
* [**DeepSeek-R1 (2025)**](https://arxiv.org/abs/2501.12948) 🇨🇳 — pure-RL reasoning training breakthrough.

### Blogs — Top Signal

* [**Lilian Weng's Blog (Lil'Log)**](https://lilianweng.github.io/) ⭐ — deep technical writing, every post a survey.
* [**Karpathy's Blog**](https://karpathy.github.io/) ⭐ — Andrej Karpathy's writing; legendary clarity.
* [**Sebastian Raschka's Magazine**](https://magazine.sebastianraschka.com/) — practical LLM and ML.
* [**Simon Willison's Blog**](https://simonwillison.net/) — daily AI tools and tips, unmatched volume.
* [**Anthropic Research**](https://www.anthropic.com/research) — Claude/safety research.
* [**OpenAI Research**](https://openai.com/research/) — papers and announcements.
* [**Google Research Blog**](https://research.google/blog/) — Google AI research.
* [**Hugging Face Blog**](https://huggingface.co/blog) — open-source AI updates.
* [**One Useful Thing (Ethan Mollick)**](https://www.oneusefulthing.org/) — practical AI essays for non-engineers.

---

## 🏢 Companies & Research Labs

### Foundation Model Labs

* [Anthropic](https://www.anthropic.com/) — Claude; AI safety research.
* [OpenAI](https://openai.com/) — GPT, ChatGPT, Sora, Codex.
* [Google DeepMind](https://deepmind.google/) — Gemini, AlphaFold, research.
* [Meta AI (FAIR)](https://ai.meta.com/) — Llama, PyTorch.
* [Mistral AI](https://mistral.ai/) — open-source / commercial models from France.
* [xAI](https://x.ai/) — Grok.
* [Cohere](https://cohere.com/) — enterprise LLMs.
* [AI21 Labs](https://www.ai21.com/) — Jamba and enterprise AI.
* [Stability AI](https://stability.ai/) — Stable Diffusion.
* [Black Forest Labs](https://blackforestlabs.ai/) — Flux image models.
* [Reka AI](https://www.reka.ai/) — multimodal frontier models.
* [DeepSeek](https://www.deepseek.com/) 🇨🇳 — Chinese open-source frontier models.
* [Alibaba Qwen Team](https://qwenlm.github.io/) 🇨🇳 — Qwen series.
* [Moonshot AI](https://www.moonshot.cn/) 🇨🇳 — Kimi K2.
* [Zhipu AI](https://www.zhipuai.cn/) 🇨🇳 — GLM series.

### AI Infrastructure & Platforms

* [Hugging Face](https://huggingface.co/) — model hub, datasets, training.
* [Replicate](https://replicate.com/) — run open-source models in the cloud.
* [Together AI](https://www.together.ai/) — fast open-model inference.
* [Groq](https://groq.com/) — extreme-speed LPU inference.
* [Cerebras](https://cerebras.ai/) — wafer-scale chip inference.
* [Modal](https://modal.com/) — serverless GPU.
* [Anyscale](https://www.anyscale.com/) — Ray-based distributed AI.
* [Databricks](https://www.databricks.com/) — data + AI platform.
* [Snowflake Cortex](https://www.snowflake.com/en/data-cloud/cortex/) — AI in the data warehouse.
* [Lightning AI](https://lightning.ai/) — Lightning Studios for ML.

### Enterprise / Vertical AI

* [Glean](https://www.glean.com/) — enterprise AI search.
* [Harvey AI](https://www.harvey.ai/) — legal AI.
* [Cresta](https://cresta.com/) — contact center AI.
* [Sierra](https://sierra.ai/) — customer service agents.
* [Decagon](https://decagon.ai/) — AI customer support agents.
* [Cursor (Anysphere)](https://www.cursor.com/) — AI coding company.
* [Cognition](https://www.cognition.ai/) — Devin SWE agent.
* [Scale AI](https://scale.com/) — data labeling and infrastructure.
* [DataRobot](https://www.datarobot.com/) — enterprise ML platform.

### AI Consulting & Implementation

* [Slalom AI Practice](https://www.slalom.com/services/data-and-ai) — global consulting with AI practice.
* [Boston Consulting Group X (BCG X)](https://www.bcg.com/x) — BCG's AI/digital build arm.
* [Accenture AI](https://www.accenture.com/us-en/services/applied-intelligence-index) — large-scale AI transformation.
* [Thoughtworks AI](https://www.thoughtworks.com/en-us/what-we-do/ai) — engineering-led AI delivery.
* [Modulai](https://modulai.io/) — boutique AI consultancy (EU).
* [MetaTree Lab](https://metatreelab.ai/) — AI consulting; LLM strategy, RAG and agent implementation, custom training.

---

## 🧠 Personal AI Tools

### General Assistants

* [**Claude**](https://claude.ai/) ⭐ — Anthropic's assistant; long context, careful reasoning.
* [**ChatGPT**](https://chat.openai.com/) ⭐ — OpenAI's general-purpose assistant.
* [**Google Gemini**](https://gemini.google.com/) — Google's assistant; native in Workspace.
* [**Perplexity**](https://www.perplexity.ai/) ⭐ — AI search; best for research questions.
* [**Grok**](https://grok.com/) — xAI's assistant with X integration.
* [**You.com**](https://you.com/) — AI search and chat.
* [**Pi (Inflection)**](https://pi.ai/) — empathetic personal AI.

### Productivity AI

* [Notion AI](https://www.notion.so/product/ai) — built into Notion docs.
* [Granola](https://www.granola.ai/) ⭐ — AI meeting notes; current favorite.
* [Otter.ai](https://otter.ai/) — meeting transcription veteran.
* [Reclaim.ai](https://reclaim.ai/) — calendar AI scheduling.
* [Motion](https://www.usemotion.com/) — AI task and calendar planner.
* [Mem](https://get.mem.ai/) — AI-organized note-taking.
* [Sunsama](https://www.sunsama.com/) — daily planner with AI.
* [Clay](https://clay.com/) — AI-powered CRM and outreach.

### Virtual Office & Remote Collaboration

* [Gather](https://www.gather.town/) — virtual office in 2D pixel-art world.
* [Teamflow](https://www.teamflow.com/) — virtual HQ for remote teams.
* [Mmhmm](https://www.mmhmm.app/) — AI presentation and async video.
* [MetaTown](https://metatown.ai/) — virtual office and meeting environment with AI agents.
* [Around](https://www.around.co/) — AI-enhanced video calls (compact tiles).

### AI Search

* [Perplexity](https://www.perplexity.ai/) ⭐ — research-grade AI search.
* [Phind](https://phind.com/) — AI search for developers.
* [Exa](https://exa.ai/) — search engine designed for AI/LLMs.
* [Tavily](https://tavily.com/) — search API for agents.
* [Linkup](https://www.linkup.so/) 🆕 — AI-grade search API.

---

## 🎨 Specialized AI Tools

### Image Generation & Design

* [**Midjourney**](https://www.midjourney.com/) ⭐ — high-quality image generation.
* [**DALL·E (OpenAI)**](https://openai.com/dall-e-3) — image generation in ChatGPT.
* [**Stable Diffusion (local)**](https://stability.ai/) — open-source image gen.
* [**Flux 1.1 Pro / Kontext**](https://blackforestlabs.ai/) ⭐ — best-in-class open image gen + editing.
* [**Recraft V3**](https://www.recraft.ai/) 🆕 — design-grade image generation.
* [**Ideogram 2.0**](https://ideogram.ai/) — image generation with great text rendering.
* [**Leonardo.AI**](https://leonardo.ai/) 🇦🇺 — Sydney-based image generation.
* [**Krea**](https://www.krea.ai/) — real-time AI canvas.
* [**Canva Magic Studio**](https://www.canva.com/magic-studio/) — AI design tools.
* [**Figma AI / Make**](https://www.figma.com/ai/) — AI in Figma.
* [**Photoshop Firefly**](https://www.adobe.com/products/photoshop/ai.html) — Adobe's generative fill.

### Video & Audio

* [**Sora 2 (OpenAI)**](https://openai.com/sora/) ⭐ 🆕 — text-to-video; current state-of-the-art.
* [**Veo 3 (Google)**](https://deepmind.google/technologies/veo/) ⭐ — video gen with native audio.
* [**Runway Gen-4**](https://runwayml.com/) — AI video generation and editing.
* [**Pika 2.0**](https://pika.art/) — text-to-video.
* [**Hailuo 02 (MiniMax)**](https://hailuoai.video/) 🇨🇳 — strong video gen.
* [**Kling AI**](https://klingai.com/) 🇨🇳 — Kuaishou's video gen.
* [**HeyGen**](https://www.heygen.com/) — AI avatars and translation.
* [**Synthesia**](https://www.synthesia.io/) — AI video for enterprise.
* [**Descript**](https://www.descript.com/) — edit audio/video like a doc.
* [**SummaryTube**](https://summarytube.com) — AI summaries, key moments, and transcripts for YouTube videos.
* [**VideoOverlayKit**](https://github.com/alichherawalla/video-overlay-kit) — renders 4-6s animated b-roll overlay mp4s for short-form social (LinkedIn / IG Reels / YouTube Shorts / TikTok). AI-driven via MCP: paste your script into Claude Code / Cursor / Codex, the model writes the scene spec and renders the mp4. Remotion + Tabler + Lottie. Free, MIT, local.
* [**ElevenLabs**](https://elevenlabs.io/) ⭐ — voice cloning and synthesis.
* [**Cartesia Sonic**](https://www.cartesia.ai/) 🆕 — sub-100ms voice for real-time agents.
* [**Hume EVI**](https://www.hume.ai/) — emotion-aware voice AI.
* [**Suno v4**](https://www.suno.ai/) — music generation.
* [**Udio**](https://www.udio.com/) — music generation.

### Writing & Content

* [Jasper AI](https://www.jasper.ai/) — AI writer for marketing teams.
* [Writesonic](https://writesonic.com/) — SEO content generator.
* [Copy.ai](https://www.copy.ai/) — AI marketing copy.
* [Grammarly](https://www.grammarly.com/) — AI writing assistant.
* [Sudowrite](https://www.sudowrite.com/) — AI for fiction writers.
* [Lex](https://lex.page/) — AI writing app for thinkers.

### Health / Medical

* [Ada Health](https://ada.com/) — symptom assessment.
* [Abridge](https://www.abridge.com/) ⭐ — clinical documentation AI; widely deployed in US health systems.
* [Suki AI](https://www.suki.ai/) — voice-enabled clinical AI.

### Finance

* [Bloomberg GPT](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/) — finance-specific LLM.
* [Hebbia](https://www.hebbia.com/) — AI for financial analysts.

### Legal

* [Harvey AI](https://www.harvey.ai/) — legal AI.
* [Spellbook](https://www.spellbook.legal/) — contract review AI.

### Travel

* [Mindtrip](https://mindtrip.ai/) — AI travel planning.
* [Layla](https://www.layla.ai/) — travel AI assistant.

### Education

* [Khan Academy Khanmigo](https://www.khanmigo.ai/) ⭐ — AI tutor for students.
* [CodeKidz](https://codekidz.ai) — AI-powered programming learning for kids.

### Career & Resume

* [Teal](https://www.tealhq.com/) — AI resume builder + job tracker.
* [Rezi](https://www.rezi.ai/) — AI resume builder optimized for ATS.
* [ResumeWorded](https://resumeworded.com/) — AI resume + LinkedIn profile feedback.
* [Kickresume](https://www.kickresume.com/) — AI resume and cover letter builder.
* [JobPin AI](https://jobpin.ai/) — AI resume editing, ATS optimization, and job matching.
* [Final Round AI](https://www.finalroundai.com/) — AI interview copilot.

---

## 📰 News, Newsletters & Podcasts

### Newsletters

* [**The Batch (deeplearning.ai)**](https://www.deeplearning.ai/the-batch/) ⭐ — Andrew Ng's weekly newsletter.
* [**Latent Space**](https://www.latent.space/) ⭐ — Swyx's AI engineering practitioner newsletter.
* [**Import AI (Jack Clark)**](https://importai.substack.com/) ⭐ — AI policy and research.
* [**The Sequence**](https://thesequence.substack.com/) — research summaries.
* [**Last Week in AI**](https://lastweekin.ai/) — weekly AI news.
* [**TLDR AI**](https://tldr.tech/ai) — daily AI news in 5 minutes.
* [**Ben's Bites**](https://www.bensbites.com/) — daily AI news for non-technical readers.
* [**One Useful Thing (Ethan Mollick)**](https://www.oneusefulthing.org/) — practical AI essays.
* [**Interconnects (Nathan Lambert)**](https://www.interconnects.ai/) — open-source AI commentary.

### Podcasts

* [**Latent Space Podcast**](https://www.latent.space/podcast) ⭐ — AI engineering deep dives.
* [**Dwarkesh Podcast**](https://www.dwarkeshpatel.com/) ⭐ — AI researchers and founders.
* [**The Lex Fridman Podcast**](https://lexfridman.com/podcast/) — long-form AI/tech conversations.
* [**No Priors**](https://www.no-priors.com/) — Sarah Guo & Elad Gil on AI.
* [**The TWIML AI Podcast**](https://twimlai.com/podcast/twimlai/) — This Week in ML & AI.
* [**Practical AI**](https://changelog.com/practicalai) — applied AI for engineers.
* [**Machine Learning Street Talk**](https://www.youtube.com/@MachineLearningStreetTalk) — academic ML discussions.

### News Sites

* [**Hacker News**](https://news.ycombinator.com/) — community AI discussion.
* [**ArXiv (cs.CL / cs.AI)**](https://arxiv.org/list/cs.AI/recent) — preprints.
* [**Papers with Code**](https://paperswithcode.com/) — papers + implementations.
* [**The Information AI**](https://www.theinformation.com/topics/artificial-intelligence) — paid; insider news.
* [**Semianalysis**](https://semianalysis.com/) — AI hardware and infrastructure analysis.

---

## 🎤 Events & Conferences

* [**NeurIPS**](https://neurips.cc/) — premier ML research conference.
* [**ICML**](https://icml.cc/) — International Conference on Machine Learning.
* [**ICLR**](https://iclr.cc/) — Learning Representations.
* [**CVPR**](https://cvpr.thecvf.com/) — Computer Vision and Pattern Recognition.
* [**ACL**](https://www.aclweb.org/) — Computational Linguistics.
* [**The AI Engineer Summit / World's Fair**](https://www.ai.engineer/) ⭐ — practitioner conference (SF/NYC).
* [**Anthropic Builder Summit**](https://www.anthropic.com/events) — Anthropic developer events.
* [**OpenAI DevDay**](https://devday.openai.com/) — OpenAI developer event.
* [**Hugging Face Events**](https://huggingface.co/events) — community events.
* [**Build Club Sydney**](https://www.buildclub.ai/) 🇦🇺 — AU AI builders.

---

## 💼 AI Jobs

* [Moai Jobs](https://www.moaijobs.com/) — top AI company jobs.
* [AI Jobster](https://aijobster.work/) — remote AI jobs.
* [Hugging Face Jobs](https://huggingface.co/jobs) — open-source AI roles.
* [LinkedIn AI Engineer search](https://www.linkedin.com/jobs/search/?keywords=AI%20Engineer) — global AI jobs.
* [WhoIsHiring (HN)](https://hnhiring.com/) — Hacker News hiring threads.
* [Cracked Engineers](https://www.crackedengineers.com/) — hand-picked tech jobs.
* [Built In](https://builtin.com/jobs) — US tech jobs by city.
* [levels.fyi](https://www.levels.fyi/) — comp benchmarking.
* For region-specific jobs, see [🌍 AI Scene by Country](#-ai-scene-by-country).

---

## 🌐 AI Communities by City

* [San Francisco AI Meetup](http://www.meetup.com/superintelligencemeetup/) — SF community.
* [New York AI](http://newyork.ai/) — NYC community.
* [Seattle AI](http://seattle.city.ai/) — Seattle community.
* [London AI](http://www.london.ai/) — London community.
* [Amsterdam AI](http://amsterdam.ai/) — Amsterdam community.
* [Hong Kong AI](http://hkg.ai/) — HK community.

For Sydney, Melbourne, Beijing, Shanghai, Singapore, KL — see [🌍 AI Scene by Country](#-ai-scene-by-country).

---

## 🌍 AI Scene by Country

> Country-specific resources — universities, companies, bootcamps, hiring, visa info, and communities. Contributions from people on the ground welcome — please open a PR for your country.

### 🇺🇸 USA

**Universities & Research**
* [Stanford AI Lab (SAIL)](https://ai.stanford.edu/) — academic AI research.
* [MIT CSAIL](https://www.csail.mit.edu/) — Computer Science and AI Lab.
* [Carnegie Mellon LTI / MLD](https://www.cmu.edu/ai/) — Language Technologies / ML departments.
* [UC Berkeley BAIR](https://bair.berkeley.edu/) — Berkeley AI Research.
* [Princeton NLP](https://nlp.princeton.edu/) — academic groups.

**Bootcamps & Career Programs**
* [Springboard AI/ML Career Track](https://www.springboard.com/courses/ai-machine-learning-career-track/) — online AI bootcamp.
* [Bloomtech](https://bloomtech.com/) — online tech bootcamp.
* [Insight Data Science Fellows](https://insightfellows.com/) — fellowship for PhDs entering industry.
* [Recurse Center](https://www.recurse.com/) — self-directed programmer retreat (NYC).
* [Anthropic Fellowship](https://www.anthropic.com/careers) — Anthropic's research fellowship.

**Hiring & Comp**
* [levels.fyi](https://www.levels.fyi/) — comp data for US tech roles.
* [Built In](https://builtin.com/jobs) — US tech jobs by city.

### 🇨🇳 China

**大学与研究院**
* [清华大学 THUNLP / AI Institute](https://nlp.csai.tsinghua.edu.cn/) — 清华 AI / NLP 研究.
* [北京大学 — 王选计算机研究所](https://www.icst.pku.edu.cn/) — 北大 AI 研究.
* [上海交大 — 人工智能研究院](https://ai.sjtu.edu.cn/) — 上交 AI 研究.
* [北京智源人工智能研究院 (BAAI)](https://www.baai.ac.cn/) — 智源研究院.
* [上海人工智能实验室 (Shanghai AI Lab)](https://www.shlab.org.cn/) — 公共大模型研究.
* [香港中文大学 MMLab](http://mmlab.ie.cuhk.edu.hk/) — 港中文 多媒体实验室.

**公司 & 大模型**
* [DeepSeek](https://www.deepseek.com/) ⭐ — 深度求索, 开源前沿大模型.
* [通义千问 Qwen (Alibaba)](https://qwenlm.github.io/) ⭐ — 阿里通义.
* [Moonshot AI Kimi](https://kimi.moonshot.cn/) ⭐ — 月之暗面 Kimi K2.
* [豆包 (ByteDance)](https://www.doubao.com/) — 字节豆包.
* [智谱 AI ChatGLM](https://www.zhipuai.cn/) — 清华系大模型.
* [MiniMax abab](https://www.minimaxi.com/) — MiniMax.
* [百度文心 ERNIE](https://yiyan.baidu.com/) — 文心一言.
* [腾讯混元](https://hunyuan.tencent.com/) — 混元大模型.
* [百川智能 Baichuan](https://www.baichuan-ai.com/) — 百川大模型.
* [01.AI Yi](https://www.lingyiwanwu.com/) — 零一万物 Yi 系列.

**学习平台 & 资讯**
* [极客时间](https://time.geekbang.org/) — 程序员付费课程.
* [慕课网 / 网易云课堂](https://www.imooc.com/) — 综合在线课程.
* [量子位 (QbitAI)](https://www.qbitai.com/) — AI 资讯媒体.
* [机器之心 (Synced)](https://www.jiqizhixin.com/) — AI 研究资讯.
* [PaperWeekly](https://www.paperweekly.site/) — 论文阅读社区.
* [Datawhale](https://www.datawhale.cn/) — 开源 AI 学习社区.

### 🇦🇺 Australia

**Universities & Education**
* [University of Sydney — AI & ML](https://www.sydney.edu.au/engineering/study/areas-of-study/computer-science.html) — academic programs.
* [UNSW AI Institute](https://www.ai.unsw.edu.au/) — research-led AI education.
* [University of Melbourne — AI](https://study.unimelb.edu.au/find/courses/major/artificial-intelligence/) — academic programs.
* [Monash University — Data Science & AI](https://www.monash.edu/it/study) — academic programs.
* [JR Academy](https://jiangren.com.au) — project-based AI engineering bootcamp; global cohorts with HQ in Australia.

**Hiring**
* [Atlassian Careers](https://www.atlassian.com/company/careers) — Sydney-based, hiring AI engineers.
* [Canva Engineering](https://www.canva.com/careers/) — Sydney-based, AI/ML roles.
* [Australian Government Digital Transformation Agency](https://www.dta.gov.au/) — public sector AI.
* [Build Club AI](https://www.buildclub.ai/) — Sydney AI builders community + jobs.
* [JobPin AI](https://jobpin.ai/) — AI-powered resume editing, ATS optimization, and job matching.
* [JR Academy Career Coaching](https://jiangren.com.au/career-coaching) — AI Engineer career coaching and placement.

**Visa Pathways for AI Engineers**
* **482 TSS** — employer-sponsored temporary skilled visa.
* **186 ENS** — employer-sponsored permanent residency.
* **189 Skilled Independent** — points-tested PR; tech occupations on MLTSSL.
* **Global Talent Visa (GTI / Subclass 858)** — for high-achieving AI specialists.

**Companies & Labs**
* [Canva](https://www.canva.com/) — Sydney; Magic Design, AI image gen.
* [Atlassian](https://www.atlassian.com/) — Sydney; Atlassian Intelligence.
* [Culture Amp](https://www.cultureamp.com/) — Melbourne; HR AI.
* [Cochlear](https://www.cochlear.com/) — Sydney; medical AI.
* [SafetyCulture](https://safetyculture.com/) — Sydney/Townsville; AI for inspections.
* [Harrison.ai](https://harrison.ai) — Sydney; medical AI.
* [Leonardo.AI](https://leonardo.ai) — Sydney; image generation.
* [Relevance AI](https://relevanceai.com/) — Sydney; agent platform.

**Meetups & Communities**
* [Build Club Sydney](https://www.buildclub.ai/) — community of AI builders.
* [Chinese AI Association (Sydney)](https://chineseai.org.au/) — AU 华人 AI 社区.
* [AI Sydney Meetup](https://www.meetup.com/topics/artificial-intelligence/au/sydney/) — regular events.
* [AI Melbourne Meetup](https://www.meetup.com/topics/artificial-intelligence/au/melbourne/) — regular events.

### 🇲🇾 Malaysia

**Universities**
* [University of Malaya (UM)](https://www.um.edu.my/) — flagship public university.
* [Universiti Sains Malaysia (USM)](https://cs.usm.my/) — School of Computer Sciences.
* [Multimedia University (MMU)](https://www.mmu.edu.my/) — Cyberjaya tech university.
* [Universiti Teknologi Malaysia (UTM)](https://www.utm.my/) — engineering & AI research.
* [Asia Pacific University (APU)](https://www.apu.edu.my/) — data science & AI programs.

**Companies & Hiring (KL / Cyberjaya)**
* [Grab](https://grab.careers/) — Southeast Asia super-app; ML roles in KL.
* [Carsome](https://www.carsome.my/) — used-car platform with AI pricing.
* [Aerodyne](https://www.aerodyne.group/) — drone AI; HQ Cyberjaya.
* [iPay88](https://www.ipay88.com/) — fintech with AI applications.
* [Hiredly](https://www.hiredly.com/) — Malaysia tech jobs platform.

**Communities**
* [AI Malaysia Meetup](https://www.meetup.com/topics/artificial-intelligence/my/) — local meetups.
* [Google Developer Groups KL](https://gdg.community.dev/gdg-cloud-kuala-lumpur/) — including AI/ML events.
* [PyData KL](https://www.meetup.com/PyData-KL/) — Python + data community.

### 🇸🇬 Singapore

**Universities & Research**
* [National University of Singapore (NUS)](https://www.comp.nus.edu.sg/) — top SEA CS school.
* [Nanyang Technological University (NTU)](https://www.ntu.edu.sg/computing) — AI / ML labs.
* [Singapore Management University (SMU)](https://scis.smu.edu.sg/) — applied AI.
* [A*STAR I²R](https://www.a-star.edu.sg/i2r) — government AI research.

**Government & Initiatives**
* [AI Singapore](https://aisingapore.org/) ⭐ — national AI program (AI Apprenticeship, Trailblazer).
* [SGTech](https://www.sgtech.org.sg/) — Singapore tech industry association.

**Companies & Hiring**
* [Sea / Shopee / Garena](https://career.sea.com/) — Sea Group, large AI/ML team.
* [Grab AI Center](https://grab.careers/) — Singapore HQ.
* [GovTech Singapore](https://www.tech.gov.sg/careers/) — public-sector AI.
* [Tech in Asia Jobs](https://www.techinasia.com/jobs) — SEA tech jobs.

> Adding a country? Open a PR. Helpful info: top universities, AI companies, hiring resources, communities, and (if relevant) visa pathways.

---

## 🤖 Robotics & Embodied AI

* [**Boston Dynamics**](https://www.bostondynamics.com) — Atlas, Spot.
* [**Figure AI**](https://www.figure.ai/) 🔥 — humanoid robots; Figure 02.
* [**1X Technologies**](https://www.1x.tech/) — Neo home humanoid.
* [**Tesla Optimus**](https://www.tesla.com/AI) — humanoid robot.
* [**Physical Intelligence (Pi)**](https://www.physicalintelligence.company/) 🆕 — robotics foundation models.
* [**Skild AI**](https://www.skild.ai/) 🆕 — general-purpose robotics intelligence.
* [**Sanctuary AI Phoenix**](https://www.sanctuary.ai/) — humanoid robot.
* [**DJI**](http://www.dji.com/) — drones.
* [**Aerodyne**](https://www.aerodyne.group/) 🇲🇾 — drone AI; Malaysia.
* [**iRobot**](http://www.irobot.com/) — Roomba.

### Robotics frameworks

* [LeRobot (Hugging Face)](https://github.com/huggingface/lerobot) 🆕 (24k ⭐) — open-source robotics learning.
* [ROS 2](https://www.ros.org/) — Robot Operating System.
* [NVIDIA Isaac](https://developer.nvidia.com/isaac) — robotics platform.

---

## Contributing

Open a pull request or email **hello@jiangren.com.au**.

**Quick rules**:
* Add resources still active and useful (we periodically prune dead links).
* Keep entries to one line: `[Name](url) — short description`.
* Place new entries in the most appropriate section.
* No affiliate / referral links without disclosure.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for full guidelines and [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) for community standards.

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [JR Academy](https://jiangren.com.au) has waived all copyright and related or neighboring rights to this work.
