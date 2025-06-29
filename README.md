**Traditional Statistical Models vs Machine Learning for Gold Price Prediction**

**Comparative study of traditional statistical methods vs machine learning algorithms for forecasting gold prices.**



**Overview**
This repository showcases my comparative study project comparing traditional time series models and machine learning algorithms to predict gold price movements. The project includes:
- Preprocessed financial and macroeconomic data
- Implemented models (ARIMA, LASSO, Random Forest, XGBoost)
- Rolling cross-validation
- Visual and quantitative evaluation

---

**Objectives**
- Predict gold prices using real-world time series data
- Compare performance of traditional statistical vs ML methods
- Identify the best-performing approach based on RMSE, MAE, and residual diagnostics

---

## 🧠 Methods & Models
| Type              | Model       |
|------------------|-------------|
| Statistical       | ARIMA       |
| Regularized ML    | LASSO       |
| Tree-based ML     | Random Forest, XGBoost |

**Repository Structure**

├── thesis/
│   └── gold_price_thesis.pdf
├── data/
│   └── cleaned_data.csv
├── code/
│   ├── 01_data_preprocessing.R
│   ├── …
├── results/
│   ├── plots/
│   └── tables/
├── LICENSE
└── README.md

**Results Summary**
- **XGBoost** achieved the lowest RMSE and best fit to recent price patterns
- **Random Forest** also performed well with minimal tuning
- **ARIMA** showed solid trend tracking but weaker performance during volatility
- **LASSO** helped highlight important predictors and reduce noise

**Sample performance table:**

| Model       | RMSE  | MAE   |
|-------------|-------|-------|
| ARIMA       | 9.63  | 7.22  |
| LASSO       | 8.45  | 6.51  |
| RandomForest| 6.18  | 4.97  |
| XGBoost     | 5.27  | 4.34  |



**Visual Outputs**
Plots, residuals, and performance visuals are stored in:
/results/plots/
/results/tables/
