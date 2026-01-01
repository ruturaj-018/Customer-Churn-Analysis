# Customer Churn Analysis

## 📌 Project Overview

Customer churn is a critical business problem where customers stop using a company’s services. This project analyzes **telecom customer churn data** to identify **key drivers of churn**, understand **high-risk customer segments**, and generate **actionable business insights** using data analysis and visualization.

The project follows a **clean, step-by-step data science workflow** — from raw data understanding to segmentation-driven insights — making it suitable for **academic evaluation, internships, and interview discussions**.

---

## 🎯 Objectives

* Understand the structure and quality of the customer churn dataset
* Clean and prepare raw data for analysis
* Perform Exploratory Data Analysis (EDA) to uncover churn patterns
* Segment customers based on behavior and risk factors
* Create business-ready visualizations to support decision-making

---

## 🗂️ Project Structure

```
Customer-Churn-Analysis/
│
├── 01_data/
│   └── Telco_Customer_Churn.csv
│
├── 02_notebooks/
│   ├── task1_dataset_overview.ipynb
│   ├── task2_data_cleaning.ipynb
│   ├── task3_eda.ipynb
│   └── task4_segmentation_visuals.ipynb
│
├── 03_outputs/
│   ├── charts/
│   └── cleaned_data.csv
│
└── README.md
```

---

## 📊 Dataset Description

* **Source:** Telecom customer dataset (Kaggle-style / academic use)
* **Rows:** ~7,000 customers
* **Columns:** Demographics, service usage, billing, contract details, and churn status
* **Target Variable:** `Churn` (1 = Customer left, 0 = Customer stayed)

Key features include:

* `tenure`, `MonthlyCharges`, `TotalCharges`
* `Contract`, `PaymentMethod`, `InternetService`
* `SeniorCitizen`, `Partner`, `Dependents`

---

## 🔧 Tools & Technologies

* **Language:** Python
* **Libraries:**

  * pandas, numpy – data handling
  * matplotlib, seaborn – visualization
* **Environment:** Google Colab / Jupyter Notebook

---

## 🧪 Workflow Summary

### 1️⃣ Dataset Overview

* Loaded raw dataset
* Inspected shape, columns, data types
* Identified target variable and data quality issues

### 2️⃣ Data Cleaning

* Converted `TotalCharges` to numeric format
* Handled missing values using business logic
* Removed non-informative columns (`customerID`)
* Converted binary categorical variables to numeric
* Exported cleaned dataset for reuse

### 3️⃣ Exploratory Data Analysis (EDA)

* Analyzed churn distribution
* Studied churn behavior across:

  * Gender
  * Senior Citizen status
  * Contract type
  * Tenure
  * Monthly charges
  * Payment method
* Generated insight-driven visualizations

### 4️⃣ Customer Segmentation

* Created churn-rate-based segments using:

  * Contract types
  * Tenure groups
  * Monthly charge buckets
  * Payment methods
  * Internet service types
* Identified high-risk churn segments
* Saved final, business-ready charts

---

## 📈 Key Insights

* **Month-to-month contracts** show the highest churn rates
* **Early-tenure customers** are most vulnerable to churn
* **High monthly charges** correlate with increased churn
* Customers using **electronic check payment** churn more often
* Long-term contracts significantly improve retention

---

## 📂 Outputs

* `cleaned_data.csv` – fully processed, ML-ready dataset
* `charts/` – churn analysis and segmentation visualizations

---

##  How to Run the Project

1. Open the notebooks in order from `02_notebooks/`
2. Use **Google Colab** or local Jupyter environment
3. Upload the dataset to the correct path if required
4. Run notebooks sequentially (Task 1 → Task 4)

---

##  Future Enhancements

* Build predictive churn models (Logistic Regression, Random Forest, XGBoost)
* Handle class imbalance using SMOTE
* Add feature importance analysis
* Deploy insights using a dashboard (Power BI / Streamlit)

---

## 👤 Author

**Ruturaj Shital Mankapure**
Final-Year B.Tech – Artificial Intelligence & Data Science

---

## 📝 License

This project is intended for **educational and academic use**.

---

> *This project demonstrates a structured, business-oriented approach to data analysis rather than just code execution — focusing on clarity, logic, and real-world relevance.*
