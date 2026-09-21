<div align="center">

<img src="hero.svg" alt="Chetan Bhangare, Financial and Data Analyst. FP&A, investment analytics, SQL, Python, Power BI. Open to work." width="100%"/>

<br/>

<a href="https://www.linkedin.com/in/chetanbhangare-ai-ml/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:cbhangare@wpi.edu"><img src="https://img.shields.io/badge/Email-cbhangare@wpi.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

<br/>

<img src="ticker.svg" alt="Ticker tape of project metrics: Walmart FY27 estimate $740.6B net sales, $34.5B operating income, $15.1B free cash flow; 3.5M+ transactions narrowed to 404 flagged; 33 ETFs and 88K+ rows; 91 backend tests; 90+ hours automated per month; 50K+ records cleaned; about 30% fewer manual scope reviews" width="100%"/>

<img src="divider.svg" width="100%" alt=""/>

## About

I turn financial and operational data into decisions using SQL, Python, Power BI, financial modeling, and automation.

I'm currently an **AI & Financial Analyst at Circa**, where I analyze and support invoicing, payments, revenue, and accounts receivable across Stripe and QuickBooks, improve the MySQL-backed job-tracking workflows, and enhance a YOLOv8 computer-vision estimating platform that cut manual scope reviews by about 30%. Before that: anomaly detection on 3.5M+ transit payments, RAG and workflow automation at AGI Beacon, and a cloud portfolio-analytics platform I built end to end.

**Open to:** Financial Analyst · FP&A · Data Analyst · Portfolio & Investment Analytics

<img src="terminal.svg" alt="Terminal-style profile monitor. The candlestick chart is illustrative simulated data. Watchlist of real project metrics: PortfolioIQ 88K+ daily records across 33 ETFs, transit fraud 404 flagged events out of 3.5M+ transactions, Walmart FP&A model FY27E net sales of $740.6B, 90+ hours of manual work automated per month, about 30% fewer manual scope reviews at Circa." width="100%"/>

<sub>The candlestick chart is illustrative simulated data. The watchlist shows real project metrics.</sub>

<img src="divider.svg" width="100%" alt=""/>

## What I Do

<table>
<tr>
<td valign="top" width="50%">

### 💹 Finance & FP&A
Driver-based forecasting, Budget vs. Actual, scenario and sensitivity analysis, and revenue and A/R tracking that gives management a clear view of cash and project performance.

</td>
<td valign="top" width="50%">

### 📊 Data Analytics & BI
SQL (CTEs, window functions), Python, Power BI, Tableau, and Excel. KPI dashboards, RFM and cohort analysis, and ETL pipelines that clean and validate 50K+ record datasets.

</td>
</tr>
<tr>
<td valign="top" width="50%">

### 📈 Investment & Predictive Analytics
Portfolio performance, risk, attribution, and optimization, plus predictive modeling and anomaly detection for fraud and forecasting problems.

</td>
<td valign="top" width="50%">

### ⚙️ AI & Automation
RAG pipelines (LangChain, GPT-4, Pinecone) and n8n / Flowise / Make.com workflows that remove manual reporting and route leads.

</td>
</tr>
</table>

<img src="divider.svg" width="100%" alt=""/>

## Featured Projects

### 🧾 Walmart Strategic FP&A & Financial Performance Model
<!-- TODO: add repo link once the workbook + README are public -->

A 15-tab, 6-year driver-based model (FY2024A–FY2029F) covering Walmart U.S., International, and Sam's Club, built from 10-K filings.

- **Forecast outputs:** FY2027 net sales of $740.6B, operating income of $34.5B, and free cash flow of $15.1B.
- **Scenarios:** 3 operating scenarios and 56 two-variable sensitivity outcomes across revenue growth, margins, operating income, and free cash flow.
- **Latest Estimate and Budget vs. Actual:** a quarterly framework across 11 line items that quantifies a $3.9B FY2026–FY2027 operating-income increase from volume, gross margin, membership growth, and SG&A leverage.
- **Benchmarking:** the forecast is compared against Walmart's published 4–5% sales-growth and 7–8.5% adjusted operating-income growth guidance.

`Excel` `Driver-based forecasting` `Scenario analysis` `Budget vs. Actual`

### 📈 [PortfolioIQ](https://github.com/ChetanBhangare/PortfolioIQ): Cloud Portfolio Analytics, Risk & Optimization Platform
<!-- TODO: add a live demo link here once you have the Vercel URL, e.g. **[Live demo](https://...)** -->

Deployed full-stack platform: `Python ETL → S3 (Parquet) → DuckDB → FastAPI on ECS/Fargate → Next.js on Vercel`

- **Data layer:** 33 ETFs and 88K+ daily records (2016–2026). Incremental ingestion with a per-ticker data-quality report. The weekday refresh runs on GitHub Actions with OIDC, so no AWS keys are stored.
- **Performance and risk:** CAGR, Sharpe, Sortino, Calmar, drawdowns, alpha/beta, tracking error, VaR/CVaR, Euler risk contributions, and historical stress windows (COVID crash, 2022 rate shock, 2023 banking stress).
- **Optimization and regimes:** minimum variance, maximum Sharpe, constrained risk parity, efficient frontier, and bull/bear × low/high-volatility regime analysis.
- **Engineering:** 91 deterministic backend tests, documented methodology, and an explicit limitations section.

`Python` `FastAPI` `AWS` `DuckDB` `GitHub Actions` `Next.js`

### 🛡️ Fraud Detection in Transit Payments (WPI capstone with Gemsen)
<!-- TODO: link a methodology write-up (no proprietary data) if you can publish one -->

Ensemble anomaly detection in SymetryML (ECOD, HBA, REPCA, OOSPCA) over 3.5M+ transit payment transactions, using 20+ behavioral and temporal risk indicators. It targeted three patterns: multiple cards per device, ZIP-code probing, and multiple devices per card. Consensus scoring narrowed the review population to 404 high-risk events, with 100% model agreement on 54 ZIP-probing cases. Selected for a capstone poster presentation.

`Anomaly detection` `Ensemble scoring` `Python` `SymetryML`

### 🔬 Quant Research: Reinforcement Learning & Omega-Ratio Analytics
<!-- TODO: link both repos. Add out-of-sample period, benchmark, rebalancing, transaction-cost, and fee assumptions to the DRL README. -->

- **DRL portfolio optimization:** A2C, PPO, and TD3 agents trained on 10+ years of market data with multithreaded backtesting. Backtests showed up to 18% cumulative excess return over benchmark indices.
- **Omega-ratio risk analytics:** an engine evaluating 1,000+ ETF allocations across 11 downside thresholds, with an Omega-efficient frontier over a 4-year horizon.

<img src="divider.svg" width="100%" alt=""/>

## Core Skills

<img src="marquee.svg" alt="Tools: Python, SQL, Excel, Power BI, Tableau, Pandas, Snowflake, BigQuery, AWS, FastAPI, scikit-learn, XGBoost, LangChain, QuickBooks, Stripe" width="100%"/>

**Tools:** Python · SQL · Excel · Power BI · Tableau · Pandas · Snowflake · BigQuery · AWS · FastAPI · scikit-learn · XGBoost · LangChain · QuickBooks · Stripe

**Finance methods:** FP&A · Forecasting · Variance Analysis · Budget vs. Actual · Scenario Modeling · Portfolio Analytics · Risk Analytics

<img src="divider.svg" width="100%" alt=""/>

## Professional Experience

| Role | Where | When | Highlights |
|---|---|---|---|
| AI & Financial Analyst | **Circa** | Jun 2026 – Present | Stripe + QuickBooks revenue and A/R, milestone billing (70/30, 60/40, 80/20), MySQL job-tracking workflows, YOLOv8 estimating platform |
| Fraud Risk Analyst (capstone) | **Gemsen** | Jan – May 2026 | Ensemble anomaly detection on 3.5M+ transactions |
| Generative AI Developer | **AGI Beacon** | Jan – May 2026 | n8n / Flowise / Make.com pipelines, CRM lead routing, RAG with LangChain + GPT-4 + Pinecone |
| AI Data Analyst | **AGI Beacon** | Jun – Aug 2025 | Python/Pandas ETL on 50K+ records, 0–100 scoring model ranking 10K+ properties |
| Graduate Assistant, FinTech Systems | **WPI** | Aug – Dec 2025 | Hyperledger Fabric test networks, 10+ validated transaction workflows |
| Financial Data Analyst | **HDPM Magical Infotech** | Sep 2021 – May 2023 | 50K+ record reconciliation, Power BI / Tableau KPI dashboards, RFM segmentation, NLP sentiment (76% → 85%) |

<img src="divider.svg" width="100%" alt=""/>

## More Projects

| Project | What it covers |
|---|---|
| [Employee Salary Prediction](https://github.com/ChetanBhangare/Employee-Salary-Prediction-and-Optimization-Using-Predictive-Analytics) | Regression, classification, and K-Means clustering on an HR dataset, with a Power BI workforce dashboard |
| COVID-19 Database Insights | Advanced SQL (joins, CTEs, window functions) on 1M+ records across 10+ countries <!-- TODO: link repo --> |
| [Online Retail Customer Segmentation](https://github.com/ChetanBhangare/Online-retail-customer-segmentation) | RFM analysis and K-Means clustering with silhouette validation |
| [Credit Card Default Prediction](https://github.com/ChetanBhangare/Credit-card-default-prediction) | Supervised ML classification for credit risk (notebooks) |

<img src="divider.svg" width="100%" alt=""/>

## Education & Certifications

**M.S. Financial Technology**, Worcester Polytechnic Institute (2026) · PG Diploma in Cyber Security, Tilak Maharashtra Vidyapeeth · BBA in Computer Applications, Pune University

Bloomberg Market Concepts · Google Data Analytics Professional Certificate · J.P. Morgan Investment Banking Simulation (Forage) · Goldman Sachs Controllers Simulation (Forage) · AlmaBetter Data Science Program

<br/>

<div align="center">

<img src="ticket.svg" alt="Order ticket. Symbol CHETAN.B, side HIRE, full-time. Roles: Financial Analyst, FP&A, Data Analyst, Investment Analytics. Worcester, MA, open to relocation. Status open." width="100%"/>

<br/>

<a href="https://www.linkedin.com/in/chetanbhangare-ai-ml/"><img src="https://img.shields.io/badge/LinkedIn-Chetan_Bhangare-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:cbhangare@wpi.edu"><img src="https://img.shields.io/badge/Email-cbhangare@wpi.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>
