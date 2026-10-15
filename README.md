# Nikita Ivanisev

**MSc student in Applied Mathematics and Computer Science, MEPhI (2026–2028).**  
I work on applied machine learning and Python systems, with an emphasis on reproducible evaluation, data quality, and reliable inference.

**Seeking:** Machine Learning / Data Science internships and entry-level ML engineering roles in Europe.

[LinkedIn](https://www.linkedin.com/in/nikita-ivanisev) · [Email](mailto:nikitosivanisev317@gmail.com)

## Selected ML projects

| Project | What I did | Verifiable evidence |
| --- | --- | --- |
| **[Avito Bot Detection](https://github.com/Leo-Daiser/avito-bot-detection)** | Built 105 behavioral features and a five-model CatBoost ensemble; removed post-window events and evaluated on four out-of-time holdouts | **0.80348 precision at recall ≥ 0.70** on the competition's hidden test (constant baseline **0.09391**); offline submission, not Avito employment |
| **[Riskline — Credit Risk ML](https://github.com/Leo-Daiser/Credit-Risk-Scoring-Service)** | Built a local financial-profile ML demo with Logistic Regression/CatBoost comparison, calibration, validation gates, API inference, model readiness/fallback logic, PostgreSQL and Docker | End-to-end local demo and documented training/inference workflows; **not** a banking underwriting or deployed approval system |
| **[Hybrid Recommendation & Ranking](https://github.com/Leo-Daiser/hybrid-recommendation-ranking-service)** | Implemented MovieLens candidate retrieval (popularity and item-KNN), a Logistic Regression/CatBoost ranking stage, temporal evaluation and FastAPI serving | Retrieval Recall@50: **0.1431** (item-KNN) vs **0.0003** (popularity) on the documented validation split; ranking results are limited by the small candidate-positive set |

## Other work

- **[Credit Risk Research Lab](https://github.com/Leo-Daiser/credit-risk-lab):** Separate synthetic-data ML experiment framework with preprocessing, calibration, explainability and four threshold-selection methods. Not integrated into Riskline.
- **[SciKnot / Nornickel AI Science Hack](https://github.com/Leo-Daiser/NorNickel-XAK):** Team-built scientific-document GraphRAG prototype with source tracking, Neo4j and hybrid retrieval.
- **Reliable ROM (MSc research, in progress):** Numerical work on reliable reduced-order models of parameterized dynamical systems under limited/noisy observations. No publication claimed.

## Competition results

- **3rd place, NuclearHack 2025** — traffic-load forecasting.
- **Top 5, NuclearHack 2026** — Raman spectra analysis.
- **45th / 180 teams, Nornickel AI Science Hack** — scientific information extraction and GraphRAG.

## Skills

**ML / data:** Python, pandas, NumPy, scikit-learn, CatBoost, SQL; temporal validation, imbalanced classification, retrieval and ranking.  
**Software engineering:** FastAPI, PostgreSQL, SQLAlchemy, Docker, pytest, Git, REST APIs.  
**Languages:** Russian (native), English (B2).

*Projects are academic, personal or competition work; affiliation with an organization named in a competition is not claimed. Performance metrics are reproduced from each project's documented evaluation, not independently re-benchmarked here.*
