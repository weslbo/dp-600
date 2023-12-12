# Implement and manage semantic models (20–25%)

## Design and build semantic models

- Choose a storage mode, including Direct Lake

  - [Semantic model modes in the Power BI service](https://learn.microsoft.com/en-us/power-bi/connect-data/service-dataset-modes-understand)
  - [Manage storage mode in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-storage-mode)
  - [Direct Lake](https://learn.microsoft.com/en-us/power-bi/enterprise/directlake-overview)
  - [Analyze query processing for Direct Lake datasets](https://learn.microsoft.com/en-us/power-bi/enterprise/directlake-analyze-qp)
  - [How direct lake mode works with Power BI reporting](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-pbi-reporting)
  - [Default Power BI semantic models in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/semantic-models)

- Identify use cases for DAX Studio and Tabular Editor 2

  - [External tools in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-external-tools)
  - [Power BI implementation planning: User tools and devices](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-user-tools-devices)
  - [Power BI implementation planning: Data-level auditing](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-auditing-monitoring-data-level-auditing)
  - [Power BI usage scenarios: Advanced data model management](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-usage-scenario-advanced-data-model-management)
  - [Power BI usage scenarios: Enterprise content publishing](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-usage-scenario-enterprise-content-publishing)

- Implement a star schema for a semantic model

  - [Understand star schema and the importance for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/star-schema)
  - [Slowly changing dimensions](https://en.wikipedia.org/wiki/Slowly_changing_dimension)

- Implement relationships, such as bridge tables and many-to-many
  relationships

  - [Many-to-many relationship guidance](https://learn.microsoft.com/en-us/power-bi/guidance/relationships-many-to-many)

- Write calculations that use DAX variables and functions, such as
  iterators, table filtering, windowing, and information functions

  - [Use DAX iterator functions in Power BI Desktop models](https://learn.microsoft.com/en-us/training/modules/dax-power-bi-iterator-functions/)
  - [Modify DAX filter context in Power BI Desktop models](https://learn.microsoft.com/en-us/training/modules/dax-power-bi-modify-filter/)
  - [WINDOW](https://learn.microsoft.com/en-us/dax/window-function-dax)
  - [WINDOW](https://dax.guide/window/)
  - [Window Functions](https://powerdobs.nl/blog/new-in-dax-window-functions/)
  - [Information functions](https://learn.microsoft.com/en-us/dax/information-functions-daxs)

- Implement calculation groups, dynamic strings, and field parameters

  - [Create calculation groups](https://learn.microsoft.com/en-us/power-bi/transform-model/calculation-groups)
  - [Create dynamic format strings for measures](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-dynamic-format-strings)
  - [Let report readers use field parameters to change visuals (preview)](https://learn.microsoft.com/en-us/power-bi/create-reports/power-bi-field-parameters)

- Design and build a large format dataset

  - [Large semantic models in Power BI Premium](https://learn.microsoft.com/en-us/power-bi/enterprise/service-premium-large-models)

- Design and build composite models that include aggregations

  - [Use composite models in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-composite-models)
  - [Composite model guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/composite-model-guidance)
  - [User-defined aggregations](https://learn.microsoft.com/en-us/power-bi/transform-model/aggregations-advanced)
  - [Automatic aggregations](https://learn.microsoft.com/en-us/power-bi/enterprise/aggregations-auto)

- Implement dynamic row-level security and object-level security

  - [Row-level security (RLS) with Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-admin-rls)
  - [Row-level security (RLS) guidance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/guidance/rls-guidance)
  - [Object level security (OLS)](https://learn.microsoft.com/en-us/power-bi/enterprise/service-admin-ols?tabs=table)

- Validate row-level security and object-level security

  - See above

## Optimize enterprise-scale semantic models

- Implement performance improvements in queries and report visuals

  - [Optimization guide for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/power-bi-optimization)
  - [Optimize ribbon in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-optimize-ribbon)
  - [DirectQuery optimization scenarios with the Optimize ribbon](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-optimize-ribbon-scenarios)
  - [Use Performance Analyzer to examine report element performance in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-performance-analyzer)
  - [Power BI implementation planning: Data-level auditing](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-auditing-monitoring-data-level-auditing)

- Improve DAX performance by using DAX Studio

  - [Troubleshoot DAX performance by using DAX Studio](https://learn.microsoft.com/en-us/training/modules/use-tools-optimize-power-bi-performance/3-troubleshoot-dax-performance-use-dax-studio)

- Optimize a semantic model by using Tabular Editor 2

  - [Best Practice Analyzer](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-auditing-monitoring-data-level-auditing)

- Implement incremental refresh

  - [Incremental refresh and real-time data for semantic models](https://learn.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-overview)
  - [Configure incremental refresh and real-time data](https://learn.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-configure)
  - [Advanced incremental refresh and real-time data with the XMLA endpoint](https://learn.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-xmla)
  - [Troubleshoot incremental refresh and real-time data](https://learn.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-troubleshoot)