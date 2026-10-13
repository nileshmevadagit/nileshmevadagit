# mevadanileshgit
### Hi, I'm Nilesh 👋

Senior Data Engineer / Architect. I design high-volume data platforms people can trust: reliable pipelines, sensible architecture, and governance that doesn't get in the way.

Most of my work sits where architecture meets day-to-day engineering:

- **Platform architecture:** batch and streaming pipelines, lakehouse and warehouse design, and choosing what to build versus what to buy.
- **High-volume data:** pipelines that scale without surprises, with backfills, idempotent loads and costs that stay predictable.
- **Data governance:** data quality, lineage, access control, data contracts, and clear ownership of datasets.
- **Engineering standards:** design reviews, reusable frameworks and patterns, and mentoring engineers so good practice outlasts any single project.

I still care about the unglamorous parts, like retries, schema drift and knowing what broke before someone else tells me, because that's usually where platforms succeed or fail.
Currently a Data Engineer at Meta

#### Side projects

**API ingestion framework** (repo coming soon). A lightweight Python library for pulling data from HTTP APIs without the usual failure modes. It handles retries only where they make sense, the common pagination styles, and hourly/daily provider quotas that survive restarts and can be shared across workers. The longer-term plan is resumable, sharded backfills and a reference pipeline that loads into Iceberg with dlt, dbt and Dagster.

I'm writing the design doc in the open, and decisions and trade-offs will live in the repo alongside the code.

#### Tools I use

Python · Spark(PySpark) · Presto · SQL · httpx · Airflow · Docker · Kubernetes · AWS (S3, Lambda, DynamoDB) · Postgres

#### Things I find interesting

- Making large backfills boring: checkpointing, resumability, and staying under provider limits
- Data quality checks that catch problems before dashboards do
- Keeping infrastructure cheap until it genuinely needs to scale

#### Get in touch

- LinkedIn: linkedin.com/in/nileshmevadasf
- Email: mevadanilesh@gmail.com
