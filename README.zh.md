# Awesome 人工智能资源精选

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/hades217/awesome-ai?style=social)](https://github.com/hades217/awesome-ai/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/hades217/awesome-ai)](https://github.com/hades217/awesome-ai/commits/master)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

**🌐 Language**: [English](README.md) · [简体中文](README.zh.md)（当前）

> 一份社区维护的 AI 资源清单 —— 大模型、Agent 框架、AI 编程工具、课程、公司、求职、各国 AI 圈（美国/中国/澳洲/马来西亚/新加坡）。**特别为中文开发者整理**：包含国产大模型、中文 newsletter、B 站 UP 主、国内学习平台、AI 工程师中文学习路径。

自 2017 年起由 [Lightman Wang](https://github.com/hades217)（[LinkedIn](https://www.linkedin.com/in/lightman-wang/)）维护。

欢迎贡献 —— 提交 PR 或在 [Discussions](https://github.com/hades217/awesome-ai/discussions) 讨论。详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

**图例**：⭐ 编辑精选 · 🔥 2026 火热 · 🆕 今年新增 · 🇨🇳 中文圈重点 · 🇦🇺 澳洲

---

## ⭐ 编辑精选 2026（30 秒看完版）

> 没时间慢慢翻 —— 直接看这张表。每季度更新。

| 类别 | 推荐 |
|---|---|
| 🤖 **前沿大模型（闭源）** | [Claude Opus 4.7](https://www.anthropic.com/claude)（推理 + Agent 最强）· [GPT-5.5](https://openai.com/api/)（综合最稳）· [Gemini 3 Pro](https://ai.google.dev/)（多模态最强）· [Grok 4](https://x.ai/)（实时网络） |
| 🇨🇳 **国产前沿大模型** | [DeepSeek V3.2 / R1](https://www.deepseek.com/)（推理冠军）· [通义千问 Qwen3](https://qwenlm.github.io/)（多语言开源最强）· [Kimi K2](https://kimi.moonshot.cn/)（长上下文）· [豆包](https://www.doubao.com/) · [GLM-4.6](https://github.com/THUDM/GLM-4) |
| 💻 **AI 编程工具** | [Claude Code](https://www.anthropic.com/claude-code)（CLI）· [Cursor](https://www.cursor.com/)（IDE）· [Codex CLI](https://github.com/openai/codex)（OpenAI 开源）· [Aider](https://aider.chat/)（终端） |
| 🤝 **Agent 框架** | [Claude Agent SDK](https://docs.anthropic.com/en/api/agent-sdk) · [LangGraph](https://langchain-ai.github.io/langgraph/) · [Anthropic MCP](https://modelcontextprotocol.io/) · [Pydantic AI](https://ai.pydantic.dev/) |
| 📚 **RAG 起步** | [pgvector](https://github.com/pgvector/pgvector)（原型）· [Qdrant](https://qdrant.tech/)（自部署生产）· [Pinecone](https://www.pinecone.io/)（托管） |
| ⚡ **推理 / 部署** | [Ollama](https://ollama.com/)（本地）· [vLLM](https://github.com/vllm-project/vllm)（生产）· [SGLang](https://github.com/sgl-project/sglang)（结构化输出最快） |
| 🎓 **免费课** | [Karpathy 神经网络从零到一](https://karpathy.ai/zero-to-hero.html) · [HuggingFace Agents 课程](https://huggingface.co/learn/agents-course) |
| 🇨🇳 **中文学习平台** | [极客时间](https://time.geekbang.org/) · [慕课网](https://www.imooc.com/) · [Datawhale](https://www.datawhale.cn/)（开源社区） |
| 📰 **必关注资讯** | [量子位 QbitAI](https://www.qbitai.com/) · [机器之心 Synced](https://www.jiqizhixin.com/) · [PaperWeekly](https://www.paperweekly.site/) |
| 📺 **B 站 UP（中文 AI）** | [跟李沐学AI](https://space.bilibili.com/1567748478) · [王树森](https://space.bilibili.com/1369507485) · [沈向洋](https://space.bilibili.com/3494360438008678) · [林亦LYi](https://space.bilibili.com/19957558) |
| 📖 **必看书** | *[AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/)*（Chip Huyen）· *[从零构建大模型](https://www.manning.com/books/build-a-large-language-model-from-scratch)*（Sebastian Raschka）|
| 🧬 **必读论文** | [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) — Transformer 起点 |

→ 下面各章节有完整对照、备选、新兴工具。

---

## 目录

1. [🤖 大模型与 API](#-大模型与-api)
2. [💻 AI 编程工具](#-ai-编程工具)
3. [🤝 Agent 框架与 MCP](#-agent-框架与-mcp)
4. [📚 RAG 与向量数据库](#-rag-与向量数据库)
5. [⚡ 大模型推理与部署](#-大模型推理与部署)
6. [📊 LLM Ops 与可观测性](#-llm-ops-与可观测性)
7. [🎯 微调与训练](#-微调与训练)
8. [🛠️ 开发框架](#%EF%B8%8F-开发框架)
9. [🎓 课程与学习路径](#-课程与学习路径)
10. [📖 书籍、论文、博客](#-书籍论文博客)
11. [🏢 公司与研究机构](#-公司与研究机构)
12. [🧠 个人 AI 工具](#-个人-ai-工具)
13. [🎨 垂直领域 AI 工具](#-垂直领域-ai-工具)
14. [📰 资讯、Newsletter、播客](#-资讯newsletter播客)
15. [📺 B 站 UP 主与中文视频博主](#-b-站-up-主与中文视频博主)
16. [🎤 会议与活动](#-会议与活动)
17. [💼 AI 求职](#-ai-求职)
18. [🌍 各国 AI 圈](#-各国-ai-圈) — 美国 / 中国 / 澳洲 / 马来西亚 / 新加坡
19. [🤖 机器人与具身智能](#-机器人与具身智能)
20. [贡献](#贡献)

---

## 🤖 大模型与 API

### 前沿闭源模型

* [**Anthropic Claude**](https://www.anthropic.com/claude) ⭐ — Claude Opus 4.7 / Sonnet 4.6 / Haiku 4.5。推理 + Agent + 长上下文（1M tokens）综合最强；代码生成强。
* [**OpenAI GPT**](https://openai.com/api/) ⭐ — GPT-5.5 / GPT-5 / o3 推理模型。综合 API 最稳。
* [**Google Gemini**](https://ai.google.dev/) ⭐ — Gemini 3 Pro / Flash。多模态 + 2M 上下文 + 原生工具调用。
* [**xAI Grok**](https://x.ai/) — Grok 4，集成 X 实时数据。
* [**Mistral Large 3**](https://mistral.ai/) — 欧洲前沿模型，多语言强。

### 国产前沿大模型 🇨🇳 🔥

* [**DeepSeek**](https://www.deepseek.com/) ⭐ — 深度求索；DeepSeek V3.2 + R1 推理。前沿级开源。
* [**通义千问 Qwen3 (Alibaba)**](https://qwenlm.github.io/) ⭐ — 阿里通义；多语言开源最强（中文 + 英文）。
* [**Kimi K2 (Moonshot AI)**](https://kimi.moonshot.cn/) ⭐ — 月之暗面；长上下文冠军，开源 MoE。
* [**豆包大模型 (ByteDance)**](https://www.doubao.com/) — 字节跳动豆包系列。
* [**智谱 AI ChatGLM / GLM-4.6**](https://www.zhipuai.cn/) — 清华系，双语开源。
* [**MiniMax abab**](https://www.minimaxi.com/) — abab 系列，多模态。
* [**百度文心 ERNIE**](https://yiyan.baidu.com/) — 百度文心一言。
* [**腾讯混元**](https://hunyuan.tencent.com/) — 腾讯混元。
* [**百川智能 Baichuan**](https://www.baichuan-ai.com/) — 百川系列。
* [**01.AI Yi**](https://www.lingyiwanwu.com/) — 零一万物 Yi 系列。

### 海外开源大模型

* [**Meta Llama 4**](https://llama.meta.com/) ⭐ — 文本 + 视觉，开源基线。
* [**Mistral Open Models**](https://mistral.ai/technology/#models) — Mixtral, Mistral Small/Medium 3。
* [**Microsoft Phi-4**](https://azure.microsoft.com/en-us/products/phi) — 小而强。
* [**Hugging Face Hub**](https://huggingface.co/) ⭐ — 50 万+ 开源模型中心。

### 多模态与音视频 🆕

* [**Sora 2 (OpenAI)**](https://openai.com/sora/) — 文生视频。
* [**Veo 3 (Google)**](https://deepmind.google/technologies/veo/) — 视频生成 + 原生音频。
* [**Hailuo 02 (MiniMax)**](https://hailuoai.video/) 🇨🇳 — 国产视频生成。
* [**Kling AI**](https://klingai.com/) 🇨🇳 — 快手可灵视频生成。
* [**Stable Diffusion 3.5**](https://stability.ai/) — 开源图像生成。
* [**Flux 1.1 Pro / Kontext**](https://blackforestlabs.ai/) ⭐ — 开源图像生成 + 编辑。
* [**ElevenLabs**](https://elevenlabs.io/) ⭐ — 语音克隆 + 多语言 TTS。
* [**Whisper Large v3**](https://openai.com/research/whisper) — 开源语音识别。
* [**Suno v4 / Udio**](https://www.suno.ai/) — 音乐生成。

---

## 💻 AI 编程工具

> 2025-2026 最被颠覆的开发者工具品类。

* [**Claude Code**](https://www.anthropic.com/claude-code) ⭐ 🔥 — Anthropic 官方 CLI 编程工具，2026 最常用 CLI Agent。
* [**Cursor**](https://www.cursor.com/) ⭐ 🔥 — AI 优先 IDE（VS Code fork）。
* [**Codex CLI (OpenAI)**](https://github.com/openai/codex) 🆕 (80k ⭐) — OpenAI 开源 CLI Agent。
* [**GitHub Copilot**](https://github.com/features/copilot) — 老牌 AI 结对编程，现支持 Agent。
* [**Windsurf**](https://codeium.com/windsurf) — Codeium AI 编辑器（被 Cognition 收购）。
* [**Aider**](https://aider.chat/) (44k ⭐) — 终端开源 AI 结对。
* [**Continue**](https://continue.dev/) (33k ⭐) — VS Code / JetBrains 开源 AI 助手。
* [**Cline**](https://github.com/cline/cline) (61k ⭐) — VS Code 自主编程 Agent。
* [**Trae (字节)**](https://www.trae.ai/) 🇨🇳 🆕 — 字节出品 AI IDE。
* [**通义灵码 (Alibaba)**](https://lingma.aliyun.com/) 🇨🇳 — 阿里通义灵码 IDE 插件。
* [**腾讯云 AI 助手**](https://cloud.tencent.com/product/coding-copilot) 🇨🇳 — 腾讯云 CodeBuddy。
* [**Bolt.new**](https://bolt.new/) — 浏览器全栈 Web 应用生成。
* [**v0 (Vercel)**](https://v0.dev/) — AI UI 生成（输出 React/Next.js）。
* [**Lovable**](https://lovable.dev/) — AI 应用搭建。
* [**Devin (Cognition)**](https://devin.ai/) — 自主 SWE Agent（付费托管）。
* [Tura](https://github.com/Tura-AI/tura) — 本地开源编程 Agent，提供 CLI、TUI、GUI、验证流程与公开基准测试。

---

## 🤝 Agent 框架与 MCP

### Agent 框架

* [**Claude Agent SDK**](https://docs.anthropic.com/en/api/agent-sdk) ⭐ 🆕 — Anthropic 官方 Agent SDK，含 Skills + 记忆 + 沙箱。
* [**LangGraph**](https://langchain-ai.github.io/langgraph/) ⭐ (31k ⭐) — 图编排的 Agent 框架，生产可用。
* [**Pydantic AI**](https://ai.pydantic.dev/) ⭐ — 类型安全 Agent 框架。
* [**CrewAI**](https://www.crewai.com/) (51k ⭐) — 角色化多 Agent 框架。
* [**AutoGen (Microsoft)**](https://github.com/microsoft/autogen) (58k ⭐) — 多 Agent 对话框架。
* [**OpenAI Swarm**](https://github.com/openai/swarm) (21k ⭐) — 轻量多 Agent。
* [**LlamaIndex Agents**](https://docs.llamaindex.ai/en/stable/module_guides/deploying/agents/) — Agent 运行时。
* [**Vercel AI SDK**](https://sdk.vercel.ai/) ⭐ — React/Next.js Agent SDK。
* [**smolagents (HuggingFace)**](https://github.com/huggingface/smolagents) (27k ⭐) — 极简代码执行型 Agent 库。
* [**Strands Agents (AWS)**](https://github.com/strands-agents/sdk-python) 🆕 — AWS 开源 Agent SDK。
* [**Letta（原 MemGPT）**](https://github.com/letta-ai/letta) (22k ⭐) — 持久记忆 Agent。

### Model Context Protocol (MCP) 🔥

* [**MCP 协议规范**](https://modelcontextprotocol.io/) ⭐ — Anthropic 开放协议，2024 起业界标准。
* [**Anthropic MCP Servers**](https://github.com/modelcontextprotocol/servers) (85k ⭐) — 官方 MCP 服务器（filesystem / fetch / GitHub / Postgres / Brave）。
* [**MCP Python SDK**](https://github.com/modelcontextprotocol/python-sdk) (23k ⭐) — Python 写 MCP 服务器。
* [**MCP TypeScript SDK**](https://github.com/modelcontextprotocol/typescript-sdk) (12k ⭐) — TS 写 MCP 服务器。
* [**Awesome MCP Servers**](https://github.com/punkpeye/awesome-mcp-servers) ⭐ (86k ⭐) — 社区 MCP 服务器列表。
* [**FastMCP**](https://github.com/jlowin/fastmcp) (25k ⭐) — Pythonic MCP 服务器框架。

### 浏览器与 Computer Use 🆕

* [**Anthropic Computer Use**](https://www.anthropic.com/news/3-5-models-and-computer-use) ⭐ — Claude 控制电脑。
* [**OpenAI Atlas**](https://openai.com/atlas) 🆕 — OpenAI Agent 浏览器。
* [**Browser Use**](https://github.com/browser-use/browser-use) (92k ⭐) — Agent 浏览器自动化。
* [**Skyvern**](https://github.com/Skyvern-AI/skyvern) (22k ⭐) — 视觉 LLM 浏览器自动化。
* [**Stagehand (Browserbase)**](https://github.com/browserbase/stagehand) (22k ⭐) — Playwright + AI 可靠 Agent。

---

## 📚 RAG 与向量数据库

### RAG 框架

* [**LangChain**](https://www.langchain.com/) ⭐ (136k ⭐) — 最流行 LLM 应用框架。
* [**LlamaIndex**](https://www.llamaindex.ai/) ⭐ (49k ⭐) — RAG 数据框架。
* [**RAGFlow**](https://github.com/infiniflow/ragflow) 🔥 (80k ⭐) — 开源 RAG 引擎，深度文档理解。
* [**Haystack (deepset)**](https://haystack.deepset.ai/) (25k ⭐) — 开源 LLM 框架。
* [**Verba (Weaviate)**](https://github.com/weaviate/Verba) — RAG 聊天 UI。
* [**Pathway**](https://github.com/pathwaycom/pathway) — 实时 RAG 管道。

### 向量数据库

* [**pgvector**](https://github.com/pgvector/pgvector) ⭐ (21k ⭐) — Postgres 扩展，原型默认选择。
* [**Qdrant**](https://qdrant.tech/) ⭐ (31k ⭐) — Rust 写的开源向量搜索引擎。
* [**Pinecone**](https://www.pinecone.io/) ⭐ — 托管向量数据库 + Serverless。
* [**Weaviate**](https://weaviate.io/) (16k ⭐) — 开源向量数据库，支持混合搜索。
* [**Chroma**](https://www.trychroma.com/) (28k ⭐) — 嵌入式向量数据库，原型 DX 一流。
* [**Milvus**](https://milvus.io/) 🇨🇳 (44k ⭐) — Zilliz 出品，国产开源向量数据库。

### Embedding 模型

* [**OpenAI text-embedding-3 / 4**](https://platform.openai.com/docs/guides/embeddings)
* [**Cohere Embed v3 / v4**](https://cohere.com/embed) — 多语言 embedding。
* [**BGE (BAAI 智源)**](https://huggingface.co/BAAI) 🇨🇳 — 国产开源，榜单常客。
* [**Voyage AI**](https://www.voyageai.com/) ⭐ — 高质量通用 embedding（被 MongoDB 收购）。
* [**Sentence Transformers**](https://www.sbert.net/) — 开源 embedding 库。

---

## ⚡ 大模型推理与部署

* [**Ollama**](https://ollama.com/) ⭐ (171k ⭐) — 一键本地跑大模型。
* [**LM Studio**](https://lmstudio.ai/) — 本地大模型 GUI。
* [**llama.cpp**](https://github.com/ggerganov/llama.cpp) ⭐ (108k ⭐) — C++ 高效推理。
* [**vLLM**](https://github.com/vllm-project/vllm) ⭐ (79k ⭐) — 高吞吐生产部署。
* [**SGLang**](https://github.com/sgl-project/sglang) 🆕 (27k ⭐) — 结构化输出推理引擎，速度领先。
* [**Together AI**](https://www.together.ai/) ⭐ — 开源模型托管 API。
* [**Groq**](https://groq.com/) ⭐ — LPU 极速推理。
* [**Cerebras Inference**](https://inference.cerebras.ai/) 🆕 — Wafer-scale 极速推理。
* [**Modal**](https://modal.com/) — 无服务器 GPU。
* [**腾讯云 TI-ONE**](https://cloud.tencent.com/product/tione) 🇨🇳 — 腾讯云 AI 训练推理平台。
* [**阿里云 PAI**](https://www.aliyun.com/product/bigdata/learn) 🇨🇳 — 阿里云 AI 平台。
* [**百度智能云千帆**](https://qianfan.cloud.baidu.com/) 🇨🇳 — 百度大模型平台。

---

## 📊 LLM Ops 与可观测性

* [**LangSmith**](https://www.langchain.com/langsmith) ⭐ — LangChain 默认观测平台。
* [**Langfuse**](https://langfuse.com/) (27k ⭐) — 开源 LLM 工程平台，eval + traces。
* [**Helicone**](https://www.helicone.ai/) (6k ⭐) — 开源 LLM 观测。
* [**Phoenix (Arize)**](https://phoenix.arize.com/) — Notebook 内 LLM 观测。
* [**Braintrust**](https://www.braintrust.dev/) ⭐ — eval 优先观测平台。
* [**Promptfoo**](https://www.promptfoo.dev/) (21k ⭐) — 开源 LLM eval 框架。
* [**OpenLIT**](https://openlit.io/) — OpenTelemetry 原生 LLM 观测。

---

## 🎯 微调与训练

* [**Unsloth**](https://unsloth.ai/) ⭐ (64k ⭐) — 2 倍快微调，省内存。
* [**Axolotl**](https://github.com/axolotl-ai-cloud/axolotl) (12k ⭐) — LoRA / QLoRA / 全参微调。
* [**LLaMA Factory**](https://github.com/hiyouga/LLaMA-Factory) 🇨🇳 (71k ⭐) — 国产开源统一微调框架。
* [**HuggingFace TRL**](https://huggingface.co/docs/trl/index) (18k ⭐) — RLHF / DPO / PPO。
* [**ColossalAI**](https://github.com/hpcaitech/ColossalAI) 🇨🇳 (41k ⭐) — 国产大规模训练框架。
* [**veRL (字节)**](https://github.com/volcengine/verl) 🇨🇳 🆕 — 字节出品 RL 训练。

---

## 🛠️ 开发框架

### 深度学习框架

* [**PyTorch**](https://pytorch.org/) ⭐ — Meta 出品，事实上的研究框架。
* [**TensorFlow**](https://www.tensorflow.org/) — Google 出品。
* [**JAX**](https://github.com/google/jax) (36k ⭐) — Google 函数式 GPU/TPU 框架。
* [**MLX (Apple)**](https://github.com/ml-explore/mlx) (26k ⭐) — Apple Silicon 优化。
* [**MindSpore (华为)**](https://www.mindspore.cn/) 🇨🇳 — 华为开源深度学习框架。
* [**PaddlePaddle (百度飞桨)**](https://www.paddlepaddle.org.cn/) 🇨🇳 — 百度开源框架。

### Python LLM 库

* [**HuggingFace Transformers**](https://github.com/huggingface/transformers) ⭐ (160k ⭐) — 业界标准。
* [**LangChain**](https://github.com/langchain-ai/langchain) (136k ⭐)
* [**LlamaIndex**](https://github.com/run-llama/llama_index) (49k ⭐)
* [**LiteLLM**](https://github.com/BerriAI/litellm) ⭐ (46k ⭐) — 100+ LLM 统一 API。
* [**DSPy**](https://github.com/stanfordnlp/dspy) ⭐ (34k ⭐) — 编程（不是写 prompt） LLM。
* [**Instructor**](https://python.useinstructor.com/) ⭐ — LLM 结构化输出。
* [**Outlines**](https://github.com/outlines-dev/outlines) (14k ⭐) — 引导式生成。

### TypeScript / JavaScript

* [**Vercel AI SDK**](https://sdk.vercel.ai/) ⭐
* [**LangChain.js**](https://github.com/langchain-ai/langchainjs)
* [**Mastra**](https://mastra.ai/) 🆕 (24k ⭐) — TS 写 Agent / eval / workflow。

---

## 🎓 课程与学习路径

### 基础 ML / AI（经典）

* [机器学习](https://www.coursera.org/learn/machine-learning) — *Stanford / 吴恩达* — 经典中的经典。
* [深度学习专项课](https://www.coursera.org/specializations/deep-learning) — *deeplearning.ai* — 神经网络 / CNN / RNN / Transformer。
* [CS231n 计算机视觉](http://cs231n.stanford.edu/) — *Stanford* — CV 黄金标准。
* [CS224N 自然语言处理](http://web.stanford.edu/class/cs224n/) — *Stanford* — NLP 基础。
* [fast.ai 实战深度学习](https://course.fast.ai/) — 自上而下实操派。
* [跟李沐学AI（B 站）](https://space.bilibili.com/1567748478) ⭐ 🇨🇳 — 中文最佳深度学习入门。

### 现代大模型 / 生成式 AI 🔥

* [**Karpathy 神经网络从零到一**](https://karpathy.ai/zero-to-hero.html) ⭐ — 从零搭神经网络、GPT、tokenizer。最佳免费 LLM 课。
* [**HuggingFace Agents 课程**](https://huggingface.co/learn/agents-course) ⭐ — 端到端搭 Agent。
* [**HuggingFace NLP 课程**](https://huggingface.co/learn/nlp-course) — Transformer 入门。
* [**Anthropic 官方课**](https://github.com/anthropics/courses) — prompt / tool use / RAG / agents。
* [**LangChain Academy**](https://academy.langchain.com/) — LangChain / LangGraph 课。
* [**CS336: 从零搭语言模型**](https://stanford-cs336.github.io/) — *Stanford*。
* [**3Blue1Brown 神经网络**](https://www.3blue1brown.com/topics/neural-networks) — 视觉直觉。

### 中文学习平台 🇨🇳

* [**极客时间**](https://time.geekbang.org/) ⭐ — 中文程序员付费精品课。
* [**慕课网 / 网易云课堂**](https://www.imooc.com/) — 综合在线课。
* [**Datawhale**](https://www.datawhale.cn/) ⭐ — 开源 AI 学习社区，免费教程多。
* [**蓝桥云课**](https://www.lanqiao.cn/) — 实战导向编程课。
* [**腾讯云开发者实验室**](https://cloud.tencent.com/developer/labs) — 云原生 / AI 实战。
* [**阿里云开发者学堂**](https://edu.aliyun.com/) — 云 / AI 综合课。
* [**B 站 课程聚合**](https://www.bilibili.com/) — 大量免费高质量 AI 课。

### 求职导向训练营

* [Springboard AI/ML 培训](https://www.springboard.com/courses/ai-machine-learning-career-track/) — 美国线上培训营 + 导师。
* [Maven AI Engineering 系列](https://maven.com/topics/artificial-intelligence) — 业内专家小班课。
* [Bloomtech](https://bloomtech.com/) — 美国线上培训营。
* [Insight Data Science Fellows](https://insightfellows.com/) — 博士转工业界 fellowship。
* [JR Academy AI Engineer Bootcamp](https://jiangren.com.au/curriculum/ai-engineer-bootcamp) — 项目制 6 个月训练营，覆盖 MCP / RAG / Agent / 部署。
* [JR Academy Vibe Coding](https://jiangren.com.au/learn/vibe-coding) — 现代 AI 增强开发（Cursor / Claude Code）。
* [Recurse Center](https://www.recurse.com/) — 自驱学习营（NYC）。

### AI 工程师专项学习路径（免费 hub）

> 给想自学 AI Engineer 的人。

* [AI Engineer Roadmap (roadmap.sh)](https://roadmap.sh/ai-engineer) — 社区 step-by-step 路线图。
* [AI Engineer 必读论文清单 (Latent Space)](https://www.latent.space/p/2025-papers) — Swyx 年度论文。
* [Generative AI Handbook (Will Brown)](https://genai-handbook.github.io/) — 实战手册。
* [Hamel Husain 博客](https://hamel.dev/) — LLM eval / ops 实战。
* [DeepLearning.AI AI Engineering 专项](https://www.deeplearning.ai/courses/) — 吴恩达系结构化课程。
* [JR Academy AI Engineer Hub](https://jiangren.com.au/learn/ai-engineer) — 免费章节式学习路径，含 MCP / RAG / Agent / 部署 + 实战 lab。
* [JR Academy Prompt Master Hub](https://jiangren.com.au/learn/prompt-master) — 免费 Prompt 工程章节式 hub。

---

## 📖 书籍、论文、博客

### 现代书（2024-2026） 🔥

* [**AI Engineering**](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — *Chip Huyen* ⭐ — 生产级 LLM 应用权威。
* [**从零构建大模型 / Build a LLM From Scratch**](https://www.manning.com/books/build-a-large-language-model-from-scratch) — *Sebastian Raschka* — 教学型 GPT 实现。
* [**Hands-On Large Language Models**](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/) — *Jay Alammar*。
* [**Designing Machine Learning Systems**](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — *Chip Huyen*。

### 经典书

* [深度学习花书 / Deep Learning](https://www.deeplearningbook.org/) — *Goodfellow, Bengio, Courville*（中文译本：人民邮电）。
* [强化学习导论 / RL: An Introduction](http://incompleteideas.net/book/the-book-2nd.html) — *Sutton & Barto*。
* [机器学习实战 / Hands-On ML](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) — *Aurélien Géron*。
* [概率机器学习 / Probabilistic ML](https://probml.github.io/pml-book/) — *Kevin Murphy*。

### 必读论文（含为什么重要）

> 按时间顺序读，理解整个 AI 圈。

* [**Attention Is All You Need (2017)**](https://arxiv.org/abs/1706.03762) ⭐ — Transformer 起源，所有现代大模型基础。
* [**BERT (2018)**](https://arxiv.org/abs/1810.04805) — 双向 Transformer，2018-2022 NLP 主流。
* [**GPT-3 (2020)**](https://arxiv.org/abs/2005.14165) — 「大模型 + 少样本」证明 scaling 路线可行。
* [**Scaling Laws (2020)**](https://arxiv.org/abs/2001.08361) — loss vs 计算/参数/数据 公式化。
* [**RAG (2020)**](https://arxiv.org/abs/2005.11401) — 检索增强生成原始论文。
* [**Chain-of-Thought (2022)**](https://arxiv.org/abs/2201.11903) — "let's think step by step" 解锁推理。
* [**InstructGPT / RLHF (2022)**](https://arxiv.org/abs/2203.02155) — RLHF 让模型按指令行动；ChatGPT 基础。
* [**Chinchilla (2022)**](https://arxiv.org/abs/2203.15556) — 修正 scaling laws：小模型多数据更优。
* [**LLaMA (2023)**](https://arxiv.org/abs/2302.13971) — Meta 开源大模型，催生整个开源生态。
* [**ReAct (2022)**](https://arxiv.org/abs/2210.03629) — 推理+行动 prompt 模板，现代 Agent 基础。
* [**LoRA (2021)**](https://arxiv.org/abs/2106.09685) — 低秩适配，所有人微调的方式。
* [**DPO (2023)**](https://arxiv.org/abs/2305.18290) — 比 RLHF 简单的偏好优化。
* [**Mixtral / MoE (2024)**](https://arxiv.org/abs/2401.04088) — 实用 MoE，开启高效大模型时代。
* [**DeepSeek-R1 (2025)**](https://arxiv.org/abs/2501.12948) 🇨🇳 — 纯强化学习推理训练突破。

### 高信号博客

* [**Lilian Weng 博客 (Lil'Log)**](https://lilianweng.github.io/) ⭐ — 深技术写作，每篇都是综述级。
* [**Karpathy 博客**](https://karpathy.github.io/) ⭐ — Andrej Karpathy 写作，清晰度天花板。
* [**Sebastian Raschka 杂志**](https://magazine.sebastianraschka.com/) — 实战 LLM / ML。
* [**Simon Willison 博客**](https://simonwillison.net/) — AI 工具日更。
* [**Anthropic Research**](https://www.anthropic.com/research) — Claude / 安全研究。
* [**OpenAI Research**](https://openai.com/research/)
* [**HuggingFace 博客**](https://huggingface.co/blog) — 开源 AI 更新。
* [**One Useful Thing (Ethan Mollick)**](https://www.oneusefulthing.org/) — 给非工程师的 AI 实用文。

### 中文必读博客 🇨🇳

* [**苏剑林 (kexue.fm)**](https://kexue.fm/) ⭐ — 中文最深度数学+模型博客。
* [**张俊林（知乎）**](https://www.zhihu.com/people/zhang-jun-lin-76) — 大模型综述。
* [**周明（清华系）**](https://www.zhihu.com/people/zhouming-67-77) — 中文 NLP 思考。
* [**JackKuo 知乎**](https://www.zhihu.com/people/JackKuo) — Agent 工程实战。
* [**回旋托马斯x（知乎）**](https://www.zhihu.com/people/jiang-jiang-43-95) — LLM 工程笔记。

---

## 🏢 公司与研究机构

### 海外大模型实验室

* [Anthropic](https://www.anthropic.com/) — Claude；AI 安全研究。
* [OpenAI](https://openai.com/) — GPT / ChatGPT / Sora / Codex。
* [Google DeepMind](https://deepmind.google/) — Gemini / AlphaFold。
* [Meta AI (FAIR)](https://ai.meta.com/) — Llama / PyTorch。
* [Mistral AI](https://mistral.ai/) — 法国开源 / 商用。
* [xAI](https://x.ai/) — Grok。
* [Cohere](https://cohere.com/) — 企业 LLM。
* [Stability AI](https://stability.ai/) — Stable Diffusion。
* [Black Forest Labs](https://blackforestlabs.ai/) — Flux 图像。

### 国产大模型公司 🇨🇳

* [DeepSeek 深度求索](https://www.deepseek.com/)
* [阿里通义 Qwen](https://qwenlm.github.io/)
* [Moonshot AI 月之暗面 (Kimi)](https://www.moonshot.cn/)
* [Zhipu AI 智谱](https://www.zhipuai.cn/) — GLM。
* [百度文心](https://yiyan.baidu.com/)
* [腾讯混元](https://hunyuan.tencent.com/)
* [字节豆包](https://www.doubao.com/)
* [MiniMax](https://www.minimaxi.com/)
* [百川智能](https://www.baichuan-ai.com/)
* [01.AI 零一万物](https://www.lingyiwanwu.com/)
* [Stepfun 阶跃星辰](https://www.stepfun.com/)

### 国内研究院 🇨🇳

* [北京智源 BAAI](https://www.baai.ac.cn/) ⭐ — 智源人工智能研究院。
* [上海人工智能实验室](https://www.shlab.org.cn/) — Shanghai AI Lab。
* [清华 THUNLP](https://nlp.csai.tsinghua.edu.cn/) — 清华 NLP 实验室。
* [北大王选所](https://www.icst.pku.edu.cn/) — 北大 AI。
* [上交 AI 研究院](https://ai.sjtu.edu.cn/)
* [港中文 MMLab](http://mmlab.ie.cuhk.edu.hk/)
* [鹏城实验室](https://www.pcl.ac.cn/) — 深圳大模型研究。

### AI 基础设施 / 平台

* [HuggingFace](https://huggingface.co/) — 模型 hub / 数据集 / 训练。
* [Replicate](https://replicate.com/) — 跑开源模型云服务。
* [Together AI](https://www.together.ai/) — 开源模型推理。
* [Groq](https://groq.com/) — LPU 极速推理。
* [Modal](https://modal.com/) — 无服务器 GPU。
* [Anyscale](https://www.anyscale.com/) — Ray 分布式 AI。
* [Databricks](https://www.databricks.com/) — 数据 + AI 平台。

### 企业 / 垂直 AI

* [Glean](https://www.glean.com/) — 企业 AI 搜索。
* [Harvey AI](https://www.harvey.ai/) — 法律 AI。
* [Cresta](https://cresta.com/) — 联系中心 AI。
* [Sierra](https://sierra.ai/) — 客服 Agent。
* [Cursor (Anysphere)](https://www.cursor.com/)
* [Cognition](https://www.cognition.ai/) — Devin SWE Agent。

### AI 咨询与落地

* [Slalom AI Practice](https://www.slalom.com/services/data-and-ai)
* [BCG X](https://www.bcg.com/x)
* [Accenture AI](https://www.accenture.com/us-en/services/applied-intelligence-index)
* [Thoughtworks AI](https://www.thoughtworks.com/en-us/what-we-do/ai)
* [Modulai](https://modulai.io/) — 欧洲精品 AI 咨询。
* [MetaTree Lab](https://metatreelab.ai/) — AI 咨询；LLM 战略、RAG / Agent 落地、定制训练。

---

## 🧠 个人 AI 工具

### 通用助手

* [**Claude**](https://claude.ai/) ⭐ — Anthropic 助手；长上下文、推理细致。
* [**ChatGPT**](https://chat.openai.com/) ⭐ — OpenAI 通用助手。
* [**Gemini**](https://gemini.google.com/) — Google 助手。
* [**豆包**](https://www.doubao.com/) 🇨🇳 — 字节豆包。
* [**Kimi**](https://kimi.moonshot.cn/) 🇨🇳 — 月之暗面 Kimi。
* [**通义**](https://tongyi.aliyun.com/) 🇨🇳 — 阿里通义。
* [**文心一言**](https://yiyan.baidu.com/) 🇨🇳 — 百度。
* [**腾讯元宝**](https://yuanbao.tencent.com/) 🇨🇳 — 腾讯元宝。
* [**Perplexity**](https://www.perplexity.ai/) ⭐ — AI 搜索。
* [**秘塔搜索**](https://metaso.cn/) 🇨🇳 — 国内对标 Perplexity。

### 生产力 AI

* [Notion AI](https://www.notion.so/product/ai)
* [Granola](https://www.granola.ai/) ⭐ — AI 会议纪要。
* [Otter.ai](https://otter.ai/) — 会议转录老牌。
* [飞书智能助手](https://www.feishu.cn/product/ai) 🇨🇳 — 飞书 Office AI。
* [钉钉 AI 助理](https://www.dingtalk.com/) 🇨🇳 — 钉钉 Office AI。
* [Reclaim.ai](https://reclaim.ai/) — 日历 AI 安排。
* [Motion](https://www.usemotion.com/) — AI 任务 + 日历。

### 虚拟办公 / 远程协作

* [Gather](https://www.gather.town/) — 像素风虚拟办公。
* [Teamflow](https://www.teamflow.com/) — 远程团队虚拟总部。
* [MetaTown](https://metatown.ai/) — 虚拟办公 + AI Agent 会议环境。
* [Around](https://www.around.co/) — AI 增强视频会议。

### AI 搜索

* [Perplexity](https://www.perplexity.ai/) ⭐ — 研究级 AI 搜索。
* [秘塔搜索](https://metaso.cn/) 🇨🇳 — 国内 AI 搜索代表。
* [Phind](https://phind.com/) — 开发者 AI 搜索。
* [Exa](https://exa.ai/) — 给 AI 用的搜索引擎。

---

## 🎨 垂直领域 AI 工具

### 图像生成与设计

* [**Midjourney**](https://www.midjourney.com/) ⭐
* [**DALL·E**](https://openai.com/dall-e-3)
* [**Flux 1.1 Pro / Kontext**](https://blackforestlabs.ai/) ⭐
* [**Stable Diffusion**](https://stability.ai/)
* [**Recraft V3**](https://www.recraft.ai/) 🆕 — 设计级图像生成。
* [**即梦 (Doubao Image)**](https://jimeng.jianying.com/) 🇨🇳 — 字节即梦。
* [**可灵 (Kling)**](https://klingai.com/) 🇨🇳 — 快手图像 + 视频。
* [**Canva Magic Studio**](https://www.canva.com/magic-studio/)
* [**Figma AI / Make**](https://www.figma.com/ai/)

### 视频与音频

* [**Sora 2**](https://openai.com/sora/) ⭐
* [**Veo 3**](https://deepmind.google/technologies/veo/) ⭐
* [**Runway Gen-4**](https://runwayml.com/)
* [**Hailuo 02 (MiniMax)**](https://hailuoai.video/) 🇨🇳
* [**Kling AI 可灵**](https://klingai.com/) 🇨🇳
* [**Pika 2.0**](https://pika.art/)
* [**HeyGen**](https://www.heygen.com/) — AI 数字人 + 翻译。
* [**Synthesia**](https://www.synthesia.io/) — 企业级 AI 视频。
* [**ElevenLabs**](https://elevenlabs.io/) ⭐ — 语音克隆。
* [**Suno**](https://www.suno.ai/) — AI 音乐。

### 写作

* [Jasper AI](https://www.jasper.ai/) — 营销文案 AI。
* [Grammarly](https://www.grammarly.com/) — 英文写作助手。
* [Sudowrite](https://www.sudowrite.com/) — 小说写作 AI。
* [秘塔写作猫](https://xiezuocat.com/) 🇨🇳 — 中文写作助手。
* [万彩 AI](https://ai.animiz.cn/) 🇨🇳 — AI 内容创作。

### 教育

* [Khan Academy Khanmigo](https://www.khanmigo.ai/) ⭐ — AI 家教（英文）。
* [CodeKidz](https://codekidz.ai) — 儿童 AI 编程学习。
* [作业帮 AI](https://www.zybang.com/) 🇨🇳 — 国内 K12 AI 辅助。

### 简历与求职

* [Teal](https://www.tealhq.com/) — AI 简历 + 求职追踪。
* [Rezi](https://www.rezi.ai/) — ATS 优化 AI 简历。
* [ResumeWorded](https://resumeworded.com/) — AI 简历 + LinkedIn 反馈。
* [Kickresume](https://www.kickresume.com/)
* [JobPin AI](https://jobpin.ai/) — AI 简历修改、ATS 优化、岗位匹配。
* [Final Round AI](https://www.finalroundai.com/) — AI 面试副驾。

### 金融

* [Bloomberg GPT](https://www.bloomberg.com/company/press/bloomberggpt-50-billion-parameter-llm-tuned-finance/)
* [Hebbia](https://www.hebbia.com/) — 金融分析 AI。

### 法律

* [Harvey AI](https://www.harvey.ai/)
* [Spellbook](https://www.spellbook.legal/) — 合同审核 AI。
* [幂律智能 Mega AI](https://www.megalaw.cn/) 🇨🇳 — 国内法律 AI。

---

## 📰 资讯、Newsletter、播客

### 中文 Newsletter / 资讯 🇨🇳 ⭐

* [**量子位 QbitAI**](https://www.qbitai.com/) ⭐ — 中文 AI 资讯第一档。
* [**机器之心 Synced**](https://www.jiqizhixin.com/) ⭐ — AI 研究资讯。
* [**PaperWeekly**](https://www.paperweekly.site/) — 论文阅读社区。
* [**Datawhale 公众号**](https://www.datawhale.cn/) — 开源 AI 学习社区。
* [**新智元**](https://www.aiera.com.cn/) — AI 综合媒体。
* [**赛博禅心**](https://www.zhihu.com/people/saibochanxin) — 知乎 AI 原创深度。
* [**AI产品黄叔**](https://www.zhihu.com/column/c_1729237247428825088) — AI 产品深度。

### 英文 Newsletter

* [**The Batch (deeplearning.ai)**](https://www.deeplearning.ai/the-batch/) ⭐ — 吴恩达每周。
* [**Latent Space**](https://www.latent.space/) ⭐ — Swyx AI 工程实战。
* [**Import AI (Jack Clark)**](https://importai.substack.com/) ⭐ — AI 政策 + 研究。
* [**The Sequence**](https://thesequence.substack.com/)
* [**TLDR AI**](https://tldr.tech/ai) — 5 分钟读完。
* [**Ben's Bites**](https://www.bensbites.com/) — 给非技术读者。
* [**One Useful Thing**](https://www.oneusefulthing.org/)

### 中文播客 🇨🇳 ⭐

* [**张小珺·商业访谈录**](https://www.xiaoyuzhoufm.com/podcast/637df93a73105e8f155afde2) ⭐ — AI 商业深度访谈。
* [**远川投研**](https://www.yuanchuan.com/) — AI 投资分析。
* [**硅谷101**](https://www.xiaoyuzhoufm.com/podcast/5e497c98418a84a04686d7d8) ⭐ — 硅谷科技 / AI 深度。
* [**半拿铁 | 商业沉浮录**](https://www.xiaoyuzhoufm.com/podcast/61cdf8f8744b73e1191cb21f) — 包含 AI 商业。
* [**OnBoard!**](https://www.xiaoyuzhoufm.com/podcast/6020f72e421c8d2a9e00ef3a) — 海外华人科技播客。

### 英文播客

* [**Latent Space Podcast**](https://www.latent.space/podcast) ⭐
* [**Dwarkesh Podcast**](https://www.dwarkeshpatel.com/) ⭐
* [**Lex Fridman Podcast**](https://lexfridman.com/podcast/)
* [**No Priors**](https://www.no-priors.com/)
* [**Practical AI**](https://changelog.com/practicalai)

### 资讯站

* [Hacker News](https://news.ycombinator.com/) — 国际 AI 讨论。
* [ArXiv (cs.CL / cs.AI)](https://arxiv.org/list/cs.AI/recent) — 论文预印。
* [Papers with Code](https://paperswithcode.com/) — 论文 + 实现。
* [机器之心 / 量子位](https://www.jiqizhixin.com/) 🇨🇳 — 国内综合。

---

## 📺 B 站 UP 主与中文视频博主

> 国内学 AI 必看的 B 站资源——免费、中文、实战。

### AI 教学 / 论文解读

* [**跟李沐学AI**](https://space.bilibili.com/1567748478) ⭐ — Mu Li 系列，中文最佳深度学习入门。
* [**王树森**](https://space.bilibili.com/1369507485) ⭐ — RecSys / RL / DL 教科书级。
* [**沈向洋**](https://space.bilibili.com/3494360438008678) — 微软 / 大佬观察。
* [**同济子豪兄**](https://space.bilibili.com/1900783) — 计算机视觉教程。
* [**deep_thoughts**](https://space.bilibili.com/373596439) — 论文精读。

### AI 实战 / 工具评测

* [**林亦LYi**](https://space.bilibili.com/19957558) ⭐ — AI 工具实测、爆款视频。
* [**赛文乔伊**](https://space.bilibili.com/2027466092) — AI 日报、工具盘点（降临派视角）。
* [**李永乐老师**](https://space.bilibili.com/1564650761) — 科普通用包含 AI。
* [**老石谈芯**](https://space.bilibili.com/612932) — 芯片 + AI 硬件。
* [**回旋托马斯x**](https://space.bilibili.com/284664065) — 大模型工程实战。

### AI 资讯 / 解读

* [**AI 学习社**](https://space.bilibili.com/3493141758927932) — AI 新闻解读。
* [**奇绩论坛**](https://space.bilibili.com/3493279050823226) — 创业与 AI。
* [**MikeWang_白**](https://space.bilibili.com/1364068700) — AI 产品/创业。

---

## 🎤 会议与活动

* [**NeurIPS**](https://neurips.cc/) — ML 研究顶会。
* [**ICML**](https://icml.cc/)
* [**ICLR**](https://iclr.cc/)
* [**CVPR**](https://cvpr.thecvf.com/) — 计算机视觉。
* [**ACL**](https://www.aclweb.org/) — 计算语言学。
* [**AI Engineer Summit**](https://www.ai.engineer/) ⭐ — AI 工程师实战会议（SF / NYC）。
* [**Anthropic Builder Summit**](https://www.anthropic.com/events) — Anthropic 开发者活动。
* [**OpenAI DevDay**](https://devday.openai.com/) — OpenAI 开发者日。
* [**HuggingFace Events**](https://huggingface.co/events) — 社区活动。

### 国内会议 🇨🇳

* [**WAIC 世界人工智能大会**](https://www.worldaic.com.cn/) ⭐ — 上海年会。
* [**CCF 大模型论坛**](https://www.ccf.org.cn/) — 中国计算机学会大模型方向。
* [**NeurIPS 北京 / 上海 Meetup**](https://neurips.cc/) — 中国分会场。
* [**智源大会 BAAI Conference**](https://www.baai.ac.cn/) — 北京智源年会。
* [**云栖大会 (阿里)**](https://yunqi.aliyun.com/) — AI / 云。
* [**腾讯全球数字生态大会**](https://summit.tencent.com/) — 腾讯 AI / 云。
* [**百度世界大会**](https://www.baidu.com/) — 百度 AI 年会。

---

## 💼 AI 求职

### 全球

* [Moai Jobs](https://www.moaijobs.com/) — 顶级 AI 公司岗位。
* [HuggingFace Jobs](https://huggingface.co/jobs) — 开源 AI 岗位。
* [LinkedIn AI Engineer 搜索](https://www.linkedin.com/jobs/search/?keywords=AI%20Engineer)
* [WhoIsHiring (HN)](https://hnhiring.com/) — Hacker News 招聘合集。
* [Cracked Engineers](https://www.crackedengineers.com/) — 精选科技岗位。
* [Built In](https://builtin.com/jobs) — 美国按城市分类。
* [levels.fyi](https://www.levels.fyi/) — 美国薪资数据。

### 国内 🇨🇳

* [**拉勾网**](https://www.lagou.com/) — 互联网技术岗位。
* [**Boss 直聘**](https://www.zhipin.com/) — 综合招聘。
* [**脉脉**](https://maimai.cn/) — 职场内推 + 薪资爆料。
* [**牛客网**](https://www.nowcoder.com/) — 应届 / 内推 + 算法面经。
* [**CSDN 招聘**](https://www.csdn.net/job/) — 程序员招聘。
* [**字节跳动招聘**](https://job.bytedance.com/) — 字节直招。
* [**阿里招聘**](https://talent.alibaba.com/) — 阿里直招。
* [**腾讯招聘**](https://careers.tencent.com/) — 腾讯直招。

---

## 🌍 各国 AI 圈

> 各国 AI 资源 — 大学、公司、求职、签证、社区。欢迎 PR 你的国家。

### 🇨🇳 中国

**大学与研究院**
* [清华大学 THUNLP / AI Institute](https://nlp.csai.tsinghua.edu.cn/)
* [北京大学 — 王选计算机研究所](https://www.icst.pku.edu.cn/)
* [上海交大 — 人工智能研究院](https://ai.sjtu.edu.cn/)
* [北京智源人工智能研究院 (BAAI)](https://www.baai.ac.cn/)
* [上海人工智能实验室 (Shanghai AI Lab)](https://www.shlab.org.cn/)
* [鹏城实验室](https://www.pcl.ac.cn/)
* [香港中文大学 MMLab](http://mmlab.ie.cuhk.edu.hk/)

**大模型公司**
* DeepSeek 深度求索 / 通义 Qwen / Kimi 月之暗面 / 豆包 / 智谱 / MiniMax / 文心 / 混元 / 百川 / 零一万物 / Stepfun

**学习平台**
* 极客时间 / 慕课网 / 网易云课堂 / Datawhale / 蓝桥云课 / 腾讯云开发者实验室 / 阿里云开发者学堂

**资讯**
* 量子位 / 机器之心 / PaperWeekly / 新智元

### 🇺🇸 美国

**大学与研究**
* [Stanford AI Lab (SAIL)](https://ai.stanford.edu/)
* [MIT CSAIL](https://www.csail.mit.edu/)
* [Carnegie Mellon LTI / MLD](https://www.cmu.edu/ai/)
* [UC Berkeley BAIR](https://bair.berkeley.edu/)
* [Princeton NLP](https://nlp.princeton.edu/)

**训练营**
* [Springboard AI/ML](https://www.springboard.com/courses/ai-machine-learning-career-track/)
* [Bloomtech](https://bloomtech.com/)
* [Insight Data Science Fellows](https://insightfellows.com/)
* [Recurse Center](https://www.recurse.com/) — NYC 自驱学习营。

### 🇦🇺 澳洲

**大学**
* [Sydney Uni AI & ML](https://www.sydney.edu.au/engineering/study/areas-of-study/computer-science.html)
* [UNSW AI Institute](https://www.ai.unsw.edu.au/)
* [Melbourne Uni AI](https://study.unimelb.edu.au/find/courses/major/artificial-intelligence/)
* [Monash University Data Science & AI](https://www.monash.edu/it/study)
* [JR Academy](https://jiangren.com.au) — 项目制 AI 工程实战训练营，全球招生（澳洲总部）。

**招聘**
* [Atlassian Careers](https://www.atlassian.com/company/careers) — 悉尼 AI 工程师。
* [Canva Engineering](https://www.canva.com/careers/) — 悉尼 AI/ML。
* [JR Academy Career Coaching](https://jiangren.com.au/career-coaching) — AI 工程师就业辅导。

**澳洲签证（IT/AI 工程师）**
* **482 TSS** — 雇主担保临时技术签。
* **186 ENS** — 雇主担保 PR。
* **189 独立技术** — 计点 PR，IT 在 MLTSSL 上。
* **GTI 全球人才签 (858)** — 给高成就 AI 专家。

**社区**
* [Build Club Sydney](https://www.buildclub.ai/) — AI 开发者社区。
* [Chinese AI Association (Sydney)](https://chineseai.org.au/) — 澳洲华人 AI。

### 🇲🇾 马来西亚

**大学**
* [University of Malaya (UM)](https://www.um.edu.my/)
* [Universiti Sains Malaysia (USM)](https://cs.usm.my/)
* [Multimedia University (MMU)](https://www.mmu.edu.my/)

**公司 (吉隆坡 / Cyberjaya)**
* [Grab](https://grab.careers/) — 东南亚超级 App。
* [Carsome](https://www.carsome.my/) — 二手车 AI。
* [Aerodyne](https://www.aerodyne.group/) — 无人机 AI。

### 🇸🇬 新加坡

**大学**
* [新加坡国立大学 NUS](https://www.comp.nus.edu.sg/)
* [南洋理工大学 NTU](https://www.ntu.edu.sg/computing)
* [新加坡管理大学 SMU](https://scis.smu.edu.sg/)

**政府 / 项目**
* [AI Singapore](https://aisingapore.org/) ⭐ — 国家 AI 项目（AI Apprenticeship）。

**公司**
* [Sea / Shopee / Garena](https://career.sea.com/)
* [Grab AI Center](https://grab.careers/)
* [GovTech Singapore](https://www.tech.gov.sg/careers/)

> 加新国家？提 PR。需要：大学、AI 公司、招聘资源、社区、（如适用）签证路径。

---

## 🤖 机器人与具身智能

* [**Boston Dynamics**](https://www.bostondynamics.com) — Atlas / Spot。
* [**Figure AI**](https://www.figure.ai/) 🔥 — 人形机器人 Figure 02。
* [**1X Technologies**](https://www.1x.tech/) — Neo 家用人形。
* [**Tesla Optimus**](https://www.tesla.com/AI)
* [**Physical Intelligence (Pi)**](https://www.physicalintelligence.company/) 🆕 — 机器人基础模型。
* [**Skild AI**](https://www.skild.ai/) 🆕 — 通用机器人智能。
* [**宇树 Unitree**](https://www.unitree.com/) 🇨🇳 — 国产人形 + 四足机器人。
* [**智元 AgiBot**](https://www.agibot.com/) 🇨🇳 — 国产人形机器人公司。
* [**银河通用 Galbot**](https://www.galbot.com/) 🇨🇳 — 国产服务机器人。
* [**LeRobot (HuggingFace)**](https://github.com/huggingface/lerobot) 🆕 (24k ⭐) — 开源机器人学习。

---

## 贡献

提 PR 或邮件 **hello@jiangren.com.au**。

**简要规则**：
* 加资源时确认仍在维护、有用（我们会定期清理死链）。
* 单行格式：`[名称](url) — 简短描述`。
* 放到合适章节。
* 无利益相关披露不加 affiliate link。

详见 [CONTRIBUTING.md](./CONTRIBUTING.md) 和 [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)。

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

In so far as the law allows, [JR Academy](https://jiangren.com.au) waives all copyright and related rights to this work.
