# 🏦 Bank Loan Analysis | Python Data Analytics Project

## 📌 Project Overview

The Bank Loan Analysis project focuses on analyzing financial loan data to understand lending performance, customer behavior, and repayment patterns. The project uses Python to perform Exploratory Data Analysis (EDA), calculate key financial metrics, and visualize important insights to support better business decision-making.

## 🎯 Project Objectives

- Analyze total loan applications and funded amounts.
- Evaluate total payments received from borrowers.
- Identify good loans and bad loans.
- Analyze monthly loan application and funding trends.
- Understand loan distribution across different states.
- Examine loan performance based on loan term, employment length, purpose, and home ownership.

## 🛠️ Tools & Technologies

- **Python** – Data analysis and manipulation.
- **Jupyter Notebook** – Development and analysis environment.
- **Pandas** – Data cleaning and manipulation.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Plotly** – Interactive visualizations.

## 📂 Dataset Description

The project uses financial loan data containing borrower information, loan details, repayment information, and loan status.

Important dataset columns include:

- `id` – Unique loan application ID.
- `issue_date` – Loan issue date.
- `loan_amount` – Funded loan amount.
- `total_payment` – Total amount received.
- `int_rate` – Interest rate.
- `dti` – Debt-to-Income ratio.
- `loan_status` – Current status of the loan.
- `address_state` – Borrower's state.
- `term` – Loan repayment term.
- `emp_length` – Employment length.
- `purpose` – Loan purpose.
- `home_ownership` – Home ownership category.

## 📊 Key Performance Indicators (KPIs)

The following metrics were calculated to evaluate overall loan performance:

1. Total Loan Applications
2. Month-to-Date (MTD) Loan Applications
3. Total Funded Amount
4. MTD Total Funded Amount
5. Total Amount Received
6. MTD Total Amount Received
7. Average Interest Rate
8. Average Debt-to-Income Ratio (DTI)

## 🔍 Analysis Performed

### 1. Good Loan Analysis
Analyzed fully paid and current loans to understand successful loan performance.

### 2. Bad Loan Analysis
Analyzed charged-off loans to evaluate unsuccessful loan performance.

### 3. Monthly Trend Analysis
Examined monthly trends in:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received

### 4. Regional Analysis
Analyzed total funded loan amounts across different states to understand regional lending patterns.

### 5. Loan Term Analysis
Compared total funded amounts across different loan repayment terms.

### 6. Employment Length Analysis
Examined loan funding distribution based on borrowers' employment length.

### 7. Loan Purpose Analysis
Analyzed loan amounts across different purposes to identify funding distribution.

### 8. Home Ownership Analysis
Evaluated total funded amounts based on home ownership categories.

## 📈 Key Insights

This project helps identify:

- Trends in loan applications and funded amounts.
- Differences between good and bad loan performance.
- Monthly changes in lending and repayment activities.
- State-wise loan funding distribution.
- Loan funding patterns based on employment length and loan purpose.
- The relationship between home ownership and loan funding distribution.

## 📁 Project Structure

Bank-Loan-Analysis/
│
├── Dataset/
│   └── financial_loan.xlsx
│
├── Notebook/
│   └── Bank_Loan_Analysis.ipynb
│
├── Images/
│   └── analysis_charts.png
│
├── README.md
│
├── Bank_Loan_Analysis.pbix
│
└── Bank_Loan_Analysis.pptx

## ⚙️ How to Run This Project

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Bank-Loan-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Bank-Loan-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Bank_Loan_Analysis.ipynb` and run the cells.

**Note:** Ensure the dataset is placed inside the `Dataset` folder and update the notebook file path accordingly.

## 📝 Conclusion

This project demonstrates the use of Python for financial data analysis, KPI calculation, Exploratory Data Analysis (EDA), and data visualization. It provides insights into loan applications, funding activities, repayment patterns, and loan performance, helping understand lending trends and business performance.

## 👩‍💻 Author
Swetha podaralla

**Data Analytics Portfolio Project**

