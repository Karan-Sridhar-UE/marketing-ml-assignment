# Predicting Marketing Campaign Revenue using Supervised Learning

**Student:** Karan Sridhar  
**Matriculation Number:** 54842784  
**Class:** MSc Data Science 120B  
**Dataset:** [Marketing and Product Performance Dataset](https://www.kaggle.com/datasets/imranalishahh/marketing-and-product-performance-dataset)

---

## Project Overview

This project applies supervised learning to predict **Revenue_Generated** from marketing campaign and product performance data. The dataset contains 10,000 rows and 17 columns covering campaign metrics, customer behavior, subscription details, and product sales.

The task is **regression** — predicting the continuous revenue value generated per campaign record.

---

## Dataset

| Property | Value |
|---|---|
| Source | Kaggle — imranalishahh |
| Rows | 10,000 |
| Columns | 17 |
| Target Variable | `Revenue_Generated` |
| Task Type | Regression |

**Key columns:** Clicks, Conversions, Revenue_Generated, ROI, Subscription_Tier, Subscription_Length, Discount_Level, Units_Sold, Bundle_Price, Customer_Satisfaction_Post_Refund, Common_Keywords, and more.

---

## Repository Structure

```
ML assignment new/
├── RQ1_Baseline_Performance.ipynb       # Baseline models: Linear Reg, Decision Tree, k-NN
├── RQ2_Model_Comparison.ipynb           # Advanced models: Random Forest, XGBoost, SVR
├── RQ3_Preprocessing_Effect.ipynb       # Impact of preprocessing strategies
├── RQ4_Feature_Importance.ipynb         # Feature importance + SHAP analysis
├── RQ5_Metric_Sensitivity.ipynb         # Model rankings across different metrics
├── RQ6_Robustness.ipynb                 # Cross-validation and noise/missingness tests
├── RQ7_Practical_Recommendation.ipynb  # Final decision matrix and recommendation
├── README.md
└── requirements.txt
```

Each notebook is **self-contained** — it reads the raw dataset and outputs figures (PDF) and tables (CSV) independently.

---

## Research Questions

| # | Research Question | Output |
|---|---|---|
| RQ1 | How effectively do baseline models predict revenue? | Table I + Figure 1 |
| RQ2 | Which model achieves the best predictive performance? | Table II + Figure 2 |
| RQ3 | How does preprocessing affect model performance? | Table III + Figure 3 |
| RQ4 | Which features contribute most to revenue prediction? | Table IV + Figure 4 |
| RQ5 | How do model rankings change across evaluation metrics? | Table V + Figure 5 |
| RQ6 | How robust is the best model under different conditions? | Table VI + Figure 6 |
| RQ7 | What is the final practical recommendation? | Table VII + Figure 7 |

---

## Models Used

- Linear Regression
- Decision Tree
- k-Nearest Neighbors (k-NN)
- Random Forest
- XGBoost
- Support Vector Regression (SVR)

## Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (Coefficient of Determination)

---

## Expected Outputs

Each notebook saves its results automatically:

- `figures/` — Publication-ready figures saved as PDF
- `tables/` — Result tables saved as CSV
