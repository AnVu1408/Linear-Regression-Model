# 📊 Linear Regression Model in Python

This project provides a simple interactive linear regression tool built in a Jupyter Notebook. It works with any `.csv` file and lets you choose independent (`X`) and dependent (`Y`) variables for single-variable linear regression. 
This model also help you predict the value of dependent variable base on independent variable.

p/s: for everyone who is struggling with statistic class like me =))

---

## 📁 Files

- `main.ipynb` — main notebook with the full model, data preview, training, and prediction tools.
- `.csv` files — sample datasets:
  - `advertising.csv`
  - `housing.csv`

---

## 🚀 Features

- 📂 Load any `.csv` file interactively
- 👀 Preview the dataset
- ✅ Choose `X` and `Y` columns for regression
- 📉 Fit a scikit-learn `LinearRegression` model
- 🔮 Predict:
  - `Y` from a given `X`
- 📊 Optional plot of data and regression line

---

## 🛠 Requirements

- Python 3.10+
- Jupyter Notebook
- `pandas`
- `matplotlib`
- `scikit-learn`

Install requirements (if not already):

```bash
pip install pandas scikit-learn matplotlib
