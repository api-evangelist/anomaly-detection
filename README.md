# Anomaly Detection (anomaly-detection)
A curated collection of APIs, tools, and platforms for detecting anomalies in data streams, time series, and multivariate metrics. Covers cloud ML services, observability platforms, and open-source frameworks used for fraud detection, predictive maintenance, IoT monitoring, and security analytics.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Anomaly Detection, Artificial Intelligence, Data Science, Fraud Detection, Machine Learning, Monitoring, Observability, Outlier Detection, Pattern Recognition, Security, Time Series

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Azure AI Anomaly Detector
Azure AI Anomaly Detector is a managed REST API service that enables monitoring and detection of anomalies in time series data without requiring machine learning expertise. Supports univariate batch and streaming detection, multivariate detection using Graph Attention Networks for up to 300 correlated signals, and change-point detection. The service is being retired on 1 October 2026 in favor of Microsoft Fabric real-time intelligence.

**Human URL:** [https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview)

#### Tags:

 - Anomaly Detection, Azure, Machine Learning, Microsoft, Multivariate, Time Series, Univariate

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview)
- [APIReference](https://learn.microsoft.com/en-us/rest/api/anomalydetector/)
- [Quickstart](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/quickstarts/client-libraries)
- [Tutorials](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/tutorials/batch-anomaly-detection-powerbi)
- [GitHubRepository](https://github.com/microsoft/anomaly-detector)

### Elasticsearch Anomaly Detection API
Elasticsearch Machine Learning APIs provide a comprehensive suite of anomaly detection capabilities for time series data stored in Elasticsearch indices. Supports creating and managing anomaly detection jobs and datafeeds, accessing bucket, record, category, and influencer results, model snapshots, calendars, scheduled events, and forecasting. Part of the Elastic Stack ML feature set available in subscriptions.

**Human URL:** [https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html](https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html)

#### Tags:

 - Anomaly Detection, Elasticsearch, Machine Learning, Monitoring, Time Series

#### Properties

- [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html)
- [APIReference](https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-ad-apis.html)
- [GettingStarted](https://www.elastic.co/guide/en/machine-learning/current/ml-ad-overview.html)
- [GitHubOrganization](https://github.com/elastic)

### Datadog Anomaly Monitor API
Datadog's Monitors API supports anomaly detection monitors that identify unusual metric behavior using historical pattern analysis including trends, day-of-week, and time-of-day seasonality. Offers three detection algorithms — Basic, Agile (SARIMA), and Robust (seasonal-trend decomposition) — configurable via REST API. Available across regional endpoints for US, EU, AP1, AP2, GOV, US3, and US5 deployments.

**Human URL:** [https://docs.datadoghq.com/monitors/types/anomaly/](https://docs.datadoghq.com/monitors/types/anomaly/)

#### Tags:

 - Anomaly Detection, Datadog, Monitoring, Observability, Time Series

#### Properties

- [Documentation](https://docs.datadoghq.com/monitors/types/anomaly/)
- [APIReference](https://docs.datadoghq.com/api/latest/monitors/)
- [Authentication](https://docs.datadoghq.com/api/latest/authentication/)
- [GitHubOrganization](https://github.com/DataDog)

### AWS Lookout for Metrics
Amazon Lookout for Metrics is a fully managed ML service that automatically detects anomalies in business and operational data. It connects to data sources including Amazon S3, Amazon Redshift, Amazon CloudWatch, and SaaS applications, learns each metric's normal behavior, and sends alerts when anomalies are detected. Provides root cause analysis grouping related anomalies for faster diagnosis.

**Human URL:** [https://aws.amazon.com/lookout-for-metrics/](https://aws.amazon.com/lookout-for-metrics/)

#### Tags:

 - Amazon Web Services, Anomaly Detection, AWS, Business Metrics, Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/lookoutmetrics-welcome.html)
- [APIReference](https://docs.aws.amazon.com/lookoutmetrics/latest/api/Welcome.html)
- [GettingStarted](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/lookoutmetrics-gettingstarted.html)
- [Pricing](https://aws.amazon.com/lookout-for-metrics/pricing/)

### PyOD (Python Outlier Detection)
PyOD is a comprehensive and scalable Python library for detecting outliers/anomalies in multivariate data. It includes more than 40 detection algorithms including deep learning approaches (AutoEncoder, VAE), proximity-based methods (LOF, CBLOF), linear models (PCA, OCSVM), and ensemble methods (IForest, LOCI). Widely used in research and production for fraud detection, intrusion detection, medical anomaly detection, and data quality monitoring.

**Human URL:** [https://pyod.readthedocs.io/](https://pyod.readthedocs.io/)

#### Tags:

 - Anomaly Detection, Data Science, Machine Learning, Open Source, Outlier Detection, Python

#### Properties

- [Documentation](https://pyod.readthedocs.io/en/latest/)
- [APIReference](https://pyod.readthedocs.io/en/latest/pyod.html)
- [GitHubRepository](https://github.com/yzhao062/pyod)
- [SDK](https://pypi.org/project/pyod/)

## Common Properties

- [GitHubOrganization](https://github.com/api-evangelist/anomaly-detection)
- [BestPractices](https://pyod.readthedocs.io/en/latest/faq.html)
- [Blog](https://techcommunity.microsoft.com/t5/AI-Customer-Engineering-Team/Introducing-Azure-Anomaly-Detector-API/ba-p/490162)
- [JSONSchema — Anomaly Schema](json-schema/anomaly-detection-anomaly-schema.json)
- [JSONSchema — Time Series Schema](json-schema/anomaly-detection-time-series-schema.json)
- [JSONSchema — Detection Job Schema](json-schema/anomaly-detection-detection-job-schema.json)
- [Vocabulary](vocabulary/anomaly-detection-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Univariate Time Series Detection | Detect anomalies in a single time series metric using statistical algorithms, SARIMA models, and SR-CNN approaches for both batch and real-time streaming use cases. |
| Multivariate Detection | Identify anomalies across multiple correlated metrics simultaneously using graph attention networks and correlation analysis, capturing system-level failures invisible in individual metrics. |
| Streaming and Batch Modes | Support for both real-time streaming anomaly detection on incoming data points and batch retrospective analysis across historical datasets. |
| Change Point Detection | Identify structural breaks and trend changes in time series data beyond point anomalies, enabling detection of regime shifts and concept drift. |
| Root Cause Analysis | Group related anomalies and surface likely contributing factors to accelerate diagnosis and response. |
| Algorithm Diversity | Access to a wide range of detection algorithms from statistical methods to deep learning, including IForest, LOF, OCSVM, AutoEncoder, VAE, and SARIMA. |

## Use Cases

| Name | Description |
|------|-------------|
| Fraud Detection | Identify fraudulent transactions, account takeovers, and suspicious behavioral patterns in financial and e-commerce systems. |
| Predictive Maintenance | Detect early signs of equipment failure in industrial IoT systems by identifying anomalous sensor readings before breakdowns occur. |
| IT and Security Operations | Detect unusual network traffic, unauthorized access patterns, and security incidents in real time using behavioral baselines. |
| Business Metrics Monitoring | Alert on unexpected drops or spikes in KPIs such as revenue, conversion rates, user engagement, or API error rates. |
| Healthcare Monitoring | Monitor patient vitals, lab values, and medical device readings for out-of-range or clinically significant anomalies. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Connect anomaly detection pipelines to S3 data lakes for batch analysis of historical metric data. |
| Elasticsearch / OpenSearch | Use Elasticsearch ML datafeeds to continuously analyze indices for anomalous patterns using built-in anomaly detection jobs. |
| Amazon CloudWatch | Pipe CloudWatch metrics into AWS Lookout for Metrics for automated operational anomaly alerting. |
| Microsoft Fabric / Real-Time Intelligence | Migration target for Azure Anomaly Detector users, providing integrated real-time anomaly detection within the Microsoft Fabric analytics platform. |
| Grafana | Visualize anomaly scores and detected anomalies from Elasticsearch ML and Datadog within Grafana dashboards. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Anomaly Schema](json-schema/anomaly-detection-anomaly-schema.json)
- [Time Series Schema](json-schema/anomaly-detection-time-series-schema.json)
- [Detection Job Schema](json-schema/anomaly-detection-detection-job-schema.json)

### JSON Structure

- [Anomaly Structure](json-structure/anomaly-detection-anomaly-structure.json)
- [Time Series Structure](json-structure/anomaly-detection-time-series-structure.json)
- [Detection Job Structure](json-structure/anomaly-detection-detection-job-structure.json)

### JSON-LD

- [Anomaly Detection Context](json-ld/anomaly-detection-context.jsonld)

### Examples

- [Anomaly Example](examples/anomaly-detection-anomaly-example.json)
- [Time Series Example](examples/anomaly-detection-time-series-example.json)
- [Detection Job Example](examples/anomaly-detection-detection-job-example.json)

## Vocabulary

- [Anomaly Detection Vocabulary](vocabulary/anomaly-detection-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 12 actions, and 5 APIs across the anomaly detection landscape

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
