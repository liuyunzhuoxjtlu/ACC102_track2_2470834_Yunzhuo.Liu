# ACC102 Track 2: Investment Portfolio Analysis for Retail Investors
## 1. Problem Definition & Target User
This project aims to provide a **data-driven, low-risk investment portfolio strategy** for **retail investors (parents)** with limited financial knowledge, low-to-medium risk tolerance, and a preference for stable long‑term returns. The project focuses on four complementary Chinese A‑share companies in the energy and resource industrial chain.

## 2. Data Description
- Source: Yahoo Finance
- Access Date: 2026-04-19
- Period: 2020–2024 annual financial data
- Key Variables:
  Gross Profit Margin, Net Profit Margin, ROE, Debt Ratio, Current Ratio, Revenue Growth, Net Income Growth, PE, PB

## 3. Python Workflow & Implementation
1. Data extraction using `yfinance`
2. Data cleaning, missing value handling, and outlier filtering with `pandas`
3. Descriptive analysis and multi-year trend analysis
4. Financial ratio calculation and cross-company comparison
5. Comprehensive scoring model (Profitability 40%, Risk 30%, Growth 30%)
6. Visualization with `matplotlib`
7. Automated output of Excel results and investment allocation strategy

## 4. Key Findings & Insights
- Jereh Group (002353.SZ) achieves the **highest total score (8.02)** with stable profitability and low financial risk.
- Tianqi Lithium (002466.SZ) shows high gross margin but faces strong cyclical volatility and negative growth in recent years.
- CITIC Metal (601061.SH) provides stable risk control but relatively weak profitability.
- The four companies cover oil equipment, lithium resources, photovoltaic, and metal trading, offering strong sector diversification.

## 5. Investment Strategy (Total Principal: 100,000 RMB)
- 002353.SZ: 35.63% → ¥35,626
- 601012.SH: 27.91% → ¥27,908
- 002466.SZ: 24.51% → ¥24,512
- 601061.SH: 11.95% → ¥11,953

## 6. Files in Repository
- `ACC102.ipynb`: Full Python analysis notebook
- `yahoo_4stocks_2020_2024_clean.xlsx`: Cleaned financial dataset
- `investment_scoring_portfolio.xlsx`: Score results and investment allocation
- `financial_trend_charts.png`: 5-year trend charts
- `cross_company_comparison.png`: Latest-year comparison chart
- `requirements.txt`: Package dependencies

## 7. How to Run
1. Install required packages:
   pandas, numpy, yfinance, matplotlib, openpyxl
2. Run the Jupyter notebook sequentially
3. All charts and Excel files will be generated automatically

## 8. Demo Video
- Demo Video Link:https://github.com/liuyunzhuoxjtlu/ACC102_track2_2470834_Yunzhuo.Liu/blob/main/ACC102%20Video.mp4

## 9. Limitations & Next Steps
- Limitations: Only annual data is used; macroeconomic and policy factors are not included.
- Next steps: Incorporate quarterly data, add industry benchmark comparisons, and optimize the scoring model.

## 10. AI Disclosure
AI tools were used to assist code debugging and report writing. All code, analysis, and results were independently run, checked, and verified by the student.
