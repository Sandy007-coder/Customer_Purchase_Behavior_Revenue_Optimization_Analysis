
# 📊 Customer Purchase Behavior && Revenue Optimization Analysis

Customer shopping behavior analysis using Python, SQL, and Power BI. Performed data cleaning, feature engineering, and exploratory data analysis on 3,900+ transactions to uncover insights on revenue trends, customer segmentation, and product performance, enabling data-driven business decisions.


## 🏷️ Badges

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server-orange?logo=postgresql)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)


## 📌 Overview

Customer shopping behavior analysis project aimed at uncovering actionable insights from transactional data. The project covers the complete data analytics pipeline, including data cleaning, exploratory data analysis (EDA), SQL-based business queries, and interactive dashboard creation using Power BI. The goal is to understand revenue trends, customer segments, and product performance to support data-driven decision-making.




## 🛠️ Tech Stack

| Category          | Tools & Technologies                        |
| ----------------- | ------------------------------------------- |
| **Programming**   | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| **Database**      | PostgreSQL, MySQL, SQL Server               |
| **Visualization** | Power BI                                    |
| **Presentation**  | Power Point                                    |

## ⚙️ Project Workflow

🔹 1. Data Collection
* Imported transactional dataset containing 3,900+ customer purchase records
* Verified dataset structure, data types, and feature distribution

🔹 2. Data Cleaning & Preprocessing
* Checked for missing values and handled 37 null values in review_rating using median imputation (category-wise)
* Removed redundant columns (promo_code_used) after validation
* Standardized column names to snake_case format
* Ensured consistency in categorical values (e.g., gender, subscription status)

🔹 3. Feature Engineering
* Created age_group by binning customers into segments (Young Adult, Adult, etc.)
* Derived purchase_frequency_days from purchase behavior
* Prepared data for better segmentation and analysis

🔹 4. Exploratory Data Analysis (EDA)
* Performed univariate and bivariate analysis
* Analyzed:
   * Customer demographics (age, gender)
   * Purchase distribution across categories
   * Seasonal trends and buying patterns
   * Ratings and product performance
* Used visualizations to identify trends and anomalies

🔹 5. Database Integration
* Connected Python environment to PostgreSQL
* Loaded cleaned dataset into database tables
* Structured data for efficient SQL querying

🔹 6. SQL-Based Analysis
* Wrote optimized SQL queries to answer business questions:
  * Revenue contribution by gender and age group
  * Identification of high-spending customers
  * Top-performing and highly rated products
  * Impact of discounts on sales
  * Subscriber vs non-subscriber comparison
  * Customer segmentation (New, Returning, Loyal)

🔹 7. Data Visualization (Power BI)
* Designed interactive dashboard with key KPIs:
   * Total revenue
   * Average purchase value
   * Customer distribution
* Implemented filters (category, gender, subscription, shipping type)
* Built charts for:
   * Revenue trends
   * Customer segmentation
   * Product performance

🔹 8. Reporting & Presentation
* Documented findings in a structured analytical report
* Created a presentation using Power Point to communicate insights
* Highlighted key business recommendations for decision-making
## 📊 Key Insights

* 💰 Revenue Distribution: Male customers contributed significantly higher revenue compared to female customers
* 👥 Customer Segmentation: Majority of customers fall under the loyal segment, indicating strong retention
* 🚚 Shipping Behavior: Customers using express shipping tend to spend slightly more on average
* 📈 Top Revenue Group: Young adult customers generated the highest overall revenue
* 🛍️ Product Performance: Certain products show high sales volume and strong customer ratings
* 🏷️ Discount Impact: Some products rely heavily on discounts, affecting overall profit margins
## 🖼️ Dashboard

The Power BI dashboard is designed to provide an interactive and comprehensive view of customer shopping behavior and revenue performance. It enables quick analysis through dynamic filters and visual insights, helping stakeholders make data-driven decisions.

🔹 Dashboard Highlights

* KPI Cards: Display total revenue, average purchase value, total customers, and average rating
* Customer Segmentation: Visual breakdown of customers into New, Returning, and Loyal segments
* Revenue Analysis: Shows revenue distribution across gender, age groups, and subscription status
* Product Performance: Identifies top-selling and top-rated products across categories
* Shipping Insights: Compares spending behavior between standard and express shipping
* Discount Analysis: Highlights products with high dependency on discounts

🔹 Interactive Features
* Filters for Category, Gender, Subscription Status, and Shipping Type
* Dynamic visuals that update based on user selection
* Easy navigation for exploring different business perspectives
### 🖼️ Dashboard Preview



![Power BI Dashboard](https://github.com/user-attachments/assets/a0fbf755-07dc-45b3-9894-4816500516fa)




## ▶️ How to Run

🔹 1. Clone the Repository

git clone https://github.com/Sandy007-coder/Customer_Purchase_Behavior_Revenue_Optimization_Analysis.git
cd Customer_Purchase_Behavior_Revenue_Optimization_Analysis

🔹 2. Download Dataset
* Dataset is hosted externally due to size
* Download from Google Drive:[Dataset Link] (https://drive.google.com/drive/folders/1igL0qltICAsrDdSvdC7oJl2HZM2czQlx?usp=drive_link)
* Place the dataset inside the data/ folder

🔹 3. Run Python Analysis
* Navigate to the python_analysis/ folder
* Open .ipynb notebooks or .py scripts
* Run using Jupyter Notebook or any Python IDE

🔹 4. Run SQL Analysis
* Import the dataset into PostgreSQL / MySQL / SQL Server
* Execute queries from the sql/ folder

🔹 5. View Dashboard
* Open the .pbix file from the dashboard/ folder
* Use Power BI Desktop to explore insights
## 👨‍💻 Author

Sarveswaran S

* 🎓 B.Tech CSE (Cybersecurity)
* 🔐 Cybersecurity, Python & Data Analytics Enthusiast
* 🎯 Interested in Penetration Testing, Red Teaming, and Data Analysis

🔗 GitHub: https://github.com/Sandy007-coder

🔗 LinkedIn: (https://www.linkedin.com/in/sarveswaran-cybersec?utm_source=share_via&utm_content=profile&utm_medium=member_android)