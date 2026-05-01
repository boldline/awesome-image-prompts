# 📝 内容页设计

> 文字+图片排版、分栏布局、要点列表等内容页。

**所属分类**: [演示文稿](README.md)  
**Prompt 数量**: 5 条  
**难度等级**: ⭐⭐ 进阶

---

## Prompt 1: 数据展示内容页

> 以数据和图表为核心的内容页设计

**Prompt:**

```text
A data-focused presentation content slide, 16:9 widescreen format, clean analytical design. Layout: section header at top-left "Q3 Revenue Performance" with a thin colored underline (teal accent). Main content area divided into top and bottom sections. Top section: three large KPI metric cards side by side — each showing a big number (e.g., "$4.2M", "+27%", "1,847"), a label below ("Revenue", "YoY Growth", "New Customers"), and a tiny sparkline trend graph underneath each number with green for up-trend. Bottom section: a clean area chart showing 12-month revenue trend in gradient teal fill with clear axis labels, grid lines in light gray at 10% opacity. Footnote area at bottom with source citation in small gray text. Design principles: generous whitespace between elements, no decorative elements that don't serve data communication, professional business intelligence dashboard aesthetic, numbers as the hero elements, Tufte-inspired data-ink ratio, clean sans-serif typography throughout
```

**示例效果：**

![数据展示内容页](images/content-slide-01.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×864 | 16:9 宽屏 |
| 风格 | Data / Analytics | 数据分析风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 改为对比式双列数据（本季vs上季）
- 换成地图热力图+区域数据卡片
- 增加预测趋势的虚线延伸区域

**标签**: `#presentation` `#content-slide` `#data` `#metrics` `#dashboard`

---

## Prompt 2: 对比/VS 内容页

> 两个方案或产品的对比分析页面

**Prompt:**

```text
A comparison slide layout for a product/strategy presentation, 16:9 format, clear visual hierarchy. Title at top: "Solution Comparison" with a subtitle "Traditional vs. AI-Powered Approach". Layout: vertical split down the middle with a subtle dividing line or "VS" badge in a circle at center. Left column (muted/gray tones): header "Traditional", icon of a manual process (gear/hand), 4 bullet points with small ✗ or neutral icons, each showing a pain point or limitation, subtle red/orange accent for negative aspects. Right column (vibrant/brand tones): header "Our Solution", icon of AI/automation (sparkle/brain), 4 matching bullet points with ✓ checkmarks showing improvements, green/teal accents for positive aspects. Bottom: a summary bar showing key differential metric "3x faster, 60% cost reduction" in a highlighted callout box. Clean modern design, consistent spacing, readable at projection distance, using contrast (color, weight, size) to make the winner obvious without being heavy-handed
```

**示例效果：**

![对比VS内容页](images/content-slide-02.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×864 | 16:9 宽屏 |
| 风格 | Comparison Layout | 对比式布局 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 改为三列对比（基础版/专业版/企业版定价表）
- 换成Before & After的视觉改造对比
- 使用时间轴对比（过去→现在→未来）

**标签**: `#presentation` `#content-slide` `#comparison` `#versus` `#decision`

---

## Prompt 3: 引用/金句页

> 突出名言或关键观点的全屏金句页

**Prompt:**

```text
A presentation quote slide with powerful visual impact, 16:9 format. A full-bleed background: slightly blurred photograph of a vast ocean horizon at golden hour, warm amber and deep blue tones, creating an inspirational atmosphere. Centered text overlay: a large quotation in elegant serif font (Playfair Display style) in white with subtle text shadow for readability — "The best way to predict the future is to create it." Large decorative opening and closing quotation marks in a semi-transparent gold/amber accent. Attribution below the quote in smaller sans-serif caps with letter-spacing: "— PETER DRUCKER" with a thin horizontal line above. The overall composition creates a moment of pause and reflection in the presentation flow, cinematic and emotional, suitable for a leadership keynote or motivational section transition, text is perfectly legible against the background with careful contrast management
```

**示例效果：**

![引用金句页](images/content-slide-03.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×864 | 16:9 宽屏 |
| 风格 | Cinematic Quote | 电影感金句 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 改为纯色背景+超大字体的极简版本
- 换成黑白人像照片+overlay文字
- 使用手写体/书法字体增加温度

**标签**: `#presentation` `#content-slide` `#quote` `#inspirational` `#typography`

---

## Prompt 4: 流程/步骤说明页

> 展示工作流程或操作步骤的内容页

**Prompt:**

```text
A process/workflow presentation slide, 16:9 format, showing a 5-step methodology. Title: "Our Design Process" at top-left in bold. Main content: a horizontal process flow with 5 connected steps arranged left to right. Each step is a rounded rectangle or circle containing: a number (01-05), a simple line icon (magnifying glass, pencil, palette, code brackets, rocket), and a label below ("Research", "Ideate", "Design", "Develop", "Launch"). Steps connected by subtle arrows or a flowing line/path between them. Color progression: steps graduate from cool blue on the left to warm orange on the right, showing evolution/warming up. Currently active step (03 Design) is slightly enlarged/highlighted with a glowing effect or accent ring. Below the flow: a brief one-line description for each step in smaller gray text. Clean white background, plenty of breathing room between elements, modern SaaS product design aesthetic, clear visual hierarchy with the flow as the primary focal element
```

**示例效果：**

![流程步骤说明页](images/content-slide-04.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×864 | 16:9 宽屏 |
| 风格 | Process / Workflow | 流程图风格 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 改为垂直时间轴版本（适合步骤多的情况）
- 换成环形循环流程（敏捷/迭代方法论）
- 使用路线图风格（带里程碑标记的时间线）

**标签**: `#presentation` `#content-slide` `#process` `#workflow` `#steps`

---

## Prompt 5: 团队介绍页

> 展示团队成员和组织架构的页面

**Prompt:**

```text
A team introduction presentation slide, 16:9 format, professional yet personable design. Title: "Meet Our Leadership Team" at top. Layout: 4 team member cards arranged in a row with equal spacing. Each card contains: a circular photo placeholder (abstract gradient placeholder in brand colors for now) with a thin white border, name in bold below ("Sarah Chen"), title in lighter weight ("Chief Technology Officer"), and a one-line expertise tag or fun fact in italics. Cards have a subtle elevated shadow on a clean white/light gray background, creating a card-based UI aesthetic. A subtle brand accent color (deep purple or navy) used for the title and thin top border on each card. Bottom section: a small text noting team size "50+ talented individuals across 12 countries" with a subtle world map dotted outline behind it at very low opacity. Design inspired by modern SaaS company about-pages, professional headshot grid layout, warm and approachable while maintaining corporate credibility
```

**示例效果：**

![团队介绍页](images/content-slide-05.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×864 | 16:9 宽屏 |
| 风格 | Team / People | 团队介绍风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 改为组织架构图（树状层级关系）
- 换成顾问委员会版本（更正式的排版）
- 使用卡通头像/Memoji风格增加亲和力

**标签**: `#presentation` `#content-slide` `#team` `#people` `#organization`

---

## 🔗 相关推荐

- [幻灯片封面](slide-cover.md) - 匹配封面设计
- [Pitch Deck](pitch-deck.md) - 完整演示方案
- [主题演讲视觉](keynote-visual.md) - 全屏视觉页
- [报告封面](report-cover.md) - 报告整体设计
- [信息图表](../08-infographic/) - 数据可视化
