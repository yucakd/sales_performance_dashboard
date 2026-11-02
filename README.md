# Sales Performance Dashboard

An interactive **sales performance dashboard** built in Excel. It summarizes 2,000 sales orders with Pivot Tables and charts, and can be filtered by region, sales channel, customer type and date using slicers and a timeline.

## Key Metrics

| Metric | Value |
|---|---|
| Total orders | 2,000 |
| Total revenue | 3,462,605 |
| Average revenue per order | 1,731 |
| Total quantity sold | 7,552 |

## Dashboard Contents

- **Monthly revenue trend** (line chart)
- **Revenue by region** (bar chart)
- **Revenue by product category** (bar chart)
- **Revenue by sales channel** (doughnut chart)
- **Top 5 products by revenue** (bar chart)
- Interactive filtering with Slicers and a Timeline

## Dataset

The `Sales_Data` sheet contains 2,000 rows of sample 2026 sales data.

| Column | Description |
|---|---|
| Order ID | Order number |
| Date | Order date |
| Region | Central, East, North, South, West |
| Sales Channel | Online, Retail Store, Corporate Sales, Marketplace |
| Customer Type | New / Returning |
| Product Category | Computers, Monitors, Networking, Storage, Accessories, Office Supplies |
| Product | Product name |
| Salesperson | Sales rep (15 people) |
| Quantity | Units sold |
| Unit Price | Price per unit |
| Discount | Discount rate |
| Revenue | Net revenue after discount |

## Workbook Structure

1. `Sales_Data` – raw data
2. `Summary_Pivot` – Pivot Table summaries (source of the dashboard charts)
3. `Dashboard` – charts, slicers and timeline

## Insights

- **Computers** account for about 59% of total revenue (~2.06M).
- **Central** is the top region (~803K); **West** is the lowest (~587K).
- **Online** is the strongest channel (~1.11M), followed by **Corporate Sales**.
- **Gaming Laptop** is the top product by revenue (~666K).
- Monthly revenue peaks in **June** (~374K) and bottoms out in **February** (~219K).

## Usage

1. Download `Sales_Performance_Dashboard.xlsx`.
2. Open it in Microsoft Excel 2013 or later (required for Slicers and Timeline).
3. Use the slicers and timeline on the `Dashboard` sheet to filter the data.

> Note: Slicers and Timelines don't work in LibreOffice or Google Sheets.

## Tools

Microsoft Excel – Pivot Tables, Pivot Charts, Slicers, Timeline
