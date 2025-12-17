Magist Marketplace Analysis for Tech Product Expansion
🎯 Project Overview
This project analyses the Brazilian e-commerce marketplace Magist to evaluate whether it is a suitable platform for ENIAC, a company that sells technology products.
Using SQL-based data analysis and Tableau visualisations, the project explores demand, pricing behaviour, seller structure, and delivery performance.
The goal is to support a data-driven business decision about market entry.
📊 Dataset & Sources
Source: Magist e-commerce database (provided during the course)
Size: ~100,000 orders across multiple related tables
Time Period: 2016–2018
Main Tables Used:
orders
order_items
customers
products
sellers
payments
reviews
geo
Notes:
The dataset represents a general marketplace. Not all orders include reviews, and some orders contain multiple items and payments.
🚀 Key Findings & Results
Demand for technology products exists, especially in electronics, telephony, and computer accessories
Customers are highly price-sensitive; low- to mid-priced products sell significantly more
Only around 17% of sellers operate in technology-related categories
About 92% of orders are delivered on time, with an average delivery time of ~12.5 days
Delivery delays are not strongly influenced by product size
🛠️ Technologies Used
SQL: MySQL
Visualisation: Tableau Public
Data Format: CSV exports
Environment: MySQL Workbench, Tableau Desktop / Public
📁 Project Structure
/sql/ – SQL queries used for analysis
/data/ – CSV files exported from the Magist database
/tableau/ – Tableau workbooks and dashboards
/images/ – Screenshots of key visualisations
📈 Visualisations
The Tableau dashboards show:
Technology demand by product category
Revenue distribution across price ranges
Order delivery performance and delays
These visualisations support the business conclusions and make the results easy to interpret.
🔗 How to Use This Project
Review SQL queries in the /sql folder
Open the Tableau workbook to explore interactive dashboards
Use the CSV files in /data to reproduce the analysis
No additional setup is required.
🚀 Future Work
Analyse customer behaviour over time (repeat customers)
Compare tech vs non-tech seller performance in more detail
Include profit margins if cost data becomes available
Extend analysis with predictive delivery delay models

📧 Contact
Email: bengiaknergiz@gmail.com
