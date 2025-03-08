Superstore Sales Analysis

Overview

This project analyzes sales and profit data from a Superstore dataset using Python. The analysis includes time-based trends, category-wise sales distribution, and profit insights using visualization libraries like Matplotlib, Seaborn, and Plotly.

Dataset

The dataset, Superstore Sales.csv, contains transaction details, including order dates, shipment details, product categories, sales, and profit figures.

Key Features

Data Preprocessing:

Loading dataset using Pandas.

Handling date columns and extracting time-based features (Month, Year, Day of the Week).

Checking for missing values.

Sales & Profit Analysis:

Aggregating sales and profit data by time periods (Year, Month, Day of the Week).

Analyzing sales and profit trends by product categories and sub-categories.

Computing Sales-to-Profit ratio by customer segments.

Data Visualization:

Line plots for monthly sales trends using Matplotlib and Seaborn.

Pie charts and bar charts for categorical analysis using Matplotlib and Plotly.

Interactive visualizations with Plotly for better data exploration.

Visualizations

The following visualizations are generated and saved under the Plots directory:

Monthly Sales Trend: Line plot showing sales trends over different months.

Sales by Category: Donut chart visualizing sales distribution among product categories.

Sales by Sub-Category: Bar chart displaying sub-category sales distribution.

Monthly Profit Analysis: Bar chart illustrating profit trends over months.

Profit by Category & Sub-Category: Pie chart and bar chart showing profit variations.

Sales & Profit by Segment: Bar chart comparing sales and profit across customer segments.

Sales by Day of the Week: Pie chart showing sales share on different days.

Yearly Sales Trend: Bar chart tracking yearly sales performance.

Prerequisites

Ensure you have the following libraries installed:

pip install pandas matplotlib seaborn plotly

Usage

Update the file path in the script to match your dataset location.

Run the script using Python:

python sales_analysis.py

The plots will be saved in the Plots folder for review.

Future Enhancements

Automate data preprocessing and cleaning.

Implement dashboarding using Power BI or Tableau.

Optimize the analysis with additional KPIs (e.g., customer segmentation, forecasting).

Author

This project was developed as part of a Mini-Project on E-commerce Sales Analysis.