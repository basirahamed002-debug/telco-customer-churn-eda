
# Telco Customer Churn - Exploratory Data Analysis (EDA)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/telco-customer-churn-eda/blob/main/TCA.ipynb)

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset to identify patterns that lead to customer attrition. By analyzing demographics, account information, and service usage, we aim to uncover the primary drivers behind why customers leave.

## 📊 Business Insights Derived
Based on the analysis in `TCA.ipynb`:
* **Churn Rate:** Approximately **26.54%** of the customer base has churned.
* **Demographics:** Senior citizens exhibit a significantly higher churn percentage compared to non-senior citizens.
* **Gender:** Churn rates are relatively balanced between male and female customers, suggesting gender is not a strong predictor of churn.
* **Financial Impact:** Customers with higher monthly charges and lower tenure are at a higher risk of churning.

## 🛠️ Tech Stack
* **Environment:** Google Colab
* **Language:** Python 3.x
* **Libraries:** * `Pandas` & `NumPy`: Data manipulation and cleaning.
    * `Matplotlib` & `Seaborn`: Advanced data visualization.

## 🚀 How to Run in Google Colab
Since this project was developed using **Google Colab**, you can run it directly in your browser without any local installation.

1.  **Open the Notebook:** Click the "Open In Colab" badge at the top of this README.
2.  **Upload the Dataset:** * Locate the `Customer Churn.csv` file in this repository.
    * In the Colab sidebar, click the **Files** icon 📁.
    * Click the **Upload to session storage** button and select the dataset.
3.  **Run All Cells:** Go to `Runtime` -> `Run all`.

## 📁 Data Cleaning Steps
The analysis includes specific preprocessing steps to ensure data quality:
* Converted `TotalCharges` from string to numeric, handling empty strings as `0`.
* Mapped `SeniorCitizen` numeric values (0, 1) to readable categories ("no", "yes") for better visualization.

## 📈 Visualizations Included
* Churn Distribution Pie Charts.
* Gender-based Attrition Counts.
* Senior Citizen Churn Percentage Analysis (Stacked Bar Charts).

---
**Developed by:** [Basir Ahammed]  
**Portfolio/Contact:** [https://www.linkedin.com/in/basir-ahammed-mandal-b75935268/]
