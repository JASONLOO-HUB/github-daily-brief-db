---
type: project_profile
date: 2026-04-29
repo: "vercel-labs/agent-browser"
owner: "vercel-labs"
name: "agent-browser"
url: "https://github.com/vercel-labs/agent-browser"
signal_type: new_hot
tags:
  - browser-automation
  - ai-agent
  - cli
  - rust
audience:
  - ai_product_manager
  - xiaohongshu_creator
stars: 31011
forks: 1901
primary_language: "Rust"
license: "Apache-2.0"
source_urls:
  - "https://github.com/vercel-labs/agent-browser"
  - "https://api.github.com/repos/vercel-labs/agent-browser"
  - "https://raw.githubusercontent.com/vercel-labs/agent-browser/main/README.md"
  - "https://github.com/vercel-labs/agent-browser/releases/tag/v0.26.0"
pm_value_score: 4
xiaohongshu_value_score: 4
product_opportunity_score: 5
confidence: high
last_checked: 2026-04-29T23:50:00+08:00
---

# vercel-labs/agent-browser

## 稳定定位

agent-browser 是给 AI agent 使用浏览器的原生 Rust CLI。它提供打开网页、快照、点击、填写、截图、PDF、JS 执行等命令，让 agent 能操作真实网页。

## 原理解释

传统浏览器自动化通常面向工程师写脚本。agent-browser 把浏览器动作变成稳定的命令行接口，并提供 accessibility tree refs，例如 snapshot 后通过 `@e2` 这样的引用点击元素。这让 LLM 更容易“看见页面结构并执行动作”。

## 典型用例

- 让 agent 自动打开网页、读取内容、填写表单。
- 用截图和 accessibility tree 验证前端页面。
- 为非 API 化网站构建自动化流程。

## 对 AI 产品经理的价值

它说明 agent 产品的落地入口不一定是 API 集成，也可以是“模拟人操作浏览器”。PM 需要考虑：页面可观测性、元素选择稳定性、失败重试、用户授权和敏感操作确认。

## 对小红书账号的价值

适合讲“不会写代码也能理解的 AI 自动化”：AI 打开网页、看页面、点按钮、填表单。可以用求职、资料整理、选题收集做演示场景。

## 产品化机会

做一个“AI 浏览器任务模板库”：把常见网页任务封装成中文模板，如抓招聘岗位、保存课程资料、整理竞品网页、生成小红书选题表。

## 风险与限制

浏览器自动化容易遇到登录、验证码、隐私、页面变动和误操作问题。面向普通用户时，必须设计确认步骤和只读模式。
