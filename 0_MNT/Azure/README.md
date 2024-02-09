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

<!-- TOC -->

- [Monitoring Azure Resources](#monitoring-azure-resources)
  - [4 Golden Signals](#4-golden-signals)
  - [Azure Monitor](#azure-monitor)
  - [Azure Log Analytics](#azure-log-analytics)
  - [Azure Analysis Services](#azure-analysis-services)
- [Metrics \& Alerting](#metrics--alerting)
  - [Network configuration (Vnet/subnet)](#network-configuration-vnetsubnet)
  - [SQL Server + DB](#sql-server--db)
  - [DataLake](#datalake)
  - [Data Factory](#data-factory)
  - [App Service](#app-service)
    - [Logic App Standard](#logic-app-standard)
    - [Function App](#function-app)
    - [WebApp](#webapp)

<!-- /TOC -->

> Kusto Query Language (KQL), how to make [log queries in AzureMonitor](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-query-overview)

<img width="1728" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/5b73cdb7-d22e-4c1a-80c8-79a471b04bec">

## 4 Golden Signals 

Click [here](#monitoring-azure-resources) to go to the Content List

| Golden Signal | Hint | |
| --- | --- | --- | 
| Errors | Rate of failed requests | <img width="250" alt="24630902-444113d0-c84f-49aa-89b3-a9cd4cdf2af4" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/444113d0-c84f-49aa-89b3-a9cd4cdf2af4"> |
| Latency | Amount of time to service a request (performance) | <img width="250" alt="24630902-cd4a44d7-b84d-4e5b-ac20-9652b6b27569" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/cd4a44d7-b84d-4e5b-ac20-9652b6b27569"> |
| Saturation | How close are you to 100% utilization? | <img width="250" alt="24630902-7b16ce93-3e96-43f2-af16-1116ff063e0c" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/7b16ce93-3e96-43f2-af16-1116ff063e0c"> | 
| Traffic | Number of: <br/> - httpRequests <br/> - sessions <br/> - transactionsPerSec | <img width="250" alt="24630902-e8a61fa8-e615-4a6d-aba0-fce454843e5d" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/e8a61fa8-e615-4a6d-aba0-fce454843e5d"> | 

## Azure Monitor 

Click [here](#monitoring-azure-resources) to go to the Content List

- [Overview](https://learn.microsoft.com/en-us/azure/azure-monitor/overview)

<img width="900" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/7dcd0959-db55-4c45-8654-6292a19f0bd7">

<img width="900" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/cc2448be-0d6d-476e-8d95-ee9e1cd6d5f5">


## Azure Log Analytics 

Click [here](#monitoring-azure-resources) to go to the Content List

- [Log Analytics tutorial](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-tutorial)
  
<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/30315059-14e1-43b1-a998-4faf1dbdeb08">

- [Azure Log Analytics: the Basics and a Quick Tutorial](https://www.exabeam.com/explainers/log-management/azure-log-analytics-the-basics-and-a-quick-tutorial/)
- [Overview of Log Analytics in Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-overview)
- [Using Azure Log Analytics in Power BI](https://learn.microsoft.com/en-us/power-bi/transform-model/log-analytics/desktop-log-analytics-overview)

## Azure Analysis Services

Click [here](#monitoring-azure-resources) to go to the Content List

- [Analysis Services tools](https://learn.microsoft.com/en-us/analysis-services/tools-and-applications-used-in-analysis-services?view=azure-analysis-services-current)
  
<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/a5b620c5-19ae-4e68-9b92-1e87f1b177ab">

- [Azure - Setting Up Azure Analysis Service (AAS)](https://microsoft-bitools.blogspot.com/2017/05/azure-setting-up-azure-analysis-server.html)
- [Use Cases for Azure Analysis Services](https://www.sqlchick.com/entries/2016/11/29/use-cases-for-azure-analysis-services)

# Metrics & Alerting

## Network configuration (Vnet/subnet)

Click [here](#monitoring-azure-resources) to go to the Content List

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

| Golden Signal | Metric / Alerting  | 
| --- | --- | 
| Errors: Rate of failed requests | (-) No metric in place|
| Latency: Amount of time to service a request (performance) | (-) No metric in place |
| Saturation: How close are you to 100% utilization? | (-) No metric in place |
| Traffic: Number of: <br/> - httpRequests <br/> - sessions <br/> - transactionsPerSec | (-) No metric in place |

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/facc45b9-0b81-4cf0-88cb-222c863bfad2">

## SQL Server + DB 

Click [here](#monitoring-azure-resources) to go to the Content List

- [Monitor Azure SQL Database with Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-sql/database/monitoring-sql-database-azure-monitor?view=azuresql)
- [Monitor Azure SQL Database with metrics and alerts](https://learn.microsoft.com/en-us/azure/azure-sql/database/monitoring-metrics-alerts?view=azuresql-db)
- [Monitor and performance tuning in Azure SQL Database and Azure SQL Managed Instance](https://learn.microsoft.com/en-us/azure/azure-sql/database/monitor-tune-overview?view=azuresql)

| Golden Signal | Metric / Alerting  | 
| --- | --- | 
| Saturation: How close are you to 100% utilization? | Avg CPU usage in the last hour by resource name. Consistently high averages could indicate a customer needs to move to a larger SKU |
| Saturation: How close are you to 100% utilization? | Performance troubleshooting <br/> Potentially query or deadlock on the system that could lead to poor performance. |
| Traffic: Number of: <br/> - httpRequests <br/> - sessions <br/> - transactionsPerSec | Loading Data <br/> Monitor data loading in the last hour.  |

~~~
// Saturation
// Avg CPU usage 
// Avg CPU usage in the last hour by resource name. 
// consistently high averages could indicate a customer needs to move to a larger SKU
AzureMetrics
| where ResourceProvider == "MICROSOFT.SQL" // /DATABASES
| where TimeGenerated >= ago(60min)
| where MetricName in ('cpu_percent') 
| parse _ResourceId with * "/microsoft.sql/servers/" Resource  // subtract Resource name for _ResourceId
| summarize CPU_Maximum_last15mins = max(Maximum), CPU_Minimum_last15mins = min(Minimum), CPU_Average_last15mins = avg(Average) by Resource , MetricName
// ---------------- | --------------- | --------------

// Performance troubleshooting 
// Potentially query or deadlock on the system that could lead to poor performance. 
//potentially a query or deadlock on the system that could lead to poor performance
AzureMetrics
| where ResourceProvider == "MICROSOFT.SQL"
| where TimeGenerated >=ago(60min)
| where MetricName in ('deadlock')
| parse _ResourceId with * "/microsoft.sql/servers/" Resource // subtract Resource name for _ResourceId
| summarize Deadlock_max_60Mins = max(Maximum) by Resource, MetricName
~~~

~~~
Traffic
// Loading Data 
// Monitor data loading in the last hour. 
AzureMetrics
| where ResourceProvider == "MICROSOFT.SQL"
| where TimeGenerated >= ago(60min)
| where MetricName in ('log_write_percent')
| parse _ResourceId with * "/microsoft.sql/servers/" Resource// subtract Resource name for _ResourceId
| summarize Log_Maximum_last60mins = max(Maximum), Log_Minimum_last60mins = min(Minimum), Log_Average_last60mins = avg(Average) by Resource, MetricName
~~~

## DataLake 

Click [here](#monitoring-azure-resources) to go to the Content List

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
// ---------------- | --------------- | --------------

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

Click [here](#monitoring-azure-resources) to go to the Content List

- [Create alerts to proactively monitor your data factory pipelines](https://azure.microsoft.com/en-us/blog/create-alerts-to-proactively-monitor-your-data-factory-pipelines/)
- [Monitor and Alert Data Factory by using Azure Monitor](https://learn.microsoft.com/en-us/azure/data-factory/monitor-using-azure-monitor)
- [Visually monitor Azure Data Factory](https://learn.microsoft.com/en-us/azure/data-factory/monitor-visually)
- [Data Factory metrics and alerts](https://learn.microsoft.com/en-us/azure/data-factory/monitor-metrics-alerts)

| Golden Signal | Metric / Alerting  | 
| --- | --- | 
| Errors: Rate of failed requests | Activity runs Top 5 Failures <br/> Returns Top 5 Activitys failing with systemErrors.   |
| Errors: Rate of failed requests |  Pipeline runs Top 5 Failures <br/> Returns Top 5 pipelines failing with systemErrors. | 
| Errors: Rate of failed requests |  Trigger runs Top 5 Failures <br/> Returns Top 5 Triggers failing with systemErrors.  | 
| Saturation: How close are you to 100% utilization? | Activity Runs Availability <br/> Gives the availability of the Activity Runs. | 
| Saturation: How close are you to 100% utilization? | PipelineRuns Availability <br/> Gives the availability of the Pipeline Runs. |
| Saturation: How close are you to 100% utilization? | TriggerRuns Availability <br/> Gives the availability of the Trigger Runs.|

~~~
// Errors
// Activity runs Top 5 Failures 
// Returns Top 5 Activitys failing with systemErrors. 
let name = ADFActivityRun
| where Status != 'InProgress' and Status != 'Queued'
| where FailureType != 'UserError'
| summarize failureCount = countif(Status != 'Succeeded') by ActivityName
| top 5 by failureCount desc nulls last
| where failureCount != 0
| project ActivityName;
ADFActivityRun 
| where TimeGenerated >= ago(24h)
| where Status != 'InProgress' and Status != 'Queued'
| where FailureType != 'UserError'
| where ActivityName  in (name)
| summarize failureCount = countif(Status != 'Succeeded') by bin(TimeGenerated, 1h), ActivityName
| order by TimeGenerated asc
| render timechart
// ---------------- | --------------- | --------------

// Pipeline runs Top 5 Failures
// Returns Top 5 pipelines failing with systemErrors. 
let name = ADFPipelineRun
| where Status != 'InProgress' and Status != 'Queued'
| where FailureType != 'UserError'
| summarize failureCount = countif(Status != 'Succeeded') by PipelineName
| top 5 by failureCount desc nulls last
| where failureCount != 0
| project PipelineName;
ADFPipelineRun 
| where TimeGenerated >= ago(24h)
| where Status != 'InProgress' and Status != 'Queued'
| where FailureType != 'UserError'
| where PipelineName  in (name)
| summarize failureCount = countif(Status != 'Succeeded') by bin(TimeGenerated, 1h), PipelineName
| order by TimeGenerated asc
| render timechart
// ---------------- | --------------- | --------------

// Trigger runs Top 5 Failures 
// Returns Top 5 Triggers failing with systemErrors. 
let name = ADFTriggerRun
| where Status != 'Running' and Status != 'Waiting' and Status != 'WaitingOnDependency'
| where TriggerFailureType != 'UserError'
| summarize failureCount = countif(Status != 'Succeeded') by TriggerName
| top 5 by failureCount desc nulls last
| where failureCount != 0
| project TriggerName;
ADFTriggerRun 
| where TimeGenerated >= ago(24h)
| where Status != 'Running' and Status != 'Waiting' and Status != 'WaitingOnDependency'
| where TriggerFailureType != 'UserError'
| where TriggerName  in (name)
| summarize failureCount = countif(Status != 'Succeeded') by bin(TimeGenerated, 1h), TriggerName
| order by TimeGenerated asc
| render timechart
~~~

~~~
// Saturation
// Activity Runs Availability 
// Gives the availability of the Activity Runs. 
// To create an alert for this query, click '+ New alert rule'
ADFActivityRun
| where Status != 'InProgress' and Status != 'Queued'
| where FailureType != 'UserError'
| summarize availability = 100.00 - (100.00*countif(Status != 'Succeeded') / count())  by bin(TimeGenerated, 1h)), _ResourceId
| order by TimeGenerated asc
| render timechart
// ---------------- | --------------- | --------------

// PipelineRuns Availability 
// Gives the availability of the Pipeline Runs. 
// To create an alert for this query, click '+ New alert rule'
ADFPipelineRun
| where Status != 'InProgress' and Status != 'Queued'
| where FailureType != 'UserError'
| summarize availability = 100.00 - (100.00*countif(Status != 'Succeeded') / count())  by bin(TimeGenerated, 1h)), _ResourceId
| order by TimeGenerated asc
| render timechart
// ---------------- | --------------- | --------------

// TriggerRuns Availability 
// Gives the availability of the Trigger Runs. 
// To create an alert for this query, click '+ New alert rule'
ADFTriggerRun
| where Status != 'Running' and Status != 'Waiting' and Status != 'WaitingOnDependency'
| where TriggerFailureType != 'UserError'
| summarize availability = 100.00 - (100.00*countif(Status != 'Succeeded') / count())  by bin(TimeGenerated, 1h)), _ResourceId
| order by TimeGenerated asc
| render timechart
~~~

## App Service  

Click [here](#monitoring-azure-resources) to go to the Content List

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/4a7752a3-b98c-4a2d-a321-5f6915efdfb2">

### Logic App Standard 

Click [here](#monitoring-azure-resources) to go to the Content List


- [Monitoring Azure Logic Apps (Standard) with Azure Monitor Logs (Preview)](https://techcommunity.microsoft.com/t5/azure-integration-services-blog/monitoring-azure-logic-apps-standard-with-azure-monitor-logs/ba-p/3746881)
- [Monitor and collect diagnostic data for workflows in Azure Logic Apps](https://learn.microsoft.com/en-us/azure/logic-apps/monitor-workflows-collect-diagnostic-data?tabs=consumption)
- [Monitor workflow run status, review trigger and workflow run history, and set up alerts in Azure Logic Apps](https://learn.microsoft.com/en-us/azure/logic-apps/monitor-logic-apps?tabs=consumption)

| Golden Signal | Metric / Alerting  | 
| --- | --- | 
| Errors: Rate of failed requests | Failing dependencies <br/> Which 5 dependencies failed the most today?  |
| Errors: Rate of failed requests | Failed requests – top 10 <br/> What are the 3 slowest pages, and how slow are they? |
| Errors: Rate of failed requests | Failed operations <br/> Calculate how many times operations failed, and how many users were impacted. |
| Errors: Rate of failed requests | Exceptions causing request failures <br/> Find which exceptions led to failed requests in the past hour. |
| Latency: Amount of time to service a request (performance) | Response time buckets <br/> Show how many requests are in each performance-bucket.  |
| Latency: Amount of time to service a request (performance) | Response time trend <br/> Chart request duration over the last 12 hours.  | 
| Saturation: How close are you to 100% utilization? | Operations performance <br/> Calculate request count and duration by operations.  |
| Traffic: Number of: <br/> - httpRequests <br/> - sessions <br/> - transactionsPerSec | Request count trend <br/> Chart Request count over the last day.  |

~~~
// Errors
// Exceptions causing request failures 
// Find which exceptions led to failed requests in the past hour. 
requests
| where timestamp > ago(1h) and success == false
| join kind= inner (
exceptions
| where timestamp > ago(1h)
) on operation_Id
| project exceptionType = type, failedMethod = method, requestName = name, requestDuration = duration
// ---------------- | --------------- | --------------

// Failed operations 
// Calculate how many times operations failed, and how many users were impacted. 
// To create an alert for this query, click '+ New alert rule'
requests
| where success == false
| summarize failedCount=sum(itemCount), impactedUsers=dcount(user_Id) by operation_Name
| order by failedCount desc
// ---------------- | --------------- | --------------

// Failed requests – top 10 
// What are the 3 slowest pages, and how slow are they? 
requests
| where success == false
| summarize failedCount=sum(itemCount) by name
| top 10 by failedCount desc
| render barchart

// ---------------- | --------------- | --------------
// Failing dependencies 
// Which 5 dependencies failed the most today? 
dependencies
| where success == false
| summarize totalCount=sum(itemCount) by type
| top 5 by totalCount desc
~~~

~~~
// Latency
// Response time buckets 
// Show how many requests are in each performance-bucket. 
requests
| summarize requestCount=sum(itemCount), avgDuration=avg(duration) by performanceBucket
| order by avgDuration asc // sort by average request duration
| project-away avgDuration // no need to display avgDuration, we used it only for sorting results
| render barchart
// ---------------- | --------------- | --------------

// Response time trend 
// Chart request duration over the last 12 hours. 
// To create an alert for this query, click '+ New alert rule'
requests
| where timestamp > ago(12h) 
| summarize avgRequestDuration=avg(duration) by bin(timestamp, 10m) // use a time grain of 10 minutes
| render timechart
~~~

~~~
// Saturation 
// Operations performance 
// Calculate request count and duration by operations. 
// To create an alert for this query, click '+ New alert rule'
requests
| summarize RequestsCount=sum(itemCount), AverageDuration=avg(duration), percentiles(duration, 50, 95, 99) by operation_Name // you can replace 'operation_Name' with another value to segment by a different property
| order by RequestsCount desc // order from highest to lower (descending)
~~~

~~~
// Traffic 
// Request count trend 
// Chart Request count over the last day. 
// To create an alert for this query, click '+ New alert rule'
requests
| summarize totalCount=sum(itemCount) by bin(timestamp, 30m)
| render timechart
~~~

- [Sending Your Azure Application Insights Alerts to Team Sites using Azure Logic App](https://dailydotnettips.com/sending-your-azure-application-insights-alerts-to-team-sites-using-azure-logic-app/)
  
  <img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/3b5728d0-ec51-43b2-8ad0-a2bf12ee4bce">

### Function App 

Click [here](#monitoring-azure-resources) to go to the Content List

- [Monitoring Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/monitor-functions?tabs=portal)
- [How to configure monitoring for Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/configure-monitoring?tabs=v2)
  
| Golden Signal | Metric / Alerting  | 
| --- | --- | 
| Errors: Rate of failed requests | Exceptions causing request failures <br/> Find which exceptions led to failed requests in the past hour.  |
| Errors: Rate of failed requests | Failed operations <br/> Calculate how many times operations failed, and how many users were impacted.  | 
| Errors: Rate of failed requests | Failed requests – top 10 <br/> What are the 3 slowest pages, and how slow are they? |
| Errors: Rate of failed requests | Failing dependencies <br/> Which 5 dependencies failed the most today?  | 
| Latency: Amount of time to service a request (performance) | Response time trend <br/> Chart request duration over the last X hours.    |
| Latency: Amount of time to service a request (performance) | Response time buckets <br/> Show how many requests are in each performance-bucket. |
| Saturation: How close are you to 100% utilization? | Operations performance <br/> Calculate request count and duration by operations.  |
| Traffic: Number of: <br/> - httpRequests <br/> - sessions <br/> - transactionsPerSec | Request count trend <br/> Chart Request count over the last day.  |

~~~
// Errors
// Exceptions causing request failures 
// Find which exceptions led to failed requests in the past hour. 
requests
| where timestamp > ago(1h) and success == false
| join kind= inner (
exceptions
| where timestamp > ago(1h)
) on operation_Id
| project exceptionType = type, failedMethod = method, requestName = name, requestDuration = duration
// ---------------- | --------------- | --------------

// Failed operations 
// Calculate how many times operations failed, and how many users were impacted. 
// To create an alert for this query, click '+ New alert rule'
requests
| where success == false
| summarize failedCount=sum(itemCount), impactedUsers=dcount(user_Id) by operation_Name
| order by failedCount desc
// ---------------- | --------------- | --------------

// Failed requests – top 10 
// What are the 3 slowest pages, and how slow are they? 
requests
| where success == false
| summarize failedCount=sum(itemCount) by name
| top 10 by failedCount desc
| render barchart
// ---------------- | --------------- | --------------

// Failing dependencies 
// Which 5 dependencies failed the most today? 
dependencies
| where success == false
| summarize totalCount=sum(itemCount) by type
| top 5 by totalCount desc
~~~

~~~
// Latency
// Response time buckets 
// Show how many requests are in each performance-bucket. 
requests
| summarize requestCount=sum(itemCount), avgDuration=avg(duration) by performanceBucket
| order by avgDuration asc // sort by average request duration
| project-away avgDuration // no need to display avgDuration, we used it only for sorting results
| render barchart
// ---------------- | --------------- | --------------

// Response time trend 
// Chart request duration over the last 12 hours. 
// To create an alert for this query, click '+ New alert rule'
requests
| where timestamp > ago(12h) 
| summarize avgRequestDuration=avg(duration) by bin(timestamp, 10m) // use a time grain of 10 minutes
| render timechart

~~~

~~~
// Saturation
// Operations performance 
// Calculate request count and duration by operations. 
// To create an alert for this query, click '+ New alert rule'
requests
| summarize RequestsCount=sum(itemCount), AverageDuration=avg(duration), percentiles(duration, 50, 95, 99) by operation_Name // you can replace 'operation_Name' with another value to segment by a different property
| order by RequestsCount desc // order from highest to lower (descending)
~~~

~~~
// Traffic
// Request count trend 
// Chart Request count over the last day. 
// To create an alert for this query, click '+ New alert rule'
requests
| summarize totalCount=sum(itemCount) by bin(timestamp, 30m)
| render timechart
~~~

- [Monitoring Azure Functions with Application Insights](https://link.springer.com/chapter/10.1007/978-1-4842-5067-9_9)
- [How To Integrate Application Insights Into Azure Functions](https://www.c-sharpcorner.com/article/how-to-integrate-application-insights-into-azure-functions/)

<img width="600" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/a84b3b71-1b74-4dc9-b0ac-5dc85caa4014">


### WebApp 

Click [here](#monitoring-azure-resources) to go to the Content List

- [Web Apps](https://azure.microsoft.com/en-us/products/app-service/web)
- [App Service overview](https://learn.microsoft.com/en-us/azure/app-service/overview)

