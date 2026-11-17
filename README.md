
# Coca-Cola Sales Data Visualization

An Excel analysis of 2021 beverage sales, units sold, operating profit, and operating margin. The workbook uses PivotTables and charts to compare performance by month, region, retailer, and beverage brand.

## Project Goals

- Track monthly sales and unit-volume patterns.
- Compare sales across regions, retailers, and beverage brands.
- Review operating profit and average operating margin by brand and region.
- Identify areas for inventory planning and focused sales improvement.

## Dataset

The source data includes:

- Retailer and Retailer ID
- Invoice Date
- Region, State, and City
- Beverage Brand
- Price per Unit
- Units Sold
- Total Sales
- Operating Profit
- Operating Margin
- Month

## Dashboard Analyses

- **Sales by month:** Total sales summarized by month.
- **Sales by region:** Total sales compared across regions.
- **Sales by retailer:** Total sales compared across retailers.
- **Sales by brand:** Total sales compared across beverage brands.
- **Units sold by brand:** Total unit volume by beverage brand.
- **Price and volume by brand:** Average price per unit compared with average units sold.
- **Profitability by brand and region:** Operating profit summed and operating margin averaged.

## Key Findings

- The West is the largest sales region, with about **33%** of sales. The Midwest is the smallest, at about **13%**.
- Sodapop is the largest retailer, contributing about **51%** of sales. FizzySip contributes about **30%**.
- Coca-Cola is the top brand by sales and operating profit. It also has the highest unit volume in the brand summary.
- The visible monthly summary suggests stronger sales around mid-year and December, with softer periods earlier in the year and around September–October.
- The West has the highest regional operating profit, but its average operating margin is **33%**. The South has the highest average regional margin, at **41%**.
- Dasani Water has a high average price per unit and above-average unit volume. Powerade’s average unit volume is the lowest among the brands shown.

## Recommendations

- Plan inventory and delivery capacity for the West, Sodapop, and high-volume brands while monitoring retailer concentration.
- Review Midwest coverage and DreamCo sales to find opportunities to improve availability and retailer support.
- Investigate the West’s lower average margin and Diet Coke’s lower brand margin by reviewing pricing, discounts, product mix, and costs.
- Use targeted tests to grow lower-volume brands, and evaluate sales and margin together before extending promotions.
- Use monthly trends to guide replenishment, after validating the PivotTable totals.

## Metrics and Method

- **Total Sales:** Sum of sales amounts.
- **Units Sold:** Sum for total-volume charts; average for the price-and-volume comparison.
- **Operating Profit:** Sum of operating profit.
- **Operating Margin:** Average of the source-row margins in the profitability PivotTables.
- **Operating Margin formula:** `Operating Profit ÷ Total Sales`, formatted as a percentage.

An average of row-level margins may differ from a weighted overall margin. For a weighted margin, divide total operating profit by total sales.

## Reproducing the Analysis in Excel

1. Use the row containing the actual column names as the source header row. Exclude report titles and generic headers such as `Column1`.
2. Select the complete data range and insert a PivotTable.
3. Place the requested category field—such as Month, Region, Retailer, or Beverage Brand—in **Rows**.
4. Place the measure—such as Total Sales, Units Sold, or Operating Profit—in **Values**, and choose **Sum** or **Average** as specified above.
5. Insert a PivotChart and give it a descriptive title and axis labels.
6. Refresh the PivotTables after changing the source data.

## Data Validation

The monthly values visible in the workbook screenshot appear not to reconcile with the grand total shown in the other summaries. Refresh the PivotTables and check the source range and filters before relying on monthly comparisons.
