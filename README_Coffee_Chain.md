
# ☕ Coffee Chain Inventory Prediction

This project aims to predict inventory requirements for a fictional U.S.-based coffee shop chain. Using historical sales, product, and marketing data, we develop machine learning models to forecast optimal inventory levels, helping the chain make data-informed supply decisions.

---

## 📂 Dataset Overview

- **Rows**: 1,062 records
- **Columns**: 22 features
- **Target Variable**: `Inventory` (inventory quantity per entry)

### 🔑 Key Features
- `Cogs`, `Sales`, `Profit`, `Marketing`, `Total Expenses`
- `Product`, `Product Type`, `Market`, `Market Size`, `State`
- Target metrics: `Target Profit`, `Target COGS`, `Target Margin`, `Target Sales`

---

## 🧠 Project Objectives

- Understand the drivers of inventory volume
- Identify key predictors through correlation analysis
- Build and evaluate machine learning models to estimate inventory
- Visualize important features that influence inventory decisions

---

## ⚙️ Models Used

| Model              | Purpose       |
|-------------------|----------------|
| Linear Regression | Baseline       |
| Random Forest     | High-accuracy, interpretable |
| XGBoost           | Gradient boosting for better generalization |

---

## 📈 Results Summary

- Features like `Cogs`, `Target COGS`, `Marketing`, and `Total Expenses` are highly correlated with inventory needs.
- Random Forest and XGBoost performed best on test data with R² scores above **0.90**.

---

## 🧪 Tech Stack

- Python, Pandas, NumPy
- Seaborn & Matplotlib for visualization
- Scikit-learn, XGBoost for modeling

---

## 📁 Files Included

- `Coffee_Chain_Inventory_Prediction.ipynb` – Main analysis notebook
- `Coffee_chain.csv` – Dataset used for modeling
- `README.md` – This documentation

---

## 📬 Author

👤 Navjot Singh  
📧 navjot.python@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/navjot-singh-6a1012231)

---

## 📝 Note

- This dataset is simulated and for academic use only.
- Feel free to extend this project by adding forecasting, Tableau dashboards, or demand-based stocking strategies.

---
