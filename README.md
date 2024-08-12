![stubble-burning](https://github.com/user-attachments/assets/01cac87a-2147-4123-947a-70b0a99f361d)

# Predictive Modelling of AQI & Influence of Stubble Burning on AQI Variability
Predictive Modelling of Air Quality Index (AQI) Across Diverse Cities and States of India Using Machine Learning: Investigating the Influence of Punjab's Stubble Burning on AQI Variability

ABSTRACT
Air pollution is a common and serious problem nowadays and it cannot be ignored as it has harmful impacts on human health. To address this issue proactively, people should be aware of their surroundings, which means the environment where they survive. With this motive, this research has predicted the AQI based on different air pollutant concentrations in the atmosphere.
The dataset used for this research has been taken from the official website of CPCB. The dataset has the air pollutant concentration from 22 different monitoring stations in different cities of Delhi, Haryana, and Punjab. This data is checked for null values and outliers. But, the most important thing to note is the correct understanding and imputation of such values rather than ignoring or doing wrong imputation. As the data used in this research is time series, it needs to be tested for stationarity, it can be done by using The Dickey-Fuller test.
Further different ML models like CatBoost, XGBoost, Random Forest, SVM regressor, time series model SARIMAX, and deep learning model LSTM have been used to predict AQI. For the performance evaluation of different models, I used MSE, RMSE, MAE, and R2. It is observed that Random Forest performed better as compared to other models. 
