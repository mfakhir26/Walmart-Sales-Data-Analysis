# Walmart Sales Forecasting

This project focuses on building a predictive model to forecast **weekly department-level sales** across 45 Walmart stores using historical data, promotional markdowns, and economic indicators. It combines **data cleaning**, **feature engineering**, **statistical analysis**, and **machine learning modeling** to accurately estimate future sales.

---

## Dataset

The dataset comes from a Kaggle competition and includes:

* **train.csv** – historical sales data (store, department, date, sales, holiday flag)
* **features.csv** – additional data like fuel price, temperature, CPI, and markdowns
* **stores.csv** – store-level metadata (type and size)
* **test.csv** – unseen data for which weekly sales predictions are made

---

## Project Objective

To predict weekly sales at the department level for each Walmart store, while understanding and modeling the impact of holidays and markdown promotions on sales. The ultimate goal is to provide an accurate forecast model that helps Walmart optimize inventory, staffing, and promotions—especially during high-impact holiday periods.

---

## Models Used

* **Linear Regression**: Used as a baseline model
* **Random Forest Regressor**: Final model with improved performance and non-linear capabilities
* Evaluation metrics: R² score, MAE, MSE

---

## 📈 Key Results

* **Linear Regression**:

  * R² Score: 0.974
  * MAE: \~14,560
  * MSE: 473169494
* **Random Forest**:

  * R² Score: 0.974
  * MAE: \~1,445
  * MSE : 13446201.3

  Random Forest model was considered best because it's MAE is less than MAE produced by linear regression model and also linear regression model failed to capture non-linear patterns but Random Forest Regressor model did excellent job and provided accurate and reliable results.
---

## Final Deliverables

* Cleaned and merged dataset
* Feature importance analysis
* Final predictions for `test.csv`
* Well-documented Jupyter Notebooks

---

## 🧪 Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, scipy)
* Jupyter Notebook

---

All of the datasets are given and all of the jupyter notebooks are also provided to check the code and report of analysis has also been provided.

---
