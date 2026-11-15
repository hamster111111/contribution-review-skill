# 可核验的写法入口

以下是检索起点，不是评分锚点、固定模板或应得分答案。每次按当前年份滚动筛选和补充新来源，不按本页排列顺序或缓存建立年份固定选例；相关性与质量相当时先选更近年份。例如核对日2026-11-15可先查2026／2025，再扩2024；2024经典可按具体用途补充。按本稿关键意见选相关实例并打开原文；不用全部引用，也继续接受更合适的新来源。待评稿就是下列论文时，跳过该条评分／荣誉背景，改选别篇。

正面核心范例应核验为顶会主会正式录用；写法可比、质量相近时优先知名企业／Lab／高校团队。以下新增的机构记录核对于2026-11-15，依据是发表稿署名，非作者当前雇主；其余条目未列机构时不自行补猜。具体作者与来源见[机构核验记录](affiliation-evidence.json)。

## 反馈对象：OpenAI 的主会范例

**Let’s Verify Step by Step，ICLR 2024主会；发表稿署名OpenAI。** [正式论文§1，PDF第1–2页](https://proceedings.iclr.cc/paper_files/paper/2024/file/aca97732e30bcf1303bc22ac3924fd16-Paper-Conference.pdf)，[会议收录页](https://proceedings.iclr.cc/paper_files/paper/2024/hash/aca97732e30bcf1303bc22ac3924fd16-Abstract-Conference.html)。可借鉴的是将反馈对象从最终结果变到推理步骤后，增加了什么错误定位信息，并明确相对前人比较改变的模型、反馈量和任务范围。第1页作者区明确为OpenAI；此处未核验数值评分或奖项，不据机构推断高分。

## 用途变化：Scale AI 的主会范例

**Rubrics as Rewards: Reinforcement Learning Beyond Verifiable Domains，ICLR 2026主会；发表稿署名Scale AI。** [正式论文§1及Figure 1，PDF第1–2页](https://proceedings.iclr.cc/paper_files/paper/2026/file/cfd7bee7a651ee9af525098ef67a9e45-Paper-Conference.pdf)，[会议收录页](https://proceedings.iclr.cc/paper_files/paper/2026/hash/cfd7bee7a651ee9af525098ef67a9e45-Abstract-Conference.html)。先说明二元反馈的适用约束，再解释rubric从评估用途进入训练奖励的变化，最后串联实现。第1页另有工作在Scale AI期间完成的脚注，不推断所有作者当前仍在该公司；未核验数值评分或奖项。

## 解释性与理论贡献：条件跟着结论

**Self-Improvement in Language Models: The Sharpening Mechanism，ICLR 2025。** [正式论文§1.2，PDF第3–4页](https://proceedings.iclr.cc/paper_files/paper/2025/file/bee8c2bc757f6bbc3efd7cf1b979f0c9-Paper-Conference.pdf#page=3)。将自奖励目标与优化算法分开，解释查询资源、基础模型覆盖条件及两类优化结果的差别。可用于把“提出框架并证明有效”改为有对象、比较和条件的贡献，不必模仿其条目数量。

机构与轨道：第1页为Microsoft Research与UIUC、MIT、CMU作者的联合署名；[官方收录页](https://proceedings.iclr.cc/paper_files/paper/2025/hash/bee8c2bc757f6bbc3efd7cf1b979f0c9-Abstract-Conference.html)核验为ICLR 2025主会。不称微软独立工作，也不从学校名猜具体Lab。

评分背景：11月13日官方公开记录缓存的整篇 `rating` 为[8,8,8,8]，并非已核实初审向量。[公开评语入口](https://openreview.net/forum?id=WJaUkwci9o&noteId=oy7uHgdzV8)还显示该评审曾在rebuttal后升分。不能据此说这种写法导致8分。

## 概念诊断：连续段落也能连接贡献

**Training on the Test Task Confounds Evaluation and Emergence，ICLR 2025。** [正式论文§1.1，PDF第1–3页](https://proceedings.iclr.cc/paper_files/paper/2025/file/ab8c971c2ccd12bac0ab249f75e2c16d-Paper-Conference.pdf#page=2)。连续段落将混淆因素、模型比较、控制该因素的方法与对既有结论的影响连接起来。可用于帮助作者说明“改变了什么判断”，不能据此强求列表或固定三条。

评分背景：同日期官方公开记录缓存的整篇 `rating` 为[8,8,8,8]；不是贡献段落写作分。[官方评语入口](https://openreview.net/forum?id=jOmk0uS1hl&noteId=tcafCpvnbl)。

## 评价资源：规格说明新增可测能力

**BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions，ICLR 2025。** [正式论文摘要与§1，尤其PDF第3页末两段](https://proceedings.iclr.cc/paper_files/paper/2025/file/a6a90bcc2aa470c3871b2d39a67d26e8-Paper-Conference.pdf#page=3)。将多库调用、复杂指令、覆盖范围和提示场景对应到旧代码题缺少的评价能力。可借鉴的是规格为何有用，不是单纯堆任务数或模型成绩。

评分背景：同日期官方公开记录缓存的整篇 `rating` 为[10,8,8,10]。[官方评语入口](https://openreview.net/forum?id=YrycTjllL0&noteId=xdutvK24rW)。保留原量尺，不将其换成ARR分或给本稿设目标。

## 方法贡献：明确相对前作改变的操作

**Steering Llama 2 via Contrastive Activation Addition，ACL 2024主会长文。** [摘要、§1及§2，PDF第1–3页](https://aclanthology.org/2024.acl-long.828.pdf#page=2)。摘要说明对比样本的激活差怎样用于推理控制，§2再定位相对前作的操作差异。可用来解释为何“新增哪一步及有什么作用”优于只写“创新高效”；注意§2属于相关工作，不冒充贡献列表。

背景已于11月15日核验：[ACL官方奖项页](https://2024.aclweb.org/program/best_papers/)列为Outstanding Paper及SAC Award。**未核验公开ARR数值评分**，仅称获奖写法参照，不能说拿了5分。

## 日期与版本

上述正式论文原文均于2026-11-15核验；三篇ICLR发表稿与2026-11-13官方论坛缓存PDF的SHA-256一致。但每位评审实际看到的初始稿版本未重建，现有总分与发表稿不能作逐句因果配对。当前OpenReview页面受限时，不将11月13日缓存说成11月15日实时评分。

完整逐条公开评语链接、评分阶段及原文校验记录见[范例来源数据](exemplar-evidence.json)。当前量尺以[ARR评分说明](scoring.md)为准；ICLR旧分只作为实例背景，不参与本稿打分。
