---
name: seckill-promotion
zh_name: "限时秒杀促销页"
en_name: "Flash Sale Promotion Page"
emoji: "⚡"
description: "大促秒杀落地页: 倒计时+商品瀑布+阶梯优惠券+进度条, 适配双11/618/黑五"
category: ecommerce
scenario: ecommerce
aspect_hint: "移动端 375×812, 无限滚动瀑布流"
featured: 2
tags: ["ecommerce", "促销", "seckill", "flash-sale", "大促", "电商"]
---

【模板: 限时秒杀促销页】
【意图】大促场景的限时秒杀落地页, 制造紧迫感和稀缺性。适合双11、618、黑五、年货节等活动。

【布局 / Layout】
- **顶栏**: 活动标题大字 + 动态倒计时 (天/时/分/秒, 用等宽字体, 红底白字)
- **进度条**: "已抢 XX%" 动态progress bar, 带闪烁光效
- **阶梯优惠券**: 横向3张券 (满200-30 / 满500-80 / 满1000-200), 可领取态vs已抢完
- **商品瀑布**: 纵向商品列表, 每项展示: 商品图(左) + 名称/价格/已抢数(右) + 秒杀进度条
- **价格视觉**: 原价划线 + 秒杀价大红字 + "已省 ¥XXX" 标签
- **底部**: 浮动tab (首页 / 秒杀 / 购物车 / 我的) + 回到顶部
- **社交证明**: 顶部滚动条 "XXX刚刚下单了" 实时消息

【设计细节】
- **主色**: 红+金 (`#d43030` + `#ffd700`) 造成紧迫感
- **字体**: 数字用 `JetBrains Mono` 或 `Inter`, 中文用 `Noto Sans SC`
- **卡片**: 白底圆角16px, 浅阴影, 列表项间12px间距
- **动效**: 倒计时每1秒刷新; progress条发光动画; 优惠券领取按钮点击反馈
- **限制**: 纯CSS/JS实现, 单文件HTML, 所有图片CSS占位
- **规范**: 价格划线用 `text-decoration: line-through` + 灰色; 秒杀价醒目红字
