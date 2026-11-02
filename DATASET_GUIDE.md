# Dataset guide and provenance

This repository includes datasets that match the field requirements in the BAIL504 lab manual. **Read the labels below before interpreting results.** The manual names some datasets but does not attach the actual files, so exact classroom data cannot be guaranteed.

| Manual program | Repository file | Data status | Notes |
|---|---|---|---|
| 1 & 3 — Video game sales | `Data/Video-Games/vgsales_practice.csv` | Small synthetic practice sample | Matches the manual's required columns (Rank, Name, Platform, Year, Genre, Publisher, regional sales and Global_Sales). It is not the full Kaggle/VGChartz file. The manual points to `vgsales.csv`; a commonly used public version is the Kaggle Video Game Sales dataset by Gregory Smith: https://www.kaggle.com/datasets/gregorut/videogamesales |
| 2 — Tableau joins | `Data/Tableau-Joins/*.csv` | Synthetic practice tables | Three tables (Demographics, Salary, Job Title) with EmployeeID keys, matching the manual's Excel workbook structure. |
| 9 — Revenue/Sales | `Data/Revenue-Sales/revenue_sales_practice.csv` | Synthetic practice dataset | Fields are tailored to the manual's state map, monthly line chart, age bins, region donut and gender-by-category butterfly chart. |
| 10 — GDP | `Data/GDP/gdp_selected_countries.csv` | Publicly sourced dataset extract | Country/year/value series for countries and regions named in the exercise. Source repository: https://github.com/datasets/gdp (verify the source metadata and indicator before citing values in formal work). |
| 11 — HR | `Data/HR/IBM_HR_Analytics.csv` | Public sample dataset | IBM HR Analytics Employee Attrition & Performance sample. Source repository: https://github.com/shantanu1109/IBM-HR-Analytics-Employee-Attrition-and-Performance-Prediction |
| 12 — Amazon Prime | `Data/Amazon-Prime/amazon_prime_titles_practice.csv` | Synthetic schema-compatible practice sample | Includes the fields needed by the manual (type, title, country, release_year, listed_in/genre and description). Rows are synthetic, not actual Amazon catalogue listings. |

## Why some files are synthetic

The manual references `Tableau Joins File.xlsx`, a Revenue/Sales dataset, and an Amazon Prime CSV without embedding those original data files. Rather than presenting invented records as college-provided data, this repository labels practice data as synthetic. The GDP and HR files are public-source extracts/samples; review their upstream metadata before using them in assessed submissions.

## Recommended next step for exact lab matching

If your faculty later shares their original files, replace the matching practice CSVs with those exact files, keep the same field names used in the manual, and rebuild the workbook/report against those files. That is the only way to guarantee the same numbers and screenshots as the classroom output.
