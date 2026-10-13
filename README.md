# theta-mmm · Investment Research Knowledge Base

面向 A/H/美股的长期投研知识库：**行业分类 → 盈利驱动 → 前置指标 → 景气传导 → 公司盈利 → 三情景估值**。

> 本仓库记录研究模型、可验证证据和跟踪状态，不代表实时行情服务或自动交易系统。所有动态结论需要标注截至日期、来源与不确定性。

## 研究入口

| 研究任务 | 入口 |
| --- | --- |
| 行业研究总览、研究导航 | [research/README.md](research/README.md) |
| 通用盈利驱动模型与景气判断 | [framework](research/framework/earnings-models.md) |
| 标准分类与细分赛道映射 | [industries.yaml](research/taxonomy/industries.yaml) |
| CXO 产业链与关键指标 | [CXO](research/industries/healthcare/cxo/README.md) |
| VLCC 运力周期与关键指标 | [VLCC](research/industries/transportation/oil-tankers/vlcc/README.md) |
| 当前重点跟踪标的 | [active](research/companies/active/README.md) |
| 历史研究标的归档 | [archive](research/companies/archive/README.md) |
| 公司跟踪状态唯一清单 | [watchlist.yaml](research/companies/watchlist.yaml) |
| 研究报告模板 | [templates](research/templates/) |

## 核心约束

- **按细分赛道研究，按盈利驱动模型比较**。申万、恒生、GICS 是映射维度，而不是唯一的研究目录结构。
- **将长期模型与当期证据分离**：行业长期逻辑位于 `README.md`；指标口径在 `indicators.yaml`；阶段性判断写入后续的 `updates/`。
- **将公司与行业分离**：一个公司可以对应多条产业链，但只保留一个公司主档案；同一公司 A/H 股共享经营模型，证券估值可分别计算。
- **明确“当前跟踪”与“历史研究”**：仅讨论过不等于长期跟踪；归档历史研究也不等于卖出股票。
- **动态数据先核实再记录**：记录 observation date、as-of date、来源、口径；不得以无来源猜测替代事实。

## 建设阶段

2026-10-13 首版：通用框架、行业映射、CXO/VLCC 试点、核心公司档案、历史研究索引。

后续按需求增加 `data/`（历史数据）、`scripts/`（采集分析）和 `briefs/`（跨行业周报）；**当前不创建空目录**。
