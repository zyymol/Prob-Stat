---
type: concept
title: "概率空间"
aliases: [probability space, (Ω,F,P), 三元组]
sources: []
related: [[sigma-algebra]], [[measurable-function]], [[bayes-formula]]
created: 2026-07-08
updated: 2026-07-08
confidence: high
cluster: measure-theory
cluster_role: member
exam_years: []
difficulty: 2
contradictions: []
open_questions:
  - "为什么 F 不能取全体子集？——待第2周测度论解答（Vitali 集构造）"
---

# 概率空间

## 我的理解

概率空间是给"概率"这件事建立的形式化框架。三元组 (Ω, F, P)：
- Ω：所有可能的结果（样本空间）。有限如掷骰子 {1..6}，连续如测电阻 [0,∞)
- F：可以赋概率的事件的集合。问了关键问题"为什么不是全体子集？"——有限情形可以取全体子集，不可数情形（如 [0,1]）有 Vitali 集矛盾，这是第2周要学的
- P：概率测度，满足非负性、归一性、可列可加性

## 核心要点

1. Ω 描述"哪些结果可能发生"
2. F 描述"哪些集合可以测概率"——不可数空间时严格小于全体子集
3. P 是可列可加的 [0,1] 值函数

## 常见错误

无（概念理解正确，关键问题已提出）

## 开放问题

- Vitali 集的具体构造（第2周解答）
- σ-代数的严格公理（第2周讲解）
