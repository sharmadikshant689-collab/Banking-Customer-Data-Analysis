# Banking-Customer-Data-Analysis
Banking Data Analysis using Python, Pandas, NumPy, and Statistics. Explore customer demographics, income, account balances, credit scores, loan analysis, risk assessment, outlier detection, and customer segmentation.
# 🏦 Banking Dataset Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing banking customer data using Python and popular data analysis libraries. The goal is to explore customer demographics, financial behavior, account balances, credit scores, loan patterns, and customer segmentation to extract meaningful business insights.

This project demonstrates practical applications of **Exploratory Data Analysis (EDA), descriptive statistics, correlation analysis, outlier detection, and customer segmentation**.

## 🎯 Project Objectives

* Understand the structure and quality of banking customer data.
* Analyze customer age, annual income, and account balances.
* Compare financial characteristics across genders, occupations, cities, and account types.
* Classify customers based on credit scores.
* Analyze loan amounts, interest rates, and loan types.
* Identify potentially high-risk customers.
* Explore relationships between financial variables.
* Detect outliers using IQR and Z-score methods.
* Analyze skewness and the effects of logarithmic transformation.
* Segment customers based on income and account balance.
* Generate actionable insights from banking data.

## 🛠️ Technologies Used

* **Python** — Data analysis and programming
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Statistics** — Descriptive statistics and distribution analysis
* **Jupyter Notebook** — Interactive analysis

## 📊 Project Analysis

### 1. Dataset Overview

* Number of rows and columns
* Column names and data types
* Missing values
* Unique values

### 2. Customer Age Analysis

* Mean, median, minimum, and maximum age
* Standard deviation of customer age

### 3. Annual Income Analysis

* Mean, median, minimum, and maximum income
* Standard deviation
* 25th, 50th, and 75th percentiles

### 4. Account Balance Analysis

* Descriptive statistics for account balances
* Identification of customers with balances above ₹10,00,000

### 5. Gender Analysis

* Customer count by gender
* Average annual income
* Average account balance
* Average credit score
* Average customer satisfaction

### 6. Occupation Analysis

* Customer distribution by occupation
* Average annual income by occupation
* Average account balance by occupation

### 7. City Analysis

* Top 10 cities with the highest number of customers

### 8. Account Type Analysis

* Customer count by account type
* Average account balance
* Average annual income
* Average monthly transactions

### 9. Credit Score Classification

Customers are classified into four categories:

| Credit Score  | Category  |
| ------------- | --------- |
| 750 and above | Excellent |
| 700–749       | Good      |
| 650–699       | Average   |
| Below 650     | Poor      |

### 10. Loan Analysis

* Number of customers with loans
* Total and average loan amounts
* Median loan amount
* Average interest rate
* Most common loan type

### 11. High-Risk Customer Identification

Identify customers who meet at least two of the following conditions:

* Credit score below 650
* Loan amount above ₹10,00,000
* Interest rate above 15%
* Account balance below ₹20,000

### 12. Correlation Analysis

Examine relationships between:

* Annual income and loan amount
* Credit score and loan amount
* Annual income and account balance
* Monthly transactions and account balance

### 13. Outlier Detection Using IQR

Detect outliers in annual income, account balance, and loan amount using the Interquartile Range (IQR) method.

Calculate:

* First quartile (Q1)
* Third quartile (Q3)
* Interquartile range (IQR)
* Lower and upper limits
* Number of outliers

### 14. Z-Score Analysis

Calculate Z-scores for annual income, account balance, credit score, and loan amount.

Identify customers whose absolute Z-score exceeds 3.

### 15. Distribution and Skewness Analysis

Analyze the distributions of annual income, account balance, and loan amount.

* Calculate skewness before transformation.
* Apply `log1p()` transformations.
* Calculate skewness after transformation.
* Compare the distributions to understand the effects of the transformation.

### 16. Customer Segmentation

Divide customers into four groups using annual income and account balance:

* High Income + High Balance
* High Income + Low Balance
* Low Income + High Balance
* Low Income + Low Balance

Compare customer counts, average credit scores, average monthly transactions, and churn rates across the segments.

## 💡 Expected Business Insights

This analysis aims to help identify:

* Customer groups with different financial characteristics
* Occupations and cities with larger customer populations
* Patterns in income, savings, and borrowing
* Potentially high-risk customers who may require further review
* Relationships between financial variables
* Unusual financial values that need investigation
* Customer segments that differ in financial behavior and churn

**Note:** These are intended areas of investigation, not confirmed findings. Actual insights will depend on the dataset and analysis results.

## 📁 Project Structure

```text
Banking-Dataset-Analysis/
│
├── banking_dataset.csv
├── Banking_Analysis.ipynb
└── README.md
```

*Replace the example filenames with your actual filenames if they differ.*

## 🚀 How to Run the Project

1. Clone or download this repository.

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Banking_Analysis.ipynb`.

5. Update the dataset path if necessary.

6. Run the notebook cells to reproduce the analysis.

## 📚 Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Descriptive statistics
* GroupBy and aggregation
* Correlation analysis
* IQR-based outlier detection
* Z-score analysis
* Skewness and logarithmic transformations
* Customer segmentation
* Business-oriented data interpretation

## 👨‍💻 Author

Created as a practical data analytics project to develop Python, statistics, and exploratory data analysis skills.

---

⭐ If you find this project useful, consider giving the repository a star!
