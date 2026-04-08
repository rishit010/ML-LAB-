# ML Lab 08 – K-Means Clustering

## Aim
The aim of this lab is to implement **unsupervised learning techniques**, specifically **K-Means Clustering and Hierarchical (Agglomerative) Clustering**, and analyze clustering performance through visualization and comparison.

---

## Dataset

### Iris Dataset

Dataset Link:  
https://archive.ics.uci.edu/dataset/53/iris

The **Iris dataset** is a well-known dataset used for clustering and classification tasks. It contains measurements of iris flowers from three different species.

### Dataset Features
- sepal length
- sepal width
- petal length
- petal width

Target classes (not used in clustering):
- setosa
- versicolor
- virginica

Total samples: 150  
Number of features: 4  

This dataset is ideal for clustering as it contains naturally separable groups.

---

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Experiments

### Experiment 1 – K-Means Clustering
Apply K-Means clustering on the Iris dataset after performing feature scaling.  
Analyze clustering performance and visualize the formed clusters.

---

### Experiment 2 – Hierarchical Clustering
Perform Agglomerative (Hierarchical) clustering and analyze cluster formation using a dendrogram.

---

## Result Analysis
- Apply both K-Means and Agglomerative Clustering
- Visualize clusters side-by-side
- Compare performance of both methods
- Repeat clustering for k = 2, 3, 4 and analyze differences