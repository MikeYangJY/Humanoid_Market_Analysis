# 02｜模型与控制

[研究首页](../README.md) · [研究地图](../research-map.md)

**回答：机器人智能能力怎样形成，能否转化为更少适配、更少接管和可靠交付。**

当前正文：[人形机器人模型行业研究](model-report.md)，资料截至 2026-09-27。以 PI、Figure、DeepMind 为主线，覆盖 π0.7、Helix 2.5 与 Gemini Robotics 2；同时纳入其他本体和竞争参照。

## 按研究问题阅读

| 主题 | 正文位置 |
|---|---|
| ER、VLA、全身控制、记忆与运行体系怎样分工 | [模型行业边界](model-report.md#scope) |
| PI 从动作学习到记忆、经验学习及可引导策略 | [PI 路线](model-report.md#pi-route) |
| Figure 从全身控制到跨家庭行为 | [Figure 路线](model-report.md#figure-route) |
| DeepMind 的多本体动作与高层任务组织 | [DeepMind 路线](model-report.md#deepmind-route) |
| 三家公司怎样比较、各自路线成立需要什么 | [路线与产品比较](model-report.md#comparison) |
| 成功率、泛化、自主性如何核对 | [六维能力与证据](model-report.md#evidence) |
| 人类数据、真机数据、仿真、记忆与世界模型 | [技术路线](model-report.md#technology) |
| 模型谁付费、怎样交付、市场如何测算 | [商业模式](model-report.md#business) · [市场边界](model-report.md#market-size) |
| 数据和交付能否形成壁垒 | [护城河与竞争参照](model-report.md#moats) |
| 下一轮应追踪什么、访谈什么 | [主要矛盾与访谈](model-report.md#bottlenecks) |

## 与前后环节如何连接

硬件决定模型可以观察什么、能够执行什么；模型决定硬件能力能否在变化场景中被利用；应用验收决定这些能力是否足够。后续模型更新既记录实验，也要检查它是否改善[统一运行指标](../04_tracking/metrics.md)。

[协作厂商供臂专题](../01_hardware/arms-and-oem-sourcing.md#capabilities)进一步讨论OEM的控制权限、反馈信号和时间同步需求。研发采集用臂与整机装机用臂分别统计，不能把训练设备采购直接当成人形整机装机；硬件销售也不自动带来客户数据使用权。

新模型资料应保留版本、机器人、训练/适配条件、任务切分、样本量、人工参与和成功定义。跨公司的不同基准不直接排序，缺失资料标为未知。原始论文链接保留在正文和[来源索引](../references/README.md)。
