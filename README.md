# Procurement 360: Category Spend & Defect Analysis 📊

## 📌 Project Overview
This project is an end-to-end **Supply Chain & Procurement Analytics Dashboard** built in Power BI. The goal of this project is to provide executives with full visibility into procure-to-pay efficiency, supplier quality, and category spending using a relational Star Schema data model.

As a certified **Lean Six Sigma Yellow Belt**, I engineered this dashboard to specifically track **Defect Rates** alongside financial metrics to identify high-risk vendors and optimize supply chain operations.

## 🛠️ Technical Skills Demonstrated
* **Data Modeling:** Designed a robust Star Schema consisting of 1 Fact Table (`Fact_Procurement`) and 3 Dimension Tables (`Dim_Vendors`, `Dim_Materials`, `Dim_Calendar`).
* **Advanced DAX (Time Intelligence):** Engineered dynamic measures including `Total Spend`, `YoY Spend Growth %`, and `Total Spend Last Year` using `CALCULATE` and `SAMEPERIODLASTYEAR`.
* **Data Transformation (ETL):** Cleaned and transformed 10,000+ rows of raw procurement data using Power Query (handling nulls, data typing, and string extraction).
* **UI/UX Design:** Implemented an executive dark-mode theme with custom-styled interactive slicers, cross-filtering, and a combination chart to contrast financial spend against Six Sigma defect rates.

## 📈 Key Insights & Features
1. **Financial Tracking:** Real-time visibility into Year-over-Year (YoY) Spend Growth and total categorical invoice amounts.
2. **Vendor Quality (Six Sigma):** A custom Line and Clustered Column chart overlaying categorical spending with average defect rates to flag high-risk procurement areas.
3. **Interactive Slicing:** Users can slice the entire data model by Year or Geographic Region using custom-styled UI buttons.

## 📂 Repository Contents
* `Procurement_Project.pbit`: The Power BI Template file containing the complete Data Model, DAX measures, and Report UI.
* `Dashboard.pdf`: A high-resolution export of the final dashboard.
* The 3 raw `.csv` files used to build the data model.

## 🚀 How to Open
To interact with the dashboard, download the `.pbit` file and open it in Power BI Desktop. The file has been saved as a template to ensure a lightweight download footprint while preserving all DAX code and visual layouts.
