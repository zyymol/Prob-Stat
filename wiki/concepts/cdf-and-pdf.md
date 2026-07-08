---
type: concept
title: "CDF与PDF"
aliases: [分布函数, 概率密度函数, F(x), f(x), CDF, PDF, cumulative distribution function]
sources: []
related: [[random-variable]], [[distribution-function-method]], [[normal-distribution]]
created: 2026-07-08
updated: 2026-07-08
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: []
difficulty: 2
contradictions: []
open_questions: []
---

# CDF 与 PDF

## 我的理解

- **CDF $F(x) = P(X \le x)$**：分布函数，累积概率——真实的概率值。一切随机变量都有 CDF。
- **PDF $f(x)$**：概率密度函数——连续型的密度，$f(x)$ 本身不是概率，$f(x)dx$ 才是近似概率。只有连续型有 PDF。
- 关系：$F(x) = \int_{-\infty}^x f(t)dt$，$f(x) = F'(x)$。

**区分记忆**：f = density（密度），F = cumulative（累积）。工科教材"分布函数"通常指 F(x)，"概率密度函数"指 f(x)。

## 核心要点

1. CDF 三条性质：单调不降、右连续、$\lim_{x\to -\infty}F(x)=0$, $\lim_{x\to \infty}F(x)=1$
2. 离散型：PMF（概率质量），$F$ 是阶梯函数
3. 连续型：PDF（密度），单点概率 = 0 但事件并非不可能——因为 $\Omega$ 不可数

## 常见错误

无（理解正确，今天练习中 F 和 f 互求全对）
