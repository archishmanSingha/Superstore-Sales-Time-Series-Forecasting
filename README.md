# Superstore-Sales-Time-Series-Forecasting

<h2>Problem Statement:</h2>

Retail dataset contains information of sale of a global superstore for 4 years. Performing EDA and Visualization to predict the Sale for the next 7days.

<h3>Data Source:</h3>

https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

<h3>Exploratory Data Analysis (EDA) and Visualization:</h3>

Data Exploration 
* df.head() - It shows the first 5 rows of the data.
* df.describe() - It shows a summary of the numerical data.
* df.info() - It has 9800 entries and it shows that Postal Code has 11 missing values.

Data cleaning

* Unnecassary columns have been removed, null values in the postalcode column have been filled, and data type validation for ship date and order date has been done.

Data Visualization

* Top 15 Cities with the highest Sale using Bar Chart
* Sale Segments and Regional Sales using Pie Chart
* Category and Sub-Category wise Sale Visualization using Pie Chart
* Common product Category and Segment in the top 10 consuming cities using Bar Chart
* Year on Year sale in Year, Month and Day Wise using Line Graph
* Day of Week Sale representation against revenue using Bar Chart 

<h3>Train Model:</h3>

**Prophet Model** :  Passing the parameter Date as 'ds' and sale amount as 'y'. Forecasted the Sale Amount for the next 7days.

<h3>Results:</h3>

Hence, was able to predict the sale amount for the next 7days. For visualization purpose, line graph was plotted.

![image](https://github.com/archishmanSingha/Superstore-Sales-Time-Series-Forecasting/assets/123219771/f99f161f-d784-4bb0-b413-e4cd972447c6)

