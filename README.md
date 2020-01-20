# windPrediction
Wind power hour-ahead prediction
Wind energy output is predicted using climate data and yearly wind energy production data of 2015. Wind energy output is predicted and accuracy and RMSE is compared using different regression models including random forest regression, gradient boosted tree regression, adaboost regression and isolation forest regression. Achieved 96% accuracy with Recurrent Neural Networks for the prediction.

# System Overview
We used public data sets for  30-year climate data for wind speed, vapor pressure, precipitation, etc., from the Gridded Agro-Meteorological Data in Europe portal, and the EMHIRES dataset of European wind power generation dataset derived from meteorological sources. The frequency of the obtained datasets were different as they were from different sources, but both used the NUTS-2 geographical classification system which was used to link the data sets. The data was processed to obtain aggregate wind energy and climate data for individual days, using the time period of 2006-2015 for our analysis.

Wind power generation is considered as the ‘label’ and other data as ‘features’ for regression. Developed correlation matrix for the data and applied different regression models to predict wind energy output. Further to improve the accuracy of the predictions, Recurrent Neural Networks were used to predict wind energy output. Recurrent Neural Networks create connections to form  directed circle and is a type of Artificial Neural Network.
