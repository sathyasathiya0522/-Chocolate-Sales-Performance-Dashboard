🍫 Chocolate Sales Performance Dashboard
📌 Project Overview
The Chocolate Sales Performance Dashboard provides an overview of shipment sales, product box volumes, geographic performance, monthly sales trends, and order-status distribution. It is designed to help users explore sales performance and monitor key shipment metrics.
🎯 Project Objectives
- Monitor overall sales value, boxes shipped, and shipment volume.
- Compare sales performance across geographic IDs.
- Identify products contributing the highest box volumes.
- Review monthly sales trends.
- Understand the distribution of orders by status.
🧰 Tools & Technologies
- Power BI – dashboard design and data visualization
- Microsoft Excel – source dataset
- Power Query / Data Model – data preparation and reporting (where used in the project)
📂 Dataset
The source workbook, Chocolate database.xlsx, contains two worksheets:
1. Shipments
Contains 7,905 shipment records and the following fields:
- ShipmentID – shipment identifier
- SPID – salesperson identifier
- PID – product identifier
- GID – geographic identifier
- Shipdate – shipment date and time
- Amount – sales amount
- Boxes – number of boxes
- Order_Status – order status
2. Dimension Data
Contains lookup information for products, geography, and salespeople, including product/category/cost per box, country/region/geographic ID, and salesperson/team/salesperson ID.
📊 Dashboard Features
- Sales Trend: Sales amount over the shipment timeline.
- Sales by Geography ID: Compares sales across G1–G6.
- Shipment Details Table: Ranks geographic IDs by sales amount.
- Boxes by Product ID: Compares box volume across products.
- Monthly Sales: Shows sales amount by shipment month.
- Order Status Distribution: Displays the percentage mix of order statuses.
- Sales by Order Status: Compares sales amount by order status.
- Date Range Filter: Allows users to filter the dashboard by a selected date range.
📈 Key Metrics & Insights
The following figures are calculated from the uploaded Shipments worksheet (all rows, without an additional date filter):
Metric	Value
Total Sales	44.69M
Total Boxes	3.78M
Total Shipments	7,905
Average Sales per Shipment	5,653.69
Lowest Shipment Amount in source data	2.25
Highest Shipment Amount in source data	33,484.50


Geographic performance
- G6 records the highest sales amount: 10,541,805.75.
- G1 follows with 10,393,677.00.
- G3 records the lowest sales amount: 2,658,602.25.
Order status
Status	Shipments	Share
Delivered	6,356	80.4%
Shipped	793	10.0%
Placed	385	4.9%
Cancelled	371	4.7%


- Delivered shipments account for 80.4% of all shipment records.
- The source data covers 01 Jan 2023 to 28 Aug 2025.
🖼️ Dashboard Preview

📁 Suggested GitHub Repository Structure
Chocolate-Sales-Performance-Dashboard/
├── README.md
├── Chocolate_Sales_Performance_Dashboard.pdf
├── chocolate_dashboard_preview.png
└── Chocolate database.xlsx
🚀 How to Use
1. Download or clone this repository.
2. Open the Power BI report file if the .pbix file is included in the repository.
3. If needed, update the Excel data source path in Power BI.
4. Refresh the data and use the date range filter to explore the dashboard.
Note: The uploaded materials include the dashboard PDF and Excel workbook. A Power BI .pbix file was not included in the source files.

👤 Project
Chocolate Sales Performance Dashboard
A data visualization project focused on sales, shipment, product, geography, and order-status analysis.
