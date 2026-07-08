---
type: concept
title: "Bayes公式"
aliases: [贝叶斯公式, Bayes theorem]
sources: []
related: [[conditional-probability]], [[law-of-total-probability]], [[conditional-expectation]]
created: 2026-07-08
updated: 2026-07-08
confidence: high
cluster: conditional-expectation
cluster_role: member
exam_years: [2018]
difficulty: 2
contradictions: []
open_questions: []
---

# Bayes公式

## 我的理解

Bayes公式是从"果"反推"因"的工具。整条链条：条件概率（定义）→ 乘法公式（变形）→ 全概率公式（拆成加权和）→ Bayes公式（反推）。

关键直觉：全概率是从因到果的加权分解（$P(A) = \sum P(A|B_i)P(B_i)$），Bayes是从果到因的反推（$P(B_k|A) = \frac{P(A|B_k)P(B_k)}{\sum P(A|B_i)P(B_i)}$）。

## 核心要点

1. 条件概率 $P(A|B) = P(A \cap B) / P(B)$ 是起点
2. 全概率公式需要一个划分 $\{B_i\}$
3. Bayes = 全概率的"逆运算"
4. 先验概率 $P(B_k)$ → 观测数据 A → 后验概率 $P(B_k|A)$

## 真题应用

- 2018年第1题：潜艇搜索 — Bayes后验更新（先在A区搜、没找到，更新B/C区概率）

## 常见错误

无（题2和题3全对，链式Bayes更新也正确处理）
