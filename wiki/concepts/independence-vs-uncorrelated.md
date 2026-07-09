---
type: concept
title: "独立与不相关"
aliases: [independence vs uncorrelated, ρ=0≠独立]
sources: []
related: [[covariance-and-correlation]], [[multivariate-normal]]
created: 2026-07-09
updated: 2026-07-09
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012, 2014]
difficulty: 2
contradictions: []
open_questions: []
---

# 独立与不相关

## 我的理解

独立（$f_{X,Y}=f_X f_Y$）⇒ ρ=0 永远成立。但 ρ=0 推不出独立——相关系数只捕捉线性关系。

**标准反例**：$X\sim N(0,1), Y=X^2$。$E[X]=E[X^3]=0$，所以 Cov(X,Y)=0（ρ=0），但 Y 显然由 X 决定。二次关系在相关系数中不可见。

**唯一等价情形**：多元正态分布。$(X,Y)\sim$二元正态时，ρ=0 ⇔ X⟂Y。

**丘赛考点**：2014 P1 考 Stein 恒等式与正态刻画；2012 P5 考对称密度下 X 与 |X| 不相关但不独立。

## 常见错误

无（Day 4 题1(c) 正确判断不独立，ρ=1/2≠0 验证了相关性）
