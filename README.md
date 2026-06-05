# Anomaly Detection (anomaly-detection)

A curated collection of APIs, tools, and platforms for detecting anomalies in data streams, time series, and multivariate metrics. Covers cloud ML services, observability platforms, and open-source frameworks used for fraud detection, predictive maintenance, IoT monitoring, and security analytics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/apis.yml)

## Tags

- Anomaly Detection
- Artificial Intelligence
- Data Science
- Fraud Detection
- Machine Learning
- Monitoring
- Observability
- Outlier Detection
- Pattern Recognition
- Security
- Time Series

## Timestamps

- **Created:** Sun Jan 14 2024 19:00:00 GMT-0500 (Eastern Standard Time)
- **Modified:** Sat Apr 18 2026 20:00:00 GMT-0400 (Eastern Daylight Time)

## APIs

### Azure AI Anomaly Detector

Azure AI Anomaly Detector is a managed REST API service that enables monitoring and detection of anomalies in time series data without requiring machine learning expertise. Supports univariate batch and streaming detection, multivariate detection using Graph Attention Networks for up to 300 correlated signals, and change-point detection. The service is being retired on 1 October 2026 in favor of Microsoft Fabric real-time intelligence.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview)
- **Base URL:** `https://api.cognitive.microsoft.com`

#### Tags

- Anomaly Detection
- Azure
- Machine Learning
- Microsoft
- Multivariate
- Time Series
- Univariate

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/anomalydetector/)
- [Quickstart](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/quickstarts/client-libraries)
- [Tutorials](https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/tutorials/batch-anomaly-detection-powerbi)
- [GitHub Repository](https://github.com/microsoft/anomaly-detector)
- [Postman Collection](collections/anomaly-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anomaly-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Elasticsearch Anomaly Detection API

Elasticsearch Machine Learning APIs provide a comprehensive suite of anomaly detection capabilities for time series data stored in Elasticsearch indices. Supports creating and managing anomaly detection jobs and datafeeds, accessing bucket, record, category, and influencer results, model snapshots, calendars, scheduled events, and forecasting. Part of the Elastic Stack ML feature set available in subscriptions.

- **Human URL:** [https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html](https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html)
- **Base URL:** `https://your-elasticsearch-host:9200`

#### Tags

- Anomaly Detection
- Elasticsearch
- Machine Learning
- Monitoring
- Time Series

#### Properties

- [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html)
- [API Reference](https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-ad-apis.html)
- [Getting Started](https://www.elastic.co/guide/en/machine-learning/current/ml-ad-overview.html)
- [GitHub Organization](https://github.com/elastic)
- [Postman Collection](collections/anomaly-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anomaly-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Anomaly Monitor API

Datadog's Monitors API supports anomaly detection monitors that identify unusual metric behavior using historical pattern analysis including trends, day-of-week, and time-of-day seasonality. Offers three detection algorithms — Basic, Agile (SARIMA), and Robust (seasonal-trend decomposition) — configurable via REST API. Available across regional endpoints for US, EU, AP1, AP2, GOV, US3, and US5 deployments.

- **Human URL:** [https://docs.datadoghq.com/monitors/types/anomaly/](https://docs.datadoghq.com/monitors/types/anomaly/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Anomaly Detection
- Datadog
- Monitoring
- Observability
- Time Series

#### Properties

- [Documentation](https://docs.datadoghq.com/monitors/types/anomaly/)
- [API Reference](https://docs.datadoghq.com/api/latest/monitors/)
- [Authentication](https://docs.datadoghq.com/api/latest/authentication/)
- [GitHub Organization](https://github.com/DataDog)
- [Postman Collection](collections/anomaly-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anomaly-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS Lookout for Metrics

Amazon Lookout for Metrics is a fully managed ML service that automatically detects anomalies in business and operational data. It connects to data sources including Amazon S3, Amazon Redshift, Amazon CloudWatch, and SaaS applications, learns each metric's normal behavior, and sends alerts when anomalies are detected. Provides root cause analysis grouping related anomalies for faster diagnosis.

- **Human URL:** [https://aws.amazon.com/lookout-for-metrics/](https://aws.amazon.com/lookout-for-metrics/)
- **Base URL:** `https://lookoutmetrics.us-east-1.amazonaws.com`

#### Tags

- Amazon Web Services
- Anomaly Detection
- AWS
- Business Metrics
- Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/lookoutmetrics-welcome.html)
- [API Reference](https://docs.aws.amazon.com/lookoutmetrics/latest/api/Welcome.html)
- [Getting Started](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/lookoutmetrics-gettingstarted.html)
- [Pricing](https://aws.amazon.com/lookout-for-metrics/pricing/)
- [Postman Collection](collections/anomaly-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anomaly-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PyOD (Python Outlier Detection)

PyOD is a comprehensive and scalable Python library for detecting outliers/anomalies in multivariate data. It includes more than 40 detection algorithms including deep learning approaches (AutoEncoder, VAE), proximity-based methods (LOF, CBLOF), linear models (PCA, OCSVM), and ensemble methods (IForest, LOCI). Widely used in research and production for fraud detection, intrusion detection, medical anomaly detection, and data quality monitoring.

- **Human URL:** [https://pyod.readthedocs.io/](https://pyod.readthedocs.io/)
- **Base URL:** `https://pypi.org/project/pyod/`

#### Tags

- Anomaly Detection
- Data Science
- Machine Learning
- Open Source
- Outlier Detection
- Python

#### Properties

- [Documentation](https://pyod.readthedocs.io/en/latest/)
- [API Reference](https://pyod.readthedocs.io/en/latest/pyod.html)
- [GitHub Repository](https://github.com/yzhao062/pyod)
- [SDK](https://pypi.org/project/pyod/)
- [Postman Collection](collections/anomaly-detection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anomaly-detection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/api-evangelist/anomaly-detection)
- [Best Practices](https://pyod.readthedocs.io/en/latest/faq.html)
- [Blog](https://techcommunity.microsoft.com/t5/AI-Customer-Engineering-Team/Introducing-Azure-Anomaly-Detector-API/ba-p/490162)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-anomaly-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-time-series-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-detection-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/vocabulary/anomaly-detection-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
