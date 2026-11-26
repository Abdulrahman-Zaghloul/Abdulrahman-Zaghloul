# Hi, I'm Abdulrahman Zaghloul

**Backend and data engineer.** I build Python services and data pipelines where correctness is the point: money that can't be spent twice, data that fails loudly when it's wrong, and detections that show their evidence.

Computer Engineering graduate with an M.S. in Computer Science & Engineering · Tampa, FL  
Open to **software, backend and data engineering** roles, remote or anywhere in the US.

---

## What I'm building

### [Civilneer](https://github.com/Abdulrahman-Zaghloul/civilneer): automated QC for roadway engineering drawings

`Python` `FastAPI` `PostgreSQL` `Next.js` `PyMuPDF` `Shapely` `Docker`

A production SaaS in private beta. It reads vector PDFs of roadway cross sections, rebuilds the geometry, and checks every printed slope, elevation and offset against it. A review that takes an engineer 5–10 minutes per sheet by hand runs in under 5 seconds.  
[civilneer.com](https://civilneer.com) · [Architecture write-up](https://github.com/Abdulrahman-Zaghloul/civilneer)

### [Ledgerline](https://github.com/Abdulrahman-Zaghloul/ledgerline): double-entry payments ledger API

`FastAPI` `PostgreSQL 16` `SQLAlchemy` `Alembic` `Docker`

Multi-currency wallets, deposits and transfers with the guarantees that matter: double-entry postings enforced at commit, mandatory idempotency keys, deadlock-free row locking, a transactional outbox with HMAC-signed webhooks, and reconciliation of every balance against the ledger. Strict `mypy` and CI on every push.

### [Retail Data Lakehouse Pipeline](https://github.com/Abdulrahman-Zaghloul/retail-lakehouse-pipeline)

`PySpark` `dbt` `Airflow` `PostgreSQL` `Parquet` `GitHub Actions`

Six retail source domains taken from an operational Postgres database to a tested star schema, orchestrated with Airflow and reproducible with one command. 37 dbt tests run in CI, so a broken data contract fails the build instead of reaching the marts.

### [Vigil](https://github.com/Abdulrahman-Zaghloul/vigil): threat-detection engine, built in public

`Python` `FastAPI` `PostgreSQL` `MITRE ATT&CK`

Reads security logs, detects SSH brute force, password spraying and logins after repeated failures, and raises alerts mapped to MITRE ATT&CK with the exact log lines as evidence. Command-line scanner, ingestion API with scoped keys and rate limits, PostgreSQL storage.

---

## More projects

| Project | What it shows |
| --- | --- |
| [SOC Lab: Wazuh SIEM](https://github.com/Abdulrahman-Zaghloul/soc-lab-wazuh) | Wazuh and Sysmon deployed from scratch, a simulated SMB brute-force attack investigated end to end and written up as an incident report |
| [Logistics Network Optimization](https://github.com/Abdulrahman-Zaghloul/logistics-network-optimization) | Delivery territories and routes for 5 drivers and about 300 stops in Tampa, using OSMnx, NetworkX and scikit-learn |
| [Spatial ETL Pipeline](https://github.com/Abdulrahman-Zaghloul/spatial-etl-pipeline) | Bronze, silver and gold layers from the OpenStreetMap Overpass API to an interactive density heatmap |
| [GIS Portfolio](https://github.com/Abdulrahman-Zaghloul/GIS-Portfolio) | Flood relocation, habitat suitability and wildfire exposure analyses in ArcGIS Pro |

---

## Stack

**Languages:** Python · SQL · Java · JavaScript · C  
**Backend:** FastAPI · SQLAlchemy · Alembic · Pydantic · PostgreSQL · Docker  
**Data:** PySpark · dbt · Airflow · Parquet · ETL/ELT  
**GIS:** PostGIS · GeoPandas · Shapely · OSMnx · NetworkX · ArcGIS Pro · QGIS  
**Security:** Wazuh · Sysmon · MITRE ATT&CK  
**Practices:** GitHub Actions CI · mypy · ruff · Linux · Make

---

## Contact

**LinkedIn:** [linkedin.com/in/Abdul-Zaghloul](https://www.linkedin.com/in/Abdul-Zaghloul)  
**Email:** [abdulrahmansamy2@gmail.com](mailto:abdulrahmansamy2@gmail.com)
