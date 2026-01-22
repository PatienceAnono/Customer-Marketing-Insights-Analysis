# 📊 Customer & Marketing Insights Analysis  
Using Google Analytics E-commerce Data

## 📌 Project Overview
This project presents an end-to-end marketing analytics case study using the Google Analytics public e-commerce dataset. The analysis evaluates marketing performance, customer behavior, product performance and conversion funnel efficiency to uncover actionable, revenue-driven insights.

The project is designed as a real-world analytics engagement, combining SQL, Python and business storytelling to support data-informed decision-making.



## 🎯 Business Objectives
- Evaluate the effectiveness of marketing channels and traffic sources  
- Identify high-value customers and engagement patterns  
- Analyze product-level revenue concentration  
- Assess conversion funnel performance and drop-off points  
- Translate analysis into strategic business recommendations

  
  ## 📁 Data Source
- Dataset: Google Analytics Sample Dataset  
- Platform: Google BigQuery (Public Dataset)  
- Table Used:  
  - `bigquery-public-data.google_analytics_sample.ga_sessions_2017*`

The dataset represents real e-commerce session-level data, including traffic sources, customer interactions, product activity and transaction behavior.



 ## 📈 Technologies Used
 - Python (Pandas, Matplotlib, Seaborn) – Data cleaning, manipulation, and visualization
- Jupyter Notebook – Interactive exploratory data analysis
- CSV files – Cleaned datasets for analysis
- Git & GitHub – Version control and portfolio hosting


## 📁 Project Structure
Customer-Marketing-Insights-Analysis/

session_customer_eda.ipynb
→ Exploratory data analysis of user sessions and customer behavior

customer_behavior.csv
 → Cleaned dataset containing session-level customer behavior metrics

marketing_performance.csv
 → Marketing channel performance data (traffic, conversions, revenue)

funnel_metrics.csv
 → Conversion funnel stages and drop-off metrics

product_performance.csv
 → Product-level sales and revenue performance data

 README.md
    → Project documentation and insights summary



## 🔍 Analysis Workflow

### 1️⃣ Data Extraction (SQL – BigQuery)
Custom SQL queries were written to aggregate session-level data into analysis-ready datasets, including:
- Marketing performance by traffic source, medium, and campaign  
- Customer-level engagement and revenue metrics  
- Product-level units sold and revenue  
- Funnel metrics from sessions to purchases  

### 2️⃣ Data Validation & Cleaning
- No missing values detected due to prior SQL aggregation  
- Data types validated for numerical analysis  
- Zero values retained to reflect real e-commerce behavior  
- Outliers preserved to maintain high-value customer and product insights  



### 3️⃣ Exploratory Data Analysis (EDA)
Key analytical areas included:
- Revenue distribution across marketing channels  
- Revenue efficiency (revenue per session)  
- Customer engagement vs revenue behavior  
- Product revenue concentration  
- Conversion funnel drop-offs and efficiency  
Visualizations were created to support insight discovery and interpretation.



## 📈 Key Insights

- Marketing Channel Performance: Organic Search & Paid Search generated the most traffic, but Email & Referral channels showed higher conversion rates.
- Customer Funnel Analysis: Largest drop-off occurred between Add to Cart → Checkout, suggesting friction in the checkout process.
- Product Performance: Top products contributed over 60% of total revenue, highlighting focus areas for marketing campaigns.
- Customer Segments: Returning customers demonstrated higher engagement and purchase frequency than new users, showing the value of loyalty programs.  



  
  ## 🧠 Business Recommendations
- Optimize the checkout process to reduce cart abandonment.  
- Invest marketing spend in high-converting channels rather than only high-traffic channels.
- Launch promotions or bundles for top-performing products to maximize revenue. 
- Implement retention strategies to convert new customers into returning buyers.  

 
 
 ## 📈 Technologies Used
 - Python (Pandas, Matplotlib, Seaborn) – Data cleaning, manipulation, and visualization
- Jupyter Notebook – Interactive exploratory data analysis
- CSV files – Cleaned datasets for analysis
- Git & GitHub – Version control and portfolio hosting




## 👤 Author
Patience Anono  
Data Analytics & Marketing Insights | Kenya
Focused on marketing analytics, customer insights and data-driven decision-making



## 🖼 Visual Insights
### Funnel Analysis
![Funnel Drop-Off](images/funnel_dropoff)

### Top Products Revenue
![Top Products](images/top_products)

### Marketing Channel Performance
![Marketing Channels](images/marketing_channels)

