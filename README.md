# AdventureWorks Sales & Marketing Performance Dashboard

## 📊 Project Overview
This repository features a professional, interactive **Power BI Dashboard** built using the Microsoft **AdventureWorks** dataset. Designed to closely simulate a modern corporate retail environment, the solution tracks and analyzes global sales performance, customer intelligence, and product patterns to empower executive decision-making.

The dashboard implements an optimized **Star Schema** data model and utilizes advanced **DAX** expressions for robust, dynamic analytical insight.

---

## 🛠️ Key Features & Technical Highlights

### 1. Interactive Navigation & UI/UX
* **Seamless Navigation:** Implemented custom **Buttons and Bookmarks** acting as a clean left-hand vertical navigation pane to toggle flawlessly between dashboard sections.
* **Pop-out Filter Pane:** Designed an intuitive, collapsible **Filter/Slicer Panel** driven by hidden bookmarks that allows users to segment data dynamically without cluttering the main visual canvas.
* **Advanced Visual Tooltips:** Developed dedicated, analytical custom **Hover Tooltips** (e.g., dynamic trend sparklines and KPI summaries) that update instantly depending on the active data context.

### 2. Multi-Page Comprehensive Analysis
* **Executive Overview:** High-level dashboard tracking core enterprise metrics: Total Revenue ($25M), Total Profit ($10M), Profit Margin (41.97%), and Return Rate (2.17%). Includes a comprehensive revenue trend timeline alongside granular monthly targets.
* **Product Performance Analytics:** Built with custom dynamic parameters (e.g., *Price Parameter* scenario testing and *Metric Parameter* selections) coupled with target gauges to isolate top-selling categories like *Tires and Tubes* and track high-return liabilities.
* **Customer Intelligence & Demographics:** Segmented active customer bases (17.42K) by professional career path, geographic location, and income bracket (Low/Medium/High) to accurately identify high-value consumer profiles like *Mr. Maurice Shan* ($12K revenue).

---

## 📐 Relational Architecture (Star Schema)
To drive ultra-fast calculation processing and reporting efficiency, the model organizes messy transactional inputs into a rigid dimensional architecture:
* **Fact Tables:** `FactInternetSales`, `FactResellerSales`
* **Dimension Tables:** `DimCustomer`, `DimProduct`, `DimGeography`, `DimDate`, `DimSalesTerritory`

---

## 🧠 Core Technical Stack
* **Power BI Desktop:** Core reporting canvas, conditional matrix formatting, and visual layout.
* **Advanced DAX Expressions:** Time-intelligence measures (YoY / MoM trends), target evaluations, and dynamic selection logic.
* **Power Query (M):** Comprehensive ETL pipeline ensuring strict data cleansing, type-casting, and semantic calendar tables.

---

## 🚀 How to View the Project
1. Clone this repository or download the `.pbix` template file directly from the `/Dashboard` directory.
2. Launch the dashboard using **Power BI Desktop**.
3. Utilize the sidebar menu icons to navigate, expand the filter fly-out to segment timelines, and hover over tabular charts to activate the custom sparkline tooltips!
