# Mavi Retail Sales and Return Analysis

This project is an end-to-end business intelligence workflow analyzing Mavi store sales data using Python and Power BI. The objective goes beyond standard revenue tracking to identify product-level return trends, discount dependency, and inflation-adjusted volume growth.

## Dashboard Previews

![Detailed Analysis](graph1.png)

![Key Performance Indicators](graph1.png)

## Data Processing and Methodology

* Analyzed 34,000 transaction records spanning from February 2024 to January 2025.
* Retained transactions with positive quantities but negative amounts to preserve inventory count and net revenue accuracy, as these likely represent gift card usage or system corrections.
* Cross-referenced products with high return volumes and high exchange card usage to pinpoint potentially problematic items (e.g., sizing inaccuracies or fit defects).
* Calculated growth rates based on net units sold rather than revenue to isolate true consumer demand shifts from inflation and price hikes.
* Exported all processed aggregations into a single, multi-sheet Excel file optimized for Power BI data modeling.

## Key Insights

* **September:** The most commercially healthy month, featuring the highest revenue and lowest return rate, driven by strong organic demand.
* **May:** The weakest month, characterized by the lowest revenue and the highest return rate, where nearly half of the sold items were returned.
* **July:** Recorded the highest discount rates despite mid-range sales volume, indicating a heavy reliance on markdowns rather than natural demand.
* **Average Order Value (AOV):** Steadily climbed from 838 TL in February to 1126 TL in January, showing increased customer spending per transaction regardless of total sales volume.

## Technologies Used

* **Data Preparation:** Python, Pandas
* **Visualization:** Power BI
* **Version Control:** Git, GitHub Project Structure (.pbip)
