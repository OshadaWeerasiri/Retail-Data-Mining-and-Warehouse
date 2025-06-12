## Retail Data Mining and Warehouse

This project implements a comprehensive retail data warehouse solution using Snowflake and Python. Starting with a detailed understanding and cleaning of the provided sales-data.csv,
a suitable star schema was designed and implemented in Snowflake for efficient analytics. ETL processes were performed to load and transform the data.
Advanced data mining techniques were applied to generate actionable business insights, including shipment status prediction, sales forecasting, order profitability analysis,
customer segmentation, and geographic performance visualization. The project also includes evaluation metrics and visualizations to support findings.
Bonus features include Power BI integration and optional real-time data streaming with Snowflake Streams and Tasks.

⏺️This is the way i created table and how data insert to the dimension and fact tables:

![Screenshot (74)](https://github.com/user-attachments/assets/8802da39-c240-43d1-98f2-cc09dbb34884)

⏺️After the data is cleaned and inserted, I use it for the prediction phase, including:

  ⚫Predicting shipment status
  
  ⚫Forecasting sales
  
  ⚫Predicting order profitability
  
  ⚫Clustering orders by buying behavior (grouping orders/customers based on similar buying and shipping patterns
  
  ⚫Visualizing shipment performance across geographies
  
  ⚫Analyzing delivery delays or profit trends by latitude and longitude

  After that, the data is used to analyze and visualize insights using Power BI

  
![Screenshot (73)](https://github.com/user-attachments/assets/3c902f9c-a578-4656-b5e5-313e070becbe)



