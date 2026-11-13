# Hi, I'm Tyler Yuen

I'm an MS Business Analytics + MS Management Information Systems student at the University of Illinois Chicago, graduating in December 2026. I build forecasting models, SQL databases, Tableau dashboards, and LLM-powered tools, and I teach business-statistics students how to use Claude for data analysis.

**Looking for:** entry-level analyst roles (data, business intelligence, or financial), mainly in Chicago.

## Projects

**ChainAnalyticsAI — Healthcare Supply Chain Forecasting (Capstone, team of 7)**
Python · SQL · PostgreSQL · Tableau · React · FastAPI
- Forecast weekly medical-supply demand with ARIMA (~13.7% MAPE) and used Lasso regression to explain demand drivers
- Built a One-Class SVM early-warning model that flags items at risk of stocking out
- Delivered a live Tableau dashboard tracking stockout risk, vendor concentration, and cost-weighted demand

**[MLOps Model Monitoring & Governance Framework](https://github.com/tcyuen2/Healthcare-AI-Dashboard)**
Python · FastAPI · Docker · Prometheus · Grafana · MLflow
- Served an ML model through a FastAPI service with live Prometheus metrics and a Grafana dashboard
- Ran a seeded A/B test (~5,700 samples per version) to decide which model to ship
- Built drift detection (PSI, KS tests) that caught accuracy falling from 0.99 to 0.66 while model confidence stayed high
- Documented governance with a model card, risk register, lineage diagram, and audit trail

**[RAG Pipeline & Multi-Tool AI Agent](https://github.com/tcyuen2/ids568-milestone6-tcyuen2)**
Python · FAISS · sentence-transformers · Ollama (Mistral 7B)
- Retrieval-augmented question answering with a local 7B LLM, reaching 0.89 recall@4 on 10 test queries
- An agent that picks between retrieval and summarization tools for multi-step tasks; completed 9 of 10 test tasks

**Lending Club Loan Default Prediction**
R (dplyr, ggplot2) · Logistic Regression · Random Forest · XGBoost
- Predicted default risk on 45,000+ peer-to-peer loans, with ROI and loan-term features built during exploratory analysis

**Bank Marketing Campaign Classification**
Decision Trees · Random Forest · Naive Bayes
- Predicted rare term-deposit subscribers, judging models by ROC/AUC instead of raw accuracy and tuning thresholds for marketing decisions

**[Student Project Management App](https://github.com/tcyuen2/Project_Management_App)** (team of 4)
Java · JavaFX · Firebase · Google Gemini API
- Desktop app with task tracking, timelines, and AI task suggestions powered by Gemini

## Skills

- **Programming & query:** SQL, Python, R, Java, JavaScript/TypeScript
- **Analytics:** predictive modeling, time-series forecasting (ARIMA), machine learning, data mining
- **Data & BI tools:** Tableau, PostgreSQL, MySQL, MS SQL Server (SSAS, SSIS), Excel
- **MLOps & AI:** Docker, FastAPI, MLflow, Prometheus, Grafana, FAISS, RAG, LLM agents (Ollama)
- **AI tools:** Claude (AI-assisted coding, data analysis, and visualization)

## Teaching

Teaching assistant for IDS 270 (Business Statistics I) and IDS 371 (Business Statistics II) at UIC: I lead lab sections, run review sessions, and train students to analyze real datasets in R and with Claude.

## Contact

[LinkedIn](https://www.linkedin.com/in/tyler-yuen/)
