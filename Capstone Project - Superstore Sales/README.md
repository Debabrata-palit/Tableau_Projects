# Tableau_Project
**Superstore Sales Performance**

![Sales Dashboard](https://github.com/Debabrata-palit/Tableau_Projects/assets/163582682/bd08815a-572f-4fb0-89bf-fcc357e04e9c)

Table Public: https://public.tableau.com/app/profile/debabrata.palit03/viz/SuperSalesPerformance/SalesDashboard

## PROBLEM STATEMENT:

> **Capstone Project - Superstore Sales Performance**

## Tableau Project Requirement:
The workbook should have a single dashboard.
Each worksheet/view/chart should meet the business requirement.

## Business Requirement:
Connect to the Sample Superstore dataset and build a Dashboard that will show the Sales Performance.

**View 1: Total Sales**
- The sheet should only display the Total Sales in thousands, along with the header “Total Sales”.
- The Total Sales displayed should have the color code “#76b7b2”. Use the Color Palette.
- Disable Tooltip for this view.
- Use the background color of your choice.
- Name the sheet as “Total Sales”.

**View 2: Total Profit**
- Requirements are the same as for the view “Total Sales”.

**View 3: Total Volume**
- Requirements are the same as for the view “Total Sales”, except it’s not a currency value.

**View 4: Sales Per Customer**
- Requirements are the same as for the view “Total Sales”.

**View 5: Pie Chart**
- Pie Chart should display the percent of Total Sales by Region.
- Use the Summer Color Palette. Pie Chart should have black borders.
- Tooltip should be formatted as seen below showing Region Name, Percent of Total Sales, and the Total Sales value formatted in currency and displayed in thousands (K).  
  ![image](https://github.com/Debabrata-palit/Tableau_Projects/assets/163582682/0a324bf6-97bb-4e73-8f13-c91ba1fc373b)

*Note: Drag all the filters mentioned in the general requirement to this sheet named Pie Chart.*

**View 6: Bar Chart**
- Horizontal Bar Chart should display the top N states by Sales.
- Using a Parameter, the user should be able to change the value of N.
- Use the color of your choice for the bars along with the labels displayed in $.
- Data should always be sorted in descending order.

**View 7: Bubble Chart**
- Bubble chart should display Sales by sub-category.
- Bubbles should be colored by category.
- Use the color of your choice for the bubble.
- Tooltip should display only sub-category along with the sales value in $ in thousands (K).

**View 8: Line Chart**
- A continuous line chart should display the Sales trend by Month-Year.
- X-axis should display month and year in the format MMM YY. For example, Mar 22 [Year 2022].
- Hide the axis titles only.
- Tooltip should display only Month-Year, along with the sales value in $ in Thousands (K).
- Use Order Date as a Date Range filter.
- Name the sheet as shown below and color the tab.

## Dashboard Requirements:
**Dashboard Name:** Sales Dashboard
**Dashboard Title:** Superstore Sales Performance
**Dashboard description:** Sales overview of the superstore data
**Dashboard size:** Width – 1055, Height – 850

**Dashboard Filters:**
- Order Date – Show as Range of date. This filter should be applied to all worksheets.
- Segment – Show as multiple values (drop-down) with the Apply button and showing only relevant values. This filter should be applied to all worksheets.
- Ship Mode – Show multiple values (drop-down) with the Apply button and show only relevant values. This filter should be applied to all worksheets.
- State – Show multiple values (drop-down) with the Apply button and show only relevant values. This filter should be applied to all worksheets except the bar chart.

**Filter Formatting:**
- Format the filter background to any color.
- Add borders if necessary.
- Place all these filters in a horizontal container and distribute them evenly.

**Dashboard Containers:**
- Horizontal Container 1: Should have the name of the dashboard and add an image showing a shopping cart (add an image with transparent background) to the left of it as shown below. You can rename this container “Title/Logo” as it will help you distinguish between containers.

  ![image](https://github.com/Debabrata-palit/Tableau_Projects/assets/163582682/6a72ae1a-0e74-4361-9b0e-2dd6a7c0d8df)

- Horizontal Container 2: This should contain all the filters arranged in a horizontal container. Name this container “Filters”. Distribute the contents evenly.
- Horizontal Container 3: Arrange all the scorecards in a horizontal container.
- Horizontal Container 4: Pie Chart and Bar Chart should be arranged and placed in a horizontal container. Name it accordingly.
- Horizontal Container 5: Bubble Chart and Line Chart should be arranged and placed in a horizontal container. Name it accordingly.
- Vertical Container: Place all these horizontal containers one above the other, top to bottom, in the order they are numbered.

**Legends:** Hide the titles for the legends and place it next to their associated charts in such a way that they don’t overlap with the chart.
**Borders:** Add borders if needed per chart or per container, whichever is visually comprehensive.

**Actionable Filters:**
- Use the Pie chart and Bubble chart as Actionable Filters.
- Parameters: Place the parameter close to the Bar chart and place it somewhere on the Sheet title.
