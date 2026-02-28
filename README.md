#  Bank Loan Portfolio Analysis Dashboard – Power BI

##  Project Overview

This project presents a comprehensive **Bank Loan Portfolio Analysis Dashboard** developed in Power BI.

The objective is to monitor loan performance, evaluate portfolio health, analyze borrower risk, and identify lending trends using advanced KPI tracking and interactive dashboards.

The solution enables data-driven decision-making by providing:

* Loan performance tracking
* Risk segmentation (Good vs Bad Loans)
* Time-based trend analysis (MTD & MoM)
* Regional and demographic breakdowns
* Detailed loan-level reporting

---

#  Tools & Technologies

* Power BI
* DAX (Time Intelligence & Advanced Measures)
* Power Query (ETL & Data Cleaning)
* Data Modeling (Star Schema)
* Financial KPI Design

---

#  Key Performance Indicators (KPIs)

##  Core Lending KPIs

* **Total Loan Applications**
* **Total Funded Amount**
* **Total Amount Received**
* **Average Interest Rate**
* **Average Debt-to-Income Ratio (DTI)**

### Time Intelligence Metrics

* Month-to-Date (MTD) Loan Applications
* MTD Funded Amount
* MTD Amount Received
* Month-over-Month (MoM) Growth %
* MoM Variations in Interest Rate & DTI

These KPIs help track portfolio growth, repayment health, and lending efficiency.

---

#  Good Loan vs  Bad Loan Analysis

Loans are segmented based on loan performance status to evaluate portfolio risk.

##  Good Loan KPIs

* Good Loan Application Percentage
* Good Loan Applications
* Good Loan Funded Amount
* Good Loan Total Received Amount

##  Bad Loan KPIs

* Bad Loan Application Percentage
* Bad Loan Applications
* Bad Loan Funded Amount
* Bad Loan Total Received Amount

### Business Value

This segmentation allows:

* Risk exposure monitoring
* Default pattern identification
* Performance comparison between healthy and risky loans
* Better credit policy evaluation

---

#  Loan Status Grid View

A structured **Loan Status Grid Report** was created to provide a consolidated overview categorized by *Loan Status*.

### Metrics Included:

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* MTD Funded Amount
* MTD Amount Received
* Average Interest Rate
* Average DTI

### Purpose:

This grid empowers stakeholders to:

* Compare performance across loan statuses
* Assess repayment efficiency
* Monitor funding quality
* Evaluate portfolio health in one consolidated view

---

#  Dashboard Pages & Visualizations

##  Page 1 – Executive Summary Dashboard

High-level KPI overview including:

* Applications
* Funded Amount
* Amount Received
* MTD & MoM Analysis
* Good vs Bad Loan Performance

---

##  Page 2 – Analytical Dashboard

###  Monthly Trends by Issue Date (Line Chart)

* Identifies seasonality
* Detects long-term lending trends
* Tracks growth patterns

---

###  Regional Analysis by State (Filled Map)

* Highlights high-lending regions
* Identifies regional disparities
* Supports geographic strategy decisions

---

###  Loan Term Analysis (Donut Chart)

* Shows distribution across term lengths
* Helps evaluate short-term vs long-term loan preferences

---

###  Employee Length Analysis (Bar Chart)

* Analyzes lending behavior across employment durations
* Assesses financial stability impact on borrowing

---

###  Loan Purpose Breakdown (Bar Chart)

* Displays primary reasons for borrowing
* Identifies high-demand financing categories

---

###  Home Ownership Analysis (Tree Map)

* Hierarchical view of home ownership categories
* Evaluates impact on loan applications & disbursement

### Metrics Displayed Across Visuals:

* Total Loan Applications
* Total Funded Amount
* Total Amount Received

---

##  Page 3 – Details Dashboard (Grid View)

###  Objective

To provide a comprehensive, detailed, and user-friendly interface containing all essential loan-level data.

### Features:

* Consolidated loan-level records
* Borrower profile insights
* Loan performance indicators
* Fully filterable grid structure

### Business Impact:

This page serves as a **one-stop solution** for:

* Deep portfolio inspection
* Individual loan tracking
* Risk investigation
* Operational reporting

---

#  Advanced DAX Techniques Used

* CALCULATE()
* TOTALMTD()
* DATESMTD()
* DATEADD()
* MoM Growth % Calculations
* Conditional Filtering (Good vs Bad Loans)
* Context Transition Handling
* Dynamic KPI Switching

---

#  Data Preparation & Modeling

* Cleaned missing and inconsistent records
* Built a dedicated Date Table
* Established relationships using star schema
* Created calculated columns for loan segmentation
* Optimized data model for performance

---

#  Key Insights Generated

* Identified monthly fluctuations in loan demand
* Evaluated repayment strength across time periods
* Measured portfolio risk using DTI & interest rate trends
* Compared profitability and risk between Good & Bad Loans
* Detected geographic lending concentration

---

#  Skills Demonstrated

* Financial Data Analysis
* Banking Portfolio Analytics
* Time Intelligence in DAX
* Risk Segmentation
* Data Modeling
* Business KPI Development
* Interactive Dashboard Design
* Analytical Storytelling






