# 🍀 Irish Species Clustering using K-Means and Hierarchical Clustering

This project demonstrates how to apply unsupervised learning algorithms—**K-Means Clustering** and **Hierarchical Clustering** to group Irish species into meaningful categories based on their features.

---

## 🐾 Project Overview

The goal is to explore patterns and natural groupings among various Irish species using clustering techniques. The data is taken from Kaggle

---

## 🔍 Methods

### 1. K-Means Clustering

- Partitions species into `k` clusters by minimizing within-cluster variance
- Requires specifying the number of clusters beforehand
- Uses the Elbow Method or Silhouette Score to choose optimal `k`

### 2. Hierarchical Clustering

- Builds a dendrogram representing nested clusters
- Does not require a pre-specified number of clusters
- Can use different linkage methods: single, complete, average, ward

---

## 🛠️ Tools and Libraries

- Python 
- Pandas, NumPy 
- Scikit-learn for clustering algorithms

