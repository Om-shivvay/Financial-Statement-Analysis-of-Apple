# Apple Inc. — Financial Statement Analysis (FY2021–FY2025)

**Tools used:** Advanced Excel (Power Query, formula-driven ratio models) · Power BI (interactive dashboard)
**Data source:** Apple Inc. Form 10-K filings, SEC EDGAR (CIK 0000320193)

---

## Project Summary

This project analyzes Apple Inc.'s financial performance over a 5-year period (FY2021–FY2025) using data pulled directly from the company's SEC 10-K filings. The workflow spans data collection, ratio modeling, and dashboard visualization — covering liquidity, profitability, leverage, efficiency, and cash flow health.

## Methodology

1. **Data Collection** — Consolidated Income Statement, Balance Sheet, and Cash Flow Statement line items into a structured Excel workbook, one column per fiscal year.
2. **Ratio Analysis** — Built 13 formula-driven ratios across 5 categories, each referencing raw data directly (fully auditable, no hardcoded results).
3. **Data Modeling** — Restructured the ratio and statement data into a flat table (Year, Statement, Metric, Value) to support Power BI's data model.
4. **Dashboarding** — Designed a 4-page interactive Power BI report: Overview, Profitability, Liquidity & Solvency, and Cash Flow Health.

## Key Findings

**Revenue & Profitability**
- Revenue grew from $365.8B (FY21) to $416.2B (FY25) — a ~3.3% 4-year CAGR, with a dip in FY23 followed by recovery.
- Gross margin expanded steadily from 41.8% to 46.9%, driven largely by Apple's growing Services mix.
- Net margin held in a tight 24–27% band throughout the period, reflecting consistent operating discipline despite revenue fluctuations.

**Balance Sheet & Leverage**
- Return on Equity ranged from 150% to 197% — unusually high, driven by Apple's aggressive share buyback program shrinking the equity base rather than by profitability alone.
- Debt-to-Equity ranged from 3.9x to 6.0x, reflecting Apple's reliance on debt-funded capital returns over retained equity.
- Current ratio stayed near or below 1.0x (0.87x–1.07x) — Apple runs lean on working capital, leaning on strong operating cash generation instead of maintaining large liquidity buffers.

**Cash Flow**
- Free Cash Flow remained strong and stable throughout, ranging from $93B to $111B annually, even in the year (FY24) when net income dipped.
- Financing cash flow was consistently and heavily negative (~$93B–$122B per year), reflecting sustained share buybacks and dividend payouts.
- FCF margin held around 24–28% of revenue across all 5 years — a sign of durable cash conversion.

## Interpretation

Apple's financial profile over this period reflects a mature, cash-generative business prioritizing shareholder returns (buybacks, dividends) over balance-sheet conservatism. The high ROE and elevated leverage ratios are not signs of financial distress — they reflect a deliberate capital structure choice, evidenced by consistently strong free cash flow and healthy margins throughout the period.

## Dashboard Structure

| Page | Focus |
|---|---|
| Overview | Revenue/Net Income trend, key FY25 KPIs (Revenue, Net Margin, ROE, Current Ratio) |
| Profitability | Gross/Operating/Net margin trends, R&D vs SG&A spend |
| Liquidity & Solvency | Current Ratio & Debt-to-Equity trend, Assets/Liabilities/Equity composition |
| Cash Flow Health | Operating/Investing/Financing CF by year, Free Cash Flow trend, FCF margin |

---
*Prepared by Sri Sai Samarth Sistla as part of a financial analyst portfolio project.*
