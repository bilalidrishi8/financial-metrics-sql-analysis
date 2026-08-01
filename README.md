# 📊 Financial Performance SQL Analysis

## 📌 Project Overview

This project analyzes financial performance data using **PostgreSQL** to generate meaningful business insights. It covers SQL concepts from beginner to advanced, including aggregation, window functions, Common Table Expressions (CTEs), ranking, and financial KPI analysis.

The goal is to help understand company performance by analyzing revenue, expenses, profitability, cash flow, financial ratios, and growth trends.

---

# 🎯 Objectives

* Analyze company financial performance.
* Measure revenue and profit trends.
* Calculate Year-over-Year (YoY) and Quarter-over-Quarter (QoQ) growth.
* Rank companies based on financial performance.
* Identify high-performing and high-risk companies.
* Detect fraud-flagged companies.
* Generate business-ready financial reports using SQL.

---

# 🛠️ Tools & Technologies

* PostgreSQL
* SQL
* pgAdmin 4
* Git
* GitHub

---

# 📂 Repository Structure

```
financial-performance-sql-analysis/
│
├── Dataset/
│   └── financial_dataset.csv
│
├── Database/
│   ├── create_table.sql
│   └── import_data.sql
│
├── SQL Queries/
│   ├── 01_Beginner.sql
│   ├── 02_Intermediate.sql
│   ├── 03_Advanced.sql
│   ├── 04_Window_Functions.sql
│   └── 05_Business_Insights.sql
│
├── Images/
│
├── README.md
│
└── LICENSE
```

---

# 📊 Dataset Description

The dataset contains financial information for multiple companies across different years and quarters.

### Key Columns

* Company ID
* Year
* Quarter
* Revenue
* Expenses
* Operating Income
* Net Income
* Assets
* Liabilities
* Equity
* Cash Flow
* Earnings Per Share (EPS)
* Return on Equity (ROE)
* Return on Assets (ROA)
* Debt-to-Equity Ratio
* Stock Price
* Volume Traded
* Inflation Rate
* Interest Rate
* Audit Flag
* Fraud Flag
* Market Shock Flag

---

# 📚 SQL Concepts Covered

### Beginner

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT
* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()

### Intermediate

* GROUP BY
* HAVING
* CASE
* Subqueries
* Date Functions

### Advanced

* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* LAG()
* LEAD()
* Running Total
* Running Average
* Moving Average
* Year-over-Year (YoY) Growth
* Quarter-over-Quarter (QoQ) Growth
* Percentage Contribution
* Standard Deviation
* Financial KPI Analysis

---

# 📈 Business Questions Solved

* Calculate total revenue for each company.
* Find the top-performing companies by net income.
* Calculate average operating income by year.
* Identify companies with a high debt-to-equity ratio.
* Find the highest Return on Equity (ROE).
* Calculate Year-over-Year (YoY) revenue growth.
* Calculate Quarter-over-Quarter (QoQ) net income growth.
* Rank companies by revenue within each year.
* Identify the top-performing company in each sector.
* Calculate each company's contribution to total revenue.
* Find companies with above-average revenue.
* Detect companies with unusually high expenses.
* Compare fraud and non-fraud companies.
* Calculate cumulative revenue over time.
* Build a complete financial performance report.
* Find the top three companies by yearly net income.
* Identify companies with consistent yearly revenue growth.

---

# 📊 Key Insights

* Revenue trends across multiple years.
* Profitability comparison between companies.
* High-growth companies based on YoY and QoQ metrics.
* Companies with strong ROE and ROA.
* High-risk companies identified by debt-to-equity ratio.
* Fraud-flagged company performance analysis.
* Revenue contribution by company.
* Financial ranking using window functions.

---

# 💡 SQL Skills Demonstrated

* Data Exploration
* Financial KPI Analysis
* Business Reporting
* Window Functions
* Ranking Functions
* Aggregate Functions
* Statistical Analysis
* Growth Analysis
* Analytical Thinking
* Query Optimization

---

# 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/financial-performance-sql-analysis.git
```

### 2. Create the Database Table

Run:

```sql
create_table.sql
```

### 3. Import the Dataset

Import `financial_dataset.csv` into PostgreSQL using pgAdmin or the `COPY` command.

### 4. Execute SQL Files

Run the SQL scripts in the following order:

1. Beginner Queries
2. Intermediate Queries
3. Advanced Queries
4. Window Functions
5. Business Insights

---

# 📸 Project Preview

You can add screenshots of:

* SQL query outputs
* PostgreSQL database
* ER Diagram (optional)
* Query execution results
* Dashboard (optional)

inside the **Images** folder.

---

# 📖 Learning Outcomes

Through this project, you will learn how to use SQL to analyze financial data, calculate business KPIs, identify trends, rank company performance, and generate insights that support business decision-making.

---

# 🔮 Future Enhancements

* Build an interactive Power BI dashboard.
* Create Tableau visualizations.
* Perform exploratory analysis using Python.
* Develop predictive financial models.
* Automate financial reporting.

---

# 👨‍💻 Author

**Your Name**

Aspiring Data Analyst | SQL | PostgreSQL | Power BI | Python

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

Happy Learning and Happy Querying! 🚀
