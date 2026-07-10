---
type: concept
title: "分布函数法"
aliases: [CDF method, 求g(X)的分布]
sources: []
related: [[cdf-and-pdf]], [[random-variable]]
created: 2026-07-08
updated: 2026-07-08
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012, 2014]
difficulty: 2
contradictions: []
open_questions: []
---

# 分布函数法

## 我的理解

已知 X 的分布，求 Y = g(X) 的分布。分布函数法是万能方法（不要求 g 一一对应）：
1. $F_Y(y) = P(Y \le y) = P(g(X) \le y)$
2. 解不等式得到 X 的范围
3. 用 X 的 CDF/PDF 表达

例：X ~ U(0,1)，Y = -ln X → $F_Y(y) = P(X \ge e^{-y}) = 1-e^{-y}$ → Y ~ Exp(1)。

## 核心要点

1. 比直接套密度变换公式更通用
2. 关键是解不等式 $g(X) \le y$ 得到 X 的取值范围
3. 最后求导得到 $f_Y(y)$

## 常见错误

> 求导 $F_Y(y)$ 时忘记链式法则。如 $F_Y(y) = 1 - e^{-\sqrt{y}}$，求导时 $\frac{d}{dy}(-\sqrt{y}) = -\frac{1}{2\sqrt{y}}$ 不能漏。漏了导致后续 $E[Y]$ 也算错——今天踩的坑。

> $E[g(X)]$ 有时不需要对 Y 硬积：$E[Y] = E[X^2] = \text{Var}(X) + (E[X])^2$ 更快。X ~ Exp(1) 时 $E[X]=\text{Var}(X)=1$，所以 $E[X^2]=2$。养成"先看能否用已知矩简化"的习惯。
