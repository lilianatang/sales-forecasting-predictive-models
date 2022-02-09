# A predictive data model to study factors that would significantly increase sales.
### Introduction
For companies to be competitive and grow exponentially, they need to be able to forecast feature sales and find out important factors that would affect their revenue. As a data scientist, using Random Forest regession model, I was able to
* Train a machine model to predict future sales based on historical data and in consideration of seasonality effects, demand, holidays, promotions, and competition.
* Identify significant factors that would affect the company's sales

### Data Source
Due to the confidentiality of companies' data, I used fictional dataset from Kaggle to demonstrate how machine learning could accurately predict future sales: https://www.kaggle.com/c/rossmann-store-sales/data
### File Description
To see all the codes and output, you can open SalesForecast.ipynb file.
### Summary of Results
The model was able to forecast future sales with 96% accuracy. 

The most important features are customers, CompetitionDistance, StoreType, and Store.
![plot](./feature_importance.png)
