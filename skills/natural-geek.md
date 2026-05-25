# 🍃 晨光绿意风排版技能 (natural-geek)

## 适用场景
清新自然的分享、生活与学习内容、需要像清晨阳光穿过树叶般通透舒适的阅读体验。

## 设计规范
- **页面背景**：`linear-gradient(180deg, #fdfcf7 0%, #f7faf2 35%, #fafcf6 100%)` 暖白带浅绿渐变，叠加 4 个光晕：
  - 左上暖金+嫩绿 `radial-gradient(ellipse, rgba(245,200,120,0.15) 0%, rgba(190,220,160,0.10) 40%, transparent 70%)`
  - 右侧草绿 `radial-gradient(ellipse, rgba(160,210,140,0.12) 0%, transparent 70%)`
  - 底部淡金+绿 `radial-gradient(ellipse, rgba(245,225,160,0.10) 0%, rgba(180,210,150,0.06) 50%, transparent 70%)`
  - 左侧嫩绿 `radial-gradient(ellipse, rgba(200,230,175,0.10) 0%, transparent 70%)`
- **主标题 h1**：字号 `28px`，颜色 `#2e3522`（深橄榄绿），加粗 `700`，字母间距 `0.3px`
- **副标题**：字号 `13px`，颜色 `#7a9a6e`，透明度 `0.8`，字母间距 `0.5px`
- **大标题 h2**：字号 `20px`，颜色 `#2e3522`，左侧 `4px solid`，颜色用 `#6b9e6b`（草绿）或 `#c8964e`（暖金）交替，内边距 `14px`
- **小标题 h3**：字号 `17px`，颜色 `#2e3522`
- **正文 p**：字号 `15px`，颜色 `#4a5540`（苔灰），行高 `2.0`
- **行内代码 code**：背景 `#edf3e5`，文字色 `#5a7a3a`，圆角 `3px`，内边距 `2px 6px`
- **多行代码块 pre**：背景 `#26302a`（深苔绿），文字色 `#c8d8b8`，圆角 `8px`，内边距 `16px 18px`，边框 `1px solid #5a7a5a`，阴影 `0 2px 14px rgba(90,122,90,0.12)`，字体 `'SF Mono', 'Fira Code', 'Monaco', 'Consolas', monospace`
- **引用/子区块**：背景 `#f6faf3`，左侧 `4px solid #6b9e6b`，圆角 `12px`，阴影 `0 2px 12px rgba(107,158,107,0.08)`
- **列表 ul/ol**：字号 `15px`，颜色 `#4a5540`，行高 `2.2`，项间距 `6px`
- **分割线**：`1px solid #d8e0cc`
- **页眉**：
  - 左对齐 `🍃 栏目名`，颜色 `#6b9e6b`，字号 `11px`，字母间距 `0.6px`
  - 右侧日期，颜色 `#a3b89a`，字号 `11px`
  - 下方分割线 `1px solid #d8e0cc`
- **页脚**：顶部 `1px solid #e4ecd8`，居中，颜色 `#a3b89a`，字号 `11px`，内容：“🍃 本文由 AI 排版 · 晨光绿意阅读风”
- **字体**：`'Alibaba PuHuiTi', 'Source Han Sans SC', 'PingFang SC', 'Microsoft YaHei', 'Helvetica Neue', sans-serif`
- **容器**：`max-width: 680px; margin: 0 auto; padding: 44px 24px 22px`

## HTML 结构要求
- 所有样式内联
- 光晕必须保留，模拟晨光穿过树叶
- 代码块使用深苔绿背景，非纯黑
- 子区块用极浅绿底，大标题可穿插暖金边（如方法三）
- 整体通透清新，有森林浴的呼吸感

## 生成指令
1. 生成页眉（🍃 + 日期）
2. 生成主标题和副标题
3. 按文章内容拆分为章节，大标题用草绿或暖金左边框
4. 代码块使用深苔绿样式，子区块使用浅绿底
5. 分割线为淡绿
6. 最后生成页脚
7. 直接输出 HTML 内容片段（不含 <!DOCTYPE>）
