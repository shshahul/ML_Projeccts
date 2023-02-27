# MajorProject_1_DemandForecast
**Item Demand Forecasting**

Demand forecasts are fundamental to plan and deliver products and services. Accurate forecasting of demand can help the manufacturers to maintain appropriate stock which results in reduction in loss due to product not being sold and also reduces the opportunity cost (i.e. higher demand but less availability => opportunity lost). Despite such relevance, manufacturers have difficulty choosing which forecast model is the best for their use case. In this project, historical sales data corresponding to multiple(25) items sold in 10 stores are provided and participants are expected to come up with a best model to predict the future demand for products which results in maximum profit for the manufacturer. **Predict the demand for the next 3 months at the item level (i.e. all the stores combined)**.

**Requirements**

> Python

>Pandas

> Mechine Learning

> numpy

> Plotly


# EDA

![27 02 2023_13 45 28_REC](https://user-images.githubusercontent.com/103018333/221510384-29705c93-8a75-44ae-a021-cb49f727014d.png)
![27 02 2023_13 46 29_REC](https://user-images.githubusercontent.com/103018333/221510424-95d0a6f1-6c3f-40a2-9266-d8caca00ad0f.png)

![27 02 2023_13 46 59_REC](https://user-images.githubusercontent.com/103018333/221510457-3edd6792-c7f2-4d8d-8009-a1b695d8d2ff.png)


**XGBREGRESSOR obtained scores**

#Metric Evolution 

  Explained variance: 0.9916556988701846

	Mean absolute error (MAE): 753.7446008133562

	Root Mean squared error (RMSE): 891.8355688079398

	R2 score: 0.9812039112253449

# Splitting Train and Test/forecasting

![27 02 2023_13 51 51_REC](https://user-images.githubusercontent.com/103018333/221511687-bdc9d901-d782-4aa2-bfca-784bfb50e4af.png)

**Test Data Predictions**

![27 02 2023_13 50 48_REC](https://user-images.githubusercontent.com/103018333/221512017-b0fd4a66-2149-45ac-aed4-aef3dcfcc26a.png)


**Next 3Months predicted Output**


![27 02 2023_13 53 46_REC](https://user-images.githubusercontent.com/103018333/221512185-65880822-ab92-4e98-9616-4850e1bd7e31.png)


