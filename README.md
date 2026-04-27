# ACC102 Track 2 - GitHub Data Analysis Project
# Financial Performance Analysis of Apple Inc. (2010–2025)

## 1. Project Background & Research Questions
This project analyzes the long-term financial performance of Apple Inc. (AAPL) over the period 2010–2025 using Python and WRDS data. The analysis focuses on key financial indicators to evaluate the company’s business growth, profitability, and asset expansion.

### Core Research Questions
1. What is the trend of Apple’s total revenue (sales) from 2010 to 2025?
2. How has Apple’s net income changed during this period?
3. What pattern does Apple’s total assets show over the 16 years?
4. Can we observe consistent and healthy financial development from these indicators?

---

## 2. Dataset Information
- Data Source: WRDS Compustat (comp.funda)
- Access Date: 2026
- Company: Apple Inc. (Ticker: AAPL)
- Fiscal Years: 2010 – 2025
- Key Variables:
  - fyear: Fiscal year
  - sale: Total revenue
  - ni: Net income
  - at: Total assets

---

## 3. Tools & Workflow (Analysis Process)
### Tools Used
- Python (pandas)
- WRDS Database Connection
- SQL Query
- Jupyter Notebook
- GitHub

### Analysis Steps
1. Connect to WRDS using Python.
2. Write and run SQL to extract Apple’s annual financial data.
3. Load and inspect data using pandas (head, info, describe).
4. Analyze trends of sales, net income, and total assets.
5. Summarize findings and draw conclusions.

---

## 4. Key Results & Findings
1. **Total Revenue (sale)**
   - Revenue grew significantly and continuously from 2010 to 2025.
   - Apple’s main business maintained strong expansion over the long term.

2. **Net Income (ni)**
   - Net income increased steadily with revenue.
   - Profitability remained strong and stable throughout the period.

3. **Total Assets (at)**
   - Total assets grew consistently year by year.
   - Company size expanded healthily to support business growth.

---

## 5. Final Conclusion
Apple Inc. showed **excellent and stable financial performance** between 2010 and 2025. The company achieved continuous growth in revenue, net income, and total assets, indicating strong business strength, high profitability, and sustainable long-term development.

---

## 6. File Structure
- ACC102_Track2_WRDS_Analysis.ipynb  Main analysis code
- AAPL_WRDS_Financial_Data.csv       Extracted financial data
- README.md                          Project overview & results
