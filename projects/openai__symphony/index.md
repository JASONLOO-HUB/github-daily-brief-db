---
type: project_profile
date: 2026-04-29
repo: "openai/symphony"
owner: "openai"
name: "symphony"
url: "https://github.com/openai/symphony"
signal_type: new_hot
tags:
  - ai-agent
  - orchestration
  - coding-agent
  - linear
audience:
  - ai_product_manager
  - engineering_lead
  - xiaohongshu_creator
stars: 18777
forks: 1557
primary_language: "Elixir"
license: "Apache-2.0"
source_urls:
  - "https://github.com/openai/symphony"
  - "https://api.github.com/repos/openai/symphony"
  - "https://raw.githubusercontent.com/openai/symphony/main/README.md"
  - "https://openai.com/index/open-source-codex-orchestration-symphony/"
pm_value_score: 5
xiaohongshu_value_score: 4
product_opportunity_score: 5
confidence: high
last_checked: 2026-04-29T23:50:00+08:00
---

# openai/symphony

## 稳定定位

Symphony 是 OpenAI 开源的 coding agent 编排实验项目。它把项目工作拆成彼此隔离的自动化实现运行，并让团队从“盯着 agent 对话”转向“管理任务、证明和验收”。

## 原理解释

它的核心不是再做一个聊天式 coding agent，而是在任务系统和代码仓库之间加一层编排器：看板里出现任务后，系统启动独立 agent 去实现；agent 完成后提交可验证证据，例如 CI 状态、PR 评审反馈、复杂度分析和 walkthrough。对非工程背景的人来说，可以把它理解成“会自己接 Linear 工单、写代码、交验收材料的自动化实习生团队”。

## 典型用例

- 工程团队把小型 bugfix、测试补全、文档更新交给 agent 异步处理。
- 产品/技术负责人不直接指导每一步，而是看任务是否通过验收。
- 内部工具团队用它验证“agent 是否能稳定处理重复工程任务”。

## 对 AI 产品经理的价值

Symphony 给出一个重要产品范式：AI agent 产品的核心界面可能不是聊天框，而是任务队列、权限、证据、验收和回滚。PM 可以借鉴它设计“agent 工作台”的需求字段：任务来源、任务状态、运行隔离、验收标准、人工批准点、失败复盘。

## 对小红书账号的价值

适合讲“AI 从帮你写一句话，升级到帮团队完成任务”。这比单纯介绍模型更容易让文科生理解 AI 产品经理为什么要懂 workflow、权限和验收。

## 产品化机会

做一个中文“AI 任务编排学习版”：把 Notion/飞书任务拆成 prompt、资料、验收清单，让学习者体验 agent 异步完成“写简历、拆岗位、整理选题”的过程。MVP 不需要真的写代码，可以先用半自动执行和可视化任务状态验证需求。

## 风险与限制

README 明确称其为 engineering preview，适合可信环境测试。它不是面向普通用户的成熟 SaaS，落地时要重视代码权限、凭证隔离、失败回滚和责任边界。
