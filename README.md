# Maven-Market-Power-BI-Dasboard

### Project Overview:
MavenMarketDashboard
This is an end-to-end Business Intelligence Project. Maven Market is a multinational grocery chain with locations in Canada, Mexico, and the United States.

### Objectives:

* Track Key Performance Indicators (KPIs).
* Connect and Shape Data.
* Build a Relational Model.
* Design a Fully Interactive Dashboard.
* Identify High-Value Customers.
* Data Source: The dataset consists of raw CSV files provided by Maven Analytics.

### Project Workflow:

1. Data Extraction: Extracted data from raw CSV files into the Power Query Editor.

2. Data Hygiene and Transformation: Corrected data types, promoted headers, and cleaned null values and duplicates.
3. Data Transformation: Added new columns for date-time analysis, such as the start of the week and the start of the year. Additionally, relevant columns like full names and email domains were incorporated.
4. Data Modeling: After the ETL (Extract, Transform, Load) process, design a data model with a star and snowflake schema, including one-to-many relationships.
5. Data Processing: Created explicit measures using DAX (Data Analysis Expressions) and added calculated columns where necessary. Measures such as Total Revenue, Total Sales, and Total Profit were generated with DAX code.
6. Data Visualization and Report Building: Developed a fully interactive dashboard with geospatial, transactional, and target metrics. Various visuals, including gauges, KPI cards, and Tree-Maps, were incorporated.

   
### Key Insights:

* The USA leads with the highest profit, transactions, revenue, and orders among the three customer countries.
* The brand "Hermanos" leads with the highest profit and total transactions but interestingly has the highest rate of return and returns quantity.
* Canada, despite having half the sales of Mexico, generates more revenue.

### Dashboard view:

<img width="518" alt="MM Dashboard" src="https://github.com/oladzie/Maven-Market-Power-BI-Dasboard/assets/141512778/97a53d43-6eb5-44e6-acdb-6c05171bcd5c">

### Note view:

<img width="517" alt="MM Note" src="https://github.com/oladzie/Maven-Market-Power-BI-Dasboard/assets/141512778/aedf90ef-f4ee-4845-b3ba-04278b2a390c">

### Model view:

<img width="544" alt="MM Model" src="https://github.com/oladzie/Maven-Market-Power-BI-Dasboard/assets/141512778/34592ffd-ec05-4805-bf1f-19c3ae3ce0e8">
