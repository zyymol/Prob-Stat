---
type: concept
title: "指数分布"
aliases: [Exponential distribution, Exp]
sources: []
related: [[gamma-distribution]], [[geometric-distribution]]
created: 2026-07-08
updated: 2026-07-08
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012, 2014, 2019]
difficulty: 2
contradictions: []
open_questions: []
---

# 指数分布

## 我的理解

指数分布 Exp($\lambda$) 是连续型中**唯一**有无记忆性的分布。$\lambda$ 是率参数（rate），$f(x)=\lambda e^{-\lambda x}, x>0$。

**关键：均值和率参数的关系**——$E[X]=\frac{1}{\lambda}$，$\text{Var}(X)=\frac{1}{\lambda^2}$。$\lambda$ 越大 → 衰减越快 → 均值越小。

## 核心要点

1. $\lambda$ = rate，不是 mean！
2. $E[X] = 1/\lambda$（率的倒数）
3. $\text{Var}(X) = 1/\lambda^2$
4. $F(x) = 1 - e^{-\lambda x}$（记住 CDF 就不用背 PDF）
5. Exp($\lambda$) = Gamma(1, $\lambda$)

## 常见错误

> $f(x)=3e^{-3x}$ → Exp(3)，$E[X] \neq 3$，$E[X] = 1/3$。率和均值互为倒数，容易搞反——今天的坑。
