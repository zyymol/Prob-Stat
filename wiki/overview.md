# 丘赛概率统计备考知识库 — 概览

## 备考目标

- **竞赛**：丘成桐大学生数学竞赛，概率统计方向
- **考试时间**：2027年春季或秋季
- **背景**：工科，无测度论基础，尚未开始系统学习
- **可用周期**：约32周核心计划（Phase 0-5）
- **每日学时**：5小时（0.5h回顾 + 1.5h精读 + 2h刷题 + 0.5h对答案 + 0.5h整理）

## 知识库集群

本知识库围绕 16 个知识集群组织，对应 YPS-LIF 学习计划的模块划分：

### 考纲内集群（Phase 0-2 攻坚）

| 集群 | 学习阶段 | Hub | 概念页数 |
|------|---------|-----|---------|
| measure-theory | Phase 0 (第1-4周) | [[measure-theory-foundations]] | 8 |
| convergence | Phase 1 (第5周) | [[convergence-modes]] | 7 |
| characteristic-functions | Phase 1 (第6周) | [[characteristic-function]] | 5 |
| conditional-expectation | Phase 0 (第3周) | [[conditional-expectation]] | 4 |
| martingale | Phase 1 (第8-9周) | [[martingale-theory]] | 8 |
| stochastic-processes | Phase 1 (第10周) | [[stochastic-processes]] | 7 |
| distribution-theory | Phase 2 (第16周) | [[distribution-families]] | 10 |
| estimation | Phase 2 (第11-13周) | [[estimation-theory]] | 10 |
| hypothesis-testing | Phase 2 (第14周) | [[hypothesis-testing]] | 7 |
| bayesian-statistics | Phase 2 (第15周) | [[bayesian-statistics]] | 5 |

### 超纲拓展集群（Phase 3 攻坚）

| 集群 | 学习阶段 | Hub | 概念页数 |
|------|---------|-----|---------|
| asymptotic-statistics | Phase 3 (第18-19周) | [[asymptotic-statistics]] | 9 |
| decision-theory | Phase 3 (第17周) | [[decision-theory]] | 7 |
| coupling-transport | Phase 3 (第20周) | [[coupling-and-tv-distance]] | 5 |
| nonparametric-bayes | Phase 3 (第21周) | [[dirichlet-process]] | 4 |
| random-graphs-matrices | Phase 3 (第22周) | [[random-graphs-and-matrices]] | 6 |
| causal-inference | Phase 3-4 (穿插) | [[causal-inference-rubin]] | 5 |

## 真题覆盖

真题覆盖 2010-2023 年（缺 2011），共 13 年。高频考点（按出现次数降序）：

1. 概率收敛与极限定理 — 几乎每年
2. Markov链 — 2017/2019/2020/2021/2022
3. 随机游走 — 2016/2017/2018/2020
4. 正态分布与多元正态 — 2012/2014/2015/2018/2020
5. 参数估计(MLE/UMVUE) — 2012/2013/2014/2015/2017/2019/2023
6. 假设检验 — 2012/2013/2014/2015/2023
7. 因果推断 — 2019/2020/2021/2022（固定大题）
8. 随机图/随机矩阵 — 2016/2017/2019/2021

## 使用方式

- **学习时**：将教材笔记放入 `raw/notes/`，触发 ingest 编译进 wiki
- **做题时**：将真题做题记录放入 `raw/notes/`，ingest 后自动更新概念页的 `exam_years`
- **复习时**：直接查询 wiki，WorkBuddy 读取相关概念页综合回答
- **检查时**：运行 lint，发现盲区和薄弱点
- **可视化**：在 Obsidian 中打开本目录，用图谱视图查看知识网络
