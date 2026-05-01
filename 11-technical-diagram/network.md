# 🌐 网络拓扑图

> 网络架构、防火墙规则、负载均衡等网络拓扑可视化。

**所属分类**: [技术图表](README.md)  
**Prompt 数量**: 5 条  
**难度等级**: ⭐⭐⭐ 高级

---

## Prompt 1: 企业网络架构

> 大型企业的多层网络安全架构

**Prompt:**

```text
A network topology diagram showing enterprise network architecture with defense-in-depth design. Layered top-to-bottom: Internet cloud at top → dual ISP connections with BGP → perimeter firewall cluster (active/standby) → DMZ zone containing WAF, reverse proxy, mail gateway → internal firewall → core network with Layer 3 switches → three segments: Server Farm (database, app servers, file storage), User Network (VLAN per department: Engineering, Sales, HR), and Management Network (jump servers, monitoring, backup). Show redundant paths with dual connections at every layer. Standard network icons: routers as circles with arrows, switches as rectangles with arrows, firewalls as brick walls, servers as tower icons. IP subnet labels (10.0.x.x/24) on each segment. Security zones color-coded: red=untrusted, yellow=DMZ, green=trusted, blue=management. Corporate professional style with clean white background, precise technical lines, Cisco-style iconography, professional network documentation quality.
```

**示例效果：**

![企业网络拓扑图](images/network-glass-01.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Corporate Professional | 企业正式风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加 SD-WAN 覆盖网络和分支办公室连接
- 增加无线网络层（AP控制器、Guest WiFi隔离）
- 加入网络监控和流量分析节点（NetFlow, SNMP）

**标签**: `#technical-diagram` `#network` `#enterprise` `#security`

---

## Prompt 2: 家庭实验室网络

> 技术爱好者的 HomeLab 网络和服务器配置

**Prompt:**

```text
A network topology diagram for a tech enthusiast's home lab setup. Show: ISP modem → pfSense router/firewall (with VLANs) → managed switch (Ubiquiti) distributing to: VLAN 10 - Home network (laptops, phones, smart TV), VLAN 20 - IoT devices (cameras, sensors, smart home), VLAN 30 - Lab network (Proxmox cluster with 3 nodes running: TrueNAS storage, Docker host with 20+ containers, Pi-hole DNS, Home Assistant, Plex media server, Grafana monitoring), VLAN 40 - Guest network (isolated). WireGuard VPN tunnel for remote access. UniFi access points for WiFi. NAS with 10GbE connection to Proxmox. Show container services as small icons inside the Docker host. Include bandwidth labels (1Gbps, 10Gbps, 2.5Gbps). Hand-drawn sketch style with graph paper background, colored pencil network icons, playful annotations, hobbyist notebook aesthetic with warmth and personality, cable colors matching VLAN colors.
```

**示例效果：**

![家庭实验室网络图](images/network-02.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Hand-drawn Sketch | 手绘草图风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加 Kubernetes (k3s) 集群节点详情
- 增加自动化备份路径（本地 + 异地 + 云）
- 加入功耗和散热标注（适合机架规划）

**标签**: `#technical-diagram` `#network` `#homelab` `#selfhosted`

---

## Prompt 3: 云 VPN 混合网络

> 多地办公的混合云 VPN 互联架构

**Prompt:**

```text
A network topology diagram showing hybrid cloud VPN architecture connecting multiple sites. Center: AWS Transit Gateway as hub. Spokes connecting to: Corporate HQ (Site-to-Site VPN, 1Gbps), Branch Office 1 in Shanghai (IPsec tunnel), Branch Office 2 in Singapore (Direct Connect), Azure VNet (VPN peering for SaaS services), GCP VPC (for ML workloads). Each site shows its local network simplified (LAN, servers). Transit Gateway routes between all VPCs: Production VPC, Development VPC, Shared Services VPC. Show route tables and security group rules as annotations. Redundant VPN tunnels (primary/failover) between sites. Latency labels between regions (HQ-Shanghai: 180ms, HQ-AWS: 5ms). Dark theme with neon accents, deep black background, sites as glowing islands connected by bright colored VPN tunnels (green=active, orange=standby), data flow particles animating along paths, futuristic global network operations center aesthetic.
```

**示例效果：**

![云 VPN 混合网络图](images/network-03.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Dark Neon Tech | 暗色科技感 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加全球地图背景，按真实地理位置布局
- 增加流量监控和带宽利用率指标
- 加入 DNS 解析和服务发现架构

**标签**: `#technical-diagram` `#network` `#vpn` `#hybrid-cloud`

---

## Prompt 4: 零信任网络架构

> 基于零信任原则的现代企业安全架构

**Prompt:**

```text
A network topology diagram illustrating Zero Trust Architecture (ZTA) implementation. No traditional perimeter - instead show: Identity Provider (Okta/Azure AD) as central trust broker, Policy Engine evaluating every request, Policy Enforcement Points (PEPs) at every resource boundary. User devices (laptop, mobile) → Device Trust Agent (checks posture: patched, encrypted, managed) → Identity verification (MFA, biometric) → Policy Decision Point (evaluates context: user, device, location, time, risk score) → micro-segmented resources each behind their own PEP. Resources shown as isolated segments: SaaS apps, internal apps, databases, APIs, file storage. East-west traffic between resources also passes through policy enforcement. Show denied connections as red X marks. Trust score visualization (0-100) for each session. Modern gradient style with deep blue-to-purple gradient, security shields as icons, trust verification checkpoints as glowing green gates, denied access as red barriers, clean futuristic cybersecurity presentation aesthetic with glass-morphism panels.
```

**示例效果：**

![零信任网络架构图](images/network-04.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Modern Gradient | 渐变现代风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加 SASE (Secure Access Service Edge) 组件
- 增加与传统 VPN 架构的对比视图
- 加入合规审计日志流和威胁检测集成

**标签**: `#technical-diagram` `#network` `#zero-trust` `#security`

---

## Prompt 5: CDN 分发架构

> 全球 CDN 内容分发网络的边缘节点架构

**Prompt:**

```text
A network topology diagram showing global CDN (Content Delivery Network) architecture. Center: Origin servers (multi-region) with object storage. Middle ring: Regional edge caches (PoPs) in major cities: US-East, US-West, Europe-West, Asia-Pacific, distributed around the origin. Outer ring: Edge locations (100+ small nodes) closest to users. Show request flow: User → nearest edge (DNS geo-routing) → cache HIT returns immediately OR cache MISS → regional PoP → cache HIT OR MISS → origin pull. Include: DNS resolver with GeoDNS/Anycast routing, TLS termination at edge, HTTP/2 and QUIC protocol labels, cache invalidation purge signal from origin broadcasting to all nodes, real-time analytics collector at each PoP. Performance annotations: edge hit ratio 95%, TTFB < 50ms. Isometric 3D perspective with soft lighting, globe-like layout showing geographic distribution, translucent layers for caching tiers, data packets shown as small glowing orbs flowing along paths, clean modern tech blog illustration style.
```

**示例效果：**

![CDN 分发架构图](images/network-05.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Isometric 3D | 等轴测立体 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加视频流媒体的自适应码率 (ABR) 分发路径
- 增加 DDoS 防护和 WAF 在边缘的过滤逻辑
- 加入边缘计算 (Edge Functions/Workers) 的处理能力展示

**标签**: `#technical-diagram` `#network` `#cdn` `#performance`

---

## 🔗 相关推荐

- [云基础设施图](cloud-infra.md) - 云架构设计
- [系统架构图](architecture.md) - 整体架构设计
- [分层堆叠图](layer-stack.md) - 协议栈分层
- [数据流图](data-flow.md) - 数据管道可视化
- [象限图](quadrant.md) - 技术选型评估
