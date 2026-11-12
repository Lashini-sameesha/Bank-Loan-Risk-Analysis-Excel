# Bank Loan Risk Analysis (Excel)

Cleaning and analysis of a 1,000-row bank loan dataset using Excel.

## What I did
1. **Data cleaning (Power Query)**
   - Removed 10 duplicate loans (1,000 → 990 rows)
   - Fixed data types, trimmed text, standardised capitalisation
   - Filled missing text values with "Unknown"
   - Filled missing interest rate and income with the median
   - Removed 13 rows with missing Loan_Date or Loan_Amount (977 rows final)
2. **Lookups:** VLOOKUP and XLOOKUP practice
3. **Analysis:** Pivot Tables and PivotCharts
4. **Dashboard:** KPI cards, charts and slicers (Year, Branch, Loan Type)

## Key findings
- 977 loans, total LKR 2.69bn
- Overdue rate 26.9%, High risk 32.0%
- High-risk loans: 45% overdue vs 10% for low-risk
- Personal loans have the highest average interest rate (12.49%)

## Tools
Excel, Power Query, Pivot Tables, XLOOKUP/VLOOKUP
