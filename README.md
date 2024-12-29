# Retail Sales Performance and Profitability Analysis
# 1. Executive Summary
This project analyzed retail supply chain sales data to understand performance trends, profitability, and supply chain efficiency. The objective was to derive actionable insights to enhance sales, optimize profitability, and improve supply chain operations.

## Key Findings:

- Sales increase massively from 2015 to 2017, as does profit.
- Standard Class Ship Mode demonstrated the highest profit and sales margin while First Class demonstrated the opposite.
- Consumer Segment demonstrated the highest profit and sales margin while Home Office demonstrated the opposite.
- California State demonstrated the highest profit and sales margin while Texas demonstrated the opposite.
- Technology Category demonstrated the highest profit and sales margin while Furniture demonstrated the opposite.
- Discount strategies demonstrated a weak negative correlation with sales.

## Recommendations:
1. Prioritize Standard Class Shipping, focusing on the high-margin Consumer segment in California, while strategically promoting Technology products and minimizing the impact of Furniture sales.
2. Re-evaluate discounting strategies, exploring alternative promotional methods to drive sales without significantly impacting profitability.
3. Conduct a thorough analysis of First Class Shipping costs and explore more cost-effective alternatives, potentially negotiating better rates for Standard Class shipments.

# 2. Introduction
## Background
The retail industry heavily relies on efficient supply chain management to maintain competitive advantage, ensure customer satisfaction, and maximize profitability. Supply chain inefficiencies can result in lost sales, increased costs, and reduced market share.

## Objectives
- To understand sales trends and identify underperforming segments.
- To analyze profitability across regions, product categories, and customer segments.
- To assess supply chain performance and identify optimization opportunities.

## Data Sources and Limitations
The dataset includes transactional data such as sales, profit, discount rates, shipping modes, and inventory levels. Limitations include a short timeframe, a lack of detailed customer-level information, and the absence of external factors such as competitive analysis, potentially limiting a comprehensive understanding of market dynamics.

# 3. Data Exploration and Preparation
## Data Overview
-> Extracted Columns: Order Date, Ship Date, Ship Mode, Segment, City, State, Category, Sub-Category, Returned, Sales, Quantity, Discount, Profit
-> Sample Size: Approximately 10,000 transactions.
-> Summary Statistics:
- Average Sales: $X
- Average Profit: $Y
- Standard Deviation in Discounts: Z%

## Data Cleaning and Transformation
- The needed columns were extracted.
- The distribution of numerical features were visualized.

![download](https://github.com/user-attachments/assets/c27a9ff6-e17f-4d35-8a6a-c1bc7a9c1f71)

- Outliers in sales values were identified and capped to prevent skewing.
- Order Date values were converted to datetime format.

# 4. Sales and Profit Performance Analysis
## Sales and Profit Trends
Sales increase massively from 2015 to 2017, as does profit.

![download](https://github.com/user-attachments/assets/cfef19a1-b858-46e5-8d66-6669e8a5868a)

## Sales and Profit by Segment
- Consumer segment accounted for 50.1% of total sales and 42.2% of total profit.

![download](https://github.com/user-attachments/assets/409b34c0-c1e5-4e07-975d-c31a83d124a3)

- Corporate segment demonstrated consistent year-round performance with average percentage sales of 34.2%.

![download](https://github.com/user-attachments/assets/50294adc-8cf4-4b2a-8dcb-f8df2a502c4b)

## Sales and Profit by Product Category
Technology products were the average top-selling category.

![download](https://github.com/user-attachments/assets/5fa12b0a-eb7e-4fe5-a253-88203c10d050)

- Furniture had the highest sales over the years.

![download](https://github.com/user-attachments/assets/493a8e3b-ba4a-4a7c-96b7-103ce5a41abe)

## Sales and Profit by State
- California State demonstrated the highest profit and sales margin.

![download](https://github.com/user-attachments/assets/613dd4fb-c24e-49d3-b657-28bd1db159d5)

- Texas demonstrated the least profit and sales margin.
![download](https://github.com/user-attachments/assets/cb7716f7-9851-4523-8f4e-df0da7213e03)

## Sales and Profit by Ship Mode
- Standard Class demonstrated the highest total profit and sales margin.

![download](https://github.com/user-attachments/assets/ba48c56a-32bf-4c74-8974-974784d85e28)

- Second Class demonstrated the highest average profit and sales margin.

![download](https://github.com/user-attachments/assets/b2d4a707-55de-48b3-990f-5ebbe580a022)

# 5. Return Rate Distribution
The business experienced a return rate of 8%, with 799 out of the 9979 orders placed returned.

![download](https://github.com/user-attachments/assets/d5e049bc-a3fb-4981-81c8-51f416d13ad4)

# 6. Profitability Analysis
## Profitability by Ship Mode
Second Class Ship Mode had the highest profitability of 15.02%

![download](https://github.com/user-attachments/assets/9bf30cdf-0fe8-4ac1-970b-4c3c9ecf5a83)






