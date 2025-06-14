**Tools & Technologies Used:**
*Python (pandas) – Data cleaning & preprocessing
*SQL (PostgreSQL/SQLite) – Data modeling & analytical queries
*Power BI – Interactive dashboards & data storytelling

**Project Structure:**
Retail-Analytics-Project/
├── data/
│   ├── raw_sales_data.csv       # Synthetic raw sales data
│   └── cleaned_sales_data.csv   # Output after Python cleaning
├── python/
│   └── data_cleaning.py         # Python script for data transformation
├── sql/
│   ├── schema.sql               # SQL to create database table
│   └── transform_queries.sql    # Sample queries for insights
├── powerbi/
│   └── SalesDashboard.pbix      # Power BI report (to be created)
├── README.md                    # Project documentation
└── requirements.txt             # Python dependencies



**🧹 Data Cleaning (Python)**
The data_cleaning.py script performs:
Date formatting
Revenue calculation (Quantity × UnitPrice)
Output: cleaned_sales_data.csv

**🧾 Database Schema & Queries (SQL)**
1)Run schema.sql to create a Sales table.
2)Use transform_queries.sql to analyze:
*Monthly revenue trends
*Top-selling products
*Customer purchase patterns

💡 Compatible with PostgreSQL or SQLite.

**📈 Power BI Dashboard**
Import cleaned_sales_data.csv or connect to your SQL database and build visuals like:
📊 Revenue over time
🥇 Top 10 products
📍 Regional sales (optional)
👥 Customer segmentation (RFM analysis as a bonus)

**✅ How to Run**
1)Install dependencies:
pip install -r requirements.txt

2)Run the Python script:
python python/data_cleaning.py

3)Set up the SQL table and run queries.

4)Open Power BI and connect to cleaned_sales_data.csv to create dashboards.

**Key Skills Demonstrated:**
Data wrangling and transformation in Python
Relational database modeling and SQL aggregation
Dashboard design and storytelling using Power BI

