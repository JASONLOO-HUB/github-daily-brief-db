---
type: project_profile
date: 2026-04-29
repo: "ComposioHQ/composio"
owner: "ComposioHQ"
name: "composio"
url: "https://github.com/ComposioHQ/composio"
signal_type: major_update
tags:
  - agent-tools
  - mcp
  - tool-calling
  - security
audience:
  - ai_product_manager
  - xiaohongshu_creator
stars: 27964
forks: 4539
primary_language: "TypeScript"
license: "MIT"
source_urls:
  - "https://github.com/ComposioHQ/composio"
  - "https://api.github.com/repos/ComposioHQ/composio"
  - "https://raw.githubusercontent.com/ComposioHQ/composio/next/README.md"
  - "https://github.com/ComposioHQ/composio/releases/tag/py%400.12.0"
pm_value_score: 4
xiaohongshu_value_score: 4
product_opportunity_score: 5
confidence: high
last_checked: 2026-04-29T23:50:00+08:00
---

# ComposioHQ/composio

## 稳定定位

Composio 是面向 agent 的工具集成 SDK，提供 Python 和 TypeScript SDK，帮助 agent 连接外部工具、处理认证、调用 toolkit，并与 OpenAI Agents 等框架集成。

## 原理解释

Agent 要执行真实任务，需要连接很多外部服务。Composio 提供工具目录、认证、上下文管理和 SDK 层，让开发者不用为每个工具单独写一套集成。它的价值在于把“工具调用”变成可管理的产品能力。

## 典型用例

- 给 OpenAI Agents 接入 Hacker News、SaaS 工具或内部系统。
- 在 Python/TypeScript 应用里统一管理 agent 可用工具。
- 控制文件上传下载、工具权限和执行边界。

## 对 AI 产品经理的价值

Composio 适合观察 agent 工具层：工具发现、授权、schema、执行、文件处理、审计、失败处理。PM 在设计 agent 产品时需要把这些能力写入权限和安全需求。

## 对小红书账号的价值

适合讲“AI 真正帮你办事，背后需要连接工具”。用生活例子解释：AI 不是凭空订票、发邮件、查网页，而是通过工具获得授权后执行。

## 产品化机会

做“AI 工具权限体检表”：帮助普通用户判断一个 AI agent 要求的权限是否合理，哪些文件/账号/操作需要显式确认。

## 风险与限制

工具层越强，误操作和数据泄露风险越高。Composio v0.12.0 把自动文件上传下载改为显式 opt-in，说明默认权限保守是趋势。
