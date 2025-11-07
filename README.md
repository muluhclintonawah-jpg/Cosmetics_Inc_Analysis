 Cosmetics Inc. — Sales Analysis (Pivot & VLOOKUP)

**Project type:** Excel / Data cleaning / Pivot Tables / VLOOKUP  
**Purpose:** Demonstrate data-cleaning, lookups, and summarization skills using a practice dataset.

 About
This project cleans and analyzes a sample sales dataset (Cosmetics Inc.). The work shows how to:
- Clean the dataset (remove blanks, trim whitespace, standardize formats)
- Use **VLOOKUP** to map product codes to product names
- Create **Pivot Tables** to summarize total sales by client and by product
- Produce quick insights and visualizations

> **Note:** The original dataset was provided for educational practice. I do **not** claim ownership of the source material; this repository contains my cleaned and transformed files and the analysis I performed.

 Files
- `Cosmetics_Inc_Cleaned.xlsx` — cleaned spreadsheet with VLOOKUP and pivot tables (primary deliverable)
- `Cosmetics_Inc_Cleaned.csv` — exported CSV of cleaned data (data file for reproducibility)
- `screenshots/` — pivot table & chart screenshots
- `README.md` — this document
- `LICENSE` — license for this repo (MIT recommended)

 Key steps I performed
1. Removed rows with missing key fields and trimmed whitespace.
2. Standardized currency and numeric formats.
3. Created a lookup table for `Product Code → Product Name` and used `VLOOKUP()` to fill product names.
4. Built pivot tables summarizing total sales by Client and by Product.
5. Generated charts to highlight top products and top clients.

 Insights (example)
- Top client by total sales: *Candy's Beauty Supply* (example)
- Top product by revenue: *HealthyU Foundation* (example)

(Replace the example insights above with your final findings.)

 How to reproduce
1. Open `Cosmetics_Inc_Cleaned.xlsx` in Excel or Google Sheets.
2. Inspect the sheet named `CleanedData` for the cleaned table.
3. Go to the `PivotTables` sheet to see the pivot summaries and charts.


This project is licensed under the MIT License — see `LICENSE` for details.

