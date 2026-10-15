# Nikita Ivanishchev

**Applied Machine Learning · MSc in Applied Mathematics and Computer Science, MEPhI (2026–2028)**

I build and evaluate ML models and develop Python services around them. My main interests are **tabular ML, trustworthy model evaluation, retrieval/ranking, and ML engineering**.

**Open to:** ML / Data Science internships and entry-level ML engineering roles in Europe.  
[LinkedIn](https://www.linkedin.com/in/nikita-ivanisev) · [Email](mailto:nikitosivanisev317@gmail.com)

## Selected projects

### [Avito Bot Detection — behavioral ML](https://github.com/Leo-Daiser/avito-bot-detection)
**Python · pandas · CatBoost · scikit-learn**

- Developed **105 behavioral features** from user event logs and a **5-model CatBoost ensemble**.
- Prevented **temporal leakage** by excluding post-observation-window events; compared models on **four out-of-time holdouts**.
- **Hidden competition test:** precision **0.80348** at recall ≥ 0.70 (constant baseline: **0.09391**).

[Technical case study and notebook →](https://github.com/Leo-Daiser/avito-bot-detection#english-overview)

### [Riskline — credit-risk ML engineering](https://github.com/Leo-Daiser/Credit-Risk-Scoring-Service)
**Python · scikit-learn · CatBoost · FastAPI · PostgreSQL · Docker**

- Built a local financial-profile demo backed by a dedicated model-training/inference workflow.
- Implemented **Logistic Regression / CatBoost comparison, calibration, acceptance checks, model-readiness checks and explicit fallback behavior**.
- Integrated scoring with an API, PostgreSQL and Docker-based demo; documented automated backend/frontend checks.

[ML approach and system boundaries →](https://github.com/Leo-Daiser/Credit-Risk-Scoring-Service/blob/main/docs/public_profile_model.md)

### [Hybrid Recommendation & Ranking — retrieval and ranking](https://github.com/Leo-Daiser/hybrid-recommendation-ranking-service)
**Python · scikit-learn · CatBoost · FastAPI · PostgreSQL**

- Implemented **two-stage recommendations**: popularity/item-KNN candidate generation followed by Logistic Regression/CatBoost ranking.
- Built temporal splits, offline retrieval/ranking evaluation, and a recommendation API with request/feedback logging.
- **Documented validation Recall@50:** item-KNN **0.1431** vs. popularity **0.0003**; ranking quality is assessed separately on a limited candidate set.

[Architecture and evaluation →](https://github.com/Leo-Daiser/hybrid-recommendation-ranking-service#results-at-a-glance)

## More engineering and research

- **[Credit Risk Research Lab](https://github.com/Leo-Daiser/credit-risk-lab):** separate **synthetic-data** research pipeline for threshold selection, calibration and explainability.
- **[SciKnot / Nornickel AI Science Hack](https://github.com/Leo-Daiser/NorNickel-XAK):** team GraphRAG prototype using Neo4j, hybrid retrieval and evidence-linked answers.
- **Reliable ROM (MSc research, in progress):** reduced-order modeling of dynamical systems with limited/noisy observations.

## Competition results

- **3rd place, NuclearHack 2025** — traffic-load forecasting.
- **Top 5, NuclearHack 2026** — Raman spectra analysis.
- **45th of 180 teams, Nornickel AI Science Hack** — scientific-document GraphRAG.

**Core tools:** Python, SQL, pandas, NumPy, scikit-learn, CatBoost, FastAPI, PostgreSQL, SQLAlchemy, Docker, pytest, Git.  
**Languages:** Russian (native), English (B2).

*Selected work includes personal, academic and competition projects, not employment at the organizations named. Reported metrics come from the projects' documented evaluations.*
