# Awesome-Search-Observability

## Top Search Observability Tools Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Search Analytics, Query Performance, Relevance Monitoring, Click-Through & Conversion Insights for Site & Product Search*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Search Observability**. These tools help teams monitor search query volume, latency, relevance quality, click-through rates, zero-result rates, conversion impact, and overall search experience health across websites, e-commerce, and applications.

**Examples** include Elastic Observability, Algolia Analytics, Meilisearch Cloud, Typesense Cloud, Coveo Analytics, Searchspring, Constructor Analytics, Swiftype Analytics, Bonsai Search Analytics, and Searchanise (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted search engines with analytics, relevance evaluation tooling, and observability stacks that can monitor search systems — ideal for teams that want full data ownership and control over search quality metrics.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Elastic Observability](https://www.elastic.co/observability)**  
  Full-stack observability platform (logs, metrics, traces, APM) frequently used to monitor Elasticsearch/OpenSearch clusters and search application performance at scale.

- **[Algolia Analytics](https://www.algolia.com/)**  
  Built-in analytics for Algolia search covering query volume, click positions, conversion rates, no-result queries, and search performance insights.

- **[Meilisearch Cloud](https://www.meilisearch.com/)**  
  Managed cloud offering of the open-source Meilisearch engine with hosting, scaling, and operational analytics for production search workloads.

- **[Typesense Cloud](https://typesense.org/)**  
  Managed cloud service for the open-source Typesense search engine, providing hosting and operational visibility for instant search deployments.

- **[Coveo Analytics](https://www.coveo.com/)**, **[Searchspring](https://searchspring.com/)**, **[Constructor Analytics](https://constructor.com/)**  
  Specialized search and discovery platforms with strong analytics around relevance, merchandising, personalization, and revenue attribution from search.

- **[Swiftype Analytics](https://swiftype.com/)** (Elastic Site Search), **[Bonsai Search Analytics](https://bonsai.io/)**, **[Searchanise](https://searchanise.com/)**  
  Additional hosted search solutions offering query analytics, performance monitoring, and insights tailored to site or e-commerce search.

## Open-Source GitHub Projects

- **[Meilisearch](https://github.com/meilisearch/meilisearch)**  
  Fast, open-source search engine with typo tolerance, faceting, and built-in capabilities that teams commonly instrument for query and performance analytics when self-hosted.

- **[Typesense](https://github.com/typesense/typesense)**  
  Open-source, in-memory search engine designed as an Algolia alternative. Self-hosted deployments give full control over search traffic and can be paired with custom analytics pipelines.

- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  
  Apache 2.0 fork of Elasticsearch with a rich Observability Stack (logs, metrics, traces, dashboards, anomaly detection) ideal for monitoring search clusters and query performance.

- **[Quepid](https://github.com/o19s/quepid)**  
  Open-source search relevance evaluation and tuning tool. Supports judging results, tracking NDCG and related metrics, and improving ranking quality across Elasticsearch, Solr, OpenSearch, and custom APIs.

- **[Rekall](https://github.com/sony-mathew/rekall)**  
  Open-source tool for measuring search relevance that can integrate with application endpoints and compute metrics such as Average Precision, DCG, and nDCG.

- **[SearchTweak](https://searchtweak.com/)** (open-source edition)  
  Evaluation platform for search and ranking teams supporting human and AI judges, NDCG tracking, and dataset building for learning-to-rank — available as self-hosted open source.

- **[OpenObserve](https://github.com/openobserve/openobserve)** & **[SigNoz](https://github.com/SigNoz/signoz)**  
  Modern open-source observability platforms (logs, metrics, traces) that teams use to monitor search service latency, error rates, and infrastructure health.

- **[PostHog](https://github.com/PostHog/posthog)** & **[Matomo](https://github.com/matomo-org/matomo)**  
  Open-source product and web analytics platforms frequently used to track search-related user events (queries, clicks, conversions) alongside broader product metrics.

### Additional Strong Open-Source Options

- Apache Solr and Elasticsearch community tooling for query logging and performance analysis.
- Custom dashboards built with Grafana, Apache Superset, or Metabase on top of search logs and clickstream data.
- OpenTelemetry instrumentation of search services for end-to-end trace and metric collection.
- Many internal relevance labs and judgment tools that are partially released as open source.

**Frameworks for building custom systems**: Self-host **Meilisearch** or **Typesense** for the search layer and instrument queries/clicks into **PostHog**, **Matomo**, or a warehouse. Use **Quepid**, **Rekall**, or **SearchTweak** for systematic relevance evaluation and ranking improvement. Layer **OpenSearch Observability**, **OpenObserve**, or **SigNoz** for infrastructure and latency monitoring of the search stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Search observability spans query analytics, relevance quality, and infrastructure health. Open-source search engines give excellent control and cost characteristics but require you to build or integrate analytics and relevance tooling. Commercial platforms often provide richer out-of-the-box search-specific insights and merchandising analytics.
- Always consider privacy, consent, and data retention when logging search queries and click behavior.

---

**Made for search engineers, relevance teams, and product organizations seeking transparent, controllable search insights.**  
Let's make search quality more measurable and open.