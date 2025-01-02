
# Takeaway Business Data Analysis Dashboard

This project involves developing a Power BI dashboard to analyze transactional data from a takeaway business. The primary objective is to generate actionable insights to drive strategic decision-making and enhance business performance.


## How to Use the Dashboard

1. Access the dashboard and dataset from [here](https://drive.google.com/drive/folders/1Zub-KxbnS79-cdNVbASx-3L4XcCiS55g?usp=sharing).
2. Download the `.pbix` file and dataset from the provided link.
3. Open the `.pbix` file in Power BI Desktop.
4. Explore the visuals to gain insights into sales performance, product analysis and bundling recommendations.

---

## Dataset Description

The dataset includes:
1. **Orders Table**:
   - Contains transactional data with `deliverect_id` as the primary key.
2. **Line Items Table**:
   - Provides details on items ordered, grouped by `grandparent_id`.
  
---

## Stakeholder Requirements

The stakeholders requested a dashboard addressing the following:

1. **Business Overview**:
   - Analyze key metrics such as sales, orders, discounts, and average order values.
   - Understand weekly trends and identify high-performing and low-performing locations.

2. **Product Evaluation**:
   - Identify critical products contributing to sales.
   - Highlight underperforming products that may need to be removed from the menu.

3. **Product Bundling**:
   - Recommend products suitable for bundling.

4. **Opportunities for Growth**:
   - Identify data-driven opportunities to improve sales and profitability.

---

## Dashboard Development and Measures

### Key Features
1. **Trends and Performance**:
   - Weekly-level trend analysis of sales and orders.
   - Comparative metrics for site performance.

2. **Product Insights**:
   - Analysis of top-performing and underperforming products.

3. **Bundling Analysis**:
   - Pairing products based on historical data.

4. **Opportunities for Action**:
   - Highlighting strategies to optimize revenue and reduce inefficiencies.

---

### Measures and Calculations

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

---

## Insights and Recommendations

1. **Focus on Popular Dishes**:
   - Concentrate marketing efforts on the top-selling dishes to maximize revenue and improve customer satisfaction.

2. **Optimize Underperforming Locations**:
   - Identify and support sites with below-average performance through targeted promotions or operational improvements.

3. **Streamline the Menu**:
   - Remove dishes with low sales to simplify the menu and improve operational efficiency.

4. **Introduce Bundles**:
   - Create value bundles based on popular combinations of dishes frequently ordered together.

5. **Leverage Weekly Patterns**:
   - Schedule promotions during high-traffic days and address slower days with targeted campaigns.

6. **Experiment with Pricing Strategies**:
   - Test competitive and value-based pricing for bundles to attract diverse customer segments.

---

## License

This project is licensed under the MIT License.

