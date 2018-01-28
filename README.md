# AnomalyDetection

## Project: Anomaly detection in wide area network mesh using two Machine Learning anomaly detection algorithms

### Install
This project requires Python 2.7 and the following Python libraries installed:

* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [scikit-learn](http://scikit-learn.org/stable/)
* [Keras](https://keras.io/)

You will also need to have software installed to run and execute a [Jupyter Notebook](https://jupyter.org/)

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

### Code
The code for each experiment can be found in the AnomalyDetection file along with this README. You will be required to use the simulated_data.py Python file for all code using Boosted Decision Trees (BDT) involving simulated data.

The following is a summary of each file in the order of its use in the paper.

*A. Boosted Decision Trees*

*A.1. Decision Stumps vs. Decision Trees*  
TestingBDTonSimulatedDataSTUMPS.ipynb  
Tested the effectiveness of boosted decision trees utilizing trees of depth one (decision stumps) on simulated data.  

TestingBDTonSimulatedDataTREES_6.ipynb  
Tested the effectiveness of boosted decision trees utilizing trees of depth 6 on simulated data.  

*A.2. Anomaly Duration vs. Degree of Anomalous Behavior*  
BDTonSimulatedDataDegreeDurationTest.ipynb  
The code in this file fluctuates the degree to which an anomaly differed from normal data, the duration of anomalous behavior, and the number of timeseries affected for a simulated data set.

*A.3 Application on real data*  
PacketLossWithAnalysis&Delay-30days.ipynb

*B. Simple feed forward neural network*

*B1. Application on simulated data*

*B2. Impact of duration, magnitude of anomaly, and number of affected timeseries*

*B3. Performance on actual data*

The code is provided in the  
You will also have be required to use the included 

BDTonSimulatedDataDegreeDurationTest.ipynb

### Run
In a terminal or command window, navigate to the top-level project directory boston_housing/ (that contains this README) and run one of the following commands:

ipython notebook boston_housing.ipynb  
or

jupyter notebook boston_housing.ipynb  
This will open the Jupyter Notebook software and project file in your browser.

### Data
The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the UCI Machine Learning Repository.

Features

RM: average number of rooms per dwelling
LSTAT: percentage of population considered lower status
PTRATIO: pupil-teacher ratio by town
Target Variable 4. MEDV: median value of owner-occupied homes
