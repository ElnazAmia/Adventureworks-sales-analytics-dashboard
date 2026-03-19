📊 AdventureWorks Sales Analytics Dashboard
🚀 Project Overview

This project is a Power BI dashboard built using the AdventureWorks dataset to analyze sales performance, customer behavior, and business trends.

It demonstrates end-to-end analytics including data modeling, DAX, and interactive reporting.

📌 Key Features

📊 KPI tracking (Revenue, Profit, Orders)

📈 Sales trends over time

👥 Customer segmentation insights

🌍 Regional performance analysis

🏆 Top products and categories

🧠 Data Model

The dataset is structured using a star schema:

Fact Tables:

Sales

Dimension Tables:

Customers

Products

Dates

Territories

📐 Key Measures (DAX)
Total Sales = SUM(Sales[SalesAmount])

Total Orders = COUNT(Sales[OrderID])

Profit = SUM(Sales[Profit])

Profit Margin = DIVIDE([Profit], [Total Sales])
📸 Dashboard Preview




💡 Insights

Identified top-performing product categories

Analyzed revenue trends across regions

Highlighted customer purchasing behavior patterns

🛠 Tools & Technologies

Power BI

DAX

Data Modeling (Star Schema)

Data Visualization


📣 Author

Elnaz Amia
LinkedIn: www.linkedin.com/in/elnaz-amia
