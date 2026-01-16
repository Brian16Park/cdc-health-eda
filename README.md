# 📊 Diabetes Prevalence Analysis (CDC Health Indicators)
### By Brian Park

## 🔍 Overview
This project explores the relationship between diabetes prevalence and key demographic, behavioral, and socioeconomic factors using a large population-based health survey dataset.
"Diabetes Health Indicators Dataset" - https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## ❓ Research Questions
- Does body mass index (BMI) differ between individuals with and without diabetes?
- Is physical activity associated with diabetes status?
- Does diabetes prevalence vary across age groups?
- Is income level associated with diabetes prevalence?

## 🧪 Methods
- Data Source: CDC Behavioral Risk Factor Surveillance System
- Statistical Tests:
  - Mann-Whitney U test
  - Chi-square tests of independence
- Effect Sizes:
  - Rank-biserial correlation
  - Cramer's V

## 📈 Key Findings
- BMI showed a moderate association with diabetes status.
- Age and income exhibited small-to-moderate associations.
- Physical activity showed a smaller but statistically significant association.

## ⚠️ Limitations
- Observational, cross-sectional data
- Self-reported measures
- No causal conclusions

## 🛠️ Tools & Technologies
- Python (pandas, numpy, scipy)
- Matplotlib & seaborn
- Jupyter Notebook
- Git & GitHub

## ▶️ How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Launch Jupyter Notebook
4. Open eda_statistical_analysis.ipynb and run cells sequentially
