# Customer Segmentation Analysis (RFM)

## Overview
This project analyzes customer transaction data using RFM (Recency, Frequency, Monetary) to identify customer segments and generate business insights.

## Objectives
- Identify high-value and loyal customers
- Analyze customer purchasing patterns
- Segment customers based on behavior
- Provide actionable business recommendations

## Tools
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab

## Key Insights
- Customer spending is highly skewed, where a small group of customers contributes the majority of total revenue (Pareto principle)
- Customers with higher purchase frequency tend to generate significantly higher revenue
- The majority of customers are low-frequency buyers, indicating opportunities for engagement and retention strategies


## Visualizations

### Revenue Distribution
![Revenue](images/revenue_dist.png)

**Insight:**
Revenue distribution is highly right-skewed, indicating that a small number of customers contribute most of the revenue.

**Business Impact:**
Retention strategies should prioritize high-value customers, as they are the main drivers of business performance.

### Frequency vs Revenue
![Frequency](images/freq_vs_revenue.png)

**Insight:**
There is a positive relationship between purchase frequency and revenue. Customers with higher frequency tend to generate higher total revenue.

**Business Impact:**
Increasing customer purchase frequency through loyalty programs or targeted promotions can significantly improve revenue.

### Customer Segmentation
![Segment](images/segment_dist.png)

**Insight:**
Most customers fall into the Regular segment, while a smaller group of high-value customers (Best Customers and Big Spenders) contributes significantly to overall revenue.

**Business Impact:**
Segment-based strategies can be applied:
- Retain and reward high-value customers
- Upsell to loyal customers
- Re-engage low-frequency customers
  
## Business Recommendations
- Prioritize retention strategies for high-value customers (VIP treatment, exclusive offers)
- Implement loyalty programs to increase purchase frequency
- Design targeted marketing campaigns for different customer segments
- Re-engage inactive customers through personalized promotions

## Dataset
Online Retail Dataset (E-commerce transaction data)

## Conclusion
This project demonstrates how customer segmentation using RFM analysis can provide valuable insights into customer behavior and support strategic business decisions. By leveraging data, companies can better target their customers and optimize revenue growth.

