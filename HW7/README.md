# HW7 — Binary Classification Methods

**Goal:** Compare classical binary classifiers on a medical diagnosis task.

- **Breast-cancer diagnosis:** a linear-regression baseline, SVM, kernel SVM, KNN, decision tree and random forest, tuned with grid search and compared on F1 and accuracy. The SVM performs best (**cross-validated F1 ≈ 0.98**, test accuracy 0.97).
- Regularization techniques for reducing overfitting.
- **Bonus – diabetes detection:** reach F1 > 0.9 on a held-out 20% test set. After handling invalid values, random forest reaches **test F1 0.92** (XGBoost 0.89).

Notebooks: [`HW7_Binary_Classification.ipynb`](HW7_Binary_Classification.ipynb) · [`HW7_Bonus_Diabetes.ipynb`](HW7_Bonus_Diabetes.ipynb)
