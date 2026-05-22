---
name: xiaohongshu-product-card
zh_name: "小红书种草卡片"
en_name: "Xiaohongshu Product Grass Card"
emoji: "🌿"
description: "小红书风格商品种草卡: 封面大字+实拍风+emoji清单+购买链接, 适合素人/博主带货"
category: ecommerce
scenario: ecommerce
aspect_hint: "1080×1440 (3:4), 多张连排"
featured: 5
tags: ["xhs", "小红书", "种草", "ecommerce", "商品", "带货", "social"]
---

【模板: 小红书种草卡片】
【意图】生成小红书的"种草"式商品推荐卡片组。封面图 + 痛点分析 + 商品卖点 + 使用体验 + 购买链接。输出N张 1080×1440 竖版卡片, 适合截图发小红书笔记。

【布局 / 卡片序列】
- **Card 1 封面**: 巨大标题 (如"这5个厨房神器, 我妈用了都说好") + emoji + 吸引眼球的tag ("干货 / 建议收藏" badge)
- **Card 2 痛点**: "为什么你需要它" — 用户痛点场景描述 + 对比 (before/after)
- **Card 3-5 商品卖点**: 每张卡一个核心卖点 + emoji + 短句 + 1-2个使用场景
- **Card 6 使用体验**: 真实感体验描述 + 评价 (⭐⭐⭐⭐⭐)
- **Card 7 总结+CTA**: 总结清单 + 行动号召 ("关注我, 每周好物推荐" / "评论区告诉我你的心头好")

【设计细节】
- **配色**: 小红书调 — 粉色/橙色/奶油色系渐变, 暖调
- **字体**: 中文 `Noto Sans SC` 字重 600-900, 大字号 (标题56-72px, 正文28-36px)
- **元素**: 大圆角卡片(24-32px), 柔和阴影, emoji作为视觉锚点
- **图片**: CSS渐变占位, 如 `linear-gradient(135deg,#fce4ec,#f8bbd0)` 模拟商品图
- **水印**: 右下角 "商品来自 @博主名" + 日期
- **限制**: 单文件HTML; 所有图标内联SVG或emoji; 不要外部图片
- **规范**: 小红书平台单帖最多18图, 通常9张以内最佳
