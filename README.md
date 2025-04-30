# 🕵️ Crime Data Analysis (US)

This project presents a detailed analysis of crime data across the United States using Python. It involves clustering, dimensionality reduction, classification modeling, and insightful visualizations to explore patterns and predict violent crime occurrences.

---

## 📌 Objectives

- Understand and explore key crime patterns across US counties.
- Apply dimensionality reduction using PCA for improved efficiency.
- Implement both clustering and classification algorithms.
- Evaluate the performance of multiple machine learning models.
- Visualize patterns, correlations, and trends in the dataset.

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Modeling: `scikit-learn`, `xgboost`
  - Clustering: `KMeans`, `GaussianMixture`
  - Dimensionality Reduction: `PCA`

---

## 📊 Exploratory Data Analysis

- Crime rates by region and population demographics.
- Heatmaps, correlation matrices, bar plots, and scatter plots.
- Linear regression analysis between `countyCode` and `ViolentCrimesPerPop`.

---

## 🧠 Machine Learning Models

### ✅ Clustering and Dimensionality Reduction

- **K-Means Clustering**  
  Used to group data into clusters based on similarity.

- **Gaussian Mixture Model (GMM)**  
  Probabilistic clustering for overlapping groups.

- **Principal Component Analysis (PCA)**  
  Applied on age group features:  
  `'agePct12t21', 'agePct12t29', 'agePct16t24', 'agePct65up'`  
  Reduces dimensions while preserving variance.

### ✅ Classification Models and Accuracy

| Model                    | Accuracy (%)         |
|-------------------------|----------------------|
| Logistic Regression      | 80.00                |
| Decision Tree Classifier | 85.56                |
| Random Forest Classifier | 86.46                |
| Support Vector Machine   | 81.20                |
| K-Nearest Neighbors (KNN)| 78.70                |

All models were evaluated using `accuracy_score` and `confusion_matrix`. Random Forest performed the best, followed by Decision Tree and SVM.

---

## 🖼️ Visualizations

KMeans Clustering :
![image](https://github.com/user-attachments/assets/81b913d7-6591-4c44-9b1d-3298b9812181)

GMM Clustering : 
![image](https://github.com/user-attachments/assets/d1d5ea29-4278-4128-885c-f71ea832e4bd)

Linear Regression :
![image](https://github.com/user-attachments/assets/0d25a16d-3034-446b-b5e3-287d3ae1c29a)


---
