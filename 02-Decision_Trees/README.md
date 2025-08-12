<h1 align="center">🌳 Decision Tree Classifier — Iris Dataset</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=25&duration=4000&pause=1000&color=2E8B57&center=true&vCenter=true&width=800&lines=Interpretable+Machine+Learning;Visualizing+Decision+Paths;High+Accuracy+%7C+Low+Complexity" alt="Typing Animation">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-Decision%20Tree-2E8B57?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Dataset-Iris-4682B4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Python-FFD43B?style=for-the-badge&logo=python&logoColor=black" />
  <img src="https://img.shields.io/badge/Accuracy-97.36%25-darkgreen?style=for-the-badge" />
</p>

---

## 🧠 Overview

This project trains and evaluates a **Decision Tree Classifier** on the **Iris dataset** — a classic dataset for multi-class classification.  
The focus is on **model interpretability** with a **visualized decision path** so every split is human-readable.

---

## 📂 Files Included

| File | Purpose |
|------|---------|
| `Descision_Tree.ipynb` | Model training, evaluation, and visualization notebook |
| `iris.csv` | Dataset file |
| `decision_tree_result.png` | Exported visualization of the trained decision tree |

---

## 📊 Performance Summary

| Metric | Value |
|--------|-------|
| **Accuracy** | **97.36%** |
| **Criterion** | Entropy |
| **Most Important Feature** | Petal Length |
| **Training Time** | < 1 second |

---

## 🌟 Model Visualization

<p align="center">
  <img src="https://raw.githubusercontent.com/ruturaj-018/Machine-learning-blueprints/master/02-Decision_Trees/decision_tree_result.png" 
       alt="Decision Tree Visualization" 
       width="650" 
       style="border-radius: 10px; box-shadow: 0 8px 18px rgba(0,0,0,0.15);" />
  <br>
  <em>📌 Visual representation of decision paths for Iris species classification</em>
</p>

---

## 🔍 Key Insights

- **Petal length** drives the first major split.
- *Setosa* is clearly separable from other species.
- *Versicolor* and *Virginica* differentiation relies on petal width thresholds.
- Decision Trees require **no feature scaling** and are highly explainable.

---

## ⚙️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sklearn,numpy,pandas,matplotlib,jupyter" />
</p>

---

## 🚀 How to Run

```bash
# Clone this repository
git clone https://github.com/ruturaj-018/Machine-learning-blueprints.git

# Navigate to Decision Tree folder
cd Machine-learning-blueprints/02-Decision_Trees

# Open the notebook
jupyter notebook Descision_Tree.ipynb
