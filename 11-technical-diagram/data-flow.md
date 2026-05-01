# 📊 数据流图

> ETL 管道、数据血缘、流处理架构的数据流可视化。

**所属分类**: [技术图表](README.md)  
**Prompt 数量**: 5 条  
**难度等级**: ⭐⭐⭐ 高级

---

## Prompt 1: ETL 数据管道

> 企业数据仓库的经典 ETL 批处理管道

**Prompt:**

```text
A data flow diagram showing a classic ETL pipeline for enterprise data warehousing. Left-to-right flow with clear stages: Sources (5 source systems: MySQL OLTP database, Salesforce CRM API, Google Analytics, CSV file uploads, SAP ERP) → Extract (Apache Airflow DAGs scheduling extractions, showing parallel extraction arrows) → Staging Area (raw data landing zone in S3, schema-on-read) → Transform (dbt models with transformation steps: cleansing, deduplication, normalization, business logic, aggregation shown as stacked processing nodes) → Load (Snowflake data warehouse with bronze/silver/gold medallion layers) → Serve (BI dashboards in Tableau, ad-hoc queries in Jupyter, reverse ETL back to Salesforce). Data quality gates between each stage (green checkmarks or red X). Volume annotations on arrows (10GB/day, 500K records). Schedule annotations (daily 2AM, hourly, real-time). Clean whiteboard style with light background, pipeline stages as colored columns, data sources as distinct icons, friendly educational diagram suitable for data engineering documentation.
```

**示例效果：**

![ETL 数据管道图](images/flowchart-dark-01.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1920×1080 | 超宽横版适合管道流 |
| 风格 | Whiteboard Sketch | 白板教学风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 改为 ELT 模式（先 Load 后 Transform），突出 Snowflake 计算下推
- 添加数据血缘追踪（从源到报表的完整链路）
- 加入数据目录和元数据管理层

**标签**: `#technical-diagram` `#data-flow` `#etl` `#data-warehouse`

---

## Prompt 2: 实时流处理架构

> 基于 Kafka 的实时事件流处理平台

**Prompt:**

```text
A data flow diagram showing real-time streaming architecture for an e-commerce platform. Event producers on left: Web clickstream (JavaScript SDK), Mobile app events, IoT sensors (inventory RFID), Transaction service (order events), Third-party webhooks. All feed into Apache Kafka cluster (3 brokers, show partitioned topics: clicks, orders, inventory, users). Stream processing layer: Kafka Streams and Apache Flink jobs performing: real-time sessionization, fraud detection (ML model scoring), inventory alerts, recommendation updates, metric aggregation. Multiple consumers/sinks on right: Real-time dashboard (Grafana), Elasticsearch for search indexing, Redis for caching computed features, S3 for cold storage archival, notification service triggering alerts. Show consumer groups and offset tracking. Backpressure indicators on slow consumers. Dark theme with neon accents, black background, Kafka topics as glowing green channels, data streams as flowing particle effects in cyan, processing nodes as pulsing purple hexagons, real-time data engineering aesthetic with sense of motion and velocity.
```

**示例效果：**

![实时流处理架构图](images/data-flow-02.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Dark Neon Tech | 暗色科技感 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加 Schema Registry 和数据契约管理
- 增加死信队列 (DLQ) 和错误处理路径
- 加入 Exactly-once 语义保证的机制标注

**标签**: `#technical-diagram` `#data-flow` `#streaming` `#kafka`

---

## Prompt 3: ML 特征工程管道

> 机器学习特征存储和在线/离线特征计算

**Prompt:**

```text
A data flow diagram showing ML Feature Store architecture with dual compute paths. Left: Raw data sources (user behavior logs, transaction history, product catalog, external data). Two parallel paths diverge: Offline path (top): Spark batch jobs → feature computation (user_purchase_frequency_30d, product_popularity_score, user_segment) → materialized to Feature Store offline storage (Hive/Delta Lake) → used for model training (notebook icon). Online path (bottom): Kafka streams → Flink real-time feature computation (session_click_count, cart_value_current, time_since_last_action) → Feature Store online storage (Redis/DynamoDB low-latency) → served to ML model inference endpoint. Feature Store in center connects both paths with feature sync mechanism. Feature registry/catalog showing feature metadata, versioning, and lineage. Model serving receives features from online store for real-time predictions. Modern gradient style with deep blue-to-purple background, offline path in cool blue tones, online path in warm orange tones, Feature Store as central golden hub, smooth flowing connections, ML engineering blog illustration quality.
```

**示例效果：**

![ML 特征工程管道图](images/data-flow-03.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Modern Gradient | 渐变现代风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加特征漂移监控和告警
- 增加 A/B 测试的特征变体管理
- 加入 Feature Store 作为数据产品的治理视图

**标签**: `#technical-diagram` `#data-flow` `#ml` `#feature-store`

---

## Prompt 4: 数据湖架构

> 基于 Medallion 架构的现代数据湖分层设计

**Prompt:**

```text
A data flow diagram showing modern Data Lakehouse architecture using Medallion (Bronze/Silver/Gold) pattern. Left: diverse data sources feeding in (structured: PostgreSQL, MySQL; semi-structured: JSON APIs, Parquet files; unstructured: PDFs, images, logs). Bronze layer (raw): data lands as-is with metadata tagging, append-only, partitioned by ingestion date, stored in Delta Lake format on cloud object storage. Transformation arrows with processing annotations. Silver layer (cleaned): schema enforcement, deduplication, data quality rules applied (Great Expectations), standardized formats, slowly changing dimensions handled. Gold layer (business): aggregated metrics, dimension tables, feature tables, materialized views optimized for specific use cases (marketing analytics, finance reporting, ML training). Cross-cutting concerns shown as vertical bars on right: data catalog (Unity Catalog), access control (column-level security), lineage tracking, cost management. Isometric 3D perspective with layered platforms rising like terraced levels, bronze colored warm/raw, silver metallic and clean, gold premium and polished, beautiful architectural visualization with depth and materiality.
```

**示例效果：**

![数据湖架构图](images/data-flow-04.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Isometric 3D | 等轴测立体 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加 Data Mesh 的域导向数据产品视图
- 增加 Iceberg/Hudi 表格式的时间旅行和快照管理
- 加入数据共享和跨组织数据交换层

**标签**: `#technical-diagram` `#data-flow` `#data-lake` `#lakehouse`

---

## Prompt 5: CDC 变更数据捕获管道

> 基于 Debezium 的实时数据库同步管道

**Prompt:**

```text
A data flow diagram showing Change Data Capture (CDC) pipeline using Debezium. Source databases (3 systems): PostgreSQL (orders service, with WAL replication slot), MySQL (user service, with binlog), MongoDB (product catalog, with oplog). Each database has a Debezium connector (shown as a bridge/adapter component) capturing INSERT/UPDATE/DELETE events in real-time. Events flow into Kafka topics (one topic per table, showing message format: before/after state, operation type, timestamp). Stream processing with Kafka Connect sink connectors and Flink: Elasticsearch sink (for search indexing with 2s delay), Snowflake sink (for analytics with micro-batch), Redis sink (for cache invalidation), another PostgreSQL sink (for read replica pattern). Show schema evolution handling: schema registry validates changes, incompatible changes trigger alert. Dead letter queue for failed events. Monitoring overlay: lag metrics, throughput per connector. Blueprint engineering style with navy background, database sources as cylinder icons with white outlines, Debezium connectors as bridge components in cyan, Kafka topics as horizontal channel strips, precise technical engineering documentation, monospace annotations showing message formats.
```

**示例效果：**

![CDC 变更数据捕获管道图](images/data-flow-05.png)

**参数说明：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 尺寸 | 1536×1024 | 横版宽幅 |
| 风格 | Blueprint Engineering | 工程蓝图风 |
| 模型 | GPT-Image-2 | 推荐 |

**变体建议：**

- 添加 Outbox Pattern 保证事件发布和数据库事务的一致性
- 增加全量初始同步 + 增量 CDC 的混合策略
- 加入多租户场景下的数据路由和过滤规则

**标签**: `#technical-diagram` `#data-flow` `#cdc` `#debezium`

---

## 🔗 相关推荐

- [系统架构图](architecture.md) - 整体架构设计
- [云基础设施图](cloud-infra.md) - 云平台部署
- [ER 实体关系图](er-diagram.md) - 数据库模型
- [时序图](sequence.md) - 服务交互时序
- [分层堆叠图](layer-stack.md) - 技术栈分层
