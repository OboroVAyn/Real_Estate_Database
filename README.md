![SQL](https://img.shields.io/badge/SQL-003B57?logo=postgresql&logoColor=white)


🏡 Real Estate Database & SQL Queries

📌 Project Overview

This project involves designing a real estate database and performing SQL queries to address business-related questions. The goal was to structure spatial and sales data into a relational database and extract insights through SQL queries.

📂 Data & Database Structure
```text
Data Dictionary: An Excel file defining tables, attributes, and relationships across spatial aspects (municipality, geography, land), including a lexicon for reference.
Relational Schema: A diagram connecting the four main tables, specifying primary keys, foreign keys, and relationships.
Source Tables (CSV):
Bien (Properties) – Contains listings with attributes (location, size, type, price).
Vente (Sales) – Records transactions including dates and sale prices.
Commune (Municipality) – Includes geographic and administrative data on towns.
Région (Region) – Defines broader territorial divisions for analysis.


🛠️ Tools & Technologies
MySQL Workbench (Database design & queries)
Excel (Data dictionary)
SQL (Queries & data retrieval)

🔍 Key Steps & Analysis
✔️ Database Design

Defined entity relationships, normalized data, and implemented foreign keys.
Imported structured tables into MySQL Workbench.

✔️ SQL Queries for Business Insights

Market trends: Identifying price fluctuations per region.
Property distribution: Number of listings by municipality and type.
Sales performance: Most expensive and least expensive properties.
Regional demand: Areas with the highest transaction volume.
Average price per m²: Calculating real estate valuation trends.


📈 Results & Insights
High-demand regions correspond to urban centers with rising property values.
Significant price variation across different property types and locations.
Sales cycles show seasonal trends influencing real estate transactions.


📎 Repository Structure
/real-estate-db  
│── data/              # Raw CSV files & Excel data dictionary  
│── schema/            # Relational schema diagram  
│── sql_queries/       # SQL scripts answering business questions  
│── README.md          # Project documentation  
💡 Future Improvements: Implement data visualization with Python (Matplotlib, Seaborn) or Power BI for better insights. 🚀
