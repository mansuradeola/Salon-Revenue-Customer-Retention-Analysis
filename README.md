# Salon Revenue & Customer Retention Analysis

### Project Overview

This project analyzes Xploit Unisex Salon’s transaction data to uncover insights on customer behavior, revenue trends, and retention patterns.

The goal is to provide data-driven recommendations to improve salon revenue and customer loyalty.

### Business Questions
- What days are the slowest?
- What time should promotions run?
- Which services generate the most revenue?
- How can repeat customers be increased?

### Tools Used
- Excel (Data Cleaning, Pivot Tables, Analysis)
- Tableau (Dashboard Visualization)

### Data Sources

Salon Revenue & Customer Retention Analysis: The primary dataset used for this project is the 'RAWSalon _Revenue_and_Customer_Retention_Using_Data.csv' file.

The dataset contains:
- 2+ weeks worth of data
- 50 customer transactions
- Service types (haircuts, braids, etc.)
- Time and day of visits
- Revenue and payment methods
- Customer return status

### Data Cleaning and Preparation 

- Verified and formatted **Time** and **Date** columns  
- Created new columns:
  - **Hour** (from Time)  
  - **Time Bucket** (Morning / Afternoon / Evening)  
  - **Week Type** (Weekday / Weekend)  
- Checked for missing or inconsistent values and ensured proper formatting for analysis

### Exploratory Data Analysis 

- **Customer Flow Analysis**: Counted transactions per day and per hour to identify traffic patterns  
- **Service Popularity**: Summarized number of requests per service  
- **Revenue Distribution**: Examined revenue by service to find high-earning services  
- **Customer Retention**: Compared returning vs new customers per service  
- **Preliminary Visualizations**: Generated charts for:
  - Transactions by day of week  
  - Transactions by time bucket  
  - Revenue by service  
  - Returning vs new customers  

> EDA allowed us to spot trends, outliers, and patterns that guided deeper analysis and recommendations.

### Results/Findings

#### Slow Days
- Five days recorded the lowest activity with only 6 transactions each  
- Indicates underutilized capacity during early-week days

#### Promo Timing
- Evening periods had the lowest traffic (5 customers)  
- Ideal for running targeted promotions

#### Revenue Drivers
- Braids (₦68,000) and Haircuts (₦60,000) are the top revenue-generating services  

#### Customer Retention
- Haircuts and braids have high repeat customer rates  
- Manicure services show low retention, suggesting improvement opportunities

You can download the full Excel analysis with pivot tables here: [PIVOTImproving Salon Revenue and Customer Retention Using Data.xlsx](excel/PIVOTImproving Salon Revenue and Customer Retention Using Data.xlsx)

### Recommendations 

- Introduce weekday and evening promotions  
- Focus marketing on high-revenue services  
- Implement loyalty programs for repeat customers  
- Improve low-retention services through bundling and quality enhancement

### Limitations 

- Dataset is small (50 transactions) and may not fully represent long-term trends  
- Customer demographics (age, location, etc.) are not included  
- Seasonal or promotional effects are not captured  
- Recommendations are based on available data

### Dashboard Preview
![Dashboard](visuals/dashboard.png)

### References

- Excel official documentation: [https://support.microsoft.com/excel](https://support.microsoft.com/excel)  
- Tableau official documentation: [https://www.tableau.com/learn](https://www.tableau.com/learn)  
- Business analytics frameworks: Harvard Business Review, *Data-Driven Decision Making*  
- Personal knowledge from previous salon operations experience

### Conclusion
This analysis demonstrates how data can be used to optimize salon operations, increase revenue, and improve customer retention.

### Author
**Mansur Adeola**  
Data Analyst  
[LinkedIn](https://www.linkedin.com/in/mansur-a-682563142)
