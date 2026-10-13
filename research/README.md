# 投资研究工作台

## 研究主线

**外部需求/供给变化 → L1 前置指标 → L2 同步定价/经营 → L3 财务兑现 → 盈利预测和估值调整。**

| 模块 | 作用 |
| --- | --- |
| [行业分类原则](framework/industry-classification.md) | 说明为何不能将交易所/券商行业分类直接当盈利模型 |
| [10 类盈利驱动](framework/earnings-models.md) | 同类盈利函数复用，共同驱动比较 |
| [L1/L2/L3 指标](framework/indicator-framework.md) | 指标设计、验证与数据质量 |
| [周期与三情景估值](framework/cycle-and-valuation.md) | 景气变化和市场定价组合 |
| [行业字典](taxonomy/industries.yaml) | 研究赛道 ID、行业归属、驱动模型及建设状态 |
| [CXO](industries/healthcare/cxo/README.md) | 融资 → 管线 → 订单 → PPQ/商业化 → 利润 |
| [VLCC](industries/transportation/oil-tankers/vlcc/README.md) | 吨海里需求 + 有效船队 → TCE → 利润/NAV |
| [当前跟踪](companies/active/README.md) | 核心与其他长期跟踪公司 |
| [历史归档](companies/archive/README.md) | 历史讨论过的研究线索，不混入当前跟踪 |

## 当前研究范围

- **正式试点**：CXO、VLCC。
- **优先扩展**：创新药、医疗器械、黄金、铜、电解铝、煤炭、半导体设备、AI 算力、AIDD 工具链。
- **公司跟踪**：以 [watchlist.yaml](companies/watchlist.yaml) 为状态来源；不能从文件是否存在猜测当前监控状态。

## 一次行业更新的最小闭环

1. 核实指标观测日期、原始来源和统计口径。
2. 描述指标较上期及较预期的变化，区分偶发波动与结构性变化。
3. 写清影响哪一层：需求/供给、订单、定价、利用率、利润。
4. 分析传导机制与延迟，检查相反证据。
5. 只有在重要假设变化时调整 Bear/Base/Bull 预测，不因每条新闻频繁重估。

模板见 [templates/](templates/)。
