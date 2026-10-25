# 📊 E-Commerce Sales Analysis using Power BI

## 📌 Project Overview

This project focuses on analyzing an **E-Commerce Sales Dataset** using Microsoft Power BI Desktop. The objective is to apply Data Analysis Expressions (DAX) to create calculated columns and measures, develop interactive visualizations, and analyze sales performance, profitability, and business trends.

The project builds on the data transformation and data modeling completed in the previous assignment, with an emphasis on DAX calculations, analytical thinking, and data storytelling.

This project demonstrates my practical skills in data analysis, business intelligence, data visualization, and dashboard development as an aspiring Data Analyst.

## 🎯 Project Objectives

- Create calculated columns using DAX.
- Develop DAX measures to calculate important business metrics.
- Analyze sales performance against targets.
- Evaluate profitability and product sub-category performance.
- Identify monthly sales trends and geographic sales patterns.
- Build interactive and informative Power BI visualizations.
- Present business data in a clear and meaningful way.

## 🗂️ Dataset Description

The project uses three datasets:

| Dataset | Description |
|---|---|
| List of Orders | Contains order dates, customer names, cities, states, categories, amounts, and profits. |
| Order Details | Contains order IDs, product categories, sub-categories, quantities, amounts, and profits. |
| Sales Target | Contains product categories, order months, and sales targets. |

The datasets were imported into Power BI Desktop, and the required data transformation and relationships were established as part of the previous assignment.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** – Data modeling, DAX calculations, and dashboard development.
- **DAX (Data Analysis Expressions)** – Calculated columns and measures.
- **Power Query** – Data cleaning and transformation.
- **Data Visualization** – Interactive charts, cards, matrices, and maps.
- **GitHub** – Project documentation and portfolio management.

## 🧮 DAX Calculations

### Calculated Columns

The following calculated columns were created in the `Order Details` table:

1. **Category Type** – Combines the Category and Sub-Category columns into a single column.
2. **Revenue per Order** – Calculates revenue using Amount × Quantity.
3. **Sales Category** – Categorizes sales as Above Average or Below Average based on the Amount value.

### Measures

The following DAX measures were developed:

1. **Order Count** – Calculates the total number of orders in the Order Details table.
2. **Average Profit in Delhi** – Calculates the average profit for orders placed in Delhi.
3. **Year-to-Date (YTD) Sales** – Calculates accumulated sales from the beginning of the year up to the relevant order date.

## 📈 Data Visualizations

The Power BI report includes the following visualizations:

| Visualization | Purpose |
|---|---|
| Sales Target Achievement by Category | Compares actual sales with sales targets across categories using a clustered column chart. |
| Maximum Profit Margin by Sub-Category | Analyzes maximum profit margin across product sub-categories using a donut chart. |
| Monthly Sales Trend | Displays monthly sales trends using a line chart. |
| Profit vs. Quantity by Sub-Category | Examines the relationship between profit and quantity sold using a scatter chart. |
| Total Sales Amount vs. Target | Uses cards to display total sales and sales target for quick comparison. |
| Minimum Target by Segment | Uses a multi-row card to display the minimum target for each segment. |
| Sales Performance Matrix | Compares actual sales and targets across categories and months. |
| Geographic Sales Analysis | Displays sales by city on a map to identify regional patterns. |
| Sales Distribution by Sub-Category | Uses a treemap to visualize sales distribution across sub-categories. |
| Order Count Analysis by State | Uses a funnel chart to visualize order counts across states. |

## 🔍 Key Skills Demonstrated

- Data cleaning and transformation
- Data modeling and table relationships
- Calculated columns and DAX measures
- Aggregations and filter context
- Time intelligence and YTD calculations
- Sales and profitability analysis
- Target achievement analysis
- Interactive dashboard design
- Data storytelling and business reporting

## 📁 Project Files

The repository is organized to include the following deliverables:

```text
E-Commerce-Sales-Analysis-Power-BI/
│
├── README.md
├── Power BI Assignment 02 Final.pbix
├── PowerBI Assignment 02 Final.pdf
└── Screenshots/
    ├── dashboard-overview.png
    ├── sales-target-analysis.png
    ├── monthly-sales-trend.png
    └── geographic-sales-analysis.png
```

*Note: The folder and screenshot names above are suggested examples. Add the files that are actually available in your repository.*

## 📄 Deliverables

- **Power BI Report (.pbix):** Contains the data model, calculated columns, DAX measures, and visualizations.
- **Project Documentation (.pdf):** Contains screenshots of DAX formulas, visualizations, dashboard layout, and explanations of the visuals.

## 💡 Learning Outcomes

Through this project, I gained practical experience in writing DAX expressions, developing analytical measures, comparing sales against targets, and designing visual reports that help communicate business performance.

This project strengthened my understanding of how Power BI can transform raw business data into meaningful insights that support data-driven decision-making.

## 👨‍💻 About Me

I am an **aspiring Data Analyst** building my portfolio through hands-on projects in data analysis, business intelligence, and data visualization.

I am continuously developing my skills in Power BI, SQL, Excel, and data storytelling to solve business problems and communicate insights effectively.


---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
