## Predictive-Maintenance-of-Aircraft-Engine

Predictive Maintenance techniques are employed to assess the condition of equipment, enabling proactive maintenance or failure prevention before issues occur. This approach is highly beneficial as it significantly reduces equipment downtime costs.

The goal of this project is to implement and evaluate various Predictive Maintenance methods. These methods can be broadly categorized into two types:

Classification: Predicting whether a machine will fail within the next 'n' days.
Regression: Predicting the remaining useful life (RUL) of a machine.

## Dataset

Data sets consists of multiple multivariate time series. Each time series is from a different engine – i.e., the data can be considered to be from a fleet of engines of the same type. The engine data Set can be found [here](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps)

The engine is operating normally at the start of each time series, and develops a fault at some point during the series. In the training set, the fault grows in magnitude until system failure. In the test set, the time series ends some time prior to system failure.

The data are provided as a zip-compressed text file with 26 columns of numbers, separated by spaces. Each row is a snapshot of data taken during a single operational cycle, each column is a different variable. The columns correspond to:

## Objective

The objective of the competition is to predict the number of remaining operational cycles before failure in the test set, i.e., the number of operational cycles after the last cycle that the engine will continue to operate. Also provided a vector of true Remaining Useful Life (RUL) values for the test data.

## Analysis and Models

1. LSTM model for RUL Prediction

## References

https://www.mathworks.com/help/predmaint/ug/rul-estimation-using-rul-estimator-models.html
https://www.mathworks.com/help/predmaint/ug/feature-selection-for-remaining-useful-life-prediction.html
https://www.mathworks.com/help/predmaint/ug/models-for-predicting-remaining-useful-life.html
