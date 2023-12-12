# Prepare and serve data (40–45%)

## Create objects in a lakehouse or warehouse

- Ingest data by using a data pipeline, dataflow, or notebook

  - General
    - [Microsoft Fabric decision guide: copy activity, dataflow, or Spark](https://learn.microsoft.com/en-us/fabric/get-started/decision-guide-pipeline-dataflow-spark)
  - Data pipelines
    - [Quickstart: Create your first pipeline to copy data](https://learn.microsoft.com/en-us/fabric/data-factory/create-first-pipeline-with-sample-data)
    - [How to monitor activity in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-factory/monitor-data-factory)
    - [How to monitor data pipeline runs in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-factory/monitor-pipeline-runs)
    - [Migrate to Data Factory in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-factory/upgrade-paths)
    - [Data Factory end-to-end scenario: introduction and architecture](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-end-to-end-introduction)
    - [Activity overview](https://learn.microsoft.com/en-us/fabric/data-factory/activity-overview)
    - [How to copy data using copy activity](https://learn.microsoft.com/en-us/fabric/data-factory/copy-data-activity)
    - [Copy activity performance and scalability guide](https://learn.microsoft.com/en-us/fabric/data-factory/copy-activity-performance-and-scalability-guide)
    - [Parameters for Data Factory in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-factory/parameters)
    - [Concept: Data pipeline Runs](https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-runs)
    - [Templates for Data Factory in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-factory/templates)
    - [Incrementally load data from Data Warehouse to Lakehouse](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-incremental-copy-data-warehouse-lakehouse)
  - Dataflows
    - [What are dataflows?](https://learn.microsoft.com/en-us/power-query/dataflows/overview-dataflows-across-power-platform-dynamics-365)
    - [Ingest Data with Dataflows Gen2 in Microsoft Fabric](https://learn.microsoft.com/en-us/training/modules/use-dataflow-gen-2-fabric/)
    - [Quickstart: Create your first dataflow to get and transform data](https://learn.microsoft.com/en-us/fabric/data-factory/create-first-dataflow-gen2)
    - [A guide to learning Dataflows for Mapping Data Flow users](https://learn.microsoft.com/en-us/fabric/data-factory/guide-to-dataflows-for-mapping-data-flow-users)
    - [Getting from Dataflow Generation 1 to Dataflow Generation 2](https://learn.microsoft.com/en-us/fabric/data-factory/dataflows-gen2-overview)
    - [Data Factory Dataflow Gen2 limitations](https://learn.microsoft.com/en-us/fabric/data-factory/dataflow-gen2-limitations)
    - [Use a dataflow in a pipeline](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-dataflows-gen2-pipeline-activity)
    - [Pattern to incrementally amass data with Dataflow Gen2](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-setup-incremental-refresh-with-dataflows-gen2)
    - [What is Power Query?](https://learn.microsoft.com/en-us/power-query/power-query-what-is-power-query)
    - [On-premises data gateway considerations for data destinations in Dataflow Gen2](https://learn.microsoft.com/en-us/fabric/data-factory/gateway-considerations-output-destinations)
    - [Transform data with a dataflow in Data Factory](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-end-to-end-dataflow)
  - Notebooks
    - [Ingest data with Spark and Microsoft Fabric notebooks](https://learn.microsoft.com/en-us/training/modules/ingest-data-with-spark-fabric-notebooks/)
    - [Transform data by running a notebook](https://learn.microsoft.com/en-us/fabric/data-factory/notebook-activity)

- Create and manage shortcuts

  - [OneLake shortcuts](https://learn.microsoft.com/en-us/fabric/onelake/onelake-shortcuts)
  - [What are shortcuts in lakehouse?](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-shortcuts)
  - [Create a OneLake shortcut](https://learn.microsoft.com/en-us/fabric/onelake/create-onelake-shortcut)
  - [Access Fabric OneLake shortcuts in a Spark notebook](https://learn.microsoft.com/en-us/fabric/onelake/access-onelake-shortcuts) 
  - [Create an Azure Data Lake Storage Gen2 shortcut](https://learn.microsoft.com/en-us/fabric/onelake/create-adls-shortcut)
  - [Create an Amazon S3 shortcut](https://learn.microsoft.com/en-us/fabric/onelake/create-s3-shortcut)
  - [Real-Time Analytics: Create OneLake shortcuts](https://learn.microsoft.com/en-us/fabric/real-time-analytics/onelake-shortcuts?tabs=onelake-shortcut)
  - [Link your Dataverse environment to Microsoft Fabric and unlock deep insights](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/azure-synapse-link-view-in-fabric)
  - [Tables over shortcuts](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-and-delta-tables)

- Implement file partitioning for analytics workloads in a lakehouse

  - [Data partitioning guidance](https://learn.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning)
  - [Efficient Data Partitioning with Microsoft Fabric: Best Practices and Implementation Guide](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/efficient-data-partitioning-with-microsoft-fabric-best-practices/ba-p/3890097)
  - [Better together: the lakehouse and warehouse](https://learn.microsoft.com/en-us/fabric/data-warehouse/get-started-lakehouse-sql-analytics-endpoint)
  - [Configure Lakehouse in a copy activity](https://learn.microsoft.com/en-us/fabric/data-factory/connector-lakehouse-copy-activity)
  - [Configure Data Warehouse in a copy activity](https://learn.microsoft.com/en-us/fabric/data-factory/connector-data-warehouse-copy-activity)
  - [Get streaming data into lakehouse with Spark structured streaming](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-streaming-data)
  - [What is autotune for Apache Spark configurations in Fabric and how to enable and disable it?](https://learn.microsoft.com/en-us/fabric/data-engineering/autotune?tabs=sparksql)
  - [Implement medallion lakehouse architecture in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/onelake/onelake-medallion-lakehouse-architecture)
  - [The need for optimize write on Apache Spark](https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/optimize-write-for-apache-spark)

- Create views, functions, and stored procedures

  - [What is the SQL analytics endpoint for a Lakehouse?](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-sql-analytics-endpoint)
  - [Query using the visual query editor](https://learn.microsoft.com/en-us/fabric/data-warehouse/visual-query-editor)
  - [Query using the SQL query editor](https://learn.microsoft.com/en-us/fabric/data-warehouse/sql-query-editor)
  - [View data in the Data preview in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/data-preview)
  - [Transact-SQL reference (Database Engine)](https://learn.microsoft.com/en-us/sql/t-sql/language-reference?view=fabric&preserve-view=true)
  - [What are the SQL database functions?](https://learn.microsoft.com/en-us/sql/t-sql/functions/functions?view=fabric)
  - [CREATE PROCEDURE (Transact-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/statements/create-procedure-transact-sql?view=fabric)
  - [What is data warehousing in Microsoft Fabric?](https://learn.microsoft.com/en-us/fabric/data-warehouse/data-warehousing)
  - [How to use Stored procedure activity](https://learn.microsoft.com/en-us/fabric/data-factory/stored-procedure-activity)
  - [Tutorial: Transform data using a stored procedure](https://learn.microsoft.com/en-us/fabric/data-warehouse/tutorial-transform-data)

- Enrich data by adding new columns or tables

  - [Transform data with a dataflow in Data Factory](https://learn.microsoft.com/en-us/fabric/data-factory/tutorial-end-to-end-dataflow)

## Copy data

- Choose an appropriate method for copying data from a Fabric data
  source to a lakehouse or warehouse

  - [Microsoft Fabric decision guide: copy activity, dataflow, or Spark](https://learn.microsoft.com/en-us/fabric/get-started/decision-guide-pipeline-dataflow-spark)

- Copy data by using a data pipeline, dataflow, or notebook

  - see above

- Add stored procedures, notebooks, and dataflows to a data pipeline

  - [How to use Stored procedure activity](https://learn.microsoft.com/en-us/fabric/data-factory/stored-procedure-activity)
  - [Use the Dataflow activity to run a Dataflow Gen2](https://learn.microsoft.com/en-us/fabric/data-factory/dataflow-activity)
  - [Transform data by running a notebook](https://learn.microsoft.com/en-us/fabric/data-factory/notebook-activity)

- Schedule data pipelines, dataflows and notebooks

  - [Concept: Data pipeline Runs](https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-runs)
  - [Use the Invoke pipeline activity to run another pipeline](https://learn.microsoft.com/en-us/fabric/data-factory/invoke-pipeline-activity)

## Transform data

- Implement a data cleansing process

  - [What is the medallion lakehouse architecture?](https://learn.microsoft.com/en-us/azure/databricks/lakehouse/medallion)
  - [Organize a Fabric lakehouse using medallion architecture design](https://learn.microsoft.com/en-us/training/modules/describe-medallion-architecture/)
  - [Power BI usage scenarios: Advanced data preparation](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-usage-scenario-advanced-data-preparation)
  - [Use Python in Power Query Editor](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-python-in-query-editor)

- Implement a star schema for a lakehouse or warehouse, including Type 1
  and Type 2 slowly changing dimensions

  - [Understand star schema and the importance for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)
  - [Best practices for creating a dimensional model using dataflows](https://learn.microsoft.com/en-us/power-query/dataflows/best-practices-for-dimensional-model-using-dataflows)
  - [Populate slowly changing dimensions in Azure Synapse Analytics pipelines](https://learn.microsoft.com/en-us/training/modules/populate-slowly-changing-dimensions-azure-synapse-analytics-pipelines/)

- Implement bridge tables for a lakehouse or a warehouse

  - [Many-to-many relationship guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-many-to-many)

- Denormalize data

  - [Normalization vs. denormalization](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema#normalization-vs-denormalization)

- Aggregate or de-aggregate data

  - [User-defined aggregations](https://learn.microsoft.com/en-us/power-bi/transform-model/aggregations-advanced)
  - [Automatic aggregations](https://learn.microsoft.com/en-us/power-bi/enterprise/aggregations-auto)

- Merge or join data

  - [Append queries](https://learn.microsoft.com/en-us/power-query/append-queries)
  - [Merge queries overview](https://learn.microsoft.com/en-us/power-query/merge-queries-overview)
  - [Tutorial: Shape and combine data in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-shape-and-combine-data)
  - [One-to-one relationship guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-one-to-one)
  - [Many-to-many relationship guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-many-to-many)
  - [Active vs inactive relationship guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-active-inactive)

- Identify and resolve duplicate data, missing data, or null values

  - [Using the data profiling tools](https://learn.microsoft.com/en-us/power-query/data-profiling-tools)
  - [Working with duplicate values](https://learn.microsoft.com/en-us/power-query/working-with-duplicates)
  - [Dealing with errors in Power Query](https://learn.microsoft.com/en-us/power-query/dealing-with-errors)
  - [Replace values and errors](https://learn.microsoft.com/en-us/power-query/replace-values)

- Convert data types by using SQL or PySpark

  - [Data types in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/data-types)
  - [CAST and CONVERT (Transact-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/functions/cast-and-convert-transact-sql?view=fabric)
  - [Conversion Functions (Transact-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/functions/conversion-functions-transact-sql?view=fabric)
  - [PySpark – Cast Column Type With Examples](https://sparkbyexamples.com/pyspark/pyspark-cast-column-type/)

- Filter data

  - [Spark DataFrame Where Filter | Multiple Conditions](https://sparkbyexamples.com/spark/spark-dataframe-where-filter/)
  - [WHERE (Transact-SQL)](https://learn.microsoft.com/en-us/sql/t-sql/queries/where-transact-sql?view=fabric)
  - [Filter by values in a column](https://learn.microsoft.com/en-us/power-query/filter-values)

## Optimize performance

- Identify and resolve data loading performance bottlenecks in
  dataflows, notebooks, and SQL queries

  - [Copy activity performance and scalability guide](https://learn.microsoft.com/en-us/fabric/data-factory/copy-activity-performance-and-scalability-guide)
  - [On-premises data gateway considerations for data destinations in Dataflow Gen2](https://learn.microsoft.com/en-us/fabric/data-factory/gateway-considerations-output-destinations))
  - [Query insights in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/query-insights)
  - [Monitor connections, sessions, and requests using DMVs](https://learn.microsoft.com/en-us/fabric/data-warehouse/monitor-using-dmv)
  - [Billing and utilization reporting in Synapse Data Warehouse](https://learn.microsoft.com/en-us/fabric/data-warehouse/usage-reporting)

- Implement performance improvements in dataflows, notebooks, and SQL
  queries

  - [Troubleshoot pipelines for Data Factory in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-factory/pipeline-troubleshoot-guide)
  - [Statistics in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/statistics)
  - [Caching in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/caching)
  - [Burstable capacity in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/burstable-capacity)
  - [Smoothing and throttling in Fabric Data Warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/compute-capacity-smoothing-throttling)
  - [Workload management](https://learn.microsoft.com/en-us/fabric/data-warehouse/workload-management)
  - [Synapse Data Warehouse in Microsoft Fabric performance guidelines](https://learn.microsoft.com/en-us/fabric/data-warehouse/guidelines-warehouse-performance)

- Identify and resolve issues with Delta table file sizes

  - [Review Delta Lake table details with describe detail](https://learn.microsoft.com/en-us/azure/databricks/delta/table-details)
  - [Delta Lake table optimization and V-Order](https://learn.microsoft.com/en-us/fabric/data-engineering/delta-optimization-and-v-order?tabs=sparksql)
  - [Use table maintenance feature to manage delta tables in Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-table-maintenance)
  - [The need for optimize write on Apache Spark](https://learn.microsoft.com/en-us/azure/synapse-analytics/spark/optimize-write-for-apache-spark)
  - [Best practices](https://docs.delta.io/latest/best-practices.html)