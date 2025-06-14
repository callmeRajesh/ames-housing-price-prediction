# Ames Housing Price Prediction 🏠

This project is part of my learning journey in machine learning. It focuses on predicting house prices using a Decision Tree Regressor with the **Ames Housing dataset**.

## 📘 Project Overview

- Predict the `SalePrice` of homes in Ames, Iowa.
- Use a **Decision Tree Regression** model.
- Compare performance with different tree depths (`max_depth=3` and `max_depth=10`).
- Evaluate using **RMSE** and **R² score**.
- Visualize the decision trees to understand feature splits.

## 🔧 Tools Used

- Python 🐍
- pandas, numpy, matplotlib
- scikit-learn (DecisionTreeRegressor, train_test_split, metrics)

## 📊 Results

| Max Depth | RMSE        | R² Score |
|-----------|-------------|----------|
| 3         | ~44,034     | 0.758    |
| 10        | ~33,218     | 0.862    |

The deeper tree (depth=10) performed significantly better in explaining the variance in house prices.

## 🧠 What I Learned

- Handling missing values in real-world datasets
- Label encoding categorical features
- Using Decision Tree Regressor for prediction
- Model evaluation using RMSE and R²
- Importance of tuning `max_depth` for tree models

## 📁 Files Included

- `AmesHousing_DecisionTree.ipynb`: Jupyter Notebook with full code and explanation.
- `README.md`: This file.

---

This is a self-learning project as I transition into the field of machine learning. Feedback and collaboration are welcome!
