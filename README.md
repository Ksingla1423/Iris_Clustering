# Clustering Analysis on the Iris Dataset

This repository contains a clustering assignment implemented using Python in Google Colab, focusing solely on the **Iris dataset**. The objective is to explore unsupervised learning techniques like **K-Means** and **Hierarchical Clustering** on one of the most classic datasets in machine learning.

---

## 📁 File

- `Clustering_Assignment.ipynb`: A complete notebook with preprocessing, clustering, and visualization steps for the Iris dataset.

---

## 📊 Dataset Overview

- **Dataset**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Features**:  
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  
- **Target Column**: `species` (removed for unsupervised clustering)

---

## 🧹 Preprocessing

- Loaded data using `pandas`
- Added column headers (since raw Iris data from UCI has none)
- Removed the `species` column
- Applied `StandardScaler` to normalize the features

---

## 🧠 Clustering Techniques Applied

### 🔹 K-Means Clustering
- Used the **Elbow Method** to find optimal number of clusters (k)
- Fitted KMeans and visualized results using 2D PCA-reduced feature space

### 🔹 Hierarchical Clustering
- Generated **dendrogram** to determine appropriate cluster cut
- Applied **Agglomerative Clustering** and compared with KMeans results

---

## 📊 Visualizations

- **Elbow Curve** for optimal k selection
- **2D scatter plots** of clustered data using PCA
- **Dendrogram** for hierarchical clustering interpretation

---

## 🛠 Tools & Libraries

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open `Clustering_Assignment.ipynb` using Jupyter Notebook or Google Colab
3. Run all cells to reproduce the analysis

---
