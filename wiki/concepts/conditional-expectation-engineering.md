---
type: concept
title: "条件期望（工科版）"
aliases: [conditional expectation E[X|Y], 塔性质]
sources: []
related: [[conditional-expectation]], [[covariance-and-correlation]]
created: 2026-07-10
updated: 2026-07-10
confidence: high
cluster: conditional-expectation
cluster_role: member
exam_years: [2012, 2015]
difficulty: 2
contradictions: []
open_questions:
  - "三条性质的严格证明在第4周（测度论版条件期望）"
---

# 条件期望（工科版）

## 我的理解

E[X|Y=y] 是代入 y 后的具体数值，E[X|Y] 是 Y 的函数（随机变量）——这是准备第4周测度论版条件期望的核心视角。

塔性质 E[E[Y|X]] = E[Y] 是条件期望最基本的不变量——分组再平均等于直接平均。条件方差分解 Var(Y) = E[Var(Y|X)] + Var(E[Y|X]) 是泛恒等式（对任意 X,Y 成立，不依赖具体分布）。

## 核心要点

1. E[X|Y] 是 Y 的函数 = 随机变量
2. 塔性质：E[E[X|Y]] = E[X]（由定义直接证：∫[∫x f(x|y)dx] f_Y(y) dy = ∫∫x f(x,y) dxdy）
3. 条件方差分解：Var(Y) = E[Var(Y|X)] + Var(E[Y|X])，总方差=组内+组间
4. **可证**：塔性质→提出已知 → 条件方差分解，第4周测度论严格版

## 常见错误

无（Day 5 题1 塔性质验证和条件方差分解计算均正确）
