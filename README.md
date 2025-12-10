# 📘 Exam Score Prediction – Data Preprocessing, Exploratory Analysis & Linear Model

This repository contains a Jupyter Notebook dedicated to **data preprocessing**, **exploratory data analysis (EDA)**, and building a **Linear Regression model** for predicting exam scores.  
The notebook prepares the dataset through cleaning, encoding, scaling, and feature transformation before training a linear model.

---

## 🚀 Project Overview

The objective of this project is to prepare a student-performance dataset for predictive modeling of **exam scores**.  
The notebook includes:

- Data loading and inspection  
- Cleaning and preprocessing  
- Exploratory data analysis  
- Ordinal and one-hot encoding of categorical features  
- Scaling numerical features  
- Building complete preprocessing pipelines  
- **Training a Linear Regression model for prediction**

This structure provides a full end-to-end pipeline from raw data to a trained machine-learning model.

---

## 📂 Dataset Information

The notebook uses the dataset:

### **Target Variable**
- `exam_score`

### **Feature Types**

#### 🔹 Numerical Features  
- `age`  
- `study_hours`  
- `class_attendance`  
- `sleep_hours`  

#### 🔸 Ordinal Categorical Features  
- `sleep_quality` → poor < average < good < excellent  
- `facility_rating` → low < medium < high  
- `exam_difficulty` → easy < medium < hard  

#### 🔹 Nominal Categorical Features  
- `gender`  
- `course`  
- `internet_access`  
- `study_method`  

---

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **Pandas** – data manipulation  
- **NumPy**  
- **Matplotlib & Seaborn** – visual analysis  
- **Scikit-Learn**  
  - `OrdinalEncoder`  
  - `OneHotEncoder`  
  - `ColumnTransformer`  
  - `StandardScaler`  
  - `LinearRegression`  
  - `train_test_split`  

---

## 📑 Notebook Workflow Summary

### **1. Data Loading & Inspection**
- Inspect first rows with `.head()`  
- Check dataset structure (`.info()`)  
- Identify missing values & duplicates  
- Basic statistics via `.describe()`  

### **2. Exploratory Data Analysis (EDA)**
- Numerical feature distributions  
- Correlation heatmap  
- Category spread & uniqueness checks  

### **3. Preprocessing & Feature Engineering**
- Split dataset into training and testing sets  
- Apply **Ordinal Encoding** with defined category order  
- Apply **One-Hot Encoding** for nominal features  
- Scale numerical features using **StandardScaler**  
- Integrate transformations using **ColumnTransformer**  
- Build final processed feature matrices  

### **4. Machine Learning Model**
- Train a **Linear Regression model** using processed features  
- Evaluate model performance on test data  
- Analyze prediction behavior  

---

## 📦 Output Artifacts

The notebook produces:

- `X_train_df` — processed training features  
- `X_test_df` — processed testing features  
- Encoded, scaled, and cleaned datasets  
- Reconstructed feature names  
- **Trained Linear Regression model and predictions**  
- Complete preprocessing + modeling pipeline  

---

## ▶️ How to Use

Clone the repository:

```bash
git clone <your-repo-url>
cd <repository-folder>
