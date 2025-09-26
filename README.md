# EU Sustainability Performance Tier Classification

## Key files
- `data/eu_sdg_performance_data.csv` — dataset (pre-prepared subset of Europe SDG Index). Original source: [Europe Sustainable Development Report 2025](https://eu-dashboards.sdgindex.org/)
- `notebooks/sdg_performance_analysis.ipynb` — main Jupyter Notebook with EDA, modeling and conclusions
- `policy_analysis/use_case.rtf` — policy recommendations on how to choose paths to improve countries' levels based on the analysis conducted
- `reports/` - graphs and charts
- `use_case_documentation/Screenshots_documentation.pdf` - screenshots of the completed use case template on the platform [appliedAI Institute’s Use Case Platform](https://ucp.appliedai-institute.de/en)
- `README.md` — project description

## Project Overview
This project classifies European countries into three sustainability performance tiers based on selected **SDG policy indicators**.
The goal is to identify **key drivers of sustainable performance** and provide **policy recommendations** for countries to move up tiers.
- **Tier 0 — Needs Improvement**
- **Tier 1 — Good Performers**
- **Tier 2 — Leaders**
The analysis combines **data exploration, machine learning models, and policy insights** to support EU decision-makers.

---
## Methods
1. **Data Exploration**
   - Understanding the three performance tiers
   - Feature analysis (income, digitalization, governance, inequality, etc.)
   - Tier-level averages and comparisons

2. **Model Training & Evaluation**
   - Logistic Regression
   - Random Forest
   - Gradient Boosting (best performance: ~98% accuracy)

3. **Feature Importance Analysis**
   - Identified top drivers: digital adoption, governance (CPI), renewable energy, education

4. **Policy Insights**
   - Profiles for each tier
   - Roadmap for advancing from Tier 0 → 1 → 2

---
## Summary of results
- **Gradient Boosting** outperformed other models with the highest accuracy.
- **Digital adoption (sdg9_digital)**, **governance quality (sdg16_cpi, sdg16_rsf)**, and **renewable energy (sdg7_eurenew)** are the strongest predictors.
- **Tier profiles** show clear patterns: higher income, better governance, and stronger green transition distinguish leaders.

---
## Policy Implications
- **Tier 0 countries** should focus on improving digital infrastructure, governance, and renewable energy deployment.
- **Tier 1 countries** should accelerate green transition, invest in R&D, and improve tertiary education.
- **Tier 2 leaders** should maintain strong performance and serve as role models for EU-wide policies.

---
## Business Impact
This project demonstrates how **AI-driven classification models** can support **evidence-based policymaking** in sustainability.
It provides a blueprint for monitoring progress towards the **at the country level**.

## Contact
Olena Pryma — markova.prima@gmail.com
