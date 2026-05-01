# 🎨 Awesome AI Image Prompts

> 一站式 AI 图像生成提示词集合，覆盖人像、摄影、电商、广告、海报、社交媒体、UI、信息图、漫画、演示文稿及技术图表等全场景。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📖 项目简介

本项目是一个精心整理的 AI 作图 Prompt 库，适配 GPT-Image、Midjourney、DALL·E、Stable Diffusion 等主流模型。每条 Prompt 均包含：

- ✅ **英文提示词**（直接复制使用）
- 🖼️ **示例效果图**（可视化参考）
- ⚙️ **参数说明**（风格、尺寸、模型建议等）

---

## 🗂️ 分类导航

| 编号 | 分类 | 文件夹 | 说明 | Prompt 数量 |
|:---:|------|--------|------|:---:|
| 01 | 🧑 人物肖像 | [`01-portrait/`](01-portrait/) | 头像、全身照、角色设计、时尚人像 | ~35 |
| 02 | 📷 摄影作品 | [`02-photography/`](02-photography/) | 电影感、风景、街拍、美食、建筑 | ~45 |
| 03 | 🛒 电商产品 | [`03-ecommerce/`](03-ecommerce/) | 产品展示、场景图、包装、模特穿搭 | ~30 |
| 04 | 📺 广告创意 | [`04-advertising/`](04-advertising/) | 品牌广告、Banner、户外广告、促销 | ~30 |
| 05 | 🎨 海报与插画 | [`05-poster-illustration/`](05-poster-illustration/) | 电影海报、活动海报、书籍封面、数字艺术、概念海报 | ~45 |
| 06 | 📱 社交媒体 | [`06-social-media/`](06-social-media/) | Instagram、小红书、微信、YouTube 缩略图 | ~35 |
| 07 | 💻 UI 与界面 | [`07-ui-mockup/`](07-ui-mockup/) | App 界面、网页着陆页、Dashboard、图标 | ~30 |
| 08 | 📊 信息图表 | [`08-infographic/`](08-infographic/) | 数据可视化、流程图、对比图、教育类 | ~35 |
| 09 | 💬 漫画与分镜 | [`09-comic-storyboard/`](09-comic-storyboard/) | 四格漫画、日漫、美漫、故事板、绘本 | ~30 |
| 10 | 📑 演示文稿 | [`10-presentation/`](10-presentation/) | 幻灯片封面、内容页、Pitch Deck、报告封面 | ~25 |
| 11 | 📐 技术图表 | [`11-technical-diagram/`](11-technical-diagram/) | 架构图、流程图、时序图、ER图、网络拓扑 | ~80 |

> 💡 **总计约 415+ 条高质量 Prompt**

---

## 🚀 快速开始

### 1. 找到你需要的场景

浏览上方分类表，点击进入对应文件夹。

### 2. 选择具体子类型

每个分类文件夹内含 `README.md`（概述）及多个子类 `.md` 文件。

### 3. 复制 Prompt 并使用

```text
# 示例：从 01-portrait/headshot.md 复制
A professional corporate headshot of a young Asian woman, 
soft studio lighting, neutral gray background, 
sharp focus on eyes, wearing a navy blazer...
```

### 4. 调整参数

根据每条 Prompt 附带的参数说明，调整尺寸、风格等设置。

---

## 📋 Prompt 条目格式

每条 Prompt 均遵循以下标准格式：

```markdown
### Prompt 名称

> 一句话描述这条 Prompt 的用途

**Prompt:**
​```text
The actual prompt text in English...
​```

**示例效果：**

![示例图](images/example.png)

**参数说明：**
| 参数 | 推荐值 |
|------|--------|
| 尺寸 | 1024×1024 |
| 风格 | Photorealistic |
| 模型 | GPT-Image / DALL·E 3 |

**使用建议：**
- 可替换 [关键词] 实现变体
- 搭配 negative prompt 提升效果
```

---

## 🔗 相关资源

> 除了自己用过的一些提示词外，很多也是来自外部的各种开源项目和大佬，明细的外部参考来源详见 [SOURCES.md](SOURCES.md)

**Prompt 画廊 & 案例集：**

- [EvoLinkAI/awesome-gpt-image-2-prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-prompts) - 170+ GPT Image 2 精选案例
- [OpenNana Prompt Gallery](https://opennana.com/awesome-prompt-gallery?model=ChatGPT) - 486+ 多模型 Prompt 画廊
- [YouMind AI 创作](https://youmind.com/zh-CN/gpt-image-2-prompts) - 分类 Prompt 集合

**内容生成 Skills：**

- [Baoyu Skills](https://github.com/jimliu/baoyu-skills) - 社交媒体卡片、信息图、漫画等多维生成
- [YouMind 手绘风 Skill](https://youmind.com/skills/x6ux3YCCI2qtaT) - 产品设计手绘速写风格

**技术图表工具：**

- [Diagram Design](https://github.com/cathrynlavery/diagram-design) - 14种图表类型系统
- [Fireworks Tech Graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) - 8类型×7风格技术架构图
- [Architecture Diagram Generator](https://github.com/Cocoon-AI/architecture-diagram-generator) - 暗色主题架构图
- [Markdown Viewer Skills](https://github.com/markdown-viewer/skills) - 15项可视化技能（Mermaid/Vega/PlantUML）
- [Blueprinter](https://skills.sh/yofine/skills/blueprinter) - 极简工程蓝图风格

**X/Twitter 创作者 Prompt：**

- [@aidavid125](https://x.com/aidavid125)（大卫叔的AI旅程）- 东方美学×现代高级感杂志封面 Prompt
- [@xiaoxiaodong01](https://x.com/xiaoxiaodong01)（小小东）- 字体视觉化×抽象几何线条概念海报系统级 Prompt
- [@MrLarus](https://x.com/MrLarus)（Larus Canus）- 现代平面几何字体概念海报 Prompt

---

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源。

---

<p align="center">
  <i>如果这个项目对你有帮助，请给一个 ⭐ Star！</i>
</p>
