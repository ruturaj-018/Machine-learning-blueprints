<h1 align="center">🧮 k-Nearest Neighbors (KNN) – Iris Dataset</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=25&color=4F46E5&center=true&vCenter=true&width=650&lines=KNN+Classifier+Implementation+from+Scratch;Using+the+Iris+Dataset;Accuracy+Achieved:+98.33%25" alt="Typing Animation">
</p>

---

## 📂 Dataset Used

We used the **Iris dataset** from the UCI Machine Learning Repository.

It contains:
- **150 samples**
- **4 features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **3 target classes**:
  - *Setosa*
  - *Versicolor*
  - *Virginica*

📁 **Dataset file:** [`iris.csv`](./iris.csv)

---

## ⚡ How the Algorithm Works

- **Type:** Supervised Learning (Classification)
- **Approach:** Lazy Learning, Non-Parametric
- **Core Idea:** Assigns a class based on the **majority vote** of the `k` closest neighbors.
- **Distance Metric Used:** Euclidean Distance
- **Best k Value Found:** *<your_best_k_here>*

---

## 📊 Model Performance

<p align="center">
  <img src="knn_confusion_matrix.png" width="500" alt="Confusion Matrix">
</p>

**Confusion Matrix**  
| Class      | Precision | Recall | F1-score | Support |
|------------|-----------|--------|----------|---------|
| Setosa     | 1.00      | 1.00   | 1.00     | 19      |
| Versicolor | 0.94      | 1.00   | 0.97     | 17      |
| Virginica  | 1.00      | 0.96   | 0.98     | 24      |

**Accuracy Achieved:** `98.33%`

---

## 🔧 Tools & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn (for evaluation metrics only)

---

## 🚀 Output Example

```python
result = classifier.predict([[3, 5, 0.6, 0.6]])
print(iris.target_names[result])
