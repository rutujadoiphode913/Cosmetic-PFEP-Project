# Cosmetic-PFEP-Project
NAME: Rutuja Anil Doiphode
This project is an example of PFEP and ERP , how it is used and how the dataset looks in the manufacturing company solely designed by me for education purposes.
🏭 **Factory Layout & Material Flow Dashboard – README
📘 Overview**

This Excel project integrates a Plan for Every Part (PFEP) and an ERP transaction dataset to simulate and analyze a cosmetic manufacturing facility in Boston, USA.
It enables data-driven optimization of factory layout, material flow, supplier performance, and inventory management using pivot tables and visual charts.

📦 Files Included
| File Name                                 | Description                                                                                                       |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| `Cosmetic_PFEP_Boston_100Entries.xlsx`    | Master PFEP dataset with 100 structured part records including storage, flow, supplier, and logistics parameters. |
| `ERP_Transactions_Boston_100Entries.xlsx` | Linked ERP dataset containing purchase, inventory, and supplier transaction data for the same parts.              |
| `Factory_Visualization_Dashboard.xlsx`    | Combined Excel dashboard with six pivot-style visualizations for real-time analysis and insights.                 |

**⚙️ Data Relationships**

The datasets are linked through the Part Number and Supplier Name fields.
Use them together in Excel or Power BI for unified insights.

| PFEP Field         | ERP Field            | Relation                              |
| ------------------ | -------------------- | ------------------------------------- |
| `Part Number`      | `Part Number`        | One-to-one link for product tracking  |
| `Supplier Name`    | `Supplier Name`      | Aggregation for supplier performance  |
| `Storage Location` | `Warehouse Location` | Maps material flow and storage layout |

**📊 Dashboards & Charts**

Average Distance vs Cycle Time (PFEP)

Identifies bottlenecks in internal logistics and long travel distances.

Supplier Lead Time Performance (ERP)

Compares reliability of major U.S. suppliers.

Route Capacity vs Daily Usage (PFEP)

Shows utilization rate of logistics routes for milk runs and tuggers.

Warehouse Space Utilization (PFEP)

Pie chart visualizing occupancy levels across WH-A to WH-E.

Inventory vs Reorder Point (ERP)

Highlights stock levels nearing reorder thresholds.

Total Cost vs Annual Demand (ERP)

Displays high-value SKUs driving procurement spend (Pareto view).
