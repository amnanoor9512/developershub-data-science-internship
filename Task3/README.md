# 🏦 Customer Churn Prediction – Task 3

## 📌 Overview
This project predicts whether a bank customer is likely to **churn** (leave the bank) based on their demographics, account information, and banking activity.  
Using historical customer data, a **machine learning classification model** is trained to identify at-risk customers so the bank can take preventive actions.

---


---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – Machine learning models & preprocessing
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced plotting
- **Pickle** – Saving model & encoders
- **Jupyter Notebook** – Development environment

---

## 📊 Dataset Information
**Dataset Name:** Churn Modelling Dataset  

| Column Name         | Description |
|--------------------|-------------|
| `RowNumber`        | Row index (not useful for prediction) |
| `CustomerId`       | Unique ID for each customer |
| `Surname`          | Customer's surname |
| `CreditScore`      | Credit score |
| `Geography`        | Country (France, Spain, Germany) |
| `Gender`           | Male / Female |
| `Age`              | Customer's age |
| `Tenure`           | Number of years with the bank |
| `Balance`          | Account balance |
| `NumOfProducts`    | Number of products held with the bank |
| `HasCrCard`        | Has a credit card (1 = Yes, 0 = No) |
| `IsActiveMember`   | Active membership status (1 = Yes, 0 = No) |
| `EstimatedSalary`  | Estimated salary |
| `Exited`           | **Target variable** – 1 = Churned, 0 = Stayed |

---

## 📌 How It Works
1. **Data Cleaning**
   - Remove unnecessary columns (`RowNumber`, `CustomerId`, `Surname`).
   - Handle missing values (if any).

2. **Encoding Categorical Variables**
   - Convert `Geography` & `Gender` into numerical values using **Label Encoding** or **One-Hot Encoding**.

3. **Model Training**
   - Split dataset into training and testing sets.
   - Train a classification model (e.g., **Random Forest Classifier**).

4. **Feature Importance Analysis**
   - Identify which features have the most influence on customer churn.

5. **Prediction**
   - Use the trained model to predict churn for new customers.

---
