# Machine Learning Project for Tip data

---

## 📌 Overview

Tip prediction using machine learning classification models, preprocessing, model tuning, and evaluation.

---

## 📊 about Dataset 

* Number of Columns : 7
* Number of Rows : 244
* Number of Duplicates : 1
* Number of Nan Values : 0
* Columns : [total_bill, tip, sex, smoker, day, time, size]
* Columns That Don`t Matter : None
* Target : tip
* Regression Problem

---

## 🧠 Models
Models Used :

* XGBoost 
* LightGBM
* Kneighbors

---

## ⚙️ Preprocessing

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Scaling
* Missing Value Imputation
* Hyperparameter Tuning
* Model Evaluation
* Evaluation Metrics

---

## 🛠️ Technologies

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* LightGBM
* Joblib

---

## 📊 Model Evaluation
- The model Evaluated by mean_absolute_error, mean_squared_error, r2, root_mean_squared_error

---

## 📈 Results


| Model | MAE | MSE | R2 | RMSE | 
| :--- | ---: | ---: | ---: | ---: | ---: |
| KNeighbors | 0.801290 | 1.394831 | 0.427521 | 1.181030 | 
| XGBoost | 0.755477 | 1.045346 | 0.570960 | 1.022421 | 
| LightGBM | 0.792142 | 1.476054 | 0.394185 | 1.214930 | 

---

## 📂 Project Structure

```text
.
├── data/
├── images/
├── models/
├── .gitignore
├── Tip.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Install requirements :
```text

pip install -r requirements.txt

```
then run ipynb file
