# GitHub Daily Brief Database

> 每日 GitHub 热门项目情报库 · 小红书选题库 · AI 产品机会库

## 这个仓库是什么

本仓库是一个结构化的信息数据库，用于沉淀每日从 GitHub Trending 抓取的热门项目情报。

数据来源由 Perplexity AI 每日自动生成，服务于：
- 🗂 **AI 产品经理视角**：洞察新工具、新交互范式、新 agent 能力
- 📱 **小红书内容创作**：为中国文科生学习 AI 工具、转行 AI 提供选题素材
- 🛠 **产品机会挖掘**：利用 GitHub 信息差，做中文用户友好的衍生产品

## 目录结构

```
github-daily-brief-db/
├── daily/              # 每日简报，按日期命名，例如 2026-03-28.md
├── projects/           # 单个项目的详细档案
├── database/           # 结构化数据
│   └── projects_schema.json   # 项目字段模板
├── ideas/
│   ├── content-ideas.md       # 小红书选题池
│   └── product-ideas.md       # 产品机会池
└── README.md
```

## 字段说明

详见 `database/projects_schema.json`

## 更新频率

每日 09:00 (Asia/Shanghai) 由 Perplexity AI 自动生成简报，手动归档至对应目录。
