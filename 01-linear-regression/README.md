<h1 align="center">📈 Linear Regression – Machine Learning Blueprint</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=26&duration=4000&color=0EA5A2&center=true&vCenter=true&width=850&lines=Predicting+Salaries+Based+on+Experience;End-to-End+Implementation+in+Python;Data+Analysis+%2B+Model+Training+%2B+Visualization;Part+of+Machine+Learning+Blueprints+Series" alt="Typing Animation">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-Linear%20Regression-blue?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Notebook-Jupyter-orange?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/github/last-commit/ruturaj-018/machine-learning-blueprints?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>

---

## 📌 Overview

This blueprint demonstrates **Simple Linear Regression** to predict **Salary** based on **Years of Experience**.

✔ **Key Highlights**
- 📊 Exploratory Data Analysis  
- 🏗 Feature Preparation  
- 🤖 Model Training with `scikit-learn`  
- 📈 Evaluation & Visualization

📁 **Notebook:** [`linrear_regression.ipynb`](./linrear_regression.ipynb)  
📁 **Dataset:** [`salary_data.csv`](./salary_data.csv)

---

## 📊 Model Performance

- **Metric Used:** R² Score  
- **Result:** *Replace with your R² score from notebook output*

**Prediction vs Actual Plot:**  
<p align="center">
  <img src="https://raw.githubusercontent.com/ruturaj-018/machine-learning-blueprints/master/01-linear-regression/linear_regression_result.png" width="750" alt="Prediction vs Actual Plot">
</p>

---

## 🛠 Steps in the Notebook

1️⃣ Load and explore the dataset  
2️⃣ Separate features (`X`) and target (`y`)  
3️⃣ Split into training and testing sets  
4️⃣ Train a Linear Regression model  
5️⃣ Predict salaries on test data  
6️⃣ Plot regression line over actual data  

---

## ⚙️ Tools & Libraries
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sklearn,numpy,pandas,matplotlib,jupyter" />
</p>

---

## 🚀 Quick Example

```python
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score
import pandas as pd

# Load data
df = pd.read_csv("salary_data.csv")
X = df[['YearsExperience']]
y = df['Salary']

# Split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Train
model = LinearRegression()
model.fit(X_train, y_train)

# Evaluate
y_pred = model.predict(X_test)
print("R² Score:", r2_score(y_test, y_pred))
