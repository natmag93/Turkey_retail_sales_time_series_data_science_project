# Turkish retail Dataset:  
Time Series forecast using AutoArima

This project focuses on leveraging data science techniques to forecast products sales for different stores in Konya, Turkey.

The project was performed using Microsoft Fabric for EDA, model train and forecast and PowerBi for dashboard creation for the Bi solution.


## Dataset
This dataset includes retail data for several stores across Turkey. Time period between 2017- 2019
The 'sales.csv' file should be downloaded from the following kaggle link.

[Dataset link](https://www.kaggle.com/datasets/berkayalan/retail-sales-data)


## Business understanding 

For many years, businesses have been trying to minimize inventory costs while providing what their customers need in a timely fashion. Maintaining a lean and responsive inventory can be challenging without using accurate forecasting techniques.

There is a necessity for creation of a robust inventory management system ensures that each product's quantity, location, and status are constantly monitored.

**Background/ Requirements Gathering**

For this project some assumptions were made:

- Shipment takes 2 weeks to be delivered
- Stocks must be ensured at least 10% of expected sales

**Business/Project Objectives and Scope**
 - Time series forecast for 2 weeks (taking into consideration the assumptions previously described)
 - Creation of a Bi solution to evaluate necessity for products stock  replenishment.


## Project steps:

- Data understanding 
- Data profiling and EDA.
- Data Preparation
- Modeling
- AutoArima
- Evaluation
-  Bi solution

tools used: Power Bi, Python (pandas), Microsoft Fabric

## In this repository

- Dashboard for data profiling
- Scripts (EDA, ETL, Data preparation, Modelling, Forecast)
- Final Bi solution dashboard
- html files
- tables (raw and processed data)
- Models evaluation - pdf file


## Evaluation


![enter image description here](https://github.com/natmag93/Turkey_retail_sales_time_series_data_science_project/blob/9bbf283bc749652aec6aa3d925df085e375918b3/Apresenta%C3%A7%C3%A3o%20sem%20t%C3%ADtulo.png)

## Business Solution

![enter image description here](https://github.com/natmag93/Turkey_retail_sales_time_series_data_science_project/blob/273c88d527eb4547447296fd5bc71d12d57c765c/Bi_solution.png)

A screenshot showing the created Bi solution to estimate the necssity to reorder stock. 
For a detail view, download the PowerBI file from this repository.

## Conclusions 

The sales forecasting project has demonstrated to be effective for predicting sales for
various stores and products. By evaluating forecast accuracy through metrics such as
Weighted Mean Absolute Percentage Error (WMAPE), the study confirms the effectiveness
of ARIMA models in different product groupings and time ranges, however, the median
WMAPE obtained after model fitting for several different products by store type was not as
low as expected. The final phase of this project included a business solution design, to
predict and control sales and stock replenishment.


**Future Work**

Future work should focus on decreasing WMAPE across all stores and products by
incorporating exogenous variables that capture external factors influencing sales, such as
promotional activities, economic indicators, and seasonal trends. A deep understanding of
the business context will further refine the forecasting model.
When optimized, this business solution should lead to improved inventory management,
reduced stockouts, and minimized overstocks, thereby achieving cost savings. Supplier
coordination and supply chain efficiency will also be enhanced. Additionally, with accurate
forecasts, promotion and pricing optimization will be more effective.


## Authors

[Francisco Leite](https://github.com/fransile)

[Natalia Magalhaes](https://github.com/natmag93)

[Zita Martins](https://github.com/zitasamartins)


Feel free to contact us!
