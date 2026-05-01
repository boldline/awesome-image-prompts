# 🧩 组件库展示

> 设计系统、UI Kit 的组件展示页面。

**所属分类**: [UI 与界面](README.md)  
**Prompt 数量**: 5 条  
**难度等级**: ⭐⭐ 进阶

---

## Prompt 1: 设计系统组件总览

> 完整 Design System 概览页，展示基础组件状态矩阵

**Prompt:**

```text
A comprehensive design system component library overview page, clean white canvas (#FAFAFA) with organized sections, top header showing system name "Atlas Design System v2.0" with version badge, content arranged in clearly labeled sections with dividers: BUTTONS section showing a matrix of button variants (Primary/Secondary/Tertiary/Ghost) × states (Default/Hover/Active/Disabled) in a 4x4 grid with labels, INPUT FIELDS section showing text input, search input with icon, dropdown select, textarea in default/focused/error/disabled states, SELECTION CONTROLS showing checkboxes, radio buttons, toggle switches, and sliders in on/off states, BADGES & CHIPS showing status badges (Success green/Warning amber/Error red/Info blue) and removable tag chips, consistent 8px spacing grid visible, proper component naming convention labels in small monospace text, brand colors: primary blue (#2563EB), neutral grays, semantic colors, Inter or SF Pro font at 14px body size, Figma component documentation style
```

**示例效果：**

![设计系统组件总览](images/design-system-01.jpg)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 深色主题版本的所有组件
- 单个组件放大展示（含代码片段）
- 移动端适配版本的组件尺寸

**标签**: `#component-library` `#design-system` `#buttons` `#inputs`

---

## Prompt 2: 色彩与字体规范页

> Design Token 可视化，色板 + 字体阶梯 + 间距系统

**Prompt:**

```text
A design system foundations page showing color palette, typography scale, and spacing tokens, clean white background with structured grid layout, LEFT SECTION - Color Palette: primary color shown in 10 shades (50-900) as horizontal swatches with hex codes labeled, secondary and accent colors similarly displayed, semantic colors row (success/warning/error/info each with light+base+dark variants), neutral gray scale from white to black in 11 steps, each swatch is a rounded rectangle with color name + hex code + contrast ratio, CENTER SECTION - Typography Scale: heading hierarchy displayed (H1 48px/H2 36px/H3 28px/H4 24px/H5 20px/H6 16px) with actual rendered text "The quick brown fox" showing size difference, body text styles (Large 18px/Regular 16px/Small 14px/Caption 12px) in regular and bold weights, font family specified as "Inter" with fallbacks, RIGHT SECTION - Spacing & Sizing: visual blocks showing 4/8/12/16/24/32/48/64px spacing as filled squares growing in size with px labels, border radius tokens shown as squares with increasing roundness (0/4/8/12/16/full), professional token documentation style
```

**示例效果：**

![色彩字体规范](images/component-library-02.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 深色模式下的色彩对比度展示
- 增加色彩无障碍 WCAG 检测标注
- 品牌色应用场景示例（Do/Don't）

**标签**: `#component-library` `#design-tokens` `#color-palette` `#typography`

---

## Prompt 3: 卡片与模态框组件

> 各类卡片变体和弹窗/模态框组件展示

**Prompt:**

```text
A design system page showcasing card components and modal/dialog variants, light gray (#F5F5F5) background canvas, TOP HALF - CARDS SECTION: 4 card variants displayed side by side: (1) Basic card - white with subtle border, title, description text, and text link, (2) Image card - top image area + content below + action buttons, (3) Horizontal card - image on left, content on right, (4) Interactive card - with hover state shown (slight elevation increase and border color change), each card has proper padding (24px), 8px border radius, and consistent shadow (0 2px 8px rgba(0,0,0,0.08)), below cards: card anatomy diagram with arrows pointing to padding, margin, border-radius measurements, BOTTOM HALF - MODALS SECTION: 3 modal/dialog examples: (1) Confirmation dialog - centered, icon at top, title, message, Cancel + Confirm buttons, (2) Form modal - header with close X, form fields inside, footer with action buttons, (3) Full-feature modal - sidebar tabs + content area (settings panel style), all modals shown with dark backdrop overlay partially visible, proper drop shadows, close button in top-right corner, responsive width annotations
```

**示例效果：**

![卡片与模态框](images/component-library-03.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 深色模式卡片变体
- 骨架屏加载状态（Skeleton）
- 底部抽屉/侧边面板（Sheet）组件

**标签**: `#component-library` `#cards` `#modals` `#dialogs`

---

## Prompt 4: 导航与菜单组件

> 各种导航模式展示：顶栏/侧栏/面包屑/标签页

**Prompt:**

```text
A design system page documenting navigation components, clean white background with clearly sectioned layout, SECTION 1 - TOP NAVIGATION BARS: three variants stacked vertically: (a) Simple nav bar with logo + text links + CTA button, (b) Mega menu expanded state showing dropdown with multi-column content and featured image, (c) Mobile responsive hamburger menu in expanded state showing full-screen overlay menu list, SECTION 2 - SIDEBAR NAVIGATION: two examples side by side: (a) Collapsed icon-only sidebar (64px wide) with tooltip showing on hover state, (b) Expanded sidebar (256px) with grouped sections, nested sub-items with indentation, active state highlighted with background fill and left border accent, badge counts on some items, user profile section at bottom, SECTION 3 - SECONDARY NAVIGATION: horizontal row showing: breadcrumb trail (Home > Products > Category > Item) with separator chevrons, tab bar with underline active indicator and badge on one tab, pagination component (Previous / 1 2 3 ... 8 9 10 / Next) with active page highlighted, segmented control with 3 options, all components showing proper interactive states labeled, consistent blue primary color throughout
```

**示例效果：**

![导航与菜单组件](images/component-library-04.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 移动端底部导航栏变体（含动画状态）
- 垂直步骤导航（Stepper）组件
- 命令面板（Command Palette）组件

**标签**: `#component-library` `#navigation` `#sidebar` `#menu`

---

## Prompt 5: 深色模式设计系统

> 完整深色主题 UI Kit，展示暗色环境下组件表现

**Prompt:**

```text
A dark mode design system showcase page, deep charcoal background (#121212) following Material Design dark theme guidelines with surface elevation levels, organized in a visually appealing grid layout, TOP ROW - SURFACE LEVELS: 5 card rectangles showing elevation levels (00dp through 24dp) with progressively lighter surface tints (from #121212 to #383838) labeled with dp values and hex codes, SECOND ROW - FORM COMPONENTS: dark mode input fields (outlined style with light gray border, white text, colored focus ring), filled buttons (primary purple gradient, secondary surface-colored, text-only), dropdown menu expanded (elevated dark surface with white text items and hover highlight), THIRD ROW - DATA DISPLAY: dark mode data table with alternating row stripes (subtle surface color alternation), progress bars and loading spinners (colored on dark track), notification toasts (success/error/warning with dark glass background and colored left border), FOURTH ROW - FEEDBACK COMPONENTS: dark tooltip with light text, dark popover menu, snackbar notification at bottom, skeleton loading placeholders with shimmer animation implied, all text in white (#FFFFFF) or light gray (#B3B3B3) for secondary content ensuring WCAG AA contrast, accent colors (purple #BB86FC, teal #03DAC6, coral #CF6679) chosen for dark background visibility, professional dark theme documentation
```

**示例效果：**

![深色模式设计系统](images/component-library-05.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 浅色/深色并排对比展示
- OLED 纯黑版本（#000000 背景）
- 自动主题切换动画过程帧展示

**标签**: `#component-library` `#dark-mode` `#design-system` `#material-design`

---

## 🔗 相关推荐

- [App 界面](app-screen.md) - 移动端设计
- [网页着陆页](web-landing.md) - 网页设计
- [数据仪表盘](dashboard.md) - 数据面板
- [图标设计](icon-set.md) - 图标系统
- [线框图](wireframe.md) - 低保真原型
