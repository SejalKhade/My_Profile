# Sejal Khade — Data Analyst & Supply Chain Analytics

**M.S. Data Science · University of Texas at Arlington · May 2026**  
Arlington, TX · Open to relocate · F-1 STEM OPT · No sponsorship needed

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sejallk-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/sejallk)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-6366f1?style=flat)](https://sejalkhade.github.io)
[![Email](https://img.shields.io/badge/Email-sejalkhade0023@gmail.com-EA4335?style=flat&logo=gmail)](mailto:sejalkhade0023@gmail.com)

---

I build production-grade analytics systems on real government data — not tutorials, not sample datasets.  
Every project below has a **live URL**, **CI/CD**, **automated testing**, and outputs a business decision.

Targeting: **Data Analyst · Data Scientist · Supply Chain Analyst · Operations Analyst**

---

## Projects

### ⚡ Power Outage Risk Analysis Pipeline
> End-to-end ML system classifying high-risk electric utilities across all 50 U.S. states

- Processed **3.44M raw records** (EIA-861 + NOAA Storm Events) → 1,677 utility-level features
- Ran **28 MLflow tracked experiments** across 7 classifiers × 2 feature sets × 2 thresholds
- Detected and fixed data leakage: ROC-AUC corrected from 1.0 → **0.668** — the kind of silent failure most production models ship with
- Weather features drove **+54% ROC-AUC uplift** (0.434 → 0.668) over utility-only baseline
- **336 utilities** flagged High Risk across 50 states · **$74.5B** estimated annual economic loss
- Deployed: Gradio dashboard on Hugging Face Spaces + FastAPI REST endpoint + Docker

**Stack:** Python · scikit-learn · XGBoost · LightGBM · MLflow · FastAPI · Gradio · Folium · Docker · GitHub Actions · HF Spaces

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-HuggingFace-orange?style=flat)](https://sejjjallll-power-outage-risk-dashboard.hf.space)
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat&logo=github)](https://github.com/SejalKhade/Power-Outage-Risk-Pipeline)

---

### 🗺 DFW Commercial Rooftop Solar & Grid Readiness Analysis
> Geospatial procurement scoring pipeline ranking 8,600+ commercial buildings across 11 DFW counties

- Pulled live data from **3 APIs with zero manual collection**: OpenStreetMap (OSMnx), Census ACS5, NREL
- Built weighted procurement scoring model: **50% solar generation · 30% household demand · 20% EV gap**
- Ranked **357 priority sites** for energy infrastructure investment with zero manual input
- 1-mile and 3-mile GeoPandas spatial buffer joins quantified household demand coverage per site
- Outputs: GeoJSON · ranked CSV · interactive Folium map · Plotly dashboard

**Stack:** Python · GeoPandas · OSMnx · Folium · Plotly · Census ACS5 · NREL API · GeoJSON · Pandas

[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat&logo=github)](https://github.com/SejalKhade/DFW-Commercial-Rooftop-Solar-Energy-and-Grid-Readiness-Analysis-)

---

### 🚄 Texas HSR & Robotaxi Supply Cost Analysis
> Full-stack transportation analytics platform — 239-mile Dallas–Houston corridor

- Integrated **7 U.S. government datasets**: TxDOT AADT · BTS DB1B (2M+ records) · ERCOT (8,760 hourly) · EPA · Census ACS
- Gravity model allocating HSR ridership by flight demand (45%), road traffic (35%), population (20%)
- **Monte Carlo simulation (1,000 runs)** — P10/P50/P90 confidence intervals for cost, CO2, and revenue
- High adoption scenario: **3.12M annual riders · 149K metric tons CO2 avoided · $156M revenue**
- HSR + Robotaxi: **$78/trip vs $180 flight** · 2.05 hours faster than driving
- **29/29 pytest tests** passing · GitHub Actions CI on every push · DuckDB SQL analytics layer · Pandera data validation

**Stack:** Python · DuckDB · Streamlit · Plotly · Folium · Pandera · pytest · GitHub Actions · TxDOT · BTS · ERCOT · EPA

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-Streamlit-FF4B4B?style=flat&logo=streamlit)](https://texas-hsr-robotaxi-analysis-krq2zexxxymto8skk8p4bx.streamlit.app/)
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat&logo=github)](https://github.com/SejalKhade/Texas-HSR-Robotaxi-Transportation-Supply-Cost-Analysis)

---

## Technical Stack

| Domain | Tools |
|---|---|
| Languages | Python · SQL · R |
| ML & Modeling | scikit-learn · XGBoost · LightGBM · MLflow · Monte Carlo simulation |
| Data Engineering | Pandas · NumPy · DuckDB · Pandera · pytest · GitHub Actions CI |
| Geospatial | GeoPandas · OSMnx · Folium · GeoJSON |
| APIs & Data Sources | Census ACS5 · NREL · EIA · NOAA · TxDOT · BTS · ERCOT · EPA |
| Deployment | FastAPI · Docker · Streamlit · Gradio · Hugging Face Spaces · Azure |
| Visualization | Plotly · Tableau · Power BI |
| Supply Chain | Procurement scoring · Cost modeling · Scenario analysis · KPI dashboards · Vendor evaluation |

---

## Background

- 📍 Arlington, TX · Open to relocate anywhere in the US
- 🎓 M.S. Data Science — University of Texas at Arlington · May 2026
- 💼 Data Analyst @ UTA Research (Jan 2026 – present)
- 💼 Data Analyst Intern @ ETLHive · Analyzed 500K+ procurement records · drove sourcing policy changes within 30 days
- 🛂 F-1 STEM OPT · Authorized to work immediately · No sponsorship needed for 3 years
- 📬 [sejalkhade0023@gmail.com](mailto:sejalkhade0023@gmail.com)
- 🔗 [linkedin.com/in/sejallk](https://linkedin.com/in/sejallk)
