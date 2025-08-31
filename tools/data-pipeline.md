# Data Pipeline Architecture # 数据管道架构

Design and implement a scalable data pipeline for: $ARGUMENTS # 设计并实现可扩展的数据管道

Create a production-ready data pipeline including: # 创建生产就绪的数据管道，包括：

1. **Data Ingestion**: # 数据摄取
   - Multiple source connectors (APIs, databases, files, streams) # 多种数据源连接器（API、数据库、文件、流）
   - Schema evolution handling # 模式演进处理
   - Incremental/batch loading # 增量/批量加载
   - Data quality checks at ingestion # 摄取时的数据质量检查
   - Dead letter queue for failures # 失败处理的死信队列

2. **Transformation Layer**: # 转换层
   - ETL/ELT architecture decision # ETL/ELT架构决策
   - Apache Beam/Spark transformations
   - Data cleansing and normalization
   - Feature engineering pipeline
   - Business logic implementation

3. **Orchestration**:
   - Airflow/Prefect DAGs
   - Dependency management
   - Retry and failure handling
   - SLA monitoring
   - Dynamic pipeline generation

4. **Storage Strategy**:
   - Data lake architecture
   - Partitioning strategy
   - Compression choices
   - Retention policies
   - Hot/cold storage tiers

5. **Streaming Pipeline**:
   - Kafka/Kinesis integration
   - Real-time processing
   - Windowing strategies
   - Late data handling
   - Exactly-once semantics

6. **Data Quality**:
   - Automated testing
   - Data profiling
   - Anomaly detection
   - Lineage tracking
   - Quality metrics and dashboards

7. **Performance & Scale**:
   - Horizontal scaling
   - Resource optimization
   - Caching strategies
   - Query optimization
   - Cost management

Include monitoring, alerting, and data governance considerations. Make it cloud-agnostic with specific implementation examples for AWS/GCP/Azure.
