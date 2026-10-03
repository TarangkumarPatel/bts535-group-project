# Sales Forecasting for Small Businesses

## Group 4

**Team Members and Contact Information**

| Student Name | GitHub ID | Student Email |
| -------- | -------- | -------- |
| Tarangkumar Janakkumar Patel | https://github.com/TarangkumarPatel | tjpatel5@myseneca.ca |
| Jaishnav Prasad | https://github.com/CyberJalagam | jprasad3@myseneca.ca |
| Festus Sabu | https://github.com/festussabu | fsabu@myseneca.ca |
| Faith Sam | https://github.com/faithsam32004 | fsam3@myseneca.ca |  

## Problem

Small businesses such as local retailers, cafes, and independent shops often rely on intuition or simple spreadsheets to plan for future sales. Without accurate forecasts, they struggle to decide how much inventory to order, how many staff to schedule, and how much cash to keep on hand. Overestimating demand leads to excess stock, spoilage, and tied-up capital, while underestimating it leads to stockouts, lost revenue, and unhappy customers. Unlike large enterprises, small businesses rarely have access to data analysts or expensive forecasting software, even though they already collect valuable sales data through their point-of-sale systems. This gap leaves many owners making high-impact decisions with limited insight, which directly affects their profitability and long-term survival.


## Proposed Solution

We propose a sales forecasting tool that turns a small business's historical sales data into clear, actionable predictions. Owners will be able to upload their sales records (for example, a CSV export from their point-of-sale system), and the tool will clean the data, identify trends and seasonal patterns, and account for factors such as holidays, weekends, and promotions. Using time series and machine learning models, the system will forecast future sales at daily, weekly, and monthly levels, both overall and per product category. Results will be presented through a simple dashboard with charts and summary insights, such as expected busy periods and products likely to run low, so that owners without a technical background can make better inventory, staffing, and budgeting decisions.


## Technologies

The solution will be built in **Python**, using **Pandas** and **NumPy** for data cleaning, transformation, and feature engineering. For forecasting, we will use **Statsmodels** (ARIMA/SARIMA), **Prophet** for handling seasonality and holidays, and **Scikit-learn** for regression-based models and evaluation metrics such as MAE and RMSE. Data exploration and visualization will be done with **Jupyter Notebook**, **Matplotlib**, and **Seaborn**, and the user-facing dashboard will be built with **Streamlit**. Sample data will come from public retail sales datasets (such as those available on Kaggle) stored as CSV files. The team will use **Git** and **GitHub** for version control, issue tracking, and pull request based collaboration.
