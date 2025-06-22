# 💼 Bank Loan Insights Dashboard – Power BI Project

## 📘 Project Overview  
This project focuses on building an advanced **Power BI dashboard solution** for analyzing bank loan data to support strategic decision-making, risk assessment, and operational efficiency. Traditional reports often lack interactivity and depth. This dashboard suite addresses those gaps by providing dynamic, drillable, and richly visualized insights into borrower demographics, lending trends, and loan performance.

The solution consists of **three interconnected dashboards**—**Executive Summary**, **Trends & Overview**, and **Detailed Insights**—designed with the goal of transforming raw loan data into actionable intelligence.

---

## 🧠 Problem Statement  
Despite having access to large volumes of loan data, many institutions fail to derive strategic value due to static and fragmented reporting methods. The objective of this project was to create a **centralized, interactive, and insightful dashboard** to analyze and visualize key loan performance metrics, borrower behavior, and financial indicators in real time.

---

## 🌟 Objective  
To craft a **multi-layered Power BI dashboard system** that offers:  
- Executive-level KPIs  
- Lending and demographic trends  
- Deep-dive drill-through analysis  
- Real-time monitoring via dynamic filters and DAX calculations  
- Segmentation by loan type, state, credit grade, and more  

---

## 📊 Dashboard Breakdown  
![image alt](https://github.com/pratikd2605/Power-BI-Bank-Loan/blob/48b87fb1c9161ddb3e9a869bdbca5a9c4923eb99/Bank_Summary.png)

### 🔹 Dashboard 1: Executive Summary  

**Purpose:**  
Provides an at-a-glance overview of loan operations using critical KPIs and performance breakdowns.

**Key Features:**  
- **Total Loan Applications**: 38.6K overall; 4.3K MTD  
- **Total Funded Amount**: $435.8M total; $54M MTD  
- **Total Received Amount**: $473.1M; $58.1M MTD  
- **Avg. Interest Rate**: 12.0% (MTD: 12.4%, MoM: +3.5%)  
- **Avg. Debt-to-Income Ratio (DTI)**: 13.3%  

**Loan Quality Split:**  
- **Good Loans**: 86.2% of total; $370.2M funded  
- **Bad Loans**: 13.8%; $65.5M funded  
- Comparison of application count, funding volume, and repayment for both categories

**Loan Status Breakdown Table:**  
- Fully Paid, Charged Off, Current  
- Associated totals for applications, funding, and received amounts  
- MTD and MoM changes  
- Avg. Interest and DTI across statuses  

---

### 🔹 Dashboard 2: Trends & Overview  
![image alt]
**Purpose:**  
Delivers exploratory visualizations for patterns in loan applications, borrower characteristics, and loan types.

**Key Visuals:**  
- **Loan Applications by Month** (Line Chart): Growth pattern, seasonal peaks  
- **Loan Applications by U.S. State** (Filled Map): Regional performance  
- **Loan Term Distribution** (Donut Chart): 36 vs 60 months  
- **Employment Length** (Bar Chart): Distribution of applicants' work history  
- **Loan Purpose** (Bar Chart): Debt consolidation, credit card, home improvement, etc.  
- **Home Ownership** (Tree Map): RENT vs MORTGAGE comparisons  

**Interactive Elements:**  
- Dynamic slicers for State, Loan Grade, Loan Type (Good vs Bad)  
- Global measure selector to update all visuals based on user choice (e.g., Total Applications, Total Funded Amount)

---

### 🔹 Dashboard 3: Detailed Insights  
![image alt]
**Purpose:**  
Provides granular, record-level data for in-depth exploration and validation.

**Features:**  
- Drill-through table showing fields such as:
  - Loan ID, Purpose, Home Ownership, Grade/Subgrade  
  - Funded Amount, Received Amount, Installment, Interest Rate  
  - Issued Date, Payment Status  
- Searchable and scrollable view of all 38.6K applications  
- Filter by borrower characteristics or loan status  
- Designed for underwriting audits and case-by-case reviews  

---
