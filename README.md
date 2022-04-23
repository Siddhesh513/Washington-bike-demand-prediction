 # Washington Bike Demand Prediction


## Introduction 

There are different bike companies such as [__Zagster__](https://en.wikipedia.org/wiki/Zagster) and [__Lime Bikes__](https://www.li.me/en-US/home) present all over the __US__ to ensure that people get rides when needed. As a result, there is an increase in demand for these bikes as some people move to these __cost-efficient__ and __environment-friendly__ transport options. As a result of this transition, there is variation in the demand for bikes in different regions. 


## Challenges

One of the challenges that these companies face is to know the __number of bikes__ that must be placed at different locations at different instances of time to ensure that they get __maximum profit__ and give the people their rides. Sometimes there is a possibility of people missing out these bikes due to their unavailability. On the contrary, there are also instances when the demand for these bikes are low while they are highly available in many locations without being used. Therefore, it becomes important to tackle these instances and understand the demand for the bikes for different days and scenarios. 

## Data Science and Machine Learning 

With the help of __machine learning__ and __deep learning__, this problem could be addressed and this would ensure that the demand for the bikes are known beforehand and thus, the companies could ensure that there are __adequate bikes__ present in different locations.

## Exploratory Data Analysis (EDA)

Therefore, with the help of __data visualization__ and __machine learning__, bike rental companies would be able to understand the total number of bikes that must be present at different instances of time and thus, they would be able to predict the demand for the bikes in the future. This would ensure that the companies save millions of dollars by giving the right service to different people who are in need. 

## Metrics

Since this is a __regression__ problem, we consider metrics that take into account __continuous output variables__ and give their estimates based on the difference between the __actual output__ and __predicted output__. Below are some metrics that are used for this prediction.

* [__Mean Squared Error__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html)
* [__Mean Absolute Error__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

## Machine Learning Models

We had used a number of machine learning models used in the prediction of the demand for __Washington Bikes__. Below are the models that were used for prediction.

* [__Deep Neural Networks__](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)
* [__K Nearest Neighbors__](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)
* [__Partial Least Squares (PLS) Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.cross_decomposition.PLSRegression.html)
* [__Decision Tree Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)
* [__Gradient Boosting Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)
* [__Logistic Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
* [__Long Short Term Memory (LSTM)__](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)

## Machine Learning Predictions and Analysis 

Before doing any __machine learning__ analysis it is very important to know th features that are present in the data. We would be performing various __data visualizations__ to understand some of the underlying features and once we get a good understanding of them, we are going to be using different machine learning models for predicting the demand for bikes based on these features. Once we get the machine learning predictions, we are going to be using different strategies that could aid us in the process of productionizing the models that could be used in different ways in companies. Therefore, this would save a lot of time and money for the bike rental companies where the demand for the bikes is predicted beforehand with the aid of machine learning and deep learning respectively. 

## Outcomes
* The models that were able to perform the best for predicting the bike demand are __Gradient Boosting Decision Regressor__ and __Deep Neural Networks__.
* __Exploratory Data Analysis (EDA)__ was performed to ensure that there is a good understanding of different features and their contribution to the output variable respectively. 
* The best machine learning models were able to generate a __mean absolute error (MAE)__ of about __23__ which is really good considering the scale of the problem at hand.

## Future Scope
* Additional features such as the __street connectivity score__ and __people's perceptions__ about the bicycling environment could be added to generate even more good predictions from the models. 
* The best machine learning models could be __deployed__ in real-time where the demand for bikes is highlighted so that admins can take action based on the __demand__. 
