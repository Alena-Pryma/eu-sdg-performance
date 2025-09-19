# EU Sustainability Performance Tier Classification

## Project Overview
This project classifies European countries into three sustainability performance tiers based on selected **SDG policy indicators**.  
The goal is to identify **key drivers of sustainable performance** and provide **policy recommendations** for countries to move up tiers.

- **Tier 0 — Needs Improvement**
- **Tier 1 — Good Performers**
- **Tier 2 — Leaders**
The analysis combines **data exploration, machine learning models, and policy insights** to support EU decision-makers.

---
## Data Source
- Dataset: `eu_sdg_performance_data.csv` (pre-prepared subset of Europe SDG Index)  
- Original source: [Europe Sustainable Development Report 2025](https://eu-dashboards.sdgindex.org/)  
- Observations: ~490 (49 countries × 10 years)  
- Features: 15 indicators (economy, innovation, governance, education, environment, social)  
- Target: `performance_tier` (0, 1, 2)

---
## ⚙️ Methods
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
## Key Findings
- **Gradient Boosting** outperformed other models with the highest accuracy.  
- **Digital adoption (sdg9_digital)**, **governance quality (sdg16_cpi, sdg16_rsf)**, and **renewable energy (sdg7_eurenew)** are the strongest predictors.  
- **Tier profiles** show clear patterns: higher income, better governance, and stronger green transition distinguish leaders.  

---
## Structure
## Policy Implications
- **Tier 0 countries** should focus on improving digital infrastructure, governance, and renewable energy deployment.  
- **Tier 1 countries** should accelerate green transition, invest in R&D, and improve tertiary education.  
- **Tier 2 leaders** should maintain strong performance and serve as role models for EU-wide policies.  

---

## Business Impact
This project demonstrates how **AI-driven classification models** can support **evidence-based policymaking** in sustainability.  
It provides a blueprint for monitoring progress towards the **UN Sustainable Development Goals (SDGs)** at the country level.  
