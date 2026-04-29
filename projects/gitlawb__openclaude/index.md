---
type: project_profile
date: 2026-04-29
repo: "Gitlawb/openclaude"
owner: "Gitlawb"
name: "openclaude"
url: "https://github.com/Gitlawb/openclaude"
signal_type: new_hot
tags:
  - coding-agent
  - ai-agent
  - cli
  - multi-model
audience:
  - ai_product_manager
  - xiaohongshu_creator
stars: 24996
forks: 8129
primary_language: "TypeScript"
license: "NOASSERTION"
source_urls:
  - "https://github.com/Gitlawb/openclaude"
  - "https://api.github.com/repos/Gitlawb/openclaude"
  - "https://raw.githubusercontent.com/Gitlawb/openclaude/main/README.md"
  - "https://github.com/Gitlawb/openclaude/releases/tag/v0.7.0"
pm_value_score: 4
xiaohongshu_value_score: 5
product_opportunity_score: 4
confidence: medium
last_checked: 2026-04-29T23:50:00+08:00
---

# Gitlawb/openclaude

## 稳定定位

OpenClaude 是一个开源 coding-agent CLI，目标是用一个终端工作流连接 OpenAI-compatible APIs、Gemini、GitHub Models、Codex、Ollama 等云端和本地模型。

## 原理解释

它把 coding agent 所需的提示、工具、agents、MCP、slash commands、streaming output 组织在一个 CLI 里，同时提供 provider 配置。对用户来说，它试图把“某个模型专属的 coding 体验”抽象成多模型可复用工作台。

## 典型用例

- 开发者在不同模型之间切换，但保留同一套 CLI 工作流。
- 使用本地 Ollama 或 OpenAI-compatible 服务运行 coding agent。
- 通过 MCP 和 web/tools 扩展 agent 能力。

## 对 AI 产品经理的价值

OpenClaude 说明用户对“模型无关的工作流层”有需求。PM 可以从中观察 provider 管理、模型切换、工具权限、项目记忆和插件生态如何影响留存。

## 对小红书账号的价值

适合讲“不要被单一工具锁死”：AI 学习者可以理解为同一个工作台连接多个模型。对文科生转 AI PM 来说，这是理解“模型层 / 工具层 / 工作流层”的好例子。

## 产品化机会

做“多模型 AI 学习工作台”的轻量版：用统一模板比较不同模型完成同一任务的表现，例如简历润色、选题生成、竞品拆解、需求文档。

## 风险与限制

GitHub API 暴露的 license 为 NOASSERTION，README 徽章显示 MIT，但自动化归档应以 API 字段为准并保留来源。多模型 CLI 还涉及供应商兼容、上下文窗口、计费和用户凭证管理。
