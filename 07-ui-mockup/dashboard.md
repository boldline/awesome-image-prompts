# 📊 数据仪表盘

> 后台管理系统、数据分析平台、监控面板设计。

**所属分类**: [UI 与界面](README.md)  
**Prompt 数量**: 5 条  
**难度等级**: ⭐⭐ 进阶

---

## Prompt 1: 数据分析仪表盘深色主题

> 企业级数据分析平台，深色主题配合紫蓝渐变高亮

**Prompt:**

```text
A professional data analytics dashboard UI design, dark theme with background (#1A1A2E) and purple-blue gradient accents, left sidebar navigation (64px wide collapsed) with icon-only menu items and active state indicator, top header bar with search input, notification bell, and user avatar, main content area in 12-column grid layout showing: top row of 4 KPI cards (Total Revenue $2.4M ↑12%, Active Users 48.2K ↑8%, Conversion Rate 3.2% ↓0.5%, Avg Order $86.40 ↑5%) with sparkline mini-charts, large area chart showing revenue trends over 12 months with gradient fill below line, bottom row split: bar chart comparing product categories on left, data table with sortable columns on right (customer name/email/amount/status badge), status pills in green/yellow/red, Inter font family, 8px border radius on cards, subtle 1px border on dark cards, enterprise SaaS aesthetic
```

**示例效果：**

![数据分析深色仪表盘](images/multi-panel-grid-01.jpg)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 浅色主题版本配合柔和渐变
- 增加实时数据动态刷新指示器
- 展开侧边栏版本（含文字标签）

**标签**: `#dashboard` `#analytics` `#dark-theme` `#enterprise`

---

## Prompt 2: 电商后台管理面板

> 电商运营后台 Admin Panel，浅色主题多功能概览

**Prompt:**

```text
An e-commerce admin panel dashboard, light theme with clean white (#FFFFFF) cards on soft gray (#F5F6FA) background, expanded left sidebar (240px) with logo at top, grouped navigation sections (Dashboard/Orders/Products/Customers/Marketing/Settings) with icons and labels, active item highlighted with brand blue, main content: welcome header with today's date and quick stats, order status pipeline (Pending 23 → Processing 15 → Shipped 42 → Delivered 186) as horizontal stepper, revenue chart (line + bar combo chart showing this week vs last week), recent orders table with columns (Order ID/Customer/Product thumbnail/Amount/Status/Date) showing 5 rows with action buttons, top-selling products card with product images and sales count, inventory alert card with low-stock warnings in amber, clean professional aesthetic with 4px rounded corners, proper spacing using 8px grid system, Segoe UI or Roboto font
```

**示例效果：**

![电商后台管理](images/dashboard-02.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 订单详情页面（含物流追踪地图）
- 商品管理列表页（含批量操作）
- 移动端响应式版本（平板适配）

**标签**: `#dashboard` `#e-commerce` `#admin-panel` `#light-theme`

---

## Prompt 3: 实时监控面板

> DevOps/服务器监控大屏，深色科技感 + 实时数据流

**Prompt:**

```text
A real-time infrastructure monitoring dashboard, very dark theme (#0F1117) with neon green (#00FF88) and electric blue (#00AAFF) accent colors creating a command-center aesthetic, no sidebar - full-width layout with top tab navigation (Overview/Servers/Network/Alerts/Logs), main content: world map with glowing dots indicating server locations and connection lines between regions, below: 3-column layout showing server health cards (CPU/Memory/Disk usage as circular progress gauges), real-time log stream panel with monospace font and color-coded severity levels (INFO blue/WARN amber/ERROR red), network traffic line chart with live data animation implied (multiple lines for inbound/outbound), incident timeline on right side showing recent alerts with timestamps, uptime percentage (99.97%) prominently displayed, terminal/console aesthetic mixed with modern UI, system status indicators with pulsing green dots, Fira Code or JetBrains Mono for data, dark sci-fi operations center feeling
```

**示例效果：**

![实时监控面板](images/dashboard-03.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1920×1080 | 全高清大屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 单服务器详情页（含进程列表和终端）
- 网络拓扑图可视化版本
- 告警规则配置界面

**标签**: `#dashboard` `#monitoring` `#devops` `#real-time` `#sci-fi`

---

## Prompt 4: CRM 客户管理仪表盘

> 销售团队 CRM 界面，Kanban 看板 + 客户数据

**Prompt:**

```text
A CRM sales pipeline dashboard design, light professional theme with white background and subtle blue (#EBF4FF) tint, left sidebar with company logo, team member avatars stack, and navigation (Dashboard/Contacts/Deals/Tasks/Reports), main view showing Kanban-style deal pipeline: 5 columns (Lead/Qualified/Proposal/Negotiation/Closed Won) with deal cards in each column, each card showing: company name, deal value, contact avatar, days in stage, probability percentage, cards are draggable with subtle shadow on one being "dragged", top metrics bar showing: pipeline value ($1.2M), deals to close this month (8), win rate (34%), average deal size ($45K), right panel: upcoming activities list (calls/meetings/follow-ups) with time indicators, small calendar widget showing month view with marked dates, clean corporate SaaS aesthetic, Salesforce/HubSpot quality, proper data hierarchy with color-coded deal stages
```

**示例效果：**

![CRM客户管理](images/dashboard-04.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 客户详情 360° 视图页面
- 销售漏斗可视化（Funnel Chart）
- 团队业绩排行和目标追踪页

**标签**: `#dashboard` `#crm` `#kanban` `#sales-pipeline`

---

## Prompt 5: 新拟态风格个人财务面板

> 个人记账/财务管理，Neomorphism 设计风格

**Prompt:**

```text
A personal finance dashboard with neomorphism (neumorphism) design style, soft light gray background (#E0E5EC), all elements using characteristic inset and outset soft shadows creating a 3D extruded clay-like appearance, no harsh borders - only shadow-defined shapes, main layout: top greeting "Good morning, Alex" with date, large balance card with neumorphic raised effect showing $24,568.00 with income/expense summary below, circular budget progress wheel with soft shadow (65% spent this month), expense categories as neumorphic pill buttons (Food/Transport/Shopping/Bills) with icons, spending trend chart with soft pastel colored areas (no hard lines), quick transfer section with contact avatars in pressed circles, recent transactions list with neumorphic list items (icon/description/amount), bottom navigation bar with pressed active state, monochromatic color scheme with subtle blue or purple accent for active states, rounded 20px+ corners on all elements, Poppins or Nunito font
```

**示例效果：**

![新拟态财务面板](images/dashboard-05.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 桌面端横屏比例 |
| 风格 | UI Design | 界面设计 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 深色新拟态版本（深灰底色）
- 仅移动端 App 版本
- 配合玻璃拟态混合风格

**标签**: `#dashboard` `#neomorphism` `#finance` `#personal`

---

## 🔗 相关推荐

- [App 界面](app-screen.md) - 移动端设计
- [网页着陆页](web-landing.md) - 网页设计
- [组件库展示](component-library.md) - 设计系统
- [线框图](wireframe.md) - 低保真原型
- [图标设计](icon-set.md) - 图标系统
