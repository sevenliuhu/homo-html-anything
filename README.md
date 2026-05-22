# HOMO HTML Anything · 📄 AI 电商物料生成器

<p align="center"><sub>基于 <a href="https://github.com/nexu-io/html-anything"><b>html-anything</b></a> (4504⭐) 的 HOMO 电商增强版 — 专注中国电商生态的 AI 物料生成器</sub></p>

<p align="center">
  <b>AI 时代的 HTML 编辑器, 专为电商运营、内容创作者、品牌营销人打造</b>
</p>

<p align="center">
  <a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/license-Apache%202.0-blue.svg?style=flat-square" /></a>
  <a href="#-技能模板"><img alt="Templates" src="https://img.shields.io/badge/电商模板-7%20套-orange?style=flat-square" /></a>
  <a href="#-技能模板"><img alt="Agents" src="https://img.shields.io/badge/编码%20Agent-8%20CLIs-black?style=flat-square" /></a>
  <a href="#-一键分发"><img alt="Export" src="https://img.shields.io/badge/发布-小红书·抖音·微信-9b59b6?style=flat-square" /></a>
  <a href="#-快速开始"><img alt="Quickstart" src="https://img.shields.io/badge/快速开始-30秒-green?style=flat-square" /></a>
</p>

<p align="center">
  <b>简体中文</b>
</p>

---

## 📋 目录

- [为什么是这个工具](#-为什么是这个工具)
- [快速开始](#-快速开始)
- [电商模板包](#-电商模板包)
- [社媒模板](#-社媒模板)
- [技能模板](#-技能模板)
- [一键分发](#-一键分发)
- [架构](#-架构)
- [FAQ](#-faq)

---

## 🤔 为什么是这个工具？

**做电商的都知道——物料是最头疼的事。**

- 商品页要好看 → 找设计师 → 排期三天
- 小红书要种草 → 重新排版 → 又找设计师
- 抖音要脚本 → 写分镜 → 天啊又要沟通
- 公众号要推送 → 又是一套新排版

**HOMO HTML Anything 的做法: 你给内容, AI 出成品。**

你写一段 Markdown / 扔一个 CSV / 贴一段 JSON, 按 ⌘+Enter, 你的**本地 AI Agent** 在几秒内把它变成——商品直链页、秒杀促销页、小红书种草卡、抖音分镜脚本、公众号文章、Banner广告——**单文件 HTML, 到手即用, 双击可看, 截图可发, 一键可部署。**

> **Markdown 是草稿, HTML 才是成品。** 在人人都用 AI Agent 的时代, 你不需要学排版——AI 替你排。

8 大编码 Agent CLI 自动识别:
`Claude Code` · `Cursor Agent` · `Codex` · `Gemini CLI` · `GitHub Copilot CLI` · `OpenCode` · `Qwen Coder` · `Aider`

---

## ⚡ 快速开始

```bash
# 1. 克隆仓库
git clone https://github.com/your-org/homo-html-anything.git
cd homo-html-anything

# 2. 选择一个电商模板
#    打开 next/src/lib/templates/skills/sku-direct-product/SKILL.md

# 3. 把商品信息发给你的编码 Agent
#    "用 sku-direct-product 模板, 生成一个 HOMO 蓝牙耳机的商品页
#     内容: [你的商品信息]"

# 4. 成品是一个 .html 文件
#    双击打开 → 直接可用 → 截图发小红书 / 嵌入商城 / 发给开发部署
```

**不需要 API Key, 不需要注册, 不需要配置。** 你在终端登录的 Agent CLI 就是你的引擎。

---

## 🛍️ 电商模板包

专为中国电商生态定制的 4 套核心物料模板:

### 1️⃣ [商品直链页](./next/src/lib/templates/skills/sku-direct-product/)

| 项目 | 说明 |
|------|------|
| 用途 | 单品商品的独立落地页, 替代传统详情长图 |
| 包含 | Hero大图 + 价格锚点 + SKU规格选择 + 卖点列表 + 参数表 + 评价区 + 购买CTA |
| 适配 | 淘宝详情页 / 京东商品页 / 独立站商品页 / 微信商品页 |
| 特色 | 移动端 sticky CTA, 价格醒目对比, 规格选中交互 |

### 2️⃣ [限时秒杀页](./next/src/lib/templates/skills/seckill-promotion/)

| 项目 | 说明 |
|------|------|
| 用途 | 大促活动的限时秒杀落地页 |
| 包含 | 动态倒计时 + 抢购进度条 + 阶梯优惠券 + 商品瀑布 + 社交证明滚动 |
| 适配 | 双11 / 618 / 黑五 / 年货节 / 品牌日活动 |
| 特色 | 紧迫感设计(红金配色), 倒计时实时刷新, "已抢XX%"进度光效 |

### 3️⃣ [商品详情页](./next/src/lib/templates/skills/shop-detail/)

| 项目 | 说明 |
|------|------|
| 用途 | 商品深度详情介绍, 替代传统长图详情 |
| 包含 | Tab切换(详情/规格/售后) + 图文混排卖点 + 场景卡片 + 规格对比表 + 相关推荐 |
| 适配 | 淘宝详情 / 微信商品页 / 独立站 / 小程序商品详情 |
| 特色 | 三Tab切换动效, 售后折叠详情, 斑马纹参数表 |

### 4️⃣ [动效 Banner](./next/src/lib/templates/skills/ecommerce-animated-banner/)

| 项目 | 说明 |
|------|------|
| 用途 | 品牌/大促动态Banner, 用于首页首屏、活动页banner位、直播间封面 |
| 包含 | CSS粒子动效 + 入场文字动画 + 渐变背景漂移 + 装饰几何体 + CTA按钮 |
| 变体A | 双11/618大促 → 红金 + 烟花粒子 + 爆炸式文字 |
| 变体B | 新品发布 → 蓝紫渐变 + 科技感光效 |
| 变体C | 年货节/春节 → 中国红 + 金色 + 灯笼元素 |
| 特色 | 纯CSS动效, 无额外JS依赖, 可直接嵌入任意页面 |

---

## 📱 社媒模板

适配中国主流社交媒体的 3 套内容模板:

### 5️⃣ [小红书种草卡片](./next/src/lib/templates/skills/xiaohongshu-product-card/)

| 项目 | 说明 |
|------|------|
| 格式 | 1080×1440 竖版, 多张连排, 每张卡片一个核心观点 |
| 内容 | 封面大字 + 痛点分析 + 商品卖点 + 使用体验 + 购买引导 |
| 配色 | 小红书调: 粉色/橙色/奶油色系渐变 |
| 特色 | 7-9张一组, 截图即可发小红书笔记, 每张右下角水印 |
| 适合 | 素人/博主带货笔记、好物推荐合集 |

### 6️⃣ [抖音脚本 Deck](./next/src/lib/templates/skills/douyin-deck/)

| 项目 | 说明 |
|------|------|
| 格式 | 9:16竖版1080×1920, 每页一分镜 |
| 内容 | 镜头画面 + 口播文字 + 时长 + 音效/BGM标记 + 商品关联 |
| 配色 | 抖音风格: 暗底 #161823 + 亮青 #00f2ea + 亮粉 #fe2c55 |
| 特色 | 可直接打印为拍摄脚本, 带货/剧情/知识分享均适用 |
| 适合 | 直播预热视频、商品带货、品牌宣传短视频 |

### 7️⃣ [微信公众号文章](./next/src/lib/templates/skills/wechat-article/)

| 项目 | 说明 |
|------|------|
| 格式 | 640px 内容宽, 符合微信生态阅读规范 |
| 内容 | 头图Banner + 段首大字 + 图文混排 + 产品卡片 + 二维码区 + 版权 |
| 配色 | 微信风格: 白底+绿强调(#07c160) |
| 特色 | 产品Card可直接嵌入, 含购买按钮, 内联SVG二维码占位 |
| 适合 | 品牌公众号推送、新品发布、促销通知、种草长文 |

---

## 🎯 技能模板

基于 html-anything 75 套技能模板, HOMO 版新增了 `ecommerce` (电商) 类别。模板结构:

```
SKILL.md    → 模板描述, 告诉 AI Agent 生成什么
example.html → 真实可打开的例子, 展示效果
```

**示例: 用 Agent 生成一个商品页**

```bash
# 场景: 你在终端里
# 1. 准备好商品信息 (Markdown 格式)
# 2. 告诉你的 Agent:
#    "用 sku-direct-product 模板, 生成华为MatePad Air的商品页
#     以下是商品信息:
#     - 品名: 华为MatePad Air
#     - 价格: 请邮件咨询
#     - 卖点: 12英寸2.8K屏 / 8300mAh电池 / 144Hz刷新率
#     - 配色: 曜金黑 / 星河蓝 / 薄荷绿"

# 3. AI 自动调用模板, 输出完整 HTML
# 4. 双击 .html → 浏览器打开 → 完美
```

---

## 🌐 一键分发

生成的 HTML 可以:

| 平台 | 方式 |
|------|------|
| **小红书** | 截图 HTML 卡片 → 直接发笔记 |
| **抖音** | 脚本 Deck → 照着拍 → 发布 |
| **微信公众号** | 复制 HTML 正文 → 粘贴到公众号编辑器微调 |
| **淘宝/京东** | 商品页 HTML → 复制到详情编辑器 |
| **独立站** | 直接部署 .html 文件 |
| **X / Twitter** | 截图贴卡 → 发布 |
| **知乎** | 长文 HTML → 复制到编辑器 |

---

## 🏗️ 架构

```
homo-html-anything/
├── next/                          # Next.js 应用
│   └── src/
│       └── lib/
│           └── templates/
│               ├── shared.ts      # 共享设计指令 (中文版)
│               └── skills/
│                   ├── sku-direct-product/       # 🛍️ 商品直链页
│                   ├── seckill-promotion/        # ⚡ 限时秒杀页
│                   ├── shop-detail/              # 📋 商品详情页
│                   ├── ecommerce-animated-banner/ # 🎪 动效Banner
│                   ├── xiaohongshu-product-card/  # 🌿 小红书种草
│                   ├── douyin-deck/              # 🎵 抖音脚本
│                   └── wechat-article/           # 💬 公众号文章
├── scripts/
├── package.json
├── LICENSE
└── README.md                      # 本文档
```

---

## ❓ FAQ

**Q: 需要 API Key 吗？**  
A: 不需要。你的本地 Agent CLI 就是引擎 (Claude Code / Cursor / Codex 等)。

**Q: 能生成中文内容吗？**  
A: 完全支持。所有模板针对中文排版优化, 使用 Noto Sans SC / Noto Serif SC 等中文字体。

**Q: 生成的页面能在手机上打开吗？**  
A: 可以。所有模板均为响应式设计, 适配桌面和移动端。

**Q: 图片怎么办？**  
A: 模板使用 CSS 渐变占位, 你可以在 HTML 里替换为真实图片 URL。

**Q: 和原版 html-anything 什么关系？**  
A: HOMO 版是原版 (4504⭐) 的电商增强分支, 新增了电商生态和社媒平台支持。

**Q: 我能自己加模板吗？**  
A: 当然。在 `skills/` 下新建目录, 写 `SKILL.md` + `example.html` 即可。

---

## 📜 License

Apache 2.0 — 自由使用、修改、商用。

---

<p align="center">
  <b>Built on <a href="https://github.com/nexu-io/html-anything">html-anything</a></b> · 4504⭐ · Apache 2.0<br/>
  <sub>HOMO 电商增强版 · 专注中国电商生态</sub>
</p>




---

## ⭐ Star 解锁专属工具

给本仓库点 Star，即可前往解锁页面获取独家数据/工具/模板：

👉 [**https://sevenliuhu.github.io/Homo-Ai/unlock.html**](https://sevenliuhu.github.io/Homo-Ai/unlock.html)

内容包括：A股量化模板 / 反爬指纹规则集 / 134技能索引 / 记忆系统配置 / 电商SKILL模板 / 中国风设计色板 等 12 份独家资源。

## 🤝 需要定制开发？

我们提供基于此项目的商业增强版和企业定制服务。

- **📧 邮件咨询**：16208204@qq.com

> 💼 **商业授权**：获取商业授权与付款信息，请填写[授权表单](https://sevenliuhu.github.io/Homo-Ai/unlock.html)或发邮件至 **16208204@qq.com**
- **💼 在 Fiverr 下单**：https://www.fiverr.com/sevenliuhu
- **🌐 HOMO 官方网站**：https://sevenliuhu.github.io/Homo-Ai/

> 💡 我们拥有 215 个 AI 智能体、15+ 专业部门，覆盖工程/设计/销售/市场/法律等全链路。无论你是需要定制开发、技术咨询，还是想把 AI 能力落地到你的业务中，我们都能帮你实现。
