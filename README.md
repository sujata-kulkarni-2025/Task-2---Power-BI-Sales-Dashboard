# Task-2---Power-BI-Sales-Dashboard
Sales Dashboard

🔧 Data Transformation Tasks
1. Data Cleaning
Removing or handling:

Null/missing values

Duplicate records

Inconsistent formats (e.g., date, currency, decimals)

Standardizing country names, product names, etc.

2. Data Type Conversion
Ensuring correct data types:

Dates for time fields (e.g., invoice date)

Text for categorical data (e.g., product names, regions)

Numbers for financials (revenue, cost, profit)

3. Column Splitting & Merging
Splitting fields like Full Name into First Name and Last Name

Combining fields like City + State into a Location field if needed

4. Currency or Unit Conversion
If data from multiple countries is present, currency normalization to a single currency (e.g., USD) may be required

5. Calculated Columns & Measures
Creating custom fields like:

Profit = Revenue - Cost

Profit Margin = Profit / Revenue

Average Rating, Conversion Rate, etc.

6. Data Aggregation & Grouping
Summarizing:

Revenue by month, region, product, campaign

Profit by product category or channel

Creating totals and subtotals for different dimensions

7. Filtering & Row-Level Data Control
Removing:

Irrelevant time periods

Products with zero sales

Applying filters for a specific year (2022, 2023, 2024) as shown in the dashboard

8. Hierarchies & Relationships
Creating hierarchies:

Date → Quarter → Month

Region → Country

Defining relationships between tables: e.g.,

Product Table ↔ Sales Table

Campaign Table ↔ Sales Table

9. Data Enrichment
Adding:

Geographic metadata for country/region-based visualizations

External data like population or market share for benchmarking

10. Data Modeling
Designing star or snowflake schema in Power BI

Organizing tables into:

Fact tables (Sales, Revenue)

Dimension tables (Products, Customers, Regions)


🔷 High-Level Business Metrics
Metric	Value
Revenue	$2M
Cost	$1M
Profit	$354K
Avg Conversion Rate	17
Views	122K

Healthy Profit Margin: With $2M in revenue and $1M in cost, profit is at ~17.7%—a decent profitability level.

Conversion Rate (17) seems strong given the 122K views, indicating effective lead-to-sale performance.

📊 Trend Analysis: Current Month vs Previous Month
Revenue and Cost both show a declining trend from mid-year to December.

Suggests possible seasonality or reduced marketing/sales effectiveness in the later half.

May require a push during Q4 or promotions to counteract.

🌍 Geographic Revenue Insights
Top Revenue Regions:

Europe: $448K (27.33%)

Asia: $427K (26.03%)

North America: $389K (23.74%)

These three regions contribute over 77% of total revenue.

Growth Opportunity: South America (22.9%) slightly lags and might benefit from targeted campaigns.

🧾 Revenue by Sales Channel
Revenue is almost equally split:

Channel A: $1M (32.86%)

Channel B: $1M (67.14%)

Consider evaluating cost efficiency and conversion rates per channel.

💡 Lead Source Performance
Top Lead Sources:

Email: $0.38M

Referral: $0.34M

Cold Calling and Website are less effective.

Consider reallocating budget or optimizing lower-performing sources.

📣 Marketing Campaign Performance
Best Campaigns:

Spring Promo 2024: $0.36M

New Year Campaign: $0.33M

Other campaigns (Winter, Fall, Summer) are clustered around $0.32M.

Spring and New Year campaigns offer templates for future successful initiatives.

📦 Product-Level Insights
Top Products by Revenue:

Gaming Console Z: $1.33M

Monitor HD 24: $1.21M

VR Headset Pro: $1.16M

Top Profit Contributors:

Gaming Console Z: $28.5K

Soundbar 360: $25.8K

Drone Vision: $25.1K

Lowest Rated Products:

Laptop Pro 14 (4.81), Fitness Tracker X (4.95)

These may need review for quality, features, or customer satisfaction.

High Inventory Products:

Monitor HD 24 (271 in stock), Drone Vision (261)

Monitor stock levels to avoid overstocking risk or initiate clearance campaigns.
