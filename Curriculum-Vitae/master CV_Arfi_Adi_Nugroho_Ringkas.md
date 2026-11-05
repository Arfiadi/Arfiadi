# Arfi Adi Nugroho

**APPLIED DATA SCIENCE STUDENT | INTERNSHIP CANDIDATE**

Surabaya, Indonesia · arfiadi13@gmail.com · 082338436210 · LinkedIn: [Arfi Adi Nugroho](https://www.linkedin.com/in/arfi-adi-nugroho-58b0a7263) · GitHub: [Arfiadi](https://github.com/Arfiadi)

## SUMMARY

Fifth-semester Applied Data Science student seeking an internship to help solve real-world business problems through data and AI. Takes a problem-oriented, end-to-end approach, from understanding problem context and designing suitable solutions to developing, evaluating, and deploying them. Brings a foundation in analytics, data engineering, and ML engineering.

**INTERSHIP AVAILABILITY** : Starting 28 December 2026 | Duration: 4-6 months

## EDUCATION

**Politeknik Elektronika Negeri Surabaya (PENS)** — Applied Data Science, 2024–Present · GPA 3.70/4.00

**Relevan Coursework:** Applied Statistical analysis & Modeling, Artificial Intelligence, Machine Learning, Data Mining, Data Exploration and Visualization, Web Service Technology, MLOps,  Big Data Infrastructure and Management, and Data Warehouse. 

## PROJECTS

[HargaWatch Surabaya — Food Price Intelligence & Early Warning System](https://github.com/Arfiadi/hargawatch-surabaya) | [Live Demo](https://hargawatch-surabaya.vercel.app/)  
Tech: Python, Next.js, React, Tailwind CSS, Supabase (PostgreSQL), CatBoost, XGBoost, Scikit-learn
- Engineered an automated data pipeline ingesting 476k+ daily food price records (2020–2026) across 6 traditional markets and 37 commodities, applying zero-lookahead feature engineering and Keputran wholesale price transmission signals.
- Built a two-tier forecasting engine using CatBoost and XGBoost quantile regression (p10, p50, p90) for multi-step horizons, coupled with an adaptive 4-pillar Early Warning System, automated Telegram alerts, and a Next.js 15 GIS disparity dashboard.

[PovertyRadar SDGs — Regional Poverty Vulnerability & Clustering Platform](https://github.com/Arfiadi/poverty-radar) | [Live App](https://poverty-radar.vercel.app/)  
Tech: Python, Scikit-learn, Pandas, React, TypeScript, Vite, ECharts, Tailwind CSS
- Audited 514 Indonesian regencies/cities across 34 provinces using BPS data, removing leakage-prone labels and isolating 26 multivariate anomalies (Isolation Forest) without dropping 3T regions.
- Benchmarked 20+ clustering setups to justify K-Means (k=4, ARI=0.9803 across 20 seeds) on 7 structural features, mapping 4 socio-economic archetypes into a 5-act interactive storytelling dashboard.

[HRSS Industrial Operational Recommendation System](https://github.com/Arfiadi/HRSS-recommendation-system) | [Live Demo](https://hrss-recommendation-system.vercel.app/) · [API Docs](https://hrss-recommendation-system.onrender.com/docs)  
Tech: Python, Pandas, Scikit-learn, MLflow, FastAPI, React, Docker
- Processed 46,898 telemetry records, removed a target-leakage feature, and evaluated a Random Forest using ROC-AUC-F1 on a chronological holdout of 9,380 records.
- Built a hybrid recommendation system combining ML-based operational pattern recognition with rule-based safety overrides; integrated FastAPI, MLflow tracking, automated tests, and a React dashboard.

[Global Inventory Business Intelligence Pipeline](https://github.com/Arfiadi/global-inventory-bi-pipeline) | [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzFkYzE2ZjItMjZmZi00MmFmLTk3ODktMDJjNmY4MDFhNzNiIiwidCI6IjUxZDc5MGQ1LWJlZmItNDg0ZS04NmM2LWQxN2I2NDcyNzYyNCIsImMiOjEwfQ%3D%3D)  
Tech: MySQL, PostgreSQL, Pentaho, Python, Prophet, XGBoost, Power BI
- Built an end-to-end decision-support pipeline: Pentaho ETL, PostgreSQL star-schema warehouse, and SQL semantic layer over MySQL transactional data.
- Aplied Spectral Clustering for inventory segmentation and compared Prophet, XGBoost, and SARIMAX for demand forecasting; Prophet achieved the lowest MAPE. delivered via Power BI.

[Customer Segmentation Analytics Dashboard](https://github.com/Arfiadi/absd-customer-segmentation) |  [Live App](https://absd-customer-seg.streamlit.app/)  
Tech: Python, Scikit-learn, Streamlit, Plotly
- K-Means segmentation on 21 features with RobustScaler and PCA (Silhouette 0.5012); deployed a Streamlit dashboard with KPIs, four segment profiles, and live segment prediction.

[Telco Customer Churn Prediction & Intelligent Retention Platform](https://github.com/Arfiadi/telco-churn-classification)  
Tech: Python, Pandas, Scikit-learn, LightGBM, Optuna, SHAP, PydanticAI, Streamlit
- Built a leakage-safe LightGBM pipeline on 7,043 IBM Telco records, engineering four behavioral features and tuning with Optuna; achieved 0.835 ROC-AUC on a 20% holdout set.
- Developed a Streamlit retention platform with OOF profit-threshold optimization, SHAP explanations, batch prioritization, what-if analysis, and an AI copilot with deterministic fallback.

[FMCG Product Portfolio & Revenue Intelligence](https://github.com/Arfiadi/GelarRasa-DSC2025)  |  Gelar Rasa 2025, Team Sepertiga Malam  
Tech: Python, LightGBM, Prophet, Statsmodels, Scikit-learn
- Contributed to hierarchical revenue forecasting using Prophet at the aggregate level and ARIMAX at the product level; the team reported MAPE below 2% and 2-5%, respectively.
- Applied MinT reconciliation to align forecasts across aggregate and product levels

[Waste Image Classification](https://github.com/Arfiadi/SatDat-BDC2026-PondasiPagi)  |  Satria Data BDC 2026, Team Pondasi Pagi  
Tech: PyTorch Lightning, Albumentations, Hydra, W&B, FiftyOne, Cleanlab, FAISS
- Curated an imbalanced image dataset, reducing duplicates from 26,527 to 26,180 images; conducted 17 CNN/ViT experiments with stratified 5-fold cross-validation.
- A soft-voting ensemble of ConvNeXt-based models and EVA02 achieved 0.9889 out-of-fold Macro F1 and 0.9793 on the public leaderboard.

[Pothole Semantic Segmentation](https://github.com/Arfiadi/ARA-ITS-2026)  |  ARA 7.0 Data Science Competition (ITS) 2026, Team Anti Galau  
Tech: PyTorch, segmentation_models_pytorch, Albumentations, OpenCV
- Built a pothole semantic segmentation pipeline using U-Net++ with an EfficientNet-B4 encoder and a hybrid Dice/BCE loss, evaluated with 5-fold cross-validation.
- Applied augmentations for variations in lighting, sharpness, perspective, and road texture; combined fold-based ensembling, test-time augmentation, and morphological and connected-component filtering to refine predicted masks.

[AI Interview Coach](https://github.com/Arfiadi/app-interview) | [Live App](https://app-interview-xi.vercel.app/) · [API Docs](https://interview-backend-737275753890.asia-southeast1.run.app/docs)  
Tech: Next.js, TypeScript, FastAPI, OpenRouter, PostgreSQL, Redis, Docker
- Full-stack interview practice platform generating role-specific questions with AI answer scoring and STAR-method feedback.
- JWT auth, session history, performance analytics, and PDF report export on a FastAPI, PostgreSQL, and Redis backend.

[FlowAgent — Agentic Financial Assistant for Indonesian SMEs](https://github.com/Arfiadi/flowagent-antigravity) | [Live App](https://gen-lang-client-0964227719.web.app/)  
Tech: FastAPI, Gemini via Vertex AI, Firestore, React, TypeScript, Docker, Cloud Run
- Multimodal extraction (Gemini 2.5 Flash) of receipts, voice, and text into validated financial records with human review; Firestore-based liquidity indicators (health score, cash runway, risk level).
- Gemini 2.5 Pro agentic workflow generating mitigation-action drafts for receivables, supplier negotiation, and inventory risk; backend on Cloud Run, frontend on Firebase Hosting.

[Aquaculture Water Quality Classification](https://github.com/SoviaLearner/satria-water-quality-ews) |  [Live App](https://satria-water-quality-ews-sage.vercel.app/)  
Tech: Scikit-learn, LightGBM, MLflow, FastAPI, Docker, Google Cloud Run
- Compared Logistic Regression, Decision Tree, Random Forest, and LightGBM for four-class water suitability classification using a 4,300-record dataset.
- Contributed to the ML component, inference backend, and deployment of a microservices-based application with MLflow tracking, FastAPI services, and a React dashboard.

[Heart Disease Clinical Screening & Prediction System](https://github.com/Arfiadi/heart-disease-prediction) | [Live App](https://heart-disease-predictiongit-yuguekaou65jhemfr9kj2g.streamlit.app/)  
Tech: Scikit-learn, MLflow, SHAP, Streamlit, Gemini API
- Compared Logistic Regression, Decision Tree, MLP, and Random Forest with stratified CV; selected Random Forest (82.8% accuracy, 0.898 ROC-AUC) with SHAP explanations.
- Streamlit clinical decision-support app with risk visualization, AI-assisted lifestyle guidance (rule-based fallback), and downloadable reports.

[East Java Food & Beverage Consumption Clustering](https://github.com/Arfiadi/jatim-fnb-clustering) | [Live Dashboard](https://jatim-fnb-clustering.streamlit.app/)  
Tech: Python, Pandas, Scikit-learn, Streamlit, Plotly
- Agglomerative Hierarchical Clustering on BPS 2024 expenditure data for 38 regencies/cities, comparing four linkage methods and selecting Ward's linkage with three clusters.
- Built a Streamlit dashboard with regional mapping and PCA visualization to communicate cluster-level patterns and potential implications for regional FMCG distribution, packaging, and pricing.

[Gastrointestinal Infection Expert System](https://github.com/Arfiadi/expertsystem-gastrousus) | [Live App](https://arfiadi-expertsystem-gastrousus-diagnosis-gastrousus-pykpyh.streamlit.app/)  
Tech: Python, Streamlit
- Rule-based system scoring 19 symptoms to rank five infection/food-poisoning hypotheses with a configurable threshold; Streamlit UI shows scores and intermediate assessments.

[JobStreet Data Analysis — Indonesia Data Job Market](https://github.com/Arfiadi/jobstreet-data-analysis)  
Tech: Python, Pandas, Matplotlib, Seaborn, WebScraper.io
- Cleaned and analyzed 878 data job listings on JobStreet Indonesia (collected on 1 June 2025), standardizing job titles, salary ranges, locations, and posting dates.
- Exploratory analysis of roles, salaries, employment types, and geography: Data Analyst was the most frequent role and Greater Jakarta the main job-market concentration.

## TECHNICAL SKILLS

**Programming & Query Languages:** Python, SQL, R  
**Data Analytics & Visualization:** Pandas, NumPy, Statsmodels, Power BI, Plotly, Exploratory Data Analysis (EDA), Data Cleaning, Statistical Analysis, Hypothesis Testing  
**Machine Learning & AI:** Scikit-learn, XGBoost, LightGBM, Prophet, PyTorch, Feature Engineering, Model Evaluation, Classification, Regression, Clustering, Time-Series Forecasting, Recommendation Systems, Computer Vision, Natural Language Processing (NLP)  
**Data Engineering & Databases:** MySQL, PostgreSQL, ETL/ELT, Data Warehousing, Dimensional Modeling, Apache Spark, Hadoop  
**MLOps & Application Development:** MLflow, Weights & Biases, Git, Docker, FastAPI, Streamlit, React, Model Serving, Experiment Tracking  

## ADDITIONAL INFORMATION

**Languages:** Indonesian, English  
**Training & Certification:** DQLab ML & AI Bootcamp (Batch 14), Google Cloud Gen AI Academy APAC (Cohort 1), LKKM Pra-dasar & Dasar, Mentor of Mentoring Keagamaan 2025 (UKM UKKI), and others. [Certificates](https://drive.google.com/file/d/1j6cT8VzE61Nv8ten-L2FZQWsse7tI1Rs/view?usp=sharing)
