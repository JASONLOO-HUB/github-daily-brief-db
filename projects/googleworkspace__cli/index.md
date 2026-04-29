---
type: project_profile
date: 2026-04-29
repo: "googleworkspace/cli"
owner: "googleworkspace"
name: "cli"
url: "https://github.com/googleworkspace/cli"
signal_type: new_hot
tags:
  - workspace-automation
  - ai-agent
  - cli
  - google-workspace
audience:
  - ai_product_manager
  - xiaohongshu_creator
stars: 25544
forks: 1313
primary_language: "Rust"
license: "Apache-2.0"
source_urls:
  - "https://github.com/googleworkspace/cli"
  - "https://api.github.com/repos/googleworkspace/cli"
  - "https://raw.githubusercontent.com/googleworkspace/cli/main/README.md"
  - "https://github.com/googleworkspace/cli/releases/tag/v0.22.5"
pm_value_score: 5
xiaohongshu_value_score: 4
product_opportunity_score: 5
confidence: high
last_checked: 2026-04-29T23:50:00+08:00
---

# googleworkspace/cli

## 稳定定位

googleworkspace/cli 是一个面向 Google Workspace 的统一命令行工具，覆盖 Drive、Gmail、Calendar、Sheets、Docs、Chat、Admin 等能力，并强调结构化 JSON 输出和 agent skills。

## 原理解释

它不维护一份静态命令表，而是读取 Google Discovery Service 动态构建命令面。换句话说，Google Workspace 新增 API 方法时，CLI 理论上可以更快获得对应操作入口。对 agent 来说，结构化 JSON 输出比网页界面更稳定。

## 典型用例

- agent 自动列出 Drive 文件、创建 Sheet、发送 Chat 消息。
- 团队把 Workspace 操作变成可审计脚本。
- 用 agent skills 教 LLM 如何安全调用办公系统。

## 对 AI 产品经理的价值

这是“现有 SaaS 如何变成 agent-native 工具”的典型样本。PM 可以观察它如何处理认证、scope、结构化输出、schema introspection 和 dry-run。

## 对小红书账号的价值

适合做“AI 如何自动化办公”的内容：整理 Drive 文件、写日程、更新表格、生成资料库。对文科生来说，办公自动化比开发自动化更接近日常需求。

## 产品化机会

做“AI 办公自动化中文模板库”：把 Workspace API 封装成中文任务，例如“把本周收藏文章整理成选题表”“把求职公司放入跟进 Sheet”“自动生成学习日历”。

## 风险与限制

README 明确说明这不是官方支持的 Google 产品。实际使用还依赖 Google Cloud 项目、OAuth 配置和 scope 管理，普通用户上手门槛较高。
