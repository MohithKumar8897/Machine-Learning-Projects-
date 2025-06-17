# 🏦 Loan Approval Prediction Using Python

## 📋 Overview

This project involves building a classification model to predict loan approval outcomes based on an applicant's profile. Using a dataset containing features such as income, education, employment status, credit history, and property area, the model helps financial institutions automate and optimize their loan approval process.

The pipeline includes data preprocessing, visualization, exploratory data analysis (EDA), machine learning model training, and evaluation.

---

## 🗃️ Dataset Description

| Column              | Description                                                     |
|---------------------|-----------------------------------------------------------------|
| `Loan_ID`           | Unique identifier for each loan record                          |
| `Gender`            | Applicant's gender (Male/Female)                                |
| `Married`           | Marital status (Yes/No)                                         |
| `Dependents`        | Number of dependents (e.g., 0, 1, 2, 3+)                        |
| `Education`         | Education level (Graduate/Not Graduate)                         |
| `Self_Employed`     | Employment type (Yes/No)                                        |
| `ApplicantIncome`   | Primary applicant’s monthly income                              |
| `CoapplicantIncome` | Co-applicant’s monthly income                                   |
| `LoanAmount`        | Loan amount in thousands (e.g., 128 = ₹128,000)                 |
| `Loan_Amount_Term`  | Loan term in months (e.g., 360)                                 |
| `Credit_History`    | Credit score status (1 = good credit, 0 = poor credit)          |
| `Property_Area`     | Property location (Urban, Semiurban, Rural)                     |
| `Loan_Status`       | Loan approval status (Y = Approved, N = Rejected)               |

---

## 📊 Visualizations

Visual exploratory analysis was conducted and saved as `.png` images for better interpretability:

| Feature                              | Visualization |
|--------------------------------------|---------------|
| Applicant Income Distribution        | ![Applicant Income](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Applicant%20Income%20Distribution.png) |
| Education Distribution               | ![Education](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Education%20Distribution.png) |
| Gender Distribution                  | ![Gender](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Gender%20Distribution.png) |
| Marital Status Distribution          | ![Marital Status](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Marital%20Status%20Distribution.png) |
| Self-Employment Distribution         | ![Self Employment](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Self-Employment%20Distribution.png) |
| Loan Approval Status                 | ![Loan Approval](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Loan%20Approval%20Status.png) |
| Loan Status vs Applicant Income      | ![Loan vs Income](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Loan_Status%20vs%20ApplicantIncome.png) |
| Loan Status vs Coapplicant Income    | ![Loan vs Coapplicant](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Loan_Status%20vs%20CoapplicantIncome.png) |
| Loan Status vs Credit History        | ![Loan vs Credit](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Loan_Status%20vs%20Credit_His.png) |
| Loan Status vs Loan Amount           | ![Loan vs Amount](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Loan_Status%20vs%20LoanAmount.png) |
| Loan Status vs Property Area         | ![Loan vs Property](https://github.com/MohithKumar8897/Machine-Learning-Projects-/raw/main/Loan%20Approval%20Prediction%20using%20Python/Loan_Status%20vs%20Property_Area.png) |

---

## 🔍 Exploratory Data Analysis (EDA)

- Frequency distributions for categorical features (Gender, Education, Marital Status, etc.)
- Income and loan amount distributions
- Loan status versus each feature using bar/box plots
- Credit history shows the strongest correlation with approval

---

## 🧩 Data Preprocessing

- Handled missing values using mean/mode imputation
- Converted categorical variables using label encoding or one-hot encoding
- Scaled numeric values (optional)
- Encoded target variable (`Loan_Status`) as binary (Y = 1, N = 0)

---

## 🧠 Model Building & Evaluation

- **Models Used**: Logistic Regression, Decision Tree, etc.
- Train-Test Split: 80/20
- Metrics: Accuracy, Precision, Recall, F1-Score
- Observations: Credit history is the most important factor influencing loan approval

---

📈 Potential Improvements

- Feature Engineering (e.g., combine applicant and coapplicant income)
- Outlier treatment and skew correction
- Try models like Random Forest, XGBoost
- Perform hyperparameter tuning using GridSearchCV
- Address class imbalance using SMOTE or class weights
- Model deployment using Flask, Django, or Streamlit

✅ Conclusion
Loan approval prediction leverages a variety of applicant attributes—such as financial history, income, credit behavior, and employment status—to construct predictive models using historical data. Machine learning algorithms, including logistic regression and decision trees, empower lenders to automate and optimize approval decisions.

This project demonstrates how simple models can achieve meaningful accuracy, with features like credit history playing a crucial role in predictions. With appropriate preprocessing, feature engineering, and model selection, machine learning provides a scalable solution to streamline the loan approval pipeline.

