
# Takeaway Business Data Analysis Dashboard

This project involves developing a Power BI dashboard to analyse transactional data from a takeaway business. The primary objective is to generate actionable insights to drive strategic decision-making and enhance business performance.


## How to Use the Dashboard

1. Access the dashboard and dataset from [here](https://drive.google.com/drive/folders/1Zub-KxbnS79-cdNVbASx-3L4XcCiS55g?usp=sharing).
2. Download the `.pbix` file and dataset from the provided link.
3. Open the `.pbix` file in Power BI Desktop.
4. Explore the visualisations to gain insights into sales performance, product analysis and bundling recommendations.



## Dataset Description

The dataset includes:
1. **Orders Table**:
   - Contains transactional data with `deliverect_id` as the primary key.
2. **Line Items Table**:
   - Provides details on items ordered, grouped by `grandparent_id`.
  


## Stakeholder Requirements

The stakeholders requested a dashboard addressing the following:
   - Analyse key metrics such as sales, orders, discounts, and average order values.
   - Understand weekly trends and identify high-performing and low-performing locations.
   - Identify critical products contributing to sales.
   - Highlight underperforming products that may need to be removed from the menu.
   - Recommend products suitable for bundling.
   - Identify data-driven opportunities to improve sales and profitability.

## Dashboard Development 

1. **Trends and Performance**:
   - Weekly-level trend analysis of sales and orders.
   - Comparative metrics for site performance.

![Take_1](https://github.com/user-attachments/assets/95269d23-561a-45b5-8542-72114fefe313)

2. **Product Insights**:
   - Analysis of top-performing and underperforming products.
  
![Take_2](https://github.com/user-attachments/assets/4f10fa6e-8814-49a5-a764-ee1178587f76)

3. **Bundling Analysis**:

   - Pairing products based on historical data.

![Take_3](https://github.com/user-attachments/assets/13e020e7-5c1e-47ef-8ee2-c2f1d78234a5)

4. **Opportunities for Action**:
   - Highlighting strategies to optimise revenue and reduce inefficiencies.

## Measures

The following measures were implemented to meet the stakeholder objectives:

1. **Sales Metrics**:
   - **Total Sales**: Aggregation of revenue generated.
   - **Average Order Value (AOV)**: `Total Sales ÷ Total Orders`.

2. **Discount Metrics**:
   - **Discount Amount**: Total value of discounts applied.
   - **Discount Rate**: `(Discount Amount ÷ Total Sales) × 100`.

3. **Weekly Trends**:
   - **Week-on-Week Growth**: Change in sales/orders compared to the previous week.

4. **Product Analysis**:
   - **Product Contribution**: Percentage contribution of each product to total sales.
   - **Underperforming Products**: Products with low sales volume or high return rates.

5. **Bundle Analysis**:
   - **Bundle Suitability Score**: Products frequently purchased together.



## Insights

1. **Sales and Orders**:
   - The company has achieved 153K total orders with a total sales figure of £3.69M. The AOV (Average Order Value) stands at £24.06.
     
2. **Weekly Trends**:
   - Sales appear to follow a generally upward trend with a slight dip towards the end. This might indicate seasonality, external factors or promotional effects. Also, Total Sales and Total Discounts are positively correlated with each other. Total Sales and Total Discounts diverged the most when the Week was 7, when Total Sales were £441,056.73 higher than Total Discounts.

3. **Site Performance**:
   - Top Performing Sites: Sites like Site4, Site6, Site12 and Site13 are leading with sales above £180K. These sites are performing exceptionally well, contributing significantly to the total revenue.
     
4. **Underperforming Sites**:
   - Sites like Site610, Site152, Site63 and Site8 have the lowest sales figures, with Site8 bringing in £52K. These sites requires a closer analysis to understand the low performance, whether it's due to lower traffic, less effective promotions or any external factor.

5. **Underperforming Products**:
   - Items like Olive oil, Basil Pesto Sauce, Prawn and Nduja Ravioli, Gnocci, Spinach Fusilli and Giant Nocellara Olives and many more items are at the bottom part with sales around just £0 to £1560. These products may not be resonating well with the customer base.

6. **Popular Bundles**:
   - 'Ultimate' Lasagne and Spaghetti Carbonara bundles are the most frequently ordered, indicating a preference for these combinations. â€"Ultimate' Lasagne with Beef & Barolo RagÄ', Grana Padano Shavings accounted for 2.39% of Total Sales. 

7. **Price Strategy**:
   - The pricing for bundles should be based on the sum of the individual item prices, minus a small discount to incentivize the bundle purchase. This discount should be carefully calculated to maintain profitability.
     
## Recommendations

1. **Targeted Marketing**:
   - Consider running location-specific campaigns to boost their sales. Focus marketing efforts on top-selling items like Carbonara and ‘Ultimate' Lasagne with Beef & Barolo Ragù. Highlight these dishes in promotions, social media campaigns and special offers to further boost their sales.
     
2. **Site Comparison Analysis**:
   - Analyse top-performing sites like Site 4 to understand what drives their success. Implement these strategies at underperforming locations, such as enhancing customer service, optimizing product availability, and tailoring local promotions.

3. **Product Rationalization**:
   - Consider removing or rebranding the lowest-performing items. Increase visibility of successful bundles and experiment with bundling underperforming products with popular items to increase their sales.

4. **Dynamic Pricing**:
   - Use historical sales data to set dynamic bundle prices. If two items are frequently bought together but are also top sellers individually, offer a small discount when bundled to avoid cutting into profits.
  
5. **Tailor Discounts Strategically**:
   -  Review the discount strategy to ensure it supports profitability. Offer targeted discounts on lower-performing products to boost their sales without heavily discounting top sellers. Encourage customers to spend more by offering attractive bundles, upselling complementary items and implementing loyalty programs that reward higher spending.
  
6. **Leverage Customer Feedback**:
   - Collect and analyze customer feedback to identify areas for improvement, particularly in product offerings and service quality. Use insights to make data-driven adjustments that align with customer preferences.
  
7. **Introduce Personalized Menus by Region**:
   - Develop region-specific menus that cater to local tastes and preferences. Promote these personalized offerings with targeted discounts and special promotions, creating a more tailored and appealing experience for customers in different regions.

## License

This project is licensed under the MIT License.

