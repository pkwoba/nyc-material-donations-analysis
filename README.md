# NYC Material Donations Analysis

## Project Overview

This project analyzes annual material donations reported by NYC Materials for the Arts from 2014 to 2025.

The goal is to understand how donor categories contribute to the total declared value of donated materials and how donation activity has changed over time.

## Tools Used

- Microsoft Excel
- Excel Tables
- PivotTables and PivotCharts
- Formulas and percentage calculations
- Data validation and exploratory analysis

## Key Findings

### 1. Donor Category Contributions

Business donors contributed 44.04% of the total declared value of donated materials, while Industry donors contributed 33.73%. Together, these categories accounted for 77.77% of the total declared material value.

### 2. Donation Count vs. Declared Material Value

Individual donors accounted for 38.62% of all recorded donations but contributed only 9.85% of the total declared material value.

In comparison, Business donors accounted for 33.63% of donations but contributed 44.04% of declared material value.

This shows that the donor category with the highest number of donations is not necessarily the category contributing the highest total material value.

### 3. Annual Donation Trends (2014–2025)

The number of recorded material donations increased from 2,445 in 2014 to a peak of 5,399 in 2019.

Between 2019 and 2020, recorded donations declined by approximately 80%, falling to 1,080.

Donation activity subsequently recovered, reaching 2,844 in 2025, but remained below the 2019 peak.

This trend highlights a significant change in donation activity over the reporting period.

## Data Preparation and Cleaning

The dataset contains 54 records across six columns, covering annual material donations from 2014 to 2025.

Data preparation was completed in Microsoft Excel:

- Preserved the original dataset in a `Raw_Data` worksheet.
- Created a separate `Working_Data` worksheet for analysis.
- Converted the working dataset into an Excel Table named `tbl_Donations`.
- Checked the declared material value column for missing and nonnumeric values.
- Confirmed there were no duplicate Year–Category combinations.
- Used PivotTables to summarize donations by donor category and year.

The dataset contains aggregated annual figures rather than individual donation transactions.

## Data Source

**Provider:** NYC Department of Cultural Affairs — Materials for the Arts (MFTA)

**Dataset:** Annual material donation statistics, 2014–2025

**Source platform:** NYC Open Data

The dataset reports annual material donations by donor category, including the number of distinct donors, number of donations, total donated weight in short tons, and total declared material value in US dollars.

**Data granularity:** One record per year and donor category.

**Important limitation:** Declared material value represents the reported value of donated goods, not cash fundraising revenue.

**Dataset link:** [DCLA Materials for the Arts Donor Information — Data.gov](https://catalog.data.gov/dataset/dcla-materials-for-the-arts-donor-information)

## Project Files

**`NYC_Material_Donations_Analysis.xlsx`** — Excel workbook containing:

- `Raw_Data` — Original dataset
- `Working_Data` — Prepared data and Excel Table
- `Summary` — Key performance indicators and analytical findings
- `Category_Summary` — Declared material value by donor category
- `Category_Chart` — Chart comparing donor categories
- `Donation_Count` — Donation counts and percentage shares
- `Yearly_Trends` — Annual donation PivotTable and line chart