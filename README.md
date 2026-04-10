# ML_Insurance_project
"An end-to-end Machine Learning project using Linear Regression to predict medical insurance costs based on patient attributes like BMI, age, and smoking status. Includes EDA, data preprocessing, and model evaluation."





# Medical Insurance Cost Prediction 🏥

This project implements a **Linear Regression** model to predict the individual medical costs billed by health insurance. It explores how various factors such as age, BMI, and lifestyle choices (smoking) impact the final insurance charges.

## 🚀 Project Overview
The goal of this project is to provide an accurate estimate of insurance costs using a dataset of 1,338 patients.

### Key Features:
* **Exploratory Data Analysis (EDA):** Visualizing distributions and correlations using Seaborn and Matplotlib.
* **Data Preprocessing:** Handling categorical variables through One-Hot Encoding and Label Encoding.
* **Model Training:** Implementing Scikit-Learn's `LinearRegression`.
* **Performance Metrics:** * **R² Score:** ~0.78
    * **Adjusted R² Score:** ~0.77

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Google Colab

## 📊 Dataset Insights
The dataset contains columns such as:
- `age`: Age of primary beneficiary
- `sex`: Insurance contractor gender
- `bmi`: Body mass index
- `children`: Number of children covered by health insurance
- `smoker`: Smoking status
- `region`: The beneficiary's residential area in the US
- `charges`: Individual medical costs billed by health insurance (Target Variable)
