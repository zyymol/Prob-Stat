# 丘成桐数学竞赛·概率统计方向备考知识库

> 备考丘成桐大学生数学竞赛（概率统计方向），2027年春季或秋季。
> 工科背景 → 测度论概率论 → 数理统计 → 真题冲刺。

## 这是什么

一个基于 **YPS-LIF 学习迭代框架** + **kb-wiki 知识库架构** 的系统化备考方案。

- **YPS-LIF**：借鉴 mattpocock/skills 仓库的工作流理念，为数学竞赛备考定制的学习迭代框架
- **kb-wiki**：借鉴 Karpathy LLM Wiki 范式，用 WorkBuddy + Obsidian + git 搭建的"会生长的个人知识库"

核心设计：**wiki 存储的不是教材知识，而是用户的学习状态**——理解程度、常见错误、证明模式、掌握进度。

## 目录结构

```
├── 丘赛概率统计备考_学习框架与计划.md   ← 33周总计划（6阶段）
├── AGENTS.md                            ← kb-wiki 生产规范
├── README.md                            ← 本文件
├── raw/                                 ← 用户学习笔记（ingest 输入）
│   ├── notes/                           每日笔记
│   ├── papers/                          教材/真题 PDF
│   └── articles/                        参考文章
├── wiki/                                ← AI 维护的知识库
│   ├── concepts/                        概念页（用户学习状态）
│   ├── syntheses/                       证明模式库
│   ├── index.md                         16集群主目录
│   ├── hot.md                           会话热缓存
│   └── log.md                           活动日志
├── templates/                           ← 页面模板
└── yau-contest/                         ← 官方考纲 + 真题（2010-2023）
```

## 学习迭代框架（YPS-LIF）

### 6 个阶段（33周）

| 阶段 | 周数 | 内容 |
|------|------|------|
| Phase 0 | 第1-5周 | 工科概统复习 + 测度论地基 |
| Phase 1 | 第6-11周 | 概率论（Durrett：收敛/条件期望/鞅/随机过程） |
| Phase 2 | 第12-17周 | 统计推断（C&B：估计/检验/贝叶斯） |
| Phase 3 | 第18-23周 | 超纲攻坚（决策论/渐近统计/耦合/Dirichlet/随机图） |
| Phase 4 | 第24-29周 | 真题冲刺（2012-2023全部真题） |
| Phase 5 | 第30-33周 | 查漏补缺 + 全真模拟 |

### 每日循环（学习期）

| 阶段 | AI 角色 | 用户行为 |
|------|---------|----------|
| D-Recall (0.5h) | 复习教练（间隔重复推送） | 回顾 |
| D-Study (1-1.5h) | 教师（讲解→确认→出题） | 听讲+确认 |
| D-Practice (1.5-2.5h) | 沉默 | 独立做题 |
| D-Verify (0.5h) | 阅卷官（批改+消化时间） | 理解错误 |
| D-Refactor (0.5h) | 编译器（ingest） | 写笔记→更新wiki |

### 每周循环

- **周六 W-Review**：AI 运行 lint，报告学习状态
- **周日 W-Plan**：AI 制定下周每日具体内容，用户确认

## 教材

| 梯队 | 教材 | 用法 |
|------|------|------|
| 主力 | 茆诗松《概率论与数理统计教程》 | 正文+习题全刷 |
| 主力 | Casella & Berger《Statistical Inference》 | 精读第6-8,10章 |
| 主力 | Durrett《Probability: Theory and Examples》 | 精读第2-6章 |
| 地基 | 程士宏《测度论与概率论基础》 | 前半部分 |
| 拓展 | van der Vaart《Asymptotic Statistics》 | 前5章 |
| 拓展 | Keener《Theoretical Statistics》 | 第6-7章 |

## 技术栈

- **WorkBuddy**：AI 助手（讲解/出题/批改/ingest）
- **Obsidian**：知识库可视化（图谱视图）
- **Git**：版本控制

## License

Personal use only.
