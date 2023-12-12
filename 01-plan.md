# Plan, implement, and manage a solution for data analytics (10–15%)

## Plan a data analytics environment

- Identify requirements for a solution, including components, features,
  performance, and capacity stock-keeping units (SKUs)

  - [Microsoft Fabric concepts and licenses](https://learn.microsoft.com/en-us/fabric/enterprise/licenses)
  - [Power BI guidance documentation](https://learn.microsoft.com/en-us/power-bi/guidance/)
  - [Power BI Embedded with Microsoft Fabric](https://powerbi.microsoft.com/en-us/blog/power-bi-embedded-with-microsoft-fabric/)

- Recommend settings in the Fabric admin portal
  
  - [Microsoft Fabric documentation for admins](https://learn.microsoft.com/en-us/fabric/admin/)

- Choose a data gateway type
  
  - [What is an on-premises data gateway?](https://learn.microsoft.com/en-us/data-integration/gateway/)
  - [Guidance for deploying a data gateway for the Power BI service](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-deployment-guidance)
  - [On-premises data gateway in-depth](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-onprem-indepth)
  - [Manage on-premises data gateway high-availability clusters and load balancing](https://learn.microsoft.com/en-us/data-integration/gateway/service-gateway-high-availability-clusters)
  - [Manage security roles of an on-premises data gateway](https://learn.microsoft.com/en-us/data-integration/gateway/manage-security-roles)
  - [Add or remove a gateway data source](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-data-sources)
  - [Manage your data source - import and scheduled refresh](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-enterprise-manage-scheduled-refresh)
  - [Use custom data connectors with an on-premises data gateway](https://learn.microsoft.com/en-us/power-bi/connect-data/service-gateway-custom-connectors)
  - [Plan, scale, and maintain a business-critical gateway solution](https://learn.microsoft.com/en-us/data-integration/gateway/plan-scale-maintain)
  - [On-premises data gateway sizing](https://learn.microsoft.com/en-us/power-bi/guidance/gateway-onprem-sizing)
  - [What is a virtual network (VNet) data gateway (Preview)?](https://learn.microsoft.com/en-us/data-integration/vnet/overview)
  - [Virtual network data gateway architecture](https://learn.microsoft.com/en-us/data-integration/vnet/data-gateway-architecture)

- Create a custom Power BI report theme

  - [Use report themes in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-report-themes)

## Implement and manage a data analytics environment

- Implement workspace and item-level access controls for Fabric items

  - [Roles in workspaces in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/get-started/roles-workspaces)
  - [Give users access to workspaces](https://learn.microsoft.com/en-us/fabric/get-started/give-access-workspaces)
  - [Share items in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/get-started/share-items)

- Implement data sharing for workspaces, warehouses, and lakehouses

  - Workspaces
    - [Share Power BI reports and dashboards with coworkers and others](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-share-dashboards)
    - [Display the dashboards and reports that others have shared with me](https://learn.microsoft.com/en-us/power-bi/collaborate-share/end-user-shared-with-me)
    - [Request or grant access to shared dashboards or reports](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-request-access)
    - [Share a filtered Power BI report](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-share-reports)
    - [Troubleshoot issues sharing dashboards and reports](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-troubleshoot-sharing)
    - [Filter a report using query string parameters in the URL](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-url-filters)
    - [Ways to collaborate and share in Power BI](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-how-to-collaborate-distribute-dashboards-reports)
    - [View Power BI files in OneDrive and SharePoint](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-sharepoint-viewer)
  - Lakehouses
    - [How lakehouse sharing works](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-sharing)
    - [OneLake security](https://learn.microsoft.com/en-us/fabric/onelake/onelake-security)
    - [Get started securing your data in OneLake](https://learn.microsoft.com/en-us/fabric/onelake/get-started-security)
  - Warehouses
    - [Workspace roles in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/workspace-roles)
    - [Security for data warehousing in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/security)
    - [Share your warehouse and manage permissions](https://learn.microsoft.com/en-us/fabric/data-warehouse/share-warehouse-manage-permissions)
    - [SQL granular permissions in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-warehouse/sql-granular-permissions)
    - [Column-level security in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/column-level-security)
    - [Row-level security in Fabric data warehousing](https://learn.microsoft.com/en-us/fabric/data-warehouse/row-level-security)
  - Best practices
    - [Power BI implementation planning: Report consumer security planning](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-security-report-consumer-planning)
    - [Power BI implementation planning: Content creator security planning](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-security-content-creator-planning)
    - [Distribute Power BI content to external guest users using Microsoft Entra B2B](https://learn.microsoft.com/en-us/power-bi/guidance/whitepaper-azure-b2b-power-bi)
    - [Power BI usage scenarios](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-usage-scenario-overview)

- Manage sensitivity labels in semantic models and lakehouses
  
  - [Power BI implementation planning: Information protection for Power BI](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-info-protection)
  - [Information protection in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/governance/information-protection)
  - [Sensitivity labels in Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-overview)
  - [Enable sensitivity labels in Fabric](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-enable-data-sensitivity-labels)
  - [How to apply sensitivity labels in Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-apply-data-sensitivity-labels)
  - [Sensitivity label downstream inheritance](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-downstream-inheritance)
  - [Audit schema for sensitivity labels in Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-audit-schema)
  - [Data protection metrics report](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-data-protection-metrics-report)

- Configure Fabric-enabled workspace settings
  
  - [Create, configure, and use an environment in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/create-and-use-environment)
  - [Spark workspace administration settings in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/workspace-admin-settings)
  - [Configuring starter pools in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/configure-starter-pools)
  - [Billing and utilization reporting for Spark in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/billing-capacity-management-for-spark)
  - [How to create custom Spark pools in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/data-engineering/create-custom-spark-pools)
  - [Configure high concurrency mode for Fabric notebooks](https://learn.microsoft.com/en-us/fabric/data-engineering/configure-high-concurrency-session-notebooks)

- Manage Fabric capacity
  
  - [Microsoft Fabric concepts and licenses](https://learn.microsoft.com/en-us/fabric/enterprise/licenses)
  - [Buy a Microsoft Fabric subscription](https://learn.microsoft.com/en-us/fabric/enterprise/buy-subscription)
  - [Pause and resume your capacity](https://learn.microsoft.com/en-us/fabric/enterprise/pause-resume)
  - [Scale your capacity](https://learn.microsoft.com/en-us/fabric/enterprise/scale-capacity)
  - [The Fabric throttling policy](https://learn.microsoft.com/en-us/fabric/enterprise/throttling)
  - [Microsoft Fabric Capacity Metrics app](https://learn.microsoft.com/en-us/fabric/enterprise/metrics-app)
  - [Microsoft Fabric trial](https://learn.microsoft.com/en-us/fabric/get-started/fabric-trial)
  - [Configure and manage data engineering and data science settings for Fabric capacities](https://learn.microsoft.com/en-us/fabric/data-engineering/capacity-settings-management)

## Manage the analytics development lifecycle

- Implement version control for a workspace

  - [Lifecycle management documentation in Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/cicd/)
  - [Lakehouse deployment pipelines and git integration (Preview)](https://learn.microsoft.com/en-us/fabric/data-engineering/lakehouse-git-deployment-pipelines)

- Create and manage a Power BI Desktop project (.pbip)

  - [Power BI Desktop projects](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-overview)
  - [Power BI Desktop project dataset folder](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-dataset)
  - [Power BI Desktop project report folder](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-report)
  - [Power BI Desktop projects Git integration](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-git)
  - [Power BI Desktop projects Azure DevOps integration](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-azdo)
  - [Power BI Project (PBIP) and Azure DevOps build pipelines for continuous integration](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-build-pipelines)

- Plan and implement deployment solutions
  
  - [Introduction to deployment pipelines](https://learn.microsoft.com/en-us/fabric/cicd/deployment-pipelines/intro-to-deployment-pipelines)
  - [The deployment pipelines process](https://learn.microsoft.com/en-us/fabric/cicd/deployment-pipelines/understand-the-deployment-process)
  - [Create deployment rules](https://learn.microsoft.com/en-us/fabric/cicd/deployment-pipelines/create-rules)
  - [Automate your deployment pipeline by using APIs and Azure DevOps](https://learn.microsoft.com/en-us/fabric/cicd/deployment-pipelines/pipeline-automation)

- Perform impact analysis of downstream dependencies from lakehouses,
  data warehouses, dataflows, and semantic models

  - [Data lineage](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-data-lineage)
  - [Semantic model impact analysis](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-dataset-impact-analysis)
  - [Data source impact analysis](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-data-source-impact-analysis)

- Deploy and manage semantic models by using the XMLA endpoint

  - [Power BI usage scenarios: Advanced data model management](https://learn.microsoft.com/en-us/power-bi/guidance/powerbi-implementation-planning-usage-scenario-advanced-data-model-management)
  - [Semantic model connectivity with the XMLA endpoint](https://learn.microsoft.com/en-us/power-bi/enterprise/service-premium-connect-tools)
  - [Troubleshoot XMLA endpoint connectivity](https://learn.microsoft.com/en-us/power-bi/enterprise/troubleshoot-xmla-endpoint)
  - [Create perspectives](https://learn.microsoft.com/en-us/analysis-services/tutorial-tabular-1400/as-lesson-8-create-perspectives?view=asallproducts-allversions)
  - [ALM Toolkit](https://www.sqlbi.com/tools/alm-toolkit/)

- Create and update reusable assets, including Power BI template (.pbit)
  files, Power BI data source (.pbids) files, and shared semantic models

  - [Create and use report templates in Power BI Desktop](https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-templates)
  - [Use PBIDS files to get data](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources#use-pbids-files-to-get-data)
  - [Use semantic models across workspaces](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-across-workspaces)
  - [Semantic model description](https://learn.microsoft.com/en-us/power-bi/connect-data/service-dataset-description)
  - [Share access to a semantic model](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-share)
  - [Semantic model permissions](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-permissions)
  - [Manage semantic model access permissions](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-manage-access-permissions)
  - [Build permission for shared semantic models](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-build-permissions)
  - [Create reports based on semantic models from different workspaces](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-discover-across-workspaces)
  - [Copy reports from other workspaces](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-copy-reports)
  - [Control the use of semantic models across workspaces](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-admin-across-workspaces)
  - [Endorse your content](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-endorse-content)