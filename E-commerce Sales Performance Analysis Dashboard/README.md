E-commerce Sales Performance Analysis Dashboard:

A dynamic, interactive data visualization report designed to analyze and monitor key sales and profitability metrics for an e-commerce business. This dashboard provides a consolidated view of transactional performance, customer geography, product category performance, and payment trends.

Short Description / Purpose:
The E-commerce Sales Performance Dashboard is a visually engaging analytical report designed to help business stakeholders explore sales data across various dimensions. It focuses on highlighting Total Sales, Profit, Quantity Sold, and analyzing performance by State, City, Product Category, Sub-Category, and Payment Mode. This tool is intended for use by sales managers, marketing teams, logistics planners, and business analysts seeking to make data-driven decisions to boost revenue and profit margins.

Tech Stack:
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main data visualization platform used for report creation.

📂 Power Query (M Language) – Used for data transformation and cleaning, including merging the two source files (Details.csv and Orders.csv) based on a common Order ID.

🧠 DAX (Data Analysis Expressions) – Used for calculated measures and Key Performance Indicators (KPIs) like Total Sales and Total Profit.

📝 Data Modeling – Relationship established between the two main tables (Details and Orders) to enable cross-filtering of sales metrics by geographical and customer details.

📁 File Format – .png for dashboard preview and .csv for source data.

Data Source
The data is sourced from two CSV files detailing e-commerce transactions:

Details.csv: Contains transactional data including Order ID, Amount, Profit, Quantity, Category, Sub-Category, and PaymentMode.

Orders.csv: Contains order and customer geographic data including Order ID, Order Date, CustomerName, State, and City.

The data covers orders from an Indian e-commerce company across 2018.

Features / Highlights
This section outlines the business context, goals, a brief walkthrough, and the actionable insights derived from the dashboard.

• Business Problem
An e-commerce company needs a quick, centralized, and interactive way to track its sales performance. Relying solely on raw spreadsheet data makes it difficult to:

Quickly assess the overall profitability and the extent of sales losses (negative profit).

Identify the top-performing and underperforming product categories and sub-categories.

Pinpoint the most valuable geographical markets (States and Cities) for focused marketing and logistics planning.

Determine the preferred customer payment methods for strategic sales promotion design (e.g., UPI vs. COD).
• Goal of the Dashboard
To deliver a comprehensive, single-page visual tool that:

Provides an immediate, high-level overview of the e-commerce business's sales and profit health.

Enables users to drill down into performance by Category, Sub-Category, and Geography.

Facilitates data-driven strategies for inventory management, marketing campaigns, and payment system optimization.
• Walkthrough of Key Visuals
The dashboard is structured to present high-level KPIs first, followed by granular distribution and segmentation charts:

Visual	Description	Value
KPI Cards (Top Row)	Displays Total Sales, Total Profit, and Total Quantity sold for the selected period/filter.	Provides an instant health check of the business.
Sales and Profit by Category (Bar Chart)	Compares the total sales and total profit across the main product categories (e.g., Clothing, Electronics, Furniture).	Easily identifies which categories are generating the most revenue and profit.
Sales by State (Map Visual)	A map showing the sales distribution across different States.	Highlights key geographic markets, with the size of the bubble often indicating sales volume.
Sales by Sub-Category (Bar Chart)	Breaks down sales performance into finer product segments (e.g., Saree, Phones, Bookcases).	Useful for optimizing product focus and inventory.
Profit by Payment Mode (Bar Chart)	Shows the total profit generated from each PaymentMode (e.g., COD, UPI, Credit Card, EMI).	Reveals customer preferences and the financial impact of different payment methods.
Sales and Profit Trend (Line Chart)	A dual-axis line chart showing sales and profit trend over time (e.g., by month or quarter).	Helps in identifying seasonal patterns, performance dips, or the impact of past campaigns.

• Business Impact & Insights
The analysis from this dashboard enables the following actions:

Profit Optimization: By analyzing profit by Sub-Category, the business can quickly identify products with negative profit and investigate the reasons (e.g., high return rates, incorrect pricing, or logistics costs) to fix them immediately.

Geographic Strategy: The Sales by State/City map allows the logistics team to optimize delivery networks and the marketing team to target high-value states like Maharashtra and Uttar Pradesh with specific campaigns.

Inventory & Product Focus: The Sales by Category/Sub-Category visuals inform the merchandising team on which products to stock more (high sales) and which to re-evaluate or discontinue (low sales, negative profit).

Payment & Conversion: Understanding the breakdown of sales and profit by PaymentMode can guide the finance team in offering incentives (e.g., discounts on UPI/Credit Card payments) to shift customers toward methods that are more profitable or logistically simpler than COD.

6.	Screenshots / Demos
https://github.com/lawanya025/Power-BI-Analysis/blob/main/E-commerce%20Sales%20Performance%20Analysis%20Dashboard/Snapshot%20of%20the%20Dashboard.png
