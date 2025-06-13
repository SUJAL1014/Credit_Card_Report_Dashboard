# 💳 Credit Card Transaction Dashboard - Power BI

This Power BI dashboard project provides a comprehensive analysis of credit card transaction data. The dashboard offers insights into customer behavior, transaction types, revenue trends, and business performance across various demographics.

---

## 📊 Key Features

- **Revenue by Card Category** (Blue, Silver, Gold, Platinum)
- **Revenue Trends by Week** with WoW (%) growth
- **Revenue by Expense Type** (Fuel, Grocery, Travel, etc.)
- **Customer Analysis by:**
  - Education Level
  - Occupation (e.g., Businessman, White-collar, Govt)
  - Income Group (Low, Medium, High)
  - Age Group & Marital Status
- **Transaction Type Breakdown** (Swipe, Chip, Online)
- **State-wise Revenue Contribution**
- **Quarterly Performance Summary**

---

## 📁 Dataset

The dashboard is powered by a CSV file containing credit card transaction data with the following fields:

- `card_category`
- `revenue`
- `total_trans_ct`
- `interest_earned`
- `customer_job`
- `education_level`
- `income`
- `week_num`, `week_start_date`
- `age_group`, `marital_status`, etc.

> **Note**: The original dataset is anonymized for privacy purposes.

---

## 🧰 Tools Used

- **Power BI Desktop**
- Data Cleaning & Transformation using Power Query
- DAX Measures for KPIs and Time Intelligence
- Custom Visuals for dynamic insights

---

## 📈 Use Case

This dashboard is ideal for:

- Business Intelligence Analysts
- Marketing and Revenue Teams
- Financial Data Analysts
- Data Engineering Portfolios

---

## 🚀 How to Run

1. Clone this repository or download the `.pbix` file.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Ensure the CSV file is in the same directory, or re-map the data source inside Power BI.
4. Interact with the visuals and filters for in-depth analysis.
