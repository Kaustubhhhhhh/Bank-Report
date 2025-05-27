# 🏦 Banking Analytics Dashboard

## 📌 Project Overview
The **Banking Analytics Dashboard** is a data visualization project developed in **Power BI**, aimed at uncovering insights from customer banking data. The dashboard assists banking institutions in understanding customer behavior, income segmentation, risk profiles, and product usage patterns to drive better financial decision-making.

## 📊 Key Features
- **Customer Demographics Analysis**: Age, gender, nationality, and occupation distributions.
- **Income Band Segmentation**: Classification of customers into low, mid, and high-income groups.
- **Account Summary**: Details about bank loans, deposits, checking and savings accounts.
- **Categorical Exploration**: Frequency analysis of variables like credit card usage, risk weighting, and loyalty tiers.
- **Heatmap Correlations**: Understand relationships between income, savings, loans, deposits, and credit balances.

## 🧮 Data Summary
- **Total Records**: 3,000 customers
- **Total Features**: 25 columns
- **Income Bands**:
  - Low: < $100,000
  - Mid: $100,000 - $300,000
  - High: > $300,000

### 💡 Main Variables Analyzed:
- Estimated Income
- Superannuation Savings
- Credit Card Balance
- Bank Loans
- Bank Deposits
- Loyalty Classification (Jade, Silver, Gold, Platinum)
- Fee Structure (High, Mid, Low)
- Risk Weighting (1 to 5 scale)
- Properties Owned

## 🔎 Insights Extracted
- Majority customers fall under **mid-income** bracket.
- **Credit Card usage** peaks with 1 card per customer.
- **Loyalty classification** is predominantly **Jade** followed by Silver and Gold.
- Strong positive correlation between **Estimated Income** and **Bank Deposits**.
- Customers with **more properties owned** and **lower risk weighting** show better financial performance.

## 📂 Project Files
| File Name            | Description                              |
|----------------------|------------------------------------------|
| `Bank Report.pbix`   | Power BI Dashboard Report File           |
| `Banking.csv`        | Source data used for building the report |
| `bank.pdf`           | EDA insights and Python analysis         |

## 🛠️ Tools Used
- **Power BI**: Data visualization and dashboard creation
- **Pandas & Seaborn**: Data analysis & plotting in Python (for EDA)
- **Matplotlib**: Additional chart visualizations

## 🧭 How to Use
1. Clone the repository.
2. Open `Bank Report.pbix` in Power BI Desktop.
3. Use filters and visuals to explore data interactively.
4. Refer to `bank.pdf` for Python-based data exploration.

## ✅ Conclusion
The **Banking Analytics Dashboard** offers a deep dive into customer financial profiles and behavior patterns. With both Python-based EDA and Power BI visuals, the dashboard provides a 360° view that can support credit risk assessment, product targeting, and strategic decision-making.

---

