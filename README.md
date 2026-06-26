#  Forest Cover Type Classification using Decision Trees

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![License](https://img.shields.io/badge/License-MIT-green)

##  Overview

This project explores Decision Tree classifiers for predicting forest cover types using cartographic variables from the Forest Cover Type dataset.

The notebook demonstrates the complete machine learning workflow from data exploration to hyperparameter tuning and model comparison.

---

##  Objectives

- Explore the Forest Cover Type dataset
- Train a baseline Decision Tree
- Analyze overfitting
- Tune hyperparameters using GridSearchCV
- Interpret feature importance
- Compare Decision Trees with Random Forests

---

##  Results

| Model | Validation Accuracy |
|--------|--------------------:|
| Decision Tree | **79.03%** |
| Tuned Decision Tree | **78.27%** |
| Random Forest | **85.88%** |

Random Forest significantly outperformed a single Decision Tree, demonstrating the effectiveness of ensemble learning.

---

##  Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

##  Concepts Covered

- Decision Trees
- Gini Impurity
- Entropy
- Overfitting
- Tree Pruning
- Cross Validation
- GridSearchCV
- Feature Importance
- Random Forests

---

##  Repository Structure

```
forest-cover-type-decision-tree/
│
├── README.md
├── requirements.txt
├── forest_cover_decision_tree.ipynb
└── images/
```

---

##  Future Improvements

- Random Forest optimization
- Extra Trees
- AdaBoost
- Gradient Boosting
- XGBoost comparison

---

##  Acknowledgements

Dataset:
Forest Cover Type Prediction (Kaggle)

Inspired by Chapter 6 of *Hands-On Machine Learning* by Aurélien Géron.
