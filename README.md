Credit Card Financial Dashboard | Power BI 

An end-to-end data analysis project where I built a Credit Card Financial Dashboard using PostgreSQL as the database and Power BI for visualization.


Tools Used


PostgreSQL — database setup and SQL queries
Power BI — dashboard design and DAX
Excel/CSV — raw data source



What I Did

1. Database Setup (PostgreSQL)


Created a database credit_card_db with two tables — cc_detail and cust_detail
Imported raw CSV data into PostgreSQL using the COPY command
Wrote SQL queries to analyze revenue, customer segments, and transaction trends


2. Data Processing (Power BI)


Connected Power BI directly to PostgreSQL database
Cleaned and transformed data using Power Query
Created calculated columns and measures using DAX


3. Dashboard Design (Power BI)


Built an interactive dashboard with charts and tables
Added filters and slicers for dynamic exploration
Exported and shared the final dashboard



Dashboard Insights


Which card category generates the most revenue
Quarterly transaction and interest trends
Customer spending patterns by income and job type
State-wise transaction volume
Week-over-week growth in transactions



Project Structure

├── sql/
│   ├── setup.sql          # Database and table creation
│   └── analysis.sql       # Analytical queries
├── dashboard/
│   └── cc_dashboard.pbix  # Power BI file
├── data/
│   ├── credit_card.csv
│   └── customer.csv
└── README.md

Author - A.Praneetha
