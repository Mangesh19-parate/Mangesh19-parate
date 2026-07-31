![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Mangesh%20Parate&fontSize=48&fontColor=fff&animation=twinkling&fontAlignY=38&desc=ML%20Engineer%20%7C%20Building%20AI%20for%20offline%20India&descAlignY=58&descSize=17)

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=800&color=2D9CDB&center=true&vCenter=true&width=680&lines=ML+Engineer+%7C+Data+Scientist;Rule-based+AutoML+%7C+Real-Estate+ML+%7C+VC+Analytics;Python+%7C+FastAPI+%7C+scikit-learn+%7C+XGBoost+%7C+SHAP;Open+to+DS+%2F+ML+Internships+%F0%9F%9A%80)](https://git.io/typing-svg)

**B.Tech IT · Graduating 2027 · 8.49 CGPA · Nagpur, India**

I design the full pipeline: problem statement, data, modeling, and deployment.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mangesh-parate-43310827b/)
[![Email](https://img.shields.io/badge/Email-paratemangesh19%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:paratemangesh19@gmail.com)
[![OCI Certified](https://img.shields.io/badge/Oracle-OCI%20AI%20Foundations%20Certified-F80000?style=flat&logo=oracle&logoColor=white)](https://www.oracle.com/cloud/)
![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Internships-brightgreen?style=flat)

</div>

---

## What I'm building

### Intelligent ML Studio — Rule-Based, Explainable AutoML Platform

> *Most AutoML tools optimize a black box and hand you a number. Intelligent ML Studio explains **why**: every metric choice, algorithm shortlist, and leakage flag traces back to a rule you can inspect.*

**The problem:** Beginners and experienced practitioners alike make avoidable ML mistakes: undetected data leakage, ignored class imbalance, misleading accuracy metrics, inconsistent train/inference preprocessing. Existing AutoML tools (Colab, Dataiku, H2O, Vertex AI) automate *execution*, not *guidance*.

**My solution:** A full-stack platform that walks a user through upload → diagnostics → recommendation → training → explainability → deployment, powered by a transparent, inspectable Recommendation Engine (not a learned "AI suggests" black box).

```
What it does
├── Diagnostics Engine — flags statistical leakage, class imbalance, missing values
├── Recommendation Engine — ~60–100 versioned YAML rules with a full traceable decision path
├── Preprocessing Pipeline Generator — guarantees identical train/inference transforms
├── Multi-algorithm training — scikit-learn, XGBoost, LightGBM + Optuna tuning
├── SHAP-based explainability with per-model-type explainer selection
├── Experiment tracking with dataset-level hashing + model versioning
└── One-click deployment of the best model as a REST API
```

**Stack:** `React` · `Tailwind CSS` · `FastAPI` · `Celery` + `Redis` · `scikit-learn` · `XGBoost` · `LightGBM` · `SHAP` · `Optuna` · `PostgreSQL` · `Docker`

**Status:** 🔧 In active development. Architecture, the ~22-paper literature review, and the full technical spec are done; the vertical slice (upload → diagnostics → training → prediction) is currently being built.

🔗 [View Repo](https://github.com/Mangesh19-parate/ML-STUDIO)

---

### HousingIQ — Real-Estate Price Prediction & Insights Platform

> *Buyers, sellers, brokers, and analysts in the Indian residential market have no single, explainable tool to price a property or read the market. I'm building one.*

**The problem:** No unified, data-driven way to get a fair, explainable price estimate for a property or to visually understand market patterns (by locality, city, size, amenities) across Indian metros.

**My solution:** An ML pipeline + web app trained on real residential listing data from four major Indian cities, with a FastAPI model-serving layer and a Flask-based insights dashboard.

```
What it covers
├── ~182K residential listings across Gurgaon, Hyderabad, Kolkata, Mumbai
├── Facet-level breakdowns: bedrooms, bathrooms, furnishing, amenities,
│   floor number, facing direction, ownership type, and more
├── Data profiling + cleaning pipeline (ydata-profiling, pandas)
├── Price prediction models — scikit-learn / XGBoost / LightGBM + SHAP
├── FastAPI serving layer, Flask dashboard for market insights
└── Parquet-based caching for fast repeated reads
```

**Stack:** `Python` · `Pandas` · `scikit-learn` · `XGBoost` · `LightGBM` · `SHAP` · `FastAPI` · `Flask` · `PostgreSQL` · `pytest`

**Status:** 🔧 In active development. Data pipeline and API/app scaffolding are in place; no live demo yet.

🔗 [View Repo](https://github.com/Mangesh19-parate/Housing-IQ-Real-Estate-Price-Prediction-Insights-Platform)

---

### Startup Funding Intelligence Dashboard

> *I couldn't find a single clean visualisation of Indian VC capital flows from 2018–2024, so I built one.*

VC analysts and ecosystem researchers use this to understand where Indian startup capital moves, who the power investors are, and how funding stage trends have shifted over time.

**Architecture:** Modular pipeline — `data_loader` → `filters` → `analysis` → `startup_view` → `investor_view`

**What it answers:**
- Which industries attract the most capital in India?
- Which cities dominate startup funding?
- Who are the most active investors by portfolio power score?
- How have funding stages (Seed → Series A/B/C) shifted year-over-year?

**Stack:** `Python` · `Pandas` · `Plotly` · `Streamlit` · `Matplotlib` · `Seaborn`

🔗 [View Repo](https://github.com/Mangesh19-parate/streamlit-dash) · [**Live App ↗**](https://startup-investment-dashboard.streamlit.app/)

---

## Skills — only what I have repos to prove

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**ML / Data**  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB0028?style=flat&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-8A2BE2?style=flat)

**Apps & Visualisation**  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Infra / Tools**  
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat&logo=git&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

---

## GitHub activity

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=Mangesh19-parate&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mangesh19-parate&layout=compact&langs_count=6&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mangesh19-parate&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mangesh19-parate/Mangesh19-parate/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mangesh19-parate/Mangesh19-parate/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Mangesh19-parate/Mangesh19-parate/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

## Let's build something together

I'm actively looking for **Data Science / ML Engineer internships** where I can work on real problems: Indian languages, edtech, fintech, or AI infrastructure.

If you're building something interesting or want to collaborate on an open-source project, reach out directly:

📧 **paratemangesh19@gmail.com**  
💼 **[linkedin.com/in/mangesh-parate-43310827b](https://www.linkedin.com/in/mangesh-parate-43310827b/)**

---

<div align="center">

*Explainable, production-minded ML, one traceable decision at a time.*
*Building AI for the 90% of India that doesn't have a stable internet connection.*

![Profile Views](https://komarev.com/ghpvc/?username=Mangesh19-parate&color=2D9CDB&style=flat&label=Profile+Views)

</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer)



