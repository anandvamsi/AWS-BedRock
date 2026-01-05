## SupervisedLearning
- Used to predict a numeric value based on input data
- Examples:
  - Predicting House prices - based on features like size,location and number of bedrooms
  - Stock Price Prediction -  Predicting the future price of a stock based on historical data
  - Weather Forecasting - Predicting temperatures on historical weather data
  - Binary Classification : Classifcy animals as mammals,bride,reptiles

- ```K-nearest neigbour(KNN) model```

## Un-Supervised Learning 
- Great on un-labled data
- The goal is to discover inherent patterns, stratures,relationships within the input data
- The machines must uncover and create groups itself,but humans still put labels on the output groups.
- common techiniques, Clutering, Association rule learning,Anomaly detection

### Clustering Technique 
- Customer Segementation ::- few customers buy (pizza,chips,cookkies) others buy (soaps,shampoo), others buy  (fuits and veggies)
- outcome: The company can target each segement with tailored marketing strategies

### Association Technique
- if some customers buy bread, we can associate jam and butter near by which increases more chances of buying.
outcome: the supermarket can place associated products together to boost sales

### Anomaly Detection
- Fraud Dection
Senario:- Detect fradulent credit card transactions based on geography and amount
Goal: identify transactions that deviate from typical behaviour
outcome:- system flags those transactions
Technique :- Isolation forest

## Semi-Supervised Learning 
use small acount of labelled data and a large amount of un-lablled data to train the systems. after that the partially trained algo itself labels the 
unlabled data. this is called psedudo labeling.

## Self-Supervised Learning 
