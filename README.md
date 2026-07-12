<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=950&lines=Data+Scientist+%7C+MLOps+Engineer;Production+ML+Pipelines+%7C+R+%26+Python;Healthcare+AI+%7C+XGBoost+%7C+RAG+%7C+Clinical+Decision+Support;Time+Series+Forecasting+%7C+ARIMA+%7C+DuckDB;REST+APIs+%7C+Docker+%7C+GitHub+Actions+CI%2FCD;Business+Intelligence+%7C+Analytics+Engineering;KAIZEN+%E6%94%B9%E5%96%84+Continuous+Improvement" alt="Typing SVG" />
</div>

<h1 align="center">Hi there, I'm Kingsley</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/kayterthesly"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"></a>
  <a href="mailto:Kingsleya402@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-green?style=for-the-badge&logo=gmail"></a>
  <a href="https://kayterthesly.github.io/Kayterthesly/"><img src="https://img.shields.io/badge/Portfolio-Visit-orange?style=for-the-badge&logo=github"></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Kayterthesly&color=2E9EF7&style=flat-square&label=Profile+Views" alt="Profile views" />
</p>

---

## About Me

**Data Scientist and MLOps Engineer** based in Lagos, Nigeria, with 3+ years of experience building end-to-end ML systems and analytics solutions across **Healthcare, Retail, Finance, and Crypto markets**.

I don't just build models. I ship production systems: secured REST APIs, automated retraining pipelines, CI/CD workflows, governance audit trails, and cloud deployments that run themselves. My work spans the full stack from raw data ingestion to live interactive dashboards.

**What sets my work apart:**
- Two production ML pipelines live in the cloud with real APIs and dashboards
- Healthcare AI with clinical decision support via Retrieval-Augmented Generation
- Governance-first engineering: every prediction is logged, hashed, and traceable
- 71 + 35 = 106 automated tests across two projects, all passing
- Systems designed for zero daily human intervention

### [Full Portfolio](https://kayterthesly.github.io/Kayterthesly/)

---

## Live in Production

### [r-healthcare-readmission](https://github.com/Kayterthesly/r-healthcare-readmission) — LIVE IN PRODUCTION

[![CI](https://github.com/Kayterthesly/r-healthcare-readmission/actions/workflows/ci.yml/badge.svg)](https://github.com/Kayterthesly/r-healthcare-readmission/actions/workflows/ci.yml)
[![R 4.5](https://img.shields.io/badge/R-4.5.2-276DC2.svg?logo=r)](https://www.r-project.org/)
[![Railway](https://img.shields.io/badge/API-Railway-0B0D0E?logo=railway)](https://r-healthcare-readmission-production.up.railway.app/health)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Kayterthesly/r-healthcare-readmission/blob/main/LICENSE)

Production-grade healthcare ML pipeline predicting 30-day hospital readmission risk with RAG-cited clinical decision support.

- **Pipeline:** MIMIC-IV MEDS demo (100 real patients) synthesised to 15,000 via synthpop, canonical casting, DuckDB feature engineering, XGBoost + glmnet training, explainability and fairness audit, TF-IDF hybrid RAG retrieval, Plumber REST API, Shiny dashboard, GitHub Actions CI/CD
- **Model:** XGBoost v3, Recall 0.885 (gate: 0.85), AUC-ROC 0.566, honestly disclosed
- **RAG:** 40/30/30 hybrid retrieval (TF-IDF cosine + keyword density + ICD tag overlap) across 8 synthetic clinical guideline documents
- **Governance:** 8 DuckDB audit tables including predictions_audit, llm_call_log, fairness_reports with 19 subgroup rows
- **Testing:** 71 automated tests (55 unit + 16 integration), 0 failures
- **Fairness:** Race dimension flagged at 87pp recall gap, gender and insurance clear
- **Deployment:** Railway (Plumber API) + shinyapps.io (Shiny dashboard) + Backblaze B2 (82MB Parquet storage)
- Live Dashboard: https://e9yw5n-kayterthesly.shinyapps.io/healthcare-readmission-pipeline/
- Live API: https://r-healthcare-readmission-production.up.railway.app/health

---

### [crypto-price-pipeline](https://github.com/Kayterthesly/crypto-price-pipeline) — LIVE IN PRODUCTION

[![CI](https://github.com/Kayterthesly/crypto-price-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/Kayterthesly/crypto-price-pipeline/actions/workflows/ci.yml)
[![R 4.5](https://img.shields.io/badge/R-4.5.0-276DC2.svg?logo=r)](https://www.r-project.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Kayterthesly/crypto-price-pipeline/blob/main/LICENSE)

Production-grade cryptocurrency price forecasting pipeline built entirely in R.

- **Pipeline:** Yahoo Finance, DuckDB, 15 technical features, ARIMA, Plumber API, Shiny dashboard
- **Automation:** GitHub Actions cron (02:00 UTC daily), retrains, validates, detects model drift
- **Security:** X-API-Key auth, rate limiting, CORS, no secrets in code
- **Testing:** 35 automated tests (14 data integrity + 6 feature + 11 modeling + 1 integration)
- **Performance:** BTC-USD RMSE 0.0233, ETH-USD RMSE 0.0358
- Live Dashboard: https://e9yw5n-kayterthesly.shinyapps.io/crypto-price-pipeline/
- Live API: https://crypto-price-pipeline-production.up.railway.app/health

---

## Earlier Projects

- **Nigerian Retail Coupon Dashboard** — Excel + MySQL + Power BI (end-to-end BI pipeline)
- **Coupon Redemption Prediction** — Python ML + Power BI (predictive analytics)
- **Business Analytics Curriculum** — 29-day R + Python course for Aptech Centre, Lagos (Nigerian fintech case studies)

---

## Currently Learning

- Advanced deep learning for tabular healthcare data
- Web3 and blockchain analytics
- Funded MSc programmes in Data Science (target: 2026-2027)

---

## Technical Skillset

### Languages and Core Tools
<p>
  <img src="https://img.shields.io/badge/R-Production%20Grade-276DC3?style=flat&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/Python-Intermediate-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-Advanced-4479A1?style=flat&logo=mysql&logoColor=white" alt="SQL">
</p>

### ML and Forecasting
<p>
  <img src="https://img.shields.io/badge/XGBoost-Production-F7931E?style=flat" alt="XGBoost">
  <img src="https://img.shields.io/badge/ARIMA-Time%20Series-0891B2?style=flat" alt="ARIMA">
  <img src="https://img.shields.io/badge/tidymodels-ML%20Framework-276DC3?style=flat&logo=r&logoColor=white" alt="tidymodels">
  <img src="https://img.shields.io/badge/RAG-Clinical%20NLP-10B981?style=flat" alt="RAG">
  <img src="https://img.shields.io/badge/Feature%20Engineering-Production-6366F1?style=flat" alt="Feature Engineering">
  <img src="https://img.shields.io/badge/Drift%20Detection-MLOps-EF4444?style=flat" alt="Drift Detection">
  <img src="https://img.shields.io/badge/Fairness%20Auditing-Governance-8B5CF6?style=flat" alt="Fairness Auditing">
</p>

### Data Engineering and Databases
<p>
  <img src="https://img.shields.io/badge/DuckDB-Embedded%20OLAP-FFC107?style=flat" alt="DuckDB">
  <img src="https://img.shields.io/badge/Backblaze%20B2-Cloud%20Storage-E05B26?style=flat" alt="Backblaze B2">
  <img src="https://img.shields.io/badge/PostgreSQL-Intermediate-336791?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-Advanced-4479A1?style=flat&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Apache%20Arrow-Parquet-CC2927?style=flat" alt="Arrow">
</p>

### APIs, Dashboards and Visualisation
<p>
  <img src="https://img.shields.io/badge/Plumber-REST%20API-E4003A?style=flat&logo=r&logoColor=white" alt="Plumber">
  <img src="https://img.shields.io/badge/Shiny-Interactive%20Apps-276DC3?style=flat&logo=r&logoColor=white" alt="Shiny">
  <img src="https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75?style=flat&logo=plotly&logoColor=white" alt="Plotly">
  <img src="https://img.shields.io/badge/Power%20BI-Advanced-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Tableau-Intermediate-E97627?style=flat&logo=tableau&logoColor=white" alt="Tableau">
  <img src="https://img.shields.io/badge/Excel-Expert-217346?style=flat&logo=microsoft-excel&logoColor=white" alt="Excel">
</p>

### DevOps, Cloud and MLOps
<p>
  <img src="https://img.shields.io/badge/Docker-Containerisation-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=flat&logo=github-actions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Railway-Cloud%20Deploy-0B0D0E?style=flat&logo=railway&logoColor=white" alt="Railway">
  <img src="https://img.shields.io/badge/shinyapps.io-App%20Deploy-276DC3?style=flat&logo=r&logoColor=white" alt="shinyapps.io">
  <img src="https://img.shields.io/badge/renv-Reproducibility-276DC3?style=flat&logo=r&logoColor=white" alt="renv">
  <img src="https://img.shields.io/badge/testthat-106%20Tests%20Passing-27ae60?style=flat&logo=r&logoColor=white" alt="testthat">
  <img src="https://img.shields.io/badge/Gemini%20API-LLM%20Integration-4285F4?style=flat&logo=google&logoColor=white" alt="Gemini">
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Kayterthesly&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kayterthesly&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</p>

---

## KAIZEN 改善

> *Continuous improvement. Not perfection on day one, but better with every commit.*

Every project I ship follows a disciplined, stage-by-stage process: verify the foundation before building the walls, write tests before deploying, document every decision and every failure honestly. The healthcare pipeline went through 10 verified stages and 12 documented deployment failures before going live. The crypto pipeline went through 8 stages and 40+ commits. Both are now running in production with zero daily human intervention.

That is what separates a portfolio project from a production system.

---

<p align="center">
  <i>Open to remote Data Scientist, MLOps Engineer, Analytics Engineer, and ML Engineer roles</i><br/>
  <a href="mailto:Kingsleya402@gmail.com">Kingsleya402@gmail.com</a>
</p>
