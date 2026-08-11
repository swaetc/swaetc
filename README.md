<h1 align="center">Hi, I'm Eugene 👋</h1>
<h3 align="center">Data Analyst Intern | Final-Year BICT Student | Turning SA data into decisions</h3>

<p align="center">
📍 Gauteng, South Africa &nbsp;|&nbsp;
🎓 Final-year BICT @ University of Mpumalanga &nbsp;|&nbsp;
🏆 MAISH 2025 Hackathon Winner · Dirisa National Finalist · CHPC National Finalist 2026
</p>

<p align="center">
<a href="https://www.linkedin.com/in/eugene-ndhlovu02">LinkedIn</a> ·
<a href="mailto:siyaeugenendhlovu@gmail.com">Email</a> ·
Available November 30 · Open to remote, hybrid, or on-site in Gauteng
</p>

---

## What I do

I turn raw, often messy South African data into dashboards, statistical tests, and
predictive models that a non-technical stakeholder can actually act on. Every
project below starts from a real, verifiable pattern — a news headline, a public
dataset, a documented public debate — not an invented scenario, and every dataset
is either genuinely real (South African government sources) or clearly disclosed
as a realistic simulation where real data isn't publicly available.

---

## 🌟 Featured Projects

### 📦 A/B Test Analysis — SA E-Commerce Free Delivery Threshold
**[Live Repo →](https://github.com/swaetc/ab-test-analysis)** · `Python` `pandas` `SciPy` `Matplotlib`

Tested whether lowering a free-delivery threshold from R500 to R400 actually
increases average order value enough to justify it — designed with a
**pre-registered power analysis before any data was generated** (MDE R30, 80%
power, 310/group), not tuned after the fact. Result: a statistically significant
lift (p = 0.022) that sits *below* the business's own R30 threshold — an honest,
nuanced finding reported as-is rather than rounded up to a clean "it works."

### 📉 SA Telecom Churn Prediction with Revenue-at-Risk Ranking
**[Live Repo →](https://github.com/swaetc/churn-revenue-risk)** · `Python` `XGBoost` `SHAP` `scikit-learn`

Modeled churn on a Telco dataset rescaled to realistic SA postpaid ARPU bands
(R250–R900/month), comparing Logistic Regression against XGBoost (+12% F1).
Goes beyond a bare prediction list with a **revenue-at-risk ranking**
(churn probability × monthly value) that tells a retention team exactly who to
call first, and SHAP explainability that surfaces contract type and tenure as
the two biggest churn drivers — in plain language, not model jargon.

### ⚡ Does Load Shedding Actually Drive Crime in South Africa?
`Python` `pandas` `statsmodels` — *(in progress)*

A replication study testing a real, publicly-debated claim: does load-shedding
severity correlate with crime, and if so, which categories specifically? Combines
two real government datasets — SAPS crime statistics and Eskom's own load-shedding
severity data — with a time-trend-controlled regression to avoid the naive
"two lines went up together" trap, and an explicit, upfront limitations section
on what quarterly public data can and can't prove.

### 🗣️ Text-to-SQL Agent — Natural Language Database Interface
**[Live Repo →](https://github.com/swaetc/text-to-sql-agent)** · `FastAPI` `Streamlit` `SQLite` `Groq/Gemini API`

An end-to-end NL-to-SQL agent — plain English in, validated read-only SQL out.
Groq as primary LLM with Gemini as an automatic fallback, both free-tier, plus a
`sqlglot`-based validator that blocks malformed queries before they ever reach
the database. Evaluated against a hand-written test set covering lookups,
aggregations, joins, ranking, time-based queries, and deliberately unanswerable
questions — not just the easy cases.

### 🌦️ SA Weather Analytics ETL/ELT Pipeline
**[Live Repo →](https://github.com/swaetc/TheWeatherPipeline)** · `PostgreSQL` `Apache Airflow` `Open-Meteo API`

Automated pipeline ingesting real-time weather data for South African cities via
the Open-Meteo API into a PostgreSQL warehouse, orchestrated with Airflow DAGs —
data engineering fundamentals beyond notebook-only work. Includes a documented
fix for a production-grade SQLAlchemy version conflict between Airflow and the
pipeline's own dependencies.

---

## 🧱 By Track

**Analytics & Experimentation:** A/B Testing · Churn + Revenue-at-Risk · Load Shedding vs Crime
**Data Engineering:** Weather ETL/ELT Pipeline (Airflow, PostgreSQL)
**Applied ML / NLP:** Text-to-SQL Agent · SHAP-based churn explainability

---

## 📁 See More Projects

The featured projects above are my strongest, most polished work — but I keep
building. Full project index below, organized by discipline.

### Data Analytics & Experimentation
- **[A/B Test Analysis — Free Delivery Threshold](https://github.com/swaetc/ab-test-analysis)** — hypothesis-driven experiment design, power analysis, t-test
- **[SA Telecom Churn + Revenue-at-Risk](https://github.com/swaetc/churn-revenue-risk)** — XGBoost, SHAP, business-prioritized retention ranking
- **Does Load Shedding Drive Crime in SA?** *(in progress)* — SAPS + Eskom government data, time-trend-controlled regression

### Data Engineering
- **[SA Weather Analytics ETL/ELT Pipeline](https://github.com/swaetc/TheWeatherPipeline)** — Airflow DAGs, PostgreSQL, Open-Meteo API
- **BlockTrack (Project300)** *(capstone, in progress)* — 13-table PostgreSQL schema, Isolation Forest anomaly detection on real Cape Town tender data, Hyperledger Fabric backend

### Applied ML / NLP / Software Engineering
- **[Text-to-SQL Agent](https://github.com/swaetc/text-to-sql-agent)** — FastAPI + Streamlit, Groq/Gemini fallback, sqlglot query validation

📌 **[Browse all repos →](https://github.com/swaetc?tab=repositories)**

---

## 🛠️ Tech Stack

**Primary:** Python (pandas, NumPy, scikit-learn, SHAP, VADER, Matplotlib, Seaborn) · SQL · PostgreSQL · Power BI · Git
**Familiar:** R (basic) · Plotly · Streamlit · MySQL · SQLite · Linux CLI · REST APIs · Excel · Apache Airflow (basic) · Node.js
**Currently learning:** FastAPI (model deployment) · MLflow · Docker · Groq / Gemini API

---

## 🏆 Competitions & Recognition

- 🥇 **Winner — MAISH 2025 AI Hackathon** (72-hour build, 10 teams) — hybrid crop and animal disease detection solution
- 🏅 **National Finalist — Dirisa Student Competition 2025** — 1 of 4 selected from a 6-person university team to represent at the National Hackathon in Cape Town, working with vehicle telemetry data
- 🎓 **Coding Mentor — Dirisa Coding School** (2026–present) — mentoring high school learners in foundational programming

---



---

## 📫 Get in touch

📧 siyaeugenendhlovu@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/eugene-ndhlovu02) · 📍South Africa
