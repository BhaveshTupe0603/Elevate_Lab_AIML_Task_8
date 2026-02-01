# 🌳 Task 8: Decision Tree Classification

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit_Learn-orange?logo=scikit-learn)

## 📖 Overview
**Task 8** focuses on **Interpretable Machine Learning**. We used a Decision Tree to predict bank term deposit subscriptions. Unlike "black box" models, this approach allows us to visualize the exact rules used for prediction.

## ⚙️ Workflow
1.  **Preprocessing:** One-Hot Encoded categorical variables (Jobs, Marital Status).
2.  **Modeling:** Trained `DecisionTreeClassifier`.
3.  **Tuning:** Limited `max_depth=3` to prevent overfitting and ensure the tree remains readable.
4.  **Visualization:** Used `plot_tree` to render the decision logic.

## 📊 Key Findings
* **Accuracy:** Achieved ~91% accuracy on the test set.
* **Top Predictor:** `nr_employed` (Number of employees - an economic indicator) and `duration` (Call duration) were the most critical features.

## 🖼️ Deliverables
<img width="1570" height="812" alt="image" src="https://github.com/user-attachments/assets/f1280806-624d-49be-8876-5ee38342a17b" />

## 📂 Files
* [📓 Jupyter Notebook](./Task_8.ipynb)
