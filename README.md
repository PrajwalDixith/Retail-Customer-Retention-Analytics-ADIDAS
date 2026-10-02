Project Overview: 
Adidas, a global leader in sportswear and lifestyle products, operates across multiple countries 
through retail stores, franchise outlets, and e-commerce platforms. With intense competition 
from brands like Nike and Puma, along with rising customer expectations in digital shopping 
experiences, retaining customers has become a critical challenge. Although Adidas collects vast 
data on customer purchases, online interactions, and loyalty programs, their current reporting 
lacks the analytical depth to: 
● Understand why customers are churning? 
● Identify loyal vs. at-risk customers 
● Measure the impact of loyalty tiers, promotions, and influencer-driven campaigns 
● Guide region- and channel-specific retention strategies 
You are hired as a Power BI Analyst to design a Customer Retention Dashboard that 
consolidates fragmented data and delivers real-time, actionable insights for Adidas. 


Project Objective: 
Develop a robust, interactive Customer Retention Analytics Dashboard in Power BI using 
Adidas data that will: 
● Consolidate customer demographics, purchase history, store/e-commerce performance, 
and loyalty data 
● Enable dynamic segmentation of high-value, repeat, and churned customers 
● Provide actionable insights to improve customer retention, loyalty engagement, and 
regional strategies

This project focuses on answering questions on different aspects as follows : 

Data Modeling & Cleaning 
● Load and transform datasets in Power Query 
● Handle duplicates, missing values, and ensure correct data types 
● Create calculated columns: 
  ○ Membership_Duration = Today – Membership_Since 
  ○ Extract Transaction_Year, Transaction_Month
  
Churn & Retention Metrics
● Create Churn Rate KPI = (Churned Customers / Total Customers) * 100 
● Visualize churn rate by: 
  ○ Region 
  ○ Income Group 
  ○ Channel (Store/Online) 
  ○ Loyalty Tier 
● Funnel Chart: Total Customers → Repeat Customers → Churned

Repeat Purchase Analysis
● Segment customers: 
  ○ Low-Tier: 0–3 purchases 
  ○ Mid-Tier: 4–8 purchases 
  ○ High-Tier: 9+ purchases 
● Compare avg. purchase frequency by Region, Age Group, Loyalty Tier 
● Identify most purchased product categories by loyal customers 

Promotion & Loyalty Impact
● % of transactions with promotion applied 
● Compare avg. purchase amount with vs without promotions 
● Churn rate across loyalty tiers 
● Points Earned vs Redeemed by Tier (clustered column chart) 
● Recommendations to improve redemption & retention

 Store & Channel Performance vs Retention
● Merge store data with transactions 
● Visualize: 
  ○ Avg. transaction amount by Store Type 
  ○ Churn rate by store type 
  ○ Correlation between store opening year & retention

Customer Lifetime Value (CLV) Analysis 
● CLV = Total Amount Spent / Membership Duration (Years) 
● Segment customers into Low, Medium, High CLV 
● Visualize: 
  ○ CLV vs Days Since Last Purchase 
  ○ CLV by Loyalty Tier & Region

Final Dashboard & Executive Summary
● Multi-page Power BI Report: 
  ○ Page 1: KPIs (Churn, CLV, Repeat Rate) 
  ○ Page 2: Loyalty & Promotion Impact 
  ○ Page 3: Store/Channel Insights 
  ○ Page 4: Segmentation (Churned, Repeat, High-Value) 
● Slicers: Region, Channel, Income, Loyalty Tier 
● Top 3 recommendations for Adidas: 
  ○ Which customers to prioritize for retention? 
  ○ Which channels are underperforming? 
  ○ How to strengthen loyalty program engagement?


  
