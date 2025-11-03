Amazon Financial Performance Analysis (2021–2024)

Author: Sowmiya Jayaseelan  
Module: 7056ENG – Global Logistics Management  
Institution: Coventry University (UK)  
Date: November 2025  

Overview

⦁	This project presents a comprehensive financial analysis of Amazon (2021–2024) based on publicly available financial data from Yahoo Finance UK and the Amazon Investor Relations portal.  
⦁	The analysis evaluates Amazon’s financial performance, efficiency, and capital structure using key financial ratios and trend-based insights.  
⦁	It also explores how the financial accounts differ from management accounts and highlights potential sources of finance — including UK government logistics and innovation schemes — that could enhance operational performance and sustainability.

Project Objectives

1. Analyse Amazon’s performance (2021–2024) using profitability, liquidity, efficiency, and solvency ratios.  
2. Evaluate how financial accounts differ from management accounts in scope, purpose, and audience.  
3. Explore suitable sources of finance for improving logistics performance and sustainability.  
4. Demonstrate the use of management accounting tools to interpret performance and support decision-making.  
5. Communicate findings visually through professional charts and a 5-minute presentation.

Key Financial Metrics Analysed

| Metric | Formula | Purpose |
|:--------|:---------|:---------|
| Gross Profit Margin (%) | Gross Profit ÷ Revenue × 100 | Shows how efficiently Amazon converts revenue into profit before expenses. |
| Operating Margin (%) | EBIT ÷ Revenue × 100 | Measures operational efficiency before tax and interest. |
| Net Profit Margin (%) | Net Income ÷ Revenue × 100 | Indicates the percentage of profit generated from sales. |
| Current Ratio | Current Assets ÷ Current Liabilities | Tests short-term liquidity. |
| Debt-to-Equity Ratio | Total Liabilities ÷ Shareholders’ Equity | Evaluates leverage and financial stability. |
| ROA (%) | Net Income ÷ Total Assets × 100 | Measures profitability relative to assets. |
| ROE (%) | Net Income ÷ Shareholders’ Equity × 100 | Indicates shareholder returns. |
| ROCE (%) | EBIT ÷ (Total Assets − Current Liabilities) × 100 | Reflects overall capital efficiency. |

Methodology

The data were extracted from Yahoo Finance (UK) for Amazon’s:
⦁	Income Statement  
⦁	Balance Sheet  
⦁	Cash Flow Statement  

and verified against Amazon’s official annual reports (2021–2024).

The dataset was processed using Python (Pandas, NumPy, Matplotlib) in a Jupyter Notebook (`calculate_ratios.ipynb`), ensuring all ratios were recomputed from raw figures for accuracy and reproducibility.

Dataset Summary

Financial Ratio Trend Summary (2021–2024)

| Metric | 2021 | 2022 | 2023 | 2024 | Trend & Interpretation |
|:--|:--:|:--:|:--:|:--:|:--|
| Gross Profit Margin (%) | 42.04 | 43.81 | 47.00 | 48.85 | 📈 Consistent increase in profitability due to operational efficiency and scaling of AWS services. |
| Operating Margin (%) | 5.29 | 2.38 | 6.41 | 10.76 | 📈 Rebounded strongly post-2022, showing improved cost management and logistics automation. |
| Net Profit Margin (%) | 7.10 | 5.92 | 10.31 | 11.07 | 📈 Steady increase—reflects strong pricing strategy and efficiency in fulfillment operations. |
| Revenue Growth (%) | — | 9.41 | 11.83 | 10.99 | 📈 Stable double-digit growth, driven by Prime, AWS, and global retail expansion. |
| Current Ratio | 1.14 | 0.94 | 1.04 | 1.06 | ⚖️ Recovered after 2022 dip, indicating better liquidity and short-term financial stability. |
| Debt-to-Equity | 2.04 | 2.17 | 1.61 | 1.19 | 📉 Declining leverage shows stronger equity position and reduced reliance on debt. |
| Asset Turnover | 1.12 | 1.11 | 1.09 | 1.02 | 📉 Slight decline, possibly due to capital-intensive investments in logistics infrastructure. |
| ROA (%) | 7.94 | 6.58 | 11.22 | 11.30 | 📈 Profitability per asset improved as digital and physical assets became more productive. |
| ROE (%) | 24.13 | 20.84 | 29.35 | 24.69 | ⚖️ Healthy returns on equity; minor dip in 2024 from equity expansion. |
| ROCE (%) | 5.91 | 3.99 | 10.16 | 15.40 | 📈 Significant rise—reflects stronger capital efficiency and effective resource allocation. |

Summary:
⦁	Amazon maintained strong top-line growth while dramatically improving operational efficiency from 2022 to 2024.
⦁	Reduced leverage and better asset utilization reinforced its long-term financial sustainability.

Key Findings

- Profitability: Gross and operating margins steadily improved, driven by digital transformation and logistics automation.  
- Liquidity: Current ratio increased from 0.94 to 1.06, indicating stronger short-term solvency.  
- Leverage: Debt-to-equity declined from 2.17 to 1.19, showing reduced reliance on borrowed capital.  
- Efficiency: Asset turnover slightly declined, suggesting a shift toward higher capital investments (warehousing, AWS infrastructure).  
- Overall Performance: Amazon’s return ratios (ROA, ROE, ROCE) grew significantly, highlighting improved asset productivity and shareholder returns.

Financial vs Management Accounts

| Aspect | Financial Accounts | Management Accounts | Amazon Example |
|:--|:--|:--|:--|
| Purpose | External reporting for investors and regulators | Internal use for planning and control | Financial accounts show consolidated results; management accounts break performance down by AWS, retail, and Prime operations. |
| Nature | Historical and audited | Forward-looking and dynamic | Financials record past results; management uses rolling forecasts. |
| Detail Level | Aggregated totals | Highly detailed | Internal dashboards track KPIs per fulfillment centre. |
| Frequency | Annual or quarterly | Monthly or weekly | Quarterly reports vs daily performance dashboards. |
| Standards | IFRS / GAAP | No external standard | Financials follow GAAP; management reports follow internal KPIs. |

Sources of Finance and Strategic Impact

| Source | Type | Application | Impact |
|:--|:--|:--|:--|
| Retained Earnings | Internal | Fund digital logistics and automation | Strengthens efficiency without new debt |
| Equity Financing | External | Raise capital for sustainability & expansion | Expands base without raising leverage |
| Long-term Debt / Bonds | External | Finance logistics infrastructure & robotics | Enables large-scale investment |
| Leasing / Hire Purchase | Medium-term | Acquire fleets, drones, equipment | Maintains liquidity & flexibility |
| Trade Credit | Short-term | Manage cash flow | Supports operations during high demand |
| Green / ESG Bonds | External | Fund low-carbon logistics & electric fleets | Lowers cost of capital, enhances reputation |
| TRIG & Mode Shift Grants (UK DfT) | Public | Support logistics innovation & modal shift | Promotes sustainability and cost reduction |
| British Business Bank Programmes | Govt-backed | Provide finance for expansion & innovation | Strengthens capital for logistics growth |

📁 Repository Structure

amazon-financial-analysis-2021-2024/
│
├── data/
│ ├── amazon_financials_2021-2024.csv
│ ├── data_computed_ratios_2021-2024.csv
│ └── source_links.md
│
├── scripts/
│ ├── calculate_ratios.ipynb
│ └── amazon_financials_data.py
│
├── visuals/
│ ├── revenue_trend.png
│ ├── profitability_ratios.png
│ ├── financial_structure_flowchart.png
│ └── performance_summary_dashboard.png
│
├── slides/
│ └── Sowmiya_Amazon_Part2_7056ENG.pptx
│
├── README.md
├── LICENSE
└── .gitignore

Tools & Technologies

| Category | Tools Used |
|:--|:--|
| Data Analysis | Python, Pandas, NumPy |
| Visualization | Matplotlib |
| Documentation | Markdown, GitHub Pages |
| Presentation | PowerPoint (PPTX) |
| Data Source | Yahoo Finance UK, Amazon IR |
| Version Control | GitHub Repository |

Reproducibility

You can reproduce this analysis by:
1. Cloning the repository  
   ```bash
   git clone https://github.com/<username>/amazon-financial-analysis-2021-2024.git
2. Opening scripts/calculate_ratios.ipynb in Google Colab or Jupyter Notebook.
3. Running all cells sequentially.
4. Outputs (charts & CSVs) will regenerate automatically in the /visuals folder.

References

All data sources, academic references, and UK funding programmes are documented in
/data/source_links.md

Conclusion

Amazon’s financial trajectory (2021–2024) shows sustained revenue growth, improved capital efficiency, and strategic leverage reduction.
The analysis demonstrates how financial ratios, when combined with management accounting insights, provide a comprehensive view of performance.

Future outlook:

1.	Continued investment in AI-driven logistics, green fleets, and warehouse robotics will likely enhance profitability.
2. Potential adoption of UK sustainability-linked finance could reduce long-term operational costs and carbon footprint.

© 2025 Sowmiya Jayaseelan | Coventry University
License: MIT
