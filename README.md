
# US Candy Distributor Sales, Profitability & Target Performance Analysis

## Project Overview
<img width="1186" height="578" alt="US CANDY PIC" src="https://github.com/user-attachments/assets/ec8cd7dc-2d55-4ca0-b302-b4822ab7e29f" />

<img width="1908" height="997" alt="MEASURES" src="https://github.com/user-attachments/assets/5fa4e03e-b8bd-4157-94de-2ca276d42414" />

<img width="1287" height="668" alt="MODEL" src="https://github.com/user-attachments/assets/a588d4c1-4170-454c-94fb-2afd1858ea8e" />

<img width="1913" height="993" alt="PPIVOT" src="https://github.com/user-attachments/assets/139fde8a-e4f3-462b-b9bc-b53c81bf2967" />



This project analyzes sales performance, profitability, and target achievement for a US Candy Distributor.

The analysis was built using **Microsoft Excel Power Pivot** to transform and model the data, create relationships between tables, and develop calculated measures for business performance analysis.

The goal was to turn raw sales data into an interactive dashboard that provides insights into revenue performance, profitability, target achievement, product divisions, states, and monthly sales trends.

## Tools Used

* Microsoft Excel
* Power Pivot
* DAX
* Data Modeling
* PivotTables
* Data Visualization

## Data Model

The project uses a relational data model consisting of five tables:

### Sales

The main fact table containing transactional sales information, including:

* Row ID
* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Country
* City
* State
* Postal Code
* Division

### Products

Contains product-level information:

* Division
* Product Name
* Factory
* Product ID
* Unit Price

### Targets

Contains target sales information by division:

* Division
* Target

### Factories

Contains factory location information:

* Factory
* Latitude
* Longitude

### Date

A dedicated date dimension used for time-based analysis:

* Order Date
* Year
* Month Name
* Quarter

The tables were connected using relationships in the Power Pivot data model to allow analysis across different dimensions.

## Data Modeling

A relational data model was created in Power Pivot rather than analyzing the tables independently.

The model connects the Sales table with Products, Targets, Factories, and Date tables. This allowed the dashboard to dynamically calculate and analyze business performance across products, divisions, locations, and time periods.

The Date table was also used to support time-based analysis such as monthly revenue trends and yearly filtering.

## Dashboard

The final dashboard provides an overview of sales, profitability, and target performance.

### Key Performance Indicators

The dashboard includes:

* **Total Revenue:** $141.33K
* **Profit Margin:** 66%
* **Target Achievement:** 314%
* **Target Sales:** $45K

These KPIs provide a quick overview of the company's overall performance.

## Dashboard Analysis

### Revenue by State

The dashboard shows revenue distribution across states.

The highest-performing states displayed include:

* California — $27.83K
* New York — $15.49K
* Texas — $13.37K
* Pennsylvania — $8.01K
* Washington — $6.91K

California generated the highest revenue among the states shown.

### Profit Margin by Division

Profitability was analyzed across product divisions, including:

* Chocolate
* Sugar
* Other

The dashboard shows differences in profit margins across the divisions, allowing the business to identify which product categories contribute most strongly to profitability.

### Revenue Trend

A monthly revenue trend was created to monitor changes in sales throughout the year.

The visualization makes it easier to identify periods of growth, decline, and significant changes in revenue performance.

### Revenue vs Target

The dashboard compares monthly revenue against target sales.

The highest revenue months shown include:

* December — $21K
* November — $21K
* October — $12K
* September — $19K
* May — $10K

This comparison helps determine whether actual sales are meeting or exceeding the expected target.

## Key Insights

From the analysis:

1. The business generated approximately **$141.33K in total revenue**.

2. The overall **profit margin was 66%**, indicating strong profitability across the analyzed sales.

3. Actual performance significantly exceeded the target, with **314% target achievement**.

4. **California recorded the highest revenue** among the states displayed on the dashboard.

5. Revenue performance varied throughout the year, with notable increases during some months.

6. Comparing revenue against targets provides a clear view of periods where sales performance was particularly strong.

7. The division-level profitability analysis helps identify which product categories contribute most to the company's margins.

## DAX & Power Pivot

Power Pivot was used to create a centralized data model and perform calculations using DAX.

Examples of analytical measures included calculations for:

* Total Revenue
* Profit
* Profit Margin
* Target Sales
* Target Achievement
* Monthly Revenue
* Revenue vs Target

Using DAX measures allowed the dashboard to update dynamically when filters such as year, country, state, or division were applied.

## Business Questions Answered

This project was designed to answer questions such as:

* What is the company's total revenue?
* How profitable is the business?
* Are sales exceeding the company's targets?
* Which states generate the highest revenue?
* Which product divisions have stronger profit margins?
* How does revenue change over time?
* Which months have the strongest sales performance?
* How does actual revenue compare with target sales?

## Project Outcome

The project transformed raw transactional data into an interactive business intelligence dashboard using **Excel Power Pivot**.

The analysis demonstrates how data modeling, DAX calculations, and visualization can be combined to support business decision-making and provide a clearer understanding of sales and profitability performance.

## Skills Demonstrated

* Data Cleaning
* Data Modeling
* Power Pivot
* DAX
* Relational Data Modeling
* KPI Development
* Sales Analysis
* Profitability Analysis
* Target Performance Analysis
* Time Series Analysis
* Data Visualization
* Business Intelligence
* Dashboard Development

## Conclusion

This project demonstrates my ability to move beyond basic spreadsheet analysis by building a structured data model in **Power Pivot**, creating analytical measures with DAX, and presenting the results through an interactive business dashboard.

The project strengthened my understanding of how data can be transformed into meaningful business insights and actionable performance information.


This project analyzes sales performance, profitability, and target achievement for a US Candy Distributor.

The analysis was built using **Microsoft Excel Power Pivot** to transform and model the data, create relationships between tables, and develop calculated measures for business performance analysis.

The goal was to turn raw sales data into an interactive dashboard that provides insights into revenue performance, profitability, target achievement, product divisions, states, and monthly sales trends.

## Tools Used

* Microsoft Excel
* Power Pivot
* DAX
* Data Modeling
* PivotTables
* Data Visualization

## Data Model

The project uses a relational data model consisting of five tables:

### Sales

The main fact table containing transactional sales information, including:

* Row ID
* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Country
* City
* State
* Postal Code
* Division

### Products

Contains product-level information:

* Division
* Product Name
* Factory
* Product ID
* Unit Price

### Targets

Contains target sales information by division:

* Division
* Target

### Factories

Contains factory location information:

* Factory
* Latitude
* Longitude

### Date

A dedicated date dimension used for time-based analysis:

* Order Date
* Year
* Month Name
* Quarter

The tables were connected using relationships in the Power Pivot data model to allow analysis across different dimensions.

## Data Modeling

A relational data model was created in Power Pivot rather than analyzing the tables independently.

The model connects the Sales table with Products, Targets, Factories, and Date tables. This allowed the dashboard to dynamically calculate and analyze business performance across products, divisions, locations, and time periods.

The Date table was also used to support time-based analysis such as monthly revenue trends and yearly filtering.

## Dashboard

The final dashboard provides an overview of sales, profitability, and target performance.

### Key Performance Indicators

The dashboard includes:

* **Total Revenue:** $141.33K
* **Profit Margin:** 66%
* **Target Achievement:** 314%
* **Target Sales:** $45K

These KPIs provide a quick overview of the company's overall performance.

## Dashboard Analysis

### Revenue by State

The dashboard shows revenue distribution across states.

The highest-performing states displayed include:

* California — $27.83K
* New York — $15.49K
* Texas — $13.37K
* Pennsylvania — $8.01K
* Washington — $6.91K

California generated the highest revenue among the states shown.

### Profit Margin by Division

Profitability was analyzed across product divisions, including:

* Chocolate
* Sugar
* Other

The dashboard shows differences in profit margins across the divisions, allowing the business to identify which product categories contribute most strongly to profitability.

### Revenue Trend

A monthly revenue trend was created to monitor changes in sales throughout the year.

The visualization makes it easier to identify periods of growth, decline, and significant changes in revenue performance.

### Revenue vs Target

The dashboard compares monthly revenue against target sales.

The highest revenue months shown include:

* December — $21K
* November — $21K
* October — $12K
* September — $19K
* May — $10K

This comparison helps determine whether actual sales are meeting or exceeding the expected target.

## Key Insights

From the analysis:

1. The business generated approximately **$141.33K in total revenue**.

2. The overall **profit margin was 66%**, indicating strong profitability across the analyzed sales.

3. Actual performance significantly exceeded the target, with **314% target achievement**.

4. **California recorded the highest revenue** among the states displayed on the dashboard.

5. Revenue performance varied throughout the year, with notable increases during some months.

6. Comparing revenue against targets provides a clear view of periods where sales performance was particularly strong.

7. The division-level profitability analysis helps identify which product categories contribute most to the company's margins.

## DAX & Power Pivot

Power Pivot was used to create a centralized data model and perform calculations using DAX.

Examples of analytical measures included calculations for:

* Total Revenue
* Profit
* Profit Margin
* Target Sales
* Target Achievement
* Monthly Revenue
* Revenue vs Target

Using DAX measures allowed the dashboard to update dynamically when filters such as year, country, state, or division were applied.

## Business Questions Answered

This project was designed to answer questions such as:

* What is the company's total revenue?
* How profitable is the business?
* Are sales exceeding the company's targets?
* Which states generate the highest revenue?
* Which product divisions have stronger profit margins?
* How does revenue change over time?
* Which months have the strongest sales performance?
* How does actual revenue compare with target sales?

## Project Outcome

The project transformed raw transactional data into an interactive business intelligence dashboard using **Excel Power Pivot**.

The analysis demonstrates how data modeling, DAX calculations, and visualization can be combined to support business decision-making and provide a clearer understanding of sales and profitability performance.

## Skills Demonstrated

* Data Cleaning
* Data Modeling
* Power Pivot
* DAX
* Relational Data Modeling
* KPI Development
* Sales Analysis
* Profitability Analysis
* Target Performance Analysis
* Time Series Analysis
* Data Visualization
* Business Intelligence
* Dashboard Development

## Conclusion

This project demonstrates my ability to move beyond basic spreadsheet analysis by building a structured data model in **Power Pivot**, creating analytical measures with DAX, and presenting the results through an interactive business dashboard.

The project strengthened my understanding of how data can be transformed into meaningful business insights and actionable performance information.
