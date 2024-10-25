# Pharma-Sales-Data-Analysis

This project involves analyzing and forecasting pharmaceutical sales data for various drug categories from 2014 to 2019. The dataset includes monthly sales for several categories classified under the Anatomical Therapeutic Chemical (ATC) classification system. The analysis aims to uncover sales trends, detect seasonal patterns, and forecast future sales using statistical models.

**Project Overview**

Pharmaceutical sales data is critical for understanding trends, managing inventory, and preparing for future demand. This project applies data analysis and forecasting techniques to a dataset containing six years of transactional data across multiple drug categories. The key objectives include:

Understanding sales trends for different drug categories over time.
Identifying seasonal patterns and fluctuations in sales.
Forecasting future sales using ARIMA and SARIMAX models.

**Dataset**

The dataset includes:

Date (datum): Monthly sales data from January 2014 to December 2019.
Drug categories: Sales for eight drug categories including:
M01AB (Non-steroidal anti-inflammatory drugs)
M01AE (Propionic acid derivatives)
N02BA (Salicylic acid derivatives)
N02BE (Anilides and Pyrazolones)
N05B (Anxiolytic psycholeptics)
N05C (Hypnotic and sedative psycholeptics)
R03 (Medications for obstructive airway diseases)
R06 (Antihistamines for systemic use)


**Key Analysis**

**1. Sales Trend Analysis:**

Visualization of monthly sales trends from 2014 to 2019. Comparative analysis of sales performance across different drug categories.

**2. Seasonality Detection:**

Identification of seasonal patterns, with a particular focus on categories such as N02BE, which shows strong seasonal fluctuations. Analysis of monthly sales averages to detect peak and off-peak periods.

**3. Forecasting:**

Time series forecasting using ARIMA and SARIMAX models to predict future sales for categories like M01AB. Confidence intervals to measure uncertainty in the forecasts.

**4. Insights:**

Categories like N02BE show high seasonality, with spikes in colder months.
M01AB shows volatile sales, making it challenging to forecast long-term trends accurately.


**Technologies Used**

Python for data analysis and modeling.

Pandas for data manipulation.

Matplotlib and Seaborn for visualization.

Statsmodels for ARIMA and SARIMAX forecasting.

Jupyter Notebook for interactive analysis.
