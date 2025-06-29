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

## 🤖 Models Used

* 🔹 **Linear Regression**: Used as a baseline model
* 🔹 **Random Forest Regressor**: Final model with improved performance and non-linear capabilities
* 🔹 Evaluation metrics: R² score, MAE, MSE

---

## 📈 Key Results

* **Linear Regression**:

  * R² Score: 0.974
  * MAE: \~14,560
* **Random Forest**:

  * 

---

## 📂 Final Deliverables

* Cleaned and merged dataset
* Feature importance analysis
* Residual plots for model diagnostics
* Final predictions for `test.csv`
* Well-documented Jupyter Notebooks

---

## 🧪 Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
* Jupyter Notebook
* Git & GitHub

---

## 🚀 How to Run

1. Clone the repo
2. Install dependencies
3. Run `main.ipynb` or `modeling.ipynb` to reproduce the analysis
4. Use `submission.csv` for final predictions

---

## 📜 License

This project is for educational and research purposes only. Data provided by Walmart via Kaggle.

---

Let me know if you’d like to include a **demo image**, **badges**, or **link to your notebook**, and I’ll help you enhance it further!
