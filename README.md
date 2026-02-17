# SQL-Integrated-Power-BI-Sales-Intelligence-Dashboard

## Project Overview:
This project presents an interactive Sales Performance Dashboard built in Power BI for Awesome Chocolates.
The objective of this dashboard is to analyze:
- Total Sales performance
- Total Boxes sold
- Shipment count & efficiency

## Data Source & SQL Integration:
SQL–Power BI Connection
Server: localhost
Database: awesome chocolates
Connection Mode: Import

## Custom SQL queries were used inside Power Query
Example SQL query used:
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
