# 🚗 Car Insurance Claim Prediction using Python

This project focuses on predicting the frequency of car insurance claims using machine learning techniques. By analyzing driver and vehicle attributes, the model aims to assist insurance companies in risk assessment and premium determination.

## 📁 Project Structure

- **Notebook**: [Car Insurance Modelling using Python.ipynb](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Car%20Insurance%20Modelling%20using%20Python/Car%20Insurance%20Modelling%20using%20Python.ipynb)
- **Dataset**: [insurance_claims.csv](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Car%20Insurance%20Modelling%20using%20Python/insurance_claims.csv)
- **Visualization**: [Distribution Plot of Age, Car Age, and Number of Claims](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Car%20Insurance%20Modelling%20using%20Python/Distplo%20of%20%20Age%2CCar%2C%20No.of%20Claims.png)

## 🎯 Objective

The primary goal is to develop a predictive model that estimates the number of insurance claims a driver might file, based on factors such as:

- Driver's age
- Vehicle age
- Geographical region (Urban, Rural, Suburban)

This model can aid insurance companies in:

- Assessing risk profiles of potential clients
- Determining appropriate premium amounts
- Implementing targeted marketing strategies

## 🧠 Methodology

The project follows a structured data science approach:

1. **Data Loading & Exploration**:
   - Imported the dataset and performed initial exploration to understand the data distribution and identify missing values.

2. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Encoded categorical variables using appropriate techniques.

3. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions of key variables.

4. **Model Development**:
   - Implemented various machine learning algorithms, including:
     - Linear Regression
     - Decision Trees
     - Random Forest
   - Evaluated models using metrics such as Mean Squared Error (MSE) and R-squared.
   - Performed hyperparameter tuning to optimize model performance.

5. **Model Interpretation**:
   - Analyzed feature importances to understand the impact of each variable.
   - Interpreted model outputs to derive actionable business insights.

## 📊 Key Findings

- Younger drivers and older vehicles tend to have a higher number of claims.
- Urban regions exhibit a higher frequency of claims compared to rural and suburban areas.
- The Random Forest model outperformed other algorithms, achieving an R-squared value of 0.85, indicating a strong predictive capability.

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn
- **Environment**: Jupyter Notebook
