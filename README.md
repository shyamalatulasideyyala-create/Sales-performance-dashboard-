# Sales Performance Dashboard

## Project Overview
A beginner-friendly sales analysis project using a sample sales dataset. The project analyzes sales KPIs, regional performance, product performance, and monthly sales trends using Power BI.

## Objectives
- Analyze total sales and quantity sold
- Compare sales across regions
- Identify top-performing products
- Understand monthly sales trends
- Present business insights using an interactive dashboard

## Tools Used
- Power BI
- Microsoft Excel / CSV
- GitHub

## Dataset
The `sales_data.csv` file contains sample sales transactions with:
- Date
- Region
- Product
- Quantity
- Unit Price
- Sales

## Power BI Dashboard
Create these visuals:
1. Total Sales KPI
2. Total Quantity KPI
3. Sales by Region – Column Chart
4. Sales by Product – Bar Chart
5. Monthly Sales Trend – Line Chart
6. Region and Product slicers

## Key DAX Measures
```DAX
Total Sales = SUM(SalesData[Sales])

Total Quantity = SUM(SalesData[Quantity])

Average Sales = AVERAGE(SalesData[Sales])
```

## Project Structure
- `sales_data.csv` – sample dataset
- `README.md` – project documentation
- `dashboard_screenshot.png` – add your Power BI dashboard screenshot here

## How to Use
1. Download `sales_data.csv`.
2. Open Power BI Desktop.
3. Select **Get Data → Text/CSV**.
4. Import `sales_data.csv`.
5. Create the visuals listed above.
6. Save the Power BI file as `Sales_Performance_Dashboard.pbix`.
7. Take a screenshot of the completed dashboard and add it to this repository.

## Author
Syamala Tulasi Deyyala
