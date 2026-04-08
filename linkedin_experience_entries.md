# LinkedIn Experience Entries — 3 Separate Projects
## Hrvoje Jerkovic | Data Architect / Principal Data Engineer
### Client: Large Financial Institution (Contractor)

---

## ENTRY 1 — Copy/paste into LinkedIn Experience

**Title:** Data Architect / Principal Data Engineer
**Company:** Financial Institution (Contract)
**Start:** Sep 2025 → **End:** Oct 2025
**Location:** Remote

### Description (paste below):

Automated Enterprise ETL Reverse Engineering at Scale

Built a production-grade data lineage platform that automatically reverse-engineered an undocumented enterprise ETL landscape — ~4,300 ODI mappings, ~1,800 tables, 20+ source systems across Oracle, PostgreSQL, DataStage, and PL/SQL.

The platform traces column-level and table-level lineage through a 7-stage pipeline (Landing Zone → Staging → DQ → Core → Views → Targets), producing interactive HTML reports with full SQL visibility. Seven distinct resolution strategies handle ODI sessions, OJC job chains, regulatory patterns, and Oracle view DDL parsing — achieving 99.6% mapping coverage.

Key deliverables:
• Column-level lineage with expression parsing through all transformation layers
• Table-level lineage with topological build sequence export
• Batch processing of ~220 analytical + ~190 regulatory target tables
• Structured JSON output feeding directly into the AI migration pipeline

Tech: Python 3.12+, Oracle Data Integrator, OJC, IBM DataStage, PL/SQL, Groovy, PostgreSQL, Oracle, sqlglot, Jinja2, Pydantic, pandas

Part of a 3-project engagement also including Legacy-to-Lakehouse Migration (Oracle → Spark + Delta Lake + dbt) and AI Multi-Agent Orchestration for autonomous migration execution.

Full portfolio: https://hrvojej.github.io/portfolio/
Visual overview: https://hrvojej.github.io/portfolio/carousel.html

---

## ENTRY 2 — Copy/paste into LinkedIn Experience

**Title:** Data Architect / Principal Data Engineer
**Company:** Financial Institution (Contract)
**Start:** Nov 2025 → **End:** Dec 2025
**Location:** Remote

### Description (paste below):

Legacy-to-Lakehouse Platform Migration — Oracle to Spark + Delta Lake

Architected and implemented a full migration framework from a dual-database Oracle + PostgreSQL DWH (~4,300 ETL mappings, ~1,800 landing zone tables) to a modern open-source Data Lakehouse — replacing millions in licensed tooling.

Target architecture: dbt with Medallion pattern (Bronze → Silver → Gold), Apache Spark for compute, MinIO (S3-compatible) for storage, Delta Lake for ACID transactions, Hive Metastore for schema catalog, Kyuubi as JDBC gateway, and Apache Airflow for orchestration.

Key deliverables:
• Full Medallion architecture: Bronze (raw 1:1), Silver (cleaned/typed/deduped), Gold (business-ready dims/facts/reports)
• dbt model patterns for Oracle PL/SQL decomposition into declarative SQL
• Local-first development against PostgreSQL with production deployment to Spark
• DQ layer elimination saving ~340 table materializations
• Migration pipeline and patterns handed over to the team for ongoing execution

Tech: dbt, Apache Spark, Delta Lake, MinIO, Hive Metastore, Kyuubi, Apache Airflow, PostgreSQL, Oracle, Jinja2, Git

Part of a 3-project engagement also including Automated ETL Reverse Engineering (~4,300 mappings analyzed) and AI Multi-Agent Orchestration for autonomous pipeline execution.

Full portfolio: https://hrvojej.github.io/portfolio/
Visual overview: https://hrvojej.github.io/portfolio/carousel.html

---

## ENTRY 3 — Copy/paste into LinkedIn Experience

**Title:** Data Architect / Principal Data Engineer
**Company:** Financial Institution (Contract)
**Start:** Jan 2026 → **End:** Feb 2026
**Location:** Remote

### Description (paste below):

AI Multi-Agent Orchestration — Autonomous Migration Pipeline

Designed and built a custom AI orchestration engine that turns months of manual data engineering into an autonomous, continuously running migration pipeline. A state machine coordinates 9 specialized AI agents — lineage extraction, KB loading, data seeding, bronze verification, model building, compilation, cross-platform verification, diagnosis, and documentation.

The system processes legacy ETL models in parallel: extracts lineage, loads to a PostgreSQL knowledge base, generates dbt SQL from legacy Oracle/PL/SQL, compiles and runs models, then verifies output 1:1 against production. A strict fail-fast policy ensures quality — one automated fix attempt, then escalation.

Key deliverables:
• State machine pipeline: Extract → KB Load → Seed → Verify → Build (level-by-level) → Final Verify → Commit
• Inter-report and intra-report parallelism with model reuse detection
• Multi-level automated testing (bronze, silver, gold, cross-model)
• Tiered AI strategy: cost-efficient models for deterministic tasks, advanced models for orchestration
• Pipeline watchdog with auto-restart and health-check endpoints

Tech: Claude AI, Python 3.12+, Custom State Machine, PostgreSQL (Knowledge Base), dbt, Git, Parallel Execution Framework

Part of a 3-project engagement also including Automated ETL Reverse Engineering (~4,300 mappings) and Legacy-to-Lakehouse Migration (Oracle → Spark + Delta Lake).

Full portfolio: https://hrvojej.github.io/portfolio/
Visual overview: https://hrvojej.github.io/portfolio/carousel.html
