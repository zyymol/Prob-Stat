---
type: concept
title: "协方差矩阵"
aliases: [covariance matrix, Σ]
sources: []
related: [[covariance-and-correlation]], [[multivariate-normal]]
created: 2026-07-10
updated: 2026-07-10
confidence: high
cluster: distribution-theory
cluster_role: member
exam_years: [2012, 2015]
difficulty: 2
contradictions: []
open_questions: []
---

# 协方差矩阵

## 我的理解

随机向量 X = (X1,...,Xn) 的协方差矩阵 Σ，第(i,j)元 = Cov(Xi,Xj)。对角 = Var —— 本质是"方差-协方差"的成对表格。

**Σ vs ρ 矩阵**：Σ 是计算中枢（变换公式干净、正态天然参数、保留全部偏相关信息），ρ 是解读工具（归一化到 [-1,1]）。实际用法：先算 Σ，最后转 ρ 展示。

## 核心要点

1. 对称半正定：a^T Σ a = Var(a^T X) >= 0 —— 本质是"方差非负"
2. 线性变换：Cov(AX+b) = A Σ A^T —— 可由 Cov 双线性性直接导出
3. 多元正态：Σ_ij = 0 ⇔ X_i ⟂ X_j（不相关即独立仅对正态成立）

## 证明模式

线性变换规则最简证明（双线性法）：
Cov(AX+b)_{ij} = Cov(Σ_k A_{ik}X_k + b_i, Σ_l A_{jl}X_l + b_j)
= Σ_{k,l} A_{ik} A_{jl} Cov(X_k, X_l) （双线性 + 常数不影响）
= [A Σ A^T]_{ij}

## 常见错误

无（Day 5 题3 Σ 计算和线性变换规则应用正确）
