# Monitoring Azure Resources  
----------

Costa Rica

Belinda Brown, belindabrownr04@gmail.com

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[brown9804](https://github.com/brown9804)

Aug, 2022

----------

`Azure Monitor and Log Analytics collectively offer a robust solution for monitoring Azure resources. While Azure Monitor provides a lot of features including aggregation of logs, real-time insights and performance metrics, Log Analytics allows advanced query capabilities and extensive log data analysis.`

> Each resource has it owns Azure Monitor schema see the example below, we can set alarms based on metrics

<img width="1728" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/5b73cdb7-d22e-4c1a-80c8-79a471b04bec">


<!-- TOC -->

- [Monitoring Azure Resources](#monitoring-azure-resources)
  - [Azure Monitor](#azure-monitor)
  - [Azure Log Analytics](#azure-log-analytics)
  - [Azure Analysis Services](#azure-analysis-services)
  - [Network configuration (Vnet/subnet)](#network-configuration-vnetsubnet)
  - [Logic App Standard](#logic-app-standard)
  - [Function App](#function-app)
  - [SQL Server + DB](#sql-server--db)
  - [Data Lake](#data-lake)
  - [Data Factory](#data-factory)
  - [WebApp](#webapp)

<!-- /TOC -->

## Azure Monitor 

- [Overview](https://learn.microsoft.com/en-us/azure/azure-monitor/overview)

<img width="900" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/7dcd0959-db55-4c45-8654-6292a19f0bd7">

<img width="900" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/cc2448be-0d6d-476e-8d95-ee9e1cd6d5f5">


## Azure Log Analytics 

- [Log Analytics tutorial](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-tutorial)
  
<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/30315059-14e1-43b1-a998-4faf1dbdeb08">

- [Azure Log Analytics: the Basics and a Quick Tutorial](https://www.exabeam.com/explainers/log-management/azure-log-analytics-the-basics-and-a-quick-tutorial/)
- [Overview of Log Analytics in Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-overview)
- [Using Azure Log Analytics in Power BI](https://learn.microsoft.com/en-us/power-bi/transform-model/log-analytics/desktop-log-analytics-overview)

## Azure Analysis Services

- [Analysis Services tools](https://learn.microsoft.com/en-us/analysis-services/tools-and-applications-used-in-analysis-services?view=azure-analysis-services-current)
  
<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/a5b620c5-19ae-4e68-9b92-1e87f1b177ab">

- [Azure - Setting Up Azure Analysis Service (AAS)](https://microsoft-bitools.blogspot.com/2017/05/azure-setting-up-azure-analysis-server.html)
- [Use Cases for Azure Analysis Services](https://www.sqlchick.com/entries/2016/11/29/use-cases-for-azure-analysis-services)

## 4 Golden Signals 

| Golden Signal | Hint | |
| --- | --- | --- | 
| Errors | Rate of failed requests | <img width="250" alt="24630902-444113d0-c84f-49aa-89b3-a9cd4cdf2af4" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/444113d0-c84f-49aa-89b3-a9cd4cdf2af4"> |
| Latency | Amount of time to service a request (performance) | <img width="250" alt="24630902-cd4a44d7-b84d-4e5b-ac20-9652b6b27569" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/cd4a44d7-b84d-4e5b-ac20-9652b6b27569"> |
| Saturation | How close are you to 100% utilization? | <img width="250" alt="24630902-7b16ce93-3e96-43f2-af16-1116ff063e0c" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/7b16ce93-3e96-43f2-af16-1116ff063e0c"> | 
| Traffic | Number of: <br/> - httpRequests <br/> - sessions <br/> - transactionsPerSec | <img width="250" alt="24630902-e8a61fa8-e615-4a6d-aba0-fce454843e5d" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/e8a61fa8-e615-4a6d-aba0-fce454843e5d"> | 

## Network configuration (Vnet/subnet)

- [Monitoring Azure virtual network](https://learn.microsoft.com/en-us/azure/virtual-network/monitor-virtual-network)
- [Azure Virtual Network (VNet) monitoring integration insights](https://www.site24x7.com/help/azure/virtual-network-monitoring.html#metrics)
- [Deep dive into managing and monitoring your Azure networks](https://www.youtube.com/watch?v=htzaJ2xc9EM&t=110s)

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/7c6cc2cf-24ca-409c-9817-f5a39275859a">

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/944be647-077c-4604-8841-78bb86221486">

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/789c5ad8-3e6f-49a3-a992-7c0b11767650">

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/7501080b-e56c-4b90-8536-33ae5d001ade">

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/4c888749-16c2-4326-899b-e3b5b198ca92">

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/26de0298-36ea-4fac-a661-477c13a7e2c1">

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/12b694fe-4fa4-40a9-8b9c-9960d893626c">

- [What is Azure Network Watcher?](https://learn.microsoft.com/en-us/azure/network-watcher/network-watcher-overview)

![image](https://github.com/brown9804/CenLog_LPath/assets/24630902/d4eb365b-834f-4e60-9254-482ffb0c76df)


## Logic App Standard 

- [Monitoring Azure Logic Apps (Standard) with Azure Monitor Logs (Preview)](https://techcommunity.microsoft.com/t5/azure-integration-services-blog/monitoring-azure-logic-apps-standard-with-azure-monitor-logs/ba-p/3746881)
- [Monitor and collect diagnostic data for workflows in Azure Logic Apps](https://learn.microsoft.com/en-us/azure/logic-apps/monitor-workflows-collect-diagnostic-data?tabs=consumption)
- [Monitor workflow run status, review trigger and workflow run history, and set up alerts in Azure Logic Apps](https://learn.microsoft.com/en-us/azure/logic-apps/monitor-logic-apps?tabs=consumption)

## Function App 

- [Monitoring Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/monitor-functions?tabs=portal)
- [How to configure monitoring for Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/configure-monitoring?tabs=v2)

## SQL Server + DB 

- [Monitor Azure SQL Database with Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-sql/database/monitoring-sql-database-azure-monitor?view=azuresql)
- [Monitor Azure SQL Database with metrics and alerts](https://learn.microsoft.com/en-us/azure/azure-sql/database/monitoring-metrics-alerts?view=azuresql-db)
- [Monitor and performance tuning in Azure SQL Database and Azure SQL Managed Instance](https://learn.microsoft.com/en-us/azure/azure-sql/database/monitor-tune-overview?view=azuresql)

## Data Lake 

- [Monitor Azure Data Lake Store](https://stackoverflow.com/questions/50324427/monitor-azure-data-lake-store)
- [Monitoring Azure Blob Storage](https://learn.microsoft.com/en-us/azure/storage/blobs/monitor-blob-storage?tabs=azure-portal)
  
| Golden Signal | Metric / Alerting |
| --- | --- | 
| Errors: Rate of failed requests | Most common errors <br/> List 10 most common errors over the last X days.  |  
| Errors: Rate of failed requests | Operations causing most errors  <br/> List top 10 operations causing the most errors over the last X days.  |  
| Latency: Amount of time to service a request (performance) | Operations with the highest latency <br/> List top 10 operations with the longest end to end latency over the last X days.  |

~~~
// Errors 
// Most common errors 
// List 10 most common errors over the last X days. 
StorageBlobLogs
| where TimeGenerated > ago({number_of_days}d) and StatusText !contains "Success"
| summarize count() by StatusText
| top 10 by count_ desc
~~~

~~~
// Errors 
// Operations causing most errors 
// List top 10 operations causing the most errors over the last X days. 
StorageBlobLogs
| where TimeGenerated > ago({number_of_days}d) and StatusText !contains "Success"
| summarize count() by OperationName
| top 10 by count_ desc
~~~

~~~
// Latency
// Operations with the highest latency 
// List top 10 operations with the longest end to end latency over the last X days. 
StorageBlobLogs
| where TimeGenerated > ago({number_of_days}d)
| top 10 by DurationMs desc
| project TimeGenerated, OperationName, DurationMs, ServerLatencyMs, ClientLatencyMs = DurationMs - ServerLatencyMs
~~~

## Data Factory

- [Create alerts to proactively monitor your data factory pipelines](https://azure.microsoft.com/en-us/blog/create-alerts-to-proactively-monitor-your-data-factory-pipelines/)
- [Monitor and Alert Data Factory by using Azure Monitor](https://learn.microsoft.com/en-us/azure/data-factory/monitor-using-azure-monitor)
- [Visually monitor Azure Data Factory](https://learn.microsoft.com/en-us/azure/data-factory/monitor-visually)
- [Data Factory metrics and alerts](https://learn.microsoft.com/en-us/azure/data-factory/monitor-metrics-alerts)

## WebApp 

- [Web Apps](https://azure.microsoft.com/en-us/products/app-service/web)
- [App Service overview](https://learn.microsoft.com/en-us/azure/app-service/overview)
