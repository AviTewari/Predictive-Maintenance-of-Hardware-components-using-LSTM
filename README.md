# Predictive-Maintenance-of-Hardware-components-using-LSTM

Introduction:

In this project I have explored various machine learning techniques and algorithms that can be used to diagnose faults in complex systems. I used the [Tennessee Eastman dataset](https://www.kaggle.com/datasets/averkij/tennessee-eastman-process-simulation-dataset), which is a widely used benchmark dataset for fault diagnosis. The dataset contains process data for a simulated chemical process with various types of faults.


## Requirements
`numpy==1.21.4
pandas==1.3.4
matplotlib==3.4.3
seaborn==0.11.2
scikit-learn==1.1
xgboost==1.5.1
tensorflow==2.7.0
keras==2.7.0`

## Description

### [Part 1: Exploratory Data Analysis (EDA)]
I have explored the Tennessee Eastman dataset and performed some exploratory data analysis (EDA) to gain insights into the data. After that I also visualized the data, performed statistical analyses, and identified patterns and anomalies in the data.

### [Part 2: Training Various Machine Learning Algorithms with Hyperparameter Tuning]
In this part of the project I then trained various machine learning algorithms on the Tennessee Eastman dataset. In order for the ML models to better fit the data I used techniques like cross-validation and hyperparameter tuning to optimize the performance of these algorithms. At last I evaluated the accuracy of each algorithm and compared their performance.

### [Part 3: Long Short-Term Memory (LSTM) Networks for Fault Diagnosis]
For the last part of this project I then implemented an LSTM network on the Tennessee Eastman dataset and compared its performance with the performance of other ML algorithms.

### Metrics:
I have used accuracy as the primary metric for evaluating the performance of the different machine learning algorithms.


Average accuracy score obtained for each method, excluding fault No. 9 and 15 (**No feature were Dropped, all 52 sensor measurements were used**)
| Method                                    |Accuracy  |
|-----------------------------------------  |----------|
| XG Boost                                  |  0.887   |
| Neural Network                            |  0.943   |
| 1D CNN-Timeserise                         |  0.892   |
| LSTM-Timeserise                           |  0.924   |
| ANN+RandomForest                          |  0.936   |
