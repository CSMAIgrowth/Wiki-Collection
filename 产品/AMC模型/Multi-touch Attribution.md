---
type: product-feature
source: https://doc.sparkx.io/en/articles/15147300-multi-touch-attribution
---
# Multi-touch Attribution（多点归因 / MTA）

## 是什么

分析完整用户转化路径、应用多种数据驱动与规则归因逻辑，揭示每个广告触达点真实边际贡献的 AMC 模型，并提供预算重分配建议与绩效预测。

## 回答什么问题

- 超出 Amazon 默认归因，上层漏斗品牌广告（DSP/SB）的真实价值？
- 把预算从 Search 转 Display 会如何影响总转化？
- 如何重分配预算以最大化整体效率？

## 何时用

跨多广告类型管理预算、停止「猜哪个活动有效」：论证品牌支出、优化预算分配、预测增长、理解完整路径。

## 关键特性

- 7 种归因模型：Markov Chain（推荐）、Shapley Value（推荐）、First/Last Touch、Linear、Time Decay、Position-Based（40/40/20）。
- 对比柱状图：Amazon 官方归因 vs 所选 MTA 归因。
- Markov Chain 交互图：节点 = 触达点，可「移除」看 Removal Effect。
- Budget Optimization 模块：给出数学推荐的预算拆分。
- Forecast Budget Optimization Result：模拟预测 ROAS 与总转化改善。
- 指标：Total Purchase、Total NTB Purchase、Actual Cost、Suggest Budget、Forecast Result Change。

## 注意事项/限制

- 预定义基线：DSP 按过去 14 天 Impression 归因，SP/SB/SD 按 7 天 Click。
- Custom Model 最多 10 个广告分组，可自定义事件类型与回溯窗口。
- 结果偏斜常因回溯窗口不当：过短漏早期触达，过长引入无关数据；应贴合产品决策周期。
- 仅跟踪 Amazon 数字交互，不含外部/线下因素。

## 相关页面

- [Path to Conversion](Path%20to%20Conversion.md)：触点路径与触点贡献互补。
- [Overlap Analysis](Overlap%20Analysis.md)：媒体组合协同背景。
- [Marketing Funnel Analysis](Marketing%20Funnel%20Analysis.md)：漏斗阶段表现。

## 来源

[Multi-touch Attribution](https://doc.sparkx.io/en/articles/15147300-multi-touch-attribution)

