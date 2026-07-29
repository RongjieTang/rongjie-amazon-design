# Amazon 主图与详情页创作 / Amazon Main Image & Detail Page Design

作者 / Author: 汤荣杰 (Tang Rongjie)

包名 / Package name: `rongjie-amazon-design`

## 中文说明

`rongjie-amazon-design` 是一个用于 Amazon 商品视觉创作的 Codex skill，重点支持主图、辅图、信息图、生活方式图、对比图、A+ 模块和详情页创意规划。

它的核心方法是把商品图片创作当成一个完整的购买决策系统，而不是一组孤立海报。每张图都需要回答一个买家问题，并且让卖点回到可见证据或用户提供的信息上。

适合用于：

- Amazon 主图创意方向
- 辅图卖点规划
- Listing 信息图文案
- A+ 页面结构
- 产品图生成提示词
- 中英文商品视觉策划
- 亚马逊合规风险检查
- 竞品参考风格重构

默认工作流程：

1. 读取产品图、竞品参考和用户提供的卖点。
2. 区分可见事实、已确认事实、合理推断和风险声明。
3. 输出 Amazon Image Matrix，规划每张图的职责。
4. 先确认主图和前 1-2 张样图方向。
5. 再继续完成完整辅图或 A+ 模块。
6. 最后检查可读性、商品一致性、卖点证据和合规风险。

## English Description

`rongjie-amazon-design` is a Codex skill for Amazon product image and detail-page creative work. It helps plan and produce main images, secondary listing graphics, infographics, lifestyle images, comparison images, A+ modules, and long-form product detail pages.

The skill treats Amazon visuals as a shopper decision system, not as disconnected posters. Every image should answer a buyer question, support its message with visible or supplied evidence, and fit the listing sequence.

Best for:

- Amazon hero/main image direction
- Secondary listing image strategy
- Infographic copywriting
- A+ content structure
- Product-image generation prompts
- Chinese-English Amazon creative planning
- Marketplace compliance review
- Reworking competitor references into original concepts

Default workflow:

1. Read product images, competitor references, and supplied selling points.
2. Separate observed facts, confirmed facts, reasonable inferences, and risky claims.
3. Create an Amazon Image Matrix for the full image set.
4. Confirm the main image and first 1-2 sample images.
5. Continue with the full secondary image set or A+ modules.
6. Audit readability, product consistency, claim evidence, and compliance risk.

## Install

Copy the `rongjie-amazon-design` folder into your Codex skills directory, then invoke it with:

```text
Use $rongjie-amazon-design to plan Amazon main images and detail-page creative for my product.
```
