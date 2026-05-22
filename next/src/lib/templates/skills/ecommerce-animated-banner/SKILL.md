---
name: ecommerce-animated-banner
zh_name: "电商动效 Banner"
en_name: "E-Commerce Animated Banner"
emoji: "🎪"
description: "品牌/大促动态Banner: CSS粒子+动效文字+轮播+CTA, 适配首页/活动页/直播间封面"
category: ecommerce
scenario: ecommerce
aspect_hint: "1920×600 (桌面) / 750×400 (移动)"
featured: 4
tags: ["ecommerce", "banner", "动画", "轮播", "电商"]
---

【模板: 电商动效 Banner】
【意图】生成品牌级动态Banner, 用于电商首页首屏、大促活动页banner位、直播间封面、社交媒体头图。丰富CSS动效营造节日/促销氛围。

【布局 / Layout】
- **全宽背景**: CSS渐变或粒子动效背景, 大促用红金渐变, 品牌用品牌色系
- **主标题**: 巨大display文字 (72-120px), 字重900, 渐变填充文字或背景裁剪
- **副标题**: 24-32px, 促销信息 (如"全场5折起 / 限时24小时")
- **动效元素**:
  - 浮动粒子 (CSS @keyframes + filter blur)
  - 旋转/平移的装饰圆圈或几何体
  - 从两侧飞入的入场文字动画
  - 闪烁或呼吸的CTA按钮
- **CTA 按钮**: 大号圆角 pill, "立即抢购" / "查看详情", hover 有放大+光效
- **底部**: 品牌logo + 活动时间水印

【设计变体 (由用户内容决定)】
- Variant A: 双11/618 大促 → 红金 + 烟花粒子 + 倒计时 + 爆炸式文字
- Variant B: 新品发布 → 蓝紫渐变 + 光效扫入 + 简约科技感
- Variant C: 年货节/春节 → 中国红 + 金色 + 灯笼/烟花元素
- Variant D: 品牌日常 → 品牌色 + 柔和动效 + 产品图占位

【设计细节】
- **动效类别**: 入场关键帧动画(0.6-1.2s), 持续粒子动画, hover交互动效
- **字体**: 标题用粗黑体/无衬线, 中文 `Noto Sans SC` 字重900
- **限制**: 纯CSS动画实现, 不允许JS动画库; 单文件HTML; 所有图片CSS占位
- **配色**: 按变体选色; 文字与背景对比度≥4.5
