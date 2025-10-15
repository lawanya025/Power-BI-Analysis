# E-commerce Sales Performance Analysis Dashboard

### 1. Short Description / Purpose

The E-commerce Sales Performance Dashboard is a visually engaging analytical report designed to help business stakeholders explore sales data across various dimensions. It focuses on highlighting **Total Sales, Profit, Quantity Sold,** and analyzing performance by **State, City, Product Category, Sub-Category,** and **Payment Mode**. This tool is intended for use by sales managers, marketing teams, logistics planners, and business analysts seeking to make data-driven decisions to boost revenue and profit margins.

---
### 2. Tech Stack

The dashboard was built using the following tools and technologies:

* **<big>📊 Power BI Desktop</big>** – Main data visualization platform used for report creation.
* **<small>📂 Power Query (M Language)</small>** – Data transformation and cleaning layer used for merging the two source files (`Details.csv` and `Orders.csv`) based on a common `Order ID`.
* **🧠 DAX (Data Analysis Expressions)** – Used for calculated measures and Key Performance Indicators (KPIs) like Total Sales and Total Profit.
* **📝 Data Modeling** – Relationship established between the two main tables (`Details` and `Orders`) to enable cross-filtering of sales metrics by geographical and customer details.
* **📁 File Format** – `.png` for dashboard preview and `.csv` for source data.

---
### 3. Data Source

The data is sourced from two CSV files detailing e-commerce transactions:

| File Name | Contains |
| :--- | :--- |
| **`Details.csv`** | Transactional data: `Order ID`, **Amount**, **Profit**, `Quantity`, `Category`, `Sub-Category`, and `PaymentMode`. |
| **`Orders.csv`** | Order and Customer data: `Order ID`, `Order Date`, `CustomerName`, **State**, and **City`. |

<small>*The data covers orders from an Indian e-commerce company across 2018.*</small>

---
### Features / Highlights

### 💡 Business Problem & Goal

The global e-commerce market is highly competitive. Our company needs a centralized, interactive view to move beyond raw data and quickly identify key performance drivers like **profitability by product** and **most valuable geographic markets** for strategic resource allocation.

<br>

### 📊 Walkthrough of Key Visuals

| Visual | Description | Value |
| :--- | :--- | :--- |
| **<big>Key KPIs (Top Row)</big>** | Displays Total Sales, Total Profit, and Total Quantity sold. | Provides an instant health check of the business. |
| **Sales and Profit by Category** | Compares sales/profit across main product categories (e.g., Clothing, Electronics, Furniture). | Easily identifies which categories are generating the most revenue and profit. |
| **Sales by State (Map)** | Shows sales distribution across different States (Geographic Strategy). | Highlights key markets for focused marketing and logistics planning. |
| **Profit by Payment Mode** | Displays profit generated from each PaymentMode (e.g., COD, UPI). | Guides in offering incentives to shift customers toward more profitable payment methods. |

<br>

### 🚀 Business Impact & Key Insights

* **Profit Optimization (The Big Win):** The dashboard helps identify products with **negative profit** in the **Sub-Category** breakdown. This pinpoints urgent areas for investigation (e.g., high return costs, pricing errors) to secure immediate profit gains.
* **<small>Geographic Strategy:</small>** **Maharashtra** and **Uttar Pradesh** stand out as key markets on the map, allowing logistics and marketing teams to prioritize these regions.
* **<small>Inventory & Product Focus:</small>** Insights inform the merchandising team on which categories to **stock more** (high sales) and which to **re-evaluate or discontinue** (low sales, negative profit).

---
Screenshots / Demos: ![E-commerce Dashboard Screenshot]([Snapshot of the Dashboard.png](https://github.com/lawanya025/Power-BI-Analysis/blob/main/E-commerce%20Sales%20Performance%20Analysis%20Dashboard/Snapshot%20of%20the%20Dashboard.png))



```
