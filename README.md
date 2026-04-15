# 🧹 Data Preprocessing and Feature Engineering in Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Preprocessing-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## ⭐ Highlights

* End-to-end data preprocessing pipeline
* Applied scaling, encoding, and transformation techniques
* Performed feature engineering and outlier detection
* Identified important features using statistical methods

---

## 📌 Project Overview

This project demonstrates a complete **data preprocessing and feature engineering pipeline** on the Adult Income dataset.

The goal is to transform raw data into a **clean, structured, and model-ready format** by applying industry-standard techniques.

---

## 📝 Problem Statement

The objective is to preprocess and engineer features for the **Adult Income Dataset**, which predicts whether an individual's income exceeds $50K per year.

The project focuses on applying:

* Data cleaning
* Feature transformation
* Feature selection techniques

to improve machine learning model performance.

---

## 🎯 Objectives

* Handle missing values effectively
* Apply feature scaling techniques
* Encode categorical variables
* Perform feature engineering
* Detect outliers
* Identify important features

---

## 📊 Dataset

* Adult Census Income Dataset
* Contains demographic and income-related attributes

---

## ⚙️ Methodology

### 🔹 1. Data Preprocessing

* Missing values handled using:

  * Median imputation (numerical features)
  * Mode imputation (categorical features)

---

### 🔹 2. Feature Scaling

* **Standard Scaling**

  * Mean = 0, Std = 1
  * Preferred for normally distributed data

* **Min-Max Scaling**

  * Scales data to [0,1] range
  * Sensitive to outliers

---

### 🔹 3. Encoding Techniques

* **One-Hot Encoding**

  * Used for low-cardinality categorical variables
  * Avoids ordinal relationships

* **Label Encoding**

  * Used for high-cardinality features
  * Memory efficient but introduces order

---

### 🔹 4. Data Exploration

* Summary statistics
* Missing value analysis
* Data type inspection

---

### 🔹 5. Feature Engineering

* Created new features:

  * Age Groups (Young, Adult, Middle-aged, Senior)
  * Work Hours Categories

📊 *Rationale:*
Captures non-linear relationships and improves interpretability.

---

### 🔹 6. Feature Transformation

* Applied **log transformation** on `capital_gain`

📊 *Why?*

* Reduces skewness
* Stabilizes variance
* Improves model performance

---

### 🔹 7. Outlier Detection

* Used **Isolation Forest** to detect anomalies

---

### 🔹 8. Feature Selection

* Applied **Mutual Information** to identify important features

---

## 📈 Key Insights

* Proper preprocessing significantly improves model readiness
* Scaling techniques impact algorithm performance
* Encoding method depends on feature cardinality
* Feature engineering reveals hidden patterns in data

---

## 💡 Key Learnings

* Importance of preprocessing in ML pipelines
* Differences between scaling techniques
* Handling categorical variables effectively
* Detecting and managing outliers
* Improving data quality for better predictions

---

## 📊 Business Impact

* Improves model accuracy and reliability
* Reduces noise and inconsistencies in data
* Enables better decision-making using clean data

---

## 🚀 How to Run

```bash
git clone https://github.com/MeghanaCVarghese/Data-Preprocessing-and-Feature-Engineering.git
cd Data-Preprocessing-and-Feature-Engineering
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook notebooks/preprocessing_feature_engineering.ipynb
```

---

## 📁 Project Structure

```
Data-Preprocessing-and-Feature-Engineering/
│
├── data/
│   └── adult_dataset.csv
│
├── notebooks/
│   └── preprocessing_feature_engineering.ipynb
│
├── README.md
├── requirements.txt
```

---

## 👩‍💻 Author

**Meghana C Varghese**
