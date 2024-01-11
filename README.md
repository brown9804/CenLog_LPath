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

| Observability Backends | Definition | Pros | Cons |
| --- | --- | --- | --- | 
| [Honeycomb](https://www.honeycomb.io/blog/all-in-on-opentelemetry)  |    Honeycomb organizes your telemetry data for fast, accurate exploration from the same UI, regardless of data type, allowing you debug issues for a single user or complex patterns across multiple users and services.     |
| [Lightstep](https://github.com/lightstep) |   Monitoring, observability, and incident response for the world’s most reliable systems       |
| [Jaeger](https://www.jaegertracing.io/)  | It provides deep visibility into the flow of requests and transactions as they traverse through various services within a complex architecture. |
| [DataDog](https://docs.datadoghq.com/opentelemetry/) |  OpenTelemetry and DataDog are both used for monitoring applications. While OpenTelemetry is an open source observability framework, DataDog is a cloud-monitoring SaaS service, [reference](https://signoz.io/blog/opentelemetry-vs-datadog/#:~:text=OpenTelemetry%20and%20DataDog%20are%20both,%2C%20metrics%2C%20and%20traces). Allows customers to ingest all metrics, traces and logs across applications, infrastructure and third-party service, [reference](https://www.chaossearch.io/blog/pros-cons-datadog-log-analytics#:~:text=Datadog%20allows%20customers%20to%20ingest,popular%20among%20fast%2Dgrowing%20companies.)   |
| [ZipKin](https://zipkin.io/) |Zipkin is a distributed tracing system. **It helps gather timing data needed to troubleshoot latency problems in service architectures. Features include both the collection and lookup of this data**. If you have a trace ID in a log file, you can jump directly to it, [reference](https://greyamp.medium.com/what-is-zipkin-and-how-does-it-work-86a628e56a2f)        |
| [Prometheus](https://prometheus.io/) |  Prometheus is an essential tool for monitoring, and a key component in observability platforms for cloud-native environments. Simplifies integrations with Kubernetes-based environments compared to other monitoring tools. Prometheus works well for recording any purely numeric time series. It fits both machine-centric monitoring as well as monitoring of highly dynamic service-oriented architectures. In a world of microservices, its support for multi-dimensional data collection and querying is a particular strength., [reference](https://prometheus.io/docs/introduction/overview/#:~:text=Prometheus%20works%20well%20for%20recording,querying%20is%20a%20particular%20strength.)     | 
| [Splunk](https://www.splunk.com/)  | It is able to find useful information within organizations' data without users having to identify it themselves. It saves searches and tags that it recognizes as important information, which helps organizations make their systems smarter, [reference](https://www.splunk.com/en_us/pdfs/resources/solution-guide/splunk-for-observability.pdf). And also, [Key Benefits and Features](https://www.fortinet.com/resources/cyberglossary/what-is-splunk#:~:text=Key%20benefits%20of%20Splunk%20include%3A&text=It%20is%20able%20to%20find,organizations%20make%20their%20systems%20smarter.) |
| [Signoz](https://signoz.io/) |    SigNoz leverages the power of ClickHouse, a columnar database.       |


- [OpenTelemetry code instrumentation](https://opentelemetry.io/docs/instrumentation/) is supported for many popular programming languages, [more details on Observability Agent](https://docs.fusion-reactor.com/Getting-started/GSOTel/)

  <img width="744" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/837e2c42-a29c-411a-b0e8-b0adc5302201">

  <img width="742" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/2344144c-07fa-4303-ad63-7346d993da58">

- [The Basics of Distributed Tracing](https://www.youtube.com/watch?v=uxT032OxVOA)

  <img width="1512" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/bf3d22b6-270d-46dd-a524-f9c90619c497">

- [Introduction to EDA & Tracing Challenges](https://www.youtube.com/watch?v=u9oBD5pqDig)

  <img width="1441" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/301c5c0f-eada-4c35-83e5-3be9e0c83c40">

- [How Does Distributed Tracing Work With an Event Broker?](https://www.youtube.com/watch?v=q4035-O4bww)

  <img width="833" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/09697172-a9ea-4c5e-8c91-41d972602c50">

  <img width="983" alt="image" src="https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/7b8a4517-0eb9-42a6-bd5f-56a7072e3bc2">

