# DashboardwithPython

The objective is to analyze the historical trends in automobile sales during recession periods. The goal is to provide insights into how the sales of XYZAutomotives, a company specializing in automotive sales, were affected during times of recession.

This project incorporates creating various visualizations using Plotly and Dash.

Dashboard has 2 reports:

1) Yearly Automobile Sales Statistics
   
2) Recession Period Statistics

NOTE: Year range is between 1980 and 2013.

Components:

1. Yearly Automobile Sales Statistics

This report mainly consists of the following items:

Yearly Automobile Sales Using Line Chart for the Whole Period (line chart):This line chart displays the average automobile sales for each year across the entire period.

Total Monthly Automobile Sales Using Line Chart (line chart):This line chart displays the total monthly automobile sales for the selected year.

Average Vehicles Sold by Vehicle Type in the Selected Year (bar chart):This bar chart shows the average number of vehicles sold for each vehicle type in the selected year.

Total Advertisement Expenditure for Each Vehicle Using Pie Chart (pie chart):
This pie chart represents the total advertising expenditure for each vehicle type in the selected year.

2. Recession Period Statistics

Average Automobile Sales Fluctuation Over Recession Period (Year-wise):This line chart shows the average automobile sales for each year during recession periods.

Average Number of Vehicles Sold by Vehicle Type:This bar chart displays the average number of vehicles sold for each vehicle type during recession periods.

Total Expenditure Share by Vehicle Type During Recessions:This pie chart represents the total advertising expenditure share by vehicle type during recession periods.

Effect of Unemployment Rate on Vehicle Type and Sales:This bar chart shows the effect of unemployment rate on automobile sales by vehicle type during recession periods.

The dataset includes the following variables

1) Date: The date of the observation.
2) Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
3) Automobile_Sales: The number of vehicles sold during the period.
4) GDP: The per capita GDP value in USD.
5) unemployment_rate: The monthly unemployment rate.
6) Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
7) Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
8) Price: The average vehicle price during the period.
9) Advertising_Expenditure: The advertising expenditure of the company.
10) Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
11) Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
12) Month: Month of the observation extracted from Date.
13) Year: Year of the observation extracted from Date.

Commands to run the code in terminal:
1) pip3.8 install setuptools
2) python3.8 -m pip install packaging
3) python3.8 -m pip install pandas dash
4) pip install more-itertools
5) Run the python file: python3.8 pythdashboard.py
