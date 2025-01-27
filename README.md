#Thai Tourism Time Series Analysis
This project performs time-series analysis and forecasting on Thai tourism data. It uses R and the forecast package to visualize trends, detect patterns, and generate forecasts for future tourist numbers. The analysis is documented in an R Markdown file and generates a PDF report.

Features
Data Cleaning: Combines year and month into a date format, handles missing values, and prepares data for analysis.
Exploratory Data Analysis (EDA): Provides an overview of the dataset, including row/column count, column names, and summary statistics.
Time Series Decomposition: Breaks down the data into trend, seasonal, and residual components.
Forecasting: Implements models like ARIMA for predicting future trends.
Requirements
Libraries
tidyverse
lubridate
tseries
forecast
Dataset
The project uses a CSV file, Thaitourism.csv, with the following columns:

year: Year of the record
month: Month of the record
tourist: Number of tourists
Additional columns, if present, are detailed in the report.
Steps
Setup:

Ensure R and RStudio are installed.
Install the required libraries using:
r
Copy
Edit
install.packages(c("tidyverse", "lubridate", "tseries", "forecast"))
Run the Analysis:

Open the tsa_aat.Rmd file in RStudio.
Knit the file to generate a PDF report.
Output:

The report includes visualizations, statistical summaries, and forecasting results.
Key Functions
Data Import and Preprocessing:

Reads the dataset.
Creates a date column by combining year and month.
Fills missing values in the tourist column with zeros.
Time Series Analysis:

Decomposes the time series into components.
Visualizes patterns and trends.
Applies ARIMA for forecasting.
