# Simon Udoh (Nsenam)
### Data Engineer | Cloud & Streaming Pipelines | Subsurface & Energy Data

I build data infrastructure where the domain complexity is high -- upstream O&G,
energy markets, and regulatory datasets. Currently contracting in London on
AWS-based pipelines (S3, Redshift, Kafka, PostgreSQL).

Previously at Shell Global Solutions, where I led the CoatHanger programme --
a migration of core well data (well names, identifiers, and key attributes)
from Shell's on-premises Corporate Data Store into the cloud-based Open
Subsurface Data Universe (OSDU) platform, across global assets.

- **ETL Pipeline Development (Informatica / OSDU)** -- built Informatica
  Cloud Data Integration (CDI) pipelines to migrate subsurface data from
  CDS and SDU into OSDU; constructed OSDU-compliant JSON manifests using
  Hierarchy Builder with full attribute coverage; applied reference data
  translation to standardise source values across regional variants;
  extended pipelines with Python scripts including DLIS-to-Parquet
  conversion via dlisio; handled flat file migration (DLIS, LAS, WITSML)
  through the OSDU Content Delivery Service; orchestrated and
  troubleshot pipeline runs via Apache Airflow; validated ingested
  records using OSDU Search and Storage APIs; versioned Informatica
  pipeline assets in GitHub; deployed to production via ServiceNow
  change management; built parameterised multi-region pipelines to
  eliminate per-asset cloning

- **Entitlements & Obligations (E&O)** -- data governance and access
  control; played a core role in designing, testing, and implementing
  the cloud-native DMA (Data Management Application) -- Shell's
  replacement for the legacy Central Data Register (CDR); performed
  detailed contractual E&O reviews for core assets and applied a
  risk-based approach for Lean and Legacy assets; extracted legal
  attributes from source documents as JSON using Python and created
  legal tags in DMA; designed ACL group structures governing data
  access and CRUD permissions; integrated legal tags directly into
  ETL pipelines for automated assignment during migration; collaborated
  with Legal, C&P (Contracts and Procurement), and Commercial teams;
  maintained the single source of truth spreadsheet tracking E&O
  approval status per asset and data type

- **Data Readiness** -- designed and codified showstopper and
  non-showstopper migration eligibility rules in collaboration with
  the data design team; built readiness dashboards in Power BI against
  SQL schemas designed to profile EDM and CDS relational data types; wrote
  Python scripts for non-relational Recall checks; validated data
  integrity (SUWI/SUWBI alignment across EDM and CDS), reference value
  consistency, and record uniqueness; produced E&O-approved,
  readiness-cleared test datasets as inputs for acceptance and
  production pipeline testing; maintained a global master migration
  eligibility tracker spanning all data types and assets

- **WMM/DS/DMA Mastership Change** -- led the mastership transition of
  three platforms -- Well Master Manager (WMM), Directional Survey (DS),
  and Data Management Application (DMA) -- from Shell Data Universe
  (SDU), Shell's proprietary precursor to OSDU, into the standardised
  cloud-based Open Subsurface Data Universe (OSDU)

- **WBDDMS Focus Group (Wellbore Domain Data Management Service)** --
  led the focus group; designed and implemented a framework to convert
  single DLIS files to Parquet, introducing Equinor's dlisio library
  into the programme; presented findings to senior leadership

I hold an MSc in Data Science (RGU), MSc in Integrated Petroleum Geoscience
(Aberdeen), and MSc in Petroleum Geophysics (OAU) -- which means I can read a
well log, a seismic section, and a Kafka offset in the same morning.

---

## What I build

- **Streaming pipelines** -- Kafka, Spark Structured Streaming, Debezium CDC
- **Cloud data infrastructure** -- AWS (S3, Redshift, Glue, Lambda), Azure (ADF, Databricks, Fabric)
- **Subsurface & geospatial data** -- OSDU, DLIS, SEG-Y, WITSML, RESQML
- **Analytics & warehousing** -- dbt, PostgreSQL, Redshift, data modelling
- **Orchestration & containerisation** -- Airflow, Docker, Docker Compose

---

## Featured project

**Stream processing -- Agile Energy Price Pipeline**
Production-grade Kafka + Spark Structured Streaming pipeline ingesting
Octopus Agile API data into PostgreSQL, with a Streamlit dashboard.
Fully containerised with Docker Compose.

[View repo]([https://github.com/nse4real/brook-green](https://github.com/nse4real/energy-streaming-pipeline)) |
[Portfolio](https://portfolio-coral-two-43.vercel.app)

---

## Domain expertise

Most data engineers can move data. Fewer understand what it means when a
WITSML log has a mismatch between depth reference frames, or why OSDU
entitlement schema matters at the asset level. That gap is where I work.

---

## Currently

- Contracting as Data Engineer (AWS stack, London)
- Building toward Microsoft Fabric Data Engineer certification (DP-700)
- Open to senior Data Engineer and Data Analyst roles (visa sponsorship required)

---

<details>
<summary>Glossary -- Shell/OSDU terminology</summary>

| Term | Definition |
|------|-----------|
| **OSDU** | Open Subsurface Data Universe -- industry-standard cloud platform for subsurface data, originally developed by Shell as SDU before being contributed to the energy industry |
| **SDU** | Shell Data Universe -- Shell's proprietary precursor to OSDU |
| **CDR** | Central Data Register -- Shell's legacy on-premises well data registry, replaced by DMA |
| **DMA** | Data Management Application -- Shell's cloud-native replacement for CDR; provides modern metadata management, ingestion, and governance capabilities |
| **EDM** | Enterprise Data Management -- Shell's company-wide framework for governing, integrating, and managing structured and unstructured data (subsurface, IoT, commercial) to drive decision-making, AI initiatives, and the transition to net-zero |
| **WMM** | Well Master Manager -- platform for managing well master data |
| **CDS** | Corporate Data Store -- Shell's on-premises corporate data store |
| **SUWI** | Shell Unique Well Identifier -- unique identifier for Shell-operated wells |
| **SUWBI** | Shell Unique Wellbore Identifier -- unique identifier for well sidetracks on Shell-operated wells |
| **DLIS** | Digital Log Interchange Standard -- binary file format for well log data |
| **WBDDMS** | Wellbore Domain Data Management Service -- specialised backend service within OSDU designed to manage, ingest, store, and retrieve wellbore-related data; provides a standardised, cloud-native way to handle high-frequency, complex well data across the full wellbore lifecycle |
| **dlisio** | Open-source Python library developed by Equinor for parsing DLIS well log files |

</details>

---

## Reach me

[LinkedIn](https://www.linkedin.com/in/simonnudoh) |
[Portfolio](https://portfolio-coral-two-43.vercel.app) |
simon.n.udoh@gmail.com
