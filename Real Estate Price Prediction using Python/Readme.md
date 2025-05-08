# 🏡 Real Estate Price Prediction using Python

This project builds a machine learning model to predict house prices per unit area using real estate data. The project follows a typical data science pipeline: data analysis, visualization, feature selection, model training, and evaluation.

## 📂 Project Structure

- `Real_Estate.csv` — Dataset containing house-related features and prices.
- `Real Estate Price Prediction using Python.ipynb` — Jupyter notebook with full implementation.
- `*.png` — Visualizations used in the analysis and results.

## 📊 Dataset Description

The dataset includes:
- `Transaction date`: When the sale occurred
- `House age`: Age in years
- `Distance to MRT station`: Proximity to public transport
- `Number of convenience stores`
- `Latitude`, `Longitude`: Location coordinates
- `House price of unit area`: Target variable (price per unit area)

## 🔍 Exploratory Data Analysis

### 📌 Histograms
![](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Real%20Estate%20Price%20Prediction%20using%20Python/Histograms%20of%20Real%20Estate%20Data.png?raw=true)

- House age and distance to MRT show skewed distributions.
- Latitude and longitude indicate geographical clustering.

### 🔗 Correlation Matrix
![](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Real%20Estate%20Price%20Prediction%20using%20Python/Correlation%20Matrix.png?raw=true)

- Distance to MRT has a strong negative correlation with price.
- Latitude shows a positive correlation.

### 📈 Scatter Plots
![](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Real%20Estate%20Price%20Prediction%20using%20Python/Scatterplots%20with%20house%20price%20of%20unit%20area.png?raw=true)

- Visual relationships between each feature and the house price.

## 🤖 Model Building

A **Linear Regression** model was trained using:
- Features: Distance to MRT, number of convenience stores, latitude, and longitude
- Target: House price of unit area

Data was split into training and testing sets. Performance was measured using:
- **Mean Squared Error (MSE)**
- **R² Score**

### 📉 Predictions vs Actual Prices
![](https://github.com/MohithKumar8897/Machine-Learning-Projects-/blob/main/Real%20Estate%20Price%20Prediction%20using%20Python/Actual%20Vs%20pridicted%20house%20prices.png?raw=true)

- **The diagonal dashed line represents where the actual and predicted values would be equal. Points close to this line indicate accurate predictions. From the plot, we can observe:**

- **Many points are close to the diagonal line, suggesting that the model makes reasonably accurate predictions for a significant portion of the test set.
Some points are further from the line, indicating areas where the model’s predictions deviate more significantly from the actual values.**

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
