# Beijing-Multi-Site-Air-Quality-Index-Time-Series-Analysis
In January 2013, a suffocating, poisonous haze hung over Beijing for four days. The record high levels of fine particulate matter in the air caused airports to close and thousands of coughing, choking citizens to seek hospital care.
Beijing’s coal-burning power plants and 5 million motor vehicles are responsible for much of the city’s pollution.
The emission of pollutants and still air that allows the pollutants to build.

The air pollution crisis in Beijing, China, during 2013 has raised significant concerns regarding public health and environmental sustainability. The city experienced severe episodes of air pollution characterized by high levels of particulate matter (PM2.5) and other pollutants, leading to adverse health effects and disruptions to daily life.
In response to this crisis, there is a need to conduct a comprehensive time-series analysis to understand the temporal patterns and trends of air pollution levels, identify key factors influencing air quality, and develop predictive models for forecasting future pollution levels.

Analyze the temporal dynamics of air pollution in Beijing during the year 2013 and develop predictive models to forecast pollutant concentrations:

Exploration Data Analysis: Explore the temporal patterns and trends of air pollution levels, including PM2.5, and other relevant pollutants, using historical data from 2013 to 2017.
Factor Identification: Identify key factors influencing air quality, including meteorological variables, industrial activities, vehicular emissions, and other environmental factors.
Model Development: Develop time-series forecasting models, such as Autoregressive Integrated Moving Average (ARIMA), Seasonal Auto-Regressive Integrated Moving Average (SARIMA), FB Prophet, Vector Auto Regressor (VAR), and machine learning approaches (e.g., neural networks), to predict future air pollution levels.
Model Evaluation: Evaluate the performance of the forecasting models using appropriate metrics, such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).


The dataset consists of hourly atmospheric measurements from 12 cities in Beijing, covering the period from March 1st, 2013, to February 28th, 2017.
It includes target variables such as PM2.5, PM10, SO2, NO2, CO, and O3, along with independent variables like temperature, pressure, dew point temperature, rainfall, wind speed, and wind direction.

Prophet model and other Uni-variate models can be used in the pipeline to use it with categorical columns.
Vector Auto Regressor can be improved and hyper-tuned to forecast more accurately, and to mitigate variance.
RNN and LSTM can be used as models to learn and take advantage of deep learning models and their capacity to learn complex patterns.

