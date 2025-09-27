#  Purchase Performance Analysis

This project is a **Data Analysis and Visualization** case study focusing on **purchases, sales, and inventory performance**.  
It combines **Python (EDA, SQLite, Pandas, Seaborn, Matplotlib)** and **Power BI** to deliver both analytical insights and interactive dashboards.  

## Project Overview
The goal of this project is to analyze **purchase and sales performance** to help answer:
- Which vendors contribute most to total purchases and sales?
- Are there inefficiencies or outliers in purchase prices and freight costs?
- How do purchase costs compare with sales prices (profitability)?
- What trends can be identified across brands, sizes, and vendors?

## Workflow
### 1. Data Ingestion
- Raw `.csv` files loaded into SQLite database.
- Automated ingestion pipeline with Python + SQLAlchemy.
- Logging implemented to monitor ingestion time.

### 2. Exploratory Data Analysis (EDA)
- Count of records per table.
- Missing value & duplicate handling.
- Grouped analysis by **Brand, Purchase Price, Quantity, Dollars**.
- Distribution plots for numerical columns.
- Correlation heatmap to find relationships between variables.

### 3. Power BI Dashboard
- **KPIs:** Total Sales, Total Purchases, Total Price.
- **Donut chart:** Purchase vs Sales share.
- **Bar charts:** Vendor-level dollars & freight, Purchase size trends.
- **Interactive filters** for Vendor, Brand, Size.

## POWER BI DASHBOARD SCREENSHOT:
<img width="959" height="543" alt="image" src="https://github.com/user-attachments/assets/798b08b9-c6ca-49bc-9cf4-d557b942025a" />


## Tech Stack
- **Python:** Pandas, Matplotlib, Seaborn, SQLite
- **SQL:** Data extraction and aggregation
- **Power BI:** Dashboard creation and visualization

## How to Run
1. Clone this repo:
   git clone https://github.com/yourusername/purchase-performance-analysis.git
