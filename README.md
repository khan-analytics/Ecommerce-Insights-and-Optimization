# Ecommerce Insights and Optimization

## Project Overview

**Ecommerce Insights and Optimization** is an end-to-end data analytics portfolio project focused on understanding e-commerce product performance and order-item data.

The goal is to assess data quality, analyze the available data, identify useful business insights, and present findings through SQL queries, Python analysis, and an interactive Power BI dashboard.

This project follows a structured analytics workflow, from understanding the business problem to communicating data-driven recommendations.

## Business Problem

E-commerce businesses need reliable data to understand product performance, sales value, and shipping-related costs.

However, raw datasets may contain missing values, duplicate records, inconsistent data, and incorrect data types. These issues can affect the accuracy of business reports and decisions.

This project will examine the available datasets, validate their quality, and use appropriate analytics tools to answer relevant business questions.

## Project Objectives

* Understand the business problem and define relevant analytical questions.
* Assess the quality and structure of the available datasets.
* Identify missing values, duplicate records, inconsistent values, and data type issues.
* Clean and prepare the data for analysis.
* Use SQL to answer business questions.
* Use Python for data cleaning, exploratory data analysis, and visualization.
* Develop an interactive Power BI dashboard.
* Identify meaningful patterns and communicate business insights.
* Provide practical, data-supported recommendations.

## Datasets

This project uses two CSV files.

### 1. Products Dataset

**File:** `products.csv`

This dataset contains information about products.

Key columns include:

* `product_id`
* `product_category_name`
* `product_name_length`
* `product_description_length`
* `product_photos_qty`
* `product_weight_g`
* `product_length_cm`
* `product_height_cm`
* `product_width_cm`

This dataset can help analyze product categories, product information completeness, and product dimensions.

### 2. Order Items Dataset

**File:** `order-items.csv`

This dataset contains information about products included in orders.

Key columns include:

* `order_id`
* `order_item_id`
* `product_id`
* `seller_id`
* `shipping_limit_date`
* `price`
* `freight_value`
* `product_category_name`
* `product_weight`

This dataset can help analyze order-item records, listed prices, freight values, and shipping-related information.

**Data limitation:** The listed columns do not include an explicit purchase date or product quantity. Therefore, time-based sales trends and quantity-based metrics will only be developed if suitable fields are available from additional data. The meaning and units of each field will also be validated before analysis.

## Tools and Technologies

* **Python:** Data cleaning, data manipulation, exploratory data analysis, and visualization.
* **Pandas:** Data processing and analysis.
* **NumPy:** Numerical operations and data analysis.
* **Matplotlib and Seaborn:** Data visualization.
* **SQL:** Querying data and answering business questions.
* **Power BI:** Interactive dashboards, KPI reporting, and business visualization.
* **Microsoft Excel:** Data inspection, validation, and analysis where appropriate.
* **Jupyter Notebook:** Interactive analysis and documentation.
* **Git and GitHub:** Version control and project documentation.

## Project Workflow

The project follows these stages:

1. **Business Understanding** — Define the business problem, objectives, and analytical questions.
2. **Data Understanding** — Inspect the datasets, columns, data types, and relationships.
3. **Data Quality Assessment** — Check for missing values, duplicates, invalid values, and inconsistent data.
4. **Data Cleaning and Preparation** — Correct identified data quality issues and prepare suitable datasets for analysis.
5. **SQL Analysis** — Write queries to answer relevant business questions.
6. **Exploratory Data Analysis** — Use Python to explore distributions, patterns, relationships, and unusual values.
7. **Business Insights** — Interpret the results and develop evidence-based recommendations.
8. **Power BI Dashboard** — Build an interactive dashboard using validated metrics.
9. **Final Reporting** — Document the findings, limitations, and recommendations.

## Key Business Questions

The final questions will depend on the results of the data quality assessment and the fields available.

Potential questions include:

* Which product categories have the highest order-item values?
* How are product prices distributed across categories?
* How do freight values vary across order items and product categories?
* Are there missing or inconsistent product details?
* Are there product records that cannot be matched between the two datasets?
* Which data quality issues could affect business reporting?
* What useful insights can be presented in a Power BI dashboard?

These questions will be refined after validating the data. Any conclusions will be based on the actual analysis rather than assumptions.

## Power BI Dashboard

An interactive Power BI dashboard will be developed to present key findings from the analysis.

The dashboard may include:

* Product and category analysis.
* Order-item value analysis.
* Price and freight value comparisons.
* Data quality indicators, where useful.
* KPI cards, charts, and interactive filters.

The final KPIs and visuals will be selected after checking the datasets and confirming that the required metrics can be calculated correctly.

## Data and Metric Limitations

To maintain accurate reporting:

* `shipping_limit_date` will not automatically be treated as the purchase date.
* The `price` column will be validated before deciding how to calculate order-item values.
* Freight value will be analyzed separately unless a justified business metric requires combining it with price.
* Revenue will not be described as profit because product cost and other expense data are not currently listed.
* Product relationships will be validated using `product_id`.
* Missing values, duplicate records, and unmatched product IDs will be assessed before drawing conclusions.

These checks will help ensure that the analysis and dashboard are based on reliable data.

## Project Structure

```text
Ecommerce-Insights-and-Optimization/
│
├── README.md
├── .gitignore
│
├── reference/
│   └── Ecommerce_Analytics_Capstone_Assignment.pdf
│
├── docs/
│   ├── Phase_1_Business_Understanding.md
│   ├── Phase_2_Data_Quality_Assessment.md
│   └── Data_Dictionary.xlsx
│
├── data/
│   ├── raw_data/
│   │   ├── order-items.csv
│   │   └── products.csv
│   ├── processed/
│   └── final/
│
├── notebooks/
│   ├── 01_business_understanding.ipynb
│   ├── 02_data_quality_assessment.ipynb
│   ├── 03_data_cleaning.ipynb
│   ├── 04_sql_analysis.ipynb
│   ├── 05_exploratory_data_analysis.ipynb
│   └── 06_business_insights.ipynb
│
├── sql/
├── dashboard/
└── reports/
```

*Note: This structure describes the planned project organization. Some folders and files may be added as the project progresses.*

## Current Progress

* [x] Initial project structure created.
* [x] Business understanding documentation started.
* [x] Initial notebooks and supporting files added.
* [x] Git repository initialized.
* [x] GitHub repository created and connected.
* [x] Initial project files pushed to GitHub.
* [ ] Complete data quality assessment.
* [ ] Complete data cleaning and preparation.
* [ ] Perform SQL analysis.
* [ ] Perform exploratory data analysis using Python.
* [ ] Develop business insights and recommendations.
* [ ] Build the Power BI dashboard.
* [ ] Complete the final report.

## Expected Outcomes

By completing this project, I aim to demonstrate my ability to:

* Understand business problems and convert them into analytical questions.
* Inspect and validate real-world datasets.
* Clean and prepare data for analysis.
* Use SQL and Python to analyze data.
* Create meaningful visualizations and an interactive Power BI dashboard.
* Explain findings in simple business language.
* Communicate data limitations and provide practical recommendations.
* Maintain a professional analytics project using Git and GitHub.

## Author

**Nasir Khan**
Aspiring Data Analyst | Python | SQL | Power BI | Excel

GitHub: [khan-analytics](https://github.com/khan-analytics)

---

*This project is being developed as part of my practical learning journey in data analytics.*
