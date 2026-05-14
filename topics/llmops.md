---
type: topic_index
date: 2026-05-14
repo: null
owner: null
name: "LLMOps"
url: "https://github.com/JASONLOO-HUB/github-daily-brief-db/blob/main/topics/llmops.md"
signal_type: aggregate
tags:
  - llmops
  - inference
  - observability
audience:
  - ai_product_manager
stars: null
forks: null
primary_language: null
license: null
source_urls:
  - "https://github.com/vllm-project/vllm"
  - "https://github.com/langgenius/dify"
  - "https://github.com/jundot/omlx"
  - "https://github.com/Continuum-AI-Corp/OrcaRouter-Lite"
  - "https://github.com/future-agi/future-agi"
pm_value_score: 5
xiaohongshu_value_score: 4
product_opportunity_score: 5
confidence: medium
last_checked: 2026-05-14T18:30:00+08:00
---

# LLMOps

## 关联项目

- [vllm-project/vllm](../projects/vllm-project__vllm/index.md)
- [langgenius/dify](../projects/langgenius__dify/index.md)
- [jundot/omlx](../projects/jundot__omlx/index.md)
- [Continuum-AI-Corp/OrcaRouter-Lite](../projects/Continuum-AI-Corp__OrcaRouter-Lite/index.md)
- [future-agi/future-agi](../projects/future-agi__future-agi/index.md)

## 产品观察

LLMOps 是 AI 产品从 demo 到生产的中后台能力：模型部署、推理成本、日志观测、权限、评测、回滚、协作。PM 不必成为 infra 工程师，但要能把这些能力转成需求、指标和上线风险清单。

2026-05-11 新增 omlx，适合作为“本地推理服务”的入门案例：用户看到的是聊天或 Agent，产品底层仍需要模型加载、接口服务、延迟控制和硬件限制说明。

2026-05-14 新增 OrcaRouter-Lite 和 future-agi，说明 LLMOps 的关注点继续向“多模型路由 + 质量评测”扩展。应用能调用模型只是第一步，后面还要管成本、失败率、prompt 版本和输出质量。

## 小红书切入

- “AI 产品经理不写模型，但要懂模型上线之后会遇到什么问题。”
- “从 Dify 和 vLLM 看 AI 应用为什么不能只靠一个 prompt。”
- “本地大模型不是玄学，背后是模型服务、硬件资源和隐私取舍。”
- “AI 产品上线后，要同时看成本、失败率和回答质量。”
