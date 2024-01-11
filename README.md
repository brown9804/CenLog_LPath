# Observability & Monitoring Learning Path

----------

Costa Rica

Belinda Brown, belindabrownr04@gmail.com

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[brown9804](https://github.com/brown9804)

Aug, 2022

----------

## Wiki 

- [What is Observability?](https://www.ibm.com/topics/observability)

  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/41a16f1b-7468-4588-82a9-d52aad5b5799)

- [What is Monitoring?](https://www.splunk.com/en_us/blog/learn/it-monitoring.html)

  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/2e23c3d4-fa1a-410c-8100-976985a62de2)

- [What is SRE (site reliability engineering)?](https://www.redhat.com/en/topics/devops/what-is-sre), to understand difference between DevOps [click here](https://jelvix.com/blog/sre-vs-devops)

  <img width="945" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/875b0794-ab5a-469c-b4d3-6ed56a44aa77">
  
- [Observability vs Monitoring](https://www.computer.org/publications/tech-news/trends/observability-vs-monitoring-the-key-differences-devops-should-know/)

  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/eebe5c5a-9b3e-4a96-9604-aa3b89c4b597)
  
  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/47f021dd-5c66-4cc4-812e-82043af9537c)

- [Observability vs Monitoring - The difference explained with an example](https://signoz.io/blog/observability-vs-monitoring/)

  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/a6976e6a-7700-4575-aecc-fe678d4c59b4)

- [Observability vs Monitoring vs Telemetry: Understanding the Key Differences](https://cribl.io/blog/observability-vs-monitoring-vs-telemetry/)
- [What is OpenTelemetry?](https://www.youtube.com/watch?v=jt5HLptVvbM) provides an overview of OpenTelemetry. A [beginner’s guide](https://faun.pub/opentelemetry-d71d369c83d7) to OpenTelemetry. <br/>
`OpenTelemetry is a collection of APIs, SDKs, and client libraries used to generate telemetry data from your application code`

  <img width="1510" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/510c002b-e0ab-40a7-8166-af9e5e4c2e34">

  <img width="1226" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/33282fc4-9e5c-4947-b2c6-07a36e36e864">

- [How Does Open Telemetry Work?](https://www.youtube.com/watch?v=YwyfYfgjG0w), look [OpenTelemetry as a Service](https://medium.com/@magstherdev/opentelemetry-as-a-service-497068b81f7c). 

  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/5da3a80d-2cf9-49da-8450-04a975aeccf9), 

  <img width="1080" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/6edf6a2a-4dbc-45d3-8615-17ad467913dd">

  <img width="1221" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/76ee4572-6774-4242-8dd1-78eebc954632">

  <img width="726" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/8dad1b3b-51a6-4652-90ba-b4e53bcb77e8">

| UX Rate | Data Type | Observability Backends | Definition | Pros | Cons |
| --- | --- | --- | --- | --- | --- | 
|[4.9 :star:](https://www.getapp.com/development-tools-software/a/honeycomb/)| - [Metrics](https://docs.honeycomb.io/getting-data-in/metrics/) <br/> - [Traces](https://docs.honeycomb.io/getting-data-in/opentelemetry-overview/) <br/> - [Logs](https://docs.honeycomb.io/getting-data-in/logs/) <br/> | [Honeycomb](https://www.honeycomb.io/blog/all-in-on-opentelemetry)  |    Honeycomb organizes your telemetry data for fast, accurate exploration from the same UI, regardless of data type, allowing you debug issues for a single user or complex patterns across multiple users and services.     | - **High-Resolution Data**: HoneyComb captures detailed data for precise troubleshooting, allowing for granular insights. <br/> - **Dynamic Sampling**: Its adaptive sampling feature ensures efficient data collection without overwhelming storage and costs. <br/> - **Collaborative Debugging**: HoneyComb's shared workspaces promote team collaboration and faster issue resolution. [reference](https://thectoclub.com/tools/honeycomb-review/) | - **Learning Curve**: HoneyComb may have a slight learning curve for users unfamiliar with observability concepts. <br/> - **Limited Integrations**: While it offers integrations, it may not have as extensive a library as some other observability tools. <br/> - **Cost Consideration**: Depending on data volume, the pricing structure can become a factor for budget-conscious teams. [reference](https://thectoclub.com/tools/honeycomb-review/) | 
| [4.8 :star:](https://www.featuredcustomers.com/vendor/lightstep) | - [Traces](https://docs.lightstep.com/docs/view-traces) <br/> - [Logs](https://docs.lightstep.com/docs/explore-logs) <br/> | [Lightstep](https://github.com/lightstep) |   Monitoring, observability, and incident response for the world’s most reliable systems       | - **Distributed tracing**: Lightstep provides detailed visibility into complex distributed systems, allowing you to trace requests across various services, microservices, and infrastructure components.  <br/> - **Real-time monitoring**: It offers real-time insights into system performance, latency, and errors, helping you identify and resolve issues quickly. <br/> - **Root cause analysis**: Lightstep enables you to analyze and understand the root causes of performance problems, making it easier to optimize and improve system performance. <br/> - **Collaboration and sharing**: The platform allows teams to collaborate by sharing traces, dashboards, and insights, facilitating effective communication and problem-solving. <br/> - **Scalability**: Lightstep is designed to handle large-scale systems, making it suitable for organizations with complex and distributed architectures. <br/> [reference](https://www.getapp.com/it-management-software/a/lightstep/) | - **Complexity**: Setting up and configuring Lightstep can be complex, especially for organizations with intricate systems and multiple services. <br/> - **Cost**: Lightstep can be relatively expensive compared to other observability tools, especially for small or budget-limited organizations. <br/> - **Learning curve**: The platform may have a learning curve for users who are not familiar with distributed tracing concepts and observability practices. <br/> - **Integration limitations**: Although Lightstep supports various programming languages and frameworks, some integrations may not be as extensive or seamless as desired. [reference](https://www.getapp.com/it-management-software/a/lightstep/) |
| [❔⭐](https://uptrace.dev/blog/distributed-tracing-tools.html#jaeger)| - [Traces](https://www.aspecto.io/blog/jaeger-tracing-the-ultimate-guide/) |[Jaeger](https://www.jaegertracing.io/)  | It provides deep visibility into the flow of requests and transactions as they traverse through various services within a complex architecture. | - **Open-source**: Jaeger is an open-source project, which means it is freely available and can be customized and extended to meet specific requirements. <br/> - **Distributed tracing**: Jaeger provides detailed visibility into complex distributed systems, allowing you to trace requests and understand the flow across various services and components. <br/> - **Scalability**: It is designed to handle large-scale systems, making it suitable for organizations with complex and highly distributed architectures. <br/>- **Community support**: Being an open-source project, Jaeger has an active community that contributes to its development and provides support through forums, documentation, and other resources. - **Integration**: Jaeger supports various programming languages and frameworks, making it compatible with a wide range of applications and services.[reference](https://gethelios.dev/blog/jaeger-vs-helios-which-one-should-you-choose/) <br/> | - **Setup and configuration**: Setting up and configuring Jaeger can be complex, especially for organizations with intricate systems and multiple services. <br/> - **Resource consumption**: Jaeger's detailed tracing capabilities can generate a significant amount of data, which may require additional resources and storage capacity. <br/> - **Learning curve**: Using Jaeger effectively may require a learning curve, especially for users who are not familiar with distributed tracing concepts and observability practices. <br/> - **Limited features**: While Jaeger provides core tracing functionality, it may have fewer advanced features compared to some commercial tracing solutions. [reference](https://www.airplane.dev/blog/open-source-apm-tools) <br/> | 
|[4.6 ⭐](https://www.getapp.com/it-management-software/a/datadog-cloud-monitoring/reviews/)| - [Metrics](https://docs.datadoghq.com/metrics/) <br/> -[Traces](https://docs.datadoghq.com/tracing/trace_pipeline/) <br/> - [Logs](https://docs.datadoghq.com/logs/) | [DataDog](https://docs.datadoghq.com/opentelemetry/) |  OpenTelemetry and DataDog are both used for monitoring applications. While OpenTelemetry is an open source observability framework, DataDog is a cloud-monitoring SaaS service, [reference](https://signoz.io/blog/opentelemetry-vs-datadog/#:~:text=OpenTelemetry%20and%20DataDog%20are%20both,%2C%20metrics%2C%20and%20traces). Allows customers to ingest all metrics, traces and logs across applications, infrastructure and third-party service, [reference](https://www.chaossearch.io/blog/pros-cons-datadog-log-analytics#:~:text=Datadog%20allows%20customers%20to%20ingest,popular%20among%20fast%2Dgrowing%20companies.)   | - **Comprehensive monitoring**: Datadog offers a wide range of monitoring capabilities, including infrastructure monitoring, application performance monitoring (APM), log management, and more. <br/> - **Ease of use**: The platform is known for its user-friendly interface and intuitive navigation, making it easy to set up and configure monitoring for various systems and services. <br/> - **Integrations**: Datadog has extensive integrations with popular technologies, frameworks, and cloud providers, allowing you to monitor and analyze data from multiple sources within a single platform. <br/> - **Real-time alerting**: Datadog provides customizable alerting and notification features, enabling you to set up real-time alerts based on various metrics and thresholds. <br/> - **Scalability**: The platform is designed to handle large-scale environments and can scale with your organization's growth. <br/> [reference](https://www.peerspot.com/products/datadog-pros-and-cons) | - **Cost**: Datadog can be relatively expensive, especially for organizations with a large number of monitored resources or high data ingestion rates. <br/> - **Learning curve**: While Datadog is user-friendly, mastering all of its features and integrations may require some time and effort, particularly for users who are new to monitoring and observability. <br/> - **Limited log management features**: Although Datadog provides log management capabilities, some users may find the features and functionality to be less robust compared to dedicated log management tools. <br/> - **UI customization**: While the Datadog interface is generally well-designed, some users may find limitations in terms of customizing dashboards and visualizations to their specific preferences. <br/> [reference](https://www.capterra.com/p/135453/Datadog-Cloud-Monitoring/reviews/) | 
| [ZipKin](https://zipkin.io/) |Zipkin is a distributed tracing system. **It helps gather timing data needed to troubleshoot latency problems in service architectures. Features include both the collection and lookup of this data**. If you have a trace ID in a log file, you can jump directly to it, [reference](https://greyamp.medium.com/what-is-zipkin-and-how-does-it-work-86a628e56a2f)        |
| [Prometheus](https://prometheus.io/) |  Prometheus is an essential tool for monitoring, and a key component in observability platforms for cloud-native environments. Simplifies integrations with Kubernetes-based environments compared to other monitoring tools. Prometheus works well for recording any purely numeric time series. It fits both machine-centric monitoring as well as monitoring of highly dynamic service-oriented architectures. In a world of microservices, its support for multi-dimensional data collection and querying is a particular strength., [reference](https://prometheus.io/docs/introduction/overview/#:~:text=Prometheus%20works%20well%20for%20recording,querying%20is%20a%20particular%20strength.)     | 
| [Splunk](https://www.splunk.com/)  | It is able to find useful information within organizations' data without users having to identify it themselves. It saves searches and tags that it recognizes as important information, which helps organizations make their systems smarter, [reference](https://www.splunk.com/en_us/pdfs/resources/solution-guide/splunk-for-observability.pdf). And also, [Key Benefits and Features](https://www.fortinet.com/resources/cyberglossary/what-is-splunk#:~:text=Key%20benefits%20of%20Splunk%20include%3A&text=It%20is%20able%20to%20find,organizations%20make%20their%20systems%20smarter.) |
| [Signoz](https://signoz.io/) |    SigNoz leverages the power of ClickHouse, a columnar database.       |


- [OpenTelemetry code instrumentation](https://opentelemetry.io/docs/instrumentation/) is supported for many popular programming languages, [more details on Observability Agent](https://docs.fusion-reactor.com/Getting-started/GSOTel/)

  <img width="744" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/837e2c42-a29c-411a-b0e8-b0adc5302201">

  <img width="742" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/2344144c-07fa-4303-ad63-7346d993da58">

- [Telemetry with OpenTelemetry, Prometheus and Jaeger](https://medium.com/@guilospanck/telemetry-with-opentelemetry-prometheus-and-jaeger-46a2d9dec86b)

  <img width="817" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/880b1806-36b2-4197-a7b4-aed3c5a5ccaf">

- [The Basics of Distributed Tracing](https://www.youtube.com/watch?v=uxT032OxVOA)

  <img width="1512" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/bf3d22b6-270d-46dd-a524-f9c90619c497">

- [Introduction to EDA & Tracing Challenges](https://www.youtube.com/watch?v=u9oBD5pqDig)

  <img width="1441" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/301c5c0f-eada-4c35-83e5-3be9e0c83c40">

- [How Does Distributed Tracing Work With an Event Broker?](https://www.youtube.com/watch?v=q4035-O4bww)

  <img width="833" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/09697172-a9ea-4c5e-8c91-41d972602c50">

  <img width="983" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/7b8a4517-0eb9-42a6-bd5f-56a7072e3bc2">

