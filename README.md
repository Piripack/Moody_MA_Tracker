# Moody_MA_Tracker

Structured dataset of recent M&A deals to demonstrate **data research, validation, and multilingual processing** relevant to financial data roles.

## Overview
- Languages covered: **English (EN), Portuguese (PT), Spanish (ES)**
- Standardised fields: deal type, status, consideration, value, acquirer/target, sources, translation
- Tabs/files: Main dataset, QC documentation, Insights

## Preview (sample rows)
| Deal ID | Announcement Date | Deal Type     | Status    | Consideration | Value (USD) | Acquirer           | Target        | Source     |
|--------:|-------------------|---------------|-----------|---------------|------------:|--------------------|---------------|------------|
| ENG01   | 2025-08-25        | acquisition   | announced | mixed         | 18000000000 | Keurig Dr Pepper   | JDE Peet's    | Reuters    |
| ENG02   | 2025-08-25        | acquisition   | pending   | stock         | 3100000000  | Crescent Energy    | Vital Energy  | Reuters    |
| ENG03   | 2025-08-21        | take-private  | pending   | cash          | 12300000000 | Thoma Bravo        | Dayforce      | Reuters    |
| ENG04   | 2025-08-24        | acquisition   | announced | cash          | 2000000000  | Thoma Bravo        | Verint Systems| Reuters    |
| PT05    | 2025-07-29        | stake purchase| announced | undisclosed   | —           | iFood              | CRMBonus      | iFood rel. |
| PT01    | 2025-08-27        | acquisition   | pending   | cash          | 27000000    | VL Mineração       | Mosaic potash (Sergipe) | Estadão |
| ES01    | 2025-07-16        | acquisition   | announced | undisclosed   | 1700000000  | Prosus             | Despegar.com  | Reuters    |
| ES02    | 2025-07-16        | general trend | —         | —             | —           | —                  | —             | Expansión  |

> Full dataset includes additional EN/PT/ES entries with translations and QC fields.

## Files
- `Main_Dataset.xlsx` or `Main_Dataset.csv` — full table with all fields
- `QC_Documentation.csv` — column definitions and QC policy
- `Insights.csv` — summary stats (counts by language/status, largest deal)
- `Insights_Summary.pdf` — one-page overview for quick review

## Notes on sources
- Primary: **Reuters, company press releases**
- Regional PT/ES: **Estadão, Fusões & Aquisições, Expansión**
- Non-English items include a brief **English summary** in the dataset

## How to use
- Filter by `status` (announced/pending/completed)
- Group by `consideration_type` (cash/stock/mixed)
- Sort by `deal_value_amount` for top-deal snapshots

## Author
Andre Ramos • [LinkedIn](https://www.linkedin.com/in/awmr/)
