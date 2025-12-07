## Project Title / Headline :
Blinkit Sales Analytics: Interactive Dashboard Built with Power BI, PostgreSQL & Python.

## Short Description / Purpose :
Built an end-to-end sales analysis dashboard for Blinkit using Power BI, PostgreSQL, Excel, and Python, showcasing KPIs like total sales, average rating, item categories, and outlet performance. Enabled dynamic filtering by outlet size, location, and item type to uncover business insights and support strategic decisions.

## Technologies Used :

1. **Python** – Used to **import and insert Blinkit sales data into PostgreSQL**, leveraging libraries such as:

   * `pandas` – For reading and structuring data from Excel/CSV files.
   * `sqlalchemy` / `psycopg2` – For establishing connections and executing insert operations to PostgreSQL.

2. **PostgreSQL** – Served as the **primary database** for storing cleaned sales data. SQL queries were used for aggregations, filtering, and data preparation for Power BI.

3. **Microsoft Excel** – Used as a **source file** containing raw sales data and sometimes for early-stage formatting.

4. **Power BI** – The main tool for building the **interactive sales dashboard**, including:

   * Visualizations (bar charts, line graphs, KPI cards, maps, etc.)
   * Slicers for outlet size, fat content, item type, and city
   * Page-level and report-level filters for deeper insights

5. **DAX (Data Analysis Expressions)** – Used to create calculated **measures and KPIs** (e.g., total sales, sales %, average rating) within the Power BI data model.

6. **Power Query (M Language)** – Used to **clean and transform** data from PostgreSQL before loading it into the Power BI model (e.g., data type changes, column filtering, null handling).

## Features / Highlights :

• **Business Problem**
Blinkit needed a consolidated system to track sales performance across diverse outlet types, sizes, and regions. The absence of a centralized view made it difficult to evaluate growth, identify top-performing outlets, and prioritize resource allocation.

• **Goal of the Dashboard**
To develop an interactive sales analysis dashboard that:

Enables regional and outlet-wise performance tracking

Highlights high- and low-performing product categories

Offers dynamic filtering for focused analysis

Supports strategic decision-making by leadership and ops teams

•***Walkthrough of Key Visuals***

**KPI Cards (Top Center):**

Total Sales: $1.20M

Number of Items: 8,523

Average Sales: $141

Average Rating: 3.9

**Donut & Bar Charts (Middle Left):** 

Sales distribution by fat content (Low Fat vs. Regular)

Sales performance by item types (Fruits, Snacks, Household, Dairy, etc.)

Outlet performance by tier and fat content

**Line Chart (Top Right):**

Outlet establishment trend over years, showing expansion and peak phases

**Donut Chart (Bottom Right):**

Outlet sales split by size: Small, Medium, High

**Funnel (Outlet Location):**

Tier-wise sales comparison (Tier 1, 2, 3)

**Matrix (Bottom Right):**

Outlet Type-wise breakdown with total sales, average sales, item count, average rating, and visibility score

**Filter Panel (Left):**

Enables selection by outlet location type, outlet size, and item type for detailed segmentation

•***Business Impact & Insights***

**Outlet Strategy:** Tier 3 regions contribute the highest sales (~$472K), suggesting potential for expansion in semi-urban/rural areas.

**Product Focus:** Top-selling categories are Fruits, Snacks, and Household items, indicating where to concentrate inventory and promotions.

**Store Size Effectiveness:** Medium-sized outlets yield the highest total sales, guiding future store development.

**Customer Ratings:** Average rating of 3.9 maintained across outlet types, showing consistent service quality.

**Sales Trend Analysis:** A visible dip in outlet expansion post-2019 suggests a strategic slowdown or external factors impacting growth.



## Dashboard Previews

### 🔵 Blinkit Sales Report  
![Blinkit Dashboard](https://github.com/AnkitSingh06/Blinkit-Sales-Analysis/blob/main/Blinkit%20Dashboard.png)



                      
