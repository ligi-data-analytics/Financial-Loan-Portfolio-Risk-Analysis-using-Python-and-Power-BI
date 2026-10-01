# Loan Default Analysis – Financial & Loan Operations

## 📌 Project Overview

This project analyzes loan application and repayment data to identify patterns associated with loan defaults.

The project is designed around **Financial/Loan Operations** and demonstrates how Python and Power BI can be used to analyze loan performance, borrower characteristics, and default risk.

The analysis focuses on understanding loan characteristics, borrower profiles, and factors associated with loan defaults.

---

## 🎯 Business Objective

The main objectives of this project are:

* Analyze overall loan performance
* Identify the proportion of defaulted loans
* Understand borrower and loan characteristics
* Analyze default rates across different loan grades
* Identify patterns in interest rates, loan amounts, income, and DTI
* Prepare insights that can support financial and loan operations
* Build an interactive Power BI dashboard for business reporting

---

## 📊 Dataset

The dataset contains **38,576 loan records** and **30 columns** after data preparation.

Important fields include:

* `loan_amount`
* `annual_income`
* `int_rate`
* `dti`
* `installment`
* `total_payment`
* `grade`
* `sub_grade`
* `emp_length`
* `home_ownership`
* `verification_status`
* `purpose`
* `address_state`
* `loan_status`
* `term`
* `issue_date`

Additional analytical columns were prepared during data cleaning:

* `emp_length_years`
* `term_months`
* `issue_year`
* `issue_month`
* `issue_month_name`
* `default_flag`

---

## 🧹 Data Preparation

The following data preparation activities were completed:

* Checked dataset structure
* Checked duplicate records
* Checked missing values
* Verified data types
* Converted date columns to datetime format
* Created employment-length numeric values
* Created loan-term numeric values
* Extracted year and month from issue dates
* Created a binary `default_flag` for default analysis

### Default Classification

| Loan Status | Default Flag |
| ----------- | -----------: |
| Fully Paid  |            0 |
| Current     |            0 |
| Charged Off |            1 |

The dataset contains:

* **33,243 non-defaulted loans**
* **5,333 defaulted loans**
* **13.82% overall default rate**

---

## 🔎 Initial EDA Findings

### Default Rate by Loan Grade

| Grade | Default Rate |
| ----- | -----------: |
| A     |        5.70% |
| B     |       11.50% |
| C     |       16.02% |
| D     |       20.69% |
| E     |       24.80% |
| F     |       30.25% |
| G     |       31.31% |

The initial analysis shows differences in default rates across loan grades.

### Defaulted vs Non-Defaulted Loans

Initial group-level analysis shows differences in:

* Average loan amount
* Annual income
* Interest rate
* DTI
* Installment amount
* Total payment

Further analysis will examine these relationships across additional borrower and loan characteristics.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook / Google Colab
* Power BI
* Git & GitHub

---

## 📈 Planned Power BI Dashboard

The next stage of the project will include an interactive Power BI dashboard covering:

* Total Loans
* Total Loan Amount
* Defaulted Loans
* Default Rate
* Loan Status Distribution
* Default Rate by Grade
* Default Rate by Purpose
* Default Rate by State
* Default Rate by Employment Length
* Default Rate by Home Ownership
* Default Rate by Verification Status
* Loan Trends by Year and Month

---

## 📂 Project Structure

```text
Loan-Default-Analysis/
│
├── data/
│   └── loan_dataset.csv
│
├── notebooks/
│   └── loan_default_analysis.ipynb
│
├── powerbi/
│   └── loan_default_dashboard.pbix
│
├── README.md
└── requirements.txt
```

---

## 🚀 Project Status

### Completed

* [x] Dataset loading
* [x] Data inspection
* [x] Duplicate check
* [x] Missing-value check
* [x] Data-type verification
* [x] Feature preparation
* [x] Default flag creation
* [x] Initial EDA
* [x] Grade-wise default analysis

### In Progress

* [ ] Employment profile analysis
* [ ] Home ownership analysis
* [ ] Verification-status analysis
* [ ] Loan-term analysis
* [ ] Purpose-wise analysis
* [ ] State-wise analysis
* [ ] Power BI dashboard
* [ ] Final business insights

---

## 👩‍💻 Author

**Ligi Mathew**

Data Analytics Portfolio Project
Focus: Financial & Loan Operations Analytics
