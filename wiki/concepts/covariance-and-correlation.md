---
type: concept
title: "协方差与相关系数"
aliases: [Cov, correlation, ρ, Cov(X,Y)]
sources: []
related: [[random-variable]], [[jacobian-method]], [[independence-vs-uncorrelated]]
created: 2026-07-09
updated: 2026-07-09
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012, 2014, 2015]
difficulty: 2
contradictions: []
open_questions: []
---

# 协方差与相关系数

## 我的理解

协方差度量两个随机变量的**线性**关联：Cov(X,Y)=E[XY]-E[X]E[Y]。相关系数 ρ 是归一化版（[-1,1]）。

双线性性：Cov(aX+b, cY+d)=ac·Cov(X,Y)。Var(X+Y)=VarX+VarY+2Cov——这个公式在算和方差时常用。

## 核心要点

1. ρ = Cov/(σ_X σ_Y)，-1 ≤ ρ ≤ 1
2. ρ=±1 ⇔ Y=aX+b（完全线性相关）
3. 独立 ⇒ 不相关，但反向不成立（见[[independence-vs-uncorrelated]]）
4. 多元正态下两者等价

## 常见错误

无（Day 4 题1 协方差和 ρ 计算正确）
