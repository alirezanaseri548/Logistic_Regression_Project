# Logistic_Regression_Project
ML
# **Logistic Regression Project**
**Predicting Purchase Decisions Based on Age and Estimated Salary**

---

## **📌 Overview**
This project implements a **Logistic Regression** model to predict whether a user will purchase a product based on their **age** and **estimated salary**. The dataset used is `Social_Network_Ads.csv`, which contains user demographics and purchase history.

---

## **📁 Dataset**
- **Source**: `Social_Network_Ads.csv`
- **Features**:
  - `Age` (Numerical)
  - `EstimatedSalary` (Numerical)
- **Target Variable**: `Purchased` (Binary: `0` = No, `1` = Yes)

---

## **🔧 Tools & Libraries**
- **Python 3.x**
- **Pandas** (Data manipulation)
- **NumPy** (Numerical operations)
- **Scikit-learn** (Machine learning)
- **Matplotlib** (Data visualization)

---

## **🛠️ Workflow**

### **1. Data Loading & Preprocessing**
- Load the dataset using `pandas`.
- Select relevant features (`Age` and `EstimatedSalary`).
- Split the dataset into **training (75%)** and **testing (25%)** sets.

### **2. Feature Scaling**
- Standardize features using `StandardScaler` to ensure equal contribution.

### **3. Model Training**
- Train a **Logistic Regression** model on the training data.

### **4. Prediction & Evaluation**
- Predict purchase decisions for new data points.
- Evaluate model performance using:
  - **Confusion Matrix**
  - **Accuracy Score**

### **5. Visualization**
- Plot the decision boundary to visualize model predictions.

---

## **📊 Results**
### **Sample Prediction**
```python
Prediction for Age 30, Salary 87000 (0=No, 1=Yes):
[0]
