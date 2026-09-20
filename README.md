# fengjunqi / 中县干部分析技能

**English**  
`fengjunqi` is a unified agent skill for analyzing Feng Junqi's dissertation *Zhongxian Cadres*（《中县干部》）. It routes a question to one of ten internal modules and consults the relevant chapter knowledge when needed. The skill supports county cadre career analysis, entry and first-job pathways, elite clusters, cadre incubators, performance regimes, genuine-versus-false performance review, relation-rule interaction, institutional adaptation, discipline-risk mapping, and county political research methods.

**中文**  
`fengjunqi` 是一个用于分析冯军旗《中县干部》的统一 Agent 技能。它会根据问题自动路由到 10 个内部模块之一，并按需读取相关章节知识。适用于县域干部生涯分析、进入与初职路径、精英集群、干部摇篮、政绩体制、真伪政绩审查、关系—规则互动、制度适应、纪律风险映射以及县域政治研究方法。

---

## Modules / 模块

| Module / 模块 | Purpose / 用途 |
|---|---|
| [`county-political-research-method`](modules/county-political-research-method.md) | Research design, samples, career coding, interviews, and evidence triangulation. / 研究设计、样本、履历编码、访谈与多源互证。 |
| [`cadre-career-trajectory-decoder`](modules/cadre-career-trajectory-decoder.md) | Decode promotion sequences, hidden steps, timing, and party-government rotation. / 解码晋升序列、隐性台阶、时间窗口与政—党螺旋。 |
| [`entry-first-job-path-analyzer`](modules/entry-first-job-path-analyzer.md) | Analyze entry channels, first posts, education, matching, and re-screening. / 分析进入渠道、初职、教育专业匹配与再筛选。 |
| [`elite-cluster-analyzer`](modules/elite-cluster-analyzer.md) | Explain why particular places or networks repeatedly produce cadres. / 解释特定地域、学校或网络持续产出干部的机制。 |
| [`cadre-incubator-audit`](modules/cadre-incubator-audit.md) | Audit key institutions, posts, screening, training, and output. / 审计关键机构、关键岗位、筛入、历练与输出。 |
| [`performance-regime-diagnostic`](modules/performance-regime-diagnostic.md) | Diagnose targets, rankings, rewards, promotion competition, and isomorphism. / 诊断目标考核、排名奖惩、晋升竞赛与政绩同构。 |
| [`genuine-performance-audit`](modules/genuine-performance-audit.md) | Review whether achievements are durable, useful, costly, or performative. / 审查政绩是否可持续、有效、成本合理或流于形式。 |
| [`relation-rule-dual-loop-diagnostic`](modules/relation-rule-dual-loop-diagnostic.md) | Analyze formal rules and informal relations together. / 分析正式规则与非正式关系的双环互动。 |
| [`institutional-adaptation-audit`](modules/institutional-adaptation-audit.md) | Study unintended consequences and strategic adaptation to institutions. / 研究制度异化、策略适应与二阶后果。 |
| [`discipline-risk-mapper`](modules/discipline-risk-mapper.md) | Map power, discretion, resources, supervision, records, and accountability risk. / 映射权力、裁量、资源、监督、留痕与问责风险。 |

---

## Repository layout / 仓库结构

```text
SKILL.md                  Router and safety rules / 总路由与安全规则
modules/                  Ten executable analysis modules / 十个可执行分析模块
knowledge/chapters/       Chapter knowledge base / 章节知识库
references/               Glossary, patterns, cheatsheet, source map / 术语、模式、速查与源本对齐
tests/                    Router and safety test cases / 路由与安全测试
```

---

## Usage / 使用方式

**English**  
Invoke `fengjunqi` and ask a question such as: “How should I analyze this cadre's career trajectory?” or “Why did target assessments create new strategic behavior?” The router selects the most relevant module and reads only the needed chapter.

**中文**  
调用 `fengjunqi` 后，直接提出问题，例如：“如何分析这份干部履历？”或“目标考核为什么诱发新的策略行为？”系统会自动选择最相关模块，并只读取必要章节。

---

## Safety and limits / 安全与边界

**English**  
This skill is for historical, sociological, governance, and research analysis. It does not predict an individual's promotion or discipline outcome, provide vote canvassing or relationship-building tactics, help evade oversight, replace current legal or party-regulation advice, or expose private individuals and family networks.

**中文**  
本技能用于历史、社会学、治理和研究分析。它不预测具体个人晋升或纪律后果，不提供拉票、送礼、关系运作方法，不协助规避监督，不替代现行法律或纪律规定意见，也不用于识别或曝光私人个体与家族网络。

---

## Source / 来源

Based on Feng Junqi's 2010 dissertation *Zhongxian Cadres* / 基于冯军旗 2010 年论文《中县干部》。  
This repository contains structured analytical notes and skill files, not the full source text. / 仓库只包含结构化分析笔记和技能文件，不包含全书原文。
