# Awesome-Business-Intelligence-BI

## Top Business Intelligence (BI) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Self-Service Analytics, Semantic Modeling & Embedded Dashboards*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Intelligence (BI)**. These tools enable organizations to connect data sources, build interactive dashboards, and empower business users with self-service analytics—from drag-and-drop explorers to code-first semantic layers that govern metrics at scale.



**Examples** include Looker, Tableau, Microsoft Power BI, Qlik Sense, Domo, Sisense, MicroStrategy, ThoughtSpot, Looker Studio, and GoodData (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, semantic modeling, and open analytics infrastructure—ideal for data teams, analysts, and developers seeking transparent, vendor-independent BI platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Looker (Google Cloud)](https://looker.com/)**  

  **Google Cloud's enterprise BI platform** built on **LookML**, a code-based semantic modeling language . **Git integration** for version control, **embedded analytics**, and **API-driven customization** . **The most developer-friendly semantic layer** in commercial BI.



- **[Tableau](https://www.tableau.com/)**  

  **The most widely adopted visual analytics platform** . **Tableau Cloud** and **Tableau Server** for hosted deployments. **Tableau Pulse** delivers AI-powered metrics insights in Slack, Teams, and email . **Tableau Agent** and **Tableau Semantics** bring AI-native analytics . **The gold standard for data visualization**.



- **[Microsoft Power BI](https://powerbi.microsoft.com/)**  

  **Microsoft's business analytics platform** integrated with Microsoft Fabric . **Power BI Desktop** for authoring, **Power BI Service** for sharing, **Copilot AI** assistance, and **Direct Lake mode** for querying OneLake without data import . **The most widely deployed BI tool** with deep Microsoft ecosystem integration.



- **[Qlik Sense](https://www.qlik.com/)**  

  **Associative analytics platform** with **Qlik Sense Enterprise**, **Qlik Cloud Analytics**, and **Qlik Analytics Platform** . Features **self-service visualization**, **guided analytics**, and **embedded analytics** with open APIs . **The associative engine** finds relationships across all data without predefined queries.



- **[Domo](https://www.domo.com/)**  

  **Cloud-native BI and data product platform** with **1,000+ connectors** . Features **Magic ETL** for data transformation, **App Catalyst** for pro-code apps, and **AI-driven workflows** integrated with Google Cloud Vertex AI . **The most end-to-end platform** from ETL to visualization.



- **[Sisense](https://www.sisense.com/)**  

  **BI and analytics platform for embedded analytics** . Features **ElastiCube** for in-memory data blending and **AI-powered predictive analytics** . **The most focused on embedded analytics** for product teams.



- **[MicroStrategy](https://www.microstrategy.com/)**  

  **Enterprise analytics platform** with **governed data discovery**, **enterprise reporting**, and **mobile analytics** . **The most mature enterprise BI platform** for large-scale deployments.



- **[ThoughtSpot](https://www.thoughtspot.com/)**  

  **Agentic analytics platform** with **Spotter AI agent** . Features **natural language search**, **embedded analytics via SDK/API/MCP**, and **unified structured and unstructured data analysis** . **The most AI-forward commercial BI platform** .



- **[Looker Studio](https://lookerstudio.google.com/)**  

  **Google's free BI platform** (formerly Google Data Studio) . Features **200+ connectors**, **real-time collaboration**, and **integration with Google Workspace** . **The most accessible free BI tool** .



- **[GoodData](https://www.gooddata.com/)**  

  **Composable analytics platform** with **Analytics Lake** infrastructure . Features **Apache Iceberg and DuckDB integration**, **FlexConnect** for custom data connectors, and **multi-tenant workspace isolation** .



## Open-Source GitHub Projects



- **[Metabase](https://github.com/metabase/metabase)**  

  **The simplest, fastest way to get BI and analytics** (AGPL-3.0) . **40,000+ GitHub stars** . **The most widely adopted open-source BI tool**—**ships as a single JVM container plus Postgres**, dramatically simpler to deploy than Superset . **Features**: **Query Builder** for non-SQL users, **Metabot AI assistant**, **interactive dashboards**, **granular permissions**, **embeddings**, and **25+ data source connectors** including Snowflake, BigQuery, Redshift, Databricks, and standard relational databases . **Best fit when the warehouse is one of the major cloud players and modeling lives elsewhere (typically dbt)** . **The default choice for teams that want self-service analytics without deep technical overhead** .



- **[Apache Superset](https://github.com/apache/superset)**  

  **Modern, enterprise-ready BI web application** (Apache-2.0) . **60,000+ GitHub stars** . **Originally built at Airbnb** and now an Apache Software Foundation top-level project . **Features**: **no-code chart builder**, **SQL Editor**, **lightweight semantic layer**, **40+ visualization types**, and **support for nearly any SQL database** . **Native connectors** for Snowflake, BigQuery, Databricks, Redshift, Postgres, MySQL, Trino, ClickHouse, and 40+ more via SQLAlchemy . **Datasets and metrics compile to SQL** that runs in the warehouse for scale . **dbt manifest integration** surfaces models and exposures . **Embedded SDK** with guest-token auth and row-level security . **Stateless web tier** scales horizontally for customer-facing concurrency . **The most feature-complete open-source BI platform** for complex analytical requirements .



- **[Redash](https://github.com/getredash/redash)**  

  **Open-source data visualization and dashboarding tool** (BSD-2-Clause) . **25,000+ GitHub stars** . **Features**: **query editor** with schema browser and auto-complete, **drag-and-drop visualizations**, **scheduled refreshes**, **alerts**, and **REST API** . **Query model is genuinely warehouse-native**—every chart is backed by SQL against the source . **Supports 35+ data sources** including all major warehouses . **Acquired by Databricks in 2020**, so **long-term maintenance is uncertain** . **Best fit when your audience is SQL-fluent and you want a fast query/dashboard surface** .



- **[Lightdash](https://github.com/lightdash/lightdash)**  

  **Open-source BI tool built natively for dbt users** (MIT) . **Your dbt project is your semantic layer**—Lightdash reads dbt models directly, exposes measures and dimensions in the BI UI, and pushes every query through to the warehouse via dbt's connection profile . **No parallel modeling layer to maintain** . **Warehouse coverage matches dbt support**: Snowflake, BigQuery, Databricks, Redshift, Postgres, and more . **Best fit for dbt-first analytics teams** who want their BI layer to track their dbt models without translation .



- **[Grafana](https://github.com/grafana/grafana)**  

  **Open-source observability and analytics platform** (AGPL-3.0) . **77,000+ GitHub stars** . **While primarily for monitoring**, widely used for BI dashboards with support for SQL databases, Prometheus, and multiple data sources . **Extensive plugin ecosystem** . **Best for**: teams already using Grafana for observability who want to add business dashboards without a separate tool.



- **[DataEase](https://github.com/dataease/dataease)**  

  **Open-source data visualization and analysis tool** (GPL-3.0) . **13,000+ GitHub stars** . **Connects to MySQL, Oracle, SQL Server, PostgreSQL, Excel, and more** . **Drag-and-drop interface** for building visualizations without code . **The most accessible open-source BI tool for non-technical users** .



- **[Cube.js](https://github.com/cube-js/cube)**  

  **Open-source semantic layer** (Apache-2.0) . **Provides headless BI infrastructure** with SQL generation, caching, and API for custom analytics frontends . **Serves as a universal semantic layer** connecting data sources to analytics tools . **The most focused semantic layer** for teams building custom BI applications .



- **[Knowage](https://github.com/KnowageLabs/Knowage-Server)**  

  **Full open-source suite for Business Intelligence and Analytics** (AGPL-3.0) by Engineering Group . **Modules include**: **Enterprise Reporting**, **Smart Intelligence** for self-service BI, **Location Intelligence**, **Performance Management with KPIs**, and **Custom Analytics with R/Python integration** .



- **[Evidence](https://github.com/evidence-dev/evidence)**  

  **Open-source, code-based BI** (MIT) . **Write SQL and Markdown**—reports are version-controlled, reviewable, and reproducible . **The most developer-friendly BI approach**—treats reports as code that lives in Git alongside the data pipeline .



### Additional Strong Open-Source Options



- **[Trino](https://github.com/trinodb/trino)** — Distributed SQL query engine (Apache-2.0) for analytics on data lakes . **The federated query engine powering many BI stacks** .

- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** — Column-oriented OLAP database for real-time analytics (Apache-2.0) . **Sub-second queries on billions of rows** .

- **[Apache Druid](https://github.com/apache/druid)** — Real-time analytics database for sub-second queries on streaming and batch data (Apache-2.0) .

- **[Apache Doris](https://github.com/apache/doris)** — MPP-based real-time analytical database (Apache-2.0) . **MySQL protocol compatible** .

- **[StarRocks](https://github.com/StarRocks/starrocks)** — High-performance OLAP database with lakehouse federation and materialized views (Apache-2.0) .

- **[DuckDB](https://github.com/duckdb/duckdb)** — In-process analytical database (MIT) . **The SQLite of analytics**—runs anywhere, embedded .

- Community **n8n** workflows for BI alerting and dashboard distribution automation.



**Frameworks for building custom systems**: Combine **Apache Superset** or **Metabase** as the BI frontend with **Cube.js** for semantic modeling, **ClickHouse** or **StarRocks** for high-performance queries, **dbt** for data transformation, and **PostgreSQL** for metadata—creating a fully self-hosted, enterprise-grade BI platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- BI platforms handling enterprise data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **Open-source BI is mature and production-ready.** Metabase provides the simplest deployment path with 40K+ stars . Apache Superset delivers the most feature-complete platform with 60K+ stars . Lightdash offers dbt-native semantic modeling . **These are genuine alternatives to Looker and Tableau.**

- **The semantic layer is the new battleground.** Looker's LookML, Cube.js, and dbt's semantic layer represent a shift from "dashboards as artifacts" to "metrics as governed assets." **The semantic layer is where metric definitions live—governed, versioned, and reused across tools.**

- **The right choice depends on your team's shape.** Metabase for non-SQL users and simple deployment . Superset for complex analytical requirements and SQL-fluent teams . Lightdash for dbt-first teams . Redash for SQL-native query/dashboard workflows . **Pick based on how your team thinks about data, not feature checklists** .

- **Open-source BI carries hidden costs.** Budget 4–10 hours per month for Superset operations, 1–2 hours for Metabase . Untested backups of metadata databases are decorations; security advisories must be monitored and patches applied . **The "free" software has real operational costs.**

- Self-hosted open-source solutions require proper security hardening, resource provisioning, and ongoing maintenance. **BI platforms are the window into your data**—access controls and audit trails are essential.



---



**Made for data teams, analysts, and organizations building transparent BI solutions.**  

Let's make Business Intelligence more open, data-driven, and self-service.
