Predicting Traffic Congestion with Machine Learning: A Historical Analysis of Traffic Data
Project Overview
This project, titled “Predicting Traffic Congestion with Machine Learning: A Historical Analysis of Traffic Data”, proposes a mobile big data analytics approach to predict traffic congestion. The study leverages traffic data from 29 regional roads in Chicago to train time series models that can forecast traffic 10, 20, and 30 minutes ahead. The primary objective is to use this predictive capability to optimize road usage and support decision-making processes.

Table of Contents
Introduction
Data Description
Exploratory Data Analysis (EDA)
Modeling
Univariate Models (ARIMA)
Multivariate Models (VAR)
Feature Selection
Model Evaluation
Results
Recommendations
Future Work
Conclusion
Introduction
Traffic congestion prediction is vital for optimizing transportation infrastructure and enhancing road usage efficiency. This project focuses on using historical traffic data to forecast future congestion, thereby enabling proactive traffic management.

Data Description
The dataset used in this study includes traffic data from 29 regional roads in Chicago. Key variables include:

Speed: The average speed of vehicles.
Bus Count: The number of buses on the road.
Hour: The time of day when data was recorded.
Exploratory Data Analysis (EDA)
EDA was conducted to understand the underlying patterns and characteristics of the traffic data. This involved:

Visualizing time series trends.
Identifying seasonal patterns and anomalies.
Understanding correlations between variables.
Modeling
Two main types of time series-based machine learning algorithms were employed:

Univariate Models (ARIMA)
The Auto-Regressive Integrated Moving Average (ARIMA) model was used to make forecasts based solely on the speed variable.

Multivariate Models (VAR)
The Vector Auto-Regressive (VAR) model was employed to make forecasts using multiple variables (bus count, hour, and speed).

Feature Selection
Feature selection techniques such as mutual information and r_regression were utilized to identify features that are moderately correlated with speed. These features were then used to train the VAR model.

Model Evaluation
The models were evaluated using the Root Mean Squared Error (RMSE) metric to measure their prediction accuracy.

Results
The study found that the VAR model, which incorporated bus count, hour, and speed, outperformed the Auto-ARIMA model in forecasting traffic speed. The VAR model demonstrated a lower RMSE, indicating higher prediction accuracy.

Recommendations
Based on the findings, the study recommends:

Using the VAR model for traffic speed forecasting.
Implementing a rolling technique to update the model with new data continuously.
Adopting the traffic congestion forecasting system in Rwanda to optimize road usage and support decision-making.
Future Work
Future research could focus on:

Developing an improved model to increase performance.
Forecasting traffic congestion in real time.
Recommending less congested routes to drivers.
Conclusion
This project demonstrates the potential for efficiently using existing transportation infrastructure through predictive analytics. By implementing the proposed traffic congestion forecasting system in Rwanda, road usage can be optimized, leading to better decision-making and reduced congestion.
