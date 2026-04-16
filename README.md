# 📊 Telecom Customer Churn Analysis

This repository contains a complete analysis of telecom customer churn
using Python and Google Colab. The project explores why customers
leave the service and identifies key patterns that influence churn
behavior.

## 🚀 Project Overview

Customer churn is a major issue for telecom companies. This project
focuses on:

-   Cleaning and preparing the dataset
-   Exploring customer behavior through visualizations
-   Understanding service-related and contract-related churn factors
-   Generating insights from demographic and usage patterns

## 🗂️ Dataset Description

The dataset includes features related to:

-   **Demographics:** gender, SeniorCitizen, Partner, Dependents
-   **Services:** InternetService, PhoneService, OnlineSecurity,
    TechSupport, StreamingTV, etc.
-   **Account Information:** Contract, PaymentMethod, PaperlessBilling
-   **Financials:** MonthlyCharges, TotalCharges
-   **Target Column:** **Churn** (Yes/No)

## 🧹 Data Cleaning & Processing

-   Fixed blank `TotalCharges` values where tenure = 0
-   Standardized column types
-   Improved category labels
-   Handled missing values

## 📈 Exploratory Data Analysis (EDA)

Includes:

-   Countplots for all categorical features
-   Churn vs non-churn comparisons
-   Stacked percentage charts
-   Tenure distribution patterns

## 🛠️ Tools & Technologies

-   Python 3
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## 📘 Notebook Structure

    Telecom_Customer_Churn_Analysis.ipynb
    │
    ├── Load & Inspect Dataset
    ├── Data Cleaning
    ├── Feature Transformation
    ├── EDA (Countplots, Stacked Charts, Distributions)
    └── Key Insights & Observations

## 🔍 Key Insights

-   Month-to-Month contract customers churn the most
-   Lack of OnlineSecurity, TechSupport, or Backup increases churn
-   Fiber optic users show higher churn
-   Tenure below 6 months has high churn probability
-   Payment method 'Electronic Check' correlates with higher churn

## 📎 Running the Project

Open the notebook using the provided link, copy it to your workspace, import the dataset, and you are ready to execute the full analysis.

Notebook: [**Telecom_Customer_Churn_Analysis.ipynb**](https://colab.research.google.com/drive/1Lw5a3JoYD8IPXvKdTHrgKqYIFUFdfBrY?usp=sharing)


## 🤝 Contribution

Contributions, issues, and pull requests are welcome.

## 📜 License

MIT License
