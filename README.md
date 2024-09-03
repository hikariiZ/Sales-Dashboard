# Sales Analysis
The sales analysis of a random company from 2016 to 2019. Tableau dashboard can be found [here](https://public.tableau.com/app/profile/xiujun.zha/viz/Salesdashboard_17252508821770/dashboard).

![Sales Dashboard](https://github.com/user-attachments/assets/2629c75f-a2a6-42c0-b650-9e795f89b371)

# Metrics and Dimensions
•**Sales**:The total revenue.

•**Return rate**: The percentage of products returned by customers relative to the total number of products sold. 

•**Profit margin**: The percentage of revenue that remains as profit after all costs have been deducted.(Porfit Margin = Profit/Sales)

**Average Order Value(AOV)**: The average amount of money spent by a customer per transaction.(AOV = Revenue/Number of orders)

•**Market**：Africa, APAC, Canada, EMEA, EU, LATAM, US

•**Ship mode**：First class, same day, second class, standard class

•**Segment**：Consumer, corporate, home office


# Summary of Insights
## Market:
• APAC has the highest sales volume ($3.5M) and Canada has the lowest sales volume ($66k)
• The overall return rate is 2.29%, with APAC and LATAM having the highest return rates of 2.69% and 2.90%. Notably, Africa and Canada have a return rate of 0%, which warrants further investigation to ensure data accuracy.
• Profit margin analysis reveals that EMEA and Africa have negative profit margins at -14.36%, suggesting possible operational inefficiencies. Conversely, Canada boasts the highest average profit margin at 24.75%.

## Ship mode：
• Sales across different shipping methods have shown a consistent upward trend, with a particularly sharp increase in Standard Class shipments in 2019, indicating a shift in customer preference or service availability.

## Segment:
• Corporate and Consumer segments show an increasing trend in sales, with Consumer leading the sales figures. Home Office shows lesser growth.

# Recommendations
• Data Verification: Investigate the completeness of return orders data, particularly for Africa and EMEA, to ensure that the 0% return rates are accurate and not due to missing data.

• Market Expansion in Canada: Given that Canada has the highest profit margin but the lowest sales volume, consider strategies to expand market presence in Canada to capitalize on its profitability.

• Negative Profit Margins in Africa and EMEA: Investigate the causes of negative profit margins in Africa and EMEA and analyze the impact of discounts on profitability.

• Post-2020 Data Collection: Collect and analyze data post-2020 to determine if the Home Office segment experienced growth due to the COVID-19 pandemic, which could suggest a lasting shift in market demand.

• Shipping Cost Analysis: Conduct a deeper analysis of shipping costs associated with different ship modes to understand their impact on profitability and customer satisfaction. This may reveal opportunities for optimizing shipping strategies.


# Data Structure
This dataset contains three tables: SalesRep, Orders, Returns.
![Screenshot 2024-09-03 at 22 51 44](https://github.com/user-attachments/assets/e9f5b8d1-173e-4dfd-aa6a-94bfa7187d1e)
