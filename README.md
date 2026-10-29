# Erica (Yun) Yang

**Data Scientist | Applied AI & Machine Learning | Statistical Modeling | LLM Evaluation**

I am a Data Scientist with a Ph.D. in Statistics and experience in applied machine learning, predictive modeling, experimentation, and business analytics. My work focuses on whether models and analytical systems are reliable enough to support real decisions—not only whether they achieve a strong headline metric.

My current work also includes LLM-assisted analytics and evidence-grounded AI applications, with an emphasis on separating generative model outputs from deterministic validation. I am particularly interested in model evaluation, probability calibration, stability analysis, statistical inference, and translating evidence into clear recommendations.

[LinkedIn](https://www.linkedin.com/in/yunyang09/) · [Email](mailto:ericayang.work@gmail.com)

## Core Expertise

- **Applied AI & LLM Systems:** LangGraph workflows, OpenAI Structured Outputs, schema-aware Text-to-SQL, SQLGlot AST validation, evidence-grounded outputs, FastAPI, and LLM evaluation design
- **Applied Machine Learning:** XGBoost, Random Forest, Logistic Regression, classification, feature engineering, model validation, SHAP, PyTorch, and transformer-based NLP
- **Statistical Evaluation:** ROC-AUC, PR-AUC, probability calibration, threshold analysis, simulation-based testing, Kendall-tau stability, bootstrap uncertainty, and subgroup diagnostics
- **Product and Business Analytics:** A/B testing, KPI development, customer segmentation, conversion, retention, revenue analysis, SQL workflows, and interactive dashboards
- **Programming and Tools:** Python, SQL, R, SAS, C++, pandas, NumPy, SciPy, scikit-learn, PyTorch, Hugging Face Transformers, Git/GitHub, Tableau, Power BI, and AWS, CI/CD

## Research & Publication

First-Author Publication — Statistical Methods in Medical Research (2026)

Yang, Y., Lin, X., & Nelson, K. P. (2026). Diagnostic accuracy analysis for multiple raters using probit hierarchical model for ordinal ratings. Statistical Methods in Medical Research, 35(1), 205–221.
[Read the Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12783370/)

Developed a Bayesian hierarchical probit framework for ordinal diagnostic ratings with latent disease classes and rater-specific effects. Derived closed-form ROC curves and AUCs, including covariate-specific extensions, and evaluated the methods through simulation and mammography data analysis.

## Ongoing Research — Statistical Machine Learning

Developing a rearrangement-based unsupervised learning framework for multi-tensor ordinal data, combining permutation-based alignment, clustering, and theoretical analysis of latent group recovery.

## Featured Projects

### Applied AI & LLM Applications

**[LLM-Powered Statistical Analytics Agent — v0.1.0 MVP](https://github.com/newbornalive/llm-analytics-agent)**  
A five-stage LangGraph workflow that integrates optional schema-aware LLM query planning, AST-guarded read-only SQL, and LLM-independent statistical analysis. Produces traceable JSON/SVG reports with confidence intervals, hypothesis tests, and multiple-comparison correction. Includes a reproducible 17-case scoped acceptance benchmark and GitHub Actions CI on Python 3.11/3.12.  
**Stack:** Python, LangGraph, OpenAI Structured Outputs, SQLGlot, SQLite, SciPy, FastAPI, pytest. · [Release v0.1.0](https://github.com/newbornalive/llm-analytics-agent/releases/tag/v0.1.0)

**[Job Scout — v0.6.1 Prototype](https://github.com/newbornalive/job-scout)**  
A Chrome/Edge extension for capturing job descriptions, routing resume variants, and tracking applications. Combines local rule-based matching with optional OpenAI-powered requirement analysis. The local Node.js backend validates structured responses and checks quoted evidence against source text; the workflow includes stale-result detection, access controls, and automated tests.  
**Stack:** JavaScript, Chrome/Edge Manifest V3, Node.js, OpenAI Responses API, Structured Outputs, GitHub Actions. · [Releases](https://github.com/newbornalive/job-scout/releases)

*Both projects have working scoped prototypes and automated tests. Live LLM task accuracy has not been independently benchmarked; neither project claims production deployment or general-purpose autonomous behaviour.*

### Machine Learning, Statistical Modelling & Analytics

| Project | Focus | Methods and Tools |
|---|---|---|
| [Financial Market Sentiment Analysis](https://github.com/newbornalive/NLP_based_Sentiment_Analysis_for_Financial_Market) | Reproducible NLP analysis of financial-text sentiment | FinBERT, VADER, Hugging Face Transformers, PyTorch, Python |
| [Credit Default Risk Modeling](https://github.com/newbornalive/credit-risk-modeling) | Credit-risk modelling with calibrated probabilities and decision thresholds | XGBoost, Random Forest, Logistic Regression, ROC-AUC, PR-AUC |
| [Portfolio Optimization and Investment Risk Analysis](https://github.com/newbornalive/portfolio-optimization) | Portfolio construction with out-of-sample evaluation and risk diagnostics | Black-Litterman, covariance shrinkage, walk-forward testing, VaR/CVaR |
| [Customer Revenue and Retention KPI Dashboard](https://github.com/newbornalive/Customer_Revenue_and_Retention_KPI_Dashboard) | Revenue, retention, conversion and customer analytics | SQL, Python, Dash, Power BI, DAX |
| [Diabetes Risk Prediction](https://github.com/newbornalive/diabetes-ai-prediction) | Comparison of machine-learning and neural-network models for healthcare risk prediction | XGBoost, PyTorch CNN, calibration, SHAP |
| [Healthcare Missing-Data Reliability](https://github.com/newbornalive/healthcare-missing-data-strategy) | Simulation-based comparison of missing-data assumptions and imputation strategies | MCAR, MAR, MNAR, multiple imputation, simulation |

## Current Focus

I am developing and evaluating applied AI, machine-learning, and statistical analytics workflows that combine:

- rigorous statistical evaluation;
- reproducible data and modeling pipelines;
- business or domain-specific decision logic;
- clear documentation of assumptions, limitations, and responsible use.

## Professional Interests

Generative AI · Applied machine learning · Predictive modeling · Bayesian Deep Learning · Product analytics · Experimentation · Model reliability · Financial and healthcare analytics · Decision-support systems
