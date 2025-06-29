# KYC-Sentinel-Risk-Scoring-AML-Compliance-Dashboard

## 📌 **Project Overview**
This project simulates a **KYC risk scoring model** integrated with an **AML risk level analysis dashboard**. It classifies customer profiles into High, Medium, and Low risk categories based on their demographic, occupational, and adverse screening attributes to support compliance teams in proactive risk mitigation.

---
![Screenshot 2025-06-27 035438](https://github.com/user-attachments/assets/09d3f882-16bc-43ce-9442-260ee275efda)


## 🎯 **Objectives**
- Develop an automated **risk scoring formula** for customer risk classification.
- Visualize risk distribution through an **interactive Power BI dashboard**.
- Identify high-risk customers for Enhanced Due Diligence (EDD) and STR filing.

---

## 🗃 **Dataset Details**
- **Rows:** 1000 (simulated)
- **Columns:** Customer ID, Province, Age, Occupation, Employment Status, Source of Funds, PEP, Sanctions Watchlist Hit, Adverse Media, Previous STR Filed, Account Type, Monthly Transactions, Risk Score, Risk Level.
- **Source:** Self-created for academic and portfolio demonstration purposes.

---

## ⚙ **Methodology**
- Created a **nested IF formula** in Excel to assign risk scores:
  - +8 if Source of Funds is Crypto, Unknown, Gambling Proceeds
  - +10 if PEP = Yes
  - +5 if Occupation is Crypto Investor, Freelancer, Real Estate Agent, Import/Export Agent
  - +6 if Monthly Transactions > 20,000
  - +3 if Age <21 or >70
  - +10 if Sanctions Watchlist Hit = Yes
  - +5 if Adverse Media Found = Yes
  - +7 if Previous STR Filed = Yes

- **Risk Classification:** High, Medium, Low based on total score thresholds.

- Developed a **Power BI dashboard** featuring:
  - KPI cards (Total Customers, High-Risk Customers, STR Filed %)
  - Pie chart for Customer Distribution by Risk Level
  - Bar charts for Risk Level by Source of Funds and High-Risk Profiles by Province
  - Matrix for Province & PEP distribution
  - Scrollable Customer Details table
  - Interactive filters for occupation, province, source of funds, and account type.

---

## 📊 **Key Insights**
- 36 high-risk customers (3.6% of dataset)
- Crypto and Gambling Proceeds were the highest risk sources of funds.
- Manitoba and British Columbia had the highest concentration of high-risk profiles.

---

## 💡 **Recommendations**
- Conduct **EDD reviews** for all high-risk customers.
- Monitor medium-risk customers periodically for changes.
- Integrate the model into automated compliance systems for real-time detection.

---

## 🛠 **Tools & Skills Applied**
- Microsoft Excel (Nested IF, OR logic, Conditional Formatting)
- Power BI (Data modeling, DAX, interactive dashboard design)
- AML and KYC compliance knowledge

---



---

### ✨ **Connect with me on https://www.linkedin.com/in/theshubhamnaik/ for collaborations or feedback.**
