---
type: product-feature
source: https://doc.sparkx.io/en/collections/19566275-amc-hub
---
# AMC 分析模型（AMC Model Gallery）

SparkX 帮助中心「AMC Hub」下的一组 AMC（Amazon Marketing Cloud）分析模型，共 12 个，用于从不同角度分析广告与购物者行为。来源 doc.sparkx.io（中文站需登录，英文站可公开访问）。

## 模型列表

- [Cross-Product Association](Cross-Product%20Association.md) — 跨产品关联：揭示同单购买 / 复购 / 浏览后购买等产品间关系。
- [Time to Conversion](Time%20to%20Conversion.md) — 转化所需时间：测量从触发事件到购买的考虑周期。
- [Overlap Analysis](Overlap%20Analysis.md) — 重叠分析：量化不同广告类型间受众重叠与协同。
- [Geographic Analysis](Geographic%20Analysis.md) — 地理分析：按州/地区映射广告表现与增长空白。
- [Multi-touch Attribution](Multi-touch%20Attribution.md) — 多点归因：多种归因模型揭示每个触达点的边际贡献。
- [Customer Lifetime Value](Customer%20Lifetime%20Value.md) — 客户终身价值：追踪长期总收益 vs 获客成本。
- [Search Term Analysis](Search%20Term%20Analysis.md) — 搜索词分析：基于曝光的搜索词表现与搜索旅程。
- [New-to-Brand Analysis](New-to-Brand%20Analysis.md) — 新客分析：拆分新客与复购，量化拓新。
- [Unique Reach](Unique%20Reach.md) — 去重触达：去重后真实触达规模与拓新效率。
- [Audience Label](Audience%20Label.md) — 受众标签：按人口 / 生活方式 / 在市场中行为细分 DSP 受众。
- [Path to Conversion](Path%20to%20Conversion.md) — 转化路径：多触点转化路径可视化。
- [Marketing Funnel Analysis](Marketing%20Funnel%20Analysis.md) — 营销漏斗：端到端漏斗诊断，定位流失层。

## 贯穿多个模型的通用概念

- **FSI（Amazon Purchase Data Insights）**：未订阅时很多模型只能看广告归因 / 首单，无法追踪自然流量、周期性 SnS 配送、长期复购；多个模型建议升级 FSI。
- **隐私门槛**：亚马逊要求达到一定独立用户数才显示数据（搜索词 100、受众标签 1001、多数模型 2 UV），低于门槛会隐藏。
- **回溯窗口**：预定义模型有默认回溯（如 Cross-Product 3 个月、Unique Reach 6 个月、Marketing Funnel 13 个月）；自定义模型按所选日期范围。
- **归因窗口**：SP 7 天点击、SD/SB/DSP 14 天（部分模型 DSP 按 14 天 Impression）。
- **冷启动**：新品无足够流量/销量时，关联、转化等数据为空，需观察期。

## 相关页面

- AMC受众运营：AMC 受众构建、投放与验证的业务背景。
- 广告数据与湖表口径：数据查询口径提醒。


