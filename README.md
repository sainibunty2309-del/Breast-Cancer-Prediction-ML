# 🩺 Breast Cancer Prediction using Machine Learning

## 📌 Project Overview

This project uses Machine Learning techniques to predict whether a breast tumor is **Benign (B)** or **Malignant (M)** based on various medical features. The goal is to build an accurate classification model that can assist in early breast cancer detection.

---

## 📂 Dataset

* **Dataset:** Breast Cancer Wisconsin Dataset
* **Target Column:** `diagnosis`

  * `B` → Benign (Non-Cancerous)
  * `M` → Malignant (Cancerous)

---

## 🔍 Project Workflow

### 1. Data Collection & Exploration

* Loaded the dataset using Pandas
* Inspected dataset shape, columns, and data types
* Checked statistical summary using `describe()`
* Verified missing values and duplicate records

### 2. Data Preprocessing

* Removed unnecessary columns (`id`, `Unnamed: 32`)
* Encoded the target variable (`B` → 0, `M` → 1)
* Checked class distribution
* Applied train-test split
* Performed feature scaling where required

### 3. Exploratory Data Analysis (EDA)

* Data distribution analysis
* Count plot of diagnosis classes
* Correlation heatmap
* Pair plot
* Box plots
* Histogram
* Scatter plot
* Bar plot

### 4. Machine Learning Models

The following classification algorithms were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest

### 5. Model Evaluation

The models were evaluated using:

* Accuracy Score
* F1 Score
* Classification Report
* Confusion Matrix

---

## 🏆 Best Model

**Random Forest Classifier** achieved the best overall performance on this dataset.

**Model Accuracy:** **`98.25'**

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Pickle


## 🚀 Future Improvements

* Hyperparameter tuning
* Cross-validation
* ROC-AUC analysis
* Feature importance visualization
* Deployment using Flask, FastAPI, or Streamlit

---

## 📊 Conclusion

This project demonstrates an end-to-end machine learning pipeline for breast cancer classification, including data preprocessing, exploratory data analysis, visualization, feature scaling, model training, and evaluation. Among the tested algorithms, the Random Forest model delivered the best predictive performance and can effectively classify tumors as Benign or Malignant based on the available features.

## Author 
  ** Bunty saini **