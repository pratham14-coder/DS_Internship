# 🛡️ Insurance Claim Prediction

Predicting whether a customer is likely to file an insurance claim using machine learning models.  
This project was completed as part of the **Data Science Internship at Rubixe™**.

---

## 📌 Problem Statement

Insurance companies face financial risks when policyholders make claims. The goal of this project is to build a **binary classification model** that predicts whether a customer is likely to make an insurance claim based on various features such as age, vehicle details, driving experience, and prior history.

---

## 🧰 Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git

---

## 📊 Dataset Overview

The dataset includes various customer attributes such as:

- Age  
- Gender  
- Driving Experience  
- Vehicle Ownership & Type  
- Accident History  
- Annual Premium  
- Previous Insurance Records

🎯 **Target Variable:** `Claim`  
(1 = Customer filed a claim, 0 = Did not file a claim)

---

## 🧪 Project Workflow

### 🔹 1. Data Preprocessing
- Handled missing values
- Converted categorical data using Label Encoding
- Scaled numerical features for uniformity

### 🔹 2. Exploratory Data Analysis (EDA)
- Visualized class imbalance
- Analyzed feature correlations
- Plotted distributions, boxplots, and countplots

### 🔹 3. Model Development
- Logistic Regression (Baseline)
- Random Forest Classifier
- XGBoost Classifier (Best Performance)
- Hyperparameter tuning using GridSearchCV

### 🔹 4. Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

### 🔹 5. Business Insights
- Identified key risk factors
- Suggested potential segmentation strategies for policyholders

---

## 📈 Results

| Model                | Accuracy | F1 Score | AUC Score |
|----------------------|----------|----------|-----------|
| Logistic Regression  | 0.79     | 0.74     | 0.81      |
| Random Forest        | 0.85     | 0.82     | 0.89      |
| 🌟 **XGBoost**       | **0.87** | **0.84** | **0.91**  |

✅ **Best Performing Model:** XGBoost Classifier

