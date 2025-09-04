<h1 align="center">🧮 k-Nearest Neighbors (KNN) – Iris Dataset</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=25&color=F97316&center=true&vCenter=true&width=800&lines=From+Scratch+Implementation;Hyperparameter+Tuning;98.33%25+Accuracy;Part+of+Machine+Learning+Blueprints" alt="Typing Animation">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-KNN-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Dataset-Iris-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge">
  <img src="https://img.shields.io/github/last-commit/ruturaj-018/machine-learning-blueprints?color=red&style=for-the-badge">
</p>

---

## 📂 Dataset Overview

We used the classic **Iris dataset** from the **UCI Machine Learning Repository**.

📌 **Key Details:**
- **150 samples**
- **4 features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **3 classes**:
  - 🌸 *Setosa*
  - 🌿 *Versicolor*
  - 🌺 *Virginica*

📁 **Dataset file:** [`iris.csv`](./iris.csv)

---

## ⚡ Algorithm Summary

- **Type:** Supervised Learning (Classification)
- **Nature:** Lazy Learning, Non-Parametric
- **Concept:** Assigns class labels based on the **majority vote** of the `k` nearest neighbors.
- **Distance Metric:** Euclidean Distance
- **Best k Found:** **k = 3** (achieved the highest accuracy of 98.33%)

💡 The algorithm was implemented **from scratch** — no ready-made classification functions from libraries like `scikit-learn` for training.

---

## 🔍 Working Steps

1️⃣ Load training & testing data.  
2️⃣ Choose `k` (number of neighbors).  
3️⃣ Calculate **Euclidean distance** for each test point against all training points.  
4️⃣ Sort and pick the top `k` nearest points.  
5️⃣ Assign the class based on majority voting.  

---

## 📊 Model Performance

<p align="center">
  <img src="knn_confusion_matrix.png" width="550" alt="Confusion Matrix">
</p>

**Classification Report**

| Class      | Precision | Recall | F1-score | Support |
|------------|-----------|--------|----------|---------|
| 🌸 Setosa     | 1.00      | 1.00   | 1.00     | 19      |
| 🌿 Versicolor | 0.94      | 1.00   | 0.97     | 17      |
| 🌺 Virginica  | 1.00      | 0.96   | 0.98     | 24      |

✅ **Accuracy Achieved:** **`98.33%`**

---

## 🛠️ Tools & Libraries Used
- **Python**
- `NumPy`
- `Pandas`
- `Matplotlib`
- `scikit-learn` (for evaluation metrics only)

---

## 🚀 Example Prediction

```python
result = classifier.predict([[3, 5, 0.6, 0.6]])
print(iris.target_names[result])
