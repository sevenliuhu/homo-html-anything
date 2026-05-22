---
name: shop-detail
zh_name: "商品详情描述页"
en_name: "Product Detail Description Page"
emoji: "📋"
description: "商品详情/参数/卖点深度页: 长图式详情+规格对比表+图文描述+底部CTA"
category: ecommerce
scenario: ecommerce
aspect_hint: "移动端 375×无限; 桌面 1440 双栏"
featured: 3
tags: ["ecommerce", "详情页", "product-detail", "description", "电商"]
---

【模板: 商品详情描述页】
【意图】替代传统电商详情长图, 直接生成为HTML详情页。适合嵌入淘宝详情、微信商品页、独立站。深度讲解商品功能、材质、工艺、使用场景和售后服务。

【布局 / Layout】
- **折叠 Banner**: 顶部全宽商品主图 (CSS 渐变占位), 下方品名+价格+标签
- **Tab 导航**: ['商品详情' / '规格参数' / '售后说明'] 三个pill切换, 切换动画
- **商品详情 Tab**:
  - 图文描述区: 左文右图/左图右文的交叉排版, 每个卖点独立section
  - 使用场景展示 (3-4个场景卡片, icon+标题+描述)
  - 工艺/材质放大说明 (圆形matrix展示细节)
- **规格参数 Tab**:
  - 对比表: 左边特性名, 右边值, 斑马纹隔行
  - 可选: 相同下的一行"vs竞品"对比 (灰底, 竞品行浅红标识)
- **售后说明 Tab**:
  - 退换货政策 / 保修 / 物流 / 客服时间
  - 图标+短句列表, 可折叠 (details/summary)
- **相关推荐**: 4个横向滑动商品卡片
- **底部 CTA**: "加入购物车" + "立即购买" 双按钮

【设计细节】
- **主色**: 品牌色 (可配置), 默认 `#2d6cdf` 科技蓝 + `#ff4757` 行动红
- **排版**: 标题26-32px, 正文16-18px, 参数14px, 注释12px
- **间距**: section之间60px间距; 左右padding 24px
- **动效**: tab切换渐入; 图片懒加载占位动画
- **限制**: 单文件HTML; 所有图片CSS占位; 内联SVG icon
- **配色**: 白底 `#fafafa`, 卡片 `#ffffff`, 分割线 `#f0f0f0`
