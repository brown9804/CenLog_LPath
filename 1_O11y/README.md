# Observability Notes

----------

Costa Rica

Belinda Brown, belindabrownr04@gmail.com

[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[brown9804](https://github.com/brown9804)

Aug, 2022

----------

`Observability is valuable for troubleshooting and identifying the underlying reasons behind problems or issues.`

  ![image](https://github.com/brown9804/Obs_Mon_LPath/assets/24630902/eebe5c5a-9b3e-4a96-9604-aa3b89c4b597)

## Content 

<!-- TOC -->

- [Observability Notes](#observability-notes)
  - [Content](#content)
  - [Observability data categories](#observability-data-categories)
  - [Grafana](#grafana)

<!-- /TOC -->

## Observability data categories 

* [IT Focus](https://acceldataio.medium.com/a-guide-to-evaluating-data-observability-tools-5589ad9d35ed)

  <img width="697" alt="image" src="https://github.com/brown9804/CenLog_LPath/assets/24630902/ba8fbad6-459d-4c2d-a4fb-807b3107730b">
  
## Grafana 

`Compose and scale observability with one or all pieces of the stack`

  ![image](https://github.com/brown9804/CenLog_LPath/assets/24630902/68be031a-aab4-4cea-b614-d10296f2741a)

- [Grafana - OSS vs Cloud](https://grafana.com/oss-vs-cloud/)
- [Grafana - Install Grafana on macOS](https://grafana.com/docs/grafana/latest/setup-grafana/installation/mac/), and see tutorial of [How to Setup on Mac](https://www.youtube.com/watch?v=CYEpiVybM8c)

## Grafana OSS Stack

| Product | Use | Pros | Cons | 
| --- |  --- |  --- |  --- | 
| [Grafana](https://grafana.com/oss/grafana/) | Grafana is the leading open source visualization and dashboarding platform that allows you to `query, visualize, alert on, and understand your data no matter where it’s stored.`    |  - **Customizable dashboards**: Grafana offers a wide range of customization options to create visually appealing and interactive dashboards that can be tailored to specific requirements. <br/> - **Integrations**: Grafana supports integration with various data sources, such as databases, cloud platforms, and monitoring tools, allowing for centralized monitoring and visualization of data from multiple sources. <br/> - **Community support**: As an open-source tool, Grafana has a large and active community of users and developers who contribute to its development, provide support, and share plugins and extensions. <br/> [reference](https://www.trustradius.com/products/grafana/reviews?qs=pros-and-cons#reviews)    |   - **Steep learning curve**: Grafana can be complex to set up and configure, especially for users who are new to monitoring and visualization tools. <br/> - **Limited data processing capabilities**: While Grafana excels in data visualization, it has limited data processing capabilities compared to dedicated data analysis tools. <br/> - **Limited alerting capabilities**: Although Grafana provides basic alerting functionalities, it may not be as comprehensive or advanced as specialized monitoring and alerting tools. <br/> [reference](https://www.softwareadvice.com/reporting-tools/grafana-profile/reviews/)   |
| [Grafana Loki](https://grafana.com/oss/loki/) | Loki is a horizontally scalable, highly available, multi-tenant `log aggregation system` using the same powerful data model as Prometheus.  |  1. Lightweight and efficient: Grafana Loki is designed to have a minimal footprint and efficient resource usage, making it suitable for resource-constrained environments. <br/> 2. Seamless integration with Grafana: Loki integrates seamlessly with Grafana, allowing users to easily create visualizations and dashboards using log data alongside other data sources. <br/> 3. Scalable and distributed architecture: Loki is built to handle high volumes of log data and can be scaled horizontally to accommodate growing needs. Its distributed architecture enables efficient querying and indexing for large-scale deployments. <br/> [reference](https://www.linkedin.com/pulse/why-you-should-using-loki-grafana-your-logging-needs-pankaj-salunkhe) | 1. Limited long-term log storage: Loki is primarily focused on indexing and querying recent log entries, which may not be suitable for long-term retention of log data. Additional solutions or archiving may be required for long-term storage needs. <br/> 2. Lack of advanced log analysis features: While Loki offers powerful log aggregation and indexing capabilities, it may not provide advanced log analysis features out of the box. Users may need to integrate Loki with other tools or build custom solutions for more advanced log analysis requirements. <br/> 3. Learning curve for new users: Getting started with Grafana Loki may require some learning and familiarization, especially for users new to the Grafana ecosystem or log aggregation in general. Users may need to invest time in understanding the concepts and configuration of Loki to effectively utilize its features. <br/> [reference](https://www.trustradius.com/products/grafana-loki/reviews?qs=pros-and-cons#reviews) | 
| [Grafana Mimir](https://grafana.com/oss/mimir/) | Mimir is the most `scalable open source metrics storage`. It lets you scale to 1 billion active series and beyond, with high availability, multi-tenancy, durable storage, and blazing fast query performance over long periods of time.   |      |      |
| [Grafana OnCall](https://grafana.com/oss/oncall/) | Grafana OnCall is an `easy-to-use on-call management tool` built to help teams improve their `collaboration and resolve incidents faster`.    |      |      |
| [Grafana Tempo](https://grafana.com/oss/tempo/) |   Grafana Tempo is a distributed tracing backend that lets you scale `tracing as far as possible` with minimal operational cost and less complexity than ever before.   |      |      |
| [Grafana Agent](https://grafana.com/oss/agent/) | Grafana Agent is a `telemetry collector` for sending `metrics, logs, and trace` data to the opinionated Grafana observability stack.    |      |      |
| [Grafana k6](https://k6.io/)  | k6 is a developer-centric, extensible `performance testing tool` built to be intuitive, flexible, and powerful.    |      |      |
| [Prometheus](https://grafana.com/oss/prometheus/) | Prometheus is an open source `monitoring system` developed. Prometheus is the de facto standard for `metrics-based observability` in `cloud native environments` and for `Kubernetes`   |      |      |
| [Grafana Faro](https://grafana.com/oss/faro/) |  Grafana Faro is a project for `frontend application observability`. It includes a highly configurable web SDK that `instruments browser frontend applications to capture observability signals`, so you can monitor web application performance, discover frontend errors, and perform real user monitoring (RUM) while respecting their privacy.   |      |      |
| [Grafana Pyroscope](https://grafana.com/oss/pyroscope/) |   Grafana Pyroscope is an open source continuous `profiling tool` that provides `insights into resource usage to optimize application performance`.   |      |      |
| [Grafana Beyla](https://grafana.com/oss/beyla-ebpf/)  |   Beyla is an open source `eBPF auto-instrumentation tool` that is now in public preview. It `reports span information` for basic transactions as well as `RED metrics (Rate-Errors-Duration)` for both `Linux HTTP/S and gRPC services` — all without requiring any code modification.   |      |      |
| [Grafana Tanka](https://grafana.com/oss/tanka/) |   Grafana Tanka is the `robust configuration utility for your Kubernetes cluster`, powered by the Jsonnet language.   |      |      |
| [Graphite](https://grafana.com/oss/graphite/) |   Graphite is a `scalable monitoring system for time series data`.    |      |      |
| [OpenTelemetry](https://grafana.com/oss/opentelemetry/) |  OpenTelemetry is a `collection of tools, APIs, and SDKs` to instrument, generate, collect, and export telemetry data, in order to `analyze software performance and behavior`    |      |      |






