---
type: concept
title: "雅可比变换法"
aliases: [Jacobian method, 变量变换法]
sources: []
related: [[distribution-function-method]], [[beta-distribution]], [[gamma-distribution]]
created: 2026-07-09
updated: 2026-07-09
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012, 2014, 2015]
difficulty: 3
contradictions: []
open_questions: []
---

# 雅可比变换法

## 我的理解

雅可比变换法是求 $(U,V) = g(X,Y)$ 联合分布的系统方法。核心公式：$f_{U,V}(u,v) = f_{X,Y}(x,y) \cdot |J|$，其中 J 是逆变换的雅可比行列式。

四步法：1) 检查一一对应 → 2) 求逆变换 → 3) 算 J → 4) 代入。推导了 Beta-Gamma 关系（$S=X+Y$, $T=X/(X+Y)$, $J=s$ → 分解出 Gamma(s)×Beta(t)），亲眼看见 PDF 分解过程。

X,Y 不需要独立——雅可比法是通用工具。独立只是方便代入后分解。一维退化版即 $\left|\frac{d}{dy}g^{-1}(y)\right|$。

## 核心要点

1. $f_{U,V}=f_{X,Y}(x(u,v), y(u,v)) \cdot |\det J|$
2. $J = \partial(x,y)/\partial(u,v)$，对**逆**变换求偏导
3. 必须在支撑集上一一映射（否则分块）
4. 来源：茆 §3.3（第151页）

## 证明模式

Beta-Gamma 关系完整推导：独立 $X\sim\text{Gamma}(\alpha,\beta), Y\sim\text{Gamma}(\gamma,\beta)$。令 $S=X+Y, T=X/(X+Y)$。逆变换 $X=ST, Y=S(1-T)$, $|J|=s$。代入 → $f_{S,T}=f_{\text{Gamma}(\alpha+\gamma,\beta)}(s) \cdot f_{\text{Beta}(\alpha,\gamma)}(t)$ → $S\perp T$。

## 常见错误

无（Day 4 练习全对，雅可比 J 计算和因式分解都正确）
