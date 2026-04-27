# Financial Performance Analysis of Apple Inc. (2010–2025)

## 1. Problem & User
This project analyzes the long-term financial trends of Apple Inc. to evaluate its business growth, profitability, and asset expansion. The target users include finance learners and analysts interested in corporate financial performance.

## 2. Data
- Source: WRDS Compustat (comp.funda)
- Access date: 2026
- Key fields: fyear (fiscal year), sale (total revenue), ni (net income), at (total assets)

## 3. Methods
1. Connect to WRDS using Python wrds package
2. Extract Apple’s financial data via SQL query
3. Explore and summarize data using pandas
4. Analyze trend changes of key financial indicators
5. Export data to CSV for reproducibility

## 4. Key Findings
- Apple’s total revenue increased continuously and significantly from 2010 to 2025.
- Net income maintained stable growth and maintained strong profitability.
- Total assets expanded consistently, reflecting the company’s growing business scale.
- All three indicators showed healthy and sustainable long-term development.

## 5. How to run
1. Open the Jupyter Notebook file
2. Run cells sequentially to connect WRDS and extract data
3. A valid WRDS account is required for data querying

## 6. Product link / Demo
https://github.com/priere499/ACC102-Track2-DataAnalysis

## 7. Limitations & next steps
- Limitation: Only annual data is used; no quarterly or industry comparison.
- Next step: Add peer company comparison and financial ratio analysis for deeper insights.
