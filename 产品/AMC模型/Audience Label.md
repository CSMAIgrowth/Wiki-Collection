---
type: product-feature
source: https://doc.sparkx.io/en/articles/15147323-audience-label
---
# Audience Label（受众标签）

## 是什么

按购物者细分人群（Demographics 人口统计 / Lifestyle 生活方式 / In-Market 在市场中行为）拆解 Amazon DSP 投放数据，画像「谁在互动、谁在转化」的 AMC 模型。

## 回答什么问题

- 看到 DSP 广告的购物者，实际人口统计 / 生活方式特征是什么？
- 哪些受众细分「未投放」但仍与品牌互动？
- 不同购物者画像在 ROAS、转化效率上的差异？

## 何时用

优化 DSP 定向、调价，或为创意团队构建买家画像时；发现未开发高潜受众、区分产品线受众。

## 关键特性

- 事件类型：DSP 投放曝光与转化。
- 维度：Audience Type（Demographic / Lifestyle / In-Market）、Target Status（Targeted / Not Targeted）、受众规模。
- 指标：ROAS、Reach UV、Impressions、DPV、Purchase UV、CTR UV、eCPC UV。
- 图表：气泡图（实心 = 已投放，虚线 = 未投放但高 ROAS/Reach）。

## 注意事项/限制

- 仅适用于 Amazon DSP 受众标签，不能评估 Sponsored Ads 受众。
- 隐私合规：某细分月内独立用户 < 1001 时隐藏敏感字段或显示 NULL。
- 数据回溯仅过去一年（自定义模型上限 365 天）。
- 小受众 ROAS 波动大，先用漏斗上层指标（CTR UV、eCPC UV）判断。
- 高 ROAS 但覆盖面极小的标签，强推规模可能失效，需小规模试投放。
- 默认模型反映店铺整体；要准确 NTB 与转化指标，建议按核心 ASIN 过滤的自定义模型。

## 相关页面

- AMC受众运营：受众构建与投放验证背景。
- [Geographic Analysis](Geographic%20Analysis.md)：受众画像与地域表现。
- [Unique Reach](Unique%20Reach.md)：触达规模去重。

## 来源

[Audience Label](https://doc.sparkx.io/en/articles/15147323-audience-label)

