# SQL-Integrated-Power-BI-Sales-Intelligence-Dashboard

## Project Overview:
This project presents an interactive Sales Performance Dashboard built in Power BI for Awesome Chocolates.
The objective of this dashboard is to analyze:
- Total Sales performance
- Total Boxes sold
- Shipment count & efficiency

## Project
- <a href="https://github.com/hrcharan001/SQL-Integrated-Power-BI-Sales-Intelligence-Dashboard/blob/main/PBI%20Linked%20with%20SQL-%20Project.pbix">Click To View</a>

<img width="1868" height="636" alt="SS of Project" src="https://github.com/hrcharan001/SQL-Integrated-Power-BI-Sales-Intelligence-Dashboard/blob/main/Awesome%20Chocolates%20-%20Dashboard(SS).png" />

## Data Source & SQL Integration:
- SQL–Power BI Connection
- Server: localhost
- Database: awesome chocolates
- Connection Mode: Import

## Custom SQL queries were used inside Power Query
- Example SQL query used:
select * 
from geo g
join sales s on g.GeoID = s.GeoID
where g.geo = 'Canada';

## Parameter-Based Filtering
A dynamic Power BI Parameter was created to filter data at the SQL level.

## Project Highlights

✔ SQL Database Integration
✔ Dynamic Parameter Filtering
✔ Data Modeling with Relationships
