# Hot Cache — 会话热缓存

> 每次会话开头静默读取。~500 词。会话后或"收工"时更新（覆盖非追加）。

## Current Focus

知识库刚初始化（2026-07-07）。骨架已就绪：16 个集群、~100 个概念页占位（状态 TODO）。等待首次 ingest 填充内容。

## Open Questions

- 首份 ingest 内容选择：建议从考纲 PDF 或真题分析报告开始
- Phase 0 测度论学习的教材笔记将是第一批大量 ingest 的内容

## Recent Decisions

- 采用独立 kb-wiki 实例（与物理/数学 kb-wiki 隔离），未来可合并
- 16 个集群对应 YPS-LIF 学习计划的 16 个模块
- 概念页 frontmatter 新增 `exam_years` 和 `difficulty` 字段（相比原版 kb-wiki 的定制）

## Last Operations

- 2026-07-07: 初始化知识库（AGENTS.md, index.md, log.md, overview.md, hot.md, templates/）

## Active Pages

- [[index]] — 主目录
- [[overview]] — 集群导航
- AGENTS.md — 生产规范
