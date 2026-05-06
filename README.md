# Awesome Artificial Intelligence

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/hades217/awesome-ai?style=social)](https://github.com/hades217/awesome-ai/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/hades217/awesome-ai)](https://github.com/hades217/awesome-ai/commits/master)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> A community-curated list of artificial intelligence resources — foundation models, agent frameworks, AI coding tools, courses, companies, jobs, and country-specific AI scenes (USA, China, Australia, Malaysia, Singapore).

Maintained since 2017 by [Lightman Wang](https://github.com/hades217) ([LinkedIn](https://www.linkedin.com/in/lightman-wang/)).

Contributions welcome — open a PR or [start a discussion](https://github.com/hades217/awesome-ai/discussions). See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Contents

1. [Foundation Models & APIs](#foundation-models--apis) — Claude, GPT, Gemini, Llama, Qwen
2. [AI Coding Tools](#ai-coding-tools) — Cursor, Claude Code, Copilot, Aider
3. [Agent Frameworks & MCP](#agent-frameworks--mcp) — LangGraph, CrewAI, Model Context Protocol
4. [RAG & Vector Databases](#rag--vector-databases) — LangChain, LlamaIndex, Pinecone
5. [LLM Inference & Hosting](#llm-inference--hosting) — vLLM, Ollama, llama.cpp
6. [LLM Ops & Observability](#llm-ops--observability) — Helicone, LangSmith, Phoenix
7. [Fine-Tuning & Training](#fine-tuning--training) — Axolotl, Unsloth, LoRA
8. [Development Frameworks](#development-frameworks) — PyTorch, JAX, TensorFlow
9. [Courses & Learning Paths](#courses--learning-paths)
10. [Books, Papers & Blogs](#books-papers--blogs)
11. [Companies & Research Labs](#companies--research-labs)
12. [Personal AI Tools](#personal-ai-tools)
13. [Specialized AI Tools](#specialized-ai-tools) — Writing, Health, Finance, Travel
14. [News, Newsletters & Podcasts](#news-newsletters--podcasts)
15. [Events & Conferences](#events--conferences)
16. [AI Jobs](#ai-jobs)
17. [AI Communities by City](#ai-communities-by-city)
18. [🌍 AI Scene by Country](#-ai-scene-by-country) — USA, China, Australia, Malaysia, Singapore
19. [Contributing](#contributing)

---

## Foundation Models & APIs

### Closed-source / Commercial APIs

* [**Anthropic Claude**](https://www.anthropic.com/claude) — Claude 4.5 / 4.7 family. Strong reasoning, long context, code generation.
* [**OpenAI GPT**](https://openai.com/api/) — GPT-4, GPT-4o, o1 reasoning models.
* [**Google Gemini**](https://ai.google.dev/) — Gemini 2.0 Flash / Pro, multimodal.
* [**xAI Grok**](https://x.ai/) — Grok 3 with real-time web access.
* [**Cohere**](https://cohere.com/) — enterprise LLM platform.
* [**Mistral AI**](https://mistral.ai/) — Mistral Large, Codestral.
* [**Perplexity API**](https://www.perplexity.ai/) — search-grounded LLM.

### Open-source Models

* [**Meta Llama**](https://llama.meta.com/) — Llama 3.x family, open weights.
* [**Qwen (Alibaba)**](https://qwenlm.github.io/) — Qwen 2.5 / 3, multilingual including Chinese.
* [**DeepSeek**](https://www.deepseek.com/) — DeepSeek-V3, R1 reasoning model.
* [**Mistral Open Models**](https://mistral.ai/technology/#models) — Mixtral, Mistral 7B.
* [**Microsoft Phi**](https://azure.microsoft.com/en-us/products/phi) — small language models.
* [**Hugging Face Hub**](https://huggingface.co/) — central hub for open-source models.

### Multimodal & Specialized

* [**Stable Diffusion**](https://stability.ai/) — open image generation.
* [**Flux**](https://blackforestlabs.ai/) — high-quality image generation.
* [**Sora (OpenAI)**](https://openai.com/sora/) — video generation.
* [**Veo (Google)**](https://deepmind.google/technologies/veo/) — video generation.
* [**ElevenLabs**](https://elevenlabs.io/) — voice synthesis and cloning.
* [**Whisper (OpenAI)**](https://openai.com/research/whisper) — open-source speech-to-text.
* [**Suno**](https://www.suno.ai/) — music generation.

---

## AI Coding Tools

> Tools that help engineers write, review, and refactor code with AI.

* [**Claude Code**](https://www.anthropic.com/claude-code) — Anthropic's CLI for software engineering with Claude.
* [**Cursor**](https://www.cursor.com/) — AI-first code editor, fork of VS Code.
* [**GitHub Copilot**](https://github.com/features/copilot) — original AI pair programmer, now with Workspace and CLI features.
* [**Windsurf**](https://codeium.com/windsurf) — Codeium's AI editor.
* [**Aider**](https://aider.chat/) — open-source AI pair programmer in your terminal.
* [**Continue**](https://continue.dev/) — open-source AI coding assistant for VS Code / JetBrains.
* [**Cline**](https://github.com/cline/cline) — autonomous coding agent for VS Code.
* [**Sourcegraph Cody**](https://sourcegraph.com/cody) — code AI with codebase context.
* [**Codeium**](https://codeium.com/) — free AI autocomplete for many languages.
* [**Tabnine**](https://www.tabnine.com/) — privacy-focused AI code completion.
* [**Bolt.new**](https://bolt.new/) — full-stack web app generation in browser.
* [**v0 (Vercel)**](https://v0.dev/) — AI UI generator with React/Next.js output.
* [**Lovable**](https://lovable.dev/) — AI app builder.
* [**Replit Agent**](https://replit.com/) — AI app generation in Replit.

---

## Agent Frameworks & MCP

> Build AI agents that can use tools, plan, and execute multi-step tasks.

### Agent Frameworks

* [**LangGraph**](https://langchain-ai.github.io/langgraph/) — graph-based agent orchestration from LangChain team.
* [**CrewAI**](https://www.crewai.com/) — role-based multi-agent framework.
* [**AutoGen (Microsoft)**](https://github.com/microsoft/autogen) — multi-agent conversation framework.
* [**OpenAI Swarm**](https://github.com/openai/swarm) — lightweight multi-agent orchestration.
* [**LlamaIndex Agents**](https://docs.llamaindex.ai/en/stable/module_guides/deploying/agents/) — agent runtime.
* [**Vercel AI SDK**](https://sdk.vercel.ai/) — AI app SDK for TypeScript/React.
* [**Pydantic AI**](https://ai.pydantic.dev/) — agent framework with type safety.
* [**smolagents (Hugging Face)**](https://github.com/huggingface/smolagents) — minimal agent library.
* [**Letta (formerly MemGPT)**](https://github.com/letta-ai/letta) — agents with persistent memory.

### Model Context Protocol (MCP)

* [**Model Context Protocol Spec**](https://modelcontextprotocol.io/) — Anthropic's open protocol for AI tool use.
* [**Anthropic MCP Servers**](https://github.com/modelcontextprotocol/servers) — official MCP server implementations.
* [**MCP Python SDK**](https://github.com/modelcontextprotocol/python-sdk) — build MCP servers in Python.
* [**MCP TypeScript SDK**](https://github.com/modelcontextprotocol/typescript-sdk) — build MCP servers in TypeScript.
* [**Awesome MCP Servers**](https://github.com/punkpeye/awesome-mcp-servers) — community MCP server list.

### Browser & Computer Use

* [**Anthropic Computer Use**](https://www.anthropic.com/news/3-5-models-and-computer-use) — Claude can control your computer.
* [**Playwright MCP**](https://github.com/microsoft/playwright-mcp) — browser automation via MCP.
* [**Browser Use**](https://github.com/browser-use/browser-use) — browser automation for agents.

---

## RAG & Vector Databases

> Retrieval-Augmented Generation: ground LLM answers in your data.

### RAG Frameworks

* [**LangChain**](https://www.langchain.com/) — most popular framework for LLM apps and RAG.
* [**LlamaIndex**](https://www.llamaindex.ai/) — data framework for LLM applications, RAG-focused.
* [**Haystack (deepset)**](https://haystack.deepset.ai/) — open-source LLM framework.
* [**RAGFlow**](https://github.com/infiniflow/ragflow) — open-source RAG engine.
* [**Verba (Weaviate)**](https://github.com/weaviate/Verba) — RAG chatbot powered by Weaviate.
* [**Pathway**](https://github.com/pathwaycom/pathway) — real-time RAG and AI pipelines.

### Vector Databases

* [**Pinecone**](https://www.pinecone.io/) — managed vector database.
* [**Weaviate**](https://weaviate.io/) — open-source vector database.
* [**Qdrant**](https://qdrant.tech/) — open-source vector search engine in Rust.
* [**Chroma**](https://www.trychroma.com/) — embeddings database for AI apps.
* [**Milvus**](https://milvus.io/) — open-source vector database for production.
* [**pgvector**](https://github.com/pgvector/pgvector) — PostgreSQL extension for vector similarity.
* [**LanceDB**](https://lancedb.com/) — serverless vector database.
* [**Vespa**](https://vespa.ai/) — search and recommendation platform with vector support.

### Embedding Models

* [**OpenAI Embeddings**](https://platform.openai.com/docs/guides/embeddings) — text-embedding-3-small/large.
* [**Cohere Embed**](https://cohere.com/embed) — multilingual embedding models.
* [**Voyage AI**](https://www.voyageai.com/) — high-quality embedding models.
* [**Sentence Transformers**](https://www.sbert.net/) — open-source embeddings.
* [**Nomic Embed**](https://www.nomic.ai/embed) — open-source embeddings.

---

## LLM Inference & Hosting

* [**Ollama**](https://ollama.com/) — run LLMs locally with one command.
* [**LM Studio**](https://lmstudio.ai/) — desktop app for running local LLMs.
* [**llama.cpp**](https://github.com/ggerganov/llama.cpp) — efficient LLM inference in C++.
* [**vLLM**](https://github.com/vllm-project/vllm) — high-throughput LLM serving.
* [**Text Generation Inference (TGI)**](https://github.com/huggingface/text-generation-inference) — Hugging Face's production server.
* [**Together AI**](https://www.together.ai/) — fast inference API for open models.
* [**Groq**](https://groq.com/) — extremely fast LPU-based inference.
* [**Fireworks AI**](https://fireworks.ai/) — production inference platform.
* [**Replicate**](https://replicate.com/) — run open-source models in the cloud.
* [**Modal**](https://modal.com/) — serverless GPU for AI workloads.
* [**RunPod**](https://www.runpod.io/) — GPU cloud for AI.

---

## LLM Ops & Observability

* [**LangSmith**](https://www.langchain.com/langsmith) — debugging, testing, monitoring for LLM apps.
* [**Helicone**](https://www.helicone.ai/) — open-source LLM observability.
* [**Phoenix (Arize)**](https://phoenix.arize.com/) — open-source LLM observability in a notebook.
* [**Braintrust**](https://www.braintrust.dev/) — eval and observability for AI products.
* [**Langfuse**](https://langfuse.com/) — open-source LLM engineering platform.
* [**Weights & Biases (W&B)**](https://wandb.ai/) — experiment tracking, also for LLMs.
* [**Fiddler AI**](https://www.fiddler.ai/) — ML & LLM observability with guardrails.
* [**Neptune.ai**](https://neptune.ai/) — experiment tracking and model registry.
* [**Promptfoo**](https://www.promptfoo.dev/) — open-source LLM eval framework.
* [**OpenLIT**](https://openlit.io/) — OpenTelemetry-native LLM observability.

---

## Fine-Tuning & Training

* [**Axolotl**](https://github.com/axolotl-ai-cloud/axolotl) — easy fine-tuning of LLMs (LoRA, QLoRA, full).
* [**Unsloth**](https://unsloth.ai/) — 2x faster LLM fine-tuning, less memory.
* [**Hugging Face TRL**](https://huggingface.co/docs/trl/index) — RLHF, DPO, PPO trainers.
* [**LLaMA Factory**](https://github.com/hiyouga/LLaMA-Factory) — unified LLM fine-tuning.
* [**Lit-GPT (Lightning AI)**](https://github.com/Lightning-AI/litgpt) — pretrain, fine-tune, serve LLMs.
* [**ColossalAI**](https://github.com/hpcaitech/ColossalAI) — large-scale training.

---

## Courses & Learning Paths

### Foundational ML / AI (Classics)

* [Machine Learning](https://www.coursera.org/learn/machine-learning) — *Stanford / Andrew Ng* — the classic introduction.
* [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) — *deeplearning.ai / Andrew Ng* — neural networks, CNNs, RNNs, transformers.
* [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/) — *Stanford* — gold standard for CV.
* [CS224N: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/) — *Stanford* — NLP foundations.
* [Practical Deep Learning for Coders](https://course.fast.ai/) — *fast.ai / Jeremy Howard* — top-down practical approach.
* [Introduction to Artificial Intelligence](http://ai.berkeley.edu/home.html) — *UC Berkeley*.
* [MIT Artificial Intelligence (6.034)](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-034-artificial-intelligence-fall-2010/) — classic MIT lectures.

### Modern LLM / Generative AI

* [**Generative AI for Everyone**](https://www.deeplearning.ai/courses/generative-ai-for-everyone/) — *deeplearning.ai / Andrew Ng* — non-technical intro.
* [**LLM Bootcamp (The Full Stack)**](https://fullstackdeeplearning.com/llm-bootcamp/) — practical LLM app dev.
* [**Hugging Face NLP Course**](https://huggingface.co/learn/nlp-course) — free, practical, transformer-focused.
* [**Hugging Face Agents Course**](https://huggingface.co/learn/agents-course) — building LLM agents.
* [**Anthropic Courses**](https://github.com/anthropics/courses) — official Anthropic courses on prompting, tool use, RAG.
* [**LangChain Academy**](https://academy.langchain.com/) — LangChain and LangGraph courses.
* [**Karpathy's Neural Networks: Zero to Hero**](https://karpathy.ai/zero-to-hero.html) — build neural nets, GPT, tokenizers from scratch.
* [**3Blue1Brown — Neural Networks**](https://www.3blue1brown.com/topics/neural-networks) — visual deep dive.

### Career-focused Bootcamps

* [Springboard AI/ML Bootcamp](https://www.springboard.com/courses/ai-machine-learning-career-track/) — US-focused.
* [Bloomtech (formerly Lambda School)](https://bloomtech.com/) — US online bootcamp.
* [Insight Data Science Fellows](https://insightfellows.com/) — US fellowship for PhDs / postdocs entering industry.
* [JR Academy AI Engineer Bootcamp](https://jiangren.com.au/curriculum/ai-engineer-bootcamp) — Australia-focused project-based bootcamp.
* [Recurse Center](https://www.recurse.com/) — self-directed programmer retreat; not AI-only but many alumni go into AI.

### Specialized Topics

* [Reinforcement Learning Course](https://www.davidsilver.uk/teaching/) — *David Silver / DeepMind*.
* [CS285: Deep Reinforcement Learning](http://rail.eecs.berkeley.edu/deeprlcourse/) — *UC Berkeley*.
* [CS336: Language Modeling from Scratch](https://stanford-cs336.github.io/) — *Stanford*.
* [Artificial Intelligence for Robotics](https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373) — *Georgia Tech / Sebastian Thrun*.

### Free Resources

* [Made With ML](https://madewithml.com/) — production ML foundations.
* [AI Engineer Roadmap](https://roadmap.sh/ai-engineer) — community-curated path.
* [Awesome MLOps](https://github.com/visenger/awesome-mlops) — production ML resources.

---

## Books, Papers & Blogs

### Books

* [Deep Learning](https://www.deeplearningbook.org/) — *Goodfellow, Bengio, Courville* — the foundational textbook.
* [Reinforcement Learning: An Introduction (2nd ed)](http://incompleteideas.net/book/the-book-2nd.html) — *Sutton & Barto*.
* [Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) — *Aurélien Géron*.
* [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — *Chip Huyen* — production ML.
* [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — *Chip Huyen* — modern LLM app development.
* [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch) — *Sebastian Raschka*.
* [The Hundred-Page Machine Learning Book](http://themlbook.com/) — *Andriy Burkov*.
* [Probabilistic Machine Learning](https://probml.github.io/pml-book/) — *Kevin Murphy*.
* [Awesome AI Books](https://github.com/zachpinto/awesome-ai-books) — curated AI book list.

### Foundational Papers

* [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) — the Transformer paper.
* [BERT (2018)](https://arxiv.org/abs/1810.04805) — Bidirectional Transformers.
* [GPT-3 (2020)](https://arxiv.org/abs/2005.14165) — Language Models are Few-Shot Learners.
* [Chain-of-Thought Prompting (2022)](https://arxiv.org/abs/2201.11903).
* [InstructGPT / RLHF (2022)](https://arxiv.org/abs/2203.02155).
* [LLaMA (2023)](https://arxiv.org/abs/2302.13971).
* [Toolformer (2023)](https://arxiv.org/abs/2302.04761) — LLMs that use tools.
* [ReAct (2022)](https://arxiv.org/abs/2210.03629) — Reasoning + Acting.
* [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (2020)](https://arxiv.org/abs/2005.11401) — original RAG paper.

### Blogs & Newsletters

* [Lilian Weng's Blog (Lil'Log)](https://lilianweng.github.io/) — deep technical writing on AI.
* [Karpathy's Blog](https://karpathy.github.io/) — Andrej Karpathy's writing.
* [Sebastian Raschka's Magazine](https://magazine.sebastianraschka.com/) — practical LLM and ML.
* [Simon Willison's Blog](https://simonwillison.net/) — daily AI tools and tips.
* [The Pragmatic Engineer](https://www.pragmaticengineer.com/) — engineering, includes AI engineering.
* [Latent Space](https://www.latent.space/) — Swyx's AI engineering newsletter and podcast.
* [Hugging Face Blog](https://huggingface.co/blog) — open-source AI updates.
* [Anthropic Research](https://www.anthropic.com/research) — Claude/safety research.
* [OpenAI Research](https://openai.com/research/) — OpenAI papers and announcements.
* [Google Research Blog](https://research.google/blog/) — Google AI research.

### Reading Lists

* [Deep Learning Reading List](http://deeplearning.net/reading-list/) — curated academic survey papers.

---

## Companies & Research Labs

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
* [DeepSeek](https://www.deepseek.com/) — Chinese open-source frontier models.
* [Alibaba Qwen Team](https://qwenlm.github.io/) — Qwen series.

### AI Infrastructure & Platforms

* [Hugging Face](https://huggingface.co/) — model hub, datasets, training.
* [Replicate](https://replicate.com/) — run open-source models in the cloud.
* [Together AI](https://www.together.ai/) — fast open-model inference.
* [Groq](https://groq.com/) — extreme-speed inference.
* [Modal](https://modal.com/) — serverless GPU.
* [Anyscale](https://www.anyscale.com/) — Ray-based distributed AI.
* [Databricks](https://www.databricks.com/) — data + AI platform.

### Enterprise / Vertical AI

* [DataRobot](https://www.datarobot.com/) — enterprise ML platform.
* [Dataiku](http://www.dataiku.com/) — collaborative data science.
* [Scale AI](https://scale.com/) — data labeling and infrastructure.
* [Glean](https://www.glean.com/) — enterprise AI search.
* [Harvey AI](https://www.harvey.ai/) — legal AI.
* [Cresta](https://cresta.com/) — contact center AI.

### Robotics

* [Boston Dynamics](https://www.bostondynamics.com) — Atlas, Spot.
* [Figure AI](https://www.figure.ai/) — humanoid robots.
* [1X Technologies](https://www.1x.tech/) — humanoid robots.
* [Tesla Robotics (Optimus)](https://www.tesla.com/AI) — humanoid robot.
* [DJI](http://www.dji.com/) — drones.
* [iRobot](http://www.irobot.com/) — Roomba.
* [Fetch Robotics](http://www.fetchrobotics.com/) — warehouse robots.
* [ABB Robotics](http://new.abb.com/products/robotics) — industrial robotics.

---

## Personal AI Tools

### General Assistants

* [ChatGPT](https://chat.openai.com/) — OpenAI's general-purpose assistant.
* [Claude](https://claude.ai/) — Anthropic's assistant; long context, careful reasoning.
* [Google Gemini](https://gemini.google.com/) — Google's assistant.
* [Perplexity](https://www.perplexity.ai/) — AI-powered search engine.
* [You.com](https://you.com/) — AI search and chat.
* [Pi (Inflection)](https://pi.ai/) — empathetic personal AI.

### Voice Assistants (Smart Devices)

* [Amazon Alexa](https://www.amazon.com/alexa) — in-home assistant.
* [Apple Siri](http://www.apple.com/ios/siri/) — iOS / macOS assistant.
* [Google Assistant](https://assistant.google.com/) — Android / Home assistant.
* [Mycroft AI](https://mycroft.ai/) — open-source voice assistant.

### Productivity AI

* [Notion AI](https://www.notion.so/product/ai) — built into Notion docs.
* [Mem](https://get.mem.ai/) — AI-organized note-taking.
* [Granola](https://www.granola.ai/) — AI meeting notes.
* [Otter.ai](https://otter.ai/) — meeting transcription.
* [Reclaim.ai](https://reclaim.ai/) — calendar AI scheduling.
* [Motion](https://www.usemotion.com/) — AI task and calendar planner.

### AI Search

* [Perplexity](https://www.perplexity.ai/) — research-grade AI search.
* [Phind](https://phind.com/) — AI search for developers.
* [Exa](https://exa.ai/) — search engine for AI/LLMs.
* [Tavily](https://tavily.com/) — search API for agents.

---

## Specialized AI Tools

### Writing & Content

* [Jasper AI](https://www.jasper.ai/) — AI writer for marketing teams.
* [Writesonic](https://writesonic.com/) — SEO content generator.
* [Copy.ai](https://www.copy.ai/) — AI marketing copy.
* [Grammarly](https://www.grammarly.com/) — AI writing assistant.
* [Sudowrite](https://www.sudowrite.com/) — AI for fiction writers.
* [Taskade AI](https://www.taskade.com) — outlining and mind mapping.
* [RightBlogger](https://rightblogger.com/) — blogger-focused AI tools.

### Image Generation & Design

* [Midjourney](https://www.midjourney.com/) — high-quality image generation.
* [DALL·E (OpenAI)](https://openai.com/dall-e-3) — image generation.
* [Stable Diffusion (local)](https://stability.ai/) — open-source image gen.
* [Flux](https://blackforestlabs.ai/) — high-quality open image gen.
* [Leonardo.AI](https://leonardo.ai/) — Sydney-based image generation.
* [Ideogram](https://ideogram.ai/) — image generation with text rendering.
* [Krea](https://www.krea.ai/) — real-time AI canvas.
* [Canva Magic Studio](https://www.canva.com/magic-studio/) — AI design tools.
* [Figma AI](https://www.figma.com/ai/) — AI in Figma.

### Video & Audio

* [Runway](https://runwayml.com/) — AI video generation and editing.
* [Pika Labs](https://pika.art/) — text-to-video.
* [HeyGen](https://www.heygen.com/) — AI avatars and translation.
* [Synthesia](https://www.synthesia.io/) — AI video for enterprise.
* [Descript](https://www.descript.com/) — edit audio/video like a doc.
* [ElevenLabs](https://elevenlabs.io/) — voice cloning and synthesis.
* [Suno](https://www.suno.ai/) — music generation.
* [Udio](https://www.udio.com/) — music generation.

### Health / Medical

* [Ada Health](https://ada.com/) — symptom assessment.
* [doc.ai](http://doc.ai/) — health insights.
* [Abridge](https://www.abridge.com/) — clinical documentation AI.
* [Tess (X2AI)](https://x2.ai/) — therapy support.

### Finance

* [Morpher AI](https://www.morpher.com/ai) — financial market analysis.
* [Bloomberg GPT](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/) — finance-specific LLM.

### Travel & Local

* [Mindtrip](https://mindtrip.ai/) — AI travel planning.
* [Layla](https://www.layla.ai/) — travel AI assistant.

### Legal

* [Harvey AI](https://www.harvey.ai/) — legal AI.
* [Spellbook](https://www.spellbook.legal/) — contract review AI.

### Education (for Kids)

* [CodeKidz](https://codekidz.ai) — AI-powered programming learning for kids.

---

## Development Frameworks

### Deep Learning Frameworks

* [**PyTorch**](https://pytorch.org/) — by Meta; the de facto research framework.
* [**TensorFlow**](https://www.tensorflow.org/) — by Google.
* [**JAX**](https://github.com/google/jax) — by Google; functional, GPU/TPU.
* [**Keras**](https://keras.io/) — high-level neural networks API.
* [**MLX (Apple)**](https://github.com/ml-explore/mlx) — array framework for Apple Silicon.

### Python Libraries

* [**Hugging Face Transformers**](https://github.com/huggingface/transformers) — state-of-the-art NLP.
* [**LangChain**](https://github.com/langchain-ai/langchain) — LLM application framework.
* [**LlamaIndex**](https://github.com/run-llama/llama_index) — LLM data framework.
* [**Pydantic AI**](https://ai.pydantic.dev/) — type-safe agent framework.
* [**Instructor**](https://python.useinstructor.com/) — structured outputs from LLMs.
* [**LiteLLM**](https://github.com/BerriAI/litellm) — unified API for 100+ LLMs.
* [**Outlines**](https://github.com/outlines-dev/outlines) — guided LLM generation.
* [**DSPy**](https://github.com/stanfordnlp/dspy) — programming (not prompting) LLMs.
* [**scikit-learn**](https://scikit-learn.org/) — classic ML in Python.
* [**Lasagne**](https://github.com/Lasagne/Lasagne) — lightweight deep learning on Theano.

### TypeScript / JavaScript Libraries

* [**Vercel AI SDK**](https://sdk.vercel.ai/) — React/Next.js AI app SDK.
* [**LangChain.js**](https://github.com/langchain-ai/langchainjs) — LangChain for JS.
* [**TensorFlow.js**](https://www.tensorflow.org/js) — browser ML.
* [**Brain.js**](https://github.com/harthur-org/brain.js) — neural networks in JS.
* [**Synaptic**](https://github.com/cazala/synaptic) — JS neural network library.
* [**Natural**](https://github.com/NaturalNode/natural) — NLP in Node.js.
* [**Compromise (NLP)**](https://github.com/spencermountain/compromise) — NLP in browser.

### Bot Frameworks

* [**Anthropic SDK (Python / TypeScript)**](https://github.com/anthropics/anthropic-sdk-python) — official Claude SDK.
* [**OpenAI SDK**](https://github.com/openai/openai-python) — official OpenAI SDK.
* [**Wechaty**](https://github.com/wechaty/wechaty) — WeChat bot framework.
* [**python-telegram-bot**](https://github.com/python-telegram-bot/python-telegram-bot) — Telegram bot SDK.
* [**Discord.py**](https://github.com/Rapptz/discord.py) — Discord bot SDK.
* [**Slack Bolt**](https://github.com/slackapi/bolt-python) — Slack app framework.

### Datasets

* [**Hugging Face Datasets**](https://huggingface.co/datasets) — central dataset hub.
* [**Common Crawl**](https://commoncrawl.org/) — web-scale data.
* [**Kaggle Datasets**](https://www.kaggle.com/datasets) — competition and reference datasets.
* [**Papers With Code Datasets**](https://paperswithcode.com/datasets) — benchmark datasets.
* [**The Pile**](https://pile.eleuther.ai/) — 800GB dataset for LLMs.

---

## News, Newsletters & Podcasts

### Newsletters

* [**The Batch (deeplearning.ai)**](https://www.deeplearning.ai/the-batch/) — Andrew Ng's weekly AI newsletter.
* [**Latent Space**](https://www.latent.space/) — AI engineering practitioner newsletter.
* [**Import AI (Jack Clark)**](https://importai.substack.com/) — AI policy and research.
* [**The Sequence**](https://thesequence.substack.com/) — AI research summaries.
* [**Last Week in AI**](https://lastweekin.ai/) — weekly AI news.
* [**AI Weekly**](http://aiweekly.co/) — weekly AI digest.
* [**TLDR AI**](https://tldr.tech/ai) — daily AI news in 5 minutes.
* [**Ben's Bites**](https://www.bensbites.com/) — daily AI news for non-technical readers.
* [**One Useful Thing (Ethan Mollick)**](https://www.oneusefulthing.org/) — practical AI essays.

### Podcasts

* [**Latent Space Podcast**](https://www.latent.space/podcast) — AI engineering deep dives.
* [**The Lex Fridman Podcast**](https://lexfridman.com/podcast/) — long-form AI/tech conversations.
* [**Dwarkesh Podcast**](https://www.dwarkeshpatel.com/) — AI researchers and founders.
* [**No Priors**](https://www.no-priors.com/) — Sarah Guo & Elad Gil on AI.
* [**The TWIML AI Podcast**](https://twimlai.com/podcast/twimlai/) — This Week in ML & AI.
* [**Practical AI**](https://changelog.com/practicalai) — applied AI for engineers.
* [**Machine Learning Street Talk**](https://www.youtube.com/@MachineLearningStreetTalk) — academic ML discussions.

### News Sites

* [**Hacker News (HN AI tag)**](https://news.ycombinator.com/) — community AI discussion.
* [**ArXiv (cs.CL / cs.AI)**](https://arxiv.org/list/cs.AI/recent) — preprints.
* [**Papers with Code**](https://paperswithcode.com/) — papers + implementations.
* [**The Information AI**](https://www.theinformation.com/topics/artificial-intelligence) — paid; insider AI news.
* [**Sciencedaily AI**](https://www.sciencedaily.com/news/computers_math/artificial_intelligence/) — research news.

---

## Events & Conferences

* [**NeurIPS**](https://neurips.cc/) — premier ML research conference.
* [**ICML**](https://icml.cc/) — International Conference on Machine Learning.
* [**ICLR**](https://iclr.cc/) — Learning Representations.
* [**CVPR**](https://cvpr.thecvf.com/) — Computer Vision and Pattern Recognition.
* [**ACL**](https://www.aclweb.org/) — Computational Linguistics.
* [**The AI Engineer Summit / Conference**](https://www.ai.engineer/) — practitioner conference (SF/NYC).
* [**Anthropic Builder Summit**](https://www.anthropic.com/events) — Anthropic developer events.
* [**OpenAI DevDay**](https://devday.openai.com/) — OpenAI developer event.
* [**Hugging Face Events**](https://huggingface.co/events) — community events.
* [**AI Sydney / AI Melbourne meetups**](https://www.meetup.com/topics/artificial-intelligence/au/) — Australia community events.
* [**Build Club Sydney events**](https://www.buildclub.ai/) — AU AI builders.

---

## AI Jobs

* [Moai Jobs](https://www.moaijobs.com/) — top AI company jobs.
* [AI Jobster](https://aijobster.work/) — remote AI jobs.
* [Hugging Face Jobs](https://huggingface.co/jobs) — open-source AI roles.
* [LinkedIn AI Engineer search](https://www.linkedin.com/jobs/search/?keywords=AI%20Engineer) — global AI jobs.
* [WhoIsHiring (HN)](https://hnhiring.com/) — Hacker News hiring threads.
* [Cracked Engineers](https://www.crackedengineers.com/) — hand-picked tech jobs.
* [Built In](https://builtin.com/jobs) — US tech jobs by city.
* For region-specific jobs, see the [🌍 AI Scene by Country](#-ai-scene-by-country) section.

---

## AI Communities by City

### Australia 🇦🇺

* [Sydney — Build Club](https://www.buildclub.ai/) — AI builders community.
* [Sydney — Chinese AI Association](https://chineseai.org.au/) — 华人 AI 社区.
* [Melbourne AI Meetup](https://www.meetup.com/topics/artificial-intelligence/au/melbourne/) — regular events.
* See the dedicated [🇦🇺 Australia AI Scene](#-australia-ai-scene) section for more AU resources.

### North America

* [**San Francisco AI Meetup**](http://www.meetup.com/superintelligencemeetup/).
* [**New York**](http://newyork.ai/) — AI community.
* [**Seattle**](http://seattle.city.ai/) — AI community.

### Europe

* [**Amsterdam**](http://amsterdam.ai/).
* [**London**](http://www.london.ai/).
* **Berlin / Hamburg / Madrid / Milan / Oslo / Stockholm** — local AI communities.

### Asia

* [**Hong Kong**](http://hkg.ai/).
* **Beijing / Shanghai / Shenzhen / Singapore** — local AI communities.

---

## 🌍 AI Scene by Country

> Country-specific resources — universities, companies, bootcamps, hiring, visa info, and communities. Contributions from people on the ground welcome — please open a PR for your country.

### 🇺🇸 USA

**Universities & Research**
* [Stanford AI Lab (SAIL)](https://ai.stanford.edu/) — academic AI research.
* [MIT CSAIL](https://www.csail.mit.edu/) — Computer Science and AI Lab.
* [Carnegie Mellon LTI / MLD](https://www.cmu.edu/ai/) — Language Technologies / Machine Learning departments.
* [UC Berkeley BAIR](https://bair.berkeley.edu/) — Berkeley AI Research.
* [Princeton NLP / Vision](https://nlp.princeton.edu/) — academic groups.

**Bootcamps & Career Programs**
* [Springboard AI/ML Career Track](https://www.springboard.com/courses/ai-machine-learning-career-track/) — online AI bootcamp.
* [Bloomtech (formerly Lambda School)](https://bloomtech.com/) — online tech bootcamp.
* [Insight Data Science Fellows](https://insightfellows.com/) — fellowship for PhDs entering industry.
* [Recurse Center](https://www.recurse.com/) — self-directed programmer retreat (NYC).
* [Fellowship at Anthropic](https://www.anthropic.com/careers) — Anthropic's research fellowship.

**Hiring**
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
* [DeepSeek](https://www.deepseek.com/) — 深度求索, 开源前沿大模型.
* [通义千问 (Qwen, Alibaba)](https://qwenlm.github.io/) — 阿里通义.
* [豆包大模型 (ByteDance)](https://www.doubao.com/) — 字节豆包.
* [智谱 AI (ChatGLM)](https://www.zhipuai.cn/) — 清华系大模型.
* [MiniMax](https://www.minimaxi.com/) — abab 系列大模型.
* [Moonshot AI (Kimi)](https://kimi.moonshot.cn/) — 月之暗面 Kimi.
* [百度文心 (ERNIE)](https://yiyan.baidu.com/) — 文心一言.
* [腾讯混元](https://hunyuan.tencent.com/) — 混元大模型.
* [百川智能 (Baichuan)](https://www.baichuan-ai.com/) — 百川大模型.
* [01.AI (Yi)](https://www.lingyiwanwu.com/) — 零一万物 Yi 系列.

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
* [JR Academy](https://jiangren.com.au) — project-based AI engineering bootcamp; AU job-market focused.

**Hiring**
* [Atlassian Careers](https://www.atlassian.com/company/careers) — Sydney-based, hiring AI engineers.
* [Canva Engineering](https://www.canva.com/careers/) — Sydney-based, AI/ML roles.
* [Australian Government Digital Transformation Agency](https://www.dta.gov.au/) — public sector AI roles.
* [Build Club AI](https://www.buildclub.ai/) — Sydney AI builders community + jobs.
* [JobPin AI](https://www.jobpin.com.au/) — AI-powered job recommendations for Australia.
* [JR Academy Career Coaching](https://jiangren.com.au/career-coaching) — AU AI Engineer placement and coaching.

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
* [University of Malaya (UM) — AI & Robotics](https://www.um.edu.my/) — flagship public university.
* [Universiti Sains Malaysia (USM) — School of Computer Sciences](https://cs.usm.my/) — AI / ML programs.
* [Multimedia University (MMU)](https://www.mmu.edu.my/) — Cyberjaya tech university.
* [Universiti Teknologi Malaysia (UTM)](https://www.utm.my/) — engineering & AI research.
* [Asia Pacific University (APU)](https://www.apu.edu.my/) — data science & AI programs.

**Companies & Hiring (KL / Cyberjaya)**
* [Grab](https://grab.careers/) — Southeast Asia super-app; ML roles in KL.
* [iPay88](https://www.ipay88.com/) — fintech with AI applications.
* [Carsome](https://www.carsome.my/) — used-car platform with AI pricing.
* [Aerodyne](https://www.aerodyne.group/) — drone AI; HQ Cyberjaya.
* [WORQ](https://worq.space/) — coworking + tech community.
* [Hiredly](https://www.hiredly.com/) — Malaysia tech jobs platform.

**Communities**
* [AI Malaysia Meetup](https://www.meetup.com/topics/artificial-intelligence/my/) — local meetups.
* [Google Developer Groups KL](https://gdg.community.dev/gdg-cloud-kuala-lumpur/) — including AI/ML events.
* [PyData KL](https://www.meetup.com/PyData-KL/) — Python + data community.

### 🇸🇬 Singapore

**Universities & Research**
* [National University of Singapore (NUS) — AI](https://www.comp.nus.edu.sg/) — top SEA CS school.
* [Nanyang Technological University (NTU) — College of Computing](https://www.ntu.edu.sg/computing) — AI / ML labs.
* [Singapore Management University (SMU) — School of Computing](https://scis.smu.edu.sg/) — applied AI.
* [A*STAR Institute for Infocomm Research (I²R)](https://www.a-star.edu.sg/i2r) — government AI research.

**Government & Initiatives**
* [AI Singapore](https://aisingapore.org/) — national AI program (AI Apprenticeship, AI Trailblazer).
* [SGTech](https://www.sgtech.org.sg/) — Singapore tech industry association.

**Companies & Hiring**
* [Sea / Shopee / Garena](https://career.sea.com/) — Sea Group, large AI/ML team.
* [Grab AI Center](https://grab.careers/) — Singapore HQ.
* [GovTech Singapore](https://www.tech.gov.sg/careers/) — public-sector AI.
* [Tech in Asia Jobs](https://www.techinasia.com/jobs) — SEA tech jobs.

> Adding a country? Open a PR. Helpful info: top universities, AI companies, hiring resources, communities, and (if relevant) visa pathways.

---

## Contributing

Open a pull request or email **hello@jiangren.com.au**.

**Contribution guidelines**:
* Add resources that are still active and useful (we periodically prune dead links).
* Keep entries to one line: `[Name](url) — short description`.
* Place new entries in the most appropriate section.
* For Australia-specific resources, use the [Australia AI Scene](#-australia-ai-scene) section.
* No affiliate / referral links without disclosure.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for full guidelines.

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [JR Academy](https://jiangren.com.au) and [JR Talent](https://jrtalent.com.au) have waived all copyright and related or neighboring rights to this work.
