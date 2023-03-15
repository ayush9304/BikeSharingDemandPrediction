# Bike Sharing Demand Prediction

<img  alt="sbdp" src="https://user-images.githubusercontent.com/56977388/225399794-b598b9c3-893c-4b13-ae2c-9d6d0e886994.png">

The business problem is to ensure a stable supply of rental bikes in urban cities by predicting the demand for bikes at each hour. By providing a stable supply of rental bikes, the system can enhance mobility comfort for the public and reduce waiting time, leading to greater customer satisfaction.

To address this problem, we need to develop a predictive model that takes into account various factors that may influence demand, such as time of day, seasonality, weather conditions, and holidays. By accurately predicting demand, the bike sharing system operators can ensure that there is an adequate supply of bikes available at all times, which can improve the user experience and increase usage of the bike sharing system. This can have a positive impact on the sustainability of urban transportation, as it can reduce congestion, air pollution, and greenhouse gas emissions.

## Dataset

The Seoul Bike Sharing Demand dataset contains information about bike rental in Seoul from 2017-2018. It includes hourly observations such as the date, time, number of rented bikes, weather conditions, and other factors that may influence bike rental demand.

## Steps Involved

- Data Wrangling
- Exploratory Data Analysis
- Hypothesis Testing
- Feature Engineering
- Feature Selection
- Modelling
- Model Interpretation

## Algorithms used

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

## Training Results

| <p align="center">   Linear Regression<br>   <img width="308" alt="image" src="https://user-images.githubusercontent.com/56977388/225401862-23ac89e6-59d8-4471-ba1d-dc78bc86a3ea.png"> </p>       | <p align="center">   Ridge Regression<br>   <img width="308" alt="image" src="https://user-images.githubusercontent.com/56977388/225402938-95caf933-42b8-4c62-96a2-433d7ecef11d.png"> </p>        |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <p align="center">   Decision Tree Regressor<br>   <img width="308" alt="image" src="https://user-images.githubusercontent.com/56977388/225403263-ca09cbd5-69ac-4a48-b8cc-f3a1c812f9eb.png"> </p> | <p align="center">   Random Forest Regressor<br>   <img width="308" alt="image" src="https://user-images.githubusercontent.com/56977388/225403684-9043d6a2-8b46-48bc-9100-2f98f9f7d92a.png"> </p> |
| <p align="center">   XGBoost Regressor<br>   <img width="305" alt="image" src="https://user-images.githubusercontent.com/56977388/225403959-aaf35ef3-78d9-4663-b0df-90c6762136bf.png"> </p>       |                                                                                                                                                                                                   |

## Model Interpretation

| <p align="center">   Feature Influence on output<br>   <img alt="image" src="https://user-images.githubusercontent.com/56977388/225405364-7516a804-1395-486f-9885-0524a20b7c42.png"> </p> | <p align="center">   Feature Importance<br>   <img alt="image" src="https://user-images.githubusercontent.com/56977388/225406416-8a4bb3f0-cd3b-4035-a470-fb83d13c04ff.png"> </p> |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
