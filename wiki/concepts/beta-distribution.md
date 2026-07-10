---
type: concept
title: "Beta分布"
aliases: [Beta distribution]
sources: []
related: [[gamma-distribution]], [[uniform-distribution]], [[jacobian-method]]
created: 2026-07-08
updated: 2026-07-09
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012]
difficulty: 2
contradictions: []
open_questions:
  - "Beta 的直觉——为什么是'概率的概率'？（下周贝叶斯讲）"
---

# Beta 分布

## 我的理解

Beta($\alpha, \beta$) 定义在 $[0,1]$ 上。会用 Beta-Gamma 关系：独立 $X \sim$ Gamma($\alpha,\beta$), $Y \sim$ Gamma($\gamma,\beta$) → $\frac{X}{X+Y} \sim$ Beta($\alpha,\gamma$)。

还不完全理解 Beta 的直觉——为什么它在 $[0,1]$ 上是"概率的概率"？等下周贝叶斯讲共轭先验时会更清楚。

## 核心要点

1. $E[X] = \frac{\alpha}{\alpha+\beta}$
2. PDF 常数：$1/B(\alpha,\beta)$，$B(\alpha,\beta) = \frac{\Gamma(\alpha)\Gamma(\beta)}{\Gamma(\alpha+\beta)}$
3. 特例：Beta(1,1) = Uniform(0,1)
4. **Beta-Gamma 关系**：Gamma 商 = Beta

## 常见错误

无（计算正确，但需要明天雅可比变换法看推导）
