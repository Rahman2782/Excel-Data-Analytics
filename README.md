# Coffee Sales Dashboard
An end-to-end Excel data analysis project featuring a dynamic and interactive dashboard for coffee bean sales data. This project demonstrates comprehensive data gathering, transformation, analysis, and visualization techniques using advanced Excel functions and features.

## Project Overview
This project analyzes coffee bean sales data to provide actionable business insights through an interactive dashboard. Users can track sales trends, identify top-performing products and customers, and analyze performance across different markets and customer segments.

## Interactive Dashboard Components
- **Total Sales Over Time:** Line chart tracking sales trends by coffee type across months and years
- **Sales by Country:** Bar chart displaying geographical performance rankings
- **Top 5 Customers:** Identification of highest-value customers
- **Dynamic Filters:** Timeline and slicers for interactive data exploration by:
   - Date ranges
   - Roast type
   - Package size
   - Loyalty card status
 
## Technical Skills
### Data Gathering & Transformation

- XLOOKUP Function: Retrieved customer information (name, email, country) from separate tables based on customer ID
- INDEX MATCH: Dynamically populated product details (coffee type, roast type, size, unit price) using flexible lookup formulas
- Conditional Logic: Implemented multiple IF functions to convert abbreviated codes into readable full names

### Data Cleaning & Structuring

- Duplicate Detection: Used Remove Duplicates feature to ensure data integrity
- Excel Tables: Converted data ranges to structured tables for automatic pivot table updates
- Data Formatting: Applied consistent date formats (MMM format), number formatting with thousand separators, and unit labels (kg, £)
