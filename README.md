# 🛍️ K-Means Clustering – Mall Customer Segmentation

This repository contains my solution for **Task 8: Clustering with K-Means** using the popular Mall Customers Dataset.

---

## 🎯 Objective

- Apply **unsupervised learning** to group customers based on their shopping behavior.
- Use **K-Means** clustering and evaluate with **Elbow Method** and **Silhouette Score**.

---

## 🧰 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## ✅ What I Did

1. Loaded the **Mall Customer dataset**.
2. Selected relevant features: Age, Annual Income, Spending Score.
3. Standardized data and reduced to 2D using **PCA**.
4. Applied **Elbow Method** to determine best `k` (clusters).
5. Trained **K-Means** and evaluated with **Silhouette Score**.
6. Visualized clusters in 2D.

---

## 📊 Results

- **Optimal Clusters (K):** 5  
- **Silhouette Score:** ~[Your Score Here]  
- Clearly distinguishable clusters were formed representing customer segments.

---

## 🧠 What I Learned

- How to apply K-Means clustering.
- How to evaluate unsupervised models (Silhouette Score, Inertia).
- Visualizing clusters using PCA.
- Importance of scaling before clustering.

---

## 📁 Files

- `task8_kmeans_clustering.ipynb`
- `Mall_Customers.csv` (Dataset)
- `README.md`

---

## 📦 Dataset

- **Mall Customers Dataset**  
- Source: [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python) or UCI

---

Happy Clustering! 🎯
