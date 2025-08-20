# Wholesale Customers Clustering

This project applies multiple clustering algorithms on the **Wholesale Customers Dataset** to explore customer segmentation with unsupervised learning.

## 📊 Dataset
The dataset contains annual spending in different product categories by wholesale distributor customers.

Columns include:
- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

## 🔧 Workflow

### 1. Load & Explore
- Import dataset, inspect shape, head, and summary statistics.
- Plot feature distributions.

### 2. Preprocessing
- Apply log-transform to reduce skewness.
- Scale features using **StandardScaler**.

### 3. Clustering Methods
- **K-Means** → find optimal k with the Elbow method.
- **Hierarchical Clustering** → dendrograms with Ward linkage.
- **DBSCAN** → density-based clustering.
- **MeanShift** → centroid-based clustering.

### 4. Evaluation
- **Silhouette Score**
- **Davies–Bouldin Index**
- **Calinski–Harabasz Index**

### 5. Visualization
- **PCA** (2D) plots for dimensionality reduction.
- **t-SNE** for non-linear visualization of cluster separation.

## 📈 Results
- All clustering methods are compared using evaluation metrics.
- Visualizations highlight how clusters are separated.

## 🚀 How to Run
```bash
pip install -r requirements.txt
python clustering_wholesale.py
