*****Advertising Performance Analysis*****

**Business Question:**  
- How have different advertising platforms performed across major states in different regions of the United States from January to October 2023, and how can we modify our marketing strategies for the next year based on this performance?

**Idea Development:**  
- The analysis aims to optimize marketing strategies by evaluating the performance of advertising platforms across regions and product categories. Insights into regional performance, product category trends, and advertising channel effectiveness will guide future marketing efforts.

**Data Collected:**  
- Sourced advertising platform sales data from Kaggle, and generated synthetic product data using ChatGPT. The primary focus was to utilize Excel for data cleaning, analysis, and dashboard creation.

## Dataset Description
The dataset contains sales data with the following columns:

- **Region**: The geographical region where the sales occurred. Possible values: `East`, `West`, `North`, `South`.
- **State**: The state where the sales occurred. Possible values: `New York`, `California`, `Illinois`, `Texas`.
- **Country**: The country where the sales occurred. Possible value: `United States`.
- **Product ID**: A unique identifier for each product.
- **Product Category**: The category of the product. There are 5 distinct categories.
- **Product Price**: The price per product.
- **Product Sold**: The quantity of the product sold.
- **Sales Date**: The date when the sales occurred.
- **Discount Offered**: The discount offered on the product.
- **Sales Channel**: The sales channel where the product was sold. Possible values: `instore`, `online`.
- **Total Sales**: The total sales amount, combining instore and online sales. Includes sales from the company website and other advertising platforms such as TV, Google Ads, Social Media, Influencer Marketing, and Affiliate Marketing.
- **Total Sales In-store Website**: The sales amount specifically from the company website.
- **Sales in Each Advertising Channel**: The sales amount from each advertising platform:
  - **TV**: Sales from TV advertising.
  - **Google Ads**: Sales from Google Ads.
  - **Social Media**: Sales from Social Media advertising.
  - **Influencer Marketing**: Sales from Influencer Marketing.
  - **Affiliate Marketing**: Sales from Affiliate Marketing.

**Data Cleaning Steps:**  
1. Formatted Headers: Centered and bolded column headers for better visibility.
2. Reorganized Columns: Prioritized category and product details.
3. Removed Duplicates: Eliminated duplicate rows.
4. Removed Blank Cells: Removed blank cells and shifted data up.
5. Checked Data Types: Ensured currency formatting for prices.
6. Identified Outliers: Flagged discounts greater than or equal to product price as outliers.

**Key Findings:**  
- Product Category Performance:
  - Decline in online sales for "Home & Kitchen" and "Sports."
- Regional Performance:
  - East: Significant decline in online sales.
  - South: Strong performance across channels.
  - North: Potential for strategy replication from South.
  - West: Good performance in specific categories.
- Advertising Platform Performance:
  - Consistent revenue generation; "Sports" outperformed "Home & Kitchen."

**Next Steps:**  
- Focus on Improvement: Enhance "Home & Kitchen" and "Sports" marketing strategies, especially in the East.
- Strategy Replication: Apply successful South strategies to the North.
- Region-Specific Strategies: Develop targeted marketing based on regional insights to optimize spend and increase sales.
