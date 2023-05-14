<h1>
Traffic Prediction and Analysis 
</h1>
This project was developed to predict and analyze US traffic from 2015. The dataset is publicly available [here](https://www.kaggle.com/datasets/jboysen/us-traffic-2015). 

<h2>📍RoadMap </h2>
This project was developed in two phases 

Phase 1:
* Predict whether a junction lies on a Rural road or an Urban road (on a highway or not)
* Data was split three different ways
  * 80-20 train-test split
  * 70-15-15 train-validation-test split
  * K-fold Cross Validation
* Used four classical machine learning algorithms to make these predictions
  * K-Nearest Neighbors
  * Support Vector Machines
  * Naive Bayes
  * Decision Trees

Phase 2:
* Calcuate the hourly traffic count 
* Used an LSTM because it is Time-Series data
* Input features - latitude and longitude coordinates, direction of travel, date and day of travel

*Disclaimer* - This project was completed as part of the Automated Learning and Data Analysis (CSC-522) course in the fall semester of 2021. 

