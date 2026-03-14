# ML Lab 05 – Supervised Learning

## Aim

The objective of this lab is to implement supervised learning techniques for classification tasks using machine learning algorithms. In this lab, Naïve Bayes and Decision Tree classifiers are developed to analyze and predict outcomes from a dataset. The models are trained and evaluated using performance metrics such as accuracy, confusion matrix, classification report, and precision-recall analysis to understand how well each model performs.

---

## Dataset

### Breast Cancer Wisconsin (Diagnostic) Dataset

**Dataset Link:**  
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

The Breast Cancer Wisconsin (Diagnostic) dataset is a commonly used dataset in machine learning for binary classification problems. It contains measurements derived from digitized images of breast tissue samples. The goal of the dataset is to classify tumors into two categories: **malignant (cancerous)** or **benign (non-cancerous)** based on several numerical features describing the characteristics of cell nuclei.

### Dataset Characteristics

- **Total instances:** 569  
- **Benign cases:** 357  
- **Malignant cases:** 212  
- **Number of features:** 30 numerical attributes  

### Example Features

- Radius  
- Texture  
- Perimeter  
- Area  
- Smoothness  
- Compactness  
- Concavity  
- Symmetry  
- Fractal dimension  

These attributes are computed from cell nuclei images and provide useful information for identifying patterns associated with cancer diagnosis.

---

## Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Experiments

### Experiment 1 – Naïve Bayes Classification

Build a Naïve Bayes classifier using the Breast Cancer dataset to predict class labels.

**Tasks include:**

- Loading the dataset  
- Splitting into training and testing sets  
- Training a Naïve Bayes model  
- Predicting test labels  
- Evaluating performance using accuracy, confusion matrix, classification report, and precision-recall curve  

---

### Experiment 2 – Decision Tree Classification

Build a Decision Tree classifier using the same dataset and evaluate its performance.

**Tasks include:**

- Training a Decision Tree model  
- Predicting class labels  
- Evaluating using accuracy, confusion matrix, classification report, and precision-recall curve  
- Visualizing the decision tree  

---

### Experiment 3 – Model Comparison

Compare the performance of Naïve Bayes and Decision Tree models using visualization techniques.

**Comparison methods include:**

- Bar chart comparing training and testing accuracy  
- ROC curve comparison  
- Confusion matrix heatmap comparison