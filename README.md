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



## 🛠️ Tools & Technologies
- SQL (Google BigQuery) – Data extraction and aggregation  
- Python (Jupyter Notebook) – Data analysis and EDA  
  - pandas  
  - matplotlib  
- CSV – Data export and portability  
- Google Docs – Executive reporting  
- GitHub – Project documentation and version control  



## 📁 Project Structure
marketing-analytics-project/

data
 marketing_performance.csv
customer_behavior.csv
product_performance.csv
 funnel_metrics.csv
notebook/
 marketing_analytics_analysis.ipynb

report/
 Executive_Report.pdf

 README.md


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

### Marketing Performance
- Revenue is concentrated among a small number of acquisition channels  
- Some channels generate fewer sessions but significantly higher revenue per session  
- Channel efficiency is more important than traffic volume alone
  ### Customer Behavior
- A small segment of customers contributes the majority of total revenue  
- Customer revenue distribution is strongly right-skewed  
- Higher engagement generally correlates with increased revenue  

### Product Performance
- A limited number of products dominate total revenue  
- Long-tail products contribute minimally on an individual basis  
- Opportunities exist for product bundling and targeted promotion  

### Conversion Funnel
- Significant drop-off occurs between sessions and product views  
- Moderate conversion from product view to purchase  
- Incremental improvements across the funnel could yield meaningful revenue growth
  ## 🧠 Strategic Recommendations
- Reallocate marketing spend toward high-efficiency channels  
- Prioritize retention and personalization strategies for high-value customers  
- Promote top-performing products and explore bundling opportunities  
- Improve product discovery and checkout experience to reduce funnel drop-offs  



## 📄 Executive Deliverable
An executive-ready PDF report was created to communicate insights clearly to non-technical stakeholders, focusing on business impact and strategic decision-making.

See: `/report/Executive_Report.pdf`
## 🚀 Why This Project Matters
This project demonstrates:
- Real-world SQL analytics using large-scale data  
- Revenue-focused exploratory data analysis  
- Strong separation of technical analysis and executive storytelling  
- Consultant-style communication of insights and recommendations  



## 👤 Author
Patience Anono  
Data Analyst |  Data Consultant  
Focused on marketing analytics, customer insights and data-driven decision-making
