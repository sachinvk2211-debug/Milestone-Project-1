# Milestone-Project-1
Data analysis and Excel dashboard for 5,000+ smartphones.
# 📱 Mobile Market Intelligence: Price-to-Performance Analysis 

**Milestone Project 1**

## 🎯 Project Objective
With over 5,000+ smartphone models on the market, consumers and retailers struggle to evaluate true device value. The goal of this project is to decode the smartphone market and identify the **"Best Value"** models for any given budget by analyzing the relationship between price, hardware specifications (RAM, Battery), and brand performance.

## 📊 The Dashboard


## 🛠️ Tools & Technical Skills Used
This project was built entirely in **Advanced Microsoft Excel**, showcasing an end-to-end business intelligence workflow:
* **Data Extraction & Cleaning (ETL):** Used **Power Query** to clean messy raw CSV data, trim spaces, and split text columns (e.g., separating "8GB/128GB" into dedicated RAM and Storage columns).
* **Data Modeling:** Built a Relational Data Model (Star Schema) linking Fact and Dimension tables to handle complex many-to-many filtering.
* **Advanced Formulas:** Utilized `XLOOKUP`, `COUNTIFS`, `IFERROR`, and nested `IF` statements for custom segmentation (e.g., grouping phones into "Budget", "Mid-Range", and "Flagship" tiers).
* **Automation:** Wrote **VBA Macros** to create "Reset Filters" and "Refresh Data" buttons for a seamless user experience.
* **Predictive Forecasting:** Implemented Excel's **What-If Analysis** (Data Tables) to model revenue sensitivity based on dynamic pricing strategies.

## 💡 Key Market Insights
1. **The Market "Sweet Spot":** The data reveals a massive performance jump in the **₹20,000 - ₹30,000** price segment. Spending an extra ₹5,000 in this tier effectively doubles RAM capacity compared to the entry-level budget tier.
2. **The 5G Premium:** 5G-enabled devices command a measurable price premium over 4G counterparts with otherwise identical specs.
3. **Battery Optimization:** The ₹10,000 - ₹20,000 budget segment consistently offers the highest battery capacity (Average 5000mAh) per rupee spent.

## 🚀 How to Use the Dashboard
1. Download the `Project Mobiles.xlsm` file from this repository.
2. Open the file in Microsoft Excel (ensure Macros are enabled).
3. Use the **Slicer Panel** on the left to filter the market by Brand, Release Year, or RAM Size.
4. Review the dynamic "Price vs. Performance" charts to see what hardware is standard for your selected budget.

## 📂 Repository Contents
* `Project Mobiles.xlsm.xlsm`: The interactive Excel Dashboard (requires Macro enablement).
* `Mobile-market-intelligence-dashboard-2025.pptx`: Executive slide deck summarizing the findings.
* `Raw_Data.csv`: The initial, uncleaned dataset of 5,000+ mobile phones.
