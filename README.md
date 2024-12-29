# Retail Sales Performance and Profitability Analysis
In case the project file above returns an error, kindly click [HERE](https://nbviewer.org/github/abdulmumeen-abdullahi/Retail-Sales-Performance-and-Profitability-Analysis/blob/main/Retail%20Sales%20Performance%20and%20Profitability%20Analysis.ipynb).
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
1. Leverage the strong Sales-Profit correlation to prioritize strategies that increase overall sales.
2. Prioritize Standard Class Shipping, focusing on the high-margin Consumer segment in California, while strategically promoting Technology products and minimizing the impact of Furniture sales.
3. Re-evaluate discounting strategies, exploring alternative promotional methods to drive sales without significantly impacting profitability.
4. Conduct a thorough analysis of First Class Shipping costs and explore more cost-effective alternatives, potentially negotiating better rates for Standard Class shipments.
5. Implement predictive analytics for demand forecasting.

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

![download](https://github.com/user-attachments/assets/e901bf53-3017-41bc-aced-44b24ee29019)

- Texas demonstrated the least profit and sales margin.

![download](https://github.com/user-attachments/assets/c7201a33-b403-48fd-8975-def6bff8adab)

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

## Profitability by Segment
Home Office had the highest profitability of 14.29%

![download](https://github.com/user-attachments/assets/db7f2fd2-8e44-4f67-8ec3-66cf3569c7fd)

## Profitability by State
District of Columbia had the highest profitability of	42.20%

![download](https://github.com/user-attachments/assets/cf032463-bcb5-4afe-aaf2-49acb4d431c7)

## Profitability by Category
Technology had the highest profitability of	15.59%

![download](https://github.com/user-attachments/assets/01238db6-fc01-41a4-a9fe-26ac7286b690)

# 7. Correlation Analysis
The correlation heatmap reveals a strong positive correlation between Sales and Profit (0.35), indicating that as sales increase, profit generally increases as well. However, there's a negative correlation between Discount and Profit (-0.27), suggesting that higher discounts tend to be associated with lower profits. Quantity and Sales show a moderate positive correlation (0.25), while the relationship between Quantity and Profit is weaker (0.07).

![download](https://github.com/user-attachments/assets/62d01a06-b870-4e2a-b4d2-16651a41689d)

![download](https://github.com/user-attachments/assets/63a12e5e-0b27-4633-a2bc-e31e68d32738)

# 8. Conclusion
## 8.1 Recap of Key Findings
This analysis highlighted critical areas for improvement in sales and supply chain operations. Addressing these inefficiencies can improve profitability, customer satisfaction, and competitive positioning.

## 8.2 Limitations and Future Work
Limitations include a limited timeframe that might not capture seasonal trends or long-term market fluctuations, which could significantly impact sales and profitability. The data lacks crucial information such as competitor pricing, marketing campaigns, and economic conditions, which significantly influence sales and profitability. Future work could incorporate additional data sources and implement predictive analytics for demand forecasting.

# 9. Appendix
## 9.1 Data Dictionary
- Order Date: Date object, date when the order was placed.
- Ship Date: Date object, date when the order was shipped.
- Ship Mode: Categorical, shipping method used (e.g., Standard Class, Second Class, First Class, Same Day).
- Segment: Categorical, customer segment (e.g., Consumer, Corporate, Home Office).
- City: Categorical, city where the order was shipped.
- State: Categorical, state where the order was shipped.
- Category: Categorical, product category (e.g., Furniture, Office Supplies, Technology).
- Sub-Category: Categorical, specific product sub-category (e.g., Chairs, Phones, Binders).
- Returned: Categorical, indicates whether the order was returned (Yes/No).
- Sales: Numeric, total sales amount for the order.
- Quantity: Numeric, number of units ordered.
- Discount: Numeric, discount percentage applied to the order.
- Profit: Numeric, profit generated from the order.
- Profitability: Calculated, profit margin or profitability percentage (e.g., Profit / Sales).

## 9.2 Technical Details
Tools Used: Python, Pandas, Seaborn, Matplotlib, Scikit-learn.
