# 历史研究标的归档规则

## 归档什么、不归档什么

本目录保存过去**研究/讨论过**但没有被确认纳入当前独立长期跟踪的公司和主题；不等同于持仓历史或投资卖出记录。

- `historical_research`：有过一次性分析或阶段关注，暂不进入 active。
- `inactive`：此前明确 active，且**用户后来明确提出停止**；必须记录 `exit_date`、`exit_reason`、`last_thesis`。本次尚没有足够依据认定任何一个明确长期跟踪标的已正式退出。
- 某公司仍在 active 时，过去的旧报告可存档，但**不得把公司状态标记 inactive**。
- 不自行杜撰历史买卖价格、仓位、研究结论、历史报告全文或退出理由。

## 历史线索登记

参见 [historical-research-index.md](historical-research-index.md)。本次只是将已知历史研究**主题及公司索引**写入仓库，尚未把过去聊天逐字全文迁移到 GitHub。

如未来实际整理历史研究，建议每篇独立 Markdown 带：
`company_id`、`research_date`、`as_of`、`source`、`conclusion_at_that_time`、`superseded_by`；旧结论原样保留，新增复盘另写。
