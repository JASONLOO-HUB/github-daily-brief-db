---
type: project_profile
date: 2026-05-07
repo: "VectifyAI/PageIndex"
owner: "VectifyAI"
name: "PageIndex"
url: "https://github.com/VectifyAI/PageIndex"
signal_type: new_hot
tags:
  - rag
  - document-ai
  - knowledge-management
  - devtools
audience:
  - ai_product_manager
  - xiaohongshu_creator
  - chinese_liberal_arts_ai_learners
stars: 28700
forks: 2000
primary_language: "TypeScript"
license: "MIT"
source_urls:
  - "https://github.com/VectifyAI/PageIndex"
  - "https://trendshift.io/repositories/13577"
pm_value_score: 5
xiaohongshu_value_score: 5
product_opportunity_score: 5
confidence: medium
last_checked: 2026-05-07T11:09:38+08:00
---

# VectifyAI/PageIndex

## 稳定定位

PageIndex 是一个面向长文档、表格和复杂版面的 reasoning-based RAG 工具，目标是让 AI 在回答时能更稳定地定位文档结构和证据，而不是只依赖普通向量相似度。

## 原理解释

普通 RAG 像把一本书切成很多便签，再让 AI 找最像问题的便签。问题是合同、论文、财报和表格经常依赖章节、页码、表头、引用关系。PageIndex 的思路是先把文档整理成更适合推理的索引，让模型知道“信息在哪里、属于什么结构、和哪些内容有关”。

## 典型用例

- 企业把 PDF、手册、财报、合同做成可追溯问答库。
- AI 产品经理评估 RAG 产品时，用它观察文档解析、索引和证据引用体验。
- 教育账号把论文、白皮书、课程资料变成结构化学习卡片。

## 对 AI 产品经理的价值

它提醒 PM：RAG 的壁垒不只是“接入向量数据库”，而是文档结构理解、证据定位、引用展示和错误可追溯。可借鉴的产品点包括：高亮原文、章节树、回答证据面板、表格问答、低置信度提示。

## 对小红书账号的价值

适合讲“AI 为什么读 PDF 经常胡说”。面向文科生可以用“读书笔记”类比：先做目录和索引，再写摘要，才不容易漏掉上下文。

## 产品化机会

MVP：中文资料库问答模板，面向考研/转行/产品学习者，上传报告后自动生成目录、术语卡、问答、引用来源和 60 秒讲解稿。
目标用户：AI 学习者、知识博主、研究助理。
差异化：强调证据定位和可复盘，而不是只给结论。

## 风险与限制

项目处于高热传播期，实际效果仍取决于文档类型、OCR/解析质量、模型能力和部署成本。涉及企业文档时还要处理隐私和权限控制。
