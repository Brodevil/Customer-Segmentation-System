# Customer Segmentation System

---

## Project Title:

**Customer Segmentation System: An End-to-End Unsupervised Machine Learning Pipeline with Web App Deployment**\
**This project implements an end-to-end unsupervised machine learning system to segment customers based on behavioral and demographic data. It showcases multiple clustering algorithms, dimensionality reduction techniques, and an interactive Streamlit app for dynamic cluster analysis — all containerized and ready for cloud deployment.**

---

## 📊 Dataset:
* **Source**: [Kaggle – Mall Customer Segmentation Dataset](https://www.kaggle.com/datasets/brodevil/customers)
* **Features**:

  * `CustomerID`
  * `Gender`
  * `Age`
  * `Annual Income`
  * `Spending Score`
  
---

## Key Steps:

### 1. 🔍 Exploratory Data Analysis (EDA)

* Histograms, pairplots, violin plots (age, income, gender)
* Correlation matrix to identify informative features

---

### 2. 🧼 Preprocessing

* One-hot encoding for `Gender`
* Standardization of numerical features
* Dimensionality reduction with **PCA** or **t-SNE** for visualization

---

### 3. 🧠 Unsupervised Model Comparison

| Algorithm                                   | Use Case                                    |
| ------------------------------------------- | ------------------------------------------- |
| **K-Means**                                 | Baseline hard clustering                    |
| **Hierarchical Clustering (Agglomerative)** | Tree-based segmentation                     |
| **DBSCAN**                                  | Density-based detection (good for outliers) |
| **Gaussian Mixture Models (GMM)**           | Probabilistic clustering                    |
| (Optional) **Autoencoders**                 | Deep clustering for nonlinear patterns      |

---

### 4. 📈 Evaluation Metrics

* Silhouette Score
* Davies–Bouldin Index
* Calinski–Harabasz Score
* Elbow method & Dendrogram for cluster tuning

---

### 5. 📊 Visualization

* 2D PCA/t-SNE cluster plots
* Interactive **Streamlit UI** with cluster count selector and segment interpretation

---

### 6. Required Modules


---
