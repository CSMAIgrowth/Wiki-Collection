---
type: product-feature
source: https://doc.sparkx.io/en/articles/15147330-marketing-funnel-analysis
---
# Marketing Funnel Analysis（营销漏斗分析）

## 是什么

端到端视图，展示广告如何推动购物者从 awareness（曝光）→ consideration（详情页浏览）→ conversion（购买）→ loyalty（复购）逐层转化，定位「在哪一层流失」。

## 回答什么问题

- 销售下滑是媒体问题（广告互动弱）还是站内问题（产品页弱）？
- 不同广告类型如何把购物者推向漏斗下层？
- 购物者在哪层流失，可据此构建精准再营销受众？

## 何时用

逐步诊断 campaign 表现、修补销售漏斗漏洞；识别转化瓶颈、优化媒体组合、构建 retargeting。

## 关键特性

- 两种视图：
  - Impression Funnel（基于 AdImpression，追踪曝光→复购）。
  - Brand View Funnel（基于 28 天内广告曝光流量，从 Detail Page View 起步，评估产品页转化）。
- 指标：User Count、Cumulative Ad Spend、Impressions、Total DPV、CPDPV、CPDPV UV、Total Purchase、Total Product Sales、CPP、CPP UV、ATV、Repeat Purchase。
- 图表：漏斗图，可点击流失点即时生成受众。

## 注意事项/限制

- 数据最多回溯 13 个月（AMC 最大回溯窗口）。
- 标准模型默认只追踪 28 天内看过/点击过广告的购物者，不含自然流量；看纯自然流量需 FSI 订阅。
- Brand View Funnel 的「Unattributed」≠ organic，只是超出标准 7/14 天归因窗口但在 28 天内仍看过广告的购买。
- FSI 用户可加入 SnS 追踪长期忠诚度。
- 可自定义：按 ASIN / campaign 过滤，可更换各阶段目标（如末步由 Purchases 改为 SnS 订阅）。

## 相关页面

- [Path to Conversion](Path%20to%20Conversion.md)：用户触点序列。
- [Time to Conversion](Time%20to%20Conversion.md)：阶段间转化耗时。
- [Multi-touch Attribution](Multi-touch%20Attribution.md)：触点贡献评估。

## 来源

[Marketing Funnel Analysis](https://doc.sparkx.io/en/articles/15147330-marketing-funnel-analysis)

