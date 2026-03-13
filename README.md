# 🔥 Awesome Daily Industrial RecSys Papers

> **Daily tracking of industrial recommendation system papers from arxiv cs.IR — updated every day.**

[![Stars](https://img.shields.io/github/stars/henryhuanghenry/Awesome-Daily-Industrial-RecSys-Papers?style=social)](https://github.com/henryhuanghenry/Awesome-Daily-Industrial-RecSys-Papers/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/henryhuanghenry/Awesome-Daily-Industrial-RecSys-Papers)](https://github.com/henryhuanghenry/Awesome-Daily-Industrial-RecSys-Papers/commits/main)

---

## ⭐ Star This Repo to Stay Updated

**If you work on or follow recommendation systems, this repo is for you.**

Every day, I automatically pull the latest papers from [arxiv cs.IR](https://rss.arxiv.org/rss/cs.IR), filter for **industry-authored papers** (Google, Meta, Alibaba, ByteDance, Netflix, Kuaishou, Uber, LinkedIn, IBM, and more), and publish:

- 📄 **Full paper markdowns** — complete section-by-section notes with all figures, tables, and equations
- 🏷️ **Structured tags** — Scene / Tech / Problem three-dimensional taxonomy
- 📊 **Bilingual weekly reports** — Chinese + English, with method summaries and highlights
- 🧪 **Online A/B test tracking** — flag papers that report real production results

> **Hit ⭐ Star** to get notified on new commits. No noise, just daily industrial RecSys papers.

---

## 📁 Repository Structure

```
Awesome-Daily-Industrial-RecSys-Papers/
├── week-report/
│   └── {YYYY_WeekN_MMDD}.md        # Bilingual weekly summary (e.g., 2026_Week11_0309.md)
└── paper-storage/
    └── {YYYY_WeekN_MMDD}/
        ├── {ArxivId}_{KeyTitle}.md  # Full paper notes with figures & equations
        └── attachment/
            └── {ArxivId}_fig{N}.png # Downloaded figures from paper
```

---

## 📋 Weekly Report Format

Each week report is **bilingual (中英双语)** and contains a full table of all papers found that week, with industrial papers fully analyzed.

### Industrial Papers Table

| ArXiv ID | Title / 标题 | MD | Affiliation / 机构 | Star Tags | Paper Tags / 论文标签 | Online A/B | Method / 主要方法 | Highlight / 亮点 |
|----------|-------------|----|--------------------|-----------|----------------------|------------|-------------------|-----------------|
| [2603.10409](https://arxiv.org/abs/2603.10409) | Differentiable Geometric Indexing for Generative Retrieval | [MD](paper-storage/2026_Week11_0309/2603.10409_DiffGeomIndexGenRetrieval.md) | Alibaba | 生成式推荐 | 场景: 电商 \| 技术: 生成式检索 \| 问题: 长尾推荐 | ✅ +1.27% CTR | 用可微分几何索引解决长尾遮蔽 / Differentiable geometric indexing for long-tail | 理论证明Scaled Cosine等价于黎曼流形梯度优化 |
| [2510.25622](https://arxiv.org/abs/2510.25622) | ADA-SID: Adaptive Behavior Mining for Semantic IDs | [MD](paper-storage/2026_Week11_0309/2510.25622_ADA-SID.md) | Alibaba | 生成式推荐, 多模态 | 场景: 电商, 广告 \| 技术: 语义ID \| 问题: 长尾推荐 | ✅ +3.50% Revenue | 自适应去噪协同信息框架 / Adaptive denoising for SID generation | 线上广告收入+3.50% |

### Non-Industrial Papers Table

| ArXiv ID | Title / 标题 | Affiliation / 机构 | MD |
|----------|-------------|-------------------|----|
| [2603.10332](https://arxiv.org/abs/2603.10332) | Does Reasoning Make Search More Fair? | Johns Hopkins | 非工业界 / Non-industrial |

---

## 🏷️ Tag Taxonomy / 标签分类体系

Papers are tagged along **three dimensions** (三维标签体系):

| Dimension | Examples |
|-----------|----------|
| **场景 (Scene)** | 电商 (E-commerce), 短视频 (Short Video), 广告 (Ads), 搜索 (Search), 外卖 (Food Delivery), 社交/内容 (Social/Content), 新闻 (News), 通用Agent |
| **技术 (Tech)** | 双塔检索 (Two-tower), 生成式检索 (Gen. Retrieval), 序列推荐 (SeqRec), 语义ID (Semantic ID), 多模态融合 (Multimodal), RAG, Agent系统, 记忆增强 |
| **问题 (Problem)** | CTR预估, 召回优化, 长尾推荐, 冷启动, 多语言, SID量化, 端到端优化, Agent经验学习 |

### ⭐ Star Tags

Special labels for significant research directions:

- **LLM&Rec** — LLMs applied to recommendation
- **生成式推荐 (Generative Rec)** — Generative recommendation models
- **长序列建模 (Long Seq. Modeling)** — Long sequence modeling
- **多模态&Rec (Multimodal)** — Multimodal recommendation
- **Rec Scaling** — Scaling laws / foundation models for recommendation

---

## 📅 Recent Week Reports

| Week | Date | Industrial Papers | Highlights |
|------|------|------------------|------------|
| [Week 11](week-report/2026_Week11_0309.md) | 2026-03-09 | 6 papers | DGI (Alibaba) +1.27% CTR · ADA-SID (Alibaba) +3.50% Revenue · Uber Eats multilingual search |

---

## 🔍 What Counts as "Industrial"

A paper is included if **at least one author** is affiliated with a company. Examples:

> Google, Meta, Microsoft, Apple, Amazon, Netflix, LinkedIn, Spotify  
> Alibaba, Tencent, Baidu, ByteDance, JD.com, Meituan, Kuaishou, Bilibili  
> Uber, Grab, Shopee, Sea, Pinterest, Snap, Salesforce, Adobe, IBM, Huawei

Academic-only papers (universities / research institutes) are listed separately as non-industrial.

---

## 📬 How to Follow

- ⭐ **Star** this repo — GitHub will notify you of new commits
- 👁️ **Watch** → "Custom" → "Commits" for email notifications on every daily update
- 🔔 Or just check back weekly — the `week-report/` folder has everything summarized

---

*Updated daily. All paper notes include full section summaries, embedded figures, tables, and LaTeX equations.*
