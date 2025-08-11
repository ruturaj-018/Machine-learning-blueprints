<h1 align="center">🌳 Decision Tree Classifier – Iris Dataset</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-Decision%20Tree-2E8B57?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Dataset-Iris-4682B4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Python-FFD43B?style=for-the-badge&logo=python&logoColor=black" />
  <img src="https://img.shields.io/badge/Accuracy-97.36%25-darkgreen?style=for-the-badge" />
</p>

---

## 🧠 Overview

This implementation uses a **Decision Tree Classifier** trained on the **Iris dataset** to predict the species of iris flowers (*Setosa*, *Versicolor*, *Virginica*).  
The model is designed for **interpretability** — visualizing the exact decision paths taken for classification.

---

## 📂 Files Included

| File | Purpose |
|------|---------|
| `Descision_Tree.ipynb` | Full model training, evaluation, and visualization |
| `iris.csv` | Dataset file |
| `decision_tree_result.png` | Decision tree diagram of the trained model |

---

## 📊 Performance Summary

| Metric | Value |
|--------|-------|
| **Accuracy** | **97.36%** |
| **Criterion** | Entropy |
| **Most Important Feature** | Petal Length |
| **Training Time** | < 1 second |

---

## 🌟 Visualization

<p align="center">
  <img src="decision_tree_result.png" width="600" alt="Decision Tree Visualization">
  <br>
  <em>Visual representation of decision paths for classifying Iris species</em>
</p>

---

## 🔍 Key Insights

- **Petal length** is the most influential splitting feature.
- *Setosa* is distinctly separable at the first split.
- *Versicolor* and *Virginica* require finer splits based on petal width.
- Decision trees require **no feature scaling** and are inherently interpretable.

---

## ⚙️ Tech Stack

- **Python** – Core programming language
- **scikit-learn** – Model building & evaluation
- **Matplotlib** – Visualization
- **Pandas / NumPy** – Data handling

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/ruturaj-018/machine-learning-blueprints.git

# Navigate to the Decision Tree project folder
cd Decision_Trees

# Open the notebook
jupyter notebook Descision_Tree.ipynb
