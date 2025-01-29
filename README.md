# EDA-for-Lending-Club-Case-Study
# 🏦 Loan Default Risk Analysis

---

## 📄 Overview
This repository contains the **Loan Default Risk Analysis Case Study**, which aims to identify key factors influencing loan defaults. By leveraging **Exploratory Data Analysis (EDA)**, the project uncovers insights into borrower behavior, loan attributes, and their impact on credit risk. The findings can help optimize lending policies, reduce financial losses, and improve risk assessment frameworks.

---

## ❓ Problem Statement
Consumer finance companies face two key risks:
1. **💰 Revenue Loss** – Rejecting applicants who could have repaid the loan.
2. **📉 Financial Loss** – Approving loans to applicants likely to default.

### 🎯 Objective
- Analyze past loan applicant data to identify patterns and indicators of default.
- Develop actionable insights to minimize credit loss and optimize lending policies.

---

## 📊 Data Description
The dataset includes information on past loan applications, with details such as:
- **Loan Status**:
  - ✅ Fully Paid
  - 🕒 Current
  - ❌ Charged-Off (Defaulted)
- **Borrower Attributes**: Income, employment length, debt-to-income ratio, home ownership, etc.
- **Loan Attributes**: Loan amount, interest rate, term, installment, and credit grades.

---

## 🛠️ Key Steps
1. **🧹 Data Cleaning**:
   - Removed columns with all null values.
   - Handled partial null values through imputation or exclusion.
2. **⚙️ Feature Engineering**:
   - Created new features (e.g., ratios like loan-to-income and revolving balance-to-income).
3. **🔍 Exploratory Data Analysis (EDA)**:
   - Performed univariate and multivariate analysis to understand key drivers of default.
4. **📌 Insights & Recommendations**:
   - Identified actionable insights for minimizing credit loss and improving risk management.

---

## 📈 Key Insights

### 1. 🔑 Borrower Financial Profile
- **Loan-to-Income Ratio**:  
  - Applicants seeking loans exceeding **25% of their income** are more likely to default.
- **Debt-to-Income (DTI) Ratio**:  
  - Higher DTI values (**above 20%**) correlate with increased default risk.
- **Revolving Balance-to-Income Ratio**:  
  - Borrowers with a revolving balance over **20% of their income** are at higher risk.

### 2. 💳 Loan Parameters
- **Loan Amount**:  
  - Larger loan amounts (**$15,000–$25,000**) have higher default probabilities.
- **Interest Rate**:  
  - Fully paid loans cluster between **5% and 10%**, while defaults are more prevalent at rates above **15%**.
- **Installments**:  
  - Higher monthly payments correlate with increased defaults; manageable installments are critical.

### 3. 👤 Borrower Demographics
- **Employment Length**:  
  - Borrowers with **shorter or very long employment histories** are more likely to repay successfully.
  - Those with **2-6 years** of employment face higher default risks.
- **Home Ownership**:  
  - **Renters** show higher default rates compared to homeowners or mortgage holders.
- **Verification Status**:  
  - Loans without verification exhibit higher default risks.
- **Delinquency History**:  
  - Borrowers with **past delinquencies** are significantly more likely to default.

### 4. ⏳ Loan Duration and Credit Grades
- **Loan Duration**:  
  - **60-month loans** are riskier than 36-month loans.
- **Credit Grade**:  
  - Lower grades (D, E, F, G) show significantly higher default rates compared to higher grades (A, B, C).

---

## 💡 Recommendations
1. Implement stricter thresholds for **loan-to-income ratio**, **DTI**, and **revolving balance utilization**.
2. Adjust interest rates to better align with borrower risk profiles.
3. Promote shorter loan terms (**36 months**) to mitigate default risks.
4. Strengthen borrower verification processes.
5. Incorporate employment length, delinquency history, and credit grades into underwriting models.

---


