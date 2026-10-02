# PRODIGY_ML_02 – Customer Segmentation with K-means

Task 2 of my Machine Learning internship at **Prodigy InfoTech**.

## Objective
Group retail store customers based on their purchase history using **K-means clustering**.

## Dataset
[Mall Customer Segmentation (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) – 200 customers

## Steps
1. Data exploration and visualization
2. Choice of K with the Elbow method and Silhouette score → **K = 5** (silhouette = 0.554)
3. K-means clustering on Annual Income & Spending Score
4. Cluster profiling and business interpretation

## Segments
| Segment | Income | Spending | Customers |
|---|---|---|---|
| VIP | High | High | 39 |
| Potential | High | Low | 35 |
| Standard | Medium | Medium | 81 |
| Young spenders | Low | High | 22 |
| Careful | Low | Low | 23 |

## Tools
Python, Pandas, Matplotlib, Scikit-learn
