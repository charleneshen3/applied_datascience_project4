# Applied Data Science Project 4: End-to-End Machine Learning

This project analyzes whether daily stock direction can be predicted for four large-cap technology stocks: **AAPL, NFLX, MSFT, and AMZN**. The workflow uses Yahoo Finance data, technical-indicator feature engineering, unsupervised PCA/k-means clustering, and supervised ML models.

The main supervised models are:

- Logistic Regression
- Random Forest
- XGBoost

The project also includes additional model evaluation analysis, a survival analysis extension, and an interactive Shiny app for exploring the results.

---

## Project Structure

```text
applied_datascience_project4/
│
├── README.md
│
├── Analysis/
│   ├── step1_analysis.R
│   ├── summary_of_results.ipynb
│   ├── survival_analysis_extension.ipynb
│   │
│   ├── all_metrics.rds
│   ├── all_cm_data.rds
│   ├── all_roc_data.rds
│   ├── all_imp_rf.rds
│   ├── all_imp_xgb.rds
│   ├── all_pca_km.rds
│   └── stocks.rds
│
├── Data/
│   ├── stock_original_data.xlsx
│   └── stock_processed_data.xlsx
│
└── ShinyApp/
    └── step2_shinyapp.R
```

---

## Team Members

- Nikhil Shanbhag (nvs2128)
- Charlene Shen (xs2546)
- Shreya Amalapurapu (sa4342)
- Yifan Wang (yw4663)

---
