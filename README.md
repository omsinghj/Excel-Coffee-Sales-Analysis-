## Excel-Coffee-Sales-Analysis-

# Project Overview
The Coffee Sales Dashboard is designed to help track, analyze, and visualize coffee sales data using Excel features like formulas, Pivot Tables, and interactive components like slicers. This project integrates customer, product, and order data to generate meaningful insights.

# Steps to Build the Dashboard
Step 1: Prepare the Data Sheets
Create the following Excel sheets:

* Orders Sheet
* Customers Sheet
* Products Sheet

# Step 2: Copy Order Data to Working Sheet
* Create a new sheet called Working.
* Copy and paste the relevant order data into this Working sheet for data transformation and calculations.

# Step 3: Fetch Customer and Product Information
Use formulas to gather additional details:
* Customer Data:
Use the XLOOKUP formula to retrieve customer names and other relevant data.

* Product Data:
Use the INDEX or XLOOKUP function to retrieve product names and prices.

# Step 4: Calculate Sales
Calculate the sales value per order:

= [Unit Price] * [Quantity]

= C2 * E2
* Place this formula in a new column in the Working sheet.
* Press Enter. This will return the total sales value for that row.

# Step 5: Create Pivot Table
*Insert a Pivot Table based on the cleaned data from the Working sheet.
* Summarize data such as:
      * Total sales by product
      * Sales by customer
      * Monthly/Weekly sales

# Step 6: Add Slicers
* Add slicers to make the dashboard interactive.
* Common slicers: Product name, Customer name, Region, or Date.

# Step 7: Create Dashboard Sheet
* Create a new sheet and name it Coffee Sales Dashboard.
* Move and arrange charts, Pivot Tables, and slicers here to present a visually clean dashboard.

# Step 8: Arrange and Finalize
* Organize all components (charts, KPIs, slicers) neatly.
* Apply formatting, titles, and labels for readability.




