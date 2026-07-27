# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project that analyzes customer shopping patterns using **Python, PostgreSQL, SQL, and Power BI**.

The project covers the complete analytics workflow — from cleaning and transforming raw customer data in Python to storing it in PostgreSQL and building an interactive Power BI dashboard for business insights.

## 📊 Dashboard Preview

![Customer Shopping Behavior Dashboard](images/dashboard.png)

## 🎯 Project Objective

The objective of this project is to analyze customer purchasing behavior and identify patterns related to:

- Revenue generation
- Customer demographics
- Product categories
- Customer segments
- Purchase frequency
- Subscription behavior
- Discounts
- Shipping preferences
- Payment methods
- Product performance

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data cleaning and transformation |
| Pandas | Data preprocessing and feature engineering |
| Jupyter Notebook | Python development and analysis |
| PostgreSQL | Relational database storage |
| SQLAlchemy | Python–PostgreSQL integration |
| SQL | Data querying and validation |
| Power BI | Data modeling, DAX, and visualization |

## 🔄 Project Workflow

```text
Raw CSV Dataset
       ↓
Python / Pandas
       ↓
Data Cleaning & Transformation
       ↓
Feature Engineering
       ↓
PostgreSQL Database
       ↓
SQL Validation
       ↓
Power BI
       ↓
DAX Measures
       ↓
Interactive Dashboard
```

## 🧹 Data Cleaning & Transformation

The dataset was processed in Python using Pandas before being loaded into PostgreSQL.

Major preprocessing steps included:

- Checking missing values
- Handling missing review ratings
- Standardizing column names
- Validating categorical values
- Checking data types
- Creating customer age groups
- Converting purchase frequency into numerical day values
- Preparing the dataset for database storage and BI analysis

## 🗄️ PostgreSQL Integration

After preprocessing, the cleaned dataset was loaded into a PostgreSQL database using **SQLAlchemy and Psycopg2**.

The database acts as the central data source for Power BI.

This demonstrates a complete analytics pipeline rather than directly importing a CSV file into Power BI.

## 📈 Dashboard KPIs

The dashboard tracks six major KPIs:

- **Total Revenue:** $233K
- **Total Customers:** 4K
- **Average Purchase Amount:** $59.76
- **Subscriber Percentage:** 27.00%
- **Discount Usage:** 43.00%
- **Average Review Rating:** 3.75

## 📊 Dashboard Analysis

The Power BI dashboard includes analysis of:

- Revenue by Category
- Revenue by Customer Segment
- Revenue by Shipping Type
- Revenue by Payment Method
- Top 10 Products
- Revenue by Gender
- Customers by Purchase Frequency
- Customers by Age Group

Interactive slicers allow analysis by:

- Age Group
- Category
- Gender
- Season
- Customer Segment

## 💡 Key Insights

Some observations from the dashboard include:

- Clothing is the highest revenue-generating product category.
- Regular customers contribute the largest share of revenue among customer segments.
- Male customers account for the majority of total revenue in the dataset.
- Purchase frequency is relatively distributed across the different frequency groups.
- Adult and middle-aged customers represent the largest customer groups.
- Several products generate approximately $10K each in total revenue.
- Subscription and discount behavior can be analyzed interactively through the dashboard filters.

## 🎨 Dashboard Design

The dashboard uses a consistent visual system:

- **Navy** — customer and count-based metrics
- **Teal** — revenue and monetary metrics
- **White cards** — KPI and visual containers
- **Light gray background** — dashboard canvas

This color system helps distinguish financial metrics from customer-related metrics while maintaining a consistent interface.

## 📂 Repository Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_analysis.ipynb
│
├── powerbi/
│   └── customer_shopping_dashboard.pbix
│
├── sql/
│   └── analysis_queries.sql
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

## 🚀 How to Run

1. Clone this repository.
2. Install the required Python packages.
3. Create a PostgreSQL database.
4. Update the database credentials locally.
5. Run the Jupyter Notebook to clean and load the dataset.
6. Open the Power BI `.pbix` file.
7. Configure the PostgreSQL data source if required.
8. Refresh the dashboard.

## 🔐 Security Note

Database credentials are **not included in this repository**.

If reproducing this project, configure your own PostgreSQL username, password, host, port, and database name locally.

## 📌 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Python / Pandas
- Feature Engineering
- PostgreSQL
- SQL
- Database Integration
- Power BI
- DAX
- Data Visualization
- Dashboard Design
- Business Intelligence

## 👤 Author

**Dipesh Lamba**

B.Tech — Artificial Intelligence & Data Science

GitHub: @dipesh7891
