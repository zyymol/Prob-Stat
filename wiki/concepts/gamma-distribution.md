---
type: concept
title: "Gamma分布"
aliases: [Gamma distribution]
sources: []
related: [[exponential-distribution]], [[beta-distribution]], [[chi-squared-distribution]]
created: 2026-07-08
updated: 2026-07-09
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2013, 2014, 2015]
difficulty: 2
contradictions: []
open_questions: []
---

# Gamma 分布

## 我的理解

Gamma($\alpha, \beta$) = 指数分布的"叠加版"。$\alpha$ 个独立 Exp($\beta$) 的和服从 Gamma($\alpha, \beta$)。$\alpha$ = shape（形状参数），$\beta$ = rate（率参数）。

会用可加性和亲属关系，但 $\alpha,\beta$ 的直觉（什么时候用 Gamma 而非 Exp？形状参数大意味着什么？）还需要加深。

## 核心要点

1. $E[X] = \alpha/\beta$，$\text{Var}(X) = \alpha/\beta^2$
2. **可加性**：同 $\beta$ 下形状参数相加
3. 特例：Gamma(1, $\beta$) = Exp($\beta$)；Gamma($k/2, 1/2$) = $\chi^2_k$

## 常见错误

无（计算正确，但需要加深直觉理解）
