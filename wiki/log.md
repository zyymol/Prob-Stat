# Wiki 活动日志

> 仅追加，永不删除条目。grep 技巧：`grep "^## \[" wiki/log.md | tail -5`

## [2026-07-10] ingest | 第1周周五：条件期望（工科版）+协方差矩阵

Source: raw/notes/1-5.txt
Phase: 0 Week 1 Day 5
Pages created: conditional-expectation-engineering, covariance-matrix
Confidence: 全部high，无错误
Tags: 塔性质, 条件方差分解, Σ vs ρ, Cov双线性性

---

## [2026-07-09] ingest | 第1周周四：多维RV+雅可比变换法+协方差

Source: raw/notes/1-4.txt
Phase: 0 Week 1 Day 4
Pages created: wiki/concepts/jacobian-method.md, wiki/concepts/covariance-and-correlation.md, wiki/concepts/independence-vs-uncorrelated.md
Pages updated: gamma-distribution(medium→high), beta-distribution(medium→high)
Confidence: jacobian=high, covariance=high, independence-vs-uncorrelated=high
Tags: 雅可比变换, Beta-Gamma关系推导, 协方差, 独立≠不相关

---

## [2026-07-08] ingest | 第1周周三：六大分布族

Source: raw/notes/1-3.txt
Phase: 0 Week 1 Day 3
Pages created: wiki/concepts/exponential-distribution.md, wiki/concepts/gamma-distribution.md, wiki/concepts/beta-distribution.md
Confidence: binomial=high, poisson=high, geometric=high, normal=high, exponential=medium (率vs均值), gamma=medium (直觉弱), beta=medium (直觉弱)
Common errors: Exp rate≠mean；E[S]² 系数检查遗漏
Tags: 工科复习, 六大分布, Gamma可加性, Beta-Gamma关系, 无记忆性

---

## [2026-07-08] ingest | 第1周周二：随机变量与分布函数

Source: raw/notes/1-2.txt
Phase: 0 Week 1 Day 2
Pages created: wiki/concepts/random-variable.md, wiki/concepts/cdf-and-pdf.md, wiki/concepts/distribution-function-method.md
Confidence: random-variable=high, cdf-and-pdf=high, distribution-function-method=medium
Common errors: 链式法则求导遗漏；E[g(X)] 忘记用已知矩简化
Tags: 工科复习, PDF vs CDF, 分布函数法, 链式法则

## [2026-07-08] ingest | 第1周周一：概率空间与基本概率计算

Source: raw/notes/practice note 1-1.txt
Phase: 0 Week 1 Day 1
Pages created: wiki/concepts/bayes-formula.md, wiki/concepts/probability-space.md, wiki/concepts/series-limit-identification.md
Confidence: bayes-formula=high, probability-space=high, series-limit-identification=medium
Tags: 工科复习, Bayes公式, 古典概型, 错排

## [2026-07-07] init | 丘赛概率统计备考知识库初始化

- 创建三层目录结构（raw/ wiki/ templates/）
- 编写 AGENTS.md v1（基于 kb-wiki 模板，定制概率统计备考领域）
- 初始化 wiki/index.md（16个集群，~100个概念页骨架）
- 初始化 wiki/log.md（本文件）
- 初始化 wiki/overview.md
- 初始化 wiki/hot.md
- 复制 5 类页面模板
- .gitignore 配置

Pages created: AGENTS.md, wiki/index.md, wiki/log.md, wiki/overview.md, wiki/hot.md, templates/{source,concept,entity,comparison,synthesis}.md, .gitignore
