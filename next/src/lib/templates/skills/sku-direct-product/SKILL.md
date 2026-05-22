---
name: sku-direct-product
zh_name: "电商商品直链页"
en_name: "E-Commerce Product Direct Page"
emoji: "🛍️"
description: "商品详情直链页: hero贴图+规格表+价格锚点+购买CTA, 适配淘宝/京东/拼多多商品页风格"
category: ecommerce
scenario: ecommerce
aspect_hint: "桌面 1440 / 移动端 375×812"
featured: 1
tags: ["ecommerce", "商品", "sku", "product-page", "电商"]
---

【模板: 电商商品直链页】
【意图】生成单品商品的直链落地页, 适合电商运营对每个SKU独立投放或嵌入商城详情页。一页完整呈现: 商品hero → 价格锚点 → 规格参数 → 卖点 → 评价 → CTA。

【布局 / Layout】
- **Top bar**: logo + 搜索 + 购物车icon + 客服入口 (轻量, 不抢产品)
- **Hero section**: 商品大图 (左) + 价格信息 (右), 价格要求用大字号红色或橙色强调; 原价划线价对比; 限时秒杀倒计时可选
- **SKU 规格**: 颜色/尺寸/版本的可选按钮组 (radio-style pills), 选中态高亮
- **卖点列表**: 3-5个icon+短句卖点 (如"顺丰包邮 / 7天无理由 / 正品保障")
- **详情区**: 商品描述 + 参数表 (2列grid)
- **评价区**: 用户评价卡片 (头像+星级+评论文本), 1-3条精选
- **底部 CTA**: 浮动"立即购买"按钮 (移动端sticky bottom)

【设计细节】
- **主色**: 品牌色 (橙/红/蓝) + 价格用 `#e74c3c` 或 `#ff6b35` 醒目标识
- **排版**: 品名用大号黑体(34-42px), 价格用粗体(28-32px), 参数用14px灰字
- **间距**: 商品图和信息区左右两栏, 移动端单栏堆叠
- **动效**: 价格数字轻微脉冲, 购买按钮hover放大, 规格选中平滑过渡
- **限制**: 所有图片CSS渐变占位; 不要外部图片URL; 单文件HTML
- **配色**: 纯白 #fafafa 底, 浅灰 #f5f5f5 卡片, 深灰 #1a1a1a 文字, 品牌色 #ff4757
