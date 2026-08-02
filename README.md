# SD-Bank-Financial-Analysis
# South Dakota Bank Financial Analysis
**Author:** Shimirimana Gerare | Finance Senior, University of South Dakota | May 2027

## Overview
This project analyzes the financial performance of all 56 active 
FDIC-insured banks in South Dakota using publicly available Call 
Report data from the FDIC API. The analysis examines asset size, 
profitability (ROA), and market concentration across the South 
Dakota banking landscape.

## Key Findings
- **56 active banks** analyzed across three size tiers: 
  17 Large (>$1B), 24 Mid-Size ($100M-$1B), 15 Community (<$100M)
- **Sioux Falls banks outperform** the rest of South Dakota 
  with average ROA of 1.54% vs 1.38% statewide
- **Pathward Financial** is the highest performing institution 
  in the state at 4.00% ROA — more than 3x the national 
  industry average of 1.26% (FDIC Q1 2026)
- **Fintech-oriented banks** (Pathward, The Bancorp) generate 
  ROA 2-3x higher than traditional community banks, driven by 
  fee-based revenue models vs traditional net interest income
- **Plains Commerce Bank** (internship employer) performs above 
  both the national average and Sioux Falls average at 1.59% ROA

## Visualizations
[Asset Size Chart]
[ROA Comparison]
[Size vs Profitability]

## Tools Used
- Python 3 | Pandas | Matplotlib | Requests
- Data Source: FDIC Call Report API (banks.data.fdic.gov)
- Data as of: Q1 2026

## Skills Demonstrated
- API data retrieval and JSON parsing
- Data cleaning and transformation with Pandas
- Financial ratio analysis (ROA, asset composition)
- Data visualization with Matplotlib
- Banking industry knowledge from Plains Commerce Bank internship

## Files
- `FDIC_Bank_Analysis.py` — main analysis script
- `sd_bank_assets.png` — top 15 SD banks by asset size
- `sd_bank_roa.png` — ROA comparison vs industry average  
- `sd_bank_scatter.png` — asset size vs profitability scatter plot
