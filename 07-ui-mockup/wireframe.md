# 📝 线框图

> 低保真原型、用户流程、信息架构展示。

**所属分类**: [UI 与界面](README.md)  
**Prompt 数量**: 5 条  
**难度等级**: ⭐⭐ 进阶

---

## Prompt 1: 移动端低保真线框

> 电商 App 核心页面流程线框图，手绘草图风格

**Prompt:**

```text
A low-fidelity mobile app wireframe sketch for an e-commerce shopping flow, hand-drawn style on white paper with gray (#666666) pencil lines, showing 4 connected screens side by side: (1) Home - search bar at top, banner placeholder rectangle with X, category grid of 6 squares, product cards in 2-column grid with image placeholder, title lines, price, (2) Product Detail - large image area, title and price lines, size/color selector dots, quantity control, large Add to Cart button, (3) Cart - list of 2 items with thumbnail squares, name lines, quantity stepper, subtotal, promo code input, checkout button, (4) Checkout - address section with form fields, payment method radio buttons, order summary, Place Order button, flow arrows connecting screens with small interaction labels ("tap product", "add to cart", "proceed"), annotations in blue ink explaining key decisions, slightly imperfect hand-drawn aesthetic, UX design process documentation
```

**示例效果：**

![电商线框草图](images/wireframe-01.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横向展示多屏幕 |
| 风格 | Hand-drawn Sketch | 手绘草图 |
| 模型 | GPT-Image-2 | 推荐使用 |

**变体建议：**

- 改为数字化清晰线框（Balsamiq 风格）
- 增加更多交互标注和条件分支
- 设计对应的平板端自适应布局线框

**标签**: `#wireframe` `#low-fi` `#mobile` `#e-commerce` `#user-flow`

---

## Prompt 2: 网页端数字线框

> SaaS 产品网页完整页面线框，数字化清晰风格

**Prompt:**

```text
A clean digital wireframe for a SaaS product landing page, full-page layout in Balsamiq/Figma wireframe style, grayscale only with three tones (white, light gray fills, dark gray lines/text), 1440px desktop width showing complete scrollable page: (1) Navigation bar: logo square + 4 text links + CTA button outline, (2) Hero section: large headline text block "H1 Title Here" + two lines of body text + two buttons side by side + right side device mockup placeholder rectangle, (3) Logo bar: 5 company logo squares in a row, (4) Features: 3-column grid with icon circles + H3 titles + paragraph text blocks, (5) How it Works: numbered steps 1-2-3 with connecting dotted line, (6) Testimonial: large quote marks + text block + avatar circle + name, (7) Pricing: 3 cards side by side with feature lists and buttons, (8) CTA banner: centered text + button, (9) Footer: 4-column link lists + bottom bar, proper spacing annotations with dimension lines in blue, responsive breakpoint notes in margins
```

**示例效果：**

![SaaS网页线框](images/wireframe-02.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1024×1536 | 纵向展示完整页面 |
| 风格 | Digital Wireframe | 数字化线框 |
| 模型 | GPT-Image-2 | 推荐使用 |

**变体建议：**

- 旁边增加移动端响应式对比版本
- 添加热力图数据层覆盖展示用户行为
- 设计带有 A/B 测试变体标注的版本

**标签**: `#wireframe` `#web` `#SaaS` `#full-page` `#digital`

---

## Prompt 3: 用户流程图

> 注册/登录流程的用户旅程图，包含决策节点

**Prompt:**

```text
A user flow diagram for a mobile app onboarding and registration process, clean flowchart style on white background, using standard UX flow notation: rounded rectangles for screens, diamonds for decision points, arrows for flow direction, start/end circles, color coding: blue for screens, yellow for decision points, green for success states, red for error states, flow includes: App Open → Splash Screen → Decision: First Time? → Yes: Welcome Carousel (3 slides) → Sign Up Method Selection (Email/Google/Apple) → Email path: Enter Email → Verify Email → Create Password → Profile Setup → Home, decision branches for "Already have account?" → Login flow, error handling: invalid email → error state → retry, social auth failure → fallback to email, small screen thumbnails inside each screen node showing basic wireframe layout, numbered steps (1-12), clear labels on all arrows explaining triggers ("tap continue", "email verified", "auth failed"), legend in corner explaining symbols, professional UX documentation quality
```

**示例效果：**

![注册流程图](images/wireframe-03.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横向流程展示 |
| 风格 | Flowchart | 流程图风格 |
| 模型 | GPT-Image-2 | 推荐使用 |

**变体建议：**

- 改为电商下单支付流程
- 增加各节点的转化率/流失率数据标注
- 设计跨平台（Web + App）的统一流程图

**标签**: `#wireframe` `#user-flow` `#flowchart` `#onboarding` `#UX`

---

## Prompt 4: 信息架构站点地图

> 大型网站信息架构可视化，树状结构展示

**Prompt:**

```text
A visual sitemap / information architecture diagram for a corporate website, hierarchical tree structure on light background, top-down layout starting from Homepage at the root, branching into primary navigation: About (→ Team, History, Values, Careers sub-pages), Products (→ Product A, Product B, Product C, each with Features/Pricing/Docs sub-pages), Solutions (→ Enterprise, Startup, Agency), Resources (→ Blog, Case Studies, Whitepapers, Webinars), Support (→ Help Center, Documentation, API Reference, Contact), clean card style for each page node: white rectangle with page title and small icon indicating page type (content, form, listing, detail), connecting lines with hierarchy levels color-coded (L1 blue, L2 teal, L3 gray), total page count summary in corner, legend showing page types and status (Existing, New, To be updated) with colored dots, annotations for cross-linking between sections shown as dashed curved arrows, professional IA deliverable quality
```

**示例效果：**

![站点地图架构](images/wireframe-04.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横向树状展示 |
| 风格 | Sitemap Diagram | 站点地图 |
| 模型 | GPT-Image-2 | 推荐使用 |

**变体建议：**

- 改为电商平台的复杂多层架构
- 增加页面权重和 SEO 优先级标注
- 设计移动端 App 的导航架构图

**标签**: `#wireframe` `#sitemap` `#information-architecture` `#tree` `#planning`

---

## Prompt 5: 响应式布局对比

> 同一页面在不同设备上的响应式适配展示

**Prompt:**

```text
A responsive design wireframe comparison showing the same dashboard page across 4 device breakpoints, displayed side by side on neutral gray background, clean digital wireframe style (grayscale, no real content): (1) Desktop 1440px - full sidebar navigation + 3-column content grid + header bar, (2) Laptop 1024px - collapsed sidebar (icons only) + 2-column grid + header, (3) Tablet 768px portrait - no sidebar, hamburger menu in header, 2-column grid becoming stacked in some areas, bottom tab bar appearing, (4) Mobile 375px - single column stack, hamburger menu, cards full width, bottom navigation bar with 4 icons, red annotation arrows showing how elements reflow: sidebar → hamburger, 3-col → 2-col → 1-col, table → card list, desktop chart → simplified mobile chart, breakpoint labels and pixel widths clearly marked above each frame, dimension annotations showing margins and gutters at each size, proper wireframe notation with placeholder content blocks, professional responsive design documentation
```

**示例效果：**

![响应式对比展示](images/wireframe-05.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横向对比展示 |
| 风格 | Responsive Wireframe | 响应式线框 |
| 模型 | GPT-Image-2 | 推荐使用 |

**变体建议：**

- 改为电商商品列表页的响应式适配
- 增加折叠屏设备的特殊适配展示
- 设计 CSS Grid/Flexbox 布局标注版本

**标签**: `#wireframe` `#responsive` `#breakpoints` `#adaptive` `#multi-device`

---

## 🔗 相关推荐

- [App 界面](app-screen.md) - 线框图的高保真实现
- [网页着陆页](web-landing.md) - 网页线框到成品
- [数据仪表盘](dashboard.md) - 仪表盘原型参考
- [组件库展示](component-library.md) - 线框图使用的组件
- [图标设计](icon-set.md) - 线框中的图标占位
