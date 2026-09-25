# Retail-sales-Data-Dashboard-Superstore-  # Superstore Sales Analysis – Power BI Report
# Superstore Sales Analysis – Power BI Report

## Overview

This Power BI report provides an interactive analysis of the Superstore dataset, focusing on key business metrics such as **Sales, Profit, Discounts, Customer Segments, Product Categories, Regional Performance, and Returns**.

The report is designed to help identify sales trends, understand which regions and product categories perform well, and analyze how discounts and returns affect overall profitability. Interactive slicers and visualizations allow users to explore the data based on different years, categories, regions, and customer segments.

The completed report can also be exported to PDF for sharing or presentation purposes.

## Project Setup

# 1. Install Power BI Desktop

Download and install Power BI Desktop from the official Microsoft website.

# 2. Import the Superstore Dataset

Open Power BI Desktop and select:

**Home → Get Data → Text/CSV**
Select the `superstore.csv` file from your computer.

Before loading the data, check that the important columns have the correct data types:

* **Order Date** → Date
* **Sales** → Decimal Number
* **Profit** → Decimal Number
* **Discount** → Decimal Number
* **Quantity** → Whole Number
* **Order ID** → Text

If required, select **Transform Data** to make changes in Power Query.

# 3. Clean and Prepare the Data

Use Power Query to perform basic data-cleaning activities, such as:

* Removing blank or unnecessary rows
* Checking for missing values
* Correcting incorrect data types
* Formatting the Order Date column
* Removing duplicate records where required
* Checking for inconsistent or invalid values

After completing the cleaning process, select **Close & Apply** to load the data into Power BI.

## Building the Report

If a pre-built `.pbix` file is available, open it directly in Power BI Desktop and review the existing report.

If you are creating the report from scratch, build the required visuals using the Power BI Report view.Save the completed file as:`superstore_report.pbix`

## Key Visualizations

# 1. Sales and Profit Trend

Visual: **Line Chart**

Use **Order Date** on the X-axis and **Sales** and **Profit** as the values.

This visualization helps track how sales and profitability changed over time, particularly between **2015 and 2018**.

The chart can be used to identify periods of strong sales growth as well as periods where profit did not increase at the same rate.

# 2. Regional Performance

Visual: **Clustered Bar Chart**

Compare **Sales and Profit by Region**.

This helps identify which regions generate higher sales and which regions contribute more to overall profitability.

The report highlights the **West region as one of the strongest-performing regions** based on the dataset.

### 3. Category and Sub-Category Analysis

Visual: **Stacked Bar Chart**

Display **Sales by Category and Sub-Category**.

This allows users to understand which product groups contribute the most revenue.

Technology is a major contributor to sales, with products such as **Phones and Accessories** accounting for a significant share of revenue.

### 4. Sales vs. Profit Analysis

**Visual:** Scatter Chart

Compare **Sales and Profit**, with Discount used as an additional field or visual indicator.

This visualization helps identify orders or products where high sales do not necessarily result in high profit.

The analysis also indicates that **higher discounts can be associated with lower or negative profit on certain orders**, highlighting the need to monitor discount levels carefully.

### 5. Sales by Customer Segment

Visual: ** Pie or Donut Chart**

Display total **Sales by Customer Segment**.

This helps compare the contribution of segments such as:

* Consumer
* Corporate
* Home Office

The Consumer segment contributes the largest share of sales in the analyzed dataset.

### 6. Top 5 Orders by Sales

Visual: **Table**

Create a table showing the **top five orders based on Sales**.

Recommended fields include:

* Order ID
* Order Date
* Customer/Segment
* Category
* Sales
* Profit
* Returned

Including the return status makes it easier to understand whether high-value orders are also associated with returns.

## Interactive Filters

Add slicers to make the report easier to explore.

Recommended slicers include:

* Year
* Region
* Category
* Sub-Category
* Segment
* Ship Mode

Users can select different values to dynamically update the report visuals.

Before exporting the report, make sure the slicers are reset or set to the required values.

## Key Business Insights

Based on the analysis, the report can be used to highlight the following business observations:

* Sales show an overall upward trend across the analyzed period.
* Regional performance varies, with the West region showing strong sales performance.
* Technology is a major contributor to overall sales.
* Phones and Accessories are important contributors within the Technology category.
* Higher discounts can reduce profitability, particularly for certain orders.
* Consumers account for the largest share of sales among the customer segments.
* Returns should be monitored, especially for high-value orders, because they can affect the overall profitability of the business.

These insights can help management review **pricing, discount strategies, regional performance, product mix, and return-related issues**.

## Final Outcome

The final Power BI report provides an interactive view of **Superstore sales and profitability**, allowing users to analyze business performance across different regions, products, customer segments, discounts, and returns.

The report can be used as a practical **business analytics project** to demonstrate skills in **data cleaning, Power BI visualization, KPI analysis, dashboard development, and business insight generation**.                                                                                                                                                                                                                                                                                      screenshot:<img width="2094" height="1172" alt="Superstore_PowerBI_Dashboard" src="https://github.com/user-attachments/assets/b386da5e-158a-4c67-8580-00a11fa23bf9" />

