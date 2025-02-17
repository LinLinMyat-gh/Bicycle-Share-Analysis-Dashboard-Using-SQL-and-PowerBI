# Bicycle Share Dashboard Overview

This project analyzes data from a **Bicycle Share Program** to derive insights into ridership trends, revenue generation, and seasonal impacts. By leveraging SQL to join datasets and Power BI for visualization, we aim to uncover key patterns in user behavior, revenue performance, and operational efficiency.

## Objectives

- **Ridership Analysis:**
    - Track ridership trends over time (daily, weekly, monthly, yearly).
    - Differentiate between casual and registered users.
    - Identify peak riding hours and seasonal demand variations.
- **Revenue & Profit Analysis:**
    - Calculate revenue and profit margins based on ride counts and pricing.
    - Assess the impact of pricing strategies on overall profitability.
    - Compare revenue performance across different seasons.
- **Operational Insights:**
    - Analyze the relationship between ridership volume and operational costs.
    - Identify areas where cost optimization can improve profit margins.
    - Evaluate factors affecting late returns and system inefficiencies.

## Datasets
- **Link** https://www.kaggle.com/datasets/walmalki/toman-bike-share-dataset

### 1. **Bike Share Usage Data**
Contains ridership information with the following columns:
- **dteday:** Date of the ride.
- **season:** Season category (Spring, Summer, Fall, Winter).
- **yr:** Year of the ride.
- **weekday:** Day of the week.
- **hr:** Hour of the ride.
- **rider_type:** User classification (casual vs. registered).
- **riders:** Number of riders.

### 2. **Cost & Revenue Data**
Contains cost-related information used to analyze profitability:
- **price:** Price per ride.
- **COGS:** Cost of goods sold per ride.
- **Revenue Calculation:** Revenue = riders * price.
- **Profit Calculation:** Profit = (riders * price) - (COGS * riders).

### **Tools Used** ###
- **SQL** – Data extraction, transformation, and preparation.
- **Power BI** – Dashboard creation & data visualization.

## SQL Query Used for Data Preparation
![Screenshot 2025-02-18 021958](https://github.com/user-attachments/assets/4fd32d9e-0630-4572-82ae-2b53c22fe71c)

# RESULT
![Screenshot 2025-02-18 020110](https://github.com/user-attachments/assets/b9a8fafe-f028-4fd0-b01b-44e499c4fca2)

## Executive Summary

This dashboard integrates ridership and revenue data to provide actionable insights into user behavior, financial performance, and seasonal trends. The goal is to help stakeholders make data-driven decisions to optimize operations, maximize profitability, and enhance user engagement.

 **Key Insights**
 **Ridership Trends:**
- Peak ridership in summer with lower engagement in winter.
- Registered riders contribute to stable ridership, while casual users increase on weekends and holidays.
- Peak riding hours observed during morning (8-9 AM) and evening (5-6 PM) commutes.

 **Revenue & Profitability:**
- Highest revenue recorded during summer due to increased demand.
- Winter had the lowest revenue, requiring potential pricing adjustments.
- Profit margins remained stable, but operational costs need further optimization.

 **Operational Efficiency:**
- Cost per ride directly affects profitability.
- Potential to optimize maintenance schedules based on high-usage patterns.
- Expanding services in high-demand areas could increase ridership and revenue.

 **Dashboard Overview**
 **Key Metrics**
- Total Revenue: $15M
- Total Profit: $10.45M
- Total Riders: 3M
- Profit Margin: 0.45
- Registered Riders: 81.17%
- Casual Riders: 18.83%

 **Visualizations**
- Revenue by Season – Highlights seasonal variations in revenue.
- Rider Segmentation – Registered vs. casual riders analysis.
- Hourly Rental Trends – Bike rental activity at different times of the day.
- Profit Margins Over Time – Tracking revenue and profit fluctuations.

  ![Screenshot 2025-02-18 020822](https://github.com/user-attachments/assets/29e25867-6c45-4263-9652-32238196221d)


 **Recommendations & Strategic Focus**
 **1. Optimize Seasonal Pricing**
- Implement dynamic pricing to maximize revenue during high-demand periods.
- Offer discounts during off-peak hours to increase ridership.

 **2. Improve Cost Efficiency**
- Identify operational inefficiencies and optimize resource allocation.
- Adjust maintenance schedules to match high-usage trends.

 **3. Increase Customer Engagement**
- Introduce loyalty programs for frequent riders.
- Promote casual-to-registered conversion with targeted marketing.

 **4. Expand High-Demand Services**
- Use ride data to expand bike stations in under-served but high-traffic areas.
- Improve bike availability forecasting for better service reliability.

 **5. Data-Driven Decision Making**
- Regularly track revenue, ridership trends, and costs.
- Use predictive analytics to anticipate demand shifts and adjust operations proactively.


