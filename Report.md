# Analysis Report: E-Commerce Sales Performance & Profitability

## 1. Executive Summary

| KPI | Value |
|---|---|
| Total Sales | ₦2.55M |
| Total Profit | ₦1.05M |
| Profit Margin | ~41%* |
| Total Orders | 2,000 |

*\*Confirm this figure against the dashboard's "Profit Margin %" card before publishing — it should equal Total Profit ÷ Total Sales.*

![Dashboard Overview](images/dashboard-overview.png)
*Full dashboard export.*

---

## 2. Sales Performance Analysis

**Q: What is the total revenue and profit?**
Total revenue is ₦2.55M with ₦1.05M in profit.

**Q: How does sales trend over time?**
Sales are volatile month to month rather than steadily trending — swings of 20–50% between adjacent months are common, with no single sustained upward or downward direction across the full period.

**Q: Which period has the highest sales?**
March 2025 (₦107,588.86). The lowest month is October 2025 (₦38,467.82).

![Sales Trend](images/sales-trend.png)
*Total sales by month and year.*

---

## 3. Product Analysis

**Q: Which products generate the highest revenue?**
1. Portable Power Bank — ₦41,852.50
2. Shin Guards – Adult — ₦38,281.02
3. Men's Casual Sneakers — ₦35,489.62
4. Gaming Mechanical Keyboard — ₦34,699.83
5. Women's High Heels — ₦33,993.66

**Q: Which products have low profit margin?**
The weakest-margin products (min. 5 orders) are all running at a net loss: Adjustable Dumbbell Set (‑55% margin), Professional Jump Rope (‑34%), Wireless Bluetooth Earbuds (‑28%), Luxury Perfume Spray (‑26%), and Premium Blanket Throw (‑19%).

**Q: Are there loss-making products?**
Yes — 13 products post a negative total profit, led by Adjustable Dumbbell Set (‑₦7,209) and Professional Jump Rope (‑₦5,533). Notably, the Gaming Mechanical Keyboard is a top-5 revenue product but is still slightly loss-making overall (‑₦520), which flags it as a pricing/cost issue rather than a demand issue.

![Profit by Category](images/profit-by-category.png)
*Profit by product category.*

**Category takeaways:**
- Sports and Clothing generated the strongest sales — the company's leading categories.
- Sports carries the highest discount rate but still produces the highest profit, indicating strong underlying customer demand.
- Clothing underperforms relative to its sales volume, suggesting a margin issue worth investigating.

---

## 4. Customer Analysis

**Q: Who are the top 10 customers?**
See the ranked list below (by revenue).

![Top 10 Customers](images/top-customers.png)
*Top 10 customers by revenue.*

**Q: What is the average order value?**
Total Sales ÷ Total Orders = ₦2.55M ÷ 2,000 = **₦1,275 per order**.

**Q: Which customer segment contributes most revenue?**
Platinum-tier customers contribute the most (₦656,104), ahead of Bronze (₦529,272), Gold (₦517,622), and Silver (₦471,397). Notably Bronze slightly outpaces Gold, suggesting loyalty tier alone isn't a clean predictor of spend — worth a closer look at what's driving Bronze customers' revenue.

---

## 5. Regional Analysis

![Sales by Region](images/sales-by-region.png)
*Total sales by region.*

**Q: Which region generates the highest sales?**
North recorded the strongest sales performance and is the company's key market.

**Q: Which region has the lowest profitability?**
West showed weaker performance compared to the other regions.

**Q: Regional comparison summary**
North, South, and East are closely matched, while West trails all three by roughly half — a priority area for regional strategy.

---

## 6. Discount Impact Analysis

![Discount vs Profit](images/discount-vs-profit.png)
*Discount vs. profit by brand and category.*

**Q: Does higher discount increase sales?**
No — the correlation between discount and revenue is essentially zero to slightly negative (-0.11) across the dataset. Discounting isn't the lever driving higher sales here.

**Q: What is the relationship between discount and profit?**
Also weakly negative (-0.12). Sports carries the highest total discount volume of any category yet still delivers the highest profit — its profit is driven by strong underlying demand, not by the discounting.

**Q: Are discounts reducing profit margin overall?**
Slightly, but not meaningfully — the effect size is small. The bigger driver of margin is category: Sports (53% margin) and Home (45%) run far healthier than Electronics (25%), regardless of discount level.

---

## 7. Time Intelligence Analysis

**Year-to-Date (YTD) Sales:** 2023: ₦223,813 (partial year) · 2024: ₦1,093,912 (full year, the strongest) · 2025: ₦856,670 (through October).
**Month-over-Month (MoM) Growth:** Recent months have been choppy — July 2025 jumped +54% after two down months, only to give most of it back by October 2025 (-57%).
**Seasonal patterns:** No consistent holiday-season spike is evident; the highest month (March 2025) and lowest (October 2025) both fall outside the typical Nov–Dec retail peak, suggesting demand here is driven more by product/category cycles than calendar seasonality.

---

## 8. Profitability Analysis

**Q: What is the overall profit margin?**
40.9% (₦888,938 profit ÷ ₦2,174,395 revenue in the underlying dataset — reconcile this against the dashboard's own Profit Margin % card, since the dashboard's ₦ figures may reflect a filtered date range).

**Q: Which category has the highest margin?**
Sports, at 53.1% — well ahead of Home (45.1%), Beauty (41.9%), and Clothing (38.6%).

**Q: Which category is risky (low margin)?**
Electronics and Beauty generate the least profit of the five categories, with Clothing not far ahead of them — all three trail Sports and Home by a wide margin.

---

## 9. Business Interpretation & Recommendations

**1. What drives sales performance?**
Category mix and regional reach matter far more than discounting: Sports and Home combine strong revenue with the best margins, and North/South/East are all healthy markets. Discount level shows almost no relationship to either sales or profit.

**2. Are discounts helping or hurting profitability?**
Neither, meaningfully — the correlation between discount and profit is weakly negative (-0.12) and not a major factor. Margin differences are explained far more by category (53% for Sports vs. 25% for Electronics) than by how much is discounted.

**3. Which products or regions should the company focus on?**
Sports and Home (categories, on margin) and Portable Power Bank / Shin Guards / Men's Casual Sneakers (products, on revenue) are the strongest performers. Regionally, North, South, and East are all close and healthy; West is the clear outlier and needs investment.

**4. Where is the business losing money?**
13 individual products are net loss-making, led by Adjustable Dumbbell Set (‑₦7,209) and Professional Jump Rope (‑₦5,533) — both in categories that otherwise perform well, so this looks like a per-product cost or pricing problem rather than a category-wide one. Electronics as a whole also has the thinnest margin (25%) of any category, despite strong revenue.

**5. Recommended strategies:**
- Launch targeted marketing campaigns and strategic discount offers in the West region and the Clothing category to lift sales and engagement.
- Investigate why Clothing underperforms despite high overall category sales — review its cost structure and discount levels.
- Continue investing in Sports, which sustains high profit even at the highest discount rate — indicating strong price-insensitive demand.
- Use the North region's performance as a benchmark; assess what is working there (store type, product mix, customer base) and test replicating it in South, East, and especially West.

---

## Appendix: Data Sources

| Table | Rows | Key Fields |
|---|---|---|
| `Sales_Fact` | 2,000 | Sales_ID, Order_Date, Customer_ID, Product_ID, Store_ID, Quantity, Unit_Price, Discount, Payment_Type, Revenue |
| `Dim_Product` | 100 | Product_ID, Product_Name, Category, Sub_Category, Brand, Cost, Stock |
| `Dim_Store` | 20 | Store_ID, Store_Name, Region, City, Store_Type |
| `Dim_Customer` | 500 | Customer_ID, Name, Age, Gender, City, State, Country, Loyalty_Level, Order_Amt |
