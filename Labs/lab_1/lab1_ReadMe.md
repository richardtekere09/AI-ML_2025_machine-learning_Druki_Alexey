# 🔥 Lab 1 — Apache Spark SQL and Machine Learning

This project demonstrates the use of **Apache Spark** for both **Data Analysis** (using Spark SQL / DataFrame API) and **Machine Learning** (using Spark MLlib) on the Bank Marketing Dataset.

It consists of two main parts:

---

## 📚 Part 1: Data Analysis with Spark SQL

- Loading and exploring the dataset
- Filtering, grouping, and aggregating data
- Calculating new fields (e.g., house age)
- Handling missing data
- Counting distinct records and analyzing group combinations

---

## 📚 Part 2: Machine Learning with Spark MLlib

- Preprocessing categorical and numeric features
- Assembling feature vectors
- Building and tuning classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model evaluation using Accuracy, Precision, Recall, and F1-score
- Analyzing the confusion matrix of predictions

---

## 🗂 Dataset

- File: `bank-additional-full.csv`
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- Target variable: `y` (converted to `label` where `yes` = 1, `no` = 0)

---

## 📊 Example Model Performance (Random Forest Classifier)

| Metric     | Value  |
|------------|--------|
| Accuracy   | 0.911  |
| Precision  | 0.898  |
| Recall     | 0.911  |
| F1-score   | 0.896  |

---

## ⚙️ Requirements

- Python 3.x
- PySpark
- Jupyter Notebook or Google Colab (optional)

Install PySpark using:

```bash
pip install pyspark
