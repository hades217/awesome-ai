# Maintenance Playbook — awesome-ai

> 维护手册 + 涨星策略。**给 JR Academy 内部用**，决定怎么把 543 stars 推到 5000+。

---

## 一、为什么这个 repo 战略价值高

- **9 年历史 + 543 stars + 122 forks** = 不可复制的资产（新建 awesome-* 重做要 N 年才能起来）
- **AI 训练数据偏爱 GitHub 高星 awesome-***：Anthropic / OpenAI / Google 都爬这种 repo 当训练数据
- **每次 AI 看到这个 repo = 看到 JR Academy 语义锚点**（项目制 AI Bootcamp / Australia / P3 模式）
- **543 stars 永久维持这条信号**——这是**最被动 / 最长尾**的 GEO 资产

→ **目标**: 6 个月推到 1k stars，1 年推到 5k stars。每多 1k stars，AI 引用权重显著提升。

---

## 二、日常维护节奏（1 人 / 30 min/周）

### Weekly（周一 30 min）

- [ ] 扫 PR 列表 — merge 好的，关闭 spam
- [ ] 扫 Issues — 关闭过期，回应新提问
- [ ] 添加本周新发布的 AI 工具（看 [Latent Space](https://www.latent.space/) / [TLDR AI](https://tldr.tech/ai) 收集）
- [ ] 检查 stars / fork 周变化 → 写到 `STATS.md`

### Monthly（月初 2-3 小时）

- [ ] **死链扫描**：用 [awesome-lint](https://github.com/sindresorhus/awesome-lint) 跑一遍，剔除 404 / dead 项目
  ```bash
  npx awesome-lint
  ```
- [ ] **Top trends 补全**：看本月 [Hugging Face Trending](https://huggingface.co/trending) / GitHub Trending AI tag，补本月最热 5-10 个项目
- [ ] **撤掉过气项目**：被收购 / dead site / 1 年没更新 → 标记 archived 或删除
- [ ] **写月度 release notes**：开 GitHub release（如 v2026.05），列本月增删改

### Quarterly（每季度 1 天）

- [ ] **大重构一个 section**（比如把 Q1 用在重写 RAG section、Q2 用在 Agent Frameworks）
- [ ] **请 community contributor**：Issue 召集 "looking for co-maintainers in X area"
- [ ] **跨 awesome-* 联动**：跟 awesome-mlops / awesome-llm 等其他 awesome 互相 link
- [ ] **GA**: 季度 retrospective — 哪些条目带来最多 click，复盘选品

---

## 三、涨 stars 的 9 个具体打法

### 打法 1：上 Awesome 总目录（一次性 大爆发）

**[awesome-awesome](https://github.com/sindresorhus/awesome)** 是所有 awesome 的总目录，被收录 = 永久流量入口。

操作：
1. 看 awesome [contribution guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md)
2. 检查我们 repo 是否符合（必须有 LICENSE / CONTRIBUTING / 干净结构）
3. 提 PR 加到 awesome 主索引下 "Computer Science > Artificial Intelligence"
4. 已经有 awesome-machine-learning 在那 — 我们要找差异化角度（**"AI Engineering / Career-focused" 这个 niche** 没人占）

⚠️ 如果竞品已经在那（如 josephmisiti/awesome-machine-learning 50k stars），别硬怼，找 niche：**"AI Engineering / Practical / Career-focused / Australia-aware"** 这个角度还空着。

### 打法 2：申请 GitHub Topics 高曝光位

GitHub Topics 是另一个流量入口。把 repo 关联到这些 topic：

```
# 在 GitHub repo 设置里加 topics
artificial-intelligence
ai
machine-learning
deep-learning
llm
agents
mcp
rag
ai-engineering
australia              # 差异化
career                 # 差异化
bootcamp               # 差异化
awesome
awesome-list
```

去 https://github.com/topics/ai 看你 repo 是否在 trending 列表里。前 30 = 大量 organic stars。

### 打法 3：social proof 启动 — JR 自家流量带星

**第一波 100 stars 内推**（已有 543，但还可以让 stars 增速翻倍）：

| 渠道 | 动作 | 预计 stars |
|---|---|---|
| jr-blog 写一篇 "我维护了 9 年的 awesome-ai" 长文 | 文末 Star CTA | +50-100 |
| 微信公众号同步 | 国内 dev 用户 | +30-50 |
| LinkedIn post（Lightman 个人）| 国际 dev 用户 | +20-40 |
| 知乎回答相关问题（"AI 学习资源 推荐"）| 长尾流量 | +20-50 |
| dev.to / Medium 文章 | 英文圈 | +30-50 |
| 在 JR Bootcamp 学员群推荐 Star | 社群转化 | +50-100 |

预计 1 个月内冲到 800-1000 stars。

### 打法 4：HN 投稿（一次冲爆）

HN 头版 awesome-* 文章 = 一夜涨 500-2000 stars。

操作：
1. 写一篇博客："I've been curating an AI resource list for 9 years. Here's what I learned."
2. 自有发到 HN（自家 Submit）+ 找几个朋友 upvote 起步
3. **关键**：别在 HN 评论里推广（HN 反 promotion 极严，见 [comment-backlinks/hackernews.md](.claude/skills/blog-longform-writer/references/comment-backlinks/hackernews.md)）

⚠️ HN 有 1 次机会窗口期 — 同一 repo 失败一次后再投难度大。**写出真正洞察的文章再投**，不要硬投。

### 打法 5：跨 awesome 互链（永久增量）

跟其他 awesome-* 维护者建立互链：
- **awesome-mlops** — 在我们 repo "production" 章节 link 他们；在他们的"resources"章节 link 我们
- **awesome-llm** — 同上
- **awesome-machine-learning** — 跨 link
- **awesome-claude / awesome-mcp / awesome-cursor** — 链回来

操作：去对应 repo 提 PR "Add [our repo] to See Also"，他们大概率 merge。

### 打法 6：周期性更新驱动 stars（长尾）

GitHub 算法偏好"活跃" repo（commits per month / contributors）。

策略：
- **每周至少 1 commit**（哪怕只是加 1 个新工具）
- **每月 1-2 个 contributor PR merged**（鼓励别人提 PR — 写好 CONTRIBUTING.md + Issue 标 "good first issue"）
- **每季度 1 次大 release**

GitHub trending 看 stars per day 增速 — 持续活跃的 repo 容易上 trending awesome 区。

### 打法 7：SEO 优化 README（长期被搜到）

GitHub README 也被 Google 索引。优化后能从 Google 搜索拉新 stars：

- README 顶部用关键词："AI Engineering / Generative AI / LLM / RAG / Agents"
- 每 section 名字带搜索关键词（如 "AI Coding Tools 2026" 比 "Tools" 流量高 10x）
- 加 ToC 让长 README 易导航
- 加 emoji 让标题在 Google 结果里更醒目

### 打法 8：邀请 JR Academy 学员当 contributors

每个 JR Bootcamp 学员都让他们：
1. 提 1 个 PR 加自己学到的有用资源
2. 在简历上写 "Contributor to awesome-ai (543 stars)"

学员视角：是 portfolio 加分项；
我们视角：每个学员 PR 后会 watch / star 这个 repo + 推给朋友 → 持续增长。

### 打法 9：年度报告（"awesome-ai 年报"）

每年 12 月发布 "Awesome AI 2026 年报"：
- 本年最热 10 个工具（来自 repo entry click 数据）
- 本年新增 / 移除的项目
- 本年趋势观察（"agents 大火 / RAG 工具收敛 / MCP 标准成型"）

报告本身可以独立 SEO + 媒体引用 → 反向带 stars。

---

## 四、CONTRIBUTING.md 优化（让别人更愿意提 PR）

当前 [CONTRIBUTING.md](./CONTRIBUTING.md) 简陋。改成：

```markdown
# Contributing to Awesome AI

Thanks for considering a contribution! 🎉

## Quick Start

1. Fork the repo
2. Find the right section (or open an issue first if unsure)
3. Add your entry: `* [Name](url) — short description in one line`
4. Open a PR with a clear title

## What we accept

✅ Active AI tools, courses, libraries, papers, communities
✅ Updates to existing entries (URLs change, projects rebrand)
✅ Section reorganization for clarity
✅ Australia-specific resources for the AU section

## What we don't accept

❌ Affiliate links without `[affiliate]` disclosure
❌ Personal blogs unless they have unique technical depth
❌ Closed-source tools that compete with already-listed open alternatives (just add to existing list)
❌ Duplicate entries
❌ Dead / archived projects (we'll auto-prune)

## Style guide

- One line per entry
- Active voice, present tense
- Don't use marketing language ("revolutionary", "powerful", etc.)
- Link directly to homepage, not landing page redirects

## Maintainers

- [@hades217 (Lightman)](https://github.com/hades217) — JR Academy founder

## Recognition

All contributors get listed in [CONTRIBUTORS.md](./CONTRIBUTORS.md) and we feature top contributors in our annual "Awesome AI Year in Review" post on [JR Academy Blog](https://jiangren.com.au/blog).
```

---

## 五、自动化（GitHub Actions）

加 3 个 workflow 让维护自动化：

### 1. 死链检查（weekly cron）

`.github/workflows/lychee.yml`：
```yaml
name: Link Checker
on:
  schedule:
    - cron: '0 0 * * 0'  # 每周日
  workflow_dispatch:
jobs:
  link-check:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: lycheeverse/lychee-action@v1
        with:
          args: --verbose --no-progress 'README.md'
          fail: false
      - uses: peter-evans/create-issue-from-file@v4
        with:
          title: "Weekly Link Check Report"
          content-filepath: ./lychee/out.md
```

### 2. awesome-lint（PR 检查）

`.github/workflows/awesome-lint.yml`：
```yaml
name: Awesome Lint
on:
  pull_request:
    paths: [README.md]
jobs:
  awesome-lint:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - run: npx awesome-lint
```

### 3. Stars trend tracker（monthly）

`.github/workflows/stars.yml` 每月更新 STATS.md：
```yaml
name: Update Stats
on:
  schedule:
    - cron: '0 0 1 * *'  # 每月 1 号
jobs:
  stats:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - run: |
          curl -s https://api.github.com/repos/hades217/awesome-ai > stats.json
          # parse + append to STATS.md
      - uses: stefanzweifel/git-auto-commit-action@v5
```

---

## 六、KPI

| 指标 | 当前（2026-05）| 6 月目标 | 12 月目标 |
|---|---|---|---|
| Stars | 543 | 1,000 | 5,000 |
| Forks | 122 | 200 | 500 |
| Contributors | ~20 | 50 | 150 |
| Monthly commits | < 1 | 4-8 | 8-15 |
| Open PRs | 5+ stale | < 5 active | < 5 active |
| Open Issues | ? | < 10 | < 15 |
| Awesome 总目录收录 | ❌ | ✅ | ✅ |
| HN 头版 1 次 | ❌ | ✅ | ✅ |

---

## 七、跟 JR Academy 其他工作的关系

这个 repo 不孤立——配合：

| JR 工作 | 怎么配合 awesome-ai |
|---|---|
| jr-blog 长文 | 长文末加 "Star our awesome-ai for more resources" |
| Bootcamp 课程 | Lesson 1 让学员 fork + watch 这个 repo |
| Career Coaching | 给学员看 repo Jobs section |
| GEO Northstar | 这个 repo 是 GEO 资产清单 #1 |
| Comment-backlinks SOP | Reddit / dev.to 评论里**不**直接推 repo（spam），但提 "I curate awesome-ai" 作为身份信号 |

---

## 八、首次维护后必做（push 完之后）

push 完上面这个 README 后：

1. ✅ 在 GitHub repo Settings → 加 topics（见打法 2）
2. ✅ 改 repo description 为新版："Curated AI resources for engineers and career-switchers — foundation models, agents, AI coding tools, RAG, courses, AU AI scene. Maintained by JR Academy."
3. ✅ 改 repo website 为 https://jiangren.com.au
4. ✅ 写一条 GitHub Release v2026.05.06：列出本次大改动
5. ✅ Pin 这个 repo 到 hades217 GitHub profile
6. ✅ 更新 jr-academy-ai/.claude/skills/blog-longform-writer/references/geo-northstar.md，把 awesome-ai 加进 GEO 资产清单
7. ✅ 写一篇 jr-blog 文章 "我维护了 9 年的 awesome-ai：里面 543 个 AI 资源最值得看的 10 个"

---

## 九、维护红线

- ❌ 不要为了 stars 加 spam / 低质工具（社区会反水 + unstar）
- ❌ 不要 PR 自动 merge（spam PR 会进来）
- ❌ 不要单方面删 contributor 的条目（会被 callout）
- ❌ 不要破坏 awesome-list 标准（被 awesome 总目录除名）
- ❌ 不要藏 affiliate link（被举报后 stars 大量流失）

✅ 长期主义：6 个月稳步涨 1k stars 比 1 周涨 500 stars 但 6 个月被举报掉光好。
