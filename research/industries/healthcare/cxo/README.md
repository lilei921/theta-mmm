# CXO · 融资、研发、订单与商业化传导

> industry_id: cxo | 模型：order-capex | 建档：2026-10-13。此为长期方法论，不代表 2026-10-13 实时景气判断。

## 业务边界

- **Discovery CRO（药物发现外包）**：靶点验证、分子筛选、药化、生物学等早期研究服务。
- **Preclinical CRO（临床前研发外包）**：DMPK、毒理、安全性评价等。
- **Clinical CRO（临床研究外包）**：临床方案、运营、患者入组、数据与注册支持。
- **CDMO（合同研发与生产）**：工艺开发、GMP 生产、临床后期验证和商业化供应。
- 生物药与 ADC/XDC 的生产工艺、质量体系、订单期限和产能约束与小分子不同。

## 核心传导路径

```text
全球 Biotech 融资 + 大药企研发预算/管线优先级
    ↓（可能用于现金跑道，不必然全部投入新项目）
候选药物/IND/临床试验立项与推进
    ↓
RFP与外包采购 → CRO新签订单 / CDMO项目导入
    ↓
净新签订单、Backlog及项目阶段迁移
    ↓
研究服务交付 / PPQ（工艺性能确认）/ BLA（生物制品许可申请）/ 商业化供应
    ↓
订单转收入、利用率、毛利率、经营现金流
    ↓
公司盈利预测与估值
```

**关键区别**：融资是更上游的需求条件；新签订单领先后续收入；PPQ 更适合观察中后期 CDMO 的商业化转化，而非作为所有 CRO 的共同领先指标。

## 核心监控面板

| 层级 | 核心指标 | 解释 |
| --- | --- | --- |
| L1 | 全球 Biotech 风险融资、IPO、Follow-on、BD upfront；Pharma R&D 预算 | 客户资金可获得性，需区分早期 Biotech 与大药企 |
| L1 | 研发活动（临床试验启动、IND、后期临床管线） | 潜在服务需求 |
| L1 | 净新签订单、Book-to-bill（订单收入比）、取消/延期 | 采购需求是否兑现 |
| L1 | 可执行 Backlog 与阶段结构 | 未来收入可见度，不能把全部金额视为确定收入 |
| L1 | 后期项目、PPQ、BLA、商业化项目数 | 生物药/ADC CDMO 重点，阶段迁移比单一项目总量更重要 |
| L2 | 工厂/实验室产能利用率、人员效率、项目价格 | 利润弹性与经营质量 |
| L3 | 分业务收入、毛利率、经营现金流、指引兑现 | 验证因果传导与盈利兑现 |

正式口径及限制见 [indicators.yaml](indicators.yaml)。

## 子行业模型

- [Discovery CRO](segments/discovery-cro.md)
- [Clinical CRO](segments/clinical-cro.md)
- [Small-molecule CDMO](segments/small-molecule-cdmo.md)
- [Biologics CDMO](segments/biologics-cdmo.md)
- [ADC/XDC CDMO](segments/adc-cdmo.md)

## 当前核心跟踪公司

[药明康德](../../../companies/active/wuxi-apptec/README.md)、[药明生物](../../../companies/active/wuxi-biologics/README.md)、[药明合联](../../../companies/active/wuxi-xdc/README.md)、[康龙化成](../../../companies/active/pharmaron/README.md)、[凯莱英](../../../companies/active/asymchem/README.md)。

## 三情景与证伪

- Bear：客户融资转弱、项目取消/延缓、订单变慢、产能闲置、价格下行。
- Base：融资与药企预算趋稳、项目漏斗正常迁移、订单按合理速度确认。
- Bull：订单和后期项目持续超预期，PPQ 转商业化、利用率改善并带来经营杠杆。
- 估值参考 DCF、Forward P/E、EV/EBITDA，复合业务采用分部模型；不得把 Backlog 原值直接折算为净利润。
