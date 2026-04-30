---
title: "GitHub Daily Brief Database"
description: "每日 GitHub 热门项目情报库 · 小红书选题库 · AI 产品机会库"
owner: "JASONLOO-HUB"
target_audience: "中国文科生、AI新手、转型AI产品经理"
data_source: "GitHub Search API"
analysis_engine: "GPT-4.1 / Perplexity API"
last_updated: 2026-04-30
---

# GitHub Daily Brief Database

> 每日 GitHub 热门项目情报库 · 小红书选题库 · AI 产品机会库

## 这个仓库是什么

本仓库是一个结构化的信息数据库，用于沉淀每日从 GitHub 抓取的热门项目情报。数据来源由 GitHub Search API 获取，通过 GPT-4.1 / Perplexity API 进行深度分析，服务于：

- **AI 产品经理视角**：洞察新工具、新交互范式、新 Agent 能力
- **小红书内容创作**：为中国文科生学习 AI 工具、转行 AI 提供选题素材
- **产品机会挖掘**：利用 GitHub 信息差，做中文用户友好的衍生产品

## 目录结构

```
github-daily-brief-db/
├── briefs/                   # 新版每日简报：按 YYYY/MM/YYYY-MM-DD 分层
│   └── 2026/04/2026-04-29.md # 日度总览，只放摘要、评分、入口链接
├── indexes/                  # 月度索引
│   └── 2026-04.md
├── topics/                   # 主题索引：按 agent、memory、LLMOps 等聚合
│   ├── ai-agent.md
│   ├── ai-memory.md
│   └── xiaohongshu-content.md
├── schema/
│   └── frontmatter.yaml      # YAML frontmatter 字段说明
├── daily/                    # 每日简报，按日期命名
│   └── 2026-03-28.md         # 今日简报（含 YAML frontmatter）
├── projects/                 # 单个项目的详细档案（含 YAML frontmatter）
│   ├── openai__symphony/
│   │   ├── index.md
│   │   └── snapshots/2026-04-29.md
│   ├── codebase-to-course.md
│   ├── wewrite.md
│   ├── TypeNo.md
│   ├── slavingia-skills.md
│   ├── OpenSpace.md
│   └── awesome-free-llm-apis.md
├── database/
│   └── projects_schema.json  # 项目字段模板（Schema 定义）
├── ideas/
│   ├── content-ideas.md      # 小红书选题池（含优先级排序）
│   └── product-ideas.md      # 产品机会池（含执行路径）
└── README.md
```

## 渐进式披露上下文设计

本仓库的文件结构遵循**渐进式披露上下文（Progressive Context Disclosure）**原则：

| 层级 | 文件 | 上下文深度 | 用途 |
|------|------|-----------|------|
| 第一层 | README.md | 概览 | 快速了解仓库结构和用途 |
| 第二层 | briefs/YYYY/MM/YYYY-MM-DD.md | 日度摘要 | 每日热门项目概览 + 机会判断 |
| 第三层 | projects/{owner}__{repo}/index.md | 项目详情 | 单个项目的长期分析档案 |
| 第四层 | projects/{owner}__{repo}/snapshots/YYYY-MM-DD.md | 日期快照 | 当天入选原因、变化和来源链接 |
| 主题层 | topics/*.md | 跨项目聚合 | 小红书选题、产品机会、学习路径 |
| 元数据 | YAML frontmatter | 结构化标签 | 支持自动化检索和 AI 上下文注入 |

每个文件都包含 YAML frontmatter，便于自动化脚本批量处理、AI 工具快速理解文件上下文，以及未来接入 Notion、飞书等知识库系统。

> 说明：`daily/` 与 `projects/*.md` 为早期结构，2026-04-29 起新增 `briefs/`、`indexes/`、`topics/` 和 `projects/{owner}__{repo}/` 结构，以减少单文件上下文膨胀，并支持按日期、项目、主题逐级展开。

## 字段说明

详见 database/projects_schema.json

## 更新频率

每日手动或通过脚本调用 GitHub API 获取热门项目，使用 GPT-4.1 / Perplexity API 进行深度分析后归档。

## 如何使用

1. **查看今日简报**：打开 daily/ 目录下最新日期的文件
2. **查看新版简报**：打开 briefs/ 目录下最新日期的文件，例如 briefs/2026/04/2026-04-29.md
3. **深入了解某个项目**：打开 projects/{owner}__{repo}/index.md
4. **查看当天变化**：打开 projects/{owner}__{repo}/snapshots/YYYY-MM-DD.md
5. **获取选题灵感**：查看 topics/xiaohongshu-content.md 或 ideas/content-ideas.md
6. **寻找产品机会**：查看每日简报里的产品化机会，或继续使用 ideas/product-ideas.md
