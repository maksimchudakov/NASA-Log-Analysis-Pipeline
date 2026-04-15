🚀 NASA Infrastructure: Log Analysis & SRE Observability Pipeline
Project Status: Production-Ready

Internal Reference: DevOps Action Infrastructure Case Study

📊 Project Context
As part of the technical initiatives at DevOps Action, this project demonstrates a robust Observability Pipeline using historical NASA web server data. The objective is to prove how legacy, unstructured log formats can be transformed into modern Service Level Indicators (SLIs) and actionable business intelligence for capacity planning.

🛠️ Professional Tech Stack
Engine: Python 3.13 (Optimized for Large-Scale ETL)

Analytics: Pandas (Time-Series Forensics), Matplotlib (Infrastructure Visualization)

Data Integrity: Regex (Custom Pattern Matching), Timezone-Normalization for Cross-Platform Portability.

📂 Dataset Infrastructure & Access
Source: [NASA HTTP Access Logs (Kaggle)](https://www.kaggle.com/datasets/adchatakora/nasa-http-access-logs) 

Volume: 1.5M+ Requests

Note on **access.log:** Due to GitHub's file size limitations for the raw 200MB+ dataset, the source file is excluded from this repository. To reproduce this analysis, download the log file from the Kaggle link above and place it in the root directory.

🚀 Key SRE Deliverables
1. Incident Post-Mortem: Hurricane Erin Recovery
A forensic analysis of the total system shutdown (Aug 1–3, 1995) was conducted to evaluate Disaster Recovery (DR) protocols and system resilience.

Cold Boot Stability: Audited the first hour of system restoration, identifying a 99%+ Success Rate.

Traffic Volatility: Documented a post-incident surge to assist in future Capacity Planning and load balancing.

2. Infrastructure Routing & Audit
302 Redirect Mapping: Validated 26,429 redirect events to ensure zero breakage of legacy URL structures and SEO integrity.

SLI Definition: Established a baseline for tracking 4xx/5xx error distributions, enabling proactive site reliability monitoring and root-cause analysis for broken links.

3. Stakeholder Interoperability (Hybrid Workflow)
This pipeline bridges the gap between Engineering and Executive Leadership:

Engineering Layer: Generates a 1-minute resolution CSV export (nasa_monitoring_final.csv) optimized for Grafana dashboard ingestion.

Executive Layer: Generates a multi-sheet Excel Workbook (NASA_Executive_Incident_Report.xlsx) containing high-level KPI summaries and failure mode distributions.


21 3
