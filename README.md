# dsml-dataeng-labs

> Data Engineering labs — storage formats, orchestration, lineage, streaming, reverse ETL

**18 projects** from a 182-project DS/ML roadmap.

## What this repo is

A monorepo of short lab projects, one folder per project. The goal is coverage and fluency, not
production polish.

## Projects

### Beginner (5)

| # | Project | Status |
|---|---|---|
| 119 | SQL Feature Warehouse | Not started |
| 143 | Parquet vs CSV Storage Benchmark | Not started |
| 144 | Automated Data Dictionary Generator | Not started |
| 145 | Task Dependency Graph Engine from Scratch | Not started |
| 146 | Change Data Capture Basics | Not started |

### Intermediate (5)

| # | Project | Status |
|---|---|---|
| 147 | Slowly Changing Dimensions & Incremental Models with dbt | Not started |
| 148 | Delta Lake Table with ACID Transactions | Not started |
| 149 | Data Lineage Tracker | Not started |
| 150 | Asset-Based Pipeline with Dagster | Not started |
| 152 | Reverse ETL to Operational Tools | Not started |

### Advanced (3)

| # | Project | Status |
|---|---|---|
| 155 | Data Catalog with Access Control | Not started |
| 156 | Multi-Team Pipeline Orchestration at Scale | Not started |
| 157 | Exactly-Once CDC Pipeline at Scale | Not started |

### Expert (5)

| # | Project | Status |
|---|---|---|
| 158 | Multi-Warehouse Data Mesh Architecture | Not started |
| 159 | Multi-Engine Lakehouse (Spark + Trino/Presto) | Not started |
| 160 | Data Governance Platform with Policy-as-Code | Not started |
| 161 | Self-Service Orchestration Platform | Not started |
| 162 | Multi-Source CDC Data Mesh Ingestion | Not started |

Update the **Status** column as projects are completed.

## Layout

One folder per project, prefixed with its roadmap number so it stays traceable:

```
dsml-dataeng-labs/
  119-<project-name>/
    notebooks/
    src/
    README.md
  ...
```

## Conventions

- Each project folder gets a short README: what it does, how to run it, what was learned.
- Datasets and model artifacts are gitignored — document how to obtain or regenerate them instead.
