# 🎯 Customer Segmentation Using K-Means

This project applies **K-Means Clustering** to a mall customer dataset to segment customers based on **age, annual income, and spending score**, with the goal of enabling targeted marketing strategies.

---

## 📁 Project Structure

📦 root/
├── data/
│ ├── Mall_Customers.csv # Original dataset
│ └── mall_customers_with_clusters.csv # Data with cluster labels
├── images/
│ ├── elbow_curve.png # Elbow method graph
│ ├── silhouette_curve.png # Silhouette score graph
│ └── 3d_cluster_plot.html # Interactive 3D cluster plot
├── customer_seg.ipynb # Final notebook
├── Untitled.ipynb # (Temporary/extra notebook)
└── README.md # This file


---

## 🔧 Tools Used

- **Python**
  - pandas, numpy, matplotlib, seaborn
  - sklearn (KMeans, StandardScaler, silhouette_score)
  - plotly (for 3D plotting)
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📊 Key Results

| Cluster | Avg Age | Income (k$) | Spending Score | Strategy |
|--------:|--------:|------------:|----------------:|----------|
| 0       | 55.3    | 47.6        | 41.7            | Personalized offers for older shoppers |
| 1       | 32.9    | 86.1        | 81.5            | High-value customers – upsell premium |
| 2       | 25.8    | 26.1        | 74.8            | Price-sensitive youth – run promotions |
| 3       | 26.7    | 54.3        | 40.9            | Mid-income – cross-sell opportunity |
| 4       | 44.4    | 89.8        | 18.5            | High income, low spenders – trigger interest |

✔ Also includes cluster-wise gender distribution and behavioral profiling.

---

## 📈 Visualizations

- 📊 `elbow_curve.png` – Elbow method to choose optimal clusters
- 📉 `silhouette_curve.png` – Cluster quality visualization
- 🌐 `3d_cluster_plot.html` – Interactive 3D plot in `images/` folder

