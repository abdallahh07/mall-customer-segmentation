# Mall Customer Segmentation

A hands-on K-Means clustering exercise — my first time building a clustering model, using the classic Mall Customers dataset to practice unsupervised learning.

## What this is

Segmenting mall customers by **Annual Income** and **Spending Score** to identify distinct customer groups a marketing team could target differently — high income/high spenders, low income/high spenders, and so on.

This is a learning/practice project, not a production deliverable — no deployment, no API, just the core clustering workflow done properly.

## Approach

1. Selected `Annual Income` and `Spending Score` as clustering features
2. Scaled features with `StandardScaler` (distance-based algorithms are scale-sensitive)
3. Used the elbow method to choose the number of clusters (`k`)
4. Fit K-Means and visualized the resulting customer segments

## Dataset

[Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) — 200 customers, 5 columns (ID, gender, age, annual income, spending score).

## Tech

Python, pandas, scikit-learn (KMeans, StandardScaler), matplotlib
