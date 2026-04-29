---
type: project_profile
date: 2026-04-29
repo: "MemPalace/mempalace"
owner: "MemPalace"
name: "mempalace"
url: "https://github.com/MemPalace/mempalace"
signal_type: new_hot
tags:
  - ai-memory
  - rag
  - knowledge-graph
  - mcp
audience:
  - ai_product_manager
  - xiaohongshu_creator
  - chinese_liberal_arts_ai_learners
stars: 50318
forks: 6614
primary_language: "Python"
license: "MIT"
source_urls:
  - "https://github.com/MemPalace/mempalace"
  - "https://api.github.com/repos/MemPalace/mempalace"
  - "https://raw.githubusercontent.com/MemPalace/mempalace/develop/README.md"
  - "https://github.com/MemPalace/mempalace/releases/tag/v3.3.3"
pm_value_score: 5
xiaohongshu_value_score: 5
product_opportunity_score: 4
confidence: high
last_checked: 2026-04-29T23:50:00+08:00
---

# MemPalace/mempalace

## 稳定定位

MemPalace 是本地优先的 AI 记忆系统。它保存原始对话和项目内容，通过语义检索、结构化空间和知识图谱让 agent 找回长期上下文。

## 原理解释

MemPalace 不把历史压缩成摘要，而是保存 verbatim text。它把人物和项目组织成 wing，把主题组织成 room，把原始内容放入 drawer，再用语义搜索检索。默认后端是 ChromaDB，同时提供可替换 backend 接口。README 还提到本地 SQLite 的时间化实体关系图，以及 MCP 工具用于读写记忆。

## 典型用例

- Claude Code、Gemini CLI 或 MCP 工具在新会话里找回过去项目决策。
- 个人把学习笔记、职业规划、求职材料变成可检索记忆。
- agent 团队为不同角色保存自己的 wing 和 diary。

## 对 AI 产品经理的价值

它提醒 PM：AI 记忆不是“聊天记录列表”，而是一个产品能力组合，包括原文证据、语义检索、权限边界、时间线、实体关系和跨工具调用接口。记忆层可以成为 AI 产品的留存核心。

## 对小红书账号的价值

这是非常适合文科生的题材，因为“知识宫殿”隐喻天然易懂。可以把 AI 记忆讲成：让 AI 记住你的简历、经历、目标岗位、作品集和学习计划。

## 产品化机会

做一个“AI 转行记忆库”：用户上传简历、笔记、岗位 JD、小红书选题、项目复盘，系统按人物/项目/技能/时间线组织，并给出每日学习建议和内容选题。

## 风险与限制

README 提到有冒充网站风险，说明热门开源项目容易出现供应链和品牌仿冒问题。产品化时要强调官方来源、安装安全和本地数据隐私。
