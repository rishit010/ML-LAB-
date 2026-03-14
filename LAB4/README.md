# Lab 04 – Regression Models

## Aim

The objective of this lab is to understand and implement regression techniques for predictive modeling. In this lab, Linear Regression and Logistic Regression models are developed using Python libraries to analyze relationships between variables and make predictions. The exercises involve exploring datasets, visualizing patterns in data, training regression models, and assessing their performance using suitable evaluation metrics.

---

## Datasets Used

### 1. TV Marketing Dataset

**Dataset Link:**  
https://github.com/Yashappin/Machine-Learning/blob/master/TvMarketing.csv

This dataset contains information about advertising expenditure on television and the resulting sales figures. It is commonly used to demonstrate the concept of **Simple Linear Regression**, where sales are predicted based on the amount spent on TV advertising.

**Main Features**

- **TV** – Advertising budget allocated for TV marketing  
- **Sales** – Total product sales generated  

---

### 2. CO2 Emission of Cars Dataset

**Dataset Link:**  
https://www.kaggle.com/datasets/midhundasl/co2-emission-of-cars-dataset

This dataset includes details about vehicle specifications along with their carbon dioxide emissions. It is used to build a **Multiple Linear Regression** model to estimate CO2 emissions using characteristics such as engine size and vehicle weight.

**Important Features**

- **Volume** – Engine capacity  
- **Weight** – Total weight of the vehicle  
- **CO2** – Carbon dioxide emission value  

---

### 3. Advertisement Click Dataset

**Dataset Link:**  
https://www.kaggle.com/datasets/gabrielsantello/advertisement-click-on-ad

This dataset contains information related to user activity and interaction with online advertisements. It is used to build a **Logistic Regression** model that predicts whether a user is likely to click on an advertisement based on behavioral and demographic attributes.

**Typical Features**

- Daily Time Spent on Site  
- Age  
- Area Income  
- Daily Internet Usage  
- Ad Topic Line  
- City  
- Gender  
- Country  
- Timestamp  
- Clicked on Ad (Target Variable)

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

### Experiment 1 – Simple Linear Regression

Build a linear regression model to predict Sales using TV advertising budget.

**Steps include:**

- Importing dataset  
- Data visualization  
- Train-test split (80:20)  
- Training regression model  
- Visualizing best-fit line  
- Evaluating model using RMSE and R²  

---

### Experiment 2 – Multiple Linear Regression

Build a multiple regression model to predict CO2 emissions using Volume and Weight.

**Steps include:**

- Data exploration  
- Correlation analysis and heatmap  
- Outlier detection using boxplots  
- Training regression model  
- Visualizing predictions  
- Evaluating model using MAE, MSE, and RMSE  

---

### Experiment 3 – Logistic Regression

Build a logistic regression model to predict whether a user will click on an advertisement.

**Steps include:**

- Exploratory Data Analysis  
- Handling missing values and preprocessing  
- Correlation analysis  
- Training logistic regression model  
- K-Fold cross validation  
- Evaluating model using classification report  
- Confusion matrix and ROC curve
