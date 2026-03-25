# SuperStore Global Performance Dashboard 📊



## Project Overview

A fully interactive Excel-based data application designed to track global sales performance, evaluate regional profitability, and perform dynamic "What-If" shipping cost analysis. 



This project transforms raw transactional data into a premium, app-like interface, demonstrating advanced data modeling, dynamic array logic, and UI/UX design principles.



![Dashboard Preview](Dashboard_Screenshot.png) 

*(Note: Upload your screenshot to the repo, and this link will display it here)*



## 🛠️ Technical Skills Demonstrated

* **Data Modeling:** Integrated multiple relational tables (Orders, People, Returns) using Excel's Data Model to calculate distinct counts (e.g., Unique Customers) and aggregate metrics.

* **Dynamic Scenarios (What-If Analysis):** Built a custom calculation engine using Form Controls (Spin Button) and helper cells to project real-time profit margins based on variable shipping cost reductions.

* **UI/UX Design:** Engineered a modern, dark-theme interface utilizing a Z-pattern layout. Replaced standard spreadsheet visuals with custom-styled slicers, invisible shape links, and data-ink optimization techniques.

* **Advanced Aggregations:** Utilized PivotCharts, GETPIVOTDATA extractions, and custom number formatting to build scalable KPI cards.



## 📈 Key Features

1. **Executive KPI Ribbon:** Tracks Total Sales, Profit, Profit Margin %, Total Orders, Unique Customers, Shipping Costs, and Average Order Value (AOV).

2. **Interactive What-If Engine:** Allows stakeholders to adjust target shipping cost reduction percentages via a UI widget, instantly calculating projected savings and new total profit.

3. **Global Control Panel:** Custom-formatted slicers (Category, Ship Mode, Region) and a dynamic Time slider allow users to filter the entire canvas with a single click.

4. **Deep-Dive Visualizations:**

   * Sales & Profit Over Time (Combo Chart)

   * Global Profitability Distribution (Geospatial Map)

   * Customer Segment Breakdown (Donut/Pie Chart)

   * Regional Shipping Performance (Bar Chart)



## 📂 File Structure

* **Frontend:** `Global_Performance_Dashboard` (The interactive user interface)

* **Backend:** `Calculations` & `Pivot_Calculations` (Hidden calculation layer powering the What-If engine and visuals)

* **Raw Data:** `Orders`, `People`, `Returns` (Hidden source tables)



## How to Use

1. Download the `.xlsx` file.

2. Ensure macros/content are enabled if prompted by Excel.

3. Use the control panel on the left to filter by Date, Category, Region, or Ship Mode.

4. Use the arrows on the green "Target Shipping Cost Reduction" widget to see dynamic profit projections.



## 💡 Key Business Insights



Based on the dashboard analysis, several critical operational and financial trends emerged:



* **The Shipping Margin Squeeze:** Total Shipping Costs ($1.35M) run nearly as high as Total Profit ($1.46M). The What-If analysis proves that even a microscopic 1-2% efficiency gain in shipping logistics yields massive improvements to the bottom line, validating the need for strict supply chain monitoring.

* **Customer Retention vs. Acquisition:** The business generated $12.6M in revenue from a remarkably concentrated pool of just 1,590 unique customers. With over 51,000 total orders, this indicates an incredibly high repeat-purchase rate, though the Average Order Value (AOV) of $246 suggests high-frequency, mid-tier purchasing rather than large enterprise contracts.

* **Heavy Q4 Seasonality:** The time-series analysis reveals a steep dependency on end-of-year performance. Both 2013 and 2014 show massive, disproportionate spikes in both Sales and Profit during the fourth quarter, establishing a clear seasonal business cycle.

* **Geospatial Profit Discrepancies:** While top-line revenue is truly global, actual profitability is highly localized. The map highlights that while core regions (like North America and parts of APAC) are driving the $1.4M net profit, several international territories are actively operating at a net loss (red zones), suggesting a need to re-evaluate pricing or shipping strategies in those specific markets.

* **Segment Concentration:** The "Standard" (48%) and "Loyal" (43%) customer segments drive 91% of the business, indicating that VIP tier programs (9%) are either highly exclusive or an area primed for targeted marketing growth.
