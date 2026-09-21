# Chetan Bhangare

**Financial Analyst | FP&A · Portfolio & Investment Analytics · AI-Enabled Finance Automation**

M.S. Financial Technology, Worcester Polytechnic Institute (2026) · Worcester, MA · Open to relocation

[LinkedIn](https://www.linkedin.com/in/chetanbhangare-ai-ml/) · [Email](mailto:cbhangare@wpi.edu)

---

## About

I build the models, pipelines, and dashboards that finance teams use to make decisions.

Right now I'm an **AI & Financial Analyst at Circa**, where I manage revenue, invoicing, and accounts receivable across 100+ active customer accounts a month (Stripe + QuickBooks) and connect estimating, scheduling, and billing data into project-level financial reporting. Before that: fraud analytics on 3.5M+ transit payments, cloud portfolio analytics, and LLM/RAG automation.

I'm looking for full-time **Financial Analyst, FP&A, Portfolio Analytics, and Investment Data Analytics** roles.

---

## Selected Results

| Where | What | Result |
|---|---|---|
| Circa | Milestone billing (70/30, 60/40, 80/20) for projects up to 14 days; YOLOv8 estimation platform | Billing tied to project progress; ~30% fewer manual scope-review cycles |
| Walmart FP&A model | 15-tab, 6-year driver-based model built from 10-K filings | 3 scenarios, 56 sensitivity outcomes, FY2027 forecast of $740.6B net sales |
| PortfolioIQ | Cloud portfolio analytics platform (AWS + Vercel) | 33 ETFs, 88K+ daily records, 91 automated backend tests |
| Transit fraud capstone | Ensemble anomaly detection on payment data | 3.5M+ transactions narrowed to 404 high-risk events |
| AGI Beacon | Real-estate ETL and 0–100 scoring model | 50K+ records cleaned, 10K+ properties ranked, preprocessing time down 35% |
| AGI Beacon | n8n / Flowise / Make.com automation and CRM lead routing | 90+ manual hours per month eliminated, qualified lead conversion up 15% |

---

## Featured Projects

### [PortfolioIQ](https://github.com/ChetanBhangare/PortfolioIQ) — Cloud Portfolio Analytics, Risk & Optimization Platform
<!-- TODO: add live demo link here once you have the Vercel URL, e.g. "**[Live demo](https://...)**" -->

Deployed full-stack platform: `Python ETL → S3 (Parquet) → DuckDB → FastAPI on ECS/Fargate → Next.js on Vercel`

- **Data layer:** 33 ETFs, 88K+ daily records (2016–2026). Incremental ingestion with a per-ticker data-quality report. Weekday refresh runs on GitHub Actions using OIDC, so no AWS keys are stored anywhere.
- **Performance and risk:** CAGR, Sharpe, Sortino, Calmar, drawdowns, alpha/beta, tracking error, VaR/CVaR, Euler risk contributions, concentration (HHI), and historical stress windows (COVID crash, 2022 rate shock, 2023 banking stress).
- **Optimization:** minimum variance, maximum Sharpe, constrained risk parity, and an efficient frontier with turnover constraints.
- **Market regimes:** bull/bear × low/high-volatility classification with conditional portfolio performance.
- **Engineering:** 91 deterministic tests, documented methodology, and an explicit limitations section.

`Python` `FastAPI` `DuckDB` `AWS S3` `ECS/Fargate` `GitHub Actions` `Next.js` `Plotly`

### Walmart Strategic FP&A & Financial Performance Model
<!-- TODO: add repo link once the workbook + README are public -->

Driver-based model (FY2024A–FY2029F) covering Walmart U.S., International, and Sam's Club, built from 10-K filings. Includes 3 operating scenarios and 56 two-variable sensitivity outcomes across revenue growth, margins, operating income, and free cash flow. A quarterly Latest Estimate and Budget vs. Actual framework covers 11 line items and quantifies a $3.9B FY2026–FY2027 operating-income increase from volume, gross margin, membership growth, and SG&A leverage. The forecast is benchmarked against Walmart's published sales and adjusted operating-income growth guidance.

`Excel` `Driver-based forecasting` `Scenario & sensitivity analysis` `Budget vs. Actual`

### Fraud Detection in Transit Payments (WPI capstone with Gemsen)
<!-- TODO: link a methodology write-up (no proprietary data) if you can publish one -->

Ensemble anomaly detection in SymetryML (ECOD, HBA, REPCA, OOSPCA) over 3.5M+ transit payment transactions, using 20+ behavioral and temporal risk indicators. Covered three fraud patterns: multiple cards per device, ZIP-code probing, and multiple devices per card. Consensus scoring reduced the review population to 404 high-risk events, with 100% model agreement on 54 ZIP-probing cases. Selected for a capstone poster presentation.

`Anomaly detection` `Ensemble scoring` `Python` `SymetryML`

### Deep Reinforcement Learning Portfolio Optimization
<!-- TODO: link repo. Add out-of-sample period, benchmark, and transaction-cost assumptions to its README. -->

A2C, PPO, and TD3 agents trained on 10+ years of market data with multithreaded backtesting and risk-adjusted performance analysis. Backtests showed up to 18% cumulative excess return over benchmark indices.

`Python` `Reinforcement learning` `Backtesting`

### Omega-Ratio Portfolio Risk Analytics
<!-- TODO: link repo -->

Risk engine evaluating 1,000+ ETF allocations across 11 downside thresholds, with an Omega-efficient frontier over a 4-year horizon and asymmetric (downside) risk metrics.

`Python` `Omega ratio` `Downside risk`

---

## More Projects

| Project | Focus |
|---|---|
| [Employee Salary Prediction](https://github.com/ChetanBhangare/Employee-Salary-Prediction-and-Optimization-Using-Predictive-Analytics) | Regression and classification on a 1,009-employee HR dataset, with a Power BI workforce dashboard |
| [Credit Card Default Prediction](https://github.com/ChetanBhangare/Credit-card-default-prediction) | Supervised ML classification (notebooks) |
| [Online Retail Customer Segmentation](https://github.com/ChetanBhangare/Online-retail-customer-segmentation) | RFM analysis and K-Means clustering with silhouette validation |
| [Seoul Bike Sharing Demand](https://github.com/ChetanBhangare/Bike-sharing-demand-prediction) | Demand forecasting with Random Forest, Gradient Boosting, and XGBoost |
| [Hotel Booking EDA](https://github.com/ChetanBhangare/EDA-hotel-booking-analysis) | Exploratory analysis of booking behavior |

---

## Skills

| Area | Tools & methods |
|---|---|
| **FP&A & Finance** | Driver-based modeling, budgeting & forecasting, variance and Budget vs. Actual analysis, scenario and sensitivity analysis, KPI reporting, revenue and AR/collections tracking, milestone billing |
| **Portfolio & Risk** | Performance and benchmark analysis, attribution, VaR/CVaR, Sharpe/Sortino/Calmar, drawdown analysis, portfolio optimization, stress testing, Omega ratio |
| **Data & Programming** | Python (pandas, NumPy, scikit-learn, FastAPI), SQL, advanced Excel (pivot tables, dynamic formulas, VBA) |
| **BI & Reporting** | Power BI, Tableau, Excel dashboards |
| **Cloud & Automation** | AWS (S3, ECS/Fargate), Snowflake, BigQuery, GitHub Actions, Docker, Next.js, n8n, Flowise, Make.com, LangChain, Pinecone, Stripe, QuickBooks |

**Certifications:** Bloomberg Market Concepts · J.P. Morgan Investment Banking Simulation (Forage) · Goldman Sachs Controllers Simulation (Forage) · Google Data Analytics

---

## Experience

- **Circa** — AI & Financial Analyst (Jun 2026 – Present)
- **Gemsen** — Fraud Risk Analyst, capstone (Jan – May 2026)
- **AGI Beacon** — Generative AI Developer (Jan – May 2026); AI Data Analyst (Jun – Aug 2025)
- **Worcester Polytechnic Institute** — Graduate Assistant, FinTech Systems (Aug – Dec 2025)
- **HDPM Magical Infotech** — Financial Data Analyst (Sep 2021 – May 2023)

---

## Get in Touch

Open to full-time roles in Financial Analysis, FP&A, Portfolio Analytics, and Investment Data Analytics.

[LinkedIn](https://www.linkedin.com/in/chetanbhangare-ai-ml/) · [cbhangare@wpi.edu](mailto:cbhangare@wpi.edu)
