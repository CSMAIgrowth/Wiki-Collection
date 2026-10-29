---
type: product-feature
source: https://doc.sparkx.io/en/articles/15147280-cross-product-association
---
# Cross-Product Association（跨产品关联）

## 是什么

映射整个商品目录中购物者行为之间关联的 AMC 分析模型，揭示「同单购买、复购、浏览后购买」等产品间关系。

## 回答什么问题

- 哪些产品经常在同一订单里被一起购买？
- 买了入门款后，通常会回来买什么？
- 哪些商品详情页是通向 Subscribe & Save 订阅的跳板？

## 何时用

规划选品、捆绑（bundling）、交叉销售、再营销策略时，用真实数据替代猜测。

## 关键特性

- 气泡图（Bubble Graph）：选一个 Root 商品，彩色气泡代表关联商品；气泡大小 = 关联数量。
- 五种事件类型（颜色区分）：
  - Simultaneous Purchase（同单购买，橙）
  - Subsequent Purchase（后续复购，青）
  - View Then Purchase（浏览后购买，粉）
  - Purchase Then Subscribe（购买后订阅，黄）
  - View Then Subscribe（浏览后订阅，绿）
- 关联粒度（Association Granularity）：默认子 ASIN，可上传 Excel 按父 ASIN / 品牌 / 产品线归组。
- 指标：Number of Associations（关联数）、Associated Sales（关联销售额）。

## 注意事项/限制

- SnS 订阅数据：无 FSI（Amazon Purchase Data Insights）订阅时，只能追踪「点订阅」动作 + 首单，无法追踪后续周期性配送；分析复购留存需升级 FSI 并用专用 Subscribe & Save Analysis 模型。
- 冷启动：新品没有足够流量/销量，关联数为零，需先观察期。
- 回溯窗口：预构建模型回溯最近 3 个月；自定义模型只查所选日期范围。
- 只反映有机购物行为，不含广告归因；要看广告驱动销售用 Path to Conversion。
- 只用于识别行为趋势，不作精确财务账本。

## 相关页面

- [Customer Lifetime Value](Customer%20Lifetime%20Value.md)：关联商品与长期客户价值。
- [New-to-Brand Analysis](New-to-Brand%20Analysis.md)：识别关联商品带来的拓新。

## 来源

[Cross-Product Association](https://doc.sparkx.io/en/articles/15147280-cross-product-association)

