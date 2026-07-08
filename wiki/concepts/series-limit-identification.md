---
type: concept
title: "级数极限辨识"
aliases: [series limit, 交错级数, n阶乘vs n]
sources: []
related: [[classical-probability]]
created: 2026-07-08
updated: 2026-07-08
confidence: medium
cluster: convergence
cluster_role: member
exam_years: []
difficulty: 3
contradictions: []
open_questions: []
---

# 级数极限辨识

## 我的理解

做错排概率时，$x_n = n! \sum_{k=0}^n (-1)^k/k!$，所以 $p_n = \sum (-1)^k/k! \to e^{-1}$。

**犯的错误**：把 $\sum (-1)^n/n!$ 当成了 $\sum (-1)^{n-1}/n$，后者的极限才是 $\ln 2$。

区分方法：
- $n!$ 在分母 → $e^{-1}$（来自 $e^x$ 的 Taylor 展开 $e^x = \sum x^n/n!$，代入 $x=-1$）
- $n$ 在分母 → $\ln 2$（来自 $\ln(1+x)$ 的 Taylor 展开，代入 $x=1$）

**防错策略**：用自己算的小 $n$ 数据验算——$p_4=9/24=0.375$ 已经接近 $0.368$，不可能接近 $0.693$。

## 常见错误

> 交错级数 Σ(-1)^n/n! 和 Σ(-1)^(n-1)/n 搞混——前者 = 1/e ≈ 0.368，后者 = ln2 ≈ 0.693。自算 p_4=0.375 应该是检测信号。
