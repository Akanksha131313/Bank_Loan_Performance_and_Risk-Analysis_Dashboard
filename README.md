# Financial-Report-Analysis |Capstone Project|

**Author**: Akanksha Mishra

**Role Demonstrated:** Data Analyst | SQL | Financial Analytics | Business Intelligence

**Project Duration:** Nov 2024 – Dec 2025

**1. Project Overview ->**

**Objective:**

Develop a comprehensive analytics framework to monitor, evaluate, and optimize bank loan performance across multiple dimensions: loan issuance, funding, repayment, interest rates, borrower risk, and geographical insights.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Purpose:**

• Transform raw transactional data into actionable business insights.

• Identify high-performing (good) loans and high-risk (bad) loans to inform strategic decisions.

• Enable dynamic reporting and dashboards for management and stakeholders.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**2. Problem Statement ->**

-> Banks and financial institutions need:

• Real-time monitoring of loan applications, funded amounts, repayments, and interest trends.

• Insights into borrower profiles (employee length, income, home ownership) for risk assessment.

• Month-over-month (MoM) and state-wise analysis to optimize portfolio allocation.

• This project provides SQL-driven solutions to answer all these business questions.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3. Approach & Methodology ->**

• Data Source:

a) Loan transactional dataset from dbo.financial_loan.

-> Includes fields: loan_amount, total_payment, issue_date, loan_status, int_rate, dti, emp_length, address_state, purpose, home_ownership, grade.

• Analysis Steps:

-> KPIs Calculation:

a) Total loan applications, fund disbursed, repayments, interest rates, DTI.

b) Month-to-date (MTD) and previous MTD comparisons for trend analysis.

-> Loan Performance Segmentation:

a) Good loans (Fully Paid or Current) vs. Bad loans (Charged Off).

b) Percentage, funded amount, and recovery metrics per segment.

-> Loan Status & Trend Analysis:

a) Aggregated loan counts, amounts funded, repayments, interest rate, and DTI by loan status.

b) Month-over-month and filter-based analysis for dynamic insights.

-> Multi-Dimensional Dashboards:

a) Time (monthly trends)

b) Geography (state-wise performance)

c) Loan term & purpose

d) Borrower profile (employee length, home ownership)

-> Advanced SQL Techniques Applied:

a) CTEs for modular analysis and ranking

b) Subqueries for conditional insights

c) Window Functions (LAG, LEAD, RANK, cumulative sums)

d) Aggregates & Grouping (AVG, SUM, TOP N, HAVING)

e) CTAS for reusable output tables

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**4. Key Highlights & Impact ->**
-> Metric	                         Insight / Result
a) Total Loans :	                 Monitored trends over time, supporting strategic loan issuance decisions

b) Funded Amount :	                 Identified allocation patterns across states and borrower profiles

c) Loan Recovery :	                 Highlighted risk exposure and repayment efficiency

d) Good vs Bad Loans :	             Segmented loans to prioritize risk mitigation and revenue optimization

e) Interest Rates & DTI	:            Assessed portfolio health and borrower affordability

f) Dashboard-Ready Data	:            Prepared outputs for Power BI/Tableau visualizations

-> Business Impact:

a) Informed Decision Making: Provides clear insights to prioritize lending strategies.

b) Risk Management: Early identification of bad loans for mitigation.

c) Revenue Optimization: Focus on high-performing loans and profitable borrower segments.

d) Scalable Analytics: Queries can be reused for future datasets and dashboard integration.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**5. Technical Skills Demonstrated ->**

a) SQL (Advanced): CTEs, Subqueries, Window Functions, Aggregates, CTAS

b) Data Analysis & Reporting: KPI computation, segment-wise analysis, MoM comparison

c) Financial Analytics: Loan portfolio evaluation, risk assessment, recovery tracking

d) Dashboard-Ready Data Preparation: Multi-dimensional outputs for visualization tools

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**6. How to Use / Run the Queries ->**

a) Load the dataset in SQL Server.

b) Execute KPI queries to get high-level insights.

c) Use filters (Grade, Loan Status, Purpose, Month) for granular analysis.

d) Apply advanced queries (CTEs, window functions) for deep-dive analysis.

e) Export results for visualization in BI tools.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**7. Outcome & Achievements ->**

a) Delivered a fully functional bank loan analytics framework.

b) Enabled data-driven strategic decisions in loan portfolio management.

c) Demonstrated end-to-end data analytics capabilities suitable for finance and data roles.

d) Ready-to-use outputs for executive dashboards and reporting.

**Result:** Project positions the candidate as an SQL-proficient Data Analyst capable of deriving actionable insights from complex financial datasets—exactly what recruiters want to see.
