# Sales and Revenue Performance Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](data-sources)
- [Tools](tools)
- [Data Cleaning/Preparation](data-cleaning-preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Results/Findings](results-findings)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](references)

### Project Overview

This report provides a comprehensive analysis of sales performance across multiple dimensions, including geography, product, manufacturer, and time. Key insights and metrics are visualized to support data-driven decision-making.

### Data Sources

-	Sales Tables: Contains transactional sales data, including revenue, units sold, product IDs, dates, ZIP codes, and country information.

- Product Table: Provides product details such as product name, category (e.g., Urban), manufacturer ID, and price.

- Geo Table: Contains geographic details like ZIP, city, state, region, district, and country.

- Date Table: Supports time-based analysis with date hierarchies (year, month, etc.)

### Tools

- PowerBI- Data Cleaning, Analysis and Report

### Data Cleaning/Preparation 

The following tasks were carried out in the initial data preparation phase:

- Data which consists of Excel and CSV files were downloaded, inspected and imported into Power BI.
- The first row of each sheet were promoted to column headers to ensure proper field names.
- Columns were converted to appropriate data types (e.g., dates, numbers, text, currency) for accurate calculations and analysis.
- Tables with same headers were appended into a single table
- Unnecessary rows were removed
- New columns were created for analysis, such as concatenating country and ZIP to create unique zipcodes and extracting year and month from dates
- Checks were performed to identify and address missing or duplicate values, ensuring data integrity.
- Some columns (e.g., price) were split and transformed to extract usable values
- Relationships between tables (e.g., ProductID, CountryZip) were defined to enable multi-table analysis.
- Data was filtered and sorted as needed to focus on relevant records and improve report performance.

This process ensured that the data was clean, well-structured, and ready for accurate, insightful analysis in Power BI.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as 

- Total Revenue and Units Sold.
- Sales by Geography: Revenue and units sold by country.
- Sales by Product and Category: Breakdown of sales by product, product category (e.g., Urban), and manufacturer.
- Time-Based Trends: Revenue and units sold by year and month to identify seasonality or growth patterns.
- Customer/Market Reach: Number of unique cities (ZIPs) and countries served.
- Top Performing products

### Data Analysis

PowerBI

### Results/Findings

The Analysis results are summarised as follows:
1. Certain countries contribute significantly more to total revenue, indicating strong market presence in those areas.
2. Some manufacturers offer a wider range of products, and these often correlate with higher sales volumes.
4. Analysis identifies top-performing products and categories, as well as those with lower sales, providing opportunities for targeted improvement or investment
5. Year-over-year (YoY) analysis highlights consistent growth overtime
6. The number of unique cities (ZIP codes) served demonstrates broad market reach

### Recommendations

Based on the analysis, I recommend these actions:
- Invest in countries with the highest sales to further grow market share.
- Analyze factors driving success in these areas and replicate strategies in underperforming regions.
- Review products and regions with low sales to identify improvement opportunities.
- Consider targeted promotions, product adjustments, or market research to boost performance.
- Encourage manufacturers with fewer products to diversify their offerings, leveraging insights from top-performing manufacturers.
- Continue tracking revenue trends by year and month to quickly identify changes in demand or seasonality.
- Use these insights for inventory planning and promotional timing.
- Improve data quality by prioritising product categorisation to reduce uncategorised revenue from over 95% to an acceptable threshold.
- Standardise product and geographic definitions across all data sources.

  ### Limitations
  I had to fill in some empty columns after observing the required trend such as inclluding the column for the United States, I had to categorise the ZIP codes for each country due to their different formats. A significant number of the products were uncategorised hence affecting detailed insightsat the product- category analysis. There were other missing or incomplete data (e.g., blank city cells, Region and State) which reduced the level of insights that could be generated

### References
1. Microsoft. (2025). Power BI Documentation. Retrieved from: https://docs.microsoft.com/power-bi/
2. Microsoft Learn. (2025). Data Analysis and Visualization Best Practices. Retrieved from: https://learn.microsoft.com/power-bi/guidance/

