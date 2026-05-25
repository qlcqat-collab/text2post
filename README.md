# text2post
Turn plain text into paste-ready formatted pages for WeChat Official Accounts. 6 beautifully designed styles including Notion minimal, glassmorphism, soft reading, and more. Copy the HTML, paste it into the source mode of the WeChat editor, and publish — no coding needed. Supports AI-powered auto-formatting. Zero learning curve, done in seconds.

# 🎨 Text2Post - 文字转公众号排版页面

> 把普通文字变成可直接粘贴的精美公众号排版页面。
> 提供 6 种精心设计的风格，覆盖极简、科技、自然、活泼、纸质、暗夜等场景。
> 所有样式复制即用，支持 AI 自动生成排版，无需任何编辑器，三秒完成一篇好看的文章。

---

## ✨ 特点

- 🚀 **复制即用** — 纯内联 CSS HTML，粘贴到公众号编辑器源码模式即可
- 🎨 **6 种风格** — 从极简到活泼，总有一款适合你的内容
- 📱 **移动端优化** — 完美适配手机阅读
- 🆓 **商用免费字体** — 思源黑体、阿里巴巴普惠体，无版权风险
- 🧩 **层级分明** — 大卡片 + 子区块 + 代码块，结构清晰
- 🤖 **AI 驱动** — 导入 AI 工具（如 Claude Code、自定义 GPT）后，一句话自动排版

---

## 🖼️ 风格预览

| 风格 | 适合场景 | 预览 |
|:---|:---|:---|
| 📋 **Notion 极简风** | 技术文档、深度教程 | 极致留白、细线分隔、无彩色卡片 |
| 🌫️ **毛玻璃科技风** | 开发工具、科技评测 | 纯白卡片、浅蓝灰底、蓝色强调 |
| 🍃 **晨光绿意风** | 生活分享、清新内容 | 暖白渐变、草绿强调、深苔绿代码块 |
| 🌈 **彩虹 Buddy 风** | 产品发布、年轻化品牌 | 流动彩虹边框、通透呼吸感 |
| 🍮 **羊皮纸阅读风** | 散文、笔记、深度阅读 | 仿古纸色、驼色强调、双线页眉 |
| 🌙 **极光暗夜风** | 夜间阅读、科技美学 | 深色底、极光光晕、青紫双色 |

---

## 🚀 快速开始

### 1. 选择风格
浏览 `skills/` 目录，选择你喜欢的风格文件（例如 `notion-style.md`）。

### 2. 导入 AI 工具
将 `.md` 文件内容复制为系统提示，或在支持的 AI 工具中直接导入该文件。

### 3. 一句话排版
对 AI 说：请用 notion-style 排版以下文章：[你的文章内容]


### 4. 复制发布
将生成的 HTML 代码粘贴到公众号编辑器的 **源代码** 模式，切换回正常模式即可看到精美排版。

---

## 📁 项目结构
text2post/
├── README.md
├── LICENSE
└── skills/
├── notion-style.md # Notion 极简风
├── glassmorphism.md # 毛玻璃科技风
├── natural-geek.md # 晨光绿意风
├── rainbow-buddy.md # 彩虹 Buddy 风
├── soft-reading.md # 羊皮纸阅读风
└── dark-mode.md # 极光暗夜风


---

## 🛠️ 自定义

每个 `.md` 文件内都包含了完整的配色和间距参数，你可以在 AI 对话中修改：把主色调改成 #你的颜色、把字号调大一号、把卡片圆角改成 20px


AI 会根据你的要求调整输出样式。



## 📖 示例

每个风格都提供了完整示例 HTML 文件，点击即可查看：

| 风格 | 示例代码 |
|:---|:---|
| Notion 极简风 | [notion-demo.html](examples/notion-demo.html) |
| 毛玻璃科技风 | [glassmorphism-demo.html](examples/glassmorphism-demo.html) |
| ... | ... |

---

## 🤝 贡献

欢迎提交新的风格模板或改进现有样式！

1. Fork 本仓库
2. 创建新分支 (`git checkout -b new-style`)
3. 提交你的更改
4. 推送到分支 (`git push origin new-style`)
5. 创建 Pull Request

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) — 可自由使用、修改、商用。

---

## ⭐ 如果这个项目对你有帮助

请点个 Star ⭐ 支持一下！你的鼓励是我们持续优化的动力。
