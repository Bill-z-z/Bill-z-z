<img width="1856" height="576" alt="Tianyang (Bill) Zhang - Data Science and Data Engineering" src="https://github.com/user-attachments/assets/efbe0674-0f34-4189-bf0d-f109c7113e40" />


### Data Scientist & Data Engineer — M.S. Applied Data Science, University of Chicago | Ex-Data Scientist Intern at Thermo Fisher Scientific, InnovaAI and MinMetals Futures

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tianyang--zhang3-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tianyang-zhang3/)
![UChicago](https://img.shields.io/badge/M.S.%20Applied%20Data%20Science-University%20of%20Chicago-800000?style=for-the-badge)
![Location](https://img.shields.io/badge/Chicago%2C%20IL-424242?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to](https://img.shields.io/badge/Open%20to%20Summer%202027%20internships-2EA043?style=for-the-badge)

I build models that people make decisions with, and the data platforms underneath them: demand forecasts that drive replenishment, churn models that shape retention, and experiments that decide what ships.

**Three data science internships so far.** At **Thermo Fisher Scientific** I built SKU-level demand forecasting models for pharmaceutical products and analyzed pricing and portfolio performance for Sanofi's medicines and vaccines. At **InnovaAI Tech** in San Francisco I built a churn prediction pipeline and a customer segmentation framework whose insights contributed to a 15% reduction in churn. At **MinMetals Futures** I forecast commodity futures prices with backtesting that prevents look-ahead bias. I'm now in the **University of Chicago's M.S. in Applied Data Science**, building cloud data platforms on GCP, Snowflake and Databricks.

---

## Value delivered

**15% lower churn, 15% higher conversion.** Turned an end-to-end churn model (85% accuracy identifying at-risk customers) and a K-Means + PCA segmentation into targeted retention strategies at InnovaAI Tech.

**+12% signup conversion.** Designed A/B tests across 120K+ sessions with power analysis and SRM checks; the winning CTA variant lifted signups 12%, and segmenting by device showed mobile users converting 2.5x higher on shorter forms.

**40% faster experiment decisions.** Built an automated Python/SQL pipeline combining Frequentist and Bayesian inference, plus a self-serve Tableau go/no-go dashboard.

**SKU-level demand forecasts → replenishment.** Forecasting models with seasonality and promotions at Thermo Fisher, turned into replenishment recommendations and dashboards for supply chain teams.

**Leak-free market forecasting.** Time-aware backtesting comparing ARIMA, regression, Random Forest and gradient boosting across market regimes at MinMetals Futures.

**ViT accuracy 83.15% → 87.95%.** Diffusion-generated (DiT-XL/2) training images for wildlife monitoring, in a Carnegie Mellon research program with Prof. David Woodruff.

---

## How I work

| Data science | Data engineering |
| --- | --- |
| Forecasting with seasonality, promotions and lagged signals | Cloud SQL (MySQL 8.0) on GCP, loaded and queried from Python |
| Classification, segmentation (K-Means, PCA), A/B testing, Bayesian inference | Snowflake: hand-written DDL, row-count reconciliation, star schemas |
| Time-aware validation: no look-ahead bias, no leakage | Type 2 slowly changing dimensions loaded idempotently with MERGE |
| Results people act on: replenishment plans, retention strategy, go/no-go | MCP server + Streamlit so non-SQL users can ask the warehouse questions |

---

## Stack

**Languages & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1B3A5C?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**Data platforms & cloud**

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Analytics & apps**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Selected work

**Cloud data warehouse: GCP Cloud SQL → Snowflake (UChicago, 2026)**: stood up MySQL 8.0 on Cloud SQL, migrated the 16-table Sakila schema to Snowflake, remodeled it into a star schema with Type 2 SCDs, and am building an MCP server and Streamlit app that answer plain-English questions over it.

**National Park demand signals lakehouse (UChicago team of 4, in progress)**: tests whether Recreation.gov reservations (9.78M FY2024 bookings) and GDELT news coverage (~9 TB) anticipate visits to five national parks. I own the Snowflake star schema, the dashboard and the held-out evaluation.

**Experimentation & conversion optimization platform**: A/B testing, Bayesian and Frequentist inference, FDR-corrected segmentation and a self-serve Tableau dashboard.

**[bee-diffusion-zy](https://github.com/Bill-z-z/bee-diffusion-zy)** · **[DIT_XL-2_my-path-ty](https://github.com/Bill-z-z/DIT_XL-2_my-path-ty)**: diffusion-model and Diffusion Transformer (DiT-XL/2) image generation projects in PyTorch.

**[vit-selector_zh](https://github.com/Bill-z-z/vit-selector_zh)** · **[convnext-selector-win-zh](https://github.com/Bill-z-z/convnext-selector-win-zh)** · **[efficientnet_ty](https://github.com/Bill-z-z/efficientnet_ty)**: image selection and classification with ViT, ConvNeXt and EfficientNet.

---

## Research

**Carnegie Mellon University, Research Program on Algorithms for Big Data** (PI: Prof. David Woodruff): *Data Complement: Utilizing Realistic Wildlife Images Generated by Different Models as Training Data to Enhance the Performance of ViT and ConvNeXt Models for Wildlife Monitoring.*

**Washington University in St. Louis, Research Program on Institutional Framework for Markets** (PI: Prof. John N. Drobak): *Research on Monopoly's Variable Effect on Digital Market in China — Take Xiaomi as an Example*, 2021 International Conference on Economic Management and Cultural Industry.

---

## Education

**M.S., Applied Data Science, University of Chicago** (Sep 2026 – Dec 2027, expected)

**B.S., Business Analytics; B.A., Econometrics and Quantitative Economics, University of Rochester** (2022 – 2025)

---

Open to **Summer 2027 data science, data engineering and product analytics internships**, and full-time roles from January 2028. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/tianyang-zhang3/).
