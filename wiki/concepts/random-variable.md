---
type: concept
title: "随机变量"
aliases: [random variable, RV]
sources: []
related: [[probability-space]], [[cdf-and-pdf]], [[measurable-function]]
created: 2026-07-08
updated: 2026-07-08
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: []
difficulty: 2
contradictions: []
open_questions:
  - "X的可测性在第3周测度论中严格定义"
---

# 随机变量

## 我的理解

随机变量 $X: \Omega \to \mathbb{R}$ 是一个确定性的函数，把样本空间中的结果映射为实数。随机性来自 $\omega \in \Omega$ 的随机选择，$X$ 本身不随机。

例：掷两枚硬币，$\Omega = \{HH, HT, TH, TT\}$，定义 $X =$ "正面朝上的次数"。$X(HH)=2, X(HT)=1, X(TH)=1, X(TT)=0$。

## 核心要点

1. 随机变量 = 从样本空间到实数的映射（确定性函数）
2. 有了 RV 后，概率的讨论从 $\Omega$ 转移到 $\mathbb{R}$ 上
3. 测度论视角（预告）：随机变量 = 可测函数
