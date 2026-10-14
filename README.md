# Financial Loan Default Analysis Using Python and Power BI

## Project Overview
This project analyzes financial loan data to identify loan default patterns, understand borrower behavior, and generate business insights using Python and Power BI.

The project follows a data analytics workflow, from data cleaning and exploratory analysis to interactive dashboard development.

## Project Objectives
- Clean and preprocess financial loan data using Python.
- Analyze loan performance and default trends.
- Identify relationships between loan grades, interest rates, loan purposes, and defaults.
- Create DAX measures for key performance indicators (KPIs).
- Develop an interactive Power BI dashboard to support data-driven decision-making.

## Dataset Information
- **Dataset:** Financial Loan Dataset
- **Initial Records:** 38,576 rows
- **Original Columns:** 24
- **Final Columns:** 25, including the derived `default_flag` column
- **Target Indicator:** `default_flag`
  - `0` = Non-defaulted loan
  - `1` = Defaulted loan

## Tools and Technologies
- **Python:** Data cleaning, preprocessing, and exploratory data analysis
- **Pandas and NumPy:** Data manipulation and analysis
- **Matplotlib:** Data visualization
- **Power BI:** Interactive dashboard development
- **DAX:** KPI calculations and business analysis
- **Excel:** Source dataset and data review
- **GitHub:** Project version control and documentation

## Project Workflow

### 1. Data Cleaning and Preprocessing
- Loaded the financial loan dataset into Python.
- Inspected the dataset structure and data types.
- Checked for missing values and duplicate records.
- Handled missing values in the `emp_title` column.
- Created the `default_flag` column using loan status.
- Saved the cleaned dataset for Power BI analysis.

### 2. Exploratory Data Analysis (EDA)
Analyzed loan characteristics and default patterns, including:
- Loan status distribution.
- Default rates across loan grades.
- Loan amounts for defaulted and non-defaulted loans.
- Interest rate patterns.
- Loan purpose distribution.
- Borrower income and loan characteristics.

### 3. Power BI Analysis
Imported the cleaned dataset into Power BI and created DAX measures for key business calculations.

The dashboard includes:
- KPI cards for key loan metrics.
- Total Loans by Loan Status.
- Default Rate by Grade.
- Total Loans by Purpose.
- Average Interest Rate by Grade.
- Interactive slicers for filtering the analysis.

### 4. Dashboard and Business Insights
The Power BI dashboard helps users explore loan performance, compare default rates, and identify categories that may require closer monitoring.

## Key Findings

- **Total loan records:** 38,576.
- **Defaulted loans:** 5,333.
- **Non-defaulted loans:** 33,243.
- **Overall default rate:** Approximately 13.82%.
- **Average interest rate:** Approximately 12.05%.
- **Default rate by grade:** The observed default rate increased from approximately 5.70% for Grade A to 31.31% for Grade G.

These findings highlight differences in default risk across loan grades and demonstrate how data analytics can support loan portfolio monitoring.

## Business Recommendations
- Monitor higher-risk loan grades more closely.
- Review borrower and loan characteristics associated with higher default rates.
- Use interactive dashboards to track loan performance and default trends.
- Apply data-driven insights to support risk assessment and lending decisions.

## Project Deliverables
- Python data cleaning and EDA work.
- Cleaned financial loan dataset.
- Power BI dashboard (`.pbix`).
- Final project report documenting methodology, calculations, findings, and visualizations.

## Conclusion
This project demonstrates the application of Python and Power BI to a financial loan dataset. It combines data preprocessing, exploratory analysis, DAX calculations, and interactive visualization to communicate meaningful business insights.

The project strengthened my practical skills in data analytics, data visualization, and business reporting.

## Author
**Ligi Mathew**

Aspiring Data Analyst | Python | SQL | Excel | Power BI









