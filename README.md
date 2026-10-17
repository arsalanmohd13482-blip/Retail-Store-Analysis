# Retail Analytics: Business Performance & Growth Strategy

**Turning retail transaction data into actionable business decisions using Databricks SQL and Power BI.**

## 📌 Project Overview

Retail businesses generate large volumes of transaction, product, store, and customer data. However, understanding whether growth is sustainable, which markets drive performance, what customers value, and where operational improvements are needed requires more than tracking total sales.

This project analyses an Indian multi-format Fast-Moving Consumer Goods (FMCG) retail chain to understand its business performance, identify growth opportunities, evaluate customer engagement, and translate analytical findings into practical business recommendations.

The analysis covers **January 2025 to May 2026**, examining revenue growth, like-for-like performance, regional and store-format differences, product and category performance, customer loyalty, and purchasing behaviour.

Using **Databricks SQL for data preparation and Power BI for business analysis**, the project follows an end-to-end analytics approach, connecting business data to measurable insights and decision-oriented recommendations.

## 🏢 Business Context

The business represents an Indian FMCG retail chain operating across multiple cities, regions, and store formats.

| Business Dimension | Description |
|---|---|
| Industry | FMCG Retail |
| Geography | 21 cities across 5 Indian regions |
| Store Formats | Supermarket, Express, and Fresh |
| Product Departments | 7 departments, from Grocery & Staples to Electronics & Accessories |
| Customer Segments | Loyalty members across Silver, Gold, and Platinum tiers, alongside non-loyalty shoppers |
| Analysis Period | January 2025 – May 2026 |
| Technology Stack | Databricks SQL and Power BI |

### Business Scale

- **₹895M** in sales during the analysed period.
- **1.1 million** transactions.
- **14,345** customers represented in the analysis.

These figures establish the scale of the business being studied and the need to analyse performance across multiple dimensions rather than relying on overall revenue alone.

## 🎯 Business Problem

The central business problem is to understand **what drives retail growth, where performance differs across the business, and which actions can improve revenue quality and customer value**.

Increasing sales does not automatically mean that a retail business is becoming more efficient or building stronger customer relationships. Growth may come from more store visits, changes in customer acquisition, larger baskets, better product performance, or differences in regional and store-format execution.

Without a structured analysis, decision-makers may struggle to identify the real drivers of growth, recognise underperforming markets, allocate resources effectively, and retain their most valuable customers.

This project addresses these challenges by connecting business performance metrics with product, geography, store-format, and customer-level analysis.

## 🔍 Key Business Questions

The analysis is structured around six business areas.

### 1. Business Performance and Growth

- How quickly is revenue growing year over year?
- Is growth driven by higher transaction volumes or higher average transaction value?
- How does like-for-like performance change when equivalent trading days are compared?
- Which payment methods contribute most to sales?

### 2. Geographic and Store-Format Performance

- Which regions and cities lead or lag in growth?
- How is revenue distributed across cities?
- Which store formats drive revenue, and which demonstrate stronger growth?
- How do Tier 1, Tier 2, and Tier 3 cities differ in spending and performance?

### 3. Product and Category Performance

- Which departments contribute most to sales and growth?
- Which categories perform consistently across regions?
- Where do high transaction volumes fail to translate into proportional sales growth?
- What does the analysis indicate about discounting, brand performance, and product mix?

### 4. Customer Loyalty and Engagement

- How do loyalty members compare with non-loyalty shoppers in spending behaviour?
- Is the active loyalty base expanding?
- How frequently do customers return?
- Which departments are associated with stronger repeat engagement?

### 5. Customer Value and Segmentation

- Which customer segments contribute the most revenue?
- How do purchasing frequency, recency, and spending differ between segments?
- Which customers may be at risk of lapsing?
- Where is there an opportunity to move occasional buyers towards more frequent purchasing?

### 6. Business Improvement Opportunities

- How can the business increase average basket value?
- Where should loyalty and customer-retention efforts be prioritised?
- Which regions and store formats require further investigation?
- How can product assortment, promotions, and expansion decisions be guided by data?

## 🛠️ Technology Stack

| Technology | Role in the Project |
|---|---|
| Databricks SQL | Data preparation, transformation, and analytical data modelling |
| Medallion Architecture | Organising data into Bronze, Silver, and Gold layers |
| SQL | Aggregations, business metrics, comparative analysis, and customer segmentation |
| Power BI | Business performance analysis, KPI monitoring, and interactive reporting |

The project separates data preparation from business reporting to create a structured analytical workflow.

## ⚙️ Analytical Approach

The project follows an end-to-end business analytics workflow.

1. **Data Preparation:** Organise and transform retail data using Databricks SQL.
2. **Layered Data Processing:** Structure data through Bronze, Silver, and Gold layers.
3. **Business Metric Development:** Analyse sales, transactions, average transaction value (ATV), year-over-year (YoY) growth, like-for-like (LFL) growth, loyalty contribution, and customer engagement.
4. **Multidimensional Analysis:** Compare performance across time, regions, cities, store formats, departments, categories, and customer segments.
5. **Insight Generation:** Identify growth drivers, performance gaps, purchasing patterns, and opportunities for improvement.
6. **Business Recommendations:** Translate the findings into prioritised actions that decision-makers can evaluate.

The objective is not simply to report what happened, but to understand the business patterns behind the results and identify where further action may create value.

## 📈 Key Findings

The analysis identifies several important patterns in the business.

| Area | Key Finding | Business Implication |
|---|---|---|
| Revenue Growth | Revenue increased by 29.2% year over year in May 2026 | The business is expanding, but the drivers of growth require continued monitoring |
| Like-for-Like Performance | Sales grew by 19.33% from January to May 2026 | Growth remains positive when comparing equivalent trading days |
| Basket Value | Like-for-like ATV declined by 1.30% | Increasing basket value is an important opportunity |
| Customer Loyalty | Loyalty members spend 81% more per transaction on average | Loyalty engagement represents a significant commercial opportunity |
| Geography | No individual city contributes more than 10% of revenue | Sales are distributed across multiple markets |
| Store Formats | Supermarkets drive revenue, while Fresh shows strong growth and Express lags | Different store formats require different strategies |
| Product Mix | Grocery & Staples and Beverages together account for approximately 52% of sales | Core categories are central to overall business performance |
| Customer Value | VIP and Frequent customers represent 22.4% of customers and contribute 52.8% of revenue | Customer retention and segment-specific engagement deserve priority |

These findings suggest that the next stage of business improvement should focus on increasing basket value, strengthening customer relationships, addressing weaker store-format and regional performance, and replicating successful product and market strategies.

## 💡 Business Recommendations

Based on the findings, the project proposes the following priorities:

- **Increase Average Basket Value:** Test product bundles, multi-buy offers, complementary products, and checkout add-ons.
- **Strengthen Customer Loyalty:** Expand loyalty acquisition and encourage new members to make repeat purchases.
- **Protect High-Value Customers:** Introduce targeted retention initiatives and early-warning mechanisms for VIP and Frequent customers.
- **Improve Underperforming Formats:** Review Express-store assortment, pricing, and convenience propositions.
- **Investigate Regional Performance:** Examine the operational and market factors behind slower growth in the Central region.
- **Replicate Successful Strategies:** Investigate the practices associated with strong performance in markets such as Nagpur and Noida, and in the Household department.
- **Improve Product Availability:** Prioritise core categories such as Tea & Coffee, Rice & Grains, and Cooking Oil & Ghee.
- **Develop Predictive Analytics:** Use customer segmentation as a foundation for future churn prediction, customer lifetime value analysis, and market-basket analysis.

These recommendations are intended to guide business decisions and further investigation; their financial impact would need to be validated through implementation and measurement.

## ⚠️ Data Interpretation and Limitations

- The findings describe the dataset and analysis period rather than independently verified performance for a named real-world retailer.
- Like-for-like growth and year-over-year growth measure different things and should not be treated as interchangeable.
- The customer engagement section uses a sample dataset. Its reported next-month return rate of 84%–86% is unusually high for real retail and should be interpreted cautiously.
- The relationship between discounting and sales is indicative, not conclusive, because the relevant comparison covers only five months.
- Recommendations represent analytical opportunities, not proven causal effects or guaranteed business outcomes.

These limitations are important when using the results to support commercial decisions.

## 🚀 Project Scope and Further Exploration

This repository serves as the **main project overview**. It establishes the business context, analytical objectives, methodology, major findings, and recommendations.

Detailed dashboard documentation will be maintained separately so that each analytical view can explain its own KPIs, business questions, measures, and visual insights without duplicating the overall project narrative.

The broader analytical direction is to extend descriptive business intelligence towards predictive and decision-support capabilities, including:

- Customer churn modelling
- Customer lifetime value analysis
- Market-basket analysis
- Customer retention and cohort analysis

## 👨‍💻 Author

**Mohd Arsalan**

Retail Analytics | SQL | Databricks | Power BI | Business Intelligence

Focused on using data analysis to understand business performance, uncover actionable insights, and support evidence-based decision-making.

---

*Retail Analytics Dashboard Project | Analysis Period: January 2025 – May 2026*
