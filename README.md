# 💼 Salary Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting **salary** based on relevant features using various **machine learning regression algorithms**.  
The objective is to compare multiple models and identify the best-performing one through proper preprocessing, feature scaling, and evaluation.

This project demonstrates a complete **end-to-end ML workflow**, from data cleaning to model analysis.

---

## 📂 Project Structure

---

## 🛠️ Technologies & Libraries Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 📊 Workflow of the Project

### 1️⃣ Data Loading
- Imported the dataset using **Pandas**
- Inspected data types and structure

### 2️⃣ Data Cleaning
- Handled missing values
- Removed inconsistencies
- Processed categorical variables

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualized data using:
  - Histograms
  - Scatter plots
  - Correlation graphs
- Identified relationships between features and salary

### 4️⃣ Feature Engineering & Processing
- Label Encoding for categorical features
- Feature scaling using **StandardScaler**
- Train-test data splitting

---

## 🤖 Machine Learning Models Implemented

### 🔹 Linear Regression
- Baseline regression model

### 🔹 Polynomial Regression
- Tested polynomial degrees: **2, 3, 4, 5**
- Selected the best-performing degree based on evaluation

### 🔹 Lasso Regression
- Tested different values of **alpha**
- Identified the optimal regularization parameter

### 🔹 Ridge Regression
- Applied L2 regularization to reduce overfitting

### 🔹 Random Forest Regressor
- Hyperparameter tuning:
  - `min_samples_split`
  - `random_state`
  - `n_jobs`
- Selected the best Random Forest model

### 🔹 Gradient Boosting Regressor
- Tuned parameters such as:
  - `max_depth`
  - `min_samples_leaf`
  - `min_samples_split`
  - `n_estimators`

---

## 📈 Model Evaluation
- Compared models using performance metrics
- Analyzed bias–variance tradeoff
- Selected the **best-performing model** based on accuracy and generalization

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/salary-prediction-ml.git
