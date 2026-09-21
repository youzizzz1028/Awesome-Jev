# Awesome Jev

[English](README.md)

一个带证据分级的 Jev 与机器原生决策模型资源库，覆盖类型化概率接口、概率校准、选择性预测、受约束生成、决策导向学习与成本敏感路由。

![机器原生决策模型技术景观](assets/fig1_machine_native_landscape.png)

## 为什么建立这个仓库

TypeSafe 在“Machine-Native Intelligence”总体叙事下提出 **System One Models**，并将 Jev 作为首个公开实例。本仓库沿用这一问题设定，以“机器原生决策模型”作为连接该工业类别与分类、结构化预测、受约束生成、概率校准、选择性预测和路由研究的上位分析术语。概念的工业源头归于 TypeSafe；配套综述的贡献是操作性边界、五维分类和四层评价框架。本仓库同时将官方材料与独立学术证据分开整理，避免把 schema 有效性、任务正确性、概率校准和系统效用混为一谈。

## 证据等级

- **A：同行评议**——正式发表的会议或期刊论文。
- **B：预印本**——尚需结合版本和后续评议使用。
- **C：官方材料**——厂商文档、第一方代码或第一方评测。
- **D：社区材料**——第三方实现与测试，需要检查协议和模型版本。

## 快速入口

- [Machine-Native Intelligence 官方首页](https://typesafe.ai/)
- [Jev 官方发布](https://typesafe.ai/blog/introducing-system-one-models-and-jev)
- [TypeSafe 文档](https://docs.typesafe.ai/introduction)
- [置信度文档](https://docs.typesafe.ai/confidence)
- [官方评测页](https://evals.typesafe.ai/)
- [Python 适配器](https://github.com/typesafe-ai/system-one-adapter-python)
- [完整英文论文索引](README.md#paper-index)
- [机器可读目录](data/resources.yml)
- [机器可读生态仓库目录](data/ecosystem.yml)

## Jev 生态仓库

仓库现已按用途收录并核验一组代表性项目，覆盖：

- TypeSafe 官方 JavaScript、Python SDK、基线适配器与 Agent skills；
- SemIf、jevlike、openjev、decider、reflex、von 等开放复现；
- Vercel eve、PostgreSQL、Home Assistant、LlamaIndex 与 n8n 集成；
- Agent 安全、代码工作流、邮件分拣、搜索重排和人工反馈应用；
- 独立延迟/成本测量、playground 与其他大型社区目录。

完整的项目说明与 GitHub 链接见[英文生态仓库索引](README.md#ecosystem-repository-index)。这些条目用于生态导航；社区仓库中的速度、成本、准确率和校准声明仍需分别核验。

## 论文分类索引

英文主索引当前收录 32 篇论文，按它们在机器原生决策流水线中的作用分类，而非简单按年份堆叠。每条记录统一给出证据等级、年份、发表场所、稳定链接、BibTeX 引用键和一句话定位。

- [基础与结构化预测](README.md#foundations-and-structured-prediction)
- [类型化输出与受约束解码](README.md#typed-output-and-constrained-decoding)
- [概率校准与不确定性](README.md#calibration-and-uncertainty)
- [选择性预测与学习拒答](README.md#selective-prediction-and-deferral)
- [决策导向学习](README.md#decision-focused-learning)
- [路由、级联与动态推断](README.md#routing-cascades-and-dynamic-inference)
- [校准感知决策训练](README.md#calibration-aware-decision-training)

完整条目见[英文论文索引](README.md#paper-index)，对应的机器可读记录位于 [`data/resources.yml`](data/resources.yml)。

## 四层评测框架

1. **结构有效性：** 输出能否满足类型、语法和 schema？
2. **语义正确性：** 选出的答案或动作是否正确？
3. **概率可靠性：** 同一置信度区间是否具有相近的经验正确率？
4. **决策效用：** 执行、复核、路由或升级之后，整个工作流是否获益？

![决策可靠性闭环](assets/fig2_evaluation_control_loop.png)

推荐至少报告准确率或任务损失、NLL、Brier、ECE、风险—覆盖曲线、AURC、schema 有效率、逻辑冲突率、p50/p95/p99 延迟、成本与分布偏移结果。

## 综述与可编辑配图

- [中文 Markdown 综述](paper/survey_zh.md)
- [英文 LaTeX 综述](paper/main.tex)
- [BibTeX 文献库](paper/references.bib)
- [图 1 HTML 源文件](assets/fig1_machine_native_landscape.html)
- [图 2 HTML 源文件](assets/fig2_evaluation_control_loop.html)

## 参与维护

新增资源时请同时修改 `README.md` 和 `data/resources.yml`，提供稳定链接、证据等级、一句话相关性说明，并标注可变网页的访问日期。具体要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。

配图中的线性图标来自 [Lucide](assets/icons/LICENSE)，并随仓库保留其开源许可证。
