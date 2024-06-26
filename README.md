Business Question:

How have different advertising platforms performed across major states in different regions of the United States from January to October 2023, and how can we modify our marketing strategies for the next year based on this performance?

Idea Development:

The idea for this analysis originated from the need to optimize our marketing strategies for the upcoming year. By examining the performance of various advertising platforms across different regions and product categories, we can identify areas of strength and weakness. This analysis aims to provide insights into regional performance, product category trends, and the effectiveness of different advertising channels.

Data Collected:

The dataset includes the following columns:

Region
State
City
Country
Product ID
Product Category
Product Price
Product Sold
Sales Date
Discount Offered
Sales Channel
Total Sales
Outliers
Advertising Channels (TV, Google Ads, Social Media, Influencer Marketing, Affiliate Marketing)
Total Sales from Advertising Channels
Data Cleaning Steps:

Formatted Headers: Centered the column headers and made them bold for better visibility.
Reorganized Columns: Arranged the columns to display category details first, followed by product details.
Removed Duplicates: Used the "Remove Duplicates" feature to eliminate duplicate rows, resulting in the removal of one duplicate row.
Removed Blank Cells: Identified and removed blank cells using the following steps: CTRL+G > Special > Blanks > CTRL+- > Shift cells up.
Checked Data Types: Ensured that prices were formatted as currencies.
Identified Outliers: Created a new column named 'Outliers' to flag discounts greater than or equal to the product price.
Formula Used: IF($I2>=$F2,"Yes","No").
Added State Names: Created a new column to include respective state names for each region.
Formulas Used:
TRIM(CLEAN(W4))
INDEX($W$4:$W$7,MATCH([@Region],$V$4:$V$7,0))
Calculated In-Store and Website Sales: Created a new column (Total_sales_instore_website) to calculate total sales through in-store and company website channels.
Formula Used: IF([@[Sales_Channel]]="In-Store",[@[Total_sales]],[@[Total_sales]]-SUM($P2:$T2))
Key Findings:

Product Category Performance: Online sales for "Home & Kitchen" and "Sports" categories have declined.
Regional Performance:
East Region: Significant decline in online sales.
South Region: Strong performance across both sales channels. North region shows similar trends, suggesting potential for strategy replication.
West Region: Good performance in specific product categories.
Advertising Platform Performance:
Bottom 2 Products: Consistent revenue generation across platforms, with "Sports" outperforming "Home & Kitchen."
East Region: Lowest sales in the bottom two product categories online.
Next Steps:

Focus on Improvement: Prioritize enhancing marketing strategies for the "Home & Kitchen" and "Sports" categories, especially in the East region.
Strategy Replication: Apply successful South region strategies to the North region to boost performance.
Region-Specific Strategies: Develop targeted marketing efforts based on regional performance insights to optimize advertising spend and increase sales.
