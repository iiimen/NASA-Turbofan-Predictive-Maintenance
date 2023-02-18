# NASA Turbofan Predictive Maintenance with Deep Learning
In the aerospace industry, ensuring the safety of passengers and crew is of utmost importance. One of the key challenges faced by aircraft manufacturers and operators is predicting when an engine is likely to fail. In this project, we aim to address this challenge by using deep learning techniques to predict the Remaining Useful Life (RUL) of turbofan engines.

The data used in this project is provided by NASA and represents the Turbofan Engine Degradation Simulation dataset. This dataset contains sensor readings from multiple sensors installed on a fleet of turbofan engines. Our task is to develop a model that can accurately predict the RUL of each engine, given its current state and the historical sensor readings.

# Table of Contents
1. Introduction
2. Dataset
3. Methods
4. Conclusion
# 1. Introduction
The goal of this project is to develop an effective model that can accurately predict when an aircraft engine is likely to fail. By doing so, aircraft manufacturers and operators can make informed decisions about maintenance schedules and avoid costly engine failures. In order to accomplish this, we will use the Turbofan Engine Degradation Simulation dataset provided by NASA and employ deep learning techniques to predict the RUL of each engine.

# 2. Dataset
The Turbofan Engine Degradation Simulation dataset contains sensor readings from 100 different turbofan engines, each of which have experienced different levels of degradation. The dataset contains four different subsets, each corresponding to a different operational setting. For each subset, the data contains the following information:

time (in cycles)
21 sensor readings
Remaining Useful Life (RUL)
The RUL is given in units of cycles, and represents the number of remaining operational cycles until the engine is likely to fail.

# 3. Methods
We use deep learning techniques to develop a model that can accurately predict the RUL of each engine. Specifically, we use a Long Short-Term Memory (LSTM) network, which is a type of recurrent neural network that can effectively model temporal data. We preprocess the data by normalizing the sensor readings, and then train the LSTM network on the normalized data. Once the model is trained, we use it to make predictions on the test set, and evaluate its performance using metrics such as root mean squared error (RMSE) and mean absolute error (MAE).

# 4. Conclusion
In this project, we demonstrate the effectiveness of deep learning techniques for predicting the RUL of turbofan engines. Our LSTM-based model achieves high accuracy on the test set, and outperforms traditional machine learning models. This work has important implications for the aerospace industry, as it can help manufacturers and operators make informed decisions about maintenance schedules and avoid costly engine failures.