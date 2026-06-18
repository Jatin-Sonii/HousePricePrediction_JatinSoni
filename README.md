# Housing Price Prediction & Model Evaluation

## Project Overview
This project implements an end-to-end machine learning pipeline to analyze and predict housing prices. It covers data preprocessing, exploratory data analysis, and a comparative performance evaluation between two distinct algorithms: **Linear Regression** and **Random Forest Regressor**.

---

## Key Pipeline Steps

* **Task 1 & 2 — Data Cleaning & Feature Engineering:** Handled categorical attributes (e.g., `mainroad`, `airconditioning`, `furnishingstatus`) using One-Hot Encoding, converting textual classifications into optimized numerical integers.
* **Task 3 — Model Building:** Trained both a baseline Linear Regression model and an advanced Random Forest Regressor using an 80/20 train-test split.
* **Task 4 — Data Visualization:** Generated a target price distribution histogram, a feature correlation matrix heatmap, and a comprehensive model prediction overlay graph.
* **Task 5 — Evaluation & Insights:** Computed statistical validation metrics (MAE, RMSE, and $R^2$ Score) to identify feature importance and compare model accuracy.

---

## Evaluation Summary

The project utilizes a house-by-house comparison data structure and tracking graphs to measure predictions against actual market values. The data demonstrates that structural capacity (**Area** and **Bathrooms**) paired with premium staging (**Air Conditioning**) serve as the strongest statistical drivers of market value. 

While both models successfully trace standard valuation benchmarks, the **Random Forest Regressor** provides superior adaptation when managing high-end volatile luxury properties.

---

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
