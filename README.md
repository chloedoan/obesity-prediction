# COMP2200 Portfolio Part 4 – Obesity Prediction via Clustering and Regression

### 📌 Project Overview
This project explores obesity prediction using unsupervised and supervised learning techniques. The aim is to identify clusters (groups) of individuals based on lifestyle and biometric attributes and assess how these clusters relate to weight gain and potential obesity risk. Regression models are then applied within the identified groups to analyze predictors of obesity.

The dataset contains various health, diet, and activity-related variables from multiple individuals. These variables are used for clustering analysis and later for predictive modeling, targeting the individual's weight in kilograms (`Weightd`) as a proxy for obesity risk.

---

### 🧾 Table of Contents
- Data CLeaning and Preprocessing
- Clustering Analysis
- Predictive Modeling
- Results Visualization
- Usage
- Contact

---

### 🧹 Data Cleaning and Preprocessing
- Checked for missing values and handled them via imputation or removal.
- Normalized continuous variables for fair clustering results.
- Categorical variables were encoded using appropriate methods.
- Outliers were addressed to improve model performance and interpretability.

---

### 🔍 Clustering Analysis
- Performed **K-Means clustering** to segment the population into distinct lifestyle or biometric groups.
- Evaluated optimal number of clusters using the **Elbow Method** and **Silhouette Score**.
- Interpreted each cluster by analyzing variable distributions and lifestyle patterns.

---

### 🔢 Predictive Modeling
Within each cluster:
- Built **Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Recursive Feature Elimination (RFE)** models to predict obesity (proxied by high weight values).
- Compared model performance using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
- Identified significant features that influence weight gain per group (e.g., activity level, diet habits).

---

### 📊 Results Visualization
- Used `matplotlib` and `seaborn` to create visual summaries:
  - Cluster distributions
  - Feature importance
  - Model predictions vs. actual outcomes
- Included annotated graphs for clarity.

---

### ▶️ Usage

Run the notebook step-by-step to:
- Preprocess the data  
- Perform clustering  
- Train and evaluate predictive models  
- Visualize the results  

**Prediction Target:**  
`Weightd` – used to infer potential obesity status

**Key Techniques:**  
- KMeans clustering  
- Logistic Regression  
- KNN classification  
- Recursive Feature Elimination (RFE)

---

### 📬 Contact

**Author:** Chloe Doan  
**Email:** lqchloe.doan@gmail.com 
**Portfolio Repository:** [GitHub Link](https://github.com/chloedoan/obesity-prediction)
