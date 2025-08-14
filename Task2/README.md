Loan Risk Prediction – Task 2
📌 Overview
This project predicts whether a loan applicant is risky or safe based on their personal, financial, and employment details.
It uses a machine learning model trained on a labeled dataset (Risk_Flag) and can predict the risk for new applicants.

📂 Project Structure
bash
Copy
Edit
task2/
│
├── loan_prediction.ipynb   # Jupyter Notebook with full code
├── dataset.csv              # Loan dataset used for training
├── model.pkl                # Saved trained model
├── label_encoders.pkl       # Saved label encoders for categorical variables
└── README.md                # Project documentation
🛠️ Technologies Used
Python 3

Pandas – Data manipulation
Scikit-learn – Machine learning model & preprocessing
Jupyter Notebook – Development environment
Pickle – Model persistence
📊 Dataset Information
The dataset contains:
Income – Annual income of the applicant
Age – Applicant's age
Experience – Years of professional experience
Married/Single – Marital status
House_Ownership – Own, Rent, or Mortgage
Car_Ownership – Owns a car or not
Profession – Job title
CITY – Applicant’s city
STATE – Applicant’s state
CURRENT_JOB_YRS – Years in current job
CURRENT_HOUSE_YRS – Years in current residence
Risk_Flag – Target variable (1 = Risky, 0 = Safe)
📌 How It Works
Data Preprocessing – Categorical values are converted to numbers using Label Encoding.
Model Training – A machine learning model (e.g., Random Forest) is trained on historical data.
Prediction – The trained model predicts risk for new applicants.
Restriction – For categorical fields, users must choose from available dataset values.
Output – 1 means Risky, 0 means Safe.

