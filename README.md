# Design-an-Interactive-Dashboard-for-Business-Stakeholders

Power BI - Adidas Sales Dashboard

Task Objective

This project is a deliverable for the Data Analyst Internship (Task 4). The objective was to design and build an interactive dashboard in Power BI for business stakeholders, based on the provided Adidas sales dataset.

What I Did

This project involved a complete, end-to-end data visualization workflow:

Data Loading & Transformation (ETL):

Connected to the AdidasSalesdata.csv file.

Used the Power Query Editor to clean the data, check for errors, and set correct data types for financial, date, and text columns.

Data Modeling:

Created a robust data model by adding a separate Date Table using DAX.

Formed a one-to-many relationship from the Dates table to the Sales table to enable accurate time-series analysis.

DAX Measures (KPIs):

Wrote DAX formulas to create the primary Key Performance Indicators (KPIs) required by the task:

Total Sales

Total Profit

Avg Profit Margin

Dashboard Design & Storytelling:

Designed a clean, multi-page executive dashboard.

Page 1 (Executive Summary): Features KPI cards, time-series analysis (Sales & Profit by Month), a map visual for profit by state, and a donut chart for the sales mix.

Page 2 (Deep-Dive): Includes breakdowns by retailer, sales method, and profitability.

Interactivity: Added slicers for Year, Region, and Product Category to allow stakeholders to dynamically filter the data and discover their own insights.

Project Deliverables

adidas sales dashboard.pbix: The complete, interactive Power BI project file.

Adidas_Dashboard_Summary.md: A slide-by-slide summary of the project's findings for a stakeholder presentation.
