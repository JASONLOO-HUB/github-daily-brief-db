---
type: project_profile
date: 2026-05-03
repo: "HKUDS/nanobot"
owner: "HKUDS"
name: "nanobot"
url: "https://github.com/HKUDS/nanobot"
signal_type: new_hot
tags:
  - ai-agent
  - mcp
  - browser-automation
  - sandbox
audience:
  - ai_product_manager
  - xiaohongshu_creator
stars: 40000
forks: 7000
primary_language: "Python"
license: "Apache-2.0"
source_urls:
  - "https://github.com/HKUDS/nanobot"
  - "https://github.com/browser-use/browser-use"
  - "https://modelcontextprotocol.io/"
pm_value_score: 5
xiaohongshu_value_score: 4
product_opportunity_score: 5
confidence: medium
last_checked: 2026-05-03T11:16:18+08:00
---

# HKUDS/nanobot

## 稳定定位

Nanobot 是一个轻量级 agent harness，README 强调用少量命令启动 agent，并把 MCP、ACP、A2A、Browser Use、Sandbox 等工具和协议接到同一个执行框架里。

## 原理解释（面向非工程背景）

Agent 不是只有“大脑”，还需要“手”和“工作台”。Nanobot 扮演的是工作台：它负责把模型、工具协议、浏览器控制、代码执行和多 agent 通信接起来。用户不用每次从零搭积木，而是在一个较轻的壳里配置 agent 能用哪些工具、去哪里执行任务。

## 典型用例

- 快速做一个会浏览网页、调用工具、写文件或跑脚本的 agent demo。
- 给产品原型接入 MCP 工具，验证“AI 调工具完成任务”的流程。
- 做多 agent 协作或浏览器自动化的教学案例。

## 对 AI 产品经理的价值

Nanobot 适合观察 agent 产品的基础模块：模型选择、工具接入、执行环境、协议兼容、任务日志。PM 可以把这些拆成 PRD 里的“可配置能力”和“安全边界”。

## 对小红书账号的价值

适合用“AI 不只是聊天，它还要有工具箱”来讲。可以用餐厅比喻：模型是厨师，MCP 是接口菜单，Browser Use 是跑腿，Sandbox 是厨房安全区，Nanobot 是把这些安排到一起的店长。

## 产品化机会

MVP：做一个“Agent 工具协议可视化地图”，把 MCP、ACP、A2A、Browser Use、Sandbox 用中文解释并配开源项目入口。
目标用户：AI 产品经理、AI 课程讲师、准备转 agent 岗位的学习者。
差异化：不是只列协议名，而是按真实任务展示“什么时候需要它”。
风险：协议生态变化快，部分能力可能还停留在 demo 阶段。

## 风险与限制

轻量框架降低了 demo 成本，但生产环境仍要考虑认证、权限、日志、失败恢复和第三方工具稳定性。
