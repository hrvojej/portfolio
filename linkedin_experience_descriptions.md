# LinkedIn Experience — Contractor Project Descriptions
## Hrvoje Jerkovic | Data Architect / Principal Data Engineer

---

### Project 1: Automated Enterprise ETL Reverse Engineering at Scale

Built a production-grade data lineage platform that automatically reverse-engineered an undocumented ETL landscape spanning ~4,300 ODI mappings, ~1,800 tables, and 20+ source systems across Oracle, PostgreSQL, DataStage, and PL/SQL. The platform traces column-level and table-level lineage through 7 pipeline stages, producing interactive HTML reports with full SQL visibility — replacing months of manual analysis with automated, repeatable discovery.

**Tech:** Python, Oracle Data Integrator (ODI), OJC, IBM DataStage, PL/SQL, PostgreSQL, Oracle, sqlglot, Jinja2, Pydantic

---

### Project 2: Legacy-to-Lakehouse Platform Migration — Oracle to Spark + Delta Lake

Architected and implemented a full migration framework from a dual-database Oracle + PostgreSQL DWH to a modern open-source Data Lakehouse using dbt with Medallion architecture (Bronze → Silver → Gold), Apache Spark, MinIO (S3), Delta Lake, Hive Metastore, Kyuubi, and Apache Airflow. Established proven patterns and tooling, then handed the process over to the data engineering team for ongoing execution — eliminating millions in licensing costs.

**Tech:** dbt, Apache Spark, Delta Lake, MinIO, Hive Metastore, Kyuubi, Apache Airflow, PostgreSQL, Oracle, Git

---

### Project 3: AI Multi-Agent Orchestration — Autonomous Migration Pipeline

Designed and built a custom AI orchestration engine with 9 specialized agents (lineage extraction, SQL translation, model compilation, cross-platform verification, diagnosis) coordinated by a state machine. The system autonomously processes legacy ETL models in parallel — extracting, translating, building, testing, and deploying dbt models with minimal human supervision. Achieved orders-of-magnitude speed improvement over manual migration approaches.

**Tech:** Claude AI, Python, Custom State Machine, PostgreSQL (Knowledge Base), dbt, Git, Parallel Execution Framework
