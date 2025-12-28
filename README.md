# FIFA Player Stats – Machine Learning Analysis

## 📌 Project Overview
This project is a comprehensive **Machine Learning assignment** performed on the **FIFA 22 Player Statistics Dataset**.  
The objective is to apply and analyze **Regression, Classification, and Clustering** techniques on a real-world dataset containing both numerical and categorical features.

The entire workflow is implemented in **Python** using a **Jupyter/Colab notebook**.

---

## 📂 Dataset
- **Source:** Kaggle – FIFA Player Stats Database  
- **File Used:** `FIFA22_official_data.csv`
- **Description:**  
  The dataset contains detailed attributes of football players including:
  - Numerical features (e.g., overall rating, potential, age, value, wage)
  - Categorical features (e.g., nationality, club, position)
  - Labels for supervised learning tasks

---

## 🛠️ Technologies & Libraries
- Python  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 🔄 Project Workflow

### 1. Data Downloading
- Dataset downloaded directly from Kaggle
- Unzipped and loaded using Pandas

---

### 2. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling and normalization
- Dimensionality reduction using **PCA (Principal Component Analysis)**

---

## 📈 Regression Analysis
**Objective:**  
Predict a numerical attribute using regression techniques.

**Models Used:**
- Linear Regression

**Experiments:**
- Regression on original dataset
- Regression on PCA-transformed dataset

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- R² Score

---

## 🧠 Classification
**Objective:**  
Classify players using labeled data.

**Models Used:**
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  

**Experiments:**
- Classification on original dataset
- Classification on preprocessed (PCA-applied) dataset

**Evaluation Metrics:**
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🔍 Clustering
**Objective:**  
Discover natural groupings in the data without using labels.

**Algorithm Used:**
- K-Means Clustering

**Approach:**
- Applied clustering on the preprocessed dataset
- Chose optimal number of clusters
- Interpreted clusters quantitatively

---

## 📊 Key Insights
- Preprocessing and PCA significantly affect model performance
- Ensemble models (Random Forest) perform better for classification
- Clustering reveals meaningful player groupings based on attributes

---

## 📁 Repository Structure
