---
id: paper-explain-concept-readme
type: documentation
title: Paper Explain Concept 论文拆解助手
status: active
version: 1.0.0
created: 2026-10-28
updated: 2026-10-28
tags: [research, paper-reading, agent-skill]
---

# Paper Explain Concept：论文拆解助手

一个供 AI agent 使用的论文深度阅读工作流。它帮助研究者从论文中梳理问题、研究思路、方法、证据、贡献和局限，并用简洁的逻辑图呈现各部分之间的关系。

## 使用方法

将本仓库的 `SKILL.md` 提供给支持技能文件的 AI agent，再提供可访问的论文 PDF、全文或链接。例如：

> 请使用 paper-explain-concept 拆解这篇论文，说明研究问题、关键方法、结果证据和局限，并标注你实际读到的材料。

工作流可输出通俗解释、研究背景、问题与洞见、关键方法和结果、贡献对比、批判性边界及文字逻辑图。是否保存或同步结果由使用者决定。

## 使用边界

分析质量取决于实际获得的材料。只有摘要时，方法和结论的细节可能无法核实；工具不替代阅读原文，也不应编造引用、数据或图表。请回到原文核对重要判断。

该公开版本根据 `paper-explain-concept` 工作流整理，移除了个人本地路径和 Notion 数据库绑定，以便在不同环境中使用。

## English

An agent skill for evidence-bounded, structured reading of a research paper. Supply an accessible paper and `SKILL.md` to your agent. The workflow separates the problem, insight, methods, evidence, contribution and limitations, and marks gaps in the material actually read. It does not replace reading the original paper.
