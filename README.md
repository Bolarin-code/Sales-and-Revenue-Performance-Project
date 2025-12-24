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
---
This report provides a comprehensive analysis of sales performance across multiple dimensions, including geography, product, manufacturer, and time. Key insights and metrics are visualized to support data-driven decision-making.

<img width="1112" height="744" alt="Sales and Revenue PowerBi Analysis Dashboard" src="https://github.com/user-attachments/assets/dcf336ea-fec7-4d43-96a4-a5ee7be862c0" />

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
- Relationships between tables (e.g., Date tables, Unique CountryZip) were defined to enable multi-table analysis.
- Data was filtered and sorted as needed to focus on relevant records and improve report performance.

This process ensured that the data was clean, well-structured, and ready for accurate, insightful analysis in Power BI.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as 

- Total Revenue.
- Total number of Products.
- Total number of Manufactures.
- % of Urban Revenue.
- Number of countries
- Total number of cities.
- Revenue trend by year and month.
- Top 5 Manufacturers By Revenue.
- Top 10 Products By Revenue.
- Total Revenue By category.
- Total Revenue By Country.
- Segment, Revenue, and a Sparkline of revenue by product (Table Visual).

### Data Analysis

PowerBI

### Results/Findings

The Analysis results are summarised as follows:
1. The business operates on a significant scale, generating $2.84 billion in total revenue across five countries, 146,000 cities, 14 manufacturer, and over 2,412 products. Performance remains robust, with $471.4 million delivered year-to-date indicating sustained growth momentum
2. Revenue distribution is uneven; key markets like the US and Australia drive the bulk of revenue, while other countries contribute less. One manufacturer accounts for over $1.25 billion, creating dependency, and a small group of high-performing products drives a large revenue share. Some manufacturers offer a wider range of products, and these often correlate with higher sales volumes.
3. Urban revenue accounts for only 4.04% of total sales, suggesting either untapped potential or a need to redefine urban markets. Additionally, 95.21% of revenue is considered uncategorized, limiting product mix visibility and highlighting a need for better data governance.
4. The business shows strong growth and has opportunities to reduce reliance on key markets and partners, improve data quality, and drive growth via focused geographic, supplier, and product strategies.
5. Analysis identifies top-performing products providing opportunities for targeted improvement or investment.
6. Year-over-year (YoY) analysis highlights consistent growth overtime
7. The number of unique (ZIP codes)-146,000 demonstrates broad market reach

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
  Filling some empty columns after observing the required trend such as filling county column for the United States, Challenges with the ZIP codes for each country due to their different formats hence affected proper selection of data type. A significant number of the products were uncategorised hence affecting detailed insight sat the product- category analysis. There were other missing or incomplete data (e.g., blank city cells, Region and State) which reduced the level of insights that could be generated.

### References
1. Microsoft. (2025). Power BI Documentation. Retrieved from: https://docs.microsoft.com/power-bi/
2. Microsoft Learn. (2025). Data Analysis and Visualization Best Practices. Retrieved from: https://learn.microsoft.com/power-bi/guidance/



